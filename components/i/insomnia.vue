<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eo59bjbyt"/><path class="lguiwbx2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insomnia" /></template>
<style>
.eo59bjbyt {
  d: path("M12.942 14.243A7 7 0 0 1 9.75 15C6.6 15 4 13 2.5 9.75C4 6.5 6.6 4.5 9.75 4.5s5.75 2 7.25 5.25a11 11 0 0 1-1.485 2.394");
}

.lguiwbx2p {
  d: path("M7.25 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12.25 5a3.5 3.5 0 1 0 1.75 4.5a2.75 2.75 0 0 1-1.75-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
