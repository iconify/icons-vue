<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jmw47lbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-area-20-regular" /></template>
<style>
.jmw47lbeg {
  fill: currentColor;
  d: path("M2.5 2a.5.5 0 0 1 .5.5v6.23l3.797-1.687a.5.5 0 0 1 .451.023l3.205 1.831l4.735-3.787A.5.5 0 0 1 16 5.5V17h1.5a.5.5 0 0 1 0 1h-13A2.5 2.5 0 0 1 2 15.5v-13a.5.5 0 0 1 .5-.5M15 17V6.54l-4.188 3.35a.5.5 0 0 1-.56.044L6.972 8.06L3 9.825V15.5A1.5 1.5 0 0 0 4.5 17z");
}

</style>
