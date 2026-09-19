<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaBefGd)" class="au33tb1-y"/><path fill="url(#iA50Idc)" class="au33tb1-y"/><g filter="url(#iYN0fBc)"><circle fill="url(#iVEVykc)" class="mb47lwlwm"/></g><path fill="url(#iq52fFc)" class="mf1ip6bkv"/><path fill="url(#iXKFByc)" class="mf1ip6bkv"/><circle fill="url(#iRYDAze)" class="sx_cogrrl"/><ellipse fill="url(#iZI8NKc)" transform="rotate(-28.067 4.438 12.105)" class="uiwyj9bsp"/><ellipse fill="url(#iUavCAc)" transform="rotate(-19.675 7.2 12.841)" class="yhdm5_82k"/><ellipse fill="url(#i7BsmQd)" transform="rotate(-3.605 11.312 13.967)" class="qdxpqddoo"/><ellipse fill="url(#iY9i0IQ)" transform="rotate(13.066 16.152 15.267)" class="trqbp0b1b"/><ellipse fill="url(#iLZbRYd)" transform="rotate(35.225 21.015 16.572)" class="owozycble"/><ellipse fill="url(#ih56z4c)" transform="rotate(49.282 25.125 17.657)" class="g9kb3olfi"/><ellipse fill="url(#ipDwkvg)" transform="rotate(57.814 27.87 18.384)" class="ymckl3bdd"/><path fill="url(#ijBewii)" class="lxs5qg_8z"/><path fill="url(#i8XGWcd)" class="lxs5qg_8z"/><path fill="url(#ijwr1ee)" class="lxs5qg_8z"/><path fill="url(#iFo3W7d)" class="lxs5qg_8z"/><defs><radialGradient id="iaBefGd" cx="0" cy="0" r="1" gradientTransform="rotate(107.317 -.17 18.52)scale(17.2179 12.9134)" gradientUnits="userSpaceOnUse"><stop class="za2--kkqh"/><stop offset="1" class="by1e4wblb"/></radialGradient><radialGradient id="iVEVykc" cx="0" cy="0" r="1" gradientTransform="rotate(-139.399 12.633 3.07)scale(9.13867)" gradientUnits="userSpaceOnUse"><stop class="cqg1l5bvd"/><stop offset="1" class="hxjx9bbtu"/></radialGradient><radialGradient id="iq52fFc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62496 -21.62506 62.2698 -13.31766 22.648 20.07)" gradientUnits="userSpaceOnUse"><stop class="dl7d5bcrr"/><stop offset="1" class="w-65gpe-v"/></radialGradient><radialGradient id="iXKFByc" cx="0" cy="0" r="1" gradientTransform="rotate(154.243 8.028 7.274)scale(15.7965 54.0343)" gradientUnits="userSpaceOnUse"><stop offset=".454" class="tt_6xpbwg"/><stop offset=".927" class="jb8ile72u"/></radialGradient><radialGradient id="iRYDAze" cx="0" cy="0" r="1" gradientTransform="matrix(1.61538 -.99721 2.10386 3.40803 19.718 10.321)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iZI8NKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06058 .84422 -1.68788 -.12111 4.508 11.704)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="ka1vt2b2i"/><stop offset="1" class="ywpul_b7i"/></radialGradient><radialGradient id="iUavCAc" cx="0" cy="0" r="1" gradientTransform="matrix(.67966 1.02292 -1.22792 .81587 6.588 12.169)" gradientUnits="userSpaceOnUse"><stop class="xehk8gb0s"/><stop offset="1" class="bkmh8w3ov"/></radialGradient><radialGradient id="i7BsmQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5629 1.19042 -1.33636 1.75452 10.425 13.391)" gradientUnits="userSpaceOnUse"><stop class="hfqoeluyz"/><stop offset="1" class="o0ie84z5l"/></radialGradient><radialGradient id="iY9i0IQ" cx="0" cy="0" r="1" gradientTransform="rotate(4.623 -179.161 191.561)scale(2.80195 2.61213)" gradientUnits="userSpaceOnUse"><stop class="hfqoeluyz"/><stop offset="1" class="o0ie84z5l"/></radialGradient><radialGradient id="iLZbRYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.2777 -.56684 .68624 2.7575 20.016 16.96)" gradientUnits="userSpaceOnUse"><stop class="qeica1bvx"/><stop offset="1" class="jrd41cb2h"/></radialGradient><radialGradient id="ih56z4c" cx="0" cy="0" r="1" gradientTransform="matrix(.0684 -1.22391 1.71863 .09606 25.17 18.285)" gradientUnits="userSpaceOnUse"><stop class="i0vk8w4qo"/><stop offset="1" class="ghn9m6p9z"/></radialGradient><radialGradient id="ipDwkvg" cx="0" cy="0" r="1" gradientTransform="matrix(.064 -.86436 1.28151 .0949 27.891 18.79)" gradientUnits="userSpaceOnUse"><stop class="v4h4_gbmx"/><stop offset="1" class="idbemgvug"/></radialGradient><radialGradient id="ijBewii" cx="0" cy="0" r="1" gradientTransform="matrix(-12.31248 -8.0589 4.06583 -6.21181 26.523 24.067)" gradientUnits="userSpaceOnUse"><stop class="c0lfucc3q"/><stop offset="1" class="d3py36b2d"/></radialGradient><radialGradient id="i8XGWcd" cx="0" cy="0" r="1" gradientTransform="rotate(167.056 8.882 10.254)scale(15.9041 41.4161)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="q_fhv7b2b"/><stop offset="1" class="jpcru7ysw"/></radialGradient><radialGradient id="ijwr1ee" cx="0" cy="0" r="1" gradientTransform="rotate(15.815 -51.932 58.894)scale(15.1355 2.11479)" gradientUnits="userSpaceOnUse"><stop class="bhg18g52b"/><stop offset="1" class="zw6a8b5fd"/></radialGradient><radialGradient id="iFo3W7d" cx="0" cy="0" r="1" gradientTransform="rotate(-80.239 21.51 3.453)scale(4.05512 11.8053)" gradientUnits="userSpaceOnUse"><stop class="sojehobgr"/><stop offset="1" class="i6gjmlofw"/></radialGradient><linearGradient id="iA50Idc" x1="14.28" x2="14.147" y1="22.188" y2="22.695" gradientUnits="userSpaceOnUse"><stop class="e85_4ccgw"/><stop offset="1" class="z2enndb2j"/></linearGradient><filter id="iYN0fBc" width="13.359" height="13.109" x="10.382" y="6.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.623529 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13115"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flying-saucer" /></template>
<style>
.au33tb1-y {
  d: path("M10.058 21.14L4.214 30h14.91l-.414-6.555z");
}

.bhg18g52b {
  stop-color: var(--svg-color--b8b2bd, #B8B2BD);
}

.bkmh8w3ov {
  stop-color: var(--svg-color--372c40, #372C40);
}

.by1e4wblb {
  stop-color: var(--svg-color--eac82d, #EAC82D);
}

.c0lfucc3q {
  stop-color: var(--svg-color--7b7180, #7B7180);
}

.cqg1l5bvd {
  stop-color: var(--svg-color--66f5ff, #66F5FF);
}

.d3py36b2d {
  stop-color: var(--svg-color--817a86, #817A86);
}

.dl7d5bcrr {
  stop-color: var(--svg-color--f7f6f8, #F7F6F8);
}

.e85_4ccgw {
  stop-color: var(--svg-color--f9d230, #F9D230);
}

.ft5dv1b6b {
  fill: none;
}

.g9kb3olfi {
  cx: 25.125px;
  cy: 17.657px;
  rx: 1.285px;
  ry: 0.654px;
}

.ghn9m6p9z {
  stop-color: var(--svg-color--4b385b, #4B385B);
}

.hfqoeluyz {
  stop-color: var(--svg-color--655771, #655771);
}

.hxjx9bbtu {
  stop-color: var(--svg-color--3ba9e3, #3BA9E3);
}

.i0vk8w4qo {
  stop-color: var(--svg-color--736282, #736282);
}

.i6gjmlofw {
  stop-color: var(--svg-color--9f8a7a, #9F8A7A);
  stop-opacity: 0;
}

.idbemgvug {
  stop-color: var(--svg-color--564366, #564366);
}

.jb8ile72u {
  stop-color: var(--svg-color--706f70, #706F70);
}

.jpcru7ysw {
  stop-color: var(--svg-color--817a82, #817A82);
}

.jrd41cb2h {
  stop-color: var(--svg-color--3e2d4c, #3E2D4C);
}

.ka1vt2b2i {
  stop-color: var(--svg-color--473b51, #473B51);
}

.lxs5qg_8z {
  d: path("M1.874 14.764c.64 1.303 1.637 2.834 3.246 4.123c1.209.968 2.65 1.641 4.156 2.043L19.5 23.65c1.175.313 2.39.508 3.597.373c1.77-.197 3.72-.735 5.607-1.975a2 2 0 0 0 .863-1.268L1.8 13.36c-.168.438-.16.93.074 1.404");
}

.mb47lwlwm {
  cx: 16.811px;
  cy: 12.766px;
  r: 6.43px;
}

.mf1ip6bkv {
  d: path("M5.12 18.887c-1.609-1.289-2.607-2.82-3.246-4.123c-.441-.899-.079-1.856.762-2.4c2.68-1.961 5.952-2.266 8.172-1.883l12.695 3.406c2.965.914 4.822 3.406 5.886 5.537c.464.928.18 2.053-.686 2.624c-1.887 1.24-3.838 1.778-5.607 1.975c-1.208.135-2.422-.06-3.597-.372L9.276 20.93c-1.507-.402-2.947-1.075-4.156-2.043");
}

.o0ie84z5l {
  stop-color: var(--svg-color--32273c, #32273C);
}

.owozycble {
  cx: 21.015px;
  cy: 16.572px;
  rx: 1.285px;
  ry: 0.847px;
}

.q_fhv7b2b {
  stop-color: var(--svg-color--817a82, #817A82);
  stop-opacity: 0;
}

.qdxpqddoo {
  cx: 11.312px;
  cy: 13.967px;
  rx: 1.285px;
  ry: 0.842px;
}

.qeica1bvx {
  stop-color: var(--svg-color--6d5a7e, #6D5A7E);
}

.sojehobgr {
  stop-color: var(--svg-color--9f8a7a, #9F8A7A);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sx_cogrrl {
  cx: 20.686px;
  cy: 9.773px;
  r: 0.969px;
}

.trqbp0b1b {
  cx: 16.152px;
  cy: 15.267px;
  rx: 1.285px;
  ry: 0.894px;
}

.tt_6xpbwg {
  stop-color: var(--svg-color--706f70, #706F70);
  stop-opacity: 0;
}

.uiwyj9bsp {
  cx: 4.438px;
  cy: 12.105px;
  rx: 1.251px;
  ry: 0.373px;
}

.v4h4_gbmx {
  stop-color: var(--svg-color--746383, #746383);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w-65gpe-v {
  stop-color: var(--svg-color--808081, #808081);
}

.xehk8gb0s {
  stop-color: var(--svg-color--5a5162, #5A5162);
}

.yhdm5_82k {
  cx: 7.2px;
  cy: 12.841px;
  rx: 1.277px;
  ry: 0.655px;
}

.ymckl3bdd {
  cx: 27.87px;
  cy: 18.384px;
  rx: 1.265px;
  ry: 0.355px;
}

.ywpul_b7i {
  stop-color: var(--svg-color--383838, #383838);
}

.z2enndb2j {
  stop-color: var(--svg-color--f9d230, #F9D230);
  stop-opacity: 0;
}

.za2--kkqh {
  stop-color: var(--svg-color--ffe940, #FFE940);
}

.zw6a8b5fd {
  stop-color: var(--svg-color--b8b2bd, #B8B2BD);
  stop-opacity: 0;
}

</style>
