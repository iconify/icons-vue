<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i78Ue0d)" class="znvrq30dg"/><path fill="url(#izK4BXc)" class="znvrq30dg"/><path fill="url(#iHKwk7b)" class="znvrq30dg"/><path fill="url(#iUjJlYb)" class="znvrq30dg"/><path fill="url(#idIDZPb)" class="znvrq30dg"/><path fill="url(#igl9goM)" class="znvrq30dg"/><path fill="url(#iph0BFd)" class="znvrq30dg"/><path fill="url(#iKJjoze)" class="kho9070_o"/><path fill="url(#iOLPuUd)" class="kho9070_o"/><path fill="url(#iEFusDc)" class="kho9070_o"/><path fill="url(#inG1Aqc)" class="kho9070_o"/><path fill="url(#is6JYdc)" class="kho9070_o"/><path fill="url(#iDuPiTY)" class="kho9070_o"/><g filter="url(#ibu3Ywe)"><path fill="url(#ikHG1oc)" clip-rule="evenodd" class="bltumx24p"/></g><path fill="url(#iELIdad)" class="azm8o7dwm"/><path fill="url(#iscy8rb)" class="azm8o7dwm"/><path fill="url(#ifvNcld)" class="azm8o7dwm"/><path fill="url(#iZVFkBc)" class="i9-rovb-z"/><path fill="url(#iFpYUqe)" class="i9-rovb-z"/><path fill="url(#iLI7k0d)" class="i9-rovb-z"/><path fill="url(#ipV2RvI)" class="i9-rovb-z"/><path fill="url(#iRbHv5d)" class="i9-rovb-z"/><path fill="url(#is2gjmb)" class="cdkb_gbko"/><path fill="url(#iEm8Bce)" class="cdkb_gbko"/><path fill="url(#iB0JlCd)" class="cdkb_gbko"/><path fill="url(#iC61ufe)" class="cdkb_gbko"/><path fill="url(#ixekUce)" class="noxgkjuoq"/><path fill="url(#iRZqtge)" class="noxgkjuoq"/><path fill="url(#ih6QZzH)" class="noxgkjuoq"/><path fill="url(#i6doBEd)" class="noxgkjuoq"/><path fill="url(#iXh2TBe)" class="noxgkjuoq"/><path fill="url(#iettR1c)" class="noxgkjuoq"/><g filter="url(#itlnmlc)"><path fill="url(#i2TRRpd)" class="h4-5b-b3b"/></g><g filter="url(#iMBA7kc)"><path fill="url(#ik7ZSbc)" class="r5w48tbko"/></g><g filter="url(#iVWnpab)"><circle fill="url(#i0XXWVb)" class="ek0jnbjyh"/></g><g filter="url(#ixeuPAc)"><path stroke="url(#irLJQwb)" class="ueow9obtg"/></g><g filter="url(#izd2vLe)"><ellipse fill="url(#iKEXslK)" transform="rotate(36.536 23.93 5.018)" class="t6rgdfshg"/></g><g filter="url(#iiZDjcb)"><ellipse fill="url(#iEvtDBl)" transform="rotate(34.838 12.638 5.152)" class="sx2pl2-qf"/></g><path fill="url(#iqNeuAd)" class="vbuet1ybh"/><path fill="url(#i09mVBb)" class="vbuet1ybh"/><path fill="url(#i9i5Hac)" class="vbuet1ybh"/><path fill="url(#i4fkWge)" class="vbuet1ybh"/><g filter="url(#iwr4sue)"><ellipse fill="url(#ikokfyd)" transform="rotate(-28.298 15.229 10.432)" class="vdk17l3cf"/></g><defs><radialGradient id="iHKwk7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.0588 3.82186 -1.1095 .59768 16.808 9.242)" gradientUnits="userSpaceOnUse"><stop class="s0ufkwb8b"/><stop offset="1" class="rgd1vib-k"/></radialGradient><radialGradient id="iUjJlYb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31608 3.32872 -.66907 -.66653 16.49 9.101)" gradientUnits="userSpaceOnUse"><stop class="s0ufkwb8b"/><stop offset="1" class="rgd1vib-k"/></radialGradient><radialGradient id="idIDZPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66492 3.08217 -2.20708 -1.19222 16.808 12.042)" gradientUnits="userSpaceOnUse"><stop class="turgb2kwj"/><stop offset="1" class="d4r1qgwfp"/></radialGradient><radialGradient id="igl9goM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6875 5.5 0 16.965 21.697)" gradientUnits="userSpaceOnUse"><stop class="k_q_swp3x"/><stop offset="1" class="ta1mmdb2y"/></radialGradient><radialGradient id="iph0BFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.34375 -1.75 0 17.059 14.354)" gradientUnits="userSpaceOnUse"><stop class="jvznk1btq"/><stop offset="1" class="pw-cz6b-o"/></radialGradient><radialGradient id="iKJjoze" cx="0" cy="0" r="1" gradientTransform="matrix(-.11426 4.68082 -10.79918 -.2636 12.44 4.99)" gradientUnits="userSpaceOnUse"><stop class="z6q45nb8k"/><stop offset="1" class="c684h3qwq"/></radialGradient><radialGradient id="iOLPuUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.36814 -6.17429 0 11.302 6.132)" gradientUnits="userSpaceOnUse"><stop class="s6gql-lox"/><stop offset="1" class="bht7z6b3k"/></radialGradient><radialGradient id="is6JYdc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.47893 1.19918 -.48178 -1.39769 9.79 8.5)" gradientUnits="userSpaceOnUse"><stop class="knnvrdb1c"/><stop offset="1" class="me838rbhy"/></radialGradient><radialGradient id="iDuPiTY" cx="0" cy="0" r="1" gradientTransform="matrix(-7.98072 .50546 -.41883 -6.61296 12.457 7.516)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="i2copv-9c"/><stop offset=".984" class="k3smzdfzf"/></radialGradient><radialGradient id="ikHG1oc" cx="0" cy="0" r="1" gradientTransform="matrix(-12.5625 0 0 -10.6845 24.277 25.947)" gradientUnits="userSpaceOnUse"><stop class="b-npy9bph"/><stop offset="1" class="nhi61ybwr"/></radialGradient><radialGradient id="iELIdad" cx="0" cy="0" r="1" gradientTransform="matrix(-12.9552 0 0 -13.6351 25.557 6.583)" gradientUnits="userSpaceOnUse"><stop class="tqwv7rbmi"/><stop offset="1" class="ogc755bvv"/></radialGradient><radialGradient id="iscy8rb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.39188 0 0 -4.17791 24.93 5.905)" gradientUnits="userSpaceOnUse"><stop class="njp3v8brf"/><stop offset="1" class="hsvnbjb2q"/></radialGradient><radialGradient id="iZVFkBc" cx="0" cy="0" r="1" gradientTransform="rotate(136.119 9.02 9.106)scale(3.63151 6.30902)" gradientUnits="userSpaceOnUse"><stop class="wbrhw-a3f"/><stop offset="1" class="bflrrb2kn"/></radialGradient><radialGradient id="iFpYUqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.21 -1.33265 5.4858 4.98092 19.612 13.438)" gradientUnits="userSpaceOnUse"><stop class="u0uvrl57z"/><stop offset="1" class="mpog9pbws"/></radialGradient><radialGradient id="iLI7k0d" cx="0" cy="0" r="1" gradientTransform="matrix(10.35146 6.07098 -5.61932 9.58134 13.933 7.787)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="l7e42zbzu"/><stop offset="1" class="u4d608b9y"/></radialGradient><radialGradient id="ipV2RvI" cx="0" cy="0" r="1" gradientTransform="matrix(-.48152 -2.04832 1.03723 -.24383 18.785 11.723)" gradientUnits="userSpaceOnUse"><stop class="hhyiprbyf"/><stop offset="1" class="obi8hkbgj"/></radialGradient><radialGradient id="is2gjmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3659 6.1753 -5.60794 -3.05666 13.653 10.305)" gradientUnits="userSpaceOnUse"><stop class="eem5z5bgx"/><stop offset="1" class="i1vauib5r"/></radialGradient><radialGradient id="iEm8Bce" cx="0" cy="0" r="1" gradientTransform="rotate(134.648 3.789 8.165)scale(3.95065 1.19038)" gradientUnits="userSpaceOnUse"><stop class="q9pq5y0wh"/><stop offset="1" class="cfjkb2b5j"/></radialGradient><radialGradient id="iB0JlCd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50226 1.5672 -1.4828 -1.42137 13.174 11.06)" gradientUnits="userSpaceOnUse"><stop class="lw1yd2bzc"/><stop offset="1" class="y-c4zmzga"/></radialGradient><radialGradient id="ixekUce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92187 2.24055 -2.82735 -2.42522 18.979 13.01)" gradientUnits="userSpaceOnUse"><stop class="m7xkaub6o"/><stop offset="1" class="itbdozb4y"/></radialGradient><radialGradient id="iRZqtge" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.16569 2.37771 .27448 18.073 15.01)" gradientUnits="userSpaceOnUse"><stop class="rrghrubou"/><stop offset="1" class="zu9od1bds"/></radialGradient><radialGradient id="ih6QZzH" cx="0" cy="0" r="1" gradientTransform="rotate(-125.655 13.567 2.448)scale(.44229 1.42759)" gradientUnits="userSpaceOnUse"><stop class="jifi4guxg"/><stop offset="1" class="dwc8e7rxl"/></radialGradient><radialGradient id="i6doBEd" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 -.34375 .56697 .87623 16.494 14.282)" gradientUnits="userSpaceOnUse"><stop class="jifi4guxg"/><stop offset="1" class="dwc8e7rxl"/></radialGradient><radialGradient id="iXh2TBe" cx="0" cy="0" r="1" gradientTransform="matrix(3.746 -2.52167 2.23979 3.32726 16.709 14.405)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="q3its-gbz"/><stop offset="1" class="s3f7e_b_x"/></radialGradient><radialGradient id="iettR1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.59191 -.53915 0 16.455 12.088)" gradientUnits="userSpaceOnUse"><stop class="fj6wbrn4a"/><stop offset="1" class="sycyf3r5m"/></radialGradient><radialGradient id="i0XXWVb" cx="0" cy="0" r="1" gradientTransform="rotate(151.44 8.084 8.765)scale(2.37084)" gradientUnits="userSpaceOnUse"><stop class="l8iihihqc"/><stop offset="1" class="o15z220fn"/></radialGradient><radialGradient id="irLJQwb" cx="0" cy="0" r="1" gradientTransform="rotate(132.065 9.107 8.965)scale(1.53074 4.60025)" gradientUnits="userSpaceOnUse"><stop class="nbaivqvxv"/><stop offset="1" class="az5nixb_q"/></radialGradient><radialGradient id="iKEXslK" cx="0" cy="0" r="1" gradientTransform="matrix(-3.54684 -.13148 .02447 -.66013 25.78 4.83)" gradientUnits="userSpaceOnUse"><stop class="gvuxz-h-v"/><stop offset="1" class="fi40vtj0l"/></radialGradient><radialGradient id="iEvtDBl" cx="0" cy="0" r="1" gradientTransform="rotate(172.726 7.579 2.913)scale(4.96326 1.74112)" gradientUnits="userSpaceOnUse"><stop class="seat-y7nu"/><stop offset="1" class="fbajdfbma"/></radialGradient><radialGradient id="iqNeuAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91226 2.22934 -2.81321 -2.41309 14.996 11)" gradientUnits="userSpaceOnUse"><stop class="v_jz3ruoj"/><stop offset="1" class="itbdozb4y"/></radialGradient><radialGradient id="i09mVBb" cx="0" cy="0" r="1" gradientTransform="matrix(.24875 -2.15486 2.36582 .2731 14.094 12.99)" gradientUnits="userSpaceOnUse"><stop class="z0_740bym"/><stop offset="1" class="sy1ce4b2s"/></radialGradient><radialGradient id="i9i5Hac" cx="0" cy="0" r="1" gradientTransform="matrix(.12438 -.38867 .89194 .28543 13.846 13.059)" gradientUnits="userSpaceOnUse"><stop class="jifi4guxg"/><stop offset="1" class="dwc8e7rxl"/></radialGradient><radialGradient id="i4fkWge" cx="0" cy="0" r="1" gradientTransform="matrix(3.72727 -2.50906 2.22859 3.31062 12.738 12.388)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="q3its-gbz"/><stop offset="1" class="s3f7e_b_x"/></radialGradient><radialGradient id="ikokfyd" cx="0" cy="0" r="1" gradientTransform="rotate(149.172 6.386 7.27)scale(2.2816 2.3911)" gradientUnits="userSpaceOnUse"><stop class="l8iihihqc"/><stop offset="1" class="o15z220fn"/></radialGradient><linearGradient id="i78Ue0d" x1="13.996" x2="18.985" y1="17.418" y2="17.418" gradientUnits="userSpaceOnUse"><stop class="yti5xtyye"/><stop offset=".476" class="nipi-xb9u"/><stop offset="1" class="koqh25kmv"/></linearGradient><linearGradient id="izK4BXc" x1="17.796" x2="17.608" y1="10.126" y2="15.461" gradientUnits="userSpaceOnUse"><stop class="fgwsvxs0l"/><stop offset="1" class="jbrpnkbdp"/></linearGradient><linearGradient id="iEFusDc" x1="15.765" x2="14.47" y1="8.786" y2="6.657" gradientUnits="userSpaceOnUse"><stop class="fpn960bvz"/><stop offset="1" class="jo_lu387v"/></linearGradient><linearGradient id="inG1Aqc" x1="9.29" x2="9.29" y1="8.896" y2="7.938" gradientUnits="userSpaceOnUse"><stop class="x8klxo89l"/><stop offset="1" class="dxzlvebbe"/></linearGradient><linearGradient id="ifvNcld" x1="23.822" x2="23.822" y1="9.25" y2="7.969" gradientUnits="userSpaceOnUse"><stop class="avvvvq2yl"/><stop offset="1" class="vjz02wh1m"/></linearGradient><linearGradient id="iRbHv5d" x1="18.944" x2="19.631" y1="12.397" y2="11.709" gradientUnits="userSpaceOnUse"><stop class="uy2av3plo"/><stop offset="1" class="s_4sbejos"/></linearGradient><linearGradient id="iC61ufe" x1="11.901" x2="11.615" y1="12.555" y2="12.294" gradientUnits="userSpaceOnUse"><stop class="n9p9ibcmz"/><stop offset="1" class="qpq9-xljm"/></linearGradient><linearGradient id="i2TRRpd" x1="3.59" x2="30.027" y1="29.01" y2="29.01" gradientUnits="userSpaceOnUse"><stop class="vyk-j44ve"/><stop offset="1" class="rupjhabwp"/></linearGradient><linearGradient id="ik7ZSbc" x1="14.485" x2="11.288" y1="8.745" y2="9.385" gradientUnits="userSpaceOnUse"><stop class="zily7gznb"/><stop offset="1" class="r9nou88mb"/></linearGradient><filter id="ibu3Ywe" width="24.559" height="6.74" x="4.351" y="21.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.611765 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5248"/></filter><filter id="itlnmlc" width="28.748" height="3.25" x="1.991" y="25.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.952941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5248"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.411765 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5248" result="effect2_innerShadow_18_5248"/></filter><filter id="iMBA7kc" width="6.359" height="4.755" x="9.787" y="6.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5248" stdDeviation=".25"/></filter><filter id="iVWnpab" width="3.618" height="3.618" x="17.176" y="10.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5248" stdDeviation=".5"/></filter><filter id="ixeuPAc" width="6.351" height="4.727" x="17.705" y="6.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5248" stdDeviation=".25"/></filter><filter id="izd2vLe" width="4.665" height="3.984" x="21.598" y="3.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5248" stdDeviation=".375"/></filter><filter id="iiZDjcb" width="5.096" height="4.548" x="10.09" y="2.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5248" stdDeviation=".375"/></filter><filter id="iwr4sue" width="3.557" height="3.638" x="13.45" y="8.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5248" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:desert-island" /></template>
<style>
.avvvvq2yl {
  stop-color: var(--svg-color--95a096, #95A096);
}

.az5nixb_q {
  stop-color: var(--svg-color--80b35c, #80B35C);
  stop-opacity: 0;
}

.azm8o7dwm {
  d: path("M21.385 8.5h-5a.467.467 0 0 1-.477-.5c.255-2.789 2.625-5 5.477-5c2.67 0 4.92 1.95 5.4 4.49c.1.53-.33 1.01-.87 1.01z");
}

.b-npy9bph {
  stop-color: var(--svg-color--ffc351, #FFC351);
}

.bflrrb2kn {
  stop-color: var(--svg-color--517d2a, #517D2A);
}

.bht7z6b3k {
  stop-color: var(--svg-color--9ac644, #9AC644);
  stop-opacity: 0;
}

.bltumx24p {
  fill-rule: evenodd;
  d: path("M28.76 28.01H4.35a14.58 14.58 0 0 1 12.205-6.59c5.106 0 9.597 2.62 12.204 6.59");
}

.c684h3qwq {
  stop-color: var(--svg-color--799d4b, #799D4B);
}

.cdkb_gbko {
  d: path("m12.645 12.18l3.07-3.07c.36-.36.33-.99-.1-1.28c-2.05-1.4-4.89-1.19-6.7.62s-2.02 4.66-.62 6.7c.29.43.91.46 1.28.1z");
}

.cfjkb2b5j {
  stop-color: var(--svg-color--69785c, #69785C);
  stop-opacity: 0;
}

.d4r1qgwfp {
  stop-color: var(--svg-color--422026, #422026);
  stop-opacity: 0;
}

.dwc8e7rxl {
  stop-color: var(--svg-color--ad619b, #AD619B);
  stop-opacity: 0;
}

.dxzlvebbe {
  stop-color: var(--svg-color--9c99a6, #9C99A6);
  stop-opacity: 0;
}

.eem5z5bgx {
  stop-color: var(--svg-color--65943f, #65943F);
}

.ek0jnbjyh {
  cx: 18.985px;
  cy: 12.783px;
  r: 0.809px;
}

.fbajdfbma {
  stop-color: var(--svg-color--b8e172, #B8E172);
  stop-opacity: 0;
}

.fgwsvxs0l {
  stop-color: var(--svg-color--734951, #734951);
}

.fi40vtj0l {
  stop-color: var(--svg-color--c0ef77, #C0EF77);
  stop-opacity: 0;
}

.fj6wbrn4a {
  stop-color: var(--svg-color--893e2f, #893E2F);
}

.fpn960bvz {
  stop-color: var(--svg-color--5d9501, #5D9501);
}

.ft5dv1b6b {
  fill: none;
}

.gvuxz-h-v {
  stop-color: var(--svg-color--c0ef77, #C0EF77);
}

.h4-5b-b3b {
  d: path("M30.49 27.916c0-.578-.333-.87-.985-1.101c-.75-.266-1.464-.805-2.644-.805c-1.72 0-1.72 1-3.44 1s-1.72-1-3.45-1c-1.72 0-1.72 1-3.45 1c-1.72 0-1.72-1-3.45-1c-1.72 0-1.72 1-3.44 1s-1.72-1-3.45-1c-1.38 0-1.94.63-2.89.88c-.47.13-.8.56-.8 1.04c0 .6.48 1.08 1.08 1.08h25.8c.845 0 1.118-.68 1.118-1.094");
}

.hhyiprbyf {
  stop-color: var(--svg-color--3e6a0c, #3E6A0C);
}

.hsvnbjb2q {
  stop-color: var(--svg-color--a3cf56, #A3CF56);
  stop-opacity: 0;
}

.i1vauib5r {
  stop-color: var(--svg-color--4c712c, #4C712C);
}

.i2copv-9c {
  stop-color: var(--svg-color--82ab5a, #82AB5A);
  stop-opacity: 0;
}

.i9-rovb-z {
  d: path("m19.175 12.11l-2.98-2.98c-.35-.35-.32-.96.09-1.24c1.99-1.36 4.75-1.15 6.51.6c1.76 1.76 1.96 4.52.6 6.51c-.28.41-.89.45-1.24.09z");
}

.itbdozb4y {
  stop-color: var(--svg-color--82582f, #82582F);
}

.jbrpnkbdp {
  stop-color: var(--svg-color--734951, #734951);
  stop-opacity: 0;
}

.jifi4guxg {
  stop-color: var(--svg-color--ad619b, #AD619B);
}

.jo_lu387v {
  stop-color: var(--svg-color--5d9501, #5D9501);
  stop-opacity: 0;
}

.jvznk1btq {
  stop-color: var(--svg-color--63353b, #63353B);
}

.k_q_swp3x {
  stop-color: var(--svg-color--733629, #733629);
}

.k3smzdfzf {
  stop-color: var(--svg-color--82ab5a, #82AB5A);
}

.kho9070_o {
  d: path("M10.545 8.5h5a.467.467 0 0 0 .477-.5c-.255-2.789-2.625-5-5.477-5c-2.67 0-4.92 1.95-5.4 4.49c-.11.52.33 1.01.87 1.01z");
}

.knnvrdb1c {
  stop-color: var(--svg-color--66981b, #66981B);
}

.koqh25kmv {
  stop-color: var(--svg-color--906c65, #906C65);
}

.l7e42zbzu {
  stop-color: var(--svg-color--6c9543, #6C9543);
  stop-opacity: 0;
}

.l8iihihqc {
  stop-color: var(--svg-color--d79f87, #D79F87);
}

.lw1yd2bzc {
  stop-color: var(--svg-color--4e5e45, #4E5E45);
}

.m7xkaub6o {
  stop-color: var(--svg-color--b97056, #B97056);
}

.me838rbhy {
  stop-color: var(--svg-color--66981b, #66981B);
  stop-opacity: 0;
}

.mpog9pbws {
  stop-color: var(--svg-color--576043, #576043);
  stop-opacity: 0;
}

.n9p9ibcmz {
  stop-color: var(--svg-color--617247, #617247);
}

.nbaivqvxv {
  stop-color: var(--svg-color--80b35c, #80B35C);
}

.nhi61ybwr {
  stop-color: var(--svg-color--f07b4c, #F07B4C);
}

.nipi-xb9u {
  stop-color: var(--svg-color--7e4d54, #7E4D54);
}

.njp3v8brf {
  stop-color: var(--svg-color--a3cf56, #A3CF56);
}

.noxgkjuoq {
  d: path("M18.455 15.01a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.o15z220fn {
  stop-color: var(--svg-color--d79f87, #D79F87);
  stop-opacity: 0;
}

.obi8hkbgj {
  stop-color: var(--svg-color--3e6a0c, #3E6A0C);
  stop-opacity: 0;
}

.ogc755bvv {
  stop-color: var(--svg-color--679e15, #679E15);
}

.pw-cz6b-o {
  stop-color: var(--svg-color--63353b, #63353B);
  stop-opacity: 0;
}

.q3its-gbz {
  stop-color: var(--svg-color--ac794f, #AC794F);
  stop-opacity: 0;
}

.q9pq5y0wh {
  stop-color: var(--svg-color--69785c, #69785C);
}

.qpq9-xljm {
  stop-color: var(--svg-color--617247, #617247);
  stop-opacity: 0;
}

.r5w48tbko {
  d: path("m15.646 8.62l-2.565 2.405l-2.794-3.482c2.246-.723 4.344.118 5.359 1.077");
}

.r9nou88mb {
  stop-color: var(--svg-color--7c9d5a, #7C9D5A);
  stop-opacity: 0;
}

.rgd1vib-k {
  stop-color: var(--svg-color--4b2231, #4B2231);
  stop-opacity: 0;
}

.rrghrubou {
  stop-color: var(--svg-color--b5547d, #B5547D);
}

.rupjhabwp {
  stop-color: var(--svg-color--6dd5ff, #6DD5FF);
}

.s_4sbejos {
  stop-color: var(--svg-color--394b28, #394B28);
  stop-opacity: 0;
}

.s0ufkwb8b {
  stop-color: var(--svg-color--4b2231, #4B2231);
}

.s3f7e_b_x {
  stop-color: var(--svg-color--ac794f, #AC794F);
}

.s6gql-lox {
  stop-color: var(--svg-color--9ac644, #9AC644);
}

.seat-y7nu {
  stop-color: var(--svg-color--b8e172, #B8E172);
}

.sx2pl2-qf {
  cx: 12.638px;
  cy: 5.152px;
  rx: 2.021px;
  ry: 1.213px;
}

.sy1ce4b2s {
  stop-color: var(--svg-color--ac4d77, #AC4D77);
  stop-opacity: 0;
}

.sycyf3r5m {
  stop-color: var(--svg-color--893e2f, #893E2F);
  stop-opacity: 0;
}

.t6rgdfshg {
  cx: 23.93px;
  cy: 5.018px;
  rx: 1.917px;
  ry: 0.608px;
}

.ta1mmdb2y {
  stop-color: var(--svg-color--733629, #733629);
  stop-opacity: 0;
}

.tqwv7rbmi {
  stop-color: var(--svg-color--a3d350, #A3D350);
}

.turgb2kwj {
  stop-color: var(--svg-color--422026, #422026);
}

.u0uvrl57z {
  stop-color: var(--svg-color--576043, #576043);
}

.u4d608b9y {
  stop-color: var(--svg-color--6c9543, #6C9543);
}

.ueow9obtg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.455 7.712c.915-.11 4.047.5 4.85 3.215");
}

.uy2av3plo {
  stop-color: var(--svg-color--394b28, #394B28);
}

.v_jz3ruoj {
  stop-color: var(--svg-color--aa674f, #AA674F);
}

.vbuet1ybh {
  d: path("M14.475 12.99a1.99 1.99 0 1 0 0-3.98a1.99 1.99 0 0 0 0 3.98");
}

.vdk17l3cf {
  cx: 15.229px;
  cy: 10.432px;
  rx: 0.761px;
  ry: 0.835px;
}

.vjz02wh1m {
  stop-color: var(--svg-color--95a096, #95A096);
  stop-opacity: 0;
}

.vyk-j44ve {
  stop-color: var(--svg-color--5884ff, #5884FF);
}

.wbrhw-a3f {
  stop-color: var(--svg-color--74a550, #74A550);
}

.x8klxo89l {
  stop-color: var(--svg-color--9c99a6, #9C99A6);
}

.y-c4zmzga {
  stop-color: var(--svg-color--4e5e45, #4E5E45);
  stop-opacity: 0;
}

.yti5xtyye {
  stop-color: var(--svg-color--56322e, #56322E);
}

.z0_740bym {
  stop-color: var(--svg-color--ac4d77, #AC4D77);
}

.z6q45nb8k {
  stop-color: var(--svg-color--9ed141, #9ED141);
}

.zily7gznb {
  stop-color: var(--svg-color--7c9d5a, #7C9D5A);
}

.znvrq30dg {
  d: path("M18.465 8.36h-3.95c-.29 0-.52.23-.52.52v17.08c0 .29.23.52.52.52h3.95c.29 0 .52-.23.52-.52V8.89c0-.29-.23-.53-.52-.53");
}

.zu9od1bds {
  stop-color: var(--svg-color--b5547d, #B5547D);
  stop-opacity: 0;
}

</style>
