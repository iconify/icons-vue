<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q2a3g8acw"/><path class="lxd5vvbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lxd5vvbhp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20v-9l7-7l7 7v9m-9 0v-4a2 2 0 1 1 4 0v4");
}

.q2a3g8acw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.707 10.293A1 1 0 0 1 20 11v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-9c0-.265.105-.52.293-.707l7-7a1 1 0 0 1 1.414 0ZM14 16a2 2 0 1 0-4 0v4h4Z");
}

</style>
