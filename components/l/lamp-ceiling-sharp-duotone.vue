<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="igcdd7obb"/><path clip-rule="evenodd" class="jd-k4pbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-ceiling-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.igcdd7obb {
  stroke-opacity: 0.4;
  d: path("M8 2H16M12 2V10M8 18C8 20.2091 9.791 22 12 22C14.209 22 16 20.2091 16 18");
}

.jd-k4pbbo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 19H4.001C3.448 19 3.001 18.5523 3.001 18C3.001 17.8448 3.037 17.6917 3.106 17.5528L7.106 9.5528C7.275 9.214 7.621 9 8 9H16C16.379 9 16.725 9.214 16.894 9.5528L20.894 17.5528C20.963 17.6917 20.999 17.8448 20.999 18C20.999 18.5523 20.552 19 19.999 19H12Z");
  stroke: none;
}

</style>
