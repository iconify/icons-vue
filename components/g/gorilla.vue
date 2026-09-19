<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iikWfEe)" class="x-prdacty"/><path fill="url(#inkDbod)" class="x-prdacty"/><path fill="url(#iowHAcc)" class="x-prdacty"/><path fill="url(#iZIPTOe)" class="z2pcl-bvf"/><path fill="url(#iPfGu4d)" class="z2pcl-bvf"/><path fill="url(#i71uZJe)" class="oxaxplblj"/><path fill="url(#inWEfLc)" class="oxaxplblj"/><path fill="url(#iGoBv5d)" class="oxaxplblj"/><path fill="url(#ifrE68b)" class="c8mpzcwuv"/><path fill="url(#irFfFKd)" class="c8mpzcwuv"/><path fill="url(#i7Iieec)" class="c8mpzcwuv"/><path fill="url(#iNDu0hc)" class="b8erv2bsc"/><path fill="url(#iJUKgWc)" class="b8erv2bsc"/><path fill="url(#ipEhzHd)" class="if79bys7v"/><path fill="url(#iWTSwpl)" class="ne3vcqb_o"/><path fill="url(#ibFLCdb)" class="p1ev7s5kb"/><path fill="url(#i3UfWdc)" class="if79bys7v"/><path fill="url(#i4uZtbd)" class="if79bys7v"/><path fill="url(#iX2mgdc)" class="if79bys7v"/><path fill="url(#i0AB7Gc)" class="if79bys7v"/><path fill="url(#inX9d8b)" class="go72zmmim"/><path fill="url(#iKz09fZ)" class="go72zmmim"/><path fill="url(#ig6PUvd)" class="fe5b8fb1d"/><path fill="url(#iags9Od)" class="fe5b8fb1d"/><path fill="url(#isCySSd)" class="fe5b8fb1d"/><g class="mc2zb0bvp"><path fill="url(#iJe2rib)" class="d_jc1q9bb"/><path fill="url(#i5g8L1d)" class="d_jc1q9bb"/><path fill="url(#ieSv6tb)" class="d_jc1q9bb"/></g><path stroke="url(#ilf4lXb)" class="hx3bebcev"/><path stroke="url(#i0JvoCP)" class="hx3bebcev"/><path stroke="url(#i58FIpe)" class="hx3bebcev"/><path fill="url(#iJHp0ib)" class="cbgt__bps"/><g filter="url(#im31Cfe)"><path stroke="url(#iqUbDWd)" class="o67r5wbic"/></g><g filter="url(#ihBdhUc)"><path stroke="url(#iYHEAZc)" class="k3c_pi7nu"/></g><g filter="url(#iCT0Itl)"><path stroke="url(#itFtdrb)" class="l6__2hsxb"/></g><g filter="url(#iO9eSiM)"><path stroke="url(#iNMX2rd)" class="a68yjcdmc"/></g><g filter="url(#iaLwLje)"><path stroke="url(#iC5QGpw)" class="ybui-o2jf"/></g><g filter="url(#ixumFdd)"><path stroke="url(#irRyvoe)" class="sdm-ndbrp"/></g><g filter="url(#iIGdgnb)"><path stroke="url(#iafaebH)" class="a5w4p81ec"/></g><g filter="url(#iUuHMec)"><circle class="r595czxld"/></g><defs><linearGradient id="iowHAcc" x1="6.438" x2="4.313" y1="4.787" y2="4.037" gradientUnits="userSpaceOnUse"><stop class="m0k7zpb2m"/><stop offset="1" class="shox5uk4r"/></linearGradient><linearGradient id="i71uZJe" x1="5.698" x2="5.698" y1="9.235" y2="12.725" gradientUnits="userSpaceOnUse"><stop class="kd8jyjbki"/><stop offset=".859" class="m34aaxg1g"/></linearGradient><linearGradient id="iGoBv5d" x1="8.469" x2="4.969" y1="8.194" y2="8.194" gradientUnits="userSpaceOnUse"><stop class="c8ik61cpo"/><stop offset="1" class="bj4kcdbld"/></linearGradient><linearGradient id="ifrE68b" x1="21.125" x2="23.49" y1="29.764" y2="29.875" gradientUnits="userSpaceOnUse"><stop offset=".006" class="qzooa0bqp"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="irFfFKd" x1="26.515" x2="24.172" y1="28.82" y2="30.569" gradientUnits="userSpaceOnUse"><stop class="ock3xybnw"/><stop offset="1" class="aabm5ab7p"/></linearGradient><linearGradient id="i7Iieec" x1="28.611" x2="28.611" y1="25.694" y2="31.975" gradientUnits="userSpaceOnUse"><stop offset=".562" class="ezqs4pheh"/><stop offset=".893" class="dqm4midsh"/></linearGradient><linearGradient id="iNDu0hc" x1="12.372" x2="12.372" y1="26.975" y2="29.764" gradientUnits="userSpaceOnUse"><stop offset=".006" class="qzooa0bqp"/><stop offset=".821" class="zaeth0b6d"/></linearGradient><linearGradient id="iJUKgWc" x1="13.531" x2="13.531" y1="25.694" y2="30.944" gradientUnits="userSpaceOnUse"><stop offset=".667" class="th91jc7ug"/><stop offset=".893" class="xra70j_um"/></linearGradient><linearGradient id="ipEhzHd" x1="17.686" x2="17.686" y1="8.375" y2="30.35" gradientUnits="userSpaceOnUse"><stop class="n0szxubcv"/><stop offset="1" class="o6b9gqfwz"/></linearGradient><linearGradient id="i3UfWdc" x1="12.875" x2="11.588" y1="25.475" y2="30.885" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zc8l7b8-k"/><stop offset="1" class="kc7ochpyp"/></linearGradient><linearGradient id="i4uZtbd" x1="10.625" x2=".75" y1="23.975" y2="23.975" gradientUnits="userSpaceOnUse"><stop offset=".246" class="zc8l7b8-k"/><stop offset="1" class="hsv73e5-f"/></linearGradient><linearGradient id="i0AB7Gc" x1="7.625" x2="4.688" y1="23.85" y2="23.85" gradientUnits="userSpaceOnUse"><stop offset=".246" class="s-mozwu8j"/><stop offset="1" class="m7v0eqbbm"/></linearGradient><linearGradient id="ig6PUvd" x1="26.601" x2="24.443" y1="26.07" y2="27.789" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zc8l7b8-k"/><stop offset="1" class="hsv73e5-f"/></linearGradient><linearGradient id="ilf4lXb" x1="1.906" x2="3.688" y1="10.069" y2="10.069" gradientUnits="userSpaceOnUse"><stop class="jnfp8ob_e"/><stop offset="1" class="cfxas3b2w"/></linearGradient><linearGradient id="i0JvoCP" x1="3.352" x2="3.352" y1="10.006" y2="9.303" gradientUnits="userSpaceOnUse"><stop class="vmvlmobft"/><stop offset="1" class="hs9_tsq5k"/></linearGradient><linearGradient id="i58FIpe" x1=".719" x2="2.391" y1="10.166" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="i3vabvstq"/><stop offset="1" class="fibjm-c2s"/></linearGradient><linearGradient id="iqUbDWd" x1="26.375" x2="2.313" y1="12.85" y2="3.35" gradientUnits="userSpaceOnUse"><stop class="avobd3kro"/><stop offset=".456" class="j28r3nlvv"/><stop offset="1" class="avobd3kro"/></linearGradient><linearGradient id="iYHEAZc" x1="28.385" x2="28.385" y1="34.787" y2="18.787" gradientUnits="userSpaceOnUse"><stop class="avobd3kro"/><stop offset="1" class="j28r3nlvv"/></linearGradient><linearGradient id="itFtdrb" x1="7.443" x2="7.443" y1="20.01" y2="3.41" gradientUnits="userSpaceOnUse"><stop class="nu0dfpdww"/><stop offset="1" class="j28r3nlvv"/></linearGradient><linearGradient id="iNMX2rd" x1="29.438" x2="24.656" y1="32.412" y2="25.225" gradientUnits="userSpaceOnUse"><stop class="zc8l7b8-k"/><stop offset="1" class="hsv73e5-f"/></linearGradient><linearGradient id="iC5QGpw" x1="10.526" x2="10.526" y1="29.665" y2="19.482" gradientUnits="userSpaceOnUse"><stop class="nu0dfpdww"/><stop offset="1" class="j28r3nlvv"/></linearGradient><linearGradient id="irRyvoe" x1="9.656" x2="4.906" y1="29.662" y2="26.225" gradientUnits="userSpaceOnUse"><stop class="avobd3kro"/><stop offset=".417" class="j28r3nlvv"/><stop offset="1" class="avobd3kro"/></linearGradient><linearGradient id="iafaebH" x1="1.055" x2="3.457" y1="9.269" y2="10.966" gradientUnits="userSpaceOnUse"><stop class="i3vabvstq"/><stop offset="1" class="fibjm-c2s"/></linearGradient><radialGradient id="iikWfEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 3.125 -2.77436 .91554 10.313 4.819)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="shox5uk4r"/><stop offset="1" class="vnxo6lb0j"/></radialGradient><radialGradient id="inkDbod" cx="0" cy="0" r="1" gradientTransform="rotate(-80.628 9.585 -.165)scale(3.2623)" gradientUnits="userSpaceOnUse"><stop class="rf6di7b3f"/><stop offset="1" class="op-a1yb2c"/></radialGradient><radialGradient id="iZIPTOe" cx="0" cy="0" r="1" gradientTransform="rotate(125.262 1.79 3.9)scale(2.34101)" gradientUnits="userSpaceOnUse"><stop class="jy3_cwzjf"/><stop offset="1" class="txof9obun"/></radialGradient><radialGradient id="iPfGu4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.29056 5.05944 0 5.371 7.881)" gradientUnits="userSpaceOnUse"><stop class="q96gxkddq"/><stop offset="1" class="hs9_tsq5k"/></radialGradient><radialGradient id="inWEfLc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -4.39611 6.438 9.527)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="zcchowbby"/><stop offset="1" class="lgcnr-bwf"/></radialGradient><radialGradient id="iWTSwpl" cx="0" cy="0" r="1" gradientTransform="matrix(7.0625 1.6875 -1.2627 5.28466 23.938 7.913)" gradientUnits="userSpaceOnUse"><stop class="o6b9gqfwz"/><stop offset="1" class="ctz-iy-wu"/></radialGradient><radialGradient id="ibFLCdb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -10.37495 9.16257 -4.8021 13.438 19.913)" gradientUnits="userSpaceOnUse"><stop class="o6b9gqfwz"/><stop offset="1" class="ctz-iy-wu"/></radialGradient><radialGradient id="iX2mgdc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.287 15.985 7.205)scale(24.0381 19.8361)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="iwxzu_b3g"/><stop offset=".96" class="txmocabtv"/></radialGradient><radialGradient id="inX9d8b" cx="0" cy="0" r="1" gradientTransform="rotate(121.091 -1.016 14.206)scale(8.7143 11.9305)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="th91jc7ug"/><stop offset="1" class="vfy8vbv6t"/></radialGradient><radialGradient id="iKz09fZ" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 0 0 12.2369 12.594 24.256)" gradientUnits="userSpaceOnUse"><stop class="hsv73e5-f"/><stop offset=".578" class="zc8l7b8-k"/></radialGradient><radialGradient id="iags9Od" cx="0" cy="0" r="1" gradientTransform="rotate(141.001 9.797 16.925)scale(8.24319 17.4719)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="th91jc7ug"/><stop offset="1" class="vfy8vbv6t"/></radialGradient><radialGradient id="isCySSd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52425 5.46875 -9.20593 -4.24926 29.125 24.662)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="i5aiy6bsa"/><stop offset="1" class="fbjq0su5e"/></radialGradient><radialGradient id="iJe2rib" cx="0" cy="0" r="1" gradientTransform="rotate(102.902 .935 16.972)scale(7.27749 12.4145)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="nuecyp9xg"/><stop offset="1" class="dl214rp3m"/></radialGradient><radialGradient id="i5g8L1d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.37508 12.12501 -18.1468 -6.54792 17.5 13.6)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="th91jc7ug"/><stop offset="1" class="vfy8vbv6t"/></radialGradient><radialGradient id="ieSv6tb" cx="0" cy="0" r="1" gradientTransform="rotate(108.362 3.842 13.115)scale(11.1107 15.0218)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="th91jc7ug"/><stop offset="1" class="ie_zhnb_p"/></radialGradient><radialGradient id="iJHp0ib" cx="0" cy="0" r="1" gradientTransform="rotate(125.134 1.407 4.081)scale(.51586)" gradientUnits="userSpaceOnUse"><stop class="sm19dz-lq"/><stop offset="1" class="vmakcsq1y"/></radialGradient><filter id="im31Cfe" width="17.652" height="11.83" x="8.967" y="4.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation="1.25"/></filter><filter id="ihBdhUc" width="4.619" height="17.345" x="25.131" y="11.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation=".75"/></filter><filter id="iCT0Itl" width="4.797" height="21.75" x="6.578" y="6.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation=".5"/></filter><filter id="iO9eSiM" width="5.844" height="10.719" x="23.406" y="19.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation=".5"/></filter><filter id="iaLwLje" width="6" height="15.125" x="7.5" y="16.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation="1.25"/></filter><filter id="ixumFdd" width="5.375" height="6.438" x="5.531" y="23.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation=".5"/></filter><filter id="iIGdgnb" width="2.583" height=".7" x="2.189" y="8.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation=".125"/></filter><filter id="iUuHMec" width=".722" height=".722" x="4.018" y="8.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1525" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:gorilla" /></template>
<style>
.a5w4p81ec {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M2.54 8.951h1.882");
}

.a68yjcdmc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M24.656 21.006v2.695a6 6 0 0 0 2.35 4.763l.994.76");
}

.aabm5ab7p {
  stop-color: var(--svg-color--4b4750, #4B4750);
  stop-opacity: 0;
}

.avobd3kro {
  stop-color: var(--svg-color--b8b8ca, #B8B8CA);
  stop-opacity: 0;
}

.b8erv2bsc {
  d: path("M14.01 29.477c.041.217-.142.398-.363.398H10.69v-2.11h1.005c1.249 0 2.127.734 2.314 1.712");
}

.bj4kcdbld {
  stop-color: var(--svg-color--8a898c, #8A898C);
  stop-opacity: 0;
}

.c8ik61cpo {
  stop-color: var(--svg-color--8a898c, #8A898C);
}

.c8mpzcwuv {
  d: path("M28.55 29.875h-4.81c-.138 0-.252-.113-.235-.25a2.11 2.11 0 0 1 2.095-1.86h3.94v1.11c.01.55-.44 1-.99 1");
}

.cbgt__bps {
  d: path("M5.371 5.876a.474.474 0 1 0 0-.948a.474.474 0 0 0 0 .948");
}

.cfxas3b2w {
  stop-color: var(--svg-color--565060, #565060);
}

.ctz-iy-wu {
  stop-color: var(--svg-color--49454f, #49454F);
  stop-opacity: 0;
}

.d_jc1q9bb {
  d: path("M23.651 22.214c.165-.379.223-.802.157-1.222a1.47 1.47 0 0 0-.39-.787l-.065-.07c-.388-.405-.946-.594-1.507-.572c-3.247.126-5.945-1.281-7.346-2.646c-.292-.285-.672-.473-1.08-.473c-.748 0-1.356.607-1.356 1.356v4.253h.001v-1.168c1.24 1.96 3.4 3.26 5.89 3.26c2.247 0 4.377-.824 5.696-1.931");
}

.dl214rp3m {
  stop-color: var(--svg-color--94899f, #94899F);
}

.dqm4midsh {
  stop-color: var(--svg-color--782bba, #782BBA);
}

.ezqs4pheh {
  stop-color: var(--svg-color--782bba, #782BBA);
  stop-opacity: 0;
}

.fbjq0su5e {
  stop-color: var(--svg-color--e09eff, #E09EFF);
}

.fe5b8fb1d {
  d: path("M29.54 19.844h-5.879v3.983c0 2.96 1.948 5.52 4.758 6.04c.559.067 1.121-.297 1.121-1.05z");
}

.fibjm-c2s {
  stop-color: var(--svg-color--9c9c9e, #9C9C9E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.go72zmmim {
  d: path("M11.564 29.875a.5.5 0 0 0 .5-.5V17.819l-5.939 3v3.006c0 4.65 2 6.05 4.81 6.05z");
}

.hs9_tsq5k {
  stop-color: var(--svg-color--8b72a5, #8B72A5);
  stop-opacity: 0;
}

.hsv73e5-f {
  stop-color: var(--svg-color--353239, #353239);
}

.hx3bebcev {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M2.5 9.166h1.705");
}

.i3vabvstq {
  stop-color: var(--svg-color--9c9c9e, #9C9C9E);
}

.i5aiy6bsa {
  stop-color: var(--svg-color--dc8fff, #DC8FFF);
  stop-opacity: 0;
}

.ie_zhnb_p {
  stop-color: var(--svg-color--8b3ad1, #8B3AD1);
}

.if79bys7v {
  d: path("M27.035 11.195c-1.33-.99-2.49-1.04-3.56-.84v-.01c-.01 0-.02.01-.03.01c-.07.01-.14.04-.21.06c-1.08.31-2.21.284-2.81.21c-1.523-.186-2.562-1.244-3.527-2.345c-1.31-1.67-3.517-2.801-5.867-2.461c-5.102.738-4.878 5.466-4.906 6.426v11.58c0 4.65 2 6.05 4.81 6.05h.63a.5.5 0 0 0 .5-.5v-8.49c1.24 1.96 3.4 3.26 5.89 3.26c2.25 0 4.383-.826 5.701-1.936v1.616c0 2.96 1.948 5.52 4.758 6.04c.559.067 1.121-.296 1.121-1.05v-12.45c-.01-2.02-.89-3.97-2.5-5.17");
}

.iwxzu_b3g {
  stop-color: var(--svg-color--5d5667, #5D5667);
  stop-opacity: 0;
}

.j28r3nlvv {
  stop-color: var(--svg-color--b8b8ca, #B8B8CA);
}

.jnfp8ob_e {
  stop-color: var(--svg-color--98979a, #98979A);
}

.jy3_cwzjf {
  stop-color: var(--svg-color--b0afb2, #B0AFB2);
}

.k3c_pi7nu {
  stroke-linecap: round;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M28 27.281V16.594c0-1.576-.545-2.563-1.119-3.158");
}

.kc7ochpyp {
  stop-color: var(--svg-color--27242b, #27242B);
}

.kd8jyjbki {
  stop-color: var(--svg-color--a7a6a9, #A7A6A9);
}

.l6__2hsxb {
  stroke-linecap: round;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.828 27.281v-15.12c0-3.286 1.703-3.88 2.297-4.13");
}

.lgcnr-bwf {
  stop-color: var(--svg-color--b9b9ba, #B9B9BA);
}

.m0k7zpb2m {
  stop-color: var(--svg-color--9c9ea0, #9C9EA0);
  stop-opacity: 0;
}

.m34aaxg1g {
  stop-color: var(--svg-color--836b9b, #836B9B);
}

.m7v0eqbbm {
  stop-color: var(--svg-color--bdb4c9, #BDB4C9);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n0szxubcv {
  stop-color: var(--svg-color--878391, #878391);
}

.ne3vcqb_o {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M27.035 11.195c-1.33-.99-2.49-1.04-3.56-.84v-.01c-.01 0-.02.01-.03.01c-.07.01-.14.04-.21.06c-1.08.31-2.21.284-2.81.21c-1.523-.186-2.562-1.244-3.527-2.345c-1.31-1.67-3.517-2.801-5.867-2.461c-5.102.738-4.878 5.466-4.906 6.426v11.58c0 4.65 2 6.05 4.81 6.05h.63a.5.5 0 0 0 .5-.5v-8.49c1.24 1.96 3.4 3.26 5.89 3.26c2.25 0 4.383-.826 5.701-1.936v1.616c0 2.96 1.948 5.52 4.758 6.04c.559.067 1.121-.296 1.121-1.05v-12.45c-.01-2.02-.89-3.97-2.5-5.17");
}

.nu0dfpdww {
  stop-color: var(--svg-color--818199, #818199);
  stop-opacity: 0;
}

.nuecyp9xg {
  stop-color: var(--svg-color--d0bfe1, #D0BFE1);
}

.o67r5wbic {
  stroke-linecap: round;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M23.719 12.907c-1.778.688-5.735.57-7.999-2.344c-1.379-1.775-2.126-3.338-3.853-3.338");
}

.o6b9gqfwz {
  stop-color: var(--svg-color--49454f, #49454F);
}

.ock3xybnw {
  stop-color: var(--svg-color--3e3b42, #3E3B42);
}

.op-a1yb2c {
  stop-color: var(--svg-color--5e5e61, #5E5E61);
  stop-opacity: 0;
}

.oxaxplblj {
  d: path("M5.698 12.725a3.198 3.198 0 1 0 0-6.395a3.198 3.198 0 0 0 0 6.395");
}

.p1ev7s5kb {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M27.035 11.195c-1.33-.99-2.49-1.04-3.56-.84v-.01c-.01 0-.02.01-.03.01c-.07.01-.14.04-.21.06c-1.08.31-2.21.284-2.81.21c-1.523-.186-2.562-1.244-3.527-2.345c-1.31-1.67-3.517-2.801-5.867-2.461c-5.102.738-4.878 5.466-4.906 6.426v11.58c0 4.65 2 6.05 4.81 6.05h.63a.5.5 0 0 0 .5-.5v-8.49c1.24 1.96 3.4 3.26 5.89 3.26c2.25 0 4.383-.826 5.701-1.936v1.616c0 2.96 1.948 5.52 4.758 6.04c.559.067 1.121-.296 1.121-1.05v-12.45c-.01-2.02-.89-3.97-2.5-5.17");
}

.q96gxkddq {
  stop-color: var(--svg-color--8b72a5, #8B72A5);
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r595czxld {
  cx: 4.379px;
  cy: 9.055px;
  r: 0.161px;
  fill: var(--svg-color--9c9c9e, #9C9C9E);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
}

.rf6di7b3f {
  stop-color: var(--svg-color--5e5e61, #5E5E61);
}

.s-mozwu8j {
  stop-color: var(--svg-color--bdb4c9, #BDB4C9);
  stop-opacity: 0;
}

.sdm-ndbrp {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.781 24.975c-.01 1.104.55 3.437 2.875 3.937");
}

.shox5uk4r {
  stop-color: var(--svg-color--9c9ea0, #9C9EA0);
}

.sm19dz-lq {
  stop-color: var(--svg-color--695c5e, #695C5E);
}

.th91jc7ug {
  stop-color: var(--svg-color--9b53d9, #9B53D9);
  stop-opacity: 0;
}

.txmocabtv {
  stop-color: var(--svg-color--564f60, #564F60);
}

.txof9obun {
  stop-color: var(--svg-color--9e9d9f, #9E9D9F);
}

.vfy8vbv6t {
  stop-color: var(--svg-color--a64bf5, #A64BF5);
}

.vmakcsq1y {
  stop-color: var(--svg-color--3f293a, #3F293A);
}

.vmvlmobft {
  stop-color: var(--svg-color--7a5c99, #7A5C99);
}

.vnxo6lb0j {
  stop-color: var(--svg-color--787980, #787980);
}

.x-prdacty {
  d: path("M11.27 3.725a3.071 3.071 0 0 0-5.63-.01c-.16.37-1.73 3.66-1.73 5c0 2.51 2.03 4.54 4.54 4.54s4.54-2.03 4.54-4.54c0-1.34-1.56-4.62-1.72-4.99");
}

.xra70j_um {
  stop-color: var(--svg-color--9042d5, #9042D5);
}

.ybui-o2jf {
  stroke-linecap: round;
  stroke-opacity: 0.4;
  d: path("M10.5 28.662v-9.125");
}

.z2pcl-bvf {
  d: path("M5.371 6.96a1.369 1.369 0 1 0 0-2.738a1.369 1.369 0 0 0 0 2.737");
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zc8l7b8-k {
  stop-color: var(--svg-color--353239, #353239);
  stop-opacity: 0;
}

.zcchowbby {
  stop-color: var(--svg-color--b9b9ba, #B9B9BA);
  stop-opacity: 0;
}

</style>
