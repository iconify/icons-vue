<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ob4cnlbcc"/><path class="tyzrg8n9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brain-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ob4cnlbcc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 20.003A5.002 5.002 0 0 1 2.999 17a5.006 5.006 0 0 1 .081-6.105a4.98 4.98 0 0 1 1.918-4.896A4.004 4.004 0 0 1 12 3.352a4 4 0 0 1 7.002 2.647a4.98 4.98 0 0 1 1.918 4.896A5.006 5.006 0 0 1 21.001 17A5.001 5.001 0 0 1 12 20.003");
}

.tyzrg8n9y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.598 7.5C18.753 5.5 17.31 3 15 3a3 3 0 0 0-3 3m5.956.511a4 4 0 0 1 1.87 4.658M17 18a4 4 0 0 0 2-7.464m.986 6.126A4 4 0 1 1 12 17M6.402 7.5C5.247 5.5 6.69 3 9 3a3 3 0 0 1 3 3m-5.956.511a4 4 0 0 0-1.87 4.658M7 18a4 4 0 0 1-2-7.464m-.986 6.126A4 4 0 1 0 12 17m0-11v11m-3-3a5 5 0 0 0 3-4a5 5 0 0 0 3 4");
}

</style>
