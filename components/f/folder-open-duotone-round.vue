<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vx_h7xb3i"/><path class="x6qcjyb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vx_h7xb3i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.414 5H15a5 5 0 0 1 5 5v.281c.881.55 1.207 1.657 1.19 2.645a4.7 4.7 0 0 1-.241 1.39l-1 3C19.237 19.452 17.281 21 15 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293Z");
}

.x6qcjyb9w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 20l2-6c.597-1.792 2.208-3 4-3h8c.984 0 1.492 1.524 1 3l-1 3c-.597 1.792-2.208 3-4 3zm14-9v-1a4 4 0 0 0-4-4h-3l-2-2H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2");
}

</style>
