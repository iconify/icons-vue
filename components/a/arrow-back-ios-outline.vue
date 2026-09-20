<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qewjwhb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-ios-outline" /></template>
<style>
.qewjwhb9y {
  fill: currentColor;
  d: path("M10 21.308L.692 12L10 2.692l1.064 1.064L2.819 12l8.244 8.244z");
}

</style>
