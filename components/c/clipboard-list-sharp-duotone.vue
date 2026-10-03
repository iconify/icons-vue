<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ew8w8y77a"/><path clip-rule="evenodd" class="nyc5e84ew"/><path class="k9vr3vxqy"/><path clip-rule="evenodd" class="ykzngxbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-list-sharp-duotone" /></template>
<style>
.ew8w8y77a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 4C3 3.4477 3.4477 3 4 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k9vr3vxqy {
  d: path("M11 13L17 13M11 17L17 17");
}

.nyc5e84ew {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1L17 1C17.5523 1 18 1.4477 18 2L18 7C18 7.5523 17.5523 8 17 8L7 8C6.4477 8 6 7.5523 6 7L6 2C6 1.4477 6.4477 1 7 1ZM8 3L8 6L16 6L16 3L8 3Z");
  stroke: none;
}

.ykzngxbve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 13C9 13.5523 8.5523 14 8 14C7.4477 14 7 13.5523 7 13C7 12.4477 7.4477 12 8 12C8.5523 12 9 12.4477 9 13ZM9 17C9 17.5523 8.5523 18 8 18C7.4477 18 7 17.5523 7 17C7 16.4477 7.4477 16 8 16C8.5523 16 9 16.4477 9 17Z");
  stroke: none;
}

</style>
