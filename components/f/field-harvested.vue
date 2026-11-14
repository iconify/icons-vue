<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ggc-6-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-harvested" /></template>
<style>
.q-ggc-6-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.3 19.5H2.5v-17h17v10.8M7 6v3m4-3v3m4-3v3m-8 3v3m4-3v3m3.75 3l2 2L21 15.75");
}

</style>
