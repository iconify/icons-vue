<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx-73pble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-large-fill-round" /></template>
<style>
.qx-73pble {
  fill: currentColor;
  d: path("m11.293 21.707l-6-6a.999.999 0 1 1 1.414-1.414L11 18.586V3a1 1 0 0 1 2 0v15.586l4.293-4.293a.999.999 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0");
}

</style>
