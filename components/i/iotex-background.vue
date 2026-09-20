<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGtZRcIbwH)" class="gyzn4gb4n"/><path fill="url(#SVG6COnTdqS)" class="jale8ebyh"/><path fill="url(#SVGjxOuBevo)" class="v95yoabwg"/><path fill="url(#SVGscJ4scOu)" class="ntvl8dq8u"/><path fill="url(#SVGvLnxJbMs)" class="xzyjhy0ex"/><path fill="url(#SVGohYw2bCO)" class="nwnho5vqb"/><path fill="url(#SVGHoyv9cxS)" class="bunrzzb5h"/><path fill="url(#SVG9K9z2dYB)" class="m6u-728_q"/><path fill="url(#SVGm5ZjSDBH)" class="pd031dbyz"/><path fill="url(#SVGKtXOmcDR)" class="rzs4ezbba"/><path fill="url(#SVGQWWPUcIW)" class="pmvm4hbmr"/><path fill="url(#SVGR6u3Ybrc)" class="djbe1w3da"/><path fill="url(#SVG3zYG5bPd)" class="geb996bzt"/><path fill="url(#SVGQb5Aae9S)" class="jm5mswbqq"/><path fill="url(#SVGdtcDCbvN)" class="ux4-ykhmv"/><path fill="url(#SVGkzjBBb4s)" class="e7oen-bga"/><path fill="url(#SVGIcShREuY)" class="aoxt_9b6b"/><path fill="url(#SVGR1NGFbOH)" class="zf_zedcvo"/><path fill="url(#SVGTLegOdAx)" class="jep02mbco"/><path fill="url(#SVGx0YRvXcD)" class="p_pogkbey"/><path fill="url(#SVGWpqhLbbb)" class="o1f4mltoq"/><path fill="url(#SVGGUCb53oI)" class="xrl52bu_c"/></g><defs><linearGradient id="SVGtZRcIbwH" x1="14.438" x2="17.115" y1="6.455" y2="6.851" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVG6COnTdqS" x1="17.63" x2="20.306" y1="8.272" y2="8.668" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGjxOuBevo" x1="14.472" x2="17.152" y1="10.094" y2="10.491" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGscJ4scOu" x1="15.261" x2="20.53" y1="12.92" y2="13.96" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGvLnxJbMs" x1="17.63" x2="20.306" y1="15.55" y2="15.945" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGohYw2bCO" x1="6.305" x2="8.981" y1="9.971" y2="10.367" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGHoyv9cxS" x1="10.287" x2="12.967" y1="11.324" y2="11.721" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVG9K9z2dYB" x1="7.948" x2="10.624" y1="13.626" y2="14.021" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGm5ZjSDBH" x1="10.026" x2="12.707" y1="16.371" y2="16.768" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGKtXOmcDR" x1="14.441" x2="17.122" y1="17.938" y2="18.335" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGQWWPUcIW" x1="10.812" x2="13.493" y1="9.527" y2="9.924" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGR6u3Ybrc" x1="11.313" x2="13.993" y1="6.455" y2="6.852" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVG3zYG5bPd" x1="8.448" x2="13.716" y1="8.997" y2="10.039" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGQb5Aae9S" x1="7.117" x2="9.798" y1="11.324" y2="11.721" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGdtcDCbvN" x1="11.313" x2="13.993" y1="13.733" y2="14.13" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGkzjBBb4s" x1="4.79" x2="7.471" y1="14.577" y2="14.975" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGIcShREuY" x1="17.63" x2="20.306" y1="10.094" y2="10.49" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGR1NGFbOH" x1="14.472" x2="17.152" y1="11.911" y2="12.308" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGTLegOdAx" x1="17.631" x2="20.312" y1="13.733" y2="14.13" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGx0YRvXcD" x1="14.47" x2="17.147" y1="15.55" y2="15.945" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGWpqhLbbb" x1="10.614" x2="13.294" y1="17.07" y2="17.468" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><linearGradient id="SVGGUCb53oI" x1="14.472" x2="17.152" y1="8.272" y2="8.669" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:iotex-background" /></template>
<style>
.aoxt_9b6b {
  d: path("M19.995 8.078v3.639l-3.154-1.822z");
}

.bunrzzb5h {
  d: path("M9.497 9.308v3.639l3.159-1.822z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.djbe1w3da {
  d: path("M13.682 4.439v3.639l-3.16-1.822z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.e7oen-bga {
  d: path("M7.16 12.564v3.634L4 14.38z");
  opacity: var(--svg-opacity--0-55, 0.55);
}

.erxb15e0q {
  stop-color: var(--svg-color--72a7ff, #72a7ff);
}

.ft5dv1b6b {
  fill: none;
}

.geb996bzt {
  d: path("M10.023 5.98v3.64L6.869 7.801zm3.159 1.807v3.639l-3.154-1.822z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.gyzn4gb4n {
  d: path("M13.65 4.439v3.639l3.153-1.822z");
}

.i5zzcz8in {
  stop-color: var(--svg-color--77fe9e, #77fe9e);
}

.jale8ebyh {
  d: path("M16.84 6.256v3.639l3.155-1.817z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.jep02mbco {
  d: path("M20 11.717v3.639l-3.16-1.822z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.jm5mswbqq {
  d: path("M9.486 9.308v3.639l-3.159-1.822z");
  opacity: var(--svg-opacity--0-95, 0.95);
}

.m6u-728_q {
  d: path("M7.16 11.61v3.639l3.153-1.822z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.ntvl8dq8u {
  d: path("M16.84 9.895v3.639l3.155-1.817zm-3.158 1.822v3.639l3.159-1.822z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.nwnho5vqb {
  d: path("M5.516 7.955v3.64L8.67 9.771z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.o1f4mltoq {
  d: path("M12.983 15.055v3.639l-3.16-1.817z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.p_pogkbey {
  d: path("M16.836 13.534v3.638l-3.154-1.816z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.pd031dbyz {
  d: path("M9.236 14.355v3.64l3.16-1.823z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.pmvm4hbmr {
  d: path("M10.022 7.511v3.64l3.16-1.818z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rzs4ezbba {
  d: path("M13.65 15.922v3.64l3.16-1.823z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ux4-ykhmv {
  d: path("M13.682 11.717v3.639l-3.16-1.822z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.v95yoabwg {
  d: path("M13.682 8.078v3.639l3.159-1.822z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.wjyp-zbjo {
  stop-color: var(--svg-color--ec02d5, #ec02d5);
}

.xrl52bu_c {
  d: path("M16.84 6.256v3.639l-3.158-1.817z");
}

.xzyjhy0ex {
  d: path("M16.84 13.534v3.638l3.155-1.816z");
}

.zf_zedcvo {
  d: path("M16.84 9.895v3.639l-3.158-1.817z");
  opacity: var(--svg-opacity--0-95, 0.95);
}

</style>
