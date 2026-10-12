<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x-tg0ib3w"/><path class="foc8bbbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deforestation-sharp" /></template>
<style>
.foc8bbbpa {
  d: path("M7 14.5c3 1.25 7 1.25 10 0m-7 3.25v1.75m1.53-11.53l.69-.69l.53-.53l.62.42l3.26 2.16l.62.42l-.53.53l-2.19 2.19L14 13l-.42-.62l-2.16-3.26L11 8.5zm.22-.47L7.25 3");
}

.x-tg0ib3w {
  d: path("m4 21.25l2.625-.75L7 18.25V11.5h10v6.75l.375 2.25l2.625.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
