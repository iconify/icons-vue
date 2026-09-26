<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wz1j55bln"/><path class="nfyt3aclc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-sparkles-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nfyt3aclc {
  fill: currentColor;
  d: path("M17.5492 2.3739L18.4196 4.5804L20.6261 5.4508C20.8518 5.5397 21 5.7576 21 6C21 6.2424 20.8518 6.4603 20.6261 6.5492L18.4196 7.4196L17.5492 9.6261C17.4603 9.8518 17.2424 10 17 10C16.7576 10 16.5397 9.8518 16.4508 9.6261L15.5804 7.4196L13.3739 6.5492C13.1482 6.4603 13 6.2424 13 6C13 5.7576 13.1482 5.5397 13.3739 5.4508L15.5804 4.5804L16.4508 2.3739C16.5397 2.1482 16.7576 2 17 2C17.2424 2 17.4603 2.1482 17.5492 2.3739ZM8.2746 14.1869L8.7098 15.2902L9.8131 15.7254C9.9259 15.7698 10 15.8788 10 16C10 16.1212 9.9259 16.2302 9.8131 16.2746L8.7098 16.7098L8.2746 17.8131C8.2302 17.9259 8.1212 18 8 18C7.8788 18 7.7698 17.9259 7.7254 17.8131L7.2902 16.7098L6.1869 16.2746C6.0741 16.2302 6 16.1212 6 16C6 15.8788 6.0741 15.7698 6.1869 15.7254L7.2902 15.2902L7.7254 14.1869C7.7698 14.0741 7.8788 14 8 14C8.1212 14 8.2302 14.0741 8.2746 14.1869Z");
  stroke: none;
}

.wz1j55bln {
  d: path("M3 2L3 21L22 21M8 12L8 7M13 18L13 10M18 18L18 12");
}

</style>
