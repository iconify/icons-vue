<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xkf_mbbhp"/><path class="c3cr_5x4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:kerning-sharp-duotone" /></template>
<style>
.c3cr_5x4k {
  d: path("M7 20L17 20M9.2929 17.7071L7 20L9.2929 22.2929M14.7071 17.7071L17 20L14.7071 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xkf_mbbhp {
  stroke-opacity: 0.4;
  d: path("M1.928 14.6273L7 2L12.072 14.6273M4.188 9L9.812 9M12.9408 1.3389L17.5 13.9958L22.0592 1.3389");
}

</style>
