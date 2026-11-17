<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v8to1b-nf"/><path class="dcay_lbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-duotone" /></template>
<style>
.dcay_lbzn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 20l2-6c.597-1.792 1.806-3 3-3h9c.984 0 1.492 1.524 1 3l-1 3c-.597 1.792-1.806 3-3 3zm14-9V8a2 2 0 0 0-2-2h-5l-2-2H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2");
}

.ft5dv1b6b {
  fill: none;
}

.v8to1b-nf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10 4l2 2h5a2 2 0 0 1 2 2v3c.984 0 1.492 1.524 1 3l-1 3c-.597 1.792-1.806 3-3 3H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2Z");
}

</style>
