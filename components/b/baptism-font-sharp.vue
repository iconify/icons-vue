<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze37-bbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baptism-font-sharp" /></template>
<style>
.ze37-bbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l1.75 2.148v.952a1.75 1.75 0 0 1-3.5 0v-.952zM3.6 10H21l-.33.5l-2.34 3.5l-.33.5H6l-.33-.5l-2.34-3.5L3 10zm6.4 4.5v6.75m4-6.75v6.75m-7.25 0h10.5");
}

</style>
