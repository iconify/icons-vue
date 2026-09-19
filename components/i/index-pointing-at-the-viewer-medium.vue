<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imKnUNR)"><path class="pqpc7ps4v"/><path fill="url(#inT4Eac)" class="yo_h1xbeu"/></g><path fill="url(#iF7gSRc)" class="c9jw-mt0w"/><path fill="url(#iWc4VBe)" class="c9jw-mt0w"/><path fill="url(#iba6Asd)" class="c9jw-mt0w"/><path fill="url(#iEMndPe)" class="c9jw-mt0w"/><path fill="url(#iD9xbqc)" class="c9jw-mt0w"/><path fill="url(#ifIAQ5d)" class="zereas7mi"/><path fill="url(#i6dc7dd)" class="zereas7mi"/><path fill="url(#iXstInd)" class="zereas7mi"/><path fill="url(#iw277Bb)" class="zereas7mi"/><path fill="url(#iIvhhIb)" class="ukbim5boq"/><path fill="url(#ib5DF2d)" class="ukbim5boq"/><path fill="url(#iNeXe8c)" class="ukbim5boq"/><path fill="url(#iF8Rr3c)" class="ukbim5boq"/><path fill="url(#ithThWd)" class="nlj0vxbdo"/><path fill="url(#iXd7BAc)" class="nlj0vxbdo"/><path fill="url(#iT6nSJd)" class="nlj0vxbdo"/><path fill="url(#isJxOHb)" class="nlj0vxbdo"/><g filter="url(#iiB4lid)"><path class="palc9wbhh"/><path fill="url(#iwPlCRW)" class="v4t4xdb4c"/></g><path fill="url(#iRA0HfS)" class="v4t4xdb4c"/><path fill="url(#iDuyGuc)" class="v4t4xdb4c"/><path fill="url(#iGr2m9P)" class="v4t4xdb4c"/><rect fill="url(#i1WXczc)" class="vpltdfbhe"/><rect fill="url(#iJta3ye)" class="vpltdfbhe"/><rect fill="url(#i2kJNyd)" class="vpltdfbhe"/><rect fill="url(#iqAUPgc)" class="vpltdfbhe"/><rect fill="url(#ioHUseb)" class="vpltdfbhe"/><rect fill="url(#iW0o1re)" class="vpltdfbhe"/><rect fill="url(#iFSYmLb)" class="vpltdfbhe"/><g filter="url(#iT1OFcc)"><path fill="url(#iz3Jrdt)" class="ubs7yur_y"/></g><g filter="url(#iy7Genb)"><rect fill="url(#iLUOytb)" class="nbbbsebgu"/></g><g filter="url(#iUUON9d)"><rect fill="url(#iQATKOe)" class="jqj_efbdb"/></g><g filter="url(#iQhPJte)"><path class="qp_n0941s"/></g><defs><radialGradient id="inT4Eac" cx="0" cy="0" r="1" gradientTransform="matrix(3.22822 9.08798 -11.67443 4.14698 23 11.103)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bqrd3pb1l"/><stop offset="1" class="wzkue7yqo"/></radialGradient><radialGradient id="iF7gSRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.18707 4.77018 0 12.39 26.17)" gradientUnits="userSpaceOnUse"><stop class="s8k379b7a"/><stop offset="1" class="yaqnefbms"/></radialGradient><radialGradient id="iEMndPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3466 -6.91977 0 11.63 16.638)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="hxr-reb3g"/><stop offset=".959" class="mtryydbuf"/></radialGradient><radialGradient id="iD9xbqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.74168 6.33423 0 11.63 23.25)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="bourxibuq"/><stop offset=".987" class="njmeptb4c"/></radialGradient><radialGradient id="ifIAQ5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.7595 7.31603 0 6.188 26.582)" gradientUnits="userSpaceOnUse"><stop class="zzqv8qbze"/><stop offset="1" class="vtjv65b5n"/></radialGradient><radialGradient id="iXstInd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.42709 -6.45029 0 5.263 17.521)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="gq01erb2e"/><stop offset="1" class="sqo2_1jyr"/><stop offset="1" class="n84_85bjx"/></radialGradient><radialGradient id="ib5DF2d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66527 0 0 -6.70115 21.267 22.561)" gradientUnits="userSpaceOnUse"><stop class="i8b6iu8zu"/><stop offset="1" class="a-en51btw"/></radialGradient><radialGradient id="ithThWd" cx="0" cy="0" r="1" gradientTransform="rotate(-92.104 24.26 -2.227)scale(13.2673 7.2243)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="u6dcu5_uo"/><stop offset=".697" class="l7ubcgbxh"/></radialGradient><radialGradient id="iXd7BAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.46536 1.87897 0 21.252 22.008)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="euf11bchs"/><stop offset="1" class="eqrde9ven"/></radialGradient><radialGradient id="iT6nSJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2452 3.784 -11.4046 9.78069 20.912 14.213)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="biu66j49h"/><stop offset="1" class="e_s2_-36h"/></radialGradient><radialGradient id="isJxOHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.7611 -6.01353 6.78822 1.98797 26.324 23.902)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="sd2-ki-1n"/><stop offset=".508" class="zv-qf599o"/></radialGradient><radialGradient id="iwPlCRW" cx="0" cy="0" r="1" gradientTransform="matrix(6.04842 0 0 1.15509 23.113 21.28)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="m2qz3yb5c"/><stop offset="1" class="enu_ehbwf"/></radialGradient><radialGradient id="iDuyGuc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7592 0 0 -9.5527 26.697 25.353)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="y7yqahbmr"/><stop offset="1" class="v_khwubzx"/></radialGradient><radialGradient id="iGr2m9P" cx="0" cy="0" r="1" gradientTransform="matrix(.54129 1.709 -.78538 .24875 15.128 26.817)" gradientUnits="userSpaceOnUse"><stop class="u0i_fd88n"/><stop offset="1" class="s9w5vg5ci"/></radialGradient><radialGradient id="i1WXczc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61197 -8.63989 0 28.234 9.37)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="v3b5nab-t"/><stop offset=".453" class="fcr2ysbgj"/></radialGradient><radialGradient id="iJta3ye" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83928 0 0 -9.61491 28.84 9.752)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="nxn-j0b0h"/><stop offset="1" class="a2ajl_bly"/></radialGradient><radialGradient id="i2kJNyd" cx="0" cy="0" r="1" gradientTransform="rotate(-84.83 20.517 -5.075)scale(6.52837 9.41844)" gradientUnits="userSpaceOnUse"><stop class="t4ihwcxzi"/><stop offset="1" class="rub8babna"/></radialGradient><radialGradient id="iqAUPgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.875 -8.86618 0 24.82 5.526)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="i39ttcbtx"/><stop offset=".872" class="w5e0ouraa"/></radialGradient><radialGradient id="ioHUseb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46077 0 0 -13.4107 27.11 9.752)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="xp8v2vfva"/><stop offset="1" class="wx6jig5kw"/></radialGradient><radialGradient id="iW0o1re" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.96323 -2.65156 0 24.82 3.688)" gradientUnits="userSpaceOnUse"><stop class="taut6bc4y"/><stop offset="1" class="nxn-j0b0h"/></radialGradient><radialGradient id="iFSYmLb" cx="0" cy="0" r="1" gradientTransform="rotate(-45 26.646 -19.136)scale(11.6673)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nxn-j0b0h"/><stop offset="1" class="wdsscobsv"/></radialGradient><linearGradient id="iWc4VBe" x1="8.511" x2="11.261" y1="20.305" y2="20.305" gradientUnits="userSpaceOnUse"><stop class="xkgdxux7m"/><stop offset="1" class="u6-oeqbip"/></linearGradient><linearGradient id="iba6Asd" x1="14.418" x2="13.27" y1="21.297" y2="21.297" gradientUnits="userSpaceOnUse"><stop class="qmkv_unme"/><stop offset="1" class="dgvv81fyn"/></linearGradient><linearGradient id="i6dc7dd" x1="8.865" x2="6.582" y1="22.265" y2="22.265" gradientUnits="userSpaceOnUse"><stop class="a8gta-bsp"/><stop offset="1" class="xab3xyb5d"/></linearGradient><linearGradient id="iw277Bb" x1="8.654" x2="8.069" y1="15.786" y2="16.843" gradientUnits="userSpaceOnUse"><stop class="njmeptb4c"/><stop offset="1" class="bourxibuq"/></linearGradient><linearGradient id="iIvhhIb" x1="14.307" x2="18.162" y1="22.857" y2="22.857" gradientUnits="userSpaceOnUse"><stop class="ol_3ii-gy"/><stop offset="1" class="kl4p_qbpv"/></linearGradient><linearGradient id="iNeXe8c" x1="14.27" x2="15.158" y1="15.823" y2="17.304" gradientUnits="userSpaceOnUse"><stop class="r-d7trp-i"/><stop offset="1" class="bd-0rybzt"/></linearGradient><linearGradient id="iF8Rr3c" x1="15.394" x2="15.394" y1="27.43" y2="23.961" gradientUnits="userSpaceOnUse"><stop class="cqbgf4b4l"/><stop offset="1" class="t_i6wtj8h"/></linearGradient><linearGradient id="iRA0HfS" x1="21.489" x2="21.489" y1="29.686" y2="27.951" gradientUnits="userSpaceOnUse"><stop class="otf1mnoto"/><stop offset="1" class="mhvitvbof"/></linearGradient><linearGradient id="iz3Jrdt" x1="25.924" x2="24.712" y1="26.353" y2="23.204" gradientUnits="userSpaceOnUse"><stop offset=".228" class="x8c5dsbku"/><stop offset="1" class="vsz0fjbqu"/></linearGradient><linearGradient id="iLUOytb" x1="6.514" x2="6.514" y1="15.207" y2="24.611" gradientUnits="userSpaceOnUse"><stop offset=".395" class="x2cfwjwld"/><stop offset="1" class="xvd6kc_kc"/></linearGradient><linearGradient id="iQATKOe" x1="12.359" x2="12.359" y1="14.549" y2="26.582" gradientUnits="userSpaceOnUse"><stop offset=".395" class="d0wb5fb-u"/><stop offset=".758" class="o2kuq2b1v"/></linearGradient><filter id="imKnUNR" width="22.598" height="20.153" x="2.342" y="7.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.462745 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7109"/></filter><filter id="iiB4lid" width="14.807" height="10.665" x="15.128" y="19.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.439216 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7109"/></filter><filter id="iT1OFcc" width="13.325" height="6.947" x="16.434" y="20.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7109" stdDeviation=".75"/></filter><filter id="iy7Genb" width="3.813" height="11.405" x="4.608" y="14.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7109" stdDeviation=".5"/></filter><filter id="iUUON9d" width="3.813" height="14.032" x="10.453" y="13.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7109" stdDeviation=".5"/></filter><filter id="iQhPJte" width="7.27" height="6.265" x="7.292" y="8.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7109" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-at-the-viewer-medium" /></template>
<style>
.a-en51btw {
  stop-color: var(--svg-color--b2896b, #B2896B);
  stop-opacity: 0;
}

.a2ajl_bly {
  stop-color: var(--svg-color--8c7667, #8C7667);
}

.a8gta-bsp {
  stop-color: var(--svg-color--7f564c, #7F564C);
}

.bd-0rybzt {
  stop-color: var(--svg-color--8f695d, #8F695D);
  stop-opacity: 0;
}

.biu66j49h {
  stop-color: var(--svg-color--7e5057, #7E5057);
}

.bourxibuq {
  stop-color: var(--svg-color--987363, #987363);
  stop-opacity: 0;
}

.bqrd3pb1l {
  stop-color: var(--svg-color--6b4140, #6B4140);
}

.c9jw-mt0w {
  d: path("M15.04 26.72a3.7 3.7 0 0 1-.344-.668c-.227.484-1.181 1.491-2.846 1.491c-2.234 0-3.029-1.78-3.248-2.468q-.029.047-.064.098a52 52 0 0 1-.026-1.731V13.216l5.996 2.685v8.458c0 .556.4 1.296.624 1.709c.067.124.118.219.138.27c-.04.097-.119.23-.23.381");
}

.cqbgf4b4l {
  stop-color: var(--svg-color--7c4857, #7C4857);
}

.d0wb5fb-u {
  stop-color: var(--svg-color--a27b70, #A27B70);
}

.dgvv81fyn {
  stop-color: var(--svg-color--8a5f57, #8A5F57);
  stop-opacity: 0;
}

.e_s2_-36h {
  stop-color: var(--svg-color--7e5057, #7E5057);
  stop-opacity: 0;
}

.enu_ehbwf {
  stop-color: var(--svg-color--936b51, #936B51);
  stop-opacity: 0;
}

.eqrde9ven {
  stop-color: var(--svg-color--8b614a, #8B614A);
  stop-opacity: 0;
}

.euf11bchs {
  stop-color: var(--svg-color--8a5c47, #8A5C47);
}

.fcr2ysbgj {
  stop-color: var(--svg-color--a07c67, #A07C67);
}

.ft5dv1b6b {
  fill: none;
}

.gq01erb2e {
  stop-color: var(--svg-color--92596f, #92596F);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i39ttcbtx {
  stop-color: var(--svg-color--996172, #996172);
  stop-opacity: 0;
}

.i8b6iu8zu {
  stop-color: var(--svg-color--b2896b, #B2896B);
}

.jqj_efbdb {
  width: 1.813px;
  height: 12.032px;
  x: 11.453px;
  y: 14.549px;
  rx: 0.906px;
}

.kl4p_qbpv {
  stop-color: var(--svg-color--815a53, #815A53);
  stop-opacity: 0;
}

.l7ubcgbxh {
  stop-color: var(--svg-color--9f7464, #9F7464);
}

.m2qz3yb5c {
  stop-color: var(--svg-color--815a43, #815A43);
}

.mhvitvbof {
  stop-color: var(--svg-color--9f6677, #9F6677);
  stop-opacity: 0;
}

.mtryydbuf {
  stop-color: var(--svg-color--8a5075, #8A5075);
}

.n84_85bjx {
  stop-color: var(--svg-color--9d658f, #9D658F);
}

.nbbbsebgu {
  width: 1.813px;
  height: 9.405px;
  x: 5.608px;
  y: 15.207px;
  rx: 0.906px;
}

.njmeptb4c {
  stop-color: var(--svg-color--987363, #987363);
}

.nlj0vxbdo {
  d: path("M21.404 24.25c0-3.101-.071-8.176-.152-10.326l7.01-2.18c.752 3.972 1.035 10.013 1.136 12.506z");
}

.nxn-j0b0h {
  stop-color: var(--svg-color--a17e68, #A17E68);
  stop-opacity: 0;
}

.o2kuq2b1v {
  stop-color: var(--svg-color--a27b70, #A27B70);
  stop-opacity: 0;
}

.ol_3ii-gy {
  stop-color: var(--svg-color--794f47, #794F47);
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.palc9wbhh {
  fill: var(--svg-color--a88166, #A88166);
  d: path("M24.304 21.358c-.614.303-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.816 3.81 3.816h4.398c4.586 0 5.738-2.665 5.994-3.816s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

.pqpc7ps4v {
  fill: var(--svg-color--987363, #987363);
  d: path("M17.149 7.761c1.114 0 2.569.681 3.043 1.045l3.998.182V27.49l-7.268.174c-1.381 0-1.908-.833-2.226-1.612c-.227.484-1.181 1.491-2.846 1.491c-2.234 0-3.029-1.779-3.248-2.468c-.323.525-1.212 1.507-2.885 1.507c-2.627 0-3.401-2.388-3.361-3.498v-7.07c-.07-.647.085-2.163 1.272-3.06c1.484-1.12 2.15-.832 3.755-1.968C8.844 9.767 9.23 9.502 10.32 9.23c.977-.19 1.978.075 3.407-.265c1.224-.292 2.029-1.204 3.422-1.204");
}

.qmkv_unme {
  stop-color: var(--svg-color--8a5f57, #8A5F57);
}

.qp_n0941s {
  fill: var(--svg-color--a37f67, #A37F67);
  d: path("M10.973 10.017c-1.005.17-1.878.949-2.18 1.393l2.937 1.787l1.332-2.968c-.757-.363-1.332-.34-2.09-.212");
}

.r-d7trp-i {
  stop-color: var(--svg-color--8f695d, #8F695D);
}

.rub8babna {
  stop-color: var(--svg-color--90576a, #90576A);
  stop-opacity: 0;
}

.s8k379b7a {
  stop-color: var(--svg-color--975b76, #975B76);
}

.s9w5vg5ci {
  stop-color: var(--svg-color--966968, #966968);
  stop-opacity: 0;
}

.sd2-ki-1n {
  stop-color: var(--svg-color--c69f85, #C69F85);
}

.sqo2_1jyr {
  stop-color: var(--svg-color--7a436d, #7A436D);
}

.t_i6wtj8h {
  stop-color: var(--svg-color--7c4857, #7C4857);
  stop-opacity: 0;
}

.t4ihwcxzi {
  stop-color: var(--svg-color--90576a, #90576A);
}

.taut6bc4y {
  stop-color: var(--svg-color--ac8e75, #AC8E75);
}

.u0i_fd88n {
  stop-color: var(--svg-color--966968, #966968);
}

.u6-oeqbip {
  stop-color: var(--svg-color--7e594f, #7E594F);
  stop-opacity: 0;
}

.u6dcu5_uo {
  stop-color: var(--svg-color--c0977f, #C0977F);
}

.ubs7yur_y {
  d: path("M21.773 24.319H18.95a1.017 1.017 0 0 0 0 2.034h5.502c2.68 0 3.875-.778 3.803-2.496s-2.31-2.044-3.803-.249c-.662.796-2.221.667-2.68.71");
}

.ukbim5boq {
  d: path("m14.695 26.055l.001-.003l.02.049l.034.057v.022c.324.74.867 1.484 2.172 1.484l7.267-.174V16.437l-9.68-.336v8.755c0 .62.103 1.011.185 1.199");
}

.v_khwubzx {
  stop-color: var(--svg-color--825e4f, #825E4F);
}

.v3b5nab-t {
  stop-color: var(--svg-color--d0a88f, #D0A88F);
}

.v4t4xdb4c {
  d: path("M24.304 21.358c-.614.303-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.816 3.81 3.816h4.398c4.586 0 5.738-2.665 5.994-3.816s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

.vpltdfbhe {
  width: 10.852px;
  height: 12.128px;
  x: 19.394px;
  y: 3.688px;
  rx: 5.426px;
}

.vsz0fjbqu {
  stop-color: var(--svg-color--d0a590, #D0A590);
  stop-opacity: 0;
}

.vtjv65b5n {
  stop-color: var(--svg-color--9a6076, #9A6076);
  stop-opacity: 0;
}

.w5e0ouraa {
  stop-color: var(--svg-color--8d5862, #8D5862);
}

.wdsscobsv {
  stop-color: var(--svg-color--c8a991, #C8A991);
}

.wx6jig5kw {
  stop-color: var(--svg-color--8e6e60, #8E6E60);
}

.wzkue7yqo {
  stop-color: var(--svg-color--774d4c, #774D4C);
  stop-opacity: 0;
}

.x2cfwjwld {
  stop-color: var(--svg-color--ae8779, #AE8779);
}

.x8c5dsbku {
  stop-color: var(--svg-color--d0a590, #D0A590);
}

.xab3xyb5d {
  stop-color: var(--svg-color--a0766b, #A0766B);
  stop-opacity: 0;
}

.xkgdxux7m {
  stop-color: var(--svg-color--754f44, #754F44);
}

.xp8v2vfva {
  stop-color: var(--svg-color--8e6e60, #8E6E60);
  stop-opacity: 0;
}

.xvd6kc_kc {
  stop-color: var(--svg-color--ae8779, #AE8779);
  stop-opacity: 0;
}

.y7yqahbmr {
  stop-color: var(--svg-color--9c706a, #9C706A);
  stop-opacity: 0;
}

.yaqnefbms {
  stop-color: var(--svg-color--975b76, #975B76);
  stop-opacity: 0;
}

.yo_h1xbeu {
  d: path("M17.149 7.761c1.114 0 2.569.681 3.043 1.045l3.998.182V27.49l-7.268.174c-1.381 0-1.908-.833-2.226-1.612c-.227.484-1.181 1.491-2.846 1.491c-2.234 0-3.029-1.779-3.248-2.468c-.323.525-1.212 1.507-2.885 1.507c-2.627 0-3.401-2.388-3.361-3.498v-7.07c-.07-.647.085-2.163 1.272-3.06c1.484-1.12 2.15-.832 3.755-1.968C8.844 9.767 9.23 9.502 10.32 9.23c.977-.19 1.978.075 3.407-.265c1.224-.292 2.029-1.204 3.422-1.204");
}

.zereas7mi {
  d: path("m8.602 25.075l.006.02a5 5 0 0 1-.096-1.027v-8.282l-6.156.651v6.647c-.04 1.11.734 3.498 3.361 3.498c1.673 0 2.562-.982 2.885-1.507");
}

.zv-qf599o {
  stop-color: var(--svg-color--c69f85, #C69F85);
  stop-opacity: 0;
}

.zzqv8qbze {
  stop-color: var(--svg-color--9a6076, #9A6076);
}

</style>
