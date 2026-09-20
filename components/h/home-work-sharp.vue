<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1ig3p5mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-work-sharp" /></template>
<style>
.j1ig3p5mc {
  fill: currentColor;
  d: path("M17.23 8.77h1.54V7.23h-1.54zm0 4h1.54v-1.54h-1.54zm0 4h1.54v-1.54h-1.54zM2 20v-8.5l6-4.27l6 4.27V20H9.846v-5.077H6.154V20zm14 0v-9.5l-5.615-4.03V4H22v16z");
}

</style>
