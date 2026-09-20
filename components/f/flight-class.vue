<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtrhc3bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flight-class" /></template>
<style>
.rtrhc3bno {
  fill: currentColor;
  d: path("M14.077 12q-.613 0-1.037-.434q-.424-.433-.424-1.066v-4q0-.633.424-1.066T14.077 5h1.558q.594 0 .98.434Q17 5.867 17 6.5v4q0 .633-.385 1.066q-.386.434-.98.434zM9.5 17q-.387 0-.69-.224q-.304-.224-.427-.585L6 8.058V5h1v3l2.385 8H17v1zm-1.096 3v-1h8.577v1z");
}

</style>
