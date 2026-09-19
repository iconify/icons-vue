<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivY8Yae)" class="j5jcniues"/><path fill="url(#ijn89Je)" class="j5jcniues"/><path fill="url(#iMQyvFe)" class="j5jcniues"/><path fill="url(#ie2z6gb)" class="j5jcniues"/><path fill="url(#iapV3zb)" class="j5jcniues"/><path fill="url(#i5kwJxc)" class="j5jcniues"/><path fill="url(#icuARtq)" class="j5jcniues"/><path fill="url(#iBN8zgC)" class="j5jcniues"/><path fill="url(#iovA7hb)" class="j5jcniues"/><path fill="url(#imtjjfG)" class="j5jcniues"/><path fill="url(#ixNIEfb)" class="j5jcniues"/><g filter="url(#i5Asnsc)"><path clip-rule="evenodd" class="i9hnkpyhg"/></g><g filter="url(#i2K04Zc)"><path stroke="url(#iD6hazc)" class="xp8y8vk5b"/></g><path class="ns7xkccln"/><path class="l00g1qg0n"/><path class="fkq8ch0po"/><path class="fpppcsb_e"/><g filter="url(#iQPuild)"><path class="t-cnt63by"/></g><path class="sh_8uswvl"/><g filter="url(#inuhjjb)"><path class="icalrfbsw"/></g><path fill="url(#iEbPOsd)" class="zg11mubgl"/><path fill="url(#i8ancMd)" class="tw6njyc7n"/><path fill="url(#ipAsr5d)" class="w0978nbej"/><path fill="url(#iKN28Qd)" class="b5s-4i7rk"/><path fill="url(#iS5Ea1P)" class="jixfx0b1x"/><path fill="url(#iDmCLld)" class="kej6x0wgg"/><g filter="url(#iwysFLb)"><path stroke="url(#iz0dWnd)" class="u7ds20caf"/></g><g filter="url(#iA48UnD)"><path stroke="url(#iXte5ge)" class="yh1qd8bgf"/></g><g filter="url(#i4DYpKe)"><path stroke="url(#iS3etTd)" class="s-bkkrmma"/></g><g filter="url(#iiV4JXd)"><path fill="url(#iMitIfc)" class="xx3l6kbmh"/></g><g filter="url(#imrn5ce)"><path stroke="url(#iCXs5TR)" class="z99lvuv5t"/></g><g filter="url(#iDSurde)"><path stroke="url(#ic6EVGb)" class="gx50a0cul"/></g><g filter="url(#i9jM2Do)"><path stroke="url(#iLi6Cke)" class="tlrf678ec"/></g><g filter="url(#iBfFszd)"><path stroke="url(#iXg5SXc)" class="a_lf6lb-w"/></g><g filter="url(#iX8ware)"><path stroke="url(#iGIhdBd)" class="l0ibfjlyy"/></g><g filter="url(#ihO8Vwb)"><path stroke="url(#i9KerHc)" class="w46j963na"/></g><g filter="url(#i1ROyfe)"><path stroke="url(#ifaGdIc)" class="ogrbim1ih"/></g><defs><radialGradient id="ivY8Yae" cx="0" cy="0" r="1" gradientTransform="translate(16.01 17.158)scale(13.3654)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="p27f4xq0x"/><stop offset=".854" class="qk57zicbg"/></radialGradient><radialGradient id="iMQyvFe" cx="0" cy="0" r="1" gradientTransform="rotate(88.076 6.373 9.856)scale(5.47184 4.31698)" gradientUnits="userSpaceOnUse"><stop class="rrfj6-_9a"/><stop offset="1" class="eh7t8b_yu"/></radialGradient><radialGradient id="ie2z6gb" cx="0" cy="0" r="1" gradientTransform="rotate(162.204 13.293 8.82)scale(1.32923 .51906)" gradientUnits="userSpaceOnUse"><stop class="rsacqrbca"/><stop offset="1" class="dftw43_df"/></radialGradient><radialGradient id="iapV3zb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.0938 -9.96865 2.0526 -1.66656 14.475 14.563)" gradientUnits="userSpaceOnUse"><stop class="fpeqfybgy"/><stop offset="1" class="t7fmnd6ip"/></radialGradient><radialGradient id="i5kwJxc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.096 26.34 -12.57)scale(12.7081 2.61668)" gradientUnits="userSpaceOnUse"><stop class="fpeqfybgy"/><stop offset="1" class="t7fmnd6ip"/></radialGradient><radialGradient id="icuARtq" cx="0" cy="0" r="1" gradientTransform="matrix(9.03125 4.0625 -.8365 1.85958 18.25 17.283)" gradientUnits="userSpaceOnUse"><stop class="fpeqfybgy"/><stop offset="1" class="t7fmnd6ip"/></radialGradient><radialGradient id="iBN8zgC" cx="0" cy="0" r="1" gradientTransform="matrix(-.33412 9.125 -1.8789 -.0688 16.344 18.314)" gradientUnits="userSpaceOnUse"><stop class="fpeqfybgy"/><stop offset="1" class="t7fmnd6ip"/></radialGradient><radialGradient id="iovA7hb" cx="0" cy="0" r="1" gradientTransform="rotate(160.322 5.944 9.9)scale(10.0228 2.06376)" gradientUnits="userSpaceOnUse"><stop class="fpeqfybgy"/><stop offset="1" class="t7fmnd6ip"/></radialGradient><radialGradient id="imtjjfG" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 -2.1875 5.39505 1.3873 4.656 19.596)" gradientUnits="userSpaceOnUse"><stop class="mvevnnbwt"/><stop offset="1" class="qrab81l_p"/></radialGradient><radialGradient id="ixNIEfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81252 -3.0625 7.57382 -2.00943 26.625 20.283)" gradientUnits="userSpaceOnUse"><stop class="mvevnnbwt"/><stop offset="1" class="qrab81l_p"/></radialGradient><radialGradient id="iEbPOsd" cx="0" cy="0" r="1" gradientTransform="rotate(131.934 5.483 9.703)scale(1.23921 1.13927)" gradientUnits="userSpaceOnUse"><stop class="gnhhk_bxu"/><stop offset="1" class="biwzr8zbd"/></radialGradient><radialGradient id="i8ancMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96624 .67326 -.61896 -.88832 20.844 15.516)" gradientUnits="userSpaceOnUse"><stop class="gnhhk_bxu"/><stop offset="1" class="biwzr8zbd"/></radialGradient><radialGradient id="ipAsr5d" cx="0" cy="0" r="1" gradientTransform="rotate(136.397 5.411 14.128)scale(.88468 .81333)" gradientUnits="userSpaceOnUse"><stop class="gnhhk_bxu"/><stop offset="1" class="y9ejf3b8j"/></radialGradient><radialGradient id="iKN28Qd" cx="0" cy="0" r="1" gradientTransform="rotate(136.397 2.726 13.054)scale(.88468 .81333)" gradientUnits="userSpaceOnUse"><stop class="gnhhk_bxu"/><stop offset="1" class="y9ejf3b8j"/></radialGradient><radialGradient id="iS5Ea1P" cx="0" cy="0" r="1" gradientTransform="rotate(131.934 2.604 10.313)scale(1.23921 1.13927)" gradientUnits="userSpaceOnUse"><stop class="gnhhk_bxu"/><stop offset="1" class="y9ejf3b8j"/></radialGradient><radialGradient id="iDmCLld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.87498 4.12502 -4.4711 -3.11619 17.344 15.877)" gradientUnits="userSpaceOnUse"><stop class="gnhhk_bxu"/><stop offset="1" class="y9ejf3b8j"/></radialGradient><filter id="i5Asnsc" width="12.69" height="12.27" x="9.66" y="10.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".5"/></filter><filter id="i2K04Zc" width="2.019" height="3.394" x="22.006" y="26.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="iQPuild" width="3.223" height="4.176" x="15.803" y="16.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".075"/></filter><filter id="inuhjjb" width=".6" height="4.87" x="15.866" y="12.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".075"/></filter><filter id="iwysFLb" width="5.316" height="9.001" x="16.413" y="2.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="iA48UnD" width="4.689" height="8.456" x="10.555" y="2.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".15"/></filter><filter id="i4DYpKe" width="7.031" height="6.875" x="7.703" y="8.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="iiV4JXd" width="2.006" height="2.428" x="14.27" y="2.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".15"/></filter><filter id="imrn5ce" width="6.581" height="3.793" x="22.913" y="8.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="iDSurde" width="6.177" height="6.925" x="24.163" y="13.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="i9jM2Do" width="8.685" height="10.894" x="18.35" y="17.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="iBfFszd" width="2.945" height="8.781" x="13.75" y="19.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".3"/></filter><filter id="iX8ware" width="6.394" height="3.137" x="2.756" y="9.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".15"/></filter><filter id="ihO8Vwb" width="5.956" height="5.988" x="1.944" y="13.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".15"/></filter><filter id="i1ROyfe" width="2.59" height="8.051" x="5.31" y="20.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7131" stdDeviation=".15"/></filter><linearGradient id="ijn89Je" x1="16.01" x2="16.01" y1="32.313" y2="24.25" gradientUnits="userSpaceOnUse"><stop class="lwk-edmaz"/><stop offset="1" class="e_or9ibyy"/></linearGradient><linearGradient id="iD6hazc" x1="23.266" x2="23.19" y1="29.111" y2="27.015" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iz0dWnd" x1="19.07" x2="21.666" y1="3.553" y2="10.754" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iXte5ge" x1="14.359" x2="10.121" y1=".205" y2="10.728" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iS3etTd" x1="11.38" x2="12.308" y1="9.869" y2="15.364" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iMitIfc" x1="14.969" x2="15.758" y1="3.338" y2="4.799" gradientUnits="userSpaceOnUse"><stop class="lwjubhbys"/><stop offset="1" class="s_dol-8gb"/></linearGradient><linearGradient id="iCXs5TR" x1="27.969" x2="26.921" y1="10.743" y2="7.936" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="ic6EVGb" x1="30.5" x2="25.724" y1="14.158" y2="18.253" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iLi6Cke" x1="28" x2="19.595" y1="25.658" y2="16.124" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iXg5SXc" x1="17" x2="22.397" y1="16.971" y2="23.859" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="iGIhdBd" x1="8.053" x2="7.736" y1="8.564" y2="12.271" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="i9KerHc" x1="6.858" x2="5.221" y1="12.249" y2="20.2" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient><linearGradient id="ifaGdIc" x1="7" x2="12.347" y1="27.845" y2="19.562" gradientUnits="userSpaceOnUse"><stop class="yrl5b3b4v"/><stop offset="1" class="a1di8ab2t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cherry-blossom" /></template>
<style>
.a_lf6lb-w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.938 20.22c.052 1.678-.163 5.482-1.438 7.282");
}

.a1di8ab2t {
  stop-color: var(--svg-color--ffa2b3, #FFA2B3);
  stop-opacity: 0;
}

.b5s-4i7rk {
  d: path("M13.32 21.626a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.biwzr8zbd {
  stop-color: var(--svg-color--e2c3ec, #E2C3EC);
}

.dftw43_df {
  stop-color: var(--svg-color--ffa2b7, #FFA2B7);
  stop-opacity: 0;
}

.e_or9ibyy {
  stop-color: var(--svg-color--f96bc3, #F96BC3);
  stop-opacity: 0;
}

.eh7t8b_yu {
  stop-color: var(--svg-color--ff85a0, #FF85A0);
  stop-opacity: 0;
}

.fkq8ch0po {
  stroke: var(--svg-color--f0d6f8, #F0D6F8);
  stroke-miterlimit: 10;
  d: path("m20.35 15.516l-4.34 1.41");
}

.fpeqfybgy {
  stop-color: var(--svg-color--f63d51, #F63D51);
}

.fpppcsb_e {
  stroke: var(--svg-color--e8c7f7, #E8C7F7);
  stroke-miterlimit: 10;
  d: path("m18.69 20.626l-2.68-3.7");
}

.ft5dv1b6b {
  fill: none;
}

.gnhhk_bxu {
  stop-color: var(--svg-color--f3dcf8, #F3DCF8);
}

.gx50a0cul {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M29.438 14.158c.041 1.5-.775 4.625-4.375 5.125");
}

.i9hnkpyhg {
  fill: var(--svg-color--f23243, #F23243);
  fill-rule: evenodd;
  d: path("M16.51 13.222a1 1 0 1 0-1 0v3.016l-2.872-.93a1 1 0 1 0-.309.95l2.871.931l-1.775 2.443a1 1 0 1 0 .809.588l1.775-2.443l1.768 2.44a1 1 0 1 0 .81-.586l-1.77-2.442l2.863-.93a1 1 0 1 0-.31-.951l-2.86.93z");
}

.icalrfbsw {
  stroke: var(--svg-color--f2d2fa, #F2D2FA);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.166 12.356v4.57");
}

.j5jcniues {
  d: path("M26.236 19.766c2.47-.8 3.96-3.19 3.76-5.68a.53.53 0 0 0-.43-.47s-.89-.19-1.09-.23c-.1-.02-.14-.15-.08-.22c.13-.14.75-.84.75-.84c.16-.17.19-.44.07-.64c-1.29-2.13-3.9-3.19-6.38-2.38c-.71.23-1.33.65-1.87 1.18c.34-.68.54-1.39.54-2.14c0-2.6-1.81-4.76-4.24-5.33a.56.56 0 0 0-.59.26s-.46.79-.56.97c-.05.09-.19.08-.23.01c-.1-.17-.56-.98-.56-.98c-.12-.2-.36-.32-.58-.26c-2.42.56-4.24 2.72-4.24 5.32c0 .75.21 1.46.54 2.14c-.54-.53-1.15-.94-1.86-1.17c-2.48-.81-5.09.25-6.38 2.38c-.12.2-.09.46.07.64c0 0 .61.68.75.83c.07.07.02.21-.07.23l-1.1.23c-.23.05-.41.24-.43.47a5.48 5.48 0 0 0 3.76 5.68c.72.23 1.46.26 2.22.14c-.68.35-1.28.81-1.72 1.42c-1.53 2.1-1.33 4.91.3 6.8c.15.18.41.23.63.13c0 0 .83-.37 1.02-.46c.09-.04.2.04.19.13l-.12 1.12c-.02.23.1.47.32.56c2.3.96 5.03.28 6.56-1.82c.44-.61.69-1.3.82-2.05c.13.75.38 1.45.82 2.05c1.53 2.1 4.26 2.78 6.56 1.82c.22-.09.34-.32.32-.56c0 0-.1-.91-.12-1.11c-.01-.1.1-.18.19-.14l1.03.46c.21.1.48.05.63-.13c1.63-1.89 1.83-4.7.3-6.8c-.44-.61-1.04-1.06-1.72-1.42c.76.12 1.5.09 2.22-.14");
}

.jixfx0b1x {
  d: path("M11.66 16.516a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.kej6x0wgg {
  d: path("M16.01 19.396a2.47 2.47 0 1 0 0-4.94a2.47 2.47 0 0 0 0 4.94");
}

.l00g1qg0n {
  stroke: var(--svg-color--edd1f8, #EDD1F8);
  stroke-miterlimit: 10;
  d: path("M16.01 12.356v4.57");
}

.l0ibfjlyy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.156 11.846c.636-.99 2.644-2.819 5.594-2.219");
}

.lwjubhbys {
  stop-color: var(--svg-color--ff9aa9, #FF9AA9);
}

.lwk-edmaz {
  stop-color: var(--svg-color--f96bc3, #F96BC3);
}

.mvevnnbwt {
  stop-color: var(--svg-color--ff689a, #FF689A);
}

.ns7xkccln {
  stroke: var(--svg-color--fff5d4, #FFF5D4);
  stroke-miterlimit: 10;
  d: path("M16.01 12.356v4.57");
}

.ogrbim1ih {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.5 20.626c-1.23 1.01-2.984 3.845-.625 7.251");
}

.p27f4xq0x {
  stop-color: var(--svg-color--fd4d67, #FD4D67);
}

.qk57zicbg {
  stop-color: var(--svg-color--ff7f9f, #FF7F9F);
}

.qrab81l_p {
  stop-color: var(--svg-color--ff689a, #FF689A);
  stop-opacity: 0;
}

.rrfj6-_9a {
  stop-color: var(--svg-color--ff85a0, #FF85A0);
}

.rsacqrbca {
  stop-color: var(--svg-color--ffa2b7, #FFA2B7);
}

.s_dol-8gb {
  stop-color: var(--svg-color--ff9aa9, #FF9AA9);
  stop-opacity: 0;
}

.s-bkkrmma {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M8.453 9.669c.438.02 1.713.475 2.688 1.625s2.302 2.979 2.843 3.75");
}

.sh_8uswvl {
  stroke: var(--svg-color--e5c1f6, #E5C1F6);
  stroke-miterlimit: 10;
  d: path("m13.32 20.626l2.69-3.7m-4.35-1.41l4.35 1.41");
}

.t-cnt63by {
  stroke: var(--svg-color--f2d2fa, #F2D2FA);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m18.755 20.501l-2.68-3.7");
}

.t7fmnd6ip {
  stop-color: var(--svg-color--fd5b78, #FD5B78);
  stop-opacity: 0;
}

.tlrf678ec {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m19.25 18.408l4.188 1.875c.77.313 2.456 1.578 2.656 3.328c.22 1.922-.485 3.328-.969 3.891");
}

.tw6njyc7n {
  d: path("M20.35 16.516a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.u7ds20caf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M17.313 3.553c.453.147 1.726.753 2.516 1.8c1.253 1.662 1.286 3.748.33 5.4");
}

.w0978nbej {
  d: path("M18.69 21.626a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.w46j963na {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M2.344 14.346c.083 1.75 1.231 5.237 5.156 5.187");
}

.xp8y8vk5b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m23.125 29.111l-.219-1.593");
}

.xx3l6kbmh {
  d: path("m15.977 5.057l-.891-1.828c-.187.18-.516.632-.516.867z");
}

.y9ejf3b8j {
  stop-color: var(--svg-color--dfb6f4, #DFB6F4);
}

.yh1qd8bgf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.844 3.299c-.758.219-2.668 1.065-3.563 3.015c-.555 1.212-.39 3.625.407 4.641");
}

.yrl5b3b4v {
  stop-color: var(--svg-color--ffa2b3, #FFA2B3);
}

.z99lvuv5t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M28.594 11.502c-.735-1.016-2.781-2.313-4.781-1.922");
}

.zg11mubgl {
  d: path("M16.01 13.356a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
