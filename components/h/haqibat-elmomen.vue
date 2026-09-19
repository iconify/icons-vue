<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1td2dxwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:haqibat-elmomen" /></template>
<style>
.j1td2dxwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.915 22.06C10.416 12.614 24.32 5.5 24.32 5.5s15.334 9.487 15.334 16.56v11.298H13.607a4.571 4.571 0 1 0 0 9.142h26.478");
}

</style>
