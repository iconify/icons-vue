<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJBzByd)" class="xrtm1txiw"/><circle fill="url(#iFlabYb)" class="jzb_ltunx"/><circle fill="url(#iOtPrNc)" class="jzb_ltunx"/><path fill="url(#id3Y9Vc)" class="z3m6y1asi"/><path fill="url(#i7VvUFb)" class="z3m6y1asi"/><circle fill="url(#idV1Q8d)" class="sav4kjb-k"/><path fill="url(#iCNH6Ic)" class="jlbw96-5f"/><path fill="url(#iulZMze)" class="jlbw96-5f"/><path fill="url(#iGlzXfc)" class="ikaolobhy"/><path fill="url(#i8YRsRb)" class="ikaolobhy"/><path fill="url(#ipwUtEd)" class="ikaolobhy"/><path fill="url(#iJ0Ftpb)" class="zgck-bbwz"/><path fill="url(#iRrN4dI)" class="zgck-bbwz"/><path fill="url(#iO4NYCz)" class="gfu-veezx"/><path fill="url(#ibcezed)" class="gfu-veezx"/><path fill="url(#iIvqRFb)" class="gfu-veezx"/><g filter="url(#iRZmAIb)"><path fill="url(#iwqTDsv)" class="hijya1u-v"/><path fill="url(#iyfF6Zk)" class="hijya1u-v"/><path fill="url(#iCqnw3b)" class="hijya1u-v"/><path fill="url(#iVa4fic)" class="hijya1u-v"/><path fill="url(#iiM79Ac)" class="hijya1u-v"/></g><path fill="url(#iu7pWic)" class="pk6egkgbi"/><path fill="url(#isCj34c)" class="pk6egkgbi"/><path fill="url(#iaEOqQd)" class="pk6egkgbi"/><path fill="url(#iMYJlGe)" class="hyhdijb9w"/><path fill="url(#icH2Yjh)" class="hyhdijb9w"/><path fill="url(#iH2UivN)" class="hyhdijb9w"/><path fill="url(#i65fsCc)" class="hyhdijb9w"/><path fill="url(#iBmBXEc)" class="hyhdijb9w"/><path fill="url(#ifhYIWd)" class="hyhdijb9w"/><path fill="url(#ix0sTEc)" class="hyhdijb9w"/><path fill="url(#i24RAsb)" class="hyhdijb9w"/><path fill="url(#inXFTUd)" class="hyhdijb9w"/><path fill="url(#imNK5ae)" class="hyhdijb9w"/><path fill="url(#iwUCQHb)" class="gh4-qqf4z"/><circle fill="url(#iVPv07c)" class="omv2z3g7g"/><path class="ctwjf1bar"/><path fill="url(#idHqm0b)" class="claojaciv"/><path fill="url(#isR7ffe)" class="claojaciv"/><path fill="url(#iybblxd)" class="claojaciv"/><defs><radialGradient id="iFlabYb" cx="0" cy="0" r="1" gradientTransform="rotate(18.433 -21.777 74.099)scale(1.97661)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="jj5cdccop"/><stop offset=".755" class="d0sr0mj_m"/></radialGradient><radialGradient id="iOtPrNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.95312 -2.40625 1.11989 .909 23.734 12.61)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="n3c1egwmp"/><stop offset="1" class="rab648bmq"/></radialGradient><radialGradient id="id3Y9Vc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.32 16.481 -.381)scale(2.46954 5.0951)" gradientUnits="userSpaceOnUse"><stop offset=".581" class="ckksfbcgk"/><stop offset="1" class="kocxw6bmh"/></radialGradient><radialGradient id="i7VvUFb" cx="0" cy="0" r="1" gradientTransform="rotate(-42.709 28.356 -23.975)scale(1.65861 2.55667)" gradientUnits="userSpaceOnUse"><stop offset=".564" class="n3c1egwmp"/><stop offset=".728" class="rab648bmq"/></radialGradient><radialGradient id="idV1Q8d" cx="0" cy="0" r="1" gradientTransform="rotate(152.354 10.857 9.447)scale(6.19123)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="qqx4uox8a"/><stop offset="1" class="yr7vi6b6s"/></radialGradient><radialGradient id="iwqTDsv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.72958 21.4715 0 16 24.104)" gradientUnits="userSpaceOnUse"><stop class="fkgczsbpb"/><stop offset="1" class="b-q19-ame"/></radialGradient><radialGradient id="iyfF6Zk" cx="0" cy="0" r="1" gradientTransform="rotate(50.356 -11.569 20.454)scale(8.52249 5.18342)" gradientUnits="userSpaceOnUse"><stop class="cg6fcsbgd"/><stop offset="1" class="avmxvfhet"/></radialGradient><radialGradient id="iCqnw3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.6982 -5.0046 0 27 12.24)" gradientUnits="userSpaceOnUse"><stop class="ec8meab_v"/><stop offset="1" class="miyqfeb8s"/></radialGradient><radialGradient id="iVa4fic" cx="0" cy="0" r="1" gradientTransform="rotate(110.45 2.642 15.406)scale(3.93551 2.5757)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="c5o74q36w"/><stop offset="1" class="m2_iuc26m"/></radialGradient><radialGradient id="iiM79Ac" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 -4 5.96178 5.03025 5 28.125)" gradientUnits="userSpaceOnUse"><stop class="if-a4468e"/><stop offset="1" class="o6nrhcblm"/></radialGradient><radialGradient id="iu7pWic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.04422 11.7897 0 16 27)" gradientUnits="userSpaceOnUse"><stop class="mton8ob5v"/><stop offset="1" class="tb-5ocvtz"/></radialGradient><radialGradient id="isCj34c" cx="0" cy="0" r="1" gradientTransform="rotate(-31.396 53.482 2.764)scale(10.3168 13.9517)" gradientUnits="userSpaceOnUse"><stop class="rwdbqybca"/><stop offset="1" class="ktaemoyai"/></radialGradient><radialGradient id="iaEOqQd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.877 19.827 8.33)scale(9.34232 9.40426)" gradientUnits="userSpaceOnUse"><stop class="bsw-h0bny"/><stop offset="1" class="hmdkkkbdt"/></radialGradient><radialGradient id="icH2Yjh" cx="0" cy="0" r="1" gradientTransform="matrix(-.573 .51313 -.45275 -.50557 17.281 6.955)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="q3m8m7bhy"/><stop offset="1" class="vxrp39aul"/></radialGradient><radialGradient id="iH2UivN" cx="0" cy="0" r="1" gradientTransform="matrix(.46182 1.13226 -.999 .40747 15.28 6.713)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="uhy_-rb7u"/><stop offset="1" class="gsrhrkoli"/></radialGradient><radialGradient id="i65fsCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47038 -.1283 .17765 -.65129 18.564 7.854)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iBmBXEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.77826 .3763 -.27793 -.5748 19.547 8.563)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="ifhYIWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95786 -.11118 .06266 -.53979 19.736 10.026)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="ix0sTEc" cx="0" cy="0" r="1" gradientTransform="matrix(.62958 -.60722 .58498 .60653 18.872 11.146)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="i24RAsb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.747 10.092 1.836)scale(.67058 .64602)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="inXFTUd" cx="0" cy="0" r="1" gradientTransform="matrix(.61577 .29078 -.35145 .74424 13.903 8.674)" gradientUnits="userSpaceOnUse"><stop class="mulvig9sp"/><stop offset="1" class="a_xm9geyk"/></radialGradient><radialGradient id="imNK5ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.62976 -.48346 .4561 -.59413 17.968 12.117)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="rwhrj1bde"/><stop offset="1" class="tzt2apygr"/></radialGradient><radialGradient id="iwUCQHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81628 3.4538 -4.2651 -2.24293 17.996 8.285)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="l5q-yw4hp"/><stop offset="1" class="hemkrl1wk"/><stop offset="1" class="mb-8qkb0z"/></radialGradient><radialGradient id="iVPv07c" cx="0" cy="0" r="1" gradientTransform="rotate(-115.017 7.692 3.612)scale(1.55184)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="juyym3i1q"/><stop offset="1" class="onpunqbdc"/></radialGradient><radialGradient id="isR7ffe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.90625 1.5625 -1.31178 -2.4399 10.563 13.313)" gradientUnits="userSpaceOnUse"><stop class="mo-uprqwm"/><stop offset="1" class="d3lwzza3u"/></radialGradient><radialGradient id="iybblxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43749 2.31292 -1.87498 -1.1653 6.875 10.688)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="kq-56mbfo"/><stop offset="1" class="mmegx4b2l"/></radialGradient><linearGradient id="iJBzByd" x1="16" x2="16" y1="5" y2="27" gradientUnits="userSpaceOnUse"><stop class="i_ei5ytle"/><stop offset=".615" class="anz6tyupo"/></linearGradient><linearGradient id="iCNH6Ic" x1="3.5" x2="3.5" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="td4-p0dkm"/><stop offset=".272" class="xab4mnbco"/><stop offset=".798" class="xab4mnbco"/><stop offset="1" class="td4-p0dkm"/></linearGradient><linearGradient id="iulZMze" x1="4.091" x2="3.867" y1="28.105" y2="27.863" gradientUnits="userSpaceOnUse"><stop class="j121lgb-t"/><stop offset="1" class="sjc3-9bdn"/></linearGradient><linearGradient id="iGlzXfc" x1="10.571" x2="31.634" y1="28.999" y2="28.999" gradientUnits="userSpaceOnUse"><stop class="q2_6ohbff"/><stop offset="1" class="m_tcnjc4n"/></linearGradient><linearGradient id="i8YRsRb" x1="16" x2="16" y1="30.563" y2="29.188" gradientUnits="userSpaceOnUse"><stop class="klk37t6on"/><stop offset="1" class="cvtbr9bcm"/></linearGradient><linearGradient id="ipwUtEd" x1="27.868" x2="27.64" y1="27.754" y2="27.983" gradientUnits="userSpaceOnUse"><stop class="x6nwj1bix"/><stop offset="1" class="ic-s051kk"/></linearGradient><linearGradient id="iJ0Ftpb" x1="28.5" x2="28.5" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="dod6c01qp"/><stop offset="1" class="oe7uqyb2h"/></linearGradient><linearGradient id="iRrN4dI" x1="28.156" x2="28.293" y1="3.75" y2="3.891" gradientUnits="userSpaceOnUse"><stop class="w7ztfpbfa"/><stop offset="1" class="erd22x04o"/></linearGradient><linearGradient id="iO4NYCz" x1="27.37" x2="3.606" y1="4.372" y2="4.372" gradientUnits="userSpaceOnUse"><stop class="k5eylmbyi"/><stop offset="1" class="kojernb8s"/></linearGradient><linearGradient id="ibcezed" x1="16" x2="16" y1="5" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="upe90mbyo"/><stop offset="1" class="rgog1yb5w"/></linearGradient><linearGradient id="iIvqRFb" x1="3.911" x2="4.456" y1="4.135" y2="3.632" gradientUnits="userSpaceOnUse"><stop class="zb_q4kb0f"/><stop offset="1" class="c8--neo2k"/></linearGradient><linearGradient id="iMYJlGe" x1="18.453" x2="15.329" y1="7.653" y2="11.64" gradientUnits="userSpaceOnUse"><stop class="s91ts3bpo"/><stop offset="1" class="uc7451bcz"/></linearGradient><linearGradient id="idHqm0b" x1="7.063" x2="7.063" y1="16" y2="15.125" gradientUnits="userSpaceOnUse"><stop class="k4dvoqbwv"/><stop offset="1" class="l0aqi3uzt"/></linearGradient><filter id="iRZmAIb" width="22" height="14.861" x="5" y="12.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4242"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:framed-picture" /></template>
<style>
.a_xm9geyk {
  stop-color: var(--svg-color--f0851d, #F0851D);
  stop-opacity: 0;
}

.anz6tyupo {
  stop-color: var(--svg-color--85d6f5, #85D6F5);
}

.avmxvfhet {
  stop-color: var(--svg-color--4dc277, #4DC277);
  stop-opacity: 0;
}

.b-q19-ame {
  stop-color: var(--svg-color--35bd69, #35BD69);
}

.bsw-h0bny {
  stop-color: var(--svg-color--93eb81, #93EB81);
}

.c5o74q36w {
  stop-color: var(--svg-color--4ca876, #4CA876);
}

.c8--neo2k {
  stop-color: var(--svg-color--c77731, #C77731);
  stop-opacity: 0;
}

.cg6fcsbgd {
  stop-color: var(--svg-color--4dc277, #4DC277);
}

.ckksfbcgk {
  stop-color: var(--svg-color--dedfff, #DEDFFF);
}

.claojaciv {
  d: path("M5 16v-6a3.07 3.07 0 0 1 2.45 2.013a.11.11 0 0 0 .161.054A2.14 2.14 0 1 1 8.781 16z");
}

.ctwjf1bar {
  fill: var(--svg-color--dfdeff, #DFDEFF);
  d: path("M5 16v-6a3.07 3.07 0 0 1 2.45 2.013a.11.11 0 0 0 .161.054A2.14 2.14 0 1 1 8.781 16z");
}

.cvtbr9bcm {
  stop-color: var(--svg-color--d47f6e, #D47F6E);
  stop-opacity: 0;
}

.d0sr0mj_m {
  stop-color: var(--svg-color--dddcff, #DDDCFF);
}

.d3lwzza3u {
  stop-color: var(--svg-color--f2f3ff, #F2F3FF);
  stop-opacity: 0;
}

.dod6c01qp {
  stop-color: var(--svg-color--ca7c50, #CA7C50);
}

.ec8meab_v {
  stop-color: var(--svg-color--3bcc74, #3BCC74);
}

.erd22x04o {
  stop-color: var(--svg-color--c2712e, #C2712E);
  stop-opacity: 0;
}

.fkgczsbpb {
  stop-color: var(--svg-color--2dac5b, #2DAC5B);
}

.ft5dv1b6b {
  fill: none;
}

.gfu-veezx {
  d: path("M27 5H5L2 2h28z");
}

.gh4-qqf4z {
  d: path("M16.755 11.738a2.187 2.187 0 1 0 0-4.373a2.187 2.187 0 0 0 0 4.373");
}

.gsrhrkoli {
  stop-color: var(--svg-color--ff942a, #FF942A);
  stop-opacity: 0;
}

.hemkrl1wk {
  stop-color: var(--svg-color--dca21c, #DCA21C);
}

.hijya1u-v {
  d: path("M7.51 17.808L5 19.248V27h22V12.24c-1.5 0-2.5.491-4 1.967l-4.5 4.429c-1 .984-1.928 1.364-2.928.872c-.333-.164-1.537-.928-3.043-1.781c-1.552-.879-3.901-.615-5.018.081");
}

.hmdkkkbdt {
  stop-color: var(--svg-color--93eb81, #93EB81);
  stop-opacity: 0;
}

.hyhdijb9w {
  d: path("M16.25 6.934c.311-.351.735-.295 1.006 0l.166.191c.057.062.14.095.224.088l.294-.088c.4-.086.765.213.765.678v.175c.008.095.092.16.178.202l.266.11c.384.189.48.634.2 1.008l-.08.104c-.07.097-.056.223.015.32l.08.111c.289.357.126.845-.283 1.016l-.229.096c-.086.036-.12.097-.136.19l-.016.298a.633.633 0 0 1-.712.555l-.349-.093a.25.25 0 0 0-.243.103l-.126.172c-.311.351-.732.293-.944.087l-.232-.28c-.06-.06-.137-.11-.229-.075l-.35.096c-.29.04-.63-.182-.685-.469l-.04-.415a.27.27 0 0 0-.154-.197l-.246-.085a.64.64 0 0 1-.28-.938l.138-.191a.27.27 0 0 0-.007-.296l-.104-.146c-.292-.417-.09-.882.344-1.022l.095-.03c.106-.035.208-.123.217-.233l.021-.268c.035-.436.432-.686.85-.559l.135.041a.26.26 0 0 0 .304-.07z");
}

.i_ei5ytle {
  stop-color: var(--svg-color--a6e5f7, #A6E5F7);
}

.ic-s051kk {
  stop-color: var(--svg-color--c67331, #C67331);
  stop-opacity: 0;
}

.if-a4468e {
  stop-color: var(--svg-color--399e60, #399E60);
}

.ikaolobhy {
  d: path("m5 27l-3 3h28l-3-3z");
}

.j121lgb-t {
  stop-color: var(--svg-color--cb7734, #CB7734);
}

.jj5cdccop {
  stop-color: var(--svg-color--d4d5ff, #D4D5FF);
}

.jlbw96-5f {
  d: path("M5 5L2 2v28l3-3z");
}

.juyym3i1q {
  stop-color: var(--svg-color--ebeaff, #EBEAFF);
}

.jzb_ltunx {
  cx: 24.188px;
  cy: 12.127px;
  r: 2.068px;
}

.k4dvoqbwv {
  stop-color: var(--svg-color--cfc9ff, #CFC9FF);
}

.k5eylmbyi {
  stop-color: var(--svg-color--d99569, #D99569);
}

.klk37t6on {
  stop-color: var(--svg-color--d47f6e, #D47F6E);
}

.kocxw6bmh {
  stop-color: var(--svg-color--d8d9ff, #D8D9FF);
}

.kojernb8s {
  stop-color: var(--svg-color--d28459, #D28459);
}

.kq-56mbfo {
  stop-color: var(--svg-color--f4f4ff, #F4F4FF);
}

.ktaemoyai {
  stop-color: var(--svg-color--79c56c, #79C56C);
  stop-opacity: 0;
}

.ku2pfdbii {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
  stop-opacity: 0;
}

.kypg0578v {
  stop-color: var(--svg-color--e0762a, #E0762A);
}

.l0aqi3uzt {
  stop-color: var(--svg-color--cfc9ff, #CFC9FF);
  stop-opacity: 0;
}

.l5q-yw4hp {
  stop-color: var(--svg-color--ffcb38, #FFCB38);
}

.m_tcnjc4n {
  stop-color: var(--svg-color--d3895c, #D3895C);
}

.m2_iuc26m {
  stop-color: var(--svg-color--4ca876, #4CA876);
  stop-opacity: 0;
}

.mb-8qkb0z {
  stop-color: var(--svg-color--e5ae1b, #E5AE1B);
}

.miyqfeb8s {
  stop-color: var(--svg-color--3bcc74, #3BCC74);
  stop-opacity: 0;
}

.mmegx4b2l {
  stop-color: var(--svg-color--f4f4ff, #F4F4FF);
  stop-opacity: 0;
}

.mo-uprqwm {
  stop-color: var(--svg-color--f2f3ff, #F2F3FF);
}

.mton8ob5v {
  stop-color: var(--svg-color--7fd86c, #7FD86C);
}

.mulvig9sp {
  stop-color: var(--svg-color--f0851d, #F0851D);
}

.n3c1egwmp {
  stop-color: var(--svg-color--efefff, #EFEFFF);
}

.o6nrhcblm {
  stop-color: var(--svg-color--399e60, #399E60);
  stop-opacity: 0;
}

.oe7uqyb2h {
  stop-color: var(--svg-color--e0966b, #E0966B);
}

.omv2z3g7g {
  cx: 7.5px;
  cy: 12.328px;
  r: 1.516px;
}

.onpunqbdc {
  stop-color: var(--svg-color--d5d8ff, #D5D8FF);
}

.pk6egkgbi {
  d: path("M27 26.812V27H5v-.189c2.564-2.579 6.538-4.311 11-4.311s8.436 1.732 11 4.311");
}

.pud-xubcs {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
}

.q2_6ohbff {
  stop-color: var(--svg-color--e69f70, #E69F70);
}

.q3m8m7bhy {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
}

.qqx4uox8a {
  stop-color: var(--svg-color--eef, #EEF);
}

.rab648bmq {
  stop-color: var(--svg-color--efefff, #EFEFFF);
  stop-opacity: 0;
}

.rgog1yb5w {
  stop-color: var(--svg-color--cc8159, #CC8159);
  stop-opacity: 0;
}

.rwdbqybca {
  stop-color: var(--svg-color--79c56c, #79C56C);
}

.rwhrj1bde {
  stop-color: var(--svg-color--e3745b, #E3745B);
}

.s91ts3bpo {
  stop-color: var(--svg-color--fc8b23, #FC8B23);
}

.sav4kjb-k {
  cx: 22.307px;
  cy: 14.733px;
  r: 3.244px;
}

.sjc3-9bdn {
  stop-color: var(--svg-color--cb7734, #CB7734);
  stop-opacity: 0;
}

.tb-5ocvtz {
  stop-color: var(--svg-color--9fd660, #9FD660);
}

.td4-p0dkm {
  stop-color: var(--svg-color--d38e57, #D38E57);
}

.tzt2apygr {
  stop-color: var(--svg-color--e3745b, #E3745B);
  stop-opacity: 0;
}

.uc7451bcz {
  stop-color: var(--svg-color--e67639, #E67639);
}

.uhy_-rb7u {
  stop-color: var(--svg-color--ff942a, #FF942A);
}

.upe90mbyo {
  stop-color: var(--svg-color--cc8159, #CC8159);
}

.vxrp39aul {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
  stop-opacity: 0;
}

.w7ztfpbfa {
  stop-color: var(--svg-color--c2712e, #C2712E);
}

.x6nwj1bix {
  stop-color: var(--svg-color--c67331, #C67331);
}

.xab4mnbco {
  stop-color: var(--svg-color--efa570, #EFA570);
}

.xrtm1txiw {
  d: path("M5 5h22v22H5z");
}

.yiqe49k2f {
  stop-color: var(--svg-color--e0762a, #E0762A);
  stop-opacity: 0;
}

.yr7vi6b6s {
  stop-color: var(--svg-color--d4d3ff, #D4D3FF);
}

.z3m6y1asi {
  d: path("M23.267 12.987C24.33 10.54 26.182 9.327 27 9.153v5.554h-2.314z");
}

.zb_q4kb0f {
  stop-color: var(--svg-color--c77731, #C77731);
}

.zgck-bbwz {
  d: path("m27 27l3 3V2l-3 3z");
}

</style>
