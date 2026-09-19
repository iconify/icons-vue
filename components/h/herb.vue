<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTS9LJt)"><path class="lhw1owbib"/></g><g filter="url(#isKaI9X)"><path class="q79g-1b9d"/></g><g filter="url(#ilvNWGc)"><path class="yrslg5bhi"/></g><g filter="url(#iYivnqd)"><path class="nzoysty1c"/></g><g filter="url(#iLWLVFe)"><path class="f0p4w8bab"/></g><g filter="url(#iVnZtIc)"><path class="loxdptbpa"/></g><g filter="url(#iwQYamb)"><path fill="url(#iFmXGtX)" class="mib-me78i"/><path fill="url(#ifF4lAb)" class="mib-me78i"/><path fill="url(#ijGC5nc)" class="mib-me78i"/></g><g filter="url(#iaaliie)"><path fill="url(#i7InGKb)" class="abh1b_fgt"/></g><g filter="url(#ijPRi0d)"><path fill="url(#iKRcUOd)" class="xld_sxbbv"/><path fill="url(#iPxhWpc)" class="xld_sxbbv"/><path fill="url(#ib3XdYi)" class="xld_sxbbv"/></g><g filter="url(#iTfIQhe)"><path fill="url(#ic2RRLK)" class="nqhmrpbne"/></g><path class="l5ow1q8dl"/><path fill="url(#iM2IVfn)" class="fylhtd2_g"/><path fill="url(#ieTcaKc)" class="fylhtd2_g"/><path fill="url(#iIpuBub)" class="fylhtd2_g"/><path fill="url(#iI9ehbb)" class="fylhtd2_g"/><path fill="url(#iEBdKBc)" class="fylhtd2_g"/><g filter="url(#izs2hNb)"><path fill="url(#ixmZg3d)" class="bpi1shebq"/><path fill="url(#i41Kxob)" class="bpi1shebq"/><path fill="url(#ijpo3te)" class="bpi1shebq"/></g><g filter="url(#ijIsERb)"><path fill="url(#it78FGc)" class="vo_r9cbdv"/></g><g filter="url(#iWeovQb)"><path fill="url(#i5wxsMz)" class="jdu3uk1iz"/><path fill="url(#iH1kX3b)" class="jdu3uk1iz"/><path fill="url(#iFjY3jc)" class="jdu3uk1iz"/><path fill="url(#imAMQwd)" class="jdu3uk1iz"/></g><g filter="url(#iOYgIie)"><path fill="url(#im6FPoe)" class="ykapl_h4t"/></g><defs><radialGradient id="iFmXGtX" cx="0" cy="0" r="1" gradientTransform="matrix(.22601 14.46443 -6.8134 .10646 8.68 15.313)" gradientUnits="userSpaceOnUse"><stop class="vnu9sk6-v"/><stop offset="1" class="aqon51bod"/></radialGradient><radialGradient id="ifF4lAb" cx="0" cy="0" r="1" gradientTransform="matrix(.33037 -5.8125 3.38424 .19235 7.95 23.098)" gradientUnits="userSpaceOnUse"><stop class="fr3-e4lvz"/><stop offset="1" class="v5swsl7ak"/></radialGradient><radialGradient id="ijGC5nc" cx="0" cy="0" r="1" gradientTransform="matrix(-.78124 3.625 -.7357 -.15855 8.406 10.035)" gradientUnits="userSpaceOnUse"><stop class="pch0fyb_w"/><stop offset="1" class="kep_8eb_x"/></radialGradient><radialGradient id="iKRcUOd" cx="0" cy="0" r="1" gradientTransform="rotate(89.105 2.684 11.837)scale(11.3145 5.32699)" gradientUnits="userSpaceOnUse"><stop class="vnu9sk6-v"/><stop offset="1" class="aqon51bod"/></radialGradient><radialGradient id="iPxhWpc" cx="0" cy="0" r="1" gradientTransform="matrix(.25823 -4.54616 2.64562 .15028 13.908 15.056)" gradientUnits="userSpaceOnUse"><stop class="fr3-e4lvz"/><stop offset="1" class="v5swsl7ak"/></radialGradient><radialGradient id="ib3XdYi" cx="0" cy="0" r="1" gradientTransform="matrix(-.61072 2.83525 -.57516 -.1239 14.264 4.84)" gradientUnits="userSpaceOnUse"><stop class="pch0fyb_w"/><stop offset="1" class="kep_8eb_x"/></radialGradient><radialGradient id="iM2IVfn" cx="0" cy="0" r="1" gradientTransform="rotate(-162.658 13.396 1.86)scale(5.30757 7.17012)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ou81hovir"/><stop offset="1" class="ciolsz3lv"/></radialGradient><radialGradient id="ieTcaKc" cx="0" cy="0" r="1" gradientTransform="rotate(25.145 -2.082 44.737)scale(6.1168 8.26332)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="ou81hovir"/><stop offset="1" class="ciolsz3lv"/></radialGradient><radialGradient id="iIpuBub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29349 4.66987 -.5781 -.16012 24.383 2.189)" gradientUnits="userSpaceOnUse"><stop class="obs3nebal"/><stop offset="1" class="pon_hjb9f"/></radialGradient><radialGradient id="iI9ehbb" cx="0" cy="0" r="1" gradientTransform="rotate(115.337 12.26 9.208)scale(6.66023 3.31004)" gradientUnits="userSpaceOnUse"><stop class="lfv9xsb6g"/><stop offset="1" class="uqixmeb0c"/></radialGradient><radialGradient id="iEBdKBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39206 -.16508 .91852 -2.18144 20.877 10.815)" gradientUnits="userSpaceOnUse"><stop class="v_mee2b5b"/><stop offset="1" class="dx8f2jt3f"/></radialGradient><radialGradient id="ixmZg3d" cx="0" cy="0" r="1" gradientTransform="matrix(.33546 5.11608 -10.07227 .66044 24.627 16.729)" gradientUnits="userSpaceOnUse"><stop class="vnu9sk6-v"/><stop offset="1" class="aqon51bod"/></radialGradient><radialGradient id="i41Kxob" cx="0" cy="0" r="1" gradientTransform="matrix(.49037 -2.05589 4.76818 1.1373 23.546 19.482)" gradientUnits="userSpaceOnUse"><stop class="fr3-e4lvz"/><stop offset="1" class="v5swsl7ak"/></radialGradient><radialGradient id="ijpo3te" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2789 1.4502 -.42352 -.66553 28.35 15.307)" gradientUnits="userSpaceOnUse"><stop class="pch0fyb_w"/><stop offset="1" class="kep_8eb_x"/></radialGradient><radialGradient id="i5wxsMz" cx="0" cy="0" r="1" gradientTransform="rotate(86.246 -2.465 22.748)scale(6.55737 12.917)" gradientUnits="userSpaceOnUse"><stop class="vnu9sk6-v"/><stop offset="1" class="aqon51bod"/></radialGradient><radialGradient id="iH1kX3b" cx="0" cy="0" r="1" gradientTransform="rotate(-76.577 26.76 1.578)scale(2.70326 6.27273)" gradientUnits="userSpaceOnUse"><stop class="fr3-e4lvz"/><stop offset="1" class="v5swsl7ak"/></radialGradient><radialGradient id="iFjY3jc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49165 1.58204 -.52795 -.8315 24.618 22.109)" gradientUnits="userSpaceOnUse"><stop class="pch0fyb_w"/><stop offset="1" class="kep_8eb_x"/></radialGradient><radialGradient id="imAMQwd" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -2.75 9.207 1.674 18.188 28)" gradientUnits="userSpaceOnUse"><stop class="p012n-b0m"/><stop offset="1" class="egj1o1b7d"/></radialGradient><filter id="iTS9LJt" width="14.437" height="20.463" x="7.397" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.462745 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7824"/></filter><filter id="isKaI9X" width="13.475" height="19.94" x="8.389" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".2"/></filter><filter id="ilvNWGc" width="2.62" height="4.327" x="7.909" y="21.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".2"/></filter><filter id="iYivnqd" width="4.635" height="1.467" x="9.732" y="24.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".2"/></filter><filter id="iLWLVFe" width="4.635" height="1.467" x="15.755" y="17.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".2"/></filter><filter id="iVnZtIc" width="2.825" height="4.514" x="13.765" y="13.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".2"/></filter><filter id="iwQYamb" width="6.102" height="12.008" x="5" y="10.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.760784 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7824"/></filter><filter id="iaaliie" width="5.293" height="9.666" x="6.366" y="10.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".5"/></filter><filter id="ijPRi0d" width="4.814" height="9.397" x="11.601" y="5.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.784314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7824"/></filter><filter id="iTfIQhe" width="4.442" height="7.664" x="12.386" y="5.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".5"/></filter><filter id="izs2hNb" width="8.899" height="4.437" x="19.197" y="15.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.760784 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7824"/></filter><filter id="ijIsERb" width="7.906" height="3.248" x="20.57" y="14.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".5"/></filter><filter id="iWeovQb" width="11.352" height="5.619" x="13.437" y="21.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.760784 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7824"/></filter><filter id="iOYgIie" width="9.873" height="3.663" x="14.995" y="21.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7824" stdDeviation=".5"/></filter><linearGradient id="i7InGKb" x1="9.906" x2="8.62" y1="15.039" y2="15.743" gradientUnits="userSpaceOnUse"><stop class="ox3bptbhr"/><stop offset="1" class="iinmjybuq"/></linearGradient><linearGradient id="ic2RRLK" x1="15.267" x2="14.318" y1="8.811" y2="9.334" gradientUnits="userSpaceOnUse"><stop class="ox3bptbhr"/><stop offset="1" class="iinmjybuq"/></linearGradient><linearGradient id="it78FGc" x1="24.581" x2="24.454" y1="15.497" y2="16.573" gradientUnits="userSpaceOnUse"><stop class="ox3bptbhr"/><stop offset="1" class="iinmjybuq"/></linearGradient><linearGradient id="im6FPoe" x1="20.009" x2="19.839" y1="22.352" y2="23.787" gradientUnits="userSpaceOnUse"><stop class="ox3bptbhr"/><stop offset="1" class="iinmjybuq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:herb" /></template>
<style>
.abh1b_fgt {
  d: path("m10.338 16.28l-2.384-4.677c-1.033.67-.46 2.316-.118 2.906l2.47 4.76c.624-1.083.281-2.444.032-2.99");
}

.aqon51bod {
  stop-color: var(--svg-color--8ec347, #8EC347);
}

.bpi1shebq {
  d: path("m23.806 15.138l3.871.404a.24.24 0 0 1 .216.274a4.224 4.224 0 0 1-4.607 3.512l-3.87-.404a.24.24 0 0 1-.216-.275c.366-2.19 2.37-3.752 4.606-3.511");
}

.ciolsz3lv {
  stop-color: var(--svg-color--96c860, #96C860);
}

.dx8f2jt3f {
  stop-color: var(--svg-color--afce6d, #AFCE6D);
  stop-opacity: 0;
}

.egj1o1b7d {
  stop-color: var(--svg-color--c0ba90, #C0BA90);
  stop-opacity: 0;
}

.f0p4w8bab {
  stroke: var(--svg-color--77975c, #77975C);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.976 18.285l-3.807-.418");
}

.fr3-e4lvz {
  stop-color: var(--svg-color--b2c770, #B2C770);
}

.ft5dv1b6b {
  fill: none;
}

.fylhtd2_g {
  d: path("M24.084 2.293a.237.237 0 0 0-.329-.113c-3.105 1.659-4.42 5.442-2.992 8.66a.237.237 0 0 0 .328.113a6.727 6.727 0 0 0 2.993-8.66");
}

.iinmjybuq {
  stop-color: var(--svg-color--cfff73, #CFFF73);
  stop-opacity: 0;
}

.jdu3uk1iz {
  d: path("m19.348 21.682l5.021.524a.24.24 0 0 1 .218.274a5.404 5.404 0 0 1-5.909 4.562l-5.021-.524a.24.24 0 0 1-.217-.274a5.404 5.404 0 0 1 5.908-4.562");
}

.kep_8eb_x {
  stop-color: var(--svg-color--b1eb4b, #B1EB4B);
  stop-opacity: 0;
}

.l5ow1q8dl {
  fill: var(--svg-color--b2dc52, #B2DC52);
  d: path("M24.084 2.293a.237.237 0 0 0-.329-.113c-3.105 1.659-4.42 5.442-2.992 8.66a.237.237 0 0 0 .328.113a6.727 6.727 0 0 0 2.993-8.66");
}

.lfv9xsb6g {
  stop-color: var(--svg-color--c7fd61, #C7FD61);
}

.lhw1owbib {
  fill: var(--svg-color--4e7c2f, #4E7C2F);
  d: path("M9.386 29.528a.603.603 0 0 1-1.14-.394l1.123-3.247a.15.15 0 0 0-.007-.114l-1.803-3.707a.605.605 0 1 1 1.09-.53l1.159 2.383a.153.153 0 0 0 .278-.01c1.057-2.517 2.686-4.544 4.959-6.083l.1-.098l.008-.007a.18.18 0 0 0 .036-.206l-1.75-3.6a.605.605 0 1 1 1.09-.53l1.62 3.333a.148.148 0 0 0 .23.049a13.2 13.2 0 0 0 3.9-5.702l.38-1.09c.11-.32.45-.48.77-.37s.48.45.37.77l-.38 1.09a14.4 14.4 0 0 1-3.774 5.803a.153.153 0 0 0 .087.264l2.567.273c.33.03.57.33.54.66s-.33.57-.66.54l-4.087-.434a.14.14 0 0 0-.1.026l-.083.06c-.071.051-.148.107-.17.121c-2.22 1.507-3.788 3.574-4.726 6.068a.15.15 0 0 0 .124.2l3.542.37c.33.03.57.33.54.66s-.33.57-.66.54l-3.901-.407a.15.15 0 0 0-.158.1z");
}

.loxdptbpa {
  stroke: var(--svg-color--83a763, #83A763);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.078 17.77l-1.801-3.602");
}

.mib-me78i {
  d: path("m10.358 15.506l-2.21-4.535a.24.24 0 0 0-.332-.11c-2.519 1.377-3.541 4.5-2.268 7.105l2.21 4.535a.24.24 0 0 0 .332.11a5.41 5.41 0 0 0 2.268-7.105");
}

.nqhmrpbne {
  d: path("m15.588 9.728l-1.77-3.453c-.762.497-.335 1.712-.082 2.148l1.834 3.515c.459-.802.203-1.807.018-2.21");
}

.nzoysty1c {
  stroke: var(--svg-color--77975c, #77975C);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.953 25.816l-3.807-.418");
}

.obs3nebal {
  stop-color: var(--svg-color--c8ff74, #C8FF74);
}

.ou81hovir {
  stop-color: var(--svg-color--96c860, #96C860);
  stop-opacity: 0;
}

.ox3bptbhr {
  stop-color: var(--svg-color--cfff73, #CFFF73);
}

.p012n-b0m {
  stop-color: var(--svg-color--c0ba90, #C0BA90);
}

.pch0fyb_w {
  stop-color: var(--svg-color--b1eb4b, #B1EB4B);
}

.pon_hjb9f {
  stop-color: var(--svg-color--c8ff74, #C8FF74);
  stop-opacity: 0;
}

.q79g-1b9d {
  stroke: var(--svg-color--77975c, #77975C);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m8.906 29.144l1.844-5a11.6 11.6 0 0 1 2.734-4.172c2.047-1.984 4.032-2.86 5.375-4.797c1.344-1.937 1.953-3.25 2.485-5.094");
}

.uqixmeb0c {
  stop-color: var(--svg-color--c7fd61, #C7FD61);
  stop-opacity: 0;
}

.v_mee2b5b {
  stop-color: var(--svg-color--afce6d, #AFCE6D);
}

.v5swsl7ak {
  stop-color: var(--svg-color--b2c770, #B2C770);
  stop-opacity: 0;
}

.vnu9sk6-v {
  stop-color: var(--svg-color--b5e64b, #B5E64B);
}

.vo_r9cbdv {
  d: path("m23.61 15.545l3.866.34c-.174.893-1.46.955-1.96.884l-3.946-.375c.57-.727 1.598-.87 2.04-.85");
}

.xld_sxbbv {
  d: path("m15.788 9.116l-1.7-3.495a.24.24 0 0 0-.331-.109a4.227 4.227 0 0 0-1.729 5.535l1.7 3.494a.24.24 0 0 0 .332.108a4.23 4.23 0 0 0 1.728-5.533");
}

.ykapl_h4t {
  d: path("m18.715 22.415l5.153.453c-.231 1.19-1.946 1.274-2.612 1.18l-5.261-.501c.76-.97 2.13-1.159 2.72-1.132");
}

.yrslg5bhi {
  stroke: var(--svg-color--83a763, #83A763);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m8.422 22.082l1.594 3.422");
}

</style>
