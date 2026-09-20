<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mp8ohq58f"/><path class="be5v4vt1q"/><path class="ufny_ofux"/><path class="l77-u97tm"/><path class="a0ad3xbzg"/><path class="v2c2asm0d"/><path class="icp673bbo"/><path class="dm5ccobgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cron-duotone-thin" /></template>
<style>
.a0ad3xbzg {
  d: path("M12 3a9 9 0 1 0 9 9");
}

.be5v4vt1q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 4v5h-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dm5ccobgo {
  d: path("M12 12h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icp673bbo {
  d: path("M12 9v3");
}

.l77-u97tm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mp8ohq58f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3a9 9 0 1 0 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ufny_ofux {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2c2asm0d {
  d: path("M21 4v5h-5");
}

</style>
