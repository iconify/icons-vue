<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="zreh_jbxm"/><ellipse class="ueqq13bxa"/><ellipse transform="rotate(-85.42 37.039 17.585)" class="scovbbcpb"/><ellipse transform="rotate(-4.58 10.961 17.584)" class="uuqfk4bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fur-affinity-noc" /></template>
<style>
.scovbbcpb {
  cx: 37.039px;
  cy: 17.585px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.066px;
  ry: 5.449px;
}

.ueqq13bxa {
  cx: 23.915px;
  cy: 13.861px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.449px;
  ry: 7.447px;
}

.uuqfk4bwi {
  cx: 10.961px;
  cy: 17.585px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.449px;
  ry: 7.066px;
}

.zreh_jbxm {
  cx: 23.915px;
  cy: 32.457px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.464px;
  ry: 9.129px;
}

</style>
