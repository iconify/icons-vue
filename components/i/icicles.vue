<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="u50-rob7f"/><path class="pzhmyob9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:icicles" /></template>
<style>
.pzhmyob9w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18h.01");
}

.u50-rob7f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.35 3.75h17.3q.6 0 .6.6V6.4q0 .6-.21 1.16l-1.83 4.88q-.21.56-.42 0l-1.83-4.88Q16.75 7 16.15 7h-1.3q-.6 0-.78.57l-1.89 5.86q-.18.57-.36 0L9.93 7.57Q9.75 7 9.15 7h-1.3q-.6 0-.81.56l-1.83 4.88q-.21.56-.42 0L2.96 7.56Q2.75 7 2.75 6.4V4.35q0-.6.6-.6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
