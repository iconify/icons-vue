<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pv3mbccsc"/><path class="ftcyjfb1t"/><path class="t1dvawbqd"/><path class="a_-94rbje"/><path class="f9uxp9ptq"/><path class="he6k4tqrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:country-flag-duotone-thin" /></template>
<style>
.a_-94rbje {
  d: path("M5 2v20");
}

.f9uxp9ptq {
  d: path("M5 4h14v9H5");
}

.ftcyjfb1t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4h14v9H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.he6k4tqrw {
  d: path("M5 8.5h14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pv3mbccsc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t1dvawbqd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8.5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
