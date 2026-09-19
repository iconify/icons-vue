<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4izZYb)"><path fill="url(#i6ipAsd)" class="zjr7_gbdk"/></g><path fill="url(#i15Ei1c)" class="zjr7_gbdk"/><path fill="url(#ivReETd)" class="zjr7_gbdk"/><path fill="url(#iqp1bTc)" class="zjr7_gbdk"/><path fill="url(#ibToWCd)" class="zjr7_gbdk"/><path fill="url(#igeHfOe)" class="zjr7_gbdk"/><path fill="url(#iwek3Cd)" class="zjr7_gbdk"/><path fill="url(#iMsbuWc)" class="zjr7_gbdk"/><path stroke="url(#ihOZ0ub)" class="e6ta-hb1r"/><path fill="url(#iquB4Le)" class="ci9k38iay"/><path fill="url(#inoW1He)" class="ci9k38iay"/><path stroke="url(#i3o0tBX)" class="ohbd59ser"/><path fill="url(#i3LE7sA)" class="wtyonjtjn"/><path fill="url(#ieEn1Hb)" class="wtyonjtjn"/><path stroke="url(#ig03dLe)" class="i3ui0tbog"/><path stroke="url(#in2ZioE)" class="i3ui0tbog"/><g filter="url(#i9yChVb)"><path stroke="url(#iasie9E)" class="dwn10t66g"/></g><g filter="url(#iSoI2Tb)"><path stroke="url(#iUgD1bb)" class="c7yi3qnrw"/></g><g filter="url(#iA22FYb)"><path fill="url(#i2MFcib)" class="vezk3kihf"/><path fill="url(#idzpa6d)" class="vezk3kihf"/><path fill="url(#iutz6pc)" class="vezk3kihf"/><path fill="url(#i5XgIwb)" class="vezk3kihf"/></g><g filter="url(#iRz62Bc)"><path class="jxqbcvb_r"/><path fill="url(#ij9AkDc)" class="ng3fuacxt"/><path fill="url(#iv3VvUd)" class="ng3fuacxt"/><path fill="url(#ihqSmBe)" class="ng3fuacxt"/></g><g filter="url(#ip8EgNe)"><rect class="pgvfhrbaa"/><rect fill="url(#iU59XMb)" class="bpu98neqd"/></g><rect fill="url(#iCmyYKd)" class="eac-tqbua"/><rect fill="url(#iD2X8Xb)" class="eac-tqbua"/><rect fill="url(#iO6zBbc)" class="eac-tqbua"/><path fill="url(#iNzYfdb)" class="wzldrlipv"/><g filter="url(#ig3QMDd)"><path stroke="url(#iKsNnPc)" class="vv-wr2wwj"/></g><defs><radialGradient id="i15Ei1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.77141 .35217 -.29116 -.63776 13.672 13.294)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="krh1j1bey"/></radialGradient><radialGradient id="ivReETd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.98 17.337 -.908)scale(1.57379 .42766)" gradientUnits="userSpaceOnUse"><stop class="apn88dn2q"/><stop offset="1" class="m-0xy7bpf"/></radialGradient><radialGradient id="iqp1bTc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82393 -3.49707 2.47427 -3.41305 14 13.182)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="g9b20ob6u"/><stop offset=".949" class="qixhejb-r"/></radialGradient><radialGradient id="ibToWCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68763 1.17209 -1.72458 -1.01176 11.638 12.202)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="l2d19yorl"/><stop offset="1" class="ccyhfh3vm"/></radialGradient><radialGradient id="igeHfOe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44919 1.05902 -.37122 -.50799 12.087 9.88)" gradientUnits="userSpaceOnUse"><stop class="putwe_b-v"/><stop offset="1" class="mjkm27bdl"/></radialGradient><radialGradient id="iwek3Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71395 .57132 -.08404 -.25211 12.52 8.75)" gradientUnits="userSpaceOnUse"><stop class="luuzb_b1w"/><stop offset="1" class="qol0huy5w"/></radialGradient><radialGradient id="iMsbuWc" cx="0" cy="0" r="1" gradientTransform="matrix(.52981 -1.55632 .38734 .13186 11.845 15.261)" gradientUnits="userSpaceOnUse"><stop class="aj01cwbrd"/><stop offset="1" class="yi12o1v5h"/></radialGradient><radialGradient id="ihOZ0ub" cx="0" cy="0" r="1" gradientTransform="matrix(-.93344 0 0 -1.84091 19.966 15.234)" gradientUnits="userSpaceOnUse"><stop class="boqrvkqhg"/><stop offset="1" class="qmfp0bbmw"/></radialGradient><radialGradient id="iquB4Le" cx="0" cy="0" r="1" gradientTransform="rotate(90 -8.5 16)scale(5.5)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="eiyrnrj6d"/><stop offset="1" class="aew9-4bjd"/></radialGradient><radialGradient id="inoW1He" cx="0" cy="0" r="1" gradientTransform="rotate(118.277 -1.46 13.236)scale(11.3535)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="q57ycabic"/><stop offset="1" class="t983ddcge"/></radialGradient><radialGradient id="i3LE7sA" cx="0" cy="0" r="1" gradientTransform="rotate(90 0 24.5)scale(5.5)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="eiyrnrj6d"/><stop offset="1" class="aew9-4bjd"/></radialGradient><radialGradient id="ieEn1Hb" cx="0" cy="0" r="1" gradientTransform="rotate(144.502 9.817 15.94)scale(7.86919)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="q57ycabic"/><stop offset="1" class="t983ddcge"/></radialGradient><radialGradient id="in2ZioE" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -1.09713 .91216 4.57274 19 23.335)" gradientUnits="userSpaceOnUse"><stop class="iqf_clbnk"/><stop offset="1" class="iq3wm_moz"/></radialGradient><radialGradient id="idzpa6d" cx="0" cy="0" r="1" gradientTransform="rotate(-109.799 16.512 2.004)scale(2.07583 .41284)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="f011s777c"/><stop offset="1" class="igjfipb9d"/></radialGradient><radialGradient id="i5XgIwb" cx="0" cy="0" r="1" gradientTransform="rotate(-130.365 10.311 7.266)scale(2.05069 .52474)" gradientUnits="userSpaceOnUse"><stop class="mj7llcnms"/><stop offset="1" class="z_-3accpr"/></radialGradient><radialGradient id="ij9AkDc" cx="0" cy="0" r="1" gradientTransform="rotate(163.578 11.165 13.71)scale(1.54751 2.9008)" gradientUnits="userSpaceOnUse"><stop class="tav95jljc"/><stop offset="1" class="k_-yzkvuv"/></radialGradient><radialGradient id="ihqSmBe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.46874 -4.00002 4.01735 -5.49243 21.938 26)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="v-biz_c_l"/><stop offset=".952" class="j89_j6b-l"/></radialGradient><radialGradient id="iU59XMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 1.1875 -.99416 -.86336 21.594 12.188)" gradientUnits="userSpaceOnUse"><stop class="qyodacbxi"/><stop offset="1" class="v4xrhm_kz"/></radialGradient><radialGradient id="iD2X8Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94541 0 0 -.34769 14.403 9.45)" gradientUnits="userSpaceOnUse"><stop class="a0qrknfcf"/><stop offset="1" class="uesmb_usg"/></radialGradient><radialGradient id="iO6zBbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8775 0 0 -.82801 15.074 9.5)" gradientUnits="userSpaceOnUse"><stop class="eatmrmb8z"/><stop offset="1" class="vklqhclft"/></radialGradient><radialGradient id="iNzYfdb" cx="0" cy="0" r="1" gradientTransform="rotate(-35.074 47.563 -15.347)scale(1.68907)" gradientUnits="userSpaceOnUse"><stop class="h6622gb-c"/><stop offset="1" class="xlsrl_qfs"/></radialGradient><linearGradient id="i6ipAsd" x1="11.5" x2="11.5" y1="9" y2="16.067" gradientUnits="userSpaceOnUse"><stop class="xfkgtfb2h"/><stop offset="1" class="bsxxumbvo"/></linearGradient><linearGradient id="i3o0tBX" x1="10.537" x2="2.953" y1="21.051" y2="28.541" gradientUnits="userSpaceOnUse"><stop offset=".006" class="h0k59ebfy"/><stop offset="1" class="vqg4nim3l"/></linearGradient><linearGradient id="ig03dLe" x1="27.537" x2="19.953" y1="21.051" y2="28.541" gradientUnits="userSpaceOnUse"><stop offset=".006" class="h0k59ebfy"/><stop offset="1" class="vqg4nim3l"/></linearGradient><linearGradient id="iasie9E" x1="28.259" x2="21.711" y1="20.41" y2="29.412" gradientUnits="userSpaceOnUse"><stop class="owe0rjbtf"/><stop offset=".259" class="bj9sxfqqe"/><stop offset=".759" class="bj9sxfqqe"/><stop offset="1" class="fi8ekh7uu"/></linearGradient><linearGradient id="iUgD1bb" x1="11.15" x2="4.603" y1="20.41" y2="29.412" gradientUnits="userSpaceOnUse"><stop class="owe0rjbtf"/><stop offset=".259" class="bj9sxfqqe"/><stop offset=".759" class="bj9sxfqqe"/><stop offset="1" class="fi8ekh7uu"/></linearGradient><linearGradient id="i2MFcib" x1="8.896" x2="23.063" y1="20.161" y2="20.161" gradientUnits="userSpaceOnUse"><stop class="l7gnvob3s"/><stop offset="1" class="d066n55_r"/></linearGradient><linearGradient id="iutz6pc" x1="22.547" x2="21.969" y1="19.656" y2="20" gradientUnits="userSpaceOnUse"><stop class="ve0i3tyai"/><stop offset="1" class="k4631hb_n"/></linearGradient><linearGradient id="iv3VvUd" x1="21.263" x2="20.948" y1="22.462" y2="24" gradientUnits="userSpaceOnUse"><stop class="aa1yoduhc"/><stop offset="1" class="j5r3228ec"/></linearGradient><linearGradient id="iCmyYKd" x1="13.5" x2="13.5" y1="9.69" y2="10" gradientUnits="userSpaceOnUse"><stop class="nnhvd4obr"/><stop offset="1" class="l5bl2cm-d"/></linearGradient><linearGradient id="iKsNnPc" x1="21.75" x2="19.063" y1="12.656" y2="12.656" gradientUnits="userSpaceOnUse"><stop class="c9_haabgh"/><stop offset="1" class="jwx15zb7h"/></linearGradient><filter id="i4izZYb" width="5.2" height="7.267" x="9" y="8.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.407843 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11430"/></filter><filter id="i9yChVb" width="10.791" height="10.791" x="19.213" y="18.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11430" stdDeviation=".125"/></filter><filter id="iSoI2Tb" width="10.791" height="10.791" x="2.105" y="18.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11430" stdDeviation=".125"/></filter><filter id="iA22FYb" width="18.531" height="10.161" x="6.919" y="14.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.203922 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11430"/></filter><filter id="iRz62Bc" width="10.145" height="4.25" x="16" y="21.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.427451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11430"/></filter><filter id="ip8EgNe" width="4.4" height="2.6" x="17.75" y="11.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.192157 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11430"/></filter><filter id="ig3QMDd" width="3.019" height="1.2" x="18.772" y="12.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11430" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bicycle" /></template>
<style>
.a0qrknfcf {
  stop-color: var(--svg-color--423e47, #423E47);
}

.aa1yoduhc {
  stop-color: var(--svg-color--ffca44, #FFCA44);
}

.aew9-4bjd {
  stop-color: var(--svg-color--dfd2ea, #DFD2EA);
}

.aj01cwbrd {
  stop-color: var(--svg-color--e1c9f8, #E1C9F8);
}

.apn88dn2q {
  stop-color: var(--svg-color--7f7987, #7F7987);
}

.bj9sxfqqe {
  stop-color: var(--svg-color--472e57, #472E57);
  stop-opacity: 0;
}

.boqrvkqhg {
  stop-color: var(--svg-color--e6d6f2, #E6D6F2);
}

.bpu98neqd {
  width: 4px;
  height: 2px;
  x: 17.75px;
  y: 12px;
  rx: 1px;
}

.bsxxumbvo {
  stop-color: var(--svg-color--d1bbe7, #D1BBE7);
}

.c7yi3qnrw {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.5 29.412a5.02 5.02 0 1 0 0-10.04a5.02 5.02 0 0 0 0 10.04");
}

.c9_haabgh {
  stop-color: var(--svg-color--c58677, #C58677);
}

.ccyhfh3vm {
  stop-color: var(--svg-color--b7b5bb, #B7B5BB);
  stop-opacity: 0;
}

.ci9k38iay {
  d: path("M12.5 24.5a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.d066n55_r {
  stop-color: var(--svg-color--ff4c65, #FF4C65);
}

.dwn10t66g {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M24.608 29.412a5.02 5.02 0 1 0 0-10.04a5.02 5.02 0 0 0 0 10.04");
}

.e6ta-hb1r {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m19.266 16.734l.484-3");
}

.eac-tqbua {
  width: 3px;
  height: 1px;
  x: 12px;
  y: 9px;
  rx: 0.5px;
}

.eatmrmb8z {
  stop-color: var(--svg-color--575657, #575657);
}

.eiyrnrj6d {
  stop-color: var(--svg-color--feeeff, #FEEEFF);
}

.f011s777c {
  stop-color: var(--svg-color--9e4049, #9E4049);
}

.fi8ekh7uu {
  stop-color: var(--svg-color--472e57, #472E57);
}

.ft5dv1b6b {
  fill: none;
}

.g9b20ob6u {
  stop-color: var(--svg-color--7c7b7d, #7C7B7D);
  stop-opacity: 0;
}

.h0k59ebfy {
  stop-color: var(--svg-color--2e2060, #2E2060);
}

.h6622gb-c {
  stop-color: var(--svg-color--e7e4ea, #E7E4EA);
}

.i3ui0tbog {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M29.5 24.5a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.igjfipb9d {
  stop-color: var(--svg-color--9e4049, #9E4049);
  stop-opacity: 0;
}

.iq3wm_moz {
  stop-color: var(--svg-color--291c31, #291C31);
  stop-opacity: 0;
}

.iqf_clbnk {
  stop-color: var(--svg-color--291c31, #291C31);
}

.j5r3228ec {
  stop-color: var(--svg-color--ffca44, #FFCA44);
  stop-opacity: 0;
}

.j89_j6b-l {
  stop-color: var(--svg-color--c28849, #C28849);
}

.jwx15zb7h {
  stop-color: var(--svg-color--c58677, #C58677);
  stop-opacity: 0;
}

.jxqbcvb_r {
  fill: var(--svg-color--ffb650, #FFB650);
  d: path("m25 23.401l-6.798-1.383C17.039 21.858 16 22.79 16 24s1.029 2.141 2.202 1.982L25 25.5c.514-.074.895-.52.895-1.05s-.39-.985-.895-1.049");
}

.k_-yzkvuv {
  stop-color: var(--svg-color--ffed66, #FFED66);
  stop-opacity: 0;
}

.k4631hb_n {
  stop-color: var(--svg-color--ff656f, #FF656F);
  stop-opacity: 0;
}

.krh1j1bey {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
  stop-opacity: 0;
}

.l2d19yorl {
  stop-color: var(--svg-color--b7b5bb, #B7B5BB);
}

.l5bl2cm-d {
  stop-color: var(--svg-color--47265f, #47265F);
}

.l7gnvob3s {
  stop-color: var(--svg-color--df3c6d, #DF3C6D);
}

.luuzb_b1w {
  stop-color: var(--svg-color--bdb6c2, #BDB6C2);
}

.m-0xy7bpf {
  stop-color: var(--svg-color--7f7987, #7F7987);
  stop-opacity: 0;
}

.mj7llcnms {
  stop-color: var(--svg-color--ae205b, #AE205B);
}

.mjkm27bdl {
  stop-color: var(--svg-color--a972d4, #A972D4);
  stop-opacity: 0;
}

.ng3fuacxt {
  d: path("m25 23.401l-6.798-1.383C17.039 21.858 16 22.79 16 24s1.029 2.141 2.202 1.982L25 25.5c.514-.074.895-.52.895-1.05s-.39-.985-.895-1.049");
}

.nnhvd4obr {
  stop-color: var(--svg-color--3b2e4c, #3B2E4C);
}

.ohbd59ser {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M12.5 24.5a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.owe0rjbtf {
  stop-color: var(--svg-color--3c4372, #3C4372);
}

.pgvfhrbaa {
  width: 4px;
  height: 2px;
  x: 17.75px;
  y: 12px;
  fill: var(--svg-color--a86f5f, #A86F5F);
  rx: 1px;
}

.putwe_b-v {
  stop-color: var(--svg-color--a972d4, #A972D4);
}

.q57ycabic {
  stop-color: var(--svg-color--c3bac3, #C3BAC3);
  stop-opacity: 0;
}

.qixhejb-r {
  stop-color: var(--svg-color--7c7b7d, #7C7B7D);
}

.qmfp0bbmw {
  stop-color: var(--svg-color--7b6787, #7B6787);
}

.qol0huy5w {
  stop-color: var(--svg-color--bdb6c2, #BDB6C2);
  stop-opacity: 0;
}

.qyodacbxi {
  stop-color: var(--svg-color--c4877a, #C4877A);
}

.t983ddcge {
  stop-color: var(--svg-color--c3bac3, #C3BAC3);
}

.tav95jljc {
  stop-color: var(--svg-color--ffed66, #FFED66);
}

.uesmb_usg {
  stop-color: var(--svg-color--423e47, #423E47);
  stop-opacity: 0;
}

.v-biz_c_l {
  stop-color: var(--svg-color--c28849, #C28849);
  stop-opacity: 0;
}

.v4xrhm_kz {
  stop-color: var(--svg-color--c4877a, #C4877A);
  stop-opacity: 0;
}

.ve0i3tyai {
  stop-color: var(--svg-color--ff656f, #FF656F);
}

.vezk3kihf {
  d: path("M12.03 15.736a.58.58 0 0 0-1.06-.472l-4 9a.58.58 0 0 0 1.06.472l2.56-5.76a.1.1 0 0 1 .154-.037l6.893 5.514a.58.58 0 0 0 .935-.352l1.196-6.782a.05.05 0 0 1 .093-.016l4.205 7.365a.58.58 0 1 0 1.008-.576l-5.07-8.88a.58.58 0 0 0-1.076.187l-1.33 7.536l-6.347-5.078a.2.2 0 0 1-.058-.237z");
}

.vklqhclft {
  stop-color: var(--svg-color--575657, #575657);
  stop-opacity: 0;
}

.vqg4nim3l {
  stop-color: var(--svg-color--411461, #411461);
}

.vv-wr2wwj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.172 12.656h2.219");
}

.wtyonjtjn {
  d: path("M29.5 24.5a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.wzldrlipv {
  d: path("M18 25a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.xfkgtfb2h {
  stop-color: var(--svg-color--b5a5c6, #B5A5C6);
}

.xlsrl_qfs {
  stop-color: var(--svg-color--cdc3d9, #CDC3D9);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.yi12o1v5h {
  stop-color: var(--svg-color--e1c9f8, #E1C9F8);
  stop-opacity: 0;
}

.z_-3accpr {
  stop-color: var(--svg-color--ae205b, #AE205B);
  stop-opacity: 0;
}

.zjr7_gbdk {
  d: path("M14 9.5a.5.5 0 0 0-.5-.5h-2A2.5 2.5 0 0 0 9 11.5c0 1.37 1.101 2.42 2.425 2.496c.071.004.12.077.092.143l-.51 1.193a.528.528 0 1 0 .97.414l.617-1.443a.5.5 0 0 1 .46-.303h.05a.5.5 0 0 0 0-1H11.5a1.5 1.5 0 0 1 0-3h2a.5.5 0 0 0 .5-.5");
}

</style>
