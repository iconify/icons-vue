<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cup1acuxo"/><path class="c8lxf1b3v"/><path class="jcb5sjbcz"/><path class="asg48chvp"/><path class="g-pndgz7k"/><path class="y_uork5-p"/><path class="me2guebva"/><path class="pkr04599e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:knowledge-cutoff-duotone-thin" /></template>
<style>
.asg48chvp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c8lxf1b3v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cup1acuxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g-pndgz7k {
  d: path("M2 12h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcb5sjbcz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.me2guebva {
  d: path("m18 9.5 3 3");
}

.pkr04599e {
  d: path("m21 9.5 -3 3");
}

.y_uork5-p {
  d: path("M15 7v10");
}

</style>
