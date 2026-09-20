<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGVOhQMIfo" x1="31.515" x2="37.452" y1="7.821" y2="35.575" gradientUnits="userSpaceOnUse"><stop offset=".368" class="ohm06yblq"/><stop offset=".616" class="ilwnqgbrm"/><stop offset=".777" class="ysisrebsv"/></linearGradient><path fill="url(#SVGVOhQMIfo)" class="yrgl8m62s"/><linearGradient id="SVGyisHInqK" x1="67.667" x2="73.092" y1="9.75" y2="35.109" gradientUnits="userSpaceOnUse"><stop offset=".415" class="ohm06yblq"/><stop offset=".635" class="ilwnqgbrm"/><stop offset=".777" class="ysisrebsv"/></linearGradient><path fill="url(#SVGyisHInqK)" class="ph3ymn0nu"/><path class="i-_v8g_6g"/><path class="u-244lerd"/><path class="dhjkjig7z"/><path class="k5z6-8bha"/><path class="r-vytlblz"/><path class="u_gga7bad"/><path class="wgaz0e_ak"/><path class="hdkh6dbxz"/><path class="t3y3-fb7k"/><path class="tzw7k9rpz"/><path class="uo2fh-bld"/><path class="t1-as5b9v"/><path class="ofoi_db9w"/><path class="nouqdhhnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:factory" /></template>
<style>
.dhjkjig7z {
  fill: var(--svg-color--848486, #848486);
  d: path("m4.19 85.46l.02-20.16c0-1 .82-1.1 1.57-.85s2.06 1.04 2.06 1.04l10.82 17.13l21.01-1.06s.16-16.08.16-17.14s1.13-.8 1.82-.49s1.85.95 1.85.95l5.23 25.75L6.5 89.37z");
}

.hdkh6dbxz {
  fill: var(--svg-color--848486, #848486);
  d: path("M78.86 21.55c-.3.25-.23 5.55.15 5.55c.39 0 46.01.35 46.36 0s.23-5.25-.08-5.63c-.15-.19-10.9-.23-21.98-.15c-12 .08-24.2.03-24.45.23");
}

.i-_v8g_6g {
  fill: var(--svg-color--cc1935, #cc1935);
  d: path("M32.83 39.43s1.17-.62 1.09-2.93c-.08-1.99-1.57-2.61-2.63-2.68s-15.26-.14-15.97-.14s-2.2.78-2.27 3.12c-.06 1.99 1.28 2.63 1.28 2.63l-3.34 28.53L22.2 79.8l14.55.35zm18.35.03s-1.4-.8-1.29-2.99c.1-2.11 1.61-2.75 2.18-2.75s16.71.07 17.28.12c.64.05 1.61.98 1.57 2.94c-.04 2-1.45 2.84-1.45 2.84l4.69 41.83l-25.49-11.73z");
}

.ilwnqgbrm {
  stop-color: var(--svg-color--c8c8c8, #c8c8c8);
}

.k5z6-8bha {
  fill: var(--svg-color--b2b2b2, #b2b2b2);
  d: path("m7.77 85.49l.07-20.01l31.83 16.07l.06 5.53l-31.79.02zm35.16 1.37l.6-1.4l-.12-20.64l37.65 18.82V25.09h42.77v94.31l-21.73 1.62l-28.53.15z");
}

.nouqdhhnj {
  fill: var(--svg-color--a7d0d6, #a7d0d6);
  d: path("M57.28 97.46h8v8.08h-8zm-38.84.07h8.36v8.08h-8.36z");
}

.ofoi_db9w {
  fill: var(--svg-color--f1ebee, #f1ebee);
  d: path("M16.52 97.03c.04.85.05 8.28.05 8.98c0 1.15.65 1.66 1.86 1.71c1.25.05 8.53.02 9.28-.05c1.15-.1 1.15-1.35 1.1-2.31c-.05-.95-.05-7.58-.05-8.33s-.38-1.58-1.69-1.58c-1.3 0-8.59-.06-9.25-.03c-.55.03-1.35.4-1.3 1.61m40.13-1.46c-1.2.05-1.42.89-1.42 1.84s-.1 7.43-.05 8.19c.05.71.26 1.96 1.57 1.91s8.13.23 9.28.1c1.48-.16 1.25-1.46 1.29-2.36c.05-1.1.06-6.93.09-7.88c.03-1.16-.48-1.79-1.73-1.79s-7.93-.06-9.03-.01");
}

.ohm06yblq {
  stop-color: var(--svg-color--e0e0e0, #e0e0e0);
}

.ph3ymn0nu {
  d: path("M52.36 35.16s-2.46-7.81 1.71-13.05c3.98-5.01 8.15-6.09 15.73-6.95c8.57-.97 11.66-.43 14.6-1.36c1.36-.43 4-2.02 4.64-1.16s-2.63 6.79-9.91 10.22c-6.23 2.93-8.76 4.46-9.62 8.1c-.74 3.16-1.28 5.13-1.28 5.13z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.r-vytlblz {
  fill: var(--svg-color--848486, #848486);
  d: path("m80.23 119.58l9.3.03V88.02c0-1.3.48-2.09 2.09-2.09h22.46c1.16 0 2.05.65 2.05 2.91v30.57l7.69-.01s-.04 2.3-.11 3.05c-.07.82-.21 1.37-1.85 1.37l-43.05-.02z");
}

.t1-as5b9v {
  fill: var(--svg-color--a41916, #a41916);
  d: path("m80.98 119.57l-76.84.27v2.14c0 .69.14 1.72 1.65 1.83s75.15 0 75.15 0s.07-4.16.04-4.24");
}

.t3y3-fb7k {
  fill: var(--svg-color--f6b99d, #f6b99d);
  d: path("M71.92 85.47h9.06v34.79h-9.06z");
}

.tzw7k9rpz {
  fill: var(--svg-color--e14536, #e14536);
  d: path("M4.18 85.46h73.81v35.1H4.18z");
}

.u_gga7bad {
  fill: var(--svg-color--f2eeed, #f2eeed);
  d: path("M90.17 81.11V26.55l11.5-2.85l13.09 3.17v54.14s-24.74-.05-24.59.1");
}

.u-244lerd {
  fill: var(--svg-color--f1edec, #f1edec);
  d: path("m13.67 44.94l19.69.01l.77 8.02l-21.4-.01c.01.01.94-8.1.94-8.02m-2.13 18.3l23.59.05l.79 8.25l-25.53.04zM50.71 45l19.36.03l.88 7.78l-20.89.01zm-1.49 18l22.88.04l.96 8.54l-24.63.08z");
}

.uo2fh-bld {
  fill: var(--svg-color--f6b99d, #f6b99d);
  d: path("M39.72 85.45h3.8v36.41h-3.8z");
}

.wgaz0e_ak {
  fill: var(--svg-color--a7d0d6, #a7d0d6);
  d: path("M93.45 30.04h18.08v13.77H93.45zm.1 17.2h17.94V61.7H93.55zm-.1 17.83h18.05v12.77H93.45z");
}

.yrgl8m62s {
  d: path("M31.28 36.83s-1.18-6.21 3-10.16s7.6-3.1 12.88-5.97c5.07-2.75 8.06-7.84 7.25-8.42c-.81-.59-1.8.98-5.86 1.54c-4.76.66-11.49.12-18.68.73c-7.87.66-12.92 2.86-15.27 9.13c-2.01 5.37 1.51 11.59 1.51 11.59z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ysisrebsv {
  stop-color: var(--svg-color--b6b6b6, #b6b6b6);
}

</style>
