<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#imKRENd)" class="rdsesgbkw"/><path fill="url(#imkvoKb)" class="rdsesgbkw"/><path fill="url(#i6XmtmF)" class="rdsesgbkw"/><g filter="url(#i9kSCFn)"><path fill="url(#iK80wKd)" class="lwbs3vats"/></g><g filter="url(#iTKybMc)"><rect transform="rotate(35.012 8.735 17.938)" class="n2keu-d_c"/></g><g filter="url(#iY8LCSb)"><path fill="url(#iF8Ktzc)" class="y7qnf8-6x"/></g><g filter="url(#ioz71ac)"><path fill="url(#iZw9kbb)" class="wa3auabfv"/></g><g filter="url(#iJk8Lbl)"><rect transform="rotate(35.012 14.934 22.05)" class="zp3yjz69k"/></g><rect fill="url(#iHKXogd)" transform="rotate(35.012 8.519 17.992)" class="anqr_-boy"/><rect fill="url(#irHKtDe)" transform="rotate(35.012 8.519 17.992)" class="anqr_-boy"/><rect fill="url(#inO1vld)" transform="rotate(35.012 14.585 22.05)" class="s4zgc_b2v"/><rect fill="url(#ijAz9BP)" transform="rotate(35.012 14.585 22.05)" class="s4zgc_b2v"/><g filter="url(#ihwDjAI)"><path fill="url(#i12Eund)" class="s8zi2lkkx"/></g><g filter="url(#ikrODld)"><path clip-rule="evenodd" class="ab8scvbri"/></g><path fill="url(#iu63y4h)" class="fhup19bmz"/><path fill="url(#i8MIaBd)" class="vc3xpbb2x"/><path stroke="url(#iUxAT9d)" class="odiw8owem"/><path stroke="url(#igWo59d)" class="i4uyxgb6q"/><circle fill="url(#iNyOQfd)" class="pb8579bvm"/><circle fill="url(#isiBSXb)" class="rns0dkbhf"/><circle fill="url(#iqKzYYM)" class="onsm46bup"/><circle fill="url(#i2a9L9U)" class="pjg-m6e8a"/><circle fill="url(#inUYohe)" class="ptnd0otrn"/><circle fill="url(#idBqNhc)" class="hfw8c-b9j"/><circle fill="url(#iSnHxfd)" transform="rotate(-29.511 11.481 10.54)" class="t7zga7bky"/><circle fill="url(#iu07gMd)" transform="rotate(-29.511 11.707 12.082)" class="za5fhwbhj"/><circle fill="url(#iPfwGZb)" transform="rotate(-29.511 10.72 12.004)" class="k6rc37bji"/><circle fill="url(#iI99lTb)" transform="rotate(-29.511 10.594 10.971)" class="qn8xgimul"/><circle fill="url(#iIQPYxZ)" transform="rotate(-29.511 11.346 11.317)" class="mbmsz8b9w"/><defs><linearGradient id="imKRENd" x1="22.826" x2="25.795" y1="27.258" y2="27.633" gradientUnits="userSpaceOnUse"><stop class="txjgp5brp"/><stop offset=".39" class="pxbjbfn8e"/></linearGradient><linearGradient id="imkvoKb" x1="29.404" x2="24.013" y1="27.008" y2="26.508" gradientUnits="userSpaceOnUse"><stop offset=".773" class="jzbahvl0b"/><stop offset=".868" class="zk2tr3btb"/></linearGradient><linearGradient id="i6XmtmF" x1="2.92" x2="8.67" y1="11.57" y2="13.695" gradientUnits="userSpaceOnUse"><stop class="jmr-qwbfn"/><stop offset="1" class="xtewuqbqt"/></linearGradient><linearGradient id="iK80wKd" x1="16.888" x2="17.592" y1="23.164" y2="21.711" gradientUnits="userSpaceOnUse"><stop class="tsx6t-bip"/><stop offset="1" class="nqmm0bbbo"/></linearGradient><linearGradient id="iF8Ktzc" x1="17.079" x2="17.782" y1="23.172" y2="21.719" gradientUnits="userSpaceOnUse"><stop class="tsx6t-bip"/><stop offset="1" class="nqmm0bbbo"/></linearGradient><linearGradient id="iZw9kbb" x1="16.799" x2="17.482" y1="23.508" y2="22.273" gradientUnits="userSpaceOnUse"><stop class="tsx6t-bip"/><stop offset="1" class="nqmm0bbbo"/></linearGradient><linearGradient id="iHKXogd" x1="8.925" x2="12.597" y1="18.909" y2="18.703" gradientUnits="userSpaceOnUse"><stop class="dq995geve"/><stop offset="1" class="p24se1bdh"/></linearGradient><linearGradient id="irHKtDe" x1="8.404" x2="8.982" y1="18.931" y2="18.717" gradientUnits="userSpaceOnUse"><stop class="n7tt0dj7f"/><stop offset="1" class="sp1vc0bqi"/></linearGradient><linearGradient id="inO1vld" x1="14.991" x2="18.662" y1="22.967" y2="22.761" gradientUnits="userSpaceOnUse"><stop class="dq995geve"/><stop offset="1" class="p24se1bdh"/></linearGradient><linearGradient id="ijAz9BP" x1="14.47" x2="15.048" y1="22.988" y2="22.775" gradientUnits="userSpaceOnUse"><stop class="n7tt0dj7f"/><stop offset="1" class="sp1vc0bqi"/></linearGradient><linearGradient id="i12Eund" x1="16.339" x2="16.339" y1="2.015" y2="22.945" gradientUnits="userSpaceOnUse"><stop offset=".15" class="ew3oa_bfx"/><stop offset="1" class="bujxfdbjc"/></linearGradient><linearGradient id="iu63y4h" x1="12.388" x2="14.138" y1="13.352" y2="12.082" gradientUnits="userSpaceOnUse"><stop class="h2wktsz9v"/><stop offset="1" class="xahy_zb6k"/></linearGradient><linearGradient id="i8MIaBd" x1="14.581" x2="14.581" y1="10.207" y2="12.023" gradientUnits="userSpaceOnUse"><stop class="ibieyubnu"/><stop offset="1" class="msy3kubwb"/></linearGradient><linearGradient id="iUxAT9d" x1="14.826" x2="14.093" y1="14.086" y2="9.977" gradientUnits="userSpaceOnUse"><stop class="cn-in89wd"/><stop offset="1" class="it_8em14s"/></linearGradient><linearGradient id="igWo59d" x1="16.67" x2="12.795" y1="12.851" y2="12.476" gradientUnits="userSpaceOnUse"><stop class="cn-in89wd"/><stop offset="1" class="it_8em14s"/></linearGradient><radialGradient id="iNyOQfd" cx="0" cy="0" r="1" gradientTransform="rotate(147.407 5.912 6.346)scale(1.13128)" gradientUnits="userSpaceOnUse"><stop class="nyxxdybhg"/><stop offset="1" class="miuw0db1k"/></radialGradient><radialGradient id="isiBSXb" cx="0" cy="0" r="1" gradientTransform="rotate(132.194 5.126 7.791)scale(1.1283)" gradientUnits="userSpaceOnUse"><stop class="nyxxdybhg"/><stop offset=".82" class="bewyuw63s"/></radialGradient><radialGradient id="iqKzYYM" cx="0" cy="0" r="1" gradientTransform="rotate(109.832 3.224 9.609)scale(1.01322)" gradientUnits="userSpaceOnUse"><stop class="srib--b3w"/><stop offset="1" class="miuw0db1k"/><stop offset="1" class="nmw7h438g"/></radialGradient><radialGradient id="i2a9L9U" cx="0" cy="0" r="1" gradientTransform="rotate(143.569 4.844 6.906)scale(1.22347)" gradientUnits="userSpaceOnUse"><stop class="srib--b3w"/><stop offset="1" class="miuw0db1k"/><stop offset="1" class="nmw7h438g"/></radialGradient><radialGradient id="inUYohe" cx="0" cy="0" r="1" gradientTransform="rotate(147.407 5.428 6.17)scale(1.13128)" gradientUnits="userSpaceOnUse"><stop class="nyxxdybhg"/><stop offset="1" class="miuw0db1k"/></radialGradient><radialGradient id="idBqNhc" cx="0" cy="0" r="1" gradientTransform="rotate(129.144 4.667 7.788)scale(.8663)" gradientUnits="userSpaceOnUse"><stop class="g2d0nt0ul"/><stop offset="1" class="p-5f8og9h"/></radialGradient><radialGradient id="iSnHxfd" cx="0" cy="0" r="1" gradientTransform="rotate(147.407 4.497 6.938)scale(1.13128)" gradientUnits="userSpaceOnUse"><stop class="nyxxdybhg"/><stop offset="1" class="miuw0db1k"/></radialGradient><radialGradient id="iu07gMd" cx="0" cy="0" r="1" gradientTransform="rotate(143.569 4.093 8.042)scale(1.22347)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bevj4oz8c"/><stop offset="1" class="q318ovjmf"/></radialGradient><radialGradient id="iPfwGZb" cx="0" cy="0" r="1" gradientTransform="rotate(143.569 3.613 7.84)scale(1.22347)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bevj4oz8c"/><stop offset="1" class="q318ovjmf"/></radialGradient><radialGradient id="iI99lTb" cx="0" cy="0" r="1" gradientTransform="rotate(147.407 3.99 7.023)scale(1.13128)" gradientUnits="userSpaceOnUse"><stop class="fkjvf3brg"/><stop offset="1" class="mrq2w_bff"/></radialGradient><radialGradient id="iIQPYxZ" cx="0" cy="0" r="1" gradientTransform="rotate(129.144 3.226 8.342)scale(.8663)" gradientUnits="userSpaceOnUse"><stop class="g2d0nt0ul"/><stop offset="1" class="p-5f8og9h"/></radialGradient><filter id="i9kSCFn" width="4.948" height="4.803" x="8.028" y="15.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26539" stdDeviation=".2"/></filter><filter id="iTKybMc" width="4.318" height="3.52" x="8.013" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26539" stdDeviation=".2"/></filter><filter id="iY8LCSb" width="4.948" height="4.803" x="8.219" y="15.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26539" stdDeviation=".2"/></filter><filter id="ioz71ac" width="4.948" height="4.803" x="14.363" y="20.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26539" stdDeviation=".2"/></filter><filter id="iJk8Lbl" width="4.318" height="3.52" x="14.212" y="21.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26539" stdDeviation=".2"/></filter><filter id="ihwDjAI" width="25.287" height="25.417" x="3.721" y="1.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.447059 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26539"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.262745 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26539" result="effect2_innerShadow_18_26539"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.192157 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_26539" result="effect3_innerShadow_18_26539"/></filter><filter id="ikrODld" width="7.533" height="7.588" x="9.175" y="7.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26539" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:coffin" /></template>
<style>
.ab8scvbri {
  fill: var(--svg-color--5a3041, #5A3041);
  fill-rule: evenodd;
  d: path("M13.577 8.086a.72.72 0 0 0-.459.163a.727.727 0 0 0-1.194.787a.727.727 0 0 0-.407.94a.725.725 0 0 0-.904.425a.726.726 0 0 0-.651 1.273a.727.727 0 0 0 1.018 1.024a.727.727 0 0 0 1.207-.214l.624.09a2.9 2.9 0 0 0-.81 1.082c-.03.07.03.145.105.128c.544-.123 1.064-.413 1.483-1.009l.331 1.521a.4.4 0 0 0 .782-.17l-.287-1.32L15.75 13a.4.4 0 1 0 .114-.792l-1.632-.236l-.002-.008c.316-.265.717-.763.885-1.519a.092.092 0 0 0-.127-.105c-.355.157-.683.39-.95.742l-.132-.605a.727.727 0 0 0 .308-1.318a.727.727 0 0 0-.639-1.073m-.992 3.648l.802.116l-.191-.88a.73.73 0 0 1-.89-.541a.7.7 0 0 1-.34-.028a.7.7 0 0 1 .05.252a.726.726 0 0 1 .569 1.08");
}

.anqr_-boy {
  width: 4.228px;
  height: 1.101px;
  x: 8.519px;
  y: 17.992px;
  rx: 0.551px;
}

.bevj4oz8c {
  stop-color: var(--svg-color--ca758a, #CA758A);
}

.bewyuw63s {
  stop-color: var(--svg-color--d17a8f, #D17A8F);
}

.bujxfdbjc {
  stop-color: var(--svg-color--714556, #714556);
}

.cn-in89wd {
  stop-color: var(--svg-color--87a863, #87A863);
}

.dq995geve {
  stop-color: var(--svg-color--c46c66, #C46C66);
}

.ew3oa_bfx {
  stop-color: var(--svg-color--83535a, #83535A);
}

.fhup19bmz {
  d: path("M12.193 13.532c.41-.938 1.133-1.356 1.459-1.45l.226.422c-.435.695-.993 1.023-1.58 1.155a.092.092 0 0 1-.105-.128");
}

.fkjvf3brg {
  stop-color: var(--svg-color--cc8384, #CC8384);
}

.ft5dv1b6b {
  fill: none;
}

.g2d0nt0ul {
  stop-color: var(--svg-color--ebc6d7, #EBC6D7);
}

.h2wktsz9v {
  stop-color: var(--svg-color--80a465, #80A465);
}

.hfw8c-b9j {
  cx: 13.269px;
  cy: 9.297px;
  r: 0.609px;
}

.i4uyxgb6q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M12.186 11.927L16 12.48");
}

.ibieyubnu {
  stop-color: var(--svg-color--5c9b6e, #5C9B6E);
}

.it_8em14s {
  stop-color: var(--svg-color--508857, #508857);
}

.jmr-qwbfn {
  stop-color: var(--svg-color--aa9796, #AA9796);
}

.jzbahvl0b {
  stop-color: var(--svg-color--7e4e79, #7E4E79);
}

.k6rc37bji {
  cx: 10.72px;
  cy: 12.004px;
  r: 0.727px;
}

.lwbs3vats {
  d: path("m8.95 16.383l3.626 2.14l-.785 1.863l-3.363-2.356z");
}

.mbmsz8b9w {
  cx: 11.346px;
  cy: 11.317px;
  r: 0.609px;
}

.miuw0db1k {
  stop-color: var(--svg-color--ca7479, #CA7479);
}

.mrq2w_bff {
  stop-color: var(--svg-color--c56a83, #C56A83);
}

.msy3kubwb {
  stop-color: var(--svg-color--699f6c, #699F6C);
}

.n2keu-d_c {
  width: 4.106px;
  height: 0.854px;
  x: 8.735px;
  y: 17.938px;
  fill: var(--svg-color--632939, #632939);
  rx: 0.427px;
}

.n7tt0dj7f {
  stop-color: var(--svg-color--d49887, #D49887);
}

.nmw7h438g {
  stop-color: var(--svg-color--c76e77, #C76E77);
}

.nqmm0bbbo {
  stop-color: var(--svg-color--763f6d, #763F6D);
  stop-opacity: 0;
}

.nyxxdybhg {
  stop-color: var(--svg-color--dc9590, #DC9590);
}

.odiw8owem {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m13.683 10.32l.82 3.766");
}

.onsm46bup {
  cx: 13.206px;
  cy: 10.141px;
  r: 0.727px;
}

.p-5f8og9h {
  stop-color: var(--svg-color--dcadc8, #DCADC8);
}

.p24se1bdh {
  stop-color: var(--svg-color--bd5458, #BD5458);
}

.pb8579bvm {
  cx: 13.769px;
  cy: 8.688px;
  r: 0.727px;
}

.pjg-m6e8a {
  cx: 12.386px;
  cy: 9.586px;
  r: 0.727px;
}

.ptnd0otrn {
  cx: 12.784px;
  cy: 8.625px;
  r: 0.727px;
}

.pxbjbfn8e {
  stop-color: var(--svg-color--7b3683, #7B3683);
}

.q318ovjmf {
  stop-color: var(--svg-color--c05f80, #C05F80);
}

.qn8xgimul {
  cx: 10.594px;
  cy: 10.971px;
  r: 0.727px;
}

.rdsesgbkw {
  d: path("m4.894 16.404l-1.173-4.6a2 2 0 0 1-.054-.671h-.005l.26-3.297H6.17l2.086-2.229a2 2 0 0 1 2.104-.527l5.412 1.841a3 3 0 0 1 1.508 1.143l9.36 13.643h2.118v3.403a1 1 0 0 1-.281.688l-3.976 4.117a1.25 1.25 0 0 1-1.611.16L6.49 18.702a4 4 0 0 1-1.596-2.299");
}

.rns0dkbhf {
  cx: 13.995px;
  cy: 9.633px;
  r: 0.727px;
}

.s4zgc_b2v {
  width: 4.228px;
  height: 1.101px;
  x: 14.585px;
  y: 22.05px;
  rx: 0.551px;
}

.s8zi2lkkx {
  d: path("M5.458 13.783L3.993 8.454a2 2 0 0 1 .51-1.94l3.887-3.91a2 2 0 0 1 1.956-.515l5.218 1.456a3 3 0 0 1 1.66 1.181L28.58 21.118a1 1 0 0 1-.1 1.26l-4.112 4.296a1 1 0 0 1-1.29.13L6.646 15.457a3 3 0 0 1-1.188-1.673");
}

.sp1vc0bqi {
  stop-color: var(--svg-color--d49887, #D49887);
  stop-opacity: 0;
}

.srib--b3w {
  stop-color: var(--svg-color--d38491, #D38491);
}

.t7zga7bky {
  cx: 11.481px;
  cy: 10.54px;
  r: 0.727px;
}

.tsx6t-bip {
  stop-color: var(--svg-color--763f6d, #763F6D);
}

.txjgp5brp {
  stop-color: var(--svg-color--7e4a81, #7E4A81);
}

.vc3xpbb2x {
  d: path("M15.308 10.32c-.222.999-.851 1.548-1.153 1.703l-.303-.371c.293-.765.778-1.194 1.33-1.437c.07-.03.143.03.126.105");
}

.wa3auabfv {
  d: path("m15.285 20.654l3.626 2.14l-.785 1.864l-3.364-2.356z");
}

.xahy_zb6k {
  stop-color: var(--svg-color--749e65, #749E65);
}

.xtewuqbqt {
  stop-color: var(--svg-color--aa9796, #AA9796);
  stop-opacity: 0;
}

.y7qnf8-6x {
  d: path("m9.141 16.39l3.626 2.141l-.785 1.863l-3.364-2.356z");
}

.za5fhwbhj {
  cx: 11.707px;
  cy: 12.082px;
  r: 0.727px;
}

.zk2tr3btb {
  stop-color: var(--svg-color--7e4e79, #7E4E79);
  stop-opacity: 0;
}

.zp3yjz69k {
  width: 4.106px;
  height: 0.854px;
  x: 14.934px;
  y: 22.05px;
  fill: var(--svg-color--632939, #632939);
  rx: 0.427px;
}

</style>
