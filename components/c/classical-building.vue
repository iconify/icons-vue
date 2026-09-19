<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iM610ze)" class="q0_vspaoh"/><path class="h2nw87n_n"/><path fill="url(#iQfZjoN)" class="ds_zot4ks"/><path fill="url(#iV5iiLd)" class="ds_zot4ks"/><path fill="url(#i6XViAd)" class="ds_zot4ks"/><path class="wzd43p3yy"/><path fill="url(#iUJkSpc)" class="fea0r_siq"/><path fill="url(#iKT1yjd)" class="fea0r_siq"/><path fill="url(#iVmweMA)" class="fea0r_siq"/><path fill="url(#iHHCd2b)" class="nhielbb9p"/><path fill="url(#i6ZpEHe)" class="nhielbb9p"/><path fill="url(#iBBPnRb)" class="b4v5mnznc"/><path fill="url(#ihshoZT)" class="b4v5mnznc"/><path fill="url(#iGGg37d)" class="zovtqobwt"/><path fill="url(#iYvPHqd)" class="zovtqobwt"/><path fill="url(#itek4lc)" class="ppqvghb_i"/><path fill="url(#iOdcSme)" class="ppqvghb_i"/><path fill="url(#irlzQUb)" class="xwi5qbcah"/><path fill="url(#iefUMJd)" class="xwi5qbcah"/><path fill="url(#iH0w4kb)" class="xwi5qbcah"/><path fill="url(#i6KUZ2v)" class="xwi5qbcah"/><path fill="url(#iEejj5b)" class="xcktlkbjp"/><path fill="url(#iai8mSb)" class="xcktlkbjp"/><path fill="url(#iH5U9sb)" class="xcktlkbjp"/><path fill="url(#iU8mzbE)" class="m5p_9g9np"/><path fill="url(#inI0Kqe)" class="m5p_9g9np"/><path fill="url(#itoZ2Sb)" class="m5p_9g9np"/><path fill="url(#ipnjm6i)" class="oe03mzhdf"/><path fill="url(#ifXlnWf)" class="oe03mzhdf"/><path fill="url(#iCaoFBb)" class="oe03mzhdf"/><path fill="url(#iGWi7Kc)" class="qin8gf0rt"/><path fill="url(#idu8Btb)" class="qin8gf0rt"/><path fill="url(#iDJDhQd)" class="qin8gf0rt"/><path fill="url(#iGDvNyd)" class="tpy8p-b_j"/><path fill="url(#iay1Cge)" class="tpy8p-b_j"/><path fill="url(#icheCAc)" class="tpy8p-b_j"/><path fill="url(#iRMB8Xd)" class="hb_yudb7v"/><path fill="url(#iXgFBhr)" class="hb_yudb7v"/><path fill="url(#iuXcrKd)" class="hb_yudb7v"/><path fill="url(#iJjGqRc)" class="twfg9jbip"/><path fill="url(#iVDMrXg)" class="twfg9jbip"/><path fill="url(#inAJ2Oe)" class="twfg9jbip"/><path fill="url(#i6fn5jc)" class="m0espzogx"/><path fill="url(#iD9Pgrb)" class="m0espzogx"/><path fill="url(#ibfJWkB)" class="m0espzogx"/><g filter="url(#i3goPje)"><path fill="url(#iFYBbuc)" class="w281w9b2q"/></g><g filter="url(#ioQXbsd)"><path class="w0bzgjbna"/></g><g filter="url(#iHwbjgc)"><path stroke="url(#iI9XXRb)" class="h9wm6cbik"/></g><defs><linearGradient id="iM610ze" x1="16.503" x2="16.503" y1="11.686" y2="26.48" gradientUnits="userSpaceOnUse"><stop class="g1730k9jq"/><stop offset="1" class="m24j37q5x"/></linearGradient><linearGradient id="iQfZjoN" x1="29.297" x2="28.197" y1="28.404" y2="28.404" gradientUnits="userSpaceOnUse"><stop class="zt2lgydao"/><stop offset="1" class="cpektjbks"/></linearGradient><linearGradient id="iV5iiLd" x1="16" x2="16" y1="26.47" y2="27.241" gradientUnits="userSpaceOnUse"><stop class="u3hnnsbrc"/><stop offset="1" class="zx8lxbcrd"/></linearGradient><linearGradient id="i6XViAd" x1="2.93" x2="3.856" y1="29.47" y2="29.47" gradientUnits="userSpaceOnUse"><stop class="k_qq7s8zi"/><stop offset="1" class="t2aykxbuc"/></linearGradient><linearGradient id="iUJkSpc" x1="27.995" x2="27.358" y1="12.49" y2="12.49" gradientUnits="userSpaceOnUse"><stop class="ofiorffzk"/><stop offset="1" class="hbww8qbbx"/></linearGradient><linearGradient id="iKT1yjd" x1="16.015" x2="16.015" y1="12.733" y2="11.898" gradientUnits="userSpaceOnUse"><stop class="n-hp9zbxp"/><stop offset="1" class="auqvj8b0e"/></linearGradient><linearGradient id="iVmweMA" x1="3.886" x2="4.761" y1="12.49" y2="12.49" gradientUnits="userSpaceOnUse"><stop class="jfbpi_b3i"/><stop offset="1" class="h2h3i5b_a"/></linearGradient><linearGradient id="iHHCd2b" x1="6.006" x2="9.432" y1="19.511" y2="19.511" gradientUnits="userSpaceOnUse"><stop class="xfu3hgb0v"/><stop offset=".573" class="n6ge8pbaa"/><stop offset=".672" class="n6ge8pbaa"/><stop offset="1" class="pwki66aju"/></linearGradient><linearGradient id="i6ZpEHe" x1="7.5" x2="7.5" y1="13.219" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="s11dyubtv"/><stop offset="1" class="yh66z7-jc"/></linearGradient><linearGradient id="iBBPnRb" x1="11.666" x2="15.092" y1="19.511" y2="19.511" gradientUnits="userSpaceOnUse"><stop class="dyv37qbxs"/><stop offset=".573" class="vh18yybpt"/><stop offset=".672" class="vh18yybpt"/><stop offset="1" class="l9avh4u-w"/></linearGradient><linearGradient id="ihshoZT" x1="13.16" x2="13.16" y1="13.219" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="s11dyubtv"/><stop offset="1" class="yh66z7-jc"/></linearGradient><linearGradient id="iGGg37d" x1="17.326" x2="20.752" y1="19.511" y2="19.511" gradientUnits="userSpaceOnUse"><stop class="q82c6reuw"/><stop offset=".573" class="n4h5-q2od"/><stop offset=".672" class="n4h5-q2od"/><stop offset="1" class="r3al79bxg"/></linearGradient><linearGradient id="iYvPHqd" x1="18.82" x2="18.82" y1="13.219" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="s11dyubtv"/><stop offset="1" class="yh66z7-jc"/></linearGradient><linearGradient id="itek4lc" x1="22.986" x2="26.412" y1="19.511" y2="19.511" gradientUnits="userSpaceOnUse"><stop class="q5lcm4bli"/><stop offset=".573" class="xhlnhyb9q"/><stop offset=".672" class="u_kw5mb5m"/><stop offset="1" class="dtvw-rhgn"/></linearGradient><linearGradient id="iOdcSme" x1="24.48" x2="24.48" y1="13.219" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="s11dyubtv"/><stop offset="1" class="yh66z7-jc"/></linearGradient><linearGradient id="irlzQUb" x1="19.871" x2="16.006" y1="4.385" y2="11.072" gradientUnits="userSpaceOnUse"><stop class="e0a4yni_a"/><stop offset="1" class="l9icbbcqi"/></linearGradient><linearGradient id="iefUMJd" x1="20.449" x2="20.09" y1="5.854" y2="6.479" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="a-c9fpbum"/></linearGradient><linearGradient id="iH0w4kb" x1="16.006" x2="16.006" y1="11.063" y2="10.362" gradientUnits="userSpaceOnUse"><stop class="khr99qb-b"/><stop offset="1" class="v4-m3fb3a"/></linearGradient><linearGradient id="i6KUZ2v" x1="11.87" x2="12.073" y1="5.531" y2="5.891" gradientUnits="userSpaceOnUse"><stop offset=".345" class="zdecnpqrh"/><stop offset="1" class="oxt8qmxir"/></linearGradient><linearGradient id="iai8mSb" x1="7.51" x2="7.51" y1="12.18" y2="12.761" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="iH5U9sb" x1="7.51" x2="7.51" y1="13.771" y2="13.298" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="inI0Kqe" x1="13.16" x2="13.16" y1="12.18" y2="12.761" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="itoZ2Sb" x1="13.16" x2="13.16" y1="13.771" y2="13.298" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="ifXlnWf" x1="18.83" x2="18.83" y1="12.18" y2="12.761" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="iCaoFBb" x1="18.83" x2="18.83" y1="13.771" y2="13.298" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="idu8Btb" x1="24.49" x2="24.49" y1="12.18" y2="12.761" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="iDJDhQd" x1="24.49" x2="24.49" y1="13.771" y2="13.298" gradientUnits="userSpaceOnUse"><stop class="ifgzk3ibd"/><stop offset="1" class="zxrl_acpg"/></linearGradient><linearGradient id="iay1Cge" x1="22.96" x2="23.819" y1="27.351" y2="25.778" gradientUnits="userSpaceOnUse"><stop class="ik169bb3c"/><stop offset="1" class="k85687bra"/></linearGradient><linearGradient id="icheCAc" x1="27.631" x2="26.319" y1="26.156" y2="26.48" gradientUnits="userSpaceOnUse"><stop class="b0og-vbjl"/><stop offset="1" class="yrhillbfj"/></linearGradient><linearGradient id="iXgFBhr" x1="17.311" x2="18.169" y1="27.351" y2="25.778" gradientUnits="userSpaceOnUse"><stop class="ik169bb3c"/><stop offset="1" class="k85687bra"/></linearGradient><linearGradient id="iuXcrKd" x1="21.981" x2="20.669" y1="26.156" y2="26.48" gradientUnits="userSpaceOnUse"><stop class="b0og-vbjl"/><stop offset="1" class="yrhillbfj"/></linearGradient><linearGradient id="iVDMrXg" x1="11.641" x2="12.499" y1="27.351" y2="25.778" gradientUnits="userSpaceOnUse"><stop class="ik169bb3c"/><stop offset="1" class="k85687bra"/></linearGradient><linearGradient id="inAJ2Oe" x1="16.311" x2="14.999" y1="26.156" y2="26.48" gradientUnits="userSpaceOnUse"><stop class="b0og-vbjl"/><stop offset="1" class="yrhillbfj"/></linearGradient><linearGradient id="iD9Pgrb" x1="5.981" x2="6.839" y1="27.351" y2="25.778" gradientUnits="userSpaceOnUse"><stop class="ik169bb3c"/><stop offset="1" class="k85687bra"/></linearGradient><linearGradient id="ibfJWkB" x1="10.651" x2="9.339" y1="26.156" y2="26.48" gradientUnits="userSpaceOnUse"><stop class="b0og-vbjl"/><stop offset="1" class="yrhillbfj"/></linearGradient><linearGradient id="iFYBbuc" x1="26.381" x2="4.551" y1="8.533" y2="8.533" gradientUnits="userSpaceOnUse"><stop class="govs_2bmf"/><stop offset="1" class="pamlbcc2j"/></linearGradient><linearGradient id="iI9XXRb" x1="5.339" x2="19.182" y1="9.156" y2=".844" gradientUnits="userSpaceOnUse"><stop class="asscap08w"/><stop offset="1" class="w5cdcqk1u"/></linearGradient><radialGradient id="iEejj5b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24521 0 0 -.937 8.797 12.993)" gradientUnits="userSpaceOnUse"><stop class="bs8sbdb7x"/><stop offset="1" class="z-cd6ssup"/></radialGradient><radialGradient id="iU8mzbE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2452 0 0 -.937 14.447 12.993)" gradientUnits="userSpaceOnUse"><stop class="bs8sbdb7x"/><stop offset="1" class="z-cd6ssup"/></radialGradient><radialGradient id="ipnjm6i" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2452 0 0 -.937 20.117 12.993)" gradientUnits="userSpaceOnUse"><stop class="bs8sbdb7x"/><stop offset="1" class="z-cd6ssup"/></radialGradient><radialGradient id="iGWi7Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2452 0 0 -.937 25.777 12.993)" gradientUnits="userSpaceOnUse"><stop class="bs8sbdb7x"/><stop offset="1" class="z-cd6ssup"/></radialGradient><radialGradient id="iGDvNyd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58035 0 0 -.66846 25.561 25.976)" gradientUnits="userSpaceOnUse"><stop class="e0xc83bfh"/><stop offset="1" class="xejvh6b3k"/></radialGradient><radialGradient id="iRMB8Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58035 0 0 -.66846 19.911 25.976)" gradientUnits="userSpaceOnUse"><stop class="wxitmfd0k"/><stop offset="1" class="jid1sw7-q"/></radialGradient><radialGradient id="iJjGqRc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58035 0 0 -.66846 14.241 25.976)" gradientUnits="userSpaceOnUse"><stop class="wxitmfd0k"/><stop offset="1" class="jid1sw7-q"/></radialGradient><radialGradient id="i6fn5jc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58035 0 0 -.66846 8.581 25.976)" gradientUnits="userSpaceOnUse"><stop class="wxitmfd0k"/><stop offset="1" class="jid1sw7-q"/></radialGradient><filter id="i3goPje" width="26.207" height="8.11" x="3.002" y="2.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.462745 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5526"/></filter><filter id="ioQXbsd" width="13.526" height="8.055" x="15.653" y="2.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5526" stdDeviation=".15"/></filter><filter id="iHwbjgc" width="12.775" height="7.65" x="3.232" y="2.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5526" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:classical-building" /></template>
<style>
.a-c9fpbum {
  stop-color: var(--svg-color--645a6f, #645A6F);
  stop-opacity: 0;
}

.asscap08w {
  stop-color: var(--svg-color--b3adba, #B3ADBA);
}

.auqvj8b0e {
  stop-color: var(--svg-color--726483, #726483);
  stop-opacity: 0;
}

.b0og-vbjl {
  stop-color: var(--svg-color--807c87, #807C87);
}

.b4v5mnznc {
  d: path("M14.655 13.46h-2.99v12.1h2.99z");
}

.bs8sbdb7x {
  stop-color: var(--svg-color--91899d, #91899D);
}

.cpektjbks {
  stop-color: var(--svg-color--fcf2ff, #FCF2FF);
  stop-opacity: 0;
}

.ds_zot4ks {
  d: path("M28.965 29.47H3.025V27.1c0-.35.28-.63.63-.63h24.69c.35 0 .63.28.63.63v2.37z");
}

.dtvw-rhgn {
  stop-color: var(--svg-color--d5cddc, #D5CDDC);
}

.dyv37qbxs {
  stop-color: var(--svg-color--7b7681, #7B7681);
}

.e0a4yni_a {
  stop-color: var(--svg-color--b3acbb, #B3ACBB);
}

.e0xc83bfh {
  stop-color: var(--svg-color--f7edfd, #F7EDFD);
}

.fea0r_siq {
  d: path("M4.045 10.49h23.95v1.37c0 .35-.28.63-.63.63h-22.7c-.35 0-.63-.28-.63-.63v-1.37z");
}

.ft5dv1b6b {
  fill: none;
}

.g1730k9jq {
  stop-color: var(--svg-color--35303b, #35303B);
}

.govs_2bmf {
  stop-color: var(--svg-color--ada7b8, #ADA7B8);
}

.h2h3i5b_a {
  stop-color: var(--svg-color--706d76, #706D76);
  stop-opacity: 0;
}

.h2nw87n_n {
  fill: var(--svg-color--b9b4c3, #B9B4C3);
  d: path("M28.965 29.47H3.025V27.1c0-.35.28-.63.63-.63h24.69c.35 0 .63.28.63.63v2.37z");
}

.h9wm6cbik {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m3.682 10l11.875-6.75");
}

.hb_yudb7v {
  d: path("M16.335 26.48h4.99v-.19c0-.45-.36-.81-.81-.81h-3.37c-.45 0-.81.36-.81.81z");
}

.hbww8qbbx {
  stop-color: var(--svg-color--e8dfef, #E8DFEF);
  stop-opacity: 0;
}

.ifgzk3ibd {
  stop-color: var(--svg-color--564f5e, #564F5E);
}

.ik169bb3c {
  stop-color: var(--svg-color--656067, #656067);
}

.jfbpi_b3i {
  stop-color: var(--svg-color--706d76, #706D76);
}

.jid1sw7-q {
  stop-color: var(--svg-color--9a949e, #9A949E);
}

.k_qq7s8zi {
  stop-color: var(--svg-color--7a7680, #7A7680);
}

.k85687bra {
  stop-color: var(--svg-color--656067, #656067);
  stop-opacity: 0;
}

.khr99qb-b {
  stop-color: var(--svg-color--878190, #878190);
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l9avh4u-w {
  stop-color: var(--svg-color--b2abb8, #B2ABB8);
}

.l9icbbcqi {
  stop-color: var(--svg-color--aca5b2, #ACA5B2);
}

.m0espzogx {
  d: path("M5.005 26.48h4.99v-.19c0-.45-.36-.81-.81-.81h-3.37c-.45 0-.81.36-.81.81z");
}

.m24j37q5x {
  stop-color: var(--svg-color--65527a, #65527A);
}

.m5p_9g9np {
  d: path("M15.655 12.49h-4.99v.19c0 .45.36.81.81.81h3.37c.45 0 .81-.36.81-.81z");
}

.n-hp9zbxp {
  stop-color: var(--svg-color--726483, #726483);
}

.n4h5-q2od {
  stop-color: var(--svg-color--cbc3d3, #CBC3D3);
}

.n6ge8pbaa {
  stop-color: var(--svg-color--cfc7d7, #CFC7D7);
}

.nhielbb9p {
  d: path("M8.995 13.46h-2.99v12.1h2.99z");
}

.oe03mzhdf {
  d: path("M21.325 12.49h-4.99v.19c0 .45.36.81.81.81h3.37c.45 0 .81-.36.81-.81z");
}

.ofiorffzk {
  stop-color: var(--svg-color--e8dfef, #E8DFEF);
}

.oxt8qmxir {
  stop-color: var(--svg-color--857f8e, #857F8E);
  stop-opacity: 0;
}

.pamlbcc2j {
  stop-color: var(--svg-color--9f99a4, #9F99A4);
}

.ppqvghb_i {
  d: path("M25.975 13.46h-2.99v12.1h2.99z");
}

.pwki66aju {
  stop-color: var(--svg-color--9a94a1, #9A94A1);
}

.q0_vspaoh {
  d: path("M23.025 12.49H9.005v13.99h14.02z");
}

.q5lcm4bli {
  stop-color: var(--svg-color--615e6a, #615E6A);
}

.q82c6reuw {
  stop-color: var(--svg-color--6e6a73, #6E6A73);
}

.qin8gf0rt {
  d: path("M26.985 12.49h-4.99v.19c0 .45.36.81.81.81h3.37c.45 0 .81-.36.81-.81z");
}

.r3al79bxg {
  stop-color: var(--svg-color--bfb9c5, #BFB9C5);
}

.s11dyubtv {
  stop-color: var(--svg-color--71677d, #71677D);
}

.t2aykxbuc {
  stop-color: var(--svg-color--7a7680, #7A7680);
  stop-opacity: 0;
}

.tpy8p-b_j {
  d: path("M21.985 26.48h4.99v-.19c0-.45-.36-.81-.81-.81h-3.37c-.45 0-.81.36-.81.81z");
}

.twfg9jbip {
  d: path("M10.665 26.48h4.99v-.19c0-.45-.36-.81-.81-.81h-3.37c-.45 0-.81.36-.81.81z");
}

.u_kw5mb5m {
  stop-color: var(--svg-color--dcd4e4, #DCD4E4);
}

.u3hnnsbrc {
  stop-color: var(--svg-color--ccc4d0, #CCC4D0);
}

.v4-m3fb3a {
  stop-color: var(--svg-color--878190, #878190);
  stop-opacity: 0;
}

.vh18yybpt {
  stop-color: var(--svg-color--bfb9c8, #BFB9C8);
}

.w0bzgjbna {
  stroke: var(--svg-color--dad0df, #DAD0DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.103 2.83L28.73 9.984");
}

.w281w9b2q {
  d: path("m28.775 9.67l-12.52-7.11a.54.54 0 0 0-.5 0L3.235 9.67c-.22.13-.3.4-.17.62c.09.14.24.22.4.22q.12 0 .24-.06l12.07-6.85a.47.47 0 0 1 .46 0l12.07 6.85c.07.04.16.06.24.06c.16 0 .32-.08.4-.22c.13-.22.06-.5-.17-.62");
}

.w5cdcqk1u {
  stop-color: var(--svg-color--b3adba, #B3ADBA);
  stop-opacity: 0;
}

.wxitmfd0k {
  stop-color: var(--svg-color--e4daea, #E4DAEA);
}

.wzd43p3yy {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M4.045 10.49h23.95v1.37c0 .35-.28.63-.63.63h-22.7c-.35 0-.63-.28-.63-.63v-1.37z");
}

.xcktlkbjp {
  d: path("M10.005 12.49h-4.99v.19c0 .45.36.81.81.81h3.37c.45 0 .81-.36.81-.81z");
}

.xejvh6b3k {
  stop-color: var(--svg-color--a29ca7, #A29CA7);
}

.xfu3hgb0v {
  stop-color: var(--svg-color--817c86, #817C86);
}

.xhlnhyb9q {
  stop-color: var(--svg-color--dad2e2, #DAD2E2);
}

.xwi5qbcah {
  d: path("M15.326 3.01L3.366 9.75c-.36.2-.22.76.2.76h24.88c.42 0 .56-.55.2-.76l-11.96-6.74c-.42-.24-.94-.24-1.36 0");
}

.yh66z7-jc {
  stop-color: var(--svg-color--71677d, #71677D);
  stop-opacity: 0;
}

.yrhillbfj {
  stop-color: var(--svg-color--807c87, #807C87);
  stop-opacity: 0;
}

.z-cd6ssup {
  stop-color: var(--svg-color--6d6976, #6D6976);
}

.zdecnpqrh {
  stop-color: var(--svg-color--857f8e, #857F8E);
}

.zovtqobwt {
  d: path("M20.315 13.46h-2.99v12.1h2.99z");
}

.zt2lgydao {
  stop-color: var(--svg-color--fcf2ff, #FCF2FF);
}

.zx8lxbcrd {
  stop-color: var(--svg-color--ccc4d0, #CCC4D0);
  stop-opacity: 0;
}

.zxrl_acpg {
  stop-color: var(--svg-color--564f5e, #564F5E);
  stop-opacity: 0;
}

</style>
