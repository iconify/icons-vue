<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="w_h8ukbof"/><path class="jtqfwhbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-off-two-tone" /></template>
<style>
.jtqfwhbdr {
  d: path("M4 17L3 17C2.4477 17 2 16.5523 2 16L2 13.6491C2 13.2192 2.0693 12.7921 2.2053 12.3842L4.2108 6.3675C4.3822 5.8532 4.7489 5.4442 5.212 5.212M8 17L15 17M3 10L10 10M8 17C8 18.1046 7.1046 19 6 19C4.8954 19 4 18.1046 4 17C4 15.8954 4.8954 15 6 15C7.1046 15 8 15.8954 8 17ZM18.4142 18.4142C18.0523 18.7761 17.5523 19 17 19C15.8954 19 15 18.1046 15 17C15 16.4477 15.2239 15.9477 15.5858 15.5858M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w_h8ukbof {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M15.1715 18L3 18C1.8954 18 1 17.1046 1 16L1 13.6491C1 13.1117 1.0866 12.5778 1.2566 12.068L3.2621 6.0513C3.4776 5.4043 3.9073 4.8501 4.4802 4.4802L18 18.0001L15.1715 18ZM8.2426 4L12.0975 4C12.9582 4 13.7775 4.3697 14.347 5.0151L18.5717 9.8031L20.9487 10.5955C22.1737 11.0038 23 12.1502 23 13.4415L23 16C23.0003 16.7212 22.6121 17.3867 21.9842 17.7415L8.2426 4Z");
  stroke: none;
}

</style>
