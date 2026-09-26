<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tx_ah59as"/><path class="vo64d318x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-u-turn-right" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tx_ah59as {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2Z");
}

.vo64d318x {
  d: path("M15.6993 10.5H11.0797C9.37884 10.5 8 11.8431 8 13.5C8 15.1569 9.37884 16.5 11.0797 16.5H12.1063M13.1329 7.5L15.8497 10.1464C16.0501 10.3417 16.0501 10.6583 15.8497 10.8536L13.1329 13.5");
}

</style>
