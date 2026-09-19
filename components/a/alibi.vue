<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udnsiiboq"/><path class="m0ma9ryke"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alibi" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m0ma9ryke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.98 24.639c1.879 0 3.399 1.475 3.399 3.297s-1.52 3.298-3.398 3.298s-3.398-1.476-3.398-3.298s1.52-3.297 3.398-3.297m-16.085 0c1.878 0 3.398 1.475 3.398 3.297s-1.52 3.298-3.398 3.298s-3.398-1.476-3.398-3.298s1.52-3.297 3.398-3.297");
}

.udnsiiboq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.98 20.123c4.405 0 7.982 3.499 7.982 7.813s-3.577 7.813-7.981 7.813S24 32.251 24 27.936s3.577-7.813 7.98-7.813m-15.96-.033c4.403 0 7.98 3.498 7.98 7.813s-3.577 7.813-7.98 7.813c-4.416 0-7.982-3.499-7.982-7.813s3.566-7.813 7.981-7.813");
}

</style>
