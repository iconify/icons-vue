<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pi5ondbao"/><path class="ybsd2cc6s"/><path class="onei9bb8c"/><path class="faeydrb7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-duotone-bold" /></template>
<style>
.faeydrb7z {
  d: path("m15 6 6 6 -6 6");
}

.onei9bb8c {
  d: path("m9 6 -6 6 6 6");
}

.pi5ondbao {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 6 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ybsd2cc6s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 6 6 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
