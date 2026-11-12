<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="z-dxw3bya"/><path class="x7g8qiggf"/><path class="jk2uj-6bl"/><path class="x-21zwayg"/><path class="bd1q7zbzn"/><path class="gcdno_bug"/><path class="f5spxzclx"/><path class="nzyd4p8sl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-2-linear" /></template>
<style>
.bd1q7zbzn {
  d: path("M10 5H14");
}

.f5spxzclx {
  d: path("M10 11H14");
}

.gcdno_bug {
  d: path("M10 8H14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk2uj-6bl {
  d: path("M3 22V11.5C3 10.0955 3 9.39331 3.33706 8.88886C3.48298 8.67048 3.67048 8.48298 3.88886 8.33706C4.39331 8 5.09554 8 6.5 8");
}

.nzyd4p8sl {
  d: path("M10 14H14");
}

.x-21zwayg {
  d: path("M12 22V19");
}

.x7g8qiggf {
  d: path("M21 22V11.5C21 10.0955 21 9.39331 20.6629 8.88886C20.517 8.67048 20.3295 8.48298 20.1111 8.33706C19.6067 8 18.9045 8 17.5 8");
}

.xpzbxokqs {
  d: path("M22 22L2 22");
}

.z-dxw3bya {
  d: path("M17 22V6C17 4.11438 17 3.17157 16.4142 2.58579C15.8284 2 14.8856 2 13 2H11C9.11438 2 8.17157 2 7.58579 2.58579C7 3.17157 7 4.11438 7 6V22");
}

</style>
