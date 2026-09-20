<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u2zam5btq"/><path class="e2e5jtb6o"/><path class="ibxltbbey"/><path class="jccaajtgs"/><path class="z_leajngu"/><path class="ptvhb3bfe"/><path class="b8xluzc6p"/><path class="v6f1oidhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collapse-duotone-bold" /></template>
<style>
.b8xluzc6p {
  d: path("M14 20v-6h6");
}

.e2e5jtb6o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ibxltbbey {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 20v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jccaajtgs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ptvhb3bfe {
  d: path("M10 10 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u2zam5btq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 4v6H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v6f1oidhi {
  d: path("m14 14 6 6");
}

.z_leajngu {
  d: path("M10 4v6H4");
}

</style>
