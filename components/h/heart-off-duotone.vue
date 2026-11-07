<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hk_1acb5z"/><path class="fablkgbgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-off-duotone" /></template>
<style>
.fablkgbgv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.564 4.564C4.106 5.178 3 6.615 3 9c0 6 9 11 9 11s2.706-1.503 5.15-3.85m2.693-3.307C20.547 11.643 21 10.347 21 9c0-5.34-5.543-5.927-8.173-3.173M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.hk_1acb5z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.827 5.827C15.457 3.073 21 3.661 21 9c0 1.362-.475 2.679-1.157 3.843ZM17.15 16.15A28 28 0 0 1 12 20S3 15 3 9c.002-1.889.733-3.662 2.564-4.436Z");
}

</style>
