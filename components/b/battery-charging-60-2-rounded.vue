<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddbolv0nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-60-2-rounded" /></template>
<style>
.ddbolv0nj {
  fill: currentColor;
  d: path("M3.308 16.5q-.348 0-.578-.23t-.23-.578V8.308q0-.348.23-.578t.578-.23h11.238q.214 0 .357.143q.143.144.143.357t-.143.357t-.357.143H10.5v7h3.556q.213 0 .357.143t.143.357t-.143.357t-.357.143zm14.663-3.712h-2.19q-.248 0-.367-.207t.024-.42l2.196-3.39q.087-.13.22-.175q.134-.044.265.006t.212.171q.08.121.05.283l-.352 2.155h2.19q.248 0 .366.208t-.024.42l-2.196 3.39q-.086.13-.22.175t-.264-.006t-.212-.171q-.08-.121-.05-.283z");
}

</style>
