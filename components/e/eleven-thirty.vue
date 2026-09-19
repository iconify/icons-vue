<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h31is259c"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:eleven-thirty" /></template>
<style>
.h31is259c {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m3.4 34.973l-1.4.375V58h-4V35.445c-1.19-.693-2-1.969-2-3.445a4 4 0 0 1 1.191-2.846L25.4 15.025L29.234 14l3.221 12H34v2.554a3.983 3.983 0 0 1 .825 6.277z");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
