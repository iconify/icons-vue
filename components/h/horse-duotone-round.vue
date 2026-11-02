<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mol2-hbmr"/><path class="rsua0ubnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:horse-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mol2-hbmr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 5.586V5c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l1.804 1.804l3.732.933a1 1 0 0 1 .651 1.417l-.442.885l2.791.698a1 1 0 0 1 .651 1.417l-.677 1.356l1.49 1.49A1 1 0 0 1 22 14v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22h-2a3.995 3.995 0 0 1-4-4c0-.127-.054-.239-.17-.297c-.045-.023-.086-.033-.123.004l-1 1C8.748 19.665 7.317 20 6 20H5a3 3 0 0 1-3-3v-2c0-1.317.335-2.748 1.293-3.707Z");
}

.rsua0ubnr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6V5c0-.738.631-1.369 1-1l2 2l4 1l-1 2l4 1l-1 2l2 2v3a4 4 0 0 1-4 4h-2a3 3 0 0 1-3-3c0-1.107-1.262-1.738-2-1l-1 1c-.64.64-1.72 1-3 1H5a2 2 0 0 1-2-2v-2c0-1.28.36-2.36 1-3zm1 4h.01M6 16h.01");
}

</style>
