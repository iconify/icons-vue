<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6ei3vbab"/><path class="pga6n1bci"/><path class="tmbikdb0m"/><path class="n63pcbbjf"/><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="qbvk0cc3q"/><path class="v4cpchbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-ring-duotone-regular" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.n63pcbbjf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 9 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.qbvk0cc3q {
  d: path("m3 9 2 -2");
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.tmbikdb0m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v4cpchbya {
  d: path("m21 9 -2 -2");
}

.x6ei3vbab {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
