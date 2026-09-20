<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-36bnbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-full-outline-sharp" /></template>
<style>
.m-36bnbii {
  fill: currentColor;
  d: path("M4 15V9h13.5v6zm-3 3V6h19.5v12zm2-2h15.5V8H3zm18.5-1.5v-5H23v5z");
}

</style>
