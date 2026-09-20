<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ly3j-y5cm"/><path class="d__fyibtt"/><path class="r1gclvbbm"/><path class="ks2swpbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:done-all-duotone-bold" /></template>
<style>
.d__fyibtt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 12 5 5 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ks2swpbkw {
  d: path("m9 12 5 5 8 -8");
}

.ly3j-y5cm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 12 5 5 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1gclvbbm {
  d: path("m2 12 5 5 8 -8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
