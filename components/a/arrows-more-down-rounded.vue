<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm3pe7bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-more-down-rounded" /></template>
<style>
.lm3pe7bns {
  fill: currentColor;
  d: path("M6.808 20q-.343 0-.576-.232T6 19.192V10.5q0-.213.144-.356T6.501 10t.356.144T7 10.5V19h8.5q.213 0 .356.144t.144.357t-.144.356T15.5 20zm4-3.98q-.343 0-.576-.233T10 15.212V6.519q0-.212.144-.356t.357-.144t.356.144t.143.356v8.5h8.5q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143z");
}

</style>
