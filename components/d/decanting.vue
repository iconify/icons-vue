<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1me_cuni"/><path class="nafmd3bkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decanting" /></template>
<style>
.nafmd3bkn {
  d: path("M12.25 9.75q1.75.5 1.75 2.75v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1me_cuni {
  d: path("m12.75 8.25l-3-1l-4.5-4.75l-3 8.5L9 10.25l2.75 1ZM11.25 14v1.75L7 21.5h14l-4.25-5.75V14");
}

</style>
