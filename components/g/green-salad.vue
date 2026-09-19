<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6tyqNb)" class="pq5u7c1tu"/><path fill="url(#i8jAF1d)" class="h-gc5tbqq"/><path fill="url(#iZvPWPe)" class="b9wo73i0l"/><g filter="url(#ikDazHd)"><path class="j47g4-qic"/></g><path fill="url(#ijJ4MTd)" class="kr0slg9qs"/><path fill="url(#iuGPdNe)" class="kr0slg9qs"/><path fill="url(#iQ1ctIc)" class="kr0slg9qs"/><g filter="url(#iu6ugNe)"><path fill="url(#iiBSDBd)" class="byt4h236s"/></g><path fill="url(#iesybXc)" class="r62e8abbx"/><g filter="url(#iXCuqqc)"><path fill="url(#i9jhDhd)" class="iky3tpbsz"/></g><g filter="url(#iLARpmb)"><path fill="url(#iSFsYFf)" class="x8x_pqp8n"/></g><path fill="url(#i9X2Q5b)" class="yu6c3mg0d"/><path fill="url(#i2DeGlo)" class="n09pdybhj"/><g filter="url(#iWfFqHb)"><path stroke="url(#i6nNSWd)" class="ri18d5rvh"/></g><g filter="url(#ilQXqje)"><path class="xfm93obvu"/></g><path fill="url(#i15WeBd)" class="i_q73218x"/><g filter="url(#iQaione)"><path class="frdxa023o"/><path fill="url(#ihiMkBc)" class="h6i_5r70k"/></g><path fill="url(#iOP4z5c)" class="z8qzntigs"/><g filter="url(#iRXPE8d)"><path class="krxc5sb-y"/></g><path fill="url(#ibEfwye)" class="j6rd9go0h"/><path fill="url(#ik6vkTc)" class="qndbcrnoy"/><g filter="url(#ilKrhEc)"><path class="u1jx656-r"/></g><path fill="url(#iiOu4IZ)" class="qwmzuf0in"/><defs><linearGradient id="i6tyqNb" x1="2" x2="29.97" y1="20.125" y2="20.125" gradientUnits="userSpaceOnUse"><stop class="sc1u_j7oz"/><stop offset=".125" class="we77b0pzk"/><stop offset=".264" class="ag8w71dlt"/><stop offset=".509" class="v4koolh9x"/><stop offset=".751" class="osy8xlbkb"/><stop offset=".831" class="p33v3-s5s"/><stop offset="1" class="npop1zbsw"/></linearGradient><linearGradient id="i8jAF1d" x1="4.216" x2="27.754" y1="12.961" y2="12.961" gradientUnits="userSpaceOnUse"><stop class="rib4jdbyi"/><stop offset="1" class="aoo6bub-i"/></linearGradient><linearGradient id="iZvPWPe" x1="2" x2="29.438" y1="11.5" y2="11.5" gradientUnits="userSpaceOnUse"><stop class="eesfzfyvx"/><stop offset="1" class="wdsb961hc"/></linearGradient><linearGradient id="ijJ4MTd" x1="4.403" x2="28.625" y1="9.5" y2="9.5" gradientUnits="userSpaceOnUse"><stop class="zj33obcpy"/><stop offset=".319" class="obxpc5bdg"/><stop offset=".536" class="l2eqiubww"/><stop offset=".85" class="she7dvb4n"/><stop offset=".954" class="t5u_m5ovb"/></linearGradient><linearGradient id="iiBSDBd" x1="5.443" x2="27.156" y1="14.938" y2="14.938" gradientUnits="userSpaceOnUse"><stop class="it40yrtdm"/><stop offset=".513" class="s9ggw9bub"/><stop offset="1" class="xmq3e4bly"/></linearGradient><linearGradient id="iesybXc" x1="24.625" x2="22.003" y1="9.75" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="t3xifugno"/><stop offset="1" class="p87-7nbdd"/></linearGradient><linearGradient id="i9jhDhd" x1="24.985" x2="18.659" y1="7.05" y2="13.638" gradientUnits="userSpaceOnUse"><stop class="sgvnld7um"/><stop offset=".428" class="jwa-9_bnx"/><stop offset=".831" class="w-oirypws"/><stop offset="1" class="wynxrqjgs"/></linearGradient><linearGradient id="i9X2Q5b" x1="20.875" x2="23.063" y1="9.125" y2="11" gradientUnits="userSpaceOnUse"><stop offset=".056" class="aja9pub6b"/><stop offset=".313" class="z12u8vbgi"/></linearGradient><linearGradient id="i2DeGlo" x1="4.734" x2="27.375" y1="16.75" y2="16.75" gradientUnits="userSpaceOnUse"><stop class="mcyb3fbsz"/><stop offset=".696" class="lqpdybu0a"/></linearGradient><linearGradient id="i15WeBd" x1="8.219" x2="10.344" y1="16.156" y2="11.656" gradientUnits="userSpaceOnUse"><stop offset=".873" class="pt9ma_boh"/><stop offset="1" class="uo-s562ql"/></linearGradient><linearGradient id="iOP4z5c" x1="10.895" x2="9.844" y1="11.813" y2="14.406" gradientUnits="userSpaceOnUse"><stop class="rh5emubjf"/><stop offset=".176" class="lez2azurz"/></linearGradient><filter id="ikDazHd" width="28.469" height="15.813" x="1.656" y="5.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".25"/></filter><filter id="iu6ugNe" width="24.156" height="8.399" x="4" y="11.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".5"/></filter><filter id="iXCuqqc" width="7.941" height="8.688" x="18.121" y="5.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".125"/></filter><filter id="iLARpmb" width="7.313" height="6.531" x="15.506" y="3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".25"/></filter><filter id="iWfFqHb" width="15.75" height="3.726" x="11.875" y="13.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".25"/></filter><filter id="ilQXqje" width="5.561" height="5.561" x="10.292" y="14.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".5"/></filter><filter id="iQaione" width="9.008" height="6.59" x="6.095" y="10.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".125"/></filter><filter id="iRXPE8d" width="6.771" height="6.496" x="10.594" y="6.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".5"/></filter><filter id="ilKrhEc" width="5.041" height="4.808" x="20.938" y="12.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30610" stdDeviation=".25"/></filter><radialGradient id="iuGPdNe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.68755 8.62496 -7.5792 -5.8767 24.688 3)" gradientUnits="userSpaceOnUse"><stop class="lqz_a4b4f"/><stop offset="1" class="jgrkxrv0s"/></radialGradient><radialGradient id="iQ1ctIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.71875 -14.1704 0 16.045 15.563)" gradientUnits="userSpaceOnUse"><stop class="e9eccd7am"/><stop offset="1" class="q9ait3b4w"/></radialGradient><radialGradient id="iSFsYFf" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -4.39655 19.444 6.266)" gradientUnits="userSpaceOnUse"><stop class="px33zkcaf"/><stop offset="1" class="dofhwr34g"/></radialGradient><radialGradient id="i6nNSWd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 5.19072 -24.36683 -18.77719 24.688 15.122)" gradientUnits="userSpaceOnUse"><stop class="ezn2eebsi"/><stop offset=".272" class="khjjw7bni"/><stop offset="1" class="x5b6e_90y"/></radialGradient><radialGradient id="ihiMkBc" cx="0" cy="0" r="1" gradientTransform="matrix(-2 .25 -.27664 -2.21315 13.25 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="e6rxvkkwd"/><stop offset=".885" class="jz6inw3bz"/></radialGradient><radialGradient id="ibEfwye" cx="0" cy="0" r="1" gradientTransform="rotate(135.764 6.16 7.42)scale(3.31486)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="mtl3kpbcv"/><stop offset=".502" class="dag5yfban"/><stop offset="1" class="tgsjcsbyo"/></radialGradient><radialGradient id="ik6vkTc" cx="0" cy="0" r="1" gradientTransform="rotate(135.764 4.042 11.005)scale(3.21939)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="wz6tscbgz"/><stop offset=".502" class="efml7wbpa"/><stop offset="1" class="t7z2u4ydw"/></radialGradient><radialGradient id="iiOu4IZ" cx="0" cy="0" r="1" gradientTransform="rotate(135.764 9.816 12.11)scale(3.30917)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="rnn5h2thi"/><stop offset=".502" class="uh0irlzhc"/><stop offset="1" class="kob7sok8r"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:green-salad" /></template>
<style>
.ag8w71dlt {
  stop-color: var(--svg-color--bdb2cd, #BDB2CD);
}

.aja9pub6b {
  stop-color: var(--svg-color--962239, #962239);
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.b9wo73i0l {
  d: path("M21.97 6H10c-4.42 0-8 3.314-8 7.406s3.58 7.406 8 7.406h11.97c4.42 0 8-3.314 8-7.406S26.39 6 21.97 6");
}

.byt4h236s {
  d: path("M27.156 15.074c-.504-.718-2.675-2.371-5.29-2.468c-2.83-.105-4.129 1.547-5.872 1.547c-1.208 0-4.35-1.647-5.856-1.547c-3.347.24-4.251 1.468-5.138 2.687c.612 1.656 2.182 2.815 4.801 3.297c2.462.453 9.73.553 11.973.188s4.48-1.375 5.382-3.704");
}

.dag5yfban {
  stop-color: var(--svg-color--f5d03b, #F5D03B);
}

.dofhwr34g {
  stop-color: var(--svg-color--87bb71, #87BB71);
  stop-opacity: 0;
}

.e6rxvkkwd {
  stop-color: var(--svg-color--ad1a46, #AD1A46);
}

.e9eccd7am {
  stop-color: var(--svg-color--306420, #306420);
}

.eesfzfyvx {
  stop-color: var(--svg-color--b5b5ba, #B5B5BA);
}

.efml7wbpa {
  stop-color: var(--svg-color--f3c046, #F3C046);
}

.ezn2eebsi {
  stop-color: var(--svg-color--91ba60, #91BA60);
}

.frdxa023o {
  fill: var(--svg-color--cf336f, #CF336F);
  d: path("M9.077 16.196a4.6 4.6 0 0 0 5.684-1.637c.231-.347-.003-.662-.386-.84l-7.054-3.123c-.392-.178-.735-.12-.842.289c-.525 2.126.525 4.394 2.598 5.31");
}

.ft5dv1b6b {
  fill: none;
}

.h-gc5tbqq {
  d: path("M21.97 7.18c3.19 0 5.78 2.59 5.78 5.78s-2.59 5.78-5.78 5.78H10c-3.19 0-5.78-2.59-5.78-5.78S6.81 7.18 10 7.18z");
}

.h6i_5r70k {
  d: path("M9.077 16.196a4.6 4.6 0 0 0 5.684-1.637c.231-.347-.003-.662-.386-.84l-7.054-3.123c-.392-.178-.735-.12-.842.289c-.525 2.126.525 4.394 2.598 5.31");
}

.i_q73218x {
  d: path("M8.886 16.533c2.33 1.03 5.02.21 6.39-1.84c.26-.39.11-.93-.32-1.13l-7.93-3.51c-.44-.2-.94.05-1.06.51c-.59 2.39.59 4.94 2.92 5.97");
}

.iky3tpbsz {
  d: path("M24.66 12.573a4.96 4.96 0 0 0 .074-6.264c-.276-.349-.617-.283-.902.066l-5.211 6.198c-.285.34-.377.782 0 1.017a4.704 4.704 0 0 0 6.04-1.017");
}

.it40yrtdm {
  stop-color: var(--svg-color--154428, #154428);
}

.j47g4-qic {
  fill: var(--svg-color--dddae4, #DDDAE4);
  d: path("M21.768 6.188H10.013c-4.34 0-7.857 3.314-7.857 7.406S5.672 21 10.013 21h11.755c4.341 0 7.857-3.314 7.857-7.406s-3.516-7.406-7.857-7.406");
}

.j6rd9go0h {
  d: path("M14.62 11.084a1.833 1.833 0 1 0 0-3.666a1.833 1.833 0 0 0 0 3.666");
}

.jgrkxrv0s {
  stop-color: var(--svg-color--67a257, #67A257);
  stop-opacity: 0;
}

.jwa-9_bnx {
  stop-color: var(--svg-color--d13464, #D13464);
}

.jz6inw3bz {
  stop-color: var(--svg-color--ae1a49, #AE1A49);
  stop-opacity: 0;
}

.khjjw7bni {
  stop-color: var(--svg-color--74a048, #74A048);
}

.kob7sok8r {
  stop-color: var(--svg-color--b28433, #B28433);
}

.kr0slg9qs {
  d: path("M27.172 11.406c-1.279-2.485-3.14-2.5-4.75-3.61S20.727 5.993 19.81 4.84a4.862 4.862 0 0 0-7.62 0c-1.124 1.41-1.221 2.41-2.471 3.082c-1.842.99-3.62.525-4.907 3.969c-.63 1.686-.454 2.89 0 3.906c1.412 3.152 6.047 3.484 11.235 3.484s7.234-.11 9.36-1.5c2.483-1.625 2.711-4.535 1.765-6.375");
}

.krxc5sb-y {
  fill: var(--svg-color--346433, #346433);
  d: path("M13.76 12c1.195 0 2.605-1.134 2.605-2.33s-.97-2.166-2.166-2.166s-2.605 1.439-2.605 2.635S12.564 12 13.759 12");
}

.l2eqiubww {
  stop-color: var(--svg-color--5c9248, #5C9248);
}

.lez2azurz {
  stop-color: var(--svg-color--b03256, #B03256);
}

.lqpdybu0a {
  stop-color: var(--svg-color--66933a, #66933A);
}

.lqz_a4b4f {
  stop-color: var(--svg-color--5e9b4b, #5E9B4B);
}

.mcyb3fbsz {
  stop-color: var(--svg-color--4b7740, #4B7740);
}

.mtl3kpbcv {
  stop-color: var(--svg-color--ffec56, #FFEC56);
}

.n09pdybhj {
  d: path("M27.375 15.375c-.516-.719-2.733-2.372-5.406-2.469c-2.893-.105-4.219 1.547-6 1.547c-1.235 0-4.445-1.647-5.985-1.547c-3.42.24-4.343 1.469-5.25 2.688c.625 1.656 2.23 2.815 4.907 3.297c2.515.453 9.941.552 12.234.187s4.578-1.375 5.5-3.703");
}

.npop1zbsw {
  stop-color: var(--svg-color--d8d7de, #D8D7DE);
}

.obxpc5bdg {
  stop-color: var(--svg-color--437943, #437943);
}

.osy8xlbkb {
  stop-color: var(--svg-color--baadcc, #BAADCC);
}

.p33v3-s5s {
  stop-color: var(--svg-color--bfb5ce, #BFB5CE);
}

.p87-7nbdd {
  stop-color: var(--svg-color--9b2938, #9B2938);
}

.pq5u7c1tu {
  d: path("M18.69 30h-5.41C5.531 30 2 24.793 2 18.383V12.96h27.97v5.423C29.97 24.793 26.563 30 18.69 30");
}

.pt9ma_boh {
  stop-color: var(--svg-color--ab2c59, #AB2C59);
}

.px33zkcaf {
  stop-color: var(--svg-color--86b76d, #86B76D);
}

.q9ait3b4w {
  stop-color: var(--svg-color--396929, #396929);
  stop-opacity: 0;
}

.qndbcrnoy {
  d: path("M13.517 18.64a1.78 1.78 0 1 0 0-3.56a1.78 1.78 0 0 0 0 3.56");
}

.qwmzuf0in {
  d: path("M24.17 16.582a1.83 1.83 0 1 0 0-3.66a1.83 1.83 0 0 0 0 3.66");
}

.r62e8abbx {
  d: path("M24.836 12.72a5.155 5.155 0 0 0 .08-6.63a.753.753 0 0 0-1.167-.01l-5.642 6.56a.767.767 0 0 0 .189 1.157a5.18 5.18 0 0 0 6.54-1.077");
}

.rh5emubjf {
  stop-color: var(--svg-color--c34765, #C34765);
}

.ri18d5rvh {
  stroke-linecap: round;
  d: path("M12.875 14.875c.708.313 2.219.813 4.156.813c1.938 0 2.469-1.594 5.282-1.47c2.25.1 4 1.24 4.312 1.72");
}

.rib4jdbyi {
  stop-color: var(--svg-color--5e669c, #5E669C);
}

.rnn5h2thi {
  stop-color: var(--svg-color--ffe75c, #FFE75C);
}

.s9ggw9bub {
  stop-color: var(--svg-color--376728, #376728);
}

.sc1u_j7oz {
  stop-color: var(--svg-color--bbbac0, #BBBAC0);
}

.sgvnld7um {
  stop-color: var(--svg-color--d7355d, #D7355D);
}

.she7dvb4n {
  stop-color: var(--svg-color--5f9231, #5F9231);
}

.t3xifugno {
  stop-color: var(--svg-color--f05879, #F05879);
}

.t5u_m5ovb {
  stop-color: var(--svg-color--3c8511, #3C8511);
}

.t7z2u4ydw {
  stop-color: var(--svg-color--ba8544, #BA8544);
}

.tgsjcsbyo {
  stop-color: var(--svg-color--ac831e, #AC831E);
}

.u1jx656-r {
  fill: var(--svg-color--588d2f, #588D2F);
  d: path("M23.219 17.125c1.01 0 2.26-.967 2.26-1.978c0-1.01-.82-1.83-1.83-1.83s-2.212 1.141-2.212 2.152c0 1.01.771 1.656 1.782 1.656");
}

.uh0irlzhc {
  stop-color: var(--svg-color--ecbf40, #ECBF40);
}

.uo-s562ql {
  stop-color: var(--svg-color--e0427a, #E0427A);
}

.v4koolh9x {
  stop-color: var(--svg-color--bbadcd, #BBADCD);
}

.w-oirypws {
  stop-color: var(--svg-color--bb3463, #BB3463);
}

.wdsb961hc {
  stop-color: var(--svg-color--f5f6fb, #F5F6FB);
}

.we77b0pzk {
  stop-color: var(--svg-color--bcb5c9, #BCB5C9);
}

.wynxrqjgs {
  stop-color: var(--svg-color--a82b5b, #A82B5B);
}

.wz6tscbgz {
  stop-color: var(--svg-color--ffdb57, #FFDB57);
}

.x5b6e_90y {
  stop-color: var(--svg-color--709d4a, #709D4A);
  stop-opacity: 0;
}

.x8x_pqp8n {
  d: path("M21.486 8.904a.5.5 0 0 0 .665-.746zm-2.183-3.091l.408-.29zm-2.672-2.297a.5.5 0 1 0-.25.968zm5.52 4.642c-.771-.689-1.39-1.157-2.44-2.635l-.816.579c1.123 1.58 1.821 2.116 2.59 2.802zm-2.44-2.635c-.864-1.216-2.298-1.806-3.08-2.007l-.25.968c.677.174 1.846.677 2.514 1.618z");
}

.xfm93obvu {
  fill: var(--svg-color--447437, #447437);
  d: path("M13.072 18.905a1.78 1.78 0 1 0 0-3.56a1.78 1.78 0 0 0 0 3.56");
}

.xmq3e4bly {
  stop-color: var(--svg-color--3b830f, #3B830F);
}

.yu6c3mg0d {
  d: path("M23.073 11.143c1-1.16.87-2.91-.29-3.91l-3.62 4.2c1.16 1.01 2.91.87 3.91-.29");
}

.z12u8vbgi {
  stop-color: var(--svg-color--ae3153, #AE3153);
}

.z8qzntigs {
  d: path("M9.86 14.426a2.855 2.855 0 0 0 3.767-1.45L8.409 10.66a2.855 2.855 0 0 0 1.451 3.766");
}

.zj33obcpy {
  stop-color: var(--svg-color--1a4a2d, #1A4A2D);
}

</style>
