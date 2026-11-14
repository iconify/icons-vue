<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r5dgpu5sm"/><path class="fsecig9_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:department-supervisor" /></template>
<style>
.fsecig9_w {
  d: path("M16.5 13.75h3.25V16H16.5Zm.25 4.5h2.75m-2.75 2h1.75");
}

.r5dgpu5sm {
  d: path("M13.99 10.97q.228-.131.437-.29q.209-.16.395-.345q.186-.186.347-.394t.292-.436t.233-.47t.169-.497t.103-.514Q16 7.763 16 7.5q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T12 3.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388T8 7.5t.019.392q.02.196.058.388q.038.193.095.381t.132.37q.076.181.168.355q.093.173.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.443 0 .875-.097q.433-.097.833-.286M4 21.5c0-3.98 3.466-6.475 7.934-6.5m2.816 0h6.75v7h-6.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
