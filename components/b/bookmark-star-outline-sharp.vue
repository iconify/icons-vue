<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhkg6ozft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-star-outline-sharp" /></template>
<style>
.fhkg6ozft {
  fill: currentColor;
  d: path("M10.071 13.462L12 12.298l1.929 1.164l-.523-2.196l1.711-1.475l-2.24-.187L12 7.539l-.877 2.065l-2.24.187l1.711 1.475zM6 19.5V4h12v15.5l-6-2.577zm1-1.55l5-2.15l5 2.15V5H7zM7 5h10z");
}

</style>
