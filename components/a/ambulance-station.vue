<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lw4gphb1q"/><path class="lecftlb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ambulance-station" /></template>
<style>
.lecftlb5j {
  d: path("M6.5 20.5v-5h11v5M12 8.25v4.5M9.75 10.5h4.5");
}

.lw4gphb1q {
  d: path("M2.5 20.5v-12L12 4l9.5 4.5v12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
