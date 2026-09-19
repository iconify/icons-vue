<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a34zs7joq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bambu-handy" /></template>
<style>
.a34zs7joq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.1 19.01V43.5h14V24.6zm0-14.51v12.141l14 5.59V4.5zM8.9 28.99V4.5h14v18.9zm0 14.51V31.359l14-5.59V43.5z");
}

</style>
