<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iC0aNhd)"><path fill="url(#iu6rNrt)" class="k-e0jwroe"/><path fill="url(#iSgaTMd)" class="k-e0jwroe"/></g><g filter="url(#i7AS2Hc)"><path fill="url(#ieyje5b)" class="kuquc1bbq"/><path fill="url(#iLmqhne)" class="kuquc1bbq"/></g><path fill="url(#iN9h1Vb)" class="h4xiyubyd"/><path fill="url(#iItvk3s)" class="h4xiyubyd"/><path fill="url(#izSxz6b)" class="h4xiyubyd"/><path fill="url(#i9NPNNd)" class="h4xiyubyd"/><path fill="url(#ivQI6Rd)" class="h4xiyubyd"/><path fill="url(#iq6uLke)" class="sywzq8j_s"/><path fill="url(#i7eACfb)" class="sywzq8j_s"/><path fill="url(#itiRvue)" class="sywzq8j_s"/><path fill="url(#iMDADuo)" class="sywzq8j_s"/><path fill="url(#ijdZy4d)" class="sywzq8j_s"/><path fill="url(#iGAVQDb)" class="sywzq8j_s"/><path fill="url(#iYitLsb)" class="sywzq8j_s"/><g filter="url(#iiCdACL)"><path class="lkwg-hz6x"/></g><g filter="url(#i0Ie1Tb)"><path class="tb4leegtb"/></g><g filter="url(#iCiE57b)"><path class="vt1gpbbjj"/><path fill="url(#iIRb8hb)" class="r8fmqwffn"/><path fill="url(#iFMu5qb)" class="r8fmqwffn"/><path fill="url(#iLsabab)" class="r8fmqwffn"/><path fill="url(#isLJiKd)" class="r8fmqwffn"/><path fill="url(#iv66ule)" class="r8fmqwffn"/></g><g filter="url(#iHGmxlb)"><circle fill="url(#ifXMiqW)" class="l8uhoibmo"/></g><g filter="url(#io085uy)"><circle stroke="url(#iR60jTc)" class="ma1grp8cv"/><circle stroke="url(#igBUX9b)" class="ma1grp8cv"/></g><circle fill="url(#i8iFnRc)" class="ev1ek_bzg"/><circle fill="url(#iY4wEcd)" class="ev1ek_bzg"/><g filter="url(#iw8wLve)"><circle fill="url(#iZVYmEe)" class="fgh-jjb_v"/><circle fill="url(#i2y1Ned)" class="fgh-jjb_v"/></g><circle fill="url(#i0G6fFP)" class="v3anf-bfi"/><circle fill="url(#iN9RRCd)" class="v3anf-bfi"/><circle fill="url(#i5VohiH)" class="v3anf-bfi"/><ellipse fill="url(#iAjZKte)" transform="rotate(-34.974 18.036 19.985)" class="ndzantbta"/><g filter="url(#iAZ4gFb)"><path class="j4akg4nsm"/></g><g filter="url(#iLANLge)"><path fill="url(#ijmbnOn)" class="wmh2hob9q"/><path fill="url(#iQokmft)" class="wmh2hob9q"/></g><g filter="url(#iCHSZEe)"><path fill="url(#i0uT1Bu)" class="zlma_6btf"/></g><defs><linearGradient id="iu6rNrt" x1="21.406" x2="27.438" y1="11.875" y2="11.875" gradientUnits="userSpaceOnUse"><stop offset=".197" class="rpt3bxeag"/><stop offset=".624" class="nfrkcnbbf"/></linearGradient><linearGradient id="ieyje5b" x1="5.309" x2="9.368" y1="11.875" y2="11.875" gradientUnits="userSpaceOnUse"><stop offset=".197" class="rpt3bxeag"/><stop offset=".624" class="nfrkcnbbf"/></linearGradient><linearGradient id="iN9h1Vb" x1="16" x2="16" y1="28.078" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="ec0qbw1jt"/><stop offset="1" class="u2myzybpq"/></linearGradient><linearGradient id="iItvk3s" x1="17.375" x2="17.375" y1="29.906" y2="28.5" gradientUnits="userSpaceOnUse"><stop class="a435j-blx"/><stop offset="1" class="pzbiupb8h"/></linearGradient><linearGradient id="izSxz6b" x1="16" x2="16" y1="28.078" y2="28.594" gradientUnits="userSpaceOnUse"><stop class="l-ihw1uwp"/><stop offset="1" class="r5hqvv_4v"/></linearGradient><linearGradient id="iq6uLke" x1="20.281" x2="29.281" y1="22.008" y2="22.008" gradientUnits="userSpaceOnUse"><stop class="x68cbnafm"/><stop offset="1" class="uxx-vdb_b"/></linearGradient><linearGradient id="i7eACfb" x1="2.031" x2="4.719" y1="23.688" y2="23.719" gradientUnits="userSpaceOnUse"><stop offset=".342" class="aj6pkxbmi"/><stop offset="1" class="jn_1ukbni"/></linearGradient><linearGradient id="itiRvue" x1="1.688" x2="2.844" y1="22.188" y2="22.188" gradientUnits="userSpaceOnUse"><stop class="qs2quyb7o"/><stop offset="1" class="pnap1sbov"/></linearGradient><linearGradient id="iMDADuo" x1="16" x2="16" y1="15.938" y2="16.688" gradientUnits="userSpaceOnUse"><stop class="qg_bhccvd"/><stop offset="1" class="t1a2xjlji"/></linearGradient><linearGradient id="ijdZy4d" x1="16" x2="16" y1="15.938" y2="16.266" gradientUnits="userSpaceOnUse"><stop class="z2265gg6j"/><stop offset="1" class="u6en0bczu"/></linearGradient><linearGradient id="iGAVQDb" x1="19.313" x2="19.313" y1="28.078" y2="27.469" gradientUnits="userSpaceOnUse"><stop class="l1qc77b7o"/><stop offset="1" class="czdqlvlim"/></linearGradient><linearGradient id="iIRb8hb" x1="16" x2="16" y1="12.023" y2="13.656" gradientUnits="userSpaceOnUse"><stop class="ja2twu1bh"/><stop offset="1" class="edxagb8pk"/></linearGradient><linearGradient id="iFMu5qb" x1="2.031" x2="3.594" y1="15.344" y2="15.344" gradientUnits="userSpaceOnUse"><stop offset=".22" class="ghoog4x-v"/><stop offset="1" class="rnkd18s-i"/></linearGradient><linearGradient id="iLsabab" x1="29.969" x2="27.406" y1="15.594" y2="15.594" gradientUnits="userSpaceOnUse"><stop offset=".15" class="t-t1ozbwo"/><stop offset="1" class="msoj9ypbi"/></linearGradient><linearGradient id="iv66ule" x1="17.625" x2="17.625" y1="15.938" y2="15.594" gradientUnits="userSpaceOnUse"><stop class="onputmdxv"/><stop offset="1" class="f2d9s2b1i"/></linearGradient><linearGradient id="iR60jTc" x1="19.281" x2="16" y1="16.781" y2="26.945" gradientUnits="userSpaceOnUse"><stop class="usrfh7yvd"/><stop offset="1" class="p8_hjlb1c"/></linearGradient><linearGradient id="igBUX9b" x1="12.844" x2="14.656" y1="25.813" y2="23.344" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sl7jd4g5m"/><stop offset="1" class="e4q3-bbvt"/></linearGradient><linearGradient id="iY4wEcd" x1="19.438" x2="12.5" y1="17.008" y2="25.875" gradientUnits="userSpaceOnUse"><stop class="vfl6geb1k"/><stop offset=".599" class="jqwfnqblj"/></linearGradient><linearGradient id="i0G6fFP" x1="17.281" x2="14.063" y1="24.25" y2="19.969" gradientUnits="userSpaceOnUse"><stop class="eo9xzn7ln"/><stop offset="1" class="qdb7hfb7s"/></linearGradient><linearGradient id="iAjZKte" x1="18.475" x2="17.739" y1="19.357" y2="21.054" gradientUnits="userSpaceOnUse"><stop offset=".051" class="lia2x-b9y"/><stop offset="1" class="uxclvxrvp"/></linearGradient><radialGradient id="iSgaTMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21875 -1.6875 0 25.438 11.469)" gradientUnits="userSpaceOnUse"><stop class="lnepqh6ql"/><stop offset="1" class="eefyptbku"/></radialGradient><radialGradient id="iLmqhne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21875 -1.13543 0 8.022 11.469)" gradientUnits="userSpaceOnUse"><stop class="lnepqh6ql"/><stop offset="1" class="eefyptbku"/></radialGradient><radialGradient id="i9NPNNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.93749 -1.25528 0 29.281 27.688)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="qo5hr8p5y"/><stop offset="1" class="f3m8w7bcc"/></radialGradient><radialGradient id="ivQI6Rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -6.48312 0 14.25 25.313)" gradientUnits="userSpaceOnUse"><stop offset=".645" class="qqu7h2bek"/><stop offset="1" class="iiqu7acsd"/></radialGradient><radialGradient id="iYitLsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.678 -16.81 25.417)scale(8.49414 8.46172)" gradientUnits="userSpaceOnUse"><stop offset=".597" class="k10p-ubda"/><stop offset="1" class="juwdgzbmi"/></radialGradient><radialGradient id="isLJiKd" cx="0" cy="0" r="1" gradientTransform="rotate(135.463 12.367 12.527)scale(1.70982 2.07599)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="t-t1ozbwo"/><stop offset="1" class="ozpawybki"/></radialGradient><radialGradient id="ifXMiqW" cx="0" cy="0" r="1" gradientTransform="rotate(143.867 7.624 12.825)scale(11.1822)" gradientUnits="userSpaceOnUse"><stop class="rwhx7cbrd"/><stop offset="1" class="lbxzetdpt"/></radialGradient><radialGradient id="i8iFnRc" cx="0" cy="0" r="1" gradientTransform="rotate(143.911 5.995 13.377)scale(6.41935 5.9978)" gradientUnits="userSpaceOnUse"><stop offset=".068" class="a31o6abkd"/><stop offset="1" class="yrtdvjb5m"/></radialGradient><radialGradient id="iZVYmEe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.54314 3.31158 -3.09411 -4.2448 18.381 20.82)" gradientUnits="userSpaceOnUse"><stop offset=".068" class="a31o6abkd"/><stop offset="1" class="yrtdvjb5m"/></radialGradient><radialGradient id="i2y1Ned" cx="0" cy="0" r="1" gradientTransform="rotate(147.397 6.24 12.765)scale(7.30776 7.07082)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="rf2fd5ggg"/><stop offset=".985" class="llnxr9a9s"/></radialGradient><radialGradient id="iN9RRCd" cx="0" cy="0" r="1" gradientTransform="rotate(-48.614 33.548 -4.007)scale(4.20681 2.88478)" gradientUnits="userSpaceOnUse"><stop class="ltx4xjb8p"/><stop offset="1" class="r3x7zjrii"/></radialGradient><radialGradient id="i5VohiH" cx="0" cy="0" r="1" gradientTransform="rotate(146.088 6.192 12.766)scale(2.24049)" gradientUnits="userSpaceOnUse"><stop class="ltx4xjb8p"/><stop offset="1" class="r3x7zjrii"/></radialGradient><radialGradient id="ijmbnOn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75002 2.24998 -3.93746 -4.81253 11.188 8.813)" gradientUnits="userSpaceOnUse"><stop class="dgq3nebbs"/><stop offset="1" class="ha2ezsvts"/></radialGradient><radialGradient id="iQokmft" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 1 -1.81617 -1.9297 10.469 8.938)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="kf6589yuz"/><stop offset="1" class="bnvrrtbpy"/></radialGradient><radialGradient id="i0uT1Bu" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.895 9.996)scale(6.04688)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="ho94igbje"/><stop offset="1" class="fjrxwybfk"/></radialGradient><filter id="iC0aNhd" width="5.898" height="1.837" x="21.063" y="11.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.709804 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20289"/></filter><filter id="i7AS2Hc" width="3.969" height="1.837" x="5.078" y="11.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.709804 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20289"/></filter><filter id="iiCdACL" width="1.769" height="12.8" x="28.366" y="15.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20289" stdDeviation=".325"/></filter><filter id="i0Ie1Tb" width="4.503" height="2.964" x="5.43" y="15.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20289" stdDeviation=".325"/></filter><filter id="iCiE57b" width="27.938" height="4.014" x="2.031" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.8 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20289"/></filter><filter id="iHGmxlb" width="14.331" height="14.331" x="8.834" y="14.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.529412 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20289"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.54902 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20289" result="effect2_innerShadow_18_20289"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.623529 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_20289" result="effect3_innerShadow_18_20289"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.803922 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_20289" result="effect4_innerShadow_18_20289"/></filter><filter id="io085uy" width="11.037" height="11.037" x="10.481" y="16.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20289" stdDeviation=".2"/></filter><filter id="iw8wLve" width="10.203" height="10.203" x="10.898" y="16.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20289" stdDeviation=".375"/></filter><filter id="iAZ4gFb" width="11.038" height="5.258" x="2.192" y="11.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20289" stdDeviation=".375"/></filter><filter id="iLANLge" width="10.016" height="10.016" x="3.219" y="6.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.666667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20289"/></filter><filter id="iCHSZEe" width="10.094" height="10.094" x="3.055" y="6.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20289" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:camera-with-flash" /></template>
<style>
.a31o6abkd {
  stop-color: var(--svg-color--67616d, #67616D);
}

.a435j-blx {
  stop-color: var(--svg-color--ac91c9, #AC91C9);
}

.aj6pkxbmi {
  stop-color: var(--svg-color--5e5c64, #5E5C64);
}

.bnvrrtbpy {
  stop-color: var(--svg-color--fffca0, #FFFCA0);
  stop-opacity: 0;
}

.czdqlvlim {
  stop-color: var(--svg-color--5c536a, #5C536A);
  stop-opacity: 0;
}

.dgq3nebbs {
  stop-color: var(--svg-color--ffff9c, #FFFF9C);
}

.e4q3-bbvt {
  stop-color: var(--svg-color--b7b6bd, #B7B6BD);
  stop-opacity: 0;
}

.ec0qbw1jt {
  stop-color: var(--svg-color--cfc6de, #CFC6DE);
}

.edxagb8pk {
  stop-color: var(--svg-color--d8d8dc, #D8D8DC);
  stop-opacity: 0;
}

.eefyptbku {
  stop-color: var(--svg-color--cfd0d2, #CFD0D2);
  stop-opacity: 0;
}

.eo9xzn7ln {
  stop-color: var(--svg-color--463755, #463755);
}

.ev1ek_bzg {
  cx: 16px;
  cy: 21.977px;
  r: 4.969px;
}

.f2d9s2b1i {
  stop-color: var(--svg-color--b6adc6, #B6ADC6);
  stop-opacity: 0;
}

.f3m8w7bcc {
  stop-color: var(--svg-color--c8bcdb, #C8BCDB);
  stop-opacity: 0;
}

.fgh-jjb_v {
  cx: 16px;
  cy: 21.977px;
  r: 4.352px;
}

.fjrxwybfk {
  stop-color: var(--svg-color--ffedd9, #FFEDD9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ghoog4x-v {
  stop-color: var(--svg-color--c6c3cc, #C6C3CC);
}

.h4xiyubyd {
  d: path("M2.031 28.141c0 .975.79 1.765 1.765 1.765h24.408c.974 0 1.765-.79 1.765-1.765a.063.063 0 0 0-.063-.063H2.094a.063.063 0 0 0-.063.063");
}

.ha2ezsvts {
  stop-color: var(--svg-color--eac73c, #EAC73C);
}

.ho94igbje {
  stop-color: var(--svg-color--ffedd9, #FFEDD9);
}

.iiqu7acsd {
  stop-color: var(--svg-color--9884af, #9884AF);
  stop-opacity: 0;
}

.j4akg4nsm {
  fill: var(--svg-color--a99a99, #A99A99);
  d: path("M6.125 15.781c-.729-1.091-1.66-1.597-2.596-2.001c-.43-.161-.575-.301-.575-.787c0-.103-.026-.343 0-.438c.334-.25.787-.257 1.237-.257l8.253-.275c.082.102 0 .089 0 .275c0 .463-.292.612-.69.788v.002c-.969.409-1.803 1.44-2.55 2.693z");
}

.ja2twu1bh {
  stop-color: var(--svg-color--d8d8dc, #D8D8DC);
}

.jn_1ukbni {
  stop-color: var(--svg-color--5e5c64, #5E5C64);
  stop-opacity: 0;
}

.jqwfnqblj {
  stop-color: var(--svg-color--40344c, #40344C);
}

.juwdgzbmi {
  stop-color: var(--svg-color--524c5d, #524C5D);
  stop-opacity: 0;
}

.k-e0jwroe {
  d: path("M21.063 11.631a.6.6 0 0 1 .6-.6h4.698a.6.6 0 0 1 .6.6v1.088h-5.898z");
}

.k10p-ubda {
  stop-color: var(--svg-color--4b4357, #4B4357);
}

.kf6589yuz {
  stop-color: var(--svg-color--fffca0, #FFFCA0);
}

.kuquc1bbq {
  d: path("M5.078 11.581a.55.55 0 0 1 .55-.55h2.869a.55.55 0 0 1 .55.55v1.138H5.078z");
}

.l-ihw1uwp {
  stop-color: var(--svg-color--cfcbd7, #CFCBD7);
}

.l1qc77b7o {
  stop-color: var(--svg-color--5c536a, #5C536A);
}

.l8uhoibmo {
  cx: 16px;
  cy: 21.977px;
  r: 7.016px;
}

.lbxzetdpt {
  stop-color: var(--svg-color--a6a2af, #A6A2AF);
}

.lia2x-b9y {
  stop-color: var(--svg-color--f3f2f4, #F3F2F4);
}

.lkwg-hz6x {
  fill: var(--svg-color--8d8d92, #8D8D92);
  d: path("M29.016 16.258h.469v11.5h-.469z");
}

.llnxr9a9s {
  stop-color: var(--svg-color--554863, #554863);
}

.lnepqh6ql {
  stop-color: var(--svg-color--cfd0d2, #CFD0D2);
}

.ltx4xjb8p {
  stop-color: var(--svg-color--544e5c, #544E5C);
}

.ma1grp8cv {
  cx: 16px;
  cy: 21.977px;
  r: 4.969px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.msoj9ypbi {
  stop-color: var(--svg-color--d3cddd, #D3CDDD);
  stop-opacity: 0;
}

.ndzantbta {
  cx: 18.036px;
  cy: 19.985px;
  rx: 0.837px;
  ry: 1.042px;
}

.nfrkcnbbf {
  stop-color: var(--svg-color--c1c2c4, #C1C2C4);
}

.onputmdxv {
  stop-color: var(--svg-color--b6adc6, #B6ADC6);
}

.ozpawybki {
  stop-color: var(--svg-color--f9f7fe, #F9F7FE);
  stop-opacity: 0;
}

.p8_hjlb1c {
  stop-color: var(--svg-color--6a6375, #6A6375);
  stop-opacity: 0;
}

.pnap1sbov {
  stop-color: var(--svg-color--6d6c71, #6D6C71);
  stop-opacity: 0;
}

.pzbiupb8h {
  stop-color: var(--svg-color--c2b3d6, #C2B3D6);
  stop-opacity: 0;
}

.qdb7hfb7s {
  stop-color: var(--svg-color--473f51, #473F51);
}

.qg_bhccvd {
  stop-color: var(--svg-color--706f76, #706F76);
}

.qo5hr8p5y {
  stop-color: var(--svg-color--f7f4fe, #F7F4FE);
}

.qqu7h2bek {
  stop-color: var(--svg-color--9884af, #9884AF);
}

.qs2quyb7o {
  stop-color: var(--svg-color--8f8f91, #8F8F91);
}

.r3x7zjrii {
  stop-color: var(--svg-color--544e5c, #544E5C);
  stop-opacity: 0;
}

.r5hqvv_4v {
  stop-color: var(--svg-color--cfcbd7, #CFCBD7);
  stop-opacity: 0;
}

.r8fmqwffn {
  d: path("M2.031 14.023a2 2 0 0 1 2-2H27.97a2 2 0 0 1 2 2v1.665a.25.25 0 0 1-.25.25H2.28a.25.25 0 0 1-.25-.25z");
}

.rf2fd5ggg {
  stop-color: var(--svg-color--554863, #554863);
  stop-opacity: 0;
}

.rnkd18s-i {
  stop-color: var(--svg-color--c6c3cc, #C6C3CC);
  stop-opacity: 0;
}

.rpt3bxeag {
  stop-color: var(--svg-color--949597, #949597);
}

.rwhx7cbrd {
  stop-color: var(--svg-color--a6a2ae, #A6A2AE);
}

.sl7jd4g5m {
  stop-color: var(--svg-color--b7b6bd, #B7B6BD);
}

.sywzq8j_s {
  d: path("M2.031 16.188a.25.25 0 0 1 .25-.25H29.72a.25.25 0 0 1 .25.25v11.64a.25.25 0 0 1-.25.25H2.28a.25.25 0 0 1-.25-.25z");
}

.t-t1ozbwo {
  stop-color: var(--svg-color--f9f7fe, #F9F7FE);
}

.t1a2xjlji {
  stop-color: var(--svg-color--706f76, #706F76);
  stop-opacity: 0;
}

.tb4leegtb {
  fill: var(--svg-color--4e474a, #4E474A);
  d: path("M9.282 15.725q-.302.452-.566 1.008h-.01a1.133 1.133 0 0 1-2.057 0h-.003a8 8 0 0 0-.566-1.008z");
}

.u2myzybpq {
  stop-color: var(--svg-color--c3b4d7, #C3B4D7);
}

.u6en0bczu {
  stop-color: var(--svg-color--5f5e65, #5F5E65);
  stop-opacity: 0;
}

.usrfh7yvd {
  stop-color: var(--svg-color--6a6375, #6A6375);
}

.uxclvxrvp {
  stop-color: var(--svg-color--f3f2f4, #F3F2F4);
  stop-opacity: 0;
}

.uxx-vdb_b {
  stop-color: var(--svg-color--6b6873, #6B6873);
}

.v3anf-bfi {
  cx: 16px;
  cy: 21.977px;
  r: 2.453px;
}

.vfl6geb1k {
  stop-color: var(--svg-color--2c2634, #2C2634);
}

.vt1gpbbjj {
  fill: var(--svg-color--dad4e6, #DAD4E6);
  d: path("M2.031 14.023a2 2 0 0 1 2-2H27.97a2 2 0 0 1 2 2v1.665a.25.25 0 0 1-.25.25H2.28a.25.25 0 0 1-.25-.25z");
}

.wmh2hob9q {
  d: path("M8.102 7.008c.455 0 .848.269 1.028.656h.01c.82 1.738 1.954 2.676 3.169 3.188v.002a1.133 1.133 0 0 1 0 2.073v.003c-1.215.511-2.348 1.449-3.168 3.187a1.12 1.12 0 0 1-1.04.656a1.13 1.13 0 0 1-1.027-.656H7.07c-.808-1.714-1.92-2.649-3.116-3.165a1.133 1.133 0 0 1 0-2.122c1.195-.517 2.308-1.452 3.116-3.166h.004c.18-.387.572-.656 1.028-.656");
}

.x68cbnafm {
  stop-color: var(--svg-color--66636f, #66636F);
}

.yrtdvjb5m {
  stop-color: var(--svg-color--4d3e5c, #4D3E5C);
}

.z2265gg6j {
  stop-color: var(--svg-color--5f5e65, #5F5E65);
}

.zlma_6btf {
  d: path("M8.102 8.344c.33 0 .616.195.746.477h.008c.596 1.262 1.42 1.943 2.302 2.315v.002a.823.823 0 0 1 0 1.506v.001c-.883.372-1.706 1.053-2.302 2.316h-.008a.823.823 0 0 1-1.493 0h-.003c-.587-1.245-1.395-1.925-2.263-2.3a.823.823 0 0 1 0-1.541c.868-.375 1.676-1.055 2.263-2.3h.003a.82.82 0 0 1 .747-.476");
}

</style>
