<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fembi-i-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bloodtype-outline" /></template>
<style>
.fembi-i-k {
  fill: currentColor;
  d: path("M6.999 18.937Q5 16.873 5 13.8q0-2.154 1.738-4.765T12 3.308q3.525 3.117 5.262 5.728Q19 11.646 19 13.8q0 3.073-2.002 5.137Q14.994 21 11.996 21t-4.998-2.064m9.301-.698Q18 16.475 18 13.8q0-1.825-1.513-4.125T12 4.65Q9.025 7.375 7.513 9.675T6 13.8q0 2.675 1.7 4.438T12 20t4.3-1.763M9.5 17.5h5v-1h-5zm2-3h1v-2h2v-1h-2v-2h-1v2h-2v1h2zm.5-2.346");
}

</style>
