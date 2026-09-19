<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7czjac0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abanca" /></template>
<style>
.b7czjac0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.076 28.789h12.937M43.5 38.74h-2.138a1.46 1.46 0 0 1-1.384-1L30.545 9.26L20.78 38.74m1.625-29.479L12.64 38.739m1.625-29.478L4.5 38.739");
}

</style>
