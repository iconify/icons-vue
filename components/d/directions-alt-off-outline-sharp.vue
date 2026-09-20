<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2w_cysfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-alt-off-outline-sharp" /></template>
<style>
.q2w_cysfn {
  fill: currentColor;
  d: path("M20.475 23.3L16 18.8l-4 4L1.2 12l4-4L.675 3.5L2.1 2.075l19.8 19.8zM14.6 17.4l-1.5-1.5L12 17l-1.4-1.4l1.075-1.1l-1.5-1.5H7v-2h1.175L6.6 9.4L4 12l8 8zm4.25-1.45l-1.4-1.4L20 12l-8-8l-2.55 2.55l-1.4-1.4L12 1.2L22.8 12zm-2.9-2.9L17 12l-5-5l-1.05 1.05zm-5.35.35");
}

</style>
