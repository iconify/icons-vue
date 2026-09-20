<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jfmvsgbrx"/><path class="qvu-rvxsg"/><path class="biz7t_4gn"/><path class="p10_onbbz"/><path class="ojq3d2bwe"/><path class="ni-_lk7vs"/><path class="c3wl0l-ou"/><path class="lmzbshh9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-save-duotone-thin" /></template>
<style>
.biz7t_4gn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c3wl0l-ou {
  d: path("M19 13v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfmvsgbrx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lmzbshh9e {
  d: path("M16.5 16.5 19 19l2.5 -2.5");
}

.ni-_lk7vs {
  d: path("M5 5h10v6H5");
}

.ojq3d2bwe {
  d: path("M5 3v18");
}

.p10_onbbz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 16.5 19 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qvu-rvxsg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 5h10v6H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
