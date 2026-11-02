<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpaf18bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-donut-fill-round" /></template>
<style>
.xpaf18bqh {
  fill: currentColor;
  d: path("M11 2.049v7.122A3 3 0 1 0 14.829 13h7.122A10 10 0 1 1 11 2.049m2 7.122V2.049A10.01 10.01 0 0 1 21.951 11h-7.122A3.02 3.02 0 0 0 13 9.171");
}

</style>
