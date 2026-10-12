<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydfln3s_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dawn-sharp" /></template>
<style>
.ydfln3s_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V17.5c2.75-2.5 5.5-3.75 8.75-3.75s6.75 1.5 9.75 4.25v3.25Zm8.73-9.78a3.75 3.75 0 0 1 7.2 2M10.24 10l-1.3-.75m3.31-1.26l-.75-1.3m3.5.56v-1.5m2.75 2.24l.75-1.3M19.76 10l1.3-.75");
}

</style>
