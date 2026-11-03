<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="o54fbbbkg"/><path class="r6h9s2bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:locate-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o54fbbbkg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.9498 16.9498C15.6384 18.2646 13.857 19.0024 12 19C8.134 19 5 15.866 5 12C4.9976 10.143 5.7354 8.3616 7.0503 7.0503L16.9498 16.9498ZM9.2274 5.5706C10.1029 5.1929 11.0465 4.9987 12 5C15.866 5 19 8.134 19 12C19.0013 12.9535 18.8071 13.8971 18.4294 14.7726L9.2274 5.5706Z");
  stroke: none;
}

.r6h9s2bre {
  d: path("M12 23L12 18M1 12L6 12M12 1L12 6M23 12L18 12M1.7071 1.7071L22.2929 22.2929");
}

</style>
