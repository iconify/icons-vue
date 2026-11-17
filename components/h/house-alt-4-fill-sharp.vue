<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2cxu0qwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-4-fill-sharp" /></template>
<style>
.a2cxu0qwk {
  fill: currentColor;
  d: path("m19.664 8.475l2 1.778a1 1 0 0 1 .334.688a1 1 0 0 1-.251.723l-.013.015a1 1 0 0 1-1.412.083L20 11.476V21a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-9.524l-.322.286a1 1 0 0 1-1.412-.083l-.013-.015a1 1 0 0 1 .083-1.411l1.999-1.778h.001l7-6.222a1 1 0 0 1 1.328 0Zm-4 2.444l-3-2.666a1 1 0 0 0-1.328 0l-3 2.666a1 1 0 0 0-.336.748V17a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-5.333a1 1 0 0 0-.336-.748");
}

</style>
