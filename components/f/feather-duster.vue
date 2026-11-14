<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efrtnwq5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feather-duster" /></template>
<style>
.efrtnwq5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V2.5m0 9.5c-1.5-5-3-8-4.75-9M12 12c1.5-5 3-8 4.75-9M12 12C8 6 4.5 5 3 8m9 4c4-6 7.5-7 9-4m-9.125 4h.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-.25a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 11.875 12M12 14.75v6.75");
}

</style>
