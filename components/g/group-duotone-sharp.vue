<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e_-4zobrf"/><path class="eul4pkbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-duotone-sharp" /></template>
<style>
.e_-4zobrf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 12h7v5h-7Z");
}

.eul4pkbhp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7h7v5H7zm3 5h7v5h-7zM3 6V3h3m12 0h3v3m0 12v3h-3M6 21H3v-3");
}

.ft5dv1b6b {
  fill: none;
}

</style>
