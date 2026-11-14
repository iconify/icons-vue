<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea1nlib4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-copyright" /></template>
<style>
.ea1nlib4j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m7.539 12.24q-2.153.125-3.722-1.355T7 12t1.569-3.637t3.722-1.355t3.54 1.778q.047.056.083.121q.035.065.057.135t.031.144t.001.147q-.006.074-.027.145t-.055.136t-.08.123t-.103.106q-.114.095-.256.14t-.291.032t-.281-.082t-.229-.183q-.97-1.156-2.477-1.244t-2.605.948T8.5 12t1.099 2.546q1.098 1.036 2.605.948t2.477-1.244q.048-.057.106-.103t.123-.08t.136-.055t.145-.027t.147.001q.073.009.144.031t.135.057t.121.083t.103.106t.08.123t.055.136t.027.145q.007.073-.001.147q-.009.073-.031.144t-.057.135t-.083.121q-1.387 1.652-3.54 1.778");
}

</style>
