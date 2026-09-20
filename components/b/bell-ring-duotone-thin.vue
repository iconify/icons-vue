<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u0jypcc9y"/><path class="hsnj9o-9y"/><path class="s5t13vp2n"/><path class="nru03jbry"/><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="qbvk0cc3q"/><path class="v4cpchbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-ring-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsnj9o-9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nru03jbry {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 9 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qbvk0cc3q {
  d: path("m3 9 2 -2");
}

.s5t13vp2n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.u0jypcc9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v4cpchbya {
  d: path("m21 9 -2 -2");
}

</style>
