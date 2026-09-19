<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="i5N7lfd" class="eogvhfbnp"/></defs><g class="ft5dv1b6b"><path fill="url(#ilgEGce)" class="n2p51bbyn"/><path fill="url(#iqsyq9b)" class="n2p51bbyn"/><g filter="url(#ic3xHmc)"><use href="#i5N7lfd"/></g><g filter="url(#ixP3zRc)"><use href="#i5N7lfd"/><path fill="url(#icBMqwb)" class="jt23i2bvm"/><path fill="url(#iNvo8Se)" class="jt23i2bvm"/><path fill="url(#iR7AQqb)" class="jt23i2bvm"/><path fill="url(#ibAfHxQ)" class="jt23i2bvm"/></g><g filter="url(#irO3Rib)"><path class="ehd_pmtai"/><path fill="url(#i93upOw)" class="euvqfr6sw"/></g><g filter="url(#i2TTffe)"><path class="y8zyutbrs"/><path fill="url(#il09Dze)" class="igf1qwkfa"/></g><g filter="url(#iCeisOo)"><circle fill="url(#iOeotWc)" class="f-w-dy72i"/></g><g filter="url(#iRupi9c)"><circle fill="url(#iPfphTb)" transform="rotate(-30.62 20.864 22.286)" class="w2ervpbyn"/></g><g filter="url(#ijN4Xqd)"><circle fill="url(#io0ZeQe)" class="zgqkb_c3b"/></g><g filter="url(#iDyFcUd)"><circle fill="url(#iXeSnqd)" transform="rotate(-30.62 21.375 20.912)" class="u1gr_pbzq"/></g><g filter="url(#iLvU7zb)"><circle fill="url(#iFRUhzb)" class="onvjr22_g"/></g><g filter="url(#iL3euzd)"><circle fill="url(#ieXy3Ld)" transform="rotate(-30.62 22.327 21.876)" class="p36bmjgkt"/></g><g filter="url(#ifbb6kb)"><circle fill="url(#it67gIe)" class="si73w_bey"/></g><g filter="url(#iDqWr0E)"><circle fill="url(#i82pUEe)" transform="rotate(-30.62 22.217 23.176)" class="lw2kimbrq"/></g><g filter="url(#igGF9zc)"><circle fill="url(#igZKObd)" class="wm-lyubdf"/></g><g filter="url(#i48kwWN)"><circle fill="url(#iLSPlrb)" transform="rotate(-30.62 21.026 23.881)" class="g-5oimbsn"/></g><g filter="url(#iBxE48d)"><circle fill="url(#iRGKvKd)" class="ueuv_7b3v"/></g><g filter="url(#iVfeyJd)"><circle fill="url(#iGuIlkb)" transform="rotate(-30.62 19.848 23.385)" class="cpnfuqgmv"/></g><g filter="url(#iwAKDVY)"><circle fill="url(#i9ugU3s)" class="u4m8e6_no"/></g><g filter="url(#ikQDTpd)"><circle fill="url(#irFMYId)" transform="rotate(-30.62 19.433 22.162)" class="j4lp7puny"/></g><g filter="url(#i0HskLc)"><circle fill="url(#ijcF8Dc)" class="u4jy1fa4n"/></g><g filter="url(#ihFWSKc)"><circle fill="url(#iWb2UtS)" transform="rotate(-30.62 20.127 21.07)" class="mfovdvz_t"/></g><defs><radialGradient id="ilgEGce" cx="0" cy="0" r="1" gradientTransform="rotate(-110.468 8.933 -.49)scale(3.57025 3.46764)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="r02t0tqck"/><stop offset="1" class="nh9jgyb1q"/></radialGradient><radialGradient id="iqsyq9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23828 -.7496 2.49269 -4.1177 14.03 6.81)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="xwn2jnbkx"/><stop offset="1" class="o70hz4bsj"/></radialGradient><radialGradient id="icBMqwb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.78308 -12.40873 6.9718 -2.1255 16.82 13.405)" gradientUnits="userSpaceOnUse"><stop class="vuekx_bhg"/><stop offset="1" class="ufq42fb7e"/></radialGradient><radialGradient id="iNvo8Se" cx="0" cy="0" r="1" gradientTransform="rotate(147.006 13.273 7.888)scale(12.0883 13.5028)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="dkaaooa7z"/><stop offset="1" class="q8r289j7a"/></radialGradient><radialGradient id="iR7AQqb" cx="0" cy="0" r="1" gradientTransform="rotate(147.319 3.197 6.655)scale(9.52873 11.6115)" gradientUnits="userSpaceOnUse"><stop class="dkaaooa7z"/><stop offset=".696" class="q8r289j7a"/></radialGradient><radialGradient id="ibAfHxQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.49688 7.64197 -2.84897 .93085 11.676 6.52)" gradientUnits="userSpaceOnUse"><stop class="dkaaooa7z"/><stop offset="1" class="q8r289j7a"/></radialGradient><radialGradient id="i93upOw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17188 .625 -.6012 -1.12727 14.984 25.344)" gradientUnits="userSpaceOnUse"><stop class="v0yzs2b3z"/><stop offset="1" class="orh7sc4sh"/></radialGradient><radialGradient id="il09Dze" cx="0" cy="0" r="1" gradientTransform="matrix(-.4048 .66558 -.64024 -.3894 22.1 21)" gradientUnits="userSpaceOnUse"><stop class="v0yzs2b3z"/><stop offset="1" class="orh7sc4sh"/></radialGradient><radialGradient id="iOeotWc" cx="0" cy="0" r="1" gradientTransform="rotate(145.204 2.664 14.646)scale(3.79658)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iPfphTb" cx="0" cy="0" r="1" gradientTransform="rotate(145.204 7.371 14.224)scale(2.22689)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="io0ZeQe" cx="0" cy="0" r="1" gradientTransform="rotate(161.044 5.312 13.521)scale(1.62669)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iXeSnqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9024 .30994 -.30994 -.9024 21.803 20.912)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iFRUhzb" cx="0" cy="0" r="1" gradientTransform="rotate(161.044 5.405 14.688)scale(1.62669)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="ieXy3Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.9024 .30994 -.30994 -.9024 22.755 21.876)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="it67gIe" cx="0" cy="0" r="1" gradientTransform="rotate(-166.264 8.774 13.424)scale(1.44765)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="i82pUEe" cx="0" cy="0" r="1" gradientTransform="rotate(-166.264 12.748 10.194)scale(.84912)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="igZKObd" cx="0" cy="0" r="1" gradientTransform="rotate(-83.014 22.303 8.23)scale(1.77077)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iLSPlrb" cx="0" cy="0" r="1" gradientTransform="rotate(-83.014 24.399 .104)scale(1.03865)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iRGKvKd" cx="0" cy="0" r="1" gradientTransform="rotate(-21.389 76.437 -9.087)scale(2.01369)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iGuIlkb" cx="0" cy="0" r="1" gradientTransform="rotate(-21.389 72.101 -39.15)scale(1.18113)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="i9ugU3s" cx="0" cy="0" r="1" gradientTransform="rotate(32.074 -37.767 27.893)scale(1.38297)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="irFMYId" cx="0" cy="0" r="1" gradientTransform="rotate(32.074 -28.705 43.724)scale(.81118)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="ijcF8Dc" cx="0" cy="0" r="1" gradientTransform="rotate(117.235 -.653 15.145)scale(2.38996)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><radialGradient id="iWb2UtS" cx="0" cy="0" r="1" gradientTransform="rotate(117.235 3.972 16.445)scale(1.40183)" gradientUnits="userSpaceOnUse"><stop class="cj_am8rwr"/><stop offset="1" class="xvxu09bgb"/></radialGradient><filter id="ic3xHmc" width="27.899" height="17.938" x="2.425" y="2.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15185"/></filter><filter id="ixP3zRc" width="27.899" height="17.938" x="2.425" y="2.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="3.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15185"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15185" result="effect2_innerShadow_18_15185"/></filter><filter id="irO3Rib" width="6.952" height="6.88" x="8.578" y="22.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.698039 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15185"/></filter><filter id="i2TTffe" width="4.062" height="4.076" x="18.812" y="20.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.698039 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15185"/></filter><filter id="iCeisOo" width="5.298" height="5.298" x="9.405" y="23.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".25"/></filter><filter id="iRupi9c" width="3.522" height="3.522" x="19.103" y="20.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".25"/></filter><filter id="ijN4Xqd" width="2.261" height="2.261" x="12.866" y="23.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iDyFcUd" width="1.657" height="1.657" x="20.546" y="20.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iLvU7zb" width="2.261" height="2.261" x="13.426" y="25.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iL3euzd" width="1.657" height="1.657" x="21.498" y="21.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="ifbb6kb" width="2.261" height="2.261" x="12.135" y="27.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iDqWr0E" width="1.657" height="1.657" x="21.388" y="22.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="igGF9zc" width="2.261" height="2.261" x="9.776" y="27.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="i48kwWN" width="1.657" height="1.657" x="20.197" y="23.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iBxE48d" width="2.261" height="2.261" x="8.479" y="25.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iVfeyJd" width="1.657" height="1.657" x="19.02" y="22.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="iwAKDVY" width="2.261" height="2.261" x="8.932" y="23.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="ikQDTpd" width="1.657" height="1.657" x="18.604" y="21.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="i0HskLc" width="2.261" height="2.261" x="10.899" y="22.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter><filter id="ihFWSKc" width="1.657" height="1.657" x="19.298" y="20.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15185" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cloud-with-snow" /></template>
<style>
.cj_am8rwr {
  stop-color: var(--svg-color--e9e2ff, #E9E2FF);
}

.cpnfuqgmv {
  cx: 19.848px;
  cy: 23.385px;
  r: 0.429px;
}

.dkaaooa7z {
  stop-color: var(--svg-color--f2f0ff, #F2F0FF);
}

.ehd_pmtai {
  fill: var(--svg-color--d1c8ff, #D1C8FF);
  d: path("m9.09 25.077l.173.362a.5.5 0 0 1-.147.612l-.165.127c-.702.538-.35 1.66.533 1.702l.09.005a.5.5 0 0 1 .476.479l.014.367a.9.9 0 0 0 1.498.636l.26-.231a.5.5 0 0 1 .65-.014l.21.173a.9.9 0 0 0 1.47-.708l-.005-.39a.5.5 0 0 1 .428-.502l.161-.023a.925.925 0 0 0 .459-1.627l-.308-.256a.5.5 0 0 1-.13-.602l.098-.204c.366-.753-.352-1.576-1.148-1.318l-.212.07a.5.5 0 0 1-.588-.226l-.197-.343a.9.9 0 0 0-1.584.046l-.185.368a.5.5 0 0 1-.513.271l-.407-.054a.9.9 0 0 0-.93 1.28");
}

.eogvhfbnp {
  fill: var(--svg-color--e0d3ff, #E0D3FF);
  d: path("M27.628 4.678c-3.545-3.455-9.216-3.395-12.671.15a8.9 8.9 0 0 0-2.013 3.195a.268.268 0 0 1-.399.13a6 6 0 0 0-.983-.53a6.447 6.447 0 0 0-9.136 5.861a6.46 6.46 0 0 0 1.407 4.025a6.47 6.47 0 0 0 5.163 2.556h12.67a8.36 8.36 0 0 0 6.82-3.515c2.716-3.555 2.417-8.667-.858-11.872");
}

.euvqfr6sw {
  d: path("m9.09 25.077l.173.362a.5.5 0 0 1-.147.612l-.165.127c-.702.538-.35 1.66.533 1.702l.09.005a.5.5 0 0 1 .476.479l.014.367a.9.9 0 0 0 1.498.636l.26-.231a.5.5 0 0 1 .65-.014l.21.173a.9.9 0 0 0 1.47-.708l-.005-.39a.5.5 0 0 1 .428-.502l.161-.023a.925.925 0 0 0 .459-1.627l-.308-.256a.5.5 0 0 1-.13-.602l.098-.204c.366-.753-.352-1.576-1.148-1.318l-.212.07a.5.5 0 0 1-.588-.226l-.197-.343a.9.9 0 0 0-1.584.046l-.185.368a.5.5 0 0 1-.513.271l-.407-.054a.9.9 0 0 0-.93 1.28");
}

.f-w-dy72i {
  cx: 12.054px;
  cy: 26.156px;
  r: 2.149px;
}

.ft5dv1b6b {
  fill: none;
}

.g-5oimbsn {
  cx: 21.026px;
  cy: 23.881px;
  r: 0.429px;
}

.igf1qwkfa {
  d: path("m19.046 22.627l.195.131c.115.078.16.225.109.353l-.046.113a.557.557 0 0 0 .778.7l.046-.024a.293.293 0 0 1 .384.1l.117.18c.242.375.81.299.946-.126l.062-.194a.29.29 0 0 1 .324-.2l.158.023a.528.528 0 0 0 .53-.797l-.119-.195a.293.293 0 0 1 .066-.381l.075-.06a.543.543 0 0 0-.255-.958l-.232-.037a.29.29 0 0 1-.245-.265l-.012-.132a.557.557 0 0 0-.973-.323l-.087.099a.29.29 0 0 1-.364.061l-.201-.114a.528.528 0 0 0-.786.497l.017.24a.29.29 0 0 1-.178.29l-.222.095a.528.528 0 0 0-.087.924");
}

.j4lp7puny {
  cx: 19.433px;
  cy: 22.162px;
  r: 0.429px;
}

.jt23i2bvm {
  d: path("M27.628 4.678c-3.545-3.455-9.216-3.395-12.671.15a8.9 8.9 0 0 0-2.013 3.195a.268.268 0 0 1-.399.13a6 6 0 0 0-.983-.53a6.447 6.447 0 0 0-9.136 5.861a6.46 6.46 0 0 0 1.407 4.025a6.47 6.47 0 0 0 5.163 2.556h12.67a8.36 8.36 0 0 0 6.82-3.515c2.716-3.555 2.417-8.667-.858-11.872");
}

.lw2kimbrq {
  cx: 22.217px;
  cy: 23.176px;
  r: 0.429px;
}

.mfovdvz_t {
  cx: 20.127px;
  cy: 21.069px;
  r: 0.429px;
}

.n2p51bbyn {
  d: path("M12.792 12.43a4.034 4.034 0 1 0 0-8.068a4.034 4.034 0 0 0 0 8.068");
}

.nh9jgyb1q {
  stop-color: var(--svg-color--b7b6fa, #B7B6FA);
}

.o70hz4bsj {
  stop-color: var(--svg-color--b8b7ff, #B8B7FF);
  stop-opacity: 0;
}

.onvjr22_g {
  cx: 14.557px;
  cy: 26.824px;
  r: 0.731px;
}

.orh7sc4sh {
  stop-color: var(--svg-color--e0ddff, #E0DDFF);
  stop-opacity: 0;
}

.p36bmjgkt {
  cx: 22.327px;
  cy: 21.876px;
  r: 0.429px;
}

.q8r289j7a {
  stop-color: var(--svg-color--f2f0ff, #F2F0FF);
  stop-opacity: 0;
}

.r02t0tqck {
  stop-color: var(--svg-color--cecdff, #CECDFF);
}

.si73w_bey {
  cx: 13.266px;
  cy: 28.636px;
  r: 0.731px;
}

.u1gr_pbzq {
  cx: 21.375px;
  cy: 20.912px;
  r: 0.429px;
}

.u4jy1fa4n {
  cx: 12.03px;
  cy: 23.73px;
  r: 0.731px;
}

.u4m8e6_no {
  cx: 10.063px;
  cy: 24.73px;
  r: 0.731px;
}

.ueuv_7b3v {
  cx: 9.61px;
  cy: 26.887px;
  r: 0.731px;
}

.ufq42fb7e {
  stop-color: var(--svg-color--d6ccff, #D6CCFF);
  stop-opacity: 0;
}

.v0yzs2b3z {
  stop-color: var(--svg-color--e0ddff, #E0DDFF);
}

.vuekx_bhg {
  stop-color: var(--svg-color--d6ccff, #D6CCFF);
}

.w2ervpbyn {
  cx: 20.864px;
  cy: 22.286px;
  r: 1.261px;
}

.wm-lyubdf {
  cx: 10.907px;
  cy: 28.636px;
  r: 0.731px;
}

.xvxu09bgb {
  stop-color: var(--svg-color--e9e2ff, #E9E2FF);
  stop-opacity: 0;
}

.xwn2jnbkx {
  stop-color: var(--svg-color--b8b7ff, #B8B7FF);
}

.y8zyutbrs {
  fill: var(--svg-color--d1c8ff, #D1C8FF);
  d: path("m19.046 22.627l.195.131c.115.078.16.225.109.353l-.046.113a.557.557 0 0 0 .778.7l.046-.024a.293.293 0 0 1 .384.1l.117.18c.242.375.81.299.946-.126l.062-.194a.29.29 0 0 1 .324-.2l.158.023a.528.528 0 0 0 .53-.797l-.119-.195a.293.293 0 0 1 .066-.381l.075-.06a.543.543 0 0 0-.255-.958l-.232-.037a.29.29 0 0 1-.245-.265l-.012-.132a.557.557 0 0 0-.973-.323l-.087.099a.29.29 0 0 1-.364.061l-.201-.114a.528.528 0 0 0-.786.497l.017.24a.29.29 0 0 1-.178.29l-.222.095a.528.528 0 0 0-.087.924");
}

.zgqkb_c3b {
  cx: 13.997px;
  cy: 24.583px;
  r: 0.731px;
}

</style>
