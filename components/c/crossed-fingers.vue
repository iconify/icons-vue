<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wt9mi1h2d"/><path fill="url(#iwYXJHb)" class="n4_ejcb_c"/><path fill="url(#ikB1Hkb)" class="n4_ejcb_c"/><path fill="url(#iBhuckd)" class="n4_ejcb_c"/><path fill="url(#iDL2whc)" class="n4_ejcb_c"/><g filter="url(#icmZ2gc)"><path class="x_bps9pbg"/></g><g filter="url(#i0erpjb)"><path class="g6gqw2f9p"/><path fill="url(#iqeKGve)" class="jdz6qe6ks"/></g><g filter="url(#iaEOTtd)"><path class="qkysqpbec"/></g><g filter="url(#iFIijhb)"><path class="r55hzq8pb"/></g><g filter="url(#iSEQqbd)"><path class="yv9ts2m5s"/></g><path class="uekqqraua"/><path fill="url(#iIFNJKc)" class="dsrehybof"/><path fill="url(#i940Pzb)" class="dsrehybof"/><path fill="url(#ijiYJNU)" class="dsrehybof"/><path class="kdj39cn7p"/><path fill="url(#invSPnd)" class="n09w99brk"/><path fill="url(#ixBoZ2b)" class="n09w99brk"/><path fill="url(#ioHLpNe)" class="n09w99brk"/><path fill="url(#iXjsjBb)" class="n09w99brk"/><path fill="url(#ii1Xl8d)" class="n09w99brk"/><g filter="url(#iwK268c)"><path class="g2dxeb1_p"/></g><path fill="url(#ifTU9NQ)" class="acjos6pyv"/><path fill="url(#iQVn5Me)" class="acjos6pyv"/><path fill="url(#ihxAmPd)" class="acjos6pyv"/><path fill="url(#itajbtd)" class="acjos6pyv"/><path fill="url(#igx98jc)" class="acjos6pyv"/><path fill="url(#igtvsbM)" class="acjos6pyv"/><g filter="url(#iHr0ffd)"><rect class="yn8z6yo5z"/></g><g filter="url(#igIaDlA)"><rect class="qx-18r3jo"/></g><path fill="url(#iIuGRLb)" class="jdz6qe6ks"/><defs><radialGradient id="iwYXJHb" cx="0" cy="0" r="1" gradientTransform="rotate(-145.784 13.108 1.82)scale(7.55811 20.3298)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="pj13n70ey"/><stop offset=".979" class="szk74fb5v"/></radialGradient><radialGradient id="ikB1Hkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44892 .96594 -7.83612 -11.75422 19.739 11.473)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="ofg12ob8s"/><stop offset="1" class="gxely6nyw"/></radialGradient><radialGradient id="iBhuckd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.26935 1.63468 0 18.81 14.705)" gradientUnits="userSpaceOnUse"><stop class="idobb_p2w"/><stop offset="1" class="hkdvukbgx"/></radialGradient><radialGradient id="iDL2whc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86066 3.38083 -4.43947 -3.75643 25.423 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="frlutkb6f"/><stop offset="1" class="yv4y3090i"/></radialGradient><radialGradient id="iqeKGve" cx="0" cy="0" r="1" gradientTransform="rotate(124.461 5.12 14.798)scale(6.69216 4.75325)" gradientUnits="userSpaceOnUse"><stop class="iz_a6hbrt"/><stop offset="1" class="barbeyb5s"/></radialGradient><radialGradient id="i940Pzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.03619 -4.95249 0 8.227 10.393)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="r49q9ji7j"/><stop offset="1" class="xpfhebbtx"/></radialGradient><radialGradient id="ijiYJNU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 0 0 -3.75 10.486 12.602)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="x451lactv"/><stop offset="1" class="c1u7x5oci"/></radialGradient><radialGradient id="ixBoZ2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.09743 -5.03847 0 12.787 9.466)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="r49q9ji7j"/><stop offset="1" class="xpfhebbtx"/></radialGradient><radialGradient id="iXjsjBb" cx="0" cy="0" r="1" gradientTransform="rotate(136.337 7.235 6.485)scale(5.75098 4.25015)" gradientUnits="userSpaceOnUse"><stop class="y0na07-wu"/><stop offset="1" class="nshtk9bjl"/></radialGradient><radialGradient id="ii1Xl8d" cx="0" cy="0" r="1" gradientTransform="rotate(-160.408 8.834 6.361)scale(1.20388 1.54138)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="oy6pclelh"/><stop offset="1" class="msxhi--rk"/></radialGradient><radialGradient id="ifTU9NQ" cx="0" cy="0" r="1" gradientTransform="rotate(112.452 6.58 15.14)scale(7.08242 13.9049)" gradientUnits="userSpaceOnUse"><stop class="v01hembdp"/><stop offset="1" class="jwgexwdzr"/></radialGradient><radialGradient id="iQVn5Me" cx="0" cy="0" r="1" gradientTransform="matrix(1.73107 -3.34314 3.52287 1.82413 19.515 21.602)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="vgvuhcb5y"/><stop offset="1" class="fpg4gxw1t"/></radialGradient><radialGradient id="ihxAmPd" cx="0" cy="0" r="1" gradientTransform="rotate(-62.276 24.583 -3.56)scale(4.18903 7.85639)" gradientUnits="userSpaceOnUse"><stop class="vgvuhcb5y"/><stop offset=".822" class="fpg4gxw1t"/></radialGradient><radialGradient id="igx98jc" cx="0" cy="0" r="1" gradientTransform="rotate(38.885 -13 26.154)scale(4.31167 13.703)" gradientUnits="userSpaceOnUse"><stop class="b9d7idb_u"/><stop offset="1" class="yizzvizuv"/></radialGradient><radialGradient id="igtvsbM" cx="0" cy="0" r="1" gradientTransform="matrix(6.35543 -6.49599 8.06928 7.89468 19.084 22.485)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="inh6ngu7g"/><stop offset="1" class="h35cgjaov"/></radialGradient><radialGradient id="iIuGRLb" cx="0" cy="0" r="1" gradientTransform="rotate(-8.638 119.938 -27.13)scale(23.0503 24.1532)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="sm_4cg83z"/><stop offset=".931" class="dm28qntnt"/></radialGradient><filter id="icmZ2gc" width="9.747" height="10.915" x="16.697" y="1.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation="1"/></filter><filter id="i0erpjb" width="20.855" height="28.619" x="5.435" y="1.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.517647 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2190"/></filter><filter id="iaEOTtd" width="14.735" height="10.475" x="11.319" y="13.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation="1"/></filter><filter id="iFIijhb" width="7.158" height="8.635" x="4.988" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation=".5"/></filter><filter id="iSEQqbd" width="9.128" height="11.13" x="7.44" y="8.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation="1"/></filter><filter id="iwK268c" width="11.711" height="22.797" x="15.244" y=".615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation="1"/></filter><filter id="iHr0ffd" width="4.84" height="8.125" x="6.215" y="8.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation=".75"/></filter><filter id="igIaDlA" width="5.193" height="8.957" x="11.242" y="7.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2190" stdDeviation=".875"/></filter><linearGradient id="iIFNJKc" x1="5.435" x2="7.768" y1="13.259" y2="13.259" gradientUnits="userSpaceOnUse"><stop class="ru2o6-bpo"/><stop offset="1" class="vb-3gibpq"/></linearGradient><linearGradient id="invSPnd" x1="9.947" x2="12.32" y1="12.764" y2="12.764" gradientUnits="userSpaceOnUse"><stop class="ru2o6-bpo"/><stop offset="1" class="vb-3gibpq"/></linearGradient><linearGradient id="ioHLpNe" x1="17.928" x2="12.787" y1="12.701" y2="12.701" gradientUnits="userSpaceOnUse"><stop class="y0na07-wu"/><stop offset="1" class="nshtk9bjl"/></linearGradient><linearGradient id="itajbtd" x1="23.36" x2="22.007" y1="23.133" y2="19.4" gradientUnits="userSpaceOnUse"><stop class="rm9l-ebcb"/><stop offset="1" class="f6hzoq-2v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-fingers" /></template>
<style>
.acjos6pyv {
  d: path("M17.44 13.384a2.984 2.984 0 1 0 0 5.968h1.59a1 1 0 0 1 .788.386l2.044 2.621c1.17 1.5 3.577.673 3.577-1.23v-1.745a6 6 0 0 0-5.211-5.949a3 3 0 0 0-.554-.051z");
}

.b9d7idb_u {
  stop-color: var(--svg-color--e4a618, #E4A618);
}

.barbeyb5s {
  stop-color: var(--svg-color--ffc345, #FFC345);
  stop-opacity: 0;
}

.c1u7x5oci {
  stop-color: var(--svg-color--b96b14, #B96B14);
  stop-opacity: 0;
}

.dm28qntnt {
  stop-color: var(--svg-color--ffe74a, #FFE74A);
}

.dsrehybof {
  d: path("M5.435 11.567c0-1.43 1.25-2.59 2.792-2.59s2.79 1.16 2.79 2.59v2.383c0 1.43-1.249 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.f6hzoq-2v {
  stop-color: var(--svg-color--ffd338, #FFD338);
  stop-opacity: 0;
}

.fpg4gxw1t {
  stop-color: var(--svg-color--ef8049, #EF8049);
  stop-opacity: 0;
}

.frlutkb6f {
  stop-color: var(--svg-color--ffe64a, #FFE64A);
}

.ft5dv1b6b {
  fill: none;
}

.g2dxeb1_p {
  stroke: var(--svg-color--ffe144, #FFE144);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.244 3.615c2.11 2.245 4.895 6.194 5.22 9.602c.344 3.617.613 6.275.433 7.195");
}

.g6gqw2f9p {
  fill: var(--svg-color--ffb043, #FFB043);
  d: path("m5.623 20.725l-.188-5.114v-1.555h14.47c.01-.844-1.844-4.116-4.255-7.32c-1.421-1.891-.62-3.566.516-4.305c1.477-.961 3.219-.25 3.945.898c0 0 5.637 5.93 5.637 13.305c.127 4.64.031 5.397-1.219 7.86c-1.815 3.574-5.716 5.357-9.248 5.357c-5.812 0-9.47-4.14-9.658-9.126");
}

.gxely6nyw {
  stop-color: var(--svg-color--ca7112, #CA7112);
  stop-opacity: 0;
}

.h35cgjaov {
  stop-color: var(--svg-color--ffe64d, #FFE64D);
}

.hkdvukbgx {
  stop-color: var(--svg-color--ffd037, #FFD037);
  stop-opacity: 0;
}

.idobb_p2w {
  stop-color: var(--svg-color--ffd037, #FFD037);
}

.inh6ngu7g {
  stop-color: var(--svg-color--ffe64d, #FFE64D);
  stop-opacity: 0;
}

.iz_a6hbrt {
  stop-color: var(--svg-color--ffc345, #FFC345);
}

.jdz6qe6ks {
  d: path("m5.623 20.725l-.188-5.114v-1.555h14.47c.01-.844-1.844-4.116-4.255-7.32c-1.421-1.891-.62-3.566.516-4.305c1.477-.961 3.219-.25 3.945.898c0 0 5.637 5.93 5.637 13.305c.127 4.64.031 5.397-1.219 7.86c-1.815 3.574-5.716 5.357-9.248 5.357c-5.812 0-9.47-4.14-9.658-9.126");
}

.jwgexwdzr {
  stop-color: var(--svg-color--ffb043, #FFB043);
}

.kdj39cn7p {
  fill: var(--svg-color--f4b923, #F4B923);
  d: path("M9.947 10.817c0-1.646 1.272-2.98 2.84-2.98s2.84 1.334 2.84 2.98v2.743c0 1.646-1.272 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.msxhi--rk {
  stop-color: var(--svg-color--b86100, #B86100);
  stop-opacity: 0;
}

.n09w99brk {
  d: path("M9.947 10.817c0-1.646 1.272-2.98 2.84-2.98s2.84 1.334 2.84 2.98v2.743c0 1.646-1.272 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.n4_ejcb_c {
  d: path("M20.424 2.813c-2.136 2.179-4.64 5.149-5.516 8.633l-.223 2.766h5.032c1.031-1.823 2.812-5.32 4.574-7.305s.555-3.777-.066-4.308c-.43-.368-2.223-1.395-3.801.214");
}

.nshtk9bjl {
  stop-color: var(--svg-color--ffe032, #FFE032);
  stop-opacity: 0;
}

.ofg12ob8s {
  stop-color: var(--svg-color--ca7112, #CA7112);
}

.oy6pclelh {
  stop-color: var(--svg-color--b86100, #B86100);
}

.pj13n70ey {
  stop-color: var(--svg-color--d09937, #D09937);
  stop-opacity: 0;
}

.qkysqpbec {
  fill: var(--svg-color--d46d13, #D46D13);
  d: path("M16.455 15.009c-1.732 0-3.136 1.245-3.136 2.782s1.404 2.782 3.136 2.782h1.67c2.526 0 3.18.133 3.38.36l1.536-.178c1.23 1.4.995.652.995-1.123v-.504c0-2.84-1.56-3.711-4.65-4.071a3.6 3.6 0 0 0-.583-.048z");
}

.qx-18r3jo {
  width: 1.693px;
  height: 5.457px;
  x: 12.992px;
  y: 9.417px;
  fill: var(--svg-color--ffe439, #FFE439);
  rx: 0.847px;
}

.r49q9ji7j {
  stop-color: var(--svg-color--f2682c, #F2682C);
  stop-opacity: 0;
}

.r55hzq8pb {
  fill: var(--svg-color--a13e02, #A13E02);
  d: path("M5.988 12.41c0-1.254 1.155-2.271 2.579-2.271s2.579 1.017 2.579 2.272v2.09c0 1.256-1.155 2.273-2.579 2.273s-2.579-1.017-2.579-2.272z");
}

.rm9l-ebcb {
  stop-color: var(--svg-color--feae43, #FEAE43);
}

.ru2o6-bpo {
  stop-color: var(--svg-color--e79739, #E79739);
}

.sm_4cg83z {
  stop-color: var(--svg-color--ffe74a, #FFE74A);
  stop-opacity: 0;
}

.szk74fb5v {
  stop-color: var(--svg-color--d09937, #D09937);
}

.uekqqraua {
  fill: var(--svg-color--f3a923, #F3A923);
  d: path("M5.435 11.567c0-1.43 1.25-2.59 2.792-2.59s2.79 1.16 2.79 2.59v2.383c0 1.43-1.249 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.v01hembdp {
  stop-color: var(--svg-color--ffe749, #FFE749);
}

.vb-3gibpq {
  stop-color: var(--svg-color--e79739, #E79739);
  stop-opacity: 0;
}

.vgvuhcb5y {
  stop-color: var(--svg-color--ef8049, #EF8049);
}

.wt9mi1h2d {
  fill: var(--svg-color--f6b41e, #F6B41E);
  d: path("M20.424 2.813c-2.136 2.179-4.64 5.149-5.516 8.633l-.223 2.766h5.032c1.031-1.823 2.812-5.32 4.574-7.305s.555-3.777-.066-4.308c-.43-.368-2.223-1.395-3.801.214");
}

.x_bps9pbg {
  stroke: var(--svg-color--ffe144, #FFE144);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.194 4.562c-.929 1.152-1.947 2.62-3.247 4.416");
}

.x451lactv {
  stop-color: var(--svg-color--b96b14, #B96B14);
}

.xpfhebbtx {
  stop-color: var(--svg-color--f2682c, #F2682C);
}

.y0na07-wu {
  stop-color: var(--svg-color--ffe032, #FFE032);
}

.yizzvizuv {
  stop-color: var(--svg-color--e4a618, #E4A618);
  stop-opacity: 0;
}

.yn8z6yo5z {
  width: 1.84px;
  height: 5.125px;
  x: 7.715px;
  y: 9.884px;
  fill: var(--svg-color--fbc131, #FBC131);
  rx: 0.92px;
}

.yv4y3090i {
  stop-color: var(--svg-color--ffe64a, #FFE64A);
  stop-opacity: 0;
}

.yv9ts2m5s {
  fill: var(--svg-color--ae4b04, #AE4B04);
  d: path("M9.44 12.817c0-1.349 1.148-2.442 2.564-2.442s2.564 1.093 2.564 2.442v2.246c0 1.349-1.148 2.442-2.564 2.442S9.44 16.412 9.44 15.064z");
}

</style>
