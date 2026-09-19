<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o4u_27btr"/><path class="a9o3v297a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-satellite-antenna" /></template>
<style>
.a9o3v297a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.081 20.746h3.288a2.437 2.437 0 0 0 .103-4.874l-3.414-.02");
}

.o4u_27btr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.116 30.473c6.73 0 12.185-5.456 12.185-12.187S28.845 6.098 22.116 6.098zM9.665 19.551H6.101s-.601.018-.601-1.243s.601-1.244.601-1.244h3.564zm24.686 22.351l2.36-17.714h2.638L36.99 41.902M9.665 18.286h12.45m-12.45 0l12.45-12.188M9.665 18.286l12.45 12.187m5.281 11.429H42.5");
}

</style>
