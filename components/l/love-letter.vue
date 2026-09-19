<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iyrCJCc)" class="l49j1eq6d"/><rect fill="url(#iZG2BVf)" class="l49j1eq6d"/><g filter="url(#iTQ0nSb)"><path class="i7mxotbzs"/></g><path fill="url(#icJTvrc)" class="pfnd4sbfm"/><path fill="url(#igqERZb)" class="vif4eu13g"/><path fill="url(#iigZ7xc)" class="nhqnhab9x"/><path fill="url(#idPokxc)" class="dgudmugsb"/><path clip-rule="evenodd" class="q--kb4b6f"/><path clip-rule="evenodd" class="kb1n8bbsh"/><path clip-rule="evenodd" class="r27xxbb-p"/><path clip-rule="evenodd" class="bl851x74t"/><path fill="url(#i24zJ4F)" class="sbotngyhu"/><path fill="url(#iZ7vXxd)" class="sbotngyhu"/><path fill="url(#iEQg7Yb)" class="sbotngyhu"/><path fill="url(#iAAq1Pb)" class="reedtvb0j"/><g filter="url(#i5yEuue)"><path stroke="url(#iNdA7Bb)" class="n-cq5_bsc"/></g><g filter="url(#ibFi5Ne)"><path stroke="url(#ibNkknc)" class="vyoxszyru"/></g><g filter="url(#ipCxWHe)" class="mc2zb0bvp"><path class="ykbq5jngz"/></g><defs><linearGradient id="iZG2BVf" x1="-.875" x2="14.375" y1="-.625" y2="16" gradientUnits="userSpaceOnUse"><stop class="o2n61ybfr"/><stop offset="1" class="xtuma4thw"/></linearGradient><linearGradient id="icJTvrc" x1="2" x2="5" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="m-73omb5n"/><stop offset="1" class="xtuma4thw"/></linearGradient><linearGradient id="igqERZb" x1="16" x2="16" y1="6" y2="7.5" gradientUnits="userSpaceOnUse"><stop class="njy_ycceq"/><stop offset="1" class="o9_8_xx8g"/></linearGradient><linearGradient id="iigZ7xc" x1="30" x2="27" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="njy_ycceq"/><stop offset="1" class="o9_8_xx8g"/></linearGradient><linearGradient id="idPokxc" x1="16" x2="16" y1="21" y2="26" gradientUnits="userSpaceOnUse"><stop class="mnljwzubi"/><stop offset="1" class="b9er5ppzj"/></linearGradient><linearGradient id="iEQg7Yb" x1="16.563" x2="16.563" y1="13.75" y2="24.508" gradientUnits="userSpaceOnUse"><stop offset=".151" class="k0jhnr2iw"/><stop offset=".895" class="gqtzoxfau"/></linearGradient><linearGradient id="iNdA7Bb" x1="15.656" x2="18.619" y1="10.156" y2="11.252" gradientUnits="userSpaceOnUse"><stop class="bjuig4bal"/><stop offset="1" class="z3iefsbma"/></linearGradient><linearGradient id="ibNkknc" x1="22.625" x2="25.588" y1="10.156" y2="11.252" gradientUnits="userSpaceOnUse"><stop class="bjuig4bal"/><stop offset="1" class="z3iefsbma"/></linearGradient><radialGradient id="iyrCJCc" cx="0" cy="0" r="1" gradientTransform="matrix(-26.00018 20.49983 -28.69971 -36.40018 24 9.5)" gradientUnits="userSpaceOnUse"><stop class="dbgwfjgev"/><stop offset=".48" class="t2d3xoqjo"/><stop offset=".676" class="fqszvtk2l"/></radialGradient><radialGradient id="i24zJ4F" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3125 -27.6487 0 19.271 11.693)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="iZ7vXxd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.9374 9.00005 -16.85803 -22.36 20.563 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="k0jhnr2iw"/><stop offset=".834" class="gqtzoxfau"/></radialGradient><radialGradient id="iAAq1Pb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -14 20.5463 0 16.313 21.75)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="z1m7nccfk"/><stop offset="1" class="d-5yxebmh"/></radialGradient><filter id="iTQ0nSb" width="19.412" height="17.553" x="6.425" y="8.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6990_5054" stdDeviation="1"/></filter><filter id="i5yEuue" width="8.5" height="12.375" x="10.562" y="8.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6990_5054" stdDeviation="1"/></filter><filter id="ibFi5Ne" width="6.414" height="8.406" x="19.562" y="8.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6990_5054" stdDeviation="1"/></filter><filter id="ipCxWHe" width="6" height="21.187" x="25.459" y="4.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6990_5054" stdDeviation="1.25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:love-letter" /></template>
<style>
.b9er5ppzj {
  stop-color: var(--svg-color--c79be7, #C79BE7);
}

.bjuig4bal {
  stop-color: var(--svg-color--ff9e75, #FF9E75);
}

.bl851x74t {
  fill: var(--svg-color--d5cfda, #D5CFDA);
  fill-rule: evenodd;
  d: path("M29.879 7.313c.078.214.121.446.121.687v.434l-8.223 5.482l-.554-.832z");
}

.d-5yxebmh {
  stop-color: var(--svg-color--ff7033, #FF7033);
}

.dbgwfjgev {
  stop-color: var(--svg-color--f3eff9, #F3EFF9);
}

.dgudmugsb {
  d: path("M2 21h28v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.fqszvtk2l {
  stop-color: var(--svg-color--e8d2f5, #E8D2F5);
}

.ft5dv1b6b {
  fill: none;
}

.gqtzoxfau {
  stop-color: var(--svg-color--c12372, #C12372);
}

.i7mxotbzs {
  fill: var(--svg-color--ccc1d3, #CCC1D3);
  d: path("M15.643 23.595c.29.17.645.155.93-.023c2.038-1.273 5.43-3.826 6.789-7.23c1.985-4.408-2.688-7.852-5.91-5.32c-.35.275-.825.68-1.13 1.015c-.112.123-.317.134-.432.013c-.367-.388-.956-.944-1.35-1.21c-2.746-1.859-7.73.514-5.6 5.741c.78 2.34 4.59 5.763 6.703 7.014");
}

.k0jhnr2iw {
  stop-color: var(--svg-color--c12372, #C12372);
  stop-opacity: 0;
}

.kb1n8bbsh {
  fill: var(--svg-color--cec4d7, #CEC4D7);
  fill-rule: evenodd;
  d: path("M30 23.59V24c0 .245-.044.479-.124.695l-10.644-6.773l.536-.844z");
}

.l49j1eq6d {
  width: 28px;
  height: 20px;
  x: 2px;
  y: 6px;
  rx: 2px;
}

.m-73omb5n {
  stop-color: var(--svg-color--e3c3c4, #E3C3C4);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mnljwzubi {
  stop-color: var(--svg-color--dcc8ef, #DCC8EF);
  stop-opacity: 0;
}

.n-cq5_bsc {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  d: path("M13.063 10.813a6.44 6.44 0 0 1 3.103 1.996c.273.315.396.728.396 1.144v4.235");
}

.nhqnhab9x {
  d: path("M27 6h1a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2h-1z");
}

.njy_ycceq {
  stop-color: var(--svg-color--dedede, #DEDEDE);
}

.o2n61ybfr {
  stop-color: var(--svg-color--e3c3c4, #E3C3C4);
  stop-opacity: 0.6;
}

.o9_8_xx8g {
  stop-color: var(--svg-color--e8e4e8, #E8E4E8);
  stop-opacity: 0;
}

.pfnd4sbfm {
  d: path("M2 8a2 2 0 0 1 2-2h1v20H4a2 2 0 0 1-2-2z");
}

.q--kb4b6f {
  fill: var(--svg-color--c2b4cb, #C2B4CB);
  fill-rule: evenodd;
  d: path("M2.124 24.695A2 2 0 0 1 2 24v-.41l10.232-6.512l.536.844z");
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.r27xxbb-p {
  fill: var(--svg-color--c5b9c4, #C5B9C4);
  fill-rule: evenodd;
  d: path("M2.121 7.313A2 2 0 0 0 2 8v.434l8.223 5.482l.554-.832z");
}

.reedtvb0j {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M16.131 22.794c.29.17.645.154.93-.023c2.1-1.31 5.608-3.945 7.011-7.46c2.046-4.544-2.77-8.093-6.09-5.484c-.364.286-.858.707-1.172 1.054a.3.3 0 0 1-.431.013c-.379-.4-.99-.978-1.399-1.255c-2.83-1.915-7.968.53-5.77 5.918c.803 2.416 4.746 5.955 6.921 7.237");
}

.sbotngyhu {
  d: path("M16.131 22.794c.29.17.645.154.93-.023c2.1-1.31 5.608-3.945 7.011-7.46c2.046-4.544-2.77-8.093-6.09-5.484c-.364.286-.858.707-1.172 1.054a.3.3 0 0 1-.431.013c-.379-.4-.99-.978-1.399-1.255c-2.83-1.915-7.968.53-5.77 5.918c.803 2.416 4.746 5.955 6.921 7.237");
}

.t2d3xoqjo {
  stop-color: var(--svg-color--e9e2ea, #E9E2EA);
}

.vif4eu13g {
  d: path("M2 8a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2z");
}

.vyoxszyru {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  d: path("M22.063 10.625c1.53 1.031 1.5 2.719 1.343 3.406");
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.xtuma4thw {
  stop-color: var(--svg-color--e1c0c2, #E1C0C2);
  stop-opacity: 0;
}

.ykbq5jngz {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.959 7.313h1V23.5h-1z");
}

.z1m7nccfk {
  stop-color: var(--svg-color--ff7033, #FF7033);
  stop-opacity: 0;
}

.z3iefsbma {
  stop-color: var(--svg-color--ff9e75, #FF9E75);
  stop-opacity: 0;
}

</style>
