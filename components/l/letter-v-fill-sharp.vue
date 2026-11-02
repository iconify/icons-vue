<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1rvn5bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-v-fill-sharp" /></template>
<style>
.m1rvn5bri {
  fill: currentColor;
  d: path("m12 17.152l5.064-13.503a1 1 0 1 1 1.872.702l-6 16a1 1 0 0 1-1.872 0l-6-16a1 1 0 1 1 1.872-.702Z");
}

</style>
