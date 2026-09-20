<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4x0cbcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:award-star-sharp" /></template>
<style>
.j4x0cbcgz {
  fill: currentColor;
  d: path("M9.075 16.25L12 14.475l2.925 1.775l-.775-3.325l2.6-2.25l-3.425-.275L12 7.25l-1.325 3.15l-3.425.275l2.6 2.25zM12 23.3L8.65 20H4v-4.65L.7 12L4 8.65V4h4.65L12 .7L15.35 4H20v4.65L23.3 12L20 15.35V20h-4.65z");
}

</style>
