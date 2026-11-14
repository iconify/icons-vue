<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8j9p-pst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:band-charging" /></template>
<style>
.y8j9p-pst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6za5 5 0 0 1 5 5v1a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-1a5 5 0 0 1 5-5m-2 0V2.5h4V6m-4 11v4.5h4V17m7.282-1.153l-1.955 2.216a.564.564 0 0 0 .423.937a.833.833 0 0 1 .769 1.154l-.144.346a.272.272 0 0 0 .455.285l2.09-2.351A.561.561 0 0 0 20 17.5a.876.876 0 0 1-.823-1.175l.073-.2a.277.277 0 0 0-.468-.278");
}

</style>
