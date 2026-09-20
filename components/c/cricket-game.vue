<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wa2h49bsg"/><path class="y09yt0b2z"/><path class="tysk7gb-g"/><path class="k9-2q5bhf"/><path class="m1qh4intb"/><circle class="m8_dt8b7r"/><circle class="iqn_fcohr"/><path class="apf689e1d"/><path class="nx85axtul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:cricket-game" /></template>
<style>
.apf689e1d {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.2 119.94c5.49-1.83 17.19-6.89 22.42-17.87q-.885-1.185-1.98-2.16c-4.71 11.19-17.26 16.17-22.06 17.71c.46.83 1 1.6 1.62 2.32");
}

.iqn_fcohr {
  cx: 10.27px;
  cy: 107.04px;
  r: 3.81px;
  fill: var(--svg-color--f48263, #f48263);
}

.k9-2q5bhf {
  fill: var(--svg-color--fac21c, #fac21c);
  d: path("M124.96 11.18a3 3 0 0 0-.63-4.35l-3.19-2.25a2.993 2.993 0 0 0-4.3.87l-1.6 2.57l7.84 5.53z");
}

.m1qh4intb {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M120.85 16.36L111 14.82l-1.84 2.95l9.41 1.47zm-5.11 6.45l-8.86-1.39l-1.84 2.95l8.42 1.32zm-5.11 6.45l-7.87-1.23l-1.84 2.95l7.42 1.16z");
}

.m8_dt8b7r {
  cx: 16.1px;
  cy: 110.62px;
  r: 14.35px;
  fill: var(--svg-color--ed6c30, #ed6c30);
}

.nx85axtul {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.89 121.62c.92.77 1.95 1.42 3.05 1.95c5.59-1.72 15.23-5.96 20.28-15.51c-.24-1.33-.66-2.59-1.24-3.76c-4.77 12.16-17.55 16.24-22.09 17.32");
}

.tysk7gb-g {
  fill: var(--svg-color--f7932a, #f7932a);
  d: path("M101.15 45.98L70.8 80.54c-.73.83-2.05-.09-1.51-1.06l22.36-40.19a.93.93 0 0 1 1.34-.31l7.98 5.63c.47.32.54.95.18 1.37");
}

.wa2h49bsg {
  fill: var(--svg-color--196ca2, #196ca2);
  d: path("M104.58 48.83c1.44 1.01 2.81-.72 1.5-1.9c0 0-5.19-4.7-.69-11.09l19.56-24.67a3 3 0 0 0-.63-4.35l-3.19-2.25a2.993 2.993 0 0 0-4.3.87l-16.66 26.71c-4.5 6.38-10.67 3.08-10.67 3.08c-1.55-.83-2.9.91-1.47 1.93z");
}

.y09yt0b2z {
  fill: var(--svg-color--fac21c, #fac21c);
  d: path("m53.43 124.98l54.44-75.51l-21.76-15.35l-52.7 76.74s6.56 12.88 20.02 14.12");
}

</style>
