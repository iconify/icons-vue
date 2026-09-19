<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="iGI4Htf" x1="17.67" x2="17.67" y1="30.648" y2="25.485" gradientUnits="userSpaceOnUse"><stop offset=".082" class="q45j2wvkl"/><stop offset="1" class="code2sjar"/></linearGradient><linearGradient id="i0mTgye" x1="7.151" x2="7.151" y1="16.163" y2="13.7" gradientUnits="userSpaceOnUse"><stop class="ft7dnhctu"/><stop offset="1" class="lbssj16fy"/></linearGradient><linearGradient id="iM1eyGb" x1="9.029" x2="9.029" y1="9.951" y2="14.081" gradientUnits="userSpaceOnUse"><stop class="jnvx2vaqr"/><stop offset="1" class="fxdcgibob"/></linearGradient><linearGradient id="iQJJU7t" x1="16.04" x2="9.462" y1="14.154" y2="14.154" gradientUnits="userSpaceOnUse"><stop class="y6axegb5k"/><stop offset="1" class="sgnitnbys"/></linearGradient><linearGradient id="iP4gilb" x1="20.153" x2="17.653" y1="6.134" y2="8.509" gradientUnits="userSpaceOnUse"><stop class="d9jmjybry"/><stop offset="1" class="wseic249b"/></linearGradient><linearGradient id="iqSBytb" x1="22.276" x2="20.166" y1="10.109" y2="8.047" gradientUnits="userSpaceOnUse"><stop offset=".223" class="ruigomqdp"/><stop offset="1" class="fiwfxccrs"/></linearGradient><linearGradient id="iamcmdb" x1="13.872" x2="16.61" y1="9.102" y2="7.237" gradientUnits="userSpaceOnUse"><stop offset=".05" class="eo5xu02ni"/><stop offset="1" class="iwgkbyb_p"/></linearGradient><linearGradient id="ihiwrQd" x1="7.761" x2="19.953" y1="13.154" y2="13.154" gradientUnits="userSpaceOnUse"><stop class="vgx4yo94m"/><stop offset="1" class="fl58mi57i"/></linearGradient><linearGradient id="iYNl68c" x1="20.674" x2="20.692" y1="3.551" y2="5.701" gradientUnits="userSpaceOnUse"><stop class="l5p9pz4rq"/><stop offset="1" class="tay44oboe"/></linearGradient><linearGradient id="iRuH2Vd" x1="10.039" x2="14.682" y1="16.126" y2="17.252" gradientUnits="userSpaceOnUse"><stop class="vhd8febrj"/><stop offset="1" class="g29l7oblo"/></linearGradient><linearGradient id="iLNp6eO" x1="10.559" x2="15.202" y1="20.685" y2="21.811" gradientUnits="userSpaceOnUse"><stop class="nix8vg7uj"/><stop offset="1" class="svrmt1bli"/></linearGradient><linearGradient id="ivkU9db" x1="11.463" x2="15.028" y1="24.695" y2="25.484" gradientUnits="userSpaceOnUse"><stop class="nix8vg7uj"/><stop offset="1" class="svrmt1bli"/></linearGradient><radialGradient id="iBz7yGb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.16159 12.46549 -18.5232 -18.0716 25.943 15.555)" gradientUnits="userSpaceOnUse"><stop class="qkza4tkjj"/><stop offset="1" class="x_qn3fbxc"/></radialGradient><radialGradient id="ih2NKdc" cx="0" cy="0" r="1" gradientTransform="matrix(6.51954 0 0 1.95986 7.375 19.236)" gradientUnits="userSpaceOnUse"><stop class="b08-bub0v"/><stop offset=".763" class="oqg7pkznf"/></radialGradient><radialGradient id="iAWhUMd" cx="0" cy="0" r="1" gradientTransform="matrix(6.40568 0 0 1.97994 9.26 23.605)" gradientUnits="userSpaceOnUse"><stop class="b08-bub0v"/><stop offset=".763" class="oqg7pkznf"/></radialGradient><radialGradient id="iO7feld" cx="0" cy="0" r="1" gradientTransform="matrix(2.6514 -.02425 .00282 .3086 9.27 19.79)" gradientUnits="userSpaceOnUse"><stop class="q344o58rl"/><stop offset="1" class="zea8e6bza"/></radialGradient><radialGradient id="ix3o2ve" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 0 0 .20313 10.169 24.259)" gradientUnits="userSpaceOnUse"><stop class="q344o58rl"/><stop offset="1" class="zea8e6bza"/></radialGradient><radialGradient id="ix2Shfe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9779 2.23385 -3.86445 -10.34144 30.398 14.224)" gradientUnits="userSpaceOnUse"><stop class="o5c0-yfdz"/><stop offset="1" class="i_lmo07pj"/></radialGradient><radialGradient id="i21p4Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.32112 0 0 -7.02379 10.554 12.588)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="md_urbcmv"/><stop offset="1" class="doysnhfra"/><stop offset="1" class="zcb4w5yye"/></radialGradient><radialGradient id="iFlDKNd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27976 1.21993 -.27629 -.7428 10.215 14.916)" gradientUnits="userSpaceOnUse"><stop class="fa6qx8f3w"/><stop offset="1" class="wgfl4sduf"/></radialGradient><filter id="iDl28ue" width="27.964" height="26.287" x="2.018" y="2.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.670588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2765"/></filter><filter id="ijA5vXb" width="16.315" height="5.12" x="2.462" y="9.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2765" stdDeviation=".75"/></filter><filter id="iKfBWUc" width="9.457" height="10.641" x="13.272" y="3.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2765" stdDeviation=".75"/></filter><filter id="iagk0qc" width="6.885" height="4.65" x="7.93" y="14.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2765" stdDeviation=".5"/></filter><filter id="iwOXRnb" width="6.885" height="4.65" x="8.45" y="18.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2765" stdDeviation=".5"/></filter><filter id="itq3Kpe" width="5.715" height="4.211" x="9.62" y="22.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2765" stdDeviation=".5"/></filter></defs><g transform="translate(32 0) scale(-1 1)"><g class="ft5dv1b6b"><g filter="url(#iDl28ue)"><path fill="url(#iBz7yGb)" class="enh5k8fqc"/><path fill="url(#ih2NKdc)" class="enh5k8fqc"/><path fill="url(#iAWhUMd)" class="enh5k8fqc"/><path fill="url(#iO7feld)" class="enh5k8fqc"/><path fill="url(#ix3o2ve)" class="enh5k8fqc"/></g><path fill="url(#ix2Shfe)" class="enh5k8fqc"/><path fill="url(#iGI4Htf)" class="enh5k8fqc"/><rect fill="url(#i0mTgye)" class="a1yscj3wv"/><rect fill="url(#i21p4Yd)" class="a1yscj3wv"/><rect fill="url(#iM1eyGb)" class="a1yscj3wv"/><rect fill="url(#iQJJU7t)" class="a1yscj3wv"/><path fill="url(#iP4gilb)" class="ka0uvzcrk"/><path fill="url(#iqSBytb)" class="ka0uvzcrk"/><path fill="url(#iamcmdb)" class="ka0uvzcrk"/><g filter="url(#ijA5vXb)"><rect fill="url(#ihiwrQd)" class="zl_vf-2-e"/></g><g filter="url(#iKfBWUc)"><rect fill="url(#iYNl68c)" transform="rotate(51.914 16.04 4.072)" class="d7pevmjlk"/></g><g filter="url(#iagk0qc)"><rect fill="url(#iRuH2Vd)" class="rgczqabmh"/></g><g filter="url(#iwOXRnb)"><rect fill="url(#iLNp6eO)" class="i7z28tb1l"/></g><g filter="url(#itq3Kpe)"><rect fill="url(#ivkU9db)" class="k4s4h0qfu"/></g><path fill="url(#iFlDKNd)" class="u302-2b6e"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-right-light" /></template>
<style>
.a1yscj3wv {
  width: 14.022px;
  height: 5.274px;
  x: 2.018px;
  y: 9.951px;
  rx: 2.637px;
}

.b08-bub0v {
  stop-color: var(--svg-color--d39289, #D39289);
}

.code2sjar {
  stop-color: var(--svg-color--b87c97, #B87C97);
  stop-opacity: 0;
}

.d7pevmjlk {
  width: 9.122px;
  height: 2.167px;
  x: 16.04px;
  y: 4.072px;
  rx: 1.083px;
}

.d9jmjybry {
  stop-color: var(--svg-color--bisque, bisque);
}

.doysnhfra {
  stop-color: var(--svg-color--e2a788, #E2A788);
}

.enh5k8fqc {
  d: path("M18.12 4.527c-.86-1.24-2.597-1.702-3.849-.889a2.657 2.657 0 0 0-.781 3.703l1.695 2.61H4.655a2.637 2.637 0 0 0 0 5.274h4.284a2.493 2.493 0 0 0 .344 4.564a2.724 2.724 0 0 0 .884 4.487a2.723 2.723 0 0 0 2.07 4.493h3.102l.104-.002h4.859c1.431 0 3.878-.849 6.022-2.51a9 9 0 0 0 .65-.537a9.2 9.2 0 0 0 3.008-6.833a9.2 9.2 0 0 0-3.944-7.577c-.833-.603-1.507-.892-2.176-1.178c-.513-.22-1.023-.439-1.601-.797c-.913-.566-1.59-1.4-1.969-1.865l-.08-.098v.002z");
}

.eo5xu02ni {
  stop-color: var(--svg-color--e7a78b, #E7A78B);
}

.fa6qx8f3w {
  stop-color: var(--svg-color--c47c60, #C47C60);
}

.fiwfxccrs {
  stop-color: var(--svg-color--f7cdb8, #F7CDB8);
  stop-opacity: 0;
}

.fl58mi57i {
  stop-color: var(--svg-color--ffd2bb, #FFD2BB);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ft7dnhctu {
  stop-color: var(--svg-color--c3828d, #C3828D);
}

.fxdcgibob {
  stop-color: var(--svg-color--f5c7aa, #F5C7AA);
  stop-opacity: 0;
}

.g29l7oblo {
  stop-color: var(--svg-color--efc0b2, #EFC0B2);
  stop-opacity: 0;
}

.i_lmo07pj {
  stop-color: var(--svg-color--ffe7c9, #FFE7C9);
  stop-opacity: 0;
}

.i7z28tb1l {
  width: 4.885px;
  height: 2.65px;
  x: 9.45px;
  y: 19.785px;
  rx: 1.325px;
}

.iwgkbyb_p {
  stop-color: var(--svg-color--e7a78b, #E7A78B);
  stop-opacity: 0;
}

.jnvx2vaqr {
  stop-color: var(--svg-color--f5c7aa, #F5C7AA);
}

.k4s4h0qfu {
  width: 3.715px;
  height: 2.211px;
  x: 10.62px;
  y: 23.944px;
  rx: 1.105px;
}

.ka0uvzcrk {
  d: path("M14.271 3.638c1.252-.813 2.988-.35 3.848.889l2.092 2.847v-.002l.078.094l.003.004c.378.466 1.056 1.299 1.969 1.865a9 9 0 0 0 1.185.616h-8.261l-1.695-2.61a2.657 2.657 0 0 1 .781-3.703");
}

.l5p9pz4rq {
  stop-color: var(--svg-color--ffe4c6, #FFE4C6);
}

.lbssj16fy {
  stop-color: var(--svg-color--c3828d, #C3828D);
  stop-opacity: 0;
}

.md_urbcmv {
  stop-color: var(--svg-color--f0b49c, #F0B49C);
  stop-opacity: 0;
}

.nix8vg7uj {
  stop-color: var(--svg-color--e8b6a7, #E8B6A7);
}

.o5c0-yfdz {
  stop-color: var(--svg-color--ffe7c9, #FFE7C9);
}

.oqg7pkznf {
  stop-color: var(--svg-color--d39289, #D39289);
  stop-opacity: 0;
}

.q344o58rl {
  stop-color: var(--svg-color--dd987e, #DD987E);
}

.q45j2wvkl {
  stop-color: var(--svg-color--b87c97, #B87C97);
}

.qkza4tkjj {
  stop-color: var(--svg-color--ffdcc2, #FFDCC2);
}

.rgczqabmh {
  width: 4.885px;
  height: 2.65px;
  x: 8.93px;
  y: 15.225px;
  rx: 1.325px;
}

.ruigomqdp {
  stop-color: var(--svg-color--f7cdb8, #F7CDB8);
}

.sgnitnbys {
  stop-color: var(--svg-color--f5c9b8, #F5C9B8);
  stop-opacity: 0;
}

.svrmt1bli {
  stop-color: var(--svg-color--e8b6a7, #E8B6A7);
  stop-opacity: 0;
}

.tay44oboe {
  stop-color: var(--svg-color--ffe4c6, #FFE4C6);
  stop-opacity: 0;
}

.u302-2b6e {
  d: path("M7.612 17.596h6.423v-2.37H8.939a2.49 2.49 0 0 0-1.327 2.37");
}

.vgx4yo94m {
  stop-color: var(--svg-color--ffd2bb, #FFD2BB);
}

.vhd8febrj {
  stop-color: var(--svg-color--efc0b2, #EFC0B2);
}

.wgfl4sduf {
  stop-color: var(--svg-color--c47c60, #C47C60);
  stop-opacity: 0;
}

.wseic249b {
  stop-color: var(--svg-color--bisque, bisque);
  stop-opacity: 0;
}

.x_qn3fbxc {
  stop-color: var(--svg-color--e5aea8, #E5AEA8);
}

.y6axegb5k {
  stop-color: var(--svg-color--f5c9b8, #F5C9B8);
}

.zcb4w5yye {
  stop-color: var(--svg-color--f0b49c, #F0B49C);
}

.zea8e6bza {
  stop-color: var(--svg-color--dd987e, #DD987E);
  stop-opacity: 0;
}

.zl_vf-2-e {
  width: 13.315px;
  height: 2.12px;
  x: 3.962px;
  y: 10.796px;
  rx: 1.06px;
}

</style>
