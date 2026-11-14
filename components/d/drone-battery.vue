<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6v_7kbuh"/><path class="cfjh0bb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-battery" /></template>
<style>
.cfjh0bb9c {
  d: path("m12 12.5l-2.25 2.25H13L10.75 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6v_7kbuh {
  d: path("M2.5 9.75H19v10H2.5Zm19.25 3.75V16M2.5 4.5a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0Zm10 0a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0ZM5.75 6v3.75m10-3.75v3.75");
}

</style>
