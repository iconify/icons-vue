<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ez-awwbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fhcode" /></template>
<style>
.ez-awwbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 30.577V17.423h6.713M4.5 24h4.364m4.561-.025h8.895m0-6.552v13.154m-8.895-13.154v13.154m11.631-2.22L33.448 24l-8.392-4.357m10.053 10.934H43.5");
}

</style>
