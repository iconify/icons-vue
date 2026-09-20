<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egnef3bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-double-arrow-right-outline-sharp" /></template>
<style>
.egnef3bkp {
  fill: currentColor;
  d: path("M10.537 12L5.942 7.4l.708-.708L11.958 12L6.65 17.308l-.708-.708zm6.1 0l-4.595-4.6l.708-.708L18.058 12l-5.308 5.308l-.708-.708z");
}

</style>
