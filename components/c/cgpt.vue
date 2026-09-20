<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGouYIodiL)" class="yc-43u4tk"/><path class="b7ih35bdj"/><path fill="url(#SVG1sUnWc6m)" class="d8xi1bc4v"/><path class="xx0o8x9ek"/><defs><linearGradient id="SVGouYIodiL" x1="20.209" x2="2.124" y1="4.958" y2="16.505" gradientUnits="userSpaceOnUse"><stop class="u7fgqqe3e"/><stop offset=".28" class="doqzoh6-z"/><stop offset=".52" class="x8a6b6t1a"/><stop offset=".84" class="mxoss6b7e"/><stop offset="1" class="c3kbdebxc"/></linearGradient><linearGradient id="SVG1sUnWc6m" x1="20.358" x2="2.478" y1="3.648" y2="8.214" gradientUnits="userSpaceOnUse"><stop class="a5smp0b1q"/><stop offset=".25" class="wm3303biu"/><stop offset=".47" class="y81yarbbb"/><stop offset="1" class="ldsqdum1k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cgpt" /></template>
<style>
.a5smp0b1q {
  stop-color: var(--svg-color--f17165, #f17165);
}

.b7ih35bdj {
  fill: var(--svg-color--e1e7cd, #e1e7cd);
  d: path("M6.9 4.8L4.8 6.9v10.242L6.9 19.2h10.2l2.1-2.1V6.858L17.4 4.8z");
}

.c3kbdebxc {
  stop-color: var(--svg-color--18d6c9, #18d6c9);
}

.d8xi1bc4v {
  d: path("M20.676 11.664H19.2v5.34L17.1 19.2H6.9l-2.1-2.1L3 18.336l2.478 2.568c.06.06.144.096.228.096h11.946a.33.33 0 0 0 .228-.096l3.024-3.138c.06-.06.096-.15.096-.24V12a.333.333 0 0 0-.324-.336");
}

.doqzoh6-z {
  stop-color: var(--svg-color--4663e9, #4663e9);
}

.ft5dv1b6b {
  fill: none;
}

.ldsqdum1k {
  stop-color: var(--svg-color--e7c653, #e7c653);
}

.mxoss6b7e {
  stop-color: var(--svg-color--17dac6, #17dac6);
}

.u7fgqqe3e {
  stop-color: var(--svg-color--684bfd, #684bfd);
}

.wm3303biu {
  stop-color: var(--svg-color--f19c5c, #f19c5c);
}

.x8a6b6t1a {
  stop-color: var(--svg-color--4380e8, #4380e8);
}

.xx0o8x9ek {
  fill: var(--svg-color--1a1a24, #1a1a24);
  d: path("M9.6 14.4a1.2 1.2 0 1 0 0-2.4a1.2 1.2 0 0 0 0 2.4m4.8 0a1.2 1.2 0 1 0 0-2.4a1.2 1.2 0 0 0 0 2.4");
}

.y81yarbbb {
  stop-color: var(--svg-color--e9be4d, #e9be4d);
}

.yc-43u4tk {
  d: path("M3 18.336L4.8 17.1V6.9l2.1-2.1h10.44l1.86 2.1l1.128-.678a.34.34 0 0 0 .06-.522L17.88 3.096A.32.32 0 0 0 17.652 3H6.024a.32.32 0 0 0-.228.096l-2.7 2.808A.33.33 0 0 0 3 6.138z");
}

</style>
