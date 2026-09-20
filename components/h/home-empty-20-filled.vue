<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dsfi-6pgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-empty-20-filled" /></template>
<style>
.dsfi-6pgv {
  fill: currentColor;
  d: path("M8.997 2.385a1.5 1.5 0 0 1 2.006 0l5.5 4.95A1.5 1.5 0 0 1 17 8.45v7.055a1.5 1.5 0 0 1-1.5 1.5h-11a1.5 1.5 0 0 1-1.5-1.5V8.45c0-.425.18-.83.497-1.115z");
}

</style>
