<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gbgc7yb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:doctor-12-regular" /></template>
<style>
.gbgc7yb5k {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v1h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H8v1a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V8H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h1zm3 0H5v1.5a.5.5 0 0 1-.5.5H3v2h1.5a.5.5 0 0 1 .5.5V9h2V7.5a.5.5 0 0 1 .5-.5H9V5H7.5a.5.5 0 0 1-.5-.5z");
}

</style>
