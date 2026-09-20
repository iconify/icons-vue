<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wkciy9bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:calendar-star" /></template>
<style>
.wkciy9bdd {
  fill: currentColor;
  d: path("M208 32h-24v-8a8 8 0 0 0-16 0v8H88v-8a8 8 0 0 0-16 0v8H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 176H48V48h24v8a8 8 0 0 0 16 0v-8h80v8a8 8 0 0 0 16 0v-8h24zm-31.38-94.36l-29.84-2.31l-11.43-26.5a8 8 0 0 0-14.7 0l-11.43 26.5l-29.84 2.31a8 8 0 0 0-4.47 14.14l22.52 18.59l-6.86 27.71a8 8 0 0 0 11.82 8.81L128 167.82l25.61 15.07a8 8 0 0 0 11.82-8.81l-6.86-27.71l22.52-18.59a8 8 0 0 0-4.47-14.14m-32.11 23.6a8 8 0 0 0-2.68 8.09l3.5 14.12l-13.27-7.81a8 8 0 0 0-8.12 0l-13.27 7.81l3.5-14.12a8 8 0 0 0-2.68-8.09l-11.11-9.18l14.89-1.15a8 8 0 0 0 6.73-4.8l6-13.92l6 13.92a8 8 0 0 0 6.73 4.8l14.89 1.15Z");
}

</style>
