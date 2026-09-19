<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipwAuve)"><path fill="url(#iBr4fwd)" class="qhph3gzux"/><path fill="url(#iTFGFrc)" class="qhph3gzux"/><path fill="url(#iTdiTno)" class="qhph3gzux"/><path fill="url(#iL8MfLb)" class="qhph3gzux"/><path fill="url(#i7lSbnc)" class="qhph3gzux"/><path fill="url(#iEFVl6c)" class="qhph3gzux"/></g><path fill="url(#i2oCcfd)" class="tkm1fubhu"/><path fill="url(#ixMBZce)" class="tkm1fubhu"/><path fill="url(#iX5Rmsb)" class="tkm1fubhu"/><path fill="url(#iNrCs1K)" class="tkm1fubhu"/><path fill="url(#iWXndJe)" class="dhz4tdbwt"/><path fill="url(#iQvMreG)" class="dhz4tdbwt"/><path fill="url(#iL4AOzH)" class="dhz4tdbwt"/><path fill="url(#ifGGI6c)" class="dhz4tdbwt"/><g filter="url(#iwNXUCb)"><path class="h6c-qvbve"/><path fill="url(#iV1Fpfc)" class="gli8bib5n"/><path fill="url(#iGvUh8H)" class="gli8bib5n"/></g><defs><linearGradient id="iBr4fwd" x1="14.484" x2="20.172" y1="13.526" y2="26.057" gradientUnits="userSpaceOnUse"><stop class="blw_aabbu"/><stop offset="1" class="ul7rmpbso"/></linearGradient><linearGradient id="iL8MfLb" x1="15.992" x2="15.992" y1="13.666" y2="14.182" gradientUnits="userSpaceOnUse"><stop class="gpm4q0n7r"/><stop offset="1" class="uwge059yq"/></linearGradient><linearGradient id="i7lSbnc" x1="8.922" x2="11.859" y1="27.995" y2="25.245" gradientUnits="userSpaceOnUse"><stop offset=".106" class="j72dudmfr"/><stop offset="1" class="ado4ccc7z"/></linearGradient><linearGradient id="iEFVl6c" x1="1.588" x2="5.86" y1="16.631" y2="16.631" gradientUnits="userSpaceOnUse"><stop class="peehbobcz"/><stop offset="1" class="xs0hvh52n"/></linearGradient><linearGradient id="i2oCcfd" x1="11.391" x2="6.609" y1="13.932" y2="25.288" gradientUnits="userSpaceOnUse"><stop class="pd8fntbxe"/><stop offset="1" class="pati50ktx"/></linearGradient><linearGradient id="ixMBZce" x1="6.953" x2="7.906" y1="24.807" y2="23.401" gradientUnits="userSpaceOnUse"><stop class="ia2qr-96y"/><stop offset="1" class="xgd8zx2lq"/></linearGradient><linearGradient id="iX5Rmsb" x1="11.492" x2="11.234" y1="16.541" y2="16.44" gradientUnits="userSpaceOnUse"><stop offset=".175" class="gun9f4idd"/><stop offset="1" class="d3td4p6hy"/></linearGradient><linearGradient id="iNrCs1K" x1="7.677" x2="7.677" y1="13.869" y2="14.197" gradientUnits="userSpaceOnUse"><stop class="ydsd8oecq"/><stop offset="1" class="tpz270btp"/></linearGradient><linearGradient id="iWXndJe" x1="20.609" x2="25.14" y1="14.338" y2="24.12" gradientUnits="userSpaceOnUse"><stop class="d2ok4uepj"/><stop offset="1" class="quche6bwz"/></linearGradient><linearGradient id="iQvMreG" x1="24.108" x2="23.797" y1="19.511" y2="19.634" gradientUnits="userSpaceOnUse"><stop offset=".131" class="dx0bddbkv"/><stop offset="1" class="xbvjph1do"/></linearGradient><linearGradient id="iL4AOzH" x1="25.203" x2="24.976" y1="24.37" y2="24.135" gradientUnits="userSpaceOnUse"><stop class="byis2gpqo"/><stop offset="1" class="iwxbb2b5d"/></linearGradient><linearGradient id="ifGGI6c" x1="20.828" x2="20.828" y1="13.87" y2="14.198" gradientUnits="userSpaceOnUse"><stop class="ydsd8oecq"/><stop offset="1" class="tpz270btp"/></linearGradient><linearGradient id="iV1Fpfc" x1="2" x2="6.547" y1="13.932" y2="13.932" gradientUnits="userSpaceOnUse"><stop class="mkz_pkbct"/><stop offset="1" class="o2hmc9xij"/></linearGradient><linearGradient id="iGvUh8H" x1="30" x2="24.297" y1="13.932" y2="13.932" gradientUnits="userSpaceOnUse"><stop offset=".463" class="lp4ptrixp"/><stop offset="1" class="mrv_lebms"/></linearGradient><radialGradient id="iTFGFrc" cx="0" cy="0" r="1" gradientTransform="rotate(-123.843 18.03 9.587)scale(6.50908 10.6984)" gradientUnits="userSpaceOnUse"><stop class="wx1t6vbnl"/><stop offset="1" class="yryk28ewt"/></radialGradient><radialGradient id="iTdiTno" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.9375 -5.53769 0 28.922 14.12)" gradientUnits="userSpaceOnUse"><stop class="j3p6p__1x"/><stop offset="1" class="k4k3tab5w"/></radialGradient><filter id="ipwAuve" width="27.816" height="16.525" x="2.059" y="13.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.462745 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16832"/></filter><filter id="iwNXUCb" width="28.1" height="3.05" x="2" y="10.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.701961 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16832"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:briefs" /></template>
<style>
.ado4ccc7z {
  stop-color: var(--svg-color--4193ff, #4193FF);
  stop-opacity: 0;
}

.blw_aabbu {
  stop-color: var(--svg-color--368ced, #368CED);
}

.byis2gpqo {
  stop-color: var(--svg-color--62e0ff, #62E0FF);
}

.d2ok4uepj {
  stop-color: var(--svg-color--55edff, #55EDFF);
}

.d3td4p6hy {
  stop-color: var(--svg-color--6bf7ff, #6BF7FF);
  stop-opacity: 0;
}

.dhz4tdbwt {
  d: path("M21.485 13.526h-2.227l5.04 11.772l1.567-1.542z");
}

.dx0bddbkv {
  stop-color: var(--svg-color--64fbff, #64FBFF);
}

.ft5dv1b6b {
  fill: none;
}

.gli8bib5n {
  d: path("M2 12.182c0-.69.56-1.25 1.25-1.25h25.5c.69 0 1.25.56 1.25 1.25v1.55a.2.2 0 0 1-.2.2H2.2a.2.2 0 0 1-.2-.2z");
}

.gpm4q0n7r {
  stop-color: var(--svg-color--2271dd, #2271DD);
}

.gun9f4idd {
  stop-color: var(--svg-color--6bf7ff, #6BF7FF);
}

.h6c-qvbve {
  fill: var(--svg-color--5decff, #5DECFF);
  d: path("M2 12.182c0-.69.56-1.25 1.25-1.25h25.5c.69 0 1.25.56 1.25 1.25v1.55a.2.2 0 0 1-.2.2H2.2a.2.2 0 0 1-.2-.2z");
}

.ia2qr-96y {
  stop-color: var(--svg-color--5597ff, #5597FF);
}

.iwxbb2b5d {
  stop-color: var(--svg-color--62e0ff, #62E0FF);
  stop-opacity: 0;
}

.j3p6p__1x {
  stop-color: var(--svg-color--6ab0ff, #6AB0FF);
}

.j72dudmfr {
  stop-color: var(--svg-color--4193ff, #4193FF);
}

.k4k3tab5w {
  stop-color: var(--svg-color--6ab0ff, #6AB0FF);
  stop-opacity: 0;
}

.lp4ptrixp {
  stop-color: var(--svg-color--7fffff, #7FFFFF);
}

.mkz_pkbct {
  stop-color: var(--svg-color--4acbff, #4ACBFF);
}

.mrv_lebms {
  stop-color: var(--svg-color--7fffff, #7FFFFF);
  stop-opacity: 0;
}

.o2hmc9xij {
  stop-color: var(--svg-color--4acbff, #4ACBFF);
  stop-opacity: 0;
}

.pati50ktx {
  stop-color: var(--svg-color--56d0ff, #56D0FF);
}

.pd8fntbxe {
  stop-color: var(--svg-color--56f1ff, #56F1FF);
}

.peehbobcz {
  stop-color: var(--svg-color--436fa9, #436FA9);
}

.qhph3gzux {
  d: path("M2.11 13.526h27.765v3.769a6 6 0 0 1-1.79 4.275l-6.416 6.318a7 7 0 0 1-4.912 2.013h-1.53a7 7 0 0 1-4.911-2.013L3.899 21.57a6 6 0 0 1-1.79-4.275z");
}

.quche6bwz {
  stop-color: var(--svg-color--5efaff, #5EFAFF);
}

.tkm1fubhu {
  d: path("m6.108 23.745l4.376-10.22h2.226L7.675 25.289z");
}

.tpz270btp {
  stop-color: var(--svg-color--48ceff, #48CEFF);
  stop-opacity: 0;
}

.ul7rmpbso {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
}

.uwge059yq {
  stop-color: var(--svg-color--2271dd, #2271DD);
  stop-opacity: 0;
}

.wx1t6vbnl {
  stop-color: var(--svg-color--46c7ff, #46C7FF);
}

.xbvjph1do {
  stop-color: var(--svg-color--64fbff, #64FBFF);
  stop-opacity: 0;
}

.xgd8zx2lq {
  stop-color: var(--svg-color--55c5ff, #55C5FF);
  stop-opacity: 0;
}

.xs0hvh52n {
  stop-color: var(--svg-color--2a80e2, #2A80E2);
  stop-opacity: 0;
}

.ydsd8oecq {
  stop-color: var(--svg-color--48ceff, #48CEFF);
}

.yryk28ewt {
  stop-color: var(--svg-color--46c7ff, #46C7FF);
  stop-opacity: 0;
}

</style>
