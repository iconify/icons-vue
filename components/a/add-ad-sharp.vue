<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkx_4obev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-ad-sharp" /></template>
<style>
.gkx_4obev {
  fill: currentColor;
  d: path("M18.192 19.385v-3h-3v-1h3v-3h1v3h3v1h-3v3zM1.808 20V4h16v6h-1V7.385h-14V19h13v1z");
}

</style>
