<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gmb1_8pwn"/><path class="k0kbcfb8h"/><path class="v0vi5lbhg"/><path class="plvge-fqj"/><path class="f2qrz_bxe"/><path class="s_uvnuivb"/><path class="uhty14kih"/><path class="f50v0cimy"/><path class="v5d935don"/><path class="ef5tcc6_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fence-duotone-thin" /></template>
<style>
.ef5tcc6_c {
  d: path("M4 16h14");
}

.f2qrz_bxe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f50v0cimy {
  d: path("M18 7v14");
}

.gmb1_8pwn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0kbcfb8h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plvge-fqj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_uvnuivb {
  d: path("M4 7v14");
}

.uhty14kih {
  d: path("M11 7v14");
}

.v0vi5lbhg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5d935don {
  d: path("M4 11h14");
}

</style>
