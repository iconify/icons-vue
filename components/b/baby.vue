<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9V2mod)" class="i_ac_snfq"/><path fill="url(#iKfIC6c)" class="i_ac_snfq"/><g filter="url(#iBNFydb)"><path class="dlncwobgz"/><path fill="url(#iCoiZGc)" class="vzd5t3blr"/></g><path fill="url(#i9zis8q)" class="u1wpdrf9o"/><path fill="url(#iI6zGMo)" class="u1wpdrf9o"/><path fill="url(#iRJhcLe)" class="u1wpdrf9o"/><g filter="url(#idlDlCc)"><path fill="url(#iY9CnDd)" class="wg1prbbsu"/></g><g filter="url(#ixhdzmc)"><path fill="url(#i3ta1ad)" class="d01w28sjj"/><path fill="url(#ixSpeld)" class="d01w28sjj"/><path fill="url(#is4sZFb)" class="d01w28sjj"/><path fill="url(#i3uMLeb)" class="d01w28sjj"/><path fill="url(#inFgaae)" class="d01w28sjj"/><path fill="url(#itHRvLb)" class="d01w28sjj"/></g><g filter="url(#iG8K9ad)"><path class="nnq5-so3e"/></g><path class="tlyk_bytb"/><path fill="url(#isNKtnb)" class="l_32wrbib"/><path fill="url(#imDMIRc)" class="e4852ofpt"/><path class="uzxx-x34i"/><g filter="url(#iDkINub)"><path class="r3uu31hto"/></g><g filter="url(#iO4RQ2b)"><path class="if3b2wbcc"/></g><g filter="url(#iBVBSyd)"><path class="x2cvxq-nn"/></g><g filter="url(#iWruTSd)"><path class="e_2lttb0z"/></g><g filter="url(#i5wAVbe)"><path fill="url(#iwqkCHO)" class="umhucgbrx"/></g><g filter="url(#i6nsese)"><path class="umqhyqbze"/><path fill="url(#iLh959d)" class="mirc02bfc"/><path fill="url(#ifSXwwb)" class="mirc02bfc"/></g><g filter="url(#iRGV67c)"><path class="uk7502q4y"/></g><g filter="url(#iF5dpKe)"><path fill="url(#iEcWCDV)" class="m_jkoeahh"/></g><g filter="url(#iDKY4xb)"><path class="ly6em7axj"/><path fill="url(#i5k2aEc)" class="uez6p-bsa"/></g><g filter="url(#iRc6sse)"><path fill="url(#iau09za)" class="zuvdohqho"/></g><g filter="url(#iUBBXId)"><path fill="url(#i3zQF8g)" class="skwxd-t4t"/></g><g filter="url(#iKebePQ)"><ellipse transform="rotate(-27.914 10.576 18.71)" class="zlpoe-b8u"/><ellipse fill="url(#ilKx8Id)" transform="rotate(-27.914 10.576 18.71)" class="cklxztchd"/></g><defs><radialGradient id="iKfIC6c" cx="0" cy="0" r="1" gradientTransform="rotate(-157.686 5.258 9.486)scale(4.03303 5.24783)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="w_r7-9bim"/><stop offset="1" class="oybb58bnw"/></radialGradient><radialGradient id="iCoiZGc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.635 13.155)scale(2.01965)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="zv7ttxbjc"/><stop offset="1" class="gpp3aqbxg"/></radialGradient><radialGradient id="iI6zGMo" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 3.785 22.022)scale(4.7194 4.52281)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="fm6dqtc6i"/><stop offset="1" class="d1mprq6ip"/></radialGradient><radialGradient id="iRJhcLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 -1.96875 1.94275 1.68063 25.867 19.383)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="iw334hahu"/><stop offset=".883" class="v294fhb1o"/></radialGradient><radialGradient id="i3ta1ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.405 -12.704 0 21.813 13.28)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="r1lbydbys"/><stop offset="1" class="iyv92ybgd"/></radialGradient><radialGradient id="ixSpeld" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 -4.17187 9.21025 7.03706 9.289 29.96)" gradientUnits="userSpaceOnUse"><stop class="fmlmf6b4u"/><stop offset="1" class="hhy8o7t0r"/></radialGradient><radialGradient id="is4sZFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.34375 15.4144 0 16.04 30.617)" gradientUnits="userSpaceOnUse"><stop class="ci9lecc-p"/><stop offset="1" class="pqn6fmb_j"/></radialGradient><radialGradient id="inFgaae" cx="0" cy="0" r="1" gradientTransform="matrix(1.43751 -3.04686 3.42024 1.61368 21.137 18.68)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="ht-7f4bgu"/><stop offset="1" class="e7g5x3bay"/></radialGradient><radialGradient id="itHRvLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.90625 3.19847 1.44446 11.278 18.96)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="chhjzdbtk"/><stop offset="1" class="rbo5nsffk"/></radialGradient><radialGradient id="isNKtnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -2.26165 0 20.215 19.523)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="r01x0bbde"/><stop offset="1" class="sk--2-b-a"/></radialGradient><radialGradient id="imDMIRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -2.26165 0 11.245 19.523)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="r01x0bbde"/><stop offset="1" class="sk--2-b-a"/></radialGradient><radialGradient id="iLh959d" cx="0" cy="0" r="1" gradientTransform="matrix(7.82167 -2.08468 1.7391 6.52504 12.04 7.004)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="yfecvtcdb"/><stop offset=".999" class="ncmwj9bfa"/></radialGradient><radialGradient id="ifSXwwb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63771 -5.65242 5.82757 -3.75043 16.77 8.263)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="vb0mv6bar"/><stop offset=".987" class="apprgee8k"/></radialGradient><radialGradient id="iEcWCDV" cx="0" cy="0" r="1" gradientTransform="rotate(117.715 1.906 15.728)scale(2.02107 3.05534)" gradientUnits="userSpaceOnUse"><stop offset=".084" class="p-1qhibxi"/><stop offset="1" class="q4myb4blf"/></radialGradient><radialGradient id="i5k2aEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5717 -.73672 1.01428 -.7871 19.652 19.153)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilKx8Id" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.861 4.555)scale(1.21806 1.46416)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iBNFydb" width="4.539" height="4.539" x="4.25" y="17.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".125"/></filter><filter id="idlDlCc" width="4.663" height="4.663" x="23.189" y="17.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".125"/></filter><filter id="ixhdzmc" width="23.25" height="26" x="5.04" y="3.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24657"/></filter><filter id="iG8K9ad" width="7" height="2.4" x="12.52" y="23.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24657"/></filter><filter id="iDkINub" width="3.72" height="1.592" x="9" y="14.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.235294 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24657"/></filter><filter id="iO4RQ2b" width="3.17" height=".992" x="9.205" y="14.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".1"/></filter><filter id="iBVBSyd" width="3.72" height="1.592" x="18.85" y="14.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.235294 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24657"/></filter><filter id="iWruTSd" width="3.17" height=".992" x="19.25" y="14.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".1"/></filter><filter id="i5wAVbe" width="7.887" height="8.705" x="12.161" y="2.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".25"/></filter><filter id="i6nsese" width="8.2" height="8.529" x="12.04" y="1.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.458824 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24657"/></filter><filter id="iRGV67c" width="3.638" height="2.603" x="14.068" y="20.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".25"/></filter><filter id="iF5dpKe" width="3.138" height="2.103" x="14.451" y="20.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".125"/></filter><filter id="iDKY4xb" width="1.647" height="1.423" x="18.552" y="18.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".05"/></filter><filter id="iRc6sse" width="1.611" height="1.666" x="20.769" y="18.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".1"/></filter><filter id="iUBBXId" width="1.845" height="1.978" x="11.605" y="18.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".1"/></filter><filter id="iKebePQ" width="1.958" height="1.444" x="9.597" y="17.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24657" stdDeviation=".05"/></filter><linearGradient id="i9V2mod" x1="3.695" x2="6.52" y1="19.789" y2="19.539" gradientUnits="userSpaceOnUse"><stop class="d8xp-vbup"/><stop offset="1" class="p-wzk38ah"/></linearGradient><linearGradient id="i9zis8q" x1="28.07" x2="25.82" y1="17.258" y2="22.289" gradientUnits="userSpaceOnUse"><stop class="da366tb6r"/><stop offset="1" class="lw70zrunl"/></linearGradient><linearGradient id="iY9CnDd" x1="26.742" x2="27.07" y1="20.945" y2="17.867" gradientUnits="userSpaceOnUse"><stop offset=".302" class="kyej7mc7h"/><stop offset="1" class="g-qng6b1e"/></linearGradient><linearGradient id="i3uMLeb" x1="5.684" x2="12.059" y1="20.648" y2="20.648" gradientUnits="userSpaceOnUse"><stop class="xz-50o4by"/><stop offset="1" class="mu403ebre"/></linearGradient><linearGradient id="iwqkCHO" x1="18.708" x2="15.402" y1="4.563" y2="10.31" gradientUnits="userSpaceOnUse"><stop class="ry3r2tbgs"/><stop offset="1" class="kyz4h9b7r"/></linearGradient><linearGradient id="iau09za" x1="22.133" x2="21.359" y1="19.078" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3zQF8g" x1="13.079" x2="12.305" y1="19.078" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby" /></template>
<style>
.apprgee8k {
  stop-color: var(--svg-color--c9983d, #C9983D);
}

.chhjzdbtk {
  stop-color: var(--svg-color--f0953d, #F0953D);
}

.ci9lecc-p {
  stop-color: var(--svg-color--d87a77, #D87A77);
}

.cklxztchd {
  cx: 10.576px;
  cy: 18.709px;
  rx: 0.96px;
  ry: 0.486px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d01w28sjj {
  d: path("M23.25 5.751a8.87 8.87 0 0 0-5.307-1.79h-3.806c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.071 5.3-3.745 8.69l.898 8.112c.296 3.14 2.378 5.78 5.265 6.68c3.123.97 6.46.97 9.582 0c2.887-.9 4.97-3.54 5.265-6.68l.898-8.111c.327-3.39-1.102-6.7-3.745-8.69");
}

.d1mprq6ip {
  stop-color: var(--svg-color--d58651, #D58651);
}

.d8xp-vbup {
  stop-color: var(--svg-color--de8d27, #DE8D27);
}

.da366tb6r {
  stop-color: var(--svg-color--ffe13f, #FFE13F);
}

.dlncwobgz {
  fill: var(--svg-color--d78125, #D78125);
  d: path("M6.52 21.809a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.e_2lttb0z {
  stroke: var(--svg-color--c45b41, #C45B41);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22.07 14.974c-.59-.21-1.41-.36-2.47-.26");
}

.e4852ofpt {
  d: path("M11.24 17.77a2.2 2.2 0 0 0-2.12 2.78h4.25c.05-.19.08-.38.08-.58c-.01-1.21-.99-2.2-2.21-2.2");
}

.e7g5x3bay {
  stop-color: var(--svg-color--ffba36, #FFBA36);
  stop-opacity: 0;
}

.fm6dqtc6i {
  stop-color: var(--svg-color--d58651, #D58651);
  stop-opacity: 0;
}

.fmlmf6b4u {
  stop-color: var(--svg-color--d17c51, #D17C51);
}

.ft5dv1b6b {
  fill: none;
}

.g-qng6b1e {
  stop-color: var(--svg-color--ffd165, #FFD165);
}

.gpp3aqbxg {
  stop-color: var(--svg-color--ce791d, #CE791D);
}

.hhy8o7t0r {
  stop-color: var(--svg-color--d17c51, #D17C51);
  stop-opacity: 0;
}

.ht-7f4bgu {
  stop-color: var(--svg-color--ffba36, #FFBA36);
}

.i_ac_snfq {
  d: path("M6.52 23.04a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.if3b2wbcc {
  stroke: var(--svg-color--c45b41, #C45B41);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.555 15.026c.59-.21 1.41-.36 2.47-.26");
}

.iw334hahu {
  stop-color: var(--svg-color--ffb61f, #FFB61F);
}

.iyv92ybgd {
  stop-color: var(--svg-color--fdab24, #FDAB24);
}

.kyej7mc7h {
  stop-color: var(--svg-color--ffc332, #FFC332);
}

.kyz4h9b7r {
  stop-color: var(--svg-color--ff9c1d, #FF9C1D);
}

.l_32wrbib {
  d: path("M20.22 17.77a2.2 2.2 0 0 1 2.12 2.78h-4.25c-.05-.19-.08-.38-.08-.58c0-1.21.99-2.2 2.21-2.2");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw70zrunl {
  stop-color: var(--svg-color--ffbd36, #FFBD36);
}

.ly6em7axj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.058 18.234c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.96-.125");
}

.m_jkoeahh {
  d: path("M16.022 22.69c.51 0 .965-.282 1.225-.703c.238-.386-.011-.901-.445-.901h-1.56c-.433 0-.693.527-.444.901c.26.433.715.702 1.224.702");
}

.mirc02bfc {
  d: path("M15.84 2.07a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.mu403ebre {
  stop-color: var(--svg-color--eb992c, #EB992C);
  stop-opacity: 0;
}

.ncmwj9bfa {
  stop-color: var(--svg-color--ffd937, #FFD937);
}

.nnq5-so3e {
  fill: var(--svg-color--8a034f, #8A034F);
  d: path("M16.012 24.002a6.4 6.4 0 0 1-3.007-.732c-.299-.161-.617.18-.428.471a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.18-.28-.13-.622-.428-.471a6.55 6.55 0 0 1-3.027.732");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oybb58bnw {
  stop-color: var(--svg-color--ce9f45, #CE9F45);
}

.p-1qhibxi {
  stop-color: var(--svg-color--ffe245, #FFE245);
}

.p-wzk38ah {
  stop-color: var(--svg-color--cb773f, #CB773F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqn6fmb_j {
  stop-color: var(--svg-color--d87a77, #D87A77);
  stop-opacity: 0;
}

.q4myb4blf {
  stop-color: var(--svg-color--f29624, #F29624);
}

.r01x0bbde {
  stop-color: var(--svg-color--8f564f, #8F564F);
}

.r1lbydbys {
  stop-color: var(--svg-color--ffe944, #FFE944);
}

.r3uu31hto {
  stroke: var(--svg-color--c15231, #C15231);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.5 15.12c.59-.21 1.41-.36 2.47-.26");
}

.rbo5nsffk {
  stop-color: var(--svg-color--f0953d, #F0953D);
  stop-opacity: 0;
}

.ry3r2tbgs {
  stop-color: var(--svg-color--e07f05, #E07F05);
}

.sk--2-b-a {
  stop-color: var(--svg-color--86534b, #86534B);
}

.skwxd-t4t {
  d: path("M13.25 19.71c0-.71-.578-1.184-.735-1.327l-.71.687l.437.89z");
}

.tlyk_bytb {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.73 17.1c1.61 0 2.97 1.11 3.34 2.61c.11.43-.22.84-.66.84h-5.5c-.35 0-.63-.32-.56-.67c.31-1.58 1.7-2.78 3.38-2.78m-10 0c-1.61 0-2.97 1.11-3.34 2.61c-.11.43.22.84.66.84h5.5c.35 0 .63-.32.56-.67a3.454 3.454 0 0 0-3.38-2.78");
}

.u1wpdrf9o {
  d: path("M25.52 23.04a3.25 3.25 0 1 0 0-6.501a3.25 3.25 0 0 0 0 6.5");
}

.uez6p-bsa {
  d: path("M20.058 18.234c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.96-.125");
}

.uk7502q4y {
  fill: var(--svg-color--f1902d, #F1902D);
  d: path("M15.89 23.039c.509 0 .964-.28 1.224-.702c.238-.386-.01-.901-.444-.901h-1.56c-.434 0-.694.526-.445.9c.26.434.715.703 1.225.703");
}

.umhucgbrx {
  d: path("M16.261 2.792c-1.473-.223-2.767.11-3.6 1.223a7.8 7.8 0 0 1 1.719.037l.134.018c1.629.226 2.717 2.047 2.482 3.674a2.97 2.97 0 0 1-.994 1.816a.493.493 0 0 0 .403.863a3.87 3.87 0 0 0 3.104-3.275c.298-2.086-1.164-4.04-3.248-4.356");
}

.umqhyqbze {
  fill: var(--svg-color--e99628, #E99628);
  d: path("M15.84 2.07a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.uzxx-x34i {
  fill: var(--svg-color--000, #000);
  d: path("M18.96 19.97c0-.7.56-1.26 1.26-1.26s1.26.56 1.26 1.26c0 .21-.05.41-.14.58h-2.23c-.1-.17-.15-.37-.15-.58m-6.46 0c0-.7-.56-1.26-1.26-1.26s-1.26.56-1.26 1.26c0 .21.05.41.14.58h2.23c.09-.17.15-.37.15-.58");
}

.v294fhb1o {
  stop-color: var(--svg-color--ffb61f, #FFB61F);
  stop-opacity: 0;
}

.vb0mv6bar {
  stop-color: var(--svg-color--c9983d, #C9983D);
  stop-opacity: 0;
}

.vzd5t3blr {
  d: path("M6.52 21.809a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.w_r7-9bim {
  stop-color: var(--svg-color--ce9f45, #CE9F45);
  stop-opacity: 0;
}

.wg1prbbsu {
  d: path("M25.52 21.87a2.081 2.081 0 1 0 0-4.162a2.081 2.081 0 0 0 0 4.163");
}

.x2cvxq-nn {
  stroke: var(--svg-color--c15231, #C15231);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.07 15.12c-.59-.21-1.41-.36-2.47-.26");
}

.xz-50o4by {
  stop-color: var(--svg-color--eb992c, #EB992C);
}

.yfecvtcdb {
  stop-color: var(--svg-color--ffd937, #FFD937);
  stop-opacity: 0;
}

.zlpoe-b8u {
  cx: 10.576px;
  cy: 18.709px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.96px;
  ry: 0.486px;
}

.zuvdohqho {
  d: path("M22.18 19.68a2.07 2.07 0 0 0-.57-1.14l-.641.702l.289.563z");
}

.zv7ttxbjc {
  stop-color: var(--svg-color--ce791d, #CE791D);
  stop-opacity: 0;
}

</style>
