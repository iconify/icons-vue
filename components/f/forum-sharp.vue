<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1om-ybpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forum-sharp" /></template>
<style>
.a1om-ybpb {
  fill: currentColor;
  d: path("M6.462 16.23v-1.768h12.384V6h1.77v13.308l-3.078-3.077zm-3.077-.691V3h13.461v9.462H6.462z");
}

</style>
