<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1aqiwbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-frames-outline-sharp" /></template>
<style>
.p1aqiwbro {
  fill: currentColor;
  d: path("M3 21V5h5.616L12 1.615L15.385 5H21v16zm1-1h16V6H4zm2.385-2.384V8.385h11.23v9.23zm1-1h9.23V9.385h-9.23zM12 13");
}

</style>
