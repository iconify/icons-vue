<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1wmeb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:error-rate" /></template>
<style>
.xy1wmeb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.535 18.5H5.04q-.115 0-.229-.015t-.225-.045t-.217-.073t-.205-.102q-.1-.057-.191-.127t-.172-.151t-.151-.173t-.127-.191t-.101-.205q-.044-.107-.074-.218t-.044-.224q-.015-.114-.015-.229t.016-.229t.045-.225t.074-.217t.102-.205L9.487 5.606q.029-.049.061-.097q.031-.047.066-.092q.035-.046.073-.089t.078-.083t.084-.078t.088-.072q.046-.035.093-.066q.048-.032.097-.06q.05-.029.101-.054t.104-.047t.107-.04t.109-.033t.112-.026t.112-.019q.057-.007.114-.011T11 4.735t.114.004t.114.011q.056.008.112.019q.057.011.112.026t.109.033t.107.04t.104.047t.101.054q.049.028.097.06q.047.031.093.066q.045.035.088.072q.043.038.084.078q.04.041.078.083t.073.089q.035.045.066.092q.032.048.061.097l4.319 7.437M11 8.5v4m0 2.75h.01m3.74 6l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
