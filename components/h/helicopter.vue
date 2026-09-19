<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVjipfd)"><path fill="url(#ihYbACe)" class="n7u_mhbca"/></g><path fill="url(#ilk4C6b)" class="jntqa42un"/><path fill="url(#iJEdlEe)" class="jntqa42un"/><g filter="url(#ioA7Epd)"><path stroke="url(#iCW7iLc)" class="rval_szed"/></g><path fill="url(#ilYZkOb)" class="c9v1glfvi"/><path fill="url(#iFwFJlS)" class="jjezepbxw"/><path class="whghi6bxo"/><path fill="url(#iE95TVd)" class="w1_1ci94b"/><path fill="url(#iaWszGq)" class="w1_1ci94b"/><path fill="url(#iVSLzdd)" class="w1_1ci94b"/><path class="ayolaotkk"/><path fill="url(#i9yg7zb)" class="wnfqtikki"/><g filter="url(#iBJ8DSc)"><path fill="url(#iAeoZAd)" clip-rule="evenodd" class="g6gl45bgt"/></g><path fill="url(#i9MUfQE)" class="lflkytjkk"/><path fill="url(#i4kM7Ob)" class="lflkytjkk"/><path fill="url(#ihLydxb)" class="lflkytjkk"/><path fill="url(#irMhcpe)" class="g3-9wrixw"/><path class="q8-0_6bbt"/><path fill="url(#i3K1gpb)" class="bfkjg84ul"/><path fill="url(#iq4Cb9d)" class="bfkjg84ul"/><g filter="url(#iv2OyDD)"><path class="fvlfjjmol"/></g><path fill="url(#iCYQzOd)" class="eou9oszzi"/><path fill="url(#ilL3tZc)" class="lnp0pdbrj"/><path fill="url(#iMaoV6Q)" class="lnp0pdbrj"/><defs><linearGradient id="ihYbACe" x1="2.625" x2="24" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="b4ertxx5k"/><stop offset="1" class="b6hix1b_u"/></linearGradient><linearGradient id="ilk4C6b" x1="7" x2="8" y1="25.777" y2="25.777" gradientUnits="userSpaceOnUse"><stop class="lfhkz4bje"/><stop offset="1" class="tyqp83bmo"/></linearGradient><linearGradient id="iJEdlEe" x1="7.894" x2="7.538" y1="24.829" y2="25.702" gradientUnits="userSpaceOnUse"><stop class="p8b7rfzoh"/><stop offset="1" class="f2aylob3h"/></linearGradient><linearGradient id="iCW7iLc" x1="23.328" x2="1.533" y1="28.86" y2="28.86" gradientUnits="userSpaceOnUse"><stop class="l30ql_rbo"/><stop offset="1" class="q0bmoyq1a"/></linearGradient><linearGradient id="ilYZkOb" x1="16.347" x2="16.914" y1="26.144" y2="25.565" gradientUnits="userSpaceOnUse"><stop class="ltjpbp_sq"/><stop offset="1" class="n9zkjyb1g"/></linearGradient><linearGradient id="iFwFJlS" x1="11.998" x2="12.998" y1="5.493" y2="5.493" gradientUnits="userSpaceOnUse"><stop class="r18zzuj7y"/><stop offset="1" class="lja0hcb6i"/></linearGradient><linearGradient id="iE95TVd" x1="12.201" x2="11.755" y1="7.99" y2="7.99" gradientUnits="userSpaceOnUse"><stop class="mou5nwb3m"/><stop offset="1" class="cyzy7mbim"/></linearGradient><linearGradient id="iaWszGq" x1="8.469" x2="8.469" y1="8.99" y2="8.646" gradientUnits="userSpaceOnUse"><stop class="doj4c69ys"/><stop offset="1" class="p39r7ibyz"/></linearGradient><linearGradient id="i9yg7zb" x1="19.076" x2="19.076" y1="8.99" y2="8.646" gradientUnits="userSpaceOnUse"><stop class="doj4c69ys"/><stop offset="1" class="p39r7ibyz"/></linearGradient><linearGradient id="iAeoZAd" x1="28.373" x2="16.063" y1="12.993" y2="12.993" gradientUnits="userSpaceOnUse"><stop class="ieaa7147v"/><stop offset="1" class="i89a6bolu"/></linearGradient><linearGradient id="irMhcpe" x1="11.859" x2="12.781" y1="7.99" y2="7.99" gradientUnits="userSpaceOnUse"><stop class="mou5nwb3m"/><stop offset="1" class="ec8y22lkj"/></linearGradient><linearGradient id="i3K1gpb" x1="10.875" x2="6" y1="16.552" y2="20.052" gradientUnits="userSpaceOnUse"><stop offset=".48" class="saztue40u"/><stop offset="1" class="u5mvl3h1i"/></linearGradient><linearGradient id="ilL3tZc" x1="11" x2="14.031" y1="10.646" y2="10.646" gradientUnits="userSpaceOnUse"><stop class="uajf6cgds"/><stop offset=".17" class="t17owibpu"/><stop offset=".827" class="t17owibpu"/><stop offset="1" class="h8phjtbsl"/></linearGradient><linearGradient id="iMaoV6Q" x1="12.516" x2="12.516" y1="9.943" y2="10.287" gradientUnits="userSpaceOnUse"><stop class="k0qjlwbrl"/><stop offset="1" class="kq6c2hb7w"/></linearGradient><radialGradient id="iVSLzdd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 0 0 -3.625 11.375 7.99)" gradientUnits="userSpaceOnUse"><stop offset=".938" class="zqy__yhsi"/><stop offset="1" class="c6307jh5o"/></radialGradient><radialGradient id="i9MUfQE" cx="0" cy="0" r="1" gradientTransform="rotate(147.362 5.771 10.302)scale(13.211 16.9856)" gradientUnits="userSpaceOnUse"><stop class="ys0fcokch"/><stop offset="1" class="a_d8j96tk"/></radialGradient><radialGradient id="i4kM7Ob" cx="0" cy="0" r="1" gradientTransform="matrix(14.12495 -10.31248 13.25895 18.16071 4.625 24.552)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="wf2vl4bhc"/><stop offset="1" class="s-j41nbsr"/></radialGradient><radialGradient id="ihLydxb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.99996 6.18758 -7.95544 -16.7142 15.688 16.177)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="vhf7a67dn"/><stop offset=".971" class="exdv5pf6p"/></radialGradient><radialGradient id="iq4Cb9d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.81248 6.37502 -1.13692 -.85826 6.125 10.303)" gradientUnits="userSpaceOnUse"><stop class="zgaxivbum"/><stop offset="1" class="tucymlblw"/></radialGradient><radialGradient id="iCYQzOd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.6094 0 0 -29.0865 17.813 21.302)" gradientUnits="userSpaceOnUse"><stop class="j08okpbqn"/><stop offset=".802" class="ibbgf0vob"/><stop offset=".962" class="y599re_2f"/></radialGradient><filter id="iVjipfd" width="22.5" height="2.25" x="2" y="27.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.235294 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12833"/></filter><filter id="ioA7Epd" width="20.493" height="1.05" x="2.989" y="28.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12833" stdDeviation=".2"/></filter><filter id="iBJ8DSc" width="20.6" height="12.2" x="8.7" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.356863 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12833"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.356863 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12833" result="effect2_innerShadow_18_12833"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.631373 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_12833" result="effect3_innerShadow_18_12833"/></filter><filter id="iv2OyDD" width="4.845" height="5.514" x="9.155" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.647059 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12833"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:helicopter" /></template>
<style>
.a_d8j96tk {
  stop-color: var(--svg-color--da4b77, #DA4B77);
}

.ayolaotkk {
  fill: var(--svg-color--d7c8d3, #D7C8D3);
  d: path("M13 6.99h9c.55 0 1 .45 1 1s-.45 1-1 1h-9z");
}

.b4ertxx5k {
  stop-color: var(--svg-color--ee488d, #EE488D);
}

.b6hix1b_u {
  stop-color: var(--svg-color--fe7e4c, #FE7E4C);
}

.bfkjg84ul {
  d: path("M1.93 17.99c0 .34.02.67.07 1h8.46c.66 0 1.06-.73.7-1.29L7 11.28c-2.89.86-5.07 3.54-5.07 6.71");
}

.c6307jh5o {
  stop-color: var(--svg-color--b8afc0, #B8AFC0);
}

.c9v1glfvi {
  d: path("m14 23.7l.71-.71l4.923 5.008c-.219.265-1.063.215-1.334.008h-.002l-.008-.008z");
}

.cyzy7mbim {
  stop-color: var(--svg-color--a2919d, #A2919D);
  stop-opacity: 0;
}

.doj4c69ys {
  stop-color: var(--svg-color--cdbebe, #CDBEBE);
}

.ec8y22lkj {
  stop-color: var(--svg-color--f5ebf2, #F5EBF2);
}

.eou9oszzi {
  d: path("M2.607 20.99c.36.75.845 1.43 1.425 2H17.89a6.8 6.8 0 0 0 1.438-2z");
}

.exdv5pf6p {
  stop-color: var(--svg-color--a63c67, #A63C67);
}

.f2aylob3h {
  stop-color: var(--svg-color--ac75a0, #AC75A0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvlfjjmol {
  fill: var(--svg-color--51ceff, #51CEFF);
  d: path("m10.29 13.28l2.18 3.35c.45.7 1.53.38 1.53-.45v-3.35c0-.46-.37-.83-.83-.83h-2.18c-.66-.01-1.06.73-.7 1.28");
}

.g3-9wrixw {
  d: path("M13 5.99h-1v4h1z");
}

.g6gl45bgt {
  fill-rule: evenodd;
  d: path("M27.39 7.27c.18-.18.42-.28.67-.28c.52 0 .94.43.94.94v4.56c0 .83-.67 1.5-1.5 1.5H23l-5 5v-5h-7.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5h13.17zm.61 4.72a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.h8phjtbsl {
  stop-color: var(--svg-color--fee45d, #FEE45D);
}

.i89a6bolu {
  stop-color: var(--svg-color--ff8346, #FF8346);
}

.ibbgf0vob {
  stop-color: var(--svg-color--ee9c48, #EE9C48);
}

.ieaa7147v {
  stop-color: var(--svg-color--fe834b, #FE834B);
}

.j08okpbqn {
  stop-color: var(--svg-color--ffbd4d, #FFBD4D);
}

.jjezepbxw {
  d: path("M13 5.49c0-.28-.22-.5-.5-.5s-.5.22-.5.5v.5h1z");
}

.jntqa42un {
  d: path("M7 23.66h1v4.343c-.398.327-.836.136-.994 0H7z");
}

.k0qjlwbrl {
  stop-color: var(--svg-color--fdd244, #FDD244);
}

.kq6c2hb7w {
  stop-color: var(--svg-color--fdd244, #FDD244);
  stop-opacity: 0;
}

.l30ql_rbo {
  stop-color: var(--svg-color--ff9e5b, #FF9E5B);
}

.lfhkz4bje {
  stop-color: var(--svg-color--a1899d, #A1899D);
}

.lflkytjkk {
  d: path("M12.973 10.99H8.957c-.703 0-1.325.1-1.957.29l-5 7.71c.492 3.39 3.413 6 6.957 6h4.016c3.885 0 7.027-3.13 7.027-7c0-3.86-3.152-7-7.027-7");
}

.lja0hcb6i {
  stop-color: var(--svg-color--ff9367, #FF9367);
}

.lnp0pdbrj {
  d: path("M11 10.443a.5.5 0 0 1 .5-.5h2.031a.5.5 0 0 1 .5.5v.547H11z");
}

.ltjpbp_sq {
  stop-color: var(--svg-color--b686a7, #B686A7);
}

.mou5nwb3m {
  stop-color: var(--svg-color--a2919d, #A2919D);
}

.n7u_mhbca {
  d: path("M2 29c0-.55.45-1 1-1h20c.55 0 1 .45 1 1s-.45 1-1 1H3c-.55 0-1-.44-1-1");
}

.n9zkjyb1g {
  stop-color: var(--svg-color--f7ebf3, #F7EBF3);
}

.p39r7ibyz {
  stop-color: var(--svg-color--cdbebe, #CDBEBE);
  stop-opacity: 0;
}

.p8b7rfzoh {
  stop-color: var(--svg-color--ac75a0, #AC75A0);
}

.q0bmoyq1a {
  stop-color: var(--svg-color--f65487, #F65487);
}

.q8-0_6bbt {
  fill: var(--svg-color--4ecaef, #4ECAEF);
  d: path("M1.93 17.99c0 .34.02.67.07 1h8.46c.66 0 1.06-.73.7-1.29L7 11.28c-2.89.86-5.07 3.54-5.07 6.71");
}

.r18zzuj7y {
  stop-color: var(--svg-color--ba6f5d, #BA6F5D);
}

.rval_szed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.514 28.86h19.443");
}

.s-j41nbsr {
  stop-color: var(--svg-color--ffa260, #FFA260);
}

.saztue40u {
  stop-color: var(--svg-color--32a2ce, #32A2CE);
}

.t17owibpu {
  stop-color: var(--svg-color--ffc748, #FFC748);
}

.tucymlblw {
  stop-color: var(--svg-color--51caf2, #51CAF2);
  stop-opacity: 0;
}

.tyqp83bmo {
  stop-color: var(--svg-color--e3cee2, #E3CEE2);
}

.u5mvl3h1i {
  stop-color: var(--svg-color--32a2ce, #32A2CE);
  stop-opacity: 0;
}

.uajf6cgds {
  stop-color: var(--svg-color--c98c34, #C98C34);
}

.vhf7a67dn {
  stop-color: var(--svg-color--a63c67, #A63C67);
  stop-opacity: 0;
}

.w1_1ci94b {
  d: path("M12 8.99H4c-.55 0-1-.45-1-1s.45-1 1-1h8z");
}

.wf2vl4bhc {
  stop-color: var(--svg-color--ffa260, #FFA260);
  stop-opacity: 0;
}

.whghi6bxo {
  fill: var(--svg-color--d7c8d3, #D7C8D3);
  d: path("M12 8.99H4c-.55 0-1-.45-1-1s.45-1 1-1h8z");
}

.wnfqtikki {
  d: path("M13 6.99h9c.55 0 1 .45 1 1s-.45 1-1 1h-9z");
}

.y599re_2f {
  stop-color: var(--svg-color--b8753b, #B8753B);
}

.ys0fcokch {
  stop-color: var(--svg-color--ff8e53, #FF8E53);
}

.zgaxivbum {
  stop-color: var(--svg-color--51caf2, #51CAF2);
}

.zqy__yhsi {
  stop-color: var(--svg-color--b8afc0, #B8AFC0);
  stop-opacity: 0;
}

</style>
