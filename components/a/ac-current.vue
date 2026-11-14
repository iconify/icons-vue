<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzkr2hbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ac-current" /></template>
<style>
.mzkr2hbig {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 6q-2.816 0-4.471 5.794q-.041.143-.024.292q.017.148.089.278q.073.131.19.223q.117.093.26.134q.071.02.145.026q.073.007.147-.002q.073-.008.143-.031q.071-.023.135-.058t.121-.084q.056-.048.102-.106t.08-.123q.034-.066.054-.137Q4.566 7.5 6.25 7.5t3.029 4.706Q10.934 18 13.75 18q2.68 0 4.309-5.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-4q-.061 0-.121.01t-.117.029t-.112.047q-.053.029-.102.065t-.09.081q-.042.044-.076.094q-.035.05-.061.105t-.042.113Q15.434 16.5 13.75 16.5t-3.029-4.706Q9.066 6 6.25 6");
}

</style>
