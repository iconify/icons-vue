<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q8iaooblc"/><path class="mdg-xhg5c"/><path class="sfyvujw3a"/><path class="yg83_ebrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dimension-reduce-duotone-bold" /></template>
<style>
.mdg-xhg5c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18.5 14 2.5 2.5 -4 4 -4 -4 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q8iaooblc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 4 4 4 -6.5 6.5L4 8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sfyvujw3a {
  d: path("m13 4 4 4 -6.5 6.5L4 8l4 -4");
}

.yg83_ebrk {
  d: path("m18.5 14 2.5 2.5 -4 4 -4 -4 2.5 -2.5");
}

</style>
