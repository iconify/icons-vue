<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ncsai8bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:i-am-sober" /></template>
<style>
.ncsai8bxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.36 13.347l5.166 5.166L24 27.038l-8.525-8.525l5.165-5.166a4.75 4.75 0 0 1 6.72 0m4.256 21.305l-5.166-5.165l8.525-8.525l8.526 8.525l-5.166 5.165a4.75 4.75 0 0 1-6.72 0m-21.95 0L4.5 29.487l8.525-8.526l8.525 8.526l-5.165 5.165a4.75 4.75 0 0 1-6.72 0");
}

</style>
