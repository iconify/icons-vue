<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i74syXy)" class="a4sih66vg"/><path fill="url(#ixHmj6d)" class="a4sih66vg"/><g filter="url(#iY3CPLi)"><path fill="url(#iIMw59X)" class="riphacblx"/><path fill="url(#iDo63Ad)" class="riphacblx"/></g><g filter="url(#ivRfded)"><path fill="url(#irL4FPP)" class="odt_prqmi"/><path fill="url(#iAMNLyb)" class="odt_prqmi"/></g><path fill="url(#iVUtm5d)" class="vf0eaacpx"/><path fill="url(#iSlvLJd)" class="vf0eaacpx"/><path fill="url(#iqYdZPc)" class="gmtvf1c3h"/><path fill="url(#iUXcY2k)" class="gmtvf1c3h"/><path fill="url(#iSO0tGB)" class="gmtvf1c3h"/><path fill="url(#ikZdNvb)" class="v4fmhkbqw"/><g filter="url(#idG6bya)"><path fill="url(#ipPt8oW)" class="cqm-smmrj"/><path fill="url(#iemjGcd)" class="cqm-smmrj"/></g><g filter="url(#iM0spMd)"><path fill="url(#ilcHRuc)" class="ry-pr9nfx"/><path fill="url(#i3Aepyb)" class="ry-pr9nfx"/></g><path fill="url(#i0mWZMc)" class="wj_peg59y"/><path fill="url(#iqSMtXc)" class="dc1guvtre"/><defs><radialGradient id="ixHmj6d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09057 4.52378 -11.29538 -5.21992 25.818 3.668)" gradientUnits="userSpaceOnUse"><stop class="rc41avbep"/><stop offset="1" class="yq81apbmx"/></radialGradient><radialGradient id="iIMw59X" cx="0" cy="0" r="1" gradientTransform="rotate(-45 28.126 -13.07)scale(11.1316 8.49872)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="oibo2ubta"/><stop offset="1" class="w7dcplrue"/></radialGradient><radialGradient id="iDo63Ad" cx="0" cy="0" r="1" gradientTransform="rotate(-138.606 14.834 1.739)scale(11.5986 13.3739)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="nh1odcbyl"/><stop offset="1" class="hxn78_q6o"/></radialGradient><radialGradient id="irL4FPP" cx="0" cy="0" r="1" gradientTransform="rotate(-45 27.916 -13.383)scale(10.64959 8.13066)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="oibo2ubta"/><stop offset="1" class="w7dcplrue"/></radialGradient><radialGradient id="iAMNLyb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.32423 -7.33724 8.46035 -9.5984 24.655 12.753)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="nh1odcbyl"/><stop offset="1" class="hxn78_q6o"/></radialGradient><radialGradient id="iSlvLJd" cx="0" cy="0" r="1" gradientTransform="rotate(114.803 .736 8.462)scale(2.70071 6.74341)" gradientUnits="userSpaceOnUse"><stop class="rc41avbep"/><stop offset="1" class="yq81apbmx"/></radialGradient><radialGradient id="iUXcY2k" cx="0" cy="0" r="1" gradientTransform="rotate(114.803 2.544 15.432)scale(3.48077 8.69114)" gradientUnits="userSpaceOnUse"><stop class="rc41avbep"/><stop offset="1" class="yq81apbmx"/></radialGradient><radialGradient id="iSO0tGB" cx="0" cy="0" r="1" gradientTransform="matrix(-.85676 2.9816 -6.12948 -1.7613 16.017 17.65)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="vc_yrqbcn"/><stop offset="1" class="rqm0zfshd"/></radialGradient><radialGradient id="ikZdNvb" cx="0" cy="0" r="1" gradientTransform="matrix(3.902 -5.1578 7.63526 5.77624 20.507 9.489)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="ogltedctx"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="ipPt8oW" cx="0" cy="0" r="1" gradientTransform="rotate(-45 39.691 -.576)scale(7.06008 5.39018)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="oibo2ubta"/><stop offset="1" class="w7dcplrue"/></radialGradient><radialGradient id="iemjGcd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5185 -4.8642 5.60873 -6.3632 16.684 25.863)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="nh1odcbyl"/><stop offset="1" class="hxn78_q6o"/></radialGradient><radialGradient id="ilcHRuc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 23.616 3.522)scale(5.37065 4.10035)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="oibo2ubta"/><stop offset="1" class="w7dcplrue"/></radialGradient><radialGradient id="i3Aepyb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.19796 -3.70022 4.2666 -4.84053 7.964 16.183)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="nh1odcbyl"/><stop offset="1" class="hxn78_q6o"/></radialGradient><radialGradient id="i0mWZMc" cx="0" cy="0" r="1" gradientTransform="matrix(2.1146 -2.7952 4.13782 3.13032 5.848 14.497)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="ogltedctx"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iqSMtXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.7254 -3.60254 5.33295 4.0345 13.91 23.662)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="ogltedctx"/><stop offset="1" class="vc--wpv5i"/></radialGradient><filter id="iY3CPLi" width="18.587" height="18.587" x="11.881" y="1.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4793_1042" stdDeviation="1"/></filter><filter id="ivRfded" width="17.955" height="17.955" x="12.197" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4793_1042" stdDeviation="1"/></filter><filter id="idG6bya" width="12.751" height="12.751" x="8" y="18.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4793_1042" stdDeviation=".875"/></filter><filter id="iM0spMd" width="9.537" height="9.538" x="1.44" y="10.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4793_1042" stdDeviation=".625"/></filter><linearGradient id="i74syXy" x1="14.988" x2="28.8" y1="3.977" y2="14.601" gradientUnits="userSpaceOnUse"><stop class="wtjrjlb-k"/><stop offset=".061" class="utda0f46l"/><stop offset=".115" class="n9hwpubid"/><stop offset=".218" class="mo-vi33tm"/><stop offset=".533" class="mo-vi33tm"/><stop offset=".694" class="b0_52dbkx"/><stop offset="1" class="qsm6hubve"/></linearGradient><linearGradient id="iVUtm5d" x1="2.857" x2="10.342" y1="11.511" y2="17.268" gradientUnits="userSpaceOnUse"><stop class="wtjrjlb-k"/><stop offset=".061" class="utda0f46l"/><stop offset=".115" class="n9hwpubid"/><stop offset=".218" class="mo-vi33tm"/><stop offset=".533" class="mo-vi33tm"/><stop offset=".694" class="b0_52dbkx"/><stop offset="1" class="qsm6hubve"/></linearGradient><linearGradient id="iqYdZPc" x1="10.056" x2="19.702" y1="19.812" y2="27.232" gradientUnits="userSpaceOnUse"><stop class="wtjrjlb-k"/><stop offset=".061" class="utda0f46l"/><stop offset=".115" class="n9hwpubid"/><stop offset=".218" class="mo-vi33tm"/><stop offset=".533" class="mo-vi33tm"/><stop offset=".694" class="b0_52dbkx"/><stop offset="1" class="qsm6hubve"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bubbles" /></template>
<style>
.a4sih66vg {
  d: path("M21.174 18.895a8.348 8.348 0 1 0 0-16.695a8.348 8.348 0 0 0 0 16.695");
}

.b0_52dbkx {
  stop-color: var(--svg-color--ff99a9, #FF99A9);
}

.cqm-smmrj {
  d: path("M14.376 29.027a4.626 4.626 0 1 0 0-9.251a4.626 4.626 0 0 0 0 9.251");
}

.dc1guvtre {
  d: path("M15.734 25.104a2.788 2.788 0 1 0 0-5.576a2.788 2.788 0 0 0 0 5.576");
}

.ft5dv1b6b {
  fill: none;
}

.gmtvf1c3h {
  d: path("M14.376 30.232a5.83 5.83 0 1 0 0-11.661a5.83 5.83 0 0 0 0 11.66");
}

.hxn78_q6o {
  stop-color: var(--svg-color--9fd2f5, #9FD2F5);
}

.mo-vi33tm {
  stop-color: var(--svg-color--ca5bc0, #CA5BC0);
}

.n9hwpubid {
  stop-color: var(--svg-color--afa8e1, #AFA8E1);
}

.nh1odcbyl {
  stop-color: var(--svg-color--9fd2f5, #9FD2F5);
  stop-opacity: 0;
}

.odt_prqmi {
  d: path("M21.174 17.525a6.977 6.977 0 1 0 0-13.955a6.977 6.977 0 0 0 0 13.955");
}

.ogltedctx {
  stop-color: var(--svg-color--ivory, ivory);
  stop-opacity: 0;
}

.oibo2ubta {
  stop-color: var(--svg-color--d893ff, #D893FF);
}

.qsm6hubve {
  stop-color: var(--svg-color--fadf9e, #FADF9E);
}

.rc41avbep {
  stop-color: var(--svg-color--ff9cea, #FF9CEA);
}

.riphacblx {
  d: path("M21.174 17.84a7.293 7.293 0 1 0 0-14.586a7.293 7.293 0 0 0 0 14.587");
}

.rqm0zfshd {
  stop-color: var(--svg-color--a876ba, #A876BA);
  stop-opacity: 0;
}

.ry-pr9nfx {
  d: path("M6.21 18.59a3.519 3.519 0 1 0 0-7.037a3.519 3.519 0 0 0 0 7.037");
}

.utda0f46l {
  stop-color: var(--svg-color--83c9f0, #83C9F0);
}

.v4fmhkbqw {
  d: path("M23.119 11.553a3.991 3.991 0 1 0 0-7.983a3.991 3.991 0 0 0 0 7.983");
}

.vc_yrqbcn {
  stop-color: var(--svg-color--a876ba, #A876BA);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vf0eaacpx {
  d: path("M6.21 19.595a4.524 4.524 0 1 0 0-9.047a4.524 4.524 0 0 0 0 9.047");
}

.w7dcplrue {
  stop-color: var(--svg-color--e8eefe, #E8EEFE);
}

.wj_peg59y {
  d: path("M7.263 15.616a2.163 2.163 0 1 0 0-4.326a2.163 2.163 0 0 0 0 4.326");
}

.wtjrjlb-k {
  stop-color: var(--svg-color--55ebff, #55EBFF);
}

.yq81apbmx {
  stop-color: var(--svg-color--ff9cea, #FF9CEA);
  stop-opacity: 0;
}

</style>
