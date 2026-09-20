<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dkxdfrn3s"/><path class="vniunubej"/><path class="biz7t_4gn"/><path class="aryvw86tm"/><path class="ozi-k-boi"/><path class="wlp3ibbib"/><path class="c3wl0l-ou"/><path class="yhbiuccel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funnel-drop-duotone-thin" /></template>
<style>
.aryvw86tm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.biz7t_4gn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c3wl0l-ou {
  d: path("M19 13v6");
}

.dkxdfrn3s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.vniunubej {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

.yhbiuccel {
  d: path("m16 16 3 3 3 -3");
}

</style>
