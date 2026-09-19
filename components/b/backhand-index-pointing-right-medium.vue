<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="iDppIWb" x1="17.67" x2="17.67" y1="29.41" y2="26.277" gradientUnits="userSpaceOnUse"><stop class="jb9zeo2nj"/><stop offset="1" class="pa2w_3boc"/></linearGradient><linearGradient id="iojCvPe" x1="7.151" x2="7.151" y1="16.163" y2="13.7" gradientUnits="userSpaceOnUse"><stop class="snlqglqld"/><stop offset="1" class="yhu3ph0yz"/></linearGradient><linearGradient id="iuVO8Ab" x1="9.029" x2="9.029" y1="9.951" y2="14.081" gradientUnits="userSpaceOnUse"><stop class="zcqrbccjx"/><stop offset="1" class="trqtwyo3i"/></linearGradient><linearGradient id="ib9VZnN" x1="16.04" x2="9.462" y1="14.154" y2="14.154" gradientUnits="userSpaceOnUse"><stop class="mp6o79bwx"/><stop offset="1" class="xzi7cv_8f"/></linearGradient><linearGradient id="ieTnJYd" x1="20.153" x2="17.653" y1="6.134" y2="8.509" gradientUnits="userSpaceOnUse"><stop class="mknk_z6tz"/><stop offset="1" class="ezr1bfihg"/></linearGradient><linearGradient id="i7PZgnv" x1="22.276" x2="20.166" y1="10.109" y2="8.047" gradientUnits="userSpaceOnUse"><stop offset=".223" class="e9xocbbjq"/><stop offset="1" class="arogfbc5e"/><stop offset="1" class="yotqm0m2v"/></linearGradient><linearGradient id="iT4sjmd" x1="13.872" x2="16.61" y1="9.102" y2="7.237" gradientUnits="userSpaceOnUse"><stop offset=".05" class="re6r14slg"/><stop offset="1" class="iqnlh-bbx"/></linearGradient><linearGradient id="iiF7Evb" x1="7.761" x2="19.953" y1="13.154" y2="13.154" gradientUnits="userSpaceOnUse"><stop class="p0-874bdl"/><stop offset="1" class="xc44p-brs"/></linearGradient><linearGradient id="i14ubLb" x1="20.572" x2="20.801" y1="4.084" y2="6.729" gradientUnits="userSpaceOnUse"><stop class="mobme-ixl"/><stop offset="1" class="dgoj-lbhf"/></linearGradient><linearGradient id="iouUcEd" x1="8.585" x2="14.682" y1="15.225" y2="17.252" gradientUnits="userSpaceOnUse"><stop class="kr9u8nblt"/><stop offset="1" class="vqex9c2fz"/></linearGradient><linearGradient id="iLmZMZd" x1="9.45" x2="14.335" y1="18.861" y2="22.435" gradientUnits="userSpaceOnUse"><stop class="kr9u8nblt"/><stop offset="1" class="vqex9c2fz"/></linearGradient><linearGradient id="ieq4Fsb" x1="10.243" x2="15.755" y1="23.105" y2="26.155" gradientUnits="userSpaceOnUse"><stop class="kr9u8nblt"/><stop offset="1" class="vqex9c2fz"/></linearGradient><radialGradient id="ioQZN5d" cx="0" cy="0" r="1" gradientTransform="matrix(-12.16159 12.46549 -18.5232 -18.0716 25.943 15.555)" gradientUnits="userSpaceOnUse"><stop class="kdsagwbbl"/><stop offset="1" class="qfjw1rbij"/></radialGradient><radialGradient id="ipEKbQb" cx="0" cy="0" r="1" gradientTransform="matrix(6.51954 0 0 1.95986 7.375 19.236)" gradientUnits="userSpaceOnUse"><stop class="ggr4300sr"/><stop offset=".763" class="niwun7b9u"/></radialGradient><radialGradient id="iLliewb" cx="0" cy="0" r="1" gradientTransform="matrix(7.0795 0 0 1.51989 8.695 24.315)" gradientUnits="userSpaceOnUse"><stop class="ggr4300sr"/><stop offset=".763" class="niwun7b9u"/></radialGradient><radialGradient id="i7wzDHb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6514 -.02425 .00282 .3086 9.27 19.79)" gradientUnits="userSpaceOnUse"><stop class="j6w8a1b2s"/><stop offset="1" class="rwdq5qbgt"/></radialGradient><radialGradient id="iECSp3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 0 0 .20313 10.169 24.259)" gradientUnits="userSpaceOnUse"><stop class="j6w8a1b2s"/><stop offset="1" class="rwdq5qbgt"/></radialGradient><radialGradient id="igZ68Ce" cx="0" cy="0" r="1" gradientTransform="rotate(149.805 13.208 10.655)scale(6.4344 8.87872)" gradientUnits="userSpaceOnUse"><stop class="u0oxvrbpk"/><stop offset="1" class="un6xx8boq"/></radialGradient><radialGradient id="iUK6Ofe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.32112 0 0 -7.02379 10.554 12.588)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="moelwiuzg"/><stop offset="1" class="s72udxbeu"/></radialGradient><radialGradient id="it57Nmh" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27976 1.21993 -.27629 -.7428 10.215 14.916)" gradientUnits="userSpaceOnUse"><stop class="q0hc7-7mg"/><stop offset="1" class="e80r2xbjh"/></radialGradient><filter id="ilMyvwe" width="27.964" height="26.287" x="2.018" y="2.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2743"/></filter><filter id="i8VjGyb" width="16.315" height="5.12" x="2.462" y="9.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2743" stdDeviation=".75"/></filter><filter id="iDuDiZb" width="9.457" height="10.641" x="13.272" y="3.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2743" stdDeviation=".75"/></filter><filter id="i8NRWNw" width="6.885" height="4.65" x="7.93" y="14.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2743" stdDeviation=".5"/></filter><filter id="ia1tb9d" width="6.885" height="4.65" x="8.45" y="18.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2743" stdDeviation=".5"/></filter><filter id="ioQ2Fbb" width="5.715" height="4.211" x="9.62" y="22.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2743" stdDeviation=".5"/></filter></defs><g transform="translate(32 0) scale(-1 1)"><g class="ft5dv1b6b"><g filter="url(#ilMyvwe)"><path fill="url(#ioQZN5d)" class="enh5k8fqc"/><path fill="url(#ipEKbQb)" class="enh5k8fqc"/><path fill="url(#iLliewb)" class="enh5k8fqc"/><path fill="url(#i7wzDHb)" class="enh5k8fqc"/><path fill="url(#iECSp3c)" class="enh5k8fqc"/></g><path fill="url(#igZ68Ce)" class="enh5k8fqc"/><path fill="url(#iDppIWb)" class="enh5k8fqc"/><rect fill="url(#iojCvPe)" class="a1yscj3wv"/><rect fill="url(#iUK6Ofe)" class="a1yscj3wv"/><rect fill="url(#iuVO8Ab)" class="a1yscj3wv"/><rect fill="url(#ib9VZnN)" class="a1yscj3wv"/><path fill="url(#ieTnJYd)" class="ka0uvzcrk"/><path fill="url(#i7PZgnv)" class="ka0uvzcrk"/><path fill="url(#iT4sjmd)" class="ka0uvzcrk"/><g filter="url(#i8VjGyb)"><rect fill="url(#iiF7Evb)" class="zl_vf-2-e"/></g><g filter="url(#iDuDiZb)"><rect fill="url(#i14ubLb)" transform="rotate(51.914 16.04 4.072)" class="d7pevmjlk"/></g><g filter="url(#i8NRWNw)"><rect fill="url(#iouUcEd)" class="rgczqabmh"/></g><g filter="url(#ia1tb9d)"><rect fill="url(#iLmZMZd)" class="i7z28tb1l"/></g><g filter="url(#ioQ2Fbb)"><rect fill="url(#ieq4Fsb)" class="k4s4h0qfu"/></g><path fill="url(#it57Nmh)" class="u302-2b6e"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-right-medium" /></template>
<style>
.a1yscj3wv {
  width: 14.022px;
  height: 5.274px;
  x: 2.018px;
  y: 9.951px;
  rx: 2.637px;
}

.arogfbc5e {
  stop-color: var(--svg-color--ad8373, #AD8373);
  stop-opacity: 0;
}

.d7pevmjlk {
  width: 9.122px;
  height: 2.167px;
  x: 16.04px;
  y: 4.072px;
  rx: 1.083px;
}

.dgoj-lbhf {
  stop-color: var(--svg-color--c79f83, #C79F83);
  stop-opacity: 0;
}

.e80r2xbjh {
  stop-color: var(--svg-color--58382a, #58382A);
  stop-opacity: 0;
}

.e9xocbbjq {
  stop-color: var(--svg-color--b98d7a, #B98D7A);
}

.enh5k8fqc {
  d: path("M18.12 4.527c-.86-1.24-2.597-1.702-3.849-.889a2.657 2.657 0 0 0-.781 3.703l1.695 2.61H4.655a2.637 2.637 0 0 0 0 5.274h4.284a2.493 2.493 0 0 0 .344 4.564a2.724 2.724 0 0 0 .884 4.487a2.723 2.723 0 0 0 2.07 4.493h3.102l.104-.002h4.859c1.431 0 3.878-.849 6.022-2.51a9 9 0 0 0 .65-.537a9.2 9.2 0 0 0 3.008-6.833a9.2 9.2 0 0 0-3.944-7.577c-.833-.603-1.507-.892-2.176-1.178c-.513-.22-1.023-.439-1.601-.797c-.913-.566-1.59-1.4-1.969-1.865l-.08-.098v.002z");
}

.ezr1bfihg {
  stop-color: var(--svg-color--c7a384, #C7A384);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ggr4300sr {
  stop-color: var(--svg-color--8b5868, #8B5868);
}

.i7z28tb1l {
  width: 4.885px;
  height: 2.65px;
  x: 9.45px;
  y: 19.785px;
  rx: 1.325px;
}

.iqnlh-bbx {
  stop-color: var(--svg-color--8e6559, #8E6559);
  stop-opacity: 0;
}

.j6w8a1b2s {
  stop-color: var(--svg-color--744d40, #744D40);
}

.jb9zeo2nj {
  stop-color: var(--svg-color--995883, #995883);
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

.kdsagwbbl {
  stop-color: var(--svg-color--c1987d, #C1987D);
}

.kr9u8nblt {
  stop-color: var(--svg-color--a77d6e, #A77D6E);
}

.mknk_z6tz {
  stop-color: var(--svg-color--c7a384, #C7A384);
}

.mobme-ixl {
  stop-color: var(--svg-color--c79f83, #C79F83);
}

.moelwiuzg {
  stop-color: var(--svg-color--9e7766, #9E7766);
  stop-opacity: 0;
}

.mp6o79bwx {
  stop-color: var(--svg-color--b88b7b, #B88B7B);
}

.niwun7b9u {
  stop-color: var(--svg-color--8b5868, #8B5868);
  stop-opacity: 0;
}

.p0-874bdl {
  stop-color: var(--svg-color--b38a74, #B38A74);
}

.pa2w_3boc {
  stop-color: var(--svg-color--995883, #995883);
  stop-opacity: 0;
}

.q0hc7-7mg {
  stop-color: var(--svg-color--58382a, #58382A);
}

.qfjw1rbij {
  stop-color: var(--svg-color--ad7a7c, #AD7A7C);
}

.re6r14slg {
  stop-color: var(--svg-color--8e6559, #8E6559);
}

.rgczqabmh {
  width: 4.885px;
  height: 2.65px;
  x: 8.93px;
  y: 15.225px;
  rx: 1.325px;
}

.rwdq5qbgt {
  stop-color: var(--svg-color--744d40, #744D40);
  stop-opacity: 0;
}

.s72udxbeu {
  stop-color: var(--svg-color--9e7766, #9E7766);
}

.snlqglqld {
  stop-color: var(--svg-color--8f5573, #8F5573);
}

.trqtwyo3i {
  stop-color: var(--svg-color--ad8b70, #AD8B70);
  stop-opacity: 0;
}

.u0oxvrbpk {
  stop-color: var(--svg-color--d0a78b, #D0A78B);
}

.u302-2b6e {
  d: path("M7.612 17.596h6.423v-2.37H8.939a2.49 2.49 0 0 0-1.327 2.37");
}

.un6xx8boq {
  stop-color: var(--svg-color--d0a78b, #D0A78B);
  stop-opacity: 0;
}

.vqex9c2fz {
  stop-color: var(--svg-color--a77d6e, #A77D6E);
  stop-opacity: 0;
}

.xc44p-brs {
  stop-color: var(--svg-color--b38a74, #B38A74);
  stop-opacity: 0;
}

.xzi7cv_8f {
  stop-color: var(--svg-color--b88b7b, #B88B7B);
  stop-opacity: 0;
}

.yhu3ph0yz {
  stop-color: var(--svg-color--8f5573, #8F5573);
  stop-opacity: 0;
}

.yotqm0m2v {
  stop-color: var(--svg-color--b98d7a, #B98D7A);
  stop-opacity: 0;
}

.zcqrbccjx {
  stop-color: var(--svg-color--ad8b70, #AD8B70);
}

.zl_vf-2-e {
  width: 13.315px;
  height: 2.12px;
  x: 3.962px;
  y: 10.796px;
  rx: 1.06px;
}

</style>
