<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egyr2vbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-off-24-filled" /></template>
<style>
.egyr2vbwt {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-8.275-8.274l-2.521 5.892a1 1 0 0 1-1.878-.677l.039-.11l2.837-6.629l-3.245-3.245L4.414 12l3.293 3.293a1 1 0 0 1-1.32 1.497l-.094-.083l-4-4a1 1 0 0 1-.084-1.32l.084-.094l3.97-3.97L2.22 3.28a.75.75 0 0 1 0-1.06m14.072 5.072a1 1 0 0 1 1.32-.083l.094.083l4.001 4.001a1 1 0 0 1 .083 1.32l-.084.095l-2.911 2.905L17.38 14.2l2.205-2.2l-3.293-3.294a1 1 0 0 1 0-1.414M14.08 4.606a1 1 0 0 1 1.879.678l-.04.11l-2.202 5.142l-1.524-1.523z");
}

</style>
