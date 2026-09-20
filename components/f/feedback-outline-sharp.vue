<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2x_h9bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:feedback-outline-sharp" /></template>
<style>
.l2x_h9bdc {
  fill: currentColor;
  d: path("M12 14.423q.262 0 .439-.177q.176-.177.176-.438t-.177-.439t-.438-.177t-.438.177t-.177.439t.177.438t.438.177m-.5-2.961h1V5.385h-1zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
