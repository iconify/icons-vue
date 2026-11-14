<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv3ilzb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:landlord" /></template>
<style>
.cv3ilzb0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.99 10.97q.228-.131.437-.29q.209-.16.395-.345q.186-.186.347-.394t.292-.436t.233-.47t.169-.497t.103-.514Q16 7.763 16 7.5q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T12 3.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388T8 7.5t.019.392q.02.196.058.388q.038.193.095.381t.132.37q.076.181.168.355q.093.173.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.082 0 .165-.003M4 21c0-4 3.5-6.5 8-6.5l.146.001M15 13.75h6v8h-6Zm3 2.75h.01M18 19.25h.01");
}

</style>
