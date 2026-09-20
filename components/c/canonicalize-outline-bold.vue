<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oboujbbaa"/><path class="rdidnh2az"/><path class="ok9ioqb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canonicalize-outline-bold" /></template>
<style>
.oboujbbaa {
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.rdidnh2az {
  d: path("m10 11.5 2 2 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
