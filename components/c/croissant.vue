<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ojbkehb_n"/><path fill="url(#ipWT76d)" class="j4jxsqb3p"/><g filter="url(#iI8g0sb)"><path fill="url(#iyBurSd)" class="fmk28gu0s"/></g><path fill="url(#iOWL6Tb)" class="my5mnzbzp"/><path fill="url(#iQS6dSc)" class="my5mnzbzp"/><path fill="url(#iuCmTfp)" class="my5mnzbzp"/><path fill="url(#idGiMje)" class="my5mnzbzp"/><path fill="url(#ixHGzyd)" class="my5mnzbzp"/><g filter="url(#i9woDxd)"><path fill="url(#iHa5pCc)" class="rd9b7_x3c"/></g><path fill="url(#iSJ7iWd)" class="xosh3wm9d"/><path fill="url(#irjtGkd)" class="xosh3wm9d"/><g filter="url(#idJUsod)"><path fill="url(#i0btAyn)" class="u43k-jtdg"/><path fill="url(#izttPnb)" class="u43k-jtdg"/></g><path class="u34qowbxt"/><path fill="url(#iAkfqQc)" class="aphs44eyb"/><path fill="url(#i3MROad)" class="aphs44eyb"/><path fill="url(#iyVivBe)" class="aphs44eyb"/><path fill="url(#iaFMisd)" class="aphs44eyb"/><path fill="url(#iMJbjhe)" class="aphs44eyb"/><g filter="url(#ic9755g)"><path fill="url(#iFXkC3d)" class="uy6xp5apa"/><path fill="url(#ioe85Fc)" class="uy6xp5apa"/></g><path class="zwq81sbxd"/><path fill="url(#iVnKyvb)" class="r0bi3cbhr"/><path fill="url(#ibCq8ud)" class="r0bi3cbhr"/><path fill="url(#i0RKWrg)" class="r0bi3cbhr"/><path fill="url(#iyVFfBe)" class="r0bi3cbhr"/><path fill="url(#io4wYRP)" class="r0bi3cbhr"/><path fill="url(#ii4IFye)" class="r0bi3cbhr"/><defs><radialGradient id="ipWT76d" cx="0" cy="0" r="1" gradientTransform="matrix(9.1875 8.5 -4.8138 5.20314 22.813 12.938)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="s86s1lblt"/><stop offset=".554" class="g42-yxs5k"/><stop offset=".833" class="kzla8cb4j"/><stop offset=".917" class="i2-futbhp"/></radialGradient><radialGradient id="iOWL6Tb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.648 14.69 .964)scale(14.3438 11.7966)" gradientUnits="userSpaceOnUse"><stop class="i8g_jaccf"/><stop offset="1" class="o-jjf6b8p"/></radialGradient><radialGradient id="iQS6dSc" cx="0" cy="0" r="1" gradientTransform="matrix(7.00001 9.625 -3.91443 2.84686 18 11.438)" gradientUnits="userSpaceOnUse"><stop class="x0-eh9ujf"/><stop offset="1" class="mau-5hb5i"/></radialGradient><radialGradient id="iuCmTfp" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 2.375 -4.12417 4.01563 23 4.188)" gradientUnits="userSpaceOnUse"><stop class="td0g-bbdm"/><stop offset=".711" class="yg7zdnlul"/><stop offset="1" class="lfawh2c7r"/></radialGradient><radialGradient id="idGiMje" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 3.375 -1.29044 .0239 22.875 12.437)" gradientUnits="userSpaceOnUse"><stop class="j8b7-kbup"/><stop offset="1" class="lu0px8yfb"/></radialGradient><radialGradient id="iSJ7iWd" cx="0" cy="0" r="1" gradientTransform="rotate(109.113 -1.582 16.577)scale(6.68078 10.2578)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="phkg252vi"/><stop offset=".828" class="m8xgmjn7j"/><stop offset="1" class="j3g1fjb-v"/></radialGradient><radialGradient id="irjtGkd" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 5.5 -1.3378 1.53544 15.188 26)" gradientUnits="userSpaceOnUse"><stop class="hhqwclbav"/><stop offset="1" class="wf4l2nb_a"/></radialGradient><radialGradient id="izttPnb" cx="0" cy="0" r="1" gradientTransform="rotate(-178.616 5.85 11.517)scale(3.23532 .56908)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="j8pvycbjo"/><stop offset="1" class="adcktiban"/></radialGradient><radialGradient id="iAkfqQc" cx="0" cy="0" r="1" gradientTransform="matrix(-15.0625 -2.18745 2.16678 -14.92019 13.625 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="nk2rzrb1g"/><stop offset=".404" class="xsmvtjd0x"/><stop offset=".926" class="biq4wqbsu"/></radialGradient><radialGradient id="iyVivBe" cx="0" cy="0" r="1" gradientTransform="matrix(11.25 0 0 5.68361 7.25 23.746)" gradientUnits="userSpaceOnUse"><stop class="kwrw3ybjm"/><stop offset="1" class="tp3yf6b6t"/></radialGradient><radialGradient id="iaFMisd" cx="0" cy="0" r="1" gradientTransform="matrix(10.0937 0 0 1.29657 7.875 23.531)" gradientUnits="userSpaceOnUse"><stop class="iu5n2ib8v"/><stop offset="1" class="ra_0mfj2v"/></radialGradient><radialGradient id="iMJbjhe" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -2.93749 5.48804 5.13778 11.438 19.875)" gradientUnits="userSpaceOnUse"><stop class="gr6slildi"/><stop offset=".62" class="pehzkjn1j"/></radialGradient><radialGradient id="iVnKyvb" cx="0" cy="0" r="1" gradientTransform="rotate(140.244 5.149 10.095)scale(18.3733 13.7403)" gradientUnits="userSpaceOnUse"><stop class="g8eqgwbiv"/><stop offset=".729" class="w563u9b-p"/><stop offset=".922" class="rz9z_4-vw"/><stop offset="1" class="iaz2dobau"/></radialGradient><radialGradient id="ibCq8ud" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 10.0625 -2.8762 1.32198 15.063 7)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="yqg9uybfj"/><stop offset=".854" class="qerdrt_jd"/></radialGradient><radialGradient id="i0RKWrg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25005 6.49999 -5.4777 -1.05345 15.313 8.875)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="m9e_aac3i"/><stop offset=".924" class="c11vh1__p"/></radialGradient><radialGradient id="io4wYRP" cx="0" cy="0" r="1" gradientTransform="matrix(11.03124 6 -.93931 1.72697 8.156 15.781)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="bbg13jbop"/><stop offset=".453" class="a9bugbcqb"/><stop offset=".633" class="yw9orob-x"/><stop offset="1" class="hys00acgu"/></radialGradient><radialGradient id="ii4IFye" cx="0" cy="0" r="1" gradientTransform="rotate(46.094 -2.459 2.998)scale(22.3963)" gradientUnits="userSpaceOnUse"><stop offset=".936" class="hxznyacix"/><stop offset=".982" class="nuraknbbd"/></radialGradient><linearGradient id="iyBurSd" x1="24.734" x2="20.859" y1="4.672" y2="12.891" gradientUnits="userSpaceOnUse"><stop class="nd-lylqwi"/><stop offset=".066" class="ifv9rvbug"/><stop offset=".531" class="xuxlhlb7a"/><stop offset=".937" class="acxn99bxl"/></linearGradient><linearGradient id="ixHGzyd" x1="20.375" x2="20.125" y1="15.688" y2="12.781" gradientUnits="userSpaceOnUse"><stop offset=".462" class="xlfuc2bvq"/><stop offset=".855" class="cs__urb3u"/></linearGradient><linearGradient id="iHa5pCc" x1="12.938" x2="18.563" y1="2.571" y2="14.389" gradientUnits="userSpaceOnUse"><stop class="csqr_cbrr"/><stop offset=".485" class="u5cbjf7lz"/><stop offset="1" class="etu25ab5x"/></linearGradient><linearGradient id="i0btAyn" x1="3.961" x2="13.375" y1="23.794" y2="23.514" gradientUnits="userSpaceOnUse"><stop class="ue_hbpbba"/><stop offset=".104" class="mwighgy4i"/><stop offset=".225" class="laomgc3gs"/><stop offset=".8" class="pm8wvzb1j"/><stop offset="1" class="jc810r4or"/></linearGradient><linearGradient id="i3MROad" x1="8.222" x2="6.812" y1="13.125" y2="15.5" gradientUnits="userSpaceOnUse"><stop offset=".611" class="cr3nuhiwl"/><stop offset=".85" class="evyfe7b1d"/></linearGradient><linearGradient id="iFXkC3d" x1="2.813" x2="14.558" y1="13.031" y2="18.94" gradientUnits="userSpaceOnUse"><stop class="op5kb0u9t"/><stop offset="1" class="t664z-bws"/></linearGradient><linearGradient id="ioe85Fc" x1="8.219" x2="7.593" y1="14.641" y2="15.672" gradientUnits="userSpaceOnUse"><stop offset=".352" class="oo-tbtbtv"/><stop offset=".845" class="l-lzr91xz"/></linearGradient><linearGradient id="iyVFfBe" x1="7.25" x2="10.759" y1="15.188" y2="10.314" gradientUnits="userSpaceOnUse"><stop offset=".142" class="owtti7-ia"/><stop offset="1" class="p50bu2lsv"/></linearGradient><filter id="iI8g0sb" width="2.653" height="9.875" x="22.035" y="3.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31665" stdDeviation=".125"/></filter><filter id="i9woDxd" width="8.648" height="12.008" x="10.781" y="2.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31665" stdDeviation=".125"/></filter><filter id="idJUsod" width="9.578" height="2.28" x="3.891" y="22.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31665" stdDeviation=".125"/></filter><filter id="ic9755g" width="12.126" height="8.509" x="2.453" y="11.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31665" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:croissant" /></template>
<style>
.a9bugbcqb {
  stop-color: var(--svg-color--c8604c, #C8604C);
}

.acxn99bxl {
  stop-color: var(--svg-color--e99e6b, #E99E6B);
}

.adcktiban {
  stop-color: var(--svg-color--b35445, #B35445);
  stop-opacity: 0;
}

.aphs44eyb {
  d: path("M2.992 22.648c-.921-2.11-1.203-5.203-.781-7.578s.997-3.119.997-3.119c.104-.625.625-.67 1.198-.38c2.328 1.843 8.906 3.655 9.837 6.507c.352 1.225.385 3.235-.079 4.438c-.123.35-.664.836-1.101.898c-.438.063-3.586-.062-4.446-.062s-3.969.32-4.476.265s-.907-.414-1.149-.969");
}

.bbg13jbop {
  stop-color: var(--svg-color--e4745d, #E4745D);
}

.biq4wqbsu {
  stop-color: var(--svg-color--a16948, #A16948);
}

.c11vh1__p {
  stop-color: var(--svg-color--ffbe7b, #FFBE7B);
  stop-opacity: 0;
}

.cr3nuhiwl {
  stop-color: var(--svg-color--984847, #984847);
}

.cs__urb3u {
  stop-color: var(--svg-color--b75077, #B75077);
  stop-opacity: 0;
}

.csqr_cbrr {
  stop-color: var(--svg-color--ddc173, #DDC173);
}

.etu25ab5x {
  stop-color: var(--svg-color--e49966, #E49966);
}

.evyfe7b1d {
  stop-color: var(--svg-color--9a4947, #9A4947);
  stop-opacity: 0;
}

.fmk28gu0s {
  d: path("m22.285 12.182l1.152 1.084l1-8.563c-.925-.579-1.417-.74-1.78-.812z");
}

.ft5dv1b6b {
  fill: none;
}

.g42-yxs5k {
  stop-color: var(--svg-color--f6ac6a, #F6AC6A);
}

.g8eqgwbiv {
  stop-color: var(--svg-color--fdae69, #FDAE69);
}

.gr6slildi {
  stop-color: var(--svg-color--ffc083, #FFC083);
}

.hhqwclbav {
  stop-color: var(--svg-color--ffd483, #FFD483);
}

.hxznyacix {
  stop-color: var(--svg-color--c17c61, #C17C61);
  stop-opacity: 0;
}

.hys00acgu {
  stop-color: var(--svg-color--c0605f, #C0605F);
  stop-opacity: 0;
}

.i2-futbhp {
  stop-color: var(--svg-color--ffdc87, #FFDC87);
}

.i8g_jaccf {
  stop-color: var(--svg-color--ffbe66, #FFBE66);
}

.iaz2dobau {
  stop-color: var(--svg-color--8b6b4a, #8B6B4A);
}

.ifv9rvbug {
  stop-color: var(--svg-color--ffffa6, #FFFFA6);
}

.iu5n2ib8v {
  stop-color: var(--svg-color--b64b4b, #B64B4B);
}

.j3g1fjb-v {
  stop-color: var(--svg-color--b05a66, #B05A66);
}

.j4jxsqb3p {
  d: path("m22.281 12.266l3.672 3.453c.94.94 2.138 1.674 3.078.734c.828-.672.902-2.353.922-2.953c0-1.937-1.031-5.125-2.703-6.781c-1.69-1.674-3.872-2.802-4.547-2.938z");
}

.j8b7-kbup {
  stop-color: var(--svg-color--ffbc67, #FFBC67);
}

.j8pvycbjo {
  stop-color: var(--svg-color--af5a3e, #AF5A3E);
}

.jc810r4or {
  stop-color: var(--svg-color--ffd780, #FFD780);
}

.kwrw3ybjm {
  stop-color: var(--svg-color--c66364, #C66364);
}

.kzla8cb4j {
  stop-color: var(--svg-color--ffd186, #FFD186);
}

.l-lzr91xz {
  stop-color: var(--svg-color--a04346, #A04346);
  stop-opacity: 0;
}

.laomgc3gs {
  stop-color: var(--svg-color--db9f84, #DB9F84);
}

.lfawh2c7r {
  stop-color: var(--svg-color--f9b870, #F9B870);
  stop-opacity: 0;
}

.lu0px8yfb {
  stop-color: var(--svg-color--ffbc67, #FFBC67);
  stop-opacity: 0;
}

.m8xgmjn7j {
  stop-color: var(--svg-color--df8c6d, #DF8C6D);
}

.m9e_aac3i {
  stop-color: var(--svg-color--ffd88c, #FFD88C);
}

.mau-5hb5i {
  stop-color: var(--svg-color--d97d67, #D97D67);
  stop-opacity: 0;
}

.mwighgy4i {
  stop-color: var(--svg-color--b37173, #B37173);
}

.my5mnzbzp {
  d: path("m22.797 3.057l-.953-.404c-2.202-.685-4.61-.84-7.172-.42c-2.563.42-3.156 1.011-3.156 1.011c-.62.123-.649.645-.344 1.21c1.908 2.272 4.004 8.95 6.875 9.797c.843.215 3.332.227 4.155-.092l.122-.051c.345-.133.843-.827.863-1.196l.235-8.882c.03-.43-.274-.778-.625-.973");
}

.nd-lylqwi {
  stop-color: var(--svg-color--ebd67c, #EBD67C);
}

.nk2rzrb1g {
  stop-color: var(--svg-color--ffb974, #FFB974);
}

.nuraknbbd {
  stop-color: var(--svg-color--c17c61, #C17C61);
}

.o-jjf6b8p {
  stop-color: var(--svg-color--e2ae5b, #E2AE5B);
}

.ojbkehb_n {
  fill: var(--svg-color--f5ab6a, #F5AB6A);
  d: path("m22.281 12.266l3.672 3.453c.94.94 2.138 1.674 3.078.734c.828-.672.902-2.353.922-2.953c0-1.937-1.031-5.125-2.703-6.781c-1.69-1.674-3.872-2.802-4.547-2.938z");
}

.oo-tbtbtv {
  stop-color: var(--svg-color--a74746, #A74746);
}

.op5kb0u9t {
  stop-color: var(--svg-color--b89367, #B89367);
}

.owtti7-ia {
  stop-color: var(--svg-color--c15f4d, #C15F4D);
}

.p50bu2lsv {
  stop-color: var(--svg-color--d58366, #D58366);
  stop-opacity: 0;
}

.pehzkjn1j {
  stop-color: var(--svg-color--ffbd7d, #FFBD7D);
  stop-opacity: 0;
}

.phkg252vi {
  stop-color: var(--svg-color--ffbf7e, #FFBF7E);
}

.pm8wvzb1j {
  stop-color: var(--svg-color--f1bb8a, #F1BB8A);
}

.qerdrt_jd {
  stop-color: var(--svg-color--ffd98b, #FFD98B);
  stop-opacity: 0;
}

.r0bi3cbhr {
  d: path("M9.832 2.822c-3.21 1.25-5.76 3.8-7.01 7.01c-.34.88 0 1.87.8 2.36l10.42 6.35c.62.38 1.4.38 2.02 0a7.45 7.45 0 0 0 2.48-2.48c.38-.62.38-1.4 0-2.02l-6.35-10.42c-.49-.8-1.48-1.14-2.36-.8");
}

.ra_0mfj2v {
  stop-color: var(--svg-color--c56158, #C56158);
  stop-opacity: 0;
}

.rd9b7_x3c {
  d: path("M13.102 2.727c-1.24.342-1.572.673-1.572.673c-.62.123-.594.715-.29 1.28c1.909 2.272 3.896 8.57 6.767 9.416c.264.067.688.115 1.173.138z");
}

.rz9z_4-vw {
  stop-color: var(--svg-color--ad7b45, #AD7B45);
}

.s86s1lblt {
  stop-color: var(--svg-color--c05159, #C05159);
}

.t664z-bws {
  stop-color: var(--svg-color--c5835e, #C5835E);
}

.td0g-bbdm {
  stop-color: var(--svg-color--ffe4a6, #FFE4A6);
}

.tp3yf6b6t {
  stop-color: var(--svg-color--d4766b, #D4766B);
  stop-opacity: 0;
}

.u34qowbxt {
  fill: var(--svg-color--ec9f6a, #EC9F6A);
  d: path("M2.992 22.648c-.921-2.11-1.203-5.203-.781-7.578s.997-3.119.997-3.119c.104-.625.625-.67 1.198-.38c2.328 1.843 8.906 3.655 9.837 6.507c.352 1.225.385 3.235-.079 4.438c-.123.35-.664.836-1.101.898c-.438.063-3.586-.062-4.446-.062s-3.969.32-4.476.265s-.907-.414-1.149-.969");
}

.u43k-jtdg {
  d: path("m12.052 22.792l1.167 1.145l-8.409.635c-.377-.705-.602-1.295-.67-1.588z");
}

.u5cbjf7lz {
  stop-color: var(--svg-color--d59f65, #D59F65);
}

.ue_hbpbba {
  stop-color: var(--svg-color--a8716f, #A8716F);
}

.uy6xp5apa {
  d: path("M2.703 13.672c.338-1.2.66-1.617.66-1.617c.104-.624.624-.669 1.198-.38c2.328 1.844 8.52 3.435 9.451 6.287q.24.841.317 1.55z");
}

.w563u9b-p {
  stop-color: var(--svg-color--ce8c4f, #CE8C4F);
}

.wf4l2nb_a {
  stop-color: var(--svg-color--ffd688, #FFD688);
  stop-opacity: 0;
}

.x0-eh9ujf {
  stop-color: var(--svg-color--d67c63, #D67C63);
}

.xlfuc2bvq {
  stop-color: var(--svg-color--b45077, #B45077);
}

.xosh3wm9d {
  d: path("m12.219 22.719l3.547 3.484c.967.914 1.567 2.046.656 3.016c-.647.85-2.198.774-2.797.812a9.65 9.65 0 0 1-6.781-2.5c-1.767-1.597-2.75-3.843-2.906-4.515z");
}

.xsmvtjd0x {
  stop-color: var(--svg-color--f2a56d, #F2A56D);
}

.xuxlhlb7a {
  stop-color: var(--svg-color--f8c281, #F8C281);
}

.yg7zdnlul {
  stop-color: var(--svg-color--f8b76f, #F8B76F);
}

.yqg9uybfj {
  stop-color: var(--svg-color--ffd47c, #FFD47C);
}

.yw9orob-x {
  stop-color: var(--svg-color--c0605f, #C0605F);
}

.zwq81sbxd {
  fill: var(--svg-color--d79453, #D79453);
  d: path("M9.832 2.822c-3.21 1.25-5.76 3.8-7.01 7.01c-.34.88 0 1.87.8 2.36l10.42 6.35c.62.38 1.4.38 2.02 0a7.45 7.45 0 0 0 2.48-2.48c.38-.62.38-1.4 0-2.02l-6.35-10.42c-.49-.8-1.48-1.14-2.36-.8");
}

</style>
