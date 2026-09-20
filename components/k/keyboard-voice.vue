<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w714f96zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-voice" /></template>
<style>
.w714f96zj {
  fill: currentColor;
  d: path("M10.577 12.423Q10 11.846 10 11V5q0-.846.577-1.423T12 3t1.423.577T14 5v6q0 .846-.577 1.423T12 13t-1.423-.577M11.5 20.5v-3.517q-2.35-.216-3.925-1.922T6 11h1q0 2.075 1.463 3.538T12 16t3.538-1.463T17 11h1q0 2.356-1.575 4.062t-3.925 1.92V20.5z");
}

</style>
