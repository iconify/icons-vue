<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu7iy7bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:low-poly" /></template>
<style>
.yu7iy7bxy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.624 6.6l-8.25-4.75q-.085-.049-.18-.075T12 1.75t-.194.025q-.095.026-.18.075L3.376 6.6q.174-.1.374-.1h16.5q.2 0 .374.1m.376.65q0 .201-.101.376l-8.25 14.25q-.101.174-.275.274l8.25-4.75q.086-.049.156-.119t.119-.156q.05-.085.075-.181q.026-.095.026-.194zm-9.376 14.899q-.173-.1-.273-.273l-8.25-14.25Q3 7.452 3 7.25v9.5q0 .099.026.194q.025.096.075.181q.049.086.119.156t.156.119z");
}

</style>
