<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ueu2mp65r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-star-bold" /></template>
<style>
.ueu2mp65r {
  fill: currentColor;
  d: path("M28 64a12 12 0 0 1 12-12h176a12 12 0 0 1 0 24H40a12 12 0 0 1-12-12m12 76h48a12 12 0 0 0 0-24H40a12 12 0 0 0 0 24m64 40H40a12 12 0 0 0 0 24h64a12 12 0 0 0 0-24m135.64-33.13l-20.58 17l6.25 25.26a12 12 0 0 1-17.73 13.22L184 188.46l-23.58 13.88a12 12 0 0 1-17.73-13.22l6.25-25.26l-20.58-17a12 12 0 0 1 6.72-21.22l27.42-2.12L173 99.25a12 12 0 0 1 22 0l10.48 24.28l27.42 2.12a12 12 0 0 1 6.72 21.22Zm-38.21.42l-5-.39a12 12 0 0 1-10.09-7.21l-2.33-5.4l-2.33 5.4a12 12 0 0 1-10.1 7.21l-5 .39l3.48 2.87a12 12 0 0 1 4 12.13l-1.21 4.89l5.07-3a12.06 12.06 0 0 1 12.18 0l5.07 3l-1.17-4.89a12 12 0 0 1 4-12.13Z");
}

</style>
