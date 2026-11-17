<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmq2ccvhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-fill" /></template>
<style>
.dmq2ccvhf {
  fill: currentColor;
  d: path("M3 19h1V6a3 3 0 0 1 3-3h5a1 1 0 0 1 1 1v4.733a3 3 0 0 1 2.874.486l3 2.4A3 3 0 0 1 20 13.961V19h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m8-14H7a.997.997 0 0 0-1 1v13h2v-5.039c0-.911.414-1.773 1.126-2.342l1.874-1.5Z");
}

</style>
