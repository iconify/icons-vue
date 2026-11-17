<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u_unmqbul"/><path class="mp99cub2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mp99cub2r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3H9c-.738 0-1.369.631-1 1l3 3a1.414 1.414 0 0 0 2 0l3-3c.369-.369-.262-1-1-1zm-7 9h2m4 0h2m4 0h2m-7 9H9c-.738 0-1.369-.631-1-1l3-3a1.414 1.414 0 0 1 2 0l3 3c.369.369-.262 1-1 1z");
}

.u_unmqbul {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3c.738 0 1.369.631 1 1l-3 3a1.415 1.415 0 0 1-2 0L8 4c-.369-.369.262-1 1-1Zm0 18H9c-.738 0-1.369-.631-1-1l3-3a1.415 1.415 0 0 1 2 0l3 3c.369.369-.262 1-1 1");
}

</style>
