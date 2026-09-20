<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ga95htbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:luminor-latvia" /></template>
<style>
.ga95htbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.2 4.5l5.55 5.55l-5.55 5.549l-5.55-5.55zm5.548 39H12.252V10.527h7.01v25.766h16.486z");
}

</style>
