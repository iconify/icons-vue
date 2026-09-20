<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdasa_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-chevron-down-16-filled" /></template>
<style>
.pdasa_bkt {
  fill: currentColor;
  d: path("M4.535 1.48c.968-.296 2 .212 2.355 1.16l.458 1.223a2 2 0 0 1-.52 2.176l-1.074.983q.03.112.078.257c.106.325.273.75.513 1.165a6.3 6.3 0 0 0 .935 1.223l1.389-.438a2 2 0 0 1 2.144.637l.841 1.022a1.9 1.9 0 0 1-.17 2.595c-1.32 1.23-3.37 1.556-4.804.25A15.9 15.9 0 0 1 3.652 9.97a15.3 15.3 0 0 1-1.746-4.475C1.5 3.6 2.82 2.004 4.536 1.48m9.612 1.666a.5.5 0 0 1 .707.707l-2.5 2.5a.5.5 0 0 1-.707 0l-2.5-2.5a.5.5 0 1 1 .707-.707L12 5.293z");
}

</style>
