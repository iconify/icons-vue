<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvi_ecb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-fill-sharp" /></template>
<style>
.uvi_ecb-a {
  fill: currentColor;
  d: path("M4 19V4a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v4.519l.375-.3a1 1 0 0 1 1.25 0l5 4A1 1 0 0 1 20 13v6h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14-5.519l-4-3.2l-1 .8V19h5Z");
}

</style>
