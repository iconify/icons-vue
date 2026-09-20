<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="godgd0bts"/><path class="u54ztzb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-down-duotone-bold" /></template>
<style>
.godgd0bts {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 9 7 7 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u54ztzb9f {
  d: path("m5 9 7 7 7 -7");
}

</style>
