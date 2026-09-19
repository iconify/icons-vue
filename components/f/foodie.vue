<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yo43fuw7d"/><path class="irmkv5bux"/><path class="eoec02mau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foodie" /></template>
<style>
.eoec02mau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 23.07c0 .97-.79 1.76-1.76 1.76s-1.76-.79-1.76-1.76s.79-1.76 1.76-1.76h1.65");
}

.irmkv5bux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 29.46c-2.36 4.8-7.29 8.11-13 8.11c-7.41 0-13.52-5.56-14.39-12.74c-.07-.57-.11-1.16-.11-1.76s.05-1.18.12-1.76M11 16.68c2.36-4.8 7.29-8.11 13-8.11c7.41 0 13.52 5.56 14.39 12.74c.07.57.11 1.16.11 1.76m-25.48-1.76h-3.4m3.4 3.52H9.61");
}

.yo43fuw7d {
  cx: 24px;
  cy: 23.069px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
