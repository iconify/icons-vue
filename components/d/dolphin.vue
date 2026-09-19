<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwRfuid)" class="rpee85bzp"/><path fill="url(#i2M8Ncw)" class="rpee85bzp"/><path fill="url(#ijJi5Je)" class="rpee85bzp"/><path fill="url(#iUe3G5k)" class="rpee85bzp"/><path fill="url(#iX0qeDe)" class="rpee85bzp"/><path fill="url(#iH0yX1b)" class="symoy0b1h"/><path fill="url(#iBAq5Bc)" class="symoy0b1h"/><path fill="url(#iZC1Btd)" class="symoy0b1h"/><path fill="url(#iFiIuXc)" class="sk7pt_bmv"/><path fill="url(#iOrNrqb)" class="sk7pt_bmv"/><path fill="url(#is6WSsU)" class="axgnqrlys"/><path fill="url(#i6mWoLb)" class="sk7pt_bmv"/><path fill="url(#io616cc)" class="o8bei7b2q"/><path fill="url(#i8R3yBe)" class="o8bei7b2q"/><path fill="url(#imZyPld)" class="o8bei7b2q"/><path class="lv051ibjs"/><path fill="url(#i3Jz1eh)" class="hfek8wbpk"/><path fill="url(#iezeXNy)" class="hfek8wbpk"/><path fill="url(#ixC1ygd)" class="hfek8wbpk"/><path class="tfds__3cu"/><path fill="url(#ijO0rCb)" class="x2bk17pew"/><path fill="url(#ibuY0bc)" class="x2bk17pew"/><g filter="url(#iAoictc)"><path class="ctb6bgigg"/></g><path fill="url(#iGetfYR)" class="ez7gu_b1k"/><path fill="url(#iPbRumb)" class="ez7gu_b1k"/><path fill="url(#iGiTFAe)" class="ez7gu_b1k"/><g filter="url(#ixt0yBe)"><path fill="url(#iUex7Gb)" class="kn93zvbjw"/></g><g filter="url(#iadmZlS)"><path fill="url(#ivMk72c)" class="qw_oan95h"/><path fill="url(#iiGKwxd)" class="qw_oan95h"/></g><g filter="url(#iJKlgZb)"><path class="kwi9p3b_g"/></g><defs><radialGradient id="iwRfuid" cx="0" cy="0" r="1" gradientTransform="rotate(124.807 9.768 9.045)scale(14.2342 20.4941)" gradientUnits="userSpaceOnUse"><stop class="qplq5bcwa"/><stop offset="1" class="fb9-4ibfz"/></radialGradient><radialGradient id="i2M8Ncw" cx="0" cy="0" r="1" gradientTransform="matrix(5 -3.25 3.4347 5.28414 17.02 13.938)" gradientUnits="userSpaceOnUse"><stop class="yx7q93bfv"/><stop offset="1" class="p76nybcie"/></radialGradient><radialGradient id="ijJi5Je" cx="0" cy="0" r="1" gradientTransform="rotate(-170.049 7.946 5.07)scale(7.23382 3.98285)" gradientUnits="userSpaceOnUse"><stop class="yx7q93bfv"/><stop offset="1" class="p76nybcie"/></radialGradient><radialGradient id="iUe3G5k" cx="0" cy="0" r="1" gradientTransform="rotate(-133.702 8.92 3.154)scale(6.82975 3.65397)" gradientUnits="userSpaceOnUse"><stop class="qt1nf_lbv"/><stop offset="1" class="qm-vjubfh"/></radialGradient><radialGradient id="iX0qeDe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3975 -3.0395 3.85862 1.77411 9.271 30.22)" gradientUnits="userSpaceOnUse"><stop class="oqs9q3djr"/><stop offset="1" class="xr5bcsjgp"/></radialGradient><radialGradient id="iH0yX1b" cx="0" cy="0" r="1" gradientTransform="rotate(57.714 -2.78 10.015)scale(3.71501 2.67598)" gradientUnits="userSpaceOnUse"><stop class="dqpiuibeu"/><stop offset="1" class="a8u5_3b9b"/></radialGradient><radialGradient id="iFiIuXc" cx="0" cy="0" r="1" gradientTransform="rotate(38.191 8.138 32.85)scale(5.96409 21.6274)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="d9qxfaban"/><stop offset=".914" class="fyniwp2ve"/></radialGradient><radialGradient id="iOrNrqb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.34375 1.21876 -.27379 -.97579 28.615 2.594)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="znu8afbpu"/><stop offset=".74" class="nkc6p3byb"/></radialGradient><radialGradient id="is6WSsU" cx="0" cy="0" r="1" gradientTransform="matrix(-8.40622 -7.43746 4.42693 -5.00356 28.552 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="a1uffjbuc"/><stop offset="1" class="yrkqh4jwg"/></radialGradient><radialGradient id="i6mWoLb" cx="0" cy="0" r="1" gradientTransform="matrix(3.51829 -3 14.10151 16.53774 23.708 5.656)" gradientUnits="userSpaceOnUse"><stop class="yrkqh4jwg"/><stop offset=".17" class="a1uffjbuc"/></radialGradient><radialGradient id="io616cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.50149 -.3622 12.485 6.477)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i8R3yBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 .24219 -.21307 -.23369 12.523 6.512)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="i3Jz1eh" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 -2.3125 3.8369 2.2814 15.71 13.563)" gradientUnits="userSpaceOnUse"><stop class="pdnzvhbvw"/><stop offset="1" class="ga444ib2j"/></radialGradient><radialGradient id="iezeXNy" cx="0" cy="0" r="1" gradientTransform="matrix(.2129 -2.45313 6.63568 .57589 12.467 12.406)" gradientUnits="userSpaceOnUse"><stop class="pdnzvhbvw"/><stop offset=".951" class="ga444ib2j"/></radialGradient><radialGradient id="ixC1ygd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07812 -2.21612 0 7.96 9.953)" gradientUnits="userSpaceOnUse"><stop class="fdtu57bml"/><stop offset="1" class="z_ls2-i6n"/></radialGradient><radialGradient id="ibuY0bc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8081 1.99142 -3.56152 -6.81054 18.286 12.541)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="iaiofbh_c"/><stop offset=".962" class="ri_xubehb"/></radialGradient><radialGradient id="iGetfYR" cx="0" cy="0" r="1" gradientTransform="rotate(74.102 -3.849 21.846)scale(5.73953 10.6177)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="p76nybcie"/><stop offset="1" class="yx7q93bfv"/></radialGradient><radialGradient id="iPbRumb" cx="0" cy="0" r="1" gradientTransform="matrix(1.18785 4.42574 -17.81528 4.78156 18.076 20.891)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="w4m7kb2ws"/><stop offset=".894" class="i74po6jof"/></radialGradient><radialGradient id="iUex7Gb" cx="0" cy="0" r="1" gradientTransform="rotate(104.138 -3.977 16.737)scale(7.15158 2.16957)" gradientUnits="userSpaceOnUse"><stop class="n1p0uki1f"/><stop offset="1" class="yl09ksb-r"/></radialGradient><radialGradient id="ivMk72c" cx="0" cy="0" r="1" gradientTransform="rotate(-120.493 12.327 7.114)scale(7.29803 4.43944)" gradientUnits="userSpaceOnUse"><stop class="n1p0uki1f"/><stop offset="1" class="yl09ksb-r"/></radialGradient><radialGradient id="iiGKwxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9957 -2.4805 .90912 -.36493 11.647 22.043)" gradientUnits="userSpaceOnUse"><stop class="h21b0j3gg"/><stop offset="1" class="mpqiw5wzl"/></radialGradient><linearGradient id="iBAq5Bc" x1="9.063" x2="8.5" y1="7.797" y2="8.484" gradientUnits="userSpaceOnUse"><stop class="g4aq7g4kb"/><stop offset="1" class="g29cizbbb"/></linearGradient><linearGradient id="iZC1Btd" x1="6.125" x2="6.453" y1="10.188" y2="9.656" gradientUnits="userSpaceOnUse"><stop class="hsegpfbsk"/><stop offset="1" class="jh1_u283j"/></linearGradient><linearGradient id="imZyPld" x1="12.238" x2="11.895" y1="6.245" y2="6.026" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ijO0rCb" x1="16.294" x2="14.722" y1="8.733" y2="14.568" gradientUnits="userSpaceOnUse"><stop class="ojwsjtirq"/><stop offset="1" class="xmdqlkbri"/></linearGradient><linearGradient id="iGiTFAe" x1="12.085" x2="12.731" y1="25.031" y2="24.752" gradientUnits="userSpaceOnUse"><stop class="fsby0o7ci"/><stop offset="1" class="rrt_tkbxl"/></linearGradient><filter id="iAoictc" width="18.899" height="17.488" x="9.337" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5877" stdDeviation="1.25"/></filter><filter id="ixt0yBe" width="3.131" height="6.171" x="9.191" y="23.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5877" stdDeviation=".25"/></filter><filter id="iadmZlS" width="3.55" height="7.848" x="8.458" y="15.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5877" stdDeviation=".25"/></filter><filter id="iJKlgZb" width="2.784" height="8.418" x="14.936" y="8.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5877" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dolphin" /></template>
<style>
.a1uffjbuc {
  stop-color: var(--svg-color--52dbff, #52DBFF);
  stop-opacity: 0;
}

.a8u5_3b9b {
  stop-color: var(--svg-color--57c6ff, #57C6FF);
  stop-opacity: 0;
}

.axgnqrlys {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M24.94 7.13a12.8 12.8 0 0 1 2.03-3.172c.51-.577.22-1.529-.52-1.678l-.37-.075a11.04 11.04 0 0 0-6.411.667c1.497.555 3.768 1.87 5.272 4.259");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.ctb6bgigg {
  stroke: var(--svg-color--43dfff, #43DFFF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.837 4.25h2.515c4.235 0 10.047 3.738 9.321 10.488");
}

.d9qxfaban {
  stop-color: var(--svg-color--42bdff, #42BDFF);
  stop-opacity: 0;
}

.dqpiuibeu {
  stop-color: var(--svg-color--57c6ff, #57C6FF);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ez7gu_b1k {
  d: path("M26.578 17.03c-3.973 6.176-12.044 6.554-15.49 5.888l1.175 2.4a.57.57 0 0 1 .523-.187c.78.134 1.586.135 2.423.135c5.242.017 9.922-3.02 11.37-8.235");
}

.fb9-4ibfz {
  stop-color: var(--svg-color--36abff, #36ABFF);
}

.fdtu57bml {
  stop-color: var(--svg-color--71cbff, #71CBFF);
}

.fsby0o7ci {
  stop-color: var(--svg-color--37abff, #37ABFF);
}

.ft5dv1b6b {
  fill: none;
}

.fyniwp2ve {
  stop-color: var(--svg-color--42bdff, #42BDFF);
}

.g29cizbbb {
  stop-color: var(--svg-color--3da9ff, #3DA9FF);
  stop-opacity: 0;
}

.g4aq7g4kb {
  stop-color: var(--svg-color--3da9ff, #3DA9FF);
}

.ga444ib2j {
  stop-color: var(--svg-color--73a9ff, #73A9FF);
  stop-opacity: 0;
}

.h21b0j3gg {
  stop-color: var(--svg-color--63c6ff, #63C6FF);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hfek8wbpk {
  d: path("M16.204 19.522c1.852-1.998 2.878-5.087.398-7.24c-1.385-.916-4.636-.906-8.243-.894l-1.242.003c-1.097 0-1.76-.656-1.982-1.438h8.545c2.37 0 4.69.178 5.718 2.297c1.021 2.104.138 4.62-3.194 7.272");
}

.hsegpfbsk {
  stop-color: var(--svg-color--36a3ff, #36A3FF);
}

.i74po6jof {
  stop-color: var(--svg-color--8594ff, #8594FF);
}

.iaiofbh_c {
  stop-color: var(--svg-color--51a7ff, #51A7FF);
  stop-opacity: 0;
}

.jh1_u283j {
  stop-color: var(--svg-color--36a3ff, #36A3FF);
  stop-opacity: 0;
}

.kn93zvbjw {
  d: path("m11.403 23.721l.42.612l-.298 2.725c-.07 1.383-1.251 1.706-1.834 1.834v-3.18z");
}

.kwi9p3b_g {
  fill: var(--svg-color--6eccff, #6ECCFF);
  d: path("M16.801 16.052c-1.337-3.208-.192-5.848.42-6.96l-.83-.457c-.1.161-.647 1.12-.9 2.879c-.294 2.04.67 3.91 1.31 4.538");
}

.lv051ibjs {
  fill: var(--svg-color--58cbff, #58CBFF);
  d: path("M16.204 19.522c1.852-1.998 2.878-5.087.398-7.24c-1.385-.916-4.636-.906-8.243-.894l-1.242.003c-1.097 0-1.76-.656-1.982-1.438h8.545c2.37 0 4.69.178 5.718 2.297c1.021 2.104.138 4.62-3.194 7.272");
}

.mpqiw5wzl {
  stop-color: var(--svg-color--63c6ff, #63C6FF);
  stop-opacity: 0;
}

.n1p0uki1f {
  stop-color: var(--svg-color--59b8ff, #59B8FF);
}

.nkc6p3byb {
  stop-color: var(--svg-color--70e0ff, #70E0FF);
  stop-opacity: 0;
}

.o8bei7b2q {
  d: path("M12.337 7.138a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.ojwsjtirq {
  stop-color: var(--svg-color--49bbff, #49BBFF);
}

.oqs9q3djr {
  stop-color: var(--svg-color--6b9bff, #6B9BFF);
}

.p76nybcie {
  stop-color: var(--svg-color--4d98ff, #4D98FF);
  stop-opacity: 0;
}

.pdnzvhbvw {
  stop-color: var(--svg-color--73a9ff, #73A9FF);
}

.qm-vjubfh {
  stop-color: var(--svg-color--4292ff, #4292FF);
  stop-opacity: 0;
}

.qplq5bcwa {
  stop-color: var(--svg-color--50e1ff, #50E1FF);
}

.qt1nf_lbv {
  stop-color: var(--svg-color--4292ff, #4292FF);
}

.qw_oan95h {
  d: path("M11.508 19.389c0-2.488-1.7-3.389-2.55-3.529v4.368l1.746 2.48l.804-.524z");
}

.ri_xubehb {
  stop-color: var(--svg-color--439bf4, #439BF4);
}

.rpee85bzp {
  d: path("M19.984 2.745a1.1 1.1 0 0 1-.788.003a11.2 11.2 0 0 0-3.416-.717l-3.02-.01c-2.547 0-4.952 2.408-4.952 4.751c.024.547-.36.574-.802.605q-.108.007-.218.017c-2.439.247-2.297 3.997.327 3.997q.626 0 1.242-.003c3.606-.012 6.858-.022 8.242.893c3.977 3.454-1.059 9.311-4.066 9.22c-.232-.008-.393-.215-.393-.448v-1.592c0-1.913-1.366-3.721-3.213-4.031c-.265-.094-.797-.133-.797.46v3.453c.156 1.631 1.01 2.417 1.557 2.92c.276.254.475.437.467.62c-.009.193-.223.392-.51.659c-.524.487-1.523 1.14-1.523 2.555v3.397c-.004.279.222.509.499.48c1.916-.2 3.52-1.522 3.52-3.473v-.854c0-.332.319-.573.646-.516c.78.134 1.586.135 2.422.135c6.27.02 11.735-4.328 11.829-11.545c-.008-2.228-.71-4.352-1.892-6.164a.75.75 0 0 1-.06-.736a12.7 12.7 0 0 1 1.885-2.863c.51-.577.22-1.529-.52-1.678l-.37-.075a11.03 11.03 0 0 0-6.096.54");
}

.rrt_tkbxl {
  stop-color: var(--svg-color--37abff, #37ABFF);
  stop-opacity: 0;
}

.sk7pt_bmv {
  d: path("M24.94 7.13a12.8 12.8 0 0 1 2.03-3.172c.51-.577.22-1.529-.52-1.678l-.37-.075a11.04 11.04 0 0 0-6.411.667c1.497.555 3.768 1.87 5.272 4.259");
}

.symoy0b1h {
  d: path("M11.54 11.404L7.808 6.771v.001c.024.547-.36.574-.802.605q-.108.007-.218.017c-2.439.247-2.297 3.997.327 3.997q.626 0 1.242-.003c1.109-.004 2.185-.007 3.183.016");
}

.tfds__3cu {
  fill: var(--svg-color--3ab9ff, #3AB9FF);
  d: path("M15.938 16.172c-1.876-1.575-2.126-3.578-1.813-6.969c.04-.437.724-1.049 1.563-1.078c.902-.031 1.952.56 1.624 1.219c-1.25 2.515-.89 4.937-.453 6.156c.37 1.028-.548.986-.922.672");
}

.w4m7kb2ws {
  stop-color: var(--svg-color--8594ff, #8594FF);
  stop-opacity: 0;
}

.x2bk17pew {
  d: path("M15.938 16.172c-1.876-1.575-2.126-3.578-1.813-6.969c.04-.437.724-1.049 1.563-1.078c.902-.031 1.952.56 1.624 1.219c-1.25 2.515-.89 4.937-.453 6.156c.37 1.028-.548.986-.922.672");
}

.xmdqlkbri {
  stop-color: var(--svg-color--49bbff, #49BBFF);
  stop-opacity: 0;
}

.xr5bcsjgp {
  stop-color: var(--svg-color--6b9bff, #6B9BFF);
  stop-opacity: 0;
}

.yl09ksb-r {
  stop-color: var(--svg-color--59b8ff, #59B8FF);
  stop-opacity: 0;
}

.yrkqh4jwg {
  stop-color: var(--svg-color--92e8ff, #92E8FF);
}

.yx7q93bfv {
  stop-color: var(--svg-color--4d98ff, #4D98FF);
}

.z_ls2-i6n {
  stop-color: var(--svg-color--71cbff, #71CBFF);
  stop-opacity: 0;
}

.znu8afbpu {
  stop-color: var(--svg-color--70e0ff, #70E0FF);
}

</style>
