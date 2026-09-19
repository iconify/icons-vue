<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="a-mu3h9zg"/><path fill="url(#iRNQpAb)" class="grba0orll"/><g filter="url(#i4rgD1d)"><path class="f3y_iwbpj"/></g><path fill="url(#iPCw6Fb)" class="bn1fecooj"/><g filter="url(#iDOO4lb)"><path class="gxu485ouu"/></g><path fill="url(#iLiLE7x)" class="vopt_x3lp"/><g filter="url(#ioVxifd)"><path class="uraetp1lj"/></g><path fill="url(#i2aoELc)" class="xgejpdbca"/><g filter="url(#iIsQ9Bc)"><path class="x408cbczr"/></g><path fill="url(#iV8I8re)" class="yiykj7_rd"/><g filter="url(#irocEqc)"><path class="wxyxel9pw"/></g><path fill="url(#icRXiOe)" class="n0wp1lu2f"/><path fill="url(#iuvQC2b)" class="eq-_v4bsc"/><path fill="url(#izNjmGe)" class="eq-_v4bsc"/><path fill="url(#i88kQDl)" class="w7jzi0c3x"/><path fill="url(#iiuzAqd)" class="w7jzi0c3x"/><path fill="url(#icuLe1b)" class="w7jzi0c3x"/><g clip-rule="evenodd" filter="url(#iNw9ybb)" class="d2kvgvbvc"><path fill="url(#ibCUuXd)" class="xvguiufsv"/><path class="nt94tjb-k"/></g><path fill="url(#iAs0hxc)" clip-rule="evenodd" class="v95v2cy_w"/><path fill="url(#iV7BaMb)" clip-rule="evenodd" class="v95v2cy_w"/><path fill="url(#i7s8smb)" class="ddz4z24yd"/><path fill="url(#id3oW2c)" class="ddz4z24yd"/><path fill="url(#iiYkswe)" class="mjxo8lb3d"/><g filter="url(#ikFwogc)"><path stroke="url(#iiZshne)" class="upl6g9bnu"/></g><g filter="url(#iZyKZPb)"><path stroke="url(#ikcOZPe)" class="b5ud9pb4a"/></g><g filter="url(#ib320nc)"><path stroke="url(#iLpNuzd)" class="bgrsenboe"/></g><g filter="url(#ipVQXpd)"><path fill="url(#inQHwlb)" class="r--4afb8h"/></g><defs><radialGradient id="iRNQpAb" cx="0" cy="0" r="1" gradientTransform="rotate(154.335 10.993 8.454)scale(16.0178 15.5184)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="ksito4bld"/><stop offset="1" class="mwr9aib1z"/></radialGradient><radialGradient id="iPCw6Fb" cx="0" cy="0" r="1" gradientTransform="rotate(124.244 5.031 10.37)scale(2.14467)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="jmhbr2bol"/><stop offset=".607" class="rf__gw59x"/></radialGradient><radialGradient id="iLiLE7x" cx="0" cy="0" r="1" gradientTransform="rotate(124.244 2.704 8.575)scale(2.14467)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="jmhbr2bol"/><stop offset=".607" class="rf__gw59x"/></radialGradient><radialGradient id="i2aoELc" cx="0" cy="0" r="1" gradientTransform="rotate(124.244 7.825 11.284)scale(2.14467)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="jmhbr2bol"/><stop offset=".607" class="rf__gw59x"/></radialGradient><radialGradient id="iV8I8re" cx="0" cy="0" r="1" gradientTransform="rotate(124.244 4.62 8.203)scale(2.14467)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="jmhbr2bol"/><stop offset=".607" class="rf__gw59x"/></radialGradient><radialGradient id="icRXiOe" cx="0" cy="0" r="1" gradientTransform="rotate(124.244 7.055 9.491)scale(2.14467)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="jmhbr2bol"/><stop offset=".607" class="rf__gw59x"/></radialGradient><radialGradient id="iiuzAqd" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 5.625 -18.58819 1.85882 11 20.125)" gradientUnits="userSpaceOnUse"><stop class="frlpgvbpg"/><stop offset="1" class="yc-i31xkz"/></radialGradient><radialGradient id="icuLe1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -11.7763 0 16 24.375)" gradientUnits="userSpaceOnUse"><stop class="isvmo4b-t"/><stop offset="1" class="t90ko-jti"/></radialGradient><radialGradient id="iV7BaMb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 1.75 -4.8465 .69236 2.75 17.094)" gradientUnits="userSpaceOnUse"><stop class="vvdovdwgf"/><stop offset="1" class="og3dqmbah"/></radialGradient><radialGradient id="id3oW2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.625 -20.4656 0 27.813 26.688)" gradientUnits="userSpaceOnUse"><stop class="hr87c4o_f"/><stop offset="1" class="ga7t3ibsu"/></radialGradient><radialGradient id="iLpNuzd" cx="0" cy="0" r="1" gradientTransform="rotate(15.695 -44.933 86.364)scale(7.85538 3.79254)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="f11ma0b9r"/><stop offset="1" class="x8zbncb8x"/></radialGradient><linearGradient id="iuvQC2b" x1="4.566" x2="27.435" y1="19.617" y2="19.617" gradientUnits="userSpaceOnUse"><stop class="ho0d4sbye"/><stop offset=".085" class="w2aiqct0d"/><stop offset=".243" class="zzrqsumkw"/><stop offset=".508" class="sjnjqzbzl"/><stop offset=".784" class="bjjfl_bjk"/><stop offset=".94" class="gz6nb2twi"/><stop offset="1" class="tba3ceakh"/></linearGradient><linearGradient id="izNjmGe" x1="16" x2="16" y1="19.938" y2="19" gradientUnits="userSpaceOnUse"><stop offset=".467" class="un4qkygga"/><stop offset=".846" class="p30j9bc2w"/></linearGradient><linearGradient id="i88kQDl" x1="16" x2="16" y1="20.489" y2="25.139" gradientUnits="userSpaceOnUse"><stop class="i1g0iewpb"/><stop offset=".312" class="o8b1v9blc"/><stop offset=".661" class="e5d7ijbsq"/><stop offset="1" class="w03l1mbqr"/></linearGradient><linearGradient id="ibCUuXd" x1="2.25" x2="29.688" y1="16.641" y2="16.641" gradientUnits="userSpaceOnUse"><stop class="r-lq9_bre"/><stop offset=".508" class="ulowmkbja"/><stop offset="1" class="fwa97_gzl"/></linearGradient><linearGradient id="iAs0hxc" x1="2.25" x2="29.688" y1="16.405" y2="16.405" gradientUnits="userSpaceOnUse"><stop class="r-lq9_bre"/><stop offset=".508" class="ulowmkbja"/><stop offset="1" class="fwa97_gzl"/></linearGradient><linearGradient id="i7s8smb" x1="16.01" x2="16.01" y1="25.139" y2="29.699" gradientUnits="userSpaceOnUse"><stop class="w1ncqbb7x"/><stop offset=".381" class="z5uf51bxh"/><stop offset=".573" class="razs20szn"/><stop offset="1" class="tkr8tpbgt"/></linearGradient><linearGradient id="iiYkswe" x1="16" x2="16" y1="18.688" y2="22.581" gradientUnits="userSpaceOnUse"><stop class="d4pk8gepq"/><stop offset=".488" class="ymz6w9bfv"/><stop offset="1" class="atrjnjbnv"/></linearGradient><linearGradient id="iiZshne" x1="19.375" x2="19.51" y1="21.188" y2="19.206" gradientUnits="userSpaceOnUse"><stop class="b9g3nsb-l"/><stop offset=".218" class="axx4dobva"/><stop offset="1" class="f6wrzrbdh"/></linearGradient><linearGradient id="ikcOZPe" x1="12.469" x2="12.333" y1="21.188" y2="19.206" gradientUnits="userSpaceOnUse"><stop class="b9g3nsb-l"/><stop offset=".218" class="axx4dobva"/><stop offset="1" class="f6wrzrbdh"/></linearGradient><linearGradient id="inQHwlb" x1="3.563" x2="11.656" y1="17.344" y2="16.156" gradientUnits="userSpaceOnUse"><stop class="ruiwa_aib"/><stop offset=".458" class="tl-okusnt"/><stop offset="1" class="lv0jd5brx"/></linearGradient><filter id="i4rgD1d" width="2.543" height="2.543" x="14.5" y="11.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="iDOO4lb" width="2.688" height="2.7" x="9.025" y="10.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="ioVxifd" width="2.543" height="2.543" x="19.621" y="10.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="iIsQ9Bc" width="2.688" height="2.7" x="11.813" y="8.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="irocEqc" width="2.543" height="2.543" x="16.789" y="8.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="iNw9ybb" width="23.031" height="4.47" x="4.563" y="14.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="ikFwogc" width="7.151" height="2.336" x="20.11" y="19.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".125"/></filter><filter id="iZyKZPb" width="7.151" height="2.336" x="4.583" y="19.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".125"/></filter><filter id="ib320nc" width="17.963" height="4.419" x="11.361" y="14.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter><filter id="ipVQXpd" width="10.5" height="5.093" x="2.188" y="13.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30551" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hamburger" /></template>
<style>
.a-mu3h9zg {
  fill: var(--svg-color--d99a64, #D99A64);
  d: path("M19.267 7h-6.524a8.317 8.317 0 0 0-8.318 8.318v1.323h23.17v-1.323C27.585 10.728 23.857 7 19.267 7");
}

.atrjnjbnv {
  stop-color: var(--svg-color--f7c747, #F7C747);
}

.axx4dobva {
  stop-color: var(--svg-color--ffe68f, #FFE68F);
}

.b5ud9pb4a {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M4.875 20.031c2.219.782 5.994 1.519 6.594 1.594");
}

.b9g3nsb-l {
  stop-color: var(--svg-color--ffe07a, #FFE07A);
  stop-opacity: 0;
}

.bgrsenboe {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M12.063 16c.75.48 2.85 1.719 4 1.719c1.437 0 6.01-3.78 8.718-2.344c2.063 1.094 3.823 1.031 3.657 1.094");
}

.bjjfl_bjk {
  stop-color: var(--svg-color--eb4a80, #EB4A80);
}

.bn1fecooj {
  d: path("M16 13.263a.772.772 0 1 0 0-1.543a.772.772 0 0 0 0 1.543");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d4pk8gepq {
  stop-color: var(--svg-color--c7850f, #C7850F);
}

.ddz4z24yd {
  d: path("M24.849 29.699H7.15a2.575 2.575 0 0 1-2.575-2.576V25.14h22.869v1.974a2.6 2.6 0 0 1-2.596 2.586");
}

.e5d7ijbsq {
  stop-color: var(--svg-color--98655d, #98655D);
}

.eq-_v4bsc {
  d: path("M27.435 16.41H4.565v3.207h22.87z");
}

.f11ma0b9r {
  stop-color: var(--svg-color--87be66, #87BE66);
}

.f3y_iwbpj {
  fill: var(--svg-color--e5a671, #E5A671);
  d: path("M15.772 13.471a.772.772 0 1 0 0-1.543a.772.772 0 0 0 0 1.543");
}

.f6wrzrbdh {
  stop-color: var(--svg-color--ffdb5c, #FFDB5C);
}

.frlpgvbpg {
  stop-color: var(--svg-color--6b544c, #6B544C);
}

.ft5dv1b6b {
  fill: none;
}

.fwa97_gzl {
  stop-color: var(--svg-color--79b142, #79B142);
}

.ga7t3ibsu {
  stop-color: var(--svg-color--ffc8a0, #FFC8A0);
  stop-opacity: 0;
}

.grba0orll {
  d: path("M19.267 7h-6.524a8.317 8.317 0 0 0-8.318 8.318v1.323h23.17v-1.323C27.585 10.728 23.857 7 19.267 7");
}

.gxu485ouu {
  fill: var(--svg-color--de9b64, #DE9B64);
  d: path("M10.37 12.7c.465 0 .843-.38.843-.85s-.378-.85-.844-.85a.847.847 0 0 0-.844.85c0 .47.378.85.844.85");
}

.gz6nb2twi {
  stop-color: var(--svg-color--db4379, #DB4379);
}

.ho0d4sbye {
  stop-color: var(--svg-color--dd7476, #DD7476);
}

.hr87c4o_f {
  stop-color: var(--svg-color--ffd5ae, #FFD5AE);
}

.i1g0iewpb {
  stop-color: var(--svg-color--946b52, #946B52);
}

.isvmo4b-t {
  stop-color: var(--svg-color--803e4c, #803E4C);
}

.jmhbr2bol {
  stop-color: var(--svg-color--f6e8d9, #F6E8D9);
}

.ksito4bld {
  stop-color: var(--svg-color--ffd39b, #FFD39B);
}

.lv0jd5brx {
  stop-color: var(--svg-color--66987e, #66987E);
  stop-opacity: 0;
}

.mjxo8lb3d {
  d: path("M27.435 19.617H4.565v.872l7.286 1.633c2.726.612 5.562.612 8.288 0l7.285-1.633v-.872z");
}

.mwr9aib1z {
  stop-color: var(--svg-color--ffd39a, #FFD39A);
  stop-opacity: 0;
}

.n0wp1lu2f {
  d: path("M18.435 10.217a.772.772 0 1 0 0-1.543a.772.772 0 0 0 0 1.543");
}

.nt94tjb-k {
  fill: var(--svg-color--e0215c, #E0215C);
  d: path("M9.666 15.411c1.58 0 3.139.645 3.843 1.021c.705.377 1.26.673 2.501.673c1.856 0 7.408-1.694 9.677-.48c.704.377-.14.48 1.094.48l.313 1.426c-.719 0-1.36-.196-2.23-.661l-.02-.01c-.705-.377-1.256-.672-2.49-.672s-1.786.294-2.49.67l-.022.012c-.872.466-1.907 1.011-3.832 1.011s-2.96-.545-3.832-1.01l-.021-.012c-.705-.377-1.257-.671-2.49-.671c-1.236 0-1.79.295-2.498.672l-.019.01c-.872.465-1.056.661-2.088.661c0 0 .054-1.724.758-2.099c.874-.466 1.912-1.02 3.846-1.02");
}

.o8b1v9blc {
  stop-color: var(--svg-color--a77a6f, #A77A6F);
}

.og3dqmbah {
  stop-color: var(--svg-color--6d9b85, #6D9B85);
  stop-opacity: 0;
}

.p30j9bc2w {
  stop-color: var(--svg-color--e72e64, #E72E64);
  stop-opacity: 0;
}

.r--4afb8h {
  d: path("M7.813 16.328c-1.481.774-3.563 1.797-4.782 2.078l-.344-2.078s.497.323 2.438-.578C7.75 14.531 9.172 14 10.703 14.5l1.485 2.938c-.948-.657-3.688-1.47-4.376-1.11");
}

.r-lq9_bre {
  stop-color: var(--svg-color--437151, #437151);
}

.razs20szn {
  stop-color: var(--svg-color--ea9d75, #EA9D75);
}

.rf__gw59x {
  stop-color: var(--svg-color--e2cfc1, #E2CFC1);
}

.ruiwa_aib {
  stop-color: var(--svg-color--66987e, #66987E);
}

.sjnjqzbzl {
  stop-color: var(--svg-color--d62650, #D62650);
}

.t90ko-jti {
  stop-color: var(--svg-color--824456, #824456);
  stop-opacity: 0;
}

.tba3ceakh {
  stop-color: var(--svg-color--d45e85, #D45E85);
}

.tkr8tpbgt {
  stop-color: var(--svg-color--e0819d, #E0819D);
}

.tl-okusnt {
  stop-color: var(--svg-color--66987e, #66987E);
  stop-opacity: 0.542;
}

.ulowmkbja {
  stop-color: var(--svg-color--619f49, #619F49);
}

.un4qkygga {
  stop-color: var(--svg-color--e72d62, #E72D62);
}

.upl6g9bnu {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M26.969 20.031c-2.219.782-5.994 1.519-6.594 1.594");
}

.uraetp1lj {
  fill: var(--svg-color--f4b982, #F4B982);
  d: path("M20.892 12.491a.772.772 0 1 0 0-1.543a.772.772 0 0 0 0 1.543");
}

.v95v2cy_w {
  fill-rule: evenodd;
  d: path("M5.839 15.175c.872-.465 1.907-1.01 3.827-1.01c1.921 0 2.954.546 3.825 1.01l.018.01c.705.377 1.26.673 2.501.673s1.796-.296 2.5-.672l.019-.01c.87-.465 1.904-1.011 3.825-1.011c1.92 0 2.954.546 3.824 1.011l.02.01c.703.377 1.255.672 2.49.672a1.394 1.394 0 0 1 0 2.788c-1.922 0-2.955-.547-3.825-1.012l-.02-.01c-.704-.377-1.255-.672-2.49-.672c-1.233 0-1.785.295-2.49.671l-.02.012c-.873.465-1.908 1.01-3.833 1.01s-2.96-.545-3.832-1.01l-.021-.012c-.705-.376-1.257-.67-2.49-.67c-1.236 0-1.79.295-2.498.672l-.019.01c-.872.465-1.907 1.01-3.827 1.01a1.394 1.394 0 1 1 0-2.787c1.235 0 1.79-.295 2.497-.673z");
}

.vopt_x3lp {
  d: path("M10.88 12.382a.772.772 0 1 0-.001-1.544a.772.772 0 0 0 0 1.544");
}

.vvdovdwgf {
  stop-color: var(--svg-color--6c9b83, #6C9B83);
}

.w03l1mbqr {
  stop-color: var(--svg-color--86536d, #86536D);
}

.w1ncqbb7x {
  stop-color: var(--svg-color--e18f63, #E18F63);
}

.w2aiqct0d {
  stop-color: var(--svg-color--e2565f, #E2565F);
}

.w7jzi0c3x {
  d: path("M27.675 25.139H4.325A2.327 2.327 0 0 1 2 22.814a2.327 2.327 0 0 1 2.325-2.325h23.35A2.327 2.327 0 0 1 30 22.814a2.327 2.327 0 0 1-2.325 2.325");
}

.wxyxel9pw {
  fill: var(--svg-color--e6a769, #E6A769);
  d: path("M18.06 10.373a.772.772 0 1 0 0-1.543a.772.772 0 0 0 0 1.543");
}

.x408cbczr {
  fill: var(--svg-color--de9d64, #DE9D64);
  d: path("M13.156 10.373c.466 0 .844-.38.844-.85a.847.847 0 0 0-.844-.85a.847.847 0 0 0-.844.85c0 .47.378.85.844.85");
}

.x8zbncb8x {
  stop-color: var(--svg-color--92c771, #92C771);
  stop-opacity: 0;
}

.xgejpdbca {
  d: path("M21.121 12.382a.772.772 0 1 0 0-1.544a.772.772 0 0 0 0 1.544");
}

.xvguiufsv {
  d: path("M9.666 15.411c1.58 0 3.139.645 3.843 1.021c.705.377 1.26.673 2.501.673c1.856 0 7.408-1.694 9.677-.48c.704.377-.14.48 1.094.48l.313 1.426c-.719 0-1.36-.196-2.23-.661l-.02-.01c-.705-.377-1.256-.672-2.49-.672s-1.786.294-2.49.67l-.022.012c-.872.466-1.907 1.011-3.832 1.011s-2.96-.545-3.832-1.01l-.021-.012c-.705-.377-1.257-.671-2.49-.671c-1.236 0-1.79.295-2.498.672l-.019.01c-.872.465-1.056.661-2.088.661c0 0 .054-1.724.758-2.099c.874-.466 1.912-1.02 3.846-1.02");
}

.yc-i31xkz {
  stop-color: var(--svg-color--6b544c, #6B544C);
  stop-opacity: 0;
}

.yiykj7_rd {
  d: path("M13.565 10.217a.772.772 0 1 0 0-1.543a.772.772 0 0 0 0 1.543");
}

.ymz6w9bfv {
  stop-color: var(--svg-color--f0cd2d, #F0CD2D);
}

.z5uf51bxh {
  stop-color: var(--svg-color--e89c6e, #E89C6E);
}

.zzrqsumkw {
  stop-color: var(--svg-color--de445c, #DE445C);
}

</style>
