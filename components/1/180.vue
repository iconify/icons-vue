<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3o-lxbgs"/><path class="tl-lux_id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:180" /></template>
<style>
.q3o-lxbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-29 13.417l3.492-1.902m0 0v13.97");
}

.tl-lux_id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.245 26.357a4.627 4.627 0 1 0 9.255 0v-4.714a4.627 4.627 0 1 0-9.255 0zM20.106 24a3.492 3.492 0 1 0 0 6.985h2.27a3.492 3.492 0 1 0 0-6.985m0 0a3.492 3.492 0 1 0 0-6.985h-2.27a3.492 3.492 0 1 0 0 6.985m0 0h2.27");
}

</style>
