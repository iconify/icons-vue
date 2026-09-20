<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vc91lmbbc"/><path class="u38qczjqj"/><path class="yl27xj7ez"/><path class="ev1ejqbjw"/><path class="ozu7q9bor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bbq-duotone-bold" /></template>
<style>
.ev1ejqbjw {
  d: path("m8 18 -3 3");
}

.ozu7q9bor {
  d: path("m16 18 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u38qczjqj {
  d: path("M4 11a8 8 0 0 1 16 0");
}

.vc91lmbbc {
  fill: currentColor;
  d: path("M4 13h16c0 3 -3 5 -8 5s-8 -2 -8 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yl27xj7ez {
  d: path("M4 13h16c0 3 -3 5 -8 5s-8 -2 -8 -5");
}

</style>
