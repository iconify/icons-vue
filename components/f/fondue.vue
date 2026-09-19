<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qse46e-nd"/><path fill="url(#is2qQId)" class="lv30s1b8s"/><path fill="url(#ijQBLhd)" class="lv30s1b8s"/><path fill="url(#iQTQoBe)" class="a--0-9qih"/><path fill="url(#iRJ3kmb)" class="s8jyzob2r"/><path fill="url(#ivcWp1d)" class="cw-ybqi5b"/><g filter="url(#iXB46Gd)"><path class="glk9ipbjn"/><path fill="url(#ihP83gb)" class="mivwqtr2w"/></g><path fill="url(#iCjVHOe)" class="cw-ybqi5b"/><path fill="url(#izbKBLe)" class="cw-ybqi5b"/><path fill="url(#iRpBWFe)" class="kwcsqv5-j"/><g filter="url(#it8I4Ce)"><path fill="url(#iBLaLQE)" class="n2wc5mgyw"/></g><path fill="url(#i9XW7Rc)" class="pu-ak8_oj"/><path fill="url(#iQUjTWc)" class="mognwcnni"/><g filter="url(#iXGdORc)"><path stroke="url(#iYlxzhe)" class="athh_6mtj"/><path stroke="url(#i85qdJb)" class="athh_6mtj"/></g><path fill="url(#iHVMk8c)" class="yxxfxnbst"/><path fill="url(#iJtLgEe)" class="yxxfxnbst"/><path fill="url(#iGins6N)" class="v2xja2bhf"/><path fill="url(#il2WDDE)" class="k35e4hb_t"/><path fill="url(#iD4tUbb)" class="k35e4hb_t"/><path fill="url(#izun5zc)" class="vmr3cxbtw"/><path fill="url(#i7TmCbv)" class="vmr3cxbtw"/><path class="fb_5ct6_n"/><path fill="url(#ipFbvUc)" class="ka5fbcc2x"/><path fill="url(#iq3qRGb)" class="ka5fbcc2x"/><g filter="url(#iDXkQud)"><rect class="hma9t4r2x"/></g><g filter="url(#i827c5b)"><rect transform="rotate(15.354 21.74 3.077)" class="gomeqcb_w"/></g><g filter="url(#iWZD1Ec)"><path stroke="url(#iYlxzhe)" class="nop1xdm5i"/></g><g filter="url(#iA0SI6b)"><path stroke="url(#iII2woF)" class="s7i6iunaz"/></g><g filter="url(#iA0SI6b)"><path stroke="url(#iII2woF)" class="s7i6iunaz"/></g><g filter="url(#ipWD2eb)"><path fill="url(#in97Gdb)" class="n7gz0478b"/><path fill="url(#iKz0Igb)" class="n7gz0478b"/></g><defs><radialGradient id="is2qQId" cx="0" cy="0" r="1" gradientTransform="rotate(68.482 -11.525 23.733)scale(2.58652 1.4211)" gradientUnits="userSpaceOnUse"><stop class="k3qmz6eds"/><stop offset="1" class="v-cp05bob"/></radialGradient><radialGradient id="iQTQoBe" cx="0" cy="0" r="1" gradientTransform="rotate(135 1.596 16.477)scale(1.19324)" gradientUnits="userSpaceOnUse"><stop class="u7d9x1bth"/><stop offset="1" class="akdztfuyg"/></radialGradient><radialGradient id="izbKBLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1 -1.5625 0 27.094 15.688)" gradientUnits="userSpaceOnUse"><stop class="f7nqzrr6b"/><stop offset="1" class="g9f4t9pro"/></radialGradient><radialGradient id="iYlxzhe" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 3.3125 -3.66952 .88276 6.203 10.688)" gradientUnits="userSpaceOnUse"><stop class="t84zjbnde"/><stop offset="1" class="q7u4pqklq"/></radialGradient><radialGradient id="i85qdJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.85938 -8.17603 0 12.96 9.453)" gradientUnits="userSpaceOnUse"><stop class="ssj1pacja"/><stop offset="1" class="he9c81qiu"/></radialGradient><radialGradient id="iHVMk8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.77972 -3.84532 0 22.813 2.887)" gradientUnits="userSpaceOnUse"><stop class="aqba3-bfs"/><stop offset=".506" class="alwj6xyns"/><stop offset=".775" class="gnctq-b_z"/><stop offset=".93" class="zj6or0bqf"/></radialGradient><radialGradient id="iJtLgEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.35197 1.068 -1.18219 -.3896 22.285 2.541)" gradientUnits="userSpaceOnUse"><stop class="cned2fbrn"/><stop offset="1" class="eml_3gxaa"/></radialGradient><radialGradient id="il2WDDE" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.75 -2.73125 0 18 2.875)" gradientUnits="userSpaceOnUse"><stop class="aqba3-bfs"/><stop offset=".506" class="alwj6xyns"/><stop offset=".775" class="gnctq-b_z"/><stop offset=".93" class="zj6or0bqf"/></radialGradient><radialGradient id="iD4tUbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25001 1.0625 -.88205 -.20755 17.625 2.531)" gradientUnits="userSpaceOnUse"><stop class="cned2fbrn"/><stop offset="1" class="eml_3gxaa"/></radialGradient><radialGradient id="izun5zc" cx="0" cy="0" r="1" gradientTransform="rotate(162.592 5.348 6.954)scale(3.24225)" gradientUnits="userSpaceOnUse"><stop class="jl8fambtc"/><stop offset="1" class="zy4s2yt4l"/></radialGradient><radialGradient id="ipFbvUc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31436 .72998 -.73358 -2.32578 17.59 11.5)" gradientUnits="userSpaceOnUse"><stop class="jl8fambtc"/><stop offset="1" class="zy4s2yt4l"/></radialGradient><radialGradient id="iII2woF" cx="0" cy="0" r="1" gradientTransform="rotate(-80.057 18.89 -5.954)scale(3.407 3.77421)" gradientUnits="userSpaceOnUse"><stop class="t84zjbnde"/><stop offset="1" class="q7u4pqklq"/></radialGradient><linearGradient id="ijQBLhd" x1="13.031" x2="13.031" y1="27.906" y2="25.875" gradientUnits="userSpaceOnUse"><stop class="ullkoib4b"/><stop offset=".523" class="tc1m68pch"/></linearGradient><linearGradient id="iRJ3kmb" x1="14" x2="14" y1="22.486" y2="31.896" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset=".599" class="x027k85me"/><stop offset=".809" class="qcluucb0m"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="ivcWp1d" x1="21" x2="28" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ihP83gb" x1="13.969" x2="13.969" y1="21.875" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="od1cyxt8v"/><stop offset="1" class="xajmv0t3c"/></linearGradient><linearGradient id="iCjVHOe" x1="25.719" x2="25.719" y1="14.262" y2="18.063" gradientUnits="userSpaceOnUse"><stop class="o9l81dywf"/><stop offset=".416" class="obffxh4jp"/><stop offset=".885" class="da81j0y2x"/></linearGradient><linearGradient id="iRpBWFe" x1="5" x2="23" y1="16.563" y2="16.563" gradientUnits="userSpaceOnUse"><stop class="doshro1iu"/><stop offset=".084" class="i82dke3zj"/><stop offset=".177" class="rddrspb6n"/><stop offset=".26" class="plvbowb8z"/><stop offset=".781" class="wct088l7h"/><stop offset=".868" class="wymbu-kfy"/><stop offset=".955" class="evbl01h_f"/><stop offset="1" class="kxv9t8boy"/></linearGradient><linearGradient id="iBLaLQE" x1="6.137" x2="22.403" y1="10.767" y2="10.767" gradientUnits="userSpaceOnUse"><stop class="cwes0qb1f"/><stop offset=".118" class="vp74cc3oh"/><stop offset=".841" class="duypixbvv"/><stop offset=".914" class="k9mlr4brq"/><stop offset=".966" class="j26b871_k"/><stop offset="1" class="pai6k2fmm"/></linearGradient><linearGradient id="i9XW7Rc" x1="6.02" x2="22.438" y1="12.313" y2="12.313" gradientUnits="userSpaceOnUse"><stop class="e5wwqmflc"/><stop offset=".119" class="scfbv3b8z"/><stop offset=".893" class="wb2-7bubk"/><stop offset="1" class="ir4ssmb3h"/></linearGradient><linearGradient id="iQUjTWc" x1="19.844" x2="20.906" y1="8.449" y2="8.781" gradientUnits="userSpaceOnUse"><stop offset=".083" class="qrkswpfhq"/><stop offset=".467" class="gw_49ss5a"/><stop offset="1" class="h416f6fnu"/></linearGradient><linearGradient id="iGins6N" x1="16.5" x2="17.5" y1="8.33" y2="8.33" gradientUnits="userSpaceOnUse"><stop class="qrkswpfhq"/><stop offset=".465" class="gw_49ss5a"/><stop offset="1" class="h416f6fnu"/></linearGradient><linearGradient id="i7TmCbv" x1="10.344" x2="10.344" y1="13.164" y2="12.703" gradientUnits="userSpaceOnUse"><stop offset=".455" class="hmen8pr-m"/><stop offset="1" class="dc3btsbzu"/></linearGradient><linearGradient id="iq3qRGb" x1="15.954" x2="15.954" y1="12.384" y2="12.037" gradientUnits="userSpaceOnUse"><stop offset=".455" class="hmen8pr-m"/><stop offset="1" class="dc3btsbzu"/></linearGradient><linearGradient id="in97Gdb" x1="19.375" x2="8.219" y1="26.281" y2="26.281" gradientUnits="userSpaceOnUse"><stop class="u3lfh5b3a"/><stop offset=".126" class="xiiozlb2v"/><stop offset=".174" class="pl4x7xb5b"/><stop offset=".838" class="du-plvbbz"/><stop offset="1" class="otqslw08p"/></linearGradient><linearGradient id="iKz0Igb" x1="12.813" x2="12.813" y1="29.938" y2="28.344" gradientUnits="userSpaceOnUse"><stop class="zktaqtb1j"/><stop offset="1" class="l6kr0-btg"/></linearGradient><filter id="iXB46Gd" width="13.688" height="3.172" x="7.125" y="20.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".25"/></filter><filter id="it8I4Ce" width="17.09" height="5.938" x="5.563" y="8.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".125"/></filter><filter id="iXGdORc" width="15.047" height="5.75" x="5.438" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".125"/></filter><filter id="iDXkQud" width="2.688" height="5.312" x="16" y="1.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".5"/></filter><filter id="i827c5b" width="3.385" height="5.229" x="19.939" y="2.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".5"/></filter><filter id="iWZD1Ec" width="3.125" height="5.75" x="5.438" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".125"/></filter><filter id="iA0SI6b" width="4.297" height="4.913" x="18.625" y="9.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".125"/></filter><filter id="ipWD2eb" width="12.518" height="7.123" x="7.719" y="22.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30985" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fondue" /></template>
<style>
.a--0-9qih {
  d: path("M14 28.32a.95.95 0 1 0 0-1.9a.95.95 0 0 0 0 1.9");
}

.akdztfuyg {
  stop-color: var(--svg-color--de9f2c, #DE9F2C);
}

.alwj6xyns {
  stop-color: var(--svg-color--f79954, #F79954);
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.aqba3-bfs {
  stop-color: var(--svg-color--ffd196, #FFD196);
}

.athh_6mtj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.125 14c-.437-.241-1.312-1.066-1.312-2.434C5.813 9.658 7.469 9 8.188 9h11.921");
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cned2fbrn {
  stop-color: var(--svg-color--ffd89b, #FFD89B);
}

.cw-ybqi5b {
  d: path("M26.02 17.72L21 17v-2l5.02-.72c1.05-.15 1.98.66 1.98 1.72s-.93 1.87-1.98 1.72");
}

.cwes0qb1f {
  stop-color: var(--svg-color--ff4e76, #FF4E76);
}

.da81j0y2x {
  stop-color: var(--svg-color--d12972, #D12972);
}

.dc3btsbzu {
  stop-color: var(--svg-color--ffd15d, #FFD15D);
  stop-opacity: 0;
}

.doshro1iu {
  stop-color: var(--svg-color--cb5468, #CB5468);
}

.du-plvbbz {
  stop-color: var(--svg-color--604c73, #604C73);
}

.duypixbvv {
  stop-color: var(--svg-color--fc3e89, #FC3E89);
}

.e5wwqmflc {
  stop-color: var(--svg-color--ffd660, #FFD660);
}

.eml_3gxaa {
  stop-color: var(--svg-color--ffd79b, #FFD79B);
  stop-opacity: 0;
}

.evbl01h_f {
  stop-color: var(--svg-color--fe4380, #FE4380);
}

.f7nqzrr6b {
  stop-color: var(--svg-color--ff6496, #FF6496);
}

.fb_5ct6_n {
  fill: var(--svg-color--fff46c, #FFF46C);
  d: path("M16.85 10.77c-.8 0-1.46.65-1.46 1.46h2.91c0-.81-.65-1.46-1.45-1.46");
}

.ft5dv1b6b {
  fill: none;
}

.g9f4t9pro {
  stop-color: var(--svg-color--ff6698, #FF6698);
  stop-opacity: 0;
}

.glk9ipbjn {
  fill: var(--svg-color--5e3781, #5E3781);
  d: path("M7.625 21.399h12.688c0 1.199-.625 2.171-2.172 2.171H9.797c-1.578 0-2.172-.972-2.172-2.171");
}

.gnctq-b_z {
  stop-color: var(--svg-color--d48759, #D48759);
}

.gomeqcb_w {
  width: 0.688px;
  height: 3.323px;
  x: 21.74px;
  y: 3.077px;
  fill: var(--svg-color--ffc590, #FFC590);
  rx: 0.344px;
}

.gw_49ss5a {
  stop-color: var(--svg-color--cfc0d3, #CFC0D3);
}

.h416f6fnu {
  stop-color: var(--svg-color--e0d3dc, #E0D3DC);
}

.he9c81qiu {
  stop-color: var(--svg-color--ec6089, #EC6089);
  stop-opacity: 0;
}

.hma9t4r2x {
  width: 0.688px;
  height: 3.312px;
  x: 17px;
  y: 2.969px;
  fill: var(--svg-color--ffc590, #FFC590);
  rx: 0.344px;
}

.hmen8pr-m {
  stop-color: var(--svg-color--ffcf61, #FFCF61);
}

.i82dke3zj {
  stop-color: var(--svg-color--d13a61, #D13A61);
}

.ir4ssmb3h {
  stop-color: var(--svg-color--e1a141, #E1A141);
}

.j26b871_k {
  stop-color: var(--svg-color--ed3d5a, #ED3D5A);
}

.jl8fambtc {
  stop-color: var(--svg-color--fff46a, #FFF46A);
}

.k35e4hb_t {
  d: path("M17 6.99c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1s1 .45 1 1v2.99c0 .55-.45 1-1 1");
}

.k3qmz6eds {
  stop-color: var(--svg-color--ff9161, #FF9161);
}

.k9mlr4brq {
  stop-color: var(--svg-color--f23967, #F23967);
}

.ka5fbcc2x {
  d: path("M16.85 10.77c-.716 0-1.32.52-1.439 1.211c-.023.136.09.249.229.249h2.41c.138 0 .252-.113.23-.249a1.45 1.45 0 0 0-1.43-1.211");
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.kwcsqv5-j {
  d: path("M19.5 8h-11C6.57 8 5 9.57 5 11.5v7C5 20.43 6.57 22 8.5 22h11c1.93 0 3.5-1.57 3.5-3.5v-7C23 9.57 21.43 8 19.5 8");
}

.kxv9t8boy {
  stop-color: var(--svg-color--fd3176, #FD3176);
}

.l6kr0-btg {
  stop-color: var(--svg-color--4c3364, #4C3364);
  stop-opacity: 0;
}

.lv30s1b8s {
  d: path("m15.47 26.35l-1.05-1.79a.487.487 0 0 0-.84 0l-1.06 1.8c-.01.02-.03.05-.04.07l-.01.01q-.225.405-.21.9c.04.91.8 1.65 1.71 1.67c.97.01 1.76-.77 1.76-1.73c0-.35-.09-.67-.26-.93");
}

.mivwqtr2w {
  d: path("M7.625 21.399h12.688c0 1.199-.625 2.171-2.172 2.171H9.797c-1.578 0-2.172-.972-2.172-2.171");
}

.mognwcnni {
  d: path("M19.783 11.969a.2.2 0 0 0 .193-.149l1.764-6.64l-.97-.25l-1.814 6.85a.15.15 0 0 0 .145.189z");
}

.n2wc5mgyw {
  d: path("M19.81 9H8.406c-1.431 0-2.592 1.218-2.592 2.719s1.16 2.719 2.592 2.719H19.81c1.43 0 2.592-1.219 2.592-2.72c0-1.5-1.161-2.718-2.592-2.718");
}

.n7gz0478b {
  d: path("M9.929 23.871a.562.562 0 0 1 1.067.356l-1.245 3.71a.25.25 0 0 0 .237.329h8.138a.25.25 0 0 0 .235-.336l-1.369-3.731A.53.53 0 1 1 18 23.871l1.719 5.16s.172.578-.532.578c-.703 0-9.898-.109-10.296-.109c-.399 0-.75-.36-.657-.64c.094-.282 1.695-4.989 1.695-4.989");
}

.nop1xdm5i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.125 14c-.437-.241-1.312-1.066-1.312-2.434C5.813 9.658 7.469 9 8.188 9");
}

.o9l81dywf {
  stop-color: var(--svg-color--ee407b, #EE407B);
}

.obffxh4jp {
  stop-color: var(--svg-color--ff4a86, #FF4A86);
}

.od1cyxt8v {
  stop-color: var(--svg-color--3c1c51, #3C1C51);
}

.otqslw08p {
  stop-color: var(--svg-color--654d7e, #654D7E);
  stop-opacity: 0;
}

.pai6k2fmm {
  stop-color: var(--svg-color--e5584c, #E5584C);
}

.pl4x7xb5b {
  stop-color: var(--svg-color--5f4e70, #5F4E70);
}

.plvbowb8z {
  stop-color: var(--svg-color--ec3a7b, #EC3A7B);
}

.pu-ak8_oj {
  d: path("M21.99 11.76c-.11-1-.96-1.77-1.99-1.77H8.01c-1.03 0-1.88.78-1.99 1.77A2.49 2.49 0 0 0 8.5 14h11c1.29 0 2.36-.98 2.49-2.24");
}

.q7u4pqklq {
  stop-color: var(--svg-color--ff5592, #FF5592);
  stop-opacity: 0;
}

.qcluucb0m {
  stop-color: var(--svg-color--51306c, #51306C);
}

.qrkswpfhq {
  stop-color: var(--svg-color--bca7af, #BCA7AF);
}

.qse46e-nd {
  fill: var(--svg-color--fa5361, #FA5361);
  d: path("m15.47 26.35l-1.05-1.79a.487.487 0 0 0-.84 0l-1.06 1.8c-.01.02-.03.05-.04.07l-.01.01q-.225.405-.21.9c.04.91.8 1.65 1.71 1.67c.97.01 1.76-.77 1.76-1.73c0-.35-.09-.67-.26-.93");
}

.rddrspb6n {
  stop-color: var(--svg-color--dd2b68, #DD2B68);
}

.s7i6iunaz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.966 10.274c.305.396.93 1.525.33 2.756c-.684 1.408-2.608 1.408-3.296 1.408");
}

.s8jyzob2r {
  d: path("M21 21.97v-1.54H7v1.54C7 23.09 7.91 24 9.03 24h.47l-1.67 5.01c-.16.49.2.99.71.99h10.92c.51 0 .87-.5.71-.99L18.5 24h-.03c1.12 0 2.53-.91 2.53-2.03m-3.19 5.96h-7.62L11.5 24h5z");
}

.scfbv3b8z {
  stop-color: var(--svg-color--fff776, #FFF776);
}

.ssj1pacja {
  stop-color: var(--svg-color--ff6099, #FF6099);
}

.t84zjbnde {
  stop-color: var(--svg-color--ff77a8, #FF77A8);
}

.tc1m68pch {
  stop-color: var(--svg-color--ff646b, #FF646B);
  stop-opacity: 0;
}

.u3lfh5b3a {
  stop-color: var(--svg-color--685b76, #685B76);
}

.u7d9x1bth {
  stop-color: var(--svg-color--f4da66, #F4DA66);
}

.ullkoib4b {
  stop-color: var(--svg-color--ff626c, #FF626C);
}

.v-cp05bob {
  stop-color: var(--svg-color--ff672c, #FF672C);
}

.v2xja2bhf {
  d: path("M17.5 4.99h-1v7.24h1z");
}

.vmr3cxbtw {
  d: path("M11.53 11.02c-.985 0-1.801.738-1.924 1.69c-.018.137.096.25.234.25h3.39c.138 0 .252-.113.234-.25a1.946 1.946 0 0 0-1.934-1.69");
}

.vp74cc3oh {
  stop-color: var(--svg-color--ff548f, #FF548F);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.wb2-7bubk {
  stop-color: var(--svg-color--ffff78, #FFFF78);
}

.wct088l7h {
  stop-color: var(--svg-color--ec356e, #EC356E);
}

.wymbu-kfy {
  stop-color: var(--svg-color--ff5489, #FF5489);
}

.x027k85me {
  stop-color: var(--svg-color--3f2f4b, #3F2F4B);
}

.xajmv0t3c {
  stop-color: var(--svg-color--4a2463, #4A2463);
  stop-opacity: 0;
}

.xiiozlb2v {
  stop-color: var(--svg-color--674588, #674588);
}

.yxxfxnbst {
  d: path("M20.74 6.99c-.53-.14-.85-.69-.71-1.22l.82-3.02c.14-.53.69-.85 1.22-.71s.85.69.71 1.22l-.82 3.02c-.14.53-.69.85-1.22.71");
}

.zj6or0bqf {
  stop-color: var(--svg-color--df773a, #DF773A);
}

.zktaqtb1j {
  stop-color: var(--svg-color--472961, #472961);
}

.zy4s2yt4l {
  stop-color: var(--svg-color--ffcd4f, #FFCD4F);
}

</style>
