<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tyoztnz-r"/><path class="a8ao9m93p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-loop-limit-sharp-two-tone" /></template>
<style>
.a8ao9m93p {
  d: path("M2 10L7 5L17 5L22 10L22 19L2 19Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tyoztnz-r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 20L2 20C1.4477 20 1 19.5523 1 19L1 10C1 9.7348 1.1054 9.4804 1.2929 9.2929L6.2929 4.2929C6.4804 4.1054 6.7348 4 7 4L17 4C17.2652 4 17.5196 4.1054 17.7071 4.2929L22.7071 9.2929C22.8946 9.4804 23 9.7348 23 10L23 19C23 19.5523 22.5523 20 22 20Z");
  stroke: none;
}

</style>
