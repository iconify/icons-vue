<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvhnnxb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:docking" /></template>
<style>
.yvhnnxb0v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.404 3.404Q1.5 5.308 1.5 8t1.904 4.596T8 14.5q.901 0 1.713-.213Q9.5 15.099 9.5 16q0 2.692 1.904 4.596T16 22.5t4.596-1.904T22.5 16t-1.904-4.596T16 9.5q-.901 0-1.713.213Q14.5 8.901 14.5 8q0-2.692-1.904-4.596T8 1.5T3.404 3.404M8 4.75q1.346 0 2.298.952T11.25 8t-.952 2.298T8 11.25q-3.25 0-3.25-3.25T8 4.75M12.75 16q0-3.25 3.25-3.25T19.25 16T16 19.25T12.75 16");
}

</style>
