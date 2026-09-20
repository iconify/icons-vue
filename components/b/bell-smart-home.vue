<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7s2f7ifg"/><path class="rd2lvx1xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bell-smart-home" /></template>
<style>
.f7s2f7ifg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.671 42.35a2.823 2.823 0 0 0 2.829-2.817V21.216c0-1.139-.89-2.207-1.78-2.915L26.859 7.291C25.177 5.953 25.099 5.65 24 5.65s-1.177.303-2.859 1.64L7.281 18.3c-.892.708-1.781 1.776-1.781 2.915V39.52a2.823 2.823 0 0 0 2.816 2.83z");
}

.rd2lvx1xl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.475 23.965a1.89 1.89 0 1 1-1.892-1.892h.001a1.89 1.89 0 0 1 1.89 1.891zm-1.891 2.067v6.697m10.034-1.892a1.89 1.89 0 0 0-3.782 0a1.89 1.89 0 0 0 1.889 1.892h.001a1.89 1.89 0 0 0 1.892-1.889zm-1.891-2.067v-6.697");
}

</style>
