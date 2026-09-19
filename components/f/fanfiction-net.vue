<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="od4q2ccli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fanfiction-net" /></template>
<style>
.od4q2ccli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h27a10 10 0 0 1 10 10v27h0h-27a10 10 0 0 1-10-10zm0 18.5h37");
}

</style>
