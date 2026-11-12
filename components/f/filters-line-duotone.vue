<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="worxp0b1t"/><path class="k8_yxdbyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filters-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8_yxdbyl {
  d: path("M12 20.4722C13.0615 21.4223 14.4633 22 16.0001 22C19.3138 22 22.0001 19.3138 22.0001 16C22.0001 13.2331 20.1271 10.9036 17.5799 10.2102");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.worxp0b1t {
  d: path("M6.42018 10.2101C3.87294 10.9035 2 13.233 2 15.9999C2 19.3136 4.68629 21.9999 8 21.9999C11.3137 21.9999 14 19.3136 14 15.9999C14 15.2194 13.851 14.4737 13.5798 13.7898M18 8C18 11.3137 15.3137 14 12 14C8.68629 14 6 11.3137 6 8C6 4.68629 8.68629 2 12 2C15.3137 2 18 4.68629 18 8Z");
}

</style>
