<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="movv8kbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cube-12-filled" /></template>
<style>
.movv8kbbk {
  fill: currentColor;
  d: path("M5.449 1.105a1.5 1.5 0 0 1 1.102 0l3.5 1.384A1.5 1.5 0 0 1 11 3.884v4.23a1.5 1.5 0 0 1-.949 1.395l-3.5 1.384a1.5 1.5 0 0 1-1.102 0l-3.5-1.384A1.5 1.5 0 0 1 1 8.114v-4.23a1.5 1.5 0 0 1 .949-1.395zm-1.763 2.93a.5.5 0 1 0-.372.93l2.186.874V8a.5.5 0 0 0 1 0V5.839l2.186-.875a.5.5 0 1 0-.372-.928L6 4.96z");
}

</style>
