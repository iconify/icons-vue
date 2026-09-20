<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="hcyd3la0t"/><circle class="xf8l25g4i"/><path class="o9me9cbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foundit-monster" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.hcyd3la0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.933 22.942v3.247a1.968 1.968 0 0 0 3.935 0v-3.247m0 3.247v1.967");
}

.o9me9cbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.701 22.942v5.214m3.02-6.836v5.853c0 .543.44.983.984.983H40m-2.312-5.214h2.066m-12.121 5.214V24.91a1.968 1.968 0 0 0-3.935 0m0 3.246v-5.214m9.787 1.968a1.968 1.968 0 0 0-3.935 0v1.279a1.968 1.968 0 0 0 3.935 0m0 1.967v-7.87m-24.318 7.87v-6.492c0-.761.616-1.378 1.377-1.378c.678 0 1.1.2 1.391.576M8 22.942h2.755m1.317 1.968a1.968 1.968 0 0 1 3.935 0v1.279a1.968 1.968 0 0 1-3.935 0z");
}

.xf8l25g4i {
  cx: 35.701px;
  cy: 20.532px;
  r: 0.75px;
  fill: currentColor;
}

</style>
