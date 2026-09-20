<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g-ew1jtjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-down-left-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g-ew1jtjz {
  d: path("M18 7.208c0-1.114-1.346-1.672-2.134-.884l-9.543 9.543c-.787.787-.23 2.133.884 2.133h9.043A1.75 1.75 0 0 0 18 16.25V7.208z");
  fill: currentColor;
}

</style>
