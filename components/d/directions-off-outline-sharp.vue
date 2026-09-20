<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r27h3-nlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-off-outline-sharp" /></template>
<style>
.r27h3-nlg {
  fill: currentColor;
  d: path("M20.475 23.3L16 18.8l-4 4L1.2 12l4-4L.675 3.5L2.1 2.075l19.8 19.8zM14.6 17.4l-8-8L4 12l8 8zm4.25-1.45l-1.4-1.4L20 12l-8-8l-2.55 2.55l-1.4-1.4L12 1.2L22.8 12zM8 15v-5h2.025l2 2H10v3zm7.45-2.45L17 11l-3.5-3.5V10h-.6z");
}

</style>
