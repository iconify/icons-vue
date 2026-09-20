<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v-yp75brd"/><path class="dl99ckb4n"/><path class="y4k_22w_l"/><path class="uokpg3btu"/><path class="k6xp8gb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gallery-duotone-bold" /></template>
<style>
.dl99ckb4n {
  d: path("M4 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.k6xp8gb2a {
  d: path("m9 17 4 -4 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uokpg3btu {
  d: path("M12 5v3");
}

.v-yp75brd {
  fill: currentColor;
  d: path("M4 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y4k_22w_l {
  d: path("M8 5h8");
}

</style>
