<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ke58ybbzd"/><path class="tknq4nnhp"/><path class="y6rk-dhbm"/><path class="o5odw2bar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-safe-place" /></template>
<style>
.ke58ybbzd {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Z");
}

.o5odw2bar {
  d: path("M8.5 15.25L12 17l3.5-1.75M12 17v3.5");
}

.tknq4nnhp {
  d: path("m12 13.5l3.5 1.75v3.5L12 20.5l-3.5-1.75v-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6rk-dhbm {
  d: path("M6 20.5v-9.75h12v9.75");
}

</style>
