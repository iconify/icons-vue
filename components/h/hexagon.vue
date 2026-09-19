<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b58b4yb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hexagon" /></template>
<style>
.b58b4yb_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.29 32.25v-16.5a4 4 0 0 0-2-3.464L26 4.036a4 4 0 0 0-4 0l-14.29 8.25a4 4 0 0 0-2 3.464v16.5a4 4 0 0 0 2 3.464L22 43.964a4 4 0 0 0 4 0l14.29-8.25a4 4 0 0 0 2-3.464");
}

</style>
