<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5ks59b2s"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hummer" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.t5ks59b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 24h3.182m0-1.876v3.752M8.5 22.123v3.753m5.027-3.752v2.862c0 .492.399.89.89.89h1.435a.89.89 0 0 0 .891-.89v-2.862m1.845 3.752v-3.753l2.317 3.753l2.317-3.753v3.753m1.845 0v-3.753l2.317 3.753l2.317-3.753v3.753m4.643-1.884h-2.799m2.799 1.885h-2.799v-3.753h2.799m5.156 3.753L37.789 24m-1.6 1.876v-3.753h2.308c.492 0 .892.399.893.891v.094a.89.89 0 0 1-.888.891h-2.314");
}

</style>
