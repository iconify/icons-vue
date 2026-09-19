<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="lqzz8kb3a"/><path class="ou-_r1lyf"/><path class="ryvfjptrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:d-menu" /></template>
<style>
.lqzz8kb3a {
  width: 31px;
  height: 31px;
  x: 8px;
  y: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ou-_r1lyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.31 9.25h.19c2.216 0 4 1.784 4 4v23c0 2.216-1.784 4-4 4h-23a3.99 3.99 0 0 1-3.311-1.75m-3.736-2.137A3.99 3.99 0 0 1 5.5 32.5v-23c0-2.216 1.784-4 4-4h23a3.99 3.99 0 0 1 3.545 2.14");
}

.ryvfjptrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.125 40.199A3.99 3.99 0 0 1 35.5 42.5h-23c-2.216 0-4-1.784-4-4v-2.059m20.059-11.777c0-2.626-2.265-4.754-5.06-4.754s-5.059 2.128-5.059 4.754v3.09c0 2.625 2.265 4.753 5.06 4.753s5.059-2.128 5.059-4.754m0 4.754V13.493");
}

</style>
