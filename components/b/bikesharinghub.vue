<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhug8sdiu"/><path class="ryx7xtb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bikesharinghub" /></template>
<style>
.ryx7xtb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.186 26.097a7.2 7.2 0 0 1 .743-1.759m2.921-2.777a7.286 7.286 0 1 1-3.607 8.587m-13.658-8.565a7.287 7.287 0 1 1-3.8-1.068");
}

.xhug8sdiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.327 16.096h3.142l-3.197 11.93h10.943l-8.459-8.595m-2.484 8.594L14.58 17.373l-2.794 10.429l4.05-15.113l4.052 1.086");
}

</style>
