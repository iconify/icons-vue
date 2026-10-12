<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldr-ywnsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barge-sharp" /></template>
<style>
.ldr-ywnsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.94 11.39l1.62-2.28L8 8.5h8l.44.61l1.62 2.28l.44.61h-13zM3.75 12h17.5l-.32.95l-.36 1.1l-.32.95H3.75l-.32-.95l-.36-1.1l-.32-.95zm-.5 7c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
