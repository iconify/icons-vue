<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s503oebdq"/><path class="dcay_lbzn"/></g>`;
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

.s503oebdq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.414 5H17a3 3 0 0 1 3 3v2.281c.881.55 1.207 1.657 1.19 2.645a4.7 4.7 0 0 1-.241 1.39l-1 3c-.317.95-.806 1.851-1.518 2.563C17.785 20.525 16.933 21 16 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293Z");
}

</style>
