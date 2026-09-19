<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iziCT7p)"><path fill="url(#i95Gsld)" class="cckdscc8f"/></g><path fill="url(#icO1bbd)" class="cckdscc8f"/><path fill="url(#i7hvcic)" class="cckdscc8f"/><g filter="url(#iXkh7ie)"><path class="a8nkx9b4n"/></g><g filter="url(#iTSr66b)"><path fill="url(#iNQQayd)" class="rip9tndip"/></g><path fill="url(#iE9anhd)" class="rip9tndip"/><path fill="url(#izBA4Qc)" class="rip9tndip"/><path fill="url(#iGxPIkc)" class="rip9tndip"/><path fill="url(#iWC6BBb)" class="rip9tndip"/><path fill="url(#iJWHmGf)" class="uf7s8zb3z"/><path fill="url(#iMmZAYb)" class="uf7s8zb3z"/><path fill="url(#ibIEX3b)" class="akrcu9ndd"/><path fill="url(#iiquC1c)" class="v5ow9wbca"/><path fill="url(#iY9me8c)" class="v5ow9wbca"/><path fill="url(#i7uxOnc)" class="v5ow9wbca"/><path fill="url(#iANeIvb)" class="slzuxybpu"/><g filter="url(#ikI0vDc)"><path class="ns4bl8bae"/></g><path fill="url(#i1zeDdc)" class="riemxlaxy"/><path fill="url(#iayH9Xd)" class="riemxlaxy"/><path fill="url(#iFgV6rb)" class="pxmjsb7vg"/><path fill="url(#ihmBiQe)" class="pxmjsb7vg"/><path fill="url(#iW01vnd)" class="n_swb0bro"/><path fill="url(#iT4eAic)" class="n_swb0bro"/><g filter="url(#iv4Wd8c)"><path fill="url(#iQ7fNxc)" class="jd75nrbwq"/><path fill="url(#iOkntAb)" class="jd75nrbwq"/><path fill="url(#i1dqKRc)" class="jd75nrbwq"/></g><path class="xov3gc4-c"/><path class="uehcfgbmf"/><path class="vbqp1pbxh"/><path class="qhijf8bcg"/><path class="qtsxuno4v"/><path class="w5_orxzhg"/><path class="ho6_uubce"/><path class="w9060wb-g"/><path class="jtadfqbjn"/><path class="fbtn3b-6i"/><path class="m63mifbku"/><path class="v7ik8kbhq"/><path class="s9veomitu"/><defs><linearGradient id="icO1bbd" x1="9.438" x2="7.406" y1="21.984" y2="21.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="kj3b22qmi"/><stop offset="1" class="cq2h2ybcw"/></linearGradient><linearGradient id="iNQQayd" x1="26.453" x2="26.453" y1="6.641" y2="21.57" gradientUnits="userSpaceOnUse"><stop class="uoj-q9bjm"/><stop offset="1" class="e30wftblj"/></linearGradient><linearGradient id="iJWHmGf" x1="9.375" x2="21.504" y1="23.26" y2="23.26" gradientUnits="userSpaceOnUse"><stop class="a_20facft"/><stop offset="1" class="uyefi-bwk"/></linearGradient><linearGradient id="iMmZAYb" x1="22.984" x2="20.989" y1="30.141" y2="30.141" gradientUnits="userSpaceOnUse"><stop class="qss9d6bea"/><stop offset="1" class="ciujlsbge"/></linearGradient><linearGradient id="ibIEX3b" x1="16" x2="16" y1="17.821" y2="18.887" gradientUnits="userSpaceOnUse"><stop offset=".172" class="k0yqtvb4y"/><stop offset="1" class="g2x3x3b9c"/></linearGradient><linearGradient id="iiquC1c" x1="9.265" x2="11.801" y1="11.573" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="czshgubnp"/><stop offset="1" class="x0t9k_1va"/></linearGradient><linearGradient id="iY9me8c" x1="11.438" x2="11.438" y1="4.453" y2="6.828" gradientUnits="userSpaceOnUse"><stop offset=".091" class="ahxlu4b_q"/><stop offset="1" class="v2o-r_b7a"/></linearGradient><linearGradient id="i1zeDdc" x1="15.375" x2="16.734" y1="5.109" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="ou_h1pnfz"/><stop offset=".755" class="lfduhsbkc"/></linearGradient><linearGradient id="iayH9Xd" x1="13.938" x2="14.813" y1="5.625" y2="5.297" gradientUnits="userSpaceOnUse"><stop class="qa3ysvbpv"/><stop offset="1" class="ot6rkkbaq"/></linearGradient><linearGradient id="ihmBiQe" x1="15.715" x2="14.833" y1="9.46" y2="9.202" gradientUnits="userSpaceOnUse"><stop offset=".33" class="qzvj8eb3p"/><stop offset="1" class="k1zwtlygy"/></linearGradient><linearGradient id="iQ7fNxc" x1="20.688" x2="16.938" y1="11.609" y2="17.234" gradientUnits="userSpaceOnUse"><stop class="c8j3jmbml"/><stop offset="1" class="fmusmhbll"/></linearGradient><linearGradient id="iOkntAb" x1="8.789" x2="10.438" y1="16.297" y2="16.297" gradientUnits="userSpaceOnUse"><stop class="vuv8q1bwf"/><stop offset="1" class="kfugjrbqq"/></linearGradient><linearGradient id="i1dqKRc" x1="8.789" x2="9.281" y1="16.297" y2="16.297" gradientUnits="userSpaceOnUse"><stop class="j8x01vxhm"/><stop offset="1" class="w4s272bjo"/></linearGradient><radialGradient id="i95Gsld" cx="0" cy="0" r="1" gradientTransform="rotate(101.941 2.156 6.556)scale(12.4717 21.6521)" gradientUnits="userSpaceOnUse"><stop class="wib31bctj"/><stop offset="1" class="tajcvj1-k"/></radialGradient><radialGradient id="i7hvcic" cx="0" cy="0" r="1" gradientTransform="rotate(111.224 .923 8.742)scale(10.6606 8.60283)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="v22nnqvdq"/><stop offset=".979" class="l5kilk6no"/></radialGradient><radialGradient id="iE9anhd" cx="0" cy="0" r="1" gradientTransform="matrix(2.26563 0 0 5.8 22.984 14.86)" gradientUnits="userSpaceOnUse"><stop class="m9oxlrbum"/><stop offset="1" class="k38d0e5fm"/></radialGradient><radialGradient id="izBA4Qc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 0 0 9.79484 22.984 13.078)" gradientUnits="userSpaceOnUse"><stop class="r7oiijjsu"/><stop offset="1" class="xto29et-h"/></radialGradient><radialGradient id="iGxPIkc" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 0 0 9.5 22.688 18.047)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q1rj5ab_c"/><stop offset="1" class="iw2to68zj"/></radialGradient><radialGradient id="iWC6BBb" cx="0" cy="0" r="1" gradientTransform="matrix(3.89065 10.211 -11.0963 4.22797 22.563 11.36)" gradientUnits="userSpaceOnUse"><stop offset=".758" class="xip7g_hqk"/><stop offset=".935" class="e--l1-b7k"/></radialGradient><radialGradient id="i7uxOnc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -4.05574 23.688 5.172)" gradientUnits="userSpaceOnUse"><stop class="abh7hobfa"/><stop offset="1" class="nxu2dbp-e"/></radialGradient><radialGradient id="iANeIvb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.1875 -.18753 .3131 -10.33036 16.563 10.922)" gradientUnits="userSpaceOnUse"><stop class="apl8_bbed"/><stop offset="1" class="a-jn0fibb"/></radialGradient><radialGradient id="iFgV6rb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 .9286 -3.8289 -5.79845 15.656 6.61)" gradientUnits="userSpaceOnUse"><stop class="v4dikkbrq"/><stop offset="1" class="we77b0pzk"/></radialGradient><radialGradient id="iW01vnd" cx="0" cy="0" r="1" gradientTransform="rotate(121.439 7.903 8.467)scale(9.04686 2.78365)" gradientUnits="userSpaceOnUse"><stop class="klhqjkj0i"/><stop offset="1" class="akzk-ob8v"/></radialGradient><radialGradient id="iT4eAic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1784 5.12503 -.4283 -.26562 19.539 5.266)" gradientUnits="userSpaceOnUse"><stop class="yqilnjbvg"/><stop offset="1" class="fezn2ocbh"/></radialGradient><filter id="iziCT7p" width="7.338" height="16.563" x="2.078" y="5.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.701961 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16682"/></filter><filter id="iXkh7ie" width="3.125" height="7.299" x="7.562" y="11.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16682" stdDeviation=".375"/></filter><filter id="iTSr66b" width="7.688" height="16.813" x="22.234" y="5.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.890196 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16682"/></filter><filter id="ikI0vDc" width="6.73" height="9.155" x="12.155" y="4.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16682" stdDeviation=".2"/></filter><filter id="iv4Wd8c" width="14.622" height="6.037" x="8.589" y="12.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.258824 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16682"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:kimono" /></template>
<style>
.a_20facft {
  stop-color: var(--svg-color--298dea, #298DEA);
}

.a-jn0fibb {
  stop-color: var(--svg-color--3282cd, #3282CD);
  stop-opacity: 0;
}

.a8nkx9b4n {
  fill: var(--svg-color--0859ae, #0859AE);
  d: path("M8.312 12.898c0-.134.013-.244.028-.244h1.57c.015 0 .027.11.027.244v5.311c0 .135-.012.244-.028.244H8.34c-.015 0-.028-.11-.028-.244z");
}

.abh7hobfa {
  stop-color: var(--svg-color--58d8ff, #58D8FF);
}

.ahxlu4b_q {
  stop-color: var(--svg-color--5ec6ff, #5EC6FF);
}

.akrcu9ndd {
  d: path("M21.476 15.946c.604.018 1.148.084 1.508.143V30.14H9.016V16.089c.36-.059.904-.125 1.508-.143z");
}

.akzk-ob8v {
  stop-color: var(--svg-color--b5adc3, #B5ADC3);
}

.apl8_bbed {
  stop-color: var(--svg-color--3282cd, #3282CD);
}

.c8j3jmbml {
  stop-color: var(--svg-color--716585, #716585);
}

.cckdscc8f {
  d: path("M8.115 5.602c.348-.175.745-.303.9-.344V21.18a.386.386 0 0 1-.391.39c-4.852-.123-6.546-4.774-6.546-6.86V9.24c0-.22.119-.421.311-.526c1.95-1.066 5.397-2.946 5.726-3.111");
}

.ciujlsbge {
  stop-color: var(--svg-color--47bdff, #47BDFF);
  stop-opacity: 0;
}

.cq2h2ybcw {
  stop-color: var(--svg-color--2f90f8, #2F90F8);
  stop-opacity: 0;
}

.czshgubnp {
  stop-color: var(--svg-color--2fa2f3, #2FA2F3);
}

.e--l1-b7k {
  stop-color: var(--svg-color--4e78df, #4E78DF);
}

.e30wftblj {
  stop-color: var(--svg-color--39aaff, #39AAFF);
}

.fbtn3b-6i {
  fill: var(--svg-color--ff90e8, #FF90E8);
  d: path("m19.204 20.723l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.fezn2ocbh {
  stop-color: var(--svg-color--e2dfec, #E2DFEC);
  stop-opacity: 0;
}

.fmusmhbll {
  stop-color: var(--svg-color--483167, #483167);
}

.ft5dv1b6b {
  fill: none;
}

.g2x3x3b9c {
  stop-color: var(--svg-color--2d8bea, #2D8BEA);
  stop-opacity: 0;
}

.ho6_uubce {
  fill: var(--svg-color--ff97ea, #FF97EA);
  d: path("m27.183 14.77l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.iw2to68zj {
  stop-color: var(--svg-color--2c96f5, #2C96F5);
  stop-opacity: 0;
}

.j8x01vxhm {
  stop-color: var(--svg-color--3c3774, #3C3774);
}

.jd75nrbwq {
  d: path("M8.79 12.453a.25.25 0 0 1 .25-.25h13.92a.25.25 0 0 1 .25.25v5.438a.25.25 0 0 1-.25.25H9.04a.25.25 0 0 1-.25-.25z");
}

.jtadfqbjn {
  fill: var(--svg-color--ea70c7, #EA70C7);
  d: path("m12.225 20.723l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.k0yqtvb4y {
  stop-color: var(--svg-color--2165c9, #2165C9);
}

.k1zwtlygy {
  stop-color: var(--svg-color--b4b3bb, #B4B3BB);
  stop-opacity: 0;
}

.k38d0e5fm {
  stop-color: var(--svg-color--40b5ff, #40B5FF);
  stop-opacity: 0;
}

.kfugjrbqq {
  stop-color: var(--svg-color--4b3f6c, #4B3F6C);
  stop-opacity: 0;
}

.kj3b22qmi {
  stop-color: var(--svg-color--0c63ca, #0C63CA);
}

.klhqjkj0i {
  stop-color: var(--svg-color--e3e1ea, #E3E1EA);
}

.l5kilk6no {
  stop-color: var(--svg-color--406dd5, #406DD5);
}

.lfduhsbkc {
  stop-color: var(--svg-color--4f4363, #4F4363);
}

.m63mifbku {
  fill: var(--svg-color--ed70cb, #ED70CB);
  d: path("m12.225 26.723l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.m9oxlrbum {
  stop-color: var(--svg-color--40b5ff, #40B5FF);
}

.n_swb0bro {
  d: path("m19.539 5l-5.188 8.62l-1.17-.703L17.946 5z");
}

.ns4bl8bae {
  fill: var(--svg-color--255ba0, #255BA0);
  d: path("m12.555 5.266l2.539.203l.703 2.797l1.094-2.157h1.593l-4.351 7.512l-1.17-.696L15 9.575z");
}

.nxu2dbp-e {
  stop-color: var(--svg-color--58d8ff, #58D8FF);
  stop-opacity: 0;
}

.ot6rkkbaq {
  stop-color: var(--svg-color--817298, #817298);
  stop-opacity: 0;
}

.ou_h1pnfz {
  stop-color: var(--svg-color--6c5b88, #6C5B88);
}

.pxmjsb7vg {
  d: path("M14.086 5h-1.593l3.054 5.076l1.17-.704z");
}

.q1rj5ab_c {
  stop-color: var(--svg-color--0e68c4, #0E68C4);
}

.qa3ysvbpv {
  stop-color: var(--svg-color--817298, #817298);
}

.qhijf8bcg {
  fill: var(--svg-color--ef72cf, #EF72CF);
  d: path("m6.8 17.739l.19.34c.03.05.07.1.13.13l.34.18c.22.12.22.44 0 .57l-.34.19c-.06.03-.1.07-.13.13l-.19.33c-.12.22-.44.22-.57 0l-.18-.33a.27.27 0 0 0-.13-.13l-.34-.19c-.22-.12-.22-.44 0-.57l.34-.18c.06-.03.1-.08.13-.13l.18-.34c.13-.22.45-.22.57 0");
}

.qss9d6bea {
  stop-color: var(--svg-color--4ecbff, #4ECBFF);
}

.qtsxuno4v {
  fill: var(--svg-color--ffa7f4, #FFA7F4);
  d: path("m27.183 8.75l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.qzvj8eb3p {
  stop-color: var(--svg-color--b4b3bb, #B4B3BB);
}

.r7oiijjsu {
  stop-color: var(--svg-color--4dc8ff, #4DC8FF);
}

.riemxlaxy {
  d: path("M14.063 5L16 8.234L17.961 5z");
}

.rip9tndip {
  d: path("M23.885 5.602a5.4 5.4 0 0 0-.9-.344V21.18c0 .217.174.396.391.39c4.852-.123 6.546-4.774 6.546-6.86V9.24a.6.6 0 0 0-.311-.526c-1.95-1.066-5.397-2.946-5.727-3.111");
}

.s9veomitu {
  fill: var(--svg-color--ff7cd8, #FF7CD8);
  d: path("m15.72 23.864l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.slzuxybpu {
  d: path("M18.188 5c.603.03-2.236 3.943-1.875 4.047l-4.47 5.281l-2.827 1.361V5.252c.36-.104.904-.221 1.508-.252z");
}

.tajcvj1-k {
  stop-color: var(--svg-color--339dfb, #339DFB);
}

.uehcfgbmf {
  fill: var(--svg-color--f87bcf, #F87BCF);
  d: path("m6.8 11.72l.19.34c.03.05.07.1.13.13l.34.18c.22.12.22.44 0 .57l-.34.19c-.06.03-.1.07-.13.13l-.19.33c-.12.22-.44.22-.57 0l-.18-.33a.27.27 0 0 0-.13-.13l-.34-.19c-.22-.12-.22-.44 0-.57l.34-.18c.06-.03.1-.08.13-.13l.18-.34c.13-.22.45-.22.57 0");
}

.uf7s8zb3z {
  d: path("M21.476 5a7 7 0 0 1 1.508.252v24.889H9.016V5.252c.36-.104.904-.221 1.508-.252z");
}

.uoj-q9bjm {
  stop-color: var(--svg-color--4bf, #4BF);
}

.uyefi-bwk {
  stop-color: var(--svg-color--46bbff, #46BBFF);
}

.v22nnqvdq {
  stop-color: var(--svg-color--3193fb, #3193FB);
  stop-opacity: 0;
}

.v2o-r_b7a {
  stop-color: var(--svg-color--329cf2, #329CF2);
  stop-opacity: 0;
}

.v4dikkbrq {
  stop-color: var(--svg-color--f1f0f7, #F1F0F7);
}

.v5ow9wbca {
  d: path("M21.476 5a7 7 0 0 1 1.508.252V15.69H9.016V5.252c.36-.104.904-.221 1.508-.252z");
}

.v7ik8kbhq {
  fill: var(--svg-color--ff90eb, #FF90EB);
  d: path("m19.204 26.723l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.vbqp1pbxh {
  fill: var(--svg-color--e871c2, #E871C2);
  d: path("m4.78 14.77l.19.34c.03.05.07.1.13.13l.34.18c.22.12.22.44 0 .57l-.34.19c-.06.03-.1.07-.13.13l-.19.33c-.12.22-.44.22-.57 0l-.18-.33a.27.27 0 0 0-.13-.13l-.34-.19c-.22-.12-.22-.44 0-.57l.34-.18c.06-.03.1-.08.13-.13l.18-.34c.13-.22.45-.22.57 0");
}

.vuv8q1bwf {
  stop-color: var(--svg-color--4b3f6c, #4B3F6C);
}

.w4s272bjo {
  stop-color: var(--svg-color--3c3774, #3C3774);
  stop-opacity: 0;
}

.w5_orxzhg {
  fill: var(--svg-color--ff89de, #FF89DE);
  d: path("m25.164 11.72l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.w9060wb-g {
  fill: var(--svg-color--f474d2, #F474D2);
  d: path("m25.164 17.739l-.19.34c-.03.05-.07.1-.13.13l-.34.18c-.22.12-.22.44 0 .57l.34.19c.06.03.1.07.13.13l.19.33c.12.22.44.22.57 0l.18-.33c.03-.06.07-.1.13-.13l.34-.19c.22-.12.22-.44 0-.57l-.34-.18a.33.33 0 0 1-.13-.13l-.18-.34c-.13-.22-.45-.22-.57 0");
}

.we77b0pzk {
  stop-color: var(--svg-color--bcb5c9, #BCB5C9);
}

.wib31bctj {
  stop-color: var(--svg-color--31a4f1, #31A4F1);
}

.x0t9k_1va {
  stop-color: var(--svg-color--2fa2f3, #2FA2F3);
  stop-opacity: 0;
}

.xip7g_hqk {
  stop-color: var(--svg-color--4e78df, #4E78DF);
  stop-opacity: 0;
}

.xov3gc4-c {
  fill: var(--svg-color--ef7bc1, #EF7BC1);
  d: path("m4.78 8.75l.19.34c.03.05.07.1.13.13l.34.18c.22.12.22.44 0 .57l-.34.19c-.06.03-.1.07-.13.13l-.19.33c-.12.22-.44.22-.57 0l-.18-.33a.27.27 0 0 0-.13-.13l-.34-.19c-.22-.12-.22-.44 0-.57l.34-.18c.06-.03.1-.08.13-.13l.18-.34c.13-.22.45-.22.57 0");
}

.xto29et-h {
  stop-color: var(--svg-color--4dc8ff, #4DC8FF);
  stop-opacity: 0;
}

.yqilnjbvg {
  stop-color: var(--svg-color--fcffff, #FCFFFF);
}

</style>
