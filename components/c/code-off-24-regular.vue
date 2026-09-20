<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcjr0w4qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-off-24-regular" /></template>
<style>
.hcjr0w4qi {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-8.482-8.48l-2.803 6.258a.75.75 0 0 1-1.405-.519l.035-.096l3.037-6.779l-3.728-3.728L3.811 12l3.72 3.72a.75.75 0 0 1-.977 1.134l-.084-.074l-4.25-4.25a.75.75 0 0 1-.074-.976l.074-.084l4.093-4.095L2.22 3.28a.75.75 0 0 1 0-1.06m14.25 4.999a.75.75 0 0 1 .976-.073l.084.073l4.25 4.25a.75.75 0 0 1 .072.976l-.072.084l-3.035 3.034l-1.06-1.06l2.505-2.504l-3.72-3.72a.75.75 0 0 1 0-1.06m-1.905-2.777a.75.75 0 0 1 1.405.519l-.035.096l-2.383 5.313l-1.135-1.136z");
}

</style>
