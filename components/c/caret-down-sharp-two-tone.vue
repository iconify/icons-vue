<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k384k8b7z"/><path class="gxhti5bxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-down-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gxhti5bxu {
  d: path("M12 18L5 6L19 6L12 18Z");
}

.k384k8b7z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.1362 18.5039L4.1362 6.5039C3.7473 5.8372 4.2282 5 5 5L19 5C19.7718 5 20.2527 5.8372 19.8638 6.5039L12.8638 18.5039C12.4779 19.1654 11.5221 19.1654 11.1362 18.5039Z");
  stroke: none;
}

</style>
