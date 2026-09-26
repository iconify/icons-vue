<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rau-pebxg"/><path class="jkh-81bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jkh-81bok {
  fill: currentColor;
  d: path("M7 7C7 7.5523 6.5523 8 6 8C5.4477 8 5 7.5523 5 7C5 6.4477 5.4477 6 6 6C6.5523 6 7 6.4477 7 7ZM19 7C19 7.5523 18.5523 8 18 8C17.4477 8 17 7.5523 17 7C17 6.4477 17.4477 6 18 6C18.5523 6 19 6.4477 19 7Z");
  stroke: none;
}

.rau-pebxg {
  d: path("M10 19L10 7C10 4.7909 8.2091 3 6 3C3.7909 3 2 4.7909 2 7C2 9.2091 3.7909 11 6 11L6 19C6 20.1046 6.8954 21 8 21C9.1046 21 10 20.1046 10 19ZM14 19C14 20.1046 14.8954 21 16 21C17.1046 21 18 20.1046 18 19L18 11C20.2091 11 22 9.2091 22 7C22 4.7909 20.2091 3 18 3C15.7909 3 14 4.7909 14 7L14 19ZM6 17L10 17M14 17L18 17");
}

</style>
