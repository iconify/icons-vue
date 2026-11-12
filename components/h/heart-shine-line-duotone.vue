<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="epi8l4ivv"/><path class="ygae94b0i"/><path class="hv3siab8m"/><path class="jft98ub-s"/><path class="c47v7pjdu"/><path class="iu-p27b9k"/><path class="rju6pr7ot"/><path class="vwck1pjsf"/><path class="v2l39z97d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-shine-line-duotone" /></template>
<style>
.c47v7pjdu {
  d: path("M6 18L6.34305 17.657");
}

.epi8l4ivv {
  d: path("M12 2V4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hv3siab8m {
  d: path("M2 12L4 12");
  opacity: var(--svg-opacity--0-5, 0.5);
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

.jft98ub-s {
  d: path("M20 12L22 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rju6pr7ot {
  d: path("M18 18L17.657 17.657");
}

.v2l39z97d {
  stroke-linejoin: round;
  d: path("M10.7847 15.3538C9.60777 14.4107 8 13.357 8 11.3796C8 9.40225 10.2001 7.99994 12 9.90096C13.7999 7.99994 16 9.40225 16 11.3796C16 13.357 14.3922 14.4107 13.2153 15.3538C12.8 15.6866 12.4 16 12 16C11.6 16 11.2 15.6866 10.7847 15.3538Z");
}

.vwck1pjsf {
  d: path("M6.34375 6.34326L6.00049 6");
}

.ygae94b0i {
  d: path("M12 20V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
