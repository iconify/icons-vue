<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_qd073dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-print-24-regular" /></template>
<style>
.w_qd073dq {
  fill: currentColor;
  d: path("M18.5 20a.5.5 0 0 1-.5.5h-5.268a2 2 0 0 1-1.732 1h-.011a2.7 2.7 0 0 1-.093.5H18a2 2 0 0 0 2-2V9.828a2 2 0 0 0-.586-1.414l-5.829-5.828A2.05 2.05 0 0 0 12.172 2H6a2 2 0 0 0-2 2v7.104Q4.358 11 4.75 11h.75V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5zm-5-15.379L17.378 8.5H14a.5.5 0 0 1-.5-.5zM3 13.75c0-.966.784-1.75 1.75-1.75h3.5c.966 0 1.75.784 1.75 1.75v.75h.5A1.5 1.5 0 0 1 12 16v3.5a1 1 0 0 1-1 1h-1v.75A1.75 1.75 0 0 1 8.25 23h-3.5A1.75 1.75 0 0 1 3 21.25v-.75H2a1 1 0 0 1-1-1V16a1.5 1.5 0 0 1 1.5-1.5H3zm5.5 0a.25.25 0 0 0-.25-.25h-3.5a.25.25 0 0 0-.25.25v.75h4zm-4 5.5v2c0 .138.112.25.25.25h3.5a.25.25 0 0 0 .25-.25v-2a.25.25 0 0 0-.25-.25h-3.5a.25.25 0 0 0-.25.25");
}

</style>
