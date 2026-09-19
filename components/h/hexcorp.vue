<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ua6oyab4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hexcorp" /></template>
<style>
.ua6oyab4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.616 5.5L7.535 11.356v22.413L24 40.692l13.08-5.856V15.654L32.816 24H15.184l-4.264 8.346V13.165L24 7.308l16.465 6.923v22.413L27.384 42.5");
}

</style>
