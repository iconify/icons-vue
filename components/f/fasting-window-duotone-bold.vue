<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wuz_1qb5l"/><path class="eblwl2bng"/><path class="nex0q68jd"/><path class="jq33rvbor"/><path class="ma01ysb5t"/><path class="uxyzhxvwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fasting-window-duotone-bold" /></template>
<style>
.eblwl2bng {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7h3v10h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jq33rvbor {
  d: path("M6 7H3v10h3");
}

.ma01ysb5t {
  d: path("M18 7h3v10h-3");
}

.nex0q68jd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

.wuz_1qb5l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7H3v10h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
