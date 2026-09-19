<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iFErVAj)" class="q3rd4utmq"/><path fill="url(#iuL2Qrc)" class="q3rd4utmq"/><g filter="url(#iFzocKe)"><path class="a6po_3bze"/><path fill="url(#inNTAWb)" class="w6kvlmbkl"/></g><g filter="url(#iWkcRnb)"><path fill="url(#i8BKlws)" class="fva_2_1ff"/></g><path class="u-vgmfbve"/><path fill="url(#iM4AiLd)" class="gylmc1-wl"/><path fill="url(#iBOG8Ac)" class="gylmc1-wl"/><path fill="url(#i4nRUid)" class="gylmc1-wl"/><g filter="url(#iujb3Yd)"><path class="vtq3g8n2e"/></g><path fill="url(#iffrfid)" class="uhjk3chrv"/><path fill="url(#iwbqCDb)" class="uhjk3chrv"/><path fill="url(#iQ31Pdc)" class="uhjk3chrv"/><path fill="url(#iBKmM1d)" class="uhjk3chrv"/><g filter="url(#iIfXrIc)"><path fill="url(#iDNVPKc)" class="hntovz6gr"/></g><path fill="url(#imevdEb)" class="vsvggzdaj"/><path fill="url(#isv7DKb)" class="vsvggzdaj"/><path fill="url(#iD3cinc)" class="vsvggzdaj"/><path fill="url(#i0QUjvd)" class="iyrp2rbac"/><path fill="url(#i6ROzCd)" class="iyrp2rbac"/><path fill="url(#iXgl6re)" class="iyrp2rbac"/><path fill="url(#ipUyWie)" class="iyrp2rbac"/><path fill="url(#ioeBRdc)" class="iyrp2rbac"/><g filter="url(#iZXpwVc)"><path fill="url(#iFdLPEe)" class="c2l7k0bjd"/><path fill="url(#i4SSuPc)" class="c2l7k0bjd"/></g><g filter="url(#i1pjIkL)"><path class="scv3u8uqx"/></g><g filter="url(#igA1nBY)"><path fill="url(#iWyaivO)" class="mr3r47b2c"/></g><g filter="url(#iV2H5Fc)"><path fill="url(#i96rL8b)" class="b9i0liusy"/></g><g filter="url(#i0bgYgc)"><path class="j6mk_lhat"/></g><g filter="url(#i2PnUdb)"><circle class="y51800eze"/></g><g filter="url(#iHUmnOb)"><circle class="jcjqqcb2e"/></g><g filter="url(#i71Yv5a)"><circle class="c44cpmbxy"/></g><defs><radialGradient id="iuL2Qrc" cx="0" cy="0" r="1" gradientTransform="rotate(115.805 8.543 10.852)scale(6.10527 9.71154)" gradientUnits="userSpaceOnUse"><stop class="vxn-_9k4i"/><stop offset="1" class="tj22jybyb"/></radialGradient><radialGradient id="inNTAWb" cx="0" cy="0" r="1" gradientTransform="rotate(-42.333 33.864 .027)scale(16.1484 16.1483)" gradientUnits="userSpaceOnUse"><stop class="fy6asbcrb"/><stop offset="1" class="z2vsfv0ny"/></radialGradient><radialGradient id="i8BKlws" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49396 3.2867 -6.15255 -2.79662 21.11 7.66)" gradientUnits="userSpaceOnUse"><stop class="waizd9bfi"/><stop offset="1" class="ff7wmgbom"/></radialGradient><radialGradient id="iM4AiLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2539 10.20778 -11.68974 1.43594 15.447 18.455)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="o0yrn2bgu"/><stop offset=".754" class="tbwc7pswj"/><stop offset=".962" class="ot92k33ji"/></radialGradient><radialGradient id="iBOG8Ac" cx="0" cy="0" r="1" gradientTransform="rotate(142.239 8.261 9.354)scale(18.642 17.7929)" gradientUnits="userSpaceOnUse"><stop offset=".477" class="y9a0n0zfd"/><stop offset=".694" class="pcvhvfb4r"/><stop offset=".816" class="icr2dbcan"/><stop offset=".962" class="rfr83ktkk"/></radialGradient><radialGradient id="i4nRUid" cx="0" cy="0" r="1" gradientTransform="matrix(9.96614 14.85861 -17.01589 11.4131 12.306 12.475)" gradientUnits="userSpaceOnUse"><stop offset=".537" class="y9a0n0zfd"/><stop offset=".754" class="j067ciben"/><stop offset=".962" class="cggok0bap"/></radialGradient><radialGradient id="iwbqCDb" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 1.3125 -.67555 2.02665 26.531 17.969)" gradientUnits="userSpaceOnUse"><stop class="md0qurb0u"/><stop offset="1" class="l4schobxy"/></radialGradient><radialGradient id="iQ31Pdc" cx="0" cy="0" r="1" gradientTransform="rotate(47.386 6.38 31.765)scale(2.12316 8.3205)" gradientUnits="userSpaceOnUse"><stop class="d0jzyib1g"/><stop offset=".799" class="q02lr-b2u"/></radialGradient><radialGradient id="iBKmM1d" cx="0" cy="0" r="1" gradientTransform="rotate(136.219 13.37 9.092)scale(1.0388 1.62421)" gradientUnits="userSpaceOnUse"><stop class="pw4928blv"/><stop offset="1" class="c_2w2ebzp"/></radialGradient><radialGradient id="isv7DKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.22656 -6.54842 0 28.669 29.992)" gradientUnits="userSpaceOnUse"><stop class="onxunrbyk"/><stop offset=".733" class="mh-dmpodh"/></radialGradient><radialGradient id="i6ROzCd" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .46875 -.57257 .64892 3.281 5.5)" gradientUnits="userSpaceOnUse"><stop class="je9gz3-cp"/><stop offset="1" class="an-woltdu"/></radialGradient><radialGradient id="iXgl6re" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 .48437 -.59166 .72526 5.78 5.328)" gradientUnits="userSpaceOnUse"><stop class="je9gz3-cp"/><stop offset="1" class="an-woltdu"/></radialGradient><radialGradient id="ipUyWie" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .51563 -.62983 .55349 8.39 5.313)" gradientUnits="userSpaceOnUse"><stop class="je9gz3-cp"/><stop offset="1" class="an-woltdu"/></radialGradient><radialGradient id="ioeBRdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25781 -4.10938 0 5.422 29.992)" gradientUnits="userSpaceOnUse"><stop class="m1qk1cbzl"/><stop offset="1" class="q6u8mtzbg"/></radialGradient><radialGradient id="i4SSuPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -9.42188 0 5.453 30)" gradientUnits="userSpaceOnUse"><stop class="m1qk1cbzl"/><stop offset="1" class="jdplk5bpy"/></radialGradient><filter id="iFzocKe" width="22.341" height="22.341" x="5.556" y="5.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><filter id="iWkcRnb" width="9.865" height="5.004" x="15.454" y="5.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".15"/></filter><filter id="iujb3Yd" width="6.348" height="11.031" x="23.558" y="9.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".5"/></filter><filter id="iIfXrIc" width="4.339" height="12.367" x="25.341" y="5.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><filter id="iZXpwVc" width="7.5" height="25.66" x="1.703" y="4.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".375"/></filter><filter id="i1pjIkL" width="1.5" height="14.531" x="5.406" y="14.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><filter id="igA1nBY" width="1.783" height="4.904" x="2.691" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".125"/></filter><filter id="iV2H5Fc" width="1.783" height="4.904" x="5.253" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".125"/></filter><filter id="i0bgYgc" width="2.884" height="9.587" x="6.159" y="5.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><filter id="i2PnUdb" width="1.516" height="1.516" x="2.305" y="4.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><filter id="iHUmnOb" width="1.516" height="1.516" x="4.922" y="4.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><filter id="i71Yv5a" width="1.516" height="1.516" x="7.438" y="4.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30937" stdDeviation=".25"/></filter><linearGradient id="iFErVAj" x1="15.447" x2="16.701" y1="6.012" y2="28.008" gradientUnits="userSpaceOnUse"><stop offset=".115" class="oar7nvu5a"/><stop offset=".228" class="nlqb0w6bp"/><stop offset=".689" class="oykwkhbrj"/><stop offset=".766" class="gr_rry0gt"/></linearGradient><linearGradient id="iffrfid" x1="29.99" x2="25.031" y1="12.063" y2="12.063" gradientUnits="userSpaceOnUse"><stop class="ic8cpf61y"/><stop offset=".036" class="yjy29ubiv"/><stop offset=".515" class="t04clcb1j"/><stop offset="1" class="x0txdmbxb"/></linearGradient><linearGradient id="iDNVPKc" x1="27.511" x2="27.511" y1="6.012" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="qpm4l0bdq"/><stop offset=".818" class="kqy2-qbqp"/></linearGradient><linearGradient id="imevdEb" x1="27.348" x2="29.99" y1="24.688" y2="24.688" gradientUnits="userSpaceOnUse"><stop class="lcz6-pubg"/><stop offset=".359" class="n6tvy208m"/><stop offset=".734" class="sv4uvfbmd"/><stop offset="1" class="v-fbicvwn"/></linearGradient><linearGradient id="iD3cinc" x1="28.669" x2="28.669" y1="18.266" y2="18.469" gradientUnits="userSpaceOnUse"><stop class="k7ogauhpa"/><stop offset="1" class="e47kkgwar"/></linearGradient><linearGradient id="i0QUjvd" x1="2" x2="10.75" y1="8" y2="9.938" gradientUnits="userSpaceOnUse"><stop class="m7vc8rbpa"/><stop offset=".59" class="zky48yb5m"/><stop offset=".839" class="qfzj2sojq"/><stop offset="1" class="e61i14bpq"/></linearGradient><linearGradient id="iFdLPEe" x1="4.438" x2="5.453" y1="6.063" y2="29.719" gradientUnits="userSpaceOnUse"><stop offset=".143" class="xfvmh8b-b"/><stop offset="1" class="n0png3b-q"/></linearGradient><linearGradient id="iWyaivO" x1="3.344" x2="4.938" y1="6.219" y2="10.594" gradientUnits="userSpaceOnUse"><stop offset=".412" class="ko4f5nbdc"/><stop offset="1" class="dcztr0b2a"/></linearGradient><linearGradient id="i96rL8b" x1="5.906" x2="7.5" y1="6.219" y2="10.594" gradientUnits="userSpaceOnUse"><stop offset=".412" class="ko4f5nbdc"/><stop offset="1" class="dcztr0b2a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fork-and-knife-with-plate" /></template>
<style>
.a6po_3bze {
  fill: var(--svg-color--ddcef5, #DDCEF5);
  d: path("M16.726 27.655c5.893 0 10.67-4.777 10.67-10.67s-4.777-10.67-10.67-10.67s-10.67 4.776-10.67 10.67c0 5.893 4.777 10.67 10.67 10.67");
}

.an-woltdu {
  stop-color: var(--svg-color--cdcad5, #CDCAD5);
  stop-opacity: 0;
}

.b9i0liusy {
  d: path("M5.903 5.934a.2.2 0 0 0-.4 0zm.683 4.203h.2v-.4h-.2zM5.503 5.934v2.8h.4v-2.8zm0 2.8c0 .172.043.504.19.802c.149.302.425.601.893.601v-.4c-.259 0-.424-.153-.535-.378c-.113-.23-.148-.5-.148-.625z");
}

.c_2w2ebzp {
  stop-color: var(--svg-color--e1dee8, #E1DEE8);
  stop-opacity: 0;
}

.c2l7k0bjd {
  d: path("M7.96 5.558c-.388 0-.444.361-.444.755v2.681c0 .639-.485.795-.79.795c-.304 0-.851-.172-.851-.795V6.313c0-.394-.055-.755-.383-.755s-.406.35-.406.754v2.682c0 .435-.445.795-.953.795c-.375 0-.883-.25-.883-.795V6.313c0-.394-.07-.755-.398-.755c-.329 0-.399.35-.399.755v5.281c0 2.055 2.125 2.612 2.125 4.065v12.958c0 .706.225 1.102.813 1.102c.587 0 .922-.349.922-1.055V15.66c0-1.505 2.14-1.994 2.14-4.065v-2.6l-.078-2.682c-.02-.393-.025-.754-.414-.754");
}

.c44cpmbxy {
  cx: 8.195px;
  cy: 5.754px;
  r: 0.258px;
  fill: var(--svg-color--e0dce8, #E0DCE8);
}

.cggok0bap {
  stop-color: var(--svg-color--b2aec4, #B2AEC4);
}

.d0jzyib1g {
  stop-color: var(--svg-color--94929a, #94929A);
}

.dcztr0b2a {
  stop-color: var(--svg-color--c0b9cc, #C0B9CC);
  stop-opacity: 0;
}

.e47kkgwar {
  stop-color: var(--svg-color--8d80a2, #8D80A2);
  stop-opacity: 0;
}

.e61i14bpq {
  stop-color: var(--svg-color--aca0c0, #ACA0C0);
}

.ff7wmgbom {
  stop-color: var(--svg-color--e5e3ef, #E5E3EF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fva_2_1ff {
  d: path("M15.755 6.344c3.202-.437 7.271.946 9.264 4.326c-2.577-2.476-5.315-4.002-9.264-4.326");
}

.fy6asbcrb {
  stop-color: var(--svg-color--eae0fd, #EAE0FD);
}

.gr_rry0gt {
  stop-color: var(--svg-color--bfa1e2, #BFA1E2);
}

.gylmc1-wl {
  d: path("M16.7 24.577a7.567 7.567 0 1 0 .001-15.134a7.567 7.567 0 0 0 0 15.134");
}

.hntovz6gr {
  d: path("M27.806 6.012c.758 0 1.374.603 1.374 1.345V17.38c-1.374 0-3.339-1.052-3.339-3.665v-5.77c-.008-1.065.869-1.932 1.965-1.932");
}

.ic8cpf61y {
  stop-color: var(--svg-color--c4c2cb, #C4C2CB);
}

.icr2dbcan {
  stop-color: var(--svg-color--ebe8fb, #EBE8FB);
}

.iyrp2rbac {
  d: path("M7.965 5.042c-.47 0-.841.33-.841.723V9.08c0 .213-.198.372-.434.372c-.247 0-.433-.17-.433-.372V5.797c0-.393-.359-.744-.817-.755c-.482-.01-.878.32-.878.723V9.08c0 .213-.198.372-.433.372c-.248 0-.434-.17-.434-.372V5.797c0-.393-.358-.744-.816-.755c-.483-.01-.879.32-.879.723v5.829c0 2.055 2.116 2.612 2.116 4.065v13.005c0 .706.595 1.328 1.306 1.328c.71 0 1.306-.622 1.306-1.328V15.66c0-1.505 2.116-1.994 2.116-4.065v-5.83c-.025-.392-.409-.722-.879-.722");
}

.j067ciben {
  stop-color: var(--svg-color--b9b5ca, #B9B5CA);
}

.j6mk_lhat {
  stroke: var(--svg-color--c3bdcf, #C3BDCF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.344 5.875V11.5c0 .86-1.016 2.125-1.485 2.563");
}

.jcjqqcb2e {
  cx: 5.68px;
  cy: 5.754px;
  r: 0.258px;
  fill: var(--svg-color--e0dce8, #E0DCE8);
}

.jdplk5bpy {
  stop-color: var(--svg-color--a493bc, #A493BC);
  stop-opacity: 0;
}

.je9gz3-cp {
  stop-color: var(--svg-color--c9c7d0, #C9C7D0);
}

.k7ogauhpa {
  stop-color: var(--svg-color--8e80a3, #8E80A3);
}

.ko4f5nbdc {
  stop-color: var(--svg-color--c0b9cc, #C0B9CC);
}

.kqy2-qbqp {
  stop-color: var(--svg-color--b4a9c5, #B4A9C5);
}

.l4schobxy {
  stop-color: var(--svg-color--a28ebb, #A28EBB);
  stop-opacity: 0;
}

.lcz6-pubg {
  stop-color: var(--svg-color--7e748e, #7E748E);
}

.m1qk1cbzl {
  stop-color: var(--svg-color--8f78ab, #8F78AB);
}

.m7vc8rbpa {
  stop-color: var(--svg-color--8b8893, #8B8893);
}

.md0qurb0u {
  stop-color: var(--svg-color--9b89b3, #9B89B3);
}

.mh-dmpodh {
  stop-color: var(--svg-color--ae9ac8, #AE9AC8);
  stop-opacity: 0;
}

.mr3r47b2c {
  d: path("M3.34 5.934a.2.2 0 0 0-.4 0zm.683 4.203h.2v-.4h-.2zM2.941 5.934v2.8h.4v-2.8zm0 2.8c0 .172.043.504.19.802c.148.302.425.601.892.601v-.4c-.258 0-.423-.153-.534-.378c-.113-.23-.148-.5-.148-.625z");
}

.n0png3b-q {
  stop-color: var(--svg-color--b5a9c8, #B5A9C8);
}

.n6tvy208m {
  stop-color: var(--svg-color--a69bb8, #A69BB8);
}

.nlqb0w6bp {
  stop-color: var(--svg-color--8f8d9b, #8F8D9B);
}

.o0yrn2bgu {
  stop-color: var(--svg-color--dacef3, #DACEF3);
}

.oar7nvu5a {
  stop-color: var(--svg-color--bcbbc4, #BCBBC4);
}

.onxunrbyk {
  stop-color: var(--svg-color--8b72a8, #8B72A8);
}

.ot92k33ji {
  stop-color: var(--svg-color--bca7dc, #BCA7DC);
}

.oykwkhbrj {
  stop-color: var(--svg-color--a8a0bc, #A8A0BC);
}

.pcvhvfb4r {
  stop-color: var(--svg-color--e9e2fd, #E9E2FD);
}

.pw4928blv {
  stop-color: var(--svg-color--d7d2e0, #D7D2E0);
}

.q02lr-b2u {
  stop-color: var(--svg-color--a29eab, #A29EAB);
  stop-opacity: 0;
}

.q3rd4utmq {
  d: path("M16.7 28.008c6.075 0 10.999-4.924 10.999-10.998S22.775 6.012 16.7 6.012S5.703 10.936 5.703 17.01s4.924 10.998 10.998 10.998");
}

.q6u8mtzbg {
  stop-color: var(--svg-color--9883b3, #9883B3);
  stop-opacity: 0;
}

.qfzj2sojq {
  stop-color: var(--svg-color--afa3c1, #AFA3C1);
}

.qpm4l0bdq {
  stop-color: var(--svg-color--c1b6d0, #C1B6D0);
}

.rfr83ktkk {
  stop-color: var(--svg-color--eae7f9, #EAE7F9);
}

.scv3u8uqx {
  stroke: var(--svg-color--c3bdcf, #C3BDCF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.156 15.594v13.031");
}

.sv4uvfbmd {
  stop-color: var(--svg-color--cbc4d9, #CBC4D9);
}

.t04clcb1j {
  stop-color: var(--svg-color--b9b1c7, #B9B1C7);
}

.tbwc7pswj {
  stop-color: var(--svg-color--ccb9eb, #CCB9EB);
}

.tj22jybyb {
  stop-color: var(--svg-color--d7d6de, #D7D6DE);
  stop-opacity: 0;
}

.u-vgmfbve {
  fill: var(--svg-color--d8cbf0, #D8CBF0);
  d: path("M16.7 24.577a7.567 7.567 0 1 0 .001-15.134a7.567 7.567 0 0 0 0 15.134");
}

.uhjk3chrv {
  d: path("M27.949 5.042c1.127 0 2.041.895 2.041 1.998v11.226h-2.63a3.83 3.83 0 0 1-2.329-3.553V7.91c-.012-1.58 1.29-2.868 2.918-2.868");
}

.v-fbicvwn {
  stop-color: var(--svg-color--c4c1cc, #C4C1CC);
}

.vsvggzdaj {
  d: path("M27.348 18.266v10.573c0 .638.526 1.153 1.177 1.153h.288c.651 0 1.177-.515 1.177-1.153V18.266z");
}

.vtq3g8n2e {
  fill: var(--svg-color--b9a9d2, #B9A9D2);
  d: path("M28.906 10.531v9.032l-2.053-.822c-1.384-.551-2.295-2.01-2.295-3.653v-4.557z");
}

.vxn-_9k4i {
  stop-color: var(--svg-color--dadae0, #DADAE0);
}

.w6kvlmbkl {
  d: path("M16.726 27.655c5.893 0 10.67-4.777 10.67-10.67s-4.777-10.67-10.67-10.67s-10.67 4.776-10.67 10.67c0 5.893 4.777 10.67 10.67 10.67");
}

.waizd9bfi {
  stop-color: var(--svg-color--e5e3ef, #E5E3EF);
}

.x0txdmbxb {
  stop-color: var(--svg-color--a398b4, #A398B4);
}

.xfvmh8b-b {
  stop-color: var(--svg-color--b4aac2, #B4AAC2);
}

.y51800eze {
  cx: 3.063px;
  cy: 5.754px;
  r: 0.258px;
  fill: var(--svg-color--e0dce8, #E0DCE8);
}

.y9a0n0zfd {
  stop-color: var(--svg-color--dacef3, #DACEF3);
  stop-opacity: 0;
}

.yjy29ubiv {
  stop-color: var(--svg-color--cfc9d9, #CFC9D9);
}

.z2vsfv0ny {
  stop-color: var(--svg-color--e7ddf9, #E7DDF9);
  stop-opacity: 0;
}

.zky48yb5m {
  stop-color: var(--svg-color--938da0, #938DA0);
}

</style>
