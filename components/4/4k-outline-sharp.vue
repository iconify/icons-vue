<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbj5imbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4k-outline-sharp" /></template>
<style>
.vbj5imbts {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15h1.825l-2.325-3l2.325-3H16.25l-1.75 2.25V9H13zm-3.5 0H11v-1.5h1V12h-1V9H9.5v3H8V9H6.5v4.5h3zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
