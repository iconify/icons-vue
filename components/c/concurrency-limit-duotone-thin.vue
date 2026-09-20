<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kzvibbczt"/><path class="s2ztwmbwx"/><path class="np1ml0bov"/><path class="pmfm1jbel"/><path class="z5jtjknvm"/><path class="bj2hlhbfp"/><path class="w03o55b0h"/><path class="ds_qvubnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:concurrency-limit-duotone-thin" /></template>
<style>
.bj2hlhbfp {
  d: path("M3 12h12");
}

.ds_qvubnl {
  d: path("M19 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzvibbczt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.np1ml0bov {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pmfm1jbel {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s2ztwmbwx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w03o55b0h {
  d: path("M3 19h12");
}

.z5jtjknvm {
  d: path("M3 5h12");
}

</style>
