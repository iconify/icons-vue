<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gwjpbneyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-20-filled" /></template>
<style>
.gwjpbneyz {
  fill: currentColor;
  d: path("M8.66 5.425a6.746 6.746 0 0 1 3.991 11.468l-.002.002l-.887.883a2.5 2.5 0 0 1-3.531-.004l-6.003-6.002a2.5 2.5 0 0 1 .003-3.538l.88-.88A6.8 6.8 0 0 1 4.55 6.258a7.8 7.8 0 0 0-.167 1.956a5 5 0 0 0-.211.2l-.883.882c-.39.39-.39 1.025 0 1.415l6.002 6.003a1 1 0 0 0 1.412 0l.886-.881a5.246 5.246 0 0 0 .001-7.418A5.23 5.23 0 0 0 7.994 6.88a4.2 4.2 0 0 1 .665-1.456m-.433-3.19a2.5 2.5 0 0 1 3.537-.001l6.002 6.002a2.5 2.5 0 0 1 .005 3.531l-.88.884l-.002.002a6.8 6.8 0 0 1-1.438 1.094a7.8 7.8 0 0 0 .165-1.957q.109-.096.211-.198l.88-.882a1 1 0 0 0-.002-1.414l-6.002-6.002a1 1 0 0 0-1.415.001l-.878.88a5.247 5.247 0 0 0 0 7.417a5.23 5.23 0 0 0 3.594 1.533a4.2 4.2 0 0 1-.665 1.456a6.7 6.7 0 0 1-3.99-1.928a6.746 6.746 0 0 1 0-9.538z");
}

</style>
