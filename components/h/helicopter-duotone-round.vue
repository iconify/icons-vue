<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="esfbuxb0w"/><path class="q-vekkb6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-duotone-round" /></template>
<style>
.esfbuxb0w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 11c0-1.33.522-2.597 1.464-3.536A4.98 4.98 0 0 1 13 6c2.213 0 4.473.62 6.258 1.959c.799.6 1.492 1.343 1.985 2.216c.486.863.757 1.832.757 2.825a4.995 4.995 0 0 1-5 5h-6a3 3 0 0 1-3-3Z");
}

.ft5dv1b6b {
  fill: none;
}

.q-vekkb6p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15a2 2 0 0 0 2 2h6a4 4 0 0 0 4-4c0-3.31-3.58-6-8-6a4 4 0 0 0-4 4Zm-6-2h6m-6-3v6m10 1v4m4-4v4m-8 0h12M13 7v4a2 2 0 0 0 2 2h6M5 3h16m-8 0v4");
}

</style>
