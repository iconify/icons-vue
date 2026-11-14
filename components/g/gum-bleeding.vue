<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr8jzwbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gum-bleeding" /></template>
<style>
.mr8jzwbki {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75q.86 0 2.216.407Q9.36 2.5 10 2.5t1.784-.343Q13.14 1.75 14 1.75q3.75 0 3.75 4.75q0 1.759-1.079 4.454q-.523 1.306-.69 1.965l-.494 2.345Q14 17.449 14 18.75q0 .076.002.151q-.278.099-.627.099q-1.273 0-1.605-1.328l-.992-4.215q-.246-.707-.778-.707t-.778.707l-.994 4.225Q7.898 19 6.625 19t-1.603-1.318l-.006-.027l-.997-4.736q-.167-.659-.69-1.965Q2.25 8.259 2.25 6.5q0-4.75 3.75-4.75m13.569 11.762q3.181 3.711 3.181 5.238q0 3.75-3.75 3.75t-3.75-3.75q0-1.527 3.181-5.238q.048-.056.106-.102t.124-.079t.137-.053t.144-.026t.147.003t.144.032t.135.059t.12.085q.044.037.081.081M16.75 18.75q0-.869 2.25-3.586q2.25 2.717 2.25 3.586Q21.25 21 19 21t-2.25-2.25");
}

</style>
