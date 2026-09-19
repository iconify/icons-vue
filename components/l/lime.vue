<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iTKGJ8b)" class="hyyrw6mwt"/><path fill="url(#i7ALoph)" class="hyyrw6mwt"/><path fill="url(#i6zExnc)" class="hyyrw6mwt"/><path fill="url(#iOMP4xs)" class="hyyrw6mwt"/><path fill="url(#igUYIze)" class="hyyrw6mwt"/><path fill="url(#iA8h1Hd)" class="r_6-4qbmx"/><path fill="url(#ig9ESwc)" class="r_6-4qbmx"/><path fill="url(#ihuIscc)" class="r_6-4qbmx"/><path fill="url(#iQdW5Sc)" class="fxgu72tlp"/><path fill="url(#iLRJcAc)" class="fxgu72tlp"/><path class="bitrq2b7i"/><path fill="url(#izdMbFe)" class="ipfbtpb3s"/><path fill="url(#ipn1Xky)" class="ipfbtpb3s"/><path fill="url(#iJoPlSb)" class="ipfbtpb3s"/><path class="puo6ki23x"/><path fill="url(#iQPk2ye)" class="kvdkpzbut"/><path fill="url(#iKGl3ie)" class="kvdkpzbut"/><path class="em3jp7bph"/><path fill="url(#ifYZ4xT)" class="ky1kyibhi"/><defs><radialGradient id="i7ALoph" cx="0" cy="0" r="1" gradientTransform="rotate(101.896 8.239 8.482)scale(34.3625 23.2845)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="dtqa16bnh"/><stop offset=".804" class="ho2t7grfj"/></radialGradient><radialGradient id="i6zExnc" cx="0" cy="0" r="1" gradientTransform="rotate(81.872 5.083 8.39)scale(32.2394 21.8458)" gradientUnits="userSpaceOnUse"><stop class="ykdlqf2mf"/><stop offset=".775" class="dtqa16bnh"/></radialGradient><radialGradient id="iOMP4xs" cx="0" cy="0" r="1" gradientTransform="rotate(91.809 8.068 9.92)scale(31.9345 21.6392)" gradientUnits="userSpaceOnUse"><stop class="ho2t7grfj"/><stop offset=".505" class="dtqa16bnh"/></radialGradient><radialGradient id="igUYIze" cx="0" cy="0" r="1" gradientTransform="rotate(35.651 -19.638 27.504)scale(17.0153 20.6619)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="jm_hzsbws"/><stop offset=".774" class="dtqa16bnh"/></radialGradient><radialGradient id="iA8h1Hd" cx="0" cy="0" r="1" gradientTransform="matrix(14.5 8 -7.6677 13.8977 12.5 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="d141pw9sb"/><stop offset=".816" class="eceirp9ka"/><stop offset=".846" class="pj3v3colm"/></radialGradient><radialGradient id="ihuIscc" cx="0" cy="0" r="1" gradientTransform="matrix(-15.49998 -5.5001 5.1374 -14.47783 23.5 25)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qoy7aj94z"/><stop offset="1" class="ztyhcdcli"/></radialGradient><radialGradient id="izdMbFe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 19.5 -21.6806 5.0032 13.5 12)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="zix6adbqf"/><stop offset=".404" class="qgyk4xbrm"/></radialGradient><radialGradient id="ipn1Xky" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00006 22 -24.46017 -4.44737 22 9.5)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="zix6adbqf"/><stop offset=".404" class="qgyk4xbrm"/></radialGradient><radialGradient id="iQPk2ye" cx="0" cy="0" r="1" gradientTransform="matrix(1.70799 20.99675 -30.24101 2.45996 15.767 21.814)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="zix6adbqf"/><stop offset=".408" class="qgyk4xbrm"/></radialGradient><radialGradient id="iKGl3ie" cx="0" cy="0" r="1" gradientTransform="rotate(71.035 -7.106 14.055)scale(24.63 35.4738)" gradientUnits="userSpaceOnUse"><stop offset=".299" class="zix6adbqf"/><stop offset=".408" class="qgyk4xbrm"/></radialGradient><radialGradient id="ifYZ4xT" cx="0" cy="0" r="1" gradientTransform="matrix(5.2921 22.76446 -22.00394 5.1153 4.5 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="zix6adbqf"/><stop offset=".404" class="qgyk4xbrm"/></radialGradient><linearGradient id="iTKGJ8b" x1="28.085" x2="12.157" y1="8.345" y2="28.768" gradientUnits="userSpaceOnUse"><stop offset=".007" class="c03p8_b5h"/><stop offset="1" class="wdmimkbki"/></linearGradient><linearGradient id="ig9ESwc" x1="9.5" x2="15" y1="10.5" y2="15" gradientUnits="userSpaceOnUse"><stop offset=".372" class="qww2qeqhk"/><stop offset=".727" class="evtk_dbfp"/></linearGradient><linearGradient id="iQdW5Sc" x1="18" x2="11" y1="5.5" y2="24" gradientUnits="userSpaceOnUse"><stop class="i6u39ybye"/><stop offset="1" class="r2hfcmbtr"/></linearGradient><linearGradient id="iLRJcAc" x1="11" x2="18.5" y1="8" y2="14" gradientUnits="userSpaceOnUse"><stop offset=".436" class="fc2v0cc8p"/><stop offset=".605" class="vsiureb4a"/></linearGradient><linearGradient id="iJoPlSb" x1="24.5" x2="18" y1="-12" y2="31.5" gradientUnits="userSpaceOnUse"><stop offset=".542" class="zix6adbqf"/><stop offset=".609" class="qgyk4xbrm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lime" /></template>
<style>
.bitrq2b7i {
  fill: var(--svg-color--b7f54c, #B7F54C);
  d: path("m14.607 12.138l5.795.66c1.04.119 1.897-.806 1.678-1.82a9.8 9.8 0 0 0-3.378-5.516l-4.583 5.473a.736.736 0 0 0 .488 1.204z");
}

.c03p8_b5h {
  stop-color: var(--svg-color--99ce6f, #99CE6F);
}

.d141pw9sb {
  stop-color: var(--svg-color--a1da3e, #A1DA3E);
}

.dtqa16bnh {
  stop-color: var(--svg-color--387569, #387569);
  stop-opacity: 0;
}

.eceirp9ka {
  stop-color: var(--svg-color--c6fe65, #C6FE65);
}

.em3jp7bph {
  fill: var(--svg-color--b4ef4d, #B4EF4D);
  d: path("m13.586 20.937l-1.731-5.512a.749.749 0 0 0-1.286-.252l-4.584 5.473a9.98 9.98 0 0 0 6.104 2.261c1.047.025 1.807-.98 1.496-1.97");
}

.evtk_dbfp {
  stop-color: var(--svg-color--95c35d, #95C35D);
  stop-opacity: 0;
}

.fc2v0cc8p {
  stop-color: var(--svg-color--e4f8a3, #E4F8A3);
}

.ft5dv1b6b {
  fill: none;
}

.fxgu72tlp {
  d: path("M21.673 20.706c4.263-5.09 3.547-12.665-1.597-16.883L4.612 22.285c5.144 4.22 12.798 3.51 17.06-1.58");
}

.ho2t7grfj {
  stop-color: var(--svg-color--377569, #377569);
}

.hyyrw6mwt {
  d: path("M23.995 4.83c5.875 4.82 6.696 13.434 1.839 19.255c-4.854 5.816-13.716 6.562-19.585 1.748l-1.755-1.44a1.246 1.246 0 0 1-.167-1.768L20.361 3.482a1.277 1.277 0 0 1 1.787-.165l1.846 1.514");
}

.i6u39ybye {
  stop-color: var(--svg-color--faffad, #FAFFAD);
}

.ipfbtpb3s {
  d: path("m14.607 12.138l5.795.66c1.04.119 1.897-.806 1.678-1.82a9.8 9.8 0 0 0-3.378-5.516l-4.583 5.473a.736.736 0 0 0 .488 1.204z");
}

.jm_hzsbws {
  stop-color: var(--svg-color--253e1b, #253E1B);
}

.kvdkpzbut {
  d: path("m13.213 14.836l1.855 5.906a1.538 1.538 0 0 0 2.217.874a9.9 9.9 0 0 0 4.479-5.347c.317-.914-.309-1.883-1.28-1.994l-6.209-.707a.986.986 0 0 0-1.062 1.268");
}

.ky1kyibhi {
  d: path("m13.586 20.937l-1.731-5.512a.749.749 0 0 0-1.286-.252l-4.584 5.473a9.98 9.98 0 0 0 6.104 2.261c1.047.025 1.807-.98 1.496-1.97");
}

.pj3v3colm {
  stop-color: var(--svg-color--ade934, #ADE934);
}

.puo6ki23x {
  fill: var(--svg-color--b7f54e, #B7F54E);
  d: path("m13.213 14.836l1.855 5.906a1.538 1.538 0 0 0 2.217.874a9.9 9.9 0 0 0 4.479-5.347c.317-.914-.309-1.883-1.28-1.994l-6.209-.707a.986.986 0 0 0-1.062 1.268");
}

.qgyk4xbrm {
  stop-color: var(--svg-color--8dc843, #8DC843);
}

.qoy7aj94z {
  stop-color: var(--svg-color--a1da28, #A1DA28);
}

.qww2qeqhk {
  stop-color: var(--svg-color--8ec827, #8EC827);
}

.r_6-4qbmx {
  d: path("M4.254 22.712a1.09 1.09 0 0 0 .228 1.606c5.837 3.998 13.897 2.98 18.512-2.53c4.614-5.509 4.13-13.535-.925-18.468a1.12 1.12 0 0 0-1.636.076z");
}

.r2hfcmbtr {
  stop-color: var(--svg-color--ffffc4, #FFFFC4);
}

.vsiureb4a {
  stop-color: var(--svg-color--e4f9a3, #E4F9A3);
  stop-opacity: 0;
}

.wdmimkbki {
  stop-color: var(--svg-color--367c6b, #367C6B);
}

.ykdlqf2mf {
  stop-color: var(--svg-color--7dc461, #7DC461);
}

.zix6adbqf {
  stop-color: var(--svg-color--b7f54d, #B7F54D);
  stop-opacity: 0;
}

.ztyhcdcli {
  stop-color: var(--svg-color--a2da28, #A2DA28);
  stop-opacity: 0;
}

</style>
