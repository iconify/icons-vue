<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5pplvbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:7k-sharp" /></template>
<style>
.c5pplvbqp {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13zm-5.25 0H9.5l1.45-4.7V9H6.5v1.5h2.65zM3 21V3h18v18z");
}

</style>
