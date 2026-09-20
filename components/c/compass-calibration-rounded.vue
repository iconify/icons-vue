<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmlzi0bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:compass-calibration-rounded" /></template>
<style>
.rmlzi0bju {
  fill: currentColor;
  d: path("M8.463 20.538Q7 19.075 7 17t1.463-3.537T12 12t3.538 1.463T17 17t-1.463 3.538T12 22t-3.537-1.463m1.225-10.15q-1.113.388-1.988 1.163q-.3.275-.687.25t-.663-.3L2.775 7.925q-.3-.3-.3-.75t.35-.725Q4.775 4.8 7.113 3.9T12 3t4.888.9t4.287 2.55q.35.275.35.725t-.3.75L17.65 11.5q-.275.275-.662.3t-.688-.25q-.875-.775-1.987-1.162T12 10t-2.312.388");
}

</style>
