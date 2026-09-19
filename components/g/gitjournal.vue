<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="trfuu7bby"/><path class="zb-dovbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gitjournal" /></template>
<style>
.trfuu7bby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.05 22.912L25.088 4.95a1.54 1.54 0 0 0-2.177 0L4.95 22.91a1.54 1.54 0 0 0 0 2.177L22.91 43.05a1.54 1.54 0 0 0 2.177 0L43.05 25.09a1.54 1.54 0 0 0 0-2.177");
}

.zb-dovbsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.988 20.94a1.797 1.797 0 1 1 1.8-1.797h0a1.8 1.8 0 0 1-1.8 1.797m0 15.486a1.797 1.797 0 1 1 1.8-1.798h0a1.8 1.8 0 0 1-1.8 1.798m8.972-5.662a1.797 1.797 0 1 1 1.8-1.798a1.8 1.8 0 0 1-1.8 1.797M18.251 14.932l3.231 3.227m2.491 2.489l6.712 6.704m-7.697-6.154v11.288");
}

</style>
