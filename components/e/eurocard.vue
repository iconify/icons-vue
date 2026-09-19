<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crzqoew7p"/><path class="qbng31rtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eurocard" /></template>
<style>
.crzqoew7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.167 29.55l-7.352-7.353a5.6 5.6 0 0 0 0 7.917L18.56 40.86a5.6 5.6 0 0 0 7.917 0l-7.352-7.352L31.59 21.043a5.6 5.6 0 0 0 0-7.917z");
}

.qbng31rtl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.512 13.417a5.6 5.6 0 0 0 0-7.917L14.047 15.965a5.6 5.6 0 0 0 0 7.916zm15.673 13.736a5.6 5.6 0 0 0 0-7.917L28.752 30.67a5.6 5.6 0 0 0 0 7.916z");
}

</style>
