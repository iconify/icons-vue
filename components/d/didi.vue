<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-8h2339h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:didi" /></template>
<style>
.z-8h2339h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.71 10.355H4.5v7.79a19.5 19.5 0 0 0 19.5 19.5h0a19.5 19.5 0 0 0 19.5-19.5");
}

</style>
