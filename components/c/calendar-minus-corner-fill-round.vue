<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrgryxb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-corner-fill-round" /></template>
<style>
.rrgryxb4s {
  fill: currentColor;
  d: path("M9 4h6V3a1 1 0 0 1 2 0v1.099a5.01 5.01 0 0 1 3.607 2.954c.261.616.395 1.278.393 1.947a1 1 0 0 1-1 1H5v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H8a5 5 0 0 1-5-5V9a5.01 5.01 0 0 1 4-4.901V3a1 1 0 0 1 2 0Zm12 11a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
