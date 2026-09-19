<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5jei3vpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:league" /></template>
<style>
.f5jei3vpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.844 4.5h11.103v31.443h15.209L35.103 43.5H11.871l4.198-7.557V12.337zm3.072 4.608v30.71");
}

</style>
