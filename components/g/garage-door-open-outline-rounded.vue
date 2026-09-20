<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpzm25bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-door-open-outline-rounded" /></template>
<style>
.gpzm25bwu {
  fill: currentColor;
  d: path("M8.212 17.404V9.712h7.576v8.307v-8.307H8.212v8.307zM6 8.946v8.458q0 .269.173.442t.443.173h1.596v-7.5q0-.343.232-.575t.575-.233h5.962q.343 0 .575.233t.233.575v7.5h1.596q.269 0 .442-.173t.173-.442V8.946l-5.615-4.33Q12.212 4.48 12 4.48t-.385.134zm3.096 3.516h5.808v-1.866H9.096zM12.01 7.98q.3 0 .511-.21q.21-.21.21-.52t-.21-.521t-.52-.21q-.29 0-.51.21q-.22.209-.22.52t.22.52t.52.21M6.615 19.02q-.667 0-1.141-.475T5 17.404V9.75h-.513q-.283 0-.384-.273t.122-.454l6.792-5.192q.449-.337.983-.337t.983.337l6.792 5.192q.223.18.122.454q-.1.273-.383.273H19v7.654q0 .666-.475 1.14t-1.14.475h-1.667q-.354 0-.584-.232t-.23-.575v-4.866H9.096v4.866q0 .343-.232.575t-.576.232z");
}

</style>
