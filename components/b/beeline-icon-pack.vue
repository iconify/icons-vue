<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wnr5vod4a"/><path class="m3d8o2bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beeline-icon-pack" /></template>
<style>
.m3d8o2bdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.858 33.37l.866.866c2 2.001 5.275 2.001 7.275 0s2.001-5.274 0-7.275l-8.14-8.141m-15.081-8.348l-3.046-3.046m.41 25.944l-.866.866c-2 2.001-5.275 2.001-7.275 0S5 28.962 7 26.961l8.14-8.141");
}

.wnr5vod4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.902zc-4.872 0-8.858 3.986-8.858 8.858v17.857a2.43 2.43 0 0 0 1.261 2.13l6.428 3.527c.728.4 1.61.4 2.338 0l6.428-3.527a2.43 2.43 0 0 0 1.261-2.13V16.76c0-4.872-3.986-8.858-8.858-8.858m-8.858 15.899h17.716m-17.716 6.792h17.716m-2.636-20.121l3.046-3.046");
}

</style>
