<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="tuarujses"/><path fill="url(#idlN8Gl)" class="slzc1mb0r"/><path fill="url(#ialqKPd)" class="iaio5bb7b"/><path fill="url(#iXemD8d)" class="hn25to01d"/><path fill="url(#iRHiIyc)" class="gf72i2b1v"/><path fill="url(#irQPwLd)" class="tdgl846cc"/><path fill="url(#iEHeEle)" class="w1ou_wbrh"/><path class="at56-2vao"/><path fill="url(#iWacj5m)" class="gjs3wacqy"/><g filter="url(#i2VQULd)"><path class="xgftvqbzm"/></g><g filter="url(#iqZA5Ac)"><path fill="url(#iquoLob)" class="vkuwt5x6l"/></g><g filter="url(#iQ7KFbW)"><path fill="url(#iL3cvsc)" class="c-21mdzno"/><path fill="url(#ikFid2d)" class="c-21mdzno"/></g><g filter="url(#io54czd)"><path fill="url(#i31vdis)" class="tgq-91k5f"/><path fill="url(#ibq2lbk)" class="tgq-91k5f"/></g><path fill="url(#imvRh4b)" class="ntr-y_btp"/><path fill="url(#iUrnXKe)" class="ntr-y_btp"/><path fill="url(#ijrV5Nb)" class="ntr-y_btp"/><path fill="url(#iJXKMpd)" class="ntr-y_btp"/><path fill="url(#iv7aBPb)" class="ntr-y_btp"/><path fill="url(#i9LHiYg)" class="bnsi545pm"/><path fill="url(#idvzhdC)" class="bnsi545pm"/><g filter="url(#iUWnuQs)"><path fill="url(#iBIEYhr)" class="a59w-mb-j"/></g><path fill="url(#i8pY4cd)" class="evml6oqwj"/><path fill="url(#icPI9Be)" class="i-hpnxbwt"/><defs><linearGradient id="idlN8Gl" x1="7.004" x2="23.004" y1="15.998" y2="15.998" gradientUnits="userSpaceOnUse"><stop class="u5c1bozbs"/><stop offset="1" class="d6v5rvbsr"/></linearGradient><linearGradient id="ialqKPd" x1="21.004" x2="9.004" y1="7.998" y2="7.998" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset="1" class="xg4qvkb5q"/></linearGradient><linearGradient id="iXemD8d" x1="21.004" x2="9.004" y1="4.998" y2="4.998" gradientUnits="userSpaceOnUse"><stop class="roy6tlxfk"/><stop offset="1" class="kpwvuab3v"/></linearGradient><linearGradient id="iRHiIyc" x1="24.004" x2="6.004" y1="28.998" y2="28.998" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset="1" class="xg4qvkb5q"/></linearGradient><linearGradient id="irQPwLd" x1="20.004" x2="15.004" y1="7.498" y2="7.498" gradientUnits="userSpaceOnUse"><stop class="roy6tlxfk"/><stop offset="1" class="kpwvuab3v"/></linearGradient><linearGradient id="iEHeEle" x1="27.004" x2="23.004" y1="10.498" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset="1" class="xg4qvkb5q"/></linearGradient><linearGradient id="iWacj5m" x1="23.004" x2="7.004" y1="14.498" y2="14.498" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset="1" class="xg4qvkb5q"/></linearGradient><linearGradient id="iquoLob" x1="14.88" x2="14.88" y1="27.797" y2="20.439" gradientUnits="userSpaceOnUse"><stop class="kmrtbdcsk"/><stop offset="1" class="i84bnu7vm"/></linearGradient><linearGradient id="iL3cvsc" x1="20.577" x2="8.88" y1="7.388" y2="7.388" gradientUnits="userSpaceOnUse"><stop class="f09cz-ben"/><stop offset="1" class="fymhzub8e"/></linearGradient><linearGradient id="ikFid2d" x1="20.88" x2="19.855" y1="9.021" y2="9.021" gradientUnits="userSpaceOnUse"><stop class="d_6nwfbnd"/><stop offset="1" class="yx4ik5bea"/></linearGradient><linearGradient id="i31vdis" x1="20.884" x2="8.884" y1="4.998" y2="4.998" gradientUnits="userSpaceOnUse"><stop class="a68xztfww"/><stop offset="1" class="q05y8-b9h"/></linearGradient><linearGradient id="ibq2lbk" x1="8.88" x2="9.48" y1="5.321" y2="5.321" gradientUnits="userSpaceOnUse"><stop class="kp-p10b1v"/><stop offset="1" class="id022_80x"/></linearGradient><linearGradient id="imvRh4b" x1="23.884" x2="5.594" y1="28.998" y2="28.998" gradientUnits="userSpaceOnUse"><stop class="z966fi52o"/><stop offset="1" class="em76014po"/></linearGradient><linearGradient id="iUrnXKe" x1="7.033" x2="7.113" y1="31.436" y2="29" gradientUnits="userSpaceOnUse"><stop class="puvmop6pl"/><stop offset="1" class="czpg9ybfg"/></linearGradient><linearGradient id="ijrV5Nb" x1="14.88" x2="14.88" y1="27.637" y2="29" gradientUnits="userSpaceOnUse"><stop class="lq8rhv8ek"/><stop offset="1" class="czg4ojbhy"/></linearGradient><linearGradient id="iJXKMpd" x1="5.88" x2="6.953" y1="29.677" y2="29.657" gradientUnits="userSpaceOnUse"><stop class="puvmop6pl"/><stop offset="1" class="czpg9ybfg"/></linearGradient><linearGradient id="iv7aBPb" x1="23.88" x2="22.669" y1="29.717" y2="29.717" gradientUnits="userSpaceOnUse"><stop class="csb4ycbcu"/><stop offset="1" class="uhzjbn8xm"/></linearGradient><linearGradient id="i9LHiYg" x1="19.884" x2="14.884" y1="7.498" y2="7.498" gradientUnits="userSpaceOnUse"><stop class="uihyjo4ez"/><stop offset="1" class="e7n7wccig"/></linearGradient><linearGradient id="iBIEYhr" x1="25.356" x2="24.263" y1="9.781" y2="13.25" gradientUnits="userSpaceOnUse"><stop class="q84e74k2i"/><stop offset="1" class="h9iaxib1y"/></linearGradient><linearGradient id="icPI9Be" x1="22.884" x2="6.884" y1="14.498" y2="14.498" gradientUnits="userSpaceOnUse"><stop class="s7a7qftcd"/><stop offset=".017" class="s7a7qftcd"/><stop offset=".059" class="fa1v68gtu"/><stop offset=".322" class="fa1v68gtu"/><stop offset=".961" class="jtg2bm5yw"/><stop offset="1" class="bzjhmdbqo"/></linearGradient><filter id="i2VQULd" width="4.25" height="13.25" x="22.88" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.145098 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11917"/></filter><filter id="iqZA5Ac" width="17" height="28" x="6.38" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.180392 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11917"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.321569 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11917" result="effect2_innerShadow_18_11917"/></filter><filter id="iQ7KFbW" width="12.3" height="8.3" x="8.88" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11917"/></filter><filter id="io54czd" width="12.5" height="2.5" x="8.38" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.152941 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11917"/></filter><filter id="iUWnuQs" width="4.3" height="7.29" x="22.73" y="6.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.952941 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11917"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.329412 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11917" result="effect2_innerShadow_18_11917"/></filter><radialGradient id="idvzhdC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .41793 -3.43845 0 18.772 7.369)" gradientUnits="userSpaceOnUse"><stop class="m24j37q5x"/><stop offset="1" class="g1p1tvbhp"/></radialGradient><radialGradient id="i8pY4cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.38281 .25781 -.24876 -.36937 25.575 12.43)" gradientUnits="userSpaceOnUse"><stop class="f2evgtpuu"/><stop offset="1" class="ab098obaj"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fuel-pump" /></template>
<style>
.a59w-mb-j {
  d: path("M22.88 7.45c0 .07.01.13.04.19l.92 2.01c.03.06.04.13.04.19v3.1c0 .59.44 1.05.99 1.05h1.59c.23 0 .42-.2.42-.45V9.96a.46.46 0 0 0-.17-.36l-3.15-2.51c-.28-.22-.68-.01-.68.36m2.58 5.48h-.15c-.23 0-.42-.2-.42-.45v-1.65c0-.4.46-.6.72-.32l.15.16c.08.08.12.2.12.32v1.5c0 .24-.19.44-.42.44");
}

.a68xztfww {
  stop-color: var(--svg-color--513e63, #513E63);
}

.ab098obaj {
  stop-color: var(--svg-color--31222e, #31222E);
}

.at56-2vao {
  fill: var(--svg-color--1b1b1b, #1B1B1B);
  d: path("M25.5 13a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.bnsi545pm {
  d: path("M19.38 7h-4c-.28 0-.5.22-.5.5s.22.5.5.5h4c.28 0 .5-.22.5-.5s-.22-.5-.5-.5");
}

.bzjhmdbqo {
  stop-color: var(--svg-color--6f6974, #6F6974);
}

.c-21mdzno {
  d: path("M19.85 12H9.91c-.57 0-1.03-.46-1.03-1.03V5.03c0-.57.46-1.03 1.03-1.03h9.94c.57 0 1.03.46 1.03 1.03v5.94c0 .57-.46 1.03-1.03 1.03");
}

.csb4ycbcu {
  stop-color: var(--svg-color--f9f4fd, #F9F4FD);
}

.czg4ojbhy {
  stop-color: var(--svg-color--d8cad3, #D8CAD3);
  stop-opacity: 0;
}

.czpg9ybfg {
  stop-color: var(--svg-color--605567, #605567);
  stop-opacity: 0;
}

.d_6nwfbnd {
  stop-color: var(--svg-color--998da0, #998DA0);
}

.d6v5rvbsr {
  stop-color: var(--svg-color--e63529, #E63529);
}

.e7n7wccig {
  stop-color: var(--svg-color--352b3c, #352B3C);
}

.em76014po {
  stop-color: var(--svg-color--a69aae, #A69AAE);
}

.evml6oqwj {
  d: path("M25.38 13a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.f09cz-ben {
  stop-color: var(--svg-color--d2c7d9, #D2C7D9);
}

.f2evgtpuu {
  stop-color: var(--svg-color--4f494a, #4F494A);
}

.fa1v68gtu {
  stop-color: var(--svg-color--d3c6db, #D3C6DB);
}

.ft5dv1b6b {
  fill: none;
}

.fymhzub8e {
  stop-color: var(--svg-color--c6bdcb, #C6BDCB);
}

.g1p1tvbhp {
  stop-color: var(--svg-color--65527a, #65527A);
  stop-opacity: 0;
}

.gf72i2b1v {
  d: path("M23.01 28H7c-.55 0-1 .45-1 1v1h18v-1.01c0-.55-.44-.99-.99-.99");
}

.gjs3wacqy {
  d: path("M23 14H7v1h16z");
}

.h9iaxib1y {
  stop-color: var(--svg-color--a699aa, #A699AA);
}

.hn25to01d {
  d: path("M21 6H9v-.97C9 4.46 9.46 4 10.03 4h9.94c.57 0 1.03.46 1.03 1.03z");
}

.i-hpnxbwt {
  d: path("M22.88 14h-16v1h16z");
}

.i84bnu7vm {
  stop-color: var(--svg-color--e73446, #E73446);
}

.iaio5bb7b {
  d: path("M19.97 12h-9.94C9.46 12 9 11.54 9 10.97V5.03C9 4.46 9.46 4 10.03 4h9.94c.57 0 1.03.46 1.03 1.03v5.94c0 .57-.46 1.03-1.03 1.03");
}

.id022_80x {
  stop-color: var(--svg-color--4a454d, #4A454D);
  stop-opacity: 0;
}

.jtg2bm5yw {
  stop-color: var(--svg-color--ada2b4, #ADA2B4);
}

.kmrtbdcsk {
  stop-color: var(--svg-color--d7357e, #D7357E);
}

.kp-p10b1v {
  stop-color: var(--svg-color--4a454d, #4A454D);
}

.kpwvuab3v {
  stop-color: var(--svg-color--1b1b1b, #1B1B1B);
}

.kz7b9dj2g {
  stop-color: var(--svg-color--d2d2d2, #D2D2D2);
}

.lq8rhv8ek {
  stop-color: var(--svg-color--d8cad3, #D8CAD3);
}

.m24j37q5x {
  stop-color: var(--svg-color--65527a, #65527A);
}

.ntr-y_btp {
  d: path("M22.89 28H6.88c-.55 0-1 .45-1 1v1h18v-1.01c0-.55-.44-.99-.99-.99");
}

.puvmop6pl {
  stop-color: var(--svg-color--605567, #605567);
}

.q05y8-b9h {
  stop-color: var(--svg-color--433b4a, #433B4A);
}

.q84e74k2i {
  stop-color: var(--svg-color--d4c4d8, #D4C4D8);
}

.roy6tlxfk {
  stop-color: var(--svg-color--503469, #503469);
}

.s7a7qftcd {
  stop-color: var(--svg-color--ece4f3, #ECE4F3);
}

.slzc1mb0r {
  d: path("M21.01 30H8.99C7.89 30 7 29.11 7 28.01V3.99C7 2.89 7.89 2 8.99 2h12.02c1.1 0 1.99.89 1.99 1.99v24.02c0 1.1-.89 1.99-1.99 1.99");
}

.tdgl846cc {
  d: path("M19.5 7h-4c-.28 0-.5.22-.5.5s.22.5.5.5h4c.28 0 .5-.22.5-.5s-.22-.5-.5-.5");
}

.tgq-91k5f {
  d: path("M20.88 6h-12v-.97c0-.57.46-1.03 1.03-1.03h9.94c.57 0 1.03.46 1.03 1.03z");
}

.tuarujses {
  fill: var(--svg-color--1b1b1b, #1B1B1B);
  d: path("M26 13v11.5c0 .28-.22.5-.5.5s-.5-.22-.5-.5v-7c0-.83-.67-1.5-1.5-1.5c-.04 0-.46-.01-.5 0v1c.06-.03.43 0 .5 0c.28 0 .5.22.5.5v7c0 .83.67 1.5 1.5 1.5s1.5-.67 1.5-1.5V13z");
}

.u5c1bozbs {
  stop-color: var(--svg-color--e22585, #E22585);
}

.uhzjbn8xm {
  stop-color: var(--svg-color--f9f4fd, #F9F4FD);
  stop-opacity: 0;
}

.uihyjo4ez {
  stop-color: var(--svg-color--503668, #503668);
}

.vkuwt5x6l {
  d: path("M20.89 30H8.87c-1.1 0-1.99-.89-1.99-1.99V3.99c0-1.1.89-1.99 1.99-1.99h12.02c1.1 0 1.99.89 1.99 1.99v24.02c0 1.1-.89 1.99-1.99 1.99");
}

.w1ou_wbrh {
  d: path("M23 7.45c0 .07.01.13.04.19l.92 2.01c.03.06.04.13.04.19v3.1c0 .59.44 1.05.99 1.05h1.59c.23 0 .42-.2.42-.45V9.96a.46.46 0 0 0-.17-.36l-3.15-2.51c-.28-.22-.68-.01-.68.36m2.58 5.48h-.15c-.23 0-.42-.2-.42-.45v-1.65c0-.4.46-.6.72-.32l.15.16c.08.08.12.2.12.32v1.5c0 .24-.19.44-.42.44");
}

.xg4qvkb5q {
  stop-color: var(--svg-color--9a9a9a, #9A9A9A);
}

.xgftvqbzm {
  fill: var(--svg-color--464143, #464143);
  d: path("M25.88 13v11.5c0 .28-.22.5-.5.5s-.5-.22-.5-.5v-7c0-.83-.67-1.5-1.5-1.5c-.04 0-.46-.01-.5 0v1c.06-.03.43 0 .5 0c.28 0 .5.22.5.5v7c0 .83.67 1.5 1.5 1.5s1.5-.67 1.5-1.5V13z");
}

.yx4ik5bea {
  stop-color: var(--svg-color--998da0, #998DA0);
  stop-opacity: 0;
}

.z966fi52o {
  stop-color: var(--svg-color--d7c7e2, #D7C7E2);
}

</style>
