<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g2t02fb2p"/><path class="jgpb9818a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jurisdiction" /></template>
<style>
.g2t02fb2p {
  d: path("m3 6l6-2l6 2l6-2v14l-6 2l-6-2l-6 2Z");
}

.jgpb9818a {
  d: path("M12 7.5a4.5 4.5 0 0 1 4.432 3.719m-.535 3.031a4.5 4.5 0 0 1-5.436 1.979M8.103 14.25a4.5 4.5 0 0 1 1.004-5.697");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
