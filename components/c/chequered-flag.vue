<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGsjTcb)"><path class="p7x34fp3s"/></g><path fill="url(#iNwsqwd)" class="ucrimqbes"/><path fill="url(#isqCo9d)" class="ucrimqbes"/><path fill="url(#is9EPee)" class="ucrimqbes"/><g filter="url(#ifM8q1c)"><path class="eg6w_xgxi"/></g><path class="c2vnnhbui"/><path fill="url(#itvPa2E)" class="aic5clbdd"/><path fill="url(#iaCiPyc)" class="aic5clbdd"/><path fill="url(#ixYjAKc)" class="aic5clbdd"/><path fill="url(#idbBrDd)" class="aic5clbdd"/><g filter="url(#iTNGype)"><path class="mxscfdb9w"/></g><g filter="url(#isosneE)"><path class="cmx031bix"/></g><g filter="url(#i6fQkmb)"><path class="q7jb2ac6l"/><path fill="url(#iFJ7wQb)" class="bbgem7vvv"/><path fill="url(#iMGBEtd)" class="bbgem7vvv"/></g><g filter="url(#if8Xvsa)"><path class="yndmnshjq"/><path fill="url(#iC5tilb)" class="h5kq-7bpd"/><path fill="url(#ik7QRnb)" class="h5kq-7bpd"/><path fill="url(#ibaxTce)" class="h5kq-7bpd"/></g><path clip-rule="evenodd" class="nt0iff9zo"/><path clip-rule="evenodd" class="cen69q41k"/><path clip-rule="evenodd" class="v8kfh5btg"/><path fill="url(#i6rnvSE)" clip-rule="evenodd" class="atc6f_bqq"/><path fill="url(#ih5u3tb)" clip-rule="evenodd" class="atc6f_bqq"/><path fill="url(#iDTC9Hd)" clip-rule="evenodd" class="atc6f_bqq"/><path clip-rule="evenodd" class="dj2j9vorp"/><path fill="url(#iSS0Bce)" clip-rule="evenodd" class="su7n0db3d"/><path clip-rule="evenodd" class="ketg2kbhx"/><path fill="url(#iwTJYOD)" clip-rule="evenodd" class="lt8yvfbbp"/><path fill="url(#ipJagfd)" clip-rule="evenodd" class="lt8yvfbbp"/><path clip-rule="evenodd" class="yipk3-bws"/><path fill="url(#iv2W89b)" clip-rule="evenodd" class="g5w4idwnc"/><path clip-rule="evenodd" class="zv061_bcq"/><path fill="url(#iRXFcDc)" clip-rule="evenodd" class="xe0sbz8jo"/><path clip-rule="evenodd" class="i-yogdblz"/><path clip-rule="evenodd" class="j0rmr7bri"/><path clip-rule="evenodd" class="fptfbcc1z"/><path clip-rule="evenodd" class="t4vvqikxs"/><path fill="url(#ibpMD6d)" clip-rule="evenodd" class="rvu3dtb5w"/><path fill="url(#iPWNfmd)" clip-rule="evenodd" class="rvu3dtb5w"/><path fill="url(#iHphoyc)" clip-rule="evenodd" class="rvu3dtb5w"/><path clip-rule="evenodd" class="zx5zdldjr"/><path fill="url(#iu9FWvc)" clip-rule="evenodd" class="h21foib9b"/><path clip-rule="evenodd" class="ttxgpvb2u"/><defs><linearGradient id="iNwsqwd" x1="6.265" x2="8.358" y1="21.838" y2="15.619" gradientUnits="userSpaceOnUse"><stop offset=".066" class="wd-pmobbk"/><stop offset="1" class="t2wui94jw"/></linearGradient><linearGradient id="isqCo9d" x1="9.046" x2="5.983" y1="18.744" y2="19.994" gradientUnits="userSpaceOnUse"><stop offset=".374" class="r9ns9qbfh"/><stop offset="1" class="msgdqmbxl"/></linearGradient><linearGradient id="is9EPee" x1="2.815" x2="7.087" y1="18.36" y2="16.501" gradientUnits="userSpaceOnUse"><stop offset=".214" class="ilfb1o36w"/><stop offset=".38" class="o__1t7bai"/></linearGradient><linearGradient id="itvPa2E" x1="7.202" x2="8.452" y1="15.744" y2="15.15" gradientUnits="userSpaceOnUse"><stop offset=".559" class="p0-igtb9f"/><stop offset="1" class="samx7hpzs"/></linearGradient><linearGradient id="iaCiPyc" x1="7.421" x2="7.562" y1="7.361" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="wstr51vhg"/><stop offset=".994" class="hop683bux"/></linearGradient><linearGradient id="ixYjAKc" x1="12.226" x2="12.101" y1="16.611" y2="16.346" gradientUnits="userSpaceOnUse"><stop class="rjqk0f4sw"/><stop offset="1" class="hb-v1ibbv"/></linearGradient><linearGradient id="idbBrDd" x1="14.858" x2="14.108" y1="12.494" y2="12.854" gradientUnits="userSpaceOnUse"><stop offset=".391" class="vc--wpv5i"/><stop offset="1" class="csogkqfmg"/></linearGradient><linearGradient id="iFJ7wQb" x1="22.89" x2="22.733" y1="17.963" y2="19.588" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></linearGradient><linearGradient id="iMGBEtd" x1="23.081" x2="22.78" y1="19.404" y2="19.268" gradientUnits="userSpaceOnUse"><stop class="fm0uxeboe"/><stop offset="1" class="p66l76blk"/></linearGradient><linearGradient id="iC5tilb" x1="25.131" x2="23.6" y1="15.744" y2="15.025" gradientUnits="userSpaceOnUse"><stop offset=".271" class="k0iunxzjd"/><stop offset="1" class="adngw-bnk"/></linearGradient><linearGradient id="ik7QRnb" x1="18.35" x2="19.131" y1="10.4" y2="10.744" gradientUnits="userSpaceOnUse"><stop offset=".099" class="oa7-35axz"/><stop offset="1" class="qz53z_d5t"/></linearGradient><linearGradient id="ibaxTce" x1="19.975" x2="20.272" y1="16.713" y2="16.104" gradientUnits="userSpaceOnUse"><stop class="hunmi-f3n"/><stop offset="1" class="azm39lm3y"/></linearGradient><linearGradient id="i6rnvSE" x1="6.802" x2="8.375" y1="18.052" y2="17.33" gradientUnits="userSpaceOnUse"><stop offset=".694" class="jbo8zcc8b"/><stop offset=".777" class="njw1xtbid"/></linearGradient><linearGradient id="ih5u3tb" x1="9.029" x2="8.376" y1="18.698" y2="17.328" gradientUnits="userSpaceOnUse"><stop offset=".424" class="jbo8zcc8b"/><stop offset=".519" class="njw1xtbid"/></linearGradient><linearGradient id="iDTC9Hd" x1="7.919" x2="8.376" y1="18.717" y2="17.329" gradientUnits="userSpaceOnUse"><stop offset=".424" class="jbo8zcc8b"/><stop offset=".519" class="njw1xtbid"/></linearGradient><linearGradient id="iSS0Bce" x1="5.271" x2="6.869" y1="14.819" y2="14.085" gradientUnits="userSpaceOnUse"><stop offset=".694" class="jbo8zcc8b"/><stop offset=".777" class="njw1xtbid"/></linearGradient><linearGradient id="iwTJYOD" x1="16.596" x2="14.942" y1="13.963" y2="14.747" gradientUnits="userSpaceOnUse"><stop offset=".575" class="kf0w67bzi"/><stop offset=".692" class="w1kry5b3h"/><stop offset=".892" class="kf0w67bzi"/></linearGradient><linearGradient id="ipJagfd" x1="15.801" x2="15.233" y1="15.249" y2="14.019" gradientUnits="userSpaceOnUse"><stop offset=".527" class="kf0w67bzi"/><stop offset=".701" class="gsvhh_98v"/></linearGradient><linearGradient id="iv2W89b" x1="15.238" x2="13.287" y1="10.576" y2="11.479" gradientUnits="userSpaceOnUse"><stop offset=".551" class="kf0w67bzi"/><stop offset=".694" class="w1kry5b3h"/><stop offset=".892" class="kf0w67bzi"/></linearGradient><linearGradient id="iRXFcDc" x1="13.627" x2="11.664" y1="7.222" y2="8.129" gradientUnits="userSpaceOnUse"><stop offset=".551" class="kf0w67bzi"/><stop offset=".694" class="w1kry5b3h"/><stop offset=".892" class="kf0w67bzi"/></linearGradient><linearGradient id="ibpMD6d" x1="25.267" x2="23.694" y1="18.052" y2="17.33" gradientUnits="userSpaceOnUse"><stop offset=".694" class="jbo8zcc8b"/><stop offset=".777" class="njw1xtbid"/></linearGradient><linearGradient id="iPWNfmd" x1="23.04" x2="23.694" y1="18.698" y2="17.328" gradientUnits="userSpaceOnUse"><stop offset=".424" class="jbo8zcc8b"/><stop offset=".519" class="njw1xtbid"/></linearGradient><linearGradient id="iHphoyc" x1="24.15" x2="23.694" y1="18.717" y2="17.329" gradientUnits="userSpaceOnUse"><stop offset=".424" class="jbo8zcc8b"/><stop offset=".519" class="njw1xtbid"/></linearGradient><linearGradient id="iu9FWvc" x1="26.798" x2="25.201" y1="14.819" y2="14.085" gradientUnits="userSpaceOnUse"><stop offset=".694" class="jbo8zcc8b"/><stop offset=".777" class="njw1xtbid"/></linearGradient><filter id="iGsjTcb" width="11.785" height="23.801" x="9.808" y="3.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.439216 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_1848"/></filter><filter id="ifM8q1c" width="2.478" height="3.752" x="8.271" y="17.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.67451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_1848"/></filter><filter id="iTNGype" width="12.035" height="23.801" x="10.736" y="3.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.439216 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_1848"/></filter><filter id="isosneE" width="8.83" height="11.323" x="21.03" y="11.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.662745 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_1848"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4_1848" result="effect2_innerShadow_4_1848"/></filter><filter id="i6fQkmb" width="2.628" height="3.752" x="21.33" y="17.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.666667 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_1848"/></filter><filter id="if8Xvsa" width="10.702" height="12.73" x="16.37" y="5.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.960784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_1848"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chequered-flag" /></template>
<style>
.adngw-bnk {
  stop-color: var(--svg-color--f0e6fa, #F0E6FA);
  stop-opacity: 0;
}

.aic5clbdd {
  d: path("m8.087 17.99l-2.629-5.63a.437.437 0 0 1 .213-.581a.35.35 0 0 0 .174-.459l-.761-1.723a1 1 0 0 1 .496-1.312l5.434-2.508a.4.4 0 0 1 .53.193l4.018 8.506a.4.4 0 0 1-.191.532L8.62 18.183a.4.4 0 0 1-.533-.193");
}

.atc6f_bqq {
  fill-rule: evenodd;
  d: path("m7.613 16.975l.474 1.015a.4.4 0 0 0 .533.193l.408-.192l-.637-1.376z");
}

.azm39lm3y {
  stop-color: var(--svg-color--ad9dbe, #AD9DBE);
  stop-opacity: 0;
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.bbgem7vvv {
  d: path("m23.807 17.651l-1.088-.486l-1.354 3.029a.4.4 0 0 0 .201.528l.358.16a.4.4 0 0 0 .528-.202z");
}

.c2vnnhbui {
  fill: var(--svg-color--e5dcf0, #E5DCF0);
  d: path("m8.087 17.99l-2.629-5.63a.437.437 0 0 1 .213-.581a.35.35 0 0 0 .174-.459l-.761-1.723a1 1 0 0 1 .496-1.312l5.434-2.508a.4.4 0 0 1 .53.193l4.018 8.506a.4.4 0 0 1-.191.532L8.62 18.183a.4.4 0 0 1-.533-.193");
}

.cen69q41k {
  fill: var(--svg-color--4f4f50, #4F4F50);
  fill-rule: evenodd;
  d: path("m9.749 18.036l.76 1.698l-.556.257l-.781-1.688zm.399 2.849a.4.4 0 0 1-.522-.205l-.2-.446l.527-.243l.376.813z");
}

.cmx031bix {
  fill: var(--svg-color--ede2f8, #EDE2F8);
  d: path("M29.622 14.327a1 1 0 0 0-.505-1.321l-3.78-1.691l-3.972 8.879a.4.4 0 0 0 .201.528l3.416 1.528a1 1 0 0 0 1.322-.504z");
}

.csogkqfmg {
  stop-color: var(--svg-color--ebe2f6, #EBE2F6);
  stop-opacity: 0;
}

.dj2j9vorp {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m6.826 15.29l-.787-1.686l.79-.366l.781 1.689z");
}

.eg6w_xgxi {
  fill: var(--svg-color--efe6f8, #EFE6F8);
  d: path("m8.271 17.651l1.088-.486l1.355 3.029a.4.4 0 0 1-.202.528l-.357.16a.4.4 0 0 1-.529-.202z");
}

.fm0uxeboe {
  stop-color: var(--svg-color--e5d9f2, #E5D9F2);
}

.fptfbcc1z {
  fill: var(--svg-color--212122, #212122);
  fill-rule: evenodd;
  d: path("M21.921 20.885a.4.4 0 0 0 .522-.205l.2-.446l-.526-.243l-.376.813z");
}

.ft5dv1b6b {
  fill: none;
}

.g5w4idwnc {
  fill-rule: evenodd;
  d: path("m13.517 10.146l.794 1.682l-1.603.741l-.781-1.688z");
}

.gsvhh_98v {
  stop-color: var(--svg-color--312d36, #312D36);
  stop-opacity: 0;
}

.h21foib9b {
  fill-rule: evenodd;
  d: path("m25.243 15.29l.787-1.686l-.79-.366l-.781 1.689z");
}

.h5kq-7bpd {
  d: path("m23.983 17.99l2.63-5.63a.437.437 0 0 0-.214-.581a.35.35 0 0 1-.173-.459l.76-1.723a1 1 0 0 0-.495-1.312l-5.435-2.508a.4.4 0 0 0-.529.193l-4.019 8.506a.4.4 0 0 0 .192.532l6.75 3.175a.4.4 0 0 0 .533-.193");
}

.hb-v1ibbv {
  stop-color: var(--svg-color--bfb0cf, #BFB0CF);
  stop-opacity: 0;
}

.hop683bux {
  stop-color: var(--svg-color--c6c2ca, #C6C2CA);
  stop-opacity: 0;
}

.hunmi-f3n {
  stop-color: var(--svg-color--ad9dbe, #AD9DBE);
}

.i-yogdblz {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m26.939 14.024l.762-1.648l1.407.63q.16.071.279.186l-.749 1.618zl-.78 1.689l-1.7-.786l.78-1.689zm2.328 1.077l-.76 1.698l-.65-.3l-.78 1.688l.67.31l-.759 1.698l-.692-.32l-.78 1.688l-1.7-.786l.78-1.688l1.7.786l.78-1.688l-1.698-.786l.78-1.688l1.7.785l.78-1.688zm-4.1 7.213a1 1 0 0 0 1.05-.427l-.702-.324zm.21-4.913l-1.699-.786l-.78 1.688l1.699.786zm-3.636 3.403l1.709.765l.366-.792l-1.7-.786z");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j0rmr7bri {
  fill: var(--svg-color--1e1e1f, #1E1E1F);
  fill-rule: evenodd;
  d: path("m22.32 18.036l-.76 1.698l.557.257l.78-1.688z");
}

.jbo8zcc8b {
  stop-color: var(--svg-color--727272, #727272);
}

.k0iunxzjd {
  stop-color: var(--svg-color--f0e6fa, #F0E6FA);
}

.ketg2kbhx {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m15.106 13.51l.456.966a.4.4 0 0 1-.191.532l-1.26.593l-.623-1.344z");
}

.kf0w67bzi {
  stop-color: var(--svg-color--312d36, #312D36);
}

.lt8yvfbbp {
  fill-rule: evenodd;
  d: path("m15.106 13.51l.456.966a.4.4 0 0 1-.191.532l-1.26.593l-.623-1.344z");
}

.msgdqmbxl {
  stop-color: var(--svg-color--8b779e, #8B779E);
  stop-opacity: 0;
}

.mxscfdb9w {
  stroke: var(--svg-color--959498, #959498);
  stroke-linecap: round;
  d: path("m21.77 4.725l-10.534 22.55");
}

.njw1xtbid {
  stop-color: var(--svg-color--322e37, #322E37);
  stop-opacity: 0;
}

.nt0iff9zo {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m5.13 14.024l-.762-1.648l-1.407.63a1 1 0 0 0-.279.186l.749 1.618zl.78 1.689l1.7-.786l-.782-1.689zm-2.327 1.077l.76 1.698l.649-.3l.78 1.688l-.67.31l.76 1.698l.691-.32l.78 1.688l1.7-.786l-.78-1.688l-1.7.786l-.78-1.688l1.699-.786l-.781-1.688l-1.7.785l-.78-1.688zM6.9 22.314a1 1 0 0 1-1.049-.427l.702-.324zm-.21-4.913l1.7-.786l.78 1.688l-1.699.786zm3.638 3.403l-1.71.765l-.366-.792l1.7-.786z");
}

.o__1t7bai {
  stop-color: var(--svg-color--a299ac, #A299AC);
  stop-opacity: 0;
}

.oa7-35axz {
  stop-color: var(--svg-color--bab5be, #BAB5BE);
}

.p0-igtb9f {
  stop-color: var(--svg-color--baaec7, #BAAEC7);
}

.p66l76blk {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
}

.p7x34fp3s {
  stroke: var(--svg-color--959498, #959498);
  stroke-linecap: round;
  d: path("m10.308 4.725l10.535 22.55");
}

.q7jb2ac6l {
  fill: var(--svg-color--c7bcd2, #C7BCD2);
  d: path("m23.807 17.651l-1.088-.486l-1.354 3.029a.4.4 0 0 0 .201.528l.358.16a.4.4 0 0 0 .528-.202z");
}

.qz53z_d5t {
  stop-color: var(--svg-color--dbd1e6, #DBD1E6);
  stop-opacity: 0;
}

.r9ns9qbfh {
  stop-color: var(--svg-color--a798b6, #A798B6);
}

.rjqk0f4sw {
  stop-color: var(--svg-color--bfb0cf, #BFB0CF);
}

.rvu3dtb5w {
  fill-rule: evenodd;
  d: path("m24.456 16.975l-.474 1.015a.4.4 0 0 1-.533.193l-.407-.192l.636-1.376z");
}

.samx7hpzs {
  stop-color: var(--svg-color--baaec7, #BAAEC7);
  stop-opacity: 0;
}

.su7n0db3d {
  fill-rule: evenodd;
  d: path("m6.826 15.29l-.787-1.686l.79-.366l.781 1.689z");
}

.t2wui94jw {
  stop-color: var(--svg-color--beb1cb, #BEB1CB);
}

.t4vvqikxs {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m25.647 7.897l-.545 1.18l1.7.785l.264-.573a1 1 0 0 0-.576-1.004zm-3.943-.393l.544-1.176l1.7.784l-.545 1.178zm3.398 1.572l-1.7-.786l-.78 1.688l-1.7-.785l-.78 1.688l1.7.786l.78-1.688l1.7.785zm-.78 1.688l1.698.786l-.78 1.688l-1.7-.785zm-1.562 3.377l1.699.786l-.78 1.688l-1.7-.786zl-1.698-.786l-.781 1.688l-1.7-.786l.781-1.688l1.7.786l.78-1.688l1.7.786zm-3.107 2.257l1.695.797l.631-1.366l-1.7-.786zm6.572-5.078a.35.35 0 0 0 .031.34l-.236-.11l.781-1.688l.056.026zm-1.769 5.655l-.474 1.015a.4.4 0 0 1-.533.193l-.407-.192l.636-1.376z");
}

.ttxgpvb2u {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m16.964 13.51l-.457.966a.4.4 0 0 0 .191.532l1.261.593l.622-1.344zm1.589-3.364l-.795 1.682l1.603.741l.781-1.688zm1.589-3.364l-.795 1.682l1.576.729l.78-1.689z");
}

.ucrimqbes {
  d: path("M2.457 14.327a1 1 0 0 1 .504-1.321l3.781-1.691l3.972 8.879a.4.4 0 0 1-.202.528L7.096 22.25a1 1 0 0 1-1.321-.504z");
}

.v8kfh5btg {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m6.422 7.897l.545 1.18l-1.699.785l-.265-.573a1 1 0 0 1 .577-1.004zm3.944-.393L9.82 6.328l-1.7.784l.545 1.178zM6.967 9.076l1.7-.786l.78 1.688l1.7-.785l.78 1.688l-1.7.786l-.78-1.688l-1.7.785zm.781 1.688l-1.7.786l.782 1.688l1.699-.785zm1.561 3.377l-1.699.786l.781 1.688l1.7-.786zl1.699-.786l.78 1.688l1.7-.786l-.781-1.688l-1.7.786l-.78-1.688l-1.7.786zm3.107 2.257l-1.694.797l-.632-1.366l1.7-.786zM5.844 11.32a.35.35 0 0 1-.031.34l.236-.11l-.781-1.688l-.056.026zm1.769 5.655l.474 1.015a.4.4 0 0 0 .533.193l.408-.192l-.637-1.376z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w1kry5b3h {
  stop-color: var(--svg-color--6d6d6d, #6D6D6D);
}

.wd-pmobbk {
  stop-color: var(--svg-color--d5c9e2, #D5C9E2);
}

.wstr51vhg {
  stop-color: var(--svg-color--c6c2ca, #C6C2CA);
}

.xe0sbz8jo {
  fill-rule: evenodd;
  d: path("m11.927 6.782l.795 1.682l-1.576.729l-.78-1.689z");
}

.yipk3-bws {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m13.517 10.146l.794 1.682l-1.603.741l-.781-1.688z");
}

.yndmnshjq {
  fill: var(--svg-color--e5dbf0, #E5DBF0);
  d: path("m23.983 17.99l2.63-5.63a.437.437 0 0 0-.214-.581a.35.35 0 0 1-.173-.459l.76-1.723a1 1 0 0 0-.495-1.312l-5.435-2.508a.4.4 0 0 0-.529.193l-4.019 8.506a.4.4 0 0 0 .192.532l6.75 3.175a.4.4 0 0 0 .533-.193");
}

.zv061_bcq {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m11.927 6.782l.795 1.682l-1.576.729l-.78-1.689z");
}

.zx5zdldjr {
  fill: var(--svg-color--312d36, #312D36);
  fill-rule: evenodd;
  d: path("m25.243 15.29l.787-1.686l-.79-.366l-.781 1.689z");
}

</style>
