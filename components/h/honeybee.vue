<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#io1zRsc)" class="v9i1vwsqe"/><path fill="url(#i0j1H8c)" class="v9i1vwsqe"/><path fill="url(#ieI1bPe)" class="v9i1vwsqe"/><path fill="url(#iaW3kXD)" class="s8p_2ykvh"/><g filter="url(#ieEvslb)"><path stroke="url(#iPSLISc)" class="rzb-ah2ql"/></g><path fill="url(#imiSz5b)" class="np8e-n43z"/><path fill="url(#ij9zd8b)" class="np8e-n43z"/><g filter="url(#iG4GMLd)"><path stroke="url(#ivhtPJd)" class="pn-phkydq"/></g><g filter="url(#iQP26Rb)"><path fill="url(#iMURODa)" class="ej6_ehd9v"/></g><g filter="url(#igkobcK)"><path stroke="url(#itMFaNb)" class="gi0mtgs_w"/></g><g filter="url(#i9v8Uwc)"><path fill="url(#iBwNpUz)" class="joohkzb7o"/></g><path fill="url(#iADuQKc)" class="ih508_w_y"/><path fill="url(#i0Scw0d)" class="ih508_w_y"/><path fill="url(#inbvKoQ)" class="ih508_w_y"/><path fill="url(#ivhO4pc)" class="ih508_w_y"/><path fill="url(#izypUtc)" class="ih508_w_y"/><path fill="url(#icmxTUU)" class="ih508_w_y"/><path fill="url(#ilwNLTb)" class="ih508_w_y"/><path fill="url(#iiMy1ub)" class="orb99eg4h"/><path fill="url(#iuQ7zwb)" class="orb99eg4h"/><path fill="url(#iN07tle)" class="orb99eg4h"/><path fill="url(#ib4MULe)" class="orb99eg4h"/><path fill="url(#i8iOkbb)" class="orb99eg4h"/><path class="emgsgtbkr"/><path fill="url(#iohVWoc)" class="amdqjvuah"/><path fill="url(#i4ApA8b)" class="amdqjvuah"/><path fill="url(#ibNnEHe)" class="amdqjvuah"/><path fill="url(#ioGlMnb)" class="ke84seg4z"/><path fill="url(#irelwod)" class="ke84seg4z"/><path fill="url(#iBS5vyb)" class="ke84seg4z"/><path fill="url(#iPAWfXb)" class="hy3j_lbrv"/><path fill="url(#ifVrKbb)" class="hy3j_lbrv"/><path fill="url(#ieoDCke)" class="hy3j_lbrv"/><path fill="url(#iGxgmLb)" class="hy3j_lbrv"/><path fill="url(#isXLz7b)" class="hy3j_lbrv"/><path fill="url(#i7hHGsb)" class="hy3j_lbrv"/><path fill="url(#iVQT3ih)" class="hy3j_lbrv"/><path fill="url(#i0nQ4Ie)" class="hy3j_lbrv"/><path fill="url(#ihbCwhd)" class="uhjf3vqql"/><path fill="url(#i4pvfAb)" class="uhjf3vqql"/><path fill="url(#iEhefVc)" class="stg25bcrk"/><path stroke="url(#i8aQnPn)" class="gtl9net1h"/><path stroke="url(#ijSsGRs)" class="gtl9net1h"/><path stroke="url(#iY76oFc)" class="gtl9net1h"/><path stroke="url(#i5TSaHy)" class="gtl9net1h"/><path stroke="url(#i5OUz7b)" class="gtl9net1h"/><path fill="url(#iVkmIrd)" class="h8g-ncbru"/><path fill="url(#ian11mj)" class="h8g-ncbru"/><path fill="url(#i1iLmAb)" class="h8g-ncbru"/><path fill="url(#iqEunLR)" class="h8g-ncbru"/><path fill="url(#io7663b)" class="pq86msbbs"/><path fill="url(#im4QkAc)" class="pq86msbbs"/><path fill="url(#iY2rdzE)" class="pq86msbbs"/><path fill="url(#ijy390c)" class="pq86msbbs"/><g filter="url(#ik4A2Fd)"><path stroke="url(#isQEyad)" class="xjmlncb6d"/></g><defs><linearGradient id="io1zRsc" x1="22.531" x2="22.688" y1="26.946" y2="25.603" gradientUnits="userSpaceOnUse"><stop class="wdcgqmbmt"/><stop offset="1" class="dbeiqbx5q"/></linearGradient><linearGradient id="iaW3kXD" x1="23.141" x2="23.141" y1="25.325" y2="25.95" gradientUnits="userSpaceOnUse"><stop class="exnlrrspe"/><stop offset="1" class="k5-e5abtb"/></linearGradient><linearGradient id="iPSLISc" x1="19.859" x2="21.15" y1="23.716" y2="27.78" gradientUnits="userSpaceOnUse"><stop class="gr71vybfs"/><stop offset="1" class="pkj_ijb_j"/></linearGradient><linearGradient id="imiSz5b" x1="17.625" x2="18.703" y1="27.302" y2="26.38" gradientUnits="userSpaceOnUse"><stop class="wdcgqmbmt"/><stop offset="1" class="dbeiqbx5q"/></linearGradient><linearGradient id="ij9zd8b" x1="18.358" x2="18.358" y1="25.146" y2="26.333" gradientUnits="userSpaceOnUse"><stop class="f0c24cw6v"/><stop offset="1" class="cgihe0b0h"/></linearGradient><linearGradient id="ivhtPJd" x1="19.328" x2="18.344" y1="27.661" y2="24.677" gradientUnits="userSpaceOnUse"><stop class="gr71vybfs"/><stop offset="1" class="pkj_ijb_j"/></linearGradient><linearGradient id="iMURODa" x1="10.875" x2="10.25" y1="28.458" y2="26.333" gradientUnits="userSpaceOnUse"><stop class="wdcgqmbmt"/><stop offset="1" class="dbeiqbx5q"/></linearGradient><linearGradient id="itMFaNb" x1="11.578" x2="9.904" y1="25.958" y2="30.013" gradientUnits="userSpaceOnUse"><stop class="gr71vybfs"/><stop offset="1" class="pkj_ijb_j"/></linearGradient><linearGradient id="iBwNpUz" x1="4.882" x2="4.538" y1="12.997" y2="11.372" gradientUnits="userSpaceOnUse"><stop class="wdcgqmbmt"/><stop offset="1" class="dbeiqbx5q"/></linearGradient><linearGradient id="iADuQKc" x1="23.354" x2="23.354" y1="15.641" y2="24.578" gradientUnits="userSpaceOnUse"><stop offset=".006" class="x3mlsjb9s"/><stop offset="1" class="qkokqcn3s"/></linearGradient><linearGradient id="i0Scw0d" x1="23.123" x2="25.092" y1="22.672" y2="24.391" gradientUnits="userSpaceOnUse"><stop class="o0qhjqjmu"/><stop offset=".945" class="ttpeygrpj"/></linearGradient><linearGradient id="inbvKoQ" x1="21.967" x2="19.655" y1="24.172" y2="24.734" gradientUnits="userSpaceOnUse"><stop class="o0qhjqjmu"/><stop offset=".945" class="ttpeygrpj"/></linearGradient><linearGradient id="icmxTUU" x1="20.592" x2="21.748" y1="14.172" y2="14.172" gradientUnits="userSpaceOnUse"><stop class="ut_8fgb4r"/><stop offset="1" class="ot3ktgbib"/></linearGradient><linearGradient id="iiMy1ub" x1="14.392" x2="14.391" y1="16.583" y2="25.376" gradientUnits="userSpaceOnUse"><stop class="f7mzanb8l"/><stop offset="1" class="dyxf7cc3v"/></linearGradient><linearGradient id="iuQ7zwb" x1="14.389" x2="14.389" y1="10.677" y2="14.114" gradientUnits="userSpaceOnUse"><stop class="hhffbc8er"/><stop offset="1" class="owq6_5bsm"/></linearGradient><linearGradient id="iN07tle" x1="14.389" x2="14.389" y1="23.114" y2="27.052" gradientUnits="userSpaceOnUse"><stop class="o0qhjqjmu"/><stop offset=".945" class="ttpeygrpj"/></linearGradient><linearGradient id="ib4MULe" x1="14.389" x2="14.389" y1="25.099" y2="25.599" gradientUnits="userSpaceOnUse"><stop class="o0qhjqjmu"/><stop offset=".945" class="ttpeygrpj"/></linearGradient><linearGradient id="iohVWoc" x1="27.344" x2="26.672" y1="18.88" y2="18.099" gradientUnits="userSpaceOnUse"><stop class="n3xp4gbys"/><stop offset="1" class="gyn8rcbnm"/></linearGradient><linearGradient id="i4ApA8b" x1="27.688" x2="27.266" y1="15.521" y2="15.849" gradientUnits="userSpaceOnUse"><stop class="n3xp4gbys"/><stop offset="1" class="gyn8rcbnm"/></linearGradient><linearGradient id="ioGlMnb" x1="18.894" x2="18.894" y1="11.927" y2="24.104" gradientUnits="userSpaceOnUse"><stop class="u3vghc08t"/><stop offset="1" class="iwicj70pg"/></linearGradient><linearGradient id="irelwod" x1="19.969" x2="19.969" y1="27.677" y2="22.239" gradientUnits="userSpaceOnUse"><stop class="k1o44hbbp"/><stop offset="1" class="gb928qbqn"/></linearGradient><linearGradient id="iPAWfXb" x1="8.614" x2="8.614" y1="9.499" y2="23.989" gradientUnits="userSpaceOnUse"><stop class="f5rrk_b2d"/><stop offset="1" class="iwicj70pg"/></linearGradient><linearGradient id="ihbCwhd" x1="28.593" x2="28.688" y1="17.489" y2="16.638" gradientUnits="userSpaceOnUse"><stop class="wq5uuhkbp"/><stop offset="1" class="oxyzswbtv"/></linearGradient><linearGradient id="iEhefVc" x1="20.576" x2="10.107" y1="6.583" y2="12.458" gradientUnits="userSpaceOnUse"><stop class="pm8ngmb7e"/><stop offset="1" class="mcnw7ab5c"/></linearGradient><linearGradient id="i8aQnPn" x1="12.92" x2="16.389" y1="7.476" y2="10.208" gradientUnits="userSpaceOnUse"><stop class="gba-k46so"/><stop offset="1" class="bubungb-e"/></linearGradient><linearGradient id="iY76oFc" x1="12.865" x2="13.037" y1="7.38" y2="7.536" gradientUnits="userSpaceOnUse"><stop class="x608ty_ky"/><stop offset="1" class="nqioa8b2w"/></linearGradient><linearGradient id="i5TSaHy" x1="22.764" x2="22.201" y1="9.818" y2="9.521" gradientUnits="userSpaceOnUse"><stop class="ld8ophb-t"/><stop offset="1" class="pfsmbgcqr"/></linearGradient><linearGradient id="i5OUz7b" x1="15.875" x2="15.875" y1="12.271" y2="11.427" gradientUnits="userSpaceOnUse"><stop class="xclde2x5b"/><stop offset="1" class="msao45bcg"/></linearGradient><linearGradient id="isQEyad" x1="3.938" x2="8.343" y1="9.271" y2="11.671" gradientUnits="userSpaceOnUse"><stop class="gr71vybfs"/><stop offset="1" class="pkj_ijb_j"/></linearGradient><radialGradient id="i0j1H8c" cx="0" cy="0" r="1" gradientTransform="rotate(143.471 8.187 16.93)scale(1.31252 1.03217)" gradientUnits="userSpaceOnUse"><stop class="hg63ueh8u"/><stop offset=".682" class="y3r-w7r9j"/></radialGradient><radialGradient id="ieI1bPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.4414 .40625 -.11958 -.12993 22.387 25.384)" gradientUnits="userSpaceOnUse"><stop class="iss6xxbrs"/><stop offset="1" class="pp8mouehb"/></radialGradient><radialGradient id="ivhO4pc" cx="0" cy="0" r="1" gradientTransform="rotate(90 3.585 19.038)scale(3.25)" gradientUnits="userSpaceOnUse"><stop class="yo-g6tbho"/><stop offset="1" class="dx00_puva"/></radialGradient><radialGradient id="izypUtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 1.51562 -3.33883 2.58157 20.936 10.797)" gradientUnits="userSpaceOnUse"><stop class="ut_8fgb4r"/><stop offset="1" class="ot3ktgbib"/></radialGradient><radialGradient id="ilwNLTb" cx="0" cy="0" r="1" gradientTransform="rotate(-117.613 18.61 5.954)scale(1.14618 1.08419)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="wskmcoepb"/><stop offset="1" class="u5jai7xmz"/></radialGradient><radialGradient id="i8iOkbb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 0 0 -3 17.719 15.864)" gradientUnits="userSpaceOnUse"><stop class="m38040ged"/><stop offset="1" class="wiy-vccws"/></radialGradient><radialGradient id="ibNnEHe" cx="0" cy="0" r="1" gradientTransform="rotate(47.337 -4.41 36.737)scale(3.25098 1.32735)" gradientUnits="userSpaceOnUse"><stop class="vchiymb1s"/><stop offset="1" class="mj8ha1b5z"/></radialGradient><radialGradient id="iBS5vyb" cx="0" cy="0" r="1" gradientTransform="matrix(5.09375 0 0 1.53125 17.438 11.833)" gradientUnits="userSpaceOnUse"><stop class="grbog0q-e"/><stop offset="1" class="d8k1c-btq"/></radialGradient><radialGradient id="ifVrKbb" cx="0" cy="0" r="1" gradientTransform="rotate(121.608 .63 8.366)scale(4.28548 1.78769)" gradientUnits="userSpaceOnUse"><stop class="vwmusxdhb"/><stop offset="1" class="dpocieinv"/></radialGradient><radialGradient id="ieoDCke" cx="0" cy="0" r="1" gradientTransform="rotate(141.411 4.287 7.568)scale(3.95101 2.62031)" gradientUnits="userSpaceOnUse"><stop class="grbog0q-e"/><stop offset="1" class="d8k1c-btq"/></radialGradient><radialGradient id="iGxgmLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.59374 -1.54687 .46353 .47757 5.875 13.615)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="pc0t7bb2o"/><stop offset="1" class="wtdp4vbyt"/></radialGradient><radialGradient id="isXLz7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.68748 -4.34377 5.82116 3.60154 7.25 24.958)" gradientUnits="userSpaceOnUse"><stop class="lr45e7jvs"/><stop offset="1" class="q9q_riljf"/></radialGradient><radialGradient id="i7hHGsb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -3.875 2.08168 .35254 7.156 22.364)" gradientUnits="userSpaceOnUse"><stop class="bfgq6bbgm"/><stop offset="1" class="u6gz85b4i"/></radialGradient><radialGradient id="iVQT3ih" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 .1875 -.54823 3.6549 6.469 20.49)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="bsgetubzn"/><stop offset=".504" class="auduobeiv"/></radialGradient><radialGradient id="i0nQ4Ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.04851 1.85683 0 11.11 25.241)" gradientUnits="userSpaceOnUse"><stop class="jn2o9rfil"/><stop offset="1" class="coreb8b7k"/></radialGradient><radialGradient id="i4pvfAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73828 0 0 -.25781 29.484 16.958)" gradientUnits="userSpaceOnUse"><stop class="h6v-cabte"/><stop offset="1" class="wuhtoubur"/></radialGradient><radialGradient id="ijSsGRs" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 2.03125 -2.26681 -3.0689 22.826 4.864)" gradientUnits="userSpaceOnUse"><stop class="ww1htmqjo"/><stop offset="1" class="i2pucnb8r"/></radialGradient><radialGradient id="iVkmIrd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 -6.09375 3.27777 -.5547 6.219 21.24)" gradientUnits="userSpaceOnUse"><stop class="hi0oci17o"/><stop offset="1" class="ghu9bvdgv"/></radialGradient><radialGradient id="ian11mj" cx="0" cy="0" r="1" gradientTransform="matrix(-6.67188 0 0 -6.56735 8.594 17.066)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="rpp3g1-ic"/><stop offset="1" class="o7ggwbbku"/></radialGradient><radialGradient id="i1iLmAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -1.02407 0 6.313 16.083)" gradientUnits="userSpaceOnUse"><stop class="m_q1tnb3s"/><stop offset="1" class="c8cy3nydr"/></radialGradient><radialGradient id="iqEunLR" cx="0" cy="0" r="1" gradientTransform="rotate(120.388 -2.417 7.48)scale(2.93438 2.20319)" gradientUnits="userSpaceOnUse"><stop class="ptoaj4blb"/><stop offset="1" class="rm_vtbtkm"/></radialGradient><radialGradient id="io7663b" cx="0" cy="0" r="1" gradientTransform="matrix(-.48437 .51563 -.49224 -.4624 5.64 16.974)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="iwvz51btf"/><stop offset="1" class="p83i62btu"/></radialGradient><radialGradient id="im4QkAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39063 -.825 .91358 -.43257 5.492 17.9)" gradientUnits="userSpaceOnUse"><stop class="tqq48ubby"/><stop offset="1" class="arrmigb8x"/></radialGradient><radialGradient id="iY2rdzE" cx="0" cy="0" r="1" gradientTransform="matrix(2.03906 0 0 1.69937 4.203 17.075)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="wmq9l1bgv"/><stop offset="1" class="hrev5dbhk"/></radialGradient><radialGradient id="ijy390c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94531 0 0 -1.51547 6.406 17.075)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="p7xbm7avr"/><stop offset="1" class="zpj1soe8p"/></radialGradient><filter id="ieEvslb" width="3.353" height="2.572" x="21.409" y="23.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6380" stdDeviation=".125"/></filter><filter id="iG4GMLd" width="2.575" height="4.309" x="17.197" y="24.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6380" stdDeviation=".2"/></filter><filter id="iQP26Rb" width="2.977" height="5.98" x="8.957" y="23.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.517647 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6380"/></filter><filter id="igkobcK" width="2.381" height="4.959" x="9.278" y="23.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6380" stdDeviation=".2"/></filter><filter id="i9v8Uwc" width="3.041" height="4.461" x="2.923" y="8.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.517647 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6380"/></filter><filter id="ik4A2Fd" width="2.753" height="4.019" x="3.1" y="9.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6380" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:honeybee" /></template>
<style>
.amdqjvuah {
  d: path("m25.875 20.572l2.49-3.56l-2.49-3.585z");
}

.arrmigb8x {
  stop-color: var(--svg-color--402256, #402256);
  stop-opacity: 0;
}

.auduobeiv {
  stop-color: var(--svg-color--c37342, #C37342);
  stop-opacity: 0;
}

.bfgq6bbgm {
  stop-color: var(--svg-color--edae97, #EDAE97);
}

.bsgetubzn {
  stop-color: var(--svg-color--c37342, #C37342);
}

.bubungb-e {
  stop-color: var(--svg-color--7bc4e3, #7BC4E3);
  stop-opacity: 0;
}

.c8cy3nydr {
  stop-color: var(--svg-color--60546b, #60546B);
  stop-opacity: 0;
}

.cgihe0b0h {
  stop-color: var(--svg-color--392841, #392841);
  stop-opacity: 0;
}

.coreb8b7k {
  stop-color: var(--svg-color--ce714b, #CE714B);
  stop-opacity: 0;
}

.d8k1c-btq {
  stop-color: var(--svg-color--be9638, #BE9638);
  stop-opacity: 0;
}

.dbeiqbx5q {
  stop-color: var(--svg-color--452e4f, #452E4F);
}

.dpocieinv {
  stop-color: var(--svg-color--d6bb7e, #D6BB7E);
  stop-opacity: 0;
}

.dx00_puva {
  stop-color: var(--svg-color--776f80, #776F80);
  stop-opacity: 0;
}

.dyxf7cc3v {
  stop-color: var(--svg-color--5c2a83, #5C2A83);
}

.ej6_ehd9v {
  d: path("M9.704 28.981c-.19 0-.38-.07-.53-.22a.754.754 0 0 1 0-1.06l.65-.65c.36-.36.56-.85.56-1.36v-1.89c0-.41.34-.75.75-.75s.75.34.75.75v1.89c0 .91-.36 1.77-1 2.42l-.65.65c-.15.15-.34.22-.53.22");
}

.emgsgtbkr {
  fill: var(--svg-color--fcc946, #FCC946);
  d: path("m25.875 20.572l2.49-3.56l-2.49-3.585z");
}

.exnlrrspe {
  stop-color: var(--svg-color--2e203a, #2E203A);
}

.f0c24cw6v {
  stop-color: var(--svg-color--392841, #392841);
}

.f5rrk_b2d {
  stop-color: var(--svg-color--d2a02e, #D2A02E);
}

.f7mzanb8l {
  stop-color: var(--svg-color--433653, #433653);
}

.ft5dv1b6b {
  fill: none;
}

.gb928qbqn {
  stop-color: var(--svg-color--e988b9, #E988B9);
  stop-opacity: 0;
}

.gba-k46so {
  stop-color: var(--svg-color--7bc4e3, #7BC4E3);
}

.ghu9bvdgv {
  stop-color: var(--svg-color--443454, #443454);
}

.gi0mtgs_w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.828 28.27c.162-.186.48-.514.804-.924c.337-.43.477-.973.477-1.52v-1.415");
}

.gr71vybfs {
  stop-color: var(--svg-color--766983, #766983);
}

.grbog0q-e {
  stop-color: var(--svg-color--be9638, #BE9638);
}

.gtl9net1h {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.782 3.325h.001c2.25.038 4.03 1.71 4.087 3.958c.056 2.39-1.85 4.344-4.212 4.344c-1.735 0-3.48-.01-5.224-.019l-2.348-.011h-.001a.82.82 0 0 1-.615-.328a.58.58 0 0 1-.113-.35c.002-.134.047-.303.178-.506a115 115 0 0 1 2.574-2.874l.262-.286c.78-.85 1.505-1.641 2.028-2.249c.901-1.048 2.008-1.707 3.383-1.679Zm-8.448 6.938c-.633.96.204 1.584.751 1.584z");
}

.gyn8rcbnm {
  stop-color: var(--svg-color--e1aa72, #E1AA72);
  stop-opacity: 0;
}

.h6v-cabte {
  stop-color: var(--svg-color--6e6579, #6E6579);
}

.h8g-ncbru {
  d: path("M6.746 12.736c0-.192-.098-.614-1.066-.446c-2.214.535-3.59 2.432-3.59 4.809c0 2.355 1.548 4.383 3.665 4.77a1 1 0 0 0 .124.01c.632-.007.867-.135.867-.558z");
}

.hg63ueh8u {
  stop-color: var(--svg-color--786f84, #786F84);
}

.hhffbc8er {
  stop-color: var(--svg-color--323151, #323151);
}

.hi0oci17o {
  stop-color: var(--svg-color--5b2983, #5B2983);
}

.hrev5dbhk {
  stop-color: var(--svg-color--291d25, #291D25);
}

.hy3j_lbrv {
  d: path("M11.884 8.781v16.46c-3.72-.717-6.54-4.128-6.54-8.23s2.82-7.513 6.54-8.23");
}

.i2pucnb8r {
  stop-color: var(--svg-color--a5e8ff, #A5E8FF);
  stop-opacity: 0;
}

.ih508_w_y {
  d: path("m25.852 13.467l-.94-1.361c-1.18-1.606-2.39-2.68-4.06-3.172V25.12c1.66-.482 3.12-1.602 4.06-3.172l.94-1.362z");
}

.iss6xxbrs {
  stop-color: var(--svg-color--655a71, #655A71);
}

.iwicj70pg {
  stop-color: var(--svg-color--de8955, #DE8955);
}

.iwvz51btf {
  stop-color: var(--svg-color--4d4a4f, #4D4A4F);
}

.jn2o9rfil {
  stop-color: var(--svg-color--ce714b, #CE714B);
}

.joohkzb7o {
  d: path("M5.413 13.382c-.28 0-.5-.22-.5-.5v-.86c0-.71-.4-1.35-1.04-1.67l-.67-.38a.5.5 0 1 1 .44-.9l.68.38c.98.49 1.59 1.47 1.59 2.57v.86c0 .28-.22.5-.5.5");
}

.k1o44hbbp {
  stop-color: var(--svg-color--e988b9, #E988B9);
}

.k5-e5abtb {
  stop-color: var(--svg-color--3e2c4e, #3E2C4E);
  stop-opacity: 0;
}

.ke84seg4z {
  d: path("M20.894 8.915a6.7 6.7 0 0 0-1.88-.27h-2.12v16.731h2.12a6.7 6.7 0 0 0 1.88-.269z");
}

.ld8ophb-t {
  stop-color: var(--svg-color--8acff1, #8ACFF1);
}

.lr45e7jvs {
  stop-color: var(--svg-color--e58dad, #E58DAD);
}

.m_q1tnb3s {
  stop-color: var(--svg-color--60546b, #60546B);
}

.m38040ged {
  stop-color: var(--svg-color--514260, #514260);
}

.mcnw7ab5c {
  stop-color: var(--svg-color--87c0ea, #87C0EA);
}

.mj8ha1b5z {
  stop-color: var(--svg-color--ffda65, #FFDA65);
  stop-opacity: 0;
}

.msao45bcg {
  stop-color: var(--svg-color--6fb2df, #6FB2DF);
  stop-opacity: 0;
}

.n3xp4gbys {
  stop-color: var(--svg-color--e1aa72, #E1AA72);
}

.np8e-n43z {
  d: path("M19.074 28.981c-.19 0-.38-.07-.53-.22l-.65-.65c-.65-.65-1-1.51-1-2.42v-1.89c0-.41.34-.75.75-.75s.75.34.75.75v1.89c0 .51.2 1 .56 1.36l.65.65c.29.29.29.77 0 1.06c-.15.15-.34.22-.53.22");
}

.nqioa8b2w {
  stop-color: var(--svg-color--9dd3e9, #9DD3E9);
  stop-opacity: 0;
}

.o0qhjqjmu {
  stop-color: var(--svg-color--9257c2, #9257C2);
  stop-opacity: 0;
}

.o7ggwbbku {
  stop-color: var(--svg-color--8c8891, #8C8891);
}

.orb99eg4h {
  d: path("M16.894 25.366V8.646h-3.777c-.421.01-.832.063-1.233.136V25.24c.401.074.812.126 1.233.136h3.777z");
}

.ot3ktgbib {
  stop-color: var(--svg-color--4f455b, #4F455B);
  stop-opacity: 0;
}

.owq6_5bsm {
  stop-color: var(--svg-color--323151, #323151);
  stop-opacity: 0;
}

.oxyzswbtv {
  stop-color: var(--svg-color--55495e, #55495E);
}

.p7xbm7avr {
  stop-color: var(--svg-color--5a575d, #5A575D);
  stop-opacity: 0;
}

.p83i62btu {
  stop-color: var(--svg-color--2b2730, #2B2730);
}

.pc0t7bb2o {
  stop-color: var(--svg-color--b5954a, #B5954A);
}

.pfsmbgcqr {
  stop-color: var(--svg-color--8acff1, #8ACFF1);
  stop-opacity: 0;
}

.pkj_ijb_j {
  stop-color: var(--svg-color--766983, #766983);
  stop-opacity: 0;
}

.pm8ngmb7e {
  stop-color: var(--svg-color--8bd1f8, #8BD1F8);
}

.pn-phkydq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.797 25.083v.612a2.5 2.5 0 0 0 .631 1.661l.744.837");
}

.pp8mouehb {
  stop-color: var(--svg-color--655a71, #655A71);
  stop-opacity: 0;
}

.pq86msbbs {
  d: path("M5.344 17.9a.825.825 0 1 0 0-1.65a.825.825 0 0 0 0 1.65");
}

.ptoaj4blb {
  stop-color: var(--svg-color--817c87, #817C87);
}

.q9q_riljf {
  stop-color: var(--svg-color--e58dad, #E58DAD);
  stop-opacity: 0;
}

.qkokqcn3s {
  stop-color: var(--svg-color--5c2e82, #5C2E82);
}

.rm_vtbtkm {
  stop-color: var(--svg-color--817c87, #817C87);
  stop-opacity: 0;
}

.rpp3g1-ic {
  stop-color: var(--svg-color--8c8891, #8C8891);
  stop-opacity: 0;
}

.rzb-ah2ql {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.86 24.42v.871a.8.8 0 0 0 .8.8h1.652");
}

.s8p_2ykvh {
  d: path("M24.916 25.95h-3.12l.605-.514h1.803a.76.76 0 0 1 .712.514");
}

.stg25bcrk {
  d: path("M18.782 3.325h.001c2.25.038 4.03 1.71 4.087 3.958c.056 2.39-1.85 4.344-4.212 4.344c-1.735 0-3.48-.01-5.224-.019l-2.348-.011h-.001a.82.82 0 0 1-.615-.328a.58.58 0 0 1-.113-.35c.002-.134.047-.303.178-.506a115 115 0 0 1 2.574-2.874l.262-.286c.78-.85 1.505-1.641 2.028-2.249c.901-1.048 2.008-1.707 3.383-1.679m-8.448 6.938c-.633.96.204 1.584.751 1.584z");
}

.tqq48ubby {
  stop-color: var(--svg-color--402256, #402256);
}

.ttpeygrpj {
  stop-color: var(--svg-color--9257c2, #9257C2);
}

.u3vghc08t {
  stop-color: var(--svg-color--ebbd47, #EBBD47);
}

.u5jai7xmz {
  stop-color: var(--svg-color--3c1e58, #3C1E58);
  stop-opacity: 0;
}

.u6gz85b4i {
  stop-color: var(--svg-color--e3a28a, #E3A28A);
  stop-opacity: 0;
}

.uhjf3vqql {
  d: path("M27.746 16.126V17.9l.058-.06a1 1 0 0 1 .408-.253l1.484-.478a.1.1 0 0 0-.002-.19l-1.436-.436a1 1 0 0 1-.472-.31z");
}

.ut_8fgb4r {
  stop-color: var(--svg-color--4f455b, #4F455B);
}

.v9i1vwsqe {
  d: path("M24.204 26.946h-2.079c-.555 0-1.23-.306-1.23-1.316v-3.884c0-.41.34-.75.75-.75s.75.34.75.75v3.69h1.81c.41 0 .75.34.75.75s-.34.76-.75.76");
}

.vchiymb1s {
  stop-color: var(--svg-color--ffda65, #FFDA65);
}

.vwmusxdhb {
  stop-color: var(--svg-color--d6bb7e, #D6BB7E);
}

.wdcgqmbmt {
  stop-color: var(--svg-color--582f7c, #582F7C);
}

.wiy-vccws {
  stop-color: var(--svg-color--514260, #514260);
  stop-opacity: 0;
}

.wmq9l1bgv {
  stop-color: var(--svg-color--291d25, #291D25);
  stop-opacity: 0;
}

.wq5uuhkbp {
  stop-color: var(--svg-color--522c71, #522C71);
}

.wskmcoepb {
  stop-color: var(--svg-color--3c1e58, #3C1E58);
}

.wtdp4vbyt {
  stop-color: var(--svg-color--b5954a, #B5954A);
  stop-opacity: 0;
}

.wuhtoubur {
  stop-color: var(--svg-color--6e6579, #6E6579);
  stop-opacity: 0;
}

.ww1htmqjo {
  stop-color: var(--svg-color--a5e8ff, #A5E8FF);
}

.x3mlsjb9s {
  stop-color: var(--svg-color--5e5566, #5E5566);
}

.x608ty_ky {
  stop-color: var(--svg-color--9dd3e9, #9DD3E9);
}

.xclde2x5b {
  stop-color: var(--svg-color--6fb2df, #6FB2DF);
}

.xjmlncb6d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m3.5 9.49l.585.297a2.5 2.5 0 0 1 1.368 2.229v.692");
}

.y3r-w7r9j {
  stop-color: var(--svg-color--786f84, #786F84);
  stop-opacity: 0;
}

.yo-g6tbho {
  stop-color: var(--svg-color--776f80, #776F80);
}

.zpj1soe8p {
  stop-color: var(--svg-color--5a575d, #5A575D);
}

</style>
