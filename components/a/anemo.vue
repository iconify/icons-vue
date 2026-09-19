<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ukh69-4iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anemo" /></template>
<style>
.ukh69-4iu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.28 36.055a4.5 4.5 0 1 0 4.217-6.056H7.5m10.78-18.054a4.5 4.5 0 1 1 4.218 6.056H4.5m30.277-.057A4.5 4.5 0 1 1 38.996 24H5.999");
}

</style>
