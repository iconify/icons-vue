<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lemq9vb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inbox-zero" /></template>
<style>
.lemq9vb_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.75h4.4l1.1 2.2c.25.5.75.8 1.3.8h4.9c.55 0 1.05-.3 1.3-.8l1.1-2.2h4.4v3a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Zm0 0l1.6-4.5A2 2 0 0 1 6.25 9h1m14 5.75l-1.6-4.5A2 2 0 0 0 17.75 9h-1M12 2.75q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4m6 0q.21 1.54 1.75 1.75q-1.54.21-1.75 1.75q-.21-1.54-1.75-1.75q1.54-.21 1.75-1.75");
}

</style>
