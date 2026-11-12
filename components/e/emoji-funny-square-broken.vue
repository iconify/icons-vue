<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="m-_j7-iyd"/><path class="dl9l1deqp"/><path class="zvbb8ccix"/><path class="tdhloyasy"/><ellipse transform="rotate(-15 8.714 11.328)" class="l5tkhob0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:emoji-funny-square-broken" /></template>
<style>
.dl9l1deqp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.7964 9.643C21.9075 13.7897 22.4631 15.863 21.5201 17.4964C20.577 19.1298 18.5037 19.6853 14.357 20.7964C10.2103 21.9075 8.13698 22.4631 6.50359 21.5201C4.87021 20.577 4.31466 18.5037 3.20356 14.357C2.09246 10.2103 1.53691 8.13698 2.47995 6.50359C3.42298 4.87021 5.49632 4.31466 9.643 3.20356C13.7897 2.09246 15.863 1.53691 17.4964 2.47995C18.5048 3.06212 19.1023 4.07505 19.6734 5.74061");
}

.l5tkhob0v {
  cx: 8.714px;
  cy: 11.328px;
  rx: 0.5px;
  ry: 1px;
}

.m-_j7-iyd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.9126 15.9331C10.1709 16.2485 11.5985 16.2487 13.0351 15.8638C14.4717 15.4788 15.7079 14.7649 16.64 13.8626");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.tdhloyasy {
  d: path("M14.9923 9.64464C15.1353 10.1781 15.0349 10.6685 14.7682 10.74C14.5014 10.8114 14.1693 10.4369 14.0264 9.90346C13.8835 9.36999 13.9838 8.87959 14.2505 8.80812C14.5173 8.73665 14.8494 9.11117 14.9923 9.64464Z");
}

.zvbb8ccix {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 15.9999L13.478 16.9737C13.8393 17.7099 14.7249 18.0193 15.4661 17.6685C16.2223 17.3105 16.5394 16.403 16.1708 15.6519L15.7115 14.7163");
}

</style>
