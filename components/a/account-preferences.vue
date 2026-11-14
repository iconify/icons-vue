<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="istyl6bsr"/><path class="fcd8w2b6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-preferences" /></template>
<style>
.fcd8w2b6w {
  d: path("M13.75 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5 0H22m-3.75 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-4.75 0h4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.istyl6bsr {
  d: path("M11.222 17.372c-.143.084-.222.128-.222.128s-8.5-4.75-8.5-9.75C2.5 5.4 4.4 3.5 6.75 3.5C8.5 3.5 10.1 4.5 11 6c.9-1.5 2.5-2.5 4.25-2.5c2.35 0 4.25 1.9 4.25 4.25c0 1.419-.684 2.817-1.665 4.093");
}

</style>
