<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsf8c2b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-fill" /></template>
<style>
.dsf8c2b6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 10H14.5C14.22386 10 14 9.77614 14 9.5V3M14.6 9.4L21 3M3 14H9.5C9.77614 14 10 14.22386 10 14.5V21M9.4 14.6L3 21");
}

</style>
