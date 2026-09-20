<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jepqryb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-info-24-filled" /></template>
<style>
.jepqryb3r {
  fill: currentColor;
  d: path("M21 12.022a6.5 6.5 0 0 0-2.05-.86A7 7 0 0 0 8.392 6H9a1 1 0 0 1 0 2H6a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0v.516A9 9 0 0 1 21 12zM12 21h.022a6.5 6.5 0 0 1-.86-2.05a7 7 0 0 1-6.108-7.826a1 1 0 1 0-1.984-.248Q3 11.43 3 12a9 9 0 0 0 9 9m0-3.5a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0m5.5 3.5a.5.5 0 0 0 .5-.5v-4a.5.5 0 0 0-1 0v4a.5.5 0 0 0 .5.5m0-7.125a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25");
}

</style>
