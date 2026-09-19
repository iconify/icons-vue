<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEzKpbe)"><path class="xd8k-p5dy"/><path fill="url(#i2lUQVb)" class="d99em7b3h"/><path fill="url(#ieYAkke)" class="d99em7b3h"/></g><path fill="url(#iIvO1Tb)" class="fc-58f-oy"/><path fill="url(#ihWR7bc)" class="fc-58f-oy"/><path fill="url(#iaNnAtd)" class="fc-58f-oy"/><path fill="url(#iSkVXDc)" class="r_9ps2gtd"/><path fill="url(#ifA2dGc)" class="r_9ps2gtd"/><path fill="url(#izWEySb)" class="r_9ps2gtd"/><path fill="url(#iRnoACc)" class="ewnex5bqg"/><g filter="url(#iYlElyb)"><path fill="url(#iCZ5T5d)" class="dv_fpfmad"/><path fill="url(#i7Prxxb)" class="dv_fpfmad"/><path fill="url(#i3K7wcH)" class="dv_fpfmad"/></g><path fill="url(#iIE8chc)" class="dv_fpfmad"/><path fill="url(#iHNCShd)" class="dv_fpfmad"/><path fill="url(#irLhx9c)" class="dv_fpfmad"/><path fill="url(#iAZj78c)" class="dv_fpfmad"/><path fill="url(#iyxLS5d)" class="dv_fpfmad"/><path fill="url(#iCc528b)" class="dv_fpfmad"/><path fill="url(#iQjx6Eb)" class="dv_fpfmad"/><path fill="url(#i2z2vQc)" class="dv_fpfmad"/><path fill="url(#iRqKOke)" class="r77r8e3rp"/><g filter="url(#ik60ZId)"><path fill="url(#iZ2cWzc)" class="d5jfrx0nc"/></g><defs><radialGradient id="i2lUQVb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43256 4.79528 -3.9123 -3.61637 20.433 22.502)" gradientUnits="userSpaceOnUse"><stop class="j4hp0ib_e"/><stop offset="1" class="vp6n5ib_i"/></radialGradient><radialGradient id="ieYAkke" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.29526 -11.0115 0 21.307 5.077)" gradientUnits="userSpaceOnUse"><stop class="j4hp0ib_e"/><stop offset="1" class="vp6n5ib_i"/></radialGradient><radialGradient id="iIvO1Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1 -12.625 0 20.563 3)" gradientUnits="userSpaceOnUse"><stop class="iv-mheb0f"/><stop offset="1" class="h2fvtu94d"/></radialGradient><radialGradient id="iSkVXDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -14.2031 0 20.563 28.64)" gradientUnits="userSpaceOnUse"><stop class="iv-mheb0f"/><stop offset="1" class="h2fvtu94d"/></radialGradient><radialGradient id="iCZ5T5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5013 -11.3361 0 19.77 23.855)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="kz1a7xh5x"/><stop offset="1" class="sssti0bco"/></radialGradient><radialGradient id="i7Prxxb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25464 6.73023 -5.52054 -4.31017 21.255 5.511)" gradientUnits="userSpaceOnUse"><stop class="hzdemlbyy"/><stop offset="1" class="jasmz67th"/></radialGradient><radialGradient id="i3K7wcH" cx="0" cy="0" r="1" gradientTransform="rotate(164.385 10.984 11.97)scale(18.1172 31.567)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="dlhlbo54q"/><stop offset="1" class="ictcb-bpp"/></radialGradient><radialGradient id="iIE8chc" cx="0" cy="0" r="1" gradientTransform="matrix(5.44043 -2.48428 2.66833 5.84349 10.56 9.318)" gradientUnits="userSpaceOnUse"><stop class="rogsku4tt"/><stop offset="1" class="rl7t4yb9v"/></radialGradient><radialGradient id="iHNCShd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.3534 0 0 -1.15561 20.777 7.156)" gradientUnits="userSpaceOnUse"><stop class="yupcp6b2q"/><stop offset=".406" class="o8vmkmbum"/><stop offset="1" class="hpghed2xg"/></radialGradient><radialGradient id="irLhx9c" cx="0" cy="0" r="1" gradientTransform="rotate(132.917 10.79 7.887)scale(11.6205 12.2866)" gradientUnits="userSpaceOnUse"><stop class="b9tng-bbp"/><stop offset="1" class="j2pceccgh"/></radialGradient><radialGradient id="iyxLS5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .64608 -7.46586 0 19.164 26.859)" gradientUnits="userSpaceOnUse"><stop class="mi3xdbtde"/><stop offset="1" class="zx1rf-sdj"/></radialGradient><radialGradient id="i2z2vQc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.746 11.387 9.444)scale(1.83117 .68055)" gradientUnits="userSpaceOnUse"><stop class="vadnxigha"/><stop offset="1" class="u_0zt-b6m"/></radialGradient><linearGradient id="ihWR7bc" x1="3.938" x2="16" y1="3.265" y2="3.265" gradientUnits="userSpaceOnUse"><stop class="z99pf7bvs"/><stop offset="1" class="r0pvbhb7v"/></linearGradient><linearGradient id="iaNnAtd" x1="16" x2="16" y1="4.828" y2="3.515" gradientUnits="userSpaceOnUse"><stop class="z99pf7bvs"/><stop offset="1" class="r0pvbhb7v"/></linearGradient><linearGradient id="ifA2dGc" x1="3.938" x2="16" y1="29.265" y2="29.265" gradientUnits="userSpaceOnUse"><stop class="z99pf7bvs"/><stop offset="1" class="r0pvbhb7v"/></linearGradient><linearGradient id="izWEySb" x1="16" x2="16" y1="30.297" y2="29.328" gradientUnits="userSpaceOnUse"><stop class="ri9usvcsw"/><stop offset="1" class="st40q3b-j"/></linearGradient><linearGradient id="iRnoACc" x1="19.938" x2="20.75" y1="20.203" y2="26.8" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".822" class="stui2mbih"/></linearGradient><linearGradient id="iAZj78c" x1="16" x2="16" y1="5.843" y2="6.507" gradientUnits="userSpaceOnUse"><stop class="abskkbc9q"/><stop offset="1" class="myjz73u1g"/></linearGradient><linearGradient id="iCc528b" x1="16" x2="16" y1="28.223" y2="26.751" gradientUnits="userSpaceOnUse"><stop class="mbupjzbim"/><stop offset="1" class="l49immmex"/></linearGradient><linearGradient id="iQjx6Eb" x1="16" x2="16" y1="28.031" y2="27.859" gradientUnits="userSpaceOnUse"><stop class="r-ok_qbgz"/><stop offset="1" class="t3d7zzb2n"/></linearGradient><linearGradient id="iRqKOke" x1="22.938" x2="19" y1="5.328" y2="12.578" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".822" class="stui2mbih"/></linearGradient><linearGradient id="iZ2cWzc" x1="16.449" x2="16.449" y1="15.812" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="tk00mxb5t"/><stop offset="1" class="s068febgy"/></linearGradient><filter id="iEzKpbe" width="18" height="24.1" x="7" y="3.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.756863 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13253"/></filter><filter id="iYlElyb" width="16.126" height="22" x="8.087" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.541176 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13253"/></filter><filter id="ik60ZId" width="3.248" height="11.469" x="14.825" y="12.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13253" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hourglass-not-done" /></template>
<style>
.abskkbc9q {
  stop-color: var(--svg-color--9e8563, #9E8563);
}

.b9tng-bbp {
  stop-color: var(--svg-color--ffd968, #FFD968);
}

.d5jfrx0nc {
  d: path("M16.098 21.72c0 1.084-.264 1.576-.397 1.686h1.46c-.404-.41-.456-1.295-.432-1.687v-6.957c0-.77.396-1.315.594-1.325h-1.748c.447.338.535 1.135.523 1.325z");
}

.d99em7b3h {
  d: path("M25 6.4V3.9H7v2.5c0 4 2.8 7.3 6.5 8.2c.3.1.5.4.5.7v1.2c0 .3-.2.6-.5.6C9.8 18 7 21.3 7 25.3V28h18v-2.7c0-4-2.8-7.3-6.5-8.2c-.3-.1-.5-.3-.5-.6v-1.2c0-.3.2-.6.5-.6c3.7-1 6.5-4.3 6.5-8.3");
}

.dlhlbo54q {
  stop-color: var(--svg-color--b7845c, #B7845C);
  stop-opacity: 0;
}

.dv_fpfmad {
  d: path("M17 22.2v-7.4c0-.5.3-.9.8-1c3.2-.7 5.6-3.3 6.1-6.6c.1-.6-.4-1.2-1-1.2H9.1c-.6 0-1.1.6-1 1.2c.5 3.3 2.9 5.9 6.1 6.6c.5.1.8.5.8 1v7.4c0 .5-.3.9-.8 1c-1.9.4-3.5 1.5-4.6 3c-.6.8 0 1.8.9 1.8h11c.9 0 1.5-1 .9-1.7c-1.1-1.5-2.8-2.6-4.6-3c-.5-.2-.8-.6-.8-1.1");
}

.ewnex5bqg {
  d: path("M22.4 26.8c-.5 0-.9-.4-.9-.9c-.2-1.9-1.2-4.5-3.6-5.4c-.5-.2-.7-.7-.5-1.2s.7-.7 1.2-.5c1.4.5 2.6 1.5 3.4 2.9c.8 1.2 1.2 2.6 1.3 4.2c.1.4-.3.9-.9.9");
}

.fc-58f-oy {
  d: path("M25 4H7c-.6 0-1-.4-1-1s.4-1 1-1h18c.6 0 1 .4 1 1s-.4 1-1 1");
}

.ft5dv1b6b {
  fill: none;
}

.h2fvtu94d {
  stop-color: var(--svg-color--a9a9a9, #A9A9A9);
}

.hpghed2xg {
  stop-color: var(--svg-color--ffcb56, #FFCB56);
  stop-opacity: 0;
}

.hzdemlbyy {
  stop-color: var(--svg-color--f3c169, #F3C169);
}

.ictcb-bpp {
  stop-color: var(--svg-color--b7845c, #B7845C);
}

.iv-mheb0f {
  stop-color: var(--svg-color--cdcfcf, #CDCFCF);
}

.j2pceccgh {
  stop-color: var(--svg-color--ffd968, #FFD968);
  stop-opacity: 0;
}

.j4hp0ib_e {
  stop-color: var(--svg-color--c4f4ff, #C4F4FF);
}

.jasmz67th {
  stop-color: var(--svg-color--f3c169, #F3C169);
  stop-opacity: 0;
}

.kz1a7xh5x {
  stop-color: var(--svg-color--ffd68c, #FFD68C);
}

.l49immmex {
  stop-color: var(--svg-color--c9895b, #C9895B);
  stop-opacity: 0;
}

.mbupjzbim {
  stop-color: var(--svg-color--c9895b, #C9895B);
}

.mi3xdbtde {
  stop-color: var(--svg-color--ffd894, #FFD894);
}

.myjz73u1g {
  stop-color: var(--svg-color--9e8563, #9E8563);
  stop-opacity: 0;
}

.o8vmkmbum {
  stop-color: var(--svg-color--ffcb56, #FFCB56);
}

.r_9ps2gtd {
  d: path("M25 30H7c-.6 0-1-.4-1-1s.4-1 1-1h18c.6 0 1 .4 1 1s-.4 1-1 1");
}

.r-ok_qbgz {
  stop-color: var(--svg-color--54453f, #54453F);
}

.r0pvbhb7v {
  stop-color: var(--svg-color--707477, #707477);
  stop-opacity: 0;
}

.r77r8e3rp {
  d: path("M22.4 4.9c-.5 0-.9.4-.9.9c-.2 1.9-1.2 4.5-3.6 5.4c-.5.2-.7.7-.5 1.2s.7.7 1.2.5c1.4-.5 2.6-1.5 3.4-2.9c.8-1.2 1.2-2.6 1.3-4.2c.1-.4-.3-.8-.9-.9");
}

.ri9usvcsw {
  stop-color: var(--svg-color--7ca0b3, #7CA0B3);
}

.rl7t4yb9v {
  stop-color: var(--svg-color--b69e6d, #B69E6D);
  stop-opacity: 0;
}

.rogsku4tt {
  stop-color: var(--svg-color--b69e6d, #B69E6D);
}

.s068febgy {
  stop-color: var(--svg-color--ffdf81, #FFDF81);
  stop-opacity: 0;
}

.sssti0bco {
  stop-color: var(--svg-color--e69e45, #E69E45);
}

.st40q3b-j {
  stop-color: var(--svg-color--7ca0b3, #7CA0B3);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t3d7zzb2n {
  stop-color: var(--svg-color--54453f, #54453F);
  stop-opacity: 0;
}

.tk00mxb5t {
  stop-color: var(--svg-color--ffdf81, #FFDF81);
}

.u_0zt-b6m {
  stop-color: var(--svg-color--ffd87f, #FFD87F);
  stop-opacity: 0;
}

.vadnxigha {
  stop-color: var(--svg-color--ffd87f, #FFD87F);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vp6n5ib_i {
  stop-color: var(--svg-color--c4f4ff, #C4F4FF);
  stop-opacity: 0;
}

.xd8k-p5dy {
  fill: var(--svg-color--9fd6ff, #9FD6FF);
  d: path("M25 6.4V3.9H7v2.5c0 4 2.8 7.3 6.5 8.2c.3.1.5.4.5.7v1.2c0 .3-.2.6-.5.6C9.8 18 7 21.3 7 25.3V28h18v-2.7c0-4-2.8-7.3-6.5-8.2c-.3-.1-.5-.3-.5-.6v-1.2c0-.3.2-.6.5-.6c3.7-1 6.5-4.3 6.5-8.3");
}

.yupcp6b2q {
  stop-color: var(--svg-color--ffe379, #FFE379);
}

.z99pf7bvs {
  stop-color: var(--svg-color--707477, #707477);
}

.zx1rf-sdj {
  stop-color: var(--svg-color--ffd894, #FFD894);
  stop-opacity: 0;
}

</style>
