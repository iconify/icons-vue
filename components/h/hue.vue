<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jr5unsq4y"/><path class="xg6_an_tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hue" /></template>
<style>
.jr5unsq4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.25 37.45v-6.17s-8-7.44-8-15.86S18.11 4.5 24 4.5S36.81 7 36.81 15.42s-8.06 15.86-8.06 15.86v6.17m-9.5 0h9.5l-9.5 6.05h9.5");
}

.xg6_an_tb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.03 18.61l-6.71-6.71l1.36 12.06l-6.71-6.72");
}

</style>
