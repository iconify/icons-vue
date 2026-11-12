<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7r47tacd"/><path class="vfd6cpb4t"/><path class="zem_esjhx"/><path class="y8f17tims"/><path class="w290wdboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-bold-duotone" /></template>
<style>
.o7r47tacd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vfd6cpb4t {
  fill: currentColor;
  d: path("M5.47924 19.5818L9.75198 15.309C9.33529 15.0254 8.97496 14.6651 8.69128 14.2484L4.41856 18.5211C4.7452 18.9005 5.09982 19.2551 5.47924 19.5818Z");
}

.w290wdboz {
  fill: currentColor;
  d: path("M19.5817 18.521L15.3089 14.2483C15.0253 14.665 14.665 15.0253 14.2483 15.3089L18.521 19.5817C18.9004 19.255 19.255 18.9004 19.5817 18.521Z");
}

.y8f17tims {
  fill: currentColor;
  d: path("M14.2484 8.69128L18.5211 4.41856C18.9005 4.7452 19.2551 5.09982 19.5818 5.47924L15.309 9.75198C15.0254 9.33529 14.6651 8.97496 14.2484 8.69128Z");
}

.zem_esjhx {
  fill: currentColor;
  d: path("M4.41846 5.47912L8.69119 9.75185C8.97485 9.33516 9.33516 8.97485 9.75185 8.69119L5.47912 4.41846C5.09971 4.74509 4.74509 5.09971 4.41846 5.47912Z");
}

</style>
