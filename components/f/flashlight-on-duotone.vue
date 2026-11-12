<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zgalpwdfk"/><path class="lfsapcbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lfsapcbux {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 9l2 2a1.414 1.414 0 0 1 0 2l-3 3h-3l-4 4a1.414 1.414 0 0 1-2 0l-1-1a1.414 1.414 0 0 1 0-2l4-4v-3l3-3a1.414 1.414 0 0 1 2 0zM9 9l6 6m1-12v2m3 0l2-2m-2 5h2");
}

.zgalpwdfk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.707 10.293a2.414 2.414 0 0 1 0 3.414l-3 3A1 1 0 0 1 14 17h-2.586l-3.707 3.707a2.414 2.414 0 0 1-3.414 0l-1-1a2.414 2.414 0 0 1 0-3.414L7 12.586V10c0-.265.105-.52.293-.707l3-3a2.414 2.414 0 0 1 3.414 0Z");
}

</style>
