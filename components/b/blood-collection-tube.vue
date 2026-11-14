<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en0iou2-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blood-collection-tube" /></template>
<style>
.en0iou2-s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 1.75h3.5q1.036 0 1.768.732t.732 1.768q0 .881-.529 1.542q.029.102.029.208v13q0 3.75-3.75 3.75T8.25 19V6q0-.106.029-.208q-.529-.661-.529-1.542q0-2.5 2.5-2.5m-.5 12V19q0 2.25 2.25 2.25T14.25 19v-5.25zm4.5-1.5V6.704q-.24.046-.5.046h-3.5q-.26 0-.5-.046v5.546z");
}

</style>
