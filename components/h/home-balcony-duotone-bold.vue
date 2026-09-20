<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zhpjv4b8h"/><path class="ycftzzhuq"/><path class="ou49oabkm"/><path class="q0_0mgbuo"/><path class="vz-jaubwy"/><path class="tp3wfdbxm"/><path class="tj_906bjf"/><path class="l8dn9jbyp"/><path class="w60p31c9m"/><path class="e2nq-yvbg"/><path class="e-3fufbxq"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-balcony-duotone-bold" /></template>
<style>
.e-3fufbxq {
  d: path("M19 15v6");
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.ou49oabkm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q0_0mgbuo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tj_906bjf {
  d: path("M4 3v9h16V3");
}

.tp3wfdbxm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vz-jaubwy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w60p31c9m {
  d: path("M5 15v6");
}

.ycftzzhuq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zhpjv4b8h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v9h16V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
