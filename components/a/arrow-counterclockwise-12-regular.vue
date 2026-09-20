<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="auzc5ej5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-12-regular" /></template>
<style>
.auzc5ej5z {
  fill: currentColor;
  d: path("M2 2.5a.5.5 0 0 1 1 0v.854a4 4 0 1 1-.963 3.19c-.04-.298.207-.544.508-.544c.251 0 .451.205.489.453A3 3 0 1 0 3.764 4H4.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5z");
}

</style>
