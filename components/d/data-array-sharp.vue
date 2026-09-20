<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8gq167yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-array-sharp" /></template>
<style>
.w8gq167yp {
  fill: currentColor;
  d: path("M15 20v-2h3V6h-3V4h5v16zM4 20V4h5v2H6v12h3v2z");
}

</style>
