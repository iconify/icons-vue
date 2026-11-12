<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lumh67bhe"/><path class="m3th6ogrs"/><path class="c5vk6tgit"/><path class="kqoyfub9q"/><path class="r4_w910su"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-2-line-duotone" /></template>
<style>
.c5vk6tgit {
  d: path("M13 11C13 12.3807 11.8807 13.5 10.5 13.5C9.11929 13.5 8 12.3807 8 11C8 9.61929 9.11929 8.5 10.5 8.5C11.8807 8.5 13 9.61929 13 11Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqoyfub9q {
  d: path("M16 13L16 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.lumh67bhe {
  d: path("M18.9303 8.06934C19.9438 8.16176 20.6197 8.37704 21.1211 8.87848C21.9998 9.75716 21.9998 11.1714 21.9998 13.9998C21.9998 16.8282 21.9998 18.2424 21.1211 19.1211C20.2424 19.9998 18.8282 19.9998 15.9998 19.9998H10.9998C8.17138 19.9998 6.75716 19.9998 5.87848 19.1211C5.37704 18.6197 5.16176 17.9438 5.06934 16.9303");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.m3th6ogrs {
  d: path("M8 17H13C15.8284 17 17.2426 17 18.1213 16.1213C19 15.2426 19 13.8284 19 11C19 8.17157 19 6.75736 18.1213 5.87868C17.2426 5 15.8284 5 13 5H8C5.17157 5 3.75736 5 2.87868 5.87868C2 6.75736 2 8.17157 2 11C2 13.8284 2 15.2426 2.87868 16.1213C3.75736 17 5.17157 17 8 17Z");
}

.r4_w910su {
  d: path("M5 13L5 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
