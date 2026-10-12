<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow-aohbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forest" /></template>
<style>
.ow-aohbbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.18 8.05l2.38 3.04q.43.55-.2.55t-.21.56l1.86 2.48q.42.56-.28.56h-.22q-.7 0-.26.55l2 2.5q.44.55-.26.55H3.51q-.7 0-.26-.55l2-2.5q.44-.55-.26-.55h-.22q-.7 0-.28-.56l1.86-2.48q.42-.56-.21-.56t-.2-.55l2.38-3.04q.43-.55.86 0m3.22 2.25l.87-1.16h-1.26L15.25 5l3.24 4.14h-1.26l2.7 3.6h-1.62l2.88 3.6H14m-5.25 2.5v2.41m8-4.91v4.91m-14 0h18.5");
}

</style>
