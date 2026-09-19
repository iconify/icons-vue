<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ip7Okhc)" class="ho8m-wbbn"/><path fill="url(#iLHtqQd)" class="ho8m-wbbn"/><path fill="url(#i3zwPKc)" class="ho8m-wbbn"/><path fill="url(#i5QYTxd)" class="gkfrerbbx"/><g filter="url(#ifx8QKA)"><path fill="url(#iQklPab)" class="kdg2qjbpe"/><path fill="url(#iWzKtoe)" class="kdg2qjbpe"/></g><path fill="url(#iOzGb5d)" class="n5llnw45q"/><path fill="url(#iaSOG4c)" class="n5llnw45q"/><g filter="url(#iQXCgQe)"><path class="d74c4u_5e"/></g><path fill="url(#iuWQ1hd)" class="f3sesmbpa"/><g filter="url(#ixHN9hm)"><path fill="url(#i3HDS8c)" class="u_-qh0b9h"/></g><g filter="url(#i1sT6YW)"><path class="t0vaeetav"/></g><g filter="url(#iccoMAb)"><path class="er8klsbmj"/></g><path fill="url(#iheHBvd)" class="bkn5zebzy"/><g filter="url(#iBdmQTc)"><path stroke="url(#iXQht9d)" class="f4m39qbuq"/></g><g filter="url(#idWqnJd)"><path stroke="url(#i67UzGs)" class="ru58fc1rw"/></g><g filter="url(#igCsyPd)"><path stroke="url(#icnYg6b)" class="vg0ix_0oj"/></g><g filter="url(#iTUupvb)"><path class="f6sfqsb9r"/></g><defs><radialGradient id="iLHtqQd" cx="0" cy="0" r="1" gradientTransform="rotate(121.551 5.967 20.797)scale(2.09025 2.09149)" gradientUnits="userSpaceOnUse"><stop class="if62qf7ni"/><stop offset=".943" class="k05n1gbkm"/></radialGradient><radialGradient id="i3zwPKc" cx="0" cy="0" r="1" gradientTransform="rotate(135.822 6.425 15.11)scale(4.61877 2.16107)" gradientUnits="userSpaceOnUse"><stop class="tp9bmsb3f"/><stop offset="1" class="gtwdcgbnr"/></radialGradient><radialGradient id="iWzKtoe" cx="0" cy="0" r="1" gradientTransform="rotate(85.118 -1.83 13.758)scale(16.7455)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="r3qjcopwk"/><stop offset=".466" class="mmohku0ok"/></radialGradient><radialGradient id="iOzGb5d" cx="0" cy="0" r="1" gradientTransform="matrix(16.875 -1 1 16.875 8.938 14.438)" gradientUnits="userSpaceOnUse"><stop class="m96h-4brc"/><stop offset=".466" class="xkhxocchr"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="iaSOG4c" cx="0" cy="0" r="1" gradientTransform="rotate(111.224 5.288 11.65)scale(13.8118)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="a7c1lh7oq"/><stop offset="1" class="x-audowon"/></radialGradient><radialGradient id="iheHBvd" cx="0" cy="0" r="1" gradientTransform="rotate(144.66 5.029 8.417)scale(4.214 4.20983)" gradientUnits="userSpaceOnUse"><stop class="f6wrzrbdh"/><stop offset=".709" class="hibjv3e0m"/><stop offset="1" class="exfvk9b6s"/></radialGradient><radialGradient id="iXQht9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .17187 -.22007 -1.18037 14.188 12.563)" gradientUnits="userSpaceOnUse"><stop class="fnwqng-ru"/><stop offset="1" class="gv51rxbna"/></radialGradient><radialGradient id="i67UzGs" cx="0" cy="0" r="1" gradientTransform="matrix(-.67969 .22655 -.38905 -1.1672 24.68 26.795)" gradientUnits="userSpaceOnUse"><stop class="k6u702b2p"/><stop offset="1" class="f1cjzob4d"/></radialGradient><radialGradient id="icnYg6b" cx="0" cy="0" r="1" gradientTransform="rotate(172.138 12.053 13.222)scale(5.76178 4.46925)" gradientUnits="userSpaceOnUse"><stop class="k6u702b2p"/><stop offset="1" class="f1cjzob4d"/></radialGradient><filter id="ifx8QKA" width="23.573" height="23.573" x="2.094" y="2.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".25"/></filter><filter id="iQXCgQe" width="12.378" height="11.031" x="7.5" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".25"/></filter><filter id="ixHN9hm" width="10.88" height="9.636" x="8.502" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".125"/></filter><filter id="i1sT6YW" width="5.878" height="5.878" x="9.248" y="10.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".25"/></filter><filter id="iccoMAb" width="6.06" height="6.06" x="9.716" y="10.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".25"/></filter><filter id="iBdmQTc" width="1.938" height="2.5" x="13.062" y="11.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".125"/></filter><filter id="idWqnJd" width="1.671" height="3.219" x="23.954" y="25.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".125"/></filter><filter id="igCsyPd" width="6.634" height="8.719" x="23.406" y="20.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".125"/></filter><filter id="iTUupvb" width="8.188" height="7.074" x="20.031" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33665" stdDeviation=".125"/></filter><linearGradient id="ip7Okhc" x1="21.625" x2="29.009" y1="21.313" y2="28.987" gradientUnits="userSpaceOnUse"><stop class="kn1w79bxk"/><stop offset="1" class="dyoc_yb4u"/></linearGradient><linearGradient id="i5QYTxd" x1="22.938" x2="4.313" y1="6.625" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="m-46u_1un"/><stop offset=".506" class="qhdxlkbzx"/><stop offset="1" class="gpwo9mbit"/></linearGradient><linearGradient id="iQklPab" x1="23.257" x2="5.908" y1="6.572" y2="21.85" gradientUnits="userSpaceOnUse"><stop class="zwaomlh3y"/><stop offset=".449" class="qp4vm7b8r"/><stop offset="1" class="i569tjbyj"/></linearGradient><linearGradient id="iuWQ1hd" x1="16.75" x2="9.75" y1="10.25" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".657" class="ofiorffzk"/><stop offset=".879" class="sp04nej8m"/><stop offset="1" class="lwg1i9bpd"/></linearGradient><linearGradient id="i3HDS8c" x1="16.875" x2="9.813" y1="11.125" y2="15.688" gradientUnits="userSpaceOnUse"><stop class="cdbndwdgf"/><stop offset="1" class="ta-0pvzol"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cooking" /></template>
<style>
.a7c1lh7oq {
  stop-color: var(--svg-color--5e3f77, #5E3F77);
  stop-opacity: 0;
}

.bkn5zebzy {
  d: path("M12.59 16.18a2.53 2.53 0 1 0 0-5.06a2.53 2.53 0 0 0 0 5.06");
}

.cdbndwdgf {
  stop-color: var(--svg-color--fbebff, #FBEBFF);
}

.d74c4u_5e {
  fill: var(--svg-color--3d3246, #3D3246);
  d: path("M18.98 12.274c-.28-.39-.65-.67-1.06-.81c-.45-.16-.85-.45-1.17-.8a4 4 0 0 0-.46-.45a5.03 5.03 0 0 0-5.72-.58c-.46.26-.96.43-1.48.53h-.01c-.54.11-.96.57-1.03 1.12c-.01.13-.01.25.01.37c.08.49.11.98.02 1.47a5.01 5.01 0 0 0 6.24 5.73c.58-.16 1.19-.2 1.79-.16c.39.02.78-.11 1.08-.41c.39-.39.51-.96.34-1.45c-.08-.24-.06-.51.04-.74v-.01c.1-.23.29-.4.51-.5c.35-.16.66-.42.91-.77c.52-.78.52-1.8-.01-2.54");
}

.dyoc_yb4u {
  stop-color: var(--svg-color--594172, #594172);
}

.er8klsbmj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.746 16.18a2.53 2.53 0 1 0 0-5.06a2.53 2.53 0 0 0 0 5.06");
}

.exfvk9b6s {
  stop-color: var(--svg-color--b47049, #B47049);
}

.f1cjzob4d {
  stop-color: var(--svg-color--846ea1, #846EA1);
  stop-opacity: 0;
}

.f3sesmbpa {
  d: path("M19.35 11.98c-.28-.39-.65-.67-1.06-.81c-.45-.16-.85-.45-1.17-.8a4 4 0 0 0-.46-.45a5.03 5.03 0 0 0-5.72-.58c-.46.26-.96.43-1.48.53h-.01c-.54.11-.96.57-1.03 1.12c-.01.13-.01.25.01.37c.08.49.11.98.02 1.47a5.01 5.01 0 0 0 6.24 5.73c.58-.16 1.19-.2 1.79-.16c.39.02.78-.11 1.08-.41c.39-.39.51-.96.34-1.45c-.08-.24-.06-.51.04-.74v-.01c.1-.23.29-.4.51-.5c.35-.16.66-.42.91-.77c.52-.78.52-1.8-.01-2.54");
}

.f4m39qbuq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M13.563 12.063c.26.145.812.65.937 1.5");
}

.f6sfqsb9r {
  stroke: var(--svg-color--513d75, #513D75);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m20.531 23.5l4.11 5.188c.64.75 1.778 1.19 3.078.64");
}

.f6wrzrbdh {
  stop-color: var(--svg-color--ffdb5c, #FFDB5C);
}

.fnwqng-ru {
  stop-color: var(--svg-color--ffec86, #FFEC86);
}

.ft5dv1b6b {
  fill: none;
}

.gkfrerbbx {
  d: path("M13.88 25.76c6.561 0 11.88-5.319 11.88-11.88S20.441 2 13.88 2S2 7.319 2 13.88s5.319 11.88 11.88 11.88");
}

.gpwo9mbit {
  stop-color: var(--svg-color--4d3966, #4D3966);
}

.gtwdcgbnr {
  stop-color: var(--svg-color--3f285c, #3F285C);
  stop-opacity: 0;
}

.gv51rxbna {
  stop-color: var(--svg-color--ffea85, #FFEA85);
  stop-opacity: 0;
}

.hibjv3e0m {
  stop-color: var(--svg-color--f3a442, #F3A442);
}

.ho8m-wbbn {
  d: path("m28.66 23.87l-6.54-5l-3.24 3.24l5 6.54a3.422 3.422 0 0 0 5.14.34c1.45-1.45 1.29-3.87-.36-5.12m-3.24 3.64a1.485 1.485 0 1 1 2.1-2.1a1.485 1.485 0 0 1-2.1 2.1");
}

.i569tjbyj {
  stop-color: var(--svg-color--5d3f7c, #5D3F7C);
}

.if62qf7ni {
  stop-color: var(--svg-color--4c3965, #4C3965);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k6u702b2p {
  stop-color: var(--svg-color--8670a3, #8670A3);
}

.kdg2qjbpe {
  d: path("M13.88 25.166c6.233 0 11.286-5.053 11.286-11.286S20.113 2.594 13.88 2.594S2.594 7.647 2.594 13.88S7.647 25.166 13.88 25.166");
}

.kn1w79bxk {
  stop-color: var(--svg-color--604a93, #604A93);
}

.lwg1i9bpd {
  stop-color: var(--svg-color--d1bbe4, #D1BBE4);
}

.m-46u_1un {
  stop-color: var(--svg-color--7e75bf, #7E75BF);
}

.m96h-4brc {
  stop-color: var(--svg-color--654b7e, #654B7E);
}

.mmohku0ok {
  stop-color: var(--svg-color--7e6898, #7E6898);
  stop-opacity: 0;
}

.n5llnw45q {
  d: path("M13.88 22.88a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.ofiorffzk {
  stop-color: var(--svg-color--e8dfef, #E8DFEF);
}

.qhdxlkbzx {
  stop-color: var(--svg-color--58457c, #58457C);
}

.qp4vm7b8r {
  stop-color: var(--svg-color--5c4385, #5C4385);
}

.r3qjcopwk {
  stop-color: var(--svg-color--b5a4cb, #B5A4CB);
}

.ru58fc1rw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M24.625 25.688a1.88 1.88 0 0 0 .5 2.218");
}

.sp04nej8m {
  stop-color: var(--svg-color--c7b7d5, #C7B7D5);
}

.t0vaeetav {
  fill: var(--svg-color--ae8cbb, #AE8CBB);
  d: path("M12.186 16.317a2.439 2.439 0 1 0 0-4.878a2.439 2.439 0 0 0 0 4.878");
}

.ta-0pvzol {
  stop-color: var(--svg-color--fbeaff, #FBEAFF);
}

.tp9bmsb3f {
  stop-color: var(--svg-color--482d6e, #482D6E);
}

.u_-qh0b9h {
  d: path("M18.776 12.169a1.95 1.95 0 0 0-.945-.722a2.6 2.6 0 0 1-1.043-.714a4.48 4.48 0 0 0-5.51-.918c-.41.232-.856.383-1.32.473H9.95a1.18 1.18 0 0 0-.919.998a1.4 1.4 0 0 0 .01.33c.07.437-.138 1.067-.218 1.504a4.468 4.468 0 0 0 5.564 5.108c.517-.142 1.296-.37 1.83-.335a1.257 1.257 0 0 0 1.267-1.659a.94.94 0 0 1 .035-.66v-.008a.9.9 0 0 1 .455-.446c.312-.143.588-.374.811-.687c.464-.695.464-1.604-.009-2.264");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vg0ix_0oj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.906 20.813l4.907 3.812c.562.5 1.23 2.106.156 3.906");
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.x-audowon {
  stop-color: var(--svg-color--60407c, #60407C);
}

.xkhxocchr {
  stop-color: var(--svg-color--4d3a5e, #4D3A5E);
}

.zwaomlh3y {
  stop-color: var(--svg-color--5e50a1, #5E50A1);
}

</style>
