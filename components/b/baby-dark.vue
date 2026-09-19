<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4uGBJb)" class="vf5ztvkiw"/><path fill="url(#iHXhJ2b)" class="vf5ztvkiw"/><g filter="url(#iQWOCle)"><path fill="url(#iGSgjxb)" class="wlp8nn_ub"/></g><path fill="url(#ipptGsb)" class="h84bfz8td"/><path fill="url(#iHrguLc)" class="h84bfz8td"/><path fill="url(#ifzodCe)" class="h84bfz8td"/><path fill="url(#iT8onyc)" class="h84bfz8td"/><g filter="url(#i1u1oYl)"><path fill="url(#itgTC8b)" class="bpta1ubgb"/></g><g filter="url(#iCpVn5c)"><path class="i8t3aob6g"/><path fill="url(#iWz9HFI)" class="otsp18aza"/><path fill="url(#iNuGSdc)" class="otsp18aza"/><path fill="url(#iYBaiIg)" class="otsp18aza"/><path fill="url(#iWpUNJb)" class="otsp18aza"/><path fill="url(#i2VOQ0w)" class="otsp18aza"/></g><g filter="url(#itjURCb)"><path class="d3p6e5btk"/></g><path stroke="url(#iWI7Hrr)" class="vwmd-5b_e"/><path class="a9h4drbls"/><path fill="url(#iSGqOwc)" class="x377v9b5z"/><path fill="url(#imY1u4d)" class="n9r5i0bal"/><path class="qwle-9byr"/><g filter="url(#ig22bZc)"><path class="cuntytbpm"/></g><g filter="url(#ibAjzIm)"><path stroke="url(#idaX0nc)" class="fwceehblp"/></g><g filter="url(#iqiPoac)"><path class="j77jw4brz"/></g><g filter="url(#iabnEiP)"><path stroke="url(#iNh1Yfd)" class="panyp8b9r"/></g><g filter="url(#iQhkaLd)"><path fill="url(#iBApK5b)" class="vibsggbex"/></g><g filter="url(#iCwKveb)"><path class="xt_7vw5fe"/><path fill="url(#iDRMJqc)" class="pfo1lekmx"/><path fill="url(#ivDDmPb)" class="pfo1lekmx"/><path fill="url(#ivDz5rc)" class="pfo1lekmx"/><path fill="url(#ilAJJAe)" class="pfo1lekmx"/></g><g filter="url(#iWgOPib)"><path class="wj9jagqeu"/></g><g filter="url(#il60DZn)"><path fill="url(#iKJy5Sb)" class="pw9ealv2p"/><path fill="url(#ihRhO1d)" class="pw9ealv2p"/></g><g filter="url(#iywYZie)"><path class="jkrirpl-o"/><path fill="url(#imwDlJd)" class="rgh259bpq"/></g><g filter="url(#iYDNt6b)"><path fill="url(#iApreGd)" class="pghtle90e"/></g><g filter="url(#iGPdVpw)"><path fill="url(#iGEVQob)" class="ucup5n5np"/></g><g filter="url(#iGy9Xpc)"><ellipse transform="rotate(-27.914 10.689 18.17)" class="ym1jfsbxi"/><ellipse fill="url(#ieWhtGb)" transform="rotate(-27.914 10.689 18.17)" class="e-_izibnw"/></g><g filter="url(#irg4URd)"><path fill="url(#iHjhXjb)" class="p7-d7ccuu"/></g><defs><radialGradient id="iHXhJ2b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 .48438 -.5037 -3.37957 6.633 19.25)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="dfgrzob2o"/><stop offset="1" class="a7g-75b1j"/></radialGradient><radialGradient id="iGSgjxb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.309 12.941)scale(2.01965)" gradientUnits="userSpaceOnUse"><stop class="p4z5r-b-d"/><stop offset="1" class="dp-1ekdei"/></radialGradient><radialGradient id="iHrguLc" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 4.107 21.808)scale(4.7194 4.52281)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="o3p45rbvx"/><stop offset="1" class="amvclhbwx"/></radialGradient><radialGradient id="ifzodCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.84823 -2.07813 2.05068 1.82382 25.98 18.844)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="qvuai0b6y"/><stop offset=".883" class="tbvggbbed"/></radialGradient><radialGradient id="iT8onyc" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -3.8125 2.99389 .63804 26.172 20.14)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rwi7dob8k"/><stop offset="1" class="x4eddproi"/></radialGradient><radialGradient id="iYBaiIg" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 10.00001 -3.04902 .41924 5.5 19.063)" gradientUnits="userSpaceOnUse"><stop class="sz3vslbub"/><stop offset="1" class="il6zdacve"/></radialGradient><radialGradient id="iWpUNJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -2.23438 2.81333 1.96736 21.249 17.968)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="ky2i9gfwu"/><stop offset="1" class="rjxs4hg5m"/></radialGradient><radialGradient id="i2VOQ0w" cx="0" cy="0" r="1" gradientTransform="rotate(-54.878 22.495 -2.228)scale(2.25417 3.17084)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="tvui7dbha"/><stop offset="1" class="zlafz0bxq"/></radialGradient><radialGradient id="iSGqOwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 20.328 18.406)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="uyq-lepzm"/><stop offset="1" class="mbk9t98yd"/></radialGradient><radialGradient id="imY1u4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 11.358 18.406)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="uyq-lepzm"/><stop offset="1" class="mbk9t98yd"/></radialGradient><radialGradient id="iDRMJqc" cx="0" cy="0" r="1" gradientTransform="matrix(7.82168 -1.52596 1.273 6.52503 12.031 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="stsoanbmy"/><stop offset="1" class="ovwdp-bik"/></radialGradient><radialGradient id="ivDDmPb" cx="0" cy="0" r="1" gradientTransform="rotate(-23.69 21.288 -25.479)scale(6.68877 6.45832)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="ovwdp-bik"/><stop offset=".912" class="stsoanbmy"/></radialGradient><radialGradient id="ivDz5rc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63771 -5.65242 5.82757 -3.75043 16.76 7.693)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="aj460xbwf"/><stop offset="1" class="rfngthbki"/></radialGradient><radialGradient id="ilAJJAe" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 4.875 -4.68236 2.94148 15.313 4.5)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="yjjmn1b0t"/><stop offset=".966" class="q4ez5acay"/></radialGradient><radialGradient id="iKJy5Sb" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 .04688 -.02424 .98567 15.36 21.156)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="tqddflbts"/><stop offset=".955" class="szge83bkx"/></radialGradient><radialGradient id="ihRhO1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.79467 0 16.133 20.547)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="jotp8y14r"/><stop offset="1" class="zlgw_eb1n"/></radialGradient><radialGradient id="imwDlJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5717 -.73672 1.01428 -.7871 19.765 18.614)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieWhtGb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.652 4.23)scale(1.21806 1.46416)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iQWOCle" width="4.539" height="4.539" x="4.363" y="16.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".125"/></filter><filter id="i1u1oYl" width="4.663" height="4.663" x="23.301" y="16.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".125"/></filter><filter id="iCpVn5c" width="23.65" height="26" x="4.753" y="3.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.34902 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24658"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.4 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24658" result="effect2_innerShadow_3987_24658"/></filter><filter id="itjURCb" width="7" height="2.4" x="12.633" y="22.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24658"/></filter><filter id="ig22bZc" width="3.72" height="1.592" x="9.113" y="13.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0313726 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24658"/></filter><filter id="ibAjzIm" width="3.17" height=".992" x="9.317" y="13.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".1"/></filter><filter id="iqiPoac" width="3.72" height="1.592" x="18.963" y="13.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0313726 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24658"/></filter><filter id="iabnEiP" width="3.17" height=".992" x="19.363" y="13.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".1"/></filter><filter id="iQhkaLd" width="7.877" height="8.718" x="12.162" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".25"/></filter><filter id="iCwKveb" width="8.1" height="8.529" x="11.931" y="1.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0313726 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24658"/></filter><filter id="iWgOPib" width="3.638" height="2.603" x="14.181" y="20.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".25"/></filter><filter id="il60DZn" width="3.138" height="2.103" x="14.564" y="20.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".125"/></filter><filter id="iywYZie" width="1.647" height="1.423" x="18.665" y="17.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".05"/></filter><filter id="iYDNt6b" width="1.611" height="1.666" x="20.881" y="17.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".1"/></filter><filter id="iGPdVpw" width="1.845" height="1.978" x="11.717" y="17.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".1"/></filter><filter id="iGy9Xpc" width="1.958" height="1.444" x="9.71" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation=".05"/></filter><filter id="irg4URd" width="13.584" height="12.368" x="14.564" y="3.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24658" stdDeviation="1.25"/></filter><linearGradient id="i4uGBJb" x1="3.808" x2="6.633" y1="19.25" y2="19" gradientUnits="userSpaceOnUse"><stop class="cl9_9ccwm"/><stop offset="1" class="k1igulbhf"/></linearGradient><linearGradient id="ipptGsb" x1="28.516" x2="25.933" y1="17.563" y2="21.75" gradientUnits="userSpaceOnUse"><stop class="hxeei7fsy"/><stop offset="1" class="trn388btv"/></linearGradient><linearGradient id="itgTC8b" x1="26.855" x2="27.5" y1="20.406" y2="17.984" gradientUnits="userSpaceOnUse"><stop class="j_83df0sk"/><stop offset="1" class="ngd5fmf0i"/></linearGradient><linearGradient id="iWz9HFI" x1="16.153" x2="16.153" y1="30" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="zwtu7acdo"/><stop offset="1" class="tqbblz5ki"/></linearGradient><linearGradient id="iNuGSdc" x1="8.938" x2="14.313" y1="20.625" y2="20.625" gradientUnits="userSpaceOnUse"><stop class="b8g00zlka"/><stop offset="1" class="wr31gnb3a"/></linearGradient><linearGradient id="iWI7Hrr" x1="13.797" x2="14.297" y1="24.484" y2="23.578" gradientUnits="userSpaceOnUse"><stop class="c62ncdc9p"/><stop offset="1" class="mo9bgo9qn"/></linearGradient><linearGradient id="idaX0nc" x1="12.531" x2="9.359" y1="14.078" y2="14.487" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iNh1Yfd" x1="22.577" x2="19.405" y1="14.026" y2="14.434" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iBApK5b" x1="16.459" x2="15.42" y1="2.495" y2="9.989" gradientUnits="userSpaceOnUse"><stop class="s4p8h2blt"/><stop offset="1" class="q2fusinmo"/></linearGradient><linearGradient id="iApreGd" x1="22.245" x2="21.472" y1="18.539" y2="19.016" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGEVQob" x1="13.191" x2="12.418" y1="18.539" y2="19.016" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHjhXjb" x1="17.804" x2="27.5" y1="13.969" y2="8.125" gradientUnits="userSpaceOnUse"><stop class="v4hf23p3e"/><stop offset="1" class="td_i0pbtq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-dark" /></template>
<style>
.a7g-75b1j {
  stop-color: var(--svg-color--695752, #695752);
}

.a9h4drbls {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.843 16.56c1.61 0 2.97 1.11 3.34 2.61c.11.43-.22.84-.66.84h-5.5c-.35 0-.63-.32-.56-.67c.31-1.58 1.7-2.78 3.38-2.78m-10 0c-1.61 0-2.97 1.11-3.34 2.61c-.11.43.22.84.66.84h5.5c.35 0 .63-.32.56-.67a3.454 3.454 0 0 0-3.38-2.78");
}

.aj460xbwf {
  stop-color: var(--svg-color--3e3431, #3E3431);
  stop-opacity: 0;
}

.amvclhbwx {
  stop-color: var(--svg-color--472d49, #472D49);
}

.b8g00zlka {
  stop-color: var(--svg-color--402e2d, #402E2D);
}

.bpta1ubgb {
  d: path("M25.633 21.331a2.081 2.081 0 1 0 0-4.163a2.081 2.081 0 0 0 0 4.163");
}

.c62ncdc9p {
  stop-color: var(--svg-color--6d6262, #6D6262);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl9_9ccwm {
  stop-color: var(--svg-color--382829, #382829);
}

.cuntytbpm {
  stroke: var(--svg-color--161515, #161515);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.613 14.58c.59-.21 1.41-.36 2.47-.26");
}

.d3p6e5btk {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.125 23.463a6.4 6.4 0 0 1-3.007-.733c-.299-.16-.617.181-.428.472a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.28-.13-.622-.428-.472a6.55 6.55 0 0 1-3.027.733");
}

.dfgrzob2o {
  stop-color: var(--svg-color--695752, #695752);
  stop-opacity: 0;
}

.dp-1ekdei {
  stop-color: var(--svg-color--251215, #251215);
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.e-_izibnw {
  cx: 10.689px;
  cy: 18.17px;
  rx: 0.96px;
  ry: 0.486px;
}

.ft5dv1b6b {
  fill: none;
}

.fwceehblp {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.668 14.487c.59-.21 1.41-.36 2.47-.26");
}

.h84bfz8td {
  d: path("M25.633 22.5a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.hxeei7fsy {
  stop-color: var(--svg-color--716362, #716362);
}

.i8t3aob6g {
  fill: var(--svg-color--4e302f, #4E302F);
  d: path("M23.362 5.212a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.112c.296 3.14 2.377 5.78 5.265 6.68c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.7-3.745-8.691");
}

.il6zdacve {
  stop-color: var(--svg-color--6b5853, #6B5853);
  stop-opacity: 0;
}

.j_83df0sk {
  stop-color: var(--svg-color--432e2e, #432E2E);
}

.j77jw4brz {
  stroke: var(--svg-color--161515, #161515);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.183 14.58c-.59-.21-1.41-.36-2.47-.26");
}

.jkrirpl-o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.171 17.695c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.125");
}

.jotp8y14r {
  stop-color: var(--svg-color--402336, #402336);
  stop-opacity: 0;
}

.k1igulbhf {
  stop-color: var(--svg-color--302325, #302325);
}

.ky2i9gfwu {
  stop-color: var(--svg-color--422628, #422628);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mo9bgo9qn {
  stop-color: var(--svg-color--6d6262, #6D6262);
  stop-opacity: 0;
}

.n9r5i0bal {
  d: path("M11.353 17.23a2.2 2.2 0 0 0-2.12 2.78h4.25c.05-.19.08-.38.08-.58c-.01-1.21-.99-2.2-2.21-2.2");
}

.ngd5fmf0i {
  stop-color: var(--svg-color--554445, #554445);
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.o3p45rbvx {
  stop-color: var(--svg-color--472d49, #472D49);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.otsp18aza {
  d: path("M23.362 5.212a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.112c.296 3.14 2.377 5.78 5.265 6.68c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.7-3.745-8.691");
}

.ovwdp-bik {
  stop-color: var(--svg-color--4b4849, #4B4849);
}

.p4z5r-b-d {
  stop-color: var(--svg-color--312329, #312329);
}

.p7-d7ccuu {
  d: path("m18.483 8.607l4.36-2.326c2.774 2 2.899 5.615 2.774 6.594l-5.513.75a2.679 2.679 0 0 1-1.621-5.018");
}

.panyp8b9r {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22.183 14.435c-.59-.21-1.41-.36-2.47-.26");
}

.pfo1lekmx {
  d: path("M15.831 1.5a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.pghtle90e {
  d: path("M22.292 19.14a2.07 2.07 0 0 0-.57-1.14l-.64.703l.288.563z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pw9ealv2p {
  d: path("M16.135 22.15c.51 0 .964-.28 1.225-.702c.238-.386-.011-.901-.445-.901h-1.56c-.434 0-.694.526-.444.9c.26.434.715.703 1.224.703");
}

.q2fusinmo {
  stop-color: var(--svg-color--2f1718, #2F1718);
}

.q4ez5acay {
  stop-color: var(--svg-color--1a1118, #1A1118);
}

.qvuai0b6y {
  stop-color: var(--svg-color--371e1f, #371E1F);
}

.qwle-9byr {
  fill: var(--svg-color--000, #000);
  d: path("M19.073 19.43c0-.7.56-1.26 1.26-1.26s1.26.56 1.26 1.26c0 .21-.05.41-.14.58h-2.23c-.1-.17-.15-.37-.15-.58m-6.46 0c0-.7-.56-1.26-1.26-1.26s-1.26.56-1.26 1.26c0 .21.05.41.14.58h2.23c.09-.17.15-.37.15-.58");
}

.rfngthbki {
  stop-color: var(--svg-color--3e3431, #3E3431);
}

.rgh259bpq {
  d: path("M20.171 17.695c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.125");
}

.rjxs4hg5m {
  stop-color: var(--svg-color--422628, #422628);
  stop-opacity: 0;
}

.rwi7dob8k {
  stop-color: var(--svg-color--56403d, #56403D);
  stop-opacity: 0.058;
}

.s4p8h2blt {
  stop-color: var(--svg-color--291816, #291816);
}

.stsoanbmy {
  stop-color: var(--svg-color--4c494a, #4C494A);
  stop-opacity: 0;
}

.sz3vslbub {
  stop-color: var(--svg-color--6b5853, #6B5853);
}

.szge83bkx {
  stop-color: var(--svg-color--6d5b59, #6D5B59);
}

.tbvggbbed {
  stop-color: var(--svg-color--371e1f, #371E1F);
  stop-opacity: 0;
}

.td_i0pbtq {
  stop-color: var(--svg-color--776867, #776867);
  stop-opacity: 0;
}

.tqbblz5ki {
  stop-color: var(--svg-color--4b2e50, #4B2E50);
  stop-opacity: 0;
}

.tqddflbts {
  stop-color: var(--svg-color--473130, #473130);
}

.trn388btv {
  stop-color: var(--svg-color--432935, #432935);
}

.tvui7dbha {
  stop-color: var(--svg-color--39222e, #39222E);
}

.ucup5n5np {
  d: path("M13.363 19.172c0-.711-.578-1.185-.735-1.328l-.71.687l.437.89z");
}

.uyq-lepzm {
  stop-color: var(--svg-color--886457, #886457);
}

.v4hf23p3e {
  stop-color: var(--svg-color--776867, #776867);
}

.vf5ztvkiw {
  d: path("M6.633 22.5a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.vibsggbex {
  d: path("M16.252 2.467c-1.473-.223-2.757-.003-3.59 1.11c1.994 0 4.463 1.673 4.325 3.843a2.97 2.97 0 0 1-.994 1.815a.492.492 0 0 0 .403.863A3.87 3.87 0 0 0 19.5 6.824c.298-2.087-1.164-4.04-3.248-4.357");
}

.vwmd-5b_e {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.153 22.664c-.367-.197-.757.223-.526.58l.063-.042a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.28-.13-.622-.428-.472a6.55 6.55 0 0 1-3.027.733a6.4 6.4 0 0 1-3.007-.733z");
}

.wj9jagqeu {
  fill: var(--svg-color--381c2e, #381C2E);
  d: path("M16.002 22.5c.51 0 .965-.28 1.225-.702c.238-.386-.011-.901-.445-.901h-1.56c-.433 0-.693.526-.444.9c.26.434.715.703 1.224.703");
}

.wlp8nn_ub {
  d: path("M6.633 21.27a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.wr31gnb3a {
  stop-color: var(--svg-color--402e2d, #402E2D);
  stop-opacity: 0;
}

.x377v9b5z {
  d: path("M20.333 17.23a2.2 2.2 0 0 1 2.12 2.78h-4.25c-.05-.19-.08-.38-.08-.58c0-1.21.99-2.2 2.21-2.2");
}

.x4eddproi {
  stop-color: var(--svg-color--56403d, #56403D);
}

.xt_7vw5fe {
  fill: var(--svg-color--211b1d, #211B1D);
  d: path("M15.831 1.5a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.yjjmn1b0t {
  stop-color: var(--svg-color--1a1118, #1A1118);
  stop-opacity: 0;
}

.ym1jfsbxi {
  cx: 10.689px;
  cy: 18.17px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.96px;
  ry: 0.486px;
}

.zlafz0bxq {
  stop-color: var(--svg-color--39222e, #39222E);
  stop-opacity: 0;
}

.zlgw_eb1n {
  stop-color: var(--svg-color--402336, #402336);
}

.zwtu7acdo {
  stop-color: var(--svg-color--4b2e50, #4B2E50);
}

</style>
