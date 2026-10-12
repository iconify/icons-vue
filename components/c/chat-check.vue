<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s708y4als"/><path class="pbc1rpa6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbc1rpa6w {
  d: path("M8.75 11.1L11 13.35l4.25-4.5");
}

.s708y4als {
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85c-1.1 0-2.15-.18-3.1-.5L4.6 20c-.6.2-1.15-.4-.9-.95l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85");
}

</style>
