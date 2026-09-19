<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ja8i80b9n"/><g filter="url(#iUb3QKb)"><ellipse fill="url(#iOt6C0d)" transform="rotate(26.087 16.732 9.302)" class="wu2_0tzks"/></g><g filter="url(#i2b1PVd)"><path fill="url(#iVu8cxd)" class="bpbu7dv4a"/><path fill="url(#iraxHEW)" class="bpbu7dv4a"/></g><g filter="url(#iMNEHfd)"><circle fill="url(#iYYoZRb)" class="lf_pakb2d"/></g><circle fill="url(#il1OIyk)" class="qilsfwmjr"/><circle fill="url(#icZk5ie)" class="qilsfwmjr"/><g filter="url(#ibWEhvd)"><circle class="mxna0tbja"/></g><g filter="url(#ihbS5Gc)"><path fill="url(#i06ADAd)" class="k9hnl5bgc"/><path fill="url(#iBvvrTb)" class="k9hnl5bgc"/></g><path fill="url(#igxj1od)" class="zxkw08qcp"/><path fill="url(#iO10hbd)" class="zxkw08qcp"/><path fill="url(#icgTGNc)" class="zxkw08qcp"/><path fill="url(#i3ogRNc)" class="zxkw08qcp"/><path fill="url(#ia1TVLc)" class="zxkw08qcp"/><g filter="url(#i3d7Ppe)"><path stroke="url(#i6ABl7b)" class="rcqia1kwr"/></g><g filter="url(#iInl0LF)"><path stroke="url(#iTHbiVd)" class="shcafccup"/></g><rect fill="url(#i4dg7ff)" class="hf5wm2mfe"/><rect fill="url(#i8JT7hd)" class="nnp22abze"/><rect fill="url(#irj2PYb)" class="nnp22abze"/><g filter="url(#iyY9xgc)"><path class="infs38bwt"/><path fill="url(#iJXZ0Rb)" class="fgqhdzbrg"/></g><path class="i2g6mlz6l"/><path fill="url(#iShd0vb)" class="bjp4tgbbt"/><path fill="url(#iEuiVVd)" class="bjp4tgbbt"/><path fill="url(#ioVccre)" class="bjp4tgbbt"/><path fill="url(#iZULrWJ)" class="kq103abhv"/><g filter="url(#iOmkT3c)"><path stroke="url(#irisOtb)" class="ucgxbccuf"/></g><g filter="url(#i9tjUbc)"><path stroke="url(#idPYdzb)" class="jqsrlfe5i"/></g><g filter="url(#iuRC5XG)"><path stroke="url(#iptkFKb)" class="qb8dbxb5j"/></g><g filter="url(#iB6UIVV)"><path fill="url(#iLuGTld)" class="u1wxr7b2p"/></g><defs><linearGradient id="iVu8cxd" x1="12.43" x2="9.775" y1="12.674" y2="18.067" gradientUnits="userSpaceOnUse"><stop class="a5-5f3bjl"/><stop offset="1" class="c8hqtvbke"/></linearGradient><linearGradient id="iraxHEW" x1="13.092" x2="15.02" y1="27.073" y2="21.681" gradientUnits="userSpaceOnUse"><stop offset=".218" class="cp6t-lt6u"/><stop offset="1" class="zc_tl-b2g"/></linearGradient><linearGradient id="iYYoZRb" x1="14.005" x2="11.79" y1="20.299" y2="24.197" gradientUnits="userSpaceOnUse"><stop offset=".34" class="vkm05yehh"/><stop offset="1" class="dl5923bfb"/></linearGradient><linearGradient id="il1OIyk" x1="11.35" x2="11.35" y1="19" y2="24.784" gradientUnits="userSpaceOnUse"><stop class="u5e9-9bjf"/><stop offset="1" class="e95bxobvz"/></linearGradient><linearGradient id="i06ADAd" x1="11.164" x2="19.298" y1="30.929" y2="-.279" gradientUnits="userSpaceOnUse"><stop class="npfpicb6j"/><stop offset="1" class="m8ss-00uh"/></linearGradient><linearGradient id="i6ABl7b" x1="24.09" x2="16.95" y1="11.379" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="j_li4o9eq"/><stop offset=".51" class="iqk_b94ku"/><stop offset="1" class="j_li4o9eq"/></linearGradient><linearGradient id="iTHbiVd" x1="8.155" x2="20.627" y1="2.492" y2="23.8" gradientUnits="userSpaceOnUse"><stop class="x6wmc3bjj"/><stop offset=".698" class="ve370msop"/></linearGradient><linearGradient id="i4dg7ff" x1="27.056" x2="27.056" y1="10.474" y2="15.429" gradientUnits="userSpaceOnUse"><stop class="kdl2hbbyb"/><stop offset="1" class="p4a1uebzz"/></linearGradient><linearGradient id="i8JT7hd" x1="27.593" x2="27.593" y1="15.688" y2="14.575" gradientUnits="userSpaceOnUse"><stop class="d7eywim1k"/><stop offset="1" class="sqji9tbob"/></linearGradient><linearGradient id="irj2PYb" x1="27.056" x2="27.056" y1="10.397" y2="10.866" gradientUnits="userSpaceOnUse"><stop class="eu-87q5qq"/><stop offset="1" class="e14ccpbpi"/></linearGradient><linearGradient id="ioVccre" x1="22.861" x2="22.861" y1="19.858" y2="17.213" gradientUnits="userSpaceOnUse"><stop class="nf1xib-zk"/><stop offset="1" class="stmsp0bcc"/></linearGradient><linearGradient id="irisOtb" x1="14.833" x2="6.677" y1="1.892" y2="8.939" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="idPYdzb" x1="6.239" x2="10.187" y1="13.249" y2="17.881" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="iptkFKb" x1="16.42" x2="30.608" y1="2.189" y2="7.394" gradientUnits="userSpaceOnUse"><stop class="h5tsjybzx"/><stop offset=".123" class="sd9-1cnwp"/><stop offset=".542" class="iab0nwb4s"/><stop offset=".763" class="borhhobgo"/></linearGradient><linearGradient id="iLuGTld" x1="27.716" x2="27.716" y1="9.624" y2="14.702" gradientUnits="userSpaceOnUse"><stop offset=".152" class="g4udvybro"/><stop offset=".5" class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><radialGradient id="iOt6C0d" cx="0" cy="0" r="1" gradientTransform="rotate(-91.906 15.033 -1.2)scale(8.56593 14.9391)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="hcgem_45j"/><stop offset=".922" class="ax09vvzzy"/></radialGradient><radialGradient id="icZk5ie" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03216 1.46585 -1.67401 -2.32073 13.962 20.712)" gradientUnits="userSpaceOnUse"><stop class="xvxnt3n-k"/><stop offset="1" class="ns22v9t-w"/></radialGradient><radialGradient id="iBvvrTb" cx="0" cy="0" r="1" gradientTransform="rotate(-55.138 18.966 -10.68)scale(6.53476 7.31664)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="emwabp4fw"/><stop offset="1" class="grzcxhmih"/></radialGradient><radialGradient id="igxj1od" cx="0" cy="0" r="1" gradientTransform="rotate(-88.224 19.079 -3.927)scale(4.46016 5.91603)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="uw0wzsn6p"/><stop offset="1" class="fmyqnxbcv"/></radialGradient><radialGradient id="iO10hbd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03675 4.33638 -4.22874 -1.9862 17.479 22.586)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="vhxzwb5vo"/><stop offset="1" class="w9v04g5wl"/></radialGradient><radialGradient id="icgTGNc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.069 6.19)scale(25.3822 18.5012)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="mfxftxb2v"/><stop offset="1" class="x23elq47e"/></radialGradient><radialGradient id="i3ogRNc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0268 21.0901 -16.4647 -2.36298 14.076 8.243)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="ho66e2gez"/><stop offset="1" class="oagukf04h"/></radialGradient><radialGradient id="ia1TVLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.01827 0 0 3.58468 9.99 21.892)" gradientUnits="userSpaceOnUse"><stop class="fkd_ifb4y"/><stop offset="1" class="n1nhqibha"/><stop offset="1" class="zqvmn0t-z"/></radialGradient><radialGradient id="iJXZ0Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78125 1.10077 0 9.88 18.67)" gradientUnits="userSpaceOnUse"><stop class="cizba4bqb"/><stop offset="1" class="gme4zsb3v"/></radialGradient><radialGradient id="iShd0vb" cx="0" cy="0" r="1" gradientTransform="matrix(6.96874 4.09377 -2.53183 4.30988 16.896 2.874)" gradientUnits="userSpaceOnUse"><stop class="p9rps_sqh"/><stop offset="1" class="bfgxzgb-n"/></radialGradient><radialGradient id="iEuiVVd" cx="0" cy="0" r="1" gradientTransform="rotate(4.645 -171.166 260.769)scale(5.41661 10.3169)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="oniokeg5c"/><stop offset="1" class="wnrg0_btk"/></radialGradient><radialGradient id="iZULrWJ" cx="0" cy="0" r="1" gradientTransform="rotate(157.557 4.27 10.867)scale(2.33294 1.92272)" gradientUnits="userSpaceOnUse"><stop class="bpzyi6xnk"/><stop offset="1" class="w74yu-sct"/></radialGradient><filter id="iUb3QKb" width="15.211" height="12.148" x="9.127" y="3.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".5"/></filter><filter id="i2b1PVd" width="12.116" height="17.116" x="7.26" y="11.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".25"/></filter><filter id="iMNEHfd" width="7.642" height="7.642" x="7.708" y="18.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".375"/></filter><filter id="ibWEhvd" width="5.943" height="5.943" x="8.378" y="18.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".25"/></filter><filter id="ihbS5Gc" width="18.415" height="26.794" x="6.485" y="2.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.623529 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4848"/></filter><filter id="i3d7Ppe" width="11.838" height="12.38" x="13.848" y="1.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".75"/></filter><filter id="iInl0LF" width="12.754" height="22.681" x="6.628" y="7.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".75"/></filter><filter id="iyY9xgc" width="10.696" height="17.149" x="5.614" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4848"/></filter><filter id="iOmkT3c" width="8.725" height="7.879" x="6.127" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".1"/></filter><filter id="i9tjUbc" width="4.898" height="4.897" x="5.813" y="12.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".1"/></filter><filter id="iuRC5XG" width="10.143" height="7.663" x="16.242" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".15"/></filter><filter id="iB6UIVV" width=".797" height="4.25" x="27.318" y="10.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4848" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-with-hearing-aid-light" /></template>
<style>
.a5-5f3bjl {
  stop-color: var(--svg-color--da8467, #DA8467);
}

.ax09vvzzy {
  stop-color: var(--svg-color--ca827d, #CA827D);
}

.bfgxzgb-n {
  stop-color: var(--svg-color--959595, #959595);
  stop-opacity: 0;
}

.bjp4tgbbt {
  d: path("M16.06 2.565c4.482.307 8.086 3.904 8.32 8.403c0 2.076-.219 3.437-1.469 5.515l-1.656 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.73a.2.2 0 0 0-.206.197z");
}

.borhhobgo {
  stop-color: var(--svg-color--dadada, #DADADA);
  stop-opacity: 0;
}

.bpbu7dv4a {
  d: path("M12.142 28.248c-3.17-.242-4.382-1.99-4.382-5.114V12.282l2.26-.15l8.856 8.826l-2.832 4.79c-.953 1.778-1.619 2.5-3.902 2.5");
}

.bpzyi6xnk {
  stop-color: var(--svg-color--cec8c7, #CEC8C7);
}

.c8hqtvbke {
  stop-color: var(--svg-color--da8467, #DA8467);
  stop-opacity: 0;
}

.cizba4bqb {
  stop-color: var(--svg-color--635951, #635951);
}

.cp6t-lt6u {
  stop-color: var(--svg-color--e19a7f, #E19A7F);
}

.d7eywim1k {
  stop-color: var(--svg-color--917ea4, #917EA4);
}

.dl5923bfb {
  stop-color: var(--svg-color--ca7a56, #CA7A56);
}

.e14ccpbpi {
  stop-color: var(--svg-color--bbb, #BBB);
  stop-opacity: 0;
}

.e95bxobvz {
  stop-color: var(--svg-color--eeaa9a, #EEAA9A);
}

.emwabp4fw {
  stop-color: var(--svg-color--c17c71, #C17C71);
}

.eu-87q5qq {
  stop-color: var(--svg-color--bbb, #BBB);
}

.fgqhdzbrg {
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.fkd_ifb4y {
  stop-color: var(--svg-color--fdc5b4, #FDC5B4);
}

.fkqbx3b-n {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
}

.fmyqnxbcv {
  stop-color: var(--svg-color--ffc8b5, #FFC8B5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4udvybro {
  stop-color: var(--svg-color--ecebed, #ECEBED);
  stop-opacity: 0;
}

.gme4zsb3v {
  stop-color: var(--svg-color--635951, #635951);
  stop-opacity: 0;
}

.grzcxhmih {
  stop-color: var(--svg-color--c17c71, #C17C71);
  stop-opacity: 0;
}

.h5tsjybzx {
  stop-color: var(--svg-color--a29f9f, #A29F9F);
  stop-opacity: 0;
}

.hcgem_45j {
  stop-color: var(--svg-color--ca827d, #CA827D);
  stop-opacity: 0;
}

.hf5wm2mfe {
  width: 2.016px;
  height: 4.955px;
  x: 26.048px;
  y: 10.474px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.5px;
}

.ho66e2gez {
  stop-color: var(--svg-color--c28296, #C28296);
  stop-opacity: 0;
}

.i2g6mlz6l {
  fill: var(--svg-color--cecad1, #CECAD1);
  d: path("M16.06 2.565c4.482.307 8.086 3.904 8.32 8.403c0 2.076-.219 3.437-1.469 5.515l-1.656 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.73a.2.2 0 0 0-.206.197z");
}

.iab0nwb4s {
  stop-color: var(--svg-color--dadada, #DADADA);
}

.infs38bwt {
  fill: var(--svg-color--bfbdbd, #BFBDBD);
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.iqk_b94ku {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
}

.j_li4o9eq {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
  stop-opacity: 0;
}

.ja8i80b9n {
  fill: var(--svg-color--ffc8b5, #FFC8B5);
  d: path("M6.485 23.134c0 3.125 2.488 5.957 5.657 6.199c2.283 0 4.297-1.325 5.25-3.103l5.549-9.823a8.957 8.957 0 1 0-16.456-4.9z");
}

.jqsrlfe5i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.115 13.14c-.021.541.165 1.853 1.578 2.453c1.765.75 2.656.828 2.718 1.843");
}

.k9hnl5bgc {
  d: path("M17.53 22.426a1.735 1.735 0 0 0-2.35.665l-.828 1.465l-.018.034c-.353.658-1.114 1.269-2.058 1.269c-1.21 0-2.321-1.376-2.321-2.725V11.506a5.487 5.487 0 1 1 10.908.859c-.142.906.12 1.902.908 2.372c.867.516 2.009.202 2.285-.769a8.957 8.957 0 1 0-17.572-2.462v11.628c0 3.125 2.489 5.957 5.658 6.199c2.238.143 4.297-1.325 5.25-3.103l.81-1.433a1.735 1.735 0 0 0-.671-2.37");
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.kq103abhv {
  d: path("M9.958 19.363a2.9 2.9 0 0 1 1.393-.357c.883 0 1.674.396 2.205 1.02a2.318 2.318 0 0 0-3.598-1.86z");
}

.lf_pakb2d {
  cx: 11.529px;
  cy: 22.071px;
  r: 3.071px;
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.m8ss-00uh {
  stop-color: var(--svg-color--fcccaf, #FCCCAF);
}

.mfxftxb2v {
  stop-color: var(--svg-color--d8b49f, #D8B49F);
  stop-opacity: 0;
}

.mxna0tbja {
  cx: 11.35px;
  cy: 21.892px;
  r: 2.472px;
  fill: var(--svg-color--fcc4b3, #FCC4B3);
}

.n1nhqibha {
  stop-color: var(--svg-color--b5877c, #B5877C);
  stop-opacity: 0;
}

.ne07wgnjt {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
  stop-opacity: 0;
}

.nf1xib-zk {
  stop-color: var(--svg-color--7b608b, #7B608B);
}

.nnp22abze {
  width: 2.016px;
  height: 4.955px;
  x: 26.048px;
  y: 10.474px;
  rx: 0.5px;
}

.npfpicb6j {
  stop-color: var(--svg-color--f1baac, #F1BAAC);
}

.ns22v9t-w {
  stop-color: var(--svg-color--ffddc6, #FFDDC6);
  stop-opacity: 0;
}

.oagukf04h {
  stop-color: var(--svg-color--c28296, #C28296);
}

.oniokeg5c {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
}

.p4a1uebzz {
  stop-color: var(--svg-color--a59eae, #A59EAE);
}

.p9rps_sqh {
  stop-color: var(--svg-color--797979, #797979);
}

.qb8dbxb5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.642 2.189c2.44.331 6.964 1.608 9.343 6.863");
}

.qilsfwmjr {
  cx: 11.35px;
  cy: 21.892px;
  r: 2.892px;
}

.rcqia1kwr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.348 3.998c2.209.362 6.67 2.344 6.838 7.38");
}

.sd9-1cnwp {
  stop-color: var(--svg-color--bebdbc, #BEBDBC);
}

.shcafccup {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.878 9.404V23.58c.021.863.321 3.285 2.952 3.886c2.214.505 3.494-.663 4.121-1.838l1.18-2.048");
}

.sqji9tbob {
  stop-color: var(--svg-color--917ea4, #917EA4);
  stop-opacity: 0;
}

.stmsp0bcc {
  stop-color: var(--svg-color--806693, #806693);
  stop-opacity: 0;
}

.u1wxr7b2p {
  d: path("M27.568 10.952h.297v3.75h-.297z");
}

.u5e9-9bjf {
  stop-color: var(--svg-color--ffc7ab, #FFC7AB);
}

.ucgxbccuf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.552 2.189c-1.969.114-7.172 1.747-8.125 7.279");
}

.uw0wzsn6p {
  stop-color: var(--svg-color--ffc8b5, #FFC8B5);
}

.ve370msop {
  stop-color: var(--svg-color--ffdcc7, #FFDCC7);
}

.vhxzwb5vo {
  stop-color: var(--svg-color--ffc9b6, #FFC9B6);
}

.vkm05yehh {
  stop-color: var(--svg-color--ffdabd, #FFDABD);
}

.w74yu-sct {
  stop-color: var(--svg-color--a99d99, #A99D99);
}

.w9v04g5wl {
  stop-color: var(--svg-color--ffc9b6, #FFC9B6);
  stop-opacity: 0;
}

.wnrg0_btk {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
  stop-opacity: 0;
}

.wu2_0tzks {
  cx: 16.732px;
  cy: 9.302px;
  rx: 7.017px;
  ry: 4.484px;
}

.x23elq47e {
  stop-color: var(--svg-color--d8b49f, #D8B49F);
}

.x6wmc3bjj {
  stop-color: var(--svg-color--ffdcc7, #FFDCC7);
  stop-opacity: 0;
}

.xvxnt3n-k {
  stop-color: var(--svg-color--ffddc6, #FFDDC6);
}

.zc_tl-b2g {
  stop-color: var(--svg-color--e19a7f, #E19A7F);
  stop-opacity: 0;
}

.zqvmn0t-z {
  stop-color: var(--svg-color--fdc5b4, #FDC5B4);
  stop-opacity: 0;
}

.zxkw08qcp {
  d: path("M17.53 22.426a1.735 1.735 0 0 0-2.35.665l-.828 1.465l-.018.034c-.353.658-1.114 1.269-2.058 1.269c-1.21 0-2.321-1.376-2.321-2.725V11.506a5.487 5.487 0 1 1 10.908.859c-.142.906.12 1.902.908 2.372c.867.516 2.009.202 2.285-.769a8.957 8.957 0 1 0-17.572-2.462v11.628c0 3.125 2.489 5.957 5.658 6.199c2.283 0 4.297-1.325 5.25-3.103l.81-1.433a1.735 1.735 0 0 0-.671-2.37");
}

</style>
