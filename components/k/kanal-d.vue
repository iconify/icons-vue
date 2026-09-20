<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="k3cnofwci"/><path class="syswpqgen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kanal-d" /></template>
<style>
.k3cnofwci {
  cx: 13.649px;
  cy: 24.079px;
  r: 5.942px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.syswpqgen {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.943 42.5c19.25-2.524 25.728-14.197 22.598-22.864c-.536-1.484-5.67-13.98-26.578-14.136l2.728 9.333a9.374 9.374 0 1 1-4.534 18.171z");
}

</style>
