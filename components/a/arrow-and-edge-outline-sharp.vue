<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgmk3mbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-and-edge-outline-sharp" /></template>
<style>
.fgmk3mbfs {
  fill: currentColor;
  d: path("m12 20.02l-3.289-3.29l.689-.707l2.1 2.094v-5.04q0-.921-.655-1.576t-1.576-.655H2.231V4h1v5.846h6.038q.881 0 1.598.42T12 11.39q.416-.702 1.133-1.123q.717-.42 1.598-.42h6.038V4h1v6.846h-7.038q-.921 0-1.576.655t-.655 1.576v5.021l2.094-2.075l.695.708z");
}

</style>
