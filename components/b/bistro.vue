<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="y75buu0hs"/><circle class="emzsrvbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bistro" /></template>
<style>
.emzsrvbar {
  cx: 18.609px;
  cy: 19.434px;
  r: 0.75px;
  fill: currentColor;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.y75buu0hs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.172 21.913l-.945 5.361m2.183-.452c.315.31.689.452 1.584.452h.454c.739 0 1.444-.6 1.574-1.34h0c.13-.74-.362-1.34-1.1-1.34h-.909c-.738 0-1.231-.6-1.1-1.341h0c.13-.74.834-1.34 1.573-1.34h.454c.896 0 1.27.142 1.584.452m3.216-2.121l-1.062 6.018c-.098.559.275 1.012.833 1.012h.304m-1.432-5.361h2.125m-15.729 2.023c.196-1.118 1.262-2.023 2.38-2.023h0c1.117 0 1.863.905 1.666 2.023l-.232 1.315c-.197 1.117-1.263 2.023-2.38 2.023h0c-1.117 0-1.863-.906-1.666-2.023m-.357 2.023l1.427-8.093m20.115 4.755c.197-1.118 1.263-2.023 2.38-2.023s1.864.905 1.667 2.023l-.232 1.315c-.197 1.117-1.263 2.023-2.38 2.023s-1.864-.906-1.667-2.023zm-3.412 0c.197-1.118 1.263-2.023 2.38-2.023h0m-2.023 0l-.945 5.361");
}

</style>
