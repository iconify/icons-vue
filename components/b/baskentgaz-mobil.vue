<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtojs6bym"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baskentgaz-mobil" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.xtojs6bym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.329 25.787h-4.953m-1.238 3.715l3.714-11.006l3.715 11.006m-9.638-7.29a3.7 3.7 0 0 0-3.683-3.715h-.032A3.7 3.7 0 0 0 10.5 22.18h0v3.746c0 2.064 1.65 3.577 3.714 3.577h0c2.064 0 3.715-1.651 3.715-3.577h-3.714m16.132-7.43H37.5l-7.153 11.006H37.5");
}

</style>
