<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mjwrhabdo"/><path class="sp2_1ob7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-connection-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mjwrhabdo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.222 17H8.778a3 3 0 0 1-3-3V9.806a3 3 0 0 1 1.024-2.258l3.222-2.819a3 3 0 0 1 3.952 0l3.222 2.819a3 3 0 0 1 1.024 2.258V14a3 3 0 0 1-3 3");
}

.sp2_1ob7w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H8.778a3 3 0 0 1-3-3V9.806a3 3 0 0 1 1.024-2.258l3.222-2.82a3 3 0 0 1 3.952 0l3.222 2.82a3 3 0 0 1 1.024 2.258V14a3 3 0 0 1-3 3zm0 0v4m-8 0h16");
}

</style>
