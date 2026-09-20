<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mphz3abvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:app-spark-outline-rounded" /></template>
<style>
.mphz3abvp {
  fill: currentColor;
  d: path("M5 16.692V19V5zM16.673 20H7.308q-1.381 0-2.344-.963T4 16.692V7.327q0-1.372.964-2.35T7.307 4h4.14q.213 0 .356.144t.144.357t-.144.356t-.356.143h-4.14q-.952 0-1.63.684Q5 6.367 5 7.327v9.365q0 .952.678 1.63t1.63.678h9.365q.96 0 1.644-.678t.683-1.63v-4.14q0-.213.144-.356t.357-.144t.356.144t.143.356v4.14q0 1.381-.977 2.345t-2.35.963m1.308-9.885q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.388-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.391-.361 2.388-1.359q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.388 1.358q-.997.997-1.358 2.387q-.025.15-.2.15");
}

</style>
