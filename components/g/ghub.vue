<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m_p5i1m2s"/><path class="axcgho9uo"/><path class="nk7b7t63v"/><path class="y3lkkwb4k"/><path class="xwxqd6i5g"/><path class="nf7x2pbsm"/><path class="n8-2wlb4w"/><path class="mlipaeboi"/><path class="pgz7em2qf"/><path class="gyti411uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ghub" /></template>
<style>
.axcgho9uo {
  fill: var(--svg-color--42c6ea, #42c6ea);
  d: path("m14.25 8.992l-2.812-.82L16.5 4.339z");
}

.ft5dv1b6b {
  fill: none;
}

.gyti411uh {
  fill: var(--svg-color--7cd1ec, #7cd1ec);
  d: path("M11.439 8.172L7.5 5.435l9-1.096z");
}

.m_p5i1m2s {
  fill: var(--svg-color--c6e9f4, #c6e9f4);
  d: path("M10.03 3.794L7.5 5.435l9-1.096z");
}

.mlipaeboi {
  fill: var(--svg-color--1d1f50, #1d1f50);
  d: path("M13.122 14.187H3l9 6.019z");
}

.n8-2wlb4w {
  fill: var(--svg-color--243e81, #243e81);
  d: path("m12 20.206l1.127-6.02L20.999 12z");
}

.nf7x2pbsm {
  fill: var(--svg-color--2589c9, #2589c9);
  d: path("m21 12l-4.5-7.661l-1.689 4.653z");
}

.nk7b7t63v {
  fill: var(--svg-color--42aadb, #42aadb);
  d: path("m11.439 8.173l-3.94-2.737L3 14.186z");
}

.pgz7em2qf {
  fill: var(--svg-color--1996ce, #1996ce);
  d: path("m13.97 9.262l-2.531-1.09L3 14.186z");
}

.xwxqd6i5g {
  fill: var(--svg-color--1b6db7, #1b6db7);
  d: path("m13.127 14.186l1.403-4.648L21 12l-7.878 2.186z");
}

.y3lkkwb4k {
  fill: var(--svg-color--2a4d9b, #2a4d9b);
  d: path("M13.97 9.813L3 14.186h10.122z");
}

</style>
