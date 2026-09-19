<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i98e0Ab)" class="o2jpiob7v"/><circle fill="url(#i0P1k2b)" class="o2jpiob7v"/><circle fill="url(#iBUhFHb)" class="o2jpiob7v"/><circle fill="url(#iWRNrtb)" class="o2jpiob7v"/><circle fill="url(#iPcfSub)" class="eiiu1cb9h"/><circle fill="url(#iayYAkb)" class="eiiu1cb9h"/><circle fill="url(#iTvxBvd)" class="eiiu1cb9h"/><circle fill="url(#ilGFuce)" class="eiiu1cb9h"/><circle fill="url(#iBdpRnw)" class="ckd_yic8s"/><circle fill="url(#iONpNvb)" class="ckd_yic8s"/><circle fill="url(#ie0xf8d)" class="ckd_yic8s"/><circle fill="url(#iIkTeQc)" class="r1m6pfx1f"/><circle fill="url(#iQcpDhe)" class="r1m6pfx1f"/><circle fill="url(#izZvUlG)" class="r1m6pfx1f"/><circle fill="url(#iuiU9Pb)" class="f_-qdf4xk"/><circle fill="url(#illW2Zb)" class="f_-qdf4xk"/><g filter="url(#iYmDMAk)" class="rv3sfkbnt"><path class="enethf1nm"/><path stroke="url(#ipMR9ed)" class="p284jjb3s"/><path stroke="url(#iHiW7vc)" class="p284jjb3s"/></g><g filter="url(#i7yMxhd)"><path stroke="url(#irBZBVD)" class="fm8ytclud"/></g><path class="auy8jb2th"/><path stroke="url(#i1SZVce)" class="vtxefibyh"/><path stroke="url(#iIXfdZc)" class="vtxefibyh"/><path stroke="url(#i5qmdUT)" class="vtxefibyh"/><path fill="url(#irMi6de)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#ix6CFab)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iemDlYd)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#i73xGbj)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iiKvEme)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iF3CiUc)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iIj8Wzb)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#ikhHQqb)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iGy0Wdb)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iLNU3Rd)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#ifnEKQc)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iN3iwWb)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iDSrexd)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#iThVvCe)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#i0wPiEc)" clip-rule="evenodd" class="yzl5sbb3g"/><path fill="url(#ixMvTIe)" clip-rule="evenodd" class="yzl5sbb3g"/><rect fill="url(#inF9tLd)" class="faonobcby"/><rect fill="url(#i6k0Aec)" class="faonobcby"/><rect fill="url(#itg1SCb)" class="faonobcby"/><g filter="url(#irnS1Md)"><path class="hnns0sbbh"/></g><g filter="url(#iKm8scc)"><path stroke="url(#is7aNCc)" class="tr0-mwb4m"/></g><defs><radialGradient id="i98e0Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.35937 -2.4922 4.2338 -.61052 11.094 20.617)" gradientUnits="userSpaceOnUse"><stop class="jm0thvepq"/><stop offset="1" class="egpy42_jm"/></radialGradient><radialGradient id="i0P1k2b" cx="0" cy="0" r="1" gradientTransform="matrix(.3711 2.21485 -1.7903 .29996 11.215 18.402)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="koob5zbbq"/><stop offset="1" class="vc1g_nbif"/></radialGradient><radialGradient id="iBUhFHb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42968 .46094 -.40898 -2.15579 12.281 19.078)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="c5e_evkdk"/><stop offset="1" class="ayqfy4bes"/></radialGradient><radialGradient id="iPcfSub" cx="0" cy="0" r="1" gradientTransform="matrix(-.35937 -2.4922 4.2338 -.61052 12.508 24.758)" gradientUnits="userSpaceOnUse"><stop class="jm0thvepq"/><stop offset="1" class="egpy42_jm"/></radialGradient><radialGradient id="iayYAkb" cx="0" cy="0" r="1" gradientTransform="matrix(.3711 2.21485 -1.7903 .29996 12.629 22.543)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="koob5zbbq"/><stop offset="1" class="vc1g_nbif"/></radialGradient><radialGradient id="iTvxBvd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -.51562 .4575 -1.88545 13.297 23.453)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c5e_evkdk"/><stop offset="1" class="ayqfy4bes"/></radialGradient><radialGradient id="iBdpRnw" cx="0" cy="0" r="1" gradientTransform="matrix(-.7344 -2.15234 4.6991 -1.60337 16.11 28)" gradientUnits="userSpaceOnUse"><stop class="jm0thvepq"/><stop offset="1" class="egpy42_jm"/></radialGradient><radialGradient id="iONpNvb" cx="0" cy="0" r="1" gradientTransform="matrix(.3711 2.21485 -1.7903 .29996 15.855 26.125)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="koob5zbbq"/><stop offset="1" class="vc1g_nbif"/></radialGradient><radialGradient id="ie0xf8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -.51562 .4575 -1.88545 16.523 27.035)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c5e_evkdk"/><stop offset="1" class="ayqfy4bes"/></radialGradient><radialGradient id="iIkTeQc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.84 20.668 7.114)scale(2.27418 4.96512)" gradientUnits="userSpaceOnUse"><stop class="jm0thvepq"/><stop offset="1" class="egpy42_jm"/></radialGradient><radialGradient id="iQcpDhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.23437 -1.80608 0 20.555 27.14)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="koob5zbbq"/><stop offset="1" class="vc1g_nbif"/></radialGradient><radialGradient id="izZvUlG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -.51562 .4575 -1.88545 21.023 28.008)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="c5e_evkdk"/><stop offset="1" class="ayqfy4bes"/></radialGradient><radialGradient id="iuiU9Pb" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 -1.20312 2.62673 1.19397 24.906 29.313)" gradientUnits="userSpaceOnUse"><stop class="jm0thvepq"/><stop offset="1" class="egpy42_jm"/></radialGradient><radialGradient id="illW2Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.23437 -1.80608 0 25.25 27.14)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="koob5zbbq"/><stop offset="1" class="vc1g_nbif"/></radialGradient><radialGradient id="ipMR9ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 .04687 -.12985 2.85667 7.883 7.383)" gradientUnits="userSpaceOnUse"><stop class="w47nohbxp"/><stop offset="1" class="j_sxcc1gh"/></radialGradient><radialGradient id="iHiW7vc" cx="0" cy="0" r="1" gradientTransform="rotate(-112.122 7.508 -2.084)scale(1.0373 3.80824)" gradientUnits="userSpaceOnUse"><stop class="re06zqbcv"/><stop offset=".434" class="k8lnd8q3t"/></radialGradient><radialGradient id="i1SZVce" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -1.96875 5.03589 2.0783 3.453 4.422)" gradientUnits="userSpaceOnUse"><stop class="re06zqbcv"/><stop offset=".379" class="k8lnd8q3t"/></radialGradient><radialGradient id="iIXfdZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44531 2.30469 0 6.078 7.86)" gradientUnits="userSpaceOnUse"><stop class="xxizlkkxt"/><stop offset="1" class="k2rrmci3e"/></radialGradient><radialGradient id="iemDlYd" cx="0" cy="0" r="1" gradientTransform="matrix(5.81249 -2.06253 3.97383 11.19875 11.063 22.031)" gradientUnits="userSpaceOnUse"><stop class="tqq-slbkc"/><stop offset="1" class="qeos7xbvn"/></radialGradient><radialGradient id="i73xGbj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.77734 6.9375 0 7.188 17.871)" gradientUnits="userSpaceOnUse"><stop class="tqq-slbkc"/><stop offset="1" class="qeos7xbvn"/></radialGradient><radialGradient id="iF3CiUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 -2.28125 15.14104 7.88163 16.563 27.813)" gradientUnits="userSpaceOnUse"><stop class="tzoke4b3n"/><stop offset=".452" class="b_vl9kbkj"/></radialGradient><radialGradient id="iIj8Wzb" cx="0" cy="0" r="1" gradientTransform="rotate(147.426 10.11 13.689)scale(8.01 6.32037)" gradientUnits="userSpaceOnUse"><stop class="yzi1ugcnw"/><stop offset="1" class="kinrycbfk"/></radialGradient><radialGradient id="ikhHQqb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9375 0 0 -11.1875 31.281 23.969)" gradientUnits="userSpaceOnUse"><stop class="yzi1ugcnw"/><stop offset="1" class="kinrycbfk"/></radialGradient><radialGradient id="iGy0Wdb" cx="0" cy="0" r="1" gradientTransform="rotate(143.973 10.556 15.993)scale(3.40037 2.73408)" gradientUnits="userSpaceOnUse"><stop class="tz50xac1s"/><stop offset="1" class="l64jabb5o"/></radialGradient><radialGradient id="iLNU3Rd" cx="0" cy="0" r="1" gradientTransform="rotate(45.277 -8.174 7.873)scale(2.28708 4.74509)" gradientUnits="userSpaceOnUse"><stop class="mgkm3miyn"/><stop offset=".729" class="vud691bxi"/></radialGradient><radialGradient id="ifnEKQc" cx="0" cy="0" r="1" gradientTransform="matrix(5.84375 -4.5 3.20505 4.16212 7.031 16.313)" gradientUnits="userSpaceOnUse"><stop class="z3amvr6nj"/><stop offset="1" class="ruc5tgb7p"/></radialGradient><radialGradient id="iN3iwWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.125 14.664 0 7.172 15.516)" gradientUnits="userSpaceOnUse"><stop class="tzoke4b3n"/><stop offset=".27" class="b_vl9kbkj"/></radialGradient><radialGradient id="iDSrexd" cx="0" cy="0" r="1" gradientTransform="matrix(-41.4062 0 0 -22.6875 43.313 12.531)" gradientUnits="userSpaceOnUse"><stop offset=".971" class="vud691bxi"/><stop offset="1" class="mgkm3miyn"/></radialGradient><radialGradient id="iThVvCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 -.5625 1.87428 6.87236 12.094 21.844)" gradientUnits="userSpaceOnUse"><stop class="mlep3abxl"/><stop offset="1" class="ko48i7b3q"/></radialGradient><radialGradient id="i0wPiEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 5 -7.47476 2.05557 5.188 4.781)" gradientUnits="userSpaceOnUse"><stop class="qhe0xdb3j"/><stop offset="1" class="htvv31bjh"/></radialGradient><radialGradient id="itg1SCb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.895 7.355 3.162)scale(1.75199 1.89375)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><linearGradient id="iWRNrtb" x1="11.664" x2="11.313" y1="18.852" y2="19.008" gradientUnits="userSpaceOnUse"><stop class="mj1vqmbxn"/><stop offset="1" class="ou6zwouhc"/></linearGradient><linearGradient id="ilGFuce" x1="13.078" x2="12.727" y1="22.992" y2="23.148" gradientUnits="userSpaceOnUse"><stop class="mj1vqmbxn"/><stop offset="1" class="ou6zwouhc"/></linearGradient><linearGradient id="irBZBVD" x1="11.969" x2="10.203" y1="3.391" y2="8.297" gradientUnits="userSpaceOnUse"><stop class="r27m-v5zk"/><stop offset="1" class="xq95qbc7x"/></linearGradient><linearGradient id="i5qmdUT" x1="1.859" x2="3.734" y1="2.969" y2="3.563" gradientUnits="userSpaceOnUse"><stop class="jqlqtu-pm"/><stop offset="1" class="hskzlyq5s"/></linearGradient><linearGradient id="irMi6de" x1="19.875" x2="17.063" y1="19.781" y2="24.969" gradientUnits="userSpaceOnUse"><stop class="fytzcub3i"/><stop offset="1" class="dv_3kkbwl"/></linearGradient><linearGradient id="ix6CFab" x1="19.688" x2="19.688" y1="28.719" y2="22.031" gradientUnits="userSpaceOnUse"><stop class="tqq-slbkc"/><stop offset="1" class="qeos7xbvn"/></linearGradient><linearGradient id="iiKvEme" x1="18.549" x2="18.549" y1="28.469" y2="27.609" gradientUnits="userSpaceOnUse"><stop class="tzoke4b3n"/><stop offset="1" class="b_vl9kbkj"/></linearGradient><linearGradient id="ixMvTIe" x1="16" x2="16" y1="7.402" y2="7.906" gradientUnits="userSpaceOnUse"><stop class="an491acad"/><stop offset="1" class="f9ayc3bup"/></linearGradient><linearGradient id="inF9tLd" x1="6.781" x2="5.908" y1="10.661" y2="10.661" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="i6k0Aec" x1="7.017" x2="7.017" y1="12.204" y2="10.778" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="is7aNCc" x1="3.703" x2="7.693" y1="2.797" y2="6.362" gradientUnits="userSpaceOnUse"><stop class="yuznc-v8u"/><stop offset="1" class="xq95qbc7x"/></linearGradient><filter id="iYmDMAk" width="5.541" height="7.119" x="7.625" y="2.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.607843 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6314"/></filter><filter id="i7yMxhd" width="5.391" height="6.969" x="7.625" y="2.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6314" stdDeviation=".25"/></filter><filter id="irnS1Md" width="20.313" height="20.563" x="5.313" y="5.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6314" stdDeviation="1.5"/></filter><filter id="iKm8scc" width="4.941" height="5.487" x="2.381" y="2.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6314" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bug" /></template>
<style>
.an491acad {
  stop-color: var(--svg-color--72dd98, #72DD98);
}

.auy8jb2th {
  stroke: var(--svg-color--2b8981, #2B8981);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.781 3.063c.275.078.82.32 1.35.57c.895.423 1.68 1.09 1.94 2.045c.181.666.304 1.49.304 2.416");
}

.ayqfy4bes {
  stop-color: var(--svg-color--799d9e, #799D9E);
}

.b_vl9kbkj {
  stop-color: var(--svg-color--b3a1ff, #B3A1FF);
  stop-opacity: 0;
}

.c5e_evkdk {
  stop-color: var(--svg-color--799d9e, #799D9E);
  stop-opacity: 0;
}

.ckd_yic8s {
  cx: 16px;
  cy: 26.934px;
  r: 1.406px;
}

.dv_3kkbwl {
  stop-color: var(--svg-color--52c8b0, #52C8B0);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.egpy42_jm {
  stop-color: var(--svg-color--1a7060, #1A7060);
}

.eiiu1cb9h {
  cx: 12.773px;
  cy: 23.352px;
  r: 1.406px;
}

.enethf1nm {
  stroke: var(--svg-color--298367, #298367);
  d: path("M12.266 3.125c-.615.11-2.235.883-3.032 2.14c-.55.868-.859 2.282-.859 3.329");
}

.f_-qdf4xk {
  cx: 25.195px;
  cy: 27.906px;
  r: 1.406px;
}

.f9ayc3bup {
  stop-color: var(--svg-color--72dd98, #72DD98);
  stop-opacity: 0;
}

.faonobcby {
  width: 1.508px;
  height: 2.992px;
  x: 5.273px;
  y: 9.352px;
  rx: 0.754px;
}

.fm8ytclud {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.266 3.125c-.615.11-2.235.883-3.032 2.14c-.55.868-.859 2.282-.859 3.329");
}

.ft5dv1b6b {
  fill: none;
}

.fytzcub3i {
  stop-color: var(--svg-color--4dd29a, #4DD29A);
}

.hnns0sbbh {
  stroke: var(--svg-color--72f7b4, #72F7B4);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.313 9.719h1.674a5 5 0 0 1 4.757 3.461l2.384 7.37a2.5 2.5 0 0 0 2.378 1.731h1.119");
}

.hskzlyq5s {
  stop-color: var(--svg-color--298272, #298272);
  stop-opacity: 0;
}

.htvv31bjh {
  stop-color: var(--svg-color--55e695, #55E695);
  stop-opacity: 0;
}

.j_sxcc1gh {
  stop-color: var(--svg-color--177b52, #177B52);
  stop-opacity: 0;
}

.jm0thvepq {
  stop-color: var(--svg-color--4c63a1, #4C63A1);
}

.jqlqtu-pm {
  stop-color: var(--svg-color--298272, #298272);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.k2rrmci3e {
  stop-color: var(--svg-color--1d835c, #1D835C);
  stop-opacity: 0;
}

.k8lnd8q3t {
  stop-color: var(--svg-color--557eab, #557EAB);
  stop-opacity: 0;
}

.kinrycbfk {
  stop-color: var(--svg-color--52cb7d, #52CB7D);
  stop-opacity: 0;
}

.ko48i7b3q {
  stop-color: var(--svg-color--8ad4bd, #8AD4BD);
  stop-opacity: 0;
}

.koob5zbbq {
  stop-color: var(--svg-color--8a78ca, #8A78CA);
  stop-opacity: 0;
}

.l64jabb5o {
  stop-color: var(--svg-color--69e09b, #69E09B);
  stop-opacity: 0;
}

.mgkm3miyn {
  stop-color: var(--svg-color--90f0b1, #90F0B1);
}

.mj1vqmbxn {
  stop-color: var(--svg-color--196a65, #196A65);
}

.mlep3abxl {
  stop-color: var(--svg-color--8cd5be, #8CD5BE);
}

.o2jpiob7v {
  cx: 11.359px;
  cy: 19.211px;
  r: 1.406px;
}

.ou6zwouhc {
  stop-color: var(--svg-color--196a65, #196A65);
  stop-opacity: 0;
}

.p284jjb3s {
  d: path("M12.266 3.125c-.615.11-2.235.883-3.032 2.14c-.55.868-.859 2.282-.859 3.329");
}

.qeos7xbvn {
  stop-color: var(--svg-color--5eb4bf, #5EB4BF);
  stop-opacity: 0;
}

.qhe0xdb3j {
  stop-color: var(--svg-color--55e695, #55E695);
}

.r1m6pfx1f {
  cx: 20.5px;
  cy: 27.906px;
  r: 1.406px;
}

.r27m-v5zk {
  stop-color: var(--svg-color--529b8a, #529B8A);
}

.re06zqbcv {
  stop-color: var(--svg-color--557eab, #557EAB);
}

.ruc5tgb7p {
  stop-color: var(--svg-color--6eb8db, #6EB8DB);
  stop-opacity: 0;
}

.rv3sfkbnt {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tqq-slbkc {
  stop-color: var(--svg-color--5eb4bf, #5EB4BF);
}

.tr0-mwb4m {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M3.031 2.89c.558.141 1.857.648 2.594 1.547c.737.9 1.005 2.136 1.047 2.641");
}

.tz50xac1s {
  stop-color: var(--svg-color--69e09b, #69E09B);
}

.tzoke4b3n {
  stop-color: var(--svg-color--b3a1ff, #B3A1FF);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.vc1g_nbif {
  stop-color: var(--svg-color--8a78ca, #8A78CA);
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vtxefibyh {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.781 3.063c.275.078.82.32 1.35.57c.895.423 1.68 1.09 1.94 2.045c.181.666.304 1.49.304 2.416");
}

.vud691bxi {
  stop-color: var(--svg-color--90f0b1, #90F0B1);
  stop-opacity: 0;
}

.w47nohbxp {
  stop-color: var(--svg-color--177b52, #177B52);
}

.xq95qbc7x {
  stop-color: var(--svg-color--529b8a, #529B8A);
  stop-opacity: 0;
}

.xxizlkkxt {
  stop-color: var(--svg-color--1d835c, #1D835C);
}

.yuznc-v8u {
  stop-color: var(--svg-color--569c8f, #569C8F);
}

.yzi1ugcnw {
  stop-color: var(--svg-color--52cb7d, #52CB7D);
}

.yzl5sbb3g {
  fill-rule: evenodd;
  d: path("M2.076 11.402a4 4 0 0 1 4-4h4.55a8 8 0 0 1 7.67 5.722l1.803 6.071a1.6 1.6 0 0 0 1.534 1.145h4.29a4 4 0 1 1 0 8H20.44a8 8 0 0 1-7.67-5.722l-1.761-6.062a1.6 1.6 0 0 0-1.536-1.154H6.076a4 4 0 0 1-4-4");
}

.z3amvr6nj {
  stop-color: var(--svg-color--6eb8db, #6EB8DB);
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
