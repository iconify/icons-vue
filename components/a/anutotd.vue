<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pp47lfbpe"/><path class="iw7np6_ep"/><path class="tzzae821f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anutotd" /></template>
<style>
.iw7np6_ep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.317 17.266a10.71 10.71 0 0 0-6.976 10.077C13.341 33.253 18.09 38 24 38s10.657-4.747 10.657-10.657c.097-4.651-2.81-8.72-7.072-10.173h0");
}

.pp47lfbpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m-18.182 8.666h7.267");
}

.tzzae821f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.317 10h7.266v21.702h-7.266z");
}

</style>
