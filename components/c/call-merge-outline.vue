<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1tsmnb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-merge-outline" /></template>
<style>
.b1tsmnb1w {
  fill: currentColor;
  d: path("M7.4 20L6 18.6l5-5V6.875L8.425 9.45L7 8.025l5-5l5.025 5.025L15.6 9.475l-2.6-2.6V14.4zm9.2.025l-3.2-3.175l1.425-1.425l3.175 3.2z");
}

</style>
