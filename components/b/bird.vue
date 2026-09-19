<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipLsj1c)" class="y7uwxwbpx"/><path fill="url(#iqbSroe)" class="y7uwxwbpx"/><path fill="url(#irLoLcb)" class="vv219tb8t"/><path fill="url(#ihVSnfd)" class="vv219tb8t"/><path fill="url(#iuyDGQe)" class="vv219tb8t"/><path fill="url(#iXU9oZf)" class="vv219tb8t"/><g filter="url(#iLFxFZb)"><path stroke="url(#iyrxPZc)" class="cs182bc-x"/></g><path fill="url(#ir9y8Nd)" class="ayjg6-bvj"/><path fill="url(#iUEZwlb)" class="ayjg6-bvj"/><path fill="url(#ipEyWub)" class="ayjg6-bvj"/><path fill="url(#iipq0Bb)" class="ayjg6-bvj"/><g filter="url(#i4S1gZd)"><path stroke="url(#itkEDce)" class="dk84z2irh"/></g><path fill="url(#iIdLPce)" class="g1gq_dbdt"/><path fill="url(#i5uuoRj)" class="g1gq_dbdt"/><path fill="url(#ihAtYyd)" class="g1gq_dbdt"/><path fill="url(#iGhueXb)" class="opljwacki"/><path fill="url(#iZKcqbI)" class="opljwacki"/><path fill="url(#iNG7PYb)" class="opljwacki"/><path fill="url(#i45qBYc)" class="opljwacki"/><path fill="url(#iXLf5TG)" class="opljwacki"/><path fill="url(#ioaCnHc)" class="z5gx07bgb"/><path fill="url(#ilES5Gb)" class="moxd2sbyh"/><path fill="url(#iyTbope)" class="moxd2sbyh"/><path fill="url(#iTXi6Oe)" class="moxd2sbyh"/><g filter="url(#iHmKFpd)"><path fill="url(#iO5DjHQ)" class="mdgxiiu_w"/></g><g filter="url(#iYMKGYb)"><path stroke="url(#itMIAlc)" class="gmim4nktt"/></g><path fill="url(#iXfkZ3d)" clip-rule="evenodd" class="zdrw0ubis"/><g filter="url(#iqjU1WR)"><path stroke="url(#iDAYsOd)" class="u0dvf2zyz"/></g><defs><linearGradient id="irLoLcb" x1="12.064" x2="10.86" y1="23.952" y2="30.658" gradientUnits="userSpaceOnUse"><stop class="n7rj7zw7e"/><stop offset="1" class="f-aaq5bek"/></linearGradient><linearGradient id="ihVSnfd" x1="11.63" x2="11.023" y1="24.469" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="ddo4vibhm"/><stop offset="1" class="jrh3blbxx"/></linearGradient><linearGradient id="iXU9oZf" x1="11.023" x2="11.023" y1="30.719" y2="29.187" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="iyrxPZc" x1="11.646" x2="8.192" y1="29.938" y2="29.938" gradientUnits="userSpaceOnUse"><stop class="z5fwcmz9p"/><stop offset="1" class="zthkikbxu"/></linearGradient><linearGradient id="ir9y8Nd" x1="17.102" x2="16.067" y1="23.952" y2="29.237" gradientUnits="userSpaceOnUse"><stop class="n7rj7zw7e"/><stop offset="1" class="f-aaq5bek"/></linearGradient><linearGradient id="iUEZwlb" x1="16.665" x2="16.062" y1="24.469" y2="27.845" gradientUnits="userSpaceOnUse"><stop class="ddo4vibhm"/><stop offset="1" class="jrh3blbxx"/></linearGradient><linearGradient id="ipEyWub" x1="16.053" x2="16.053" y1="30.719" y2="29.187" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="itkEDce" x1="17.33" x2="13.293" y1="29.938" y2="29.938" gradientUnits="userSpaceOnUse"><stop class="z5fwcmz9p"/><stop offset="1" class="zthkikbxu"/></linearGradient><linearGradient id="iIdLPce" x1="17.324" x2="28.474" y1="21.137" y2="21.137" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="i5uuoRj" x1="20.316" x2="20.316" y1="27.875" y2="23.5" gradientUnits="userSpaceOnUse"><stop offset=".271" class="lp7p36b3w"/><stop offset="1" class="be3mk-b4f"/></linearGradient><linearGradient id="ihAtYyd" x1="16.724" x2="19.786" y1="12.938" y2="19.701" gradientUnits="userSpaceOnUse"><stop class="lp7p36b3w"/><stop offset="1" class="be3mk-b4f"/></linearGradient><linearGradient id="iGhueXb" x1="10.508" x2="10.508" y1="-2.928" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iZKcqbI" x1="9.161" x2="9.161" y1="26.188" y2="17.75" gradientUnits="userSpaceOnUse"><stop class="lp7p36b3w"/><stop offset="1" class="be3mk-b4f"/></linearGradient><linearGradient id="i45qBYc" x1="3.661" x2="8.849" y1="15.938" y2="15.938" gradientUnits="userSpaceOnUse"><stop class="w7ipstb0e"/><stop offset="1" class="i59eslbfv"/></linearGradient><linearGradient id="ioaCnHc" x1="18.544" x2="14.42" y1="22.125" y2="10.285" gradientUnits="userSpaceOnUse"><stop class="c3htxbc9y"/><stop offset="1" class="xp-428bxe"/></linearGradient><linearGradient id="iTXi6Oe" x1="9.939" x2="9.596" y1="8.131" y2="7.912" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iO5DjHQ" x1="19.724" x2="15.88" y1="20.875" y2="2.563" gradientUnits="userSpaceOnUse"><stop class="kpx0s-b_y"/><stop offset="1" class="f06zu6bii"/></linearGradient><linearGradient id="itMIAlc" x1="19.427" x2="17.395" y1="3.794" y2="5.387" gradientUnits="userSpaceOnUse"><stop class="ifu16v9om"/><stop offset="1" class="vkw0fxvnm"/></linearGradient><linearGradient id="iXfkZ3d" x1="17.255" x2="16.583" y1="5.027" y2="6.172" gradientUnits="userSpaceOnUse"><stop class="tl_l9f0kz"/><stop offset="1" class="wnn1yktjo"/></linearGradient><linearGradient id="iDAYsOd" x1="29.864" x2="29.864" y1="15.063" y2="23.969" gradientUnits="userSpaceOnUse"><stop class="s9tnw8mfx"/><stop offset="1" class="kw27o1_mi"/></linearGradient><radialGradient id="ipLsj1c" cx="0" cy="0" r="1" gradientTransform="matrix(7.25 0 0 4.46875 3.724 9.469)" gradientUnits="userSpaceOnUse"><stop class="hmh_tqbda"/><stop offset="1" class="fsweid5ds"/></radialGradient><radialGradient id="iqbSroe" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.60937 .43877 2.07011 3.974 9.406)" gradientUnits="userSpaceOnUse"><stop class="z00sc4vob"/><stop offset="1" class="d03_imaef"/></radialGradient><radialGradient id="iuyDGQe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 0 0 -2.54664 12.849 30)" gradientUnits="userSpaceOnUse"><stop class="dlf6ubcnk"/><stop offset="1" class="yyc1b7j1z"/></radialGradient><radialGradient id="iipq0Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01714 -.25 .15804 -1.2752 20.069 29.531)" gradientUnits="userSpaceOnUse"><stop class="tq0ogeb4k"/><stop offset="1" class="ynwky3ese"/></radialGradient><radialGradient id="iNG7PYb" cx="0" cy="0" r="1" gradientTransform="rotate(132.87 4.285 13.846)scale(4.60499 6.33279)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="e98eezbpf"/><stop offset="1" class="k-7zke8_t"/></radialGradient><radialGradient id="iXLf5TG" cx="0" cy="0" r="1" gradientTransform="matrix(-15.33834 -22.71864 15.55181 -10.4997 23.874 25)" gradientUnits="userSpaceOnUse"><stop offset=".904" class="i59eslbfv"/><stop offset="1" class="w7ipstb0e"/></radialGradient><radialGradient id="ilES5Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 10.186 8.362)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iyTbope" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 3.485 6.18)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><filter id="iLFxFZb" width="5.172" height=".75" x="7.614" y="29.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4842" stdDeviation=".125"/></filter><filter id="i4S1gZd" width="7.359" height=".75" x="12.458" y="29.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4842" stdDeviation=".125"/></filter><filter id="iHmKFpd" width="13.559" height="21.321" x="10.914" y="4.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4842" stdDeviation="1"/></filter><filter id="iYMKGYb" width="3.482" height="2.496" x="16.563" y="2.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4842" stdDeviation=".25"/></filter><filter id="iqjU1WR" width="1.2" height="10.106" x="28.764" y="14.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4842" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bird" /></template>
<style>
.ayjg6-bvj {
  d: path("M18.594 28.5h-1.78l1.2-6h-1.5l-1.2 6h-1.8c-.73 0-1.33.52-1.47 1.21c-.04.15.09.29.24.29h7.53c.16 0 .28-.14.25-.29a1.51 1.51 0 0 0-1.47-1.21");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.be3mk-b4f {
  stop-color: var(--svg-color--9f31a1, #9F31A1);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cs182bc-x {
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.864 29.578h4.672");
}

.d03_imaef {
  stop-color: var(--svg-color--ffd150, #FFD150);
  stop-opacity: 0;
}

.ddo4vibhm {
  stop-color: var(--svg-color--b87e33, #B87E33);
}

.dk84z2irh {
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.708 29.578h6.86");
}

.dlf6ubcnk {
  stop-color: var(--svg-color--c67500, #C67500);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.e98eezbpf {
  stop-color: var(--svg-color--ba2159, #BA2159);
}

.f-aaq5bek {
  stop-color: var(--svg-color--e99d23, #E99D23);
}

.f06zu6bii {
  stop-color: var(--svg-color--ff589b, #FF589B);
  stop-opacity: 0;
}

.fsweid5ds {
  stop-color: var(--svg-color--be8244, #BE8244);
}

.ft5dv1b6b {
  fill: none;
}

.g1gq_dbdt {
  d: path("m17.324 25l.14-5.23l11.38-5.3a.726.726 0 0 1 1.03.65v9.15c0 .4-.32.72-.72.72h-11.83z");
}

.gmim4nktt {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.067 4.484c.571.02 1.93-.053 2.36-1.328");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hmh_tqbda {
  stop-color: var(--svg-color--edb134, #EDB134);
}

.i59eslbfv {
  stop-color: var(--svg-color--b2516b, #B2516B);
  stop-opacity: 0;
}

.ifu16v9om {
  stop-color: var(--svg-color--ffb3d1, #FFB3D1);
}

.jrh3blbxx {
  stop-color: var(--svg-color--b87e33, #B87E33);
  stop-opacity: 0;
}

.k-7zke8_t {
  stop-color: var(--svg-color--ba2159, #BA2159);
  stop-opacity: 0;
}

.kpx0s-b_y {
  stop-color: var(--svg-color--ff589b, #FF589B);
}

.kw27o1_mi {
  stop-color: var(--svg-color--ff5cab, #FF5CAB);
  stop-opacity: 0;
}

.lp7p36b3w {
  stop-color: var(--svg-color--992e9b, #992E9B);
}

.mdgxiiu_w {
  d: path("m14.599 18.767l-1.685-12.58h3.56l5.968 16.653a.5.5 0 0 1-.543.663l-3.074-.453a5 5 0 0 1-4.226-4.283");
}

.moxd2sbyh {
  d: path("M10.038 9.023a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.n7rj7zw7e {
  stop-color: var(--svg-color--d69946, #D69946);
}

.opljwacki {
  d: path("M17.604 6.22c-.13-.42-.3-.82-.52-1.19h.62c1.29 0 2.33-1.04 2.33-2.33c0-.38-.32-.7-.7-.7h-7.46c-3.18 0-5.78 2.48-5.99 5.61l-1.29 11.18c-.38 3.31 2.2 6.21 5.53 6.21h13.75z");
}

.p_ptxbjeb {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
}

.s9tnw8mfx {
  stop-color: var(--svg-color--ff5cab, #FF5CAB);
}

.tl_l9f0kz {
  stop-color: var(--svg-color--a92e39, #A92E39);
}

.tq0ogeb4k {
  stop-color: var(--svg-color--ffbd59, #FFBD59);
}

.u0dvf2zyz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M29.364 15.063v8.906");
}

.u5vkysn3x {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
  stop-opacity: 0;
}

.vkw0fxvnm {
  stop-color: var(--svg-color--ffb3d1, #FFB3D1);
  stop-opacity: 0;
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vv219tb8t {
  d: path("M13.534 28.5h-1.72l1.2-6h-1.5l-1.2 6h-1.8c-.73 0-1.33.52-1.47 1.21c-.04.15.09.29.24.29h7.47c.16 0 .28-.14.25-.29c-.14-.69-.74-1.21-1.47-1.21");
}

.w7ipstb0e {
  stop-color: var(--svg-color--b2516b, #B2516B);
}

.wnn1yktjo {
  stop-color: var(--svg-color--a92e39, #A92E39);
  stop-opacity: 0;
}

.xp-428bxe {
  stop-color: var(--svg-color--ed1746, #ED1746);
}

.y7uwxwbpx {
  d: path("m6.424 7.22l-3.07 1.61c-.36.19-.43.68-.13.97l2.61 2.47z");
}

.ynwky3ese {
  stop-color: var(--svg-color--ffbd59, #FFBD59);
  stop-opacity: 0;
}

.yyc1b7j1z {
  stop-color: var(--svg-color--c67500, #C67500);
  stop-opacity: 0;
}

.z00sc4vob {
  stop-color: var(--svg-color--ffd150, #FFD150);
}

.z5fwcmz9p {
  stop-color: var(--svg-color--fdb65d, #FDB65D);
}

.z5gx07bgb {
  d: path("M13.214 11v6.93a7.07 7.07 0 0 0 7.07 7.07h3.59l-4.67-14z");
}

.zdrw0ubis {
  fill-rule: evenodd;
  d: path("M17.084 5.03c.22.37.39.77.52 1.19l.536 1.603l-4.28-2.796h3.844l.001.003z");
}

.zthkikbxu {
  stop-color: var(--svg-color--fdb65d, #FDB65D);
  stop-opacity: 0;
}

</style>
