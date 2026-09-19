<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ubx3cbcaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blacksky" /></template>
<style>
.ubx3cbcaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.2 31.815h17.6m-8.8 8.8v-17.6M4.5 19.068l17 4.555m22-4.555l-17 4.555m-15.777 6.223l4.555-17m22 17l-4.556-17M17.778 7.385L30.223 19.83m-12.445 0L30.223 7.385");
}

</style>
