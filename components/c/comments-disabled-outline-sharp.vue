<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1l7_tbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comments-disabled-outline-sharp" /></template>
<style>
.h1l7_tbrg {
  fill: currentColor;
  d: path("M2 18V4.825L.675 3.5L2.1 2.075l19.8 19.8l-1.425 1.425l-5.3-5.3zm20 1.125L18.875 16H20V4H6.875l-2-2H22zM4 16h9.175l-2-2H6v-2h3.175l-1-1H6V9h.175L4 6.825zm12.875-2l-2-2H18v2zm-3-3l-2-2H18v2zm-3-3l-2-2H18v2zm2 2");
}

</style>
