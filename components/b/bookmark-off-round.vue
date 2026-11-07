<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggill5szr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-round" /></template>
<style>
.ggill5szr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h2a4 4 0 0 1 4 4v3m0 6v1c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V8c0-.85.265-1.637.716-2.284M3 2l19 19");
}

</style>
