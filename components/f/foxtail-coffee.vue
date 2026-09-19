<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w1nu9b2sm"/><path class="u209hwb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foxtail-coffee" /></template>
<style>
.u209hwb5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.325 23.9c1.332-.357 10.88-.214 11.252 0");
}

.w1nu9b2sm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 30.219c0 3.227 3.092 11.103 12.053 5.93c8.961-5.174 11.199-22.482 23.668-25.823c6.024-1.614 3.765 7.603-6.826 3.863c-2.027-.715-4.594-1.81-6.648-2.69c-4.844-2.075-15.74-2.94-15.74 7.221");
}

</style>
