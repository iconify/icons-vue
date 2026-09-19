<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEssV3b)" class="cevw3t_aw"/><path fill="url(#iQL0xse)" class="cevw3t_aw"/><path fill="url(#iH3nsFc)" class="cevw3t_aw"/><path fill="url(#i615W3P)" class="s1-qaqbvt"/><path fill="url(#iPgwmXH)" class="s1-qaqbvt"/><path fill="url(#iDxFSAd)" class="s1-qaqbvt"/><path class="ihmjjjigj"/><path fill="url(#iiL4aRc)" class="ammx9od1y"/><path fill="url(#i1qcV3b)" class="ammx9od1y"/><path fill="url(#insKLRc)" class="ammx9od1y"/><path fill="url(#ivQj8ic)" class="ammx9od1y"/><path fill="url(#iP3PpKd)" class="ammx9od1y"/><path fill="url(#iTyOwYb)" class="ammx9od1y"/><path fill="url(#i2RHtLb)" class="ammx9od1y"/><path fill="url(#i11t5Zb)" class="ammx9od1y"/><path fill="url(#iJHnv9b)" class="ammx9od1y"/><path fill="url(#iGGZOrz)" class="ammx9od1y"/><g filter="url(#ipliFbb)"><path fill="url(#ipAiACb)" class="m71eaeb7x"/></g><path fill="url(#i7LVKBb)" class="uy6hh4bsz"/><path fill="url(#iIf3Znc)" class="uy6hh4bsz"/><path fill="url(#iAQBwuc)" class="uy6hh4bsz"/><path fill="url(#i8Mi7Ae)" class="uy6hh4bsz"/><path fill="url(#ik7ZZsb)" class="ot1ijpbyp"/><path fill="url(#iC1NaKc)" class="ot1ijpbyp"/><path fill="url(#iKTOgzR)" class="fwptkhrcc"/><path fill="url(#iUQJ92d)" class="z414gyb9w"/><path fill="url(#iCEkp4D)" class="z414gyb9w"/><path fill="url(#iWg02yg)" class="zqcjh-0dv"/><g filter="url(#iIBNaGd)"><path fill="url(#iRAJ1Yc)" class="e17d1_hvc"/><path fill="url(#iLrtlXb)" class="e17d1_hvc"/><path fill="url(#iYCAP2c)" class="e17d1_hvc"/><path fill="url(#iOvJHEd)" class="e17d1_hvc"/><path fill="url(#iqXWSrb)" class="e17d1_hvc"/><path fill="url(#iYcSjqd)" class="e17d1_hvc"/></g><g filter="url(#iayMcmd)"><path fill="url(#iJOY0Bc)" class="out3ue2qu"/></g><path fill="url(#inpkcyb)" class="v13blqqdv"/><path fill="url(#i2WkE7b)" class="v13blqqdv"/><path fill="url(#ihF3oRb)" class="v13blqqdv"/><path fill="url(#idwC2kb)" class="h_bowvj6m"/><path fill="url(#i1j3xgb)" class="h_bowvj6m"/><path fill="url(#iMeUG4c)" class="tz_56zbfh"/><path fill="url(#iFITFJp)" class="tz_56zbfh"/><g filter="url(#ipgieic)"><path class="m7n73jb2n"/></g><g filter="url(#iS3o3Pc)"><path class="j2k5oshtz"/></g><path fill="url(#is8Jj9Y)" class="awz_eimzr"/><path fill="url(#iJSB6sd)" class="awz_eimzr"/><path fill="url(#i6ZYcOb)" class="awz_eimzr"/><path fill="url(#iYK3lDc)" class="p90zc0bvq"/><path fill="url(#isgt5re)" class="p90zc0bvq"/><path fill="url(#iJat3Je)" class="p90zc0bvq"/><g filter="url(#iPSOgLe)"><ellipse fill="url(#il6Wo8d)" transform="rotate(45.67 24.653 12.842)" class="z8gfvabdb"/></g><g filter="url(#iBVdaGZ)"><path fill="url(#it6Xmad)" class="ci3g-pbsd"/></g><g filter="url(#ix2Zqye)"><path fill="url(#icBovfc)" class="zmoovbcxs"/></g><g filter="url(#i0huXod)"><path stroke="url(#iN3VpBc)" class="bai2i2b0r"/></g><g filter="url(#iAl8vpm)"><path stroke="url(#i5RJ40d)" class="ic5t1k9ki"/></g><defs><linearGradient id="iEssV3b" x1="8.75" x2="8.75" y1="18.474" y2="24.161" gradientUnits="userSpaceOnUse"><stop class="deou2-nvv"/><stop offset="1" class="qizwslptk"/></linearGradient><linearGradient id="iQL0xse" x1="8.75" x2="8.75" y1="23.664" y2="25.661" gradientUnits="userSpaceOnUse"><stop class="tafy_0bai"/><stop offset="1" class="m4ym1g00h"/></linearGradient><linearGradient id="iH3nsFc" x1="4.75" x2="6.203" y1="22.536" y2="23.302" gradientUnits="userSpaceOnUse"><stop class="h0av6ybac"/><stop offset=".724" class="ujgw73bje"/></linearGradient><linearGradient id="i615W3P" x1="19.75" x2="18.922" y1="19.38" y2="23.161" gradientUnits="userSpaceOnUse"><stop class="deou2-nvv"/><stop offset="1" class="qizwslptk"/></linearGradient><linearGradient id="iPgwmXH" x1="19.75" x2="19.75" y1="23.664" y2="25.661" gradientUnits="userSpaceOnUse"><stop class="tafy_0bai"/><stop offset="1" class="m4ym1g00h"/></linearGradient><linearGradient id="iDxFSAd" x1="14.984" x2="17.203" y1="22.286" y2="23.302" gradientUnits="userSpaceOnUse"><stop class="h0av6ybac"/><stop offset=".724" class="ujgw73bje"/></linearGradient><linearGradient id="i11t5Zb" x1="11.266" x2="11.266" y1="25.911" y2="16.786" gradientUnits="userSpaceOnUse"><stop class="j6pledb1h"/><stop offset="1" class="z0_w1acsl"/></linearGradient><linearGradient id="iJHnv9b" x1="19.146" x2="19.146" y1="23.349" y2="25.911" gradientUnits="userSpaceOnUse"><stop class="tafy_0bai"/><stop offset="1" class="m4ym1g00h"/></linearGradient><linearGradient id="ipAiACb" x1="20.941" x2="20.941" y1="23.841" y2="18.926" gradientUnits="userSpaceOnUse"><stop class="vq9hkubad"/><stop offset="1" class="gn0ws_b8s"/></linearGradient><linearGradient id="i7LVKBb" x1="15.891" x2="25.078" y1="21.095" y2="21.095" gradientUnits="userSpaceOnUse"><stop class="lslk0wbet"/><stop offset="1" class="a-a4g0boh"/></linearGradient><linearGradient id="iIf3Znc" x1="16.422" x2="17.359" y1="22.339" y2="22.339" gradientUnits="userSpaceOnUse"><stop class="hmg4m5ace"/><stop offset="1" class="pqdqm2bqx"/></linearGradient><linearGradient id="iAQBwuc" x1="19.641" x2="19.641" y1="21.521" y2="23.349" gradientUnits="userSpaceOnUse"><stop class="me1q-ibjy"/><stop offset=".752" class="qavaavbor"/></linearGradient><linearGradient id="ik7ZZsb" x1="10.797" x2="10.797" y1="9.005" y2="6.661" gradientUnits="userSpaceOnUse"><stop class="j7tpg1sdw"/><stop offset="1" class="jg0rpqp_y"/></linearGradient><linearGradient id="iC1NaKc" x1="10.484" x2="10.891" y1="8.458" y2="8.458" gradientUnits="userSpaceOnUse"><stop class="d3om1vbcl"/><stop offset="1" class="vdv14_bxl"/></linearGradient><linearGradient id="iUQJ92d" x1="6.952" x2="6.952" y1="9.005" y2="6.661" gradientUnits="userSpaceOnUse"><stop class="j7tpg1sdw"/><stop offset="1" class="jg0rpqp_y"/></linearGradient><linearGradient id="iRAJ1Yc" x1="9.496" x2="9.496" y1="16.099" y2="21.419" gradientUnits="userSpaceOnUse"><stop class="ig-1egbtx"/><stop offset="1" class="lxz-b4o1r"/></linearGradient><linearGradient id="iLrtlXb" x1="9.496" x2="9.496" y1="19.255" y2="21.724" gradientUnits="userSpaceOnUse"><stop class="tafy_0bai"/><stop offset="1" class="m4ym1g00h"/></linearGradient><linearGradient id="iYCAP2c" x1="9.496" x2="9.496" y1="20.724" y2="21.786" gradientUnits="userSpaceOnUse"><stop offset=".382" class="plp3jqqdp"/><stop offset="1" class="homoywb9x"/></linearGradient><linearGradient id="iJOY0Bc" x1="12.047" x2="12.047" y1="10.599" y2="17.38" gradientUnits="userSpaceOnUse"><stop class="v8ajsgb1f"/><stop offset="0" class="v8ajsgb1f"/><stop offset="1" class="p8yzywbyh"/></linearGradient><linearGradient id="i2WkE7b" x1="9.828" x2="9.844" y1="20.161" y2="18.192" gradientUnits="userSpaceOnUse"><stop class="giuz38bmi"/><stop offset="1" class="afjxy2bxw"/></linearGradient><linearGradient id="i1j3xgb" x1="7.078" x2="6.703" y1="16.646" y2="14.505" gradientUnits="userSpaceOnUse"><stop class="pgo4l0cns"/><stop offset="1" class="gw1a99b8j"/></linearGradient><linearGradient id="is8Jj9Y" x1="8.511" x2="7.932" y1="12.845" y2="12.845" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iJSB6sd" x1="8.667" x2="8.667" y1="14.021" y2="13.302" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iYK3lDc" x1="11.48" x2="10.901" y1="12.845" y2="12.845" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="isgt5re" x1="11.636" x2="11.636" y1="14.021" y2="13.302" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="it6Xmad" x1="28.609" x2="28.609" y1="23.849" y2="18.474" gradientUnits="userSpaceOnUse"><stop class="vq9hkubad"/><stop offset="1" class="gn0ws_b8s"/></linearGradient><linearGradient id="icBovfc" x1="26.234" x2="26.234" y1="15.599" y2="25.349" gradientUnits="userSpaceOnUse"><stop class="vq9hkubad"/><stop offset="1" class="gn0ws_b8s"/></linearGradient><linearGradient id="iN3VpBc" x1="11.484" x2="12.609" y1="24.302" y2="23.38" gradientUnits="userSpaceOnUse"><stop class="vq9hkubad"/><stop offset="1" class="gn0ws_b8s"/></linearGradient><linearGradient id="i5RJ40d" x1="29.484" x2="29.484" y1="21.771" y2="19.755" gradientUnits="userSpaceOnUse"><stop class="v8ajsgb1f"/><stop offset="1" class="p8yzywbyh"/></linearGradient><radialGradient id="iiL4aRc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.06252 4.56248 -7.76924 -8.62075 30.89 7.849)" gradientUnits="userSpaceOnUse"><stop class="ke56yvbts"/><stop offset="1" class="rqzwlbbqo"/></radialGradient><radialGradient id="i1qcV3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.46875 .67187 0 28.14 22.224)" gradientUnits="userSpaceOnUse"><stop class="ewpcvtbfj"/><stop offset="1" class="ms2befbgr"/></radialGradient><radialGradient id="insKLRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -3.3125 1.17735 -.17771 28.734 22.911)" gradientUnits="userSpaceOnUse"><stop class="ewpcvtbfj"/><stop offset="1" class="ms2befbgr"/></radialGradient><radialGradient id="ivQj8ic" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 -1.78125 2.20142 2.7035 13.703 13.693)" gradientUnits="userSpaceOnUse"><stop class="xbf18fbav"/><stop offset="1" class="l2wvi5z4b"/></radialGradient><radialGradient id="iP3PpKd" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -1.75 1.27049 .55584 11.547 9.833)" gradientUnits="userSpaceOnUse"><stop class="xbf18fbav"/><stop offset="1" class="l2wvi5z4b"/></radialGradient><radialGradient id="iTyOwYb" cx="0" cy="0" r="1" gradientTransform="rotate(143.746 2.916 12.652)scale(3.4877 1.6444)" gradientUnits="userSpaceOnUse"><stop class="rsnxv5dvv"/><stop offset="1" class="gf8oxvbmt"/></radialGradient><radialGradient id="i2RHtLb" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 -.71875 1.15739 4.227 11.14 22.599)" gradientUnits="userSpaceOnUse"><stop class="rsnxv5dvv"/><stop offset="1" class="gf8oxvbmt"/></radialGradient><radialGradient id="iGGZOrz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46878 -3.18748 2.15464 -.99285 21.578 22.192)" gradientUnits="userSpaceOnUse"><stop class="m4ym1g00h"/><stop offset="1" class="tafy_0bai"/></radialGradient><radialGradient id="i8Mi7Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -1.21873 .79937 -2.62363 23.203 22.755)" gradientUnits="userSpaceOnUse"><stop class="m4ym1g00h"/><stop offset="1" class="tafy_0bai"/></radialGradient><radialGradient id="iKTOgzR" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.10938 -1.04688 0 11.328 8.114)" gradientUnits="userSpaceOnUse"><stop class="l_9lssbff"/><stop offset="1" class="kigo8pweb"/></radialGradient><radialGradient id="iCEkp4D" cx="0" cy="0" r="1" gradientTransform="rotate(165.174 3.877 4.364)scale(.82432 1.69085)" gradientUnits="userSpaceOnUse"><stop class="d3om1vbcl"/><stop offset="1" class="vdv14_bxl"/></radialGradient><radialGradient id="iWg02yg" cx="0" cy="0" r="1" gradientTransform="matrix(-.7403 0 0 -2.05319 8 8.74)" gradientUnits="userSpaceOnUse"><stop class="l_9lssbff"/><stop offset="1" class="kigo8pweb"/></radialGradient><radialGradient id="iOvJHEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71875 1.59375 -1.65027 -1.7797 14.922 15.724)" gradientUnits="userSpaceOnUse"><stop class="v8ajsgb1f"/><stop offset=".863" class="p8yzywbyh"/></radialGradient><radialGradient id="iqXWSrb" cx="0" cy="0" r="1" gradientTransform="rotate(49.205 -10.811 10.75)scale(3.01332 1.71904)" gradientUnits="userSpaceOnUse"><stop class="v8ajsgb1f"/><stop offset=".863" class="p8yzywbyh"/></radialGradient><radialGradient id="iYcSjqd" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 3.59375 -1.84893 1.73639 4.516 10.443)" gradientUnits="userSpaceOnUse"><stop class="q48-tbc4a"/><stop offset="1" class="gis-f2ndt"/></radialGradient><radialGradient id="inpkcyb" cx="0" cy="0" r="1" gradientTransform="translate(9.496 13.536)scale(7.645)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="a-a4g0boh"/><stop offset="1" class="spf0x5bup"/></radialGradient><radialGradient id="ihF3oRb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9375 0 0 -2.12905 16.64 16.589)" gradientUnits="userSpaceOnUse"><stop class="lf3sz40pc"/><stop offset="1" class="lmsk0gi8f"/></radialGradient><radialGradient id="idwC2kb" cx="0" cy="0" r="1" gradientTransform="matrix(.92187 1 -.64255 .59235 6.11 16.036)" gradientUnits="userSpaceOnUse"><stop class="bnd24b94j"/><stop offset=".965" class="x_1t01wrv"/></radialGradient><radialGradient id="iMeUG4c" cx="0" cy="0" r="1" gradientTransform="rotate(-32.216 35.06 -10.948)scale(2.84413 1.9628)" gradientUnits="userSpaceOnUse"><stop class="bnd24b94j"/><stop offset=".42" class="x_1t01wrv"/></radialGradient><radialGradient id="iFITFJp" cx="0" cy="0" r="1" gradientTransform="matrix(.16938 1.73438 -1.58998 .15528 12.281 15.16)" gradientUnits="userSpaceOnUse"><stop class="op31oijyr"/><stop offset=".877" class="pgo4l0cns"/></radialGradient><radialGradient id="i6ZYcOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.38573 -1.0945 1.06073 -.37383 8.206 12.965)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iJat3Je" cx="0" cy="0" r="1" gradientTransform="matrix(-.38573 -1.0945 1.06073 -.37383 11.175 12.965)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="il6Wo8d" cx="0" cy="0" r="1" gradientTransform="rotate(84.458 6.069 19.379)scale(4.21272 5.19287)" gradientUnits="userSpaceOnUse"><stop class="vq9hkubad"/><stop offset=".796" class="gn0ws_b8s"/></radialGradient><filter id="ipliFbb" width="2.788" height="6.272" x="14.012" y="18.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".4"/></filter><filter id="iIBNaGd" width="15.91" height="12.28" x="1.641" y="9.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.636111 0 0 0 0 0.642222 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3592"/></filter><filter id="iayMcmd" width="4.188" height="6.044" x="9.953" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".5"/></filter><filter id="ipgieic" width="1.899" height="2.805" x="6.851" y="11.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".25"/></filter><filter id="iS3o3Pc" width="1.899" height="2.805" x="9.882" y="11.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".25"/></filter><filter id="iPSOgLe" width="9.98" height="10.008" x="19.663" y="7.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".5"/></filter><filter id="iBVdaGZ" width="2.069" height="6.709" x="25.887" y="18.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".4"/></filter><filter id="ix2Zqye" width="9.25" height="13.798" x="21.609" y="12.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation="1"/></filter><filter id="i0huXod" width="2.478" height="2.623" x="10.759" y="22.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".35"/></filter><filter id="iAl8vpm" width=".65" height="2.431" x="29.003" y="19.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3592" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hippopotamus" /></template>
<style>
.a-a4g0boh {
  stop-color: var(--svg-color--e9877a, #E9877A);
  stop-opacity: 0;
}

.afjxy2bxw {
  stop-color: var(--svg-color--dc8490, #DC8490);
  stop-opacity: 0;
}

.ammx9od1y {
  d: path("M22 7.849c3.21 0 5.51 1.07 6.83 3.5c.52.94.81 2.03.82 3.18v3.73q0 .145-.01.288v3.292c0 .28-.22.5-.5.5s-.5-.22-.5-.5v-.888a4.1 4.1 0 0 1-1 .83v2.568c0 .28-.22.5-.5.5h-4.69c-.37 0-.61-.39-.45-.72l.3-.59c.183-.372.296-.778.33-1.19h-5.99v2c0 .28-.22.5-.5.5h-4.78a.5.5 0 0 1-.43-.75l.28-.5c.28-.49.43-1.05.43-1.62V20.35c-.946-.439-1.973-.716-3-.932v-7.6c0-2.19 1.78-3.97 3.97-3.97z");
}

.awz_eimzr {
  d: path("M8.011 13.849c-.28 0-.5-.22-.5-.5V12.34c0-.28.22-.5.5-.5s.5.22.5.5v1.008c0 .28-.22.5-.5.5");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bai2i2b0r {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.61 24.2c.155-.137.658-.695.777-.922");
}

.bnd24b94j {
  stop-color: var(--svg-color--815a57, #815A57);
}

.cevw3t_aw {
  d: path("M12.64 16.849h-5l-2.75 7.32c-.12.33.12.68.47.68h3.93c.21 0 .39-.13.47-.32z");
}

.ci3g-pbsd {
  d: path("M26.688 19.192h.469v5.109h-.469z");
}

.d3om1vbcl {
  stop-color: var(--svg-color--919193, #919193);
}

.deou2-nvv {
  stop-color: var(--svg-color--2a2233, #2A2233);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e17d1_hvc {
  d: path("M4.752 13.118c.288-.079.509-.327.509-.626V10.91c0-.87.7-1.57 1.57-1.57h5.32c.87 0 1.57.7 1.57 1.57v1.58c0 .3.221.548.51.626a4.226 4.226 0 0 1-1.11 8.304H5.87a4.226 4.226 0 0 1-1.119-8.301");
}

.ewpcvtbfj {
  stop-color: var(--svg-color--4d425b, #4D425B);
}

.ft5dv1b6b {
  fill: none;
}

.fwptkhrcc {
  d: path("M12.48 7.729c-.03-.58-.91-.56-.92.02v1.59h.26l.56-1.14a.9.9 0 0 0 .1-.47");
}

.gf8oxvbmt {
  stop-color: var(--svg-color--47474e, #47474E);
  stop-opacity: 0;
}

.gis-f2ndt {
  stop-color: var(--svg-color--4d4d55, #4D4D55);
  stop-opacity: 0;
}

.giuz38bmi {
  stop-color: var(--svg-color--dc8490, #DC8490);
}

.gn0ws_b8s {
  stop-color: var(--svg-color--8d8e91, #8D8E91);
  stop-opacity: 0;
}

.gw1a99b8j {
  stop-color: var(--svg-color--864d54, #864D54);
}

.h_bowvj6m {
  d: path("m6.65 17.089l-.56-.57a.59.59 0 0 1 0-.85c.24-.24.62-.24.85 0l.57.57c.24.24.24.62 0 .85s-.62.23-.86 0");
}

.h0av6ybac {
  stop-color: var(--svg-color--848485, #848485);
}

.hmg4m5ace {
  stop-color: var(--svg-color--e08d95, #E08D95);
}

.homoywb9x {
  stop-color: var(--svg-color--8261a0, #8261A0);
}

.ic5t1k9ki {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M29.328 21.896v-1.782");
}

.ig-1egbtx {
  stop-color: var(--svg-color--68696c, #68696C);
}

.ihmjjjigj {
  fill: var(--svg-color--6f7073, #6F7073);
  d: path("M22 7.849c3.21 0 5.51 1.07 6.83 3.5c.52.94.81 2.03.82 3.18v3.73q0 .145-.01.288v3.292c0 .28-.22.5-.5.5s-.5-.22-.5-.5v-.888a4.1 4.1 0 0 1-1 .83v2.568c0 .28-.22.5-.5.5h-4.69c-.37 0-.61-.39-.45-.72l.3-.59c.183-.372.296-.778.33-1.19h-5.99v2c0 .28-.22.5-.5.5h-4.78a.5.5 0 0 1-.43-.75l.28-.5c.28-.49.43-1.05.43-1.62V20.35c-.946-.439-1.973-.716-3-.932v-7.6c0-2.19 1.78-3.97 3.97-3.97z");
}

.j2k5oshtz {
  fill: var(--svg-color--46454a, #46454A);
  d: path("M10.832 13.747a.445.445 0 0 1-.45-.45v-.905c0-.252.198-.45.45-.45c.251 0 .449.198.449.45v.906c0 .251-.198.45-.45.45");
}

.j6pledb1h {
  stop-color: var(--svg-color--525257, #525257);
}

.j7tpg1sdw {
  stop-color: var(--svg-color--616264, #616264);
}

.jg0rpqp_y {
  stop-color: var(--svg-color--767779, #767779);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.ke56yvbts {
  stop-color: var(--svg-color--838487, #838487);
}

.kigo8pweb {
  stop-color: var(--svg-color--bd5750, #BD5750);
}

.l_9lssbff {
  stop-color: var(--svg-color--e7958a, #E7958A);
}

.l2wvi5z4b {
  stop-color: var(--svg-color--5d5d60, #5D5D60);
  stop-opacity: 0;
}

.lf3sz40pc {
  stop-color: var(--svg-color--f2aaa3, #F2AAA3);
}

.lmsk0gi8f {
  stop-color: var(--svg-color--f2aaa3, #F2AAA3);
  stop-opacity: 0;
}

.lslk0wbet {
  stop-color: var(--svg-color--c06e84, #C06E84);
}

.lxz-b4o1r {
  stop-color: var(--svg-color--534e5d, #534E5D);
}

.m4ym1g00h {
  stop-color: var(--svg-color--62487a, #62487A);
}

.m71eaeb7x {
  d: path("M16 19.583v4.672l-1.187-4.078z");
}

.m7n73jb2n {
  fill: var(--svg-color--46454a, #46454A);
  d: path("M7.8 13.747a.445.445 0 0 1-.45-.45v-.905c0-.252.199-.45.45-.45c.252 0 .45.198.45.45v.906c0 .251-.198.45-.45.45");
}

.me1q-ibjy {
  stop-color: var(--svg-color--a5517f, #A5517F);
  stop-opacity: 0;
}

.ms2befbgr {
  stop-color: var(--svg-color--4d425b, #4D425B);
  stop-opacity: 0;
}

.op31oijyr {
  stop-color: var(--svg-color--9b5961, #9B5961);
}

.ot1ijpbyp {
  d: path("M11.56 6.849c-.51 0-.92.41-.92.92v1.57h1.18l.56-1.14a.924.924 0 0 0-.82-1.35");
}

.out3ue2qu {
  d: path("M10.953 11.32v2.748c0 .138.112.25.25.25h1.688a.25.25 0 0 0 .25-.25v-3.544a.25.25 0 0 0-.357-.226l-1.687.796a.25.25 0 0 0-.144.226");
}

.p8yzywbyh {
  stop-color: var(--svg-color--8a8b8f, #8A8B8F);
  stop-opacity: 0;
}

.p90zc0bvq {
  d: path("M10.98 13.849c-.28 0-.5-.22-.5-.5V12.34c0-.28.22-.5.5-.5s.5.22.5.5v1.008c0 .28-.22.5-.5.5");
}

.pgo4l0cns {
  stop-color: var(--svg-color--864d54, #864D54);
  stop-opacity: 0;
}

.plp3jqqdp {
  stop-color: var(--svg-color--8261a0, #8261A0);
  stop-opacity: 0;
}

.pqdqm2bqx {
  stop-color: var(--svg-color--e08d95, #E08D95);
  stop-opacity: 0;
}

.q48-tbc4a {
  stop-color: var(--svg-color--4d4d55, #4D4D55);
}

.qavaavbor {
  stop-color: var(--svg-color--a5517f, #A5517F);
}

.qizwslptk {
  stop-color: var(--svg-color--433851, #433851);
}

.rqzwlbbqo {
  stop-color: var(--svg-color--838487, #838487);
  stop-opacity: 0;
}

.rsnxv5dvv {
  stop-color: var(--svg-color--47474e, #47474E);
}

.s1-qaqbvt {
  d: path("M23.64 16.849h-5l-2.75 7.32c-.12.33.12.68.47.68h3.93c.21 0 .39-.13.47-.32z");
}

.spf0x5bup {
  stop-color: var(--svg-color--e9877a, #E9877A);
}

.tafy_0bai {
  stop-color: var(--svg-color--62487a, #62487A);
  stop-opacity: 0;
}

.tz_56zbfh {
  d: path("m12.59 17.089l.57-.57c.24-.24.24-.62 0-.85a.59.59 0 0 0-.85 0l-.57.56c-.24.24-.24.62 0 .85a.6.6 0 0 0 .85.01");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ujgw73bje {
  stop-color: var(--svg-color--848485, #848485);
  stop-opacity: 0;
}

.uy6hh4bsz {
  d: path("M22.64 21.799c0-.61-.24-1.19-.67-1.62l-.33-.33h-5v2.49h6z");
}

.v13blqqdv {
  d: path("M5.87 19.009c-1.33 0-2.42-1.08-2.42-2.42s1.09-2.42 2.42-2.42h7.25c1.33 0 2.42 1.08 2.42 2.42s-1.08 2.42-2.42 2.42z");
}

.v8ajsgb1f {
  stop-color: var(--svg-color--8a8b8f, #8A8B8F);
}

.vdv14_bxl {
  stop-color: var(--svg-color--919193, #919193);
  stop-opacity: 0;
}

.vq9hkubad {
  stop-color: var(--svg-color--8d8e91, #8D8E91);
}

.x_1t01wrv {
  stop-color: var(--svg-color--402d2b, #402D2B);
}

.xbf18fbav {
  stop-color: var(--svg-color--5d5d60, #5D5D60);
}

.z0_w1acsl {
  stop-color: var(--svg-color--525257, #525257);
  stop-opacity: 0;
}

.z414gyb9w {
  d: path("M7.72 6.849c.51 0 .92.41.92.92v1.57H7.46l-.56-1.14a.924.924 0 0 1 .82-1.35");
}

.z8gfvabdb {
  cx: 24.653px;
  cy: 12.842px;
  rx: 4.289px;
  ry: 3.683px;
}

.zmoovbcxs {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m23.651 19.505l2.847 4.28a.25.25 0 0 0 .458-.139v-2.864a.25.25 0 0 1 .095-.196l1.713-1.35a.25.25 0 0 0 .095-.196v-4.691a.25.25 0 0 0-.25-.25h-4.75a.25.25 0 0 0-.25.25v5.018q0 .076.042.138");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.zqcjh-0dv {
  d: path("M6.8 7.729c.03-.58.91-.56.92.02v1.59h-.26l-.56-1.14a.9.9 0 0 1-.1-.47");
}

</style>
