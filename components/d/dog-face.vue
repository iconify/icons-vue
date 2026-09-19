<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ilHLh0d)" class="ztdzxdbjq"/><rect fill="url(#ipJWOGZ)" class="ztdzxdbjq"/><rect fill="url(#iFUosKb)" class="ztdzxdbjq"/><rect fill="url(#iZQ0Gte)" class="ztdzxdbjq"/><rect fill="url(#iuKOSDc)" class="ztdzxdbjq"/><rect fill="url(#ifTU6rK)" class="ztdzxdbjq"/><rect fill="url(#iKJzEdb)" class="ztdzxdbjq"/><rect fill="url(#iiO6Qic)" class="ztdzxdbjq"/><rect fill="url(#iIV4R3L)" class="ztdzxdbjq"/><rect fill="url(#iPTjJ2b)" class="ztdzxdbjq"/><g filter="url(#iBa1htd)"><path fill="url(#i6RHWJc)" class="bxw28xbwr"/></g><g filter="url(#imPxiLc)"><path class="keylzackq"/></g><path fill="url(#iCAcKyc)" class="a4q6f1bqf"/><path fill="url(#i10HqYc)" class="a4q6f1bqf"/><path fill="url(#iHlXjtu)" class="a4q6f1bqf"/><g filter="url(#iaAL8Pe)"><path fill="url(#i3qJCpe)" class="p9-t1dpkp"/></g><g filter="url(#iUHfNSd)"><path fill="url(#ikr0CNe)" class="x_p3b_8bt"/></g><g filter="url(#iWEmjfd)"><path class="wara-mb-k"/></g><path fill="url(#idQRtfd)" class="qo2bddcqz"/><path fill="url(#i5bUiOb)" class="qo2bddcqz"/><path stroke="url(#iBfBmAb)" class="ozd3t4bxf"/><path stroke="url(#ixQisyd)" class="ozd3t4bxf"/><path fill="url(#iWcOfId)" class="fx3bet5ri"/><path fill="url(#i5YZH8c)" class="ze25ljb8i"/><path fill="url(#i5wPZVb)" class="ze25ljb8i"/><path fill="url(#idxiO7b)" class="ze25ljb8i"/><path fill="url(#iNBRd9i)" class="ze25ljb8i"/><path fill="url(#iwL7NSb)" class="ze25ljb8i"/><path fill="url(#iRAtRNb)" class="yl574yboh"/><path fill="url(#inmVZiU)" class="yl574yboh"/><path fill="url(#iYQEkgd)" class="yl574yboh"/><path fill="url(#ihYxO8c)" class="yl574yboh"/><g filter="url(#iperWPd)"><rect class="jv9b3vbrt"/></g><rect fill="url(#i5OBPze)" class="k-40b3b-z"/><rect fill="url(#iwVuKLC)" class="k-40b3b-z"/><g filter="url(#iKOvbte)"><path class="iv5dqfb8a"/></g><rect fill="url(#isA18UC)" class="qw8lpswdy"/><rect fill="url(#iT5vwGF)" class="qw8lpswdy"/><g filter="url(#iw5qCue)"><path class="predy65-q"/></g><path fill="url(#isOm8te)" class="ac2b2jbcv"/><path fill="url(#inmw5ye)" class="ac2b2jbcv"/><path fill="url(#iLtlPpd)" class="ac2b2jbcv"/><g filter="url(#iFZ1nLe)"><ellipse transform="rotate(-41.998 17.112 17.647)" class="anjp-37hl"/></g><g filter="url(#iKsBlsb)"><path stroke="url(#i1AqGme)" class="sbumcdl_y"/></g><g filter="url(#i2QGRlb)"><path stroke="url(#iRAoqdc)" class="q62fi9_ow"/></g><defs><linearGradient id="ilHLh0d" x1="15.969" x2="15.969" y1="6.037" y2="31.443" gradientUnits="userSpaceOnUse"><stop class="t2rn8x8sh"/><stop offset="1" class="w7veipeoo"/></linearGradient><linearGradient id="ipJWOGZ" x1="2.844" x2="7.656" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="a61ui5bws"/><stop offset="1" class="i7h39qb_i"/></linearGradient><linearGradient id="iFUosKb" x1="31.781" x2="24.156" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="kycpeysdb"/><stop offset="1" class="znovzgb7k"/></linearGradient><linearGradient id="iZQ0Gte" x1="15.969" x2="15.969" y1="21.287" y2="31.475" gradientUnits="userSpaceOnUse"><stop class="g9nurmghy"/><stop offset="1" class="hqf834fqu"/></linearGradient><linearGradient id="iuKOSDc" x1="15.969" x2="15.969" y1="26.537" y2="27.319" gradientUnits="userSpaceOnUse"><stop class="cw88l5bek"/><stop offset="1" class="nwodxjbni"/></linearGradient><linearGradient id="iPTjJ2b" x1="15.171" x2="15.171" y1="3.733" y2="6.415" gradientUnits="userSpaceOnUse"><stop class="xbpiv709r"/><stop offset="1" class="znovzgb7k"/></linearGradient><linearGradient id="i6RHWJc" x1="27.375" x2="27.775" y1="21.723" y2="4.745" gradientUnits="userSpaceOnUse"><stop class="kycpeysdb"/><stop offset="1" class="znovzgb7k"/></linearGradient><linearGradient id="i3qJCpe" x1="14.219" x2="14.219" y1="21.225" y2="28.412" gradientUnits="userSpaceOnUse"><stop class="d7vidkbbw"/><stop offset="1" class="dozz6qlkd"/></linearGradient><linearGradient id="ikr0CNe" x1="20.253" x2="15.594" y1="29.594" y2="29.693" gradientUnits="userSpaceOnUse"><stop offset=".438" class="mo0vjqb5x"/><stop offset=".948" class="iqcsp1b3j"/></linearGradient><linearGradient id="i5bUiOb" x1="12.5" x2="14.345" y1="24.256" y2="23.838" gradientUnits="userSpaceOnUse"><stop class="fnwxn0mja"/><stop offset="1" class="bldy_ccyg"/></linearGradient><linearGradient id="ixQisyd" x1="16.156" x2="16.596" y1="19.522" y2="21.124" gradientUnits="userSpaceOnUse"><stop class="b7bzk2bty"/><stop offset="1" class="c9x45bcoc"/></linearGradient><linearGradient id="i5YZH8c" x1="7.609" x2="2.813" y1="4.094" y2="15.6" gradientUnits="userSpaceOnUse"><stop class="ubxwtl1un"/><stop offset="1" class="mqmjd8mtb"/></linearGradient><linearGradient id="i5wPZVb" x1=".719" x2="4.406" y1="11.35" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="ezabbtb7o"/><stop offset="1" class="k5sycnb3l"/></linearGradient><linearGradient id="idxiO7b" x1="7.969" x2="6.875" y1="12.537" y2="11.694" gradientUnits="userSpaceOnUse"><stop offset=".208" class="ezabbtb7o"/><stop offset="1" class="k5sycnb3l"/></linearGradient><linearGradient id="iNBRd9i" x1="3.75" x2="5.063" y1="18.35" y2="12.662" gradientUnits="userSpaceOnUse"><stop class="au-fhtaxh"/><stop offset="1" class="k5sycnb3l"/></linearGradient><linearGradient id="iRAtRNb" x1="24.297" x2="29.094" y1="4.094" y2="15.6" gradientUnits="userSpaceOnUse"><stop class="ubxwtl1un"/><stop offset="1" class="mqmjd8mtb"/></linearGradient><linearGradient id="inmVZiU" x1="22.719" x2="25.969" y1="13.537" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="ezabbtb7o"/><stop offset="1" class="k5sycnb3l"/></linearGradient><linearGradient id="iYQEkgd" x1="28.156" x2="26.844" y1="18.35" y2="12.662" gradientUnits="userSpaceOnUse"><stop class="au-fhtaxh"/><stop offset="1" class="k5sycnb3l"/></linearGradient><linearGradient id="i5OBPze" x1="14.202" x2="11.995" y1="13.498" y2="13.498" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iwVuKLC" x1="11.995" x2="11.995" y1="15.092" y2="14.254" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vylhu7i4w"/><stop offset="1" class="ueu24dben"/></linearGradient><linearGradient id="isA18UC" x1="20.186" x2="17.98" y1="13.498" y2="13.498" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iT5vwGF" x1="17.98" x2="17.98" y1="15.092" y2="14.254" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vylhu7i4w"/><stop offset="1" class="ueu24dben"/></linearGradient><linearGradient id="isOm8te" x1="17.406" x2="14.469" y1="16.725" y2="19.662" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iLtlPpd" x1="16.375" x2="16.375" y1="18.147" y2="16.428" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="i1AqGme" x1="30.75" x2="30.75" y1="8.881" y2="16.381" gradientUnits="userSpaceOnUse"><stop class="f7amp4ngb"/><stop offset="1" class="o97hrtb5f"/></linearGradient><linearGradient id="iRAoqdc" x1="11.266" x2="7.391" y1="6.459" y2="12.209" gradientUnits="userSpaceOnUse"><stop class="pmm1ixbmq"/><stop offset="1" class="i2f0b7sju"/></linearGradient><radialGradient id="ifTU6rK" cx="0" cy="0" r="1" gradientTransform="matrix(1.93745 7.8125 -6.98186 1.73146 2.032 12.163)" gradientUnits="userSpaceOnUse"><stop class="a61ui5bws"/><stop offset="1" class="i7h39qb_i"/></radialGradient><radialGradient id="iKJzEdb" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8125 0 0 -8.28742 15.969 23.037)" gradientUnits="userSpaceOnUse"><stop class="butij_fdk"/><stop offset="1" class="ip48neb1a"/></radialGradient><radialGradient id="iiO6Qic" cx="0" cy="0" r="1" gradientTransform="rotate(87.745 -5.404 20.051)scale(7.94365 6.9459)" gradientUnits="userSpaceOnUse"><stop class="butij_fdk"/><stop offset="1" class="ip48neb1a"/></radialGradient><radialGradient id="iIV4R3L" cx="0" cy="0" r="1" gradientTransform="matrix(2.70183 7.73596 -17.76422 6.20428 12.469 5)" gradientUnits="userSpaceOnUse"><stop class="gk-ruvbdr"/><stop offset="1" class="znovzgb7k"/></radialGradient><radialGradient id="iCAcKyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.625 -24.0312 0 16 18.537)" gradientUnits="userSpaceOnUse"><stop class="h0o4w5dba"/><stop offset=".318" class="oqncn45bc"/><stop offset=".896" class="lieg0x_od"/></radialGradient><radialGradient id="i10HqYc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.49999 8.6251 -8.8256 -10.74409 18.469 19.975)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="r7590ybyk"/><stop offset="1" class="lieg0x_od"/></radialGradient><radialGradient id="iHlXjtu" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0625 4.25 -5.54527 -3.99585 23.094 16.975)" gradientUnits="userSpaceOnUse"><stop class="ce374hbpu"/><stop offset="1" class="j6m-qsbfd"/></radialGradient><radialGradient id="idQRtfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.25 -2.83974 2.55574 14.235 22.756)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".653" class="b7bzk2bty"/><stop offset="1" class="uka5n8bbu"/></radialGradient><radialGradient id="iBfBmAb" cx="0" cy="0" r="1" gradientTransform="rotate(132.556 3.954 15.215)scale(1.81361 4.34755)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".508" class="b7bzk2bty"/><stop offset=".902" class="uka5n8bbu"/></radialGradient><radialGradient id="iWcOfId" cx="0" cy="0" r="1" gradientTransform="matrix(-2.625 2.71874 -1.36643 -1.31931 14.75 21.178)" gradientUnits="userSpaceOnUse"><stop class="kvzluubyw"/><stop offset="1" class="xz33o5bwi"/></radialGradient><radialGradient id="iwL7NSb" cx="0" cy="0" r="1" gradientTransform="rotate(125.218 5.357 3.394)scale(9.10379 9.64599)" gradientUnits="userSpaceOnUse"><stop class="b279wb47z"/><stop offset="1" class="v3e0u_bef"/></radialGradient><radialGradient id="ihYxO8c" cx="0" cy="0" r="1" gradientTransform="rotate(-173.904 16.768 4.453)scale(6.47411 6.85969)" gradientUnits="userSpaceOnUse"><stop class="b279wb47z"/><stop offset="1" class="v3e0u_bef"/></radialGradient><radialGradient id="inmw5ye" cx="0" cy="0" r="1" gradientTransform="rotate(135.864 4.598 12.128)scale(2.19891 4.04729)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="ueu24dben"/><stop offset=".956" class="vylhu7i4w"/></radialGradient><filter id="iBa1htd" width="7.219" height="18.156" x="22.188" y="7.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation="1.25"/></filter><filter id="imPxiLc" width="11.855" height="19.753" x="17.346" y="3.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation="1"/></filter><filter id="iaAL8Pe" width="6.016" height="8.094" x="12.961" y="21.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.841667 0 0 0 0 0.164826 0 0 0 0 0.552771 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_1654"/></filter><filter id="iUHfNSd" width="4.019" height="8.222" x="15.194" y="22.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".2"/></filter><filter id="iWEmjfd" width="6.211" height="3.705" x="12.863" y="21.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".25"/></filter><filter id="iperWPd" width="3.077" height="4.577" x="10.961" y="11.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".4"/></filter><filter id="iKOvbte" width=".8" height="2.393" x="12.821" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".15"/></filter><filter id="iw5qCue" width=".8" height="2.393" x="18.805" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".15"/></filter><filter id="iFZ1nLe" width="1.591" height="1.622" x="16.317" y="16.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".25"/></filter><filter id="iKsBlsb" width="1.7" height="9.75" x="28.025" y="6.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".375"/></filter><filter id="i2QGRlb" width="4.742" height="6.271" x="7.121" y="4.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1654" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dog-face" /></template>
<style>
.a4q6f1bqf {
  d: path("M24.031 21.844c0-4.475-4.312-5.875-8-5.875c-4.125 0-8.062 1.562-8.062 5.875c0 3.95 4.312 7.343 8.062 7.343c4.5 0 8-4.656 8-7.343");
}

.a61ui5bws {
  stop-color: var(--svg-color--bd8465, #BD8465);
}

.ac2b2jbcv {
  d: path("M16.97 16.998h-1.907a.8.8 0 0 0-.617 1.31l.675.816a1.2 1.2 0 0 0 1.883-.043l.605-.801a.8.8 0 0 0-.64-1.282");
}

.anjp-37hl {
  cx: 17.112px;
  cy: 17.647px;
  fill: var(--svg-color--786366, #786366);
  rx: 0.216px;
  ry: 0.37px;
}

.au-fhtaxh {
  stop-color: var(--svg-color--50212a, #50212A);
}

.b279wb47z {
  stop-color: var(--svg-color--bf867c, #BF867C);
}

.b7bzk2bty {
  stop-color: var(--svg-color--65484a, #65484A);
}

.bldy_ccyg {
  stop-color: var(--svg-color--473132, #473132);
  stop-opacity: 0;
}

.butij_fdk {
  stop-color: var(--svg-color--ad5c30, #AD5C30);
}

.bxw28xbwr {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M24.688 10.319h2.218v12.047a1.11 1.11 0 0 1-2.219 0z");
}

.c9x45bcoc {
  stop-color: var(--svg-color--65484a, #65484A);
  stop-opacity: 0;
}

.ce374hbpu {
  stop-color: var(--svg-color--ffe9be, #FFE9BE);
}

.cw88l5bek {
  stop-color: var(--svg-color--e273a2, #E273A2);
  stop-opacity: 0;
}

.d7vidkbbw {
  stop-color: var(--svg-color--b41d4e, #B41D4E);
}

.dozz6qlkd {
  stop-color: var(--svg-color--c9297c, #C9297C);
}

.ew8h6t88b {
  stop-color: var(--svg-color--261317, #261317);
}

.ezabbtb7o {
  stop-color: var(--svg-color--5f333b, #5F333B);
}

.f7amp4ngb {
  stop-color: var(--svg-color--b3887f, #B3887F);
}

.fnwxn0mja {
  stop-color: var(--svg-color--4a3435, #4A3435);
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.fx3bet5ri {
  d: path("M16.474 20.516a.5.5 0 0 0-.5-.5h-.011a.5.5 0 0 0-.5.5q0 .123.005.243c-.116 2.221-1.806 3.225-2.962 3.225a.5.5 0 1 0 0 1c1.21 0 2.699-.746 3.463-2.242c.764 1.496 2.252 2.242 3.463 2.242a.5.5 0 0 0 0-1c-1.156 0-2.847-1.004-2.963-3.225a6 6 0 0 0 .005-.243");
}

.g9nurmghy {
  stop-color: var(--svg-color--89254f, #89254F);
  stop-opacity: 0;
}

.gk-ruvbdr {
  stop-color: var(--svg-color--ffd6b3, #FFD6B3);
}

.h0o4w5dba {
  stop-color: var(--svg-color--ffe3b6, #FFE3B6);
}

.hqf834fqu {
  stop-color: var(--svg-color--98335e, #98335E);
}

.i2f0b7sju {
  stop-color: var(--svg-color--d3b4ae, #D3B4AE);
  stop-opacity: 0;
}

.i7h39qb_i {
  stop-color: var(--svg-color--bd8465, #BD8465);
  stop-opacity: 0;
}

.ip48neb1a {
  stop-color: var(--svg-color--ad5c30, #AD5C30);
  stop-opacity: 0;
}

.iqcsp1b3j {
  stop-color: var(--svg-color--ef6a9a, #EF6A9A);
  stop-opacity: 0;
}

.iv5dqfb8a {
  stroke: var(--svg-color--725f62, #725F62);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.221 12.463v1.594");
}

.j6m-qsbfd {
  stop-color: var(--svg-color--ffe9be, #FFE9BE);
  stop-opacity: 0;
}

.jv9b3vbrt {
  width: 1.477px;
  height: 2.977px;
  x: 11.761px;
  y: 12.229px;
  fill: var(--svg-color--dc9868, #DC9868);
  rx: 0.738px;
}

.k-40b3b-z {
  width: 1.477px;
  height: 2.977px;
  x: 12.227px;
  y: 12.01px;
  rx: 0.738px;
}

.k5sycnb3l {
  stop-color: var(--svg-color--683c44, #683C44);
  stop-opacity: 0;
}

.keylzackq {
  fill: var(--svg-color--d89475, #D89475);
  d: path("m26.219 21.475l-6.747-13.96a1.25 1.25 0 0 1 1.216-1.79l2.338.17a4.5 4.5 0 0 1 4.157 4.891z");
}

.kvzluubyw {
  stop-color: var(--svg-color--392930, #392930);
}

.kycpeysdb {
  stop-color: var(--svg-color--ffc390, #FFC390);
}

.lieg0x_od {
  stop-color: var(--svg-color--be625b, #BE625B);
}

.mo0vjqb5x {
  stop-color: var(--svg-color--f26d9e, #F26D9E);
}

.mqmjd8mtb {
  stop-color: var(--svg-color--683c44, #683C44);
}

.nwodxjbni {
  stop-color: var(--svg-color--e273a2, #E273A2);
}

.o97hrtb5f {
  stop-color: var(--svg-color--b3887f, #B3887F);
  stop-opacity: 0;
}

.oqncn45bc {
  stop-color: var(--svg-color--f5c19b, #F5C19B);
}

.ozd3t4bxf {
  stroke-linecap: round;
  d: path("M19.426 24.484c-1.453 0-3.469-1.28-3.469-3.968");
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.p9-t1dpkp {
  d: path("m12.96 24.656l3.009-2.25l3.008 2.25V27c0 1.657-1.351 3-3.008 3a3.007 3.007 0 0 1-3.008-3z");
}

.pmm1ixbmq {
  stop-color: var(--svg-color--d3b4ae, #D3B4AE);
}

.predy65-q {
  stroke: var(--svg-color--725f62, #725F62);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.205 12.463v1.594");
}

.q62fi9_ow {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.281 5.475L7.703 10.63");
}

.qo2bddcqz {
  d: path("M12.5 23.984a.5.5 0 1 0 0 1zm3.969-3.468a.5.5 0 0 0-1 0zM12.5 24.984c1.709 0 3.969-1.484 3.969-4.468h-1c0 2.39-1.771 3.468-2.969 3.468z");
}

.qw8lpswdy {
  width: 1.477px;
  height: 2.977px;
  x: 18.211px;
  y: 12.01px;
  rx: 0.738px;
}

.r7590ybyk {
  stop-color: var(--svg-color--be625b, #BE625B);
  stop-opacity: 0;
}

.sbumcdl_y {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M28.875 7.287v8.25");
}

.t2rn8x8sh {
  stop-color: var(--svg-color--f7c5a1, #F7C5A1);
}

.ubxwtl1un {
  stop-color: var(--svg-color--9f6c5b, #9F6C5B);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.uka5n8bbu {
  stop-color: var(--svg-color--3c1534, #3C1534);
}

.v3e0u_bef {
  stop-color: var(--svg-color--bf867c, #BF867C);
  stop-opacity: 0;
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.w7veipeoo {
  stop-color: var(--svg-color--e28454, #E28454);
}

.wara-mb-k {
  fill: var(--svg-color--bd1836, #BD1836);
  d: path("m16.623 22.896l-.654-.49l-.669.5c-.394.983-1.216 1.167-1.937 1.315v.89c.96-.093 2.021-.453 2.6-1.59c.583 1.14 1.65 1.5 2.611 1.59v-.888c-.726-.145-1.557-.333-1.95-1.327");
}

.x_p3b_8bt {
  d: path("M15.594 22.406v7.422c2.567-.125 3.219-2.265 3.219-3.094V24.47c-1.891-.375-2.934-1.532-3.22-2.063");
}

.xbpiv709r {
  stop-color: var(--svg-color--ffe0c6, #FFE0C6);
}

.xz33o5bwi {
  stop-color: var(--svg-color--392930, #392930);
  stop-opacity: 0;
}

.yl574yboh {
  d: path("m27.512 16.362l-7.3-10.295a1.25 1.25 0 0 1 1.02-1.973h4.05a4.5 4.5 0 0 1 4.5 4.5v7.045c0 1.218-1.566 1.717-2.27.723");
}

.ze25ljb8i {
  d: path("m4.395 16.362l7.3-10.295a1.25 1.25 0 0 0-1.02-1.973h-4.05a4.5 4.5 0 0 0-4.5 4.5v7.045c0 1.218 1.565 1.717 2.27.723");
}

.znovzgb7k {
  stop-color: var(--svg-color--ffc390, #FFC390);
  stop-opacity: 0;
}

.ztdzxdbjq {
  width: 24px;
  height: 22px;
  x: 3.969px;
  y: 5px;
  rx: 4px;
}

</style>
