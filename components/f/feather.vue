<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icElxEb)"><path fill="url(#inqf8Ed)" class="obn74ko8j"/><path fill="url(#i76Rh1b)" class="obn74ko8j"/><path fill="url(#iok3Wzb)" class="obn74ko8j"/><path fill="url(#iv7atbU)" class="obn74ko8j"/><path fill="url(#i0VANib)" class="obn74ko8j"/></g><path fill="url(#irlduGQ)" class="obn74ko8j"/><path fill="url(#iNp35YK)" class="obn74ko8j"/><path fill="url(#i6Aadnb)" class="zz_gq-u7m"/><path fill="url(#i3zJ02b)" class="zz_gq-u7m"/><path fill="url(#imIOenB)" class="zz_gq-u7m"/><g filter="url(#iINraWc)"><path class="n9kbl3wcn"/></g><g filter="url(#ici3KMe)"><path fill="url(#iCNWCEj)" class="sfai8phsn"/><path fill="url(#isC8ITd)" class="sfai8phsn"/></g><path fill="url(#iF9sU9d)" class="sfai8phsn"/><path fill="url(#iYRY2sv)" class="sfai8phsn"/><g filter="url(#ieoFHDb)"><path stroke="url(#iR2A2ub)" class="rapp70b6u"/></g><defs><radialGradient id="i76Rh1b" cx="0" cy="0" r="1" gradientTransform="rotate(-118.387 16.077 7.399)scale(12.1454 61.4735)" gradientUnits="userSpaceOnUse"><stop class="c2onurbrk"/><stop offset="1" class="y00c-obev"/></radialGradient><radialGradient id="iok3Wzb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 -.625 .14484 -.97045 14.156 22.469)" gradientUnits="userSpaceOnUse"><stop class="m2n2fmb9w"/><stop offset="1" class="q-l5-yk7p"/></radialGradient><radialGradient id="iv7atbU" cx="0" cy="0" r="1" gradientTransform="rotate(-122.876 15.586 .874)scale(6.10232 3.47844)" gradientUnits="userSpaceOnUse"><stop class="m2n2fmb9w"/><stop offset="1" class="q-l5-yk7p"/></radialGradient><radialGradient id="i0VANib" cx="0" cy="0" r="1" gradientTransform="matrix(-13.87509 -10.31244 18.9087 -25.4411 21.688 22.313)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="lkdtyzbss"/><stop offset="1" class="udwej920g"/></radialGradient><radialGradient id="iNp35YK" cx="0" cy="0" r="1" gradientTransform="matrix(-2.33683 1.49999 -.7248 -1.12916 30.212 2.219)" gradientUnits="userSpaceOnUse"><stop class="ks-_trb4m"/><stop offset="1" class="yj4zgxboi"/></radialGradient><radialGradient id="i3zJ02b" cx="0" cy="0" r="1" gradientTransform="rotate(-152.671 13.183 3.514)scale(5.24125 2.12873)" gradientUnits="userSpaceOnUse"><stop class="lnwkv8bdt"/><stop offset="1" class="lullgybpd"/></radialGradient><radialGradient id="iF9sU9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.77611 .34375 -.2553 -.5764 25.527 4.172)" gradientUnits="userSpaceOnUse"><stop class="s40jpibwn"/><stop offset="1" class="zwog-3b1n"/></radialGradient><radialGradient id="iYRY2sv" cx="0" cy="0" r="1" gradientTransform="matrix(-.84374 -1.25 6.28208 -4.24035 20.906 8.375)" gradientUnits="userSpaceOnUse"><stop class="iaq1-uzhn"/><stop offset="1" class="vlyjdfcxx"/></radialGradient><linearGradient id="inqf8Ed" x1="1.437" x2="26.427" y1="27.875" y2="1.202" gradientUnits="userSpaceOnUse"><stop class="bwk35rjdi"/><stop offset="1" class="gc75n1w1i"/></linearGradient><linearGradient id="irlduGQ" x1="27.125" x2="17.688" y1=".188" y2="7.875" gradientUnits="userSpaceOnUse"><stop class="rb_60ybll"/><stop offset="1" class="qr8yb7b5e"/></linearGradient><linearGradient id="i6Aadnb" x1="14.563" x2="23.563" y1="12" y2="6.625" gradientUnits="userSpaceOnUse"><stop class="wri_1275p"/><stop offset="1" class="or_2lvb5h"/></linearGradient><linearGradient id="imIOenB" x1="13.563" x2="17.125" y1="13.75" y2="10.813" gradientUnits="userSpaceOnUse"><stop class="bwxiykb4y"/><stop offset="1" class="ac9abgqux"/></linearGradient><linearGradient id="iCNWCEj" x1="20.438" x2="2.188" y1="8.75" y2="32.5" gradientUnits="userSpaceOnUse"><stop offset=".006" class="an4u7sb1i"/><stop offset="1" class="hpq-x3bvw"/></linearGradient><linearGradient id="isC8ITd" x1="38.688" x2="6.938" y1="-5.312" y2="20.625" gradientUnits="userSpaceOnUse"><stop class="tanggcbjt"/><stop offset="1" class="rn2_sc6jr"/></linearGradient><linearGradient id="iR2A2ub" x1="4.75" x2="19.063" y1="28.438" y2="8.813" gradientUnits="userSpaceOnUse"><stop class="j-y6lwvxh"/><stop offset="1" class="g38p8iens"/></linearGradient><filter id="icElxEb" width="26.25" height="23.81" x="4.212" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.466667 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5144"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.816667 0 0 0 0 0.455972 0 0 0 0 0.501059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_5144" result="effect2_innerShadow_28327_5144"/></filter><filter id="iINraWc" width="21.579" height="22.126" x="4.072" y="3.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5144" stdDeviation=".25"/></filter><filter id="ici3KMe" width="23.339" height="26.384" x="2.188" y="3.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.443137 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5144"/></filter><filter id="ieoFHDb" width="18.375" height="23.531" x="2.062" y="6.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5144" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:feather" /></template>
<style>
.ac9abgqux {
  stop-color: var(--svg-color--9c6361, #9C6361);
  stop-opacity: 0;
}

.an4u7sb1i {
  stop-color: var(--svg-color--d38750, #D38750);
}

.bwk35rjdi {
  stop-color: var(--svg-color--ce9270, #CE9270);
}

.bwxiykb4y {
  stop-color: var(--svg-color--9c6361, #9C6361);
}

.c2onurbrk {
  stop-color: var(--svg-color--e6a180, #E6A180);
}

.ft5dv1b6b {
  fill: none;
}

.g38p8iens {
  stop-color: var(--svg-color--faad7c, #FAAD7C);
  stop-opacity: 0;
}

.gc75n1w1i {
  stop-color: var(--svg-color--d78c55, #D78C55);
}

.hpq-x3bvw {
  stop-color: var(--svg-color--eea374, #EEA374);
}

.iaq1-uzhn {
  stop-color: var(--svg-color--bb3ccf, #BB3CCF);
}

.j-y6lwvxh {
  stop-color: var(--svg-color--faad7c, #FAAD7C);
}

.ks-_trb4m {
  stop-color: var(--svg-color--efa86f, #EFA86F);
}

.lkdtyzbss {
  stop-color: var(--svg-color--c68a61, #C68A61);
  stop-opacity: 0;
}

.lnwkv8bdt {
  stop-color: var(--svg-color--934e4c, #934E4C);
}

.lullgybpd {
  stop-color: var(--svg-color--934e4c, #934E4C);
  stop-opacity: 0;
}

.m2n2fmb9w {
  stop-color: var(--svg-color--f2c48e, #F2C48E);
}

.n9kbl3wcn {
  fill: var(--svg-color--995e44, #995E44);
  d: path("M4.572 24.991a40.3 40.3 0 0 1 8.235-11.841a40.4 40.4 0 0 1 12.04-8.32a.5.5 0 0 0 .25-.69a.5.5 0 0 0-.65-.23c-4.6 2.07-8.74 4.94-12.34 8.53c-3.237 3.237-5.525 6.576-7.535 10.638l.13 1.172c-.09.38-.13.59-.13.59z");
}

.obn74ko8j {
  d: path("M29.562 2h-4.17c-5.3 0-10.42 1.88-14.46 5.3a19.02 19.02 0 0 0-6.72 14.51v3.25s.17-.3.49-.81c-.09.38-.13.59-.13.59v.22h3.92c2.08 0 4.08-.47 5.89-1.34c.21-.1.21-.4 0-.5l-2.17-1.01c-.13-.04-.09-.21.04-.21h4.53c.21 0 .41-.08.57-.21c1.33-1.14 2.45-2.54 3.27-4.15c.3-.6.87-1.67 1.18-2.25c.13-.24.12-.53-.02-.77l-1.36-2.24a.25.25 0 0 1 .21-.38h2.66c.26 0 .51-.14.64-.36c1.78-2.96 3.84-5.95 6.08-8.45c.13-.14.2-.33.2-.52a.653.653 0 0 0-.65-.67");
}

.or_2lvb5h {
  stop-color: var(--svg-color--bc755b, #BC755B);
}

.q-l5-yk7p {
  stop-color: var(--svg-color--f2c48e, #F2C48E);
  stop-opacity: 0;
}

.qr8yb7b5e {
  stop-color: var(--svg-color--ce8646, #CE8646);
  stop-opacity: 0;
}

.rapp70b6u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.688 29.5C4.229 24.542 8.28 14.594 19.813 7.219");
}

.rb_60ybll {
  stop-color: var(--svg-color--ce8646, #CE8646);
}

.rn2_sc6jr {
  stop-color: var(--svg-color--d77d2c, #D77D2C);
  stop-opacity: 0;
}

.s40jpibwn {
  stop-color: var(--svg-color--f3a963, #F3A963);
}

.sfai8phsn {
  d: path("M25.472 4.14a.5.5 0 0 0-.65-.23c-4.6 2.07-8.74 4.94-12.34 8.53a41.6 41.6 0 0 0-8.92 13.22a42 42 0 0 0-1.35 3.67c-.09.3.08.61.38.66c.26.05.5-.11.57-.35c.38-1.21.82-2.41 1.32-3.59c2.04-4.83 4.97-9.18 8.7-12.9c3.51-3.51 7.55-6.3 12.04-8.32a.5.5 0 0 0 .25-.69q0 .015 0 0");
}

.tanggcbjt {
  stop-color: var(--svg-color--d77d2c, #D77D2C);
}

.udwej920g {
  stop-color: var(--svg-color--c68a61, #C68A61);
}

.vlyjdfcxx {
  stop-color: var(--svg-color--bb3ccf, #BB3CCF);
  stop-opacity: 0;
}

.wri_1275p {
  stop-color: var(--svg-color--9f6562, #9F6562);
}

.y00c-obev {
  stop-color: var(--svg-color--e6a180, #E6A180);
  stop-opacity: 0;
}

.yj4zgxboi {
  stop-color: var(--svg-color--e39c62, #E39C62);
  stop-opacity: 0;
}

.zwog-3b1n {
  stop-color: var(--svg-color--f3a963, #F3A963);
  stop-opacity: 0;
}

.zz_gq-u7m {
  d: path("M26.982 7h-7.79V2.88c-1.77.51-3.48 1.24-5.08 2.18V12h9.19c.26 0 .51-.14.64-.36c.94-1.57 1.96-3.14 3.04-4.64");
}

</style>
