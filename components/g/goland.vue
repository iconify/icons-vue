<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGR5DOvb6y" x1="63.101%" x2="28.874%" y1="29.811%" y2="83.71%"><stop offset="0%" class="r_lf9ybqi"/><stop offset="2%" class="xn5n65oec"/><stop offset="37%" class="hza7p58_s"/><stop offset="66%" class="hrd46ge2u"/><stop offset="88%" class="n-448bcfb"/><stop offset="100%" class="v1-n43bey"/></linearGradient><linearGradient id="SVG2hUKVc6x" x1="49.124%" x2="74.872%" y1="38.465%" y2="4.95%"><stop offset="0%" class="r_lf9ybqi"/><stop offset="2%" class="xn5n65oec"/><stop offset="37%" class="hza7p58_s"/><stop offset="66%" class="hrd46ge2u"/><stop offset="88%" class="n-448bcfb"/><stop offset="100%" class="v1-n43bey"/></linearGradient><linearGradient id="SVGuvNPzdRR" x1="13.896%" x2="86.031%" y1="71.063%" y2="34.549%"><stop offset="0%" class="r_lf9ybqi"/><stop offset="10%" class="caj3n_bnh"/><stop offset="22%" class="f14osrb1i"/><stop offset="35%" class="kg5lk3g9z"/><stop offset="46%" class="zlv-h5bce"/><stop offset="57%" class="bhmv3lg4g"/><stop offset="67%" class="k_ry59jvu"/></linearGradient></defs><path fill="url(#SVGR5DOvb6y)" class="r6jqbtnqn"/><path class="p_x7x2bje"/><path fill="url(#SVG2hUKVc6x)" class="rtittbcly"/><path fill="url(#SVGuvNPzdRR)" class="bmta6xbbv"/><path class="wj8kk3bmp"/><path class="qz2q2oh6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:goland" /></template>
<style>
.bhmv3lg4g {
  stop-color: var(--svg-color--39e767, #39e767);
}

.bmta6xbbv {
  d: path("M256 54.347L148.667 79.84L0 206.32L95.893 256l75.734-78.08z");
}

.caj3n_bnh {
  stop-color: var(--svg-color--1598d3, #1598d3);
}

.f14osrb1i {
  stop-color: var(--svg-color--23b6aa, #23b6aa);
}

.hrd46ge2u {
  stop-color: var(--svg-color--8a57f8, #8a57f8);
}

.hza7p58_s {
  stop-color: var(--svg-color--5566f9, #5566f9);
}

.k_ry59jvu {
  stop-color: var(--svg-color--3bea62, #3bea62);
}

.kg5lk3g9z {
  stop-color: var(--svg-color--2dcc8b, #2dcc8b);
}

.n-448bcfb {
  stop-color: var(--svg-color--ab4ef7, #ab4ef7);
}

.p_x7x2bje {
  fill: var(--svg-color--b74af7, #b74af7);
  d: path("m171.627 177.92l32.16 78.08l-80.907-27.813z");
}

.qz2q2oh6a {
  fill: var(--svg-color--fff, #fff);
  d: path("M63.013 178h60v10h-60zm-4.507-75.84v-.187A33.87 33.87 0 0 1 93.093 68a36.32 36.32 0 0 1 25.947 9.04l-9.147 11.04a24.35 24.35 0 0 0-17.253-6.747c-10.453 0-18.627 8.964-18.95 19.864l-.01.856c0 11.848 7.977 20.592 19.328 20.924l.672.01a23.12 23.12 0 0 0 13.653-3.974v-9.493H92.72V96.987h28.613v28.64a42.86 42.86 0 0 1-28.186 10.48c-20.507 0-34.64-14.427-34.64-33.947m68.96 0v-.187A34.107 34.107 0 0 1 162.64 68c20.052 0 34.535 14.737 34.95 33.107l.01 1a34.107 34.107 0 0 1-34.159 34.149l-.988-.016c-20.373-.133-34.986-15.307-34.986-34.08m54.96 0v-.187a20.027 20.027 0 0 0-19.973-20.64a19.734 19.734 0 0 0-19.8 19.65l.014.99a20.053 20.053 0 0 0 20 20.747a19.734 19.734 0 0 0 19.76-20.56");
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.r6jqbtnqn {
  d: path("M225.493 99.013L256 166.667L203.787 256l-32.16-78.08z");
}

.rtittbcly {
  d: path("M180.347 72.293L163.76 0H71.787L0 109.813l20.773 50.454L0 206.32L148.667 79.84z");
}

.v1-n43bey {
  stop-color: var(--svg-color--b74af7, #b74af7);
}

.wj8kk3bmp {
  d: path("M48 48h160v160H48z");
}

.xn5n65oec {
  stop-color: var(--svg-color--0d7bfa, #0d7bfa);
}

.zlv-h5bce {
  stop-color: var(--svg-color--35dd74, #35dd74);
}

</style>
