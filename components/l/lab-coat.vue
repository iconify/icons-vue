<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLNof7b)"><path class="a0pwhzuar"/><path fill="url(#iiAFKkc)" class="w6fsrvb0k"/><path fill="url(#ikD7qNd)" class="w6fsrvb0k"/></g><path fill="url(#iLTTPSb)" class="z8xpf8bsa"/><g filter="url(#i6sjUFe)"><path class="r16pfdchs"/><path fill="url(#i8VolOd)" class="xoxcc55er"/></g><path fill="url(#iBv14ic)" class="xoxcc55er"/><path fill="url(#iqVmJCc)" class="xoxcc55er"/><path fill="url(#i26scqb)" class="xoxcc55er"/><path fill="url(#icmMBdd)" class="gix1u1b2c"/><path fill="url(#iMhjLwb)" class="ync48lv_r"/><g filter="url(#iN38Vld)"><path class="zhflryujd"/><path fill="url(#iWfcmRc)" class="az9rckm6a"/></g><path fill="url(#ihMn3dd)" class="az9rckm6a"/><path fill="url(#igL3LBe)" class="az9rckm6a"/><path fill="url(#ixkzK0c)" class="az9rckm6a"/><path fill="url(#ijW80cd)" class="sytbmk56x"/><path fill="url(#iezv8Vc)" class="sytbmk56x"/><g filter="url(#ifs5jkb)"><path class="av6dofb0g"/></g><g filter="url(#iZC1h6d)"><path fill="url(#i0rDTUc)" class="bk0_of6ka"/><path fill="url(#iNFwdse)" class="bk0_of6ka"/><path fill="url(#iOR3jgc)" class="bk0_of6ka"/></g><g filter="url(#iO4G3Ee)"><path class="yrcmxm-nr"/></g><g filter="url(#itEP3Ld)"><path fill="url(#io7sZxc)" class="ddr1scbgj"/><path fill="url(#i5ranPe)" class="ddr1scbgj"/><path fill="url(#igkMtod)" class="ddr1scbgj"/></g><path class="uxahhxbxm"/><g filter="url(#i4XIOpu)"><path fill="url(#ig9jjNe)" class="gr60mbb6n"/></g><g filter="url(#i4UQc0d)"><path fill="url(#i54teje)" class="kreo24fdc"/></g><path class="cq6igt4zq"/><path fill="url(#iM0DlRd)" class="e8g2u8v0r"/><path fill="url(#inBMW7c)" class="e8g2u8v0r"/><g filter="url(#iEFO9qc)"><path fill="url(#iSqx2vc)" class="pn1bnkkqw"/></g><g filter="url(#i5rG9Me)"><path class="tf46qg1wh"/><path fill="url(#ikFcNsT)" class="zmua-nbin"/></g><path class="nilnv6bse"/><path fill="url(#iKah8Yd)" class="lvwt4srzh"/><path fill="url(#iuRPvVN)" class="lvwt4srzh"/><defs><linearGradient id="iiAFKkc" x1="15.688" x2="15.688" y1="6.942" y2="9.981" gradientUnits="userSpaceOnUse"><stop class="ygxmsfbbb"/><stop offset="1" class="ke2da4b4p"/></linearGradient><linearGradient id="ikD7qNd" x1="15.688" x2="15.688" y1="6.942" y2="7.442" gradientUnits="userSpaceOnUse"><stop class="cj3pj2bpt"/><stop offset="1" class="gzyuomg_v"/></linearGradient><linearGradient id="iLTTPSb" x1="15.687" x2=".687" y1="21.825" y2="14.45" gradientUnits="userSpaceOnUse"><stop class="vzladfblq"/><stop offset="1" class="jk8yw0big"/></linearGradient><linearGradient id="i8VolOd" x1="6.156" x2="9.125" y1="11.669" y2="13.138" gradientUnits="userSpaceOnUse"><stop offset=".181" class="o-n7feele"/><stop offset="1" class="b3vwi94ol"/></linearGradient><linearGradient id="iBv14ic" x1="4.195" x2="4.594" y1="22.864" y2="22.153" gradientUnits="userSpaceOnUse"><stop class="jhlutzbgk"/><stop offset="1" class="txpl42b0n"/></linearGradient><linearGradient id="iqVmJCc" x1="6.703" x2="5.625" y1="23.184" y2="22.638" gradientUnits="userSpaceOnUse"><stop class="jhlutzbgk"/><stop offset="1" class="txpl42b0n"/></linearGradient><linearGradient id="iMhjLwb" x1="16.325" x2="31.325" y1="21.825" y2="14.45" gradientUnits="userSpaceOnUse"><stop class="w219o0bmj"/><stop offset="1" class="jk8yw0big"/></linearGradient><linearGradient id="iWfcmRc" x1="25.856" x2="22.887" y1="11.669" y2="13.138" gradientUnits="userSpaceOnUse"><stop offset=".181" class="o-n7feele"/><stop offset="1" class="b3vwi94ol"/></linearGradient><linearGradient id="ihMn3dd" x1="27.817" x2="27.419" y1="22.864" y2="22.153" gradientUnits="userSpaceOnUse"><stop class="jhlutzbgk"/><stop offset="1" class="txpl42b0n"/></linearGradient><linearGradient id="igL3LBe" x1="25.309" x2="26.387" y1="23.184" y2="22.638" gradientUnits="userSpaceOnUse"><stop class="cuanroadt"/><stop offset="1" class="yzunkh57t"/></linearGradient><linearGradient id="i0rDTUc" x1="13.188" x2="13.188" y1="6.258" y2="9.442" gradientUnits="userSpaceOnUse"><stop class="rrtrurbph"/><stop offset="1" class="cxx5yrbad"/></linearGradient><linearGradient id="iNFwdse" x1="14.688" x2="14.172" y1="10.106" y2="10.325" gradientUnits="userSpaceOnUse"><stop offset=".2" class="ju_ufwk3g"/><stop offset="1" class="mwvi1abkj"/></linearGradient><linearGradient id="iOR3jgc" x1="12.593" x2="14.804" y1="14.926" y2="13.201" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xduscohlb"/><stop offset="1" class="j9wu7cb4s"/></linearGradient><linearGradient id="io7sZxc" x1="18.817" x2="18.817" y1="6.258" y2="9.442" gradientUnits="userSpaceOnUse"><stop class="rrtrurbph"/><stop offset="1" class="cxx5yrbad"/></linearGradient><linearGradient id="i5ranPe" x1="17.317" x2="17.833" y1="10.106" y2="10.325" gradientUnits="userSpaceOnUse"><stop offset=".2" class="n8yj9nbnl"/><stop offset="1" class="hsokz3b6t"/></linearGradient><linearGradient id="igkMtod" x1="19.412" x2="17.201" y1="14.926" y2="13.201" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xduscohlb"/><stop offset="1" class="j9wu7cb4s"/></linearGradient><linearGradient id="ig9jjNe" x1="20.77" x2="20.77" y1="24.099" y2="24.618" gradientUnits="userSpaceOnUse"><stop class="t4os--btq"/><stop offset="1" class="mywlm5xoq"/></linearGradient><linearGradient id="i54teje" x1="11.242" x2="11.242" y1="24.099" y2="24.618" gradientUnits="userSpaceOnUse"><stop class="t4os--btq"/><stop offset="1" class="mywlm5xoq"/></linearGradient><linearGradient id="inBMW7c" x1="21.156" x2="21.156" y1="24.575" y2="24.2" gradientUnits="userSpaceOnUse"><stop class="ugm2obbuw"/><stop offset="1" class="unfc843im"/></linearGradient><linearGradient id="iSqx2vc" x1="22.018" x2="20.615" y1="16.058" y2="19.804" gradientUnits="userSpaceOnUse"><stop offset=".747" class="t4os--btq"/><stop offset="1" class="mywlm5xoq"/></linearGradient><linearGradient id="ikFcNsT" x1="20.629" x2="20.629" y1="15.419" y2="15.763" gradientUnits="userSpaceOnUse"><stop class="we93f1w0k"/><stop offset="1" class="u_ilj606c"/></linearGradient><linearGradient id="iuRPvVN" x1="10.856" x2="10.856" y1="24.575" y2="24.2" gradientUnits="userSpaceOnUse"><stop class="ugm2obbuw"/><stop offset="1" class="unfc843im"/></linearGradient><filter id="iLNof7b" width="6.46" height="22.938" x="12.357" y="6.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.372549 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16300"/></filter><filter id="i6sjUFe" width="12.123" height="16.769" x="2.254" y="6.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.52549 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16300"/></filter><filter id="iN38Vld" width="12.773" height="17.269" x="16.985" y="6.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.941176 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.717647 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16300" result="effect2_innerShadow_18_16300"/></filter><filter id="ifs5jkb" width="5.846" height="10.386" x="10.188" y="6.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16300" stdDeviation=".25"/></filter><filter id="iZC1h6d" width="5.249" height="9.784" x="10.688" y="6.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.623529 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.560784 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16300" result="effect2_innerShadow_18_16300"/></filter><filter id="iO4G3Ee" width="5.999" height="10.684" x="15.817" y="6.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16300" stdDeviation=".25"/></filter><filter id="itEP3Ld" width="5.249" height="9.934" x="16.067" y="6.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.878431 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.631373 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16300" result="effect2_innerShadow_18_16300"/></filter><filter id="i4XIOpu" width="5.363" height="1.321" x="18.089" y="23.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16300" stdDeviation=".05"/></filter><filter id="i4UQc0d" width="5.363" height="1.321" x="8.561" y="23.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16300" stdDeviation=".05"/></filter><filter id="iEFO9qc" width="5.114" height="4.411" x="18.072" y="15.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16300" stdDeviation=".05"/></filter><filter id="i5rG9Me" width="5.486" height="4.603" x="18.211" y="15.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.721569 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.686275 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16300" result="effect2_innerShadow_18_16300"/></filter><radialGradient id="i26scqb" cx="0" cy="0" r="1" gradientTransform="rotate(109.472 1.073 10.846)scale(9.28083 2.60702)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="nbupjtxac"/><stop offset=".873" class="d5bqjz0tj"/></radialGradient><radialGradient id="icmMBdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 18.375 8.25 29.013)" gradientUnits="userSpaceOnUse"><stop offset=".044" class="vw_s9tdow"/><stop offset="1" class="xqoqpj8uv"/></radialGradient><radialGradient id="ixkzK0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.09374 8.75 -2.4579 .86904 20.356 13.45)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="nbupjtxac"/><stop offset=".873" class="d5bqjz0tj"/></radialGradient><radialGradient id="ijW80cd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4375 0 0 -11.8285 24.75 24.138)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="w0koyzjae"/><stop offset="1" class="yhy15mtda"/></radialGradient><radialGradient id="iezv8Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90698 2.55087 0 20.564 15.883)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="rira3fb_h"/><stop offset="1" class="jku2pehsh"/></radialGradient><radialGradient id="iM0DlRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45313 7.00165 0 20.77 24.716)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="s8ursro3h"/><stop offset="1" class="klle60b3t"/></radialGradient><radialGradient id="iKah8Yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45313 7.00165 0 11.242 24.716)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="s8ursro3h"/><stop offset="1" class="klle60b3t"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lab-coat" /></template>
<style>
.a0pwhzuar {
  fill: var(--svg-color--3986e4, #3986E4);
  d: path("M18.817 6.942h-6.36V29.88h3.868V12.95a.2.2 0 0 1 .015-.077z");
}

.av6dofb0g {
  fill: var(--svg-color--a892c0, #A892C0);
  d: path("M12.353 7.266c-.739 0-1.36.554-1.445 1.287l-.217 1.882a.34.34 0 0 0 .313.378l.824.058a.097.097 0 0 1 .06.166l-.801.766a.39.39 0 0 0-.008.553l4.206 4.253a.145.145 0 0 0 .249-.102v-3.271l-.004-.019c-.176-.426-.41-.997-.665-1.62a316 316 0 0 0-1.676-4.044a.48.48 0 0 0-.439-.287z");
}

.az9rckm6a {
  d: path("m17.985 8.936l.832-1.994h1.728a3.15 3.15 0 0 1 2.81 1.727l6.343 12.527a.55.55 0 0 1-.232.734l-3.23 1.717a.55.55 0 0 1-.746-.231l-1.018-1.948z");
}

.b3vwi94ol {
  stop-color: var(--svg-color--d5d1da, #D5D1DA);
  stop-opacity: 0;
}

.bk0_of6ka {
  d: path("M12.405 6.786a1.5 1.5 0 0 0-1.49 1.328l-.224 1.941a.35.35 0 0 0 .323.39l.85.06a.1.1 0 0 1 .062.172l-.827.789a.4.4 0 0 0-.008.57l4.34 4.389a.15.15 0 0 0 .257-.106v-3.375l-.004-.019c-.182-.439-.423-1.029-.687-1.672c-.616-1.502-1.353-3.3-1.728-4.171a.49.49 0 0 0-.454-.296z");
}

.cj3pj2bpt {
  stop-color: var(--svg-color--3a8cd3, #3A8CD3);
}

.cq6igt4zq {
  fill: var(--svg-color--d4c2e6, #D4C2E6);
  d: path("M23.244 24.575c.027 0 .05-.022.048-.05c-.026-.598-.417-1.075-1.123-1.075h-2.797c-.813 0-1.098.477-1.124 1.075a.05.05 0 0 0 .049.05z");
}

.cuanroadt {
  stop-color: var(--svg-color--8970a0, #8970A0);
}

.cxx5yrbad {
  stop-color: var(--svg-color--d3c7e1, #D3C7E1);
}

.d5bqjz0tj {
  stop-color: var(--svg-color--d1c3e0, #D1C3E0);
  stop-opacity: 0;
}

.ddr1scbgj {
  d: path("M19.6 6.786a1.5 1.5 0 0 1 1.49 1.328l.224 1.941a.35.35 0 0 1-.323.39l-.85.06a.1.1 0 0 0-.062.172l.827.789a.4.4 0 0 1 .008.57l-4.34 4.389a.15.15 0 0 1-.257-.106v-3.375l.004-.019c.182-.439.423-1.029.687-1.672a345 345 0 0 1 1.728-4.171a.49.49 0 0 1 .453-.296z");
}

.e8g2u8v0r {
  d: path("M23.244 24.575c.027 0 .05-.022.048-.05c-.026-.598-.417-1.075-1.123-1.075h-2.797c-.813 0-1.098.477-1.124 1.075a.05.05 0 0 0 .049.05z");
}

.ft5dv1b6b {
  fill: none;
}

.gix1u1b2c {
  d: path("m8.25 20.286l.004.02v9.474a.1.1 0 0 0 .1.1h7.334V12.95a.2.2 0 0 0-.016-.077l-2.477-5.932h-1.728a3.15 3.15 0 0 0-2.81 1.727l-.407.804z");
}

.gr60mbb6n {
  d: path("M23.302 24.618a.05.05 0 0 0 .05-.05c-.027-.596-.427-1.071-1.15-1.071h-2.863c-.832 0-1.124.475-1.15 1.071a.05.05 0 0 0 .05.05z");
}

.gzyuomg_v {
  stop-color: var(--svg-color--3a8cd3, #3A8CD3);
  stop-opacity: 0;
}

.hsokz3b6t {
  stop-color: var(--svg-color--b4b1c7, #B4B1C7);
  stop-opacity: 0;
}

.j9wu7cb4s {
  stop-color: var(--svg-color--cbbddb, #CBBDDB);
  stop-opacity: 0;
}

.jhlutzbgk {
  stop-color: var(--svg-color--8661a6, #8661A6);
}

.jk8yw0big {
  stop-color: var(--svg-color--d0c3de, #D0C3DE);
}

.jku2pehsh {
  stop-color: var(--svg-color--e7daf7, #E7DAF7);
  stop-opacity: 0;
}

.ju_ufwk3g {
  stop-color: var(--svg-color--e6e2f1, #E6E2F1);
}

.ke2da4b4p {
  stop-color: var(--svg-color--4ea4f6, #4EA4F6);
  stop-opacity: 0;
}

.klle60b3t {
  stop-color: var(--svg-color--e0d4ed, #E0D4ED);
}

.kreo24fdc {
  d: path("M13.774 24.618a.05.05 0 0 0 .05-.05c-.027-.596-.427-1.071-1.15-1.071H9.81c-.831 0-1.123.475-1.15 1.071a.05.05 0 0 0 .05.05z");
}

.lvwt4srzh {
  d: path("M8.769 24.575a.05.05 0 0 1-.05-.05c.027-.598.418-1.075 1.125-1.075h2.797c.812 0 1.097.477 1.124 1.075a.05.05 0 0 1-.05.05z");
}

.mwvi1abkj {
  stop-color: var(--svg-color--e6e2f1, #E6E2F1);
  stop-opacity: 0;
}

.mywlm5xoq {
  stop-color: var(--svg-color--a388bc, #A388BC);
}

.n8yj9nbnl {
  stop-color: var(--svg-color--b4b1c7, #B4B1C7);
}

.nbupjtxac {
  stop-color: var(--svg-color--d1c3e0, #D1C3E0);
}

.nilnv6bse {
  fill: var(--svg-color--d4c2e6, #D4C2E6);
  d: path("M8.769 24.575a.05.05 0 0 1-.05-.05c.027-.598.418-1.075 1.125-1.075h2.797c.812 0 1.097.477 1.124 1.075a.05.05 0 0 1-.05.05z");
}

.o-n7feele {
  stop-color: var(--svg-color--d5d1da, #D5D1DA);
}

.pn1bnkkqw {
  d: path("M18.172 15.599h4.914v2.958c0 .692-.569 1.252-1.27 1.252h-2.374c-.701 0-1.27-.56-1.27-1.252z");
}

.r16pfdchs {
  fill: var(--svg-color--d1c3e0, #D1C3E0);
  d: path("m14.028 8.936l-.833-1.994h-1.728a3.15 3.15 0 0 0-2.81 1.727L2.314 21.196a.55.55 0 0 0 .232.734l3.23 1.717a.55.55 0 0 0 .746-.231l1.018-1.948z");
}

.rira3fb_h {
  stop-color: var(--svg-color--e7daf7, #E7DAF7);
}

.rrtrurbph {
  stop-color: var(--svg-color--efedf2, #EFEDF2);
}

.s8ursro3h {
  stop-color: var(--svg-color--e0d4ed, #E0D4ED);
  stop-opacity: 0;
}

.sytbmk56x {
  d: path("m23.762 20.286l-.004.02v9.474a.1.1 0 0 1-.1.1h-7.333V12.95q0-.04.015-.077l2.477-5.932h1.728a3.15 3.15 0 0 1 2.81 1.727l.407.804z");
}

.t4os--btq {
  stop-color: var(--svg-color--b0a3c1, #B0A3C1);
}

.tf46qg1wh {
  fill: var(--svg-color--dacce9, #DACCE9);
  d: path("M18.21 15.56h4.837v2.953c0 .69-.56 1.25-1.25 1.25H19.46c-.69 0-1.25-.56-1.25-1.25z");
}

.txpl42b0n {
  stop-color: var(--svg-color--c4b1d7, #C4B1D7);
  stop-opacity: 0;
}

.u_ilj606c {
  stop-color: var(--svg-color--e7ddf1, #E7DDF1);
  stop-opacity: 0;
}

.ugm2obbuw {
  stop-color: var(--svg-color--ccb9e1, #CCB9E1);
}

.unfc843im {
  stop-color: var(--svg-color--ccb9e1, #CCB9E1);
  stop-opacity: 0;
}

.uxahhxbxm {
  fill: var(--svg-color--c2b3d2, #C2B3D2);
  d: path("M23.244 24.575c.027 0 .05-.022.048-.05c-.026-.598-.417-1.075-1.123-1.075h-2.797c-.813 0-1.098.477-1.124 1.075a.05.05 0 0 0 .049.05z");
}

.vw_s9tdow {
  stop-color: var(--svg-color--7a7282, #7A7282);
}

.vzladfblq {
  stop-color: var(--svg-color--d1c2e1, #D1C2E1);
}

.w0koyzjae {
  stop-color: var(--svg-color--7e6c90, #7E6C90);
}

.w219o0bmj {
  stop-color: var(--svg-color--d3c3e3, #D3C3E3);
}

.w6fsrvb0k {
  d: path("M18.817 6.942h-6.36V29.88h3.868V12.95a.2.2 0 0 1 .015-.077z");
}

.we93f1w0k {
  stop-color: var(--svg-color--e7ddf1, #E7DDF1);
}

.xduscohlb {
  stop-color: var(--svg-color--cbbddb, #CBBDDB);
}

.xoxcc55er {
  d: path("m14.028 8.936l-.833-1.994h-1.728a3.15 3.15 0 0 0-2.81 1.727L2.314 21.196a.55.55 0 0 0 .232.734l3.23 1.717a.55.55 0 0 0 .746-.231l1.018-1.948z");
}

.xqoqpj8uv {
  stop-color: var(--svg-color--c7b7d8, #C7B7D8);
  stop-opacity: 0;
}

.ygxmsfbbb {
  stop-color: var(--svg-color--4ea4f6, #4EA4F6);
}

.yhy15mtda {
  stop-color: var(--svg-color--b4a7c1, #B4A7C1);
  stop-opacity: 0;
}

.ync48lv_r {
  d: path("M20.545 6.942a3.15 3.15 0 0 1 2.81 1.727l6.343 12.527a.55.55 0 0 1-.232.734l-3.23 1.717a.55.55 0 0 1-.746-.231l-1.637-3.134c-.025-.046-.095-.029-.095.024v9.474a.1.1 0 0 1-.1.1h-7.333V12.95a.2.2 0 0 1 .015-.077l2.477-5.932z");
}

.yrcmxm-nr {
  fill: var(--svg-color--a892c0, #A892C0);
  d: path("M19.6 7.118a1.5 1.5 0 0 1 1.49 1.327l.224 1.942a.35.35 0 0 1-.323.39l-.85.06a.1.1 0 0 0-.062.171l.827.79a.4.4 0 0 1 .008.57l-4.34 4.389a.15.15 0 0 1-.257-.106v-3.375l.004-.019c.182-.44.423-1.029.687-1.672a345 345 0 0 1 1.728-4.171a.49.49 0 0 1 .453-.296z");
}

.yzunkh57t {
  stop-color: var(--svg-color--b19ac8, #B19AC8);
  stop-opacity: 0;
}

.z8xpf8bsa {
  d: path("M11.467 6.942a3.15 3.15 0 0 0-2.81 1.727L2.314 21.196a.55.55 0 0 0 .232.734l3.23 1.717a.55.55 0 0 0 .746-.231l1.638-3.134c.024-.046.094-.029.094.024v9.474a.1.1 0 0 0 .1.1h7.333V12.95a.2.2 0 0 0-.015-.077l-2.477-5.932z");
}

.zhflryujd {
  fill: var(--svg-color--d1c3e0, #D1C3E0);
  d: path("m17.985 8.936l.832-1.994h1.728a3.15 3.15 0 0 1 2.81 1.727l6.343 12.527a.55.55 0 0 1-.232.734l-3.23 1.717a.55.55 0 0 1-.746-.231l-1.018-1.948z");
}

.zmua-nbin {
  d: path("M18.21 15.56h4.837v2.953c0 .69-.56 1.25-1.25 1.25H19.46c-.69 0-1.25-.56-1.25-1.25z");
}

</style>
