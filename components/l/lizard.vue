<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u57i21jcm"/><rect class="dr4301u_i"/><path class="s2dy2tbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lizard" /></template>
<style>
.dr4301u_i {
  width: 4px;
  height: 7.25px;
  x: 10px;
  y: 8.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s2dy2tbth {
  d: path("M10 10.25H8l-.75-2m6.75 2h2l.75-2m-6.75 6H8l-.75 2m6.75-2h2l.75 2m-9.5-8L6 7.75m1.25.5L7 7m.25 1.25l.75-.5m8.75.5l1.25-.5m-1.25.5L17 7m-.25 1.25l-.75-.5m-8.75 8.5l-1.25.5m1.25-.5L7 17.5m.25-1.25l.75.5m8.75-.5l1.25.5m-1.25-.5L17 17.5m-.25-1.25l-.75.5M12 16c0 1.5 2 1.75 2 3.25s-1.25 2-2.5 2");
}

.u57i21jcm {
  d: path("M12 2.75c.75 0 2.5 2 2.5 3.5s-1.25 2-2.5 2s-2.5-.5-2.5-2s1.75-3.5 2.5-3.5M11 6.5h.01m1.99 0h.01");
}

</style>
