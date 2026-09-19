<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ao0ngkboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:just-craigslist" /></template>
<style>
.ao0ngkboj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.145 2.5 2.5 12.145 2.5 24S12.145 45.5 24 45.5S45.5 35.853 45.5 24S35.855 2.5 24 2.5m0 0v43M8.819 39.209L24 24m15.181 15.209L24 24");
}

</style>
