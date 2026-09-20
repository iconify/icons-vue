<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nrffvyb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-in-line-horizontal-bold" /></template>
<style>
.nrffvyb4t {
  fill: currentColor;
  d: path("M140 40v176a12 12 0 0 1-24 0V40a12 12 0 0 1 24 0M64.49 87.51a12 12 0 0 0-17 17L59 116H16a12 12 0 0 0 0 24h43l-11.49 11.51a12 12 0 0 0 17 17l32-32a12 12 0 0 0 0-17ZM240 116h-43l11.52-11.51a12 12 0 0 0-17-17l-32 32a12 12 0 0 0 0 17l32 32a12 12 0 0 0 17-17L197 140h43a12 12 0 0 0 0-24");
}

</style>
