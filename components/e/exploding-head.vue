<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ircoadb)" class="xt1oura8r"/><path fill="url(#iALn8Qr)" class="xt1oura8r"/><path fill="url(#i8Tdzad)" class="xt1oura8r"/><path fill="url(#iPxXmne)" class="bq88w7her"/><path fill="url(#iARUN6d)" class="ky5nyacxc"/><g filter="url(#i6ii8oc)"><path class="kzpv5y6xh"/></g><path fill="url(#ifG4hzd)" class="pr89gieja"/><path fill="url(#ila7Utb)" class="pr89gieja"/><path fill="url(#ijvU89b)" class="pr89gieja"/><path fill="url(#i97Y7Pb)" class="pr89gieja"/><path fill="url(#iyx0SWc)" class="pr89gieja"/><path fill="url(#iYFRLBd)" class="pr89gieja"/><g filter="url(#inNPUJb)"><path fill="url(#ia0NQla)" class="hqo-0fbgn"/><path fill="url(#i48bzuZ)" class="hqo-0fbgn"/><path fill="url(#iInkchd)" class="hqo-0fbgn"/></g><g filter="url(#id2NePd)"><path fill="url(#ip17QCd)" class="htc-mobfi"/><path fill="url(#i4OpEle)" class="htc-mobfi"/><path fill="url(#if6vcce)" class="htc-mobfi"/></g><g filter="url(#irxRRYc)"><path fill="url(#iIXIiPp)" class="f-26orgcy"/></g><path fill="url(#ikBcLpc)" class="dm1qjtbaq"/><path fill="url(#itr5Eec)" class="v6ym8ivax"/><path fill="url(#itrpHVb)" class="fpb3tponm"/><path fill="url(#i2pisXc)" class="w0zwr5s2z"/><path fill="url(#iF7TqUb)" class="yi8u8ob_d"/><path fill="url(#ibtGvXc)" class="yi8u8ob_d"/><path fill="url(#iIVNHvd)" class="yi8u8ob_d"/><g filter="url(#iYzR29d)"><path fill="url(#iGU29Ke)" class="ir5d69now"/><path fill="url(#iq3cDzd)" class="ir5d69now"/><path fill="url(#i0P8pXE)" class="ir5d69now"/></g><g filter="url(#iEgeohd)"><path fill="url(#i4ZfAed)" class="sej3nwb3n"/></g><g filter="url(#iaWKCld)"><path class="aic1q2bnt"/></g><g filter="url(#i6iQC7b)"><path class="s5pzjabdf"/></g><path class="ztawbeb4f"/><path class="yjc4wn8fd"/><path class="ybf91rbrl"/><path class="k--zh1bzf"/><defs><radialGradient id="ircoadb" cx="0" cy="0" r="1" gradientTransform="matrix(0 28.375 -74.5612 0 16.403 13.62)" gradientUnits="userSpaceOnUse"><stop class="h66atab_c"/><stop offset=".172" class="gphneqr8o"/><stop offset=".49" class="h66atab_c"/><stop offset="1" class="w9napxb6c"/></radialGradient><radialGradient id="iALn8Qr" cx="0" cy="0" r="1" gradientTransform="matrix(-.55678 17.68754 -70.16125 -2.20858 15.943 13.613)" gradientUnits="userSpaceOnUse"><stop class="h6-r1q1vl"/><stop offset="1" class="mx2iljl3h"/></radialGradient><radialGradient id="i8Tdzad" cx="0" cy="0" r="1" gradientTransform="scale(19.7411 13.875)rotate(90 -.18 .987)" gradientUnits="userSpaceOnUse"><stop offset=".824" class="wwuz49buj"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="iPxXmne" cx="0" cy="0" r="1" gradientTransform="matrix(.00111 4.5492 -13.8543 .00339 15.885 11.5)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="h66atab_c"/><stop offset=".9" class="mu6ahg2uu"/></radialGradient><radialGradient id="ifG4hzd" cx="0" cy="0" r="1" gradientTransform="rotate(135.922 9.972 4.837)scale(19.227 17.9698)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".983" class="v5veftf9h"/></radialGradient><radialGradient id="ila7Utb" cx="0" cy="0" r="1" gradientTransform="matrix(11.19991 -5.9167 4.94721 9.36475 10.367 8.822)" gradientUnits="userSpaceOnUse"><stop class="fslrr3bpx"/><stop offset="1" class="y4o16ykyv"/></radialGradient><radialGradient id="ijvU89b" cx="0" cy="0" r="1" gradientTransform="matrix(4.59375 -8.34375 7.49567 4.12683 6.875 9.719)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="kgf1emk2c"/><stop offset="1" class="oezix-b3s"/></radialGradient><radialGradient id="i97Y7Pb" cx="0" cy="0" r="1" gradientTransform="rotate(-53.56 15.058 -3.82)scale(10.8378 8.89035)" gradientUnits="userSpaceOnUse"><stop class="ax72abnws"/><stop offset="1" class="y4o16ykyv"/></radialGradient><radialGradient id="iyx0SWc" cx="0" cy="0" r="1" gradientTransform="rotate(-116.432 16.215 -1.506)scale(6.0374 8.13909)" gradientUnits="userSpaceOnUse"><stop class="ax72abnws"/><stop offset="1" class="y4o16ykyv"/></radialGradient><radialGradient id="iYFRLBd" cx="0" cy="0" r="1" gradientTransform="matrix(17.05825 10.89914 -22.70018 35.52806 -2.619 -3.322)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="kgf1emk2c"/><stop offset="1" class="oezix-b3s"/></radialGradient><radialGradient id="ia0NQla" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0108 4.87547 -4.56693 -2.82026 17.86 2.913)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".983" class="v5veftf9h"/></radialGradient><radialGradient id="i48bzuZ" cx="0" cy="0" r="1" gradientTransform="rotate(-54.31 15.215 -9.59)scale(6.7091 6.43579)" gradientUnits="userSpaceOnUse"><stop class="fslrr3bpx"/><stop offset="1" class="y4o16ykyv"/></radialGradient><radialGradient id="iInkchd" cx="0" cy="0" r="1" gradientTransform="rotate(74.982 7.398 6.04)scale(7.61966 22.7483)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="kgf1emk2c"/><stop offset="1" class="oezix-b3s"/></radialGradient><radialGradient id="ip17QCd" cx="0" cy="0" r="1" gradientTransform="rotate(126.323 4.349 4.552)scale(4.7734 4.77317)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".983" class="v5veftf9h"/></radialGradient><radialGradient id="i4OpEle" cx="0" cy="0" r="1" gradientTransform="rotate(-49.465 12.273 -3.67)scale(5.65565 5.65551)" gradientUnits="userSpaceOnUse"><stop class="fslrr3bpx"/><stop offset="1" class="y4o16ykyv"/></radialGradient><radialGradient id="if6vcce" cx="0" cy="0" r="1" gradientTransform="rotate(54.739 2.166 2.338)scale(9.69723 20.9837)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="kgf1emk2c"/><stop offset="1" class="oezix-b3s"/></radialGradient><radialGradient id="iIXIiPp" cx="0" cy="0" r="1" gradientTransform="matrix(4.37499 -4.09376 13.00577 13.89924 21.375 8.968)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="kgf1emk2c"/><stop offset="1" class="oezix-b3s"/></radialGradient><radialGradient id="ikBcLpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89798 .92132 -1.325 -1.29143 4.372 8.614)" gradientUnits="userSpaceOnUse"><stop class="d9it1jk5w"/><stop offset=".536" class="m2g4nbcbq"/><stop offset="1" class="psox6vbyf"/></radialGradient><radialGradient id="itr5Eec" cx="0" cy="0" r="1" gradientTransform="rotate(134.265 11.64 10.578)scale(1.24907 1.79636)" gradientUnits="userSpaceOnUse"><stop class="d9it1jk5w"/><stop offset=".536" class="m2g4nbcbq"/><stop offset="1" class="psox6vbyf"/></radialGradient><radialGradient id="itrpHVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20311 1.23438 -1.77525 -1.73027 24.469 5.453)" gradientUnits="userSpaceOnUse"><stop class="d9it1jk5w"/><stop offset=".536" class="m2g4nbcbq"/><stop offset="1" class="psox6vbyf"/></radialGradient><radialGradient id="i2pisXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20311 1.23438 -1.77525 -1.73027 5.969 3.953)" gradientUnits="userSpaceOnUse"><stop class="d9it1jk5w"/><stop offset=".536" class="m2g4nbcbq"/><stop offset="1" class="psox6vbyf"/></radialGradient><radialGradient id="ibtGvXc" cx="0" cy="0" r="1" gradientTransform="matrix(3.6375 -5.03125 10.41461 7.52956 12.312 12.313)" gradientUnits="userSpaceOnUse"><stop class="fslrr3bpx"/><stop offset="1" class="y4o16ykyv"/></radialGradient><radialGradient id="iIVNHvd" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 3.5625 -7.40881 6.49896 8.437 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".042" class="gfj-2hbfq"/><stop offset=".885" class="oezix-b3s"/></radialGradient><radialGradient id="iGU29Ke" cx="0" cy="0" r="1" gradientTransform="rotate(122.51 8.741 9.07)scale(5.07132 4.81595)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".983" class="v5veftf9h"/></radialGradient><radialGradient id="iq3cDzd" cx="0" cy="0" r="1" gradientTransform="rotate(-53.451 20.127 -11.908)scale(5.94984 5.76258)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="fslrr3bpx"/><stop offset=".693" class="y4o16ykyv"/></radialGradient><radialGradient id="i0P8pXE" cx="0" cy="0" r="1" gradientTransform="matrix(4.46317 6.89674 -14.1055 9.12826 13.6 1.54)" gradientUnits="userSpaceOnUse"><stop class="hp_fn-4iz"/><stop offset="1" class="oezix-b3s"/></radialGradient><filter id="i6ii8oc" width="6.063" height="4.75" x="23.621" y="12.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".5"/></filter><filter id="inNPUJb" width="9.288" height="10.754" x="11.441" y=".358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".4"/></filter><filter id="id2NePd" width="8.402" height="9.221" x="4.315" y="1.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".5"/></filter><filter id="irxRRYc" width="8.596" height="9.44" x="18.93" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".5"/></filter><filter id="iYzR29d" width="8.96" height="10.03" x="15" y="4.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".5"/></filter><filter id="iEgeohd" width="3.692" height="5.047" x="12.839" y="10.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".25"/></filter><filter id="iaWKCld" width="10.52" height="10.52" x="4.97" y="15.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".5"/></filter><filter id="i6iQC7b" width="10.52" height="10.52" x="15.533" y="15.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6808_5249" stdDeviation=".5"/></filter><linearGradient id="iARUN6d" x1="15.86" x2="15.86" y1="29.026" y2="24.087" gradientUnits="userSpaceOnUse"><stop class="xtpc5ebsm"/><stop offset="1" class="b7g_n2krb"/></linearGradient><linearGradient id="iF7TqUb" x1="15.375" x2="10.25" y1="13.316" y2="17.513" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".983" class="v5veftf9h"/></linearGradient><linearGradient id="i4ZfAed" x1="14.685" x2="16.416" y1="9.531" y2="13.91" gradientUnits="userSpaceOnUse"><stop offset=".141" class="kgf1emk2c"/><stop offset="1" class="oezix-b3s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:exploding-head" /></template>
<style>
.aic1q2bnt {
  fill: var(--svg-color--d66a46, #D66A46);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M10.23 25.5a4.26 4.26 0 1 0 0-8.52a4.26 4.26 0 0 0 0 8.52");
}

.ax72abnws {
  stop-color: var(--svg-color--b076cb, #B076CB);
}

.b7g_n2krb {
  stop-color: var(--svg-color--b7039b, #B7039B);
}

.bq88w7her {
  d: path("M25.867 13.083c0 1.11-3.89 2-9.96 2s-10-.9-10-2s3.92-2 10-2s9.96.9 9.96 2");
}

.d9it1jk5w {
  stop-color: var(--svg-color--ffe363, #FFE363);
}

.dm1qjtbaq {
  d: path("M4 10.03a1.03 1.03 0 1 0 0-2.06a1.03 1.03 0 0 0 0 2.06");
}

.f-26orgcy {
  d: path("M19.93 3.961c0-.577.602-.992 1.11-1.266a3.72 3.72 0 1 1-.91 5.858q-.096.14-.2.274z");
}

.fpb3tponm {
  d: path("M23.97 7.35a1.38 1.38 0 1 0 0-2.76a1.38 1.38 0 0 0 0 2.76");
}

.fslrr3bpx {
  stop-color: var(--svg-color--dcc4e7, #DCC4E7);
}

.ft5dv1b6b {
  fill: none;
}

.gfj-2hbfq {
  stop-color: var(--svg-color--a6a2a2, #A6A2A2);
}

.gphneqr8o {
  stop-color: var(--svg-color--f8d51d, #F8D51D);
}

.h6-r1q1vl {
  stop-color: var(--svg-color--eb9037, #EB9037);
  stop-opacity: 0;
}

.h66atab_c {
  stop-color: var(--svg-color--f89c20, #F89C20);
}

.hp_fn-4iz {
  stop-color: var(--svg-color--ddd, #DDD);
}

.hqo-0fbgn {
  d: path("M12.241 8.818V3.361c0-.4.302-.725.6-.992a4.74 4.74 0 0 1 3.17-1.21a4.74 4.74 0 0 1 3.172 1.21c.356.318.747.693.747 1.171v5.076a4.8 4.8 0 0 1-2.096 1.697H14.19a4.8 4.8 0 0 1-1.949-1.495");
}

.htc-mobfi {
  d: path("M11.717 4.02c0-.56-.585-.962-1.077-1.229a3.61 3.61 0 1 0 .884 5.686q.092.137.193.266z");
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.ir5d69now {
  d: path("M18.739 13.063H18a2 2 0 0 1-2-2V6.029c.208-.01.414-.078.584-.205a3.99 3.99 0 1 1 2.386 7.188a.6.6 0 0 0-.232.05");
}

.k--zh1bzf {
  fill: var(--svg-color--412933, #412933);
  d: path("M19.95 22.46a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.kgf1emk2c {
  stop-color: var(--svg-color--c6c6c6, #C6C6C6);
}

.ky5nyacxc {
  d: path("M15.857 29.023c-1.36 0-2.47-1.11-2.47-2.47s1.11-2.47 2.47-2.47s2.47 1.11 2.47 2.47s-1.11 2.47-2.47 2.47");
}

.kzpv5y6xh {
  stroke: var(--svg-color--fff500, #FFF500);
  stroke-linecap: round;
  stroke-opacity: 0.5;
  d: path("M28.184 14.222c-.657.703-2.079 1.453-3.063 1.75");
}

.m2g4nbcbq {
  stop-color: var(--svg-color--f4c222, #F4C222);
}

.mu6ahg2uu {
  stop-color: var(--svg-color--bd824f, #BD824F);
}

.mx2iljl3h {
  stop-color: var(--svg-color--eb9037, #EB9037);
}

.oezix-b3s {
  stop-color: var(--svg-color--c1b4b8, #C1B4B8);
  stop-opacity: 0;
}

.pr89gieja {
  d: path("M20.092 8.748a4.97 4.97 0 0 1-4.122 2.192a4.97 4.97 0 0 1-4.122-2.192a4 4 0 1 1-.98-6.3c.56.303 1.316.24 1.79-.184A4.95 4.95 0 0 1 15.97 1c1.272 0 2.433.478 3.312 1.264c.474.424 1.23.487 1.79.185a4 4 0 1 1-.98 6.3");
}

.psox6vbyf {
  stop-color: var(--svg-color--ed8546, #ED8546);
}

.s5pzjabdf {
  fill: var(--svg-color--ff7c32, #FF7C32);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M20.793 25.5a4.26 4.26 0 1 0 0-8.52a4.26 4.26 0 0 0 0 8.52");
}

.sej3nwb3n {
  d: path("M13.34 13.148a.6.6 0 0 1 .194.259c.235.624.33.883.434 1.639q.928.032 1.939.032h.124v-4.047z");
}

.v5veftf9h {
  stop-color: var(--svg-color--d1d3d4, #D1D3D4);
}

.v6ym8ivax {
  d: path("M26.98 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w0zwr5s2z {
  d: path("M5.47 5.85a1.38 1.38 0 1 0 0-2.76a1.38 1.38 0 0 0 0 2.76");
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.wwuz49buj {
  stop-color: var(--svg-color--ffb56d, #FFB56D);
  stop-opacity: 0;
}

.xt1oura8r {
  d: path("M14.68 10.94h2.527c10.183-.012 12.823-.014 12.674 5.2c-.22 7.705-4.469 13.723-13.89 13.91h-.094c-9.422-.187-13.67-6.205-13.891-13.91c-.15-5.214 2.491-5.212 12.674-5.2");
}

.xtpc5ebsm {
  stop-color: var(--svg-color--d3037b, #D3037B);
}

.y4o16ykyv {
  stop-color: var(--svg-color--dcc4e7, #DCC4E7);
  stop-opacity: 0;
}

.ybf91rbrl {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.45 24.94a4.48 4.48 0 1 0 0-8.96a4.48 4.48 0 0 0 0 8.96");
}

.yi8u8ob_d {
  d: path("M13.534 13.407a.64.64 0 0 0-.604-.395a3.99 3.99 0 1 1 2.386-7.188a1.08 1.08 0 0 0 1.268 0a3.99 3.99 0 1 1 2.386 7.188a.53.53 0 0 0-.499.326c-.247.613-.32.678-.493 1.703a57 57 0 0 1-4.01.005c-.104-.756-.199-1.015-.434-1.639");
}

.yjc4wn8fd {
  fill: var(--svg-color--402933, #402933);
  d: path("M11.95 22.46a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.ztawbeb4f {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.45 24.94a4.48 4.48 0 1 0 0-8.96a4.48 4.48 0 0 0 0 8.96");
}

</style>
