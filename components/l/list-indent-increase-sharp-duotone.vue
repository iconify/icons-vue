<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lhn3s488c"/><path class="spmdglbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-indent-increase-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lhn3s488c {
  stroke-opacity: 0.4;
  d: path("M1 12L8 12M4.7071 8.7071L8 12L4.7071 15.2929");
}

.spmdglbzj {
  d: path("M11 6L23 6M11 12L23 12M11 18L23 18");
}

</style>
