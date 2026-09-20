<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsjvc17ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:3k-plus-outline-sharp" /></template>
<style>
.fsjvc17ke {
  fill: currentColor;
  d: path("M16.5 14h1v-1.5H19v-1h-1.5V10h-1v1.5H15v1h1.5zM11 15h1.5v-2.25L14.25 15h1.825l-2.325-3l2.325-3H14.25l-1.75 2.25V9H11zm-5.5 0H10V9H5.5v1.5h3v1h-2v1h2v1h-3zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
