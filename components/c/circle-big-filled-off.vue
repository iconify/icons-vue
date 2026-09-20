<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="l5r4gpbgv"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:circle-big-filled-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l5r4gpbgv {
  d: path("M19.5 10a9.5 9.5 0 1 1-19 0a9.5 9.5 0 0 1 19 0");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
