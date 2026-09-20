<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhfulkbds"/><path class="lm91bacup"/><path class="kz_z3acnf"/><path class="kc2bz0p3g"/><path class="haaojh5gc"/><path class="mh3_-obpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:contentment-duotone-thin" /></template>
<style>
.haaojh5gc {
  d: path("M16 7h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc2bz0p3g {
  d: path("M4 7h4");
}

.kz_z3acnf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 12a8 8 0 0 1 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lhfulkbds {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lm91bacup {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 7h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mh3_-obpm {
  d: path("M20 12a8 8 0 0 1 -16 0");
}

</style>
