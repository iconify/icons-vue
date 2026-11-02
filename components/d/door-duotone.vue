<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wau2s1esc"/><path class="mdox9kbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:door-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mdox9kbui {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M6 21V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v16m-4-9h.01");
}

.wau2s1esc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 22a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1Z");
}

</style>
