<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j31wakssm"/><path class="lh023vobf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pin-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j31wakssm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.707 2.293l6 6A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293M13 4v2a2 2 0 0 0 2 2h2Zm6 9v3l1 1c.369.369.369 1 0 1h-6c-.369 0-.369-.631 0-1l1-1v-3Z");
}

.lh023vobf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-4 4h4v3l1 1c.369.369.369 1 0 1h-6c-.369 0-.369-.631 0-1l1-1zm-1 0h6m-3 5v3");
}

</style>
