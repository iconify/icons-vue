<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5rmalbpi"/><path class="kh-0nbiwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bollard-retractable" /></template>
<style>
.k5rmalbpi {
  d: path("M2.5 17h4v4.5h11V17h4");
}

.kh-0nbiwy {
  d: path("M9.25 18.75V12a2.75 2.75 0 0 1 5.5 0v6.75M12 2.5v4M9.25 3.75L12 6.5l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
