<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hj8az6bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hj8az6bzf {
  d: path("M18 7.207c0-1.114-1.346-1.671-2.134-.884l-9.543 9.543c-.787.788-.23 2.134.884 2.134h9.043A1.75 1.75 0 0 0 18 16.25V7.207z");
  fill: currentColor;
}

</style>
