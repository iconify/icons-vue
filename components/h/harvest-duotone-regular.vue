<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q5ee4_3ab"/><path class="xct1uqbtr"/><path class="y0xsptb-g"/><path class="pga6n1bci"/><path class="sfnyx4wnk"/><path class="h-el3xdlg"/><path class="zjyeu0bzf"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:harvest-duotone-regular" /></template>
<style>
.h-el3xdlg {
  d: path("M12 6v14");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pga6n1bci {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q5ee4_3ab {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sfnyx4wnk {
  d: path("M6 6v14");
}

.xct1uqbtr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y0xsptb-g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zjyeu0bzf {
  d: path("M18 6v14");
}

</style>
