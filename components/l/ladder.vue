<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPqZJwe)"><path fill="url(#iwluT0c)" class="lnubocbig"/><path fill="url(#iySl78d)" class="lnubocbig"/><path fill="url(#iV6hXAK)" class="lnubocbig"/><path fill="url(#itpvMPb)" class="lnubocbig"/></g><g filter="url(#iufFfhe)"><path fill="url(#i82e6Pb)" class="xjb9uiqem"/></g><g filter="url(#i73b57d)"><path fill="url(#iPxiJNb)" class="ir17o9l1f"/></g><g filter="url(#icAS8bd)"><path fill="url(#ilrY7Vb)" class="w7r90h5nc"/></g><g filter="url(#ixTiHRc)"><path fill="url(#i2crhZm)" class="jsnh03buh"/></g><path fill="url(#iWJBHdb)" class="o5_j9fboo"/><path fill="url(#iYDtoOH)" class="o5_j9fboo"/><path fill="url(#i43vyXT)" class="o5_j9fboo"/><path fill="url(#ixZj5Ib)" class="o5_j9fboo"/><path fill="url(#i4pu46b)" class="vizzb0_au"/><path fill="url(#iFU0ide)" class="vizzb0_au"/><path fill="url(#ibPnhjd)" class="vizzb0_au"/><path fill="url(#ihp5dMc)" class="vizzb0_au"/><path fill="url(#i7bhxcb)" class="pedr1edor"/><path fill="url(#iHiLINd)" class="pedr1edor"/><path fill="url(#iZWPc4c)" class="pedr1edor"/><path fill="url(#iv7BUUd)" class="pedr1edor"/><path fill="url(#ieQb4HZ)" class="li6axkv_n"/><path fill="url(#il7wYxb)" class="li6axkv_n"/><path fill="url(#i7Dap2c)" class="li6axkv_n"/><path fill="url(#i3IbhQb)" class="li6axkv_n"/><g filter="url(#iLYt6kq)"><path fill="url(#iMtjWOd)" class="cl-equ8vo"/><path fill="url(#iT6uBee)" class="cl-equ8vo"/><path fill="url(#iVlwmqe)" class="cl-equ8vo"/></g><defs><linearGradient id="iwluT0c" x1="4.375" x2="11.181" y1="9.378" y2="19.586" gradientUnits="userSpaceOnUse"><stop class="y21eb6bvc"/><stop offset="1" class="p3deyub5c"/></linearGradient><linearGradient id="iV6hXAK" x1="11.704" x2="11.704" y1="2.078" y2="3.358" gradientUnits="userSpaceOnUse"><stop offset=".202" class="z04k91bwf"/><stop offset="1" class="uwcqd70kg"/></linearGradient><linearGradient id="itpvMPb" x1="9.651" x2="5.714" y1="26.422" y2="25.172" gradientUnits="userSpaceOnUse"><stop offset=".291" class="eez9e_zgq"/><stop offset="1" class="i-ne55b6v"/></linearGradient><linearGradient id="i82e6Pb" x1="11.827" x2="12.114" y1="7.031" y2="8.816" gradientUnits="userSpaceOnUse"><stop class="q3vu3dbsx"/><stop offset="1" class="vpxk3bczq"/></linearGradient><linearGradient id="iPxiJNb" x1="9.968" x2="10.254" y1="13.986" y2="15.771" gradientUnits="userSpaceOnUse"><stop class="q3vu3dbsx"/><stop offset="1" class="vpxk3bczq"/></linearGradient><linearGradient id="ilrY7Vb" x1="8.265" x2="8.551" y1="20.941" y2="22.726" gradientUnits="userSpaceOnUse"><stop class="q3vu3dbsx"/><stop offset="1" class="vpxk3bczq"/></linearGradient><linearGradient id="i2crhZm" x1="6.39" x2="6.676" y1="27.844" y2="29.628" gradientUnits="userSpaceOnUse"><stop class="q3vu3dbsx"/><stop offset="1" class="vpxk3bczq"/></linearGradient><linearGradient id="iWJBHdb" x1="12.129" x2="24.317" y1="6.455" y2="6.455" gradientUnits="userSpaceOnUse"><stop class="dtwcfacdl"/><stop offset="1" class="jpow9bbsz"/></linearGradient><linearGradient id="iYDtoOH" x1="17.849" x2="17.849" y1="3.766" y2="4.328" gradientUnits="userSpaceOnUse"><stop class="hh52x1bsl"/><stop offset="1" class="v461c75ez"/></linearGradient><linearGradient id="i43vyXT" x1="10.537" x2="11.216" y1="5.848" y2="6.045" gradientUnits="userSpaceOnUse"><stop class="pkrm_2bih"/><stop offset="1" class="bjwfmp3pv"/></linearGradient><linearGradient id="ixZj5Ib" x1="19.87" x2="19.87" y1="7.023" y2="6.516" gradientUnits="userSpaceOnUse"><stop class="wid3jrdpg"/><stop offset="1" class="z15urfbrq"/></linearGradient><linearGradient id="i4pu46b" x1="10.247" x2="22.506" y1="13.37" y2="13.37" gradientUnits="userSpaceOnUse"><stop class="dtwcfacdl"/><stop offset="1" class="jpow9bbsz"/></linearGradient><linearGradient id="iFU0ide" x1="16" x2="16" y1="10.68" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="hh52x1bsl"/><stop offset="1" class="v461c75ez"/></linearGradient><linearGradient id="ibPnhjd" x1="8.646" x2="9.328" y1="12.763" y2="12.962" gradientUnits="userSpaceOnUse"><stop class="pkrm_2bih"/><stop offset="1" class="bjwfmp3pv"/></linearGradient><linearGradient id="ihp5dMc" x1="18.033" x2="18.033" y1="13.937" y2="13.43" gradientUnits="userSpaceOnUse"><stop class="wid3jrdpg"/><stop offset="1" class="z15urfbrq"/></linearGradient><linearGradient id="i7bhxcb" x1="8.491" x2="20.75" y1="20.382" y2="20.382" gradientUnits="userSpaceOnUse"><stop class="dtwcfacdl"/><stop offset="1" class="jpow9bbsz"/></linearGradient><linearGradient id="iHiLINd" x1="14.244" x2="14.244" y1="17.693" y2="18.255" gradientUnits="userSpaceOnUse"><stop class="hh52x1bsl"/><stop offset="1" class="v461c75ez"/></linearGradient><linearGradient id="iZWPc4c" x1="6.89" x2="7.572" y1="19.775" y2="19.975" gradientUnits="userSpaceOnUse"><stop class="pkrm_2bih"/><stop offset="1" class="bjwfmp3pv"/></linearGradient><linearGradient id="iv7BUUd" x1="16.277" x2="16.277" y1="20.95" y2="20.443" gradientUnits="userSpaceOnUse"><stop class="wid3jrdpg"/><stop offset="1" class="z15urfbrq"/></linearGradient><linearGradient id="ieQb4HZ" x1="6.692" x2="18.95" y1="27.33" y2="27.33" gradientUnits="userSpaceOnUse"><stop class="dtwcfacdl"/><stop offset="1" class="jpow9bbsz"/></linearGradient><linearGradient id="il7wYxb" x1="12.445" x2="12.445" y1="24.64" y2="25.202" gradientUnits="userSpaceOnUse"><stop class="hh52x1bsl"/><stop offset="1" class="v461c75ez"/></linearGradient><linearGradient id="i7Dap2c" x1="5.091" x2="5.773" y1="26.722" y2="26.922" gradientUnits="userSpaceOnUse"><stop class="pkrm_2bih"/><stop offset="1" class="bjwfmp3pv"/></linearGradient><linearGradient id="i3IbhQb" x1="14.477" x2="14.477" y1="27.897" y2="27.39" gradientUnits="userSpaceOnUse"><stop class="wid3jrdpg"/><stop offset="1" class="z15urfbrq"/></linearGradient><linearGradient id="iMtjWOd" x1="20.036" x2="26.842" y1="9.378" y2="19.586" gradientUnits="userSpaceOnUse"><stop class="y21eb6bvc"/><stop offset="1" class="p3deyub5c"/></linearGradient><linearGradient id="iVlwmqe" x1="27.365" x2="27.365" y1="2.078" y2="3.358" gradientUnits="userSpaceOnUse"><stop offset=".202" class="z04k91bwf"/><stop offset="1" class="uwcqd70kg"/></linearGradient><filter id="iPqZJwe" width="13.121" height="28.244" x="1.818" y="1.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.239216 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24814"/></filter><filter id="iufFfhe" width="3.477" height="3.359" x="10.019" y="6.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24814" stdDeviation=".25"/></filter><filter id="i73b57d" width="3.477" height="3.359" x="8.159" y="13.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24814" stdDeviation=".25"/></filter><filter id="icAS8bd" width="3.477" height="3.359" x="6.456" y="20.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24814" stdDeviation=".25"/></filter><filter id="ixTiHRc" width="3.477" height="3.359" x="4.581" y="26.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24814" stdDeviation=".25"/></filter><filter id="iLYt6kq" width="13.121" height="28.244" x="17.479" y="1.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.239216 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24814"/></filter><radialGradient id="iySl78d" cx="0" cy="0" r="1" gradientTransform="rotate(-164.358 6.178 13.218)scale(2.2651 11.5372)" gradientUnits="userSpaceOnUse"><stop class="p3deyub5c"/><stop offset="1" class="a4vojkbft"/></radialGradient><radialGradient id="iT6uBee" cx="0" cy="0" r="1" gradientTransform="rotate(-164.358 14.009 12.143)scale(2.2651 11.5372)" gradientUnits="userSpaceOnUse"><stop class="p3deyub5c"/><stop offset="1" class="a4vojkbft"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ladder" /></template>
<style>
.a4vojkbft {
  stop-color: var(--svg-color--7a4d49, #7A4D49);
  stop-opacity: 0;
}

.bjwfmp3pv {
  stop-color: var(--svg-color--965d4d, #965D4D);
  stop-opacity: 0;
}

.cl-equ8vo {
  d: path("M24.26 2.978a1.2 1.2 0 0 1 1.162-.9h3.728a.65.65 0 0 1 .629.813l-6.76 26.131a1.2 1.2 0 0 1-1.162.9H18.13a.65.65 0 0 1-.63-.813z");
}

.dtwcfacdl {
  stop-color: var(--svg-color--945b4b, #945B4B);
}

.eez9e_zgq {
  stop-color: var(--svg-color--6a4038, #6A4038);
}

.ft5dv1b6b {
  fill: none;
}

.hh52x1bsl {
  stop-color: var(--svg-color--9f684b, #9F684B);
}

.i-ne55b6v {
  stop-color: var(--svg-color--6a4038, #6A4038);
  stop-opacity: 0;
}

.ir17o9l1f {
  d: path("m10.406 15.94l-1.747-2.258l2.477-.102z");
}

.jpow9bbsz {
  stop-color: var(--svg-color--753e2d, #753E2D);
}

.jsnh03buh {
  d: path("M6.828 29.797L5.08 27.539l2.477-.102z");
}

.li6axkv_n {
  d: path("M5.614 25.23a.5.5 0 0 1 .485-.376h13.854v3.043H5.322a.3.3 0 0 1-.29-.374z");
}

.lnubocbig {
  d: path("M8.6 2.978a1.2 1.2 0 0 1 1.161-.9h3.728a.65.65 0 0 1 .629.813l-6.76 26.131a1.2 1.2 0 0 1-1.162.9H2.468a.65.65 0 0 1-.629-.813z");
}

.o5_j9fboo {
  d: path("M10.976 4.356a.5.5 0 0 1 .484-.376h13.855v3.043H10.683a.3.3 0 0 1-.29-.374z");
}

.p3deyub5c {
  stop-color: var(--svg-color--7a4d49, #7A4D49);
}

.pedr1edor {
  d: path("M7.414 18.283a.5.5 0 0 1 .484-.376h13.855v3.043H7.121a.3.3 0 0 1-.29-.374z");
}

.pkrm_2bih {
  stop-color: var(--svg-color--78402d, #78402D);
}

.q3vu3dbsx {
  stop-color: var(--svg-color--592d2b, #592D2B);
}

.uwcqd70kg {
  stop-color: var(--svg-color--956455, #956455);
  stop-opacity: 0;
}

.v461c75ez {
  stop-color: var(--svg-color--9f684b, #9F684B);
  stop-opacity: 0;
}

.vizzb0_au {
  d: path("M9.17 11.27a.5.5 0 0 1 .484-.376H23.51v3.043H8.877a.3.3 0 0 1-.29-.374z");
}

.vpxk3bczq {
  stop-color: var(--svg-color--592d2b, #592D2B);
  stop-opacity: 0;
}

.w7r90h5nc {
  d: path("m8.703 22.894l-1.747-2.257l2.477-.102z");
}

.wid3jrdpg {
  stop-color: var(--svg-color--653036, #653036);
}

.xjb9uiqem {
  d: path("M12.265 8.984L10.52 6.727l2.476-.102z");
}

.y21eb6bvc {
  stop-color: var(--svg-color--915f51, #915F51);
}

.z04k91bwf {
  stop-color: var(--svg-color--9f705f, #9F705F);
}

.z15urfbrq {
  stop-color: var(--svg-color--844849, #844849);
  stop-opacity: 0;
}

</style>
