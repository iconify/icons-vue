<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zo3l58xvi"/><path class="ug46bh26v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flip-video" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ug46bh26v {
  d: path("m11.756 6.816l1.523.888a1.5 1.5 0 0 1 0 2.592l-1.523.888A1.5 1.5 0 0 1 9.5 9.888V8.112a1.5 1.5 0 0 1 2.256-1.296M2.75 16h18.5M5 13.75L2.75 16L5 18.25m14-4.5L21.25 16L19 18.25");
}

.zo3l58xvi {
  d: path("M4 11.166V7.375q0-.107.005-.215q.006-.107.016-.214t.026-.213t.037-.212t.047-.209q.026-.104.057-.207t.068-.204t.077-.2t.087-.197t.097-.191q.05-.095.105-.187q.056-.092.115-.182q.06-.089.124-.175t.132-.169t.14-.163t.148-.156t.156-.148t.163-.14t.169-.132t.175-.124t.182-.115q.092-.055.187-.105q.094-.051.191-.097q.098-.046.197-.087t.2-.077t.204-.068t.207-.057t.209-.047t.212-.037t.213-.026t.214-.016T8.375 3h7.25q.107 0 .215.005q.107.006.214.016t.213.026t.212.037t.209.047t.207.057t.204.068t.2.077t.197.087t.191.097t.187.105q.092.056.182.115q.089.06.175.124t.169.132t.163.14t.156.148t.148.156t.14.163t.132.169t.124.175t.115.182q.055.092.105.187q.051.094.097.191q.046.098.087.197t.077.2t.068.204q.031.103.057.207t.047.209q.021.106.037.212t.026.213t.016.214t.005.215v3.753m-3.329 8.745q-.515.127-1.046.127h-7.25q-.562 0-1.107-.142");
}

</style>
