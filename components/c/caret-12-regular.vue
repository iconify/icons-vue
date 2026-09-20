<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="ft5dv1b6b"><path class="dmqwyqbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-12-regular" /></template>
<style>
.dmqwyqbbk {
  d: path("M7.298 3.255c.63-.63 1.707-.184 1.707.707v3.543a1.5 1.5 0 0 1-1.5 1.5H3.962c-.89 0-1.337-1.077-.707-1.707l4.043-4.043zm.707.707L3.962 8.005h3.543a.5.5 0 0 0 .5-.5V3.962z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

</style>
