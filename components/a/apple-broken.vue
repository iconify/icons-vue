<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlxieetlr"/><path class="h04_tzbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:apple-broken" /></template>
<style>
.dlxieetlr {
  d: path("M3.16167 13.6674C3.82367 17.9812 6.41177 22 8.99977 22C10.2998 22 10.9998 21.3 11.9998 21.3C12.9998 21.3 13.6998 22 14.9998 22C17.9998 22 20.9998 16.6 20.9998 11.6C20.9998 8.3 19.3998 5.5 16.3998 5.5C14.9998 5.5 13.3998 6.2 11.9998 7.2C10.5998 6.2 8.99977 5.5 7.59977 5.5C5.00967 5.5 3.46307 7.5872 3.08887 10.2813");
}

.h04_tzbza {
  d: path("M12 7.2C12 5.2 12.8 3.4 14.5 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
