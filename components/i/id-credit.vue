<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="w3gw-ma3l"/><path class="mplgl_bzu"/><path class="sl6y_-bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:id-credit" /></template>
<style>
.mplgl_bzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.587 22.172l-.035 9.236m4.535-9.248l-.035 9.248m.035-9.248c-.895.086-4.969.612-6.437-.97m0 11.06c1.902-.842 6.402-.842 7.87-.145m5.182-15.302c7.501 2.332 10.387-.983 15.855-.81c6.312.2 9.664 2.67 9.793 8.484c-.13 5.814-3.481 8.284-9.793 8.484c-5.468.173-8.354-3.142-15.855-.81");
}

.sl6y_-bus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.886 16.073c5.15 1.75 4.862 7.315 4.862 8.404s.288 6.655-4.862 8.404M23.911 17.593v13.77M20.075 17.39v14.174");
}

.w3gw-ma3l {
  cx: 8.837px;
  cy: 17.282px;
  r: 2.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
