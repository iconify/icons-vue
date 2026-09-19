<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVfdVTd)"><path class="anjwbxvnd"/></g><path fill="url(#iIU6X5c)" class="l-dxkbw1b"/><path fill="url(#i7lytDb)" class="l-dxkbw1b"/><path fill="url(#i150D6b)" class="l-dxkbw1b"/><path fill="url(#i4rY3Zd)" class="l-dxkbw1b"/><circle fill="url(#idH3AKd)" class="kce5cpbfh"/><path fill="url(#iIeGu9d)" class="t8cgycben"/><path fill="url(#iNvsKLP)" class="t8cgycben"/><path fill="url(#iZzVgBd)" class="t8cgycben"/><g filter="url(#i91ywWm)"><path fill="url(#iJANxoc)" class="vuyj1io3j"/><path fill="url(#i3ZfBVc)" class="vuyj1io3j"/><path fill="url(#iu8XQNd)" class="vuyj1io3j"/></g><g filter="url(#ikIrTpc)"><path stroke="url(#ivLf1Tc)" class="cm_1uxb7b"/></g><rect fill="url(#iP6hlfd)" class="c-cvxsbli"/><rect fill="url(#iXOSRge)" class="c-cvxsbli"/><rect fill="url(#iKsDRke)" class="c-cvxsbli"/><path fill="url(#i5QNx2c)" class="b4i265bkl"/><g filter="url(#ivzONVb)"><path fill="url(#iEf8Ztg)" class="oynb-qtes"/></g><defs><radialGradient id="i7lytDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09436 7.34375 -3.76675 .56132 10.406 15.656)" gradientUnits="userSpaceOnUse"><stop offset=".021" class="ejs1v1zqg"/><stop offset="1" class="buhpqxbum"/></radialGradient><radialGradient id="i150D6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.0625 .85938 0 13.468 17.453)" gradientUnits="userSpaceOnUse"><stop class="k_f5accqw"/><stop offset="1" class="fpxhk4sbg"/></radialGradient><radialGradient id="i4rY3Zd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87441 1.23133 -2.24067 -1.59119 9.804 10.624)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="zx9lv7b4j"/><stop offset="1" class="hu_c5-byk"/></radialGradient><radialGradient id="idH3AKd" cx="0" cy="0" r="1" gradientTransform="rotate(140.981 10.078 13.894)scale(9.33157)" gradientUnits="userSpaceOnUse"><stop class="pb0dz8b4w"/><stop offset="1" class="rlmsjvxgj"/></radialGradient><radialGradient id="iNvsKLP" cx="0" cy="0" r="1" gradientTransform="rotate(-30.196 21.495 -14.268)scale(7.083 12.6242)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="q-vl8pz-x"/><stop offset="1" class="qub1xs4hw"/></radialGradient><radialGradient id="iZzVgBd" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 7.792 .644)scale(5.48766 7.79014)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="i9hk8yb6v"/><stop offset=".961" class="vvvb55bdb"/></radialGradient><radialGradient id="i3ZfBVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.81251 1.21874 -2.41974 3.59865 10.718 20.156)" gradientUnits="userSpaceOnUse"><stop class="ab46_nbbb"/><stop offset="1" class="z6loa81nb"/></radialGradient><radialGradient id="iu8XQNd" cx="0" cy="0" r="1" gradientTransform="rotate(143.344 4.777 13.53)scale(1.67501 9.91772)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="xmx26ib1g"/><stop offset="1" class="qlhsa2bsm"/></radialGradient><radialGradient id="iXOSRge" cx="0" cy="0" r="1" gradientTransform="rotate(137.353 5.226 7.046)scale(1.61445 1.40902)" gradientUnits="userSpaceOnUse"><stop class="k9xxlac3w"/><stop offset="1" class="t-xr9itjq"/></radialGradient><radialGradient id="i5QNx2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21213 1.47114 0 11.492 7.08)" gradientUnits="userSpaceOnUse"><stop class="j0eir_bfh"/><stop offset="1" class="s54ej3srj"/></radialGradient><linearGradient id="iIU6X5c" x1="16" x2="16" y1="29.969" y2="27.031" gradientUnits="userSpaceOnUse"><stop class="topp6gzri"/><stop offset="1" class="gqstt692v"/></linearGradient><linearGradient id="iIeGu9d" x1="8.406" x2="16.843" y1="8.781" y2="6.781" gradientUnits="userSpaceOnUse"><stop class="gw_bjo7wd"/><stop offset="1" class="pbw6czb-j"/></linearGradient><linearGradient id="iJANxoc" x1="13.421" x2="13.421" y1="18.688" y2="26.149" gradientUnits="userSpaceOnUse"><stop class="a4xw1tbvv"/><stop offset="1" class="qdu1srbuh"/></linearGradient><linearGradient id="ivLf1Tc" x1="14.812" x2="11.004" y1="6.717" y2="5.04" gradientUnits="userSpaceOnUse"><stop class="y2m_-ackd"/><stop offset="1" class="ua1yppbot"/></linearGradient><linearGradient id="iP6hlfd" x1="8.687" x2="14.437" y1="9.406" y2="9.406" gradientUnits="userSpaceOnUse"><stop class="gw_bjo7wd"/><stop offset="1" class="wu7fqpb_a"/></linearGradient><linearGradient id="iKsDRke" x1="10.738" x2="10.738" y1="11.624" y2="8.626" gradientUnits="userSpaceOnUse"><stop class="od74409ye"/><stop offset="1" class="crsstob6d"/></linearGradient><linearGradient id="iEf8Ztg" x1="10.39" x2="9.856" y1="5.906" y2="7.137" gradientUnits="userSpaceOnUse"><stop class="dx0v9gnru"/><stop offset="1" class="b3b364b-u"/></linearGradient><filter id="iVfdVTd" width="28.811" height="22.656" x="2.094" y="6.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.541176 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4291"/></filter><filter id="i91ywWm" width="15.781" height="10.719" x="5.546" y="17.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4291" stdDeviation=".5"/></filter><filter id="ikIrTpc" width="6.851" height="7.657" x="9.699" y="2.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4291" stdDeviation=".5"/></filter><filter id="ivzONVb" width="2.391" height="2.502" x="8.906" y="4.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4291" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flexed-biceps" /></template>
<style>
.a4xw1tbvv {
  stop-color: var(--svg-color--ffca40, #FFCA40);
}

.ab46_nbbb {
  stop-color: var(--svg-color--ffe060, #FFE060);
}

.anjwbxvnd {
  fill: var(--svg-color--ffb336, #FFB336);
  d: path("M7.968 7.844h-1.64L2.577 19.03C.843 24.938 3.977 29 8.797 29h12.827a8.391 8.391 0 1 0-8.01-11.221a.24.24 0 0 1-.223.159a.23.23 0 0 1-.207-.126z");
}

.b3b364b-u {
  stop-color: var(--svg-color--ffd863, #FFD863);
  stop-opacity: 0;
}

.b4i265bkl {
  d: path("M10.653 5.009L10 6.929h3.75z");
}

.buhpqxbum {
  stop-color: var(--svg-color--ffea5e, #FFEA5E);
  stop-opacity: 0;
}

.c-cvxsbli {
  width: 8.914px;
  height: 4.07px;
  x: 6.281px;
  y: 6.898px;
  rx: 2.035px;
}

.cm_1uxb7b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.449 4.268l2.383.984c.402.148.91.68.964 1.46c.058.823-.524 1.485-.89 1.712");
}

.crsstob6d {
  stop-color: var(--svg-color--f0960f, #F0960F);
  stop-opacity: 0;
}

.dx0v9gnru {
  stop-color: var(--svg-color--ffd863, #FFD863);
}

.ejs1v1zqg {
  stop-color: var(--svg-color--ffea5e, #FFEA5E);
}

.fpxhk4sbg {
  stop-color: var(--svg-color--e49b48, #E49B48);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gqstt692v {
  stop-color: var(--svg-color--d27a7f, #D27A7F);
  stop-opacity: 0;
}

.gw_bjo7wd {
  stop-color: var(--svg-color--e9a73e, #E9A73E);
}

.hu_c5-byk {
  stop-color: var(--svg-color--d4934e, #D4934E);
  stop-opacity: 0;
}

.i9hk8yb6v {
  stop-color: var(--svg-color--d0a659, #D0A659);
  stop-opacity: 0;
}

.j0eir_bfh {
  stop-color: var(--svg-color--a55812, #A55812);
}

.k_f5accqw {
  stop-color: var(--svg-color--e49b48, #E49B48);
}

.k9xxlac3w {
  stop-color: var(--svg-color--ffeb64, #FFEB64);
}

.kce5cpbfh {
  cx: 21.515px;
  cy: 20.609px;
  r: 8.391px;
}

.l-dxkbw1b {
  d: path("M7.968 7.844h-1.64L2.577 19.03C.843 24.938 3.977 29 8.797 29h12.827a8.391 8.391 0 1 0-8.01-11.221a.24.24 0 0 1-.223.159a.23.23 0 0 1-.207-.126z");
}

.od74409ye {
  stop-color: var(--svg-color--f0960f, #F0960F);
}

.oynb-qtes {
  d: path("m9.406 5.433l1.39.891v.612h-1.39z");
}

.pb0dz8b4w {
  stop-color: var(--svg-color--ffed59, #FFED59);
}

.pbw6czb-j {
  stop-color: var(--svg-color--ffcc30, #FFCC30);
}

.q-vl8pz-x {
  stop-color: var(--svg-color--ffdd47, #FFDD47);
  stop-opacity: 0;
}

.qdu1srbuh {
  stop-color: var(--svg-color--ffca40, #FFCA40);
  stop-opacity: 0;
}

.qlhsa2bsm {
  stop-color: var(--svg-color--f99d45, #F99D45);
  stop-opacity: 0;
}

.qub1xs4hw {
  stop-color: var(--svg-color--ffdd47, #FFDD47);
}

.rlmsjvxgj {
  stop-color: var(--svg-color--ffed59, #FFED59);
  stop-opacity: 0;
}

.s54ej3srj {
  stop-color: var(--svg-color--f29b05, #F29B05);
  stop-opacity: 0;
}

.t-xr9itjq {
  stop-color: var(--svg-color--ffeb64, #FFEB64);
  stop-opacity: 0;
}

.t8cgycben {
  d: path("M7.32 5.039L6.296 7.934l.499.962a2.04 2.04 0 0 0 1.817 1.12h4.941a2.5 2.5 0 0 0 2.315-1.557l.087-.213a3.5 3.5 0 0 0-1.814-4.517l-1.774-.752c-2.172-.805-4.283.047-5.047 2.062");
}

.topp6gzri {
  stop-color: var(--svg-color--d27a7f, #D27A7F);
}

.ua1yppbot {
  stop-color: var(--svg-color--ffed67, #FFED67);
  stop-opacity: 0;
}

.vuyj1io3j {
  d: path("m13.171 18.688l-6.625 8.718h13.782l-6.532-8.718z");
}

.vvvb55bdb {
  stop-color: var(--svg-color--d0a659, #D0A659);
}

.wu7fqpb_a {
  stop-color: var(--svg-color--ffc524, #FFC524);
}

.xmx26ib1g {
  stop-color: var(--svg-color--f99d45, #F99D45);
}

.y2m_-ackd {
  stop-color: var(--svg-color--ffed67, #FFED67);
}

.z6loa81nb {
  stop-color: var(--svg-color--ffe060, #FFE060);
  stop-opacity: 0;
}

.zx9lv7b4j {
  stop-color: var(--svg-color--d4934e, #D4934E);
}

</style>
