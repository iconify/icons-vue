<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cn9lfwb1r"/><path class="p_dm2tzcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dependency" /></template>
<style>
.cn9lfwb1r {
  d: path("M2.5 3H12v6H2.5ZM12 15h9.5v6H12ZM7.25 9v9H12");
}

.p_dm2tzcb {
  d: path("m10 16l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
