<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ge8kr1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dhaba-sign-sharp" /></template>
<style>
.s9ge8kr1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.75v18.5m0-16h15.75m-10.75 0v3.5m8.5-3.5v3.5m-10.75 0h13v8h-13zm2.75 3h7.5M9 14h4.5");
}

</style>
