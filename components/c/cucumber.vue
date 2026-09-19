<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iN4Ialb)" class="usswy4mwy"/><path fill="url(#iQDzpvJ)" class="y3nvudtwx"/><path fill="url(#ixMibFe)" class="q1oindboc"/><path fill="url(#ibwPo3c)" class="q1oindboc"/><path fill="url(#im62gLe)" class="tuyc9sn2d"/><path fill="url(#iXl5XNe)" class="tuyc9sn2d"/><path class="qnqny5buc"/><path fill="url(#iqHjaBb)" class="nco9v_bhn"/><path fill="url(#iLAAkPc)" class="nco9v_bhn"/><path fill="url(#iJ5pRge)" class="nco9v_bhn"/><path fill="url(#ior9FCe)" class="nco9v_bhn"/><g filter="url(#iYeXWcd)"><path fill="url(#iEyi9ob)" class="dcud33bmp"/><path class="fohj84bpr"/></g><path fill="url(#i3nygfd)" class="v9_4b5bds"/><path fill="url(#ijvibKe)" class="v9_4b5bds"/><g filter="url(#ikvbUsb)"><path fill="url(#iFhwJEb)" class="s_f07qb5s"/><path class="muly40bvx"/></g><path fill="url(#iQ3Cx4p)" class="thhxt_b0v"/><path fill="url(#ikIL2Bb)" class="thhxt_b0v"/><g filter="url(#itHIObd)"><path fill="url(#ig4U7dd)" class="iqpdd0b-f"/><path class="pgwsbwebc"/></g><path fill="url(#iT7miyb)" class="eo55_qbmb"/><path fill="url(#iKjVYYd)" class="eo55_qbmb"/><g filter="url(#ik3EdHb)"><ellipse fill="url(#i6dZq5b)" transform="rotate(-28.883 24.95 6.136)" class="yp8ubzinv"/></g><defs><radialGradient id="iN4Ialb" cx="0" cy="0" r="1" gradientTransform="rotate(90.116 1.966 11.911)scale(2.08001)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="g74p60bsh"/><stop offset="1" class="xbdh7qbln"/></radialGradient><radialGradient id="iQDzpvJ" cx="0" cy="0" r="1" gradientTransform="rotate(90.116 -2.934 12.478)scale(2.08001)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="g74p60bsh"/><stop offset="1" class="xbdh7qbln"/></radialGradient><radialGradient id="ixMibFe" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 -1.443 19.395)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset=".458" class="ik-25su6n"/><stop offset=".847" class="b6bg5ta6m"/></radialGradient><radialGradient id="ibwPo3c" cx="0" cy="0" r="1" gradientTransform="rotate(126.206 3.018 16.766)scale(.96821)" gradientUnits="userSpaceOnUse"><stop class="wy-jkzu8a"/><stop offset="1" class="its31cbzs"/></radialGradient><radialGradient id="im62gLe" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 5.118 18.348)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset=".458" class="ik-25su6n"/><stop offset=".847" class="b6bg5ta6m"/></radialGradient><radialGradient id="iXl5XNe" cx="0" cy="0" r="1" gradientTransform="rotate(126.206 8.187 14.553)scale(.96821)" gradientUnits="userSpaceOnUse"><stop class="wy-jkzu8a"/><stop offset="1" class="its31cbzs"/></radialGradient><radialGradient id="iqHjaBb" cx="0" cy="0" r="1" gradientTransform="matrix(-22.81238 27.12514 -15.8166 -13.30185 6.125 8.5)" gradientUnits="userSpaceOnUse"><stop class="s1hs38b4j"/><stop offset=".455" class="plm5xcarp"/><stop offset=".695" class="h5yefrage"/><stop offset=".754" class="h5yefrage"/><stop offset="1" class="jhcek3fej"/></radialGradient><radialGradient id="iLAAkPc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.24998 -7.18754 7.38231 -8.47354 27.375 6.563)" gradientUnits="userSpaceOnUse"><stop class="wbuj5jbsp"/><stop offset=".572" class="mz9-rsbxp"/><stop offset=".98" class="jd4dv1bfj"/></radialGradient><radialGradient id="iJ5pRge" cx="0" cy="0" r="1" gradientTransform="rotate(-15.73 106.18 4.062)scale(20.5184 18.2098)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="p5mbzubcn"/><stop offset="1" class="gm0ttnntk"/></radialGradient><radialGradient id="ior9FCe" cx="0" cy="0" r="1" gradientTransform="matrix(-20.43753 21.62493 -10.28232 -9.71773 19.813 11.125)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="dkoax62pp"/><stop offset=".707" class="tmsmnyc_g"/><stop offset=".785" class="o9rj0iqug"/></radialGradient><radialGradient id="iEyi9ob" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 -4.79 14.946)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="rpkb24svf"/><stop offset=".458" class="haokhbbsd"/><stop offset=".847" class="llz8twbun"/></radialGradient><radialGradient id="i3nygfd" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 -4.416 15.272)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="rpkb24svf"/><stop offset=".458" class="haokhbbsd"/><stop offset=".847" class="llz8twbun"/></radialGradient><radialGradient id="ijvibKe" cx="0" cy="0" r="1" gradientTransform="rotate(126.206 -.273 13.995)scale(.96821)" gradientUnits="userSpaceOnUse"><stop class="e2txekbnz"/><stop offset="1" class="vc1cae24v"/></radialGradient><radialGradient id="iFhwJEb" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 1.01 14.777)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset=".458" class="ik-25su6n"/><stop offset=".847" class="b6bg5ta6m"/></radialGradient><radialGradient id="iQ3Cx4p" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 1.227 14.965)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset=".458" class="ik-25su6n"/><stop offset=".847" class="b6bg5ta6m"/></radialGradient><radialGradient id="ikIL2Bb" cx="0" cy="0" r="1" gradientTransform="rotate(126.206 4.295 12.58)scale(.96821)" gradientUnits="userSpaceOnUse"><stop class="wy-jkzu8a"/><stop offset="1" class="its31cbzs"/></radialGradient><radialGradient id="ig4U7dd" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 6.41 13.548)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset=".458" class="ik-25su6n"/><stop offset=".847" class="b6bg5ta6m"/></radialGradient><radialGradient id="iT7miyb" cx="0" cy="0" r="1" gradientTransform="rotate(97.999 6.68 13.617)scale(2.47032)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset=".458" class="ik-25su6n"/><stop offset=".847" class="b6bg5ta6m"/></radialGradient><radialGradient id="iKjVYYd" cx="0" cy="0" r="1" gradientTransform="rotate(126.206 8.493 10.35)scale(.96821)" gradientUnits="userSpaceOnUse"><stop class="wy-jkzu8a"/><stop offset="1" class="its31cbzs"/></radialGradient><radialGradient id="i6dZq5b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12698 1.21168 -1.1382 -2.93734 25.697 5.766)" gradientUnits="userSpaceOnUse"><stop class="xy836i3jq"/><stop offset="1" class="d8-vyc5cp"/></radialGradient><filter id="iYeXWcd" width="4.28" height="4.28" x="7.397" y="20.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31639" stdDeviation=".5"/></filter><filter id="ikvbUsb" width="4.28" height="4.28" x="13.838" y="14.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31639" stdDeviation=".5"/></filter><filter id="itHIObd" width="4.28" height="4.28" x="18.773" y="8.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31639" stdDeviation=".5"/></filter><filter id="ik3EdHb" width="7.34" height="7.942" x="21.281" y="2.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31639" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cucumber" /></template>
<style>
.b6bg5ta6m {
  stop-color: var(--svg-color--407a78, #407A78);
}

.d8-vyc5cp {
  stop-color: var(--svg-color--b1f461, #B1F461);
  stop-opacity: 0;
}

.dcud33bmp {
  d: path("M9.537 24.05a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.dkoax62pp {
  stop-color: var(--svg-color--7767ba, #7767BA);
  stop-opacity: 0;
}

.e2txekbnz {
  stop-color: var(--svg-color--99c574, #99C574);
}

.eo55_qbmb {
  d: path("M21.288 11.178a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.fohj84bpr {
  fill: var(--svg-color--3f7d58, #3F7D58);
  d: path("M9.537 24.05a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.ft5dv1b6b {
  fill: none;
}

.g74p60bsh {
  stop-color: var(--svg-color--639437, #639437);
}

.gm0ttnntk {
  stop-color: var(--svg-color--406a5e, #406A5E);
  stop-opacity: 0;
}

.h5yefrage {
  stop-color: var(--svg-color--87b96b, #87B96B);
}

.haokhbbsd {
  stop-color: var(--svg-color--6e9f5c, #6E9F5C);
}

.ik-25su6n {
  stop-color: var(--svg-color--71a855, #71A855);
}

.iqpdd0b-f {
  d: path("M20.913 11.365a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.its31cbzs {
  stop-color: var(--svg-color--9acc73, #9ACC73);
  stop-opacity: 0;
}

.jd4dv1bfj {
  stop-color: var(--svg-color--82c03b, #82C03B);
  stop-opacity: 0;
}

.jhcek3fej {
  stop-color: var(--svg-color--7d9f82, #7D9F82);
}

.llz8twbun {
  stop-color: var(--svg-color--326d7e, #326D7E);
}

.muly40bvx {
  fill: var(--svg-color--5a9154, #5A9154);
  d: path("M15.978 18.113a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.mz9-rsbxp {
  stop-color: var(--svg-color--88c839, #88C839);
}

.nco9v_bhn {
  d: path("M5.437 19.75c1.9-1.45 5.474-4.566 6.782-6.281c2.906-3.813 3.906-6.594 5.156-8.75C18.653 2.514 21.87.85 25.5 2.938c2.812 1.617 3.062 4.593 2.687 5.968c-1.603 5.881-8.617 15.793-14.906 19.657c-4.055 2.491-6.406.921-8.031-.594c-2.185-2.038-2.188-6.407.187-8.219");
}

.o9rj0iqug {
  stop-color: var(--svg-color--7566b7, #7566B7);
}

.p5mbzubcn {
  stop-color: var(--svg-color--3a666d, #3A666D);
}

.pgwsbwebc {
  fill: var(--svg-color--6da343, #6DA343);
  d: path("M20.913 11.365a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.plm5xcarp {
  stop-color: var(--svg-color--659c4a, #659C4A);
}

.q1oindboc {
  d: path("M17.756 25.803a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.qnqny5buc {
  fill: var(--svg-color--6fa755, #6FA755);
  d: path("M5.437 19.75c1.9-1.45 5.474-4.566 6.782-6.281c2.906-3.813 3.906-6.594 5.156-8.75C18.653 2.514 21.87.85 25.5 2.938c2.812 1.617 3.062 4.593 2.687 5.968c-1.603 5.881-8.617 15.793-14.906 19.657c-4.055 2.491-6.406.921-8.031-.594c-2.185-2.038-2.188-6.407.187-8.219");
}

.rpkb24svf {
  stop-color: var(--svg-color--86bb3f, #86BB3F);
}

.s_f07qb5s {
  d: path("M15.978 18.113a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.s1hs38b4j {
  stop-color: var(--svg-color--67993c, #67993C);
}

.thhxt_b0v {
  d: path("M16.41 18.113a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.tju132bmi {
  stop-color: var(--svg-color--8ed800, #8ED800);
}

.tmsmnyc_g {
  stop-color: var(--svg-color--7767b9, #7767B9);
  stop-opacity: 0.241;
}

.tuyc9sn2d {
  d: path("M24.194 18.113a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.usswy4mwy {
  d: path("M13.881 12.053a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.v9_4b5bds {
  d: path("M10.288 24.05a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.vc1cae24v {
  stop-color: var(--svg-color--99c670, #99C670);
  stop-opacity: 0;
}

.wbuj5jbsp {
  stop-color: var(--svg-color--b2f465, #B2F465);
}

.wy-jkzu8a {
  stop-color: var(--svg-color--9acc73, #9ACC73);
}

.xbdh7qbln {
  stop-color: var(--svg-color--3d694b, #3D694B);
}

.xy836i3jq {
  stop-color: var(--svg-color--b3f663, #B3F663);
}

.y3nvudtwx {
  d: path("M9.537 17.521a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.yp8ubzinv {
  cx: 24.951px;
  cy: 6.136px;
  rx: 2.527px;
  ry: 3.093px;
}

</style>
