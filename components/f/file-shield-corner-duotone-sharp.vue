<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a20bdibtt"/><path class="py7j8u_3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-corner-duotone-sharp" /></template>
<style>
.a20bdibtt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13 3l.034.034q-.01-.01-.022-.004a.02.02 0 0 0-.012.018V8.98q.002.018.02.02H9v12H5V3Zm8 10v3c-.002 2.649-1.701 4.08-4 5c-2.299-.92-3.998-2.351-4-5v-3Z");
}

.ft5dv1b6b {
  fill: none;
}

.py7j8u_3b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-2 4h4v3c0 2.5-1.5 4-4 5c-2.5-1-4-2.5-4-5v-3z");
}

</style>
