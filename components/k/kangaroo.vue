<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixFDMTd)"><path class="vhz0r03_d"/><path fill="url(#iBHeUsd)" class="l88y3goco"/><path fill="url(#iHNemnb)" class="l88y3goco"/><path fill="url(#iUcMKEO)" class="l88y3goco"/><path fill="url(#iMmZXse)" class="l88y3goco"/><path fill="url(#iFFW3Md)" class="l88y3goco"/></g><path fill="url(#iGCDm3d)" class="cpm2hz9ie"/><path fill="url(#iy3Lwmd)" class="bqxf6lqvv"/><g filter="url(#i2clZUo)"><path class="ir4z7bb_e"/></g><path fill="url(#iePLuYb)" class="s81om7gmf"/><path fill="url(#iIFOTwd)" class="s81om7gmf"/><path fill="url(#i2x6Fce)" class="s81om7gmf"/><path fill="url(#iuD5cbc)" class="s81om7gmf"/><path fill="url(#iSopzYT)" class="s81om7gmf"/><path fill="url(#ifJLBjc)" class="xqlzryt3q"/><path fill="url(#iskLFae)" class="xqlzryt3q"/><path fill="url(#iFixigd)" class="xqlzryt3q"/><path fill="url(#iaxFzke)" class="u5k4w9q4e"/><path fill="url(#iFXhIac)" class="u5k4w9q4e"/><path fill="url(#i2wYuQe)" class="u5k4w9q4e"/><g filter="url(#iyCnOSM)"><path stroke="url(#iEC8Dyc)" class="mwfilwb5b"/></g><g filter="url(#i4Szhtb)"><ellipse fill="url(#izm8Gpe)" transform="rotate(45 19.522 11.215)" class="np9ii-bap"/></g><g filter="url(#ibNnEzb)"><rect fill="url(#ibbS14d)" transform="rotate(-30 13.677 15.885)" class="gw1wi3pqc"/></g><g filter="url(#ioVonrb)"><rect transform="rotate(-30 17.357 18.45)" class="izs-k-x-h"/></g><path fill="url(#igUXDvd)" class="qp-5ol-zw"/><path fill="url(#io3StXb)" class="qp-5ol-zw"/><path fill="url(#isZYUKe)" class="qp-5ol-zw"/><path class="rs8eujbpc"/><path fill="url(#iMB3y9f)" class="rtm2vpz0a"/><path fill="url(#iD26VFb)" class="rtm2vpz0a"/><path fill="url(#ivUNRte)" class="rtm2vpz0a"/><path fill="url(#ihBwbPc)" class="rtm2vpz0a"/><defs><radialGradient id="iBHeUsd" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -4.5564 6.0665 4.7432 5.927 16.91)" gradientUnits="userSpaceOnUse"><stop class="x-yi25bfg"/><stop offset="1" class="zpmbn0lko"/></radialGradient><radialGradient id="iHNemnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.8689 -2.95762 0 23.152 20.637)" gradientUnits="userSpaceOnUse"><stop class="hjoxs5bzb"/><stop offset="1" class="bsjk3xf1d"/></radialGradient><radialGradient id="iUcMKEO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65894 23.2265 0 26.866 25.267)" gradientUnits="userSpaceOnUse"><stop class="hjoxs5bzb"/><stop offset="1" class="bsjk3xf1d"/></radialGradient><radialGradient id="iMmZXse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.4624 7.49182 0 25.886 26.48)" gradientUnits="userSpaceOnUse"><stop class="v7r08abro"/><stop offset="1" class="adluebbpc"/></radialGradient><radialGradient id="iFFW3Md" cx="0" cy="0" r="1" gradientTransform="matrix(3.47558 -2.30823 1.0931 1.64593 2.44 10.935)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="efj4t7bvs"/><stop offset=".869" class="adluebbpc"/></radialGradient><radialGradient id="iy3Lwmd" cx="0" cy="0" r="1" gradientTransform="rotate(50.521 .46 12.652)scale(1.92967 4.66869)" gradientUnits="userSpaceOnUse"><stop class="f6nxteydk"/><stop offset="1" class="nr9ophb2t"/></radialGradient><radialGradient id="iIFOTwd" cx="0" cy="0" r="1" gradientTransform="rotate(10.413 -105.272 84.467)scale(4.55463 2.18941)" gradientUnits="userSpaceOnUse"><stop class="v7r08abro"/><stop offset="1" class="adluebbpc"/></radialGradient><radialGradient id="iuD5cbc" cx="0" cy="0" r="1" gradientTransform="rotate(34.312 -37.863 34.822)scale(2.82301 2.4551)" gradientUnits="userSpaceOnUse"><stop class="kz2_x5z0v"/><stop offset="1" class="mv2-ymb1o"/></radialGradient><radialGradient id="iSopzYT" cx="0" cy="0" r="1" gradientTransform="matrix(5.2174 -.75207 .4525 3.13918 13.873 18.64)" gradientUnits="userSpaceOnUse"><stop class="f3vukhs9w"/><stop offset="1" class="wwq8alblk"/></radialGradient><radialGradient id="ifJLBjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.38 7.336)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iskLFae" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 1.78 4.929)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iaxFzke" cx="0" cy="0" r="1" gradientTransform="matrix(-.434 .57026 -.5162 -.39286 2.691 8.336)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iFXhIac" cx="0" cy="0" r="1" gradientTransform="matrix(-.28376 .24553 -.21467 -.2481 2.734 8.373)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="izm8Gpe" cx="0" cy="0" r="1" gradientTransform="matrix(.12036 7.69658 -12.82013 .20048 19.402 8.407)" gradientUnits="userSpaceOnUse"><stop class="luub37oiu"/><stop offset="1" class="a24xkkb2j"/></radialGradient><radialGradient id="ivUNRte" cx="0" cy="0" r="1" gradientTransform="matrix(1.22083 .00732 -.00682 1.13751 10.087 19.067)" gradientUnits="userSpaceOnUse"><stop class="xepfrob6y"/><stop offset="1" class="boh9k5b7g"/></radialGradient><linearGradient id="iGCDm3d" x1="13.328" x2="13.3" y1="17.636" y2="15.04" gradientUnits="userSpaceOnUse"><stop class="efj4t7bvs"/><stop offset=".918" class="adluebbpc"/></linearGradient><linearGradient id="iePLuYb" x1="21.288" x2="15.011" y1="11.842" y2="15.185" gradientUnits="userSpaceOnUse"><stop class="zcij52bpz"/><stop offset="1" class="iyg0thbwx"/></linearGradient><linearGradient id="i2x6Fce" x1="19.139" x2="17.945" y1="25.884" y2="23.708" gradientUnits="userSpaceOnUse"><stop class="v7r08abro"/><stop offset=".819" class="adluebbpc"/></linearGradient><linearGradient id="iFixigd" x1="6.132" x2="5.788" y1="7.104" y2="6.885" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="i2wYuQe" x1="2.429" x2="2.073" y1="8.101" y2="7.863" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iEC8Dyc" x1="24.681" x2="33.102" y1="19.83" y2="19.83" gradientUnits="userSpaceOnUse"><stop class="luub37oiu"/><stop offset="1" class="a24xkkb2j"/></linearGradient><linearGradient id="ibbS14d" x1="21.669" x2="8.263" y1="18.241" y2="18.132" gradientUnits="userSpaceOnUse"><stop class="luub37oiu"/><stop offset="1" class="a24xkkb2j"/></linearGradient><linearGradient id="igUXDvd" x1="22.3" x2="20.749" y1="18.415" y2="15.767" gradientUnits="userSpaceOnUse"><stop class="wrcf6sbkj"/><stop offset="1" class="m5sr9kb8x"/></linearGradient><linearGradient id="io3StXb" x1="20.97" x2="20.201" y1="19" y2="17.686" gradientUnits="userSpaceOnUse"><stop class="v7r08abro"/><stop offset=".575" class="adluebbpc"/></linearGradient><linearGradient id="isZYUKe" x1="22.647" x2="20.201" y1="19.308" y2="17.686" gradientUnits="userSpaceOnUse"><stop class="v7r08abro"/><stop offset=".575" class="adluebbpc"/></linearGradient><linearGradient id="iMB3y9f" x1="7.727" x2="7.727" y1="21.469" y2="16.11" gradientUnits="userSpaceOnUse"><stop class="l4t2mnrdg"/><stop offset="1" class="xe_pqrbwg"/></linearGradient><linearGradient id="iD26VFb" x1="8.922" x2="9.441" y1="21.245" y2="18.785" gradientUnits="userSpaceOnUse"><stop class="v7r08abro"/><stop offset=".465" class="adluebbpc"/></linearGradient><linearGradient id="ihBwbPc" x1="9.798" x2="9.798" y1="15.358" y2="16.623" gradientUnits="userSpaceOnUse"><stop class="w76-pwl2j"/><stop offset="1" class="ecz-lb2kq"/></linearGradient><filter id="ixFDMTd" width="28.2" height="21.23" x="2" y="2.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.443137 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4480"/></filter><filter id="i2clZUo" width="10.42" height="17.352" x="13.04" y="11.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.443137 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4480"/></filter><filter id="iyCnOSM" width="6.795" height="9.261" x="23.431" y="13.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4480" stdDeviation=".5"/></filter><filter id="i4Szhtb" width="16.672" height="16.673" x="11.186" y="2.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4480" stdDeviation="1.5"/></filter><filter id="ibNnEzb" width="12.259" height="10.733" x="12.527" y="10.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4480" stdDeviation="1"/></filter><filter id="ioVonrb" width="4.789" height="6.208" x="16.513" y="17.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4480" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:kangaroo" /></template>
<style>
.a24xkkb2j {
  stop-color: var(--svg-color--ffc78f, #FFC78F);
  stop-opacity: 0;
}

.adluebbpc {
  stop-color: var(--svg-color--de6e8e, #DE6E8E);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.boh9k5b7g {
  stop-color: var(--svg-color--c6724f, #C6724F);
  stop-opacity: 0;
}

.bqxf6lqvv {
  d: path("M9 5.987v.01h1.01c1.1 0 1.99-.89 1.99-1.99v-.01h-1.01c-1.1 0-1.99.89-1.99 1.99");
}

.bsjk3xf1d {
  stop-color: var(--svg-color--df8366, #DF8366);
  stop-opacity: 0;
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cpm2hz9ie {
  d: path("M20.341 13.512v.295l-1.2-.18v3.37h-6.72v-.005H8.002a3.215 3.215 0 0 1-3.042-3.205v-.275z");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ecz-lb2kq {
  stop-color: var(--svg-color--e39f65, #E39F65);
  stop-opacity: 0;
}

.efj4t7bvs {
  stop-color: var(--svg-color--bf5472, #BF5472);
}

.f3vukhs9w {
  stop-color: var(--svg-color--e29a73, #E29A73);
}

.f6nxteydk {
  stop-color: var(--svg-color--b36f53, #B36F53);
}

.ft5dv1b6b {
  fill: none;
}

.gw1wi3pqc {
  width: 8.817px;
  height: 4.647px;
  x: 13.677px;
  y: 15.885px;
  rx: 2.324px;
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hjoxs5bzb {
  stop-color: var(--svg-color--df8366, #DF8366);
}

.ir4z7bb_e {
  fill: var(--svg-color--e4a063, #E4A063);
  d: path("m19.51 19.587l2.1-1.21c1.96-1.13 2.35-3.8.78-5.45a3.504 3.504 0 0 0-4.28-.62l-3.24 1.87c-1.67.97-2.25 3.11-1.28 4.78a3.49 3.49 0 0 0 3.11 1.75l.8 1.39l-2.73 1.52c-1.07.6-1.73 1.72-1.73 2.95v1.53c0 .44.32.83.76.89c.39.05.75-.16.9-.51l.58-1.32c.19-.43.5-.66.62-.73l4.1-2.3c.43-.24.73-.63.86-1.1s.07-.96-.18-1.39z");
}

.iyg0thbwx {
  stop-color: var(--svg-color--f5b97f, #F5B97F);
  stop-opacity: 0;
}

.izs-k-x-h {
  width: 0.85px;
  height: 4.727px;
  x: 17.357px;
  y: 18.451px;
  fill: var(--svg-color--ffc78f, #FFC78F);
  rx: 0.425px;
}

.kz2_x5z0v {
  stop-color: var(--svg-color--e08f78, #E08F78);
}

.l4t2mnrdg {
  stop-color: var(--svg-color--d6876c, #D6876C);
}

.l88y3goco {
  d: path("M2 8.527c.02.81.68 1.47 1.5 1.47h1.21a.25.25 0 0 1 .25.25v3.54c0 1.77 1.44 3.21 3.22 3.21h1.047c.08 0 .12.09.06.15l-.62.62c-.36.36-.58.85-.57 1.36a1.93 1.93 0 0 0 1.92 1.87h.56c.42 0 .76-.34.75-.76a.77.77 0 0 0-.77-.74h-.55a.4.4 0 0 1-.38-.26c-.05-.15-.01-.3.09-.4l.8-.8c.25-.25.44-.53.58-.84c.05-.12.17-.2.31-.2h7.733v-3.37l3.86.58v6.27c0 1.92 1.53 3.53 3.45 3.55c1.95.03 3.55-1.55 3.55-3.5v-7.09c0-.24-.2-.44-.44-.44c-.86 0-1.56.7-1.56 1.56v4.35c0 .55-.45 1-1 1s-1-.45-1-1v-5.58c0-4.44-3.52-8.13-7.95-8.23c-3.69-.09-6.43 2.42-7.91 5.55c-.1.21-.26.45-.54.45a.61.61 0 0 1-.6-.6v-4.5h1.01c1.1 0 1.99-.89 1.99-1.99v-.7c0-.17-.14-.31-.31-.31h-1.7c-1.1 0-1.99.74-1.99 1.84c0 .09-.07.16-.16.16H6.02c-.59 0-1.1.41-1.22.99l-.09.41c-.08.35-.38.6-.74.6h-.44c-.84 0-1.55.69-1.53 1.53");
}

.luub37oiu {
  stop-color: var(--svg-color--ffc78f, #FFC78F);
}

.m5sr9kb8x {
  stop-color: var(--svg-color--e29e68, #E29E68);
  stop-opacity: 0;
}

.mv2-ymb1o {
  stop-color: var(--svg-color--e08f78, #E08F78);
  stop-opacity: 0;
}

.mwfilwb5b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M24.681 15.74v4c0 1.187.961 2.148 2.147 2.148v0a2.147 2.147 0 0 0 2.148-2.147v-4.614");
}

.np9ii-bap {
  cx: 19.522px;
  cy: 11.215px;
  rx: 5.749px;
  ry: 4.889px;
}

.nr9ophb2t {
  stop-color: var(--svg-color--bb7a5c, #BB7A5C);
}

.qp-5ol-zw {
  d: path("m21.61 18.377l-2.1 1.21l.126.22l-1.498-2.566l5.094-2.84a3.5 3.5 0 0 1-1.622 3.976");
}

.rs8eujbpc {
  fill: var(--svg-color--de9b69, #DE9B69);
  d: path("M11.5 16.997v-1.783H9.593v1.28a.81.81 0 0 1-.282.614a.1.1 0 0 1-.024.039l-.62.62c-.36.36-.58.85-.57 1.36a1.93 1.93 0 0 0 1.92 1.87h.56c.42 0 .76-.34.75-.76a.77.77 0 0 0-.77-.74h-.55a.4.4 0 0 1-.38-.26c-.05-.15-.01-.3.09-.4l.8-.8c.25-.25.44-.53.58-.84c.05-.12.17-.2.31-.2z");
}

.rtm2vpz0a {
  d: path("M11.5 16.997v-1.783H9.593v1.28a.81.81 0 0 1-.282.614a.1.1 0 0 1-.024.039l-.62.62c-.36.36-.58.85-.57 1.36a1.93 1.93 0 0 0 1.92 1.87h.56c.42 0 .76-.34.75-.76a.77.77 0 0 0-.77-.74h-.55a.4.4 0 0 1-.38-.26c-.05-.15-.01-.3.09-.4l.8-.8c.25-.25.44-.53.58-.84c.05-.12.17-.2.31-.2z");
}

.s81om7gmf {
  d: path("m19.51 19.587l2.1-1.21c1.96-1.13 2.35-3.8.78-5.45a3.504 3.504 0 0 0-4.28-.62l-3.24 1.87c-1.67.97-2.25 3.11-1.28 4.78a3.49 3.49 0 0 0 3.11 1.75l.8 1.39l-2.73 1.52c-1.07.6-1.73 1.72-1.73 2.95v1.53c0 .44.32.83.76.89c.39.05.75-.16.9-.51l.58-1.32c.19-.43.5-.66.62-.73l4.1-2.3c.43-.24.73-.63.86-1.1s.07-.96-.18-1.39z");
}

.u5k4w9q4e {
  d: path("M2.09 9.006a1.5 1.5 0 0 1-.09-.48a1.4 1.4 0 0 1 .09-.533h.48c.275 0 .498.222.498.497v.019a.5.5 0 0 1-.497.497z");
}

.v7r08abro {
  stop-color: var(--svg-color--de6e8e, #DE6E8E);
}

.vhz0r03_d {
  fill: var(--svg-color--e4a063, #E4A063);
  d: path("M2 8.527c.02.81.68 1.47 1.5 1.47h1.21a.25.25 0 0 1 .25.25v3.54c0 1.77 1.44 3.21 3.22 3.21h1.047c.08 0 .12.09.06.15l-.62.62c-.36.36-.58.85-.57 1.36a1.93 1.93 0 0 0 1.92 1.87h.56c.42 0 .76-.34.75-.76a.77.77 0 0 0-.77-.74h-.55a.4.4 0 0 1-.38-.26c-.05-.15-.01-.3.09-.4l.8-.8c.25-.25.44-.53.58-.84c.05-.12.17-.2.31-.2h7.733v-3.37l3.86.58v6.27c0 1.92 1.53 3.53 3.45 3.55c1.95.03 3.55-1.55 3.55-3.5v-7.09c0-.24-.2-.44-.44-.44c-.86 0-1.56.7-1.56 1.56v4.35c0 .55-.45 1-1 1s-1-.45-1-1v-5.58c0-4.44-3.52-8.13-7.95-8.23c-3.69-.09-6.43 2.42-7.91 5.55c-.1.21-.26.45-.54.45a.61.61 0 0 1-.6-.6v-4.5h1.01c1.1 0 1.99-.89 1.99-1.99v-.7c0-.17-.14-.31-.31-.31h-1.7c-1.1 0-1.99.74-1.99 1.84c0 .09-.07.16-.16.16H6.02c-.59 0-1.1.41-1.22.99l-.09.41c-.08.35-.38.6-.74.6h-.44c-.84 0-1.55.69-1.53 1.53");
}

.w76-pwl2j {
  stop-color: var(--svg-color--e39f65, #E39F65);
}

.wrcf6sbkj {
  stop-color: var(--svg-color--e29e68, #E29E68);
}

.wwq8alblk {
  stop-color: var(--svg-color--e29a73, #E29A73);
  stop-opacity: 0;
}

.x-yi25bfg {
  stop-color: var(--svg-color--d8966e, #D8966E);
}

.xe_pqrbwg {
  stop-color: var(--svg-color--d6876c, #D6876C);
  stop-opacity: 0;
}

.xepfrob6y {
  stop-color: var(--svg-color--c6724f, #C6724F);
}

.xqlzryt3q {
  d: path("M6.23 7.997a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.zcij52bpz {
  stop-color: var(--svg-color--f1b378, #F1B378);
}

.zpmbn0lko {
  stop-color: var(--svg-color--d8966e, #D8966E);
  stop-opacity: 0;
}

</style>
