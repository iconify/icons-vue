<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s404w6g_g"/><path class="yn4ftnbvf"/><path class="mocjfac8k"/><path class="tn-y1gb8r"/><path class="zzoug-3hz"/><path class="jm1dfw2ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layout-list-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm1dfw2ei {
  d: path("M21 20.0171H14");
}

.mocjfac8k {
  d: path("M21 8.98315H14");
}

.s404w6g_g {
  d: path("M6.5 9.98309C4.85008 9.98309 4.02513 9.98309 3.51256 9.47053C3 8.95797 3 8.13301 3 6.48309C3 4.83318 3 4.00822 3.51256 3.49566C4.02513 2.98309 4.85008 2.98309 6.5 2.98309C8.14992 2.98309 8.97487 2.98309 9.48744 3.49566C10 4.00822 10 4.83318 10 6.48309C10 8.13301 10 8.95797 9.48744 9.47053C8.97487 9.98309 8.14992 9.98309 6.5 9.98309Z");
}

.tn-y1gb8r {
  d: path("M6.5 21.0171C4.85008 21.0171 4.02513 21.0171 3.51256 20.5045C3 19.992 3 19.167 3 17.5171C3 15.8672 3 15.0422 3.51256 14.5297C4.02513 14.0171 4.85008 14.0171 6.5 14.0171C8.14992 14.0171 8.97487 14.0171 9.48744 14.5297C10 15.0422 10 15.8672 10 17.5171C10 19.167 10 19.992 9.48744 20.5045C8.97487 21.0171 8.14992 21.0171 6.5 21.0171Z");
}

.yn4ftnbvf {
  d: path("M21 3.98315L14 3.98315");
}

.zzoug-3hz {
  d: path("M21 15.0171H14");
}

</style>
