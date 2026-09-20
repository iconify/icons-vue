<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziul6bkgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-indoor-outline-sharp" /></template>
<style>
.ziul6bkgs {
  fill: currentColor;
  d: path("M8.539 16.616h5.23v-2.077l1.847.973v-3.023l-1.847.973v-2.077H8.54zM5 20V9.5l7-5.27l7 5.27V20zm1-1h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
