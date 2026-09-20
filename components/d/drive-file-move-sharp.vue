<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpusjjhdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-file-move-sharp" /></template>
<style>
.qpusjjhdj {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm10.2-6l-1.625 1.625l1.4 1.4L16 13l-4.025-4.025l-1.4 1.4L12.2 12H8v2z");
}

</style>
