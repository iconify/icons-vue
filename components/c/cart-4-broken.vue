<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fglcsabuc"/><path class="xuvn6vbjj"/><path class="euua0jb3r"/><path class="pynb684jo"/><path class="sflsy2gta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-4-broken" /></template>
<style>
.euua0jb3r {
  stroke-linejoin: round;
  d: path("M18 9L15 3");
}

.fglcsabuc {
  stroke-linejoin: round;
  d: path("M11 11H21M3 11H7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pynb684jo {
  stroke-linejoin: round;
  d: path("M6 9L9 3");
}

.sflsy2gta {
  d: path("M20.0168 16.2572C19.5299 18.5297 19.2864 19.666 18.4613 20.333C17.6362 21 16.4742 21 14.15 21H9.85102C7.52688 21 6.36481 21 5.53974 20.333C4.71467 19.666 4.47118 18.5297 3.9842 16.2572L3.55563 14.2572C2.83717 10.9043 2.47794 9.22793 3.37849 8.11397C4.27904 7 5.99351 7 9.42245 7H14.5786C18.0075 7 19.722 7 20.6226 8.11397C21.2934 8.94376 21.2652 10.0856 20.9102 12");
}

.xuvn6vbjj {
  stroke-linejoin: round;
  d: path("M10 14H14");
}

</style>
