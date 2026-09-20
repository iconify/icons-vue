<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lccp6ubmj"/><path class="sl1xnlz7n"/><path class="eg32wvt_u"/><path class="d31-ss03q"/><path class="uim10mbhy"/><path class="s_qnepbtm"/><path class="e1s2le8fv"/><path class="lmc6jyb6f"/><path class="p41-m0bke"/><path class="vg0qlegui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:list-tree-duotone-thin" /></template>
<style>
.d31-ss03q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e1s2le8fv {
  d: path("M5 10h6");
}

.eg32wvt_u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lccp6ubmj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 3v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lmc6jyb6f {
  d: path("M14 10h7");
}

.p41-m0bke {
  d: path("M5 17h6");
}

.s_qnepbtm {
  d: path("M5 3v14");
}

.sl1xnlz7n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uim10mbhy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vg0qlegui {
  d: path("M14 17h7");
}

</style>
