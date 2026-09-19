<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="n057jqi-c"/><path class="tlytpz1ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digical" /></template>
<style>
.n057jqi-c {
  width: 39px;
  height: 27.368px;
  x: 4.5px;
  y: 10.316px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.tlytpz1ft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.267 14.639h5.131m-5.131 6.251h5.131m-5.131 6.251h5.131m-5.131 6.251h5.131m3.266-12.502h5.132m-5.132 6.251h5.132m-5.132 6.251h5.132m3.265-12.502h5.132m-13.529-6.251h5.132m3.265 0h5.132m-5.132 12.502h5.132M8.823 20.89h5.131m-5.131 6.251h5.131m-5.131 6.251h5.131");
}

</style>
