<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":249};
const content = `<path class="fq_y67bif"/><path class="omd3_82zy"/><path class="y6xg9yb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:cloudant" /></template>
<style>
.fq_y67bif {
  d: path("M256 124.832C256 193.408 198.692 249 128 249C57.308 249 0 193.408 0 124.832C0 56.256 57.308.664 128 .664c70.692 0 128 55.592 128 124.168");
  fill: var(--svg-color--72c7e6, #72C7E6);
}

.omd3_82zy {
  d: path("M45.605 112.186S40.43 86.414 92.647 80.569c2.14-34.427 123.497-35.193 93.22 8.623c22.42 7.76 18.78 23.377 18.78 23.377s.894 8.815-6.898 16.863c-7.793 8.047-16.115 13.05-42.156 13.029c-10.447-.008-25.293.51-42.667-7.41c-23.505 4.856-48.992.015-56.718-5.875c-12.902-9.836-10.603-16.99-10.603-16.99");
  fill: var(--svg-color--fff, #FFF);
}

.y6xg9yb0t {
  d: path("M45.605 112.186v39.856s2.683 36.024 68.216 21.845c26.059 19.16 86.227 6.898 90.826-15.713v-45.605c.383 11.114-51.353 41.389-90.443 15.33c-58.252 13.03-68.6-15.713-68.6-15.713");
  fill: var(--svg-color--002c77, #002C77);
}

</style>
