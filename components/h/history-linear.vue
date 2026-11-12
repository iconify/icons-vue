<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kk45u3h5t"/><path class="ryj6knohh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:history-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kk45u3h5t {
  d: path("M12 8V12L14.5 14.5");
}

.ryj6knohh {
  d: path("M4.33776 6.87058L5.60414 5.6042C9.10115 2.10719 14.7996 2.13582 18.3319 5.66816C21.8642 9.2005 21.8929 14.8989 18.3959 18.3959C14.8988 21.8929 9.20044 21.8643 5.6681 18.332C3.57589 16.2397 2.71285 13.3876 3.08355 10.6831M4.32497 4.32503L4.33776 6.87058L6.88331 6.88337");
}

</style>
