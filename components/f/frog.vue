<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="av6xjhb-m"/><path class="gfr8mbbbj"/><circle class="raqyatbvb"/><circle class="lt1xlfogd"/><circle class="n_93m5ucl"/><circle class="vk1i4c9xn"/><circle class="jix_m4bsz"/><circle class="qx-r7doew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:frog" /></template>
<style>
.av6xjhb-m {
  fill: var(--svg-color--c6e5b3, #c6e5b3);
  d: path("M36 22c0 7.456-8.059 12-18 12S0 29.456 0 22S8.059 7 18 7s18 7.544 18 15");
}

.gfr8mbbbj {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M31.755 12.676A5.99 5.99 0 0 0 34 8a6 6 0 0 0-11.851-1.315A11.8 11.8 0 0 0 18 5.927c-1.465 0-2.861.275-4.149.758A6 6 0 0 0 2 8c0 1.891.877 3.576 2.245 4.676C1.6 15.356 0 18.685 0 22c0 7.456 8.059 1 18 1s18 6.456 18-1c0-3.315-1.6-6.644-4.245-9.324");
}

.jix_m4bsz {
  cx: 14px;
  cy: 20px;
  r: 1px;
  fill: var(--svg-color--5c913b, #5c913b);
}

.lt1xlfogd {
  cx: 7.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.n_93m5ucl {
  cx: 28.5px;
  cy: 7.5px;
  r: 3.5px;
  fill: var(--svg-color--fff, #fff);
}

.qx-r7doew {
  cx: 22px;
  cy: 20px;
  r: 1px;
  fill: var(--svg-color--5c913b, #5c913b);
}

.raqyatbvb {
  cx: 7.5px;
  cy: 7.5px;
  r: 3.5px;
  fill: var(--svg-color--fff, #fff);
}

.vk1i4c9xn {
  cx: 28.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

</style>
