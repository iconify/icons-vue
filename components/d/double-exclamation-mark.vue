<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ikm6qhd-m"/><ellipse class="f3fxo95gg"/><path class="u5j61ybjh"/><ellipse class="j8re6-bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:double-exclamation-mark" /></template>
<style>
.f3fxo95gg {
  cx: 17.999px;
  cy: 54.354px;
  fill: currentColor;
  rx: 7.663px;
  ry: 7.646px;
}

.ikm6qhd-m {
  fill: currentColor;
  d: path("M22.989 42.439H13.01L9 2h18z");
}

.j8re6-bct {
  cx: 45.999px;
  cy: 54.354px;
  fill: currentColor;
  rx: 7.663px;
  ry: 7.646px;
}

.u5j61ybjh {
  fill: currentColor;
  d: path("M50.989 42.439H41.01L37 2h18z");
}

</style>
