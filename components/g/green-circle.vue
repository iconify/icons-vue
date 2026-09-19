<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipjFdfb)" class="m_ob72i3o"/><path fill="url(#iu9RYoe)" class="m_ob72i3o"/><path fill="url(#izGGV9l)" class="m_ob72i3o"/><path fill="url(#inEUtHe)" class="m_ob72i3o"/><path fill="url(#iarJcgc)" class="m_ob72i3o"/><defs><radialGradient id="ipjFdfb" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.994 9.81)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="ysuw4aczg"/><stop offset=".835" class="n0wn5ebbv"/></radialGradient><radialGradient id="izGGV9l" cx="0" cy="0" r="1" gradientTransform="rotate(136.38 10.117 10.14)scale(14.6767 15.816)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="fyh7tobet"/><stop offset="1" class="ahr79_jza"/></radialGradient><radialGradient id="inEUtHe" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.249 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="b977_7b4m"/><stop offset=".951" class="k-ikjwu0f"/></radialGradient><radialGradient id="iarJcgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 22.1875 -22.9876 0 15.757 8.75)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="o2zib1bad"/><stop offset="1" class="ubyqar-vi"/></radialGradient><linearGradient id="iu9RYoe" x1="15.757" x2="15.757" y1="1.75" y2="8.25" gradientUnits="userSpaceOnUse"><stop class="pxummbb5x"/><stop offset="1" class="xl0_txb8r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:green-circle" /></template>
<style>
.ahr79_jza {
  stop-color: var(--svg-color--65e6a7, #65E6A7);
  stop-opacity: 0;
}

.b977_7b4m {
  stop-color: var(--svg-color--64cb85, #64CB85);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyh7tobet {
  stop-color: var(--svg-color--6ffca5, #6FFCA5);
}

.k-ikjwu0f {
  stop-color: var(--svg-color--a4e4b7, #A4E4B7);
}

.m_ob72i3o {
  d: path("M29.757 15.75c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.n0wn5ebbv {
  stop-color: var(--svg-color--43a684, #43A684);
}

.o2zib1bad {
  stop-color: var(--svg-color--4a9795, #4A9795);
  stop-opacity: 0;
}

.pxummbb5x {
  stop-color: var(--svg-color--5ed284, #5ED284);
}

.ubyqar-vi {
  stop-color: var(--svg-color--718cad, #718CAD);
}

.xl0_txb8r {
  stop-color: var(--svg-color--5ed284, #5ED284);
  stop-opacity: 0;
}

.ysuw4aczg {
  stop-color: var(--svg-color--5ae68d, #5AE68D);
}

</style>
