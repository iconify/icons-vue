<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p472stlyl"/><path fill="url(#iuU3yUb)" class="jxrt4w04u"/><path fill="url(#izXVCFK)" class="g526egmgv"/><path fill="url(#i1lUl9d)" class="g526egmgv"/><path fill="url(#ih1S2Ke)" class="g526egmgv"/><path fill="url(#ii1J2Zd)" class="mn3apetpj"/><path class="sl7eh7blp"/><path fill="url(#iQZ59Cc)" class="jp9gpjbkc"/><path fill="url(#iBUNSTd)" class="jp9gpjbkc"/><path fill="url(#iuMrWJd)" class="jp9gpjbkc"/><path fill="url(#ixF0lqx)" class="jp9gpjbkc"/><path fill="url(#in1BPGd)" class="vjfgct3od"/><path fill="url(#ixkFLhd)" class="vjfgct3od"/><path fill="url(#iLvzJpn)" class="vjfgct3od"/><path fill="url(#i7FO6Pd)" class="vjfgct3od"/><path fill="url(#iAK8rwd)" class="vjfgct3od"/><path fill="url(#ieRaoqc)" class="czsha9grg"/><path fill="url(#i9ob9zc)" class="czsha9grg"/><path fill="url(#i3Th1Yd)" class="czsha9grg"/><path fill="url(#ijs9D1b)" class="czsha9grg"/><path fill="url(#izevsPd)" class="weiya1b2l"/><path fill="url(#iqmzMNe)" class="weiya1b2l"/><path fill="url(#iS4i8Lc)" class="weiya1b2l"/><path fill="url(#iKUsiQc)" class="r633tsbcg"/><path fill="url(#iF2YS4b)" class="r633tsbcg"/><path fill="url(#iVlj67d)" class="r633tsbcg"/><path fill="url(#ifLHwec)" class="jup-d8ndn"/><path fill="url(#iNjhNzd)" class="jup-d8ndn"/><g filter="url(#iPPrsKy)"><path stroke="url(#i0gfOcd)" class="t7-in3g0u"/></g><path class="bages52lg"/><path fill="url(#ilid1lc)" class="khkpl7zow"/><path fill="url(#iNcZWge)" class="khkpl7zow"/><path fill="url(#ita6yJb)" class="pwq730bpu"/><path class="xxi120vcc"/><path class="e-n_6ub0e"/><path class="dude-8i0z"/><path fill="url(#iQZfwIs)" class="va-frtb-c"/><path class="apnv38eoy"/><path fill="url(#iDH6soo)" class="o32yj-bct"/><g filter="url(#ix5jAtb)"><rect class="n2uy4dbem"/></g><rect fill="url(#iX1zPzc)" class="ccqtotgbv"/><g filter="url(#inIIgFb)"><path stroke="url(#iGMCIBz)" class="ljm36wb8a"/></g><g filter="url(#iiR8WMd)"><path stroke="url(#ibOdzrv)" class="bi-h8abzi"/></g><g filter="url(#ieulead)"><path stroke="url(#iOzOnec)" class="f1g1mybak"/></g><g filter="url(#iTC1sbU)"><path stroke="url(#iX0pRSb)" class="cyhtbd6ew"/></g><path fill="url(#iq7Rd6x)" class="zxv4jwbou"/><path fill="url(#ifsez3b)" class="zxv4jwbou"/><path fill="url(#iTKqkIe)" class="zxv4jwbou"/><g filter="url(#iL8Ed4c)"><ellipse fill="url(#iK6BS2d)" transform="rotate(-30.695 24.279 16.684)" class="lew07lzmu"/></g><g filter="url(#idite0b)"><path class="oei0m2b8t"/></g><circle class="l4s8bhb4m"/><defs><linearGradient id="iuU3yUb" x1="26.694" x2="28.229" y1="17.938" y2="17.938" gradientUnits="userSpaceOnUse"><stop class="hoerrobht"/><stop offset="1" class="rf80cbchs"/></linearGradient><linearGradient id="izXVCFK" x1="25.51" x2="27.169" y1="23.548" y2="23.548" gradientUnits="userSpaceOnUse"><stop offset=".207" class="zjsvaac5f"/><stop offset="1" class="lvlglo3ob"/></linearGradient><linearGradient id="i1lUl9d" x1="25.667" x2="27.169" y1="25.906" y2="24.125" gradientUnits="userSpaceOnUse"><stop offset=".207" class="zjsvaac5f"/><stop offset="1" class="lvlglo3ob"/></linearGradient><linearGradient id="ih1S2Ke" x1="25.731" x2="26.545" y1="16.455" y2="18.274" gradientUnits="userSpaceOnUse"><stop class="f5vv2nr8h"/><stop offset="1" class="p76xxsy0t"/></linearGradient><linearGradient id="ii1J2Zd" x1="29.104" x2="29.104" y1="27.313" y2="24.5" gradientUnits="userSpaceOnUse"><stop class="uk0_wpacj"/><stop offset="1" class="wx-3gyges"/></linearGradient><linearGradient id="iQZ59Cc" x1="11.635" x2="13.056" y1="21.469" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="zjsvaac5f"/><stop offset="1" class="w4a1r0_dn"/></linearGradient><linearGradient id="iBUNSTd" x1="12.832" x2="12.832" y1="30.438" y2="28.656" gradientUnits="userSpaceOnUse"><stop class="w7jggcbbn"/><stop offset="1" class="ibpyn9bnj"/></linearGradient><linearGradient id="iuMrWJd" x1="15.507" x2="13.925" y1="25.688" y2="26.415" gradientUnits="userSpaceOnUse"><stop class="duu0fib-o"/><stop offset="1" class="m05bcr4_s"/></linearGradient><linearGradient id="ixF0lqx" x1="10.26" x2="12.617" y1="23.656" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="duu0fib-o"/><stop offset="1" class="m05bcr4_s"/></linearGradient><linearGradient id="in1BPGd" x1="21.524" x2="18.763" y1="21.063" y2="30.697" gradientUnits="userSpaceOnUse"><stop class="zjsvaac5f"/><stop offset="1" class="w4a1r0_dn"/></linearGradient><linearGradient id="ixkFLhd" x1="20.604" x2="19.604" y1="22.938" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="duu0fib-o"/><stop offset="1" class="m05bcr4_s"/></linearGradient><linearGradient id="iLvzJpn" x1="20.838" x2="19.604" y1="27.578" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="duu0fib-o"/><stop offset="1" class="m05bcr4_s"/></linearGradient><linearGradient id="i7FO6Pd" x1="16.854" x2="17.667" y1="26.141" y2="26.563" gradientUnits="userSpaceOnUse"><stop class="duu0fib-o"/><stop offset=".83" class="m05bcr4_s"/></linearGradient><linearGradient id="iAK8rwd" x1="18.51" x2="18.51" y1="30.438" y2="28.656" gradientUnits="userSpaceOnUse"><stop class="w7jggcbbn"/><stop offset="1" class="ibpyn9bnj"/></linearGradient><linearGradient id="i9ob9zc" x1="27.354" x2="14.109" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="plcltqw7z"/><stop offset=".311" class="o7-4khdrm"/></linearGradient><linearGradient id="i3Th1Yd" x1="13.198" x2="13.198" y1="30.625" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="w7jggcbbn"/><stop offset="1" class="ibpyn9bnj"/></linearGradient><linearGradient id="izevsPd" x1="5.213" x2="5.37" y1="18.313" y2="16.766" gradientUnits="userSpaceOnUse"><stop class="kr3mlwnss"/><stop offset="1" class="a70oymw9w"/></linearGradient><linearGradient id="iqmzMNe" x1="7.104" x2="5.995" y1="18.313" y2="16.813" gradientUnits="userSpaceOnUse"><stop offset=".073" class="cztpc7bcq"/><stop offset=".715" class="pz622haub"/></linearGradient><linearGradient id="iS4i8Lc" x1="4.042" x2="6.459" y1="10.688" y2="11.595" gradientUnits="userSpaceOnUse"><stop class="hefw-7b0q"/><stop offset="1" class="hv8ztze2s"/></linearGradient><linearGradient id="iKUsiQc" x1="16.76" x2="16.76" y1="24.582" y2="22.719" gradientUnits="userSpaceOnUse"><stop class="v5bz8x9av"/><stop offset="1" class="u2wuoe60f"/></linearGradient><linearGradient id="iF2YS4b" x1="20.213" x2="18.932" y1="23.984" y2="23.578" gradientUnits="userSpaceOnUse"><stop class="tbeduhw0r"/><stop offset="1" class="jr4xwqrui"/></linearGradient><linearGradient id="iVlj67d" x1="11.042" x2="12.635" y1="24.582" y2="24" gradientUnits="userSpaceOnUse"><stop class="tbeduhw0r"/><stop offset="1" class="jr4xwqrui"/></linearGradient><linearGradient id="ifLHwec" x1="6.289" x2="8.479" y1="20.188" y2="20.188" gradientUnits="userSpaceOnUse"><stop class="dta8o5brs"/><stop offset="1" class="mor28ut6h"/></linearGradient><linearGradient id="iNjhNzd" x1="7.729" x2="7.729" y1="24.594" y2="21.488" gradientUnits="userSpaceOnUse"><stop class="qewncpb8y"/><stop offset="1" class="kkv8zzkpx"/></linearGradient><linearGradient id="i0gfOcd" x1="12.969" x2="12.969" y1="9.063" y2="16.375" gradientUnits="userSpaceOnUse"><stop class="law9irbvh"/><stop offset="1" class="i_1jmbbrs"/></linearGradient><linearGradient id="ilid1lc" x1="1.667" x2="4.491" y1="15.295" y2="15.295" gradientUnits="userSpaceOnUse"><stop class="dta8o5brs"/><stop offset="1" class="mor28ut6h"/></linearGradient><linearGradient id="iNcZWge" x1="3.902" x2="3.902" y1="17.654" y2="15.77" gradientUnits="userSpaceOnUse"><stop class="qewncpb8y"/><stop offset="1" class="kkv8zzkpx"/></linearGradient><linearGradient id="iQZfwIs" x1="22.054" x2="22.197" y1="16.05" y2="19.431" gradientUnits="userSpaceOnUse"><stop class="jjjhpdenh"/><stop offset="1" class="to5twtbls"/></linearGradient><linearGradient id="iDH6soo" x1="12.76" x2="10.854" y1="12.688" y2="13.938" gradientUnits="userSpaceOnUse"><stop class="jjjhpdenh"/><stop offset="1" class="to5twtbls"/></linearGradient><linearGradient id="iGMCIBz" x1="25.478" x2="25.478" y1="17.719" y2="22.427" gradientUnits="userSpaceOnUse"><stop class="bih3dd--i"/><stop offset="1" class="qt6r38bbw"/></linearGradient><linearGradient id="ibOdzrv" x1="10.718" x2="10.718" y1="25.406" y2="32.438" gradientUnits="userSpaceOnUse"><stop class="y6-l7nbdr"/><stop offset="1" class="i_1jmbbrs"/></linearGradient><linearGradient id="iOzOnec" x1="13.672" x2="14.916" y1="25.406" y2="30.016" gradientUnits="userSpaceOnUse"><stop class="y6-l7nbdr"/><stop offset="1" class="i_1jmbbrs"/></linearGradient><linearGradient id="iX0pRSb" x1="25.482" x2="24.174" y1="26.286" y2="30.21" gradientUnits="userSpaceOnUse"><stop class="bih3dd--i"/><stop offset="1" class="qt6r38bbw"/></linearGradient><linearGradient id="iq7Rd6x" x1="3.704" x2="2.774" y1="14.789" y2="14.789" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="ifsez3b" x1="4.066" x2="4.066" y1="15.854" y2="15.018" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iTKqkIe" x1="1.452" x2="2.772" y1="15.221" y2="15.221" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset=".84" class="zmzak_sfz"/></linearGradient><filter id="iPPrsKy" width="8.426" height="9.375" x="8.824" y="8.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".375"/></filter><filter id="ix5jAtb" width="1.799" height="2.616" x="5.498" y="12.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".25"/></filter><filter id="inIIgFb" width="4.988" height="8.731" x="21.866" y="14.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".625"/></filter><filter id="iiR8WMd" width="1.8" height="6.3" x="9.329" y="23.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".3"/></filter><filter id="ieulead" width="3.017" height="6.581" x="12.284" y="23.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".3"/></filter><filter id="iTC1sbU" width="4.758" height="8.266" x="21.784" y="22.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".625"/></filter><filter id="iL8Ed4c" width="4.604" height="4.196" x="21.977" y="14.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".5"/></filter><filter id="idite0b" width="4.281" height="11.594" x="25.573" y="15.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2357" stdDeviation=".375"/></filter><radialGradient id="ieRaoqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.6315 -15.9682 0 17.23 11.25)" gradientUnits="userSpaceOnUse"><stop class="bfkqanb2b"/><stop offset=".889" class="l84v7mbsk"/></radialGradient><radialGradient id="ijs9D1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 1.21875 -2.40447 3.26762 7.98 26.469)" gradientUnits="userSpaceOnUse"><stop class="x7hc4h67b"/><stop offset="1" class="mr581w0dn"/></radialGradient><radialGradient id="ita6yJb" cx="0" cy="0" r="1" gradientTransform="matrix(1 -1 1 1 9.104 10)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="amb2ddcyl"/><stop offset="1" class="o14s83ldd"/></radialGradient><radialGradient id="iX1zPzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.28255 0 0 -1.16952 6.76 13.98)" gradientUnits="userSpaceOnUse"><stop class="mqpbk469p"/><stop offset="1" class="bp2mrabfz"/></radialGradient><radialGradient id="iK6BS2d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41242 .28536 -.17894 -1.51278 26.244 16.758)" gradientUnits="userSpaceOnUse"><stop class="wwjtzqe7n"/><stop offset="1" class="awujcsbjg"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leopard" /></template>
<style>
.a70oymw9w {
  stop-color: var(--svg-color--e08539, #E08539);
  stop-opacity: 0;
}

.amb2ddcyl {
  stop-color: var(--svg-color--ffe6a9, #FFE6A9);
}

.apnv38eoy {
  fill: var(--svg-color--855b51, #855B51);
  d: path("M16.744 15c.16.58.68 1 1.31 1s1.15-.42 1.31-1z");
}

.awujcsbjg {
  stop-color: var(--svg-color--ffe38b, #FFE38B);
  stop-opacity: 0;
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bages52lg {
  fill: var(--svg-color--ffdea3, #FFDEA3);
  d: path("M2.104 15.26c0 1.26.85 2.31 2 2.64v-4.26c0 .2-.16.36-.36.36h-.742");
}

.bfkqanb2b {
  stop-color: var(--svg-color--ffd14f, #FFD14F);
}

.bi-h8abzi {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M10.23 24.25v4.5");
}

.bih3dd--i {
  stop-color: var(--svg-color--ffd967, #FFD967);
}

.bp2mrabfz {
  stop-color: var(--svg-color--3b2439, #3B2439);
}

.ccqtotgbv {
  width: 0.969px;
  height: 1.96px;
  x: 6.135px;
  y: 13px;
  rx: 0.484px;
}

.cyhtbd6ew {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m25.042 23.656l-1.758 5.266");
}

.czsha9grg {
  d: path("M2.104 15.26c0 1.51 1.23 2.74 2.74 2.74h.76a.5.5 0 0 1 .5.5v1.92c0 1.18.576 2.233 1.464 2.887c.305.225.526.562.526.941V27.5c0 .276-.237.49-.48.622a.98.98 0 0 0-.51.858v.6c0 .23.19.42.42.42h3.25c.17 0 .31-.14.31-.31V24.5a.5.5 0 0 1 .5-.5h7.666a1 1 0 0 1 .707.293l1.698 1.698a1 1 0 0 1 .26.967l-.224.83a.29.29 0 0 1-.277.212c-.48 0-.9.33-1.01.79l-.2.8c-.05.21.11.41.33.41h3.22c.22 0 .41-.14.47-.34l1.5-4.5c.15-.46.26-.94.32-1.43c0-.02 0-.04.01-.05c0-.02 0-.03.01-.05c0-.02 0-.04.01-.06c0-.04.01-.08.01-.12c0-.03.01-.07.01-.1c0-.04.01-.08.01-.12s0-.08.01-.13v-6.14c0-.44-.14-.86-.41-1.2c-.38-.48-.95-.76-1.56-.76h-8.75a4.3 4.3 0 0 1-2.36-.71a4.29 4.29 0 0 1-1.94-3.59V9.5c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.5h-.35a3.64 3.64 0 0 0-3.64 3.64c0 .2-.16.36-.36.36h-.64");
}

.cztpc7bcq {
  stop-color: var(--svg-color--fca83f, #FCA83F);
}

.dta8o5brs {
  stop-color: var(--svg-color--ffe3bf, #FFE3BF);
}

.dude-8i0z {
  fill: var(--svg-color--8d605a, #8D605A);
  d: path("M14.054 18.05a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.duu0fib-o {
  stop-color: var(--svg-color--c14100, #C14100);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e-n_6ub0e {
  fill: var(--svg-color--8a5b5b, #8A5B5B);
  d: path("M21.694 21.18a.59.59 0 1 0 0-1.18a.59.59 0 0 0 0 1.18");
}

.f1g1mybak {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m13.184 24.547l1.217 4.781");
}

.f5vv2nr8h {
  stop-color: var(--svg-color--ffad3a, #FFAD3A);
}

.ft5dv1b6b {
  fill: none;
}

.g526egmgv {
  d: path("M26.104 24c0 1.65 1.35 3 3 3c.55 0 1-.45 1-1s-.45-1-1-1s-1-.45-1-1v-6q0-.111-.008-.219c-.072-.986-1.108-1.472-2.096-1.472h-1.765v.69l.05.001h.82c.55 0 1 .45 1 1z");
}

.hefw-7b0q {
  stop-color: var(--svg-color--ffcf86, #FFCF86);
}

.hoerrobht {
  stop-color: var(--svg-color--ffaa35, #FFAA35);
}

.hv8ztze2s {
  stop-color: var(--svg-color--ffcf86, #FFCF86);
  stop-opacity: 0;
}

.i_1jmbbrs {
  stop-color: var(--svg-color--ffe183, #FFE183);
  stop-opacity: 0;
}

.ibpyn9bnj {
  stop-color: var(--svg-color--e3843d, #E3843D);
  stop-opacity: 0;
}

.jjjhpdenh {
  stop-color: var(--svg-color--845452, #845452);
}

.jp9gpjbkc {
  d: path("m15.494 29.61l-1.89-7.09h-3l1.34 5.023c.072.268-.11.538-.294.745a.8.8 0 0 0-.196.402l-.17.98c-.03.17.1.33.28.33h3.63c.21 0 .36-.19.3-.39");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jr4xwqrui {
  stop-color: var(--svg-color--fb9f3b, #FB9F3B);
  stop-opacity: 0;
}

.jup-d8ndn {
  d: path("M8.094 25v-5.01c0-1.1-.89-1.99-1.99-1.99l-1.62-.024q.177.024.36.024h.76a.5.5 0 0 1 .5.5v1.92c0 1.18.576 2.233 1.464 2.887c.305.225.526.562.526.941z");
}

.jxrt4w04u {
  d: path("M29.104 27c-1.65 0-3-1.35-3-3v-6c0-.55-.45-1-1-1h-.82c-.55 0-1-.45-1-1s.45-1 1-1h.82c1.65 0 3 1.35 3 3v6c0 .55.45 1 1 1s1 .45 1 1s-.45 1-1 1");
}

.khkpl7zow {
  d: path("M2.104 15.26c0 1.26.85 2.31 2 2.64v-4.26c0 .2-.16.36-.36.36h-.742");
}

.kkv8zzkpx {
  stop-color: var(--svg-color--edbaab, #EDBAAB);
  stop-opacity: 0;
}

.kr3mlwnss {
  stop-color: var(--svg-color--cd752b, #CD752B);
}

.l4s8bhb4m {
  cx: 18.02px;
  cy: 18.625px;
  r: 1.344px;
  fill: var(--svg-color--845452, #845452);
}

.l84v7mbsk {
  stop-color: var(--svg-color--fa9e3b, #FA9E3B);
}

.law9irbvh {
  stop-color: var(--svg-color--ffe285, #FFE285);
}

.lew07lzmu {
  cx: 24.279px;
  cy: 16.684px;
  rx: 1.4px;
  ry: 0.969px;
}

.ljm36wb8a {
  stroke-linecap: round;
  d: path("M25.104 21.356v-3.812c0-1.072-.75-1.419-1.488-1.419");
}

.lvlglo3ob {
  stop-color: var(--svg-color--ffa43d, #FFA43D);
  stop-opacity: 0;
}

.m05bcr4_s {
  stop-color: var(--svg-color--c14100, #C14100);
  stop-opacity: 0;
}

.mn3apetpj {
  d: path("M29.104 27c.55 0 1-.45 1-1s-.45-1-1-1s-1-.45-1-1v2.83a3 3 0 0 0 1 .17");
}

.mor28ut6h {
  stop-color: var(--svg-color--f0c0a7, #F0C0A7);
}

.mqpbk469p {
  stop-color: var(--svg-color--67545f, #67545F);
}

.mr581w0dn {
  stop-color: var(--svg-color--fbb15e, #FBB15E);
  stop-opacity: 0;
}

.n2uy4dbem {
  width: 0.799px;
  height: 1.616px;
  x: 5.998px;
  y: 13.172px;
  fill: var(--svg-color--bd702d, #BD702D);
  rx: 0.399px;
}

.o14s83ldd {
  stop-color: var(--svg-color--f1b187, #F1B187);
}

.o32yj-bct {
  d: path("M12.054 14.96c.46 0 .88-.22 1.13-.57c-.05-.03-.11-.06-.16-.1c-.74-.49-1.3-1.19-1.62-1.99a1.408 1.408 0 0 0 .65 2.66");
}

.o7-4khdrm {
  stop-color: var(--svg-color--ffd55d, #FFD55D);
  stop-opacity: 0;
}

.oei0m2b8t {
  stroke: var(--svg-color--ffde77, #FFDE77);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M26.448 16.094c.323.093.969.587.969 1.812v6.313c.02.468.362 1.468 1.562 1.718");
}

.p472stlyl {
  fill: var(--svg-color--ffb000, #FFB000);
  d: path("m15.494 29.61l-1.89-7.09h-3l1.47 5.51a.84.84 0 0 0-.62.66l-.17.98c-.03.17.1.33.28.33h3.63c.21 0 .36-.19.3-.39");
}

.p76xxsy0t {
  stop-color: var(--svg-color--ffad3a, #FFAD3A);
  stop-opacity: 0;
}

.plcltqw7z {
  stop-color: var(--svg-color--ffd55d, #FFD55D);
}

.pwq730bpu {
  d: path("M10.104 10v-.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5v.5z");
}

.pz622haub {
  stop-color: var(--svg-color--fca83f, #FCA83F);
  stop-opacity: 0;
}

.qewncpb8y {
  stop-color: var(--svg-color--edbaab, #EDBAAB);
}

.qt6r38bbw {
  stop-color: var(--svg-color--ffd967, #FFD967);
  stop-opacity: 0;
}

.r633tsbcg {
  d: path("M20.543 22.893c.166-.663-.335-1.34-1.019-1.34h-9.248l.805 3.029c.005-.377.203-.539.46-.576h7.709c.265 0 .577.1.874.447c.136-.407.274-.982.419-1.56");
}

.rf80cbchs {
  stop-color: var(--svg-color--fec45a, #FEC45A);
}

.sl7eh7blp {
  fill: var(--svg-color--ffb000, #FFB000);
  d: path("M18.544 22.52L17.074 28h-.08c-.4 0-.75.29-.82.69l-.17.95c-.03.19.11.36.3.36h2.84c.23 0 .42-.15.48-.37l1.9-7.11z");
}

.t7-in3g0u {
  stroke-linecap: round;
  d: path("M10.125 9.5c-.156 1.781-.037 3.775 1.563 5.375c1.062 1.063 3.124 1.5 4.312 1.5");
}

.tbeduhw0r {
  stop-color: var(--svg-color--fb9f3b, #FB9F3B);
}

.to5twtbls {
  stop-color: var(--svg-color--a57c75, #A57C75);
}

.u2wuoe60f {
  stop-color: var(--svg-color--de7c3a, #DE7C3A);
  stop-opacity: 0;
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.uk0_wpacj {
  stop-color: var(--svg-color--71374e, #71374E);
}

.v5bz8x9av {
  stop-color: var(--svg-color--de7c3a, #DE7C3A);
}

.va-frtb-c {
  d: path("M22.054 18.05a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.vjfgct3od {
  d: path("m18.544 22.52l-1.45 5.403a.104.104 0 0 1-.1.077c-.4 0-.75.29-.82.69l-.17.95c-.03.19.11.36.3.36h2.84c.23 0 .42-.15.48-.37l1.9-7.11z");
}

.w4a1r0_dn {
  stop-color: var(--svg-color--ffa43d, #FFA43D);
}

.w7jggcbbn {
  stop-color: var(--svg-color--bc6422, #BC6422);
}

.weiya1b2l {
  d: path("M4.844 18c-1.51 0-2.74-1.23-2.74-2.74l1-1.26h.64c.2 0 .36-.16.36-.36A3.64 3.64 0 0 1 7.744 10h.35v-.5c0-.67.437-1.236 1.041-1.429l-.646 7.431L7.042 18z");
}

.wwjtzqe7n {
  stop-color: var(--svg-color--ffebac, #FFEBAC);
}

.wx-3gyges {
  stop-color: var(--svg-color--8f6157, #8F6157);
}

.x7hc4h67b {
  stop-color: var(--svg-color--ffbe73, #FFBE73);
}

.xxi120vcc {
  fill: var(--svg-color--845452, #845452);
  d: path("M14.514 21.18a.59.59 0 1 0 0-1.18a.59.59 0 0 0 0 1.18");
}

.y6-l7nbdr {
  stop-color: var(--svg-color--ffdb6a, #FFDB6A);
}

.zjsvaac5f {
  stop-color: var(--svg-color--da530e, #DA530E);
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.zxv4jwbou {
  d: path("M2.832 14c-.4 0-.72.32-.72.72v.628a.1.1 0 0 0 .168.073l1.337-1.248A.1.1 0 0 0 3.548 14z");
}

</style>
