<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oignfwbku"/><circle class="wt2dqolnd"/><circle class="eak9nub1a"/><path class="ltui5cb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ankiconnect-android" /></template>
<style>
.eak9nub1a {
  cx: 29.222px;
  cy: 16.268px;
  r: 1.623px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ltui5cb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.639 9.158L34.297 5.5M17.361 9.158L13.703 5.5");
}

.oignfwbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.082 7.447c6.97.045 12.584 5.732 12.538 12.702v9.649c0 7.015-5.687 12.702-12.702 12.702c-6.97-.045-12.583-5.732-12.538-12.702v-9.649c0-7.015 5.687-12.702 12.702-12.702q0 0 0 0M11.38 22.296h25.24");
}

.wt2dqolnd {
  cx: 18.778px;
  cy: 16.268px;
  r: 1.623px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
