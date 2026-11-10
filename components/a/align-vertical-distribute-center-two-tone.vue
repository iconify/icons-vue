<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s_fuq-2dw"/><path class="zm13vpbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-center-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_fuq-2dw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 13C16.6555 13 18 14.344 18 16H22C22.5523 16 23 16.448 23 17C23 17.552 22.5523 18 22 18H18C18 19.659 16.6553 21 15 21H9C7.3422 21 6 19.658 6 18H2C1.4477 18 1 17.552 1 17C1 16.448 1.4477 16 2 16H6C6 14.345 7.3411 13 9 13H15ZM17 3C18.6519 3 20 4.341 20 6H22C22.5523 6 23 6.448 23 7C23 7.552 22.5523 8 22 8H20C20 9.656 18.6545 11 17 11H7C5.3415 11 4 9.661 4 8H2C1.4477 8 1 7.552 1 7C1 6.448 1.4477 6 2 6H4C4 4.349 5.3375 3 7 3H17Z");
  stroke: none;
}

.zm13vpbbe {
  d: path("M7 17V16C7 14.896 7.8941 14 9 14H15C16.1032 14 17 14.897 17 16V17M7 17V18C7 19.106 7.8945 20 9 20H15C16.1037 20 17 19.106 17 18V17M7 17H2M17 17H22M19 7V8C19 9.104 18.1025 10 17 10H7C5.8934 10 5 9.108 5 8V7M19 7V6C19 4.894 18.1011 4 17 4H7C5.892 4 5 4.899 5 6V7M19 7H22M5 7H2");
}

</style>
