<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="wv99g7doe"/><rect transform="rotate(-90 24 12.5)" class="ojrn9nbam"/><rect transform="rotate(-45 20.632 20.672)" class="bs2rlsbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:feeld" /></template>
<style>
.bs2rlsbfn {
  width: 14px;
  height: 37px;
  x: 13.632px;
  y: 2.172px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7px;
}

.ojrn9nbam {
  width: 14px;
  height: 37px;
  x: 17px;
  y: -6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7px;
}

.wv99g7doe {
  width: 14px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7px;
}

</style>
