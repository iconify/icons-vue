<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvgwqk01h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-circle-32-regular" /></template>
<style>
.qvgwqk01h {
  fill: currentColor;
  d: path("M21.707 10.293a1 1 0 0 1 0 1.414L17.414 16l4.293 4.293a1 1 0 0 1-1.414 1.414L16 17.414l-4.293 4.293a1 1 0 0 1-1.414-1.414L14.586 16l-4.293-4.293a1 1 0 1 1 1.414-1.414L16 14.586l4.293-4.293a1 1 0 0 1 1.414 0M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2M4 16C4 9.373 9.373 4 16 4s12 5.373 12 12s-5.373 12-12 12S4 22.627 4 16");
}

</style>
