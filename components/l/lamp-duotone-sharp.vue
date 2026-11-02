<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dw_b_kboh"/><path class="xjp78kbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lamp-duotone-sharp" /></template>
<style>
.dw_b_kboh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 2c.379 0 .725.214.894.553l4 8A1 1 0 0 1 19 12H5a1 1 0 0 1-.894-1.447l4-8A1 1 0 0 1 9 2Zm1 14a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
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
