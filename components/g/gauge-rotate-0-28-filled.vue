<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jrq7bfjbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-0-28-filled" /></template>
<style>
.jrq7bfjbh {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12s-5.373 12-12 12S2 20.627 2 14S7.373 2 14 2m0 2C8.477 4 4 8.477 4 14s4.477 10 10 10s10-4.477 10-10S19.523 4 14 4m-.976 2.295c.215-1.026 1.637-1.058 1.927-.096l.025.096c.468 2.273.955 4.544 1.345 6.832c.1.584.179 1.11.179 1.374a2.5 2.5 0 0 1-5 0c0-.264.08-.79.179-1.374c.316-1.856.985-5.107 1.345-6.832");
}

</style>
