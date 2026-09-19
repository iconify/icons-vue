<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2QkLwe)"><path fill="url(#ibtXsob)" class="ujydyib8d"/><path fill="url(#iDFf17d)" class="ujydyib8d"/><path fill="url(#iMBTGpc)" class="ujydyib8d"/><path fill="url(#iwvImge)" class="ujydyib8d"/></g><g filter="url(#iIVRvxe)"><path fill="url(#iDzYhJc)" class="ueos9yy2y"/></g><rect fill="url(#irPi33d)" class="zys7f72ey"/><rect fill="url(#iTzyasd)" class="qxrjxujji"/><path fill="url(#iWbGghe)" class="tx2om3yfw"/><path fill="url(#iogY77c)" class="tx2om3yfw"/><path fill="url(#iF5Du0v)" class="tx2om3yfw"/><path fill="url(#ifoEnTd)" class="tx2om3yfw"/><g filter="url(#ifnuxed)"><rect fill="url(#i9pPKQe)" class="zgqyibz6l"/><rect fill="url(#iaFyRBe)" class="zgqyibz6l"/><rect fill="url(#i5lxGkU)" class="zgqyibz6l"/></g><rect fill="url(#iHcEl9b)" class="ap-god9dl"/><rect fill="url(#iuRhlLf)" class="ap-god9dl"/><rect fill="url(#ilEofGq)" class="ap-god9dl"/><g filter="url(#iEHJ20c)"><rect class="ufa2f4bjx"/></g><g filter="url(#iHCStNe)"><rect class="lm7lry1ov"/></g><rect fill="url(#iANJDId)" class="n9fokxb3a"/><rect fill="url(#i2NDFYc)" class="n9fokxb3a"/><rect fill="url(#iUvfVzd)" class="n9fokxb3a"/><defs><radialGradient id="iDFf17d" cx="0" cy="0" r="1" gradientTransform="matrix(8.56555 0 0 4.57895 7.71 11.043)" gradientUnits="userSpaceOnUse"><stop class="o-jksacjl"/><stop offset="1" class="ih021idxk"/></radialGradient><radialGradient id="iwvImge" cx="0" cy="0" r="1" gradientTransform="matrix(-6.63519 0 0 -10.3302 16.544 19.184)" gradientUnits="userSpaceOnUse"><stop class="kt17l7sie"/><stop offset="1" class="y7c2vrbpl"/></radialGradient><radialGradient id="iDzYhJc" cx="0" cy="0" r="1" gradientTransform="matrix(4.68782 -7.19713 5.98956 3.90127 15.573 24.596)" gradientUnits="userSpaceOnUse"><stop class="na8ddjbqw"/><stop offset="1" class="o_f0cm06s"/></radialGradient><radialGradient id="irPi33d" cx="0" cy="0" r="1" gradientTransform="matrix(-10.14807 -.05048 .00666 -1.33965 28.08 26.41)" gradientUnits="userSpaceOnUse"><stop class="jfx2np-qj"/><stop offset="1" class="crjd7cbgk"/></radialGradient><radialGradient id="iTzyasd" cx="0" cy="0" r="1" gradientTransform="rotate(-42.93 47.206 -22.411)scale(2.54081 2.06084)" gradientUnits="userSpaceOnUse"><stop class="jfx2np-qj"/><stop offset="1" class="crjd7cbgk"/></radialGradient><radialGradient id="iWbGghe" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1.8125 -5.24074 5.42145 12.967 6.38)" gradientUnits="userSpaceOnUse"><stop class="jsfzcsbqj"/><stop offset=".858" class="l27sgm3pw"/></radialGradient><radialGradient id="iogY77c" cx="0" cy="0" r="1" gradientTransform="rotate(142.344 8.33 7.288)scale(5.01297 1.89469)" gradientUnits="userSpaceOnUse"><stop class="tu60jbchi"/><stop offset="1" class="djsm13bco"/></radialGradient><radialGradient id="iF5Du0v" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 8.932 6.449)scale(2.98951 1.97665)" gradientUnits="userSpaceOnUse"><stop class="eegxolbhf"/><stop offset="1" class="dicqufbhu"/></radialGradient><radialGradient id="ifoEnTd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53125 0 0 -1.78125 17.752 10.813)" gradientUnits="userSpaceOnUse"><stop class="yxv7gzbqa"/><stop offset="1" class="r8m3gybjp"/></radialGradient><radialGradient id="i9pPKQe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.84274 23.662 11.85)" gradientUnits="userSpaceOnUse"><stop class="bzpjtjb_i"/><stop offset="1" class="ykc0znbsu"/></radialGradient><radialGradient id="i5lxGkU" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -.25 .16715 3.48919 17.125 15.031)" gradientUnits="userSpaceOnUse"><stop class="p1wdjgz1s"/><stop offset="1" class="d1vvt5brf"/></radialGradient><radialGradient id="iHcEl9b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.20272 22.19 21.615)" gradientUnits="userSpaceOnUse"><stop class="fvbl5pb0w"/><stop offset="1" class="icbl5ibjw"/></radialGradient><radialGradient id="ilEofGq" cx="0" cy="0" r="1" gradientTransform="matrix(7.33922 0 0 2.25494 18.534 25.193)" gradientUnits="userSpaceOnUse"><stop class="xiziqcb-g"/><stop offset="1" class="b8r_pg8dx"/></radialGradient><radialGradient id="iANJDId" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.11937 22.19 16.719)" gradientUnits="userSpaceOnUse"><stop class="l3r2-fb1n"/><stop offset="1" class="t9erzcpju"/></radialGradient><radialGradient id="iUvfVzd" cx="0" cy="0" r="1" gradientTransform="matrix(6.46207 0 0 3.4824 17.179 20.162)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="kny_dnbng"/><stop offset="1" class="yfmndvbnj"/></radialGradient><linearGradient id="ibtXsob" x1="14.36" x2="30.649" y1="31.333" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="uytcw0b7c"/><stop offset="1" class="ejmmex9wx"/></linearGradient><linearGradient id="iMBTGpc" x1="18.212" x2="18.212" y1="30.189" y2="26.494" gradientUnits="userSpaceOnUse"><stop class="t5t08qb6u"/><stop offset="1" class="ki9pd0bni"/></linearGradient><linearGradient id="iaFyRBe" x1="14.772" x2="19.102" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="e37clnbgw"/><stop offset="1" class="sigprqdzb"/></linearGradient><linearGradient id="iuRhlLf" x1="14.772" x2="19.102" y1="23.107" y2="23.107" gradientUnits="userSpaceOnUse"><stop class="i0jd6bqsl"/><stop offset="1" class="hmjvb-t8i"/></linearGradient><linearGradient id="i2NDFYc" x1="14.772" x2="19.102" y1="18.155" y2="18.155" gradientUnits="userSpaceOnUse"><stop class="rdlpvmb9l"/><stop offset="1" class="j4exkytzg"/></linearGradient><filter id="i2QkLwe" width="27.371" height="28.636" x="2.689" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.25098 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2635"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.380392 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2635" result="effect2_innerShadow_20020_2635"/></filter><filter id="iIVRvxe" width="11.25" height="16.974" x="13.037" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2635" stdDeviation=".75"/></filter><filter id="ifnuxed" width="10.338" height="6.078" x="15.376" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.298039 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2635"/></filter><filter id="iEHJ20c" width="8.315" height="2.188" x="16.308" y="13.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2635" stdDeviation=".375"/></filter><filter id="iHCStNe" width="8.315" height="2.188" x="16.308" y="19.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2635" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:call-me-hand-medium-dark" /></template>
<style>
.ap-god9dl {
  width: 10.088px;
  height: 5.781px;
  x: 15.376px;
  y: 19.412px;
  rx: 2.891px;
}

.b8r_pg8dx {
  stop-color: var(--svg-color--733a5f, #733A5F);
  stop-opacity: 0;
}

.bzpjtjb_i {
  stop-color: var(--svg-color--a47e73, #A47E73);
}

.crjd7cbgk {
  stop-color: var(--svg-color--a47e74, #A47E74);
  stop-opacity: 0;
}

.d1vvt5brf {
  stop-color: var(--svg-color--70454c, #70454C);
  stop-opacity: 0;
}

.dicqufbhu {
  stop-color: var(--svg-color--a37f72, #A37F72);
  stop-opacity: 0;
}

.djsm13bco {
  stop-color: var(--svg-color--7e5b50, #7E5B50);
  stop-opacity: 0;
}

.e37clnbgw {
  stop-color: var(--svg-color--6b4a3e, #6B4A3E);
}

.eegxolbhf {
  stop-color: var(--svg-color--a37f72, #A37F72);
}

.ejmmex9wx {
  stop-color: var(--svg-color--917060, #917060);
}

.ft5dv1b6b {
  fill: none;
}

.fvbl5pb0w {
  stop-color: var(--svg-color--a17b72, #A17B72);
}

.hmjvb-t8i {
  stop-color: var(--svg-color--5f3b38, #5F3B38);
  stop-opacity: 0;
}

.i0jd6bqsl {
  stop-color: var(--svg-color--5f3b38, #5F3B38);
}

.icbl5ibjw {
  stop-color: var(--svg-color--7e554c, #7E554C);
}

.ih021idxk {
  stop-color: var(--svg-color--805c4e, #805C4E);
  stop-opacity: 0;
}

.j4exkytzg {
  stop-color: var(--svg-color--66433b, #66433B);
  stop-opacity: 0;
}

.jfx2np-qj {
  stop-color: var(--svg-color--a47e74, #A47E74);
}

.jsfzcsbqj {
  stop-color: var(--svg-color--745b51, #745B51);
}

.ki9pd0bni {
  stop-color: var(--svg-color--7a4065, #7A4065);
  stop-opacity: 0;
}

.kny_dnbng {
  stop-color: var(--svg-color--6d3d4f, #6D3D4F);
}

.kt17l7sie {
  stop-color: var(--svg-color--604242, #604242);
}

.l27sgm3pw {
  stop-color: var(--svg-color--745b51, #745B51);
  stop-opacity: 0;
}

.l3r2-fb1n {
  stop-color: var(--svg-color--a37d73, #A37D73);
}

.lm7lry1ov {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 19.818px;
  fill: var(--svg-color--2d1c1a, #2D1C1A);
  rx: 0.344px;
}

.n9fokxb3a {
  width: 10.088px;
  height: 5.563px;
  x: 15.376px;
  y: 14.599px;
  rx: 2.781px;
}

.na8ddjbqw {
  stop-color: var(--svg-color--5c3240, #5C3240);
}

.o_f0cm06s {
  stop-color: var(--svg-color--3c2220, #3C2220);
}

.o-jksacjl {
  stop-color: var(--svg-color--805c4e, #805C4E);
}

.p1wdjgz1s {
  stop-color: var(--svg-color--70454c, #70454C);
}

.qxrjxujji {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  rx: 2.898px;
}

.r8m3gybjp {
  stop-color: var(--svg-color--8e7165, #8E7165);
  stop-opacity: 0;
}

.rdlpvmb9l {
  stop-color: var(--svg-color--66433b, #66433B);
}

.sigprqdzb {
  stop-color: var(--svg-color--6b4a3e, #6B4A3E);
  stop-opacity: 0;
}

.t5t08qb6u {
  stop-color: var(--svg-color--7a4065, #7A4065);
}

.t9erzcpju {
  stop-color: var(--svg-color--8c6554, #8C6554);
}

.tu60jbchi {
  stop-color: var(--svg-color--7e5b50, #7E5B50);
}

.tx2om3yfw {
  d: path("m17.97 10.425l-.008-.005c.597-.853 1.968-2.82 2.508-3.703c.79-1.29.679-3.1-.581-4.073a2.76 2.76 0 0 0-1.69-.587a3 3 0 0 0-1.566.46c-.36.222-.7.528-1 .918c-2.388 3.7-5.187 5.899-6.611 6.504l-.035.02q-.196.087-.389.182c-.155.108-.203.22-.236.559c-.133 1.348 1.235 3.249 2.294 4.058c1.271.972 3.09.73 4.063-.542l2.967-3.39z");
}

.ueos9yy2y {
  d: path("M14.537 14.715c0-1.439 1.07-2.606 2.388-2.606H20.4c1.319 0 2.388 1.167 2.388 2.606c0 .942-.457 1.767-1.143 2.224c.683.43 1.143 1.235 1.143 2.157c0 .934-.471 1.747-1.168 2.173c.699.449 1.168 1.28 1.168 2.229c0 .75-.145 1.874-1.338 2.15l-4.543.435c-1.308 0-2.369-1.157-2.369-2.585c0-.95.47-1.78 1.169-2.23c-.697-.425-1.169-1.238-1.169-2.172c0-.922.46-1.727 1.143-2.157c-.685-.457-1.143-1.282-1.143-2.224");
}

.ufa2f4bjx {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 14.256px;
  fill: var(--svg-color--75493c, #75493C);
  rx: 0.344px;
}

.ujydyib8d {
  d: path("M17.962 10.42c3.188 1.826 5.35 5.346 5.35 9.273c0 1.603-.361 3.112-1.004 4.453h4.13c1.587 0 2.873 1.298 2.873 2.899s-1.286 2.898-2.872 2.898H14.084q-.33 0-.634-.008q-.21.008-.419.008c-6.874 0-10.342-4.551-10.342-10.281c0-4.284 2.608-8.067 6.298-9.703l.035-.02c1.424-.605 4.223-2.804 6.61-6.504c1.192-1.547 2.997-1.764 4.257-.791c1.26.972 1.371 2.784.581 4.073c-.54.883-1.911 2.85-2.508 3.703");
}

.uytcw0b7c {
  stop-color: var(--svg-color--805454, #805454);
}

.xiziqcb-g {
  stop-color: var(--svg-color--733a5f, #733A5F);
}

.y7c2vrbpl {
  stop-color: var(--svg-color--604242, #604242);
  stop-opacity: 0;
}

.yfmndvbnj {
  stop-color: var(--svg-color--6d3d4f, #6D3D4F);
  stop-opacity: 0;
}

.ykc0znbsu {
  stop-color: var(--svg-color--8c6959, #8C6959);
}

.yxv7gzbqa {
  stop-color: var(--svg-color--8e7165, #8E7165);
}

.zgqyibz6l {
  width: 10.088px;
  height: 5.828px;
  x: 15.376px;
  y: 9.568px;
  rx: 2.914px;
}

.zys7f72ey {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 2.898px;
}

</style>
