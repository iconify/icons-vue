<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8xf350k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-left-bulk" /></template>
<style>
.zp8xf350k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.293 7.293A1 1 0 0 1 15 8v8a1.002 1.002 0 0 1-1.707.707l-4-4a1 1 0 0 1 0-1.414Z");
}

</style>
