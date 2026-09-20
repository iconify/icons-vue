<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6x2e-i7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:15mp-sharp" /></template>
<style>
.a6x2e-i7b {
  fill: currentColor;
  d: path("M8.5 11.5H10v-6H7V7h1.5zm3.5 0h4.5V8h-3V7h3V5.5H12V9h3v1h-3zm-6 7h1.5V14h1v3H10v-3h1v4.5h1.5v-6H6zm7.5 0H15V17h3v-4.5h-4.5zm1.5-3V14h1.5v1.5zM3 21V3h18v18z");
}

</style>
