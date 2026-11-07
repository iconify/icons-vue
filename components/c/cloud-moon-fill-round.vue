<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga0ahkbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-moon-fill-round" /></template>
<style>
.ga0ahkbmv {
  fill: currentColor;
  d: path("M20.998 8H21a1 1 0 0 1 1 .998V9a7 7 0 0 1-4.491 6.535a1.002 1.002 0 0 1-1.358-.96a1 1 0 0 1 .641-.907a5 5 0 0 0 2.651-2.375a5.267 5.267 0 0 1-6.736-6.738A4.99 4.99 0 0 0 10 9a1 1 0 0 1-2 0a6.9 6.9 0 0 1 .551-2.725A6.9 6.9 0 0 1 10.05 4.05A6.97 6.97 0 0 1 15 2a1 1 0 0 1 .625 1.781a3.265 3.265 0 0 0 1.313 5.739a3.27 3.27 0 0 0 3.281-1.145c.189-.236.476-.374.779-.375M4.967 14.733a4.7 4.7 0 0 1 1.913-2.071a4.84 4.84 0 0 1 3.102-.568c2.138.322 3.657 1.935 3.959 4.057A3 3 0 0 1 13 22H5.667a3.668 3.668 0 0 1-.7-7.267");
}

</style>
