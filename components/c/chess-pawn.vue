<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ieKaEIT)" class="zwdifibaa"/><circle fill="url(#ii6jZ0d)" class="zwdifibaa"/><circle fill="url(#ilKIpJc)" class="zwdifibaa"/><g filter="url(#iNSTdKe)"><path class="er65e58xz"/><path fill="url(#iBJz1Me)" class="zzrvnth3p"/><path fill="url(#inrTVtc)" class="zzrvnth3p"/><path fill="url(#iaJUXbc)" class="zzrvnth3p"/><path fill="url(#iZaopSc)" class="zzrvnth3p"/></g><path fill="url(#iDbN2Ic)" class="zzrvnth3p"/><rect class="eavefib1y"/><rect fill="url(#i2VpYTc)" class="t3z0kebmf"/><rect fill="url(#idVPSAY)" class="t3z0kebmf"/><rect fill="url(#iPCBRbc)" class="t3z0kebmf"/><rect fill="url(#ixoc2re)" class="t3z0kebmf"/><path class="pp3bv5b9z"/><path fill="url(#i158z6c)" class="e6bm57b7l"/><path fill="url(#ixSgJAc)" class="e6bm57b7l"/><path fill="url(#iiL3bMd)" class="e6bm57b7l"/><g filter="url(#iVvbuRc)"><path fill="url(#ibsL5fe)" class="k_cn0xb0v"/></g><g filter="url(#i69Emqe)"><path fill="url(#ipxVcHB)" class="j83dsda_w"/></g><defs><linearGradient id="ilKIpJc" x1="17.131" x2="17.131" y1="9.477" y2="8.66" gradientUnits="userSpaceOnUse"><stop class="bnalogb2m"/><stop offset="1" class="z119qywrr"/></linearGradient><linearGradient id="iBJz1Me" x1="16.016" x2="16.016" y1="13.135" y2="13.619" gradientUnits="userSpaceOnUse"><stop class="adeyt3biy"/><stop offset="1" class="falhm3ddg"/></linearGradient><linearGradient id="iaJUXbc" x1="16.311" x2="16.311" y1="25.33" y2="24.44" gradientUnits="userSpaceOnUse"><stop class="iv4y1_b_n"/><stop offset="1" class="m0qg90bho"/></linearGradient><linearGradient id="iDbN2Ic" x1="16.016" x2="16.016" y1="13.158" y2="13.83" gradientUnits="userSpaceOnUse"><stop class="jgdhkobbj"/><stop offset="1" class="wj-6klb4e"/></linearGradient><linearGradient id="iPCBRbc" x1="16.002" x2="16.002" y1="8.848" y2="9.602" gradientUnits="userSpaceOnUse"><stop class="j7l34tb_e"/><stop offset="1" class="zonrxxqjp"/></linearGradient><linearGradient id="ixSgJAc" x1="16.561" x2="16.561" y1="29.858" y2="29.096" gradientUnits="userSpaceOnUse"><stop offset=".167" class="d-qh370ov"/><stop offset="1" class="ckg96ab_f"/></linearGradient><linearGradient id="iiL3bMd" x1="16" x2="16" y1="24.821" y2="25.777" gradientUnits="userSpaceOnUse"><stop class="ljf-rb23f"/><stop offset="1" class="v8ur26f1j"/></linearGradient><linearGradient id="ibsL5fe" x1="19.092" x2="12.78" y1="20.158" y2="23.916" gradientUnits="userSpaceOnUse"><stop class="oi11t1bsk"/><stop offset="1" class="hosv7yiis"/></linearGradient><linearGradient id="ipxVcHB" x1="17.374" x2="19.852" y1="18.658" y2="17.262" gradientUnits="userSpaceOnUse"><stop class="oi11t1bsk"/><stop offset="1" class="hosv7yiis"/></linearGradient><radialGradient id="ieKaEIT" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61155 3.0777 -2.76622 -3.24605 18.575 4.891)" gradientUnits="userSpaceOnUse"><stop class="h2yveybmi"/><stop offset="1" class="nc5q6ab1c"/></radialGradient><radialGradient id="ii6jZ0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.63306 -2.85785 4.02207 2.29833 14.712 8.126)" gradientUnits="userSpaceOnUse"><stop class="j-edhkuuw"/><stop offset="1" class="w3d-bnixc"/></radialGradient><radialGradient id="inrTVtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78125 4.30307 0 14.03 24.596)" gradientUnits="userSpaceOnUse"><stop class="mx3jf9y-o"/><stop offset="1" class="f_6zj97el"/></radialGradient><radialGradient id="iZaopSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.6407 -1.64208 0 16.016 12.955)" gradientUnits="userSpaceOnUse"><stop class="x4twqwtrs"/><stop offset="1" class="e5ah99kvi"/></radialGradient><radialGradient id="i2VpYTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47603 -4.20111 0 18.481 10.544)" gradientUnits="userSpaceOnUse"><stop class="e8o_wr2lc"/><stop offset="1" class="pclp-hsoo"/></radialGradient><radialGradient id="idVPSAY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.61496 8.32231 0 14.744 13.16)" gradientUnits="userSpaceOnUse"><stop class="hb60_rb1z"/><stop offset="1" class="hqdug1bmc"/></radialGradient><radialGradient id="ixoc2re" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.46968 3.3125 0 16.108 13.16)" gradientUnits="userSpaceOnUse"><stop class="o1_xopb_k"/><stop offset="1" class="itshi6zsm"/></radialGradient><radialGradient id="i158z6c" cx="0" cy="0" r="1" gradientTransform="matrix(-11.5625 0 0 -3.75 21.249 28.596)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="k20z6-b2e"/><stop offset="1" class="bt9325y-f"/></radialGradient><filter id="iNSTdKe" width="12.624" height="13.292" x="9.553" y="12.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.345098 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4063"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.219608 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4063" result="effect2_innerShadow_18_4063"/></filter><filter id="iVvbuRc" width="11.258" height="7.008" x="11.936" y="18.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4063" stdDeviation="1"/></filter><filter id="i69Emqe" width="5.349" height="8.362" x="14.28" y="12.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4063" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chess-pawn" /></template>
<style>
.adeyt3biy {
  stop-color: var(--svg-color--241931, #241931);
}

.bnalogb2m {
  stop-color: var(--svg-color--16111c, #16111C);
}

.bt9325y-f {
  stop-color: var(--svg-color--575459, #575459);
  stop-opacity: 0;
}

.ckg96ab_f {
  stop-color: var(--svg-color--372447, #372447);
  stop-opacity: 0;
}

.d-qh370ov {
  stop-color: var(--svg-color--372447, #372447);
}

.e5ah99kvi {
  stop-color: var(--svg-color--453c4f, #453C4F);
  stop-opacity: 0;
}

.e6bm57b7l {
  d: path("M7.646 28.038a3 3 0 0 1 3-3h10.708a3 3 0 0 1 3 3v.82a1 1 0 0 1-1 1H8.646a1 1 0 0 1-1-1z");
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.eavefib1y {
  width: 9.5px;
  height: 4px;
  x: 11.252px;
  y: 9.159px;
  fill: var(--svg-color--302a36, #302A36);
  rx: 2px;
}

.er65e58xz {
  fill: var(--svg-color--29272c, #29272C);
  d: path("M13.611 12.955h4.81v3.556s0 .856.633 1.469c.478.5 1.97 2 1.97 2c2.11 2.205.474 6.267-2.507 6.267h-5.002c-2.982 0-4.617-4.062-2.508-6.267c0 0 1.492-1.5 1.97-2c.634-.613.634-1.469.634-1.469z");
}

.f_6zj97el {
  stop-color: var(--svg-color--32283d, #32283D);
  stop-opacity: 0;
}

.falhm3ddg {
  stop-color: var(--svg-color--241931, #241931);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h2yveybmi {
  stop-color: var(--svg-color--645c6c, #645C6C);
}

.hb60_rb1z {
  stop-color: var(--svg-color--2e1e3e, #2E1E3E);
}

.hosv7yiis {
  stop-color: var(--svg-color--59565d, #59565D);
  stop-opacity: 0;
}

.hqdug1bmc {
  stop-color: var(--svg-color--2e1e3e, #2E1E3E);
  stop-opacity: 0;
}

.itshi6zsm {
  stop-color: var(--svg-color--1e122a, #1E122A);
  stop-opacity: 0;
}

.iv4y1_b_n {
  stop-color: var(--svg-color--131016, #131016);
}

.j-edhkuuw {
  stop-color: var(--svg-color--3a294b, #3A294B);
}

.j7l34tb_e {
  stop-color: var(--svg-color--22182a, #22182A);
}

.j83dsda_w {
  d: path("M15.78 16.908v-3.187h2.125v3.187c0 .866.107 1.476.215 1.85c.048.164-.1.36-.265.319c-1.603-.395-2.056-1.582-2.075-2.169");
}

.jgdhkobbj {
  stop-color: var(--svg-color--231830, #231830);
}

.k_cn0xb0v {
  d: path("M13.936 20.908h7.247c.06.939 0 3.157-3.428 3c-2.69-.122-3.583-2.187-3.819-3");
}

.k20z6-b2e {
  stop-color: var(--svg-color--575459, #575459);
}

.ljf-rb23f {
  stop-color: var(--svg-color--1b181f, #1B181F);
}

.m0qg90bho {
  stop-color: var(--svg-color--131016, #131016);
  stop-opacity: 0;
}

.mx3jf9y-o {
  stop-color: var(--svg-color--32283d, #32283D);
}

.nc5q6ab1c {
  stop-color: var(--svg-color--352d3d, #352D3D);
}

.o1_xopb_k {
  stop-color: var(--svg-color--1e122a, #1E122A);
}

.oi11t1bsk {
  stop-color: var(--svg-color--59565d, #59565D);
}

.pclp-hsoo {
  stop-color: var(--svg-color--615b67, #615B67);
  stop-opacity: 0;
}

.pp3bv5b9z {
  fill: var(--svg-color--2a282c, #2A282C);
  d: path("M7.646 28.038a3 3 0 0 1 3-3h10.708a3 3 0 0 1 3 3v.82a1 1 0 0 1-1 1H8.646a1 1 0 0 1-1-1z");
}

.t3z0kebmf {
  width: 9.5px;
  height: 4px;
  x: 11.252px;
  y: 9.159px;
  rx: 2px;
}

.v8ur26f1j {
  stop-color: var(--svg-color--1b181f, #1B181F);
  stop-opacity: 0;
}

.w3d-bnixc {
  stop-color: var(--svg-color--3a294b, #3A294B);
  stop-opacity: 0;
}

.wj-6klb4e {
  stop-color: var(--svg-color--231830, #231830);
  stop-opacity: 0;
}

.x4twqwtrs {
  stop-color: var(--svg-color--453c4f, #453C4F);
}

.z119qywrr {
  stop-color: var(--svg-color--16111c, #16111C);
  stop-opacity: 0;
}

.zonrxxqjp {
  stop-color: var(--svg-color--22182a, #22182A);
  stop-opacity: 0;
}

.zwdifibaa {
  cx: 16.002px;
  cy: 6.17px;
  r: 4.17px;
}

.zzrvnth3p {
  d: path("M13.611 12.955h4.81v3.556s0 .856.633 1.469c.478.5 1.97 2 1.97 2c2.11 2.205.474 6.267-2.507 6.267h-5.002c-2.982 0-4.617-4.062-2.508-6.267c0 0 1.492-1.5 1.97-2c.634-.613.634-1.469.634-1.469z");
}

</style>
