<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bvteyex9r"/><path class="khrcunw1e"/><path class="pvu5whbqv"/><path class="stv5qh8-u"/><path class="tarx0u94d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-jordan" /></template>
<style>
.bvteyex9r {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4z");
}

.khrcunw1e {
  fill: var(--svg-color--007a3d, #007A3D);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0V27z");
}

.pvu5whbqv {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 13.5h36v9H0z");
}

.stv5qh8-u {
  fill: var(--svg-color--ce1126, #CE1126);
  d: path("M1.351 6.004H1.35A3.991 3.991 0 0 0 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18L1.351 6.004z");
}

.tarx0u94d {
  fill: var(--svg-color--fff, #FFF);
  d: path("M6.627 19.338l1.056.976l-.105-1.435L9 18.662l-1.187-.812l.717-1.247l-1.375.421l-.528-1.338l-.528 1.338l-1.375-.421l.716 1.247l-1.186.812l1.421.217l-.104 1.435z");
}

</style>
