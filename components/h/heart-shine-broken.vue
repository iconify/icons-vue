<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x_jwp_bge"/><path class="a0gtrrbuj"/><path class="mhrx-fb4o"/><path class="hk3yrq41f"/><path class="c47v7pjdu"/><path class="iu-p27b9k"/><path class="rju6pr7ot"/><path class="vwck1pjsf"/><path class="h57vu8ids"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-shine-broken" /></template>
<style>
.a0gtrrbuj {
  d: path("M12 20V22");
}

.c47v7pjdu {
  d: path("M6 18L6.34305 17.657");
}

.h57vu8ids {
  stroke-linejoin: round;
  d: path("M8 11.3796C8 9.40225 10.2001 7.99994 12 9.90096C13.7999 7.99994 16 9.40225 16 11.3796C16 13.357 14.3922 14.4107 13.2153 15.3538C12.8 15.6866 12.4 16 12 16C11.6 16 11.2 15.6866 10.7847 15.3538C10.477 15.1072 10.1398 14.8531 9.8096 14.5768");
}

.hk3yrq41f {
  d: path("M20 12L22 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iu-p27b9k {
  d: path("M17.6562 6.34326L17.9995 6");
}

.mhrx-fb4o {
  d: path("M2 12L4 12");
}

.rju6pr7ot {
  d: path("M18 18L17.657 17.657");
}

.vwck1pjsf {
  d: path("M6.34375 6.34326L6.00049 6");
}

.x_jwp_bge {
  d: path("M12 2V4");
}

</style>
