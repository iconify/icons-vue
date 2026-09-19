<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aekecsb9z"/><path class="bjwpj7bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:codeberg" /></template>
<style>
.aekecsb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.125 2.5 2.5 12.126 2.5 24a21.5 21.5 0 0 0 3.283 11.418l17.925-23.174c.129-.167.454-.167.582 0L42.216 35.42A21.5 21.5 0 0 0 45.5 24c0-11.874-9.625-21.5-21.5-21.5");
}

.bjwpj7bsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.404 12.535c-.104 0-.187.064-.185.141q0 .013.003.025l8.282 31.044a21.5 21.5 0 0 0 9.712-8.326L24.567 12.604a.2.2 0 0 0-.163-.07");
}

</style>
