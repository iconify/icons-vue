<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifK6qAd)"><path fill="url(#i1Kffwq)" class="vgqypybsp"/><path fill="url(#iYodJCj)" class="vgqypybsp"/></g><g filter="url(#i4OkEBd)"><path class="k46530bqd"/><path fill="url(#iHvzVje)" class="rw-5jyb7r"/><path fill="url(#iPiuFhc)" class="rw-5jyb7r"/><path fill="url(#iIFLl9X)" class="rw-5jyb7r"/></g><path fill="url(#iG8xR1d)" class="rw-5jyb7r"/><path fill="url(#iNSJ73b)" class="rw-5jyb7r"/><path fill="url(#iTzGkFe)" class="rw-5jyb7r"/><g filter="url(#i1MPnod)"><path fill="url(#i6JWlxU)" class="yz8a8ebre"/><path fill="url(#ihgpRfb)" class="yz8a8ebre"/><path fill="url(#ibEZ6Qi)" class="yz8a8ebre"/></g><path fill="url(#iuyVGsp)" class="uowfckvfp"/><path fill="url(#i9I4ehb)" class="uowfckvfp"/><path fill="url(#inNcZ6b)" class="uowfckvfp"/><path fill="url(#iGqXETd)" class="uowfckvfp"/><path fill="url(#ienxOcc)" class="uowfckvfp"/><g filter="url(#iTrMwzb)" class="o51_cfbva"><path stroke="url(#iqquKwd)" class="vrm1jvb0k"/><path stroke="url(#icACgVm)" class="vrm1jvb0k"/></g><g filter="url(#iQ4rfyb)"><path class="t30dirltu"/></g><g filter="url(#ioq4GRc)"><path class="tm0r2_2hh"/></g><g filter="url(#iA2MSKe)"><path fill="url(#i6bqu2b)" class="po_107b8e"/><path fill="url(#iw5Txoc)" class="po_107b8e"/><path fill="url(#iIQYbEd)" class="po_107b8e"/></g><path fill="url(#i51UuHo)" class="ewkgs-nte"/><path fill="url(#iCH5eIe)" class="ewkgs-nte"/><path fill="url(#iX5ugse)" class="ewkgs-nte"/><path fill="url(#iNcPtJb)" class="ewkgs-nte"/><g filter="url(#io7DETb)"><path class="hrxtdpi4o"/><path fill="url(#itqIeWb)" class="w6rcxhbby"/><path fill="url(#i6DpH5c)" class="w6rcxhbby"/><path fill="url(#ioFpmgh)" class="w6rcxhbby"/></g><path fill="url(#iNPP1td)" class="w6rcxhbby"/><g filter="url(#iD4ihpn)"><path fill="url(#iwnIy2b)" class="bhm7fbccc"/></g><g filter="url(#izCD37c)"><path fill="url(#inI4oFe)" class="enu7rnb_v"/></g><g filter="url(#iEOtwSO)"><path class="icabobigc"/></g><g filter="url(#iapDWpb)"><path fill="url(#ifvLuze)" class="gh4dodblb"/></g><g filter="url(#ilsBvre)"><path fill="url(#iIj4Gwd)" class="czz2g9cpn"/></g><defs><radialGradient id="i1Kffwq" cx="0" cy="0" r="1" gradientTransform="matrix(5.18748 -3.28129 2.0747 3.27994 15.446 29.57)" gradientUnits="userSpaceOnUse"><stop class="oe3y4vbqf"/><stop offset="0" class="qzsq__aku"/><stop offset="1" class="oe3y4vbqf"/></radialGradient><radialGradient id="iYodJCj" cx="0" cy="0" r="1" gradientTransform="matrix(3.0516 -1.76942 .60604 1.0452 15.117 29.514)" gradientUnits="userSpaceOnUse"><stop class="w5j3vf2yi"/><stop offset="1" class="j09s_7bvl"/></radialGradient><radialGradient id="iHvzVje" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01163 -12.4153 0 26.697 18.275)" gradientUnits="userSpaceOnUse"><stop class="ksmxe9b1k"/><stop offset="1" class="mbbw6obru"/></radialGradient><radialGradient id="iPiuFhc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.34375 0 0 -1.71875 30.821 20.945)" gradientUnits="userSpaceOnUse"><stop class="jjklggbfo"/><stop offset="1" class="quub0mbyo"/></radialGradient><radialGradient id="iIFLl9X" cx="0" cy="0" r="1" gradientTransform="rotate(171.87 13.906 8.122)scale(3.97748 2.8903)" gradientUnits="userSpaceOnUse"><stop class="eybi48asf"/><stop offset="1" class="w2c8rvnzp"/></radialGradient><radialGradient id="iG8xR1d" cx="0" cy="0" r="1" gradientTransform="rotate(160.313 13.748 8.116)scale(5.93738 7.09013)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="r-4m4ls2d"/><stop offset="1" class="adb0-lbtf"/></radialGradient><radialGradient id="iNSJ73b" cx="0" cy="0" r="1" gradientTransform="rotate(-108.02 18.827 -3.295)scale(2.23821 9.18924)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="unhzkabxh"/><stop offset="1" class="s_n_7nbja"/></radialGradient><radialGradient id="iTzGkFe" cx="0" cy="0" r="1" gradientTransform="matrix(3.62508 -.92317 .29444 1.1562 26.375 11.23)" gradientUnits="userSpaceOnUse"><stop class="ndxlh839d"/><stop offset="1" class="yiw3td3cv"/></radialGradient><radialGradient id="ihgpRfb" cx="0" cy="0" r="1" gradientTransform="rotate(-68.344 15.038 -13)scale(1.14319 5.74498)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="csazurs5s"/><stop offset=".799" class="w6ob-ac3n"/></radialGradient><radialGradient id="ibEZ6Qi" cx="0" cy="0" r="1" gradientTransform="matrix(7.15625 -1.46875 1.6512 8.04525 17.509 8.758)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="lflmfzgsf"/><stop offset=".988" class="s9im-ghfp"/></radialGradient><radialGradient id="iuyVGsp" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.75 -12.4075 0 15.93 12.195)" gradientUnits="userSpaceOnUse"><stop class="wy1sq25mx"/><stop offset="1" class="sky7cmovp"/></radialGradient><radialGradient id="i9I4ehb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.125 30.6406 0 15.93 22.508)" gradientUnits="userSpaceOnUse"><stop class="d8jt7eb6h"/><stop offset="1" class="yfpg4fbgp"/></radialGradient><radialGradient id="inNcZ6b" cx="0" cy="0" r="1" gradientTransform="matrix(-24.9375 0 0 -22.9531 30.071 13.46)" gradientUnits="userSpaceOnUse"><stop offset=".875" class="n5few9bmp"/><stop offset=".99" class="xx6_ns0zy"/></radialGradient><radialGradient id="iGqXETd" cx="0" cy="0" r="1" gradientTransform="matrix(-12.5625 0 0 -7.79947 18.946 10.133)" gradientUnits="userSpaceOnUse"><stop offset=".364" class="so_m05reo"/><stop offset="1" class="cxjzlgb8g"/></radialGradient><radialGradient id="ienxOcc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5625 -12.49996 15.90696 -9.62373 16.665 17.852)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="ftk4j4bor"/><stop offset="1" class="p81-j5b_p"/></radialGradient><radialGradient id="icACgVm" cx="0" cy="0" r="1" gradientTransform="matrix(3.76993 -2.28738 3.79992 6.26281 10.116 14.541)" gradientUnits="userSpaceOnUse"><stop class="tvlted_0y"/><stop offset="1" class="kbrkgpbst"/></radialGradient><radialGradient id="iw5Txoc" cx="0" cy="0" r="1" gradientTransform="rotate(148.577 4.524 3.595)scale(.65932 .62966)" gradientUnits="userSpaceOnUse"><stop class="j87u4_a2r"/><stop offset="1" class="y5quubg8w"/></radialGradient><radialGradient id="iIQYbEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90925 2.10428 -.69727 -.63265 8.326 7.23)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="xtsep34hf"/><stop offset="1" class="gfsuzjbon"/></radialGradient><radialGradient id="iNcPtJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.54321 -1.14062 4.08404 5.52552 22.43 5.18)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="mzpc7w4ji"/><stop offset=".609" class="e8ks04b2s"/></radialGradient><radialGradient id="i6DpH5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.01464 2.25 -8.64565 3.89876 17.135 13.977)" gradientUnits="userSpaceOnUse"><stop offset=".529" class="w317104hw"/><stop offset=".932" class="pc3igcbvn"/></radialGradient><radialGradient id="ioFpmgh" cx="0" cy="0" r="1" gradientTransform="matrix(-.80469 .20312 -.12704 -.50328 21.626 12.86)" gradientUnits="userSpaceOnUse"><stop class="k55xjabfz"/><stop offset="1" class="hvcn27b-j"/></radialGradient><filter id="ifK6qAd" width="7.01" height="4.6" x="14.155" y="25.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.447059 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/></filter><filter id="i4OkEBd" width="28" height="21.307" x="2" y="6.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.192157 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/></filter><filter id="i1MPnod" width="11.781" height="6.582" x="14.071" y="2.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.627451 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.662745 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_8166" result="effect2_innerShadow_28327_8166"/></filter><filter id="iTrMwzb" width="17.147" height="11.459" x="7.396" y="4.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8166" stdDeviation=".2"/></filter><filter id="iQ4rfyb" width="17.375" height="6.516" x="6.293" y="9.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.203922 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/></filter><filter id="ioq4GRc" width="15.547" height="10.997" x="8.196" y="4.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.341176 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.54902 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_8166" result="effect2_innerShadow_28327_8166"/></filter><filter id="iA2MSKe" width="5.131" height="8.266" x="5.228" y="4.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.611765 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/></filter><filter id="io7DETb" width="8.828" height="4.155" x="12.721" y="12.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.54902 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_8166"/></filter><filter id="iD4ihpn" width="4.326" height="5.434" x="5.989" y="4.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8166" stdDeviation=".2"/></filter><filter id="izCD37c" width="7.403" height="2.419" x="14.065" y="2.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8166" stdDeviation=".2"/></filter><filter id="iEOtwSO" width="5.555" height="11.21" x="21.06" y="2.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8166" stdDeviation=".3"/></filter><filter id="iapDWpb" width="5.286" height="3.28" x="17.32" y="22.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8166" stdDeviation=".25"/></filter><filter id="ilsBvre" width="4.485" height="3.463" x="20.728" y="24.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8166" stdDeviation=".25"/></filter><linearGradient id="i6JWlxU" x1="21.759" x2="13.79" y1="6.176" y2="2.985" gradientUnits="userSpaceOnUse"><stop class="j5y_qjkke"/><stop offset="1" class="oou96xbmu"/></linearGradient><linearGradient id="iqquKwd" x1="22.946" x2="8.884" y1="14.07" y2="7.195" gradientUnits="userSpaceOnUse"><stop class="tl4ws7biz"/><stop offset="1" class="bl1khvb-v"/></linearGradient><linearGradient id="i6bqu2b" x1="7.743" x2="5.665" y1="4.117" y2="12.695" gradientUnits="userSpaceOnUse"><stop offset=".135" class="i4ltob86u"/><stop offset=".933" class="mfs03pmkl"/></linearGradient><linearGradient id="i51UuHo" x1="22.509" x2="27.384" y1="3.008" y2="13.133" gradientUnits="userSpaceOnUse"><stop class="isg6nebem"/><stop offset=".625" class="z-idq_bvg"/></linearGradient><linearGradient id="iCH5eIe" x1="26.29" x2="26.196" y1="13.539" y2="12.914" gradientUnits="userSpaceOnUse"><stop class="wwpy4bx_w"/><stop offset="1" class="mgpl5kb0z"/></linearGradient><linearGradient id="iX5ugse" x1="21.227" x2="21.61" y1="2.805" y2="3.148" gradientUnits="userSpaceOnUse"><stop class="i8m2s2azp"/><stop offset="1" class="bpouxpbgj"/></linearGradient><linearGradient id="itqIeWb" x1="12.821" x2="17.759" y1="16.375" y2="15.695" gradientUnits="userSpaceOnUse"><stop class="a7g358bkr"/><stop offset="1" class="ogvllacot"/></linearGradient><linearGradient id="iNPP1td" x1="12.915" x2="14.321" y1="16.164" y2="16.164" gradientUnits="userSpaceOnUse"><stop class="iz27wdyyt"/><stop offset="1" class="bfqh7jzyr"/></linearGradient><linearGradient id="iwnIy2b" x1="9.814" x2="6.879" y1="4.653" y2="8.636" gradientUnits="userSpaceOnUse"><stop class="xxfcvcb_d"/><stop offset="1" class="y5xweczmu"/></linearGradient><linearGradient id="inI4oFe" x1="14.665" x2="15.412" y1="3.133" y2="1.225" gradientUnits="userSpaceOnUse"><stop class="eh80ye77s"/><stop offset="1" class="p5m6kbopy"/></linearGradient><linearGradient id="ifvLuze" x1="22.106" x2="19.915" y1="24.386" y2="25.399" gradientUnits="userSpaceOnUse"><stop class="o2wxs-bxn"/><stop offset="1" class="vln-urbsy"/></linearGradient><linearGradient id="iIj4Gwd" x1="24.431" x2="22.173" y1="26.539" y2="24.461" gradientUnits="userSpaceOnUse"><stop class="o2wxs-bxn"/><stop offset="1" class="vln-urbsy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:empty-nest" /></template>
<style>
.a7g358bkr {
  stop-color: var(--svg-color--efb888, #EFB888);
}

.adb0-lbtf {
  stop-color: var(--svg-color--8d5f4e, #8D5F4E);
  stop-opacity: 0;
}

.bfqh7jzyr {
  stop-color: var(--svg-color--f0b989, #F0B989);
  stop-opacity: 0;
}

.bhm7fbccc {
  d: path("M9.895 4.472a.1.1 0 0 1-.022.14C9.068 5.191 7.497 6.56 6.583 9a.1.1 0 0 1-.188-.07c.933-2.488 2.537-3.885 3.36-4.48a.1.1 0 0 1 .14.022");
}

.bl1khvb-v {
  stop-color: var(--svg-color--ffdca6, #FFDCA6);
}

.bpouxpbgj {
  stop-color: var(--svg-color--d6a374, #D6A374);
  stop-opacity: 0;
}

.csazurs5s {
  stop-color: var(--svg-color--ffcc8d, #FFCC8D);
}

.cxjzlgb8g {
  stop-color: var(--svg-color--ffefab, #FFEFAB);
  stop-opacity: 0;
}

.czz2g9cpn {
  d: path("m24.459 26.197l-2.423-1.428a.535.535 0 1 0-.538.927l2.443 1.394a.516.516 0 0 0 .518-.893");
}

.d8jt7eb6h {
  stop-color: var(--svg-color--c47076, #C47076);
}

.e8ks04b2s {
  stop-color: var(--svg-color--ee9b5a, #EE9B5A);
  stop-opacity: 0;
}

.eh80ye77s {
  stop-color: var(--svg-color--ffd6a0, #FFD6A0);
}

.enu7rnb_v {
  d: path("M20.782 4.829c-2.49-1.183-5.28-1.245-6.102-1.184a.2.2 0 1 1-.03-.4c.865-.063 3.731 0 6.304 1.223a.2.2 0 1 1-.172.361");
}

.ewkgs-nte {
  d: path("M21.32 2.89a.5.5 0 0 1 .697-.118c.73.52 1.854 1.39 2.825 3.004c.969 1.611 1.847 4.095 1.878 7.322c.01.276-.18.508-.457.519a.5.5 0 0 1-.52-.48c-.13-3.249-.888-5.399-1.758-6.846c-.87-1.446-1.87-2.223-2.547-2.704a.5.5 0 0 1-.118-.697");
}

.eybi48asf {
  stop-color: var(--svg-color--834c50, #834C50);
}

.ft5dv1b6b {
  fill: none;
}

.ftk4j4bor {
  stop-color: var(--svg-color--d2926b, #D2926B);
  stop-opacity: 0;
}

.gfsuzjbon {
  stop-color: var(--svg-color--e5b078, #E5B078);
  stop-opacity: 0;
}

.gh4dodblb {
  d: path("M22.106 24.114v.215l-1.799 1.248l-2.487-2.28z");
}

.hrxtdpi4o {
  fill: var(--svg-color--e9b281, #E9B281);
  d: path("M21.383 12.667a.5.5 0 0 1 .038.706c-2.805 3.123-6.552 3.22-8.2 3.22a.5.5 0 0 1 0-1c1.617 0 4.96-.11 7.456-2.888a.5.5 0 0 1 .706-.038");
}

.hvcn27b-j {
  stop-color: var(--svg-color--ffdfaa, #FFDFAA);
  stop-opacity: 0;
}

.i4ltob86u {
  stop-color: var(--svg-color--f9c58e, #F9C58E);
}

.i8m2s2azp {
  stop-color: var(--svg-color--d6a374, #D6A374);
}

.icabobigc {
  fill: var(--svg-color--ffedb0, #FFEDB0);
  d: path("M21.695 3.035a.2.2 0 0 1 .278-.052c1.37.941 4.344 3.973 4.017 9.786a.2.2 0 1 1-.4-.022c.318-5.648-2.567-8.557-3.843-9.434a.2.2 0 0 1-.052-.278");
}

.isg6nebem {
  stop-color: var(--svg-color--f5bc89, #F5BC89);
}

.iz27wdyyt {
  stop-color: var(--svg-color--f0b989, #F0B989);
}

.j09s_7bvl {
  stop-color: var(--svg-color--6d9553, #6D9553);
  stop-opacity: 0;
}

.j5y_qjkke {
  stop-color: var(--svg-color--ffc78a, #FFC78A);
}

.j87u4_a2r {
  stop-color: var(--svg-color--ffe9b4, #FFE9B4);
}

.jjklggbfo {
  stop-color: var(--svg-color--805550, #805550);
}

.k46530bqd {
  fill: var(--svg-color--633c3e, #633C3E);
  d: path("M2 18.998s.278.057.708-.115S30 7.803 30 7.803v5l-15.495 6.283H30v4.912h-7.255c-.424 0-.424.378-.29.455l1.813 1.108c1.31.756.769 2.548-.744 2.548c-.259 0-.514-.068-.739-.198l-5.753-3.372c-.906-.586-1.396-.541-2.273-.541H2z");
}

.k55xjabfz {
  stop-color: var(--svg-color--ffdfaa, #FFDFAA);
}

.kbrkgpbst {
  stop-color: var(--svg-color--eead84, #EEAD84);
  stop-opacity: 0;
}

.ksmxe9b1k {
  stop-color: var(--svg-color--7a5349, #7A5349);
}

.lflmfzgsf {
  stop-color: var(--svg-color--d5803f, #D5803F);
  stop-opacity: 0.241;
}

.mbbw6obru {
  stop-color: var(--svg-color--7a5349, #7A5349);
  stop-opacity: 0;
}

.mfs03pmkl {
  stop-color: var(--svg-color--d6a072, #D6A072);
}

.mgpl5kb0z {
  stop-color: var(--svg-color--f7c696, #F7C696);
  stop-opacity: 0;
}

.mzpc7w4ji {
  stop-color: var(--svg-color--ee9b5a, #EE9B5A);
}

.n5few9bmp {
  stop-color: var(--svg-color--d39f70, #D39F70);
  stop-opacity: 0;
}

.ndxlh839d {
  stop-color: var(--svg-color--996557, #996557);
}

.o2wxs-bxn {
  stop-color: var(--svg-color--7b5d59, #7B5D59);
}

.o51_cfbva {
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
}

.oe3y4vbqf {
  stop-color: var(--svg-color--56845b, #56845B);
}

.ogvllacot {
  stop-color: var(--svg-color--eeb687, #EEB687);
  stop-opacity: 0;
}

.oou96xbmu {
  stop-color: var(--svg-color--feca97, #FECA97);
}

.p5m6kbopy {
  stop-color: var(--svg-color--ffd6a0, #FFD6A0);
  stop-opacity: 0;
}

.p81-j5b_p {
  stop-color: var(--svg-color--d59065, #D59065);
}

.pc3igcbvn {
  stop-color: var(--svg-color--da7e63, #DA7E63);
}

.po_107b8e {
  d: path("M10.184 4.354a.5.5 0 0 1-.162.689c-1.074.664-3.393 2.956-3.797 6.89a.5.5 0 1 1-.995-.101c.44-4.284 2.965-6.835 4.266-7.64a.5.5 0 0 1 .688.162");
}

.quub0mbyo {
  stop-color: var(--svg-color--805550, #805550);
  stop-opacity: 0;
}

.qzsq__aku {
  stop-color: var(--svg-color--77a159, #77A159);
}

.r-4m4ls2d {
  stop-color: var(--svg-color--8d5f4e, #8D5F4E);
}

.rw-5jyb7r {
  d: path("M2 18.998s.278.057.708-.115S30 7.803 30 7.803v5l-15.495 6.283H30v4.912h-7.255c-.424 0-.424.378-.29.455l1.813 1.108c1.31.756.769 2.548-.744 2.548c-.259 0-.514-.068-.739-.198l-5.753-3.372c-.906-.586-1.396-.541-2.273-.541H2z");
}

.s_n_7nbja {
  stop-color: var(--svg-color--7e494f, #7E494F);
  stop-opacity: 0;
}

.s9im-ghfp {
  stop-color: var(--svg-color--d5803f, #D5803F);
}

.sky7cmovp {
  stop-color: var(--svg-color--f2a989, #F2A989);
}

.so_m05reo {
  stop-color: var(--svg-color--ffefab, #FFEFAB);
}

.t30dirltu {
  fill: var(--svg-color--8a5948, #8A5948);
  d: path("M23.667 11.846c-.373 2.042-2.492 3.74-4.815 3.74h-5.765c-2.244 0-4.33-1.683-4.794-3.996c.44-1.955 2.295-2.52 3.622-2.52h7.984c2.305 0 3.474.977 3.768 2.776");
}

.tl4ws7biz {
  stop-color: var(--svg-color--f2b97d, #F2B97D);
}

.tm0r2_2hh {
  fill: var(--svg-color--b4784d, #B4784D);
  d: path("M13.087 5.727c-2.422 0-4.89 1.908-4.89 4.609c0 .172.008.624.025.793q.025.234.07.461c.44-1.955 2.296-2.52 3.623-2.52h7.984c2.305 0 3.474.977 3.768 2.776c-.27 1.476-1.451 2.772-2.963 3.377c1.726-.69 3.021-2.281 3.021-4.012c.012-.14.018-.875.018-1.016c0-2.437-2.172-4.468-5.266-4.468z");
}

.tvlted_0y {
  stop-color: var(--svg-color--eead84, #EEAD84);
}

.unhzkabxh {
  stop-color: var(--svg-color--7e494f, #7E494F);
}

.uowfckvfp {
  d: path("M5.134 12.977a8 8 0 0 1 8-8h5.593a8 8 0 0 1 8 8v.968a8 8 0 0 1-8 8h-5.593a8 8 0 0 1-8-8z");
}

.vgqypybsp {
  d: path("M21.166 26.479V25.9h-2.737c-1.734 0-3.774 1.829-3.774 3.623c0 .213.173.385.385.385l2.54.092c1.892 0 3.586-1.628 3.586-3.521");
}

.vln-urbsy {
  stop-color: var(--svg-color--7b5d59, #7B5D59);
  stop-opacity: 0;
}

.vrm1jvb0k {
  d: path("M8.196 10.336c0-2.701 2.469-4.61 4.89-4.61h5.391c3.094 0 5.266 2.032 5.266 4.47c0 .14-.006.875-.018 1.015q0 .322-.058.635v.006c-.273 1.474-1.453 2.767-2.963 3.371a5 5 0 0 1-1.852.363h-5.765c-2.244 0-4.33-1.683-4.794-3.996a5 5 0 0 1-.07-.461c-.018-.169-.027-.62-.027-.793Z");
}

.w2c8rvnzp {
  stop-color: var(--svg-color--834c50, #834C50);
  stop-opacity: 0;
}

.w317104hw {
  stop-color: var(--svg-color--e89f85, #E89F85);
  stop-opacity: 0;
}

.w5j3vf2yi {
  stop-color: var(--svg-color--6d9553, #6D9553);
}

.w6ob-ac3n {
  stop-color: var(--svg-color--ffcc8d, #FFCC8D);
  stop-opacity: 0;
}

.w6rcxhbby {
  d: path("M21.383 12.667a.5.5 0 0 1 .038.706c-2.805 3.123-6.552 3.22-8.2 3.22a.5.5 0 0 1 0-1c1.617 0 4.96-.11 7.456-2.888a.5.5 0 0 1 .706-.038");
}

.wwpy4bx_w {
  stop-color: var(--svg-color--f7c696, #F7C696);
}

.wy1sq25mx {
  stop-color: var(--svg-color--e6b37b, #E6B37B);
}

.xtsep34hf {
  stop-color: var(--svg-color--ffd9a2, #FFD9A2);
}

.xx6_ns0zy {
  stop-color: var(--svg-color--d39f70, #D39F70);
}

.xxfcvcb_d {
  stop-color: var(--svg-color--ffd5a1, #FFD5A1);
}

.y5quubg8w {
  stop-color: var(--svg-color--ffe9b4, #FFE9B4);
  stop-opacity: 0;
}

.y5xweczmu {
  stop-color: var(--svg-color--ffd5a1, #FFD5A1);
  stop-opacity: 0;
}

.yfpg4fbgp {
  stop-color: var(--svg-color--d8947b, #D8947B);
  stop-opacity: 0;
}

.yiw3td3cv {
  stop-color: var(--svg-color--996557, #996557);
  stop-opacity: 0;
}

.yz8a8ebre {
  d: path("M19.785 4.846c-1.99-.77-3.972-.95-5.162-.825a.5.5 0 1 1-.103-.995c1.357-.141 3.497.064 5.626.888c2.135.826 4.303 2.293 5.644 4.71a.5.5 0 1 1-.875.486c-1.196-2.158-3.146-3.496-5.13-4.264");
}

.z-idq_bvg {
  stop-color: var(--svg-color--f8cf9a, #F8CF9A);
}

</style>
