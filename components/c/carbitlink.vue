<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i1sxg6b4b"/><path class="pjogw_bld"/><path class="lv_2nw5-s"/><path class="e1qsr7ztv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carbitlink" /></template>
<style>
.e1qsr7ztv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.272 21.077zc2.578-2.577 5.652-5.326 2.82-5.326H21.17");
}

.i1sxg6b4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.34 32.25h6.313a3.84 3.84 0 0 0 3.847-3.829v-.018l-.001-19.055A3.84 3.84 0 0 0 38.667 5.5h-19.07a3.84 3.84 0 0 0-3.847 3.829v.018l.001 14.744c0 2.833 2.749-.24 5.327-2.819v-8.13a2.31 2.31 0 0 1 2.305-2.315h11.473a2.31 2.31 0 0 1 2.316 2.304v.012l.001 11.465a2.31 2.31 0 0 1-2.305 2.315H32.34");
}

.lv_2nw5-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.657 15.75h-6.31A3.84 3.84 0 0 0 5.5 19.581v.016l.001 19.055A3.84 3.84 0 0 0 9.333 42.5h19.071a3.84 3.84 0 0 0 3.847-3.829v-.018l-.001-14.744c0-2.833-2.749.24-5.327 2.819v8.13a2.31 2.31 0 0 1-2.305 2.315H13.144a2.31 2.31 0 0 1-2.316-2.304v-.012l-.001-11.465a2.31 2.31 0 0 1 2.305-2.315h2.527");
}

.pjogw_bld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.728 26.923zc-2.578 2.577-5.652 5.326-2.82 5.326h2.922");
}

</style>
