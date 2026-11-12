<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ma3owob5u"/><path class="k2l2q8byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-sparkle-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k2l2q8byq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H4V5h16v4M8 3v2m8-2v2M4 9h16m-3 4c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.ma3owob5u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9v12H4V9Zm12 8c-2.005.002-3.998 1.995-4 4c-.002-2.005-1.995-3.998-4-4c2.005-.002 3.998-1.995 4-4c.002 2.005 1.995 3.998 4 4");
}

</style>
