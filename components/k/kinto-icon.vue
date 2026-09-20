<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":99};
const content = `<defs><linearGradient id="SVGqkb1odNS" x1="-.944%" x2="100.193%" y1="34.58%" y2="93.74%"><stop offset="0%" class="iyb4c2bxc"/><stop offset="100%" class="te4weebxk"/></linearGradient><linearGradient id="SVG340gCcUH" x1="50%" x2="50%" y1="-26.499%" y2="107.049%"><stop offset="0%" class="iyb4c2bxc"/><stop offset="19%" class="m0k2qfbts"/><stop offset="39%" class="t5ism__no"/><stop offset="61%" class="wt_w7sbza"/><stop offset="82%" class="lofeu9_jk"/><stop offset="100%" class="te4weebxk"/></linearGradient><linearGradient id="SVG95685drO" x1="-31.443%" x2="46.858%" y1="50%" y2="50%"><stop offset="0%" class="iyb4c2bxc"/><stop offset="11%" class="ckf74-b5b"/><stop offset="71%" class="zrb3ybcew"/><stop offset="100%" class="te4weebxk"/></linearGradient><linearGradient id="SVGIf82NccS" x1="50.002%" x2="50.002%" y1="-9.408%" y2="98.339%"><stop offset="0%" class="iyb4c2bxc"/><stop offset="61%" class="xmdd17bcg"/><stop offset="100%" class="te4weebxk"/></linearGradient><linearGradient id="SVGH3nDSc2c" x1="50%" x2="50%" y1=".98%" y2="101.601%"><stop offset="0%" class="f-u7lfbtp"/><stop offset="52%" class="nk4b3_bzp"/><stop offset="100%" class="adatm6x1c"/></linearGradient><linearGradient id="SVGAmVavdRD" x1="-25.306%" x2="74.694%" y1="50%" y2="50%"><stop offset="0%" class="chf2m-uiv"/><stop offset="6%" class="x6t4x4y0o"/><stop offset="21%" class="ohccwx4xf"/><stop offset="37%" class="clsyh6ryt"/><stop offset="55%" class="x7rvupbwm"/><stop offset="74%" class="xktjz6b3g"/><stop offset="100%" class="p2jiltb_m"/></linearGradient><linearGradient id="SVGD7XntbXM" x1="50%" x2="50%" y1="-34.375%" y2="144.062%"><stop offset="0%" class="iyb4c2bxc"/><stop offset="61%" class="wiz0qqbxr"/><stop offset="100%" class="te4weebxk"/></linearGradient><linearGradient id="SVGRpRP8dvW" x1="50.354%" x2="50.354%" y1="-109.762%" y2="69.444%"><stop offset="0%" class="iyb4c2bxc"/><stop offset="23%" class="mn3vy6b2u"/><stop offset="42%" class="i_2yu9wso"/><stop offset="60%" class="v0-2djbgp"/><stop offset="78%" class="ewn3ifb-y"/><stop offset="94%" class="e2is6y_1s"/><stop offset="100%" class="te4weebxk"/></linearGradient><linearGradient id="SVGHQ1CZ7Mw" x1="50.006%" x2="50.006%" y1="7.134%" y2="136.776%"><stop offset="0%" class="f-u7lfbtp"/><stop offset="52%" class="nk4b3_bzp"/><stop offset="100%" class="adatm6x1c"/></linearGradient><linearGradient id="SVG6HfzkD9D" x1="75.144%" x2="25.511%" y1="18.361%" y2="69.806%"><stop offset="0%" class="u60igh10b"/><stop offset="100%" class="u60igh10b"/></linearGradient><linearGradient id="SVGW1YEIeKu" x1="50%" x2="50%" y1="-28.81%" y2="101.905%"><stop offset="0%" class="chf2m-uiv"/><stop offset="6%" class="x6t4x4y0o"/><stop offset="21%" class="ohccwx4xf"/><stop offset="37%" class="clsyh6ryt"/><stop offset="55%" class="x7rvupbwm"/><stop offset="74%" class="xktjz6b3g"/><stop offset="100%" class="p2jiltb_m"/></linearGradient><linearGradient id="SVGD0S6p8uS" x1="50.001%" x2="50.001%" y1="-14.918%" y2="65.637%"><stop offset="0%" class="chf2m-uiv"/><stop offset="35%" class="a-bhsubmz"/><stop offset="100%" class="p2jiltb_m"/></linearGradient></defs><path fill="url(#SVGqkb1odNS)" class="abgc8j6yo"/><path fill="url(#SVG340gCcUH)" class="zi1jqkb6c"/><path fill="url(#SVG95685drO)" class="n8qlphbsh"/><path fill="url(#SVGIf82NccS)" class="ta-rzrame"/><path fill="url(#SVGH3nDSc2c)" class="yvms5ybyw"/><path fill="url(#SVGAmVavdRD)" class="epwv7sbsw"/><path fill="url(#SVGD7XntbXM)" class="z3grztbap"/><path fill="url(#SVGRpRP8dvW)" class="ynl47obag"/><path fill="url(#SVGHQ1CZ7Mw)" class="mxx7ntemr"/><path class="a6locfp4l"/><path fill="url(#SVG6HfzkD9D)" class="g2bj-nsvp"/><path fill="url(#SVGW1YEIeKu)" class="i57gfyain"/><path fill="url(#SVGD0S6p8uS)" class="zwv4d1bif"/><path class="jkg2xog_f"/><path class="k4a1v7bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:kinto-icon" /></template>
<style>
.a-bhsubmz {
  stop-color: var(--svg-color--ef961a, #ef961a);
}

.a6locfp4l {
  fill: var(--svg-color--e35702, #e35702);
  d: path("M199.302 60.836c-.855 4.155-1.222 8.676-.489 13.808c2.566 16.619 17.597 21.262 21.751 23.218h.122c6.721 0 12.953-2.444 18.208-6.232c-1.222-1.1-7.82-6.966-9.776-12.953c-6.232-18.94 7.943-24.562 8.798-24.928c-6.843-.122-29.205-.367-38.614 7.087");
  opacity: var(--svg-opacity--0-47, 0.47);
}

.abgc8j6yo {
  d: path("M107.41 97.862H58.533c-7.576-.245-16.008-.856-23.095-2.2c-3.544-.61-6.843-1.466-10.02-2.322c-1.589-.488-3.055-.855-4.521-1.344a159 159 0 0 1-7.943-2.933c-1.222-.488-2.322-1.1-3.3-1.588c-2.077-1.1-3.91-1.955-5.254-2.81a62 62 0 0 1-3.3-2.078L0 81.854s.367.244 1.222.733c.733.489 1.833 1.1 3.3 1.955c1.466.856 3.299 1.71 5.376 2.689a59 59 0 0 0 7.21 2.81c1.344.489 2.688.978 4.154 1.344c1.467.489 2.933.856 4.521 1.222c3.178.733 6.477 1.467 10.02 2.077c6.966 1.222 14.542 1.956 22.118 2.2c3.544.244 49.49.978 49.49.978");
}

.adatm6x1c {
  stop-color: var(--svg-color--e96c04, #e96c04);
}

.chf2m-uiv {
  stop-color: var(--svg-color--f7b425, #f7b425);
}

.ckf74-b5b {
  stop-color: var(--svg-color--fde373, #fde373);
}

.clsyh6ryt {
  stop-color: var(--svg-color--e6720e, #e6720e);
}

.e2is6y_1s {
  stop-color: var(--svg-color--f4ac28, #f4ac28);
}

.epwv7sbsw {
  d: path("M126.595 65.846c5.01 9.287 26.028 24.317 93.97 32.016c-53.767-6.966-78.817-17.108-93.97-32.016");
}

.ewn3ifb-y {
  stop-color: var(--svg-color--f8c347, #f8c347);
}

.f-u7lfbtp {
  stop-color: var(--svg-color--f9c32e, #f9c32e);
}

.g2bj-nsvp {
  d: path("M198.813 74.644c2.2 14.42 14.297 21.018 21.751 23.218c-4.277-2.078-15.274-8.799-15.152-20.407c.367-22.729 24.195-23.584 24.195-23.584c-10.02 0-22.85 1.1-30.427 6.965c-.978 4.277-1.222 8.676-.367 13.808");
}

.i_2yu9wso {
  stop-color: var(--svg-color--fce271, #fce271);
}

.i57gfyain {
  d: path("M114.01 97.862c-4.278-.123-15.275-1.467-21.14-10.265c3.176 6.477 9.53 10.265 16.74 10.265z");
}

.iyb4c2bxc {
  stop-color: var(--svg-color--feec7f, #feec7f);
}

.jkg2xog_f {
  fill: var(--svg-color--eb7808, #eb7808);
  d: path("M107.41 97.862H58.533c-1.466 0-2.322-.978-2.322-.978c1.344.122 51.2.978 51.2.978");
}

.k4a1v7bfe {
  fill: var(--svg-color--e35702, #e35702);
  d: path("M109.243 97.862H79.672c-3.422 0-5.132-.611-5.132-.611zm90.059-37.026c9.41-7.576 28.227-7.82 38.736-7.087c0 0-14.663-.367-24.806 1.833c-10.264 2.321-13.93 5.254-13.93 5.254");
}

.lofeu9_jk {
  stop-color: var(--svg-color--f6b93a, #f6b93a);
}

.m0k2qfbts {
  stop-color: var(--svg-color--fee97b, #fee97b);
}

.mn3vy6b2u {
  stop-color: var(--svg-color--feea7c, #feea7c);
}

.mxx7ntemr {
  d: path("M239.993 26.743c-1.222-.977-2.566-1.833-3.788-2.566c-1.344-.733-2.81-1.466-4.52-1.955c-3.178-1.222-6.477-1.833-9.654-2.2h-1.345c-5.743 0-11.853.245-19.062 3.055c.733 1.956 1.344 4.033 1.588 6.232c2.2 13.442-2.077 22.118-4.032 31.65c9.409-7.577 27.494-7.821 37.636-7.21h1.1q1.65 0 2.933-.367c9.898-2.566 10.509-17.596-.856-26.639");
}

.n8qlphbsh {
  d: path("M109.488 97.862c-10.142 0-18.452-8.188-18.452-18.33s8.432-19.796 18.33-19.796c19.429 0 22.117 17.597 52.422 26.273c19.673 5.62 58.776 11.853 58.776 11.853z");
}

.nk4b3_bzp {
  stop-color: var(--svg-color--f19819, #f19819);
}

.ohccwx4xf {
  stop-color: var(--svg-color--ec8816, #ec8816);
}

.p2jiltb_m {
  stop-color: var(--svg-color--df5504, #df5504);
}

.t5ism__no {
  stop-color: var(--svg-color--fcdf6e, #fcdf6e);
}

.ta-rzrame {
  d: path("M220.564 97.862c-3.91-1.589-19.185-6.599-21.75-23.218c-2.567-16.863 7.575-25.905 4.398-45.335c-2.81-17.107-17.107-25.539-31.404-28.471c-7.332-1.467-15.397-1.1-23.584 1.833c-22.973 8.309-30.671 34.459-26.394 52.422c3.543 14.786 18.207 29.327 53.4 35.559c30.06 5.254 32.504 5.743 45.334 7.21");
}

.te4weebxk {
  stop-color: var(--svg-color--f3a21b, #f3a21b);
}

.u60igh10b {
  stop-color: var(--svg-color--e66a09, #e66a09);
}

.v0-2djbgp {
  stop-color: var(--svg-color--fbd560, #fbd560);
}

.wiz0qqbxr {
  stop-color: var(--svg-color--f7bd40, #f7bd40);
}

.wt_w7sbza {
  stop-color: var(--svg-color--facf58, #facf58);
}

.x6t4x4y0o {
  stop-color: var(--svg-color--f3a620, #f3a620);
}

.x7rvupbwm {
  stop-color: var(--svg-color--e26208, #e26208);
}

.xktjz6b3g {
  stop-color: var(--svg-color--e05805, #e05805);
}

.xmdd17bcg {
  stop-color: var(--svg-color--f7bc3f, #f7bc3f);
}

.ynl47obag {
  d: path("M109.488 97.862c-5.255 0-10.265-2.444-13.686-5.988c-9.654-3.666-11.242-9.41-18.452-9.41c-4.032 0-7.332 3.911-7.332 7.944s3.3 7.454 7.332 7.454h44.48z");
}

.yvms5ybyw {
  d: path("M198.813 74.644c-2.566-16.863 7.576-25.905 4.4-45.335a46 46 0 0 0-1.59-6.232c-11.119 4.4-25.05 14.664-44.479 39.348c-41.424 52.422-62.93 26.883-64.153 25.172c3.055 5.988 9.287 10.265 16.497 10.265h111.198c-4.032-1.589-19.307-6.599-21.873-23.218");
}

.z3grztbap {
  d: path("M58.654 97.862c-2.077 0-3.666-1.711-3.666-3.788s1.711-4.033 3.666-4.033c3.91 0 4.521 4.277 10.631 5.988c3.91 1.1 11.731 1.71 11.731 1.71z");
}

.zi1jqkb6c {
  d: path("M256.001 58.392c0-19.551-16.13-38.37-35.315-38.37c-14.785 0-31.526 1.834-63.542 42.525c-41.424 52.3-62.93 26.76-64.153 25.05c3.055 5.988 9.165 10.265 16.375 10.265h111.32c19.43 0 35.315-19.918 35.315-39.47");
}

.zrb3ybcew {
  stop-color: var(--svg-color--f6b434, #f6b434);
}

.zwv4d1bif {
  d: path("M197.47 74.644c-2.567-16.863 8.43-25.905 5.254-45.335c-.367-2.199-1.222-6.232-1.222-6.232c.733 1.956 1.344 4.033 1.588 6.232c3.177 19.43-6.965 28.472-4.399 45.335c2.566 16.619 17.84 21.629 21.751 23.218c.122 0-20.162-4.888-22.973-23.218");
}

</style>
