<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m6joozgyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-out-line-horizontal-bold" /></template>
<style>
.m6joozgyz {
  fill: currentColor;
  d: path("M140 40v176a12 12 0 0 1-24 0V40a12 12 0 0 1 24 0m-52 76H45l11.52-11.51a12 12 0 0 0-17-17l-32 32a12 12 0 0 0 0 17l32 32a12 12 0 0 0 17-17L45 140h43a12 12 0 0 0 0-24m160.49 3.51l-32-32a12 12 0 0 0-17 17L211 116h-43a12 12 0 0 0 0 24h43l-11.52 11.51a12 12 0 0 0 17 17l32-32a12 12 0 0 0 .01-17");
}

</style>
