<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf4adxg1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-sharp" /></template>
<style>
.zf4adxg1q {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm4-8h8v-2H6zm0-3h12V9H6zm0-3h12V6H6z");
}

</style>
