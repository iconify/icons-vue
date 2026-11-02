<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tzekg83xr"/><path class="yffi_koea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eagle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tzekg83xr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.547 5.013a9.4 9.4 0 0 1 3.525-2.311A11 11 0 0 1 15 2c1.873 0 3.683.645 5.02 1.98a6.6 6.6 0 0 1 1.464 2.236c.348.887.523 1.832.516 2.784v11a1 1 0 0 1-1.555.832l-2.168-1.445l-1.445 2.168a1 1 0 0 1-1.726-.108l-1.38-2.759l-2.019 2.019A1 1 0 0 1 10 20c0-2.078-.365-4.233-1.52-6H5a1 1 0 0 1-1.651.759c-.518-.444-.86-1.049-1.065-1.694C2.073 12.399 2 11.696 2 11c.001-3.342 2.19-5.786 5.547-5.987");
}

.yffi_koea {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6c2-2.3 4.8-3 7-3c3.5 0 6 2.5 6 6v11l-3-2l-2 3l-2-4l-3 3c0-2.5-.5-5-2-7H5c-.6 0-1 .4-1 1c-.7-.6-1-1.7-1-3c0-3 2-5 5-5m4 3h.01");
}

</style>
