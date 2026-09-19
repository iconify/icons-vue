<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3f5-bxfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daiichi" /></template>
<style>
.m3f5-bxfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 5.5c0 20.435-16.565 37-37 37C15.717 42.5 24 34.217 24 24S15.717 5.5 5.5 5.5v37h37z");
}

</style>
