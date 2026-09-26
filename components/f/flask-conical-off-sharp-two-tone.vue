<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mutq2p_rd"/><path class="o6099mb7z"/><path class="fi8fabbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-off-sharp-two-tone" /></template>
<style>
.fi8fabbiq {
  d: path("M18.7058 18.7058L19.9999 22L4.0001 22L9.0769 9.0769M5.5715 18L18 18M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mutq2p_rd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.4754 20.4754L20.9307 21.6344C20.9765 21.7508 20.9999 21.8749 20.9999 22C20.9999 22.5523 20.5522 23 19.9999 23L4.0001 23C3.4478 23 3.0001 22.5523 3.0001 22C3.0001 21.8749 3.0235 21.7508 3.0693 21.6344L8.3056 8.3056Z");
  stroke: none;
}

.o6099mb7z {
  stroke-opacity: 0.4;
  d: path("M9.5 4.8431L9.5 3.8431L9.5 2L14.5 2L14.5 8L15.0456 9.3887L15.5008 10.5475M7 2L17 2");
}

</style>
