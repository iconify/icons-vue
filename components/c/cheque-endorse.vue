<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="za_8ohbis"/><path class="j4oixebzv"/><path class="qfv5ojbmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-endorse" /></template>
<style>
.j4oixebzv {
  d: path("M21.5 8h-9v10.5");
}

.qfv5ojbmy {
  d: path("M13.75 14c.75-2.5 1.5-3 2-2.25s-.25 1.75.5 1.75c.5 0 .75-1 1.5-1.75M5.5 9.5h4m-4 5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.za_8ohbis {
  d: path("M4.5 5.5h15a2 2 0 0 1 2 2V8l-9 10.5h-8a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2Z");
}

</style>
