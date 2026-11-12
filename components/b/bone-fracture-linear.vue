<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nwcmqsbpt"/><path class="y87zpc5sn"/><path class="xctzs9_bc"/><path class="a_u8cmuxy"/><path class="lg0z81ujb"/><path class="ri10h9mxk"/><path class="va0j451bl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-fracture-linear" /></template>
<style>
.a_u8cmuxy {
  d: path("M15 19V20");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg0z81ujb {
  d: path("M5 9L4 9");
}

.nwcmqsbpt {
  stroke-linejoin: round;
  d: path("M13.2895 5.7897C13.0092 4.77646 13.3942 3.48102 14.1374 2.73779C15.1212 1.75407 16.7161 1.75407 17.6998 2.73779C18.6835 3.72152 18.6835 5.31646 17.6998 6.30018C18.6835 5.31646 20.2785 5.31646 21.2622 6.30018C22.2459 7.28391 22.2459 8.87884 21.2622 9.86257C20.519 10.6058 19.2235 10.9908 18.2103 10.7105C17.674 10.562 17.0246 10.5378 16.6311 10.9313L15.3516 12.2108C15.2819 12.2804 15.1639 12.2577 15.1251 12.1671C14.4911 10.6877 13.3123 9.50892 11.8329 8.8749C11.7423 8.83608 11.7196 8.71805 11.7892 8.64837L13.0687 7.3689C13.4622 6.97541 13.438 6.32603 13.2895 5.7897ZM6.30018 17.6998C5.31646 18.6835 3.72152 18.6835 2.73779 17.6998C1.75407 16.7161 1.75407 15.1212 2.73779 14.1374C3.48101 13.3942 4.77646 13.0092 5.7897 13.2895C6.32603 13.438 6.97541 13.4622 7.3689 13.0687L8.64837 11.7892C8.71805 11.7196 8.83608 11.7423 8.8749 11.8329C9.50892 13.3123 10.6877 14.4911 12.1671 15.1251C12.2577 15.1639 12.2804 15.2819 12.2108 15.3516L10.9313 16.6311C10.5378 17.0246 10.562 17.674 10.7105 18.2103C10.9908 19.2235 10.6058 20.519 9.86257 21.2622C8.87884 22.2459 7.28391 22.2459 6.30018 21.2622C5.31645 20.2785 5.31646 18.6835 6.30018 17.6998Z");
}

.ri10h9mxk {
  d: path("M19 15H20");
}

.va0j451bl {
  d: path("M9 5L9 4");
}

.xctzs9_bc {
  d: path("M6.34277 6.34314L4.92856 4.92893");
}

.y87zpc5sn {
  d: path("M17.6572 17.6567L19.0714 19.071");
}

</style>
