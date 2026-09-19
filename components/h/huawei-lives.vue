<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zcbrahbik"/><circle class="fucaczbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-lives" /></template>
<style>
.fucaczbxx {
  cx: 24px;
  cy: 23.944px;
  r: 6.075px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zcbrahbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.162 4.5l-1.605 6.03l2.877 32.97h21.132l2.877-32.97l-1.605-6.03Zm-5.864 6.583h35.404");
}

</style>
