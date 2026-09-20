<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkq_kjbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clear-all-outline-rounded" /></template>
<style>
.wkq_kjbmp {
  fill: currentColor;
  d: path("M4.5 15.885q-.213 0-.356-.144Q4 15.597 4 15.384t.144-.356t.356-.144h11.25q.213 0 .356.145t.144.356t-.144.356t-.356.144zM6.366 12.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h11.25q.212 0 .356.144t.143.357t-.143.356t-.357.143zM8.25 9.116q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.144H19.5q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.144z");
}

</style>
