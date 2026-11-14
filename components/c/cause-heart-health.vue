<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mz_fhvbca"/><path class="f_6luopvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cause-heart-health" /></template>
<style>
.f_6luopvj {
  d: path("M7 12h2l1.5-3l2.5 6l1.5-3H17");
}

.mz_fhvbca {
  d: path("M12 20.5c-5-4-9-7-9-11.5c0-3 2.25-5 4.75-5c2 0 3.5 1 4.25 2.5C12.75 5 14.25 4 16.25 4C18.75 4 21 6 21 9c0 4.5-4 7.5-9 11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
