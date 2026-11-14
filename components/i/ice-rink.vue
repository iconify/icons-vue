<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pb8evojqp"/><path class="ammu_nb_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-rink" /></template>
<style>
.ammu_nb_l {
  d: path("M9.25 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6.5 12h.01m10.99 0h.01");
}

.pb8evojqp {
  d: path("M5.5 5h13a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3ZM12 5v14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
