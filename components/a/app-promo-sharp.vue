<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bej_zjp1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:app-promo-sharp" /></template>
<style>
.bej_zjp1m {
  fill: currentColor;
  d: path("M15.308 11L12 14.308L8.692 11l.708-.708l2.1 2.089V7.692h1v4.689l2.1-2.089zm-5.077 8.654h3.538v-.77h-3.538zM6 22V2h12v20zm1-5.462h10V5.5H7z");
}

</style>
