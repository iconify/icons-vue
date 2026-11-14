<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-nishbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-fork" /></template>
<style>
.b-nishbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.055 8.288l5.657 5.657m-.707-10.607l-4.95 4.95m7.779-2.122l-7.779 7.779m10.607-4.95l-4.95 4.95m-5.657 0za1.75 1.75 0 0 1 0 2.474l-2.474 2.475a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l2.475-2.474a1.75 1.75 0 0 1 2.474 0");
}

</style>
