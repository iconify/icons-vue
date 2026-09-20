<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s_uvnuivb"/><path class="uhty14kih"/><path class="f50v0cimy"/><path class="v5d935don"/><path class="ef5tcc6_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fence-outline-regular" /></template>
<style>
.ef5tcc6_c {
  d: path("M4 16h14");
}

.f50v0cimy {
  d: path("M18 7v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_uvnuivb {
  d: path("M4 7v14");
}

.uhty14kih {
  d: path("M11 7v14");
}

.v5d935don {
  d: path("M4 11h14");
}

</style>
