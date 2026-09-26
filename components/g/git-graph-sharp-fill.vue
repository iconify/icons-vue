<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="knttfobnd"/><path class="dm2ls-bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-graph-sharp-fill" /></template>
<style>
.dm2ls-bhz {
  fill: currentColor;
  d: path("M5 1C7.0711 1 9 2.929 9 5C9 7.0711 7.0711 9 5 9C2.929 9 1 7.0711 1 5C1 2.929 2.929 1 5 1ZM19 1C21.0711 1 23 2.929 23 5C23 7.0711 21.0711 9 19 9C16.9289 9 15 7.0711 15 5C15 2.929 16.9289 1 19 1ZM5 14.5C7.0711 14.5 9 16.4289 9 18.5C9 20.5711 7.0711 22.5 5 22.5C2.929 22.5 1 20.5711 1 18.5C1 16.4289 2.929 14.5 5 14.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.knttfobnd {
  d: path("M5 16L5 7M12 22L12 2M19 7L19 8C19 10 18.8 12.4 16 14L15.1318 14.4961");
}

</style>
