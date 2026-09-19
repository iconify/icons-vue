<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hnzwhpwsy"/><path class="qctd-ubtm"/><path class="y_8s3xb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:authenticator-alt-1" /></template>
<style>
.hnzwhpwsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 27.95l19.5-10.43L24 8.13L4.5 17.52z");
}

.qctd-ubtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.37 20.66L4.5 23.48L24 33.91l19.5-10.43l-5.87-2.82");
}

.y_8s3xb8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.37 26.62L4.5 29.44L24 39.87l19.5-10.43l-5.87-2.82");
}

</style>
