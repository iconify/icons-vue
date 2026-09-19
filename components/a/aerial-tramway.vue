<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iRyj0cz)" class="d2kvgvbvc"><path class="zlvcq37vt"/><path fill="url(#iVywrVd)" class="m_tbqdbhv"/><path fill="url(#iPlNqcb)" class="m_tbqdbhv"/><path fill="url(#i8KvHbd)" class="m_tbqdbhv"/></g><path fill="url(#i3xQiDe)" class="jclhzhb3z"/><path fill="url(#iKbb2ae)" class="jclhzhb3z"/><g filter="url(#iGqHxwb)"><path fill="url(#ivnn8Sc)" class="plf-7tt9j"/><path fill="url(#iPWKUab)" class="plf-7tt9j"/><path fill="url(#iTEn00d)" class="plf-7tt9j"/><path fill="url(#iQbkdub)" class="plf-7tt9j"/></g><path fill="url(#i3qWrQc)" class="w0fmhobsa"/><path fill="url(#iA7GnPd)" class="a59xcxf5s"/><path fill="url(#iqFHcrc)" class="a59xcxf5s"/><path fill="url(#i32GxDe)" class="a59xcxf5s"/><path fill="url(#igQYU6b)" class="a59xcxf5s"/><g filter="url(#iHUkL1d)"><path fill="url(#iK4xBAb)" class="b_kiixhgv"/></g><g clip-rule="evenodd" filter="url(#ivS4W3d)" class="d2kvgvbvc"><path class="vq8u2mf9n"/><path fill="url(#ixqHxYb)" class="r-nq3cccu"/></g><defs><linearGradient id="iVywrVd" x1="3.658" x2="14.934" y1="8.083" y2="5.915" gradientUnits="userSpaceOnUse"><stop class="qfm1ug5ro"/><stop offset="1" class="fa9qeccsn"/></linearGradient><linearGradient id="iPlNqcb" x1="29" x2="27.879" y1="2.937" y2="3.053" gradientUnits="userSpaceOnUse"><stop class="om_3hee9d"/><stop offset="1" class="w9e7z6buv"/></linearGradient><linearGradient id="iKbb2ae" x1="15.885" x2="16" y1="5.373" y2="6.248" gradientUnits="userSpaceOnUse"><stop class="ao3y47bck"/><stop offset="1" class="dd79nk01j"/></linearGradient><linearGradient id="ivnn8Sc" x1="16" x2="16" y1="12" y2="30" gradientUnits="userSpaceOnUse"><stop class="th6u2rbei"/><stop offset="1" class="ak6n2q4gj"/></linearGradient><linearGradient id="iPWKUab" x1="23" x2="21.006" y1="25.246" y2="25.246" gradientUnits="userSpaceOnUse"><stop class="sbb39ac5k"/><stop offset="1" class="nzh8yhsyg"/></linearGradient><linearGradient id="iTEn00d" x1="16" x2="16" y1="12" y2="14.093" gradientUnits="userSpaceOnUse"><stop class="c0ej3vb5q"/><stop offset="1" class="w_wm6vuza"/></linearGradient><linearGradient id="i3qWrQc" x1="9" x2="23" y1="27.523" y2="27.523" gradientUnits="userSpaceOnUse"><stop class="qheux7b8t"/><stop offset=".096" class="du3_l0sja"/><stop offset=".927" class="du3_l0sja"/><stop offset="1" class="fs190mzdm"/></linearGradient><linearGradient id="iA7GnPd" x1="20" x2="20" y1="14" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".833" class="s3567j-ep"/><stop offset="1" class="i20hxab4m"/></linearGradient><linearGradient id="iqFHcrc" x1="15.807" x2="18.369" y1="20.813" y2="20.813" gradientUnits="userSpaceOnUse"><stop class="n5u1jnb5z"/><stop offset="1" class="fjqophbsj"/></linearGradient><linearGradient id="i32GxDe" x1="20" x2="20" y1="14" y2="16.313" gradientUnits="userSpaceOnUse"><stop class="sh2e23bom"/><stop offset="1" class="dct8l_bfe"/></linearGradient><linearGradient id="iK4xBAb" x1="10.619" x2="10.619" y1="23" y2="14" gradientUnits="userSpaceOnUse"><stop class="ghkgt8bnw"/><stop offset=".153" class="uljfmhh4r"/></linearGradient><linearGradient id="ixqHxYb" x1="23" x2="21.798" y1="3.964" y2="4.132" gradientUnits="userSpaceOnUse"><stop class="bogmdxbyf"/><stop offset="1" class="zq6xn0b-z"/></linearGradient><radialGradient id="i8KvHbd" cx="0" cy="0" r="1" gradientTransform="rotate(170.031 4.531 3.469)scale(1.19254 1.74148)" gradientUnits="userSpaceOnUse"><stop offset=".338" class="sl74fsblt"/><stop offset="1" class="mgq8tbf9k"/></radialGradient><radialGradient id="i3xQiDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2 0 0 -13.8855 17 8.104)" gradientUnits="userSpaceOnUse"><stop class="qf24miecr"/><stop offset=".896" class="tv94cubcg"/></radialGradient><radialGradient id="iQbkdub" cx="0" cy="0" r="1" gradientTransform="rotate(138.751 9.14 10.6)scale(4.13485 3.93679)" gradientUnits="userSpaceOnUse"><stop class="mkdkzebig"/><stop offset="1" class="qweqosb-i"/></radialGradient><radialGradient id="igQYU6b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84375 4.4375 -.99872 -.86509 24.432 13.688)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="axuu3ghgo"/><stop offset="1" class="t6qxzibft"/></radialGradient><filter id="iRyj0cz" width="26.4" height="6.15" x="3" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.545098 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12954"/></filter><filter id="iGqHxwb" width="15" height="18.5" x="9" y="11.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.45098 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12954"/></filter><filter id="iHUkL1d" width="7.5" height="10" x="7.5" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.521569 0 0 0 0 0.870588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12954"/></filter><filter id="ivS4W3d" width="14.9" height="4.353" x="8.5" y="2.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.317647 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12954"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:aerial-tramway" /></template>
<style>
.a59xcxf5s {
  d: path("M23 14h-5.07c-.51 0-.93.39-.93.861v7.278c0 .48.42.861.93.861H23z");
}

.ak6n2q4gj {
  stop-color: var(--svg-color--ff9f43, #FF9F43);
}

.ao3y47bck {
  stop-color: var(--svg-color--463d43, #463D43);
}

.axuu3ghgo {
  stop-color: var(--svg-color--41c9ff, #41C9FF);
}

.b_kiixhgv {
  d: path("M9 23h5.07c.51 0 .93-.39.93-.861v-7.278c0-.48-.42-.861-.93-.861H9z");
}

.bogmdxbyf {
  stop-color: var(--svg-color--989698, #989698);
}

.c0ej3vb5q {
  stop-color: var(--svg-color--ffca3a, #FFCA3A);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dct8l_bfe {
  stop-color: var(--svg-color--2298f9, #2298F9);
  stop-opacity: 0;
}

.dd79nk01j {
  stop-color: var(--svg-color--463d43, #463D43);
  stop-opacity: 0;
}

.du3_l0sja {
  stop-color: var(--svg-color--4ae98e, #4AE98E);
}

.fa9qeccsn {
  stop-color: var(--svg-color--eae3ef, #EAE3EF);
  stop-opacity: 0;
}

.fjqophbsj {
  stop-color: var(--svg-color--4ffaff, #4FFAFF);
  stop-opacity: 0;
}

.fs190mzdm {
  stop-color: var(--svg-color--62ffa9, #62FFA9);
}

.ft5dv1b6b {
  fill: none;
}

.ghkgt8bnw {
  stop-color: var(--svg-color--41d7ff, #41D7FF);
}

.i20hxab4m {
  stop-color: var(--svg-color--3fe6ff, #3FE6FF);
}

.jclhzhb3z {
  d: path("M15 13h2V5h-2z");
}

.m_tbqdbhv {
  d: path("M28.988 2.846a1 1 0 0 1-.834 1.142l-24 3.75a1 1 0 1 1-.308-1.976l24-3.75a1 1 0 0 1 1.142.834");
}

.mgq8tbf9k {
  stop-color: var(--svg-color--92748f, #92748F);
  stop-opacity: 0;
}

.mkdkzebig {
  stop-color: var(--svg-color--ffde55, #FFDE55);
}

.n5u1jnb5z {
  stop-color: var(--svg-color--4ffaff, #4FFAFF);
}

.nzh8yhsyg {
  stop-color: var(--svg-color--ffb950, #FFB950);
  stop-opacity: 0;
}

.om_3hee9d {
  stop-color: var(--svg-color--e5e2e8, #E5E2E8);
}

.plf-7tt9j {
  d: path("M20.999 30H11a2 2 0 0 1-2-2.001V14a2 2 0 0 1 2.001-2H21a2 2 0 0 1 2 2.001V28a2 2 0 0 1-2.001 2");
}

.qf24miecr {
  stop-color: var(--svg-color--8c888d, #8C888D);
}

.qfm1ug5ro {
  stop-color: var(--svg-color--eae3ef, #EAE3EF);
}

.qheux7b8t {
  stop-color: var(--svg-color--30a260, #30A260);
}

.qweqosb-i {
  stop-color: var(--svg-color--ffde55, #FFDE55);
  stop-opacity: 0;
}

.r-nq3cccu {
  d: path("M22.988 3.783a1 1 0 0 1-.834 1.143l-12.5 1.953a1 1 0 1 1-.308-1.976l12.5-1.953a1 1 0 0 1 1.142.833");
}

.s3567j-ep {
  stop-color: var(--svg-color--44ceff, #44CEFF);
}

.sbb39ac5k {
  stop-color: var(--svg-color--ffb950, #FFB950);
}

.sh2e23bom {
  stop-color: var(--svg-color--2298f9, #2298F9);
}

.sl74fsblt {
  stop-color: var(--svg-color--92748f, #92748F);
}

.t6qxzibft {
  stop-color: var(--svg-color--41c9ff, #41C9FF);
  stop-opacity: 0;
}

.th6u2rbei {
  stop-color: var(--svg-color--ffbc43, #FFBC43);
}

.tv94cubcg {
  stop-color: var(--svg-color--515151, #515151);
}

.uljfmhh4r {
  stop-color: var(--svg-color--3fb9ff, #3FB9FF);
}

.vq8u2mf9n {
  fill: var(--svg-color--797879, #797879);
  d: path("M22.988 3.783a1 1 0 0 1-.834 1.143l-12.5 1.953a1 1 0 1 1-.308-1.976l12.5-1.953a1 1 0 0 1 1.142.833");
}

.w_wm6vuza {
  stop-color: var(--svg-color--ffca3a, #FFCA3A);
  stop-opacity: 0;
}

.w0fmhobsa {
  d: path("M23 26H9v2h14z");
}

.w9e7z6buv {
  stop-color: var(--svg-color--e5e2e8, #E5E2E8);
  stop-opacity: 0;
}

.zlvcq37vt {
  fill: var(--svg-color--cec8d1, #CEC8D1);
  d: path("M28.988 2.846a1 1 0 0 1-.834 1.142l-24 3.75a1 1 0 1 1-.308-1.976l24-3.75a1 1 0 0 1 1.142.834");
}

.zq6xn0b-z {
  stop-color: var(--svg-color--989698, #989698);
  stop-opacity: 0;
}

</style>
