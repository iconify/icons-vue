<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="xwhj4xbwf"/><path class="yyulwlb7u"/><path clip-rule="evenodd" class="yhxyf4f2m"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:battery-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.xwhj4xbwf {
  width: 2px;
  height: 5px;
  x: 17px;
  y: 7.5px;
  rx: 0.5px;
}

.yhxyf4f2m {
  fill-rule: evenodd;
  d: path("M14 4.5H4a3 3 0 0 0-3 3v5a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-5a3 3 0 0 0-3-3m-11 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

.yyulwlb7u {
  d: path("M4 7.5h3v5H4zm3.5 0h3v5h-3zm3.5 0h3v5h-3z");
}

</style>
