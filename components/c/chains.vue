<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isGxpib)"><rect stroke="url(#iBcF4Tc)" class="pk9cx6bfl"/></g><g filter="url(#iSA3ctd)"><rect stroke="url(#iBLFACe)" class="f72gm0r_z"/><rect stroke="url(#iC67yLe)" class="f72gm0r_z"/></g><g filter="url(#iPtEy0b)"><rect stroke="url(#iTHYGVb)" class="jrfguaclk"/></g><g filter="url(#itpAIRw)"><rect stroke="url(#ia3tsAc)" class="u3opaxbsy"/><rect stroke="url(#ixLAb7b)" class="u3opaxbsy"/></g><g filter="url(#ivBnLFb)"><rect stroke="url(#iEEdbTc)" class="tawgxgbsf"/></g><g filter="url(#iVdMdoe)"><rect stroke="url(#iQ6ppud)" class="d6hvrgbna"/><rect stroke="url(#iRNJIdc)" class="d6hvrgbna"/></g><path fill="url(#iRpWHKe)" class="o9w8xibop"/><path fill="url(#iSB9XLe)" class="o9w8xibop"/><path fill="url(#imViaxc)" class="o9w8xibop"/><path fill="url(#ibBlveb)" class="o9w8xibop"/><path fill="url(#iKmHCCc)" class="o9w8xibop"/><path fill="url(#iqRWA7c)" class="pwfrwr6vx"/><path fill="url(#i3xfyEc)" class="pwfrwr6vx"/><path fill="url(#ikhpaYd)" class="pwfrwr6vx"/><path fill="url(#iTANAJd)" class="pwfrwr6vx"/><path fill="url(#i9dYY4b)" class="pwfrwr6vx"/><path fill="url(#iV1gyQc)" class="pwfrwr6vx"/><path fill="url(#i276qqd)" class="pwfrwr6vx"/><path fill="url(#ipocTob)" class="p62xjb_nz"/><path fill="url(#ioEVdce)" class="p62xjb_nz"/><path fill="url(#iZjuXtT)" class="p62xjb_nz"/><path fill="url(#i1aAfrO)" class="yj6zigb3p"/><path fill="url(#ilyHXzb)" class="yj6zigb3p"/><path fill="url(#ijtO5gc)" class="yj6zigb3p"/><path fill="url(#iyEE0lb)" class="mqaabbwlv"/><path fill="url(#iki4zXb)" class="mqaabbwlv"/><path fill="url(#ivbXoqc)" class="mqaabbwlv"/><path fill="url(#i50oM3b)" class="mqaabbwlv"/><g filter="url(#iCTzYeS)"><path stroke="url(#ij46ncd)" class="ssrealbwc"/><path stroke="url(#iLpMceb)" class="ssrealbwc"/></g><path fill="url(#iz8MERc)" class="eq1mp9kyq"/><path fill="url(#ix252lb)" class="eq1mp9kyq"/><path fill="url(#iCfXXmc)" class="eq1mp9kyq"/><path fill="url(#i61QsWd)" class="eq1mp9kyq"/><g filter="url(#ishZhnE)"><path stroke="url(#iMi8q0b)" class="as5bymgwi"/><path stroke="url(#iAzPlme)" class="as5bymgwi"/></g><path fill="url(#iTIBrYc)" class="fpmv_i9zs"/><path fill="url(#iGIahxe)" class="fpmv_i9zs"/><path fill="url(#i0CDacb)" class="fpmv_i9zs"/><defs><radialGradient id="iSB9XLe" cx="0" cy="0" r="1" gradientTransform="rotate(125.848 4.66 3.77)scale(6.74584 7.38164)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="ywv43ac4a"/><stop offset="1" class="wpg65xr7s"/></radialGradient><radialGradient id="imViaxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.87791 -2.36137 0 4.296 1.78)" gradientUnits="userSpaceOnUse"><stop class="b7cyikb-t"/><stop offset="1" class="kubdf2y5u"/></radialGradient><radialGradient id="ibBlveb" cx="0" cy="0" r="1" gradientTransform="rotate(125.218 4.653 3.806)scale(7.032 7.96753)" gradientUnits="userSpaceOnUse"><stop offset=".896" class="ywv43ac4a"/><stop offset="1" class="y_x0gep_a"/></radialGradient><radialGradient id="iKmHCCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.27799 -2.35465 0 11.413 1.676)" gradientUnits="userSpaceOnUse"><stop class="f0m4hrbdx"/><stop offset="1" class="c4nlelbgu"/></radialGradient><radialGradient id="i3xfyEc" cx="0" cy="0" r="1" gradientTransform="rotate(-54.152 32.594 8.128)scale(6.74584 7.38164)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="ywv43ac4a"/><stop offset="1" class="wpg65xr7s"/></radialGradient><radialGradient id="ikhpaYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.78051 1.80872 0 10.863 30.023)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="b7cyikb-t"/><stop offset="1" class="kubdf2y5u"/></radialGradient><radialGradient id="iTANAJd" cx="0" cy="0" r="1" gradientTransform="matrix(4.05524 -5.74492 6.50922 4.59474 6.917 29.788)" gradientUnits="userSpaceOnUse"><stop offset=".896" class="ywv43ac4a"/><stop offset="1" class="y_x0gep_a"/></radialGradient><radialGradient id="i9dYY4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.27799 2.35465 0 5.95 30.311)" gradientUnits="userSpaceOnUse"><stop class="f0m4hrbdx"/><stop offset="1" class="c4nlelbgu"/></radialGradient><radialGradient id="iV1gyQc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.75872 0 0 -8.82408 12.695 29.696)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="l8dqi677w"/><stop offset="1" class="gshlwybdx"/></radialGradient><radialGradient id="i276qqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.29651 -2.51753 0 7.279 27.682)" gradientUnits="userSpaceOnUse"><stop class="qti_vnbjy"/><stop offset="1" class="lqz6b8bwx"/></radialGradient><radialGradient id="ioEVdce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.37791 4.90329 0 8.681 27.937)" gradientUnits="userSpaceOnUse"><stop class="u1v-8jbga"/><stop offset="1" class="ln0astbwj"/></radialGradient><radialGradient id="iZjuXtT" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.9186 -1.30438 0 9.686 19.695)" gradientUnits="userSpaceOnUse"><stop class="b0_t7yb7p"/><stop offset="1" class="cthxzdbxn"/></radialGradient><radialGradient id="ilyHXzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.37791 4.90329 0 22.678 20.918)" gradientUnits="userSpaceOnUse"><stop class="u1v-8jbga"/><stop offset="1" class="ln0astbwj"/></radialGradient><radialGradient id="ijtO5gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.9186 -1.30438 0 23.683 12.676)" gradientUnits="userSpaceOnUse"><stop class="b0_t7yb7p"/><stop offset="1" class="cthxzdbxn"/></radialGradient><radialGradient id="iyEE0lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.78779 2.6978 0 22.009 30.036)" gradientUnits="userSpaceOnUse"><stop class="i4rzwgbxm"/><stop offset="1" class="uq1vt6bxb"/></radialGradient><radialGradient id="iki4zXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.13953 -1.3237 0 23.552 27.446)" gradientUnits="userSpaceOnUse"><stop class="xe2dx2b-y"/><stop offset="1" class="sy3a7kbgq"/></radialGradient><radialGradient id="ivbXoqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.49855 .6196 0 21.127 30.337)" gradientUnits="userSpaceOnUse"><stop class="wabtttuxy"/><stop offset="1" class="zvj0vmb3h"/></radialGradient><radialGradient id="ij46ncd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28197 -1.22965 2.73285 2.84914 5.788 5.757)" gradientUnits="userSpaceOnUse"><stop class="jk7hiz_7e"/><stop offset="1" class="b4d_dsbbs"/></radialGradient><radialGradient id="iLpMceb" cx="0" cy="0" r="1" gradientTransform="rotate(131.828 5.554 4.383)scale(3.5111 6.7823)" gradientUnits="userSpaceOnUse"><stop class="dg4tn5bbr"/><stop offset="1" class="s4dgkod2u"/></radialGradient><radialGradient id="ix252lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33647 1.7682 0 22.678 7.085)" gradientUnits="userSpaceOnUse"><stop offset=".089" class="uutqfntoy"/><stop offset="1" class="u_cvn40sq"/></radialGradient><radialGradient id="iCfXXmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.10327 -.4888 0 21.127 1.581)" gradientUnits="userSpaceOnUse"><stop class="ejpad0x-n"/><stop offset="1" class="wv70prcol"/></radialGradient><radialGradient id="i61QsWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41279 0 0 -.1646 23.67 1.715)" gradientUnits="userSpaceOnUse"><stop class="p2q3slxqh"/><stop offset="1" class="t_wf0vbfn"/></radialGradient><radialGradient id="iMi8q0b" cx="0" cy="0" r="1" gradientTransform="rotate(133.276 .14 15.622)scale(1.68893 3.75004)" gradientUnits="userSpaceOnUse"><stop class="jk7hiz_7e"/><stop offset="1" class="b4d_dsbbs"/></radialGradient><radialGradient id="iAzPlme" cx="0" cy="0" r="1" gradientTransform="matrix(2.1147 -2.61628 4.97188 4.01871 5.526 28.82)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="dg4tn5bbr"/><stop offset="1" class="s4dgkod2u"/></radialGradient><radialGradient id="iGIahxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.37791 4.90329 0 8.681 13.79)" gradientUnits="userSpaceOnUse"><stop class="u1v-8jbga"/><stop offset="1" class="ln0astbwj"/></radialGradient><radialGradient id="i0CDacb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.9186 -1.30438 0 9.686 5.548)" gradientUnits="userSpaceOnUse"><stop class="b0_t7yb7p"/><stop offset="1" class="cthxzdbxn"/></radialGradient><linearGradient id="iBcF4Tc" x1="18.843" x2="23.75" y1="19.265" y2="24.597" gradientUnits="userSpaceOnUse"><stop class="n37vbxi6a"/><stop offset="1" class="agoi5kpvc"/></linearGradient><linearGradient id="iBLFACe" x1="28.314" x2="22.504" y1="18.237" y2="24.371" gradientUnits="userSpaceOnUse"><stop class="hokpuib7w"/><stop offset="1" class="atesu6b7b"/></linearGradient><linearGradient id="iC67yLe" x1="18.843" x2="21.302" y1="24.213" y2="24.213" gradientUnits="userSpaceOnUse"><stop class="pcwgiubrz"/><stop offset="1" class="j47-qibrs"/></linearGradient><linearGradient id="iTHYGVb" x1="18.843" x2="23.75" y1="5.157" y2="10.489" gradientUnits="userSpaceOnUse"><stop class="n37vbxi6a"/><stop offset="1" class="agoi5kpvc"/></linearGradient><linearGradient id="ia3tsAc" x1="28.314" x2="22.579" y1="4.255" y2="10.384" gradientUnits="userSpaceOnUse"><stop class="hokpuib7w"/><stop offset="1" class="atesu6b7b"/></linearGradient><linearGradient id="ixLAb7b" x1="18.843" x2="21.302" y1="10.157" y2="10.157" gradientUnits="userSpaceOnUse"><stop class="pcwgiubrz"/><stop offset="1" class="j47-qibrs"/></linearGradient><linearGradient id="iEEdbTc" x1="4.846" x2="9.817" y1="12.272" y2="17.609" gradientUnits="userSpaceOnUse"><stop class="n37vbxi6a"/><stop offset="1" class="agoi5kpvc"/></linearGradient><linearGradient id="iQ6ppud" x1="14.317" x2="8.493" y1="11.332" y2="17.467" gradientUnits="userSpaceOnUse"><stop class="hokpuib7w"/><stop offset="1" class="atesu6b7b"/></linearGradient><linearGradient id="iRNJIdc" x1="4.846" x2="7.305" y1="17.322" y2="17.322" gradientUnits="userSpaceOnUse"><stop class="pcwgiubrz"/><stop offset="1" class="j47-qibrs"/></linearGradient><linearGradient id="iRpWHKe" x1="5.003" x2="12.695" y1="4.954" y2="4.954" gradientUnits="userSpaceOnUse"><stop offset=".241" class="k2vurib-f"/><stop offset="1" class="s_8bwbbxs"/></linearGradient><linearGradient id="iqRWA7c" x1="12.359" x2="4.667" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop offset=".241" class="k2vurib-f"/><stop offset="1" class="kb343tbpx"/></linearGradient><linearGradient id="ipocTob" x1="8.681" x2="8.681" y1="18.039" y2="28.273" gradientUnits="userSpaceOnUse"><stop class="phjfa3qvr"/><stop offset="1" class="zej7zybcv"/></linearGradient><linearGradient id="i1aAfrO" x1="22.678" x2="22.678" y1="11.02" y2="21.254" gradientUnits="userSpaceOnUse"><stop class="phjfa3qvr"/><stop offset="1" class="zej7zybcv"/></linearGradient><linearGradient id="i50oM3b" x1="23.585" x2="23.585" y1="30.337" y2="30.139" gradientUnits="userSpaceOnUse"><stop class="qa65aesje"/><stop offset="1" class="avta81byy"/></linearGradient><linearGradient id="iz8MERc" x1="21.485" x2="24.625" y1="4.972" y2="5.025" gradientUnits="userSpaceOnUse"><stop class="n9zr5ubwp"/><stop offset="1" class="i89dh4bfm"/></linearGradient><linearGradient id="iTIBrYc" x1="8.681" x2="8.681" y1="3.891" y2="14.125" gradientUnits="userSpaceOnUse"><stop class="phjfa3qvr"/><stop offset="1" class="zej7zybcv"/></linearGradient><filter id="isGxpib" width="10.112" height="14.753" x="17.622" y="15.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.411765 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24669"/></filter><filter id="iSA3ctd" width="9.312" height="13.398" x="18.022" y="16.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24669" stdDeviation=".3"/></filter><filter id="iPtEy0b" width="10.112" height="14.753" x="17.622" y="1.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.411765 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24669"/></filter><filter id="itpAIRw" width="9.312" height="13.261" x="18.022" y="2.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24669" stdDeviation=".3"/></filter><filter id="ivBnLFb" width="10.112" height="14.884" x="3.625" y="8.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.411765 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24669"/></filter><filter id="iVdMdoe" width="9.312" height="13.424" x="4.025" y="9.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24669" stdDeviation=".3"/></filter><filter id="iCTzYeS" width="9.312" height="5.382" x="4.313" y="2.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24669" stdDeviation=".3"/></filter><filter id="ishZhnE" width="8.623" height="5.552" x="4.426" y="24.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24669" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chains" /></template>
<style>
.agoi5kpvc {
  stop-color: var(--svg-color--827a8c, #827A8C);
}

.as5bymgwi {
  d: path("M11.949 29.37v-.483c0-1.767-1.294-3.2-2.89-3.2h-.643c-1.596 0-2.89 1.433-2.89 3.2v.652");
}

.atesu6b7b {
  stop-color: var(--svg-color--b9b2c1, #B9B2C1);
  stop-opacity: 0;
}

.avta81byy {
  stop-color: var(--svg-color--a385c0, #A385C0);
  stop-opacity: 0;
}

.b0_t7yb7p {
  stop-color: var(--svg-color--d3cdda, #D3CDDA);
}

.b4d_dsbbs {
  stop-color: var(--svg-color--b8b3be, #B8B3BE);
  stop-opacity: 0;
}

.b7cyikb-t {
  stop-color: var(--svg-color--867f8f, #867F8F);
}

.c4nlelbgu {
  stop-color: var(--svg-color--b0a8b9, #B0A8B9);
  stop-opacity: 0;
}

.cthxzdbxn {
  stop-color: var(--svg-color--c7c2cc, #C7C2CC);
  stop-opacity: 0;
}

.d6hvrgbna {
  width: 7.112px;
  height: 11.224px;
  x: 5.125px;
  y: 10.388px;
  rx: 3.2px;
}

.dg4tn5bbr {
  stop-color: var(--svg-color--d3c9dd, #D3C9DD);
}

.ejpad0x-n {
  stop-color: var(--svg-color--b6b0bc, #B6B0BC);
}

.eq1mp9kyq {
  d: path("M22.678 7.085a1.55 1.55 0 0 1-1.55-1.55V1.73a.15.15 0 0 1 .15-.15h2.8a.15.15 0 0 1 .15.15v3.803a1.55 1.55 0 0 1-1.55 1.551");
}

.f0m4hrbdx {
  stop-color: var(--svg-color--b0a8b9, #B0A8B9);
}

.f72gm0r_z {
  width: 7.112px;
  height: 11.198px;
  x: 19.122px;
  y: 17.295px;
  rx: 3.2px;
}

.fpmv_i9zs {
  d: path("M7.13 5.442a1.55 1.55 0 0 1 3.102 0v7.133a1.55 1.55 0 0 1-3.102 0z");
}

.ft5dv1b6b {
  fill: none;
}

.gshlwybdx {
  stop-color: var(--svg-color--d7cee0, #D7CEE0);
}

.hokpuib7w {
  stop-color: var(--svg-color--b9b2c1, #B9B2C1);
}

.i4rzwgbxm {
  stop-color: var(--svg-color--a694ba, #A694BA);
}

.i89dh4bfm {
  stop-color: var(--svg-color--c2b9cd, #C2B9CD);
}

.j47-qibrs {
  stop-color: var(--svg-color--b4a9c0, #B4A9C0);
  stop-opacity: 0;
}

.jk7hiz_7e {
  stop-color: var(--svg-color--b8b3be, #B8B3BE);
}

.jrfguaclk {
  width: 7.112px;
  height: 10.753px;
  x: 19.122px;
  y: 3.632px;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  rx: 3.2px;
}

.k2vurib-f {
  stop-color: var(--svg-color--a4a0a9, #A4A0A9);
}

.kb343tbpx {
  stop-color: var(--svg-color--bfabd3, #BFABD3);
}

.kubdf2y5u {
  stop-color: var(--svg-color--867f8f, #867F8F);
  stop-opacity: 0;
}

.l8dqi677w {
  stop-color: var(--svg-color--d7cee0, #D7CEE0);
  stop-opacity: 0;
}

.ln0astbwj {
  stop-color: var(--svg-color--8b7e99, #8B7E99);
  stop-opacity: 0;
}

.lqz6b8bwx {
  stop-color: var(--svg-color--ba9cd8, #BA9CD8);
  stop-opacity: 0;
}

.mqaabbwlv {
  d: path("M22.678 24.834a1.55 1.55 0 0 0-1.55 1.55v3.803c0 .083.067.15.15.15h2.8a.15.15 0 0 0 .15-.15v-3.803a1.55 1.55 0 0 0-1.55-1.55");
}

.n37vbxi6a {
  stop-color: var(--svg-color--beb2ca, #BEB2CA);
}

.n9zr5ubwp {
  stop-color: var(--svg-color--a397ae, #A397AE);
}

.o9w8xibop {
  d: path("M3.775 1.964a.15.15 0 0 0-.15.15v1.13a4.7 4.7 0 0 0 4.7 4.7h.712a4.7 4.7 0 0 0 4.7-4.7v-1.13a.15.15 0 0 0-.15-.15h-2.7a.15.15 0 0 0-.15.15v1.13a1.7 1.7 0 0 1-1.7 1.7h-.712a1.7 1.7 0 0 1-1.7-1.7v-1.13a.15.15 0 0 0-.15-.15z");
}

.p2q3slxqh {
  stop-color: var(--svg-color--c7c0cd, #C7C0CD);
}

.p62xjb_nz {
  d: path("M7.13 19.59a1.55 1.55 0 1 1 3.102 0v7.132a1.55 1.55 0 1 1-3.102 0z");
}

.pcwgiubrz {
  stop-color: var(--svg-color--b4a9c0, #B4A9C0);
}

.phjfa3qvr {
  stop-color: var(--svg-color--c8c4cc, #C8C4CC);
}

.pk9cx6bfl {
  width: 7.112px;
  height: 10.753px;
  x: 19.122px;
  y: 17.74px;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  rx: 3.2px;
}

.pwfrwr6vx {
  d: path("M13.587 30.023a.15.15 0 0 0 .15-.15v-1.13a4.7 4.7 0 0 0-4.7-4.7h-.712a4.7 4.7 0 0 0-4.7 4.7v1.13c0 .083.067.15.15.15h2.7a.15.15 0 0 0 .15-.15v-1.13a1.7 1.7 0 0 1 1.7-1.7h.712a1.7 1.7 0 0 1 1.7 1.7v1.13c0 .083.067.15.15.15z");
}

.qa65aesje {
  stop-color: var(--svg-color--a385c0, #A385C0);
}

.qti_vnbjy {
  stop-color: var(--svg-color--ba9cd8, #BA9CD8);
}

.s_8bwbbxs {
  stop-color: var(--svg-color--d6c8e5, #D6C8E5);
}

.s4dgkod2u {
  stop-color: var(--svg-color--d3c9dd, #D3C9DD);
  stop-opacity: 0;
}

.ssrealbwc {
  d: path("M12.525 3.1a3.2 3.2 0 0 1-3.2 3.2h-.712a3.2 3.2 0 0 1-3.2-3.2v-.482");
}

.sy3a7kbgq {
  stop-color: var(--svg-color--c3bace, #C3BACE);
  stop-opacity: 0;
}

.t_wf0vbfn {
  stop-color: var(--svg-color--c7c0cd, #C7C0CD);
  stop-opacity: 0;
}

.tawgxgbsf {
  width: 7.112px;
  height: 10.884px;
  x: 5.125px;
  y: 10.728px;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  rx: 3.2px;
}

.u_cvn40sq {
  stop-color: var(--svg-color--b4a0ca, #B4A0CA);
  stop-opacity: 0;
}

.u1v-8jbga {
  stop-color: var(--svg-color--7e6893, #7E6893);
}

.u3opaxbsy {
  width: 7.112px;
  height: 11.06px;
  x: 19.122px;
  y: 3.324px;
  rx: 3.2px;
}

.uq1vt6bxb {
  stop-color: var(--svg-color--bcb4c4, #BCB4C4);
}

.uutqfntoy {
  stop-color: var(--svg-color--b4a0ca, #B4A0CA);
}

.wabtttuxy {
  stop-color: var(--svg-color--b0a2be, #B0A2BE);
}

.wpg65xr7s {
  stop-color: var(--svg-color--9a8da8, #9A8DA8);
}

.wv70prcol {
  stop-color: var(--svg-color--b6b0bc, #B6B0BC);
  stop-opacity: 0;
}

.xe2dx2b-y {
  stop-color: var(--svg-color--d8d0e2, #D8D0E2);
}

.y_x0gep_a {
  stop-color: var(--svg-color--b3abbc, #B3ABBC);
}

.yj6zigb3p {
  d: path("M21.127 12.57a1.55 1.55 0 0 1 3.102 0v7.133a1.55 1.55 0 0 1-3.102 0z");
}

.ywv43ac4a {
  stop-color: var(--svg-color--9a8da8, #9A8DA8);
  stop-opacity: 0;
}

.zej7zybcv {
  stop-color: var(--svg-color--a69eaf, #A69EAF);
}

.zvj0vmb3h {
  stop-color: var(--svg-color--b2a3c1, #B2A3C1);
  stop-opacity: 0;
}

</style>
