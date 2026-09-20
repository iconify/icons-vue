<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="go-czmuvt"/><path class="cjhzy1raw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hatena-blog" /></template>
<style>
.cjhzy1raw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.924 38.645a15.5 15.5 0 0 0 10.152 0L30.5 19c-2.668-2.668-5.133-7.266-6-10.5h-1c-.867 3.234-3.332 7.832-6 10.5zM24 23V8.5");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.go-czmuvt {
  cx: 24px;
  cy: 24px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
