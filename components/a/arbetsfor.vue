<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="unug2mbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arbetsfor" /></template>
<style>
.unug2mbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.71 3.71C40.77 4.35 50.61 28 40.6 44.26M17.4 16.51A13.88 13.88 0 1 1 7.59 40.2a13.89 13.89 0 0 1 9.81-23.69");
}

</style>
