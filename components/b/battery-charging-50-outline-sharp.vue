<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsfreebqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-50-outline-sharp" /></template>
<style>
.rsfreebqs {
  fill: currentColor;
  d: path("M16.577 21.48v-2.634h-1.538l2.384-4.327v2.635h1.539zM7.884 21V4.48h2.424V3h3.384v1.48h2.424v7.712q-.275.039-.516.088t-.484.128V5.462H8.885v8.73h3.569q-.644.757-1.01 1.714q-.367.958-.367 2.036q0 .843.227 1.618t.663 1.44z");
}

</style>
