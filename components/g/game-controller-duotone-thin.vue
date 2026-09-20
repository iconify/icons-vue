<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="njozfyw8i"/><path class="j8v_p1wrt"/><path class="y1xrshbyn"/><path class="te6l0fu1w"/><path class="emd5ykbgi"/><path class="lymn1951z"/><path class="me7c_bbry"/><path class="ec5tld62j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-controller-duotone-thin" /></template>
<style>
.ec5tld62j {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.emd5ykbgi {
  d: path("M8 10v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8v_p1wrt {
  fill: currentColor;
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lymn1951z {
  d: path("M6 12h4");
}

.me7c_bbry {
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.njozfyw8i {
  fill: currentColor;
  d: path("M7 7h10c2.5 0 4 3 4 7 0 3 -1 5 -3 5s-3 -3 -6 -3 -4 3 -6 3 -3 -2 -3 -5c0 -4 1.5 -7 4 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.te6l0fu1w {
  d: path("M7 7h10c2.5 0 4 3 4 7 0 3 -1 5 -3 5s-3 -3 -6 -3 -4 3 -6 3 -3 -2 -3 -5c0 -4 1.5 -7 4 -7");
}

.y1xrshbyn {
  fill: currentColor;
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
