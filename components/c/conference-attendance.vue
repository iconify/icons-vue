<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ewi34-80q"/><path class="fg8wk1b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conference-attendance" /></template>
<style>
.ewi34-80q {
  d: path("M3 5.5h18V10a2 2 0 0 0 0 4v4.5H3V14a2 2 0 0 0 0-4ZM7 16l1.75-8");
}

.fg8wk1b3h {
  d: path("m8.75 8l7.5 2.25l-8 .25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
