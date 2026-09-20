<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9t4-d51j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calculator-arrow-clockwise-24-filled" /></template>
<style>
.j9t4-d51j {
  fill: currentColor;
  d: path("M4 5.25A3.25 3.25 0 0 1 7.25 2h9.5A3.25 3.25 0 0 1 20 5.25v5.025a2 2 0 0 0-.232.294A7 7 0 0 0 12.101 22H7.25A3.25 3.25 0 0 1 4 18.751zM9 5a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2zm.5 8.25a1.25 1.25 0 1 0-2.5 0a1.25 1.25 0 0 0 2.5 0M8.25 18.5a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m13-3.5a.75.75 0 0 0 .75-.75V11.5a.75.75 0 0 0-1.5 0v.626A6 6 0 1 0 23 17a.75.75 0 0 0-1.5 0a4.5 4.5 0 1 1-1.688-3.513l.008.006l.01.007H18.5a.75.75 0 0 0 0 1.5z");
}

</style>
