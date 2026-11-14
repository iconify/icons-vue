<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="weez58bvj"/><path class="nl9flrb8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:find-a-doctor" /></template>
<style>
.nl9flrb8a {
  d: path("M9.25 5.5v2.25c0 1.5 1 2.5 2.25 2.5s2.25-1 2.25-2.5V5.5m-2.25 4.75V11c0 1 .75 1.75 1.75 1.75S15 12 15 11.25M14 10a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.weez58bvj {
  d: path("M12 21.5S4.5 15 4.5 9.5a7.5 7.5 0 0 1 15 0c0 5.5-7.5 12-7.5 12Z");
}

</style>
