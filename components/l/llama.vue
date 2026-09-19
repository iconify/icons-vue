<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iCMwLhs)" class="tse1pgbsd"/><path fill="url(#iIIxt0c)" class="tse1pgbsd"/><path fill="url(#i6DkTWd)" class="tse1pgbsd"/><path fill="url(#i41Us9c)" class="tse1pgbsd"/><path fill="url(#isl1fhH)" class="tse1pgbsd"/><path fill="url(#igBREUd)" class="tse1pgbsd"/><path fill="url(#iGrlw3d)" class="m5dp9ncle"/><path fill="url(#iSns2pd)" class="m5dp9ncle"/><path fill="url(#iUepdhc)" class="m5dp9ncle"/><path fill="url(#iyUz9wq)" class="ggy8oqgjq"/><path fill="url(#iGOwk4c)" class="ggy8oqgjq"/><path fill="url(#i8wwYTb)" class="ggy8oqgjq"/><g filter="url(#ioUvWCc)"><path fill="url(#iG14xpb)" class="cu9owf-3s"/><path fill="url(#i0ocUec)" class="cu9owf-3s"/><path fill="url(#ikvvAeb)" class="cu9owf-3s"/><path fill="url(#iaCXYad)" class="cu9owf-3s"/><path fill="url(#iV01m2d)" class="cu9owf-3s"/><path fill="url(#i0mSlob)" class="cu9owf-3s"/><path fill="url(#iR9MAQb)" class="cu9owf-3s"/><path fill="url(#iflsTad)" class="cu9owf-3s"/><path fill="url(#ibQMGec)" class="cu9owf-3s"/><path fill="url(#izntcjZ)" class="rhttwyu8s"/></g><path fill="url(#iwOMC9b)" class="zkkwkki_c"/><path fill="url(#i0jS6nn)" class="zkkwkki_c"/><path fill="url(#iruuyjd)" class="zkkwkki_c"/><path fill="url(#iSpucpd)" class="zkkwkki_c"/><path fill="url(#igVQUZb)" class="g2inwgbbu"/><path fill="url(#i3AGgFZ)" class="g2inwgbbu"/><path fill="url(#iJXyEJd)" class="cu32rcbck"/><path fill="url(#i4WPpBc)" class="cu32rcbck"/><path fill="url(#ihvNYBd)" class="cu32rcbck"/><path fill="url(#iKPYdqk)" class="cu32rcbck"/><path fill="url(#iA0BGKb)" class="ddpt6h1ct"/><path fill="url(#iVA1IQe)" class="nk_73ac6p"/><g filter="url(#is9LA9H)"><path stroke="url(#iqBA48d)" class="ai9srtb9e"/></g><g filter="url(#i3fh3gd)"><path stroke="url(#iEEI81c)" class="i202febxk"/></g><g filter="url(#ibNZzZd)"><path stroke="url(#ic3Phbd)" class="kbaor5bbo"/></g><g filter="url(#iYnm6VY)"><path stroke="url(#ipjoz8c)" class="kg0q3wbfb"/></g><path fill="url(#i6X1BsL)" class="wakrmbbsr"/><path fill="url(#idVXehb)" class="wakrmbbsr"/><g filter="url(#inIMKab)"><path stroke="url(#inpjwyd)" class="t70hs4bdn"/></g><g filter="url(#i1na6Vd)"><path stroke="url(#iS8Eo6c)" class="wh9_b3gvv"/></g><defs><radialGradient id="iCMwLhs" cx="0" cy="0" r="1" gradientTransform="rotate(112.109 8.92 16.584)scale(3.2381)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="kuot97fmj"/><stop offset=".677" class="jyld_-b_l"/><stop offset="1" class="odebtccyv"/></radialGradient><radialGradient id="iIIxt0c" cx="0" cy="0" r="1" gradientTransform="rotate(107.684 7.695 18.662)scale(2.2632 2.14028)" gradientUnits="userSpaceOnUse"><stop class="nhxvt9but"/><stop offset="1" class="esxd31b0c"/></radialGradient><radialGradient id="i6DkTWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8437 -5.87501 3.53606 -1.1097 27.89 18.219)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="dbi1ugn_j"/><stop offset="1" class="odebtccyv"/></radialGradient><radialGradient id="i41Us9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.29687 -.8125 1.47262 2.35053 25.375 16.453)" gradientUnits="userSpaceOnUse"><stop class="odebtccyv"/><stop offset="1" class="dbi1ugn_j"/></radialGradient><radialGradient id="isl1fhH" cx="0" cy="0" r="1" gradientTransform="matrix(.87502 4.78125 -3.66968 .6716 26.655 12.594)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="xb7bkbbgh"/><stop offset=".96" class="waih3lbdk"/></radialGradient><radialGradient id="igBREUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.12612 1.07813 -.93486 -.10936 24.86 14.219)" gradientUnits="userSpaceOnUse"><stop class="lvda8uous"/><stop offset="1" class="sqmrghbhm"/></radialGradient><radialGradient id="iGrlw3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 -5.28125 1.77265 -.41956 15.61 28.156)" gradientUnits="userSpaceOnUse"><stop class="eno6ayisd"/><stop offset="1" class="dl7k3f01p"/></radialGradient><radialGradient id="iUepdhc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -.75 3.07633 6.53722 13.11 26.719)" gradientUnits="userSpaceOnUse"><stop class="wevqdhbej"/><stop offset="1" class="ez98g6b3k"/></radialGradient><radialGradient id="iyUz9wq" cx="0" cy="0" r="1" gradientTransform="rotate(-71.211 30.323 .11)scale(6.40373 1.58804)" gradientUnits="userSpaceOnUse"><stop class="eno6ayisd"/><stop offset="1" class="dl7k3f01p"/></radialGradient><radialGradient id="iGOwk4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.5 -4.6875 1.71122 1.27771 18.297 31)" gradientUnits="userSpaceOnUse"><stop class="gnw-dw1nf"/><stop offset="1" class="lrhgsxbom"/></radialGradient><radialGradient id="i8wwYTb" cx="0" cy="0" r="1" gradientTransform="rotate(13.888 -90.245 92.169)scale(1.90607 4.18001)" gradientUnits="userSpaceOnUse"><stop class="wevqdhbej"/><stop offset="1" class="ez98g6b3k"/></radialGradient><radialGradient id="i0ocUec" cx="0" cy="0" r="1" gradientTransform="matrix(9.37503 -9.06254 6.0787 6.28831 15.11 28.5)" gradientUnits="userSpaceOnUse"><stop class="tjue4hbkk"/><stop offset="1" class="q3whbiz9s"/></radialGradient><radialGradient id="ikvvAeb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.851 52.487 13.85)scale(16.1876 37.331)" gradientUnits="userSpaceOnUse"><stop class="tjue4hbkk"/><stop offset=".942" class="q3whbiz9s"/></radialGradient><radialGradient id="iV01m2d" cx="0" cy="0" r="1" gradientTransform="matrix(.67188 1 -2.14477 1.44102 6.344 5.703)" gradientUnits="userSpaceOnUse"><stop class="w4nq0obzd"/><stop offset="1" class="k6-eazbnm"/></radialGradient><radialGradient id="i0mSlob" cx="0" cy="0" r="1" gradientTransform="matrix(9.0625 -.9375 .33542 3.2424 17.61 14.25)" gradientUnits="userSpaceOnUse"><stop class="vl66_rb7h"/><stop offset="1" class="hzsbm0mtl"/></radialGradient><radialGradient id="iR9MAQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 1.71875 -.59493 .384 7.687 3.922)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iflsTad" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 5.625 -2.96226 .67474 7.672 10.031)" gradientUnits="userSpaceOnUse"><stop class="e35z7jbmz"/><stop offset="1" class="eenlpz0ll"/></radialGradient><radialGradient id="ibQMGec" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 6.3125 -1.25427 .36014 10.36 9.688)" gradientUnits="userSpaceOnUse"><stop class="q7s_lsdao"/><stop offset="1" class="deg4gwy-t"/></radialGradient><radialGradient id="izntcjZ" cx="0" cy="0" r="1" gradientTransform="matrix(5.9375 -.125 .02915 1.38481 17.36 16.625)" gradientUnits="userSpaceOnUse"><stop class="q7s_lsdao"/><stop offset="1" class="deg4gwy-t"/></radialGradient><radialGradient id="iwOMC9b" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 -2.36437 4.42906 4.44897 24.422 26.25)" gradientUnits="userSpaceOnUse"><stop class="tjue4hbkk"/><stop offset="1" class="q3whbiz9s"/></radialGradient><radialGradient id="i0jS6nn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81256 -7.36499 6.858 -1.68779 27.922 29.99)" gradientUnits="userSpaceOnUse"><stop class="gnw-dw1nf"/><stop offset="1" class="lrhgsxbom"/></radialGradient><radialGradient id="iruuyjd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 1.10436 -2.40934 -5.24963 29.172 22.781)" gradientUnits="userSpaceOnUse"><stop class="g0ef-8prm"/><stop offset="1" class="g0dfzlbtk"/></radialGradient><radialGradient id="iJXyEJd" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 -.25 .46721 11.03792 3.39 8.844)" gradientUnits="userSpaceOnUse"><stop class="l08wh7bwu"/><stop offset="1" class="l52wh5qyl"/></radialGradient><radialGradient id="iKPYdqk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 0 0 -2.08478 8 9.906)" gradientUnits="userSpaceOnUse"><stop class="hhx86ob_n"/><stop offset="1" class="oa67vibei"/></radialGradient><radialGradient id="iA0BGKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 .64312 -.5597 -.29916 6.55 7.356)" gradientUnits="userSpaceOnUse"><stop class="ckq7otbdc"/><stop offset="1" class="jx0oumbhp"/></radialGradient><radialGradient id="iVA1IQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 .64312 -.65704 -.52679 3.896 8.357)" gradientUnits="userSpaceOnUse"><stop class="ckq7otbdc"/><stop offset="1" class="jx0oumbhp"/></radialGradient><linearGradient id="iSns2pd" x1="17.182" x2="14.707" y1="30.219" y2="25.161" gradientUnits="userSpaceOnUse"><stop class="fzvswcbdb"/><stop offset=".898" class="ykuuwbc-o"/></linearGradient><linearGradient id="iG14xpb" x1="15.856" x2="15.856" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="id08ivbsj"/><stop offset="1" class="ihr20616w"/></linearGradient><linearGradient id="iaCXYad" x1="6.391" x2="9.047" y1="19.375" y2="19.375" gradientUnits="userSpaceOnUse"><stop offset=".069" class="igovhqmbz"/><stop offset=".579" class="fqfl76byt"/></linearGradient><linearGradient id="iSpucpd" x1="29.516" x2="28.453" y1="26.938" y2="26.938" gradientUnits="userSpaceOnUse"><stop offset=".206" class="g0ef-8prm"/><stop offset="1" class="g0dfzlbtk"/></linearGradient><linearGradient id="igVQUZb" x1="11.77" x2="9.473" y1="30" y2="21.961" gradientUnits="userSpaceOnUse"><stop class="fzvswcbdb"/><stop offset=".676" class="ykuuwbc-o"/></linearGradient><linearGradient id="i3AGgFZ" x1="9.172" x2="10.484" y1="25.652" y2="25.652" gradientUnits="userSpaceOnUse"><stop class="wevqdhbej"/><stop offset="1" class="ez98g6b3k"/></linearGradient><linearGradient id="i4WPpBc" x1="4.406" x2="4.766" y1="6.984" y2="7.594" gradientUnits="userSpaceOnUse"><stop class="b1uf-cbwo"/><stop offset=".642" class="vgmyn_6gg"/></linearGradient><linearGradient id="ihvNYBd" x1="4.766" x2="4.766" y1="10.172" y2="9.484" gradientUnits="userSpaceOnUse"><stop class="vs5urib8a"/><stop offset=".925" class="nrz8m7mnn"/></linearGradient><linearGradient id="iqBA48d" x1="27.422" x2="29.109" y1="22.344" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="ybp50hbwu"/><stop offset="1" class="ktzmk3bsn"/></linearGradient><linearGradient id="iEEI81c" x1="9.734" x2="12.712" y1="8.5" y2="21.159" gradientUnits="userSpaceOnUse"><stop class="mrx9-i7eo"/><stop offset=".459" class="l0xhuwb2y"/><stop offset="1" class="mrx9-i7eo"/></linearGradient><linearGradient id="ic3Phbd" x1="15.109" x2="18.834" y1="23.438" y2="27.964" gradientUnits="userSpaceOnUse"><stop class="ez98g6b3k"/><stop offset=".364" class="cog7otbnm"/><stop offset="1" class="ez98g6b3k"/></linearGradient><linearGradient id="ipjoz8c" x1="21.891" x2="19.272" y1="24" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="ez98g6b3k"/><stop offset=".364" class="cog7otbnm"/><stop offset="1" class="ez98g6b3k"/></linearGradient><linearGradient id="i6X1BsL" x1="17.098" x2="17.098" y1="25.438" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".351" class="zbql46o9c"/><stop offset=".546" class="f3ratnbvg"/></linearGradient><linearGradient id="idVXehb" x1="17.098" x2="17.098" y1="27.031" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="zbql46o9c"/><stop offset="1" class="f3ratnbvg"/></linearGradient><linearGradient id="inpjwyd" x1="11.256" x2="13.479" y1="20.971" y2="27.457" gradientUnits="userSpaceOnUse"><stop class="wevqdhbej"/><stop offset="1" class="ez98g6b3k"/></linearGradient><linearGradient id="iS8Eo6c" x1="8.919" x2="11.067" y1="3.188" y2="5.126" gradientUnits="userSpaceOnUse"><stop class="mrx9-i7eo"/><stop offset=".459" class="l0xhuwb2y"/><stop offset="1" class="mrx9-i7eo"/></linearGradient><filter id="ioUvWCc" width="26.09" height="28.1" x="2.76" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752396 0 0 0 0 0.729792 0 0 0 0 0.775 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3359"/></filter><filter id="is9LA9H" width="4.394" height="10.289" x="24.678" y="19.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3359" stdDeviation=".375"/></filter><filter id="i3fh3gd" width="16.469" height="13.963" x="7.716" y="4.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3359" stdDeviation=".6"/></filter><filter id="ibNZzZd" width="3.063" height="7.063" x="14.047" y="23.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3359" stdDeviation=".25"/></filter><filter id="iYnm6VY" width="3.61" height="6.031" x="19.328" y="23.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3359" stdDeviation=".25"/></filter><filter id="inIMKab" width="1.5" height="7.813" x="10.266" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3359" stdDeviation=".25"/></filter><filter id="i1na6Vd" width="2.459" height="4.156" x="8.106" y="2.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3359" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:llama" /></template>
<style>
.ai9srtb9e {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M25.578 20.438v1.593l2.344 2.094l.25 5.094");
}

.b1uf-cbwo {
  stop-color: var(--svg-color--f2a56a, #F2A56A);
}

.ckq7otbdc {
  stop-color: var(--svg-color--605255, #605255);
}

.cog7otbnm {
  stop-color: var(--svg-color--e2cce3, #E2CCE3);
}

.cu32rcbck {
  d: path("M6.7 6c-.36 0-.72.1-1.03.29L3.48 7.64c-.36.23-.6.61-.62 1.03c-.03.73.55 1.33 1.27 1.33h3.49c.57 0 1.04-.47 1.04-1.05v-1C8.66 6.88 7.78 6 6.7 6");
}

.cu9owf-3s {
  d: path("m28.4 23.08l-1.27-.96a.94.94 0 0 1-.27-.66v-2.75c0-2.07-1.68-3.75-3.75-3.75h-8.17c-.66 0-1.27-.38-1.57-.97L9.9 3.5A2.23 2.23 0 0 0 7.8 2c-.18 0-.3.17-.24.34l.656 2.005c.106.323-.132.708-.453.819c-.348.12-.777.306-1.183.566L3.46 7.66c-.37.23-.6.64-.6 1.07c0 .7.57 1.27 1.27 1.27h2.73v8.26c0 2.01 1.25 3.72 3.01 4.41v7.02c-.01.17.13.31.3.31h1.37c.18 0 .32-.14.32-.31v-1.96c0-.17.07-.32.18-.44c.53-.52.82-1.23.82-1.97V23h5.07a4.46 4.46 0 0 0 2.958-1.126c.137-.123.388-.03.425.15c.148.71.6 1.311 1.328 1.796l3.96 2.43c.16.11.26.3.26.5v2.93c0 .17.14.31.31.31h1.37c.17 0 .31-.14.31-.31v-5.51c.01-.4-.15-.8-.45-1.09");
}

.dbi1ugn_j {
  stop-color: var(--svg-color--c0bbc3, #C0BBC3);
  stop-opacity: 0;
}

.ddpt6h1ct {
  d: path("M6.36 8a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.deg4gwy-t {
  stop-color: var(--svg-color--eee6f7, #EEE6F7);
  stop-opacity: 0;
}

.dl7k3f01p {
  stop-color: var(--svg-color--b49fbb, #B49FBB);
}

.e35z7jbmz {
  stop-color: var(--svg-color--ddd0e6, #DDD0E6);
}

.eenlpz0ll {
  stop-color: var(--svg-color--ddd0e6, #DDD0E6);
  stop-opacity: 0;
}

.eno6ayisd {
  stop-color: var(--svg-color--d8bedb, #D8BEDB);
}

.esxd31b0c {
  stop-color: var(--svg-color--d3bfd9, #D3BFD9);
  stop-opacity: 0;
}

.ez98g6b3k {
  stop-color: var(--svg-color--e1c7e3, #E1C7E3);
  stop-opacity: 0;
}

.f3ratnbvg {
  stop-color: var(--svg-color--bb7cb7, #BB7CB7);
  stop-opacity: 0;
}

.fqfl76byt {
  stop-color: var(--svg-color--efe7f3, #EFE7F3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fzvswcbdb {
  stop-color: var(--svg-color--e0948a, #E0948A);
}

.g0dfzlbtk {
  stop-color: var(--svg-color--d5c9cf, #D5C9CF);
  stop-opacity: 0;
}

.g0ef-8prm {
  stop-color: var(--svg-color--c2b0b9, #C2B0B9);
}

.g2inwgbbu {
  d: path("M9.87 22.67v7.02c-.01.17.13.31.3.31h1.37c.18 0 .32-.14.32-.31v-1.96c0-.17.07-.32.18-.44c.53-.52.82-1.23.82-1.97V23c0-1.969-2.5-2.406-2.99-.33");
}

.ggy8oqgjq {
  d: path("M20.73 18.71v6.07c0 .15-.03.29-.1.42l-1.67 4.35c-.1.21.05.45.28.45h1.03c.3 0 .57-.14.75-.37l2.41-4.2c.19-.32.31-.6.31-.94v-5.77h-3.01z");
}

.gnw-dw1nf {
  stop-color: var(--svg-color--d28c89, #D28C89);
}

.hhx86ob_n {
  stop-color: var(--svg-color--ffc28b, #FFC28B);
}

.hzsbm0mtl {
  stop-color: var(--svg-color--c8c6cb, #C8C6CB);
  stop-opacity: 0;
}

.i202febxk {
  d: path("m9.39 5.906l2.689 8.158a4 4 0 0 0 3.799 2.749h7.106");
}

.id08ivbsj {
  stop-color: var(--svg-color--e9e5f2, #E9E5F2);
}

.igovhqmbz {
  stop-color: var(--svg-color--f5ecfa, #F5ECFA);
}

.ihr20616w {
  stop-color: var(--svg-color--e3c8eb, #E3C8EB);
}

.jx0oumbhp {
  stop-color: var(--svg-color--3c273a, #3C273A);
}

.jyld_-b_l {
  stop-color: var(--svg-color--decde3, #DECDE3);
}

.k6-eazbnm {
  stop-color: var(--svg-color--cbcad3, #CBCAD3);
  stop-opacity: 0;
}

.kbaor5bbo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m14.797 23.813l1.562 5.562");
}

.kg0q3wbfb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m22.188 24.734l-2.11 4.532");
}

.ktzmk3bsn {
  stop-color: var(--svg-color--f5e1ef, #F5E1EF);
  stop-opacity: 0;
}

.kuot97fmj {
  stop-color: var(--svg-color--f2eaf6, #F2EAF6);
}

.l08wh7bwu {
  stop-color: var(--svg-color--fea973, #FEA973);
}

.l0xhuwb2y {
  stop-color: var(--svg-color--eee7fc, #EEE7FC);
}

.l52wh5qyl {
  stop-color: var(--svg-color--ffc48d, #FFC48D);
}

.lrhgsxbom {
  stop-color: var(--svg-color--da9f99, #DA9F99);
  stop-opacity: 0;
}

.lvda8uous {
  stop-color: var(--svg-color--d6d3d8, #D6D3D8);
}

.m5dp9ncle {
  d: path("M17.17 29.62c.04.17-.02.38-.22.38l-1.4-.01c-.17 0-.34-.05-.38-.22l-.87-3.14a.62.62 0 0 0-.29-.38c-.64-.37-1.11-.98-1.3-1.69l-.85-3.55h2.99z");
}

.mrx9-i7eo {
  stop-color: var(--svg-color--eee7fc, #EEE7FC);
  stop-opacity: 0;
}

.nhxvt9but {
  stop-color: var(--svg-color--d3bfd9, #D3BFD9);
}

.nk_73ac6p {
  d: path("M4.36 8.5c0-.28-.22-.5-.5-.5H3.1a1.2 1.2 0 0 0-.21 1h.97c.28 0 .5-.22.5-.5");
}

.nrz8m7mnn {
  stop-color: var(--svg-color--e9907c, #E9907C);
  stop-opacity: 0;
}

.oa67vibei {
  stop-color: var(--svg-color--ffc28b, #FFC28B);
  stop-opacity: 0;
}

.odebtccyv {
  stop-color: var(--svg-color--c0bbc3, #C0BBC3);
}

.q3whbiz9s {
  stop-color: var(--svg-color--cb9fcc, #CB9FCC);
  stop-opacity: 0;
}

.q7s_lsdao {
  stop-color: var(--svg-color--eee6f7, #EEE6F7);
}

.rhttwyu8s {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m28.4 23.08l-1.27-.96a.94.94 0 0 1-.27-.66v-2.75c0-2.07-1.68-3.75-3.75-3.75h-8.17c-.66 0-1.27-.38-1.57-.97L9.9 3.5A2.23 2.23 0 0 0 7.8 2c-.18 0-.3.17-.24.34l.656 2.005c.106.323-.132.708-.453.819c-.348.12-.777.306-1.183.566L3.46 7.66c-.37.23-.6.64-.6 1.07c0 .7.57 1.27 1.27 1.27h2.73v8.26c0 2.01 1.25 3.72 3.01 4.41v7.02c-.01.17.13.31.3.31h1.37c.18 0 .32-.14.32-.31v-1.96c0-.17.07-.32.18-.44c.53-.52.82-1.23.82-1.97V23h5.07a4.46 4.46 0 0 0 2.958-1.126c.137-.123.388-.03.425.15c.148.71.6 1.311 1.328 1.796l3.96 2.43c.16.11.26.3.26.5v2.93c0 .17.14.31.31.31h1.37c.17 0 .31-.14.31-.31v-5.51c.01-.4-.15-.8-.45-1.09");
}

.sqmrghbhm {
  stop-color: var(--svg-color--d6d3d8, #D6D3D8);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t70hs4bdn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.016 22.531v6.313");
}

.tjue4hbkk {
  stop-color: var(--svg-color--cb9fcc, #CB9FCC);
}

.tse1pgbsd {
  d: path("M26.86 17a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgmyn_6gg {
  stop-color: var(--svg-color--efaa75, #EFAA75);
  stop-opacity: 0;
}

.vl66_rb7h {
  stop-color: var(--svg-color--c8c6cb, #C8C6CB);
}

.vs5urib8a {
  stop-color: var(--svg-color--e98069, #E98069);
}

.w4nq0obzd {
  stop-color: var(--svg-color--cbcad3, #CBCAD3);
}

.waih3lbdk {
  stop-color: var(--svg-color--af95b3, #AF95B3);
}

.wakrmbbsr {
  d: path("M21.335 22.118V17.5H12.86V23h5.07a4.46 4.46 0 0 0 2.957-1.126c.137-.123.388-.03.425.15z");
}

.wevqdhbej {
  stop-color: var(--svg-color--e1c7e3, #E1C7E3);
}

.wh9_b3gvv {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m8.844 2.875l.984 3");
}

.xb7bkbbgh {
  stop-color: var(--svg-color--bea8c1, #BEA8C1);
  stop-opacity: 0;
}

.ybp50hbwu {
  stop-color: var(--svg-color--f5e1ef, #F5E1EF);
}

.ykuuwbc-o {
  stop-color: var(--svg-color--e0948a, #E0948A);
  stop-opacity: 0;
}

.zbql46o9c {
  stop-color: var(--svg-color--bb7cb7, #BB7CB7);
}

.zkkwkki_c {
  d: path("m27.13 22.12l1.27.96c.3.29.46.69.45 1.09v5.51c0 .17-.14.31-.31.31h-1.37c-.17 0-.31-.14-.31-.31v-2.93c0-.2-.1-.39-.26-.5l-3.96-2.43c-.694-.463-1.139-1.033-1.305-1.702v-1.574a2.763 2.763 0 0 1 5.526 0v.916c0 .25.1.49.27.66");
}

</style>
