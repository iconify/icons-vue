<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-d5rybqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bancolombia" /></template>
<style>
.u-d5rybqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.262 12.81c8.345-3.3 12.937-4.205 21.54-5.305M5.5 30.469c8.603-5.952 22.51-9.445 37-10.803M18.825 40.495c7.31-4.01 15.783-5.887 23.675-7.18");
}

</style>
