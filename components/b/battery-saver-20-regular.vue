<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w61fymbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-saver-20-regular" /></template>
<style>
.w61fymbdf {
  fill: currentColor;
  d: path("M4.18 4.273c.233-.364.778-.369.987.015C6.382 6.528 7 8.327 7 9.564c0 1.236-.578 2.274-1.14 2.764a1 1 0 0 1-.152.107l-.088.046a.352.352 0 0 1-.494-.389l.02-.07q.714-1.785.688-3.505a.586.586 0 0 0-.591-.58a.586.586 0 0 0-.574.562l.003.019q.007.435-.044.88l-.051.374l-.033.186l-.052.259l-.08.324l-.034.122q-.198.71-.53 1.44C3.253 13.404 2.23 14.36.805 14.955a.58.58 0 0 1-.762-.319a.59.59 0 0 1 .316-.77q1.123-.469 1.807-1.273C.874 12.181.122 11.281.018 10.026c-.116-1.421.414-2.382 1.757-3.463l.657-.508l.287-.228q.971-.793 1.46-1.554M16 5a3 3 0 0 1 3 3h1v4h-1a3 3 0 0 1-3 3H4a.5.5 0 0 1 0-1h12a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2H7.5a.5.5 0 0 1 0-1z");
}

</style>
