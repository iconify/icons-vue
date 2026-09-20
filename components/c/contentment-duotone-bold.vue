<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ztk-57bkf"/><path class="ke6e1gheh"/><path class="asywpnb9d"/><path class="kc2bz0p3g"/><path class="haaojh5gc"/><path class="mh3_-obpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:contentment-duotone-bold" /></template>
<style>
.asywpnb9d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 12a8 8 0 0 1 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.haaojh5gc {
  d: path("M16 7h4");
}

.kc2bz0p3g {
  d: path("M4 7h4");
}

.ke6e1gheh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 7h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mh3_-obpm {
  d: path("M20 12a8 8 0 0 1 -16 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ztk-57bkf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
