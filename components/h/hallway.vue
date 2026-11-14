<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r20dvcy5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hallway" /></template>
<style>
.r20dvcy5q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 1.75h15.5q.631 0 1.15.272l-5.362 4.387q-.44-.159-1.038-.159h-5q-.598 0-1.038.159L3.1 2.022q.519-.272 1.15-.272m12.347 5.73q.153.434.153 1.02v7q0 .586-.153 1.02l5.373 4.395q.28-.524.28-1.165V4.25q0-.641-.28-1.165zM20.9 21.978l-5.362-4.387q-.44.159-1.038.159h-5q-.598 0-1.038-.159L3.1 21.978q.519.272 1.15.272h15.5q.631 0 1.15-.272M7.25 15.5q0 .586.153 1.02L2.03 20.915q-.28-.524-.28-1.165V4.25q0-.641.28-1.165L7.403 7.48q-.153.434-.153 1.02z");
}

</style>
