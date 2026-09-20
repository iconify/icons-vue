<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-suqgbdw"/><path class="ib2ejzoki"/><path class="gp76xqbkg"/><path class="hmx2r2iko"/><path class="teamv5bhf"/><path class="fjiurnzxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cookie-duotone-thin" /></template>
<style>
.fjiurnzxd {
  d: path("M12 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gp76xqbkg {
  fill: currentColor;
  d: path("M12 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hmx2r2iko {
  d: path("M12 4a8 8 0 1 0 8 8 3 3 0 0 1 -4 -4 3 3 0 0 1 -4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib2ejzoki {
  fill: currentColor;
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.teamv5bhf {
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.x-suqgbdw {
  fill: currentColor;
  d: path("M12 4a8 8 0 1 0 8 8 3 3 0 0 1 -4 -4 3 3 0 0 1 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
