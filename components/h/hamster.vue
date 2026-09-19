<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#iPsI6Yd)"><path fill="url(#iRMrVhb)" class="iwxnzyypj"/><path fill="url(#ijYlLEd)" class="iwxnzyypj"/><path fill="url(#i7wOe6c)" class="iwxnzyypj"/><path fill="url(#iQbfSkc)" class="iwxnzyypj"/><path fill="url(#iYPkL8l)" class="iwxnzyypj"/><path fill="url(#iPiG7xb)" class="iwxnzyypj"/><path fill="url(#idH6Emc)" class="iwxnzyypj"/><path fill="url(#iyRQyTd)" class="iwxnzyypj"/><path fill="url(#ipW0wDe)" class="iwxnzyypj"/><path fill="url(#i4XfBQs)" class="iwxnzyypj"/><path fill="url(#iVZcrXb)" class="iwxnzyypj"/><path fill="url(#ir1CZKe)" class="iwxnzyypj"/><g filter="url(#iw7vi6b)"><path class="oqhwqxbpy"/></g><path fill="url(#i1iv22T)" class="rbwmiccjh"/><path fill="url(#iqe3rhx)" class="rbwmiccjh"/><path fill="url(#ixqcRuP)" class="rbwmiccjh"/><rect fill="url(#ijPxuAd)" class="iizmxc5sk"/><rect fill="url(#iomOemd)" class="iizmxc5sk"/><rect fill="url(#icp5jdI)" class="iizmxc5sk"/><rect fill="url(#iJOIVYW)" class="yt54b-b_d"/><rect fill="url(#izqYoJc)" class="yt54b-b_d"/><rect fill="url(#i438Lyb)" class="yt54b-b_d"/><g filter="url(#i4gSxIU)"><circle fill="url(#ihwW4Wd)" class="tzase31ra"/><circle fill="url(#ikOmX1d)" class="tzase31ra"/></g><g filter="url(#iiaxS3U)"><circle fill="url(#iHqve0c)" class="s3epqhb4u"/><circle fill="url(#isMOWvZ)" class="s3epqhb4u"/><circle fill="url(#ihOnIJe)" class="s3epqhb4u"/></g><g filter="url(#iZ7E8Ld)"><ellipse fill="url(#i7XQgEk)" transform="rotate(-34.317 23.078 17.996)" class="clcqpxbuv"/></g><g filter="url(#il2Icdk)"><path stroke="url(#iAKw54b)" class="r5_lz_ber"/></g><g filter="url(#iAyfSUc)"><path stroke="url(#iWaLJ6c)" class="l3q9c-byt"/></g><path stroke="url(#iojAipd)" class="mmbyv6b8j"/><path stroke="url(#ihdaODe)" class="mmbyv6b8j"/><path stroke="url(#iigmQOl)" class="qbt1jcbzd"/><path stroke="url(#iWwzw8d)" class="qbt1jcbzd"/><path fill="url(#iKC7mOb)" clip-rule="evenodd" class="iktc0eb2t"/></g><defs><radialGradient id="ijYlLEd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 2.1875 -6.19564 10.26706 3.813 19.25)" gradientUnits="userSpaceOnUse"><stop class="mxm_qjwik"/><stop offset="1" class="o_tl0nb_s"/></radialGradient><radialGradient id="i7wOe6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 3.0625 -4.76296 5.05456 20 5)" gradientUnits="userSpaceOnUse"><stop class="q1w1asb3c"/><stop offset="1" class="zdu84_u1y"/></radialGradient><radialGradient id="iQbfSkc" cx="0" cy="0" r="1" gradientTransform="matrix(7.4375 .625 -1.03525 12.31948 2 9.375)" gradientUnits="userSpaceOnUse"><stop class="q1w1asb3c"/><stop offset="1" class="zdu84_u1y"/></radialGradient><radialGradient id="iYPkL8l" cx="0" cy="0" r="1" gradientTransform="matrix(-4.68752 3.99998 -3.43626 -4.0269 29.625 7.188)" gradientUnits="userSpaceOnUse"><stop class="izozt5b0n"/><stop offset="1" class="h_6fgdh4m"/></radialGradient><radialGradient id="iPiG7xb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93749 2.18753 -3.14567 -5.66212 12.75 5.625)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="izozt5b0n"/><stop offset="1" class="h_6fgdh4m"/></radialGradient><radialGradient id="idH6Emc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25 -5.3125 3.0221 -2.98656 28.125 15.688)" gradientUnits="userSpaceOnUse"><stop class="mm0hjbcnb"/><stop offset="1" class="j71yqnp3y"/></radialGradient><radialGradient id="iyRQyTd" cx="0" cy="0" r="1" gradientTransform="matrix(5.875 -1.0625 .70705 3.90957 3.313 15.375)" gradientUnits="userSpaceOnUse"><stop class="nm-axxbxl"/><stop offset="1" class="gz2diml1n"/></radialGradient><radialGradient id="ipW0wDe" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -6.625 17.90413 18.74864 2.75 26.063)" gradientUnits="userSpaceOnUse"><stop class="nm-axxbxl"/><stop offset="1" class="gz2diml1n"/></radialGradient><radialGradient id="i4XfBQs" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.875 14.5 0 16 30.375)" gradientUnits="userSpaceOnUse"><stop class="jv20scj_o"/><stop offset="1" class="f-zv3fbcy"/></radialGradient><radialGradient id="iVZcrXb" cx="0" cy="0" r="1" gradientTransform="matrix(.125 -3.1875 8.50408 .3335 13.313 31.5)" gradientUnits="userSpaceOnUse"><stop class="jv20scj_o"/><stop offset="1" class="f-zv3fbcy"/></radialGradient><radialGradient id="ir1CZKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.18753 -3.1875 8.50408 -.50032 21.625 31.5)" gradientUnits="userSpaceOnUse"><stop class="jv20scj_o"/><stop offset="1" class="f-zv3fbcy"/></radialGradient><radialGradient id="iqe3rhx" cx="0" cy="0" r="1" gradientTransform="rotate(-171.87 9.194 10.818)scale(2.54116 2.45548)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="jnn8gachp"/><stop offset="1" class="pbdnt9b_j"/></radialGradient><radialGradient id="ixqcRuP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33593 .72267 -.42448 -.7847 17.336 22.445)" gradientUnits="userSpaceOnUse"><stop class="cqefsqb0k"/><stop offset=".663" class="v74648q6x"/></radialGradient><radialGradient id="icp5jdI" cx="0" cy="0" r="1" gradientTransform="matrix(-.5726 -1.63534 1.57679 -.5521 12.273 19.664)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="i438Lyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5726 -1.63534 1.57679 -.5521 20.273 19.664)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="ihwW4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.58596 -2.18754 3.23556 -9.7412 11.148 10.875)" gradientUnits="userSpaceOnUse"><stop class="u_va_nbey"/><stop offset="1" class="bb4qhdcdt"/></radialGradient><radialGradient id="ikOmX1d" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -5.8125 5.9736 3.72548 4.812 14.813)" gradientUnits="userSpaceOnUse"><stop class="h1a90zbxt"/><stop offset=".867" class="b5ik0c0-u"/></radialGradient><radialGradient id="iHqve0c" cx="0" cy="0" r="1" gradientTransform="matrix(4.5625 -4.4375 6.56347 6.74835 22.125 12.438)" gradientUnits="userSpaceOnUse"><stop class="jufiuqe8v"/><stop offset="1" class="bb4qhdcdt"/></radialGradient><radialGradient id="isMOWvZ" cx="0" cy="0" r="1" gradientTransform="rotate(-43.76 28.865 -19.223)scale(10.2112 9.9649)" gradientUnits="userSpaceOnUse"><stop class="h1a90zbxt"/><stop offset=".867" class="b5ik0c0-u"/></radialGradient><radialGradient id="ihOnIJe" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.5625 7.64243 8.58464 22.625 12.563)" gradientUnits="userSpaceOnUse"><stop class="h1a90zbxt"/><stop offset=".24" class="b5ik0c0-u"/></radialGradient><radialGradient id="i7XQgEk" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4379 -.64833 1.88521 -15.81221 25.698 19.784)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="oagqsfbmn"/><stop offset="1" class="hzx-btbkr"/></radialGradient><radialGradient id="iojAipd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3568 1.42187 -1.68395 -.42257 14.755 25.531)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="nd-qy1bcv"/><stop offset=".725" class="zrku6vbzr"/><stop offset="1" class="m6gfci9pl"/></radialGradient><radialGradient id="ihdaODe" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 1.20312 -1.39086 .78574 13.43 25.305)" gradientUnits="userSpaceOnUse"><stop class="ac4p5y5ob"/><stop offset="1" class="doxl7_zcy"/></radialGradient><radialGradient id="iigmQOl" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 1.8828 -1.57718 .30758 17.305 25.148)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="nd-qy1bcv"/><stop offset=".725" class="zrku6vbzr"/><stop offset="1" class="m6gfci9pl"/></radialGradient><radialGradient id="iWwzw8d" cx="0" cy="0" r="1" gradientTransform="rotate(119.464 1.901 18.071)scale(1.38184 1.59746)" gradientUnits="userSpaceOnUse"><stop class="ac4p5y5ob"/><stop offset="1" class="doxl7_zcy"/></radialGradient><radialGradient id="iKC7mOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07811 1.5625 -1.59078 -.07953 16.078 25.234)" gradientUnits="userSpaceOnUse"><stop class="ac4p5y5ob"/><stop offset="1" class="doxl7_zcy"/></radialGradient><linearGradient id="iRMrVhb" x1="16" x2="16" y1="4" y2="29.938" gradientUnits="userSpaceOnUse"><stop class="s9hov9bap"/><stop offset="1" class="os6fa4qvp"/></linearGradient><linearGradient id="i1iv22T" x1="15.031" x2="16.563" y1="22.25" y2="24" gradientUnits="userSpaceOnUse"><stop class="b_1uydbhs"/><stop offset="1" class="hf-zpcceu"/></linearGradient><linearGradient id="ijPxuAd" x1="12.727" x2="11.867" y1="19.484" y2="19.484" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iomOemd" x1="12.959" x2="12.959" y1="21.028" y2="19.619" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iJOIVYW" x1="20.727" x2="19.867" y1="19.484" y2="19.484" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="izqYoJc" x1="20.959" x2="20.959" y1="21.028" y2="19.619" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iAKw54b" x1="22.547" x2="22.547" y1="12.672" y2="15.359" gradientUnits="userSpaceOnUse"><stop class="ikb36437m"/><stop offset=".208" class="k3abtablb"/><stop offset=".755" class="kelaa4bea"/><stop offset="1" class="ikb36437m"/></linearGradient><linearGradient id="iWaLJ6c" x1="13.22" x2="10.545" y1="12.396" y2="12.139" gradientUnits="userSpaceOnUse"><stop class="ikb36437m"/><stop offset=".208" class="k3abtablb"/><stop offset=".755" class="kelaa4bea"/><stop offset="1" class="ikb36437m"/></linearGradient><filter id="iw7vi6b" width="6.979" height="3.426" x="12.511" y="24.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3793" stdDeviation=".25"/></filter><filter id="i4gSxIU" width="8.778" height="8.878" x="2.57" y="5.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.411765 0 0 0 0 0.501961 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3793"/></filter><filter id="iiaxS3U" width="8.728" height="8.728" x="20.702" y="5.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.9125 0 0 0 0 0.410625 0 0 0 0 0.502237 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3793"/></filter><filter id="iZ7E8Ld" width="11.584" height="14.359" x="17.286" y="10.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3793" stdDeviation=".75"/></filter><filter id="il2Icdk" width="4.271" height="3.641" x="20.683" y="12.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3793" stdDeviation=".2"/></filter><filter id="iAyfSUc" width="4.948" height="4.509" x="8.327" y="10.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3793" stdDeviation=".2"/></filter><clipPath id="iPsI6Yd"><path class="dzwchhb5s"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hamster" /></template>
<style>
.ac4p5y5ob {
  stop-color: var(--svg-color--492f30, #492F30);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b_1uydbhs {
  stop-color: var(--svg-color--f03273, #F03273);
}

.b5ik0c0-u {
  stop-color: var(--svg-color--ffcfb5, #FFCFB5);
  stop-opacity: 0;
}

.bb4qhdcdt {
  stop-color: var(--svg-color--ff8199, #FF8199);
}

.clcqpxbuv {
  cx: 23.078px;
  cy: 17.996px;
  rx: 2.52px;
  ry: 6.656px;
}

.cqefsqb0k {
  stop-color: var(--svg-color--ff8ad5, #FF8AD5);
}

.doxl7_zcy {
  stop-color: var(--svg-color--492f30, #492F30);
  stop-opacity: 0;
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.dzwchhb5s {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 .969h32v32H0z");
}

.f-zv3fbcy {
  stop-color: var(--svg-color--c8656a, #C8656A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gz2diml1n {
  stop-color: var(--svg-color--d48670, #D48670);
  stop-opacity: 0;
}

.h_6fgdh4m {
  stop-color: var(--svg-color--ffdaae, #FFDAAE);
  stop-opacity: 0;
}

.h1a90zbxt {
  stop-color: var(--svg-color--ffcfb5, #FFCFB5);
}

.hf-zpcceu {
  stop-color: var(--svg-color--ff32af, #FF32AF);
}

.hzx-btbkr {
  stop-color: var(--svg-color--ffda9f, #FFDA9F);
  stop-opacity: 0;
}

.iizmxc5sk {
  width: 1.484px;
  height: 3px;
  x: 11.242px;
  y: 17.984px;
  rx: 0.742px;
}

.ikb36437m {
  stop-color: var(--svg-color--ffce9d, #FFCE9D);
  stop-opacity: 0;
}

.iktc0eb2t {
  fill-rule: evenodd;
  d: path("M16 24.688a.5.5 0 0 1 .5.477c.004.074.066.359.23.606c.152.23.342.362.62.34c.347-.028.487-.151.55-.238a.5.5 0 0 0 .087-.336a.5.5 0 0 1 .995-.105c.03.296-.025.688-.273 1.029c-.26.358-.687.6-1.279.647c-.67.053-1.137-.272-1.43-.641c-.293.369-.76.695-1.43.64c-.592-.046-1.02-.288-1.28-.646a1.5 1.5 0 0 1-.272-1.029a.5.5 0 0 1 .995.105a.5.5 0 0 0 .087.337c.063.086.203.21.55.237c.278.022.468-.11.62-.34a1.5 1.5 0 0 0 .23-.606a.5.5 0 0 1 .149-.333a.5.5 0 0 1 .351-.145");
}

.iwxnzyypj {
  d: path("M13.36 10.66q.077-.46.078-.941a5.719 5.719 0 1 0-6.697 5.635c.24.042.364.33.215.523c-1.769 2.304-2.925 4.831-2.925 6.639c0 4.484 4.063 7.422 7.063 7.422c2.257 0 3.27-.397 3.978-.675c.38-.149.672-.263 1.022-.263c.383 0 .683.138 1.054.307c.597.274 1.377.63 2.977.63c2.828 0 7.828-2.125 7.828-7.421c0-1.785-1.08-4.34-2.793-6.668c-.14-.191-.021-.47.212-.514A5.72 5.72 0 0 0 24.282 4a5.72 5.72 0 0 0-5.66 6.553a7.5 7.5 0 0 0-2.528-.46c-.905 0-1.825.206-2.734.567");
}

.izozt5b0n {
  stop-color: var(--svg-color--ffdaae, #FFDAAE);
}

.j71yqnp3y {
  stop-color: var(--svg-color--f8a583, #F8A583);
  stop-opacity: 0;
}

.jnn8gachp {
  stop-color: var(--svg-color--d53238, #D53238);
  stop-opacity: 0;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jufiuqe8v {
  stop-color: var(--svg-color--ffad98, #FFAD98);
}

.jv20scj_o {
  stop-color: var(--svg-color--c8656a, #C8656A);
}

.k3abtablb {
  stop-color: var(--svg-color--ffd6ac, #FFD6AC);
}

.kelaa4bea {
  stop-color: var(--svg-color--ffd9b4, #FFD9B4);
}

.l3q9c-byt {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.781 14.688c1.344-.876 3.39-2.782 4.016-3.563");
}

.m6gfci9pl {
  stop-color: var(--svg-color--4c2e4c, #4C2E4C);
}

.mm0hjbcnb {
  stop-color: var(--svg-color--f8a583, #F8A583);
}

.mmbyv6b8j {
  stroke-linecap: round;
  d: path("M13.516 25.484c-.042.396.156 1.05 1.093 1.125c1.037.083 1.375-1.109 1.391-1.422");
}

.mxm_qjwik {
  stop-color: var(--svg-color--b9886a, #B9886A);
}

.nd-qy1bcv {
  stop-color: var(--svg-color--4a2d2a, #4A2D2A);
}

.nm-axxbxl {
  stop-color: var(--svg-color--d48670, #D48670);
}

.o_tl0nb_s {
  stop-color: var(--svg-color--b9886a, #B9886A);
  stop-opacity: 0;
}

.oagqsfbmn {
  stop-color: var(--svg-color--ffda9f, #FFDA9F);
}

.oqhwqxbpy {
  fill: var(--svg-color--cf6161, #CF6161);
  d: path("M16 24.914a.5.5 0 0 1 .5.478c.004.074.066.358.23.605c.152.23.342.363.62.34c.347-.027.487-.15.55-.237a.5.5 0 0 0 .087-.337a.5.5 0 0 1 .995-.104a1.5 1.5 0 0 1-.273 1.029c-.26.358-.687.6-1.279.646c-.67.054-1.137-.271-1.43-.64c-.293.369-.76.694-1.43.64c-.592-.047-1.02-.288-1.28-.646a1.5 1.5 0 0 1-.272-1.03a.5.5 0 0 1 .995.105a.5.5 0 0 0 .087.337c.063.087.203.21.55.238c.278.022.468-.11.62-.34a1.5 1.5 0 0 0 .23-.606a.496.496 0 0 1 .5-.478");
}

.os6fa4qvp {
  stop-color: var(--svg-color--fba27f, #FBA27F);
}

.pbdnt9b_j {
  stop-color: var(--svg-color--d53238, #D53238);
}

.q1w1asb3c {
  stop-color: var(--svg-color--d09f75, #D09F75);
}

.qbt1jcbzd {
  stroke-linecap: round;
  d: path("M18.484 25.484c.042.396-.156 1.05-1.093 1.125c-1.037.083-1.375-1.109-1.391-1.422");
}

.r5_lz_ber {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.484 15.531c-.458-.437-2.143-1.837-3.343-2.687");
}

.rbwmiccjh {
  d: path("M17.586 22.64c0 .488-.93 1.704-1.578 1.704c-.694 0-1.594-1.11-1.594-1.703c0-.594.703-.649 1.594-.649c.89 0 1.578.04 1.578.649");
}

.s3epqhb4u {
  cx: 25.141px;
  cy: 9.648px;
  r: 4.289px;
}

.s9hov9bap {
  stop-color: var(--svg-color--febd86, #FEBD86);
}

.tzase31ra {
  cx: 6.859px;
  cy: 9.648px;
  r: 4.289px;
}

.u_va_nbey {
  stop-color: var(--svg-color--fd9988, #FD9988);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.v74648q6x {
  stop-color: var(--svg-color--ff6ccb, #FF6CCB);
  stop-opacity: 0;
}

.yt54b-b_d {
  width: 1.484px;
  height: 3px;
  x: 19.242px;
  y: 17.984px;
  rx: 0.742px;
}

.zdu84_u1y {
  stop-color: var(--svg-color--cb976a, #CB976A);
  stop-opacity: 0;
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.zrku6vbzr {
  stop-color: var(--svg-color--625358, #625358);
}

</style>
