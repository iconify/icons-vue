<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4-4j6zix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:car-fan-low-mid-left-outline" /></template>
<style>
.x4-4j6zix {
  fill: currentColor;
  d: path("m13.275 23l-2.9-5H4.15q-.725 0-1.287-.45t-.688-1.15L1.1 11.025q-.225-1.2.538-2.113T3.6 8q.85 0 1.525.55t.925 1.425L7.5 15h2.3q.55 0 1.013.263t.737.737L15 22zM3 7q-.825 0-1.412-.587T1 5t.588-1.412T3 3t1.413.588T5 5t-.587 1.413T3 7m10 4L8 6l5-5l1.4 1.425L11.825 5H18v2h-6.175L14.4 9.6zm5 8l-5-5l1.4-1.4l2.6 2.575V9h2v6.175l2.575-2.575L23 14z");
}

</style>
