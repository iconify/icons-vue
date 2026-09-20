<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk01ewu2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hexagon" /></template>
<style>
.wk01ewu2z {
  fill: currentColor;
  d: path("M7.089 20.5L2.177 12l4.912-8.5h9.823l4.911 8.5l-4.911 8.5z");
}

</style>
