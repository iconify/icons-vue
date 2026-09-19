<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="hhnhx3b8m"/><path class="oifa08eet"/></g><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biquge" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.hhnhx3b8m {
  d: path("M19.15 16.412c-.931 1.283-1.795 2.488-3.15 3.365m2.134-2.009h5.365m-3.953.001c.528.57.998 1.19 1.368 1.926m5.731-3.196c-.879 1.318-1.694 2.556-3.013 3.486m2.144-2.217H32m-5.193.001c.527.57.997 1.19 1.368 1.926m-10.829 2.528c3.954-.243 7.103-.909 10.437-1.921");
}

.oifa08eet {
  d: path("M31.2 29.478v.903c0 1.054-.865 1.207-1.86 1.207h-5.163a.966.966 0 0 1-.969-.967v-9.152m-5.818 2.918h12.756M16.04 27.289h15.907");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
