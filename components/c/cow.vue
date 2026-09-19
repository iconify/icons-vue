<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gn1vkccis"/><path fill="url(#iNu7O6d)" class="jqxn9v7kl"/><path fill="url(#iMKxtHe)" class="jqxn9v7kl"/><g filter="url(#imC5VNe)"><path fill="url(#ioVUKXb)" class="ijisigr1s"/><path fill="url(#iS3w3Db)" class="ijisigr1s"/><path fill="url(#ivofxob)" class="ijisigr1s"/></g><path fill="url(#if6mvme)" class="ydrvfxapf"/><path fill="url(#iGTIQNc)" class="wbmw69bfs"/><path fill="url(#ilP0mme)" class="wbmw69bfs"/><path fill="url(#iwFsxQE)" class="wbmw69bfs"/><path fill="url(#iJqbXDb)" class="wbmw69bfs"/><path fill="url(#iy0tUZd)" class="wbmw69bfs"/><path fill="url(#iQTwIPe)" class="wbmw69bfs"/><path fill="url(#iPHYBwd)" class="wbmw69bfs"/><path fill="url(#i1yOFic)" class="wbmw69bfs"/><path fill="url(#iWX1uqc)" class="z-o07lghe"/><path fill="url(#i8fOUUd)" class="p04t-ybjb"/><path fill="url(#i7UlONp)" class="p04t-ybjb"/><path fill="url(#iwoeYDI)" class="xxl_ufjvs"/><path fill="url(#iQPrxLd)" class="r_60-_b1v"/><path fill="url(#inxBjKd)" class="r_60-_b1v"/><path fill="url(#iiIyWNc)" class="uivqnog9f"/><path fill="url(#imkeJkd)" class="upy2fxbdf"/><path fill="url(#itoSRpd)" class="upy2fxbdf"/><path fill="url(#idHOUDc)" class="k7fkkn_lj"/><path class="ugtrnlbyq"/><path fill="url(#imjPFPc)" class="v69etjbdd"/><path fill="url(#i0Oa9nd)" class="v69etjbdd"/><path fill="url(#iatvYSd)" class="qzpg_4b9i"/><path fill="url(#iVW3Ard)" class="z7vobrb6q"/><path fill="url(#iCOmFtb)" class="ej4p73bid"/><g filter="url(#imdL5qb)"><path fill="url(#ifv6gvd)" class="iwddwnbgf"/></g><path fill="url(#iIa1JBj)" class="o0glwejhv"/><path fill="url(#iNxSibd)" class="nsmvpbcbs"/><path fill="url(#i3YeR6b)" class="n1l8bgbsy"/><path fill="url(#isf1Sub)" class="mkae6imnj"/><path fill="url(#iLwvege)" class="zev3g0beu"/><path fill="url(#iJtDbbc)" class="zev3g0beu"/><path class="nt6_ffb5y"/><path fill="url(#iJpcmee)" class="i4jnvdbhk"/><path fill="url(#iKNwLhd)" class="i4jnvdbhk"/><path fill="url(#i9WA0Ay)" class="i4jnvdbhk"/><path fill="url(#iAaEcQb)" class="e7ofo4lco"/><path fill="url(#iyo4Lgd)" class="e7ofo4lco"/><path fill="url(#icpJF6b)" class="b1eld3b6h"/><g filter="url(#ilmHDvd)"><rect class="dysihlfpp"/></g><rect fill="url(#ixCZTjb)" class="kmyxkible"/><rect fill="url(#iKrRChh)" class="kmyxkible"/><rect fill="url(#ibPVmRw)" class="kmyxkible"/><g filter="url(#i9zyMKc)"><path class="u47hj0jbl"/></g><g filter="url(#iPwQ5Od)"><path fill="url(#i16Dn4c)" class="f6mmj2gkf"/></g><g filter="url(#iNMyUEe)"><path stroke="url(#iVOfemc)" class="pwcquob8l"/></g><g filter="url(#iNNeK3b)"><path stroke="url(#isGLAwc)" class="rs604fbvq"/></g><g filter="url(#iyMJT3c)"><path fill="url(#igUNwWr)" class="p4aho-ttv"/></g><g filter="url(#i0gEuph)"><path fill="url(#iw97OMd)" class="zwd299b_x"/></g><g filter="url(#idiVV2I)"><path fill="url(#ilj4rjc)" class="ak9pwccjn"/></g><g filter="url(#igHgYib)"><path stroke="url(#ihfrrdc)" class="ij2pbj08i"/></g><defs><linearGradient id="iNu7O6d" x1="21.624" x2="22.455" y1="23.766" y2="26.158" gradientUnits="userSpaceOnUse"><stop class="mlt4iruen"/><stop offset="1" class="nwwl4dy4c"/></linearGradient><linearGradient id="iMKxtHe" x1="21.718" x2="21.718" y1="29.573" y2="28.708" gradientUnits="userSpaceOnUse"><stop class="x5ianix4n"/><stop offset="1" class="ohlgprb1g"/></linearGradient><linearGradient id="ioVUKXb" x1="15.595" x2="15.595" y1="19.134" y2="29.124" gradientUnits="userSpaceOnUse"><stop class="h34rt5ymw"/><stop offset="1" class="dyra_0bwn"/></linearGradient><linearGradient id="iS3w3Db" x1="17.125" x2="16.125" y1="21.984" y2="24.547" gradientUnits="userSpaceOnUse"><stop class="mlt4iruen"/><stop offset="1" class="nwwl4dy4c"/></linearGradient><linearGradient id="ivofxob" x1="15.689" x2="15.689" y1="29.75" y2="28.516" gradientUnits="userSpaceOnUse"><stop class="x5ianix4n"/><stop offset="1" class="ohlgprb1g"/></linearGradient><linearGradient id="if6mvme" x1="23.844" x2="18.188" y1="23.766" y2="23.766" gradientUnits="userSpaceOnUse"><stop class="czcv0lbrf"/><stop offset="1" class="ha_7fxbhl"/></linearGradient><linearGradient id="iGTIQNc" x1="17.625" x2="17.625" y1="8.109" y2="30.234" gradientUnits="userSpaceOnUse"><stop class="czyng5bqy"/><stop offset="1" class="pehackbtp"/></linearGradient><linearGradient id="iJqbXDb" x1="19.813" x2="19.813" y1="11.484" y2="7.797" gradientUnits="userSpaceOnUse"><stop class="f37ky2brs"/><stop offset="1" class="ig8sqp_mn"/></linearGradient><linearGradient id="iQTwIPe" x1="18.196" x2="18.196" y1="30.953" y2="27.748" gradientUnits="userSpaceOnUse"><stop class="x5ianix4n"/><stop offset=".796" class="ohlgprb1g"/></linearGradient><linearGradient id="iWX1uqc" x1="15.5" x2="12.5" y1="24.547" y2="24.547" gradientUnits="userSpaceOnUse"><stop class="qsfqb8won"/><stop offset="1" class="dpyyeib6l"/></linearGradient><linearGradient id="i8fOUUd" x1="30.375" x2="30.375" y1="19.922" y2="16.063" gradientUnits="userSpaceOnUse"><stop class="w44hqmbkk"/><stop offset="1" class="jxzpu5u7b"/></linearGradient><linearGradient id="i7UlONp" x1="27.375" x2="28.125" y1="18.078" y2="18" gradientUnits="userSpaceOnUse"><stop class="hffkdxxqc"/><stop offset="1" class="pew6frnzi"/></linearGradient><linearGradient id="iiIyWNc" x1="9.613" x2="9.613" y1="22.359" y2="20.016" gradientUnits="userSpaceOnUse"><stop class="j2fch6-5l"/><stop offset="1" class="hjsde98bq"/></linearGradient><linearGradient id="imkeJkd" x1="28.047" x2="29.266" y1="21.766" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="vu3gnbc9x"/><stop offset="1" class="bqxb0-dut"/></linearGradient><linearGradient id="itoSRpd" x1="28.484" x2="29.124" y1="21.766" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="t0wxo5bmo"/><stop offset="1" class="bqxb0-dut"/></linearGradient><linearGradient id="idHOUDc" x1="29.5" x2="29.124" y1="20.094" y2="20.094" gradientUnits="userSpaceOnUse"><stop class="e6-b92mws"/><stop offset=".453" class="tnubzejbp"/><stop offset="1" class="e6-b92mws"/></linearGradient><linearGradient id="i0Oa9nd" x1="29.234" x2="29.234" y1="26.422" y2="23.969" gradientUnits="userSpaceOnUse"><stop class="pl4x7xb5b"/><stop offset="1" class="fz1rws49h"/></linearGradient><linearGradient id="ifv6gvd" x1="28.906" x2="33.453" y1="24.266" y2="19.796" gradientUnits="userSpaceOnUse"><stop class="hsiqmvppz"/><stop offset="1" class="e4rup4byc"/></linearGradient><linearGradient id="iIa1JBj" x1="25.125" x2="25.125" y1="12.984" y2="16.359" gradientUnits="userSpaceOnUse"><stop class="dh17324sh"/><stop offset="1" class="ho17touts"/></linearGradient><linearGradient id="iNxSibd" x1="13.75" x2="13.75" y1="19.797" y2="16.547" gradientUnits="userSpaceOnUse"><stop class="bhil4cbht"/><stop offset="1" class="smdo9ebed"/></linearGradient><linearGradient id="isf1Sub" x1="20.75" x2="23.215" y1="18.484" y2="19.874" gradientUnits="userSpaceOnUse"><stop class="l20qrjbto"/><stop offset="1" class="s9yrk6_lk"/></linearGradient><linearGradient id="iLwvege" x1="6.766" x2="12.48" y1="5.172" y2="13.48" gradientUnits="userSpaceOnUse"><stop class="xmb07ebsd"/><stop offset=".073" class="ext_6n6sk"/></linearGradient><linearGradient id="iJtDbbc" x1="10.75" x2="10.75" y1="3.703" y2="4.969" gradientUnits="userSpaceOnUse"><stop class="xmb07ebsd"/><stop offset="1" class="c9ozlqb6i"/></linearGradient><linearGradient id="iJpcmee" x1="7.344" x2="8.844" y1="5.828" y2="7.891" gradientUnits="userSpaceOnUse"><stop class="c7r012s9s"/><stop offset="1" class="qigai5upa"/></linearGradient><linearGradient id="iKNwLhd" x1="9.968" x2="9.968" y1="12.114" y2="9.203" gradientUnits="userSpaceOnUse"><stop class="krcylmbtg"/><stop offset="1" class="whw6xlbrn"/></linearGradient><linearGradient id="iyo4Lgd" x1="5.234" x2="4.844" y1="12.359" y2="10.359" gradientUnits="userSpaceOnUse"><stop class="zhs46kbgk"/><stop offset="1" class="uchyrc_vn"/></linearGradient><linearGradient id="ixCZTjb" x1="7.438" x2="6.844" y1="9.274" y2="9.274" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iKrRChh" x1="7.745" x2="7.745" y1="10.475" y2="9.763" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ibPVmRw" x1="6.422" x2="6.859" y1="9.394" y2="9.394" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="i16Dn4c" x1="11.141" x2="8.734" y1="7.453" y2="10.313" gradientUnits="userSpaceOnUse"><stop offset=".321" class="dditoq1jw"/><stop offset=".75" class="zokbf9bxm"/></linearGradient><linearGradient id="iVOfemc" x1="17.031" x2="17.031" y1="28.453" y2="22.391" gradientUnits="userSpaceOnUse"><stop class="a2ztw5tmm"/><stop offset="1" class="zr9xvdbnb"/></linearGradient><linearGradient id="isGLAwc" x1="22.864" x2="22.864" y1="28.414" y2="24.446" gradientUnits="userSpaceOnUse"><stop class="a2ztw5tmm"/><stop offset="1" class="zr9xvdbnb"/></linearGradient><linearGradient id="igUNwWr" x1="12.535" x2="8.48" y1="17.097" y2="19.333" gradientUnits="userSpaceOnUse"><stop class="hsiqmvppz"/><stop offset="1" class="e4rup4byc"/></linearGradient><linearGradient id="iw97OMd" x1="11.431" x2="12.499" y1="29.625" y2="29.36" gradientUnits="userSpaceOnUse"><stop class="hsiqmvppz"/><stop offset="1" class="e4rup4byc"/></linearGradient><linearGradient id="ilj4rjc" x1="27.527" x2="29.273" y1="31.797" y2="31.61" gradientUnits="userSpaceOnUse"><stop class="hsiqmvppz"/><stop offset="1" class="e4rup4byc"/></linearGradient><radialGradient id="ilP0mme" cx="0" cy="0" r="1" gradientTransform="matrix(-5.75 5.5 -4.14893 -4.33752 25.75 12.734)" gradientUnits="userSpaceOnUse"><stop class="hsiqmvppz"/><stop offset="1" class="e4rup4byc"/></radialGradient><radialGradient id="iwFsxQE" cx="0" cy="0" r="1" gradientTransform="matrix(15.0625 -18.99998 13.85477 10.98355 13.438 28.36)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="f37ky2brs"/><stop offset="1" class="ig8sqp_mn"/></radialGradient><radialGradient id="iy0tUZd" cx="0" cy="0" r="1" gradientTransform="rotate(60.751 -5.505 13.004)scale(4.47705 4.48738)" gradientUnits="userSpaceOnUse"><stop class="bqo7-xbuk"/><stop offset="1" class="ec-pibrug"/></radialGradient><radialGradient id="iPHYBwd" cx="0" cy="0" r="1" gradientTransform="rotate(-135.807 12.219 10.865)scale(2.35357 1.79596)" gradientUnits="userSpaceOnUse"><stop class="x5ianix4n"/><stop offset="1" class="ohlgprb1g"/></radialGradient><radialGradient id="i1yOFic" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -5.6875 4.7263 2.83058 20.719 27.672)" gradientUnits="userSpaceOnUse"><stop class="x5ianix4n"/><stop offset="1" class="ohlgprb1g"/></radialGradient><radialGradient id="iwoeYDI" cx="0" cy="0" r="1" gradientTransform="matrix(3.59374 1.8594 -3.62617 7.00847 25.407 15.907)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="pew6frnzi"/><stop offset="1" class="hffkdxxqc"/></radialGradient><radialGradient id="iQPrxLd" cx="0" cy="0" r="1" gradientTransform="rotate(-135 15.255 8.28)scale(9.67853 6.40115)" gradientUnits="userSpaceOnUse"><stop class="qsfqb8won"/><stop offset="1" class="dpyyeib6l"/></radialGradient><radialGradient id="inxBjKd" cx="0" cy="0" r="1" gradientTransform="rotate(-105.866 17.038 5.695)scale(3.08632 8.10203)" gradientUnits="userSpaceOnUse"><stop class="x5ianix4n"/><stop offset="1" class="ohlgprb1g"/></radialGradient><radialGradient id="imjPFPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.54687 -1.81735 0 29.625 24.328)" gradientUnits="userSpaceOnUse"><stop class="n83d-_bcn"/><stop offset="1" class="i7tvr2-ly"/></radialGradient><radialGradient id="iatvYSd" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.21875 -.39725 .19353 9.844 3.634)" gradientUnits="userSpaceOnUse"><stop class="cb4_3cbkw"/><stop offset="1" class="npcqhgb8l"/></radialGradient><radialGradient id="iVW3Ard" cx="0" cy="0" r="1" gradientTransform="matrix(-7.59375 0 0 -4.12917 22.938 14.14)" gradientUnits="userSpaceOnUse"><stop class="d674_jpoz"/><stop offset="1" class="zidv-cbxv"/></radialGradient><radialGradient id="iCOmFtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 11.5156 0 19.055 11.11)" gradientUnits="userSpaceOnUse"><stop class="vlzxxcccm"/><stop offset="1" class="tg__-gbph"/></radialGradient><radialGradient id="i3YeR6b" cx="0" cy="0" r="1" gradientTransform="matrix(5.1525 -2.0872 2.96001 7.30715 6.535 17.634)" gradientUnits="userSpaceOnUse"><stop class="b62r89_4y"/><stop offset="1" class="jqi3v0b1o"/></radialGradient><radialGradient id="i9WA0Ay" cx="0" cy="0" r="1" gradientTransform="rotate(-142.125 8.042 1.196)scale(2.13783 2.39344)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="krcylmbtg"/><stop offset="1" class="whw6xlbrn"/></radialGradient><radialGradient id="iAaEcQb" cx="0" cy="0" r="1" gradientTransform="matrix(3.1575 .46875 -.5523 3.7203 2.188 9.953)" gradientUnits="userSpaceOnUse"><stop class="dimle0bpx"/><stop offset="1" class="i27try1jr"/></radialGradient><radialGradient id="icpJF6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.23438 0 0 2.61888 3.531 9.875)" gradientUnits="userSpaceOnUse"><stop class="uydoy3bkx"/><stop offset=".633" class="zxk13obmj"/></radialGradient><radialGradient id="ihfrrdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.73438 -1.31319 0 29.734 22.516)" gradientUnits="userSpaceOnUse"><stop class="b0s6mmbmi"/><stop offset="1" class="ep6l40bwk"/></radialGradient><filter id="imC5VNe" width="4.09" height="10.14" x="13.625" y="19.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.439216 0 0 0 0 0.572549 0 0 0 0.2 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2940"/></filter><filter id="imdL5qb" width="5.273" height="9.875" x="22.625" y="14.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".5"/></filter><filter id="ilmHDvd" width="1.569" height="2.56" x="6.169" y="7.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".15"/></filter><filter id="i9zyMKc" width="4.568" height="6.511" x="9.985" y="4.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".25"/></filter><filter id="iPwQ5Od" width="3.688" height="6.813" x="8.531" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".5"/></filter><filter id="iNMyUEe" width="2.319" height="7.219" x="14.844" y="22.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".25"/></filter><filter id="iNNeK3b" width="2.422" height="5.156" x="20.516" y="24.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".25"/></filter><filter id="iyMJT3c" width="3.641" height="8.047" x="10.552" y="18.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".5"/></filter><filter id="i0gEuph" width="1.551" height="4.069" x="10.252" y="25.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".3"/></filter><filter id="idiVV2I" width="1.746" height="11.538" x="26.025" y="17.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".3"/></filter><filter id="igHgYib" width=".8" height="3.544" x="28.834" y="22.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2940" stdDeviation=".175"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cow" /></template>
<style>
.a2ztw5tmm {
  stop-color: var(--svg-color--bfb1cd, #BFB1CD);
}

.ak9pwccjn {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M26.625 18.453h.546v10.338h-.546z");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b0s6mmbmi {
  stop-color: var(--svg-color--bab7bc, #BAB7BC);
}

.b1eld3b6h {
  d: path("M3.725 10.46c-.28 0-.5-.22-.5-.5V9.4c0-.28.22-.5.5-.5s.5.22.5.5v.55c0 .28-.22.51-.5.51");
}

.b62r89_4y {
  stop-color: var(--svg-color--7e7c81, #7E7C81);
}

.bhil4cbht {
  stop-color: var(--svg-color--6a6075, #6A6075);
}

.bqo7-xbuk {
  stop-color: var(--svg-color--c4b9d0, #C4B9D0);
}

.bqxb0-dut {
  stop-color: var(--svg-color--bfb0c4, #BFB0C4);
  stop-opacity: 0;
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.c7r012s9s {
  stop-color: var(--svg-color--6e6b71, #6E6B71);
}

.c9ozlqb6i {
  stop-color: var(--svg-color--c4c4c5, #C4C4C5);
  stop-opacity: 0;
}

.cb4_3cbkw {
  stop-color: var(--svg-color--fed9aa, #FED9AA);
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.czcv0lbrf {
  stop-color: var(--svg-color--ca5e6d, #CA5E6D);
}

.czyng5bqy {
  stop-color: var(--svg-color--ddd9e1, #DDD9E1);
}

.d674_jpoz {
  stop-color: var(--svg-color--7d7a83, #7D7A83);
}

.dditoq1jw {
  stop-color: var(--svg-color--97959a, #97959A);
}

.dh17324sh {
  stop-color: var(--svg-color--8f8d91, #8F8D91);
}

.dimle0bpx {
  stop-color: var(--svg-color--e28487, #E28487);
}

.dpyyeib6l {
  stop-color: var(--svg-color--ac92c4, #AC92C4);
  stop-opacity: 0;
}

.dyra_0bwn {
  stop-color: var(--svg-color--b9adc6, #B9ADC6);
}

.dysihlfpp {
  width: 0.969px;
  height: 1.96px;
  x: 6.469px;
  y: 8.294px;
  fill: var(--svg-color--605b65, #605B65);
  rx: 0.484px;
}

.e4rup4byc {
  stop-color: var(--svg-color--fefbff, #FEFBFF);
  stop-opacity: 0;
}

.e6-b92mws {
  stop-color: var(--svg-color--f5f1f7, #F5F1F7);
  stop-opacity: 0;
}

.e7ofo4lco {
  d: path("M5.345 12.114v-2.98c0-1.17-.85-1.89-1.58-1.89l-1.43.96c-.44.3-.71.79-.71 1.33a2.58 2.58 0 0 0 2.58 2.58z");
}

.ec-pibrug {
  stop-color: var(--svg-color--c4b9d0, #C4B9D0);
  stop-opacity: 0;
}

.ej4p73bid {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M22.625 14.434v-1.98c0-.73.26-1.43.73-1.98l1.14-1.33h-8.09c-1.01 0-1.98-.3-2.79-.85v3.86c0 1.22.67 2.35 1.75 2.93l3.26 1.74c.39.21.83.32 1.28.32c1.51-.01 2.72-1.22 2.72-2.71");
}

.ep6l40bwk {
  stop-color: var(--svg-color--bab7bc, #BAB7BC);
  stop-opacity: 0;
}

.ext_6n6sk {
  stop-color: var(--svg-color--dedae1, #DEDAE1);
}

.f37ky2brs {
  stop-color: var(--svg-color--d9d9da, #D9D9DA);
  stop-opacity: 0;
}

.f6mmj2gkf {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M9.531 8.375c.672-1.062 1.219-1.766 1.688-2.578v3.156c0 .975-.542 1.51-.813 1.656z");
}

.ft5dv1b6b {
  fill: none;
}

.fz1rws49h {
  stop-color: var(--svg-color--5f4e70, #5F4E70);
  stop-opacity: 0;
}

.gn1vkccis {
  fill: var(--svg-color--a898b5, #A898B5);
  d: path("M21.395 29.134h-1.48c-.17 0-.29-.16-.24-.32l1.91-6.68h2l-1.95 6.82c-.03.11-.13.18-.24.18");
}

.h34rt5ymw {
  stop-color: var(--svg-color--a898b5, #A898B5);
}

.ha_7fxbhl {
  stop-color: var(--svg-color--d36a78, #D36A78);
}

.hffkdxxqc {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
}

.hjsde98bq {
  stop-color: var(--svg-color--b49fc8, #B49FC8);
  stop-opacity: 0;
}

.ho17touts {
  stop-color: var(--svg-color--87848a, #87848A);
}

.hsiqmvppz {
  stop-color: var(--svg-color--fefbff, #FEFBFF);
}

.i27try1jr {
  stop-color: var(--svg-color--db7681, #DB7681);
}

.i4jnvdbhk {
  d: path("M8.655 12.115H5.32V8.994c0-1.044.65-1.721.975-1.93l3.94-2.52c.47-.29 1-.45 1.55-.45h2.83c0 1.26-1.03 2.29-2.29 2.29h-.41v2.47c0 1.8-1.46 3.26-3.26 3.26");
}

.i7tvr2-ly {
  stop-color: var(--svg-color--645d69, #645D69);
}

.ig8sqp_mn {
  stop-color: var(--svg-color--d9d9da, #D9D9DA);
}

.ij2pbj08i {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M29.234 22.64v2.844");
}

.ijisigr1s {
  d: path("M15.625 19.134h-2l1.98 6.91c.02.06.02.12 0 .17l-.76 2.59c-.05.16.07.32.24.32h1.48c.11 0 .21-.07.24-.18l.7-2.39c.08-.28.08-.58 0-.87z");
}

.iwddwnbgf {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M23.625 15.328h3.273v7.875l-1.745-.983a3 3 0 0 1-1.528-2.614z");
}

.j2fch6-5l {
  stop-color: var(--svg-color--b49fc8, #B49FC8);
}

.jqi3v0b1o {
  stop-color: var(--svg-color--6e6972, #6E6972);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jqxn9v7kl {
  d: path("M21.395 29.134h-1.48c-.17 0-.29-.16-.24-.32l1.91-6.68h2l-1.95 6.82c-.03.11-.13.18-.24.18");
}

.jxzpu5u7b {
  stop-color: var(--svg-color--b9adc5, #B9ADC5);
  stop-opacity: 0;
}

.k7fkkn_lj {
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("m29.625 16l-.501 1.844l-.501.691v.002l.002-.003v4.61h1z");
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.kmyxkible {
  width: 0.969px;
  height: 1.96px;
  x: 6.625px;
  y: 8.294px;
  rx: 0.484px;
}

.krcylmbtg {
  stop-color: var(--svg-color--5b4b6a, #5B4B6A);
}

.l20qrjbto {
  stop-color: var(--svg-color--6a5f76, #6A5F76);
}

.mkae6imnj {
  d: path("M22.225 19.874a.99.99 0 1 0 0-1.98a.99.99 0 0 0 0 1.98");
}

.mlt4iruen {
  stop-color: var(--svg-color--857092, #857092);
}

.n1l8bgbsy {
  d: path("M8.056 21.133A1.4 1.4 0 0 0 8.492 21c.68-.336 1.123-1.276 1.123-2.026v-.42c0-.25.1-.49.27-.67l.6-.63c.62-.64.59-1.68.132-2.317c-.412-.573-1.19-.803-1.93-.803H6.536l-.003.002l.363 1.998l.68 3.9c.074.412.242.785.48 1.1");
}

.n83d-_bcn {
  stop-color: var(--svg-color--635b6a, #635B6A);
  stop-opacity: 0;
}

.npcqhgb8l {
  stop-color: var(--svg-color--f4cd98, #F4CD98);
}

.nsmvpbcbs {
  d: path("m16.865 18.264l-3.14-2.36a.381.381 0 0 0-.61.31v2.27c0 .53.43.96.96.96h2.4c.63 0 .9-.8.39-1.18");
}

.nt6_ffb5y {
  fill: var(--svg-color--777679, #777679);
  d: path("M8.655 12.115H5.32V8.994c0-1.044.65-1.721.975-1.93l3.94-2.52c.47-.29 1-.45 1.55-.45h2.83c0 1.26-1.03 2.29-2.29 2.29h-.41v2.47c0 1.8-1.46 3.26-3.26 3.26");
}

.nwwl4dy4c {
  stop-color: var(--svg-color--857092, #857092);
  stop-opacity: 0;
}

.o0glwejhv {
  d: path("m25.205 11.384l-.43.43a3.93 3.93 0 0 0-1.15 2.77v1.05c0 .83.67 1.5 1.5 1.5s1.5-.67 1.5-1.5v-3.66c0-.74-.9-1.11-1.42-.59");
}

.ohlgprb1g {
  stop-color: var(--svg-color--a177c8, #A177C8);
  stop-opacity: 0;
}

.p04t-ybjb {
  d: path("M27.621 9.98v9.442a5.5 5.5 0 0 0 1.004-.888v.004c.78-.868 1-2.072 1-3.24v-1.464a4.7 4.7 0 0 0-2.004-3.854");
}

.p4aho-ttv {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M11.552 19.36v6.046a1.64 1.64 0 0 0 1.641-1.64v-1.798z");
}

.pehackbtp {
  stop-color: var(--svg-color--d5c4e7, #D5C4E7);
}

.pew6frnzi {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
  stop-opacity: 0;
}

.pl4x7xb5b {
  stop-color: var(--svg-color--5f4e70, #5F4E70);
}

.pwcquob8l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m15.688 28.656l.843-2.562l-1.062-3.407");
}

.qigai5upa {
  stop-color: var(--svg-color--6e6b71, #6E6B71);
  stop-opacity: 0;
}

.qsfqb8won {
  stop-color: var(--svg-color--ac92c4, #AC92C4);
}

.qzpg_4b9i {
  d: path("m8.695 3.604l.52 1.03h1.5l-.82-1.63a.67.67 0 0 0-.6-.37c-.5 0-.82.52-.6.97");
}

.r_60-_b1v {
  d: path("M21.625 21.841v-8.044L8.5 13.359l5.063 8.75l.083.025h6.359c.61 0 1.16-.21 1.61-.55q0 .13.01.257");
}

.rs604fbvq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m21.14 28.547l1.172-3.906");
}

.s9yrk6_lk {
  stop-color: var(--svg-color--756e7c, #756E7C);
}

.smdo9ebed {
  stop-color: var(--svg-color--6e6874, #6E6874);
}

.t0wxo5bmo {
  stop-color: var(--svg-color--aa9eae, #AA9EAE);
}

.tg__-gbph {
  stop-color: var(--svg-color--757575, #757575);
  stop-opacity: 0;
}

.tnubzejbp {
  stop-color: var(--svg-color--f5f1f7, #F5F1F7);
}

.u47hj0jbl {
  stroke: var(--svg-color--97959a, #97959A);
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M10.531 9.953c.214-.167.64-.722.64-1.61V5.657h1.235c.461 0 1.153-.15 1.578-1.125");
}

.uchyrc_vn {
  stop-color: var(--svg-color--bc5777, #BC5777);
  stop-opacity: 0;
}

.ugtrnlbyq {
  fill: var(--svg-color--77727d, #77727D);
  d: path("M29.625 26.134v-4a2 2 0 1 0 0 4");
}

.uivqnog9f {
  d: path("M9.613 22.094v-9.98H6.166l.729 4.02l.68 3.9a2.54 2.54 0 0 0 2.038 2.06");
}

.upy2fxbdf {
  d: path("m29.625 16l-.501 1.844l-.501.691v.002l.002-.003v4.61h1z");
}

.uydoy3bkx {
  stop-color: var(--svg-color--b51c82, #B51C82);
  stop-opacity: 0.25;
}

.v69etjbdd {
  d: path("M29.625 26.134v-4a2 2 0 1 0 0 4");
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

.vu3gnbc9x {
  stop-color: var(--svg-color--bfb0c4, #BFB0C4);
}

.w44hqmbkk {
  stop-color: var(--svg-color--b9adc5, #B9ADC5);
}

.wbmw69bfs {
  d: path("M24.935 9.134h-8.52c-1.74 0-3.35-.9-4.27-2.38l-.22-.37l-1.58 2.75h-4.72l1.27 7l.68 3.9a2.54 2.54 0 0 0 2.04 2.06v6.79c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-2.442a.5.5 0 0 1 .274-.446l.596-.302c.69-.35 1.13-1.05 1.13-1.82v-1.74h6.39c.61 0 1.16-.21 1.61-.55c0 1.5 1.02 2.81 2.48 3.17l.96.24a.75.75 0 0 1 .57.727v3.163c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-9.46c.38-.25.71-.55 1-.89v4.61h1v-9.31c0-2.6-2.1-4.7-4.69-4.7");
}

.whw6xlbrn {
  stop-color: var(--svg-color--5b4b6a, #5B4B6A);
  stop-opacity: 0;
}

.x5ianix4n {
  stop-color: var(--svg-color--a476ce, #A476CE);
}

.xmb07ebsd {
  stop-color: var(--svg-color--c4c4c5, #C4C4C5);
}

.xxl_ufjvs {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M27.621 9.98v9.442a5.5 5.5 0 0 0 1.004-.888v.004c.78-.868 1-2.072 1-3.24v-1.464a4.7 4.7 0 0 0-2.004-3.854");
}

.ydrvfxapf {
  d: path("M25.565 24.134h-5.06c-1.63 0-2.94-1.32-2.94-2.94v-3.06h8z");
}

.z-o07lghe {
  d: path("m13.555 22.09l-1.781-3.067l-3.747 2.072c.377.517.941.88 1.588 1v6.79c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-2.443a.5.5 0 0 1 .274-.446l.596-.302c.69-.35 1.13-1.05 1.13-1.82v-1.74z");
}

.z7vobrb6q {
  d: path("M22.625 14.434v-1.98c0-.73.26-1.43.73-1.98l1.14-1.33h-8.09c-1.01 0-1.98-.3-2.79-.85v3.86c0 1.22.67 2.35 1.75 2.93l3.26 1.74c.39.21.83.32 1.28.32c1.51-.01 2.72-1.22 2.72-2.71");
}

.zev3g0beu {
  d: path("M11.925 4.104h-2.29c-.75 0-1.48.22-2.1.64l-5.2 3.47c-.44.29-.71.78-.71 1.32a2.58 2.58 0 0 0 2.58 2.58h4.45c1.8 0 3.26-1.46 3.26-3.26v-2.47h.41c1.26 0 2.29-1.03 2.29-2.29h-2.69z");
}

.zhs46kbgk {
  stop-color: var(--svg-color--ae4868, #AE4868);
}

.zidv-cbxv {
  stop-color: var(--svg-color--6f6b73, #6F6B73);
}

.zokbf9bxm {
  stop-color: var(--svg-color--97959a, #97959A);
  stop-opacity: 0;
}

.zr9xvdbnb {
  stop-color: var(--svg-color--bfb1cd, #BFB1CD);
  stop-opacity: 0;
}

.zwd299b_x {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M10.852 25.922h.351v2.869h-.351z");
}

.zxk13obmj {
  stop-color: var(--svg-color--b51c82, #B51C82);
}

</style>
