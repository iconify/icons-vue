<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uwhalhbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:frame-16-regular" /></template>
<style>
.uwhalhbyb {
  fill: currentColor;
  d: path("M4 1.5a.5.5 0 0 0-1 0V3H1.5a.5.5 0 0 0 0 1H3v8H1.5a.5.5 0 0 0 0 1H3v1.5a.5.5 0 0 0 1 0V13h8v1.5a.5.5 0 0 0 1 0V13h1.5a.5.5 0 0 0 0-1H13V4h1.5a.5.5 0 0 0 0-1H13V1.5a.5.5 0 0 0-1 0V3H4zM12 12H4V4h8z");
}

</style>
