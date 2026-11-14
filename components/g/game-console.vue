<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0f-lgkcm"/><path class="jn23fbrtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-console" /></template>
<style>
.jn23fbrtd {
  d: path("M8 5.5h8v6H8Zm1.5 9v4m-2-2h4m4.25-1h.01M14 18h.01");
}

.q0f-lgkcm {
  d: path("M5 2.5h14v19H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
