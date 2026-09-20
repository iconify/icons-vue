<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtkd9ebnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flashlight-off-sharp" /></template>
<style>
.mtkd9ebnn {
  fill: currentColor;
  d: path("M8 22V10.8L1.4 4.2l1.4-1.4l18.4 18.4l-1.4 1.4l-3.8-3.8V22zM6 3.15V2h12v3H7.85zm10 10L9.85 7H18v1l-2 3z");
}

</style>
