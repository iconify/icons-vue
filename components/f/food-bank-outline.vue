<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0w1uoawv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:food-bank-outline" /></template>
<style>
.w0w1uoawv {
  fill: currentColor;
  d: path("M10 18h1v-4q.625 0 1.063-.437T12.5 12.5v-3h-1v3H11v-3h-1v3h-.5v-3h-1v3q0 .625.438 1.063T10 14zm4 0h1V9.5q-.825 0-1.412.588T13 11.5v3h1zM4 21V9l8-6l8 6v12zm2-2h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
