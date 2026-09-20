<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pgujc4bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:key-command-20-regular" /></template>
<style>
.pgujc4bgf {
  fill: currentColor;
  d: path("M5.5 4A1.5 1.5 0 0 1 7 5.5V7H5.5a1.5 1.5 0 1 1 0-3M8 7V5.5A2.5 2.5 0 1 0 5.5 8H7v4H5.5A2.5 2.5 0 1 0 8 14.5V13h4v1.5a2.5 2.5 0 1 0 2.5-2.5H13V8h1.5A2.5 2.5 0 1 0 12 5.5V7zm0 1h4v4H8zm5-1V5.5A1.5 1.5 0 1 1 14.5 7zm0 6h1.5a1.5 1.5 0 1 1-1.5 1.5zm-6 0v1.5A1.5 1.5 0 1 1 5.5 13z");
}

</style>
