<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfnyx4wnk"/><path class="h-el3xdlg"/><path class="zjyeu0bzf"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:harvest-outline-regular" /></template>
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

.sfnyx4wnk {
  d: path("M6 6v14");
}

.zjyeu0bzf {
  d: path("M18 6v14");
}

</style>
