<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tics_4jdh"/><path class="me3whhbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:environment-variable" /></template>
<style>
.me3whhbyn {
  d: path("M8 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.5 8.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

.tics_4jdh {
  d: path("M11.761 19.366H9.495l-.308-2.124l-2.686-1.551l-1.993.795l-1.505-2.607l1.685-1.329v-3.1L3.003 8.121l1.505-2.607l1.993.795l2.686-1.551l.308-2.124h3.01l.308 2.124l2.686 1.551l1.993-.795l1.505 2.607l-1.685 1.329v3.1l1.252.987");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
