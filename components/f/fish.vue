<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#izYpuzc)" class="fx4ktu0uo"/><circle fill="url(#iLRcMFd)" class="mg03avwsp"/><g filter="url(#i1QNuQd)"><rect fill="url(#ikacIub)" class="pnh-m2-ug"/><rect fill="url(#i4lIDec)" class="pnh-m2-ug"/></g><rect fill="url(#igV1GSF)" class="pnh-m2-ug"/><rect fill="url(#iDbi2ed)" class="pnh-m2-ug"/><g filter="url(#icmia7d)"><path class="qobhfgjrf"/></g><g filter="url(#i11JUdm)"><path class="zrjybhb3j"/><path fill="url(#iizSplb)" class="z262e5b8h"/><path fill="url(#ivWr4xd)" class="z262e5b8h"/><path fill="url(#iiVx8Fb)" class="z262e5b8h"/></g><circle fill="url(#iPPjTna)" class="yvhk3f21p"/><circle fill="url(#iq99Dke)" class="yvhk3f21p"/><circle fill="url(#iUXF3Gd)" class="yvhk3f21p"/><path fill="url(#ijD1TTb)" class="t2h3eunft"/><path fill="url(#iyGVs2c)" class="t2h3eunft"/><path fill="url(#icnBfeu)" class="t2h3eunft"/><path fill="url(#ifLZyld)" class="t2h3eunft"/><path fill="url(#iIPE20b)" class="f7b33gbef"/><path fill="url(#ialOvpe)" class="f7b33gbef"/><path fill="url(#im1FcCc)" class="f7b33gbef"/><path fill="url(#inlMXTb)" class="igykl00lo"/><path fill="url(#iFP6YEe)" class="igykl00lo"/><path fill="url(#ii3Zy2z)" class="igykl00lo"/><path fill="url(#iJ3qdyc)" class="kwke1jb8a"/><path fill="url(#ijMLOHc)" class="kwke1jb8a"/><path fill="url(#ilYn2Eb)" class="kwke1jb8a"/><defs><radialGradient id="izYpuzc" cx="0" cy="0" r="1" gradientTransform="rotate(150.684 -.954 10.222)scale(1.1648 1.5939)" gradientUnits="userSpaceOnUse"><stop class="blr5wsblo"/><stop offset="1" class="dnwm9gb8k"/></radialGradient><radialGradient id="iLRcMFd" cx="0" cy="0" r="1" gradientTransform="rotate(150.684 -.693 9.222)scale(1.1648 1.5939)" gradientUnits="userSpaceOnUse"><stop class="blr5wsblo"/><stop offset="1" class="dnwm9gb8k"/></radialGradient><radialGradient id="ikacIub" cx="0" cy="0" r="1" gradientTransform="matrix(11.37503 14.62504 -19.21583 14.94565 11 16)" gradientUnits="userSpaceOnUse"><stop class="pdh73mazh"/><stop offset="1" class="upywglb-x"/></radialGradient><radialGradient id="igV1GSF" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.43752 -11.9454 8.58352 5.75 11.5)" gradientUnits="userSpaceOnUse"><stop class="pdh73mazh"/><stop offset="1" class="w8ubovymj"/></radialGradient><radialGradient id="iDbi2ed" cx="0" cy="0" r="1" gradientTransform="rotate(-144.29 17.701 10.406)scale(26.5554 22.4157)" gradientUnits="userSpaceOnUse"><stop offset=".935" class="s4rkikb0n"/><stop offset="1" class="nkistxw6x"/></radialGradient><radialGradient id="iizSplb" cx="0" cy="0" r="1" gradientTransform="matrix(.92187 -1.17969 .66496 .51964 11.906 24.507)" gradientUnits="userSpaceOnUse"><stop class="x4aqxyecp"/><stop offset=".609" class="ajyyq3awm"/></radialGradient><radialGradient id="ivWr4xd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 .92969 -.55416 .52156 12.047 14.43)" gradientUnits="userSpaceOnUse"><stop class="x4aqxyecp"/><stop offset=".609" class="ajyyq3awm"/></radialGradient><radialGradient id="iiVx8Fb" cx="0" cy="0" r="1" gradientTransform="matrix(1.64731 0 0 3.34375 13.196 19.344)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="tj8bo-t7r"/><stop offset="1" class="w_ajqibtd"/></radialGradient><radialGradient id="iPPjTna" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 8.828 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iq99Dke" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 1.071 10.395)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="ijD1TTb" cx="0" cy="0" r="1" gradientTransform="matrix(.125 7.375 -7.4691 .1266 28.375 20.75)" gradientUnits="userSpaceOnUse"><stop class="mu306i01g"/><stop offset="1" class="xvbew__1q"/></radialGradient><radialGradient id="iyGVs2c" cx="0" cy="0" r="1" gradientTransform="rotate(135.266 12.15 17.095)scale(9.50185 15.6131)" gradientUnits="userSpaceOnUse"><stop offset=".801" class="v5m6ybcwn"/><stop offset="1" class="vqi5j2blf"/></radialGradient><radialGradient id="ifLZyld" cx="0" cy="0" r="1" gradientTransform="matrix(0 7 -2.96293 0 29.719 21.125)" gradientUnits="userSpaceOnUse"><stop class="togwtu2rb"/><stop offset=".923" class="m98r0kgls"/></radialGradient><radialGradient id="iIPE20b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.85113 8.09803 -5.91743 -2.0834 28.726 11.59)" gradientUnits="userSpaceOnUse"><stop class="mu306i01g"/><stop offset="1" class="xvbew__1q"/></radialGradient><radialGradient id="ialOvpe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.75 -2.3125 3.79981 -14.37766 33.188 16)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="v5m6ybcwn"/><stop offset="1" class="vqi5j2blf"/></radialGradient><radialGradient id="im1FcCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.3125 -1.16539 0 29.719 11.094)" gradientUnits="userSpaceOnUse"><stop class="togwtu2rb"/><stop offset=".923" class="m98r0kgls"/></radialGradient><radialGradient id="inlMXTb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3125 -1 .70957 -1.6409 15.688 29.5)" gradientUnits="userSpaceOnUse"><stop class="zt39hwfcy"/><stop offset="1" class="yw6p4ac_h"/></radialGradient><radialGradient id="ii3Zy2z" cx="0" cy="0" r="1" gradientTransform="rotate(-153.997 12.059 12.917)scale(2.85112 1.12711)" gradientUnits="userSpaceOnUse"><stop class="z_3g9iggj"/><stop offset=".969" class="scbldwdiv"/></radialGradient><radialGradient id="iJ3qdyc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.57831 3.8125 -1.89075 -4.25428 20.688 6.875)" gradientUnits="userSpaceOnUse"><stop class="mu306i01g"/><stop offset="1" class="v53gl_bea"/></radialGradient><radialGradient id="ilYn2Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 3.12502 -.98416 -1.31877 22.25 5.5)" gradientUnits="userSpaceOnUse"><stop class="togwtu2rb"/><stop offset=".644" class="m98r0kgls"/></radialGradient><linearGradient id="i4lIDec" x1="14" x2="14" y1="29.375" y2="24.438" gradientUnits="userSpaceOnUse"><stop class="om3xxbt3s"/><stop offset="1" class="swts57lcx"/></linearGradient><linearGradient id="iUXF3Gd" x1="8.581" x2="8.238" y1="17.088" y2="16.869" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="icnBfeu" x1="38.438" x2="25" y1="25.563" y2="25.563" gradientUnits="userSpaceOnUse"><stop offset=".849" class="v5m6ybcwn"/><stop offset="1" class="vqi5j2blf"/></linearGradient><linearGradient id="iFP6YEe" x1="15.188" x2="15.219" y1="27.531" y2="28.516" gradientUnits="userSpaceOnUse"><stop class="urt9xyoml"/><stop offset="1" class="kdep7o28r"/></linearGradient><linearGradient id="ijMLOHc" x1="12.109" x2="12.109" y1="11.469" y2="9.469" gradientUnits="userSpaceOnUse"><stop offset=".109" class="ip3jyvb3a"/><stop offset="1" class="iitgg7bxk"/></linearGradient><filter id="i1QNuQd" width="22.5" height="17.813" x="2.5" y="10.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.407843 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5956"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.411765 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_5956" result="effect2_innerShadow_28327_5956"/></filter><filter id="icmia7d" width="7.174" height="14.672" x="9.609" y="12.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5956" stdDeviation="1"/></filter><filter id="i11JUdm" width="3.174" height="10.672" x="11.609" y="14.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.439216 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5956"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fish" /></template>
<style>
.ajyyq3awm {
  stop-color: var(--svg-color--4a8cff, #4A8CFF);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.blr5wsblo {
  stop-color: var(--svg-color--3aaee7, #3AAEE7);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.dnwm9gb8k {
  stop-color: var(--svg-color--45a5e8, #45A5E8);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f7b33gbef {
  d: path("M25 14.625a4 4 0 0 1 4-4h.219a.5.5 0 0 1 .5.5v4.25a4 4 0 0 1-4 4H25z");
}

.ft5dv1b6b {
  fill: none;
}

.fx4ktu0uo {
  cx: 3.055px;
  cy: 19.945px;
  r: 1.055px;
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.igykl00lo {
  d: path("M15.17 28c.977 0 1.768.791 1.768 1.767a.22.22 0 0 1-.221.22h-1.76A1.99 1.99 0 0 1 12.968 28z");
}

.iitgg7bxk {
  stop-color: var(--svg-color--0a75cc, #0A75CC);
  stop-opacity: 0;
}

.ip3jyvb3a {
  stop-color: var(--svg-color--0a75cc, #0A75CC);
}

.kdep7o28r {
  stop-color: var(--svg-color--0e66fd, #0E66FD);
  stop-opacity: 0;
}

.kwke1jb8a {
  d: path("M17.75 10.688a4 4 0 0 0 4-4v-.329a.5.5 0 0 0-.5-.5h-5.14a4 4 0 0 0-4 4v.829z");
}

.m98r0kgls {
  stop-color: var(--svg-color--54bdff, #54BDFF);
  stop-opacity: 0;
}

.mg03avwsp {
  cx: 3.055px;
  cy: 17.945px;
  r: 1.055px;
}

.mu306i01g {
  stop-color: var(--svg-color--46aaff, #46AAFF);
}

.nkistxw6x {
  stop-color: var(--svg-color--59c0e7, #59C0E7);
}

.om3xxbt3s {
  stop-color: var(--svg-color--508bff, #508BFF);
}

.pdh73mazh {
  stop-color: var(--svg-color--50caff, #50CAFF);
}

.pnh-m2-ug {
  width: 22px;
  height: 17.313px;
  x: 3px;
  y: 10.688px;
  rx: 8.656px;
}

.qobhfgjrf {
  fill: var(--svg-color--3a94e7, #3A94E7);
  d: path("M12.43 14.125a.5.5 0 1 0-.642.766zm-.684 9.711a.5.5 0 0 0 .726.687zm.042-8.945c2.545 2.132 2.79 5.951-.042 8.945l.726.687c3.169-3.35 3.007-7.843-.042-10.398z");
}

.s4rkikb0n {
  stop-color: var(--svg-color--59c0e7, #59C0E7);
  stop-opacity: 0;
}

.scbldwdiv {
  stop-color: var(--svg-color--519dff, #519DFF);
  stop-opacity: 0;
}

.swts57lcx {
  stop-color: var(--svg-color--508bff, #508BFF);
  stop-opacity: 0;
}

.t2h3eunft {
  d: path("M25 24.125a4 4 0 0 0 4 4h.219a.5.5 0 0 0 .5-.5v-4.25a4 4 0 0 0-4-4H25z");
}

.tj8bo-t7r {
  stop-color: var(--svg-color--4f7fe6, #4F7FE6);
}

.togwtu2rb {
  stop-color: var(--svg-color--54bdff, #54BDFF);
}

.upywglb-x {
  stop-color: var(--svg-color--4d7fff, #4D7FFF);
}

.urt9xyoml {
  stop-color: var(--svg-color--0e66fd, #0E66FD);
}

.v53gl_bea {
  stop-color: var(--svg-color--2b86d9, #2B86D9);
}

.v5m6ybcwn {
  stop-color: var(--svg-color--3184e6, #3184E6);
  stop-opacity: 0;
}

.vqi5j2blf {
  stop-color: var(--svg-color--3184e6, #3184E6);
}

.w_ajqibtd {
  stop-color: var(--svg-color--4f7fe6, #4F7FE6);
  stop-opacity: 0;
}

.w8ubovymj {
  stop-color: var(--svg-color--50caff, #50CAFF);
  stop-opacity: 0;
}

.x4aqxyecp {
  stop-color: var(--svg-color--4a8cff, #4A8CFF);
}

.xvbew__1q {
  stop-color: var(--svg-color--368aff, #368AFF);
}

.yvhk3f21p {
  cx: 8.68px;
  cy: 17.48px;
  r: 0.5px;
}

.yw6p4ac_h {
  stop-color: var(--svg-color--3170ff, #3170FF);
}

.z_3g9iggj {
  stop-color: var(--svg-color--519dff, #519DFF);
}

.z262e5b8h {
  d: path("M12.43 14.125a.5.5 0 1 0-.642.766zm-.684 9.711a.5.5 0 0 0 .726.687zm.042-8.945c2.545 2.132 2.79 5.951-.042 8.945l.726.687c3.169-3.35 3.007-7.843-.042-10.398z");
}

.zrjybhb3j {
  fill: var(--svg-color--3f61e7, #3F61E7);
  d: path("M12.43 14.125a.5.5 0 1 0-.642.766zm-.684 9.711a.5.5 0 0 0 .726.687zm.042-8.945c2.545 2.132 2.79 5.951-.042 8.945l.726.687c3.169-3.35 3.007-7.843-.042-10.398z");
}

.zt39hwfcy {
  stop-color: var(--svg-color--4286ff, #4286FF);
}

</style>
