<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukt7t7lih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:9k-plus-sharp" /></template>
<style>
.ukt7t7lih {
  fill: currentColor;
  d: path("M6 15h4.5V9H6v3.5h3v1H6zm1.5-3.5V10H9v1.5zM11 15h1.5v-2.25L14.25 15H16l-2.25-3L16 9h-1.75l-1.75 2.25V9H11zm5.5-1h1v-1.5H19v-1h-1.5V10h-1v1.5H15v1h1.5zM3 21V3h18v18z");
}

</style>
