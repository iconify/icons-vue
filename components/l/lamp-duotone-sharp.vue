<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="augw3-b9y"/><path class="xjp78kbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lamp-duotone-sharp" /></template>
<style>
.augw3-b9y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3h6l4 8H5ZM8 17h8v4H8Z");
}

.ft5dv1b6b {
  fill: none;
}

.xjp78kbaj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6l4 8H5zm3 8v6m-4 0h8v4H8Z");
}

</style>
