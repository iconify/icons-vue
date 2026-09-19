<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLHw4Pm)" class="fpw1dibkj"/><path fill="url(#iOnfE5c)" class="fpw1dibkj"/><path fill="url(#ik23FNe)" class="fpw1dibkj"/><path fill="url(#i7lG5Gb)" class="fpw1dibkj"/><path fill="url(#ianF1Ld)" class="fpw1dibkj"/><g filter="url(#iuueL4d)"><path class="a_i-xitaj"/></g><g filter="url(#iaY7VQb)"><path class="p3k9gosaa"/><path fill="url(#i5uoFee)" class="n_m0ys0rt"/><path fill="url(#ikyOOKb)" class="n_m0ys0rt"/><path fill="url(#iccL3qd)" class="n_m0ys0rt"/></g><g filter="url(#iY7P3Rb)"><path class="b23ha1bnl"/></g><g filter="url(#iNoWAoL)"><path class="quftqob0z"/></g><g filter="url(#iKOLfdt)"><path class="odspdbbjb"/></g><path class="kpiqozb3b"/><path fill="url(#iYYVhKc)" class="dnco-pjnw"/><path fill="url(#iDWAOxc)" class="dnco-pjnw"/><path fill="url(#iJI6aDe)" class="dnco-pjnw"/><path fill="url(#iyUsMMB)" class="dnco-pjnw"/><path class="e40-3vm0s"/><path fill="url(#ij9veRd)" class="jt2z0jq_a"/><path fill="url(#iBvwP1w)" class="jt2z0jq_a"/><path fill="url(#ibkzBhK)" class="jt2z0jq_a"/><path fill="url(#if9Iute)" class="jt2z0jq_a"/><g filter="url(#iyavX5d)"><path class="exzue-bbq"/></g><path fill="url(#iHBSnZc)" class="pyycpcc6t"/><path fill="url(#i6PTxyb)" class="pyycpcc6t"/><path fill="url(#ibgLifb)" class="pyycpcc6t"/><path fill="url(#idBN2Ow)" class="pyycpcc6t"/><g filter="url(#iRhDGac)"><rect fill="url(#ibCWw0b)" class="vru19zblu"/></g><g filter="url(#iagz4dM)"><rect class="n4mpufbph"/></g><path fill="url(#iH41Shj)" class="eva8h4bvc"/><path fill="url(#iI6aD0c)" class="eva8h4bvc"/><g filter="url(#iowGued)"><path stroke="url(#ij454nd)" class="y-09j-5gw"/></g><path fill="url(#ioBbVYU)" class="k0ts761-w"/><path fill="url(#i2PCbJb)" class="k0ts761-w"/><defs><radialGradient id="iOnfE5c" cx="0" cy="0" r="1" gradientTransform="rotate(-145.784 13.31 1.811)scale(7.55811 20.3298)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="cjm83h0yp"/><stop offset="1" class="fkugq9v2v"/></radialGradient><radialGradient id="ik23FNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44892 .96594 -7.83612 -11.75422 20.112 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="r0o-qwbxs"/><stop offset="1" class="gd0adhb3s"/></radialGradient><radialGradient id="i7lG5Gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.26935 1.63468 0 19.183 14.802)" gradientUnits="userSpaceOnUse"><stop class="kbaovabxk"/><stop offset="1" class="o8xggdbnl"/></radialGradient><radialGradient id="ianF1Ld" cx="0" cy="0" r="1" gradientTransform="rotate(128.409 12.302 7.468)scale(3.53833 4.6463)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="jwrdadcdn"/><stop offset="1" class="dsv0sgwla"/></radialGradient><radialGradient id="i5uoFee" cx="0" cy="0" r="1" gradientTransform="matrix(9.31253 10.06253 -14.13907 13.08522 6.674 14.53)" gradientUnits="userSpaceOnUse"><stop class="yq1cnib9k"/><stop offset="1" class="nvdhdwbgn"/></radialGradient><radialGradient id="ikyOOKb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 0 0 -2.78125 20.69 20.74)" gradientUnits="userSpaceOnUse"><stop class="gu196_b-i"/><stop offset="1" class="hpgurty9y"/></radialGradient><radialGradient id="iccL3qd" cx="0" cy="0" r="1" gradientTransform="matrix(.61472 -8.4666 16.95696 1.23117 14.35 29.925)" gradientUnits="userSpaceOnUse"><stop class="p38fir0qv"/><stop offset="1" class="sq72eym-f"/></radialGradient><radialGradient id="iDWAOxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.14698 -4.32661 0 8.6 10.49)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="aocgxmblx"/><stop offset="1" class="x7ljarmly"/></radialGradient><radialGradient id="iJI6aDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 0 0 -3.75 10.86 12.7)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="slr-ambqj"/><stop offset="1" class="dwezpu8qg"/></radialGradient><radialGradient id="ij9veRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.80191 -4.23235 0 13.16 9.563)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="wwplfuj4r"/><stop offset="1" class="ov_r32bpj"/></radialGradient><radialGradient id="ibkzBhK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16274 -.82077 1.14253 -1.61856 15.584 15.878)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="n9op-sbml"/><stop offset="1" class="lsu163ygp"/></radialGradient><radialGradient id="iHBSnZc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36442 6.31216 -14.65791 -5.49058 23.369 14.901)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="i8xyi-54t"/><stop offset="1" class="cijw77xba"/></radialGradient><radialGradient id="ibgLifb" cx="0" cy="0" r="1" gradientTransform="matrix(2.53066 1.77831 -3.77054 5.36574 14.643 14.613)" gradientUnits="userSpaceOnUse"><stop class="k2euzmbfw"/><stop offset="1" class="ea85904kk"/></radialGradient><radialGradient id="idBN2Ow" cx="0" cy="0" r="1" gradientTransform="matrix(.90292 -.5788 .91809 1.43221 15.373 17.911)" gradientUnits="userSpaceOnUse"><stop class="n54ahujkr"/><stop offset="1" class="l5tvdacot"/></radialGradient><radialGradient id="iH41Shj" cx="0" cy="0" r="1" gradientTransform="matrix(18.51557 -4.60029 4.82039 19.40144 8.234 18.36)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="uav4pabdo"/><stop offset="1" class="udqb71bgn"/></radialGradient><radialGradient id="iI6aD0c" cx="0" cy="0" r="1" gradientTransform="matrix(-16.56248 5.49997 -10.06467 -30.30848 22.986 18.237)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="fttgpldms"/><stop offset="1" class="kpnhaop3p"/></radialGradient><radialGradient id="ioBbVYU" cx="0" cy="0" r="1" gradientTransform="matrix(2.6769 -1.59518 7.56953 12.70254 18.252 9.645)" gradientUnits="userSpaceOnUse"><stop class="wifihe1qp"/><stop offset="1" class="zibcchyxc"/></radialGradient><radialGradient id="i2PCbJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.99614 3.81794 -5.7135 2.9872 16.271 2.078)" gradientUnits="userSpaceOnUse"><stop class="vi_7ch7-s"/><stop offset="1" class="usb7yzbzo"/></radialGradient><filter id="iuueL4d" width="9.747" height="10.915" x="17.071" y="1.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation="1"/></filter><filter id="iaY7VQb" width="20.855" height="28.601" x="5.809" y="1.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.490196 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2271"/></filter><filter id="iY7P3Rb" width="14.735" height="10.475" x="11.692" y="13.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation="1"/></filter><filter id="iNoWAoL" width="7.158" height="9.171" x="5.362" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation=".5"/></filter><filter id="iKOLfdt" width="9.128" height="11.13" x="7.814" y="8.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation="1"/></filter><filter id="iyavX5d" width="11.372" height="22.961" x="15.717" y="1.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation="1"/></filter><filter id="iRhDGac" width="3.86" height="6.984" x="7.204" y="9.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation=".625"/></filter><filter id="iagz4dM" width="5.193" height="9.397" x="11.616" y="7.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation=".875"/></filter><filter id="iowGued" width="11.553" height="9.797" x="15.722" y="13.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2271" stdDeviation="1"/></filter><linearGradient id="iLHw4Pm" x1="16.787" x2="25.014" y1="16.053" y2="3.286" gradientUnits="userSpaceOnUse"><stop class="g9rx29bya"/><stop offset="1" class="bxjtrzhdg"/></linearGradient><linearGradient id="iYYVhKc" x1="5.809" x2="8.141" y1="13.356" y2="13.356" gradientUnits="userSpaceOnUse"><stop class="fa6dpirps"/><stop offset="1" class="tzdkw8bsj"/></linearGradient><linearGradient id="iyUsMMB" x1="5.482" x2="9.225" y1="13.021" y2="13.021" gradientUnits="userSpaceOnUse"><stop class="ll-u65hkb"/><stop offset=".25" class="cwvhxryzf"/></linearGradient><linearGradient id="iBvwP1w" x1="9.93" x2="12.694" y1="12.861" y2="12.861" gradientUnits="userSpaceOnUse"><stop class="p74ungb8f"/><stop offset="1" class="aqt3-8h6m"/></linearGradient><linearGradient id="if9Iute" x1="17.642" x2="13.161" y1="10.117" y2="11.102" gradientUnits="userSpaceOnUse"><stop class="kx7a8ob5d"/><stop offset="1" class="d16nf17ay"/></linearGradient><linearGradient id="i6PTxyb" x1="23.364" x2="23.364" y1="23.23" y2="20.153" gradientUnits="userSpaceOnUse"><stop offset=".371" class="w5g8lwoth"/><stop offset="1" class="lbout0f0z"/></linearGradient><linearGradient id="ibCWw0b" x1="9.483" x2="9.483" y1="14.557" y2="10.487" gradientUnits="userSpaceOnUse"><stop class="c5i_ib_bv"/><stop offset="1" class="e8-t0rb4l"/></linearGradient><linearGradient id="ij454nd" x1="17.652" x2="27.22" y1="16.001" y2="20.366" gradientUnits="userSpaceOnUse"><stop class="tsc3_abvm"/><stop offset="1" class="ay9_w8o5e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-fingers-light" /></template>
<style>
.a_i-xitaj {
  stroke: var(--svg-color--ffe2c5, #FFE2C5);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.567 4.66c-.928 1.151-1.946 2.619-3.246 4.415");
}

.aocgxmblx {
  stop-color: var(--svg-color--c58789, #C58789);
  stop-opacity: 0;
}

.aqt3-8h6m {
  stop-color: var(--svg-color--cf977d, #CF977D);
  stop-opacity: 0;
}

.ay9_w8o5e {
  stop-color: var(--svg-color--ffe3ca, #FFE3CA);
  stop-opacity: 0;
}

.b23ha1bnl {
  fill: var(--svg-color--b8736b, #B8736B);
  d: path("M16.829 15.106c-1.733 0-3.137 1.246-3.137 2.782s1.404 2.783 3.137 2.783h1.67c2.526 0 3.18.132 3.38.359l1.535-.178c1.23 1.4.996.652.996-1.122v-.505c0-2.84-1.56-3.711-4.65-4.071a3.5 3.5 0 0 0-.583-.048z");
}

.bxjtrzhdg {
  stop-color: var(--svg-color--f9c6a7, #F9C6A7);
}

.c5i_ib_bv {
  stop-color: var(--svg-color--efc1b1, #EFC1B1);
}

.cijw77xba {
  stop-color: var(--svg-color--bf7f86, #BF7F86);
}

.cjm83h0yp {
  stop-color: var(--svg-color--d6a58a, #D6A58A);
  stop-opacity: 0;
}

.cwvhxryzf {
  stop-color: var(--svg-color--eeb59b, #EEB59B);
  stop-opacity: 0;
}

.d16nf17ay {
  stop-color: var(--svg-color--ffd5b4, #FFD5B4);
  stop-opacity: 0;
}

.dnco-pjnw {
  d: path("M5.81 11.664c0-1.43 1.249-2.59 2.79-2.59c1.542 0 2.791 1.16 2.791 2.59v2.383c0 1.43-1.25 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.dsv0sgwla {
  stop-color: var(--svg-color--ffe1c2, #FFE1C2);
  stop-opacity: 0;
}

.dwezpu8qg {
  stop-color: var(--svg-color--ce9175, #CE9175);
  stop-opacity: 0;
}

.e40-3vm0s {
  fill: var(--svg-color--e6b498, #E6B498);
  d: path("M10.32 10.914c0-1.646 1.272-2.98 2.84-2.98c1.569 0 2.84 1.334 2.84 2.98v2.743c0 1.646-1.271 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.e8-t0rb4l {
  stop-color: var(--svg-color--efc1b1, #EFC1B1);
  stop-opacity: 0;
}

.ea85904kk {
  stop-color: var(--svg-color--e5ab8c, #E5AB8C);
  stop-opacity: 0;
}

.eva8h4bvc {
  d: path("m5.997 20.819l-.188-5.115V14.15h.002c.06 1.382 1.286 2.485 2.79 2.485c.966 0 1.818-.457 2.319-1.15c.52.7 1.33 1.15 2.24 1.15c1.408 0 2.576-1.075 2.8-2.485h4.318c.01-.843-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.566.516-4.305c1.476-.96 3.218-.25 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.397-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.138-9.658-9.125");
}

.exzue-bbq {
  stroke: var(--svg-color--ffe7c9, #FFE7C9);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.717 4.23c2.11 2.244 4.896 6.193 5.22 9.601c.345 3.617 0 5.966 0 7.36");
}

.fa6dpirps {
  stop-color: var(--svg-color--dbaa8f, #DBAA8F);
}

.fkugq9v2v {
  stop-color: var(--svg-color--d6a58a, #D6A58A);
}

.fpw1dibkj {
  d: path("M20.798 2.91c-2.137 2.179-4.641 5.149-5.516 8.633l-.223 2.766h5.031c1.032-1.823 2.813-5.32 4.575-7.305s.555-3.777-.067-4.308a2.68 2.68 0 0 0-3.8.215");
}

.ft5dv1b6b {
  fill: none;
}

.fttgpldms {
  stop-color: var(--svg-color--eeb39b, #EEB39B);
  stop-opacity: 0;
}

.g9rx29bya {
  stop-color: var(--svg-color--f6a781, #F6A781);
}

.gd0adhb3s {
  stop-color: var(--svg-color--e2916e, #E2916E);
  stop-opacity: 0;
}

.gu196_b-i {
  stop-color: var(--svg-color--f7c1b4, #F7C1B4);
}

.hpgurty9y {
  stop-color: var(--svg-color--f7c1b4, #F7C1B4);
  stop-opacity: 0;
}

.i8xyi-54t {
  stop-color: var(--svg-color--ffddc1, #FFDDC1);
}

.jt2z0jq_a {
  d: path("M10.32 10.914c0-1.646 1.272-2.98 2.84-2.98c1.569 0 2.84 1.334 2.84 2.98v2.743c0 1.646-1.271 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.jwrdadcdn {
  stop-color: var(--svg-color--ffe1c2, #FFE1C2);
}

.k0ts761-w {
  d: path("M20.112 13.48c1.027.113 3.179.378 4.779 2.76c.887-7.738-4.406-12.814-4.406-12.814c-.727-1.148-2.469-1.86-3.945-.898c-1.136.739-1.938 2.414-.516 4.304c1.979 2.632 3.583 5.308 4.088 6.649");
}

.k2euzmbfw {
  stop-color: var(--svg-color--e5ab8c, #E5AB8C);
}

.kbaovabxk {
  stop-color: var(--svg-color--ffcaac, #FFCAAC);
}

.kpiqozb3b {
  fill: var(--svg-color--e1af93, #E1AF93);
  d: path("M5.81 11.664c0-1.43 1.249-2.59 2.79-2.59c1.542 0 2.791 1.16 2.791 2.59v2.383c0 1.43-1.25 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.kpnhaop3p {
  stop-color: var(--svg-color--eeb39b, #EEB39B);
}

.kx7a8ob5d {
  stop-color: var(--svg-color--ffd5b4, #FFD5B4);
}

.l5tvdacot {
  stop-color: var(--svg-color--d69b8e, #D69B8E);
  stop-opacity: 0;
}

.lbout0f0z {
  stop-color: var(--svg-color--e4aea5, #E4AEA5);
  stop-opacity: 0;
}

.ll-u65hkb {
  stop-color: var(--svg-color--eeb59b, #EEB59B);
}

.lsu163ygp {
  stop-color: var(--svg-color--c97e64, #C97E64);
  stop-opacity: 0;
}

.n_m0ys0rt {
  d: path("m5.997 20.8l-.188-5.115V14.13h14.469c.01-.843-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.565.516-4.305c1.476-.96 3.05-.16 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.397-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.138-9.658-9.125");
}

.n4mpufbph {
  width: 1.693px;
  height: 5.897px;
  x: 13.366px;
  y: 9.075px;
  fill: var(--svg-color--ffe6c9, #FFE6C9);
  rx: 0.847px;
}

.n54ahujkr {
  stop-color: var(--svg-color--d69b8e, #D69B8E);
}

.n9op-sbml {
  stop-color: var(--svg-color--c97e64, #C97E64);
}

.nvdhdwbgn {
  stop-color: var(--svg-color--d7a092, #D7A092);
  stop-opacity: 0;
}

.o8xggdbnl {
  stop-color: var(--svg-color--ffcaac, #FFCAAC);
  stop-opacity: 0;
}

.odspdbbjb {
  fill: var(--svg-color--b8736b, #B8736B);
  d: path("M9.814 12.914c0-1.348 1.148-2.442 2.564-2.442s2.564 1.094 2.564 2.442v2.247c0 1.348-1.148 2.441-2.564 2.441s-2.564-1.093-2.564-2.441z");
}

.ov_r32bpj {
  stop-color: var(--svg-color--c8898e, #C8898E);
}

.p38fir0qv {
  stop-color: var(--svg-color--e8b1ac, #E8B1AC);
}

.p3k9gosaa {
  fill: var(--svg-color--e4ada4, #E4ADA4);
  d: path("m5.997 20.8l-.188-5.115V14.13h14.469c.01-.843-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.565.516-4.305c1.476-.96 3.05-.16 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.397-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.138-9.658-9.125");
}

.p74ungb8f {
  stop-color: var(--svg-color--cf977d, #CF977D);
}

.pyycpcc6t {
  d: path("M17.813 13.48a2.984 2.984 0 1 0 0 5.97h1.59a1 1 0 0 1 .788.385l2.045 2.621c1.17 1.501 3.577.674 3.577-1.23v-1.745a6 6 0 0 0-5.212-5.949a3 3 0 0 0-.554-.051z");
}

.quftqob0z {
  fill: var(--svg-color--b8736b, #B8736B);
  d: path("M6.362 12.155C6.362 10.8 7.516 9.7 8.94 9.7s2.579 1.1 2.579 2.455v2.26c0 1.357-1.155 2.456-2.58 2.456c-1.424 0-2.578-1.1-2.578-2.456z");
}

.r0o-qwbxs {
  stop-color: var(--svg-color--e2916e, #E2916E);
}

.slr-ambqj {
  stop-color: var(--svg-color--ce9175, #CE9175);
}

.sq72eym-f {
  stop-color: var(--svg-color--e8b1ac, #E8B1AC);
  stop-opacity: 0;
}

.tsc3_abvm {
  stop-color: var(--svg-color--ffe3ca, #FFE3CA);
}

.tzdkw8bsj {
  stop-color: var(--svg-color--dbaa8f, #DBAA8F);
  stop-opacity: 0;
}

.uav4pabdo {
  stop-color: var(--svg-color--ffe0c0, #FFE0C0);
  stop-opacity: 0;
}

.udqb71bgn {
  stop-color: var(--svg-color--ffe0c0, #FFE0C0);
}

.usb7yzbzo {
  stop-color: var(--svg-color--d5a88e, #D5A88E);
  stop-opacity: 0;
}

.vi_7ch7-s {
  stop-color: var(--svg-color--d5a88e, #D5A88E);
}

.vru19zblu {
  width: 1.36px;
  height: 4.484px;
  x: 8.454px;
  y: 10.487px;
  rx: 0.68px;
}

.w5g8lwoth {
  stop-color: var(--svg-color--e4aea5, #E4AEA5);
}

.wifihe1qp {
  stop-color: var(--svg-color--efa17a, #EFA17A);
}

.wwplfuj4r {
  stop-color: var(--svg-color--c8898e, #C8898E);
  stop-opacity: 0;
}

.x7ljarmly {
  stop-color: var(--svg-color--c58789, #C58789);
}

.y-09j-5gw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.722 16.001h.614c2.03 0 4.2.587 4.724 2.548c.1.372.175.788.214 1.249");
}

.yq1cnib9k {
  stop-color: var(--svg-color--d7a092, #D7A092);
}

.zibcchyxc {
  stop-color: var(--svg-color--efa17a, #EFA17A);
  stop-opacity: 0;
}

</style>
