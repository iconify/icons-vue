<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vs2-kbchr"/><circle class="a6z_yfyfp"/><path class="b7jm274xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baidu-netdisk" /></template>
<style>
.a6z_yfyfp {
  cx: 26.441px;
  cy: 17.321px;
  r: 8.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.b7jm274xh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.14 35.639l11.161-12.117c3.288-3.568 12.447-1.495 12.447 5.863c0 9.826-8.692 13.045-15.019 4.747m-4.597-20.767c-2.054 1.236-3.8 2.713-2.62 6.675");
}

.vs2-kbchr {
  cx: 13.81px;
  cy: 29.904px;
  r: 9.307px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
