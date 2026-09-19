<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8m23Bc)"><path fill="url(#iiAN8xe)" class="wuu391bav"/><path fill="url(#if68NxM)" class="wuu391bav"/><path fill="url(#iZAlS7d)" class="wuu391bav"/></g><path fill="url(#ihMj83b)" class="duoizhb_i"/><path fill="url(#ipjhZfe)" class="duoizhb_i"/><path fill="url(#iPPZzXA)" class="duoizhb_i"/><path fill="url(#iOEBsVd)" class="duoizhb_i"/><path fill="url(#iuQ8WId)" class="duoizhb_i"/><path fill="url(#is8Iymd)" class="duoizhb_i"/><path fill="url(#ii97bJb)" class="duoizhb_i"/><path fill="url(#iopQS3b)" class="duoizhb_i"/><path fill="url(#i6euFkc)" class="duoizhb_i"/><path fill="url(#iQrhged)" class="v2caxibau"/><path fill="url(#i5s4cSb)" class="v2caxibau"/><g filter="url(#iSttXod)"><path class="zvj_9ab8f"/><path fill="url(#iK1AJlb)" class="h5a3otwqo"/><path fill="url(#iv3i2ze)" class="h5a3otwqo"/><path fill="url(#inZQlFe)" class="h5a3otwqo"/><path fill="url(#iz6QCTz)" class="mxg5lqyny"/><path fill="url(#iiPKJGv)" class="h5a3otwqo"/></g><g filter="url(#iOZ1rxc)"><path fill="url(#idRK03d)" class="yg37wrblh"/><path fill="url(#itBp1kc)" class="yg37wrblh"/><path fill="url(#iaC5zmI)" class="yg37wrblh"/></g><path fill="url(#i90C3jB)" class="yg37wrblh"/><path fill="url(#iJKqgRd)" class="yg37wrblh"/><g filter="url(#iHlbsNc)"><path fill="url(#ij0M7WE)" class="c0fzj7_mc"/><path fill="url(#iWcPljb)" class="c0fzj7_mc"/><path fill="url(#i5urqPG)" class="c0fzj7_mc"/><path fill="url(#iwZ5BCe)" class="c0fzj7_mc"/><path fill="url(#iBfH6Ob)" class="c0fzj7_mc"/><path fill="url(#ibhuugb)" class="c0fzj7_mc"/></g><g filter="url(#iPrLHJe)"><path stroke="url(#ia0Gu9s)" class="d7notq2xg"/></g><g filter="url(#ieMyNNX)"><path fill="url(#i81Ymte)" class="js1k9qh3y"/></g><g filter="url(#iVBi2Zb)"><path fill="url(#icOahIe)" class="qchacs6gd"/></g><g filter="url(#iyS5xIe)"><ellipse fill="url(#iw2YA5b)" transform="rotate(13.617 23.415 17.519)" class="c93yxxbda"/></g><g filter="url(#iNgY4kb)"><path fill="url(#imub2Vc)" class="i7l22ac9q"/></g><g filter="url(#iS3Oi8c)"><path fill="url(#if5Uqzc)" class="pc38lrb1r"/><path fill="url(#iBEkSOd)" class="pc38lrb1r"/></g><g filter="url(#ijtjYhX)"><path fill="url(#i2hUcCf)" class="a2xddbclb"/></g><g filter="url(#ieveGxd)"><ellipse fill="url(#isAEW0d)" transform="rotate(6.434 24.212 8.766)" class="o3-g_db5n"/></g><g filter="url(#iIyAJpV)"><ellipse fill="url(#iGKZZLd)" transform="rotate(-97.022 21.274 5.7)" class="wqrt4blqq"/></g><defs><radialGradient id="if68NxM" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 .1875 -.20052 -.91904 21.822 29.725)" gradientUnits="userSpaceOnUse"><stop class="fz54du4sr"/><stop offset="1" class="p88bivhxd"/></radialGradient><radialGradient id="iZAlS7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .17188 -.99916 -5.4499 17.229 23.084)" gradientUnits="userSpaceOnUse"><stop class="vel21obtg"/><stop offset="1" class="s1jy6pbhr"/></radialGradient><radialGradient id="ipjhZfe" cx="0" cy="0" r="1" gradientTransform="rotate(-161.184 15.205 7.1)scale(8.91387 4.25138)" gradientUnits="userSpaceOnUse"><stop class="vvt15hb0f"/><stop offset="1" class="zgxznhi6i"/></radialGradient><radialGradient id="iPPZzXA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.47638 -3 3.38577 -3.92342 24.744 23.537)" gradientUnits="userSpaceOnUse"><stop class="y7bg4rbfw"/><stop offset="1" class="zlo2y9b5v"/></radialGradient><radialGradient id="iOEBsVd" cx="0" cy="0" r="1" gradientTransform="rotate(178.075 11.797 11.189)scale(3.72085 7.0097)" gradientUnits="userSpaceOnUse"><stop class="tk4zk-bdb"/><stop offset="1" class="mr3oxccxq"/></radialGradient><radialGradient id="iuQ8WId" cx="0" cy="0" r="1" gradientTransform="matrix(5.2111 5.14368 -.56937 .57683 16.057 13.912)" gradientUnits="userSpaceOnUse"><stop class="oc_qyt5ql"/><stop offset="1" class="traizac5a"/></radialGradient><radialGradient id="is8Iymd" cx="0" cy="0" r="1" gradientTransform="rotate(99.541 5.396 15.48)scale(1.74286 8.17569)" gradientUnits="userSpaceOnUse"><stop class="a4lje9ldk"/><stop offset="1" class="ylkz39bfe"/></radialGradient><radialGradient id="ii97bJb" cx="0" cy="0" r="1" gradientTransform="rotate(-179.091 11.897 10.91)scale(1.969 2.34643)" gradientUnits="userSpaceOnUse"><stop class="g0kj2vb1g"/><stop offset="1" class="uqunobg5s"/></radialGradient><radialGradient id="iopQS3b" cx="0" cy="0" r="1" gradientTransform="matrix(-8.4375 -.06244 .14151 -19.12278 22.994 17.662)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="i6hhhctqg"/><stop offset="1" class="v88c76bwg"/></radialGradient><radialGradient id="i6euFkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99235 8.625 -6.70944 -1.54986 21.268 16.6)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="jf03ln08u"/><stop offset=".969" class="pfuxhgbep"/></radialGradient><radialGradient id="i5s4cSb" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 6.1875 -14.72894 .44633 22.557 15.443)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="jf03ln08u"/><stop offset="1" class="pfuxhgbep"/></radialGradient><radialGradient id="iK1AJlb" cx="0" cy="0" r="1" gradientTransform="rotate(135 9.864 8.245)scale(10.6066 10.051)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="hvvhf-b6v"/><stop offset="1" class="dpoxmkw2l"/></radialGradient><radialGradient id="iv3i2ze" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99999 4.1875 -4.40457 -4.20733 24.418 5.037)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="hs8ki979t"/><stop offset="1" class="mqow4y04l"/></radialGradient><radialGradient id="inZQlFe" cx="0" cy="0" r="1" gradientTransform="rotate(-45 25.927 -9.12)scale(8.83883 6.0546)" gradientUnits="userSpaceOnUse"><stop class="fgwe66bok"/><stop offset="1" class="ttp3dzb3l"/></radialGradient><radialGradient id="iz6QCTz" cx="0" cy="0" r="1" gradientTransform="rotate(136.672 8.056 8.811)scale(6.05718 .89244)" gradientUnits="userSpaceOnUse"><stop class="s5-ipwpda"/><stop offset="1" class="w907u8oyl"/></radialGradient><radialGradient id="iiPKJGv" cx="0" cy="0" r="1" gradientTransform="matrix(-5.43753 5.12496 -.11597 -.12304 23.635 5.834)" gradientUnits="userSpaceOnUse"><stop class="xn20_mb_h"/><stop offset="1" class="p908hz0rk"/></radialGradient><radialGradient id="idRK03d" cx="0" cy="0" r="1" gradientTransform="rotate(-47.586 26.064 -5.431)scale(6.85708 6.70787)" gradientUnits="userSpaceOnUse"><stop class="pgdoaj92a"/><stop offset="1" class="ej42q0bnx"/></radialGradient><radialGradient id="itBp1kc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -3.375 .48572 .5127 12.525 16.6)" gradientUnits="userSpaceOnUse"><stop class="i0d_dob-j"/><stop offset="1" class="lfvc-ki2i"/></radialGradient><radialGradient id="iaC5zmI" cx="0" cy="0" r="1" gradientTransform="matrix(-5.31482 5.13767 -.0608 -.06289 15.856 13.587)" gradientUnits="userSpaceOnUse"><stop offset=".366" class="ga4cd8bkb"/><stop offset="1" class="hopug3b2j"/></radialGradient><radialGradient id="i90C3jB" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.89844 1.12878 .46133 7.19 21.232)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="v9k6_h7ua"/><stop offset="1" class="uahlglbvs"/></radialGradient><radialGradient id="iJKqgRd" cx="0" cy="0" r="1" gradientTransform="matrix(.6023 -1.65625 6.2 2.25465 10.33 24.725)" gradientUnits="userSpaceOnUse"><stop class="v9k6_h7ua"/><stop offset="1" class="uahlglbvs"/></radialGradient><radialGradient id="iWcPljb" cx="0" cy="0" r="1" gradientTransform="rotate(45 -1.96 11.72)scale(5.43588 7.34918)" gradientUnits="userSpaceOnUse"><stop class="hny4279fr"/><stop offset="1" class="odf4r6p7m"/></radialGradient><radialGradient id="i5urqPG" cx="0" cy="0" r="1" gradientTransform="rotate(145.105 6.777 4.537)scale(4.53394 4.41419)" gradientUnits="userSpaceOnUse"><stop class="xcbbuobzm"/><stop offset="1" class="e66uyob0u"/></radialGradient><radialGradient id="iwZ5BCe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.582 10.786 3.51)scale(9.90899 .51511)" gradientUnits="userSpaceOnUse"><stop offset=".433" class="n9h-8xboq"/><stop offset="1" class="xuv9_pbdt"/></radialGradient><radialGradient id="iBfH6Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-6.65627 -6.8906 .03697 -.03571 15.994 13.834)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="lf-uxmb-c"/><stop offset="1" class="jgru2r76f"/></radialGradient><radialGradient id="ibhuugb" cx="0" cy="0" r="1" gradientTransform="matrix(6.1875 .47362 -.24275 3.17136 8.963 13.657)" gradientUnits="userSpaceOnUse"><stop class="mn3xenbyv"/><stop offset="1" class="y12jjt74v"/></radialGradient><radialGradient id="icOahIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 6.21875 -1.63255 -.09024 14.838 14.225)" gradientUnits="userSpaceOnUse"><stop class="ftru0hjfu"/><stop offset="1" class="u2i623t7o"/></radialGradient><radialGradient id="iw2YA5b" cx="0" cy="0" r="1" gradientTransform="rotate(167.615 12.408 9.618)scale(5.44834 2.82167)" gradientUnits="userSpaceOnUse"><stop class="axzt8hrpg"/><stop offset="1" class="hfcbhkbxt"/></radialGradient><radialGradient id="imub2Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-.54502 .52322 -3.31096 -3.4489 19.847 17.95)" gradientUnits="userSpaceOnUse"><stop class="zn_xutbkp"/><stop offset="1" class="ek63yccse"/></radialGradient><radialGradient id="if5Uqzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96875 1.03344 -4.64055 -8.84044 14.932 8.316)" gradientUnits="userSpaceOnUse"><stop class="mpwes_iff"/><stop offset="1" class="txq-adbxg"/></radialGradient><radialGradient id="iBEkSOd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.84377 -1.09382 .5334 -5.28796 21.12 8.943)" gradientUnits="userSpaceOnUse"><stop class="mpwes_iff"/><stop offset=".999" class="txq-adbxg"/></radialGradient><radialGradient id="isAEW0d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0759 .05337 -.01868 -1.07679 25.672 8.602)" gradientUnits="userSpaceOnUse"><stop class="h85uyoefd"/><stop offset="1" class="hkawme14e"/></radialGradient><radialGradient id="iGKZZLd" cx="0" cy="0" r="1" gradientTransform="matrix(4.13832 -.73388 .25691 1.44872 19.758 6.555)" gradientUnits="userSpaceOnUse"><stop class="h85uyoefd"/><stop offset="1" class="hkawme14e"/></radialGradient><filter id="i8m23Bc" width="6.978" height="13.963" x="14.917" y="16.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.380392 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7891"/></filter><filter id="iSttXod" width="11.254" height="11.167" x="15.856" y="2.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.596078 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7891"/></filter><filter id="iOZ1rxc" width="11.053" height="10.938" x="4.803" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.576471 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7891"/></filter><filter id="iHlbsNc" width="11.254" height="11.167" x="4.852" y="2.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.505882 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7891"/></filter><filter id="iPrLHJe" width="6.172" height="9.225" x="15.45" y="20.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".2"/></filter><filter id="ieMyNNX" width="6.175" height="5.387" x="9.9" y="13.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".25"/></filter><filter id="iVBi2Zb" width="4.535" height="6.469" x="11.432" y="14.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".25"/></filter><filter id="iyS5xIe" width="8.518" height="7.692" x="19.156" y="13.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".625"/></filter><filter id="iNgY4kb" width="6.556" height="6.44" x="15.969" y="14.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".2"/></filter><filter id="iS3Oi8c" width="7.132" height="11.442" x="9.112" y="2.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".375"/></filter><filter id="ijtjYhX" width="6.281" height="6.516" x="9.143" y="6.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".25"/></filter><filter id="ieveGxd" width="6.211" height="4.273" x="21.107" y="6.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".5"/></filter><filter id="iIyAJpV" width="4.28" height="6.207" x="19.134" y="2.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7891" stdDeviation=".5"/></filter><linearGradient id="iiAN8xe" x1="16.369" x2="21.369" y1="19.475" y2="30.412" gradientUnits="userSpaceOnUse"><stop class="jxa6n8buo"/><stop offset="1" class="rngfnpbcg"/></linearGradient><linearGradient id="ihMj83b" x1="15.244" x2="21.994" y1="13.975" y2="19.975" gradientUnits="userSpaceOnUse"><stop class="pdgei4bbw"/><stop offset="1" class="h-dczab8z"/></linearGradient><linearGradient id="iQrhged" x1="15.182" x2="18.619" y1="17.262" y2="14.568" gradientUnits="userSpaceOnUse"><stop class="tddngsb5q"/><stop offset="1" class="fa7h1z8mt"/></linearGradient><linearGradient id="ij0M7WE" x1="10.354" x2="15.856" y1="5.287" y2="14.287" gradientUnits="userSpaceOnUse"><stop class="b8puysb2s"/><stop offset="1" class="rssferj3w"/></linearGradient><linearGradient id="ia0Gu9s" x1="21.072" x2="15.791" y1="29.287" y2="22.006" gradientUnits="userSpaceOnUse"><stop class="g0u1tqtcm"/><stop offset="1" class="fo45iybrt"/></linearGradient><linearGradient id="i81Ymte" x1="14.963" x2="9.119" y1="14.725" y2="18.006" gradientUnits="userSpaceOnUse"><stop class="mzh9t9bxq"/><stop offset="1" class="u2i623t7o"/></linearGradient><linearGradient id="i2hUcCf" x1="12.127" x2="12.768" y1="10.771" y2="10.092" gradientUnits="userSpaceOnUse"><stop class="e2oflny8d"/><stop offset="1" class="g248rhbnt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:four-leaf-clover" /></template>
<style>
.a2xddbclb {
  d: path("m9.643 7.334l5.28 5.516c-.905-.453-1.765-.766-3.171-2.25c-1.451-1.532-2.11-2.776-2.11-3.266");
}

.a4lje9ldk {
  stop-color: var(--svg-color--439059, #439059);
}

.axzt8hrpg {
  stop-color: var(--svg-color--81ffb3, #81FFB3);
}

.b8puysb2s {
  stop-color: var(--svg-color--3ac97d, #3AC97D);
}

.c0fzj7_mc {
  d: path("M13.697 3.475c2.5 2.093 2.14 7.109 2.14 10.156c-4.062 0-6.796.328-9.421-1.328c-3.163-1.996-1.047-6.235 2.094-5.907c-.485-2.78 2.935-4.808 5.187-2.921");
}

.c93yxxbda {
  cx: 23.415px;
  cy: 17.519px;
  rx: 3.032px;
  ry: 2.568px;
}

.d7notq2xg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.01 21.38c-.115 1.803.737 5.95 5.062 8.126");
}

.dpoxmkw2l {
  stop-color: var(--svg-color--188a50, #188A50);
}

.duoizhb_i {
  d: path("M17.965 23.84c-2.799-2.115-2.182-7.193-2.182-10.24c4.063 0 6.838-.244 9.463 1.412c3.164 1.996 1.047 6.234-2.093 5.906c.484 2.781-2.844 4.693-5.188 2.922");
}

.e2oflny8d {
  stop-color: var(--svg-color--75d79f, #75D79F);
}

.e66uyob0u {
  stop-color: var(--svg-color--5af095, #5AF095);
  stop-opacity: 0;
}

.ej42q0bnx {
  stop-color: var(--svg-color--39b97c, #39B97C);
}

.ek63yccse {
  stop-color: var(--svg-color--72dda1, #72DDA1);
  stop-opacity: 0;
}

.fa7h1z8mt {
  stop-color: var(--svg-color--219756, #219756);
  stop-opacity: 0;
}

.fgwe66bok {
  stop-color: var(--svg-color--338b6e, #338B6E);
}

.fo45iybrt {
  stop-color: var(--svg-color--69aa99, #69AA99);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftru0hjfu {
  stop-color: var(--svg-color--6ee79d, #6EE79D);
}

.fz54du4sr {
  stop-color: var(--svg-color--6aac9a, #6AAC9A);
}

.g0kj2vb1g {
  stop-color: var(--svg-color--4dd695, #4DD695);
}

.g0u1tqtcm {
  stop-color: var(--svg-color--69aa99, #69AA99);
}

.g248rhbnt {
  stop-color: var(--svg-color--75d79f, #75D79F);
  stop-opacity: 0;
}

.ga4cd8bkb {
  stop-color: var(--svg-color--6ad392, #6AD392);
}

.h-dczab8z {
  stop-color: var(--svg-color--3cce7f, #3CCE7F);
}

.h5a3otwqo {
  d: path("M18.014 3.475c-2.5 2.093-2.14 7.109-2.14 10.156c4.062 0 6.797.328 9.422-1.328c3.163-1.996 1.046-6.235-2.094-5.907c.484-2.78-2.935-4.808-5.188-2.921");
}

.h85uyoefd {
  stop-color: var(--svg-color--80ffb4, #80FFB4);
}

.hfcbhkbxt {
  stop-color: var(--svg-color--81ffb3, #81FFB3);
  stop-opacity: 0;
}

.hkawme14e {
  stop-color: var(--svg-color--80ffb4, #80FFB4);
  stop-opacity: 0;
}

.hny4279fr {
  stop-color: var(--svg-color--3bc577, #3BC577);
}

.hopug3b2j {
  stop-color: var(--svg-color--6ad392, #6AD392);
  stop-opacity: 0;
}

.hs8ki979t {
  stop-color: var(--svg-color--75f9a8, #75F9A8);
}

.hvvhf-b6v {
  stop-color: var(--svg-color--188a50, #188A50);
  stop-opacity: 0;
}

.i0d_dob-j {
  stop-color: var(--svg-color--1fae5a, #1FAE5A);
}

.i6hhhctqg {
  stop-color: var(--svg-color--1d9453, #1D9453);
  stop-opacity: 0;
}

.i7l22ac9q {
  d: path("m22.125 20.052l-5.756-5.64c.59.8 1.276 1.683 2.704 3.438c1.303 1.601 2.017 2.082 3.052 2.202");
}

.jf03ln08u {
  stop-color: var(--svg-color--438882, #438882);
  stop-opacity: 0;
}

.jgru2r76f {
  stop-color: var(--svg-color--4eb87f, #4EB87F);
  stop-opacity: 0;
}

.js1k9qh3y {
  d: path("m10.4 18.193l5.175-4.386c-.551.105-2.001.692-3.112 1.636c-1.25 1.063-2.034 2.328-2.063 2.75");
}

.jxa6n8buo {
  stop-color: var(--svg-color--18554d, #18554D);
}

.lf-uxmb-c {
  stop-color: var(--svg-color--4eb87f, #4EB87F);
}

.lfvc-ki2i {
  stop-color: var(--svg-color--1fae5a, #1FAE5A);
  stop-opacity: 0;
}

.mn3xenbyv {
  stop-color: var(--svg-color--379876, #379876);
}

.mpwes_iff {
  stop-color: var(--svg-color--77e8a3, #77E8A3);
}

.mqow4y04l {
  stop-color: var(--svg-color--75f9a8, #75F9A8);
  stop-opacity: 0;
}

.mr3oxccxq {
  stop-color: var(--svg-color--45df94, #45DF94);
  stop-opacity: 0;
}

.mxg5lqyny {
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("M18.014 3.475c-2.5 2.093-2.14 7.109-2.14 10.156c4.062 0 6.797.328 9.422-1.328c3.163-1.996 1.046-6.235-2.094-5.907c.484-2.78-2.935-4.808-5.188-2.921");
}

.mzh9t9bxq {
  stop-color: var(--svg-color--75e2a0, #75E2A0);
}

.n9h-8xboq {
  stop-color: var(--svg-color--3aa578, #3AA578);
}

.o3-g_db5n {
  cx: 24.212px;
  cy: 8.766px;
  rx: 2.115px;
  ry: 1.118px;
}

.oc_qyt5ql {
  stop-color: var(--svg-color--249f5c, #249F5C);
}

.odf4r6p7m {
  stop-color: var(--svg-color--3bc577, #3BC577);
  stop-opacity: 0;
}

.p88bivhxd {
  stop-color: var(--svg-color--6aac9a, #6AAC9A);
  stop-opacity: 0;
}

.p908hz0rk {
  stop-color: var(--svg-color--79f0af, #79F0AF);
  stop-opacity: 0;
}

.pc38lrb1r {
  d: path("m10.432 6.35l5.062 6.937c0-1.516 0-4.187-.625-6.656c-.393-1.551-1.484-3.781-3.86-3.188c-1.9.475-.952 2.625-.578 2.907");
}

.pdgei4bbw {
  stop-color: var(--svg-color--2c9c60, #2C9C60);
}

.pfuxhgbep {
  stop-color: var(--svg-color--438882, #438882);
}

.pgdoaj92a {
  stop-color: var(--svg-color--53ce8d, #53CE8D);
}

.qchacs6gd {
  d: path("m15.4 14.63l-3.468 3.376l3.03 2.094c.6-2.2.543-4.563.438-5.47");
}

.rngfnpbcg {
  stop-color: var(--svg-color--509e85, #509E85);
}

.rssferj3w {
  stop-color: var(--svg-color--3fad80, #3FAD80);
}

.s1jy6pbhr {
  stop-color: var(--svg-color--557c70, #557C70);
  stop-opacity: 0;
}

.s5-ipwpda {
  stop-color: var(--svg-color--309b69, #309B69);
}

.tddngsb5q {
  stop-color: var(--svg-color--219756, #219756);
}

.tk4zk-bdb {
  stop-color: var(--svg-color--45df94, #45DF94);
}

.traizac5a {
  stop-color: var(--svg-color--249f5c, #249F5C);
  stop-opacity: 0;
}

.ttp3dzb3l {
  stop-color: var(--svg-color--338b6e, #338B6E);
  stop-opacity: 0;
}

.txq-adbxg {
  stop-color: var(--svg-color--77e8a3, #77E8A3);
  stop-opacity: 0;
}

.u2i623t7o {
  stop-color: var(--svg-color--72d79a, #72D79A);
  stop-opacity: 0;
}

.uahlglbvs {
  stop-color: var(--svg-color--718c9f, #718C9F);
  stop-opacity: 0;
}

.uqunobg5s {
  stop-color: var(--svg-color--4dd695, #4DD695);
  stop-opacity: 0;
}

.v2caxibau {
  d: path("M15.783 13.648V13.6q.718-.001 1.384-.007c3.33-.024 5.764-.042 8.08 1.419c3.128 1.974 1.122 6.174-2.089 5.908z");
}

.v88c76bwg {
  stop-color: var(--svg-color--1d9453, #1D9453);
}

.v9k6_h7ua {
  stop-color: var(--svg-color--718c9f, #718C9F);
}

.vel21obtg {
  stop-color: var(--svg-color--557c70, #557C70);
}

.vvt15hb0f {
  stop-color: var(--svg-color--46d282, #46D282);
}

.w907u8oyl {
  stop-color: var(--svg-color--34bb72, #34BB72);
  stop-opacity: 0;
}

.wqrt4blqq {
  cx: 21.274px;
  cy: 5.701px;
  rx: 2.115px;
  ry: 1.118px;
}

.wuu391bav {
  d: path("M20.47 30.503a.875.875 0 1 0 .799-1.557zm.799-1.557c-2.709-1.39-3.812-3.233-4.277-5.269c-.49-2.143-.28-4.44-.28-6.89h-1.75c0 2.226-.225 4.881.324 7.28c.573 2.506 1.986 4.795 5.184 6.436z");
}

.xcbbuobzm {
  stop-color: var(--svg-color--5af095, #5AF095);
}

.xn20_mb_h {
  stop-color: var(--svg-color--79f0af, #79F0AF);
}

.xuv9_pbdt {
  stop-color: var(--svg-color--3aa578, #3AA578);
  stop-opacity: 0;
}

.y12jjt74v {
  stop-color: var(--svg-color--379876, #379876);
  stop-opacity: 0;
}

.y7bg4rbfw {
  stop-color: var(--svg-color--43d592, #43D592);
}

.yg37wrblh {
  d: path("M13.648 23.84c2.799-2.116 2.14-7.193 2.14-10.24c-4.062 0-6.797-.245-9.422 1.412c-3.163 1.996-1.046 6.234 2.094 5.906c-.484 2.781 2.844 4.693 5.188 2.922");
}

.ylkz39bfe {
  stop-color: var(--svg-color--439059, #439059);
  stop-opacity: 0;
}

.zgxznhi6i {
  stop-color: var(--svg-color--46d282, #46D282);
  stop-opacity: 0;
}

.zlo2y9b5v {
  stop-color: var(--svg-color--43d592, #43D592);
  stop-opacity: 0;
}

.zn_xutbkp {
  stop-color: var(--svg-color--72dda1, #72DDA1);
}

.zvj_9ab8f {
  fill: var(--svg-color--48d386, #48D386);
  d: path("M18.014 3.475c-2.5 2.093-2.14 7.109-2.14 10.156c4.062 0 6.797.328 9.422-1.328c3.163-1.996 1.046-6.235-2.094-5.907c.484-2.78-2.935-4.808-5.188-2.921");
}

</style>
