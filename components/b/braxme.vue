<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0g2rbcfc"/><path class="xnb24-btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:braxme" /></template>
<style>
.n0g2rbcfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.616 40.508A19.5 19.5 0 1 1 38.92 36.56m0 0c.92 2.404 1.026 5.284-.234 6.705c-1.856 1.542-6.499-5.093-11.107-3.653c-5.238 2.87-11.135 2.76-13.962.896");
}

.xnb24-btw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.172 23.967a4.91 4.91 0 0 1 0 9.821h-8.103V14.146h8.103a4.91 4.91 0 0 1 0 9.821m0 0h-8.103");
}

</style>
