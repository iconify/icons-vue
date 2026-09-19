<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ihLUfPe)" class="vuoh_wbem"/><g filter="url(#i47Hihe)"><path class="jeovr84gw"/></g><g filter="url(#iFnAfhe)"><path class="tmq6e0b-s"/></g><g filter="url(#iEJedBe)"><path class="zsoz1vb8h"/></g><g filter="url(#iQeFkwc)"><path class="dyn-qtbio"/></g><g filter="url(#it1w7Ac)"><path class="xdwprshzn"/></g><g filter="url(#i26r31d)"><path class="zodf4t0fs"/></g><g filter="url(#i74dnCc)"><path class="a9g62qbva"/></g><g filter="url(#iebwkNc)"><path class="o2dg603nj"/></g><g filter="url(#iN4MNYc)"><path class="dfwyznwyz"/></g><path fill="url(#imCVPVc)" class="u3fw6_bwc"/><path fill="url(#il5Pn5r)" class="u3fw6_bwc"/><path fill="url(#ia07dZX)" class="mday2obkg"/><path fill="url(#iEbiBoe)" class="mday2obkg"/><path fill="url(#iDFrode)" class="mday2obkg"/><g filter="url(#iovi7Rd)"><path fill="url(#iCbsxle)" class="r3xs_nb8w"/><path fill="url(#i47xDDd)" class="r3xs_nb8w"/></g><g filter="url(#iAwX1lb)"><path fill="url(#imVMC8b)" class="hnhokccjt"/></g><g filter="url(#iOJaETK)"><path fill="url(#iBZCNQd)" class="u28s1tmov"/><path fill="url(#i4Mi07d)" class="u28s1tmov"/></g><g filter="url(#iQyAHAe)"><path fill="url(#iOn9VZb)" class="y-2jw5b2q"/><path fill="url(#iTaeJmd)" class="y-2jw5b2q"/></g><g filter="url(#iZxRC2d)"><path fill="url(#iwp70Fs)" class="ii9aegbns"/></g><path fill="url(#iqyaFNb)" class="qr9eoiykt"/><path fill="url(#ie8y8od)" class="qr9eoiykt"/><path fill="url(#igkW2hc)" class="qr9eoiykt"/><g filter="url(#iq3nTrd)"><path fill="url(#iXAuHvX)" class="cmm-e3bhe"/></g><g filter="url(#iYbyyGc)"><path fill="url(#itDqeCd)" class="lo8nz3bvt"/></g><g filter="url(#iL2NpPK)"><path stroke="url(#io1QYqe)" class="o_p11abfx"/></g><g filter="url(#ikstbUb)"><path stroke="url(#it3xd3d)" class="c-42egryl"/></g><g filter="url(#iP0Noib)"><path stroke="url(#i88Sxjc)" class="ktgr9qx-v"/></g><g filter="url(#iTPL8Ce)"><path stroke="url(#iVS4lde)" class="shfdkyndy"/></g><g filter="url(#iTCO2ab)"><path stroke="url(#i3O7bsb)" class="dtxq3acwy"/></g><g filter="url(#iNJeupz)"><path stroke="url(#iplwH5d)" class="gw5wwb_dy"/></g><g filter="url(#iIKhptc)"><path stroke="url(#iyefGMg)" class="ue293mb4c"/></g><defs><linearGradient id="ihLUfPe" x1="16.375" x2="16.375" y1="2" y2="30.445" gradientUnits="userSpaceOnUse"><stop class="rhyuspbmb"/><stop offset="1" class="x0cyrcb4c"/></linearGradient><linearGradient id="imCVPVc" x1="5.545" x2="2.018" y1="20" y2="20" gradientUnits="userSpaceOnUse"><stop class="xt2m6sb3k"/><stop offset="1" class="rir98sf_p"/></linearGradient><linearGradient id="il5Pn5r" x1="3.769" x2="3.769" y1="23" y2="22.07" gradientUnits="userSpaceOnUse"><stop class="khd9f_h2s"/><stop offset="1" class="fw9vak32p"/></linearGradient><linearGradient id="ia07dZX" x1="5.421" x2="1.872" y1="4.87" y2="4.87" gradientUnits="userSpaceOnUse"><stop class="v_7ms9b9d"/><stop offset="1" class="z2_c79b2w"/></linearGradient><linearGradient id="iEbiBoe" x1="7.292" x2="6.808" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="w0j7mepuw"/><stop offset="1" class="a1hubh84q"/></linearGradient><linearGradient id="iDFrode" x1="4.875" x2="4.875" y1="7.279" y2="6.285" gradientUnits="userSpaceOnUse"><stop class="frgw81ies"/><stop offset="1" class="e088vyb2n"/></linearGradient><linearGradient id="iCbsxle" x1="20.939" x2="7.58" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="jp56h8bfc"/><stop offset="1" class="g0exftbjt"/></linearGradient><linearGradient id="i47xDDd" x1="23.375" x2="22.326" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="w0j7mepuw"/><stop offset="1" class="a1hubh84q"/></linearGradient><linearGradient id="imVMC8b" x1="18.25" x2="8.375" y1="20" y2="20" gradientUnits="userSpaceOnUse"><stop class="rgzu2obfm"/><stop offset="1" class="f0rdnoq5a"/></linearGradient><linearGradient id="iBZCNQd" x1="29.875" x2="26.063" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="zhr2o-bob"/><stop offset="1" class="oxtzxnowl"/></linearGradient><linearGradient id="i4Mi07d" x1="30.375" x2="30" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="w0j7mepuw"/><stop offset="1" class="a1hubh84q"/></linearGradient><linearGradient id="iOn9VZb" x1="29.875" x2="26.063" y1="20" y2="20" gradientUnits="userSpaceOnUse"><stop class="zhr2o-bob"/><stop offset="1" class="oxtzxnowl"/></linearGradient><linearGradient id="iTaeJmd" x1="30.375" x2="30" y1="20" y2="20" gradientUnits="userSpaceOnUse"><stop class="w0j7mepuw"/><stop offset="1" class="a1hubh84q"/></linearGradient><linearGradient id="iwp70Fs" x1="10.616" x2="1.446" y1="27.5" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="rgzu2obfm"/><stop offset="1" class="f0rdnoq5a"/></linearGradient><linearGradient id="iqyaFNb" x1="10.294" x2="1.067" y1="12.444" y2="12.444" gradientUnits="userSpaceOnUse"><stop class="v_7ms9b9d"/><stop offset="1" class="z2_c79b2w"/></linearGradient><linearGradient id="ie8y8od" x1="15.159" x2="13.9" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="w0j7mepuw"/><stop offset="1" class="a1hubh84q"/></linearGradient><linearGradient id="igkW2hc" x1="8.875" x2="8.875" y1="15" y2="14.143" gradientUnits="userSpaceOnUse"><stop class="frgw81ies"/><stop offset="1" class="e088vyb2n"/></linearGradient><linearGradient id="iXAuHvX" x1="20.803" x2="30.875" y1="28" y2="28" gradientUnits="userSpaceOnUse"><stop class="r6s_wmbxw"/><stop offset="1" class="mc8docbky"/></linearGradient><linearGradient id="itDqeCd" x1="28.113" x2="15.708" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="u00in2ben"/><stop offset=".836" class="f0rdnoq5a"/></linearGradient><linearGradient id="io1QYqe" x1="29.029" x2="28.929" y1="9.659" y2="10.721" gradientUnits="userSpaceOnUse"><stop class="v_hwwsbok"/><stop offset="1" class="yr1eq0b2d"/></linearGradient><linearGradient id="it3xd3d" x1="13.757" x2="13.657" y1="9.659" y2="10.721" gradientUnits="userSpaceOnUse"><stop class="rcg7mg7xa"/><stop offset="1" class="yr1eq0b2d"/></linearGradient><linearGradient id="i88Sxjc" x1="29.492" x2="29.186" y1="17.769" y2="18.744" gradientUnits="userSpaceOnUse"><stop class="v_hwwsbok"/><stop offset="1" class="yr1eq0b2d"/></linearGradient><linearGradient id="iVS4lde" x1="22.563" x2="19.743" y1="20.656" y2="24.725" gradientUnits="userSpaceOnUse"><stop offset=".195" class="na476kbiw"/><stop offset="1" class="yr1eq0b2d"/></linearGradient><linearGradient id="i3O7bsb" x1="9.143" x2="8.225" y1="19.906" y2="21.647" gradientUnits="userSpaceOnUse"><stop class="na476kbiw"/><stop offset="1" class="yr1eq0b2d"/></linearGradient><linearGradient id="iplwH5d" x1="19.219" x2="16.771" y1="27.609" y2="32.768" gradientUnits="userSpaceOnUse"><stop class="na476kbiw"/><stop offset="1" class="yr1eq0b2d"/></linearGradient><linearGradient id="iyefGMg" x1="29.449" x2="29.31" y1="25.706" y2="26.947" gradientUnits="userSpaceOnUse"><stop class="nhsctebvu"/><stop offset="1" class="antt9347k"/></linearGradient><filter id="i47Hihe" width="6.019" height="6.573" x="24.506" y="16.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="iFnAfhe" width="5.503" height="6.573" x="2.116" y="16.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="iEJedBe" width="13.175" height="5.534" x="16.725" y="24.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="iQeFkwc" width="14.8" height="6.573" x="8.6" y="16.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="it1w7Ac" width="13.25" height="6.5" x="2.125" y="8.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".125"/></filter><filter id="i26r31d" width="5.409" height="5.425" x="2.209" y="2.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="i74dnCc" width="14.8" height="5.612" x="8.6" y="1.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="iebwkNc" width="5.8" height="5.675" x="24.725" y="1.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="iN4MNYc" width="13.816" height="6.628" x="16.709" y="8.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".2"/></filter><filter id="iovi7Rd" width="14.5" height="5.5" x="9.375" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.258824 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iAwX1lb" width="14.5" height="6.5" x="9.375" y="16.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.227451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iOJaETK" width="5.5" height="5.5" x="25.375" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.258824 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iQyAHAe" width="5.5" height="6.5" x="25.375" y="16.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.258824 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iZxRC2d" width="13.1" height="5.1" x="2.275" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.490196 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iq3nTrd" width="13.5" height="5.1" x="17.375" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.25098 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iYbyyGc" width="13.5" height="6.5" x="17.375" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.227451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5652"/></filter><filter id="iL2NpPK" width="11.971" height=".9" x="18.162" y="9.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".15"/></filter><filter id="ikstbUb" width="11.971" height=".9" x="2.89" y="9.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".15"/></filter><filter id="iP0Noib" width="4.213" height=".9" x="25.925" y="17.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".15"/></filter><filter id="iTPL8Ce" width="13.984" height="6.188" x="9.688" y="16.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".25"/></filter><filter id="iTCO2ab" width="5.174" height="6.188" x="2.343" y="16.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".25"/></filter><filter id="iNJeupz" width="13.375" height="5.281" x="2.125" y="24.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".25"/></filter><filter id="iIKhptc" width="11.598" height=".9" x="18.753" y="25.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5652" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:brick" /></template>
<style>
.a1hubh84q {
  stop-color: var(--svg-color--ff924d, #FF924D);
  stop-opacity: 0;
}

.a9g62qbva {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M23 2.281H9v3.85c0 .532.448.963 1 .963h12c.552 0 1-.431 1-.963z");
}

.antt9347k {
  stop-color: var(--svg-color--ff7f41, #FF7F41);
  stop-opacity: 0;
}

.c-42egryl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.34 9.671h11.07");
}

.cmm-e3bhe {
  d: path("M30.375 25v2a3 3 0 0 1-3 3h-10v-4a1 1 0 0 1 1-1z");
}

.dfwyznwyz {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M30.125 9.328v5.828H18.111c-.553 0-1.002-.435-1.002-.971v-3.886c0-.536.449-.97 1.002-.97z");
}

.dtxq3acwy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M3.093 17.563h3.174a.5.5 0 0 1 .5.5v4.187");
}

.dyn-qtbio {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M9 18.337c0-.531.448-.962 1-.962h12c.552 0 1 .43 1 .962v3.849c0 .531-.448.962-1 .962H10c-.552 0-1-.43-1-.962z");
}

.e088vyb2n {
  stop-color: var(--svg-color--d4583a, #D4583A);
  stop-opacity: 0;
}

.f0rdnoq5a {
  stop-color: var(--svg-color--ec5242, #EC5242);
}

.frgw81ies {
  stop-color: var(--svg-color--d4583a, #D4583A);
}

.ft5dv1b6b {
  fill: none;
}

.fw9vak32p {
  stop-color: var(--svg-color--d35b36, #D35B36);
  stop-opacity: 0;
}

.g0exftbjt {
  stop-color: var(--svg-color--ed5342, #ED5342);
}

.gw5wwb_dy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M2.875 25.719H14.25a.5.5 0 0 1 .5.5V29.5");
}

.hnhokccjt {
  d: path("M9.375 18a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-12a1 1 0 0 1-1-1z");
}

.ii9aegbns {
  d: path("M15.375 30h-10a3 3 0 0 1-3-3v-2h12a1 1 0 0 1 1 1z");
}

.jeovr84gw {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M30.125 17.375v5.773H25.95c-.576 0-1.044-.43-1.044-.962v-3.849c0-.531.468-.962 1.044-.962z");
}

.jp56h8bfc {
  stop-color: var(--svg-color--f77d3e, #F77D3E);
}

.khd9f_h2s {
  stop-color: var(--svg-color--d35b36, #D35B36);
}

.ktgr9qx-v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M26.375 17.781h3.313");
}

.lo8nz3bvt {
  d: path("M30.375 9v6h-12a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1z");
}

.mc8docbky {
  stop-color: var(--svg-color--fa7b40, #FA7B40);
}

.mday2obkg {
  d: path("M7.375 2h-2a3 3 0 0 0-3 3v2h4a1 1 0 0 0 1-1z");
}

.na476kbiw {
  stop-color: var(--svg-color--ff9151, #FF9151);
}

.nhsctebvu {
  stop-color: var(--svg-color--ff7f41, #FF7F41);
}

.o_p11abfx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M18.612 9.671h11.07");
}

.o2dg603nj {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M30.125 7.156h-4c-.552 0-1-.436-1-.975v-3.9h2c1.657 0 3 1.31 3 2.925z");
}

.oxtzxnowl {
  stop-color: var(--svg-color--e94942, #E94942);
}

.qr9eoiykt {
  d: path("M2.375 15V9h12a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1z");
}

.r3xs_nb8w {
  d: path("M23.375 2h-14v4a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1z");
}

.r6s_wmbxw {
  stop-color: var(--svg-color--ee4944, #EE4944);
}

.rcg7mg7xa {
  stop-color: var(--svg-color--ff9149, #FF9149);
}

.rgzu2obfm {
  stop-color: var(--svg-color--fb7e3f, #FB7E3F);
}

.rhyuspbmb {
  stop-color: var(--svg-color--ccc1c9, #CCC1C9);
}

.rir98sf_p {
  stop-color: var(--svg-color--f65944, #F65944);
}

.shfdkyndy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.438 17.563h11.984a.5.5 0 0 1 .5.5v4.187");
}

.tmq6e0b-s {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M2.516 23.148v-5.773h3.762c.52 0 .94.43.94.962v3.849a.95.95 0 0 1-.94.962z");
}

.u00in2ben {
  stop-color: var(--svg-color--f77c3e, #F77C3E);
}

.u28s1tmov {
  d: path("M30.375 7h-4a1 1 0 0 1-1-1V2h2a3 3 0 0 1 3 3z");
}

.u3fw6_bwc {
  d: path("M2.375 23v-6h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1z");
}

.ue293mb4c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.901 25.719H19.203");
}

.v_7ms9b9d {
  stop-color: var(--svg-color--fc803f, #FC803F);
}

.v_hwwsbok {
  stop-color: var(--svg-color--ff843c, #FF843C);
}

.vuoh_wbem {
  width: 28px;
  height: 28px;
  x: 2.375px;
  y: 2px;
  rx: 3px;
}

.w0j7mepuw {
  stop-color: var(--svg-color--ff924d, #FF924D);
}

.x0cyrcb4c {
  stop-color: var(--svg-color--c4b7c5, #C4B7C5);
}

.xdwprshzn {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M2.375 15.242v-6h11.77a.99.99 0 0 1 .98 1v4c0 .552-.44 1-.98 1z");
}

.xt2m6sb3k {
  stop-color: var(--svg-color--fe8040, #FE8040);
}

.y-2jw5b2q {
  d: path("M30.375 17v6h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1z");
}

.yr1eq0b2d {
  stop-color: var(--svg-color--ff843c, #FF843C);
  stop-opacity: 0;
}

.z2_c79b2w {
  stop-color: var(--svg-color--f14d43, #F14D43);
}

.zhr2o-bob {
  stop-color: var(--svg-color--f4753e, #F4753E);
}

.zodf4t0fs {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M7.219 2.469H5.375a2.77 2.77 0 0 0-2.766 2.775v1.85h3.688a.924.924 0 0 0 .922-.925z");
}

.zsoz1vb8h {
  fill: var(--svg-color--8e6a79, #8E6A79);
  d: path("M29.5 25.11v1.893a2.85 2.85 0 0 1-2.856 2.84h-9.519v-3.787a.95.95 0 0 1 .952-.947z");
}

</style>
