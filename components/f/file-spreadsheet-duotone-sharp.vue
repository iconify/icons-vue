<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="im5zac-eg"/><path class="z5t19fdfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-spreadsheet-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.im5zac-eg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h8l.034.034q-.01-.01-.022-.004a.02.02 0 0 0-.012.018V9h5.952a.02.02 0 0 0 .018-.012q.006-.012-.004-.022L19 9v12H5Z");
}

.z5t19fdfm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h14V9m-6-6l6 6m-6-6v6h6M8 12h8v6H8Zm0 3h8m-5-3v6");
}

</style>
