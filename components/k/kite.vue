<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isGU6Yc)" class="atjk8mbde"><path stroke="url(#ifY4mbd)" class="jlzn4wowc"/><path stroke="url(#i03WSXc)" class="jlzn4wowc"/><path stroke="url(#iz40FSb)" class="jlzn4wowc"/><path stroke="url(#idvjEnb)" class="jlzn4wowc"/></g><path stroke="url(#ixFXu5b)" class="es40qyq_l"/><path stroke="url(#iJtfWOc)" class="es40qyq_l"/><path fill="url(#igr97Ne)" class="oe5ohbbmo"/><path fill="url(#ijqppad)" class="oe5ohbbmo"/><path fill="url(#iwRoukb)" class="ub65l3bon"/><path fill="url(#ifbSCIj)" class="ub65l3bon"/><path fill="url(#ie2izZd)" class="ub65l3bon"/><path fill="url(#iOQXQ9c)" class="qh295f64i"/><path fill="url(#i0GGUib)" class="qh295f64i"/><path fill="url(#iZJ4Gob)" class="qh295f64i"/><path fill="url(#i3RQhWE)" class="pn_e7hulh"/><path fill="url(#iRY71oc)" class="pn_e7hulh"/><g filter="url(#itT7zQB)"><path class="gfhc9xoby"/><path fill="url(#iMsnmBe)" class="kcwr78bzc"/><path fill="url(#ijx1mil)" class="kcwr78bzc"/></g><g filter="url(#ibR2YKo)"><path class="ahq0dc_di"/><path fill="url(#ig7Ucxc)" class="fbllngtjc"/><path fill="url(#iwU8QZc)" class="fbllngtjc"/></g><g filter="url(#iIbhnqc)"><path class="gmayp7ddi"/><path fill="url(#ieomRTd)" class="dybp7qb0f"/><path fill="url(#io3jwVO)" class="dybp7qb0f"/></g><defs><radialGradient id="i03WSXc" cx="0" cy="0" r="1" gradientTransform="matrix(.90056 1.9228 -1.42179 .6659 24.642 17.906)" gradientUnits="userSpaceOnUse"><stop class="w7oc1mb-b"/><stop offset="1" class="n4x4o6dvl"/></radialGradient><radialGradient id="iz40FSb" cx="0" cy="0" r="1" gradientTransform="matrix(.29207 2.23922 -1.29255 .1686 26.832 21.119)" gradientUnits="userSpaceOnUse"><stop class="eybvq-nrk"/><stop offset="1" class="u731jqc8t"/></radialGradient><radialGradient id="idvjEnb" cx="0" cy="0" r="1" gradientTransform="rotate(120.256 5.883 20.82)scale(2.0288 1.17109)" gradientUnits="userSpaceOnUse"><stop class="fjucdopoj"/><stop offset="1" class="asjehm8ym"/></radialGradient><radialGradient id="ixFXu5b" cx="0" cy="0" r="1" gradientTransform="matrix(2.43393 3.11544 -.75062 .58642 18.752 25.402)" gradientUnits="userSpaceOnUse"><stop class="hvk7n6-vh"/><stop offset="1" class="t_tsdwbqn"/></radialGradient><radialGradient id="iJtfWOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60848 .29207 -.40506 -.84389 28 11.407)" gradientUnits="userSpaceOnUse"><stop class="rpjzb6qqx"/><stop offset="1" class="gwfr4ipbg"/></radialGradient><radialGradient id="igr97Ne" cx="0" cy="0" r="1" gradientTransform="rotate(-163.448 5.545 4.66)scale(5.90998 13.8095)" gradientUnits="userSpaceOnUse"><stop class="ig-ul38gd"/><stop offset="1" class="gu-_vlwwj"/></radialGradient><radialGradient id="iwRoukb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56901 -7.63077 11.41196 -2.34648 11.498 10.496)" gradientUnits="userSpaceOnUse"><stop class="nj74078pn"/><stop offset="1" class="dftkitbnf"/></radialGradient><radialGradient id="iOQXQ9c" cx="0" cy="0" r="1" gradientTransform="rotate(135.556 2.96 10.45)scale(4.33438 14.8275)" gradientUnits="userSpaceOnUse"><stop class="doztywbat"/><stop offset="1" class="rizt28b5n"/></radialGradient><radialGradient id="i3RQhWE" cx="0" cy="0" r="1" gradientTransform="matrix(4.77091 17.79287 -9.75935 2.61684 13.123 7.294)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="govct_g1o"/><stop offset="1" class="v7n4cmb_s"/></radialGradient><radialGradient id="iMsnmBe" cx="0" cy="0" r="1" gradientTransform="rotate(174.651 14.53 13.424)scale(1.03404 1.68142)" gradientUnits="userSpaceOnUse"><stop class="pxc3wlb2z"/><stop offset="1" class="hop9z3b4a"/></radialGradient><radialGradient id="ijx1mil" cx="0" cy="0" r="1" gradientTransform="rotate(179.525 13.621 12.781)scale(1.15196 .72512)" gradientUnits="userSpaceOnUse"><stop class="pxc3wlb2z"/><stop offset="1" class="hop9z3b4a"/></radialGradient><radialGradient id="ig7Ucxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91148 .4883 -.79401 -1.48213 28.823 20.54)" gradientUnits="userSpaceOnUse"><stop class="k_kvw83qw"/><stop offset="1" class="ze7or7bsh"/></radialGradient><radialGradient id="iwU8QZc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05797 .45574 -.28688 -.66596 26.154 21.68)" gradientUnits="userSpaceOnUse"><stop class="ixbhubcer"/><stop offset="1" class="rwhn6kb0y"/></radialGradient><radialGradient id="ieomRTd" cx="0" cy="0" r="1" gradientTransform="rotate(151.783 11.152 11.765)scale(1.1325 1.4161)" gradientUnits="userSpaceOnUse"><stop class="j_k_xgbdl"/><stop offset="1" class="synkxp2oa"/></radialGradient><radialGradient id="io3jwVO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09527 .48678 -.33322 -.74976 23.924 18.417)" gradientUnits="userSpaceOnUse"><stop class="v3fkql-nb"/><stop offset="1" class="j9b-tzb5k"/></radialGradient><linearGradient id="ifY4mbd" x1="22.578" x2="27.734" y1="18.413" y2="29.434" gradientUnits="userSpaceOnUse"><stop class="vnho24nti"/><stop offset="1" class="k8_t12bse"/></linearGradient><linearGradient id="ijqppad" x1="2.459" x2="3.76" y1="12.511" y2="12.636" gradientUnits="userSpaceOnUse"><stop class="uki-6nbix"/><stop offset="1" class="lzkqc5gta"/></linearGradient><linearGradient id="ifbSCIj" x1="3.867" x2="7.504" y1="1.975" y2="5.29" gradientUnits="userSpaceOnUse"><stop class="rljw6acou"/><stop offset="1" class="dxksqzxge"/></linearGradient><linearGradient id="ie2izZd" x1="9.715" x2="9.43" y1="3.685" y2="4.47" gradientUnits="userSpaceOnUse"><stop class="rljw6acou"/><stop offset="1" class="dxksqzxge"/></linearGradient><linearGradient id="i0GGUib" x1="17.117" x2="13.896" y1="25.174" y2="20.736" gradientUnits="userSpaceOnUse"><stop class="oty3cha0r"/><stop offset="1" class="kor802bqj"/></linearGradient><linearGradient id="iZJ4Gob" x1="8.68" x2="8.991" y1="19.73" y2="19.272" gradientUnits="userSpaceOnUse"><stop class="jbu-xzvou"/><stop offset="1" class="w_oxyabcp"/></linearGradient><linearGradient id="iRY71oc" x1="17.6" x2="16.856" y1="15.452" y2="15.496" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cjvcs-rmg"/><stop offset="1" class="sop9gtkap"/></linearGradient><filter id="isGU6Yc" width="11.313" height="19.116" x="16.922" y="10.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.686275 0 0 0 0 0.85098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3322"/></filter><filter id="itT7zQB" width="5.089" height="3.359" x="25.364" y="23.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.160784 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3322"/></filter><filter id="ibR2YKo" width="5.533" height="4.657" x="23.937" y="19.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.478431 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3322"/></filter><filter id="iIbhnqc" width="5.436" height="4.902" x="21.828" y="15.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3322"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:kite" /></template>
<style>
.ahq0dc_di {
  fill: var(--svg-color--288fec, #288FEC);
  d: path("m24.708 23.355l-.733-1.783a.5.5 0 0 1 .474-.69l1.656.038a.5.5 0 0 0 .405-.192l.997-1.278a.5.5 0 0 1 .842.085l.818 1.943a.5.5 0 0 1-.491.72l-1.617-.203a.5.5 0 0 0-.43.181l-1.073 1.306a.5.5 0 0 1-.848-.127");
}

.asjehm8ym {
  stop-color: var(--svg-color--c3accd, #C3ACCD);
  stop-opacity: 0;
}

.atjk8mbde {
  stroke-linecap: round;
}

.cjvcs-rmg {
  stop-color: var(--svg-color--63d5fe, #63D5FE);
}

.dftkitbnf {
  stop-color: var(--svg-color--6ec03e, #6EC03E);
}

.doztywbat {
  stop-color: var(--svg-color--ffde54, #FFDE54);
}

.dxksqzxge {
  stop-color: var(--svg-color--4fa42e, #4FA42E);
  stop-opacity: 0;
}

.dybp7qb0f {
  d: path("m22.869 20.128l-.972-1.665a.5.5 0 0 1 .374-.748l1.645-.191a.5.5 0 0 0 .375-.247l.81-1.403a.5.5 0 0 1 .846-.032l1.079 1.812a.5.5 0 0 1-.387.781l-1.63.022a.5.5 0 0 0-.4.238l-.882 1.442a.5.5 0 0 1-.858-.009");
}

.es40qyq_l {
  stroke-linecap: round;
  d: path("M17.422 24.585c.76 2.145 3.795 6.781 8.266 3.968c3.625-2.28 1.7-6.622-.164-8.882c-.75-.886-2-2.899-1.375-4.82c.607-1.868 2.518-2.96 3.382-3.282");
}

.eybvq-nrk {
  stop-color: var(--svg-color--cac6d8, #CAC6D8);
}

.fbllngtjc {
  d: path("m24.708 23.355l-.733-1.783a.5.5 0 0 1 .474-.69l1.656.038a.5.5 0 0 0 .405-.192l.997-1.278a.5.5 0 0 1 .842.085l.818 1.943a.5.5 0 0 1-.491.72l-1.617-.203a.5.5 0 0 0-.43.181l-1.073 1.306a.5.5 0 0 1-.848-.127");
}

.fjucdopoj {
  stop-color: var(--svg-color--c3accd, #C3ACCD);
}

.ft5dv1b6b {
  fill: none;
}

.gfhc9xoby {
  fill: var(--svg-color--df2b6e, #DF2B6E);
  d: path("m25.365 26.432l.016-1.927a.5.5 0 0 1 .705-.452l1.51.677a.5.5 0 0 0 .45-.02l1.414-.79a.5.5 0 0 1 .743.405v2.108a.5.5 0 0 1-.733.473l-1.41-.814a.5.5 0 0 0-.467 0l-1.495.787a.5.5 0 0 1-.733-.447");
}

.gmayp7ddi {
  fill: var(--svg-color--e6ad42, #E6AD42);
  d: path("m22.869 20.128l-.972-1.665a.5.5 0 0 1 .374-.748l1.645-.191a.5.5 0 0 0 .375-.247l.81-1.403a.5.5 0 0 1 .846-.032l1.079 1.812a.5.5 0 0 1-.387.781l-1.63.022a.5.5 0 0 0-.4.238l-.882 1.442a.5.5 0 0 1-.858-.009");
}

.govct_g1o {
  stop-color: var(--svg-color--70faff, #70FAFF);
}

.gu-_vlwwj {
  stop-color: var(--svg-color--e7374d, #E7374D);
}

.gwfr4ipbg {
  stop-color: var(--svg-color--f9f4fe, #F9F4FE);
  stop-opacity: 0;
}

.hop9z3b4a {
  stop-color: var(--svg-color--fb6390, #FB6390);
  stop-opacity: 0;
}

.hvk7n6-vh {
  stop-color: var(--svg-color--eae3f4, #EAE3F4);
}

.ig-ul38gd {
  stop-color: var(--svg-color--ff4066, #FF4066);
}

.ixbhubcer {
  stop-color: var(--svg-color--55adfa, #55ADFA);
}

.j_k_xgbdl {
  stop-color: var(--svg-color--ffd469, #FFD469);
}

.j9b-tzb5k {
  stop-color: var(--svg-color--f1c15f, #F1C15F);
  stop-opacity: 0;
}

.jbu-xzvou {
  stop-color: var(--svg-color--feca8a, #FECA8A);
}

.jlzn4wowc {
  d: path("M17.422 24.585c.76 2.145 3.795 6.781 8.266 3.968c3.625-2.28 1.7-6.622-.164-8.882c-.75-.886-2-2.899-1.375-4.82c.607-1.868 2.518-2.96 3.382-3.282");
}

.k_kvw83qw {
  stop-color: var(--svg-color--5fbcff, #5FBCFF);
}

.k8_t12bse {
  stop-color: var(--svg-color--cdc0db, #CDC0DB);
}

.kcwr78bzc {
  d: path("m25.365 26.432l.016-1.927a.5.5 0 0 1 .705-.452l1.51.677a.5.5 0 0 0 .45-.02l1.414-.79a.5.5 0 0 1 .743.405v2.108a.5.5 0 0 1-.733.473l-1.41-.814a.5.5 0 0 0-.467 0l-1.495.787a.5.5 0 0 1-.733-.447");
}

.kor802bqj {
  stop-color: var(--svg-color--fba943, #FBA943);
  stop-opacity: 0;
}

.lzkqc5gta {
  stop-color: var(--svg-color--eb777b, #EB777B);
  stop-opacity: 0;
}

.n4x4o6dvl {
  stop-color: var(--svg-color--d2c9d5, #D2C9D5);
  stop-opacity: 0;
}

.nj74078pn {
  stop-color: var(--svg-color--97e05e, #97E05E);
}

.oe5ohbbmo {
  d: path("m4.042 2.457l-1.8 12.32q-.03.255.06.48l7.23-4.17l-5.21-9.03c-.15.08-.26.22-.28.4");
}

.oty3cha0r {
  stop-color: var(--svg-color--fba943, #FBA943);
}

.pn_e7hulh {
  d: path("m17.892 24.577l-.98-17.2a.94.94 0 0 0-.178-.464l-7.212 4.164l8.09 14.01c.18-.09.3-.28.28-.51");
}

.pxc3wlb2z {
  stop-color: var(--svg-color--fb6390, #FB6390);
}

.qh295f64i {
  d: path("M2.292 15.257c.07.15.18.28.33.38l14.41 9.44c.19.13.42.12.59.02l-8.09-14.01z");
}

.rizt28b5n {
  stop-color: var(--svg-color--fab644, #FAB644);
}

.rljw6acou {
  stop-color: var(--svg-color--4fa42e, #4FA42E);
}

.rpjzb6qqx {
  stop-color: var(--svg-color--f9f4fe, #F9F4FE);
}

.rwhn6kb0y {
  stop-color: var(--svg-color--55adfa, #55ADFA);
  stop-opacity: 0;
}

.sop9gtkap {
  stop-color: var(--svg-color--63d5fe, #63D5FE);
  stop-opacity: 0;
}

.synkxp2oa {
  stop-color: var(--svg-color--ffd469, #FFD469);
  stop-opacity: 0;
}

.t_tsdwbqn {
  stop-color: var(--svg-color--eae3f4, #EAE3F4);
  stop-opacity: 0;
}

.u731jqc8t {
  stop-color: var(--svg-color--cac6d8, #CAC6D8);
  stop-opacity: 0;
}

.ub65l3bon {
  d: path("m16.362 6.617l-11.57-4.6a.53.53 0 0 0-.49.04l5.21 9.03l7.23-4.17a.76.76 0 0 0-.38-.3");
}

.uki-6nbix {
  stop-color: var(--svg-color--eb777b, #EB777B);
}

.v3fkql-nb {
  stop-color: var(--svg-color--f1c15f, #F1C15F);
}

.v7n4cmb_s {
  stop-color: var(--svg-color--41c6ff, #41C6FF);
}

.vnho24nti {
  stop-color: var(--svg-color--e2dced, #E2DCED);
}

.w_oxyabcp {
  stop-color: var(--svg-color--feca8a, #FECA8A);
  stop-opacity: 0;
}

.w7oc1mb-b {
  stop-color: var(--svg-color--d2c9d5, #D2C9D5);
}

.ze7or7bsh {
  stop-color: var(--svg-color--5fbcff, #5FBCFF);
  stop-opacity: 0;
}

</style>
