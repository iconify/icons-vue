<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w9o-syxvx"/><path class="g1u28rbcv"/><circle class="lag-e5ujd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-laos" /></template>
<style>
.g1u28rbcv {
  fill: var(--svg-color--002868, #002868);
  d: path("M0 24h36V12H0v12zm18-11a5 5 0 1 1-.001 10.001A5 5 0 0 1 18 13z");
}

.lag-e5ujd {
  fill: var(--svg-color--fff, #FFF);
  cx: 18px;
  cy: 18px;
  r: 5px;
}

.w9o-syxvx {
  fill: var(--svg-color--ce1126, #CE1126);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-3H0v3zM32 5H4a4 4 0 0 0-4 4v3h36V9a4 4 0 0 0-4-4z");
}

</style>
