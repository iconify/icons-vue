<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dq1n5ycwa"/><path class="andt5oz3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-duotone-round" /></template>
<style>
.andt5oz3w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 11l3 6c.919 1.838-.162 4-2 4H7c-1.838 0-2.919-2.162-2-4l5-10c.824-1.648 3.176-1.648 4 0zM9 9h6m-9 6h12");
}

.dq1n5ycwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.894 16.553c.56 1.12.597 2.457.034 3.583a3.44 3.44 0 0 1-1.154 1.328A3.2 3.2 0 0 1 17 22H7a3.2 3.2 0 0 1-1.774-.536a3.44 3.44 0 0 1-1.154-1.328c-.563-1.126-.526-2.463.034-3.583l5-10a3.234 3.234 0 0 1 5.788 0Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
