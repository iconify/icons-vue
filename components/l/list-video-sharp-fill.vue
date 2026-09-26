<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tv7158lia"/><path class="w65t0dwgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-video-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tv7158lia {
  fill: currentColor;
  d: path("M16.64 8.2342L22.64 13.2316C23.1537 13.6595 23.111 14.4612 22.5547 14.8321L16.5547 18.8321C15.8901 19.2751 15 18.7987 15 18L15 9.0026C15 8.1549 15.9886 7.6917 16.64 8.2342Z");
  stroke: none;
}

.w65t0dwgg {
  d: path("M1 6L17 6M1 12L13 12M1 18L13 18");
}

</style>
