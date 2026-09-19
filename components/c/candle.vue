<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#it6oare)" class="soel1tb_b"/><path fill="url(#iqAAQrd)" class="soel1tb_b"/><path fill="url(#i7PUSFb)" class="soel1tb_b"/><g filter="url(#ij6vBfy)"><path fill="url(#i0ANbHE)" class="qoyf2tb8e"/><path fill="url(#iEqhvHe)" class="qoyf2tb8e"/><path fill="url(#isocRUc)" class="qoyf2tb8e"/><path fill="url(#it3yPHe)" class="qoyf2tb8e"/></g><path fill="url(#ivMoMxe)" class="qkjjvsbnd"/><path fill="url(#iXF1bbb)" class="qkjjvsbnd"/><path fill="url(#ipL98KZ)" class="qkjjvsbnd"/><path fill="url(#iBqUfGc)" class="l4qc1wqra"/><path fill="url(#iDrDYOb)" class="l4qc1wqra"/><path fill="url(#iEfhdAO)" class="l4qc1wqra"/><path fill="url(#iKFyQjd)" class="l4qc1wqra"/><path fill="url(#iMmxMhe)" class="l4qc1wqra"/><g filter="url(#ioJBcVb)"><path fill="url(#ivixwub)" class="ei-r7zb5q"/></g><g filter="url(#ifP5doc)"><path fill="url(#iRKlsCe)" class="erk8n7bps"/></g><g filter="url(#ih79jKh)"><path fill="url(#itHcPec)" class="ruyaisb9x"/><path fill="url(#iTxbu9b)" class="ruyaisb9x"/></g><path fill="url(#iNv3YeQ)" class="ruyaisb9x"/><path fill="url(#iLTpoae)" class="ruyaisb9x"/><g filter="url(#iGRDLJb)"><rect class="pa-phoe2o"/></g><g filter="url(#iWM84Yc)"><rect fill="url(#il1iKBb)" class="drwoaebjx"/></g><g filter="url(#iXjU6hd)"><path class="o3wseac9n"/></g><defs><linearGradient id="it6oare" x1="15.391" x2="16.75" y1="11.797" y2="11.797" gradientUnits="userSpaceOnUse"><stop class="orbhwqbsi"/><stop offset="1" class="r5isp-bzd"/></linearGradient><linearGradient id="iqAAQrd" x1="17.016" x2="16.578" y1="12.109" y2="12.109" gradientUnits="userSpaceOnUse"><stop class="yok-rivfb"/><stop offset="1" class="j5s7l1dta"/></linearGradient><linearGradient id="i0ANbHE" x1="16" x2="16" y1="2.017" y2="9.906" gradientUnits="userSpaceOnUse"><stop class="hppfvxbav"/><stop offset=".792" class="l9gx_bbgf"/></linearGradient><linearGradient id="iXF1bbb" x1="15.797" x2="15.797" y1="9.047" y2="7.641" gradientUnits="userSpaceOnUse"><stop class="f_e5jdbhi"/><stop offset="1" class="uymxyrqis"/></linearGradient><linearGradient id="iBqUfGc" x1="11.797" x2="20.969" y1="25.781" y2="25.781" gradientUnits="userSpaceOnUse"><stop class="mukiqrb_x"/><stop offset="1" class="bh7yksbhl"/></linearGradient><linearGradient id="iDrDYOb" x1="16" x2="16" y1="14.781" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="hsq7h93jb"/><stop offset="1" class="ux2712bpe"/></linearGradient><linearGradient id="iEfhdAO" x1="10.578" x2="12.797" y1="25.875" y2="25.875" gradientUnits="userSpaceOnUse"><stop class="kjaethbgs"/><stop offset="1" class="i-zu_89da"/></linearGradient><linearGradient id="iKFyQjd" x1="21.188" x2="20.016" y1="26.438" y2="26.438" gradientUnits="userSpaceOnUse"><stop class="h9zkuqfxr"/><stop offset="1" class="s6_j26b3j"/></linearGradient><linearGradient id="iMmxMhe" x1="17.047" x2="17.047" y1="30.016" y2="28.469" gradientUnits="userSpaceOnUse"><stop class="sdb6vbb9j"/><stop offset="1" class="a0784saht"/></linearGradient><linearGradient id="ivixwub" x1="20.852" x2="15.547" y1="25.772" y2="25.772" gradientUnits="userSpaceOnUse"><stop offset=".133" class="k8m0mobcd"/><stop offset="1" class="kaaw_ub0k"/></linearGradient><linearGradient id="iRKlsCe" x1="14.781" x2="16.117" y1="14.625" y2="21.258" gradientUnits="userSpaceOnUse"><stop class="bns6ceb0s"/><stop offset="1" class="nxrc1dbpn"/></linearGradient><linearGradient id="itHcPec" x1="21.047" x2="14.672" y1="20.781" y2="15.156" gradientUnits="userSpaceOnUse"><stop class="hvn4ffbfd"/><stop offset="1" class="ad9ey1ium"/></linearGradient><linearGradient id="iTxbu9b" x1="10.055" x2="16.391" y1="14.813" y2="14.813" gradientUnits="userSpaceOnUse"><stop class="kk8cz9bgw"/><stop offset="1" class="orgy_ksrc"/></linearGradient><linearGradient id="iNv3YeQ" x1="16" x2="16" y1="12.094" y2="12.547" gradientUnits="userSpaceOnUse"><stop class="y3yur6beb"/><stop offset="1" class="wbkh3yh4k"/></linearGradient><linearGradient id="il1iKBb" x1="17.688" x2="17.688" y1="16.125" y2="13.906" gradientUnits="userSpaceOnUse"><stop class="n_sz5y-ke"/><stop offset="1" class="a-8gbob5k"/></linearGradient><radialGradient id="i7PUSFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96875 -1.05085 0 16 9.828)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="qqk81jbik"/><stop offset="1" class="ngdlsbb9r"/></radialGradient><radialGradient id="iEqhvHe" cx="0" cy="0" r="1" gradientTransform="rotate(90 5.313 12)scale(1.96875)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="z0lcnrb6r"/><stop offset="1" class="v9ebqqbrz"/></radialGradient><radialGradient id="isocRUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84375 -2.14453 0 15.156 6.75)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="b4qgcbe-x"/><stop offset="1" class="spokfpbfl"/></radialGradient><radialGradient id="it3yPHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 3.5 -1.51406 .83814 16.719 2.266)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="uk8vg3m4o"/><stop offset="1" class="siz-lacek"/></radialGradient><radialGradient id="ivMoMxe" cx="0" cy="0" r="1" gradientTransform="rotate(179.685 8.608 3.406)scale(2.84379 2.20206)" gradientUnits="userSpaceOnUse"><stop class="tbvpk1vgf"/><stop offset=".547" class="xj1ts9b8a"/><stop offset="1" class="h2cw72ssr"/></radialGradient><radialGradient id="ipL98KZ" cx="0" cy="0" r="1" gradientTransform="matrix(2.07813 0 0 3.23438 13.922 7.172)" gradientUnits="userSpaceOnUse"><stop class="qnuui8lzy"/><stop offset="1" class="qkvk7bclq"/></radialGradient><radialGradient id="iLTpoae" cx="0" cy="0" r="1" gradientTransform="rotate(-171.782 10.285 7.727)scale(9.40122 8.83726)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="n6ueyytcp"/><stop offset="1" class="fhdnxbcnk"/></radialGradient><filter id="ij6vBfy" width="6.227" height="8.12" x="13.012" y="2.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.619608 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20489"/></filter><filter id="ioJBcVb" width="8.875" height="15.281" x="13.547" y="15.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20489" stdDeviation="1"/></filter><filter id="ifP5doc" width="10.703" height="8.711" x="10.766" y="13.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20489" stdDeviation=".25"/></filter><filter id="ih79jKh" width="12.141" height="9.18" x="10.055" y="11.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.768627 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20489" result="effect2_innerShadow_18_20489"/></filter><filter id="iGRDLJb" width="3" height="7.188" x="19.109" y="13.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20489" stdDeviation=".5"/></filter><filter id="iWM84Yc" width="3" height="4.537" x="16.188" y="13.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20489" stdDeviation=".5"/></filter><filter id="iXjU6hd" width=".941" height="3.706" x="11.725" y="14.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20489" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:candle" /></template>
<style>
.a-8gbob5k {
  stop-color: var(--svg-color--ffefd1, #FFEFD1);
  stop-opacity: 0;
}

.a0784saht {
  stop-color: var(--svg-color--e3a7c9, #E3A7C9);
  stop-opacity: 0;
}

.ad9ey1ium {
  stop-color: var(--svg-color--ffd3b0, #FFD3B0);
}

.b4qgcbe-x {
  stop-color: var(--svg-color--fcb276, #FCB276);
}

.bh7yksbhl {
  stop-color: var(--svg-color--fdd7ce, #FDD7CE);
}

.bns6ceb0s {
  stop-color: var(--svg-color--d38665, #D38665);
}

.drwoaebjx {
  width: 1px;
  height: 2.537px;
  x: 17.188px;
  y: 14.219px;
  rx: 0.5px;
}

.ei-r7zb5q {
  d: path("M15.547 17.656h4.875v11.281h-4.875z");
}

.erk8n7bps {
  d: path("M20.969 21.104v-6.157c0-.773-.612-1.4-1.367-1.4h-6.97c-.754 0-1.366.627-1.366 1.4v4.23a1.19 1.19 0 0 0 1.083-1.197v-2.05c0-.277.218-.5.488-.5h2.548c.27 0 .488.223.488.5v.468c0 .686.543 1.243 1.213 1.243s1.213-.556 1.213-1.243v-.535c0-.24.19-.433.423-.433c.234 0 .423.194.423.433l-.003 1.846c-.002.764-.004 1.528-.004 2.28c0 .7.555 1.269 1.24 1.269c.214 0 .415-.056.59-.154");
}

.f_e5jdbhi {
  stop-color: var(--svg-color--ffa03d, #FFA03D);
}

.fhdnxbcnk {
  stop-color: var(--svg-color--b79b81, #B79B81);
}

.ft5dv1b6b {
  fill: none;
}

.h2cw72ssr {
  stop-color: var(--svg-color--ffb236, #FFB236);
  stop-opacity: 0;
}

.h9zkuqfxr {
  stop-color: var(--svg-color--f6e0bb, #F6E0BB);
}

.hppfvxbav {
  stop-color: var(--svg-color--fed873, #FED873);
}

.hsq7h93jb {
  stop-color: var(--svg-color--eab18c, #EAB18C);
}

.hvn4ffbfd {
  stop-color: var(--svg-color--ffeed0, #FFEED0);
}

.i-zu_89da {
  stop-color: var(--svg-color--d2afa6, #D2AFA6);
  stop-opacity: 0;
}

.j5s7l1dta {
  stop-color: var(--svg-color--a69495, #A69495);
  stop-opacity: 0;
}

.k8m0mobcd {
  stop-color: var(--svg-color--fff1d4, #FFF1D4);
}

.kaaw_ub0k {
  stop-color: var(--svg-color--fff1d4, #FFF1D4);
  stop-opacity: 0;
}

.kjaethbgs {
  stop-color: var(--svg-color--ba9d88, #BA9D88);
}

.kk8cz9bgw {
  stop-color: var(--svg-color--cca99b, #CCA99B);
}

.l4qc1wqra {
  d: path("M11.031 14.713a1.4 1.4 0 0 1 1.4-1.4h7.138a1.4 1.4 0 0 1 1.4 1.4V28.49a1.4 1.4 0 0 1-1.4 1.4H12.43a1.4 1.4 0 0 1-1.4-1.4z");
}

.l9gx_bbgf {
  stop-color: var(--svg-color--ffa03c, #FFA03C);
}

.mukiqrb_x {
  stop-color: var(--svg-color--e4bfba, #E4BFBA);
}

.n_sz5y-ke {
  stop-color: var(--svg-color--ffefd1, #FFEFD1);
}

.n6ueyytcp {
  stop-color: var(--svg-color--cea794, #CEA794);
  stop-opacity: 0;
}

.ngdlsbb9r {
  stop-color: var(--svg-color--aa6772, #AA6772);
  stop-opacity: 0;
}

.nxrc1dbpn {
  stop-color: var(--svg-color--ffd0a5, #FFD0A5);
}

.o3wseac9n {
  fill: var(--svg-color--f0cdc0, #F0CDC0);
  d: path("M12.125 15.105h.141v2.906h-.141z");
}

.orbhwqbsi {
  stop-color: var(--svg-color--8d7a77, #8D7A77);
}

.orgy_ksrc {
  stop-color: var(--svg-color--cca99b, #CCA99B);
  stop-opacity: 0;
}

.pa-phoe2o {
  width: 1px;
  height: 5.188px;
  x: 20.109px;
  y: 14.891px;
  fill: var(--svg-color--ffefd1, #FFEFD1);
  rx: 0.5px;
}

.qkjjvsbnd {
  d: path("m14.404 6.086l1.035-1.89c.254-.477.861-.478 1.112 0l1.028 1.86q.021.035.04.074l.004.006a1.826 1.826 0 1 1-3.22-.05");
}

.qkvk7bclq {
  stop-color: var(--svg-color--ff9335, #FF9335);
  stop-opacity: 0;
}

.qnuui8lzy {
  stop-color: var(--svg-color--ff9335, #FF9335);
}

.qoyf2tb8e {
  d: path("m13.389 5.695l1.693-3.093c.415-.779 1.409-.781 1.82 0l1.682 3.044l.066.12l.006.011a2.988 2.988 0 1 1-5.268-.083");
}

.qqk81jbik {
  stop-color: var(--svg-color--aa6772, #AA6772);
}

.r5isp-bzd {
  stop-color: var(--svg-color--c4b4b4, #C4B4B4);
}

.ruyaisb9x {
  d: path("M13.055 12.094a3 3 0 0 0-3 3v2.652a1.2 1.2 0 1 0 2.398 0v-2.05a.5.5 0 0 1 .5-.5h2.61a.5.5 0 0 1 .5.5v.468a1.242 1.242 0 0 0 2.484 0v-.535a.433.433 0 0 1 .866 0c0 1.364-.007 2.765-.007 4.125a1.27 1.27 0 0 0 2.54 0v-4.66a3 3 0 0 0-3-3z");
}

.s6_j26b3j {
  stop-color: var(--svg-color--f6e0bb, #F6E0BB);
  stop-opacity: 0;
}

.sdb6vbb9j {
  stop-color: var(--svg-color--c477bf, #C477BF);
}

.siz-lacek {
  stop-color: var(--svg-color--ffef50, #FFEF50);
  stop-opacity: 0;
}

.soel1tb_b {
  d: path("M15.141 9.25h1.719v3.859h-1.719z");
}

.spokfpbfl {
  stop-color: var(--svg-color--fcb276, #FCB276);
  stop-opacity: 0;
}

.tbvpk1vgf {
  stop-color: var(--svg-color--ffc25e, #FFC25E);
}

.uk8vg3m4o {
  stop-color: var(--svg-color--ffef50, #FFEF50);
}

.ux2712bpe {
  stop-color: var(--svg-color--f6c6b0, #F6C6B0);
  stop-opacity: 0;
}

.uymxyrqis {
  stop-color: var(--svg-color--ffa03d, #FFA03D);
  stop-opacity: 0;
}

.v9ebqqbrz {
  stop-color: var(--svg-color--fcd381, #FCD381);
  stop-opacity: 0;
}

.wbkh3yh4k {
  stop-color: var(--svg-color--ffbd7e, #FFBD7E);
  stop-opacity: 0;
}

.xj1ts9b8a {
  stop-color: var(--svg-color--ffb236, #FFB236);
}

.y3yur6beb {
  stop-color: var(--svg-color--ffbd7e, #FFBD7E);
}

.yok-rivfb {
  stop-color: var(--svg-color--a69495, #A69495);
}

.z0lcnrb6r {
  stop-color: var(--svg-color--fcd381, #FCD381);
}

</style>
