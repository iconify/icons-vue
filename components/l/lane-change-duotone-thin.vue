<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u2wjvdbsd"/><path class="qzhqkqbxa"/><path class="p7om_zblw"/><path class="o7gvdd0dh"/><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="xtovmhbxk"/><path class="codat6b9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lane-change-duotone-thin" /></template>
<style>
.codat6b9f {
  d: path("M11.5 6H15v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwdt7zb5f {
  d: path("M4 2v20");
}

.o7gvdd0dh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 6H15v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p7om_zblw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 19v-7l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pk1ekjvnl {
  d: path("M20 2v20");
}

.qzhqkqbxa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u2wjvdbsd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xtovmhbxk {
  d: path("M9 19v-7l6 -6");
}

</style>
