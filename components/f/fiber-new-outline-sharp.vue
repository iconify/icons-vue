<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7vyc2-jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fiber-new-outline-sharp" /></template>
<style>
.s7vyc2-jc {
  fill: currentColor;
  d: path("M2 19V5h20v14zm1-1h18V6H3zm.885-3.308h.827v-4l2.704 4h.853V9.308h-.827v4l-2.654-4h-.904zm5.923 0h3.384v-.827h-2.5v-1.407h2.5v-.827h-2.5v-1.497h2.5v-.826H9.808zm4.923 0h5.385V9.308h-.827v4.5h-1.447v-3.5h-.826v3.5h-1.458v-4.5h-.827zM3 18V6z");
}

</style>
