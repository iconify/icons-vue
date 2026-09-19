<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHyIc9d)"><path fill="url(#iQAvRVb)" class="u-z0d0bqe"/></g><path fill="url(#idCggXd)" class="u-z0d0bqe"/><path fill="url(#iwmSUkb)" class="u-z0d0bqe"/><path fill="url(#iJtGHkQ)" class="u-z0d0bqe"/><path fill="url(#imjjWne)" class="u-z0d0bqe"/><path fill="url(#iKTxXKd)" class="u-z0d0bqe"/><path fill="url(#ipuc5zd)" class="auk85ibsp"/><path fill="url(#iQVADml)" class="nrwkusu1n"/><path fill="url(#iabhvIc)" class="nrwkusu1n"/><path fill="url(#iSvJK3B)" class="nrwkusu1n"/><g filter="url(#irsbTXb)"><path fill="url(#iYRn0sd)" class="ynk738bti"/><path fill="url(#iYcHlLd)" class="ynk738bti"/><path fill="url(#i2LEfBb)" class="ynk738bti"/></g><g filter="url(#ivf0DEb)"><path stroke="url(#iWkvagb)" class="bpfrm0fzo"/></g><rect fill="url(#i9GTJ7z)" class="rgyctbbre"/><rect fill="url(#ivzqesb)" class="rgyctbbre"/><rect fill="url(#iG7l29c)" class="rgyctbbre"/><rect fill="url(#itQ78Jd)" class="rgyctbbre"/><path fill="url(#iuVD07V)" class="eai08uiel"/><g filter="url(#iiVnAtF)"><path fill="url(#iXtHhCc)" class="tz5vaj4uw"/></g><g filter="url(#iWkpJ0W)"><circle fill="url(#iIdZ7OC)" class="ksu-9abuv"/></g><g filter="url(#iFN42Vc)"><path fill="url(#ir7YdMd)" class="y8j3k2bxh"/></g><defs><radialGradient id="iQAvRVb" cx="0" cy="0" r="1" gradientTransform="rotate(155.964 11.36 12.97)scale(19.1812 18.4333)" gradientUnits="userSpaceOnUse"><stop class="llarqs5rn"/><stop offset="1" class="ahrvpibfa"/></radialGradient><radialGradient id="iwmSUkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72446 1.45063 0 13.468 17.454)" gradientUnits="userSpaceOnUse"><stop class="scie5ybui"/><stop offset="1" class="fmrge9bag"/></radialGradient><radialGradient id="iJtGHkQ" cx="0" cy="0" r="1" gradientTransform="rotate(173.66 4.26 5.995)scale(1.74697 3.13176)" gradientUnits="userSpaceOnUse"><stop class="h8_7x5bsn"/><stop offset="1" class="ls3l1ttrr"/></radialGradient><radialGradient id="imjjWne" cx="0" cy="0" r="1" gradientTransform="rotate(165.675 7.388 12.705)scale(16.0964 23.7714)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="pt33iccpy"/><stop offset="1" class="r7gx004oy"/></radialGradient><radialGradient id="iKTxXKd" cx="0" cy="0" r="1" gradientTransform="rotate(109.983 2.727 10.039)scale(10.2416 3.16316)" gradientUnits="userSpaceOnUse"><stop class="d6byybc_p"/><stop offset="1" class="jadbq2bza"/></radialGradient><radialGradient id="ipuc5zd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.536 19.193 9.682)scale(24.7131 26.7219)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="m2hk0hbes"/><stop offset="1" class="rypey4bpf"/></radialGradient><radialGradient id="iabhvIc" cx="0" cy="0" r="1" gradientTransform="rotate(-30.196 23.058 -13.846)scale(7.083 8.73249)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="flzwrkbii"/><stop offset="1" class="tpoihzh7j"/></radialGradient><radialGradient id="iSvJK3B" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 8.022 1.066)scale(5.48766 7.79014)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="ngiy6kd7m"/><stop offset="1" class="mby5a_-gf"/></radialGradient><radialGradient id="iYcHlLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.81251 1.21874 -2.41974 3.59865 10.417 20.734)" gradientUnits="userSpaceOnUse"><stop class="xmhbxgbvu"/><stop offset="1" class="v0uvj0bvu"/></radialGradient><radialGradient id="i2LEfBb" cx="0" cy="0" r="1" gradientTransform="rotate(143.906 4.729 13.688)scale(1.94536 8.27452)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="q4wr0w-zn"/><stop offset="1" class="hf92me_2p"/></radialGradient><radialGradient id="ivzqesb" cx="0" cy="0" r="1" gradientTransform="rotate(137.353 5.061 7.467)scale(1.61445 1.40902)" gradientUnits="userSpaceOnUse"><stop class="iqk_b94ku"/><stop offset="1" class="j_li4o9eq"/></radialGradient><radialGradient id="itQ78Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.91406 0 0 -7.03626 15.195 9.777)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="fleqnx02z"/><stop offset="1" class="dr0sus78y"/></radialGradient><radialGradient id="iuVD07V" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21213 1.47114 0 11.492 7.925)" gradientUnits="userSpaceOnUse"><stop class="gg0pr-b6g"/><stop offset="1" class="kvjsqp_ep"/></radialGradient><radialGradient id="iIdZ7OC" cx="0" cy="0" r="1" gradientTransform="rotate(144.36 11.102 13.31)scale(5.72588 9.69685)" gradientUnits="userSpaceOnUse"><stop class="xl_wv6bjo"/><stop offset="1" class="i2qp_y7bb"/></radialGradient><radialGradient id="ir7YdMd" cx="0" cy="0" r="1" gradientTransform="rotate(-102 14.357 6.333)scale(15.05 5.24944)" gradientUnits="userSpaceOnUse"><stop class="ez7-ggbre"/><stop offset="1" class="gmvfctb6t"/></radialGradient><linearGradient id="idCggXd" x1="16" x2="16" y1="31.75" y2="21.125" gradientUnits="userSpaceOnUse"><stop class="f_4a56bsv"/><stop offset="1" class="pwefzhl3a"/></linearGradient><linearGradient id="iQVADml" x1="8.406" x2="17.335" y1="9.625" y2="7.189" gradientUnits="userSpaceOnUse"><stop class="w3o8lpr1d"/><stop offset="1" class="soupurbex"/></linearGradient><linearGradient id="iYRn0sd" x1="13.135" x2="13.12" y1="17.051" y2="27.344" gradientUnits="userSpaceOnUse"><stop class="t8z9264fh"/><stop offset="1" class="km5ujwbpk"/></linearGradient><linearGradient id="iWkvagb" x1="14.812" x2="11.004" y1="7.56" y2="5.884" gradientUnits="userSpaceOnUse"><stop class="zfgsai7gf"/><stop offset="1" class="rb9ypvr6g"/></linearGradient><linearGradient id="i9GTJ7z" x1="8.687" x2="14.437" y1="10.25" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="w3o8lpr1d"/><stop offset="1" class="zqeghxbdd"/></linearGradient><linearGradient id="iG7l29c" x1="10.738" x2="10.738" y1="12.011" y2="9.777" gradientUnits="userSpaceOnUse"><stop class="wsbfv1byf"/><stop offset="1" class="ospegq1qy"/></linearGradient><linearGradient id="iXtHhCc" x1="10.39" x2="9.856" y1="6.75" y2="7.981" gradientUnits="userSpaceOnUse"><stop class="w962mbc7c"/><stop offset="1" class="o15o7pb6h"/></linearGradient><filter id="iHyIc9d" width="28.811" height="22.656" x="2.094" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.619608 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4346"/></filter><filter id="irsbTXb" width="15.781" height="10.719" x="5.245" y="18.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4346" stdDeviation=".5"/></filter><filter id="ivf0DEb" width="6.851" height="7.657" x="9.699" y="3.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4346" stdDeviation=".5"/></filter><filter id="iiVnAtF" width="2.913" height="3.108" x="8.383" y="5.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4346" stdDeviation=".25"/></filter><filter id="iWkpJ0W" width="12.915" height="12.915" x="17.567" y="13.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4346" stdDeviation="1"/></filter><filter id="iFN42Vc" width="8.938" height="19.03" x="4.812" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4346" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flexed-biceps-light" /></template>
<style>
.ahrvpibfa {
  stop-color: var(--svg-color--ecb5a9, #ECB5A9);
}

.auk85ibsp {
  d: path("m19.901 29.844l-6.403-11.089a.24.24 0 0 0 .116-.133a8.39 8.39 0 0 1 16.292 2.83a8.39 8.39 0 0 1-8.282 8.392z");
}

.bpfrm0fzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.449 5.111l2.383.985c.402.148.91.68.964 1.46c.058.823-.524 1.485-.89 1.712");
}

.d6byybc_p {
  stop-color: var(--svg-color--ffdbbd, #FFDBBD);
}

.dr0sus78y {
  stop-color: var(--svg-color--e9b098, #E9B098);
}

.eai08uiel {
  d: path("M10.653 5.853L10 7.773h3.75z");
}

.ez7-ggbre {
  stop-color: var(--svg-color--ffe2c3, #FFE2C3);
}

.f_4a56bsv {
  stop-color: var(--svg-color--b47997, #B47997);
}

.fleqnx02z {
  stop-color: var(--svg-color--e9b098, #E9B098);
  stop-opacity: 0;
}

.flzwrkbii {
  stop-color: var(--svg-color--ffe2c4, #FFE2C4);
  stop-opacity: 0;
}

.fmrge9bag {
  stop-color: var(--svg-color--d5997c, #D5997C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gg0pr-b6g {
  stop-color: var(--svg-color--a76040, #A76040);
}

.gmvfctb6t {
  stop-color: var(--svg-color--ffe2c3, #FFE2C3);
  stop-opacity: 0;
}

.h8_7x5bsn {
  stop-color: var(--svg-color--d49176, #D49176);
}

.hf92me_2p {
  stop-color: var(--svg-color--d99877, #D99877);
  stop-opacity: 0;
}

.i2qp_y7bb {
  stop-color: var(--svg-color--ffe9ca, #FFE9CA);
  stop-opacity: 0;
}

.iqk_b94ku {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
}

.j_li4o9eq {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
  stop-opacity: 0;
}

.jadbq2bza {
  stop-color: var(--svg-color--ffdbbd, #FFDBBD);
  stop-opacity: 0;
}

.km5ujwbpk {
  stop-color: var(--svg-color--f7bfa1, #F7BFA1);
  stop-opacity: 0;
}

.ksu-9abuv {
  cx: 24.025px;
  cy: 19.972px;
  r: 4.458px;
}

.kvjsqp_ep {
  stop-color: var(--svg-color--d8916c, #D8916C);
  stop-opacity: 0;
}

.llarqs5rn {
  stop-color: var(--svg-color--ffdbbb, #FFDBBB);
}

.ls3l1ttrr {
  stop-color: var(--svg-color--d49176, #D49176);
  stop-opacity: 0;
}

.m2hk0hbes {
  stop-color: var(--svg-color--dc9e81, #DC9E81);
  stop-opacity: 0;
}

.mby5a_-gf {
  stop-color: var(--svg-color--c79b7a, #C79B7A);
}

.ngiy6kd7m {
  stop-color: var(--svg-color--c79b7a, #C79B7A);
  stop-opacity: 0;
}

.nrwkusu1n {
  d: path("M7.32 5.883L6.296 8.777l.499.963a2.04 2.04 0 0 0 1.817 1.12h4.941a2.5 2.5 0 0 0 2.315-1.557l.087-.214a3.5 3.5 0 0 0-1.814-4.517l-1.774-.752c-2.172-.804-4.283.048-5.047 2.063");
}

.o15o7pb6h {
  stop-color: var(--svg-color--ffcdb6, #FFCDB6);
  stop-opacity: 0;
}

.ospegq1qy {
  stop-color: var(--svg-color--db9788, #DB9788);
  stop-opacity: 0;
}

.pt33iccpy {
  stop-color: var(--svg-color--ecb19b, #ECB19B);
  stop-opacity: 0;
}

.pwefzhl3a {
  stop-color: var(--svg-color--b47997, #B47997);
  stop-opacity: 0;
}

.q4wr0w-zn {
  stop-color: var(--svg-color--d99877, #D99877);
}

.r7gx004oy {
  stop-color: var(--svg-color--ecb19b, #ECB19B);
}

.rb9ypvr6g {
  stop-color: var(--svg-color--ffe6ca, #FFE6CA);
  stop-opacity: 0;
}

.rgyctbbre {
  width: 8.914px;
  height: 4.07px;
  x: 6.281px;
  y: 7.742px;
  rx: 2.035px;
}

.rypey4bpf {
  stop-color: var(--svg-color--dc9e81, #DC9E81);
}

.scie5ybui {
  stop-color: var(--svg-color--d5997c, #D5997C);
}

.soupurbex {
  stop-color: var(--svg-color--fdc6ad, #FDC6AD);
}

.t8z9264fh {
  stop-color: var(--svg-color--f7bfa1, #F7BFA1);
}

.tpoihzh7j {
  stop-color: var(--svg-color--ffe2c4, #FFE2C4);
}

.tz5vaj4uw {
  d: path("m9.406 5.672l1.39 1.047v1.06H8.883z");
}

.u-z0d0bqe {
  d: path("M7.968 8.688h-1.64l-3.75 11.187c-1.735 5.906 1.399 9.969 6.219 9.969h12.827a8.391 8.391 0 1 0-8.01-11.222a.24.24 0 0 1-.223.16a.23.23 0 0 1-.207-.126z");
}

.v0uvj0bvu {
  stop-color: var(--svg-color--ffd9c0, #FFD9C0);
  stop-opacity: 0;
}

.w3o8lpr1d {
  stop-color: var(--svg-color--e2ab9f, #E2AB9F);
}

.w962mbc7c {
  stop-color: var(--svg-color--ffcdb6, #FFCDB6);
}

.wsbfv1byf {
  stop-color: var(--svg-color--db9788, #DB9788);
}

.xl_wv6bjo {
  stop-color: var(--svg-color--ffe9ca, #FFE9CA);
}

.xmhbxgbvu {
  stop-color: var(--svg-color--ffd9c0, #FFD9C0);
}

.y8j3k2bxh {
  d: path("M8.516 11.737c-.498 3.77-2.204 15.86-2.204 16.03l5.938-8.491z");
}

.ynk738bti {
  d: path("m12.87 19.266l-6.625 8.718h13.781l-6.13-8.718z");
}

.zfgsai7gf {
  stop-color: var(--svg-color--ffe6ca, #FFE6CA);
}

.zqeghxbdd {
  stop-color: var(--svg-color--f9c6a8, #F9C6A8);
}

</style>
