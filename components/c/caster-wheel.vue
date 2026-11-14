<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ovq01mbys"/><path class="mojn788jt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:caster-wheel" /></template>
<style>
.mojn788jt {
  d: path("M7.25 15.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm4.75 0h.01");
}

.ovq01mbys {
  d: path("M7 3.25h10m-5 0v4.5m-7.5 8v-8h15v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
