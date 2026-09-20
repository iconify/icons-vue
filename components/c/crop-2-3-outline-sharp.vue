<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak1734bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-2-3-outline-sharp" /></template>
<style>
.ak1734bru {
  fill: currentColor;
  d: path("M7 21V3h10v18zm1-1h8V4H8zm0 0V4z");
}

</style>
