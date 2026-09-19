<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="s40cbewxv"/><path class="znbdvvbqk"/><path class="jfe5vo1oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:frimake" /></template>
<style>
.jfe5vo1oy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.93 28.561h2.352l.42-8.569l2.898-1.26l.458-4.344a.774.774 0 0 0-1.04-.806l-1.644.613l.21-2.184l3.235-1.386l.606-4.916a1.075 1.075 0 0 0-1.504-1.114l-9.1 4.056z");
}

.s40cbewxv {
  cx: 24px;
  cy: 32.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.584px;
  ry: 2.1px;
}

.znbdvvbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.781 31.895C38.781 38.313 32.165 43.5 24 43.5S9.219 38.313 9.219 31.895c0-4.923 3.89-9.131 9.395-10.825l.516 1.84c-3.983 1.31-6.735 4.168-6.735 7.49c0 4.565 5.2 8.257 11.605 8.257s11.606-3.692 11.606-8.258c0-3.321-2.753-6.18-6.736-7.49l.516-1.84c5.505 1.695 9.395 5.903 9.395 10.826");
}

</style>
