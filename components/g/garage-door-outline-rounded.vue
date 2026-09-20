<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk9hmpgqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-door-outline-rounded" /></template>
<style>
.zk9hmpgqy {
  fill: currentColor;
  d: path("M8.212 17.404V9.712h7.576v8.307v-8.307H8.212v8.307zm-1.597 1.615q-.666 0-1.14-.474T5 17.404V9.75h-.533q-.292 0-.378-.273t.136-.454l6.792-5.192q.449-.337.983-.337t.983.337l6.748 5.173q.223.18.136.454q-.086.273-.378.273L19 9.75v7.654q0 .666-.475 1.14t-1.14.475zM6 8.946v8.458q0 .269.173.442t.443.173h1.596v-7.5q0-.343.232-.575t.575-.233h5.962q.343 0 .575.233t.233.575v7.5h1.596q.269 0 .442-.173t.173-.442V8.946l-5.615-4.33Q12.212 4.48 12 4.48t-.385.134zm3.096 9.073h5.808v-1.903H9.096zm0-2.788h5.808v-1.885H9.096zm0-2.77h5.808v-1.865H9.096zm2.913-4.48q.3 0 .511-.21q.21-.21.21-.52t-.21-.521t-.52-.21q-.29 0-.51.21q-.22.209-.22.52t.22.52t.52.21");
}

</style>
