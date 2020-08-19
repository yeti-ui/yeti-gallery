<template>
  <div class="container">
    <yeti-gallery />
  </div>
</template>
<script>
import { YetiGallery } from '../src/'

export default {
  components: {
    YetiGallery,
  },
  name: '',
}
</script>

<style>
  .container {
    width: 1200px;
    margin: 0 auto;
  }
</style>
