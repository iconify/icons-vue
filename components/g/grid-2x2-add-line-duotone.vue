<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c8yuot4zz"/><path class="duo8u5b0b"/><path class="dpswkyzrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-add-line-duotone" /></template>
<style>
.c8yuot4zz {
  d: path("M14.5 17.5H17.5M17.5 17.5H20.5M17.5 17.5V14.5M17.5 17.5V20.5");
}

.dpswkyzrt {
  d: path("M12 22L12 11.9951M12 11.9951V2M12 11.9951H2.00488M12 11.9951H22.0048");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.duo8u5b0b {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
