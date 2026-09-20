<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kvg3iabbs"/><path class="cen9cjvmm"/><path class="caznxbcdb"/><path class="ag27qibsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-up-down-duotone-bold" /></template>
<style>
.ag27qibsz {
  d: path("m7 15 5 5 5 -5");
}

.caznxbcdb {
  d: path("m7 9 5 -5 5 5");
}

.cen9cjvmm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kvg3iabbs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
