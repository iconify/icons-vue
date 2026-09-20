<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8z5vxa1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aldi" /></template>
<style>
.b8z5vxa1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.633 40.377zc1.19 0 2.255-.738 2.673-1.853L30.197 9.475a2.855 2.855 0 0 1 2.673-1.852M10.077 40.377zc1.19 0 2.255-.738 2.673-1.853L23.641 9.475a2.855 2.855 0 0 1 2.673-1.852M5.5 40.377L17.086 9.475a2.855 2.855 0 0 1 2.673-1.852m16.637 9.345a1.715 1.715 0 0 0-1.621-1.157h-3.443M28.262 24h9.547c.732 0 1.383.465 1.62 1.157m-14.237 7.032h15.687c.732 0 1.383.464 1.621 1.156");
}

</style>
