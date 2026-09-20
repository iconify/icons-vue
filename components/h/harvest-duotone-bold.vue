<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hzasgob7a"/><path class="ncqq4rbxm"/><path class="yobyeezoh"/><path class="hpm6v1-ys"/><path class="sfnyx4wnk"/><path class="h-el3xdlg"/><path class="zjyeu0bzf"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:harvest-duotone-bold" /></template>
<style>
.h-el3xdlg {
  d: path("M12 6v14");
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hzasgob7a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ncqq4rbxm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sfnyx4wnk {
  d: path("M6 6v14");
}

.yobyeezoh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zjyeu0bzf {
  d: path("M18 6v14");
}

</style>
