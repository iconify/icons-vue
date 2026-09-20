<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p587xlb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:backlight-low-outline-sharp" /></template>
<style>
.p587xlb9j {
  fill: currentColor;
  d: path("M2 15v-2h3v2zm4.35-5.25L4.225 7.625l1.4-1.4L7.75 8.35zM7 18v-3h10v3zm4-11V4h2v3zm6.65 2.775l-1.4-1.425l2.125-2.125l1.4 1.425zM19 15v-2h3v2z");
}

</style>
