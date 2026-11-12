<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tstvupbdo"/><path class="j86hmxb3c"/><path class="ni50aab4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checkerboard-line-duotone" /></template>
<style>
.j86hmxb3c {
  stroke-linecap: round;
  d: path("M12 2V12M12 12V22M12 12H2M12 12H22");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni50aab4d {
  stroke-linecap: round;
  d: path("M21.9949 14.0052L14.0053 21.9947M12.0001 18.5L18.5001 12M2.00537 9.99482L9.99487 2.00525M12.0001 5.49999L5.50012 12.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tstvupbdo {
  d: path("M12 22C7.286 22 4.9289 22 3.4645 20.5355C2 19.0711 2 16.714 2 12C2 7.286 2 4.9289 3.4645 3.4645C4.9289 2 7.286 2 12 2C16.714 2 19.0711 2 20.5355 3.4645C22 4.9289 22 7.286 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
