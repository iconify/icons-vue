<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-vk3kt6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flip-to-front-outline-sharp" /></template>
<style>
.k-vk3kt6y {
  fill: currentColor;
  d: path("M7.692 16.308V4H20v12.308zm1-1H19V5H8.692zM4 20v-1.23h1.23V20zm0-3.692v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zM7.692 20v-1.23h1.231V20zm3.693 0v-1.23h1.23V20zm3.692 0v-1.23h1.23V20z");
}

</style>
