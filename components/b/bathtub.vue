<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ep2gmkbma"/><path class="fly_jhbug"/><path class="vzhwoqbcv"/><path class="b-leqvbse"/><path class="ch_uqum4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:bathtub" /></template>
<style>
.b-leqvbse {
  fill: var(--svg-color--ddd3ca, #ddd3ca);
  d: path("M59.4 41.4H5.1c-4.1 0-4.1-4.8 0-4.8h54.3c3.5 0 3.5 4.8 0 4.8");
}

.ch_uqum4m {
  fill: var(--svg-color--a6aeb0, #a6aeb0);
  d: path("M33.8 14.8C28.8 9.6 32.1 2 32.1 2s-10.5 10.1-3.9 17c7.7 8 3.9 13 3.9 13s9.6-9 1.7-17.2m-15 4.7c-3.8-3.8-1.3-9.3-1.3-9.3s-7.9 7.3-2.9 12.4c5.8 5.8 2.9 9.5 2.9 9.5s7.2-6.6 1.3-12.6m29.9 0c-3.8-3.8-1.3-9.3-1.3-9.3s-7.9 7.3-2.9 12.4c5.8 5.8 2.9 9.5 2.9 9.5s7.2-6.6 1.3-12.6");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.ep2gmkbma {
  fill: var(--svg-color--c6bbb3, #c6bbb3);
  d: path("M13.1 57.5c0 2.5-.9 4.5-2.9 4.5s-3.4-2.2-2.5-4.5C9 53.9 12.2 52 14.2 52c1.9 0-1.1 3-1.1 5.5m37.8 0c0 2.5.9 4.5 2.9 4.5s3.4-2.2 2.5-4.5C55 53.9 51.8 52 49.8 52c-1.9 0 1.1 3 1.1 5.5");
}

.fly_jhbug {
  fill: var(--svg-color--e2d8c7, #e2d8c7);
  d: path("M59.1 40.1c0 18.4-12 18.8-26.9 18.8S5.4 58.5 5.4 40.1z");
}

.vzhwoqbcv {
  fill: var(--svg-color--c6bbb3, #c6bbb3);
  d: path("M5.4 41h53.7v1.2H5.4z");
}

</style>
