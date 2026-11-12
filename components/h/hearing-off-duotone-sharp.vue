<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xohbcmoks"/><path class="t0nnhnb7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t0nnhnb7o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 9c0-.88.19-1.717.53-2.47m3-3A6 6 0 0 1 18 9c0 1.03-.177 1.853-.47 2.53m-2.983 3.017C13.212 15.414 12 16.202 12 18a3 3 0 0 1-6 0M2 2l20 20");
}

.xohbcmoks {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.53 3.53A6.003 6.003 0 0 1 18 9c0 .862-.127 1.735-.469 2.531ZM6 18V9c0-.853.178-1.693.53-2.47l8.017 8.017c-1.346.875-2.545 1.67-2.547 3.453a2.998 2.998 0 1 1-6 0");
}

</style>
