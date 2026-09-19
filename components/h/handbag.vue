<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iS9JVNe)"><path class="dktpch3qz"/></g><g filter="url(#iOAwOib)"><path class="m828krb5j"/><path fill="url(#i3xg6id)" class="ho_yvgrji"/><path fill="url(#iait5Jb)" class="ho_yvgrji"/></g><g filter="url(#iUqU7Xd)"><path class="my08qowat"/></g><path fill="url(#iJCjoTd)" class="rtb0wcc2p"/><path fill="url(#izoVWlc)" class="rtb0wcc2p"/><path fill="url(#iFOueUc)" class="rtb0wcc2p"/><path fill="url(#ikzALHd)" class="rtb0wcc2p"/><g filter="url(#iUQjz8b)"><path fill="url(#ioZ0sOe)" class="l4o2qzbvq"/></g><path fill="url(#iMKCrAe)" class="l4o2qzbvq"/><g filter="url(#iT8rDkc)"><path fill="url(#iWkYCSc)" class="og0_vob7e"/></g><g filter="url(#ii5XpUb)"><rect class="c03ea6boe"/></g><g filter="url(#iFae5ub)"><rect class="b86czze4c"/></g><g filter="url(#iTexDzd)"><rect class="t1jo08v2f"/><rect fill="url(#iFw3Ifv)" class="b05d-_bih"/><rect fill="url(#iPiS3Ec)" class="b05d-_bih"/><rect fill="url(#iQ3RAJb)" class="b05d-_bih"/></g><rect class="if6hbbb7y"/><rect fill="url(#iEEOt5o)" class="uh3pg0bpn"/><rect fill="url(#i6n7KEc)" class="uh3pg0bpn"/><rect fill="url(#iIycuJc)" class="uh3pg0bpn"/><g filter="url(#iWD8zEL)"><path class="f74jn1bmi"/></g><g filter="url(#ih0tH7d)"><path class="u2lwk8bnb"/></g><g filter="url(#i9EUZnL)"><path class="c88g9hrhz"/></g><defs><linearGradient id="i3xg6id" x1="29.873" x2="20.281" y1="22.382" y2="24.408" gradientUnits="userSpaceOnUse"><stop class="gwqjjwbsm"/><stop offset="1" class="kctjy5bzo"/></linearGradient><linearGradient id="iait5Jb" x1="2.922" x2="9.672" y1="21.044" y2="21.35" gradientUnits="userSpaceOnUse"><stop class="ejp4f9b4c"/><stop offset="1" class="ors3bxxiq"/></linearGradient><linearGradient id="iJCjoTd" x1="16" x2="16" y1="21.617" y2="30.349" gradientUnits="userSpaceOnUse"><stop class="hr5lgosjh"/><stop offset="1" class="a3r_thbyt"/></linearGradient><linearGradient id="izoVWlc" x1="2.127" x2="5.735" y1="26.525" y2="26.709" gradientUnits="userSpaceOnUse"><stop offset=".205" class="z0p3v88mn"/><stop offset="1" class="c7ub638gc"/></linearGradient><linearGradient id="iFOueUc" x1="14.859" x2="14.859" y1="30.349" y2="25.378" gradientUnits="userSpaceOnUse"><stop offset=".154" class="hoq1u4b1x"/><stop offset="1" class="b-1-ztk-a"/></linearGradient><linearGradient id="ikzALHd" x1="2.127" x2="3.501" y1="25.314" y2="25.467" gradientUnits="userSpaceOnUse"><stop class="h8n1hxhmf"/><stop offset="1" class="fk4rhobeg"/></linearGradient><linearGradient id="ioZ0sOe" x1="10.83" x2="22.493" y1="12.149" y2="12.149" gradientUnits="userSpaceOnUse"><stop class="gk2ltgpah"/><stop offset="1" class="l-e862dsh"/></linearGradient><linearGradient id="iWkYCSc" x1="8.051" x2="24.77" y1="12.843" y2="12.843" gradientUnits="userSpaceOnUse"><stop class="cx_6hgbbi"/><stop offset="1" class="zqf2z3bdx"/></linearGradient><linearGradient id="iFw3Ifv" x1="5.953" x2="7.084" y1="15.69" y2="15.69" gradientUnits="userSpaceOnUse"><stop offset=".483" class="zdtptqbbx"/><stop offset="1" class="kenlp0b4p"/></linearGradient><linearGradient id="iPiS3Ec" x1="8.318" x2="8.318" y1="17.14" y2="16.229" gradientUnits="userSpaceOnUse"><stop offset=".194" class="qd042dbwf"/><stop offset="1" class="xs3_ttbjy"/></linearGradient><linearGradient id="iQ3RAJb" x1="7.891" x2="7.891" y1="13.189" y2="14.015" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ml8zr5ilx"/><stop offset="1" class="xt5uxkbgn"/></linearGradient><linearGradient id="iEEOt5o" x1="22.266" x2="23.396" y1="15.69" y2="15.69" gradientUnits="userSpaceOnUse"><stop offset=".483" class="zdtptqbbx"/><stop offset="1" class="kenlp0b4p"/></linearGradient><linearGradient id="i6n7KEc" x1="24.631" x2="24.631" y1="17.14" y2="16.229" gradientUnits="userSpaceOnUse"><stop offset=".194" class="qd042dbwf"/><stop offset="1" class="xs3_ttbjy"/></linearGradient><linearGradient id="iIycuJc" x1="24.203" x2="24.203" y1="13.189" y2="14.015" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ml8zr5ilx"/><stop offset="1" class="xt5uxkbgn"/></linearGradient><filter id="iS9JVNe" width="5.094" height="18.382" x="25.141" y="10.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".5"/></filter><filter id="iOAwOib" width="28.745" height="20.662" x="2.127" y="10.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.560784 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17058"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.8 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17058" result="effect2_innerShadow_18_17058"/></filter><filter id="iUqU7Xd" width="5.125" height="17.553" x="25.109" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".5"/></filter><filter id="iUQjz8b" width="17.844" height="13.874" x="7.109" y="1.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.27451 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17058"/></filter><filter id="iT8rDkc" width="17.444" height="13.824" x="7.501" y="2.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".2"/></filter><filter id="ii5XpUb" width="5.875" height="5.951" x="20.891" y="12.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".5"/></filter><filter id="iFae5ub" width="5.875" height="5.951" x="4.516" y="12.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".5"/></filter><filter id="iTexDzd" width="4.025" height="3.951" x="5.953" y="13.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17058"/></filter><filter id="iWD8zEL" width="4.156" height="8.121" x="26.078" y="20.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".5"/></filter><filter id="ih0tH7d" width="1.5" height="3.518" x="8.42" y="13.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".25"/></filter><filter id="i9EUZnL" width="1.5" height="3.518" x="24.723" y="13.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17058" stdDeviation=".25"/></filter><radialGradient id="iMKCrAe" cx="0" cy="0" r="1" gradientTransform="rotate(-86.61 11.111 2.6)scale(4.16459 5.28768)" gradientUnits="userSpaceOnUse"><stop class="vusi8ibmz"/><stop offset="1" class="cl-33ubsw"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:handbag" /></template>
<style>
.a3r_thbyt {
  stop-color: var(--svg-color--744c50, #744C50);
}

.b-1-ztk-a {
  stop-color: var(--svg-color--724950, #724950);
  stop-opacity: 0;
}

.b05d-_bih {
  width: 3.875px;
  height: 3.951px;
  x: 5.953px;
  y: 13.189px;
  rx: 0.75px;
}

.b86czze4c {
  width: 3.875px;
  height: 3.951px;
  x: 5.516px;
  y: 13.667px;
  fill: var(--svg-color--c18f7d, #C18F7D);
  rx: 0.75px;
}

.c03ea6boe {
  width: 3.875px;
  height: 3.951px;
  x: 21.891px;
  y: 13.667px;
  fill: var(--svg-color--c18f7d, #C18F7D);
  rx: 0.75px;
}

.c7ub638gc {
  stop-color: var(--svg-color--634743, #634743);
  stop-opacity: 0;
}

.c88g9hrhz {
  stroke: var(--svg-color--8d706d, #8D706D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.473 13.982V16");
}

.cl-33ubsw {
  stop-color: var(--svg-color--5f3d38, #5F3D38);
  stop-opacity: 0;
}

.cx_6hgbbi {
  stop-color: var(--svg-color--7a5354, #7A5354);
}

.dktpch3qz {
  stroke: var(--svg-color--9a726a, #9A726A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m26.89 12.44l1.594 14.882");
}

.ejp4f9b4c {
  stop-color: var(--svg-color--c18f70, #C18F70);
}

.f74jn1bmi {
  stroke: var(--svg-color--966f68, #966F68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m27.828 22.7l.656 4.622");
}

.fk4rhobeg {
  stop-color: var(--svg-color--674a46, #674A46);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gk2ltgpah {
  stop-color: var(--svg-color--69413d, #69413D);
}

.gwqjjwbsm {
  stop-color: var(--svg-color--e8b585, #E8B585);
}

.h8n1hxhmf {
  stop-color: var(--svg-color--ac9a95, #AC9A95);
}

.ho_yvgrji {
  d: path("M3.553 13.436c.156-1.562 1.446-2.749 2.984-2.749h19.004c1.545 0 2.838 1.197 2.986 2.766l1.334 14.102c.142 1.498-1.013 2.794-2.489 2.794H4.628c-1.481 0-2.638-1.306-2.487-2.808z");
}

.hoq1u4b1x {
  stop-color: var(--svg-color--683858, #683858);
}

.hr5lgosjh {
  stop-color: var(--svg-color--90605d, #90605D);
}

.if6hbbb7y {
  width: 3.875px;
  height: 3.951px;
  x: 22.266px;
  y: 13.189px;
  fill: var(--svg-color--6a4448, #6A4448);
  rx: 0.75px;
}

.kctjy5bzo {
  stop-color: var(--svg-color--e8b585, #E8B585);
  stop-opacity: 0;
}

.kenlp0b4p {
  stop-color: var(--svg-color--593b39, #593B39);
  stop-opacity: 0;
}

.l-e862dsh {
  stop-color: var(--svg-color--743f44, #743F44);
}

.l4o2qzbvq {
  d: path("M23.453 11.277v4.54h1.5v-4.54zM8.61 15.817v-4.54h-1.5v4.54zm7.422-12.124c4.085 0 7.422 3.382 7.422 7.584h1.5c0-5.003-3.98-9.084-8.922-9.084zm0-1.5c-4.94 0-8.922 4.081-8.922 9.084h1.5c0-4.202 3.337-7.584 7.422-7.584z");
}

.m828krb5j {
  fill: var(--svg-color--e4b8a4, #E4B8A4);
  d: path("M3.553 13.436c.156-1.562 1.446-2.749 2.984-2.749h19.004c1.545 0 2.838 1.197 2.986 2.766l1.334 14.102c.142 1.498-1.013 2.794-2.489 2.794H4.628c-1.481 0-2.638-1.306-2.487-2.808z");
}

.ml8zr5ilx {
  stop-color: var(--svg-color--6a443d, #6A443D);
}

.my08qowat {
  stroke: var(--svg-color--f4c79c, #F4C79C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m26.86 13.268l1.624 14.054");
}

.og0_vob7e {
  d: path("M24.245 11.277v4.54h.3v-4.54zM8.2 15.817v-4.54h-.3v4.54zm8.022-12.724c4.428 0 8.022 3.661 8.022 8.184h.3c0-4.683-3.723-8.484-8.322-8.484zm0-.3c-4.599 0-8.322 3.801-8.322 8.484h.3c0-4.523 3.594-8.184 8.022-8.184z");
}

.ors3bxxiq {
  stop-color: var(--svg-color--c18f70, #C18F70);
  stop-opacity: 0;
}

.qd042dbwf {
  stop-color: var(--svg-color--602e4c, #602E4C);
}

.rtb0wcc2p {
  d: path("m29.3 21.617l.56 5.938c.143 1.498-1.012 2.794-2.488 2.794H4.628c-1.481 0-2.638-1.306-2.487-2.808l.593-5.924z");
}

.t1jo08v2f {
  width: 3.875px;
  height: 3.951px;
  x: 5.953px;
  y: 13.189px;
  fill: var(--svg-color--6a4448, #6A4448);
  rx: 0.75px;
}

.u2lwk8bnb {
  stroke: var(--svg-color--8d706d, #8D706D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.17 13.982V16");
}

.uh3pg0bpn {
  width: 3.875px;
  height: 3.951px;
  x: 22.266px;
  y: 13.189px;
  rx: 0.75px;
}

.vusi8ibmz {
  stop-color: var(--svg-color--5f3d38, #5F3D38);
}

.xs3_ttbjy {
  stop-color: var(--svg-color--602e4c, #602E4C);
  stop-opacity: 0;
}

.xt5uxkbgn {
  stop-color: var(--svg-color--6a443d, #6A443D);
  stop-opacity: 0;
}

.z0p3v88mn {
  stop-color: var(--svg-color--634743, #634743);
}

.zdtptqbbx {
  stop-color: var(--svg-color--593b39, #593B39);
}

.zqf2z3bdx {
  stop-color: var(--svg-color--987772, #987772);
}

</style>
