<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwa-2kbij"/><path class="ge9talb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ge9talb9u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14c0-6-7-11-7-11s-.954.681-2.157 1.843M7.079 8.079C5.913 9.797 5 11.833 5 14a7 7 0 0 0 12.425 4.425M2 3l19 19");
}

.kwa-2kbij {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.843 4.843C11.046 3.681 12 3 12 3s7 5 7 11Zm7.582 13.582A6.97 6.97 0 0 1 12 21a7.003 7.003 0 0 1-7-7c.002-2.142.895-4.175 2.079-5.921Z");
}

</style>
