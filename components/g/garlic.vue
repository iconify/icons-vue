<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mljdzn9ih"/><path fill="url(#immUIRd)" class="wgosexc8u"/><path fill="url(#ij9NwJc)" class="wgosexc8u"/><path fill="url(#iD3YGyc)" class="wgosexc8u"/><path fill="url(#ibJJvld)" class="wgosexc8u"/><g filter="url(#iqMjWPb)"><path fill="url(#iw5WN6b)" class="jwspbvbbw"/></g><path class="ge9ic6bjo"/><path fill="url(#iE30Sfe)" class="p2mj-djxc"/><path fill="url(#iXR1cBY)" class="p2mj-djxc"/><path fill="url(#iCxiVro)" class="p2mj-djxc"/><path fill="url(#itHbNbd)" class="p2mj-djxc"/><g filter="url(#i90Ffii)"><path fill="url(#iILGWTd)" class="l3ddltbdn"/></g><path fill="url(#iLozSec)" class="twt4a1dji"/><path fill="url(#iAY1fHQ)" class="twt4a1dji"/><path fill="url(#ibNr7Kb)" class="twt4a1dji"/><path fill="url(#iHARyAb)" class="twt4a1dji"/><path fill="url(#igKAETz)" class="twt4a1dji"/><path fill="url(#i3Mc5Bc)" class="twt4a1dji"/><path fill="url(#iwUyamd)" class="twt4a1dji"/><path fill="url(#ik1YQic)" class="twt4a1dji"/><g filter="url(#ia9otYK)"><path fill="url(#idBnr2b)" class="vho5lobci"/></g><g filter="url(#iIopIwc)"><path fill="url(#iLHodGe)" class="e3sxz-b6x"/></g><defs><radialGradient id="ij9NwJc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25 7.5 -4.75672 -3.3297 5.625 11.938)" gradientUnits="userSpaceOnUse"><stop class="ftwxcactj"/><stop offset=".649" class="eycz3lbko"/><stop offset="1" class="k4yp7wwxa"/></radialGradient><radialGradient id="iD3YGyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 4.75 -4.41573 .98773 9.125 21.938)" gradientUnits="userSpaceOnUse"><stop class="capd0nbru"/><stop offset=".903" class="knc3qhbzf"/></radialGradient><radialGradient id="iE30Sfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.34374 -5.8125 0 26.5 19.063)" gradientUnits="userSpaceOnUse"><stop class="l75d_1b9u"/><stop offset=".594" class="zr8rgybdj"/><stop offset="1" class="m0ikkobrx"/></radialGradient><radialGradient id="iXR1cBY" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 8.875 -8.60337 2.72642 21.938 26.313)" gradientUnits="userSpaceOnUse"><stop class="ox7_41e3c"/><stop offset=".265" class="s7_61-oxa"/><stop offset=".951" class="e1ad8bc2n"/></radialGradient><radialGradient id="iCxiVro" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 8.375 -6.27583 .60885 22.75 6.813)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="zs58v279x"/><stop offset=".693" class="l47cpkb3t"/></radialGradient><radialGradient id="iLozSec" cx="0" cy="0" r="1" gradientTransform="rotate(167.546 10.252 10.668)scale(13.9111 18.2687)" gradientUnits="userSpaceOnUse"><stop class="hktq_db7n"/><stop offset=".39" class="s8n3fvylh"/><stop offset=".792" class="ye5w_s8br"/><stop offset="1" class="fq3b3hb-o"/></radialGradient><radialGradient id="iAY1fHQ" cx="0" cy="0" r="1" gradientTransform="matrix(3.75001 11.375 -9.86913 3.25357 14.188 26.75)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="ke725u6-g"/><stop offset=".501" class="eq42_ew9r"/><stop offset=".83" class="ly4y05boy"/></radialGradient><radialGradient id="ibNr7Kb" cx="0" cy="0" r="1" gradientTransform="rotate(88.161 5.34 12.65)scale(6.81601 2.04923)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="mojndmbum"/><stop offset=".692" class="diuoopmos"/><stop offset="1" class="xfa5fvbbi"/></radialGradient><radialGradient id="iHARyAb" cx="0" cy="0" r="1" gradientTransform="rotate(110.556 1.855 8.872)scale(8.01 4.94789)" gradientUnits="userSpaceOnUse"><stop class="yjvp-3bxa"/><stop offset="1" class="q_nb74mqd"/></radialGradient><radialGradient id="igKAETz" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 3.25 -2.97653 1.37378 22 19.188)" gradientUnits="userSpaceOnUse"><stop class="mqunxhg2b"/><stop offset="1" class="tr24w6ikw"/></radialGradient><radialGradient id="i3Mc5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.625 9.9375 -6.00014 .37737 7.313 20.688)" gradientUnits="userSpaceOnUse"><stop class="l5mg6ybej"/><stop offset="1" class="v6ejm1b3h"/></radialGradient><radialGradient id="iwUyamd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5 -2.0599 0 16.078 3.844)" gradientUnits="userSpaceOnUse"><stop class="m8rnj7bzp"/><stop offset="1" class="ue8tzccgw"/></radialGradient><radialGradient id="ik1YQic" cx="0" cy="0" r="1" gradientTransform="matrix(4.18755 7.12497 -4.40119 2.5867 21.937 12.062)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="bgt17eb_c"/><stop offset="1" class="f5ob-aboo"/></radialGradient><linearGradient id="immUIRd" x1="9.836" x2="9.836" y1="4.422" y2="27.406" gradientUnits="userSpaceOnUse"><stop class="v36e6k_fy"/><stop offset=".433" class="fg7ohuvak"/><stop offset=".77" class="g987i6bfx"/><stop offset="1" class="txovdyb6a"/></linearGradient><linearGradient id="ibJJvld" x1="11.188" x2="12.094" y1="5.313" y2="6.969" gradientUnits="userSpaceOnUse"><stop class="tprau9kyu"/><stop offset=".387" class="wf02k8bir"/></linearGradient><linearGradient id="iw5WN6b" x1="11.591" x2="11.591" y1="4.422" y2="26.969" gradientUnits="userSpaceOnUse"><stop class="h3xco7bjf"/><stop offset="1" class="y_1uvbb6k"/></linearGradient><linearGradient id="itHbNbd" x1="22.136" x2="22.136" y1="4.422" y2="27.406" gradientUnits="userSpaceOnUse"><stop class="hfzpqgr-k"/><stop offset=".02" class="pdi72bbaz"/></linearGradient><linearGradient id="iILGWTd" x1="20.656" x2="20.656" y1="5" y2="26.875" gradientUnits="userSpaceOnUse"><stop class="qffkkibem"/><stop offset=".389" class="fr4e4lbok"/><stop offset=".694" class="yzaeetb2u"/><stop offset=".871" class="qry48f1dy"/><stop offset="1" class="agy_dhbrz"/></linearGradient><linearGradient id="idBnr2b" x1="14.525" x2="14.525" y1="4.961" y2="10.969" gradientUnits="userSpaceOnUse"><stop class="u4f7gvqil"/><stop offset=".758" class="q7a04pbqy"/><stop offset="1" class="mh358hkmc"/></linearGradient><linearGradient id="iLHodGe" x1="16.109" x2="16.109" y1="5.047" y2="10.656" gradientUnits="userSpaceOnUse"><stop class="d4x2bkbbr"/><stop offset="1" class="ugpfhbomm"/></linearGradient><filter id="iqMjWPb" width="8.274" height="23.506" x="7.626" y="4.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30809" stdDeviation=".5"/></filter><filter id="i90Ffii" width="8.903" height="23.746" x="16.222" y="4.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30809" stdDeviation=".5"/></filter><filter id="ia9otYK" width="1.737" height="7.508" x="13.656" y="4.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30809" stdDeviation=".25"/></filter><filter id="iIopIwc" width="2.281" height="6.609" x="14.969" y="4.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30809" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:garlic" /></template>
<style>
.agy_dhbrz {
  stop-color: var(--svg-color--b9538a, #B9538A);
}

.bgt17eb_c {
  stop-color: var(--svg-color--fce4c1, #FCE4C1);
}

.capd0nbru {
  stop-color: var(--svg-color--b35889, #B35889);
}

.d4x2bkbbr {
  stop-color: var(--svg-color--cdb0ab, #CDB0AB);
}

.diuoopmos {
  stop-color: var(--svg-color--dec1b8, #DEC1B8);
}

.e1ad8bc2n {
  stop-color: var(--svg-color--d17295, #D17295);
  stop-opacity: 0;
}

.e3sxz-b6x {
  d: path("M15.469 5.047h1.281v5.609h-1.281z");
}

.eq42_ew9r {
  stop-color: var(--svg-color--b46391, #B46391);
  stop-opacity: 0.342;
}

.eycz3lbko {
  stop-color: var(--svg-color--765a4d, #765A4D);
  stop-opacity: 0.262;
}

.f5ob-aboo {
  stop-color: var(--svg-color--ffe6c3, #FFE6C3);
  stop-opacity: 0;
}

.fg7ohuvak {
  stop-color: var(--svg-color--b98c7d, #B98C7D);
}

.fq3b3hb-o {
  stop-color: var(--svg-color--b08886, #B08886);
}

.fr4e4lbok {
  stop-color: var(--svg-color--dca996, #DCA996);
}

.ft5dv1b6b {
  fill: none;
}

.ftwxcactj {
  stop-color: var(--svg-color--977666, #977666);
}

.g987i6bfx {
  stop-color: var(--svg-color--c2888b, #C2888B);
}

.ge9ic6bjo {
  fill: var(--svg-color--ffc6ad, #FFC6AD);
  d: path("M15.803 4.422h3.059c.58 0 1.044.473 1.044 1.064V6.85c0 2.31.726 4.494 2.475 5.958l3.775 3.174c4.579 3.857 1.901 11.424-4.034 11.424h-5.427s-.892-15.244-.892-22.984");
}

.h3xco7bjf {
  stop-color: var(--svg-color--94676f, #94676F);
}

.hfzpqgr-k {
  stop-color: var(--svg-color--d1a690, #D1A690);
}

.hktq_db7n {
  stop-color: var(--svg-color--fffedc, #FFFEDC);
}

.jwspbvbbw {
  d: path("M14.9 5.778c.004-.277-.232-.5-.478-.372c-.21.111-.39.303-.39.605c0 2.151.312 5.514-.688 7.489c-1.145 2.26-3.069 2.384-4.157 4.906c-1.468 3.407 0 8.469 3.782 8.469C14.58 23.145 14.86 8.653 14.9 5.778");
}

.k4yp7wwxa {
  stop-color: var(--svg-color--6b5045, #6B5045);
  stop-opacity: 0;
}

.ke725u6-g {
  stop-color: var(--svg-color--b46490, #B46490);
}

.knc3qhbzf {
  stop-color: var(--svg-color--b16b84, #B16B84);
  stop-opacity: 0;
}

.l3ddltbdn {
  d: path("M18.332 6.156c.013-.45-.32-.789-.645-.98c-.25-.147-.483.069-.464.357l1.412 21.342c4.04 0 7.17-4.578 4.494-9.687c-1.063-2.03-2.612-3.257-4.035-5.657c-1.048-1.766-.817-3.433-.762-5.375");
}

.l47cpkb3t {
  stop-color: var(--svg-color--ffebd4, #FFEBD4);
  stop-opacity: 0;
}

.l5mg6ybej {
  stop-color: var(--svg-color--c39492, #C39492);
}

.l75d_1b9u {
  stop-color: var(--svg-color--ffead4, #FFEAD4);
}

.ly4y05boy {
  stop-color: var(--svg-color--b46292, #B46292);
  stop-opacity: 0;
}

.m0ikkobrx {
  stop-color: var(--svg-color--ffc7ae, #FFC7AE);
}

.m8rnj7bzp {
  stop-color: var(--svg-color--c1b197, #C1B197);
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.mljdzn9ih {
  fill: var(--svg-color--b8897d, #B8897D);
  d: path("M16.169 7.505V4.422h-3.047a1.05 1.05 0 0 0-1.044 1.064V6.85c0 2.31-.738 4.494-2.487 5.958l-3.776 3.174c-4.578 3.857-1.9 11.424 4.035 11.424h5.426s.893-14.042.893-19.9");
}

.mojndmbum {
  stop-color: var(--svg-color--fff8de, #FFF8DE);
}

.mqunxhg2b {
  stop-color: var(--svg-color--ffd, #FFD);
}

.ox7_41e3c {
  stop-color: var(--svg-color--af478a, #AF478A);
}

.p2mj-djxc {
  d: path("M15.803 4.422h3.059c.58 0 1.044.473 1.044 1.064V6.85c0 2.31.726 4.494 2.475 5.958l3.775 3.174c4.579 3.857 1.901 11.424-4.034 11.424h-5.427s-.892-15.244-.892-22.984");
}

.pdi72bbaz {
  stop-color: var(--svg-color--cfa58f, #CFA58F);
  stop-opacity: 0;
}

.q_nb74mqd {
  stop-color: var(--svg-color--9f8c79, #9F8C79);
  stop-opacity: 0;
}

.q7a04pbqy {
  stop-color: var(--svg-color--c2aca8, #C2ACA8);
}

.qffkkibem {
  stop-color: var(--svg-color--d29c97, #D29C97);
}

.qry48f1dy {
  stop-color: var(--svg-color--bb578c, #BB578C);
}

.s7_61-oxa {
  stop-color: var(--svg-color--ba558b, #BA558B);
}

.s8n3fvylh {
  stop-color: var(--svg-color--edc3b2, #EDC3B2);
}

.tprau9kyu {
  stop-color: var(--svg-color--967666, #967666);
}

.tr24w6ikw {
  stop-color: var(--svg-color--ffddc5, #FFDDC5);
  stop-opacity: 0;
}

.twt4a1dji {
  d: path("m17.625 7.572l.046-2.641a.5.5 0 0 0-.5-.51h-2.384a.5.5 0 0 0-.499.53l.15 2.62c.025.722-.062 2.785-.735 4.117c-1.145 2.265-2.413 3.138-3.828 5.5c-2.031 3.39-.531 10.218 3.703 10.218h4.735c3.75 0 6.375-5.11 3.89-10.218c-.987-2.03-2.538-3.1-3.86-5.5c-.718-1.305-.757-3.178-.718-4.116");
}

.txovdyb6a {
  stop-color: var(--svg-color--b14c8b, #B14C8B);
}

.u4f7gvqil {
  stop-color: var(--svg-color--c2a9a3, #C2A9A3);
}

.ue8tzccgw {
  stop-color: var(--svg-color--dac9ad, #DAC9AD);
  stop-opacity: 0;
}

.ugpfhbomm {
  stop-color: var(--svg-color--d6beaf, #D6BEAF);
  stop-opacity: 0;
}

.v36e6k_fy {
  stop-color: var(--svg-color--b38780, #B38780);
}

.v6ejm1b3h {
  stop-color: var(--svg-color--b28683, #B28683);
  stop-opacity: 0;
}

.vho5lobci {
  d: path("M14.813 5.156c-.126-.2-.282-.208-.344-.187c.25 3.406 0 4.656-.313 6.5c.813-1.469.813-6.063.656-6.313");
}

.wf02k8bir {
  stop-color: var(--svg-color--957665, #957665);
  stop-opacity: 0;
}

.wgosexc8u {
  d: path("M16.169 7.505V4.422h-3.047a1.05 1.05 0 0 0-1.044 1.064V6.85c0 2.31-.738 4.494-2.487 5.958l-3.776 3.174c-4.578 3.857-1.9 11.424 4.035 11.424h5.426s.893-14.042.893-19.9");
}

.xfa5fvbbi {
  stop-color: var(--svg-color--d6bab1, #D6BAB1);
  stop-opacity: 0;
}

.y_1uvbb6k {
  stop-color: var(--svg-color--a85284, #A85284);
}

.ye5w_s8br {
  stop-color: var(--svg-color--b6a18c, #B6A18C);
}

.yjvp-3bxa {
  stop-color: var(--svg-color--a08e79, #A08E79);
}

.yzaeetb2u {
  stop-color: var(--svg-color--df999f, #DF999F);
}

.zr8rgybdj {
  stop-color: var(--svg-color--ffcab0, #FFCAB0);
}

.zs58v279x {
  stop-color: var(--svg-color--ffeed5, #FFEED5);
}

</style>
