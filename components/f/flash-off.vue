<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dop9dhgnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flash-off" /></template>
<style>
.dop9dhgnv {
  fill: currentColor;
  d: path("M7 2h10l-2 7h4l-2.925 4.225L7 4.15zm3 20v-8H7V9.85L1.375 4.225L2.8 2.8l18.4 18.4l-1.425 1.425L13.75 16.6z");
}

</style>
