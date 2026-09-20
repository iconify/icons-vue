<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgt3h2b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-added-outline" /></template>
<style>
.fgt3h2b0p {
  fill: currentColor;
  d: path("M17.825 9L15 6.175l1.4-1.425l1.425 1.425l3.525-3.55l1.425 1.425zM5 21V5q0-.825.588-1.412T7 3h6v2H7v12.95l5-2.15l5 2.15V11h2v10l-7-3zM7 5h6z");
}

</style>
