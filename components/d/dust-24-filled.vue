<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo-5eqb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dust-24-filled" /></template>
<style>
.jo-5eqb2q {
  fill: currentColor;
  d: path("M6 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2m16 8a1 1 0 1 1-2 0a1 1 0 0 1 2 0M7 21a1 1 0 1 1-2 0a1 1 0 0 1 2 0M8.664 6.943A5.252 5.252 0 0 1 19 8.25c0 1.47-.604 2.798-1.576 3.75a5.25 5.25 0 1 1-8.76 5.057a5.25 5.25 0 1 1 0-10.114");
}

</style>
