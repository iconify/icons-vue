<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5mpx3bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:book-walker" /></template>
<style>
.z5mpx3bak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.735 24.974v-12.5m4.221 12.5v-12.5m4.22 12.5v-12.5m4.221 12.5v-12.5m4.221 12.5v-12.5m4.22 12.5v-12.5m4.221 12.5v-12.5m4.22 12.5v-12.5m4.221 12.5v-12.5M4.5 24.76l3.235-12.073M24 27.591l-.985 3.031h-3.187l2.579 1.873l-.985 3.031L24 33.653l2.578 1.873l-.984-3.03l2.578-1.874h-3.187z");
}

</style>
