<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yy8jtxbtv"/><path clip-rule="evenodd" class="a72483bhe"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:down-left-off" /></template>
<style>
.a72483bhe {
  fill-rule: evenodd;
  d: path("M12.75 11c.595 0 1.166-.238 1.588-.663A2.28 2.28 0 0 0 15 8.727V3a1 1 0 1 1 2 0v5.727a4.3 4.3 0 0 1-1.242 3.02A4.24 4.24 0 0 1 12.75 13H3a1 1 0 1 1 0-2z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.yy8jtxbtv {
  fill-rule: evenodd;
  d: path("M7.707 16.707a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 1.414L4.414 12l3.293 3.293a1 1 0 0 1 0 1.414");
}

</style>
