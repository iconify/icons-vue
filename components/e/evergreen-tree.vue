<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l9v5qkllj"/><path fill="url(#iMVVUhd)" class="hekqtuynf"/><path fill="url(#i8XRZdj)" class="hekqtuynf"/><path fill="url(#iojEare)" class="hekqtuynf"/><path fill="url(#is6Nwca)" class="hekqtuynf"/><path fill="url(#iNpqVvb)" class="hekqtuynf"/><path fill="url(#ijx3h8d)" class="hekqtuynf"/><g filter="url(#iRkvk8H)"><path fill="url(#idPTknc)" class="ve_y3fy3v"/><path fill="url(#iLAvcBb)" class="ve_y3fy3v"/><path fill="url(#iYbJVid)" class="ve_y3fy3v"/><path fill="url(#iyJVJWb)" class="ve_y3fy3v"/></g><path fill="url(#izoB5qB)" class="ve_y3fy3v"/><path fill="url(#iYwbWne)" class="u9pxigvpi"/><path fill="url(#iKZfZjZ)" class="u9pxigvpi"/><path fill="url(#iarwaxy)" class="u9pxigvpi"/><path fill="url(#i5TqXOL)" class="u9pxigvpi"/><path fill="url(#iPcjZqe)" class="u9pxigvpi"/><path fill="url(#iswYhcb)" class="u9pxigvpi"/><path fill="url(#ip43fMe)" class="u9pxigvpi"/><path fill="url(#ihV1Afc)" class="k5l7nvg0w"/><path fill="url(#iBGQpKO)" class="k5l7nvg0w"/><path fill="url(#iHuoMde)" class="k5l7nvg0w"/><path fill="url(#iFM2Lyb)" class="k5l7nvg0w"/><path fill="url(#iht7U3d)" class="k5l7nvg0w"/><path fill="url(#irJbMec)" class="k5l7nvg0w"/><path fill="url(#itOEw0c)" class="k5l7nvg0w"/><g filter="url(#igs47bd)"><ellipse fill="url(#i7OlO8d)" class="l3xhgs9ol"/><ellipse fill="url(#iwX7dlM)" class="l3xhgs9ol"/></g><g filter="url(#iNyIzue)"><ellipse fill="url(#iGbmd5c)" class="rdlu9ccuf"/><ellipse fill="url(#ie4L9Rb)" class="rdlu9ccuf"/></g><g filter="url(#iuLZelc)"><path fill="url(#iKy95Hd)" class="pdzdjuvfb"/></g><g filter="url(#i9F0Cib)"><path fill="url(#izqBqKb)" class="wa270cc6w"/></g><defs><radialGradient id="iMVVUhd" cx="0" cy="0" r="1" gradientTransform="rotate(70.328 -9.8 25.224)scale(3.03988 1.95488)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="xrivgk6fv"/><stop offset="1" class="ueq16fb8c"/></radialGradient><radialGradient id="i8XRZdj" cx="0" cy="0" r="1" gradientTransform="rotate(102.416 -2.632 18.885)scale(5.35131 2.99668)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="xrivgk6fv"/><stop offset=".967" class="ueq16fb8c"/></radialGradient><radialGradient id="idPTknc" cx="0" cy="0" r="1" gradientTransform="matrix(-16.4585 0 0 -9.1748 24.294 23.078)" gradientUnits="userSpaceOnUse"><stop class="fzobf6bft"/><stop offset="1" class="f001zybfp"/></radialGradient><radialGradient id="iLAvcBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.01113 -22.6983 0 16.023 18.067)" gradientUnits="userSpaceOnUse"><stop class="u88cwb8jd"/><stop offset="1" class="ba0kdvpfm"/></radialGradient><radialGradient id="iYbJVid" cx="0" cy="0" r="1" gradientTransform="matrix(10.0406 0 0 1.58933 10.317 26.898)" gradientUnits="userSpaceOnUse"><stop class="n0mn_dy-c"/><stop offset="1" class="ml9jtga1m"/></radialGradient><radialGradient id="izoB5qB" cx="0" cy="0" r="1" gradientTransform="rotate(173.698 7.753 9.904)scale(9.53308 2.17183)" gradientUnits="userSpaceOnUse"><stop class="n986iwbda"/><stop offset="1" class="ojvvjhb0k"/></radialGradient><radialGradient id="iYwbWne" cx="0" cy="0" r="1" gradientTransform="matrix(-11.1275 0 0 -6.54807 21.6 16.531)" gradientUnits="userSpaceOnUse"><stop class="fzobf6bft"/><stop offset="1" class="f001zybfp"/></radialGradient><radialGradient id="iarwaxy" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.57645 -15.3461 0 16.008 12.955)" gradientUnits="userSpaceOnUse"><stop class="u88cwb8jd"/><stop offset="1" class="ba0kdvpfm"/></radialGradient><radialGradient id="i5TqXOL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.80124 9.00368 0 16.008 19.646)" gradientUnits="userSpaceOnUse"><stop class="z9ejxxonq"/><stop offset="1" class="uh3hbsbrq"/></radialGradient><radialGradient id="iPcjZqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.84375 7.43741 0 16.008 19.398)" gradientUnits="userSpaceOnUse"><stop class="sqvqvi0de"/><stop offset="1" class="tjoej6pls"/></radialGradient><radialGradient id="iswYhcb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.816 12.329 8.276)scale(12.5421 6.6444)" gradientUnits="userSpaceOnUse"><stop offset=".871" class="o1d-5wbgb"/><stop offset="1" class="nuknrdb6c"/></radialGradient><radialGradient id="ip43fMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07813 -7.3989 0 15.07 13.273)" gradientUnits="userSpaceOnUse"><stop class="sqvqvi0de"/><stop offset="1" class="tjoej6pls"/></radialGradient><radialGradient id="iBGQpKO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.8125 8.0625 0 16.023 14.117)" gradientUnits="userSpaceOnUse"><stop class="mfthzox2b"/><stop offset="1" class="i07xb9bnx"/></radialGradient><radialGradient id="iHuoMde" cx="0" cy="0" r="1" gradientTransform="matrix(3.89304 -.78575 .934 4.62756 11.516 13.425)" gradientUnits="userSpaceOnUse"><stop class="xyjj9wbjf"/><stop offset="1" class="xxmwjyb0l"/></radialGradient><radialGradient id="iht7U3d" cx="0" cy="0" r="1" gradientTransform="matrix(.86717 -.95535 1.85992 1.68825 12.4 14.256)" gradientUnits="userSpaceOnUse"><stop class="yby9906zi"/><stop offset="1" class="jypwbywvm"/></radialGradient><radialGradient id="irJbMec" cx="0" cy="0" r="1" gradientTransform="matrix(4.37193 -.38214 .0865 .98966 11.651 14.315)" gradientUnits="userSpaceOnUse"><stop class="sqvqvi0de"/><stop offset="1" class="tjoej6pls"/></radialGradient><radialGradient id="i7OlO8d" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74151 0 0 -1.76903 24.489 23.078)" gradientUnits="userSpaceOnUse"><stop class="h1olwgbiv"/><stop offset="1" class="npo2z7pct"/></radialGradient><radialGradient id="iwX7dlM" cx="0" cy="0" r="1" gradientTransform="matrix(13.1471 0 0 4.03716 10.71 23.078)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="d3zqjfbhp"/><stop offset="1" class="c0q7qjbdq"/></radialGradient><radialGradient id="iGbmd5c" cx="0" cy="0" r="1" gradientTransform="matrix(-7.72205 0 0 -1.08151 21.58 16.531)" gradientUnits="userSpaceOnUse"><stop class="h1olwgbiv"/><stop offset="1" class="npo2z7pct"/></radialGradient><radialGradient id="ie4L9Rb" cx="0" cy="0" r="1" gradientTransform="matrix(10.4217 0 0 2.46816 10.657 16.531)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="d3zqjfbhp"/><stop offset="1" class="c0q7qjbdq"/></radialGradient><linearGradient id="iojEare" x1="16.023" x2="15.875" y1="30.076" y2="28.858" gradientUnits="userSpaceOnUse"><stop class="h8g7ummha"/><stop offset="1" class="i44ymih6r"/></linearGradient><linearGradient id="is6Nwca" x1="11.56" x2="12.983" y1="27.798" y2="27.961" gradientUnits="userSpaceOnUse"><stop class="ftjuge8hl"/><stop offset="1" class="b0qt7bheb"/></linearGradient><linearGradient id="iNpqVvb" x1="20.179" x2="19.282" y1="27.603" y2="27.961" gradientUnits="userSpaceOnUse"><stop class="ftjuge8hl"/><stop offset="1" class="b0qt7bheb"/></linearGradient><linearGradient id="ijx3h8d" x1="16.023" x2="16.023" y1="29.722" y2="30.024" gradientUnits="userSpaceOnUse"><stop class="fcsd2-b1c"/><stop offset="1" class="bif2ztb0a"/></linearGradient><linearGradient id="iyJVJWb" x1="17.114" x2="17.114" y1="27.175" y2="26.434" gradientUnits="userSpaceOnUse"><stop class="n0mn_dy-c"/><stop offset="1" class="ml9jtga1m"/></linearGradient><linearGradient id="iKZfZjZ" x1="11.094" x2="17.019" y1="16.531" y2="16.531" gradientUnits="userSpaceOnUse"><stop class="q5e4s7g5t"/><stop offset="1" class="n5aruue2y"/></linearGradient><linearGradient id="ihV1Afc" x1="14.648" x2="19.398" y1="11.049" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="gi1j30bmu"/><stop offset="1" class="e2kpw2zoc"/></linearGradient><linearGradient id="iFM2Lyb" x1="11.96" x2="13.606" y1="10.098" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="xyjj9wbjf"/><stop offset="1" class="xxmwjyb0l"/></linearGradient><linearGradient id="itOEw0c" x1="16.023" x2="16.023" y1="6.39" y2="7.574" gradientUnits="userSpaceOnUse"><stop class="jtze1414o"/><stop offset="1" class="tss5i0b3g"/></linearGradient><linearGradient id="iKy95Hd" x1="18.663" x2="15.326" y1="12.277" y2="12.277" gradientUnits="userSpaceOnUse"><stop class="e84bsccgx"/><stop offset="1" class="ayil1ivkq"/></linearGradient><linearGradient id="izqBqKb" x1="18.553" x2="16.61" y1="9.842" y2="10.362" gradientUnits="userSpaceOnUse"><stop class="gm5xec7wv"/><stop offset="1" class="gctnlrb3i"/></linearGradient><filter id="iRkvk8H" width="18.153" height="7.641" x="7.072" y="19.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.6 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7648"/></filter><filter id="igs47bd" width="15.193" height="9.188" x="10.827" y="18.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7648" stdDeviation="1"/></filter><filter id="iNyIzue" width="12.873" height="7.172" x="10.335" y="12.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7648" stdDeviation="1"/></filter><filter id="iuLZelc" width="6.273" height="2.773" x="14.109" y="10.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7648" stdDeviation=".5"/></filter><filter id="i9F0Cib" width="5.153" height="7.673" x="15.6" y="5.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7648" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:evergreen-tree" /></template>
<style>
.ayil1ivkq {
  stop-color: var(--svg-color--9dd573, #9DD573);
  stop-opacity: 0;
}

.b0qt7bheb {
  stop-color: var(--svg-color--826c6a, #826C6A);
  stop-opacity: 0;
}

.ba0kdvpfm {
  stop-color: var(--svg-color--57a22c, #57A22C);
  stop-opacity: 0;
}

.bif2ztb0a {
  stop-color: var(--svg-color--8f5790, #8F5790);
}

.c0q7qjbdq {
  stop-color: var(--svg-color--9fdf6b, #9FDF6B);
}

.d3zqjfbhp {
  stop-color: var(--svg-color--9fdf6b, #9FDF6B);
  stop-opacity: 0;
}

.e2kpw2zoc {
  stop-color: var(--svg-color--7fc43a, #7FC43A);
}

.e84bsccgx {
  stop-color: var(--svg-color--9dd573, #9DD573);
}

.f001zybfp {
  stop-color: var(--svg-color--52915c, #52915C);
}

.fcsd2-b1c {
  stop-color: var(--svg-color--8f5790, #8F5790);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftjuge8hl {
  stop-color: var(--svg-color--826c6a, #826C6A);
}

.fzobf6bft {
  stop-color: var(--svg-color--80c156, #80C156);
}

.gctnlrb3i {
  stop-color: var(--svg-color--9ad869, #9AD869);
  stop-opacity: 0;
}

.gi1j30bmu {
  stop-color: var(--svg-color--5a9d57, #5A9D57);
}

.gm5xec7wv {
  stop-color: var(--svg-color--9ad869, #9AD869);
}

.h1olwgbiv {
  stop-color: var(--svg-color--a2e070, #A2E070);
}

.h8g7ummha {
  stop-color: var(--svg-color--7b4064, #7B4064);
}

.hekqtuynf {
  d: path("M19.18 29.96h-6.31c-.536 0-.943-.608-.825-1.242l.514-2.757h6.933l.515 2.757c.107.634-.29 1.243-.825 1.243");
}

.i07xb9bnx {
  stop-color: var(--svg-color--3b9017, #3B9017);
  stop-opacity: 0;
}

.i44ymih6r {
  stop-color: var(--svg-color--7b4064, #7B4064);
  stop-opacity: 0;
}

.jtze1414o {
  stop-color: var(--svg-color--639e52, #639E52);
}

.jypwbywvm {
  stop-color: var(--svg-color--637374, #637374);
  stop-opacity: 0;
}

.k5l7nvg0w {
  d: path("M14.708 7.169a1.5 1.5 0 0 1 2.63 0l2.586 4.71a1.3 1.3 0 0 1-1.14 1.926h-5.522a1.3 1.3 0 0 1-1.14-1.926z");
}

.l3xhgs9ol {
  cx: 18.424px;
  cy: 23.078px;
  rx: 5.597px;
  ry: 2.594px;
}

.l9v5qkllj {
  fill: var(--svg-color--795556, #795556);
  d: path("M19.18 29.96h-6.31c-.536 0-.943-.608-.825-1.242l.514-2.757h6.933l.515 2.757c.107.634-.29 1.243-.825 1.243");
}

.mfthzox2b {
  stop-color: var(--svg-color--3b9017, #3B9017);
}

.ml9jtga1m {
  stop-color: var(--svg-color--7f779b, #7F779B);
  stop-opacity: 0;
}

.n0mn_dy-c {
  stop-color: var(--svg-color--7f779b, #7F779B);
}

.n5aruue2y {
  stop-color: var(--svg-color--529257, #529257);
  stop-opacity: 0;
}

.n986iwbda {
  stop-color: var(--svg-color--105b0d, #105B0D);
}

.npo2z7pct {
  stop-color: var(--svg-color--a2e070, #A2E070);
  stop-opacity: 0;
}

.nuknrdb6c {
  stop-color: var(--svg-color--75947d, #75947D);
}

.o1d-5wbgb {
  stop-color: var(--svg-color--75947d, #75947D);
  stop-opacity: 0;
}

.ojvvjhb0k {
  stop-color: var(--svg-color--105b0d, #105B0D);
  stop-opacity: 0;
}

.pdzdjuvfb {
  d: path("M15.11 12.283c.69-.313 2.513-.735 4.273.078c-.758.245-2.673.572-4.274-.078");
}

.q5e4s7g5t {
  stop-color: var(--svg-color--529257, #529257);
}

.rdlu9ccuf {
  cx: 16.772px;
  cy: 16.531px;
  rx: 4.436px;
  ry: 1.586px;
}

.sqvqvi0de {
  stop-color: var(--svg-color--15600b, #15600B);
}

.tjoej6pls {
  stop-color: var(--svg-color--15600b, #15600B);
  stop-opacity: 0;
}

.tss5i0b3g {
  stop-color: var(--svg-color--70a960, #70A960);
  stop-opacity: 0;
}

.u88cwb8jd {
  stop-color: var(--svg-color--57a22c, #57A22C);
}

.u9pxigvpi {
  d: path("M13.65 13.804c-.996 0-1.85.348-2.564 1.18l-.084.11c-.421.545-.876 1.136-1.041 2.183c-.07 1.332.583 1.98 1.687 1.98h8.72c1.104 0 1.757-.648 1.687-1.98c-.165-1.047-.62-1.638-1.041-2.184l-.084-.109c-.715-.832-1.568-1.18-2.564-1.18z");
}

.ueq16fb8c {
  stop-color: var(--svg-color--5f2f2e, #5F2F2E);
  stop-opacity: 0;
}

.uh3hbsbrq {
  stop-color: var(--svg-color--479820, #479820);
  stop-opacity: 0;
}

.ve_y3fy3v {
  d: path("M12.378 19.258h7.29c2.09 0 2.937.303 4.035 1.468c.68.81 1.344 1.68 1.266 3.282c-.094 1.921-1.203 2.89-3.5 2.89H10.578c-2.297 0-3.406-.969-3.5-2.89c-.078-1.601.586-2.472 1.266-3.282c1.098-1.165 1.945-1.468 4.034-1.468");
}

.wa270cc6w {
  d: path("M16.6 6.871v5.674h3.152z");
}

.xrivgk6fv {
  stop-color: var(--svg-color--5f2f2e, #5F2F2E);
}

.xxmwjyb0l {
  stop-color: var(--svg-color--608371, #608371);
  stop-opacity: 0;
}

.xyjj9wbjf {
  stop-color: var(--svg-color--608371, #608371);
}

.yby9906zi {
  stop-color: var(--svg-color--637374, #637374);
}

.z9ejxxonq {
  stop-color: var(--svg-color--479820, #479820);
}

</style>
