<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="so-wx8b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goldenwestcu" /></template>
<style>
.so-wx8b0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.71 14.917v13.1l-5.016-12.11m-2.348.964l5.014 12.112l-9.286-9.287M9.28 21.492l9.29 9.29l-12.116-5.019m-.963 2.348l12.11 5.016H4.5m39 0H30.355l12.143-5.03m-.968-2.345l-12.14 5.026l9.289-9.288m-1.796-1.796l-9.292 9.293l5.03-12.143m-2.346-.969l-5.029 12.143V14.873");
}

</style>
