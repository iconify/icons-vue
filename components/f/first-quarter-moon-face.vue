<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDt926c)"><path fill="url(#i5qEF6u)" class="v86xa1bzs"/><path fill="url(#iCSACNx)" class="v86xa1bzs"/><path fill="url(#iaTHLSc)" class="v86xa1bzs"/></g><path fill="url(#it5BPAh)" class="v86xa1bzs"/><path fill="url(#iZq4e9n)" class="v86xa1bzs"/><path fill="url(#iT5G1Dc)" class="ddiz_rbop"/><path fill="url(#ilidgqe)" class="ddiz_rbop"/><path fill="url(#iiT3sud)" class="ddiz_rbop"/><path fill="url(#iyTxzmA)" class="tt_vjjwhr"/><path fill="url(#iCFsTqb)" class="tt_vjjwhr"/><path fill="url(#ioV48hb)" class="tt_vjjwhr"/><path fill="url(#ic4oYcb)" class="tt_vjjwhr"/><g filter="url(#iYALzle)"><path stroke="url(#iZcOkad)" class="kgkgebnch"/></g><path fill="url(#iiVPoAY)" class="l7f1x3b6a"/><path fill="url(#iLVppkd)" class="l7f1x3b6a"/><path fill="url(#i60VnQd)" class="l7f1x3b6a"/><g filter="url(#iftVRsN)"><path stroke="url(#ipE1Kkb)" class="mxx9-qi3z"/></g><g filter="url(#iclWNzb)"><path fill="url(#irrBvdb)" class="mt3lrjtly"/><path fill="url(#iizHfPM)" class="mt3lrjtly"/><path fill="url(#ib5A6zd)" class="mt3lrjtly"/></g><g filter="url(#ixDyMGe)"><path fill="url(#i2mGZQb)" clip-rule="evenodd" class="wvfzggb2k"/></g><path fill="url(#icIrEhd)" clip-rule="evenodd" class="p1e9cpb8h"/><g filter="url(#iCIklFB)"><path clip-rule="evenodd" class="o-mvmlbun"/></g><g clip-rule="evenodd" filter="url(#iYHzo7c)" class="d2kvgvbvc"><path class="u4hh6cbno"/><path fill="url(#iwjswXt)" class="gl36g9byh"/></g><g clip-rule="evenodd" filter="url(#iaBrOAb)" class="d2kvgvbvc"><path fill="url(#iYdL2xO)" class="ry7nl3xch"/><path fill="url(#ikX3FZc)" class="ry7nl3xch"/></g><path fill="url(#iuypHBd)" clip-rule="evenodd" class="shkw18hah"/><g filter="url(#itsCT7b)"><path stroke="url(#i3ehoAA)" class="htpfu3t_j"/></g><g filter="url(#iESGBad)"><path stroke="url(#iyCdXIc)" class="nodiubpsv"/></g><g filter="url(#iq9c4ec)"><path stroke="url(#ivnr34p)" class="pcq5um11a"/></g><defs><radialGradient id="i5qEF6u" cx="0" cy="0" r="1" gradientTransform="rotate(107.864 6.815 12.191)scale(21.5965 15.2632)" gradientUnits="userSpaceOnUse"><stop class="pc8lqpbmj"/><stop offset="1" class="sd05am3ze"/></radialGradient><radialGradient id="iCSACNx" cx="0" cy="0" r="1" gradientTransform="matrix(12.79835 -5.1867 2.5913 6.3941 8.326 28.23)" gradientUnits="userSpaceOnUse"><stop class="rs3vfqbpa"/><stop offset="1" class="r5zx3nbgo"/></radialGradient><radialGradient id="iaTHLSc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82577 -8.40618 11.0521 -6.34472 23.171 26.235)" gradientUnits="userSpaceOnUse"><stop class="q66k5kbtk"/><stop offset="1" class="eo1ucgxrq"/></radialGradient><radialGradient id="it5BPAh" cx="0" cy="0" r="1" gradientTransform="matrix(18.2156 -12.5527 12.95858 18.8046 7.759 20.507)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="z4gen72wg"/><stop offset="1" class="zo7-j83mr"/></radialGradient><radialGradient id="iZq4e9n" cx="0" cy="0" r="1" gradientTransform="rotate(-159.274 13.063 5.98)scale(2.47251 2.70273)" gradientUnits="userSpaceOnUse"><stop class="uajfipbim"/><stop offset="1" class="fuf0k75ce"/></radialGradient><radialGradient id="iT5G1Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60456 -3.49997 13.75973 6.30812 13.384 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="s2gyqu6rw"/><stop offset="1" class="tk00mxb5t"/></radialGradient><radialGradient id="ilidgqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01562 2.20313 -3.40948 -3.1193 14.883 2.226)" gradientUnits="userSpaceOnUse"><stop offset=".861" class="xbtaaib8x"/><stop offset="1" class="cq4n3ib5h"/></radialGradient><radialGradient id="iiT3sud" cx="0" cy="0" r="1" gradientTransform="matrix(1.06247 3.08827 -5.33328 1.83483 15.18 2.014)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="cb44zvbnt"/><stop offset=".979" class="ugi06actu"/></radialGradient><radialGradient id="iyTxzmA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4603 3.18748 -3.60482 -3.91335 27 15.538)" gradientUnits="userSpaceOnUse"><stop class="o38zlvdte"/><stop offset="1" class="e8sw-7_8z"/></radialGradient><radialGradient id="iCFsTqb" cx="0" cy="0" r="1" gradientTransform="rotate(9.744 -85.516 141.025)scale(3.13903 4.47076)" gradientUnits="userSpaceOnUse"><stop class="h14gl52mt"/><stop offset="1" class="xxgdn9sur"/></radialGradient><radialGradient id="ioV48hb" cx="0" cy="0" r="1" gradientTransform="rotate(139.917 10.284 13.316)scale(4.12524 4.32527)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="a9_opub8c"/><stop offset=".961" class="i6wh4zqhx"/></radialGradient><radialGradient id="ic4oYcb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.67191 -4.93748 4.2521 -2.30102 27.259 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="blkf2b47b"/><stop offset=".98" class="o79vkbb5u"/></radialGradient><radialGradient id="iLVppkd" cx="0" cy="0" r="1" gradientTransform="rotate(146.904 5.124 15.238)scale(5.20825 5.68062)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="m3w8qz5zs"/><stop offset=".958" class="r-0qskb3f"/></radialGradient><radialGradient id="i60VnQd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.87 49.167 -6.014)scale(5.44845 4.74593)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="opj597btl"/><stop offset=".976" class="rk292gb6z"/></radialGradient><radialGradient id="irrBvdb" cx="0" cy="0" r="1" gradientTransform="rotate(-15.577 34.267 -64.006)scale(3.16497)" gradientUnits="userSpaceOnUse"><stop class="l9epxg-rl"/><stop offset=".777" class="hneu2tzbv"/></radialGradient><radialGradient id="iizHfPM" cx="0" cy="0" r="1" gradientTransform="rotate(-31.64 21.556 -30.932)scale(1.81694)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="wr-fjk83a"/><stop offset="1" class="k6dxhzpoo"/></radialGradient><radialGradient id="ib5A6zd" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 -1.25 1.53232 2.3368 19.134 6.913)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="wr-fjk83a"/><stop offset="1" class="k6dxhzpoo"/></radialGradient><radialGradient id="icIrEhd" cx="0" cy="0" r="1" gradientTransform="matrix(2.32764 -1.95015 1.30654 1.55944 17.43 21.083)" gradientUnits="userSpaceOnUse"><stop class="ctsw_g6wf"/><stop offset="1" class="ntrjtj3gf"/></radialGradient><radialGradient id="ikX3FZc" cx="0" cy="0" r="1" gradientTransform="rotate(40.77 -6.64 32.318)scale(3.44548 6.40211)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="njvtv6tpp"/><stop offset="1" class="jcypb8b9t"/></radialGradient><radialGradient id="iuypHBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 6.11501 0 20.426 13.367)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="yu4vrishy"/><stop offset="1" class="i3lji-b1e"/></radialGradient><filter id="iDt926c" width="20.029" height="28.486" x="7.221" y="1.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.482353 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14578"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.615686 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14578" result="effect2_innerShadow_18_14578"/></filter><filter id="iYALzle" width="5.68" height="5.68" x="12.716" y="23.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".1"/></filter><filter id="iftVRsN" width="4.04" height="4.04" x="17.586" y="4.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".15"/></filter><filter id="iclWNzb" width="11.14" height="11.14" x="14.036" y="5.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14578"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14578" result="shape"/></filter><filter id="ixDyMGe" width="4.25" height="4.03" x="15.73" y="17.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".25"/></filter><filter id="iCIklFB" width="4.309" height="4.54" x="20.523" y="7.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".15"/></filter><filter id="iYHzo7c" width="4.13" height="4.13" x="20.866" y="7.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14578"/></filter><filter id="iaBrOAb" width="6.5" height="3.96" x="16.856" y="10.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".25"/></filter><filter id="itsCT7b" width="3.994" height="3.963" x="20.949" y="7.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".125"/></filter><filter id="iESGBad" width="5.325" height="2.937" x="17.815" y="11.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".2"/></filter><filter id="iq9c4ec" width="3.138" height="3.147" x="16.745" y="17.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14578" stdDeviation=".2"/></filter><linearGradient id="iZcOkad" x1="17.47" x2="13.636" y1="24.581" y2="28.55" gradientUnits="userSpaceOnUse"><stop class="fsyum4xkk"/><stop offset="1" class="dcexg2b7d"/></linearGradient><linearGradient id="iiVPoAY" x1="17.528" x2="13.017" y1="25.067" y2="28.445" gradientUnits="userSpaceOnUse"><stop offset=".272" class="llxnkgbkd"/><stop offset="1" class="ax-kqe63j"/></linearGradient><linearGradient id="ipE1Kkb" x1="17.696" x2="21.176" y1="5.257" y2="7.695" gradientUnits="userSpaceOnUse"><stop class="ojyd0bcbr"/><stop offset="1" class="hu0wpdcnx"/></linearGradient><linearGradient id="i2mGZQb" x1="18.816" x2="16.23" y1="18.921" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="xm8xo2bck"/><stop offset="1" class="fwr0k5bfj"/></linearGradient><linearGradient id="iwjswXt" x1="20.415" x2="24.305" y1="8.052" y2="9.57" gradientUnits="userSpaceOnUse"><stop class="v_jh0qb6r"/><stop offset="1" class="yyjkh3b6t"/></linearGradient><linearGradient id="iYdL2xO" x1="21.509" x2="15.165" y1="12.648" y2="14.342" gradientUnits="userSpaceOnUse"><stop class="yqmvb6b_f"/><stop offset="1" class="vozyuwbkf"/></linearGradient><linearGradient id="i3ehoAA" x1="21.118" x2="24.649" y1="8.437" y2="11.671" gradientUnits="userSpaceOnUse"><stop offset=".204" class="iotdm4jnc"/><stop offset=".52" class="h_q3w4und"/><stop offset=".801" class="i90gflbvo"/></linearGradient><linearGradient id="iyCdXIc" x1="18.009" x2="20.85" y1="13.632" y2="15.718" gradientUnits="userSpaceOnUse"><stop class="y5_8fg_du"/><stop offset="1" class="kso5qihdf"/></linearGradient><linearGradient id="ivnr34p" x1="17.887" x2="19.93" y1="20.648" y2="20.029" gradientUnits="userSpaceOnUse"><stop class="b7_-o8ate"/><stop offset="1" class="q5cs4fbld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:first-quarter-moon-face" /></template>
<style>
.a9_opub8c {
  stop-color: var(--svg-color--ffda83, #FFDA83);
  stop-opacity: 0;
}

.ax-kqe63j {
  stop-color: var(--svg-color--ffbf66, #FFBF66);
}

.b7_-o8ate {
  stop-color: var(--svg-color--554c58, #554C58);
  stop-opacity: 0;
}

.blkf2b47b {
  stop-color: var(--svg-color--e8a051, #E8A051);
  stop-opacity: 0;
}

.cb44zvbnt {
  stop-color: var(--svg-color--ffcb6e, #FFCB6E);
  stop-opacity: 0;
}

.cq4n3ib5h {
  stop-color: var(--svg-color--ffd678, #FFD678);
}

.ctsw_g6wf {
  stop-color: var(--svg-color--301e3a, #301E3A);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dcexg2b7d {
  stop-color: var(--svg-color--ffcf5d, #FFCF5D);
}

.ddiz_rbop {
  d: path("M18.317 3.043a3.5 3.5 0 0 1-6.658-.96a14 14 0 0 1 6.658.96");
}

.e8sw-7_8z {
  stop-color: var(--svg-color--ffc46d, #FFC46D);
}

.eo1ucgxrq {
  stop-color: var(--svg-color--ffa454, #FFA454);
  stop-opacity: 0;
}

.fsyum4xkk {
  stop-color: var(--svg-color--f49d4c, #F49D4C);
}

.ft5dv1b6b {
  fill: none;
}

.fuf0k75ce {
  stop-color: var(--svg-color--ff9d5a, #FF9D5A);
  stop-opacity: 0;
}

.fwr0k5bfj {
  stop-color: var(--svg-color--bf7a37, #BF7A37);
}

.gl36g9byh {
  d: path("M20.867 8.552a.5.5 0 0 1 .5-.5a3.48 3.48 0 0 1 3.48 3.48a.5.5 0 0 1-1 0a2.48 2.48 0 0 0-2.48-2.48a.5.5 0 0 1-.5-.5");
}

.h_q3w4und {
  stop-color: var(--svg-color--644f76, #644F76);
  stop-opacity: 0;
}

.h14gl52mt {
  stop-color: var(--svg-color--ffa566, #FFA566);
}

.hneu2tzbv {
  stop-color: var(--svg-color--f8bc5b, #F8BC5B);
}

.htpfu3t_j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.4 8.398c.494-.021 1.663.383 2.179.945c.695.633.914 1.664.914 2.117");
}

.hu0wpdcnx {
  stop-color: var(--svg-color--ffca66, #FFCA66);
}

.i3lji-b1e {
  stop-color: var(--svg-color--3b302e, #3B302E);
}

.i6wh4zqhx {
  stop-color: var(--svg-color--ffda83, #FFDA83);
}

.i90gflbvo {
  stop-color: var(--svg-color--644f76, #644F76);
}

.iotdm4jnc {
  stop-color: var(--svg-color--644f76, #644F76);
  stop-opacity: 0.5;
}

.jcypb8b9t {
  stop-color: var(--svg-color--cd7f3f, #CD7F3F);
}

.k6dxhzpoo {
  stop-color: var(--svg-color--dda64b, #DDA64B);
}

.kgkgebnch {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.557 29.093a2.54 2.54 0 1 0 0-5.08a2.54 2.54 0 0 0 0 5.08Z");
}

.kso5qihdf {
  stop-color: var(--svg-color--5d5168, #5D5168);
}

.l7f1x3b6a {
  d: path("M15.557 29.093a2.54 2.54 0 1 0 0-5.08a2.54 2.54 0 0 0 0 5.08");
}

.l9epxg-rl {
  stop-color: var(--svg-color--ffec9d, #FFEC9D);
}

.llxnkgbkd {
  stop-color: var(--svg-color--faa660, #FAA660);
}

.m3w8qz5zs {
  stop-color: var(--svg-color--ffe596, #FFE596);
  stop-opacity: 0;
}

.mt3lrjtly {
  d: path("M19.606 8.163a1.57 1.57 0 1 0 0-3.14a1.57 1.57 0 0 0 0 3.14");
}

.mxx9-qi3z {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.606 8.163a1.57 1.57 0 1 0 0-3.14a1.57 1.57 0 0 0 0 3.14Z");
}

.njvtv6tpp {
  stop-color: var(--svg-color--cd7f3f, #CD7F3F);
  stop-opacity: 0;
}

.nodiubpsv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.415 13.382c.036-.526.675-1.556 1.937-1.719c1.263-.162 2.032.797 2.188 1.375");
}

.ntrjtj3gf {
  stop-color: var(--svg-color--332e2c, #332E2C);
}

.o-mvmlbun {
  fill: var(--svg-color--9c6d2f, #9C6D2F);
  fill-rule: evenodd;
  d: path("M20.824 8.643a.475.475 0 0 1 .502-.447c1.818.107 3.308 1.663 3.2 3.492a.475.475 0 0 1-.949-.056c.077-1.303-1.011-2.41-2.307-2.487a.475.475 0 0 1-.446-.502");
}

.o38zlvdte {
  stop-color: var(--svg-color--ffdb7d, #FFDB7D);
}

.o79vkbb5u {
  stop-color: var(--svg-color--e8a051, #E8A051);
}

.ojyd0bcbr {
  stop-color: var(--svg-color--ffe07c, #FFE07C);
}

.opj597btl {
  stop-color: var(--svg-color--d78555, #D78555);
  stop-opacity: 0;
}

.p1e9cpb8h {
  fill-rule: evenodd;
  d: path("M19.169 18.06a.75.75 0 0 1 .64.845a2.526 2.526 0 0 1-2.493 2.178a.75.75 0 0 1 0-1.5c.502 0 .938-.38 1.007-.883a.75.75 0 0 1 .846-.64");
}

.pc8lqpbmj {
  stop-color: var(--svg-color--ffc65d, #FFC65D);
}

.pcq5um11a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.284 18.472c-.187 1.185-1.1 1.947-1.939 1.947");
}

.q5cs4fbld {
  stop-color: var(--svg-color--554c58, #554C58);
}

.q66k5kbtk {
  stop-color: var(--svg-color--ffa454, #FFA454);
}

.r-0qskb3f {
  stop-color: var(--svg-color--ffe596, #FFE596);
}

.r5zx3nbgo {
  stop-color: var(--svg-color--ffc050, #FFC050);
  stop-opacity: 0;
}

.rk292gb6z {
  stop-color: var(--svg-color--d78555, #D78555);
}

.rs3vfqbpa {
  stop-color: var(--svg-color--ffc050, #FFC050);
}

.ry7nl3xch {
  d: path("M17.394 13.357a2.88 2.88 0 0 1 2.732-1.975c1.213 0 2.257.743 2.678 1.816a.75.75 0 0 1-1.396.548a1.37 1.37 0 0 0-1.282-.864c-.607 0-1.126.394-1.307.945a.75.75 0 1 1-1.425-.47");
}

.s2gyqu6rw {
  stop-color: var(--svg-color--fabf62, #FABF62);
}

.sd05am3ze {
  stop-color: var(--svg-color--ffae4e, #FFAE4E);
}

.shkw18hah {
  fill-rule: evenodd;
  d: path("M17.714 12.998a2.88 2.88 0 0 1 2.732-1.975c1.213 0 2.257.743 2.678 1.816a.75.75 0 0 1-1.396.548a1.37 1.37 0 0 0-1.282-.864c-.607 0-1.126.394-1.307.944a.75.75 0 0 1-1.425-.469");
}

.tk00mxb5t {
  stop-color: var(--svg-color--ffdf81, #FFDF81);
}

.tt_vjjwhr {
  d: path("M26.835 13.83c.358 2.33.133 4.737-.667 6.968a3.5 3.5 0 1 1 .667-6.968");
}

.u4hh6cbno {
  fill: var(--svg-color--3f294d, #3F294D);
  d: path("M20.867 8.552a.5.5 0 0 1 .5-.5a3.48 3.48 0 0 1 3.48 3.48a.5.5 0 0 1-1 0a2.48 2.48 0 0 0-2.48-2.48a.5.5 0 0 1-.5-.5");
}

.uajfipbim {
  stop-color: var(--svg-color--ff9d5a, #FF9D5A);
}

.ugi06actu {
  stop-color: var(--svg-color--ffcb6e, #FFCB6E);
}

.v_jh0qb6r {
  stop-color: var(--svg-color--3b2d31, #3B2D31);
}

.v86xa1bzs {
  d: path("M15.292 18.231a.49.49 0 0 1 .13.475a13.7 13.7 0 0 1-3.516 6.127a13.8 13.8 0 0 1-4.31 2.94c-.5.22-.5.92 0 1.13c5.35 2.25 11.8 1.04 15.93-3.63c4.5-5.09 4.65-12.91.32-18.15c-3.51-4.25-8.85-5.84-13.73-4.8c-.52.11-.64.81-.2 1.11c1.29.88 2.46 1.99 3.44 3.38a14.1 14.1 0 0 1 2.476 6.603q.022.28.024.587c.008.781-.582 1.282-1.062 1.69a6 6 0 0 0-.348.31a.993.993 0 0 0 .01 1.4z");
}

.vozyuwbkf {
  stop-color: var(--svg-color--a36231, #A36231);
  stop-opacity: 0;
}

.wr-fjk83a {
  stop-color: var(--svg-color--dda64b, #DDA64B);
  stop-opacity: 0;
}

.wvfzggb2k {
  fill-rule: evenodd;
  d: path("M18.833 18.2a.75.75 0 0 1 .64.845a2.526 2.526 0 0 1-2.492 2.178a.75.75 0 1 1 0-1.5c.502 0 .937-.38 1.006-.883a.75.75 0 0 1 .846-.64");
}

.xbtaaib8x {
  stop-color: var(--svg-color--ffd678, #FFD678);
  stop-opacity: 0;
}

.xm8xo2bck {
  stop-color: var(--svg-color--be8435, #BE8435);
}

.xxgdn9sur {
  stop-color: var(--svg-color--ffa566, #FFA566);
  stop-opacity: 0;
}

.y5_8fg_du {
  stop-color: var(--svg-color--3f3445, #3F3445);
}

.yqmvb6b_f {
  stop-color: var(--svg-color--a36231, #A36231);
}

.yu4vrishy {
  stop-color: var(--svg-color--3d2a48, #3D2A48);
}

.yyjkh3b6t {
  stop-color: var(--svg-color--3b2d31, #3B2D31);
  stop-opacity: 0;
}

.z4gen72wg {
  stop-color: var(--svg-color--fff29e, #FFF29E);
  stop-opacity: 0;
}

.zo7-j83mr {
  stop-color: var(--svg-color--fff29e, #FFF29E);
}

</style>
