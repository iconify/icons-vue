<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x3a78gl7n"/><path class="msw8e_b6b"/><path class="vjb_b7bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-public" /></template>
<style>
.msw8e_b6b {
  d: path("M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjb_b7bja {
  d: path("M16.5 18a1.5 3.5 0 1 0 3 0a1.5 3.5 0 1 0-3 0Zm-2 0h7");
}

.x3a78gl7n {
  d: path("M11.7 19H2.5V3h18v9.2M2.5 9h18m-10 0v10");
}

</style>
