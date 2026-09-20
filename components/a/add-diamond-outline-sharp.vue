<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_0e9tih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-diamond-outline-sharp" /></template>
<style>
.mc_0e9tih {
  fill: currentColor;
  d: path("M11.5 15.616h1V12.5h3.116v-1H12.5V8.385h-1V11.5H8.385v1H11.5zm.506 6.061L2.34 12l9.665-9.671L21.66 12zM12 20.269L20.264 12L12 3.73L3.737 12zM12 12");
}

</style>
