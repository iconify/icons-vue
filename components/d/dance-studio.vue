<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ilvsz3bxn"/><path class="tmebgacce"/><path class="rcio_lb6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dance-studio" /></template>
<style>
.ilvsz3bxn {
  d: path("m3 10l9-7l9 7v11H3Z");
}

.rcio_lb6f {
  d: path("m8.5 11l3.5 1.75l3.5-2.25M12 12.75v2.75l-2.75 2.75M12 15.5l2.75 2.75");
}

.tmebgacce {
  fill: currentColor;
  d: path("M12.5 9.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
