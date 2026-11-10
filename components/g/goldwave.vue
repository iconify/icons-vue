<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihijmvb1c"/><path class="is2iwwlam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goldwave" /></template>
<style>
.ihijmvb1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 21.51l-5.808-5.808l-5.809 5.809H6.574L18.191 9.894L24 15.702l5.809-5.808L41.426 21.51h-5.809l-5.808-5.809zm0 4.98l-5.808 5.808l-5.809-5.809H6.574l11.617 11.617L24 32.298l5.809 5.808L41.426 26.49h-5.809l-5.808 5.809z");
}

.is2iwwlam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.16 26.49L3.5 24l2.66-2.49h35.68L44.5 24l-2.66 2.49z");
}

</style>
