<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGEJTKRdVM)" class="eluniclwg"/><path class="typepabds"/><path fill="url(#SVGnOvDoeCS)" class="d0ac0xb2t"/><path class="l0zc2cckr"/></g><defs><linearGradient id="SVGEJTKRdVM" x1="19.297" x2="3.221" y1="5.74" y2="16.004" gradientUnits="userSpaceOnUse"><stop class="u7fgqqe3e"/><stop offset=".28" class="doqzoh6-z"/><stop offset=".52" class="x8a6b6t1a"/><stop offset=".84" class="mxoss6b7e"/><stop offset="1" class="c3kbdebxc"/></linearGradient><linearGradient id="SVGnOvDoeCS" x1="19.429" x2="3.536" y1="4.576" y2="8.635" gradientUnits="userSpaceOnUse"><stop class="a5smp0b1q"/><stop offset=".25" class="wm3303biu"/><stop offset=".47" class="y81yarbbb"/><stop offset="1" class="ldsqdum1k"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cgpt-background" /></template>
<style>
.a5smp0b1q {
  stop-color: var(--svg-color--f17165, #f17165);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c3kbdebxc {
  stop-color: var(--svg-color--18d6c9, #18d6c9);
}

.d0ac0xb2t {
  d: path("M19.712 11.701H18.4v4.747L16.533 18.4H7.467L5.6 16.533L4 17.632l2.203 2.283a.3.3 0 0 0 .202.085h10.619c.075 0 .15-.032.203-.085l2.688-2.79a.3.3 0 0 0 .085-.213V12a.296.296 0 0 0-.288-.299");
}

.doqzoh6-z {
  stop-color: var(--svg-color--4663e9, #4663e9);
}

.eluniclwg {
  d: path("m4 17.632l1.6-1.099V7.467L7.467 5.6h9.28L18.4 7.467l1.003-.603a.302.302 0 0 0 .053-.464l-2.23-2.315A.28.28 0 0 0 17.025 4H6.688a.28.28 0 0 0-.203.085l-2.4 2.496A.3.3 0 0 0 4 6.79z");
}

.ft5dv1b6b {
  fill: none;
}

.l0zc2cckr {
  fill: var(--svg-color--1a1a24, #1a1a24);
  d: path("M9.867 14.133a1.067 1.067 0 1 0 0-2.133a1.067 1.067 0 0 0 0 2.133m4.267 0a1.067 1.067 0 1 0 0-2.133a1.067 1.067 0 0 0 0 2.133");
}

.ldsqdum1k {
  stop-color: var(--svg-color--e7c653, #e7c653);
}

.mxoss6b7e {
  stop-color: var(--svg-color--17dac6, #17dac6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.typepabds {
  fill: var(--svg-color--e1e7cd, #e1e7cd);
  d: path("M7.467 5.6L5.6 7.467v9.104L7.467 18.4h9.066l1.867-1.867V7.43L16.8 5.6z");
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

.y81yarbbb {
  stop-color: var(--svg-color--e9be4d, #e9be4d);
}

</style>
