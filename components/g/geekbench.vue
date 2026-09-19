<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cisovnylv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geekbench" /></template>
<style>
.cisovnylv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.835 10.629h4.457v26.743h-4.457zm-7.8 4.795h4.457v21.947h-4.457zm-14.527-4.795h4.457v26.743h-4.457zm-7.8 9.763h4.457v16.98H6.708zm34.584 12.934H43.5m-10.008 0h3.343m-17.87 0h10.07m-17.87 0h3.343m-10.008 0h2.208M41.292 13.56H43.5m-24.535 0h17.87m-32.335 0h10.008m26.784 9.883H43.5m-10.008 0h3.343m-17.87 0h10.07m-17.87 0h3.343m-10.008 0h2.208");
}

</style>
