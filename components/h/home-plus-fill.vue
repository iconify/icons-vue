<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l5o7821vm"/><path class="oq4of54oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-plus-fill" /></template>
<style>
.l5o7821vm {
  fill: currentColor;
  d: path("M21 12L21 20.0002C20.9999 21.657 19.6568 23.0002 18 23.0002L15 23.0002L15 14.0002L7 14.0002L7 23.0002L4 23.0002C2.3432 23.0002 1.0001 21.657 1 20.0002L1 11.927C1 11.0454 1.3878 10.2079 2.0605 9.6379L9.0605 3.7073C10.0406 2.877 11.4212 2.7739 12.5007 3.3981C12.8098 3.5768 13 3.907 13 4.264L13 8C13 9.6569 14.3431 11 16 11L20 11C20.5523 11 21 11.4477 21 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oq4of54oo {
  d: path("M19 2V8M16 5H22");
}

</style>
