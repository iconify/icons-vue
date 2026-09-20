<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><g transform="translate(3 3)"><rect class="xwhj4xbwf"/><path class="yyulwlb7u"/><path clip-rule="evenodd" class="yhxyf4f2m"/></g><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:battery-circle" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
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
