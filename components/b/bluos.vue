<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="a3-25dzdw"/><path class="tmn7d5txh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bluos" /></template>
<style>
.a3-25dzdw {
  d: path("M7.771 42.499h21.231s10.993.406 11.253-12.386c.261-12.848-11.253-12.312-11.253-12.312l-15.475.044c-5.144-.135-5.729-3.555-5.747-5.178c-.032-2.806-.055-3.254-.025-7.167");
}

.tmn7d5txh {
  d: path("M7.771 5.501h21.231s10.993-.405 11.253 12.386c.261 12.848-11.253 12.312-11.253 12.312l-15.475-.044c-5.144.135-5.729 3.556-5.747 5.178c-.032 2.806-.055 3.254-.025 7.167");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
