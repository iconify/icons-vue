<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5rE8Pc)"><path fill="url(#ic1KTbd)" class="ujydyib8d"/><path fill="url(#iNwGEAd)" class="ujydyib8d"/><path fill="url(#iNk15Oc)" class="ujydyib8d"/><path fill="url(#iGTp4vZ)" class="ujydyib8d"/></g><g filter="url(#i4E2Wyb)"><path fill="url(#i6N4Ixd)" class="ueos9yy2y"/></g><rect fill="url(#i9pjy2B)" class="zys7f72ey"/><rect fill="url(#i4Awhud)" class="qxrjxujji"/><path fill="url(#ivO79Tc)" class="tx2om3yfw"/><path fill="url(#iMeYzfd)" class="tx2om3yfw"/><path fill="url(#i49IYxb)" class="tx2om3yfw"/><path fill="url(#iy75jcd)" class="tx2om3yfw"/><g filter="url(#iIfADNd)"><rect fill="url(#ikApamd)" class="zgqyibz6l"/><rect fill="url(#iJPIbYb)" class="zgqyibz6l"/><rect fill="url(#iQv4lqd)" class="zgqyibz6l"/></g><rect fill="url(#iwaNGEe)" class="ap-god9dl"/><rect fill="url(#iCEVuid)" class="ap-god9dl"/><rect fill="url(#iFEBOge)" class="ap-god9dl"/><g filter="url(#iUz8SXC)"><rect class="n9s4v3bnu"/></g><g filter="url(#iCL2hZc)"><rect class="i1s3ywnee"/></g><rect fill="url(#iyyD0Cc)" class="n9fokxb3a"/><rect fill="url(#iNEccib)" class="n9fokxb3a"/><rect fill="url(#iiBonvc)" class="n9fokxb3a"/><defs><radialGradient id="iNwGEAd" cx="0" cy="0" r="1" gradientTransform="matrix(8.56555 0 0 4.57895 7.71 11.043)" gradientUnits="userSpaceOnUse"><stop class="clu0dlb4s"/><stop offset="1" class="q_h3xcy8u"/></radialGradient><radialGradient id="iGTp4vZ" cx="0" cy="0" r="1" gradientTransform="matrix(-6.63519 0 0 -10.3302 16.544 19.184)" gradientUnits="userSpaceOnUse"><stop class="rp70k1kyf"/><stop offset="1" class="urxl1cm8v"/></radialGradient><radialGradient id="i6N4Ixd" cx="0" cy="0" r="1" gradientTransform="matrix(4.68782 -7.19713 5.98956 3.90127 15.573 24.596)" gradientUnits="userSpaceOnUse"><stop class="ylvb6uzsv"/><stop offset="1" class="jchhhib4v"/></radialGradient><radialGradient id="i9pjy2B" cx="0" cy="0" r="1" gradientTransform="matrix(-10.14807 -.05048 .00666 -1.33965 28.08 26.41)" gradientUnits="userSpaceOnUse"><stop class="ntknf1bqz"/><stop offset="1" class="uf2y76k7n"/></radialGradient><radialGradient id="i4Awhud" cx="0" cy="0" r="1" gradientTransform="matrix(4.4375 0 0 4.60372 29.625 27.045)" gradientUnits="userSpaceOnUse"><stop class="ntknf1bqz"/><stop offset=".885" class="uf2y76k7n"/></radialGradient><radialGradient id="ivO79Tc" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1.8125 -5.24074 5.42145 12.967 6.38)" gradientUnits="userSpaceOnUse"><stop class="kq-vnjbzs"/><stop offset=".858" class="vs96a1y3z"/></radialGradient><radialGradient id="iMeYzfd" cx="0" cy="0" r="1" gradientTransform="rotate(142.344 8.33 7.288)scale(5.01297 1.89469)" gradientUnits="userSpaceOnUse"><stop class="n6wy1ebat"/><stop offset="1" class="fjgge1b8v"/></radialGradient><radialGradient id="i49IYxb" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 8.932 6.449)scale(2.98951 1.97665)" gradientUnits="userSpaceOnUse"><stop class="h-tuxy96a"/><stop offset="1" class="fn_d7wy9u"/></radialGradient><radialGradient id="iy75jcd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53125 0 0 -1.78125 17.752 10.813)" gradientUnits="userSpaceOnUse"><stop class="fnqutn4nq"/><stop offset="1" class="djenvokyv"/></radialGradient><radialGradient id="ikApamd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.84274 23.662 11.85)" gradientUnits="userSpaceOnUse"><stop class="nk--e8xuh"/><stop offset="1" class="bk2yrobhf"/></radialGradient><radialGradient id="iQv4lqd" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -.25 .16715 3.48919 17.125 15.031)" gradientUnits="userSpaceOnUse"><stop class="o93aulutx"/><stop offset="1" class="noufvt53v"/></radialGradient><radialGradient id="iwaNGEe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.20272 22.19 21.615)" gradientUnits="userSpaceOnUse"><stop class="m_l87kbdg"/><stop offset="1" class="sry72opfr"/></radialGradient><radialGradient id="iFEBOge" cx="0" cy="0" r="1" gradientTransform="matrix(7.33922 0 0 2.25494 18.534 25.193)" gradientUnits="userSpaceOnUse"><stop class="ezzii7vwe"/><stop offset="1" class="g4vc5849i"/></radialGradient><radialGradient id="iyyD0Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.11937 22.19 16.719)" gradientUnits="userSpaceOnUse"><stop class="bs5n2vwdl"/><stop offset="1" class="sp9byi8ur"/></radialGradient><radialGradient id="iiBonvc" cx="0" cy="0" r="1" gradientTransform="matrix(6.46207 0 0 3.4824 17.179 20.162)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="i2tcfgpxk"/><stop offset="1" class="h51r-_bjl"/></radialGradient><linearGradient id="ic1KTbd" x1="14.36" x2="30.649" y1="31.333" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="atow_rb2z"/><stop offset="1" class="uspel7bnu"/></linearGradient><linearGradient id="iNk15Oc" x1="18.438" x2="18.438" y1="32.938" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="iqkzbvbpi"/><stop offset="1" class="o-ltl1bjv"/></linearGradient><linearGradient id="iJPIbYb" x1="14.772" x2="19.102" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="r4qb_1jyq"/><stop offset="1" class="rahkz9bgn"/></linearGradient><linearGradient id="iCEVuid" x1="14.772" x2="19.102" y1="23.107" y2="23.107" gradientUnits="userSpaceOnUse"><stop class="i53o-ibqr"/><stop offset="1" class="ez-xrabvn"/></linearGradient><linearGradient id="iNEccib" x1="15.376" x2="19.102" y1="18.155" y2="18.155" gradientUnits="userSpaceOnUse"><stop class="wb0wj9b_z"/><stop offset="1" class="goxuy69oo"/></linearGradient><filter id="i5rE8Pc" width="27.371" height="28.636" x="2.689" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.341176 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2645"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2645" result="effect2_innerShadow_20020_2645"/></filter><filter id="i4E2Wyb" width="11.25" height="16.974" x="13.037" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2645" stdDeviation=".75"/></filter><filter id="iIfADNd" width="10.338" height="6.078" x="15.376" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.403922 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2645"/></filter><filter id="iUz8SXC" width="8.315" height="2.188" x="16.308" y="13.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2645" stdDeviation=".375"/></filter><filter id="iCL2hZc" width="8.315" height="2.188" x="16.308" y="19.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2645" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:call-me-hand-medium" /></template>
<style>
.ap-god9dl {
  width: 10.088px;
  height: 5.781px;
  x: 15.376px;
  y: 19.412px;
  rx: 2.891px;
}

.atow_rb2z {
  stop-color: var(--svg-color--a57671, #A57671);
}

.bk2yrobhf {
  stop-color: var(--svg-color--b08c70, #B08C70);
}

.bs5n2vwdl {
  stop-color: var(--svg-color--cba28c, #CBA28C);
}

.clu0dlb4s {
  stop-color: var(--svg-color--a9826d, #A9826D);
}

.djenvokyv {
  stop-color: var(--svg-color--ba967d, #BA967D);
  stop-opacity: 0;
}

.ez-xrabvn {
  stop-color: var(--svg-color--835d53, #835D53);
  stop-opacity: 0;
}

.ezzii7vwe {
  stop-color: var(--svg-color--935378, #935378);
}

.fjgge1b8v {
  stop-color: var(--svg-color--a78168, #A78168);
  stop-opacity: 0;
}

.fn_d7wy9u {
  stop-color: var(--svg-color--cda68b, #CDA68B);
  stop-opacity: 0;
}

.fnqutn4nq {
  stop-color: var(--svg-color--ba967d, #BA967D);
}

.ft5dv1b6b {
  fill: none;
}

.g4vc5849i {
  stop-color: var(--svg-color--935378, #935378);
  stop-opacity: 0;
}

.goxuy69oo {
  stop-color: var(--svg-color--846050, #846050);
  stop-opacity: 0;
}

.h-tuxy96a {
  stop-color: var(--svg-color--cda68b, #CDA68B);
}

.h51r-_bjl {
  stop-color: var(--svg-color--955f6f, #955F6F);
  stop-opacity: 0;
}

.i1s3ywnee {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 19.818px;
  fill: var(--svg-color--634130, #634130);
  rx: 0.344px;
}

.i2tcfgpxk {
  stop-color: var(--svg-color--955f6f, #955F6F);
}

.i53o-ibqr {
  stop-color: var(--svg-color--835d53, #835D53);
}

.iqkzbvbpi {
  stop-color: var(--svg-color--995782, #995782);
}

.jchhhib4v {
  stop-color: var(--svg-color--62413c, #62413C);
}

.kq-vnjbzs {
  stop-color: var(--svg-color--8d705e, #8D705E);
}

.m_l87kbdg {
  stop-color: var(--svg-color--d0a690, #D0A690);
}

.n6wy1ebat {
  stop-color: var(--svg-color--a78168, #A78168);
}

.n9fokxb3a {
  width: 10.088px;
  height: 5.563px;
  x: 15.376px;
  y: 14.599px;
  rx: 2.781px;
}

.n9s4v3bnu {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 14.395px;
  fill: var(--svg-color--634130, #634130);
  rx: 0.344px;
}

.nk--e8xuh {
  stop-color: var(--svg-color--cea58e, #CEA58E);
}

.noufvt53v {
  stop-color: var(--svg-color--976969, #976969);
  stop-opacity: 0;
}

.ntknf1bqz {
  stop-color: var(--svg-color--cea490, #CEA490);
}

.o-ltl1bjv {
  stop-color: var(--svg-color--995782, #995782);
  stop-opacity: 0;
}

.o93aulutx {
  stop-color: var(--svg-color--976969, #976969);
}

.q_h3xcy8u {
  stop-color: var(--svg-color--a9826d, #A9826D);
  stop-opacity: 0;
}

.qxrjxujji {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  rx: 2.898px;
}

.r4qb_1jyq {
  stop-color: var(--svg-color--896955, #896955);
}

.rahkz9bgn {
  stop-color: var(--svg-color--896955, #896955);
  stop-opacity: 0;
}

.rp70k1kyf {
  stop-color: var(--svg-color--8d6962, #8D6962);
}

.sp9byi8ur {
  stop-color: var(--svg-color--a68168, #A68168);
}

.sry72opfr {
  stop-color: var(--svg-color--ab8270, #AB8270);
}

.tx2om3yfw {
  d: path("m17.97 10.425l-.008-.005c.597-.853 1.968-2.82 2.508-3.703c.79-1.29.679-3.1-.581-4.073a2.76 2.76 0 0 0-1.69-.587a3 3 0 0 0-1.566.46c-.36.222-.7.528-1 .918c-2.388 3.7-5.187 5.899-6.611 6.504l-.035.02q-.196.087-.389.182c-.155.108-.203.22-.236.559c-.133 1.348 1.235 3.249 2.294 4.058c1.271.972 3.09.73 4.063-.542l2.967-3.39z");
}

.ueos9yy2y {
  d: path("M14.537 14.715c0-1.439 1.07-2.606 2.388-2.606H20.4c1.319 0 2.388 1.167 2.388 2.606c0 .942-.457 1.767-1.143 2.224c.683.43 1.143 1.235 1.143 2.157c0 .934-.471 1.747-1.168 2.173c.699.449 1.168 1.28 1.168 2.229c0 .75-.145 1.874-1.338 2.15l-4.543.435c-1.308 0-2.369-1.157-2.369-2.585c0-.95.47-1.78 1.169-2.23c-.697-.425-1.169-1.238-1.169-2.172c0-.922.46-1.727 1.143-2.157c-.685-.457-1.143-1.282-1.143-2.224");
}

.uf2y76k7n {
  stop-color: var(--svg-color--cea490, #CEA490);
  stop-opacity: 0;
}

.ujydyib8d {
  d: path("M17.962 10.42c3.188 1.826 5.35 5.346 5.35 9.273c0 1.603-.361 3.112-1.004 4.453h4.13c1.587 0 2.873 1.298 2.873 2.899s-1.286 2.898-2.872 2.898H14.084q-.33 0-.634-.008q-.21.008-.419.008c-6.874 0-10.342-4.551-10.342-10.281c0-4.284 2.608-8.067 6.298-9.703l.035-.02c1.424-.605 4.223-2.804 6.61-6.504c1.192-1.547 2.997-1.764 4.257-.791c1.26.972 1.371 2.784.581 4.073c-.54.883-1.911 2.85-2.508 3.703");
}

.urxl1cm8v {
  stop-color: var(--svg-color--8d6962, #8D6962);
  stop-opacity: 0;
}

.uspel7bnu {
  stop-color: var(--svg-color--a68169, #A68169);
}

.vs96a1y3z {
  stop-color: var(--svg-color--8d705e, #8D705E);
  stop-opacity: 0;
}

.wb0wj9b_z {
  stop-color: var(--svg-color--846050, #846050);
}

.ylvb6uzsv {
  stop-color: var(--svg-color--814d5f, #814D5F);
}

.zgqyibz6l {
  width: 10.088px;
  height: 5.828px;
  x: 15.376px;
  y: 9.568px;
  rx: 2.914px;
}

.zys7f72ey {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 2.898px;
}

</style>
