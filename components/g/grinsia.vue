<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpgu5pymp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grinsia" /></template>
<style>
.xpgu5pymp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203L25.481 27.576L24 45.5l-1.481-17.925L8.797 39.203l11.627-13.722L2.5 24l17.925-1.481L8.797 8.797l13.722 11.627L24 2.5l1.481 17.925L39.203 8.797L27.576 22.519L45.5 24l-17.925 1.481zM27.537 24a3.537 3.537 0 0 1-7.074.002V24a3.537 3.537 0 0 1 7.074 0");
}

</style>
