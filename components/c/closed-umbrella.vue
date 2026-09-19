<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDcRFUb)"><path class="a1c91325t"/><path fill="url(#iEGIUMd)" class="s01yccc6l"/><path fill="url(#isiMvUb)" class="s01yccc6l"/></g><g filter="url(#iY9iUFd)"><path fill="url(#i4aBkUd)" clip-rule="evenodd" class="mhsh8tbbx"/></g><path fill="url(#iyusm3b)" clip-rule="evenodd" class="mhsh8tbbx"/><g filter="url(#isR3YFc)"><path stroke="url(#i3jj29c)" class="xz3svux5q"/></g><rect transform="rotate(-38.083 25.204 26.694)" class="y3wo6plwf"/><rect fill="url(#i7VSPrd)" transform="rotate(-38.083 25.204 26.694)" class="y-a3yubia"/><g filter="url(#iNBWZje)"><path fill="url(#inBrRHc)" class="x2-pbkb5t"/></g><g filter="url(#iLeSWye)"><path fill="url(#i16BJqd)" class="wz5qiy4my"/></g><g filter="url(#ifdCPae)"><path fill="url(#iIcxj1d)" class="fremjab9d"/></g><g filter="url(#iHMT3md)"><path fill="url(#iIcxj1d)" class="x58z4vsba"/></g><g filter="url(#ioBOesd)"><path fill="url(#iSDcxId)" class="u-ziy_bgv"/></g><g filter="url(#iRj5qTc)"><path fill="url(#iQGBkhV)" class="a43asrbyq"/></g><g filter="url(#ikHElse)"><path fill="url(#iwhbeLw)" class="fwxd0jbxr"/></g><g filter="url(#iU94ORb)"><path fill="url(#ibRcOkc)" class="jkzuy9bds"/></g><g filter="url(#iLXg8Cs)"><path stroke="url(#inE6V9d)" class="acp0f17kf"/></g><g filter="url(#iXzKPee)"><path stroke="url(#iEgaXRb)" class="bwk65s9ak"/></g><g filter="url(#iqvq7wZ)"><path stroke="url(#if0gLgZ)" class="wlx1-ybwy"/></g><defs><filter id="iDcRFUb" width="16.885" height="20.452" x="10.528" y="7.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.117647 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15429"/></filter><filter id="iY9iUFd" width="8.798" height="6.194" x="3.505" y="2.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.215686 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15429"/></filter><filter id="isR3YFc" width="8.38" height="5.518" x="4.039" y="2.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".3"/></filter><filter id="iNBWZje" width="20.694" height="22.896" x="7.68" y="5.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.211765 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15429"/></filter><filter id="iLeSWye" width="10.306" height="21.3" x="18.272" y="5.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="ifdCPae" width="12.197" height="18.509" x="15.325" y="8.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="iHMT3md" width="14.375" height="16.25" x="12.428" y="11.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="ioBOesd" width="17.729" height="14.735" x="8.981" y="13.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="iRj5qTc" width="11.103" height="19.81" x="17.063" y="7.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="ikHElse" width="13.719" height="17.621" x="13.803" y="10.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="iU94ORb" width="16.068" height="15.687" x="10.789" y="12.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".5"/></filter><filter id="iLXg8Cs" width="14.741" height="13.191" x="11.234" y="14.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".2"/></filter><filter id="iXzKPee" width="12.406" height="15.609" x="14.422" y="11.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".2"/></filter><filter id="iqvq7wZ" width="9.981" height="17.439" x="17.547" y="8.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15429" stdDeviation=".2"/></filter><linearGradient id="i4aBkUd" x1="7.516" x2="12.084" y1="2.407" y2="8.041" gradientUnits="userSpaceOnUse"><stop class="e5dkhtc9m"/><stop offset=".549" class="ig0r51y6l"/></linearGradient><linearGradient id="i3jj29c" x1="7.791" x2="5.366" y1="6.896" y2="3.424" gradientUnits="userSpaceOnUse"><stop class="m0wa2haqm"/><stop offset="1" class="irja-i3wm"/></linearGradient><linearGradient id="inBrRHc" x1="13.259" x2="27.202" y1="10.527" y2="28.306" gradientUnits="userSpaceOnUse"><stop offset=".275" class="w31do8bkb"/><stop offset=".79" class="n82w5yeno"/></linearGradient><linearGradient id="i16BJqd" x1="20.204" x2="27.677" y1="8.948" y2="25.919" gradientUnits="userSpaceOnUse"><stop class="h42ebkfhf"/><stop offset="1" class="jp7kk4bsm"/></linearGradient><linearGradient id="iIcxj1d" x1="17.436" x2="24.908" y1="11.16" y2="28.131" gradientUnits="userSpaceOnUse"><stop class="h42ebkfhf"/><stop offset="1" class="jp7kk4bsm"/></linearGradient><linearGradient id="iSDcxId" x1="9.959" x2="25.395" y1="15.666" y2="26.492" gradientUnits="userSpaceOnUse"><stop class="h42ebkfhf"/><stop offset="1" class="qpvbr_xzb"/></linearGradient><linearGradient id="iQGBkhV" x1="18.063" x2="26.772" y1="8.031" y2="25.84" gradientUnits="userSpaceOnUse"><stop class="ipt08t_aq"/><stop offset=".638" class="a1z55ibiz"/></linearGradient><linearGradient id="iwhbeLw" x1="14.803" x2="20.607" y1="11.014" y2="28.437" gradientUnits="userSpaceOnUse"><stop class="ipt08t_aq"/><stop offset=".638" class="a1z55ibiz"/></linearGradient><linearGradient id="ibRcOkc" x1="12.584" x2="23.459" y1="14.354" y2="25.26" gradientUnits="userSpaceOnUse"><stop class="lw4o9ybfw"/><stop offset="1" class="g9tu61b6h"/></linearGradient><linearGradient id="inE6V9d" x1="12.212" x2="25.723" y1="16.705" y2="28.273" gradientUnits="userSpaceOnUse"><stop class="exa1jsbsi"/><stop offset="1" class="vnu76q86h"/></linearGradient><linearGradient id="iEgaXRb" x1="15.334" x2="29.712" y1="14.235" y2="22.713" gradientUnits="userSpaceOnUse"><stop class="exa1jsbsi"/><stop offset="1" class="vnu76q86h"/></linearGradient><linearGradient id="if0gLgZ" x1="18.392" x2="31.391" y1="12.017" y2="17.347" gradientUnits="userSpaceOnUse"><stop class="exa1jsbsi"/><stop offset="1" class="vnu76q86h"/></linearGradient><radialGradient id="iEGIUMd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.92192 -5.90621 .6204 -.51701 14.71 11.354)" gradientUnits="userSpaceOnUse"><stop class="dnmd33bvr"/><stop offset="1" class="g-xtiac7e"/></radialGradient><radialGradient id="isiMvUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9079 -.07121 .18073 -2.30416 14.627 11.016)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="sipkckf3o"/><stop offset="1" class="frzhoubmw"/></radialGradient><radialGradient id="iyusm3b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94738 -2.50928 3.52014 -2.73188 11.436 8.524)" gradientUnits="userSpaceOnUse"><stop class="h17qn6pos"/><stop offset="1" class="eqxo0f4sy"/></radialGradient><radialGradient id="i7VSPrd" cx="0" cy="0" r="1" gradientTransform="rotate(90.64 -1.25 27.715)scale(.9618 .94243)" gradientUnits="userSpaceOnUse"><stop class="k7ec6ab2k"/><stop offset="1" class="cvixgzb_f"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:closed-umbrella" /></template>
<style>
.a1c91325t {
  fill: var(--svg-color--422865, #422865);
  d: path("M10.558 8.377c-.02-.009-.039.015-.025.032l14.995 18.745a1 1 0 1 0 1.571-1.237L12.12 7.192c-.013-.017-.04-.005-.037.016c.053.38-.01.83-.374 1.095c-.428.312-.8.234-1.151.074");
}

.a1z55ibiz {
  stop-color: var(--svg-color--4d3598, #4D3598);
}

.a43asrbyq {
  d: path("m18.063 9.797l9.103 16.043c-1.486-4.627-5.876-13.8-7.885-17.81z");
}

.acp0f17kf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m11.834 14.854l13.542 11.991");
}

.bwk65s9ak {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m15.022 12.01l11.206 14.41");
}

.cvixgzb_f {
  stop-color: var(--svg-color--665f88, #665F88);
  stop-opacity: 0;
}

.dnmd33bvr {
  stop-color: var(--svg-color--66527e, #66527E);
}

.e5dkhtc9m {
  stop-color: var(--svg-color--67403b, #67403B);
}

.eqxo0f4sy {
  stop-color: var(--svg-color--7f4b47, #7F4B47);
  stop-opacity: 0;
}

.exa1jsbsi {
  stop-color: var(--svg-color--7e57b6, #7E57B6);
}

.fremjab9d {
  d: path("m26.522 26.354l-9.995-14.688a1.166 1.166 0 0 1 .214-1.549a1.16 1.16 0 0 1 1.74.288c4.35 7.215 7.032 12.743 8.04 15.949");
}

.frzhoubmw {
  stop-color: var(--svg-color--341d57, #341D57);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwxd0jbxr {
  d: path("M26.522 26.635L14.803 12.01l1.074-.996z");
}

.g-xtiac7e {
  stop-color: var(--svg-color--66527e, #66527E);
  stop-opacity: 0;
}

.g9tu61b6h {
  stop-color: var(--svg-color--4b3197, #4B3197);
}

.h17qn6pos {
  stop-color: var(--svg-color--7f4b47, #7F4B47);
}

.h42ebkfhf {
  stop-color: var(--svg-color--8c5fc1, #8C5FC1);
}

.ig0r51y6l {
  stop-color: var(--svg-color--7d4a46, #7D4A46);
}

.ipt08t_aq {
  stop-color: var(--svg-color--703dae, #703DAE);
}

.irja-i3wm {
  stop-color: var(--svg-color--775350, #775350);
}

.jkzuy9bds {
  d: path("M25.857 26.754L13.42 13.665a.946.946 0 1 0-1.314 1.36l13.537 12.033z");
}

.jp7kk4bsm {
  stop-color: var(--svg-color--6e60a8, #6E60A8);
}

.k7ec6ab2k {
  stop-color: var(--svg-color--665f88, #665F88);
}

.lw4o9ybfw {
  stop-color: var(--svg-color--682fab, #682FAB);
}

.m0wa2haqm {
  stop-color: var(--svg-color--9c7972, #9C7972);
}

.mhsh8tbbx {
  fill-rule: evenodd;
  d: path("M8.126 5.354a1.475 1.475 0 0 0-2.064-.241a1.466 1.466 0 0 0-.239 2.062a1 1 0 1 1-1.574 1.234a3.466 3.466 0 0 1 .578-4.87a3.475 3.475 0 0 1 4.867.574l.002.002l2.192 2.783a1 1 0 1 1-1.57 1.238l-2.19-2.78z");
}

.n82w5yeno {
  stop-color: var(--svg-color--482f8c, #482F8C);
}

.qpvbr_xzb {
  stop-color: var(--svg-color--7065a3, #7065A3);
}

.s01yccc6l {
  d: path("M10.558 8.377c-.02-.009-.039.015-.025.032l14.995 18.745a1 1 0 1 0 1.571-1.237L12.12 7.192c-.013-.017-.04-.005-.037.016c.053.38-.01.83-.374 1.095c-.428.312-.8.234-1.151.074");
}

.sipkckf3o {
  stop-color: var(--svg-color--341d57, #341D57);
}

.u-ziy_bgv {
  d: path("M11.662 14.985c4.148 3.698 9.842 8.635 14.047 12.338c0 0-6.382-3.468-15.431-10.798c-.52-.421-.302-1.377.23-1.78c.42-.318.761-.11 1.154.24");
}

.vnu76q86h {
  stop-color: var(--svg-color--695da2, #695DA2);
}

.w31do8bkb {
  stop-color: var(--svg-color--6e42a0, #6E42A0);
}

.wlx1-ybwy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m18.147 9.51l8.781 16.24");
}

.wz5qiy4my {
  d: path("M27.578 26.154L19.272 8.666l1.5-1.812c5.125 10.031 6.228 15.738 6.806 19.3");
}

.x2-pbkb5t {
  d: path("M7.854 16.803c-.236-.285-.3-1.175.245-1.871c.566-.888 1.68-1.045 2.447-1.054a.47.47 0 0 0 .45-.403c.078-.503.303-1.224.877-1.668c.615-.476 1.44-.602 1.998-.561c.207.015.415-.14.44-.346c.07-.596.312-1.255.944-1.757c.538-.427 1.191-.51 1.834-.48a.486.486 0 0 0 .486-.395c.117-.589.434-1.416 1.055-1.836c1.102-.745 2.155-.442 2.379-.106l.004-.003c3.313 5.462 6.888 14.95 7.11 21.217a1.02 1.02 0 0 1-1.328 1.03c-4.55-1.386-13.306-6.053-18.946-11.763z");
}

.x58z4vsba {
  d: path("M25.803 26.698L13.428 13.573l1.406-1.125c2.97 3.75 8.72 10.656 10.97 14.25");
}

.xz3svux5q {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.37 7.747a2.466 2.466 0 0 1 .409-3.466a2.475 2.475 0 0 1 3.466.409l2.417 3.057");
}

.y-a3yubia {
  width: 1.969px;
  height: 3.85px;
  x: 25.204px;
  y: 26.694px;
  rx: 0.985px;
}

.y3wo6plwf {
  width: 1.969px;
  height: 3.85px;
  x: 25.204px;
  y: 26.694px;
  fill: var(--svg-color--402e6f, #402E6F);
  rx: 0.985px;
}

</style>
