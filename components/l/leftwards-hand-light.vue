<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGGLvte)"><path fill="url(#iUahgyu)" class="eurr65b3y"/><path fill="url(#iEtZrTl)" class="eurr65b3y"/></g><path fill="url(#i6h8Kad)" class="qjws5qxoo"/><path fill="url(#iYKesTd)" class="qjws5qxoo"/><path fill="url(#iiZO2zc)" class="qjws5qxoo"/><path fill="url(#iyM83se)" class="qjws5qxoo"/><path fill="url(#iOPlW0b)" class="qjws5qxoo"/><path fill="url(#iPMdwge)" class="xoe87acmz"/><path fill="url(#i9c0f1b)" class="xoe87acmz"/><path fill="url(#ib3hUeM)" class="xoe87acmz"/><path fill="url(#ialEVOe)" class="xoe87acmz"/><path fill="url(#iKSNtgM)" class="xoe87acmz"/><path fill="url(#i2Mxw7d)" class="xoe87acmz"/><path fill="url(#ieb0zVc)" class="xv8ebljba"/><path fill="url(#iwUmTQd)" class="xv8ebljba"/><path fill="url(#iZWgFBO)" class="xv8ebljba"/><path fill="url(#iv8u3Gd)" class="xv8ebljba"/><path fill="url(#ihzScCN)" class="xv8ebljba"/><path fill="url(#iMbKi7Z)" class="xdoag_q9p"/><path fill="url(#i0ijaGd)" class="xdoag_q9p"/><path fill="url(#iVzNfob)" class="xdoag_q9p"/><g filter="url(#iPvBtOc)"><path fill="url(#iZc13mW)" class="t2d1oablt"/></g><g filter="url(#i4Smksw)"><path fill="url(#i9xcXVA)" class="ee2yicsdd"/></g><g filter="url(#izg5axe)"><path fill="url(#isG61de)" class="m43x-n-zd"/></g><g filter="url(#iY2fWxe)"><path class="fetf0hbus"/></g><path fill="url(#iMdFjCR)" class="xcl71mbby"/><g filter="url(#idOjGcb)"><path stroke="url(#iJvdcke)" class="u21ufccuh"/></g><g filter="url(#ihDUvcb)"><path stroke="url(#ijc2p5c)" class="ae_ernsjy"/></g><g filter="url(#iYOBmMd)"><path stroke="url(#iLKcMAE)" class="qk_wm3boh"/></g><g filter="url(#iUr6ErN)"><path stroke="url(#iJta8Je)" class="qpqbqtbbm"/></g><g filter="url(#iIBzwHe)"><path stroke="url(#inAPbze)" class="fsu03cbcn"/></g><path fill="url(#iCubaac)" class="eurr65b3y"/><path fill="url(#im5iG6c)" class="eurr65b3y"/><path fill="url(#iZECcnV)" class="eurr65b3y"/><path fill="url(#i3M3eHe)" class="eurr65b3y"/><defs><linearGradient id="i6h8Kad" x1="7.524" x2="7.629" y1="13.878" y2="11.772" gradientUnits="userSpaceOnUse"><stop offset=".043" class="bfgq6bbgm"/><stop offset="1" class="hbgieofjc"/></linearGradient><linearGradient id="iYKesTd" x1="3.822" x2="6.287" y1="11.408" y2="11.227" gradientUnits="userSpaceOnUse"><stop class="yegb75-ac"/><stop offset="1" class="rnkcqiywh"/></linearGradient><linearGradient id="iiZO2zc" x1="10.752" x2="10.8" y1="14.336" y2="13.398" gradientUnits="userSpaceOnUse"><stop offset=".07" class="lx3zquz-s"/><stop offset="1" class="u308zo_yo"/></linearGradient><linearGradient id="iOPlW0b" x1="15.941" x2="13.416" y1="13.402" y2="13.276" gradientUnits="userSpaceOnUse"><stop class="j_sdomb5r"/><stop offset="1" class="akw4o1b4x"/></linearGradient><linearGradient id="iPMdwge" x1="6.05" x2="6.095" y1="18.281" y2="15.871" gradientUnits="userSpaceOnUse"><stop offset=".043" class="ihbj04bdr"/><stop offset="1" class="em_5boqhn"/></linearGradient><linearGradient id="i9c0f1b" x1="1.676" x2="4.554" y1="15.778" y2="15.531" gradientUnits="userSpaceOnUse"><stop class="yegb75-ac"/><stop offset="1" class="rnkcqiywh"/></linearGradient><linearGradient id="ib3hUeM" x1="9.844" x2="9.826" y1="18.813" y2="17.771" gradientUnits="userSpaceOnUse"><stop offset=".07" class="lx3zquz-s"/><stop offset="1" class="u308zo_yo"/></linearGradient><linearGradient id="iKSNtgM" x1="15.86" x2="12.907" y1="17.775" y2="17.602" gradientUnits="userSpaceOnUse"><stop class="j_sdomb5r"/><stop offset="1" class="akw4o1b4x"/></linearGradient><linearGradient id="ieb0zVc" x1="7.648" x2="7.692" y1="22.711" y2="20.522" gradientUnits="userSpaceOnUse"><stop offset=".043" class="ihbj04bdr"/><stop offset="1" class="em_5boqhn"/></linearGradient><linearGradient id="iwUmTQd" x1="3.949" x2="6.385" y1="20.437" y2="20.242" gradientUnits="userSpaceOnUse"><stop class="yegb75-ac"/><stop offset="1" class="rnkcqiywh"/></linearGradient><linearGradient id="iZWgFBO" x1="10.855" x2="10.838" y1="23.194" y2="22.248" gradientUnits="userSpaceOnUse"><stop offset=".07" class="lx3zquz-s"/><stop offset="1" class="u308zo_yo"/></linearGradient><linearGradient id="ihzScCN" x1="15.942" x2="13.444" y1="22.251" y2="22.116" gradientUnits="userSpaceOnUse"><stop class="j_sdomb5r"/><stop offset="1" class="akw4o1b4x"/></linearGradient><linearGradient id="iMbKi7Z" x1="10.498" x2="10.678" y1="22.242" y2="24.019" gradientUnits="userSpaceOnUse"><stop offset=".169" class="hp9pfe6dv"/><stop offset=".828" class="lt5fs243n"/></linearGradient><linearGradient id="i0ijaGd" x1="7.213" x2="8.993" y1="25.403" y2="25.267" gradientUnits="userSpaceOnUse"><stop class="rry-d5bab"/><stop offset="1" class="ila5y0vii"/></linearGradient><linearGradient id="iJvdcke" x1="14.724" x2="14.044" y1="4.664" y2="9.9" gradientUnits="userSpaceOnUse"><stop class="nsooqoy6p"/><stop offset="1" class="gus-yqtns"/></linearGradient><linearGradient id="ijc2p5c" x1="5.882" x2="5.878" y1="11.033" y2="11.469" gradientUnits="userSpaceOnUse"><stop class="gbzybnb0l"/><stop offset="1" class="ktnj45bbe"/></linearGradient><linearGradient id="iLKcMAE" x1="3.618" x2="3.615" y1="15.249" y2="15.663" gradientUnits="userSpaceOnUse"><stop class="gbzybnb0l"/><stop offset="1" class="ktnj45bbe"/></linearGradient><linearGradient id="iJta8Je" x1="6.253" x2="6.231" y1="19.73" y2="20.671" gradientUnits="userSpaceOnUse"><stop class="gbzybnb0l"/><stop offset="1" class="ktnj45bbe"/></linearGradient><linearGradient id="inAPbze" x1="8.945" x2="8.943" y1="24.267" y2="24.52" gradientUnits="userSpaceOnUse"><stop class="gbzybnb0l"/><stop offset="1" class="ktnj45bbe"/></linearGradient><linearGradient id="iCubaac" x1="15.487" x2="15.426" y1="27.1" y2="25.367" gradientUnits="userSpaceOnUse"><stop offset=".078" class="durnh5heb"/><stop offset="1" class="upexqebji"/></linearGradient><radialGradient id="iUahgyu" cx="0" cy="0" r="1" gradientTransform="rotate(170.048 14.177 8.417)scale(27.1022 28.0881)" gradientUnits="userSpaceOnUse"><stop class="aa_q_sbch"/><stop offset=".467" class="xauzwrm1k"/></radialGradient><radialGradient id="iEtZrTl" cx="0" cy="0" r="1" gradientTransform="matrix(22.05272 -5.34917 5.14119 21.19528 8.68 21.479)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="kpwscabck"/><stop offset=".943" class="scjo-lbpq"/></radialGradient><radialGradient id="iyM83se" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46752 .41117 -.28996 -5.97146 12.278 11.772)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="za7hpobbx"/><stop offset="1" class="odirvxbrg"/></radialGradient><radialGradient id="ialEVOe" cx="0" cy="0" r="1" gradientTransform="rotate(177.62 5.618 8.191)scale(9.9186 5.9904)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="za7hpobbx"/><stop offset="1" class="odirvxbrg"/></radialGradient><radialGradient id="i2Mxw7d" cx="0" cy="0" r="1" gradientTransform="matrix(.53986 -1.06819 1.89864 .95958 3.392 18.56)" gradientUnits="userSpaceOnUse"><stop class="i49xw_bqa"/><stop offset="1" class="bo3c2mbsg"/></radialGradient><radialGradient id="iv8u3Gd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.3793 .3742 -.2428 -5.43686 12.317 20.768)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="za7hpobbx"/><stop offset="1" class="odirvxbrg"/></radialGradient><radialGradient id="iVzNfob" cx="0" cy="0" r="1" gradientTransform="matrix(-8.3125 .47216 -1.021 -17.97483 15.386 24.453)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="p6774f_mu"/><stop offset="1" class="x-5_bcb3f"/></radialGradient><radialGradient id="iZc13mW" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -.0872 .07968 2.34138 15.053 14.046)" gradientUnits="userSpaceOnUse"><stop class="az9e5ebcm"/><stop offset="1" class="z9mirpbhu"/></radialGradient><radialGradient id="i9xcXVA" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 -.09153 .07422 2.45803 14.534 18.19)" gradientUnits="userSpaceOnUse"><stop class="az9e5ebcm"/><stop offset="1" class="z9mirpbhu"/></radialGradient><radialGradient id="isG61de" cx="0" cy="0" r="1" gradientTransform="matrix(2.75258 -.09773 .09316 2.62374 15.24 22.645)" gradientUnits="userSpaceOnUse"><stop class="az9e5ebcm"/><stop offset="1" class="z9mirpbhu"/></radialGradient><radialGradient id="iMdFjCR" cx="0" cy="0" r="1" gradientTransform="rotate(-141.886 9.442 2.72)scale(5.46598 2.15008)" gradientUnits="userSpaceOnUse"><stop class="ap0r-euxx"/><stop offset=".251" class="jgustt-xq"/><stop offset="1" class="biukvsb_s"/></radialGradient><radialGradient id="im5iG6c" cx="0" cy="0" r="1" gradientTransform="rotate(65.36 -1.024 19.681)scale(16.1661 27.6703)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="upexqebji"/><stop offset="1" class="durnh5heb"/></radialGradient><radialGradient id="iZECcnV" cx="0" cy="0" r="1" gradientTransform="rotate(115.574 9.372 9.572)scale(5.5163 13.1955)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="v-_zx_bok"/><stop offset="1" class="o68g-0tez"/></radialGradient><radialGradient id="i3M3eHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 .15625 -.34108 3.06974 11.886 6.609)" gradientUnits="userSpaceOnUse"><stop class="n-_82dbnn"/><stop offset="1" class="pac1_mzel"/></radialGradient><filter id="iGGLvte" width="28.465" height="24.039" x="1.922" y="3.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.584314 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7041"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.662745 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7041" result="effect2_innerShadow_20020_7041"/></filter><filter id="iPvBtOc" width="3.163" height="3.347" x="14.753" y="12.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".15"/></filter><filter id="i4Smksw" width="3.631" height="3.483" x="14.234" y="16.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".15"/></filter><filter id="izg5axe" width="3.353" height="3.679" x="14.941" y="20.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".15"/></filter><filter id="iY2fWxe" width="6.246" height="16.916" x="13.8" y="9.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".75"/></filter><filter id="idOjGcb" width="12.792" height="9.153" x="13.303" y="3.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".625"/></filter><filter id="ihDUvcb" width="14.446" height="4.713" x="4.118" y="8.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".75"/></filter><filter id="iYOBmMd" width="16.246" height="4.69" x="1.917" y="13.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".75"/></filter><filter id="iUr6ErN" width="13.313" height="4.25" x="4.449" y="17.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".75"/></filter><filter id="iIBzwHe" width="10.701" height="4.519" x="7.049" y="22.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7041" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-hand-light" /></template>
<style>
.aa_q_sbch {
  stop-color: var(--svg-color--ffd5bd, #FFD5BD);
}

.ae_ernsjy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m6.243 11.1l10.196.464");
}

.akw4o1b4x {
  stop-color: var(--svg-color--f3bcab, #F3BCAB);
  stop-opacity: 0;
}

.ap0r-euxx {
  stop-color: var(--svg-color--c87353, #C87353);
}

.az9e5ebcm {
  stop-color: var(--svg-color--e9ab92, #E9AB92);
}

.bfgq6bbgm {
  stop-color: var(--svg-color--edae97, #EDAE97);
}

.biukvsb_s {
  stop-color: var(--svg-color--d78d6f, #D78D6F);
  stop-opacity: 0;
}

.bo3c2mbsg {
  stop-color: var(--svg-color--c98789, #C98789);
  stop-opacity: 0;
}

.durnh5heb {
  stop-color: var(--svg-color--ba7f9a, #BA7F9A);
}

.ee2yicsdd {
  d: path("M17.565 19.632c-1.005-.887-2.44-1.085-3.03-1.072c1.537-.178 2.66-1.282 3.03-1.811z");
}

.em_5boqhn {
  stop-color: var(--svg-color--eab1a7, #EAB1A7);
  stop-opacity: 0;
}

.eurr65b3y {
  d: path("M4.396 13.736a2.406 2.406 0 0 0-.136 4.81l.944.026a2.406 2.406 0 0 0 1.4 4.393l1.37-.026a2.406 2.406 0 0 0 1.736 4.16l8.823-.336c1.33-.005 3.695-.149 5.76-1.003c3.267-1.208 5.595-4.341 5.595-8.016c0-3.715-2.38-6.877-5.702-8.055c-2.108-.888-4.283-2.361-5.205-2.986l-.06-.041l-2.82-2.099a2.536 2.536 0 0 0-3.054 4.05l1.424 1.089l-7.953-.344a2.385 2.385 0 0 0-1.378 4.399z");
}

.fetf0hbus {
  stroke: var(--svg-color--ecb6a2, #ECB6A2);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.448 11.387c-1.146 2-2.663 7.438.437 13.188");
}

.fsu03cbcn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m9.174 24.575l6.45-.269");
}

.ft5dv1b6b {
  fill: none;
}

.gbzybnb0l {
  stop-color: var(--svg-color--f8c7ae, #F8C7AE);
}

.gus-yqtns {
  stop-color: var(--svg-color--ffd8ba, #FFD8BA);
  stop-opacity: 0;
}

.hbgieofjc {
  stop-color: var(--svg-color--f0b9a7, #F0B9A7);
  stop-opacity: 0;
}

.hp9pfe6dv {
  stop-color: var(--svg-color--c2735c, #C2735C);
}

.i49xw_bqa {
  stop-color: var(--svg-color--c98789, #C98789);
}

.ihbj04bdr {
  stop-color: var(--svg-color--d39895, #D39895);
}

.ila5y0vii {
  stop-color: var(--svg-color--ce8b77, #CE8B77);
  stop-opacity: 0;
}

.j_sdomb5r {
  stop-color: var(--svg-color--f3bcab, #F3BCAB);
}

.jgustt-xq {
  stop-color: var(--svg-color--d78d6f, #D78D6F);
}

.kpwscabck {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
  stop-opacity: 0;
}

.ktnj45bbe {
  stop-color: var(--svg-color--f8c7ae, #F8C7AE);
  stop-opacity: 0;
}

.lt5fs243n {
  stop-color: var(--svg-color--d79079, #D79079);
  stop-opacity: 0;
}

.lx3zquz-s {
  stop-color: var(--svg-color--cf7952, #CF7952);
}

.m43x-n-zd {
  d: path("M17.993 24.185c-1.038-1.052-2.16-1.434-2.752-1.422c1.538-.177 2.383-1.127 2.752-1.657z");
}

.n-_82dbnn {
  stop-color: var(--svg-color--edb196, #EDB196);
}

.nsooqoy6p {
  stop-color: var(--svg-color--ffd8ba, #FFD8BA);
}

.o68g-0tez {
  stop-color: var(--svg-color--ffdbbc, #FFDBBC);
  stop-opacity: 0;
}

.odirvxbrg {
  stop-color: var(--svg-color--f0b69a, #F0B69A);
}

.p6774f_mu {
  stop-color: var(--svg-color--e9ad9a, #E9AD9A);
  stop-opacity: 0;
}

.pac1_mzel {
  stop-color: var(--svg-color--eab094, #EAB094);
  stop-opacity: 0;
}

.qjws5qxoo {
  d: path("m6.286 9.359l10.136.423v4.404l-11.288-.433a2.384 2.384 0 0 1 1.152-4.394");
}

.qk_wm3boh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m4.042 15.313l11.997.44");
}

.qpqbqtbbm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.574 19.875h9.062");
}

.rnkcqiywh {
  stop-color: var(--svg-color--e1ad90, #E1AD90);
  stop-opacity: 0;
}

.rry-d5bab {
  stop-color: var(--svg-color--ce8b77, #CE8B77);
}

.scjo-lbpq {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
}

.t2d1oablt {
  d: path("M17.616 15.42c-.836-.896-2.063-1.227-2.563-1.216c1.3-.15 2.25-1.084 2.563-1.532z");
}

.u21ufccuh {
  stroke-linecap: round;
  d: path("M15.053 5.486c1.48 1.398 5.87 4.074 9.292 5.653");
}

.u308zo_yo {
  stop-color: var(--svg-color--de9574, #DE9574);
  stop-opacity: 0;
}

.upexqebji {
  stop-color: var(--svg-color--cd939b, #CD939B);
  stop-opacity: 0;
}

.v-_zx_bok {
  stop-color: var(--svg-color--ffdbbc, #FFDBBC);
}

.x-5_bcb3f {
  stop-color: var(--svg-color--e9ad9a, #E9AD9A);
}

.xauzwrm1k {
  stop-color: var(--svg-color--f2bbab, #F2BBAB);
}

.xcl71mbby {
  d: path("m17.789 9.827l-4.994-5.025q-.13.13-.243.282a2.536 2.536 0 0 0 .495 3.53l1.424 1.088z");
}

.xdoag_q9p {
  d: path("M7.975 22.939a2.406 2.406 0 0 0 1.736 4.16l6.91-.27c0-1.343-.852-3.157-.852-4.08z");
}

.xoe87acmz {
  d: path("M1.92 16.063a2.406 2.406 0 0 1 2.472-2.337c4.003.112 8.021.29 12.03.436v4.398H5.198l-.941-.025a2.406 2.406 0 0 1-2.337-2.472");
}

.xv8ebljba {
  d: path("M5.204 18.572a2.406 2.406 0 0 0 1.4 4.393l9.814-.215v-4.178z");
}

.yegb75-ac {
  stop-color: var(--svg-color--e1ad90, #E1AD90);
}

.z9mirpbhu {
  stop-color: var(--svg-color--e9ab92, #E9AB92);
  stop-opacity: 0;
}

.za7hpobbx {
  stop-color: var(--svg-color--f0b69a, #F0B69A);
  stop-opacity: 0;
}

</style>
