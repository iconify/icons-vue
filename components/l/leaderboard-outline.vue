<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi2sg6bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:leaderboard-outline" /></template>
<style>
.yi2sg6bfk {
  fill: currentColor;
  d: path("M4 19h4.673v-8H4zm5.673 0h4.654V5H9.673zm5.654 0H20v-6h-4.673zM3 20V10h5.673V4h6.654v8H21v8z");
}

</style>
