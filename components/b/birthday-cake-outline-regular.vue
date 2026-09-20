<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k8jcztb-g"/><path class="u4sowhi7h"/><path class="v85yu_66d"/><path class="ihh3idyew"/><path class="t_-p3gl9a"/><path class="zfnkrabzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:birthday-cake-outline-regular" /></template>
<style>
.ihh3idyew {
  d: path("M15 8v5");
}

.k8jcztb-g {
  d: path("M4 13v7h16v-7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t_-p3gl9a {
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.v85yu_66d {
  d: path("M9 8v5");
}

.zfnkrabzj {
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
