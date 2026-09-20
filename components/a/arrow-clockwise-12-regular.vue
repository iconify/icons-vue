<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xee4e3zgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-clockwise-12-regular" /></template>
<style>
.xee4e3zgg {
  fill: currentColor;
  d: path("M8.966 6.453c.038-.248.238-.453.489-.453c.3 0 .549.246.508.544A4 4 0 1 1 9 3.354V2.5a.5.5 0 0 1 1 0v2a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h.736a3 3 0 1 0 .73 2.453");
}

</style>
