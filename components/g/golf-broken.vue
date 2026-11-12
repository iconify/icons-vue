<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="owzpq1dsn"/><path class="ya4v2ogmm"/><path class="hzret1bgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-broken" /></template>
<style>
.hzret1bgp {
  d: path("M12 3.5L17.4224 6.21114C18.9835 6.99169 19.764 7.38196 19.764 8C19.764 8.61804 18.9835 9.00831 17.4224 9.78886L12 12.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.owzpq1dsn {
  d: path("M16.9785 21.5361C15.5125 21.8312 13.8126 22 12 22C6.47715 22 2 20.433 2 18.5C2 16.567 6.47715 15 12 15C17.5228 15 22 16.567 22 18.5C22 19.0476 21.6407 19.5659 21 20.0274");
}

.ya4v2ogmm {
  d: path("M12 18V2");
}

</style>
