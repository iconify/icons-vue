<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nlmmeubzn"/><path class="hwkylkb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:falling-rocks-sharp" /></template>
<style>
.hwkylkb3y {
  d: path("m7.79 5.63l.38-.24l.67-.43l.74.31l.41.17l.74.31l-.13.79l-.07.4l-.14.79l-.75.25l-.69.23l-.75.26l-.33-.73l-.42-.94l-.33-.73zm4.9 5.14l.33-.21l.59-.38l.65.27l.36.15l.65.28l-.12.68l-.06.35l-.12.69l-.66.23l-.6.2l-.66.23l-.29-.64l-.37-.83l-.28-.64zm4.59 4.59l.31-.2l.53-.34l.59.24l.34.14l.59.25l-.11.63l-.06.32l-.11.63l-.6.21l-.55.18l-.6.21l-.26-.59l-.34-.75l-.26-.59z");
}

.nlmmeubzn {
  d: path("M4 3v18h16");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
