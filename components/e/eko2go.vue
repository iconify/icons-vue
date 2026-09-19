<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnu1yjlvv"/><path class="ix9hd9cqb"/><rect class="h0stgsbtn"/><path class="w86d-_yqd"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eko2go" /></template>
<style>
.cnu1yjlvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.106 30.704c.257-1.456 1.778-2.604 3.235-2.314c.955.19 1.595 1.046 1.516 2.048c-.058.746-.424 1.482-1.019 1.934c-1.101.837-4.572 3.094-4.572 3.094h4.718m6.216-4.718l-.94 5.341c-.174.983-1.112 1.78-2.095 1.78h0c-.492 0-.901-.199-1.167-.521");
}

.h0stgsbtn {
  width: 7.769px;
  height: 11.726px;
  x: 28.732px;
  y: 14.131px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.884px;
  ry: 3.884px;
}

.ix9hd9cqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.42 30.748c.984 0 1.64.797 1.467 1.78l-.204 1.158c-.173.983-1.11 1.78-2.094 1.78h0c-.983 0-1.64-.797-1.466-1.78l.203-1.157c.174-.984 1.111-1.78 2.095-1.78m3.491 1.78c.173-.984 1.11-1.78 2.094-1.78s1.64.796 1.466 1.78l-.204 1.157c-.173.983-1.11 1.78-2.094 1.78s-1.64-.797-1.466-1.78z");
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

.w86d-_yqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.266 14.131v11.726m0-4.084l6.303-7.603m0 11.687l-4.828-5.863m-10.241 0h3.823m2.04 5.863H11.5V14.131h5.863");
}

</style>
