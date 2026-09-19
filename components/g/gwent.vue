<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="srmg2db2a"/><path class="bkom-bb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gwent" /></template>
<style>
.bkom-bb7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.602 26.133L24 19.734l6.398 6.399L24 32.53Z");
}

.srmg2db2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.719 40.148H42.28M5.719 37.71H42.28M4.5 32.706l2.438 2.567h7.007v-4.875h-2.742v-4.875L12.727 24L4.5 15.773Zm39 0l-2.437 2.568h-7.008v-4.875h2.742v-4.875L35.273 24l8.227-8.227Zm-27.422 2.567h15.844v-18.89L24 7.852l-7.922 8.53Z");
}

</style>
