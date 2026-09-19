<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hizdxibal"/><path class="w-nhws_tr"/><path class="cbtu5acvz"/><path class="h59n5gc2n"/><path class="aeo_0boen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-mouth" /></template>
<style>
.aeo_0boen {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.995 26.015c-5.055 0-6.455-3.234-9.143-2.83c4.46-3.36 6.91-.405 9.143-.405s4.687-2.956 9.144.405c-2.69-.405-4.09 2.83-9.144 2.83");
}

.cbtu5acvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 23.071l9.908 9.469c1.668 1.617 3.842 2.98 8.592 2.98s6.924-1.364 8.592-2.981L42.5 23.07");
}

.h59n5gc2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.071c3.007-1.954 6.57-6.122 10.34-9.436c.876-.77 1.928-1.693 3.857-.77l2.54 1.351c.585.339.785.455 1.756.455s1.17-.116 1.756-.455l2.54-1.351c1.927-.923 2.98 0 3.857.77c3.773 3.31 7.336 7.476 10.34 9.436m.003 0c-3.31 1.103-4.157 1.255-9.35.118");
}

.hizdxibal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.071c3.31 1.103 4.157 1.255 9.35.118m27.639-.118c-3.31 1.103-4.157 1.255-9.35.118");
}

.w-nhws_tr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.071c3.31 1.103 4.157 1.255 9.35.118");
}

</style>
