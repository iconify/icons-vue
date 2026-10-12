<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqodo8b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caduceus-sharp" /></template>
<style>
.eqodo8b-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v18.5m0-13.5c-3.75.75-7.5-.75-9.25-4c3.5-.5 6.75.25 9.25 2Zm0 0c3.75.75 7.5-.75 9.25-4c-3.5-.5-6.75.25-9.25 2Zm-2.75 2.5c0 1.75 5.5 1.75 5.5 3.5s-5.5 1.75-5.5 3.5v1.792L12 19.5m2.75-9.25c0 1.75-5.5 1.75-5.5 3.5s5.5 1.75 5.5 3.5v1.792L12 19.5");
}

</style>
