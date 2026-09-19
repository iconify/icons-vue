<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5w1skb8f"/><path class="u7mf3ghwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atom-store" /></template>
<style>
.g5w1skb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.5l-9.25 9.25L24 24l-9.25 9.25L24 42.5L42.5 24z");
}

.u7mf3ghwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 5.5L5.5 14.75L14.75 24L5.5 33.25l9.25 9.25L33.25 24zm0 18.5l4.625 4.625");
}

</style>
