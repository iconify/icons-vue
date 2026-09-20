<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q31y1lb9i"/><path class="ci4oydb4u"/><path class="w69svbcwu"/><path class="am7eiccgy"/><path class="r4nj1cczx"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:groupby-duotone-thin" /></template>
<style>
.am7eiccgy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ci4oydb4u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eu9kkgbdm {
  d: path("M9 12h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q31y1lb9i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4H3v16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r4nj1cczx {
  d: path("M6 4H3v16h3");
}

.sxy07wbdf {
  d: path("M9 7h12");
}

.w69svbcwu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3jqftbaj {
  d: path("M9 17h12");
}

</style>
