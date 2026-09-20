<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfyw8dbnu"/><path class="enrpg0aoq"/><path class="mg7aqnbsf"/><path class="jkuojibnm"/><path class="ka0_g35wl"/><path class="gls0jcb3n"/><path class="j7s4o3bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alpn-duotone-regular" /></template>
<style>
.enrpg0aoq {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.gls0jcb3n {
  d: path("m16 6 -2.5 2.5");
}

.j7s4o3bav {
  d: path("m9 15 2.5 2.5");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ka0_g35wl {
  d: path("m8 6 2.5 2.5");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wfyw8dbnu {
  fill: currentColor;
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
