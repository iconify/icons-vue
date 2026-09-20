<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbvjwjbfy"/><path class="edhn96b3v"/><path class="tbu692b6a"/><path class="r3-bp3bbk"/><path class="f1um23b3l"/><path class="jor2cmbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:elevation-duotone-thin" /></template>
<style>
.edhn96b3v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 19h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f1um23b3l {
  d: path("M4 19h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jor2cmbne {
  d: path("m6 16 4 -4 3 3 5 -5");
}

.r3-bp3bbk {
  d: path("M4 3v16");
}

.tbu692b6a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 16 4 -4 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vbvjwjbfy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
