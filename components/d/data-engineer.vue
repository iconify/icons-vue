<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rooutyrzp"/><path class="mb41c7bhd"/><path class="bim2vfbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-engineer" /></template>
<style>
.bim2vfbjn {
  d: path("M14.5 14v4.75m3 2.75H22");
}

.mb41c7bhd {
  fill: currentColor;
  d: path("M15.25 15.25h4L21 17v3.5h-2.25v-3h-3.5Z");
}

.rooutyrzp {
  d: path("M11.672 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.331 0 .653.018m.768-3.279q.141-.053.277-.118q.137-.064.269-.138q.131-.074.257-.158q.125-.084.244-.177q.119-.094.231-.195q.111-.102.215-.212q.103-.11.198-.228q.095-.117.181-.242t.161-.254q.077-.131.143-.267q.066-.135.121-.276q.056-.14.101-.285t.079-.291t.057-.296q.022-.15.034-.3Q15 7.651 15 7.5q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T11 3.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388T7 7.5t.019.392q.02.196.058.388q.038.193.095.381t.132.37t.168.355t.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.373 0 .739-.069");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
