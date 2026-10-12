<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="v1jwvbc9a"/><path class="j9i9we_6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gamepad-check-sharp" /></template>
<style>
.j9i9we_6n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 11.75h.01m2.49-2h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v1jwvbc9a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 6.25h9.5l3.435.004l.515 3.396l.3 5.6a2.5 2.5 0 0 1-4.1 2L15 15H9l-1.9 2.25a2.5 2.5 0 0 1-4.1-2l.3-5.6l.515-3.396zm-1 4.5h3m-1.5-1.5v3");
}

</style>
