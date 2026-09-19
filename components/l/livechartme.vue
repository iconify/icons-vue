<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vq55xdbnp"/><path class="r5o0crb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:livechartme" /></template>
<style>
.r5o0crb4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.61 27.61l1.507 1.507m0 0v3.771l9.612 9.612l3.771-3.771l-9.612-9.612zm-23.05-6.864h5.015l3.37 5.357l7.741-18.706l4.235 8.061h4.895");
}

.vq55xdbnp {
  cx: 18.451px;
  cy: 18.451px;
  r: 12.951px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
