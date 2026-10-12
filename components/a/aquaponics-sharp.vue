<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kavst7ymp"/><path class="pbyx5hspp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aquaponics-sharp" /></template>
<style>
.kavst7ymp {
  d: path("M12 11.5v-5M12 9q-1.14-4.28-5.5-3.5Q7.64 9.78 12 9Zm0-1.5q4.65.07 5.5-4.5q-4.65-.07-5.5 4.5Zm-9.25 4h18.5v9.75H2.75z");
}

.pbyx5hspp {
  d: path("M7 16.5c1.75-2 4.75-2 6.5 0c-1.75 2-4.75 2-6.5 0Zm6.5 0l2.5-1.75v3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
