<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fb-q0wmum"/><path class="jcqnblbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coach-front-duotone" /></template>
<style>
.fb-q0wmum {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 2a5 5 0 0 1 5 5v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a5 5 0 0 1 5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.jcqnblbzb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4a4 4 0 0 1 4 4v9a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7a4 4 0 0 1 4-4zM6 18h2v2H6Zm10 0h2v2h-2ZM4 12h16M8 15h.01M16 15h.01");
}

</style>
