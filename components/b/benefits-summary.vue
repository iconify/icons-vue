<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2o23_b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:benefits-summary" /></template>
<style>
.i2o23_b9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13v6.5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V13Zm0 0l-1.25-2.25M20 13l1.25-2.25M12 13v8.5m-7.75-14a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 3.25l.735 1.739l1.88.161l-1.426 1.236l.427 1.839L12 7.25l-1.616.975l.427-1.839L9.385 5.15l1.88-.161Zm6.75 6.25l-2-2a1.25 1.25 0 0 1 2-1.5a1.25 1.25 0 0 1 2 1.5Z");
}

</style>
