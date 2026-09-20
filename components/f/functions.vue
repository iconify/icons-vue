<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy5-ernil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:functions" /></template>
<style>
.jy5-ernil {
  fill: currentColor;
  d: path("M6 20v-2l6.5-6L6 6V4h12v3h-7.225l5.375 5l-5.375 5H18v3z");
}

</style>
