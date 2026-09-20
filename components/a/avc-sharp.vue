<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9otlpjwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:avc-sharp" /></template>
<style>
.w9otlpjwr {
  fill: currentColor;
  d: path("M4.5 15H6v-1.5h1.5V15H9V9H4.5zM6 12v-1.5h1.5V12zm5.25 3h1.5l1.75-6H13l-1 3.425L11 9H9.5zM15 15h4.5v-2H18v.5h-1.5v-3H18v.5h1.5V9H15zM1 20V4h22v16z");
}

</style>
