<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mdz6s4b1j"/><path class="aslqjgb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-off-sharp-duotone" /></template>
<style>
.aslqjgb8d {
  d: path("M1.707 1.7071L22.293 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mdz6s4b1j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 12.12V13H10.9C10.437 15.2822 8.419 17 6 17C3.239 17 1 14.7614 1 12C1 9.2386 3.239 7 6 7C6.334 7 6.66 7.0326 6.975 7.095L12 12.12ZM16.657 13V11H17.657H23V13H22V15.3431V16.3431H20V15.3431V13H17.657H16.657Z");
  stroke: none;
}

</style>
