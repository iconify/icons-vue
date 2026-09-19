<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilRLEgc)"><path class="hx49uluvn"/><path fill="url(#ieO2Lgd)" class="gc82q5iuf"/></g><path fill="url(#ivhBODe)" class="nfco7pblp"/><path fill="url(#iLOCZRb)" class="nfco7pblp"/><path fill="url(#iWhp5Nc)" class="nfco7pblp"/><path fill="url(#ifjkpBf)" class="nfco7pblp"/><path fill="url(#i9Y9Drd)" class="zshrapsrr"/><path fill="url(#i8AA9FJ)" class="zshrapsrr"/><path fill="url(#i4SlN0j)" class="ck3p61y8v"/><path fill="url(#iMW7Rjb)" class="ck3p61y8v"/><path fill="url(#ihygu8x)" class="ck3p61y8v"/><path fill="url(#imMdzQc)" class="ck3p61y8v"/><path fill="url(#ib9GJNd)" class="dc43f9rim"/><path fill="url(#iNL9brS)" class="dc43f9rim"/><path fill="url(#iwk0E8i)" class="dc43f9rim"/><path fill="url(#ihaUMge)" class="dc43f9rim"/><g filter="url(#itwJ1Qc)"><path class="nruw_ub_d"/><path fill="url(#iKH2Jfd)" class="fgb14cbrf"/><path fill="url(#i6OxvBb)" class="fgb14cbrf"/></g><rect fill="url(#irSCB0d)" class="e9bkddchj"/><rect fill="url(#iUHJzjc)" class="e9bkddchj"/><rect fill="url(#i2659ye)" class="e9bkddchj"/><rect fill="url(#iZzyXvi)" class="e9bkddchj"/><rect fill="url(#iFtrC7d)" class="e9bkddchj"/><rect fill="url(#i0Y3P3c)" class="e9bkddchj"/><g filter="url(#iAVVuhd)"><path fill="url(#iFoUmec)" class="axuybz95v"/></g><g filter="url(#iLRtz2d)"><rect fill="url(#ii3xGKp)" class="agoc6rt1g"/></g><g filter="url(#im1bTNb)"><rect fill="url(#iWdx9le)" class="uhibtub3m"/></g><g filter="url(#i7JvZWd)"><path class="k6kdelbum"/></g><defs><radialGradient id="ieO2Lgd" cx="0" cy="0" r="1" gradientTransform="rotate(65.117 1.923 23.236)scale(9.59073 10.3722)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="n15wab67u"/><stop offset="1" class="u6y2iwbfb"/></radialGradient><radialGradient id="iWhp5Nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3466 -6.91977 0 11.63 16.861)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="ftg5a3n4a"/><stop offset="1" class="p62o-1rsv"/></radialGradient><radialGradient id="ifjkpBf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.74168 6.33423 0 11.63 23.473)" gradientUnits="userSpaceOnUse"><stop offset=".876" class="j2wv2absw"/><stop offset="1" class="p8z8f88ci"/></radialGradient><radialGradient id="i8AA9FJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.42709 -6.45029 0 5.263 17.745)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="jbq-kgvzy"/><stop offset="1" class="qzuczol3y"/></radialGradient><radialGradient id="iMW7Rjb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66527 0 0 -6.70115 21.267 22.785)" gradientUnits="userSpaceOnUse"><stop class="eghj5eb6n"/><stop offset="1" class="t_rtiabaa"/></radialGradient><radialGradient id="ib9GJNd" cx="0" cy="0" r="1" gradientTransform="rotate(-92.104 24.367 -2.115)scale(13.2673 7.2243)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="d983fmb_q"/><stop offset="1" class="jc44pgb1x"/></radialGradient><radialGradient id="iNL9brS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.81896 1.72444 0 21.252 22.232)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="uhw2-6kri"/><stop offset="1" class="n2bq2ex8w"/></radialGradient><radialGradient id="iwk0E8i" cx="0" cy="0" r="1" gradientTransform="matrix(3.2452 3.784 -11.4046 9.78069 20.912 14.436)" gradientUnits="userSpaceOnUse"><stop class="vg5ocdcio"/><stop offset="1" class="tcvdfbcic"/></radialGradient><radialGradient id="ihaUMge" cx="0" cy="0" r="1" gradientTransform="matrix(1.72612 -5.88788 7.21193 2.11429 26.36 24)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="dtegydbwv"/><stop offset=".479" class="fx5v_x05m"/></radialGradient><radialGradient id="iKH2Jfd" cx="0" cy="0" r="1" gradientTransform="matrix(6.04842 0 0 1.15509 23.113 21.503)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="lu3w2fb0v"/><stop offset="1" class="o4v2kt38g"/></radialGradient><radialGradient id="i6OxvBb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7592 0 0 -9.5527 26.697 25.576)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="dfshb41-y"/><stop offset="1" class="cxs4g6s_l"/></radialGradient><radialGradient id="irSCB0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61197 -8.63989 0 28.234 9.594)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="a5c9r5b5q"/><stop offset=".453" class="c825x_9dc"/></radialGradient><radialGradient id="iUHJzjc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83928 0 0 -9.61491 28.84 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qsoicckul"/><stop offset="1" class="x44zrszvk"/></radialGradient><radialGradient id="i2659ye" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.875 -10.8823 0 24.82 5.75)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="zyy5tu5qv"/><stop offset=".937" class="oqdkmabgz"/></radialGradient><radialGradient id="iZzyXvi" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42622 0 0 -8.60081 24.82 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="lyc9gdb1q"/><stop offset=".973" class="uyh3ytbmg"/></radialGradient><radialGradient id="iFtrC7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.96323 -2.65156 0 24.82 3.912)" gradientUnits="userSpaceOnUse"><stop class="cgf-2dbrs"/><stop offset="1" class="q9_4ce4pn"/></radialGradient><radialGradient id="i0Y3P3c" cx="0" cy="0" r="1" gradientTransform="rotate(-45 26.916 -19.024)scale(11.6673)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="eb-wd26de"/><stop offset="1" class="szge83bkx"/></radialGradient><linearGradient id="ivhBODe" x1="8.511" x2="12.011" y1="20.529" y2="20.529" gradientUnits="userSpaceOnUse"><stop class="k3tn-3b-v"/><stop offset="1" class="molnx2bgj"/></linearGradient><linearGradient id="iLOCZRb" x1="14.418" x2="13.27" y1="21.521" y2="21.521" gradientUnits="userSpaceOnUse"><stop class="ui31g8eyb"/><stop offset="1" class="alnv6zbis"/></linearGradient><linearGradient id="i9Y9Drd" x1="8.865" x2="6.582" y1="22.488" y2="22.488" gradientUnits="userSpaceOnUse"><stop class="wzzp_4bkm"/><stop offset="1" class="ktkr-7vou"/></linearGradient><linearGradient id="i4SlN0j" x1="14.307" x2="19.349" y1="23.081" y2="23.081" gradientUnits="userSpaceOnUse"><stop class="n1vsvyble"/><stop offset="1" class="vawispbvs"/></linearGradient><linearGradient id="ihygu8x" x1="14.27" x2="15.158" y1="16.047" y2="17.527" gradientUnits="userSpaceOnUse"><stop class="e462zg3jb"/><stop offset="1" class="e1c5osbwp"/></linearGradient><linearGradient id="imMdzQc" x1="15.394" x2="15.394" y1="27.653" y2="22.99" gradientUnits="userSpaceOnUse"><stop offset=".097" class="mwvg4w86l"/><stop offset="1" class="ntl4cbczk"/></linearGradient><linearGradient id="iFoUmec" x1="28.259" x2="19.093" y1="24.951" y2="24.951" gradientUnits="userSpaceOnUse"><stop class="mw5vlrbvk"/><stop offset="1" class="ut-a4zo6y"/></linearGradient><linearGradient id="ii3xGKp" x1="6.514" x2="6.514" y1="15.431" y2="24.835" gradientUnits="userSpaceOnUse"><stop offset=".395" class="bwoutoplr"/><stop offset="1" class="cdhuq155p"/></linearGradient><linearGradient id="iWdx9le" x1="12.359" x2="12.359" y1="14.773" y2="26.805" gradientUnits="userSpaceOnUse"><stop offset=".395" class="mz2xp-b3k"/><stop offset="1" class="l9p_tzbnu"/></linearGradient><filter id="ilRLEgc" width="22.598" height="20.153" x="2.342" y="7.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.243137 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7084"/></filter><filter id="itwJ1Qc" width="15.807" height="10.665" x="15.128" y="19.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.137255 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7084"/></filter><filter id="iAVVuhd" width="14.325" height="8.477" x="15.934" y="20.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7084" stdDeviation="1"/></filter><filter id="iLRtz2d" width="3.813" height="11.405" x="4.608" y="14.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7084" stdDeviation=".5"/></filter><filter id="im1bTNb" width="3.813" height="14.032" x="10.453" y="13.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7084" stdDeviation=".5"/></filter><filter id="i7JvZWd" width="7.27" height="6.265" x="7.292" y="8.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7084" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-at-the-viewer-dark" /></template>
<style>
.a5c9r5b5q {
  stop-color: var(--svg-color--64504e, #64504E);
}

.agoc6rt1g {
  width: 1.813px;
  height: 9.405px;
  x: 5.608px;
  y: 15.431px;
  rx: 0.906px;
}

.alnv6zbis {
  stop-color: var(--svg-color--4b3739, #4B3739);
  stop-opacity: 0;
}

.axuybz95v {
  d: path("M21.773 24.075H19.49a1.557 1.557 0 0 0 0 3.115h4.962c2.68 0 3.875-.778 3.803-2.496s-2.065-2.712-3.803-1.33c-.81.645-2.221.668-2.68.71");
}

.bwoutoplr {
  stop-color: var(--svg-color--534141, #534141);
}

.c825x_9dc {
  stop-color: var(--svg-color--452d2e, #452D2E);
}

.cdhuq155p {
  stop-color: var(--svg-color--472c34, #472C34);
}

.cgf-2dbrs {
  stop-color: var(--svg-color--594643, #594643);
}

.ck3p61y8v {
  d: path("m14.695 26.279l.001-.004l.02.05l.034.056v.023c.324.74.867 1.484 2.172 1.484l7.267-.174V16.66l-9.68-.337v8.755c0 .621.103 1.012.185 1.2");
}

.cxs4g6s_l {
  stop-color: var(--svg-color--35211e, #35211E);
}

.d983fmb_q {
  stop-color: var(--svg-color--5a4644, #5A4644);
}

.dc43f9rim {
  d: path("M21.404 24.474c0-3.101-.071-8.177-.152-10.327l7.01-2.18c.752 3.973 1.035 10.013 1.136 12.507z");
}

.dfshb41-y {
  stop-color: var(--svg-color--3e252e, #3E252E);
  stop-opacity: 0;
}

.dtegydbwv {
  stop-color: var(--svg-color--5f4b48, #5F4B48);
}

.e1c5osbwp {
  stop-color: var(--svg-color--3f2b2b, #3F2B2B);
  stop-opacity: 0;
}

.e462zg3jb {
  stop-color: var(--svg-color--3f2b2b, #3F2B2B);
}

.e9bkddchj {
  width: 10.852px;
  height: 12.128px;
  x: 19.394px;
  y: 3.912px;
  rx: 5.426px;
}

.eb-wd26de {
  stop-color: var(--svg-color--6d5b59, #6D5B59);
  stop-opacity: 0;
}

.eghj5eb6n {
  stop-color: var(--svg-color--4c3430, #4C3430);
}

.fgb14cbrf {
  d: path("M24.304 21.582c-.614.302-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.665 5.994-3.815c.256-1.151.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.137");
}

.ft5dv1b6b {
  fill: none;
}

.ftg5a3n4a {
  stop-color: var(--svg-color--3d212f, #3D212F);
  stop-opacity: 0;
}

.fx5v_x05m {
  stop-color: var(--svg-color--5f4b48, #5F4B48);
  stop-opacity: 0;
}

.gc82q5iuf {
  d: path("M17.149 7.985c1.114 0 2.569.681 3.043 1.044l3.998.182v18.503l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.506-2.885 1.506c-2.627 0-3.401-2.387-3.361-3.497v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.833 3.755-1.968C8.844 9.99 9.23 9.726 10.32 9.453c.977-.189 1.978.076 3.407-.265c1.224-.29 2.029-1.203 3.422-1.203");
}

.hx49uluvn {
  fill: var(--svg-color--432f2f, #432F2F);
  d: path("M17.149 7.985c1.114 0 2.569.681 3.043 1.044l3.998.182v18.503l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.506-2.885 1.506c-2.627 0-3.401-2.387-3.361-3.497v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.833 3.755-1.968C8.844 9.99 9.23 9.726 10.32 9.453c.977-.189 1.978.076 3.407-.265c1.224-.29 2.029-1.203 3.422-1.203");
}

.j2wv2absw {
  stop-color: var(--svg-color--442f2f, #442F2F);
  stop-opacity: 0;
}

.jbq-kgvzy {
  stop-color: var(--svg-color--3e2339, #3E2339);
  stop-opacity: 0;
}

.jc44pgb1x {
  stop-color: var(--svg-color--382427, #382427);
}

.k3tn-3b-v {
  stop-color: var(--svg-color--2c1819, #2C1819);
}

.k6kdelbum {
  fill: var(--svg-color--462f2d, #462F2D);
  d: path("M10.973 10.24c-1.005.172-1.878.95-2.18 1.394l2.937 1.786l1.332-2.967c-.757-.364-1.332-.34-2.09-.212");
}

.ktkr-7vou {
  stop-color: var(--svg-color--493135, #493135);
  stop-opacity: 0;
}

.l9p_tzbnu {
  stop-color: var(--svg-color--452a33, #452A33);
}

.lu3w2fb0v {
  stop-color: var(--svg-color--281614, #281614);
}

.lyc9gdb1q {
  stop-color: var(--svg-color--504240, #504240);
  stop-opacity: 0;
}

.molnx2bgj {
  stop-color: var(--svg-color--3f282b, #3F282B);
  stop-opacity: 0;
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mwvg4w86l {
  stop-color: var(--svg-color--29141c, #29141C);
}

.mz2xp-b3k {
  stop-color: var(--svg-color--4c393a, #4C393A);
}

.n15wab67u {
  stop-color: var(--svg-color--1f0e10, #1F0E10);
}

.n1vsvyble {
  stop-color: var(--svg-color--291617, #291617);
}

.n2bq2ex8w {
  stop-color: var(--svg-color--2e1715, #2E1715);
  stop-opacity: 0;
}

.nfco7pblp {
  d: path("M15.04 26.943a3.7 3.7 0 0 1-.344-.668c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468l-.064.098a52 52 0 0 1-.026-1.732V13.44l5.996 2.685v8.459c0 .556.4 1.296.624 1.708c.067.125.118.22.138.27c-.04.098-.119.23-.23.382");
}

.nruw_ub_d {
  fill: var(--svg-color--492f2b, #492F2B);
  d: path("M24.304 21.582c-.614.302-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.665 5.994-3.815c.256-1.151.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.137");
}

.ntl4cbczk {
  stop-color: var(--svg-color--29141c, #29141C);
  stop-opacity: 0;
}

.o4v2kt38g {
  stop-color: var(--svg-color--3d2622, #3D2622);
  stop-opacity: 0;
}

.oqdkmabgz {
  stop-color: var(--svg-color--311920, #311920);
}

.p62o-1rsv {
  stop-color: var(--svg-color--412a41, #412A41);
}

.p8z8f88ci {
  stop-color: var(--svg-color--442f2f, #442F2F);
}

.q9_4ce4pn {
  stop-color: var(--svg-color--594643, #594643);
  stop-opacity: 0;
}

.qsoicckul {
  stop-color: var(--svg-color--452e2c, #452E2C);
  stop-opacity: 0;
}

.qzuczol3y {
  stop-color: var(--svg-color--3e2339, #3E2339);
}

.szge83bkx {
  stop-color: var(--svg-color--6d5b59, #6D5B59);
}

.t_rtiabaa {
  stop-color: var(--svg-color--4c3839, #4C3839);
  stop-opacity: 0;
}

.tcvdfbcic {
  stop-color: var(--svg-color--321f24, #321F24);
  stop-opacity: 0;
}

.u6y2iwbfb {
  stop-color: var(--svg-color--362424, #362424);
  stop-opacity: 0;
}

.uhibtub3m {
  width: 1.813px;
  height: 12.032px;
  x: 11.453px;
  y: 14.773px;
  rx: 0.906px;
}

.uhw2-6kri {
  stop-color: var(--svg-color--2e1715, #2E1715);
}

.ui31g8eyb {
  stop-color: var(--svg-color--321d1d, #321D1D);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uyh3ytbmg {
  stop-color: var(--svg-color--504240, #504240);
}

.vawispbvs {
  stop-color: var(--svg-color--3b2628, #3B2628);
  stop-opacity: 0;
}

.vg5ocdcio {
  stop-color: var(--svg-color--321f24, #321F24);
}

.wzzp_4bkm {
  stop-color: var(--svg-color--2f191a, #2F191A);
}

.x44zrszvk {
  stop-color: var(--svg-color--361d29, #361D29);
}

.zshrapsrr {
  d: path("m8.602 25.299l.006.02a5 5 0 0 1-.096-1.027v-8.283l-6.156.652v6.647c-.04 1.11.734 3.497 3.361 3.497c1.673 0 2.562-.981 2.885-1.506");
}

.zyy5tu5qv {
  stop-color: var(--svg-color--311920, #311920);
  stop-opacity: 0;
}

</style>
