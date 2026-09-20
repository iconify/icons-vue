<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzf9ku16i"/><path class="enu3nubgv"/><path class="pv52uob6b"/><path class="cfwhgr43a"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:emergency-room-duotone-thin" /></template>
<style>
.cfwhgr43a {
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
}

.enu3nubgv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pv52uob6b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.wzf9ku16i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
