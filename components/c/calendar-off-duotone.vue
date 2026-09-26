<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hso6gpkjb"/><path class="rzalgfbro"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.hso6gpkjb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 10H7C6.44772 10 6 10.4477 6 11C6 11.5523 6.44772 12 7 12H11C11.2761 12 11.5261 11.888 11.707 11.707L20.8281 20.8281C20.1043 21.552 19.1046 22 18 22H6C3.7909 22 2 20.2091 2 18V8C2 6.3778 2.96572 4.98112 4.35352 4.35352L10 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rzalgfbro {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 4C20.2091 4 22 5.7909 22 8V15.3428C22 15.7472 21.7564 16.1117 21.3828 16.2666C21.0092 16.4214 20.579 16.3366 20.293 16.0508L9.94922 5.70703C9.66344 5.42103 9.57865 4.99077 9.7334 4.61719C9.88825 4.24362 10.2528 4 10.6572 4H18Z");
  stroke: none;
}

</style>
