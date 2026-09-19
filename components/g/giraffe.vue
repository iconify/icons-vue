<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iskIy0b)"><path class="xp4zxacid"/><path fill="url(#iKhYlGc)" class="zhgiojbac"/></g><path fill="url(#izB4gLb)" class="zhgiojbac"/><path fill="url(#iZW2Trb)" class="q74ahwb6v"/><path class="pa0l9xm_p"/><path fill="url(#iOaibIe)" class="afoq_gd0e"/><path fill="url(#ifMHowe)" class="afoq_gd0e"/><path fill="url(#ikOG76d)" class="afoq_gd0e"/><path fill="url(#iQH0hrd)" class="afoq_gd0e"/><path fill="url(#imbbQBe)" class="afoq_gd0e"/><path fill="url(#iCIFePe)" class="afoq_gd0e"/><path fill="url(#iydN3lc)" class="afoq_gd0e"/><g filter="url(#iTpsyBd)"><path clip-rule="evenodd" class="dpsewkbho"/></g><path fill="url(#iVlf2Rb)" clip-rule="evenodd" class="qx9vggb0g"/><g filter="url(#iXVo1Jb)"><path class="xpkjmw7nf"/></g><path fill="url(#ijVDeRH)" class="yvju9rbco"/><path fill="url(#i20kdFc)" class="yvju9rbco"/><path fill="url(#iMlEt9b)" class="yvju9rbco"/><path class="t-yfdkb9z"/><path fill="url(#irPRC7d)" class="sbdpdxwvl"/><path fill="url(#i9Ve57b)" class="sbdpdxwvl"/><path fill="url(#iw7tE4b)" class="x9qdzga9q"/><path class="nd4juhsbc"/><path fill="url(#iGjnvZb)" class="al8qlwn9k"/><path fill="url(#isSBqBd)" class="f78m1kbdn"/><path fill="url(#iuziHuc)" class="l20rqab5k"/><path class="efhcqpbqe"/><path fill="url(#ibvS2Nc)" class="mmf-7obzs"/><path fill="url(#irRdeac)" class="mmf-7obzs"/><g filter="url(#iM1vLls)"><path class="v715lacbm"/></g><path class="psx80pbgc"/><path fill="url(#iSL1Nud)" class="hf9nuhzws"/><path fill="url(#i4qjH3c)" class="hf9nuhzws"/><path class="ezq-n3q4r"/><path fill="url(#imp1erc)" class="cimz03b8h"/><path fill="url(#itAOSmb)" class="cimz03b8h"/><circle fill="url(#iIU5HZk)" class="wq8esyysw"/><path fill="url(#iAE3Bxb)" class="gz02y0brw"/><path fill="url(#iG5Ij7b)" class="zxkff392n"/><path fill="url(#i4oyDmc)" class="a00nswbkj"/><path fill="url(#ijw1yNc)" class="ii7ahgbgx"/><path fill="url(#inOxKQb)" class="kz-o_jdqr"/><path class="zka008qrc"/><path fill="url(#isKEYoc)" class="jz_l3dbbb"/><path fill="url(#i2xrxLb)" class="vzxvi73po"/><path class="eun4g9esz"/><path fill="url(#iv0qtBe)" class="uhaax0b4b"/><path class="s9_xdikhh"/><path class="g_a8gxb5r"/><path fill="url(#i5WPY1b)" class="o5ipzcbmw"/><path fill="url(#izzC3Ke)" class="ip3kvsbcw"/><path fill="url(#icXcsUc)" class="d2953-kga"/><g filter="url(#iG3ViVc)"><path class="brqvuhbav"/><path fill="url(#ixwCqob)" class="z9d87wkof"/></g><g filter="url(#i1WMybc)"><path stroke="url(#iV2nvXb)" class="cjwl_wo5c"/></g><defs><linearGradient id="iKhYlGc" x1="23.874" x2="25.999" y1="22.475" y2="24.412" gradientUnits="userSpaceOnUse"><stop class="whr8unjzc"/><stop offset="1" class="ucozsibwp"/></linearGradient><linearGradient id="izB4gLb" x1="28.186" x2="26.405" y1="25.162" y2="24.991" gradientUnits="userSpaceOnUse"><stop class="xeyabtbnj"/><stop offset="1" class="rtg5cubhg"/></linearGradient><linearGradient id="iZW2Trb" x1="14.03" x2="15.78" y1="21.938" y2="30" gradientUnits="userSpaceOnUse"><stop class="z--czezff"/><stop offset="1" class="soyz639_q"/></linearGradient><linearGradient id="iQH0hrd" x1="7.717" x2="11.967" y1="18.787" y2="17.75" gradientUnits="userSpaceOnUse"><stop class="y8_gewbhk"/><stop offset="1" class="g0v6mubun"/></linearGradient><linearGradient id="imbbQBe" x1="7.717" x2="9.28" y1="19.412" y2="19.069" gradientUnits="userSpaceOnUse"><stop class="lr89xhgea"/><stop offset="1" class="j30rpxbma"/></linearGradient><linearGradient id="iVlf2Rb" x1="24.796" x2="28.593" y1="17.819" y2="18.756" gradientUnits="userSpaceOnUse"><stop class="r89hgkb0c"/><stop offset="1" class="c05p23b8h"/></linearGradient><linearGradient id="ijVDeRH" x1="21.749" x2="18.435" y1="27.256" y2="26.506" gradientUnits="userSpaceOnUse"><stop class="vb-g_xbzw"/><stop offset="1" class="uaweq8lsf"/></linearGradient><linearGradient id="i20kdFc" x1="21.047" x2="21.047" y1="21.169" y2="25.668" gradientUnits="userSpaceOnUse"><stop class="s64ex-bjk"/><stop offset="1" class="tkt0yac5z"/></linearGradient><linearGradient id="iMlEt9b" x1="23.405" x2="22.139" y1="25.225" y2="25.241" gradientUnits="userSpaceOnUse"><stop class="d0pme0_hv"/><stop offset="1" class="sos4--bxo"/></linearGradient><linearGradient id="irPRC7d" x1="13.376" x2="12.495" y1="25.34" y2="25.34" gradientUnits="userSpaceOnUse"><stop class="d0pme0_hv"/><stop offset="1" class="sos4--bxo"/></linearGradient><linearGradient id="i9Ve57b" x1="11.392" x2="11.392" y1="21.381" y2="25.772" gradientUnits="userSpaceOnUse"><stop class="xv87z4kqa"/><stop offset="1" class="tkt0yac5z"/></linearGradient><linearGradient id="iw7tE4b" x1="6.28" x2="7.28" y1="3.406" y2="3.406" gradientUnits="userSpaceOnUse"><stop class="f2g5ohb7g"/><stop offset=".488" class="wkez0kbrr"/><stop offset="1" class="zu7l8ubxg"/></linearGradient><linearGradient id="iGjnvZb" x1="7.28" x2="6.78" y1="3" y2="3" gradientUnits="userSpaceOnUse"><stop class="yabq7iahl"/><stop offset="1" class="h2modnbjc"/></linearGradient><linearGradient id="isSBqBd" x1="8.639" x2="9.28" y1="3.406" y2="3.406" gradientUnits="userSpaceOnUse"><stop class="vozemoxgg"/><stop offset="1" class="hzjxy9xuw"/></linearGradient><linearGradient id="iuziHuc" x1="8.28" x2="9.28" y1="2.5" y2="2.5" gradientUnits="userSpaceOnUse"><stop class="hmj3lwz7a"/><stop offset="1" class="qi3s7cc3t"/></linearGradient><linearGradient id="itAOSmb" x1="3.546" x2="3.546" y1="8.381" y2="6.787" gradientUnits="userSpaceOnUse"><stop class="wtsprfbww"/><stop offset="1" class="e69j8lbjn"/></linearGradient><linearGradient id="iAE3Bxb" x1="18.78" x2="18.78" y1="15" y2="18" gradientUnits="userSpaceOnUse"><stop class="yb7gnub6q"/><stop offset="1" class="jz6ybr74z"/></linearGradient><linearGradient id="iG5Ij7b" x1="20.956" x2="20.956" y1="15" y2="17.649" gradientUnits="userSpaceOnUse"><stop class="l8ew-sdhb"/><stop offset="1" class="wcm2xxbri"/></linearGradient><linearGradient id="i4oyDmc" x1="19.785" x2="19.785" y1="18.67" y2="21.032" gradientUnits="userSpaceOnUse"><stop class="t63z5jtlm"/><stop offset="1" class="bwf-ii3ce"/></linearGradient><linearGradient id="ijw1yNc" x1="8.28" x2="10.055" y1="12.069" y2="11.381" gradientUnits="userSpaceOnUse"><stop offset=".333" class="re8el5bvt"/><stop offset="1" class="tz7pdif_x"/></linearGradient><linearGradient id="inOxKQb" x1="11.562" x2="11.562" y1="15.287" y2="19.38" gradientUnits="userSpaceOnUse"><stop class="icx0zbcor"/><stop offset="1" class="tgvppveii"/></linearGradient><linearGradient id="isKEYoc" x1="12.28" x2="12.28" y1="14.475" y2="15.881" gradientUnits="userSpaceOnUse"><stop class="eyiioum8e"/><stop offset="1" class="hkf2gfpcc"/></linearGradient><linearGradient id="i2xrxLb" x1="16" x2="16" y1="18" y2="20.99" gradientUnits="userSpaceOnUse"><stop class="ktf3w1_co"/><stop offset="1" class="qe9vsdncn"/></linearGradient><linearGradient id="iv0qtBe" x1="8.53" x2="9.999" y1="13.725" y2="14.75" gradientUnits="userSpaceOnUse"><stop class="a5rqt-b3k"/><stop offset="1" class="mcva14b2w"/></linearGradient><linearGradient id="i5WPY1b" x1="23.635" x2="23.635" y1="18.178" y2="19.772" gradientUnits="userSpaceOnUse"><stop class="otuz62bgx"/><stop offset="1" class="x8j19ld5g"/></linearGradient><linearGradient id="icXcsUc" x1="23.702" x2="22.975" y1="17.35" y2="17.35" gradientUnits="userSpaceOnUse"><stop class="psj9b0bnd"/><stop offset="1" class="ppa_-abyq"/></linearGradient><linearGradient id="iV2nvXb" x1="27.749" x2="25.796" y1="29.303" y2="21.444" gradientUnits="userSpaceOnUse"><stop class="rtg5cubhg"/><stop offset=".479" class="l5bd-9gfl"/><stop offset="1" class="rtg5cubhg"/></linearGradient><radialGradient id="iOaibIe" cx="0" cy="0" r="1" gradientTransform="rotate(166.942 11.085 9.915)scale(3.01548 3.59998)" gradientUnits="userSpaceOnUse"><stop class="ll_zt5eoq"/><stop offset="1" class="ujffpfi7z"/></radialGradient><radialGradient id="ifMHowe" cx="0" cy="0" r="1" gradientTransform="rotate(147.395 11.033 10.642)scale(4.11766 4.9158)" gradientUnits="userSpaceOnUse"><stop class="ll_zt5eoq"/><stop offset="1" class="ujffpfi7z"/></radialGradient><radialGradient id="ikOG76d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.40625 11.2812 0 16.218 23.569)" gradientUnits="userSpaceOnUse"><stop class="e9q3rbcxe"/><stop offset="1" class="t2n5eac6c"/></radialGradient><radialGradient id="iCIFePe" cx="0" cy="0" r="1" gradientTransform="matrix(4.42188 -3.07813 .71722 1.03033 6.983 18.334)" gradientUnits="userSpaceOnUse"><stop class="lr89xhgea"/><stop offset="1" class="j30rpxbma"/></radialGradient><radialGradient id="iydN3lc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.064 17.134 5.102)scale(1.84064 1.48436)" gradientUnits="userSpaceOnUse"><stop class="d0pme0_hv"/><stop offset="1" class="sos4--bxo"/></radialGradient><radialGradient id="ibvS2Nc" cx="0" cy="0" r="1" gradientTransform="matrix(2.39063 -1.89063 .9529 1.20491 4.233 9.069)" gradientUnits="userSpaceOnUse"><stop class="utdxvd9db"/><stop offset="1" class="sq0bukbmm"/></radialGradient><radialGradient id="irRdeac" cx="0" cy="0" r="1" gradientTransform="rotate(-151.783 4.752 3.308)scale(1.45405 2.18107)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="fypn9lbiw"/><stop offset="1" class="f8lpwgrsx"/></radialGradient><radialGradient id="iSL1Nud" cx="0" cy="0" r="1" gradientTransform="rotate(-147.779 5.703 1.462)scale(2.19785 1.67723)" gradientUnits="userSpaceOnUse"><stop class="l4i1om29a"/><stop offset="1" class="d57yh7bac"/></radialGradient><radialGradient id="i4qjH3c" cx="0" cy="0" r="1" gradientTransform="rotate(168.346 5.372 2.695)scale(1.27631 .50206)" gradientUnits="userSpaceOnUse"><stop class="oec4xbcze"/><stop offset=".541" class="j0fbtcmas"/></radialGradient><radialGradient id="imp1erc" cx="0" cy="0" r="1" gradientTransform="rotate(111.088 -.277 4.991)scale(1.28111 1.26607)" gradientUnits="userSpaceOnUse"><stop offset=".499" class="v2rdeooks"/><stop offset=".902" class="tyzttvbuv"/></radialGradient><radialGradient id="iIU5HZk" cx="0" cy="0" r="1" gradientTransform="matrix(-.34913 .65317 -.56844 -.30384 6.981 5.347)" gradientUnits="userSpaceOnUse"><stop class="ckq7otbdc"/><stop offset="1" class="jx0oumbhp"/></radialGradient><radialGradient id="izzC3Ke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23844 -.39307 .60425 -1.9038 22.62 22.053)" gradientUnits="userSpaceOnUse"><stop class="hs-hjyb4c"/><stop offset=".673" class="rbsjidb0p"/></radialGradient><radialGradient id="ixwCqob" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 .92187 -.49832 .15414 29.296 24.303)" gradientUnits="userSpaceOnUse"><stop offset=".042" class="nm409db_u"/><stop offset=".529" class="ryenjplsf"/></radialGradient><filter id="iskIy0b" width="5.338" height="9.831" x="22.28" y="20.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.825 0 0 0 0 0.304919 0 0 0 0 0.171875 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3399"/></filter><filter id="iTpsyBd" width="4.522" height="8.044" x="24.796" y="17.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.825 0 0 0 0 0.463572 0 0 0 0 0.055 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3399"/></filter><filter id="iXVo1Jb" width="3.484" height="6.072" x="25.721" y="17.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3399" stdDeviation=".125"/></filter><filter id="iM1vLls" width="4.603" height="9.833" x="6.941" y="5.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3399" stdDeviation=".5"/></filter><filter id="iG3ViVc" width="1.977" height="2.591" x="27.854" y="23.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.604167 0 0 0 0 0.336302 0 0 0 0 0.171181 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3399"/></filter><filter id="i1WMybc" width="2.463" height="6.965" x="25.197" y="22.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3399" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:giraffe" /></template>
<style>
.a00nswbkj {
  d: path("M22.03 18.67h-4.5c-.14 0-.25.11-.25.25v1.86c0 .17.17.29.33.24l2.62-.88c.03-.01.05-.01.08-.01h1.73c.14 0 .25-.11.25-.25v-.95c-.01-.15-.12-.26-.26-.26");
}

.a5rqt-b3k {
  stop-color: var(--svg-color--b46f44, #B46F44);
}

.afoq_gd0e {
  d: path("M12.19 14h9.34c1.88 0 3.915 1.385 4.273 3.19a.57.57 0 0 0 .287.4c.828.438 1.938 1.192 2.672 2.519c.354.64.456 1.354.456 2.015V24.6a.5.5 0 1 1-1 0v-2.476c0-.569-.09-1.095-.331-1.531c-.503-.91-1.226-1.501-1.88-1.9a.098.098 0 0 0-.149.084v.745c0 1.422-1.298 2.478-2.198 2.478a.38.38 0 0 0-.38.38v2.79c0 .54-.18 1.07-.5 1.5l-2.35 3.13a.48.48 0 0 1-.4.2h-1.35c-.18 0-.3-.2-.22-.37l1.69-3.37c.08-.17.13-.37.13-.56v-3.39c0-.17-.14-.31-.31-.31h-6.38c-.17 0-.31.14-.31.31v2.2c0 .32-.06.64-.18.94l-1.79 4.39c-.04.1-.13.16-.23.16H9.44c-.17 0-.29-.18-.23-.35l2-4.89c.05-.11.07-.23.07-.35v-2.24c0-.14-.1-.26-.24-.3a4 4 0 0 1-2.9-3.02L5.17 5.5H9.3l1.67 7.52c.13.57.63.98 1.22.98");
}

.al8qlwn9k {
  d: path("M6.78 2c-.27 0-.5.22-.5.5V3h1v-.5c0-.28-.22-.5-.5-.5");
}

.brqvuhbav {
  fill: var(--svg-color--b8744c, #B8744C);
  d: path("M27.854 25.723v-1.39a.6.6 0 0 1 .6-.6h.527a.6.6 0 0 1 .6.6v.52a.75.75 0 0 1-.19.5l-.509.57a.6.6 0 0 1-.448.2h-.18a.4.4 0 0 1-.4-.4");
}

.bwf-ii3ce {
  stop-color: var(--svg-color--ae6051, #AE6051);
}

.c05p23b8h {
  stop-color: var(--svg-color--e29739, #E29739);
  stop-opacity: 0;
}

.cimz03b8h {
  d: path("M4.28 6c-.55 0-1 .45-1 1s.45 1 1 1z");
}

.cjwl_wo5c {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.796 23.428l.812 1.035a2 2 0 0 1 .416 1.442l-.353 3.398");
}

.ckq7otbdc {
  stop-color: var(--svg-color--605255, #605255);
}

.d0pme0_hv {
  stop-color: var(--svg-color--eda84f, #EDA84F);
}

.d2953-kga {
  d: path("M23.45 17.58a.39.39 0 1 0 0-.78a.39.39 0 0 0 0 .78");
}

.d57yh7bac {
  stop-color: var(--svg-color--dd832b, #DD832B);
  stop-opacity: 0;
}

.dpsewkbho {
  fill: var(--svg-color--e29739, #E29739);
  fill-rule: evenodd;
  d: path("M24.841 17.547a.5.5 0 0 1 .664-.245c.798.367 2.328 1.129 3.257 2.807c.354.64.456 1.354.456 2.015V24.6a.5.5 0 1 1-1 0v-2.476c0-.569-.09-1.095-.331-1.531c-.764-1.381-2.036-2.031-2.8-2.383a.5.5 0 0 1-.246-.663");
}

.e69j8lbjn {
  stop-color: var(--svg-color--a65b58, #A65B58);
  stop-opacity: 0;
}

.e9q3rbcxe {
  stop-color: var(--svg-color--c4409f, #C4409F);
}

.efhcqpbqe {
  fill: var(--svg-color--e09435, #E09435);
  d: path("M6.87 4c-.94 0-1.75.64-1.97 1.54c-.07.27-.32.46-.59.46h-.03c-.55 0-1 .45-1 1s.45 1 1 1h3.547C9.28 8 9.28 5.75 9.28 4z");
}

.eun4g9esz {
  fill: var(--svg-color--ad6839, #AD6839);
  d: path("m6.77 9.3l.36 1.6c.01.06.06.1.12.1h.43c.07 0 .12-.06.12-.12V9.25c.01-.14-.11-.25-.24-.25h-.54c-.16 0-.28.15-.25.3");
}

.eyiioum8e {
  stop-color: var(--svg-color--be8455, #BE8455);
}

.ezq-n3q4r {
  fill: var(--svg-color--ac6e3d, #AC6E3D);
  d: path("M4.28 6c-.55 0-1 .45-1 1s.45 1 1 1z");
}

.f2g5ohb7g {
  stop-color: var(--svg-color--df6d28, #DF6D28);
}

.f78m1kbdn {
  d: path("M9.28 4.38h-1V2.5c0-.28.22-.5.5-.5c.27 0 .5.22.5.5z");
}

.f8lpwgrsx {
  stop-color: var(--svg-color--d8892a, #D8892A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fypn9lbiw {
  stop-color: var(--svg-color--d8892a, #D8892A);
}

.g_a8gxb5r {
  fill: var(--svg-color--c78a5d, #C78A5D);
  d: path("M8.12 8.34a.41.41 0 1 0 0-.82a.41.41 0 0 0 0 .82");
}

.g0v6mubun {
  stop-color: var(--svg-color--d18121, #D18121);
  stop-opacity: 0;
}

.gz02y0brw {
  d: path("M17.28 15.25v2.5c0 .14.11.25.25.25h2.5c.14 0 .25-.11.25-.25v-.65c0-.07-.03-.13-.07-.18l-1.85-1.85a.3.3 0 0 0-.18-.07h-.65c-.14 0-.25.11-.25.25");
}

.h2modnbjc {
  stop-color: var(--svg-color--8e8a8d, #8E8A8D);
  stop-opacity: 0;
}

.hf9nuhzws {
  d: path("M7.475 4s.063 1.5 1.055 1.5h1.25c.66 0 1.23-.43 1.42-1.03a.354.354 0 0 0-.34-.47z");
}

.hkf2gfpcc {
  stop-color: var(--svg-color--b8793e, #B8793E);
}

.hmj3lwz7a {
  stop-color: var(--svg-color--716d70, #716D70);
}

.hs-hjyb4c {
  stop-color: var(--svg-color--c07e51, #C07E51);
}

.hzjxy9xuw {
  stop-color: var(--svg-color--d49361, #D49361);
}

.icx0zbcor {
  stop-color: var(--svg-color--b47539, #B47539);
}

.ii7ahgbgx {
  d: path("m9.27 9.2l.78 3.52c.03.16-.08.3-.24.3H8.53c-.14 0-.25-.11-.25-.25V9.25c0-.14.11-.25.25-.25h.5c.12 0 .22.08.24.2");
}

.ip3kvsbcw {
  d: path("M21.88 22.4a.74.74 0 1 0 0-1.48a.74.74 0 0 0 0 1.48");
}

.j0fbtcmas {
  stop-color: var(--svg-color--f2af5d, #F2AF5D);
  stop-opacity: 0;
}

.j30rpxbma {
  stop-color: var(--svg-color--f2ba8a, #F2BA8A);
  stop-opacity: 0;
}

.jx0oumbhp {
  stop-color: var(--svg-color--3c273a, #3C273A);
}

.jz_l3dbbb {
  d: path("M13.28 14h-1.09c-.35 0-.68-.15-.91-.4v1.5c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25z");
}

.jz6ybr74z {
  stop-color: var(--svg-color--be7d4f, #BE7D4F);
}

.ktf3w1_co {
  stop-color: var(--svg-color--bc7b4e, #BC7B4E);
}

.kz-o_jdqr {
  d: path("M10.27 19.38c-.29 0-.54-.2-.61-.47c-.21-.86-.66-3.03-.82-3.67c-.03-.13.06-.24.18-.24h1.05c.13 0 .24.08.29.2l.27.69c.03.06.1.11.18.11h2.27c.13 0 .26.05.35.15l.71.71c.09.09.15.22.15.35v1.98c0 .1-.08.19-.19.19z");
}

.l20rqab5k {
  d: path("M8.78 2c-.28 0-.5.22-.5.5V3h1v-.5c0-.28-.23-.5-.5-.5");
}

.l4i1om29a {
  stop-color: var(--svg-color--dd832b, #DD832B);
}

.l5bd-9gfl {
  stop-color: var(--svg-color--ffa575, #FFA575);
}

.l8ew-sdhb {
  stop-color: var(--svg-color--c28141, #C28141);
}

.ll_zt5eoq {
  stop-color: var(--svg-color--fbb95f, #FBB95F);
}

.lr89xhgea {
  stop-color: var(--svg-color--f2ba8a, #F2BA8A);
}

.mcva14b2w {
  stop-color: var(--svg-color--cc9160, #CC9160);
}

.mmf-7obzs {
  d: path("M6.87 4c-.94 0-1.75.64-1.97 1.54c-.07.27-.32.46-.59.46h-.03c-.55 0-1 .45-1 1s.45 1 1 1h3.547C9.28 8 9.28 5.75 9.28 4z");
}

.nd4juhsbc {
  fill: var(--svg-color--716d70, #716D70);
  d: path("M6.78 2c-.27 0-.5.22-.5.5V3h1v-.5c0-.28-.22-.5-.5-.5");
}

.nm409db_u {
  stop-color: var(--svg-color--cd996f, #CD996F);
}

.o5ipzcbmw {
  d: path("M22.99 19.86v-1.27c0-.21.24-.33.4-.2l.79.62c.06.05.1.12.1.2v.65c0 .14-.11.25-.25.25h-.79c-.14 0-.25-.11-.25-.25");
}

.oec4xbcze {
  stop-color: var(--svg-color--f2af5d, #F2AF5D);
}

.otuz62bgx {
  stop-color: var(--svg-color--cb8958, #CB8958);
}

.pa0l9xm_p {
  fill: var(--svg-color--e09435, #E09435);
  d: path("M12.19 14h9.34c1.88 0 3.915 1.385 4.273 3.19a.57.57 0 0 0 .287.4c.828.438 1.938 1.192 2.672 2.519c.354.64.456 1.354.456 2.015V24.6a.5.5 0 1 1-1 0v-2.476c0-.569-.09-1.095-.331-1.531c-.503-.91-1.226-1.501-1.88-1.9a.098.098 0 0 0-.149.084v.745c0 1.422-1.298 2.478-2.198 2.478a.38.38 0 0 0-.38.38v2.79c0 .54-.18 1.07-.5 1.5l-2.35 3.13a.48.48 0 0 1-.4.2h-1.35c-.18 0-.3-.2-.22-.37l1.69-3.37c.08-.17.13-.37.13-.56v-3.39c0-.17-.14-.31-.31-.31h-6.38c-.17 0-.31.14-.31.31v2.2c0 .32-.06.64-.18.94l-1.79 4.39c-.04.1-.13.16-.23.16H9.44c-.17 0-.29-.18-.23-.35l2-4.89c.05-.11.07-.23.07-.35v-2.24c0-.14-.1-.26-.24-.3a4 4 0 0 1-2.9-3.02L5.17 5.5H9.3l1.67 7.52c.13.57.63.98 1.22.98");
}

.ppa_-abyq {
  stop-color: var(--svg-color--d69a6b, #D69A6B);
}

.psj9b0bnd {
  stop-color: var(--svg-color--dca171, #DCA171);
}

.psx80pbgc {
  fill: var(--svg-color--e09435, #E09435);
  d: path("M7.475 4s.063 1.5 1.055 1.5h1.25c.66 0 1.23-.43 1.42-1.03a.354.354 0 0 0-.34-.47z");
}

.q74ahwb6v {
  d: path("M17.03 30h-1.5c-.14 0-.25-.11-.25-.25v-4.17a.67.67 0 0 0-.14-.4l-2.63-3.2l1.55-1.27l2.87 3.5c.22.28.35.63.35.99v4.55c0 .14-.11.25-.25.25");
}

.qe9vsdncn {
  stop-color: var(--svg-color--ae6052, #AE6052);
}

.qi3s7cc3t {
  stop-color: var(--svg-color--969495, #969495);
}

.qx9vggb0g {
  fill-rule: evenodd;
  d: path("M24.841 17.547a.5.5 0 0 1 .664-.245c.798.367 2.328 1.129 3.257 2.807c.354.64.456 1.354.456 2.015V24.6a.5.5 0 1 1-1 0v-2.476c0-.569-.09-1.095-.331-1.531c-.764-1.381-2.036-2.031-2.8-2.383a.5.5 0 0 1-.246-.663");
}

.r89hgkb0c {
  stop-color: var(--svg-color--f5b156, #F5B156);
}

.rbsjidb0p {
  stop-color: var(--svg-color--b7704d, #B7704D);
}

.re8el5bvt {
  stop-color: var(--svg-color--ba7649, #BA7649);
}

.rtg5cubhg {
  stop-color: var(--svg-color--f0915f, #F0915F);
  stop-opacity: 0;
}

.ryenjplsf {
  stop-color: var(--svg-color--cd996f, #CD996F);
  stop-opacity: 0;
}

.s64ex-bjk {
  stop-color: var(--svg-color--de8e3d, #DE8E3D);
}

.s9_xdikhh {
  fill: var(--svg-color--ad6050, #AD6050);
  d: path("M10.74 20h3.36c.1 0 .19.08.19.19v.62c0 .1-.08.19-.19.19h-2.67c-.1 0-.19-.04-.26-.11l-.57-.56a.194.194 0 0 1 .14-.33");
}

.sbdpdxwvl {
  d: path("M11.04 21.87c.14.04.24.16.24.3v2.24c0 .12-.02.24-.07.35l-2 4.89c-.06.17.06.35.23.35h1.64c.1 0 .19-.06.23-.16l1.79-4.39c.12-.3.18-.62.18-.94v-2.2c0-.17.31-.31.31-.31s-1.115-1.531-2.55-.13");
}

.sos4--bxo {
  stop-color: var(--svg-color--eda84f, #EDA84F);
  stop-opacity: 0;
}

.soyz639_q {
  stop-color: var(--svg-color--d6603c, #D6603C);
}

.sq0bukbmm {
  stop-color: var(--svg-color--d1699b, #D1699B);
  stop-opacity: 0;
}

.t-yfdkb9z {
  fill: var(--svg-color--e3953d, #E3953D);
  d: path("M11.04 21.87c.14.04.24.16.24.3v2.24c0 .12-.02.24-.07.35l-2 4.89c-.06.17.06.35.23.35h1.64c.1 0 .19-.06.23-.16l1.79-4.39c.12-.3.18-.62.18-.94v-2.2c0-.17.31-.31.31-.31s-1.115-1.531-2.55-.13");
}

.t2n5eac6c {
  stop-color: var(--svg-color--c3409f, #C3409F);
  stop-opacity: 0;
}

.t63z5jtlm {
  stop-color: var(--svg-color--b8724b, #B8724B);
}

.tgvppveii {
  stop-color: var(--svg-color--b56e4e, #B56E4E);
}

.tkt0yac5z {
  stop-color: var(--svg-color--d87c54, #D87C54);
  stop-opacity: 0;
}

.tyzttvbuv {
  stop-color: var(--svg-color--d7a98c, #D7A98C);
}

.tz7pdif_x {
  stop-color: var(--svg-color--d29768, #D29768);
}

.uaweq8lsf {
  stop-color: var(--svg-color--d6852b, #D6852B);
}

.ucozsibwp {
  stop-color: var(--svg-color--d24e2c, #D24E2C);
  stop-opacity: 0;
}

.uhaax0b4b {
  d: path("M10.09 14.49H8.47a.19.19 0 0 1-.19-.19v-.57c0-.1.08-.19.19-.19h1.62c.1 0 .19.08.19.19v.57c0 .11-.08.19-.19.19");
}

.ujffpfi7z {
  stop-color: var(--svg-color--fbb95f, #FBB95F);
  stop-opacity: 0;
}

.utdxvd9db {
  stop-color: var(--svg-color--d1699b, #D1699B);
}

.v2rdeooks {
  stop-color: var(--svg-color--caa48c, #CAA48C);
  stop-opacity: 0;
}

.v715lacbm {
  stroke: var(--svg-color--fbb95f, #FBB95F);
  d: path("m8.43 6.162l1.625 7.625");
}

.vb-g_xbzw {
  stop-color: var(--svg-color--e3953c, #E3953C);
}

.vozemoxgg {
  stop-color: var(--svg-color--c97c36, #C97C36);
}

.vzxvi73po {
  d: path("M16.47 20.99h-.94c-.14 0-.25-.11-.25-.25v-2.49c0-.14.11-.25.25-.25h.94c.14 0 .25.11.25.25v2.49c0 .14-.11.25-.25.25");
}

.wcm2xxbri {
  stop-color: var(--svg-color--c88855, #C88855);
}

.whr8unjzc {
  stop-color: var(--svg-color--d24e2c, #D24E2C);
}

.wkez0kbrr {
  stop-color: var(--svg-color--e98452, #E98452);
}

.wq8esyysw {
  cx: 6.788px;
  cy: 5.492px;
  r: 0.508px;
}

.wtsprfbww {
  stop-color: var(--svg-color--a65b58, #A65B58);
}

.x8j19ld5g {
  stop-color: var(--svg-color--c17648, #C17648);
}

.x9qdzga9q {
  d: path("M7.28 4.38h-1V2.5c0-.28.23-.5.5-.5c.28 0 .5.22.5.5z");
}

.xeyabtbnj {
  stop-color: var(--svg-color--f0915f, #F0915F);
}

.xp4zxacid {
  fill: var(--svg-color--e16b3c, #E16B3C);
  d: path("M25.42 22.004V20.1h-3.14v3.484l2.437 2.215a1 1 0 0 1 .325.67l.219 3.133a.3.3 0 0 0 .299.28h1.277a.3.3 0 0 0 .299-.27l.367-3.624a3 3 0 0 0-.958-2.514l-.8-.733a1 1 0 0 1-.324-.737");
}

.xpkjmw7nf {
  stroke: var(--svg-color--fbb95f, #FBB95F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M25.983 18.014c.852.21 2.922 2.117 2.922 3.867v1.656");
}

.xv87z4kqa {
  stop-color: var(--svg-color--d77958, #D77958);
}

.y8_gewbhk {
  stop-color: var(--svg-color--d18121, #D18121);
}

.yabq7iahl {
  stop-color: var(--svg-color--8e8a8d, #8E8A8D);
}

.yb7gnub6q {
  stop-color: var(--svg-color--bd7f41, #BD7F41);
}

.yvju9rbco {
  d: path("M19.97 22c.17 0 .31.14.31.31v3.39c0 .19-.05.39-.13.56l-1.69 3.37c-.08.17.04.37.22.37h1.35c.16 0 .31-.07.4-.2l2.35-3.13c.32-.43.5-.96.5-1.5v-2.79c0-.21.17-.38.38-.38c-.536-.625-1.88-1.75-3.69 0");
}

.z--czezff {
  stop-color: var(--svg-color--cb4b24, #CB4B24);
}

.z9d87wkof {
  d: path("M27.854 25.723v-1.39a.6.6 0 0 1 .6-.6h.527a.6.6 0 0 1 .6.6v.52a.75.75 0 0 1-.19.5l-.509.57a.6.6 0 0 1-.448.2h-.18a.4.4 0 0 1-.4-.4");
}

.zhgiojbac {
  d: path("M25.42 22.004V20.1h-3.14v3.484l2.437 2.215a1 1 0 0 1 .325.67l.219 3.133a.3.3 0 0 0 .299.28h1.277a.3.3 0 0 0 .299-.27l.367-3.624a3 3 0 0 0-.958-2.514l-.8-.733a1 1 0 0 1-.324-.737");
}

.zka008qrc {
  fill: var(--svg-color--bc7d40, #BC7D40);
  d: path("m14.35 16.07l.85.85c.05.05.12.08.18.08h1.08c.14 0 .25-.11.25-.25v-1.5c0-.14-.11-.25-.25-.25h-1.94c-.13 0-.24.11-.24.25v.65c0 .06.03.13.07.17");
}

.zu7l8ubxg {
  stop-color: var(--svg-color--df8450, #DF8450);
}

.zxkff392n {
  d: path("M19.88 15h2.15c.14 0 .25.11.25.25v2.15c0 .22-.27.33-.43.18l-2.15-2.15c-.15-.16-.04-.43.18-.43");
}

</style>
