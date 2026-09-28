<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlrt-fb0l"/><path class="afjmqabbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baseball-duotone" /></template>
<style>
.afjmqabbu {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlrt-fb0l {
  stroke-opacity: 0.4;
  d: path("M9.4118 2.3407C9.8068 3.1401 10.0735 3.9967 10.2022 4.8789M9.7265 9.1526C9.4069 9.9849 8.9584 10.7619 8.3973 11.4548M4.9341 14.0036C4.1057 14.3333 3.2305 14.5305 2.3407 14.5882M21.6593 9.4118C20.7695 9.4695 19.8943 9.6667 19.0659 9.9964M15.6027 12.5452C15.0416 13.2381 14.5931 14.0151 14.2735 14.8474M13.7978 19.1211C13.9265 20.0033 14.1932 20.8599 14.5882 21.6593");
}

</style>
