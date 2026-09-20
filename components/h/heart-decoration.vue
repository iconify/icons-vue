<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dpvarpbiq"/><path class="q-_fbfbpi"/><path class="sc5o1nzqk"/><radialGradient id="SVGK3uFedlr" cx="-3364.513" cy="2296.505" r="44.47" fx="-3338.032" fy="2332.231" gradientTransform="matrix(0 -.93 1.07 0 -2389.6 -3096.14)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="kvwb2tr-m"/><stop offset="1" class="rwhk7-m5g"/></radialGradient><path fill="url(#SVGK3uFedlr)" class="e4--cjx6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:heart-decoration" /></template>
<style>
.dpvarpbiq {
  fill: var(--svg-color--8e24aa, #8e24aa);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.e4--cjx6g {
  d: path("M86.4 22.9C70.1 22.9 64 42.5 64 42.5s-5.9-19.6-22.4-19.6c-12.4 0-26.5 9.8-21.3 32.2s43.6 50 43.6 50s.2-.1.2-.2c.01.08.05.15.1.2c0 0 38.3-27.7 43.5-50s-8.9-32.2-21.3-32.2");
}

.kvwb2tr-m {
  stop-color: var(--svg-color--fafafa, #fafafa);
}

.q-_fbfbpi {
  fill: var(--svg-color--ab47bc, #ab47bc);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.rwhk7-m5g {
  stop-color: var(--svg-color--eee, #eee);
}

.sc5o1nzqk {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
