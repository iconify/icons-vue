<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZeAQ0c)" class="aq3pf6bgl"/><path fill="url(#ihBV6Ec)" class="aq3pf6bgl"/><path fill="url(#iWTtxKd)" class="aq3pf6bgl"/><ellipse fill="url(#iSMcvwh)" class="div_70bpx"/><g filter="url(#iiLGv2c)"><path stroke="url(#ixI5eie)" class="lhuli2tii"/></g><g filter="url(#iSU2V6c)"><path class="gaczzzbgo"/></g><g filter="url(#iQWv8hd)"><path class="kf4_0nbvw"/></g><path fill="url(#iucff9c)" class="xfrgn9bhk"/><path fill="url(#iXfmx9X)" class="xfrgn9bhk"/><path fill="url(#itX6rzc)" class="xfrgn9bhk"/><path fill="url(#iLAJJIL)" class="a9zu_tbuj"/><path fill="url(#iax2IIc)" class="a9zu_tbuj"/><path fill="url(#ixY8Khb)" class="a9zu_tbuj"/><path fill="url(#iVxVNVb)" class="a9zu_tbuj"/><path fill="url(#iQKW7Rb)" class="a9zu_tbuj"/><path fill="url(#ifZ7Mjc)" class="a9zu_tbuj"/><g filter="url(#i2F95ld)"><path class="u_jgfhb_o"/></g><g filter="url(#i02b4Ce)"><path class="qqfribbdn"/></g><path fill="url(#iZgxhLC)" class="l3-_crntu"/><path fill="url(#irN4I5d)" class="l3-_crntu"/><path fill="url(#iXo5PAb)" class="dva297b_c"/><path fill="url(#i1mYtte)" class="dva297b_c"/><g filter="url(#i8Hmnnc)"><path stroke="url(#iBTkZ6a)" class="kt30bpbvl"/></g><path fill="url(#iUJ4ITd)" class="m7cdq810k"/><path fill="url(#if2w5Cc)" class="m7cdq810k"/><path fill="url(#iwujEsb)" class="m7cdq810k"/><path fill="url(#iup7Sie)" class="f4rrrccga"/><path fill="url(#ihyFWwb)" class="f4rrrccga"/><path fill="url(#irGerIe)" class="f4rrrccga"/><path fill="url(#iLHX1ed)" class="f4rrrccga"/><path fill="url(#iJQTvDX)" class="f4rrrccga"/><path fill="url(#ieZzzIb)" class="f4rrrccga"/><g filter="url(#iE3vvdc)"><path class="riuyvw7ly"/></g><path stroke="url(#iT1lSOc)" class="wvpirfbnw"/><path stroke="url(#iJgsBae)" class="wvpirfbnw"/><path stroke="url(#ixBRAGd)" class="wvpirfbnw"/><path stroke="url(#iGBXVod)" class="q56nwebze"/><path stroke="url(#iEkUYKd)" class="q56nwebze"/><path fill="url(#il93uLb)" class="n1mc1rm6x"/><path fill="url(#i4OhWne)" class="n1mc1rm6x"/><path fill="url(#iwbHo3d)" class="n1mc1rm6x"/><path fill="url(#i6943XI)" class="n1mc1rm6x"/><path fill="url(#ilBGvhd)" class="imxqf8ipt"/><path fill="url(#iUMdEEb)" class="imxqf8ipt"/><path fill="url(#iC5O55b)" class="imxqf8ipt"/><path fill="url(#iUgn7nb)" class="imxqf8ipt"/><path fill="url(#imhLZMd)" class="imxqf8ipt"/><path fill="url(#iqyDfSe)" class="imxqf8ipt"/><g filter="url(#i3VOa1c)"><circle class="vw11j7btk"/></g><g filter="url(#i9AGMTd)"><path fill="url(#iY3H2nd)" class="i4qbz4-vv"/></g><g filter="url(#i5yoMUc)"><path fill="url(#im6cfvt)" class="eyg0p3bmr"/></g><g filter="url(#iLlBd2d)"><path class="tfdaz8bcd"/></g><g filter="url(#iIsdfia)"><path class="ga53nbc0j"/></g><g filter="url(#iGpyKDc)"><path class="pwjl7efxd"/></g><g filter="url(#iI3yues)"><path stroke="url(#irI8W4c)" class="ytcgr7bhg"/></g><g filter="url(#itGCMIt)"><path stroke="url(#i8gowHc)" class="i3wxvtl8n"/></g><defs><linearGradient id="ixI5eie" x1="20.474" x2="20.474" y1="7.406" y2="-3.875" gradientUnits="userSpaceOnUse"><stop class="dr6o98iee"/><stop offset="1" class="azwduabyc"/></linearGradient><linearGradient id="iucff9c" x1="21.494" x2="22.087" y1=".639" y2="5.664" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iXfmx9X" x1="22.058" x2="21.957" y1="3.084" y2=".544" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="itX6rzc" x1="23.283" x2="23.283" y1="7.285" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iLAJJIL" x1="23.346" x2="20.034" y1="13.75" y2="5.188" gradientUnits="userSpaceOnUse"><stop class="plffaesge"/><stop offset="1" class="rr7wogb_o"/></linearGradient><linearGradient id="iax2IIc" x1="25.034" x2="22.909" y1="12.73" y2="7.688" gradientUnits="userSpaceOnUse"><stop class="js5p6fb9f"/><stop offset="1" class="xhvfkz60h"/></linearGradient><linearGradient id="ixY8Khb" x1="24.784" x2="22.627" y1="7.688" y2="7.688" gradientUnits="userSpaceOnUse"><stop class="js5p6fb9f"/><stop offset="1" class="xhvfkz60h"/></linearGradient><linearGradient id="iVxVNVb" x1="25.284" x2="22.346" y1="4.563" y2="7.375" gradientUnits="userSpaceOnUse"><stop class="sd85qxbgu"/><stop offset="1" class="womdddchv"/></linearGradient><linearGradient id="ifZ7Mjc" x1="18.709" x2="20.034" y1="6.406" y2="7.344" gradientUnits="userSpaceOnUse"><stop class="evkj8zo-e"/><stop offset="1" class="c2cf1q2hz"/></linearGradient><linearGradient id="iZgxhLC" x1="20.471" x2="19.646" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="irN4I5d" x1="20.793" x2="20.793" y1="20.525" y2="18.935" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iXo5PAb" x1="12.891" x2="12.066" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="i1mYtte" x1="13.213" x2="13.213" y1="20.525" y2="18.935" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iBTkZ6a" x1="8.734" x2="8.734" y1="9.563" y2="-1.719" gradientUnits="userSpaceOnUse"><stop class="dr6o98iee"/><stop offset="1" class="azwduabyc"/></linearGradient><linearGradient id="iUJ4ITd" x1="10.479" x2="11.062" y1=".656" y2="5.619" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="if2w5Cc" x1="11.039" x2="10.94" y1="3.07" y2=".563" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="iwujEsb" x1="12.255" x2="12.255" y1="7.219" y2="4.469" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ixBRAGd" x1="15.842" x2="15.139" y1="24.53" y2="25.545" gradientUnits="userSpaceOnUse"><stop class="z6-ovubwn"/><stop offset="1" class="fmxmxcb-i"/></linearGradient><linearGradient id="il93uLb" x1="17.088" x2="14.555" y1="20.752" y2="22.993" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iwbHo3d" x1="16.303" x2="16.303" y1="21.766" y2="20.378" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="i6943XI" x1="16.997" x2="16.997" y1="24.096" y2="21.996" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ilBGvhd" x1="12.108" x2="8.326" y1="13.762" y2="6.385" gradientUnits="userSpaceOnUse"><stop class="plffaesge"/><stop offset="1" class="rr7wogb_o"/></linearGradient><linearGradient id="iUMdEEb" x1="13.239" x2="10.348" y1="11.063" y2="7.446" gradientUnits="userSpaceOnUse"><stop offset=".139" class="js5p6fb9f"/><stop offset="1" class="xhvfkz60h"/></linearGradient><linearGradient id="iC5O55b" x1="13.543" x2="11.39" y1="7.686" y2="7.686" gradientUnits="userSpaceOnUse"><stop class="js5p6fb9f"/><stop offset="1" class="xhvfkz60h"/></linearGradient><linearGradient id="iUgn7nb" x1="13.239" x2="11.104" y1="5.875" y2="7.364" gradientUnits="userSpaceOnUse"><stop class="sd85qxbgu"/><stop offset="1" class="womdddchv"/></linearGradient><linearGradient id="iqyDfSe" x1="7.479" x2="9.6" y1="6.402" y2="7.554" gradientUnits="userSpaceOnUse"><stop class="evkj8zo-e"/><stop offset="1" class="c2cf1q2hz"/></linearGradient><linearGradient id="iY3H2nd" x1="29.205" x2="26.783" y1="19.609" y2="21.125" gradientUnits="userSpaceOnUse"><stop offset=".211" class="hnoezjs0v"/><stop offset="1" class="mpd-lbukd"/></linearGradient><linearGradient id="im6cfvt" x1="2.931" x2="6.627" y1="19.609" y2="21.875" gradientUnits="userSpaceOnUse"><stop offset=".211" class="h5e-xlglk"/><stop offset="1" class="mpd-lbukd"/></linearGradient><linearGradient id="irI8W4c" x1="21.511" x2="19.246" y1="2.664" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="akntbu9yv"/><stop offset="1" class="gjpekiuwi"/></linearGradient><linearGradient id="i8gowHc" x1="10.416" x2="8.15" y1="2.664" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="akntbu9yv"/><stop offset="1" class="gjpekiuwi"/></linearGradient><radialGradient id="iZeAQ0c" cx="0" cy="0" r="1" gradientTransform="rotate(136.338 7.575 10.288)scale(20.8211)" gradientUnits="userSpaceOnUse"><stop class="eldfyo1fb"/><stop offset=".285" class="t-tt_4b-g"/><stop offset=".611" class="crqqh7b8b"/></radialGradient><radialGradient id="ihBV6Ec" cx="0" cy="0" r="1" gradientTransform="rotate(134.433 10.804 15.2)scale(4.46383 3.0354)" gradientUnits="userSpaceOnUse"><stop class="e2ov1_p1i"/><stop offset="1" class="grsly65vi"/></radialGradient><radialGradient id="iWTtxKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 1.78125 -.95441 1.49022 1.94 19.688)" gradientUnits="userSpaceOnUse"><stop class="pw3ptqfki"/><stop offset="1" class="sb_btjo-h"/></radialGradient><radialGradient id="iSMcvwh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.4375 12.9825 0 15.988 19.875)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="ykw3u9bdx"/><stop offset="1" class="mhdeakbvc"/></radialGradient><radialGradient id="iQKW7Rb" cx="0" cy="0" r="1" gradientTransform="matrix(2.01251 -.84375 1.86255 4.44256 18.709 9.375)" gradientUnits="userSpaceOnUse"><stop class="evkj8zo-e"/><stop offset="1" class="c2cf1q2hz"/></radialGradient><radialGradient id="iup7Sie" cx="0" cy="0" r="1" gradientTransform="rotate(116.074 5.331 16.265)scale(14.3337 20.0167)" gradientUnits="userSpaceOnUse"><stop offset=".084" class="ij9bgo8-q"/><stop offset="1" class="vs-fs57-d"/></radialGradient><radialGradient id="ihyFWwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.01 -21.575 0 15.983 20.99)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="ndexub-tq"/><stop offset="1" class="dd7ukzgdj"/></radialGradient><radialGradient id="irGerIe" cx="0" cy="0" r="1" gradientTransform="rotate(128.469 2.926 14.352)scale(13.5833 44.3384)" gradientUnits="userSpaceOnUse"><stop offset=".589" class="ndexub-tq"/><stop offset="1" class="dd7ukzgdj"/></radialGradient><radialGradient id="iLHX1ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5725 -16.07 0 15.983 20.99)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="uxj0sia3i"/><stop offset="1" class="k646d19-x"/></radialGradient><radialGradient id="iJQTvDX" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37498 4.4375 -6.28317 -3.3628 24.346 19.625)" gradientUnits="userSpaceOnUse"><stop class="n7rsoccit"/><stop offset="1" class="rfo71i7jc"/></radialGradient><radialGradient id="ieZzzIb" cx="0" cy="0" r="1" gradientTransform="matrix(6.26248 -6.5 8.1083 7.812 9.721 31.188)" gradientUnits="userSpaceOnUse"><stop class="dd7ukzgdj"/><stop offset="1" class="ndexub-tq"/></radialGradient><radialGradient id="iT1lSOc" cx="0" cy="0" r="1" gradientTransform="matrix(1.73438 2.42188 -3.03987 2.17694 13.748 24.201)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".589" class="ajx6-mbfo"/><stop offset=".747" class="z6-ovubwn"/></radialGradient><radialGradient id="iJgsBae" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 -.76562 1.26836 -1.00951 14.561 25.264)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><radialGradient id="iGBXVod" cx="0" cy="0" r="1" gradientTransform="rotate(122.471 2.57 17.209)scale(3.05588 4.35358)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".589" class="ajx6-mbfo"/><stop offset=".747" class="z6-ovubwn"/></radialGradient><radialGradient id="iEkUYKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 .89062 -1.47543 -1.5272 17.686 24.498)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><radialGradient id="i4OhWne" cx="0" cy="0" r="1" gradientTransform="rotate(132.349 3.38 14.363)scale(1.80048 3.30126)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="ueu24dben"/><stop offset=".956" class="vylhu7i4w"/></radialGradient><radialGradient id="imhLZMd" cx="0" cy="0" r="1" gradientTransform="matrix(3 .5625 -2.35332 12.55098 6.096 7.125)" gradientUnits="userSpaceOnUse"><stop class="evkj8zo-e"/><stop offset="1" class="c2cf1q2hz"/></radialGradient><filter id="iiLGv2c" width="3.328" height="5.328" x="17.721" y="3.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="iSU2V6c" width="2.75" height="8.125" x="23.449" y="4.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="iQWv8hd" width="2.764" height="4.853" x="11.864" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="i2F95ld" width="3" height="4.5" x="18.062" y="16.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".375"/></filter><filter id="i02b4Ce" width="3" height="4.5" x="10.482" y="16.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".375"/></filter><filter id="i8Hmnnc" width="3.016" height="8.231" x="6.344" y="4.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="iE3vvdc" width="7.65" height="7.166" x="11.955" y="20.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".375"/></filter><filter id="i3VOa1c" width="1.641" height="1.641" x="16.268" y="21.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="i9AGMTd" width="4.063" height="3.047" x="25.455" y="18.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="i5yoMUc" width="5.063" height="4.047" x="2.119" y="18.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".5"/></filter><filter id="iLlBd2d" width="8.656" height="11.281" x="20.408" y="12.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation="1.25"/></filter><filter id="iIsdfia" width="3.648" height="4.148" x="21.05" y="2.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="iGpyKDc" width="3.648" height="4.148" x="9.955" y="2.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="iI3yues" width="3.648" height="4.148" x="18.488" y="2.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter><filter id="itGCMIt" width="3.648" height="4.148" x="7.393" y="2.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1940" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fox" /></template>
<style>
.a9zu_tbuj {
  d: path("M23.983 12.002c.15.202.495.099.495-.153v-1.43c0-2.48-1.06-4.81-2.89-6.43a.196.196 0 0 0-.25.001a8.6 8.6 0 0 0-2.475 3.834c-.096.307.091.624.396.73a10 10 0 0 1 4.724 3.448");
}

.ajx6-mbfo {
  stop-color: var(--svg-color--4e4647, #4E4647);
}

.akntbu9yv {
  stop-color: var(--svg-color--665d5f, #665D5F);
}

.aq3pf6bgl {
  d: path("M28.928 19h-2.14c-.45 0-.81-.36-.81-.81v-7.77c0-3.09-1.42-6.27-3.82-8.18c-.19-.16-.44-.24-.69-.24s-.5.08-.7.24c-1.75 1.4-2.97 3.6-3.5 5.76h-2.58c-.53-2.16-1.75-4.36-3.5-5.76c-.19-.16-.44-.24-.69-.24s-.5.08-.7.24c-2.39 1.91-3.81 5.08-3.81 8.18v7.77c0 .45-.36.81-.81.81h-2.14c-.41 0-.71.4-.6.8c1.66 5.88 7.06 10.2 13.48 10.2h.14c6.41 0 11.82-4.31 13.48-10.2c.11-.4-.19-.8-.61-.8");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.azwduabyc {
  stop-color: var(--svg-color--ffb444, #FFB444);
  stop-opacity: 0;
}

.c2cf1q2hz {
  stop-color: var(--svg-color--ff894c, #FF894C);
  stop-opacity: 0;
}

.crqqh7b8b {
  stop-color: var(--svg-color--f4763d, #F4763D);
}

.dd7ukzgdj {
  stop-color: var(--svg-color--d87da0, #D87DA0);
}

.div_70bpx {
  cx: 15.988px;
  cy: 17.631px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 9.767px;
  ry: 9.663px;
}

.dr6o98iee {
  stop-color: var(--svg-color--ffb444, #FFB444);
}

.dva297b_c {
  d: path("M12.229 20c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .41-.33.75-.75.75");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e2ov1_p1i {
  stop-color: var(--svg-color--e78327, #E78327);
}

.eldfyo1fb {
  stop-color: var(--svg-color--ffc177, #FFC177);
}

.evkj8zo-e {
  stop-color: var(--svg-color--ff894c, #FF894C);
}

.ew8h6t88b {
  stop-color: var(--svg-color--261317, #261317);
}

.eyg0p3bmr {
  d: path("M3.14 19.678a.125.125 0 1 1 .209-.137zm2.949 1.607a.125.125 0 0 1-.065.242zm-2.74-1.744q.022.038.126.135q.102.094.257.217c.207.164.473.356.759.546c.577.383 1.214.743 1.598.846l-.065.242c-.428-.115-1.096-.498-1.671-.88a12 12 0 0 1-.776-.558a5 5 0 0 1-.272-.23a1 1 0 0 1-.166-.182z");
}

.f4rrrccga {
  d: path("M29.139 20.99h-6.46c-1.75 0-3.46.55-4.88 1.57l-1.81 1.29l-1.81-1.29a8.37 8.37 0 0 0-4.88-1.57h-6.47c2.01 5.27 7.11 9.01 13.08 9.01h.14c5.98-.01 11.08-3.75 13.09-9.01");
}

.fmxmxcb-i {
  stop-color: var(--svg-color--2f172a, #2F172A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.ga53nbc0j {
  stroke: var(--svg-color--665d5f, #665D5F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.676 2.664c.445.398 1.664 1.57 2.398 2.899");
}

.gaczzzbgo {
  stroke: var(--svg-color--ffb160, #FFB160);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M24.074 5.194c.75 1.03 1.5 3.062 1.5 6.875");
}

.gjpekiuwi {
  stop-color: var(--svg-color--665d5f, #665D5F);
  stop-opacity: 0;
}

.grsly65vi {
  stop-color: var(--svg-color--f4953d, #F4953D);
  stop-opacity: 0;
}

.h5e-xlglk {
  stop-color: var(--svg-color--ffd199, #FFD199);
}

.hnoezjs0v {
  stop-color: var(--svg-color--ffcb8c, #FFCB8C);
}

.i3wxvtl8n {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.416 2.664c-.445.398-1.664 1.57-2.398 2.899");
}

.i4qbz4-vv {
  d: path("M28.998 19.678a.125.125 0 1 0-.21-.137zm-2.95 1.607a.125.125 0 0 0 .065.242zm2.74-1.744a1 1 0 0 1-.126.135a5 5 0 0 1-.258.217a12 12 0 0 1-.758.546c-.577.383-1.214.743-1.598.846l.065.242c.428-.115 1.096-.498 1.671-.88c.29-.193.563-.39.776-.558q.16-.127.272-.23a1 1 0 0 0 .166-.182z");
}

.ij9bgo8-q {
  stop-color: var(--svg-color--ffdfa1, #FFDFA1);
}

.imxqf8ipt {
  d: path("M12.689 8.554c.304-.106.492-.422.395-.73a8.65 8.65 0 0 0-2.485-3.844a.196.196 0 0 0-.25 0a8.64 8.64 0 0 0-2.87 6.42v1.461c0 .252.343.355.494.153a10 10 0 0 1 4.716-3.46");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.js5p6fb9f {
  stop-color: var(--svg-color--e83525, #E83525);
}

.k646d19-x {
  stop-color: var(--svg-color--c55188, #C55188);
}

.kf4_0nbvw {
  stroke: var(--svg-color--ffb160, #FFB160);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.488 4.35c.494.679 1.358 2.353 1.514 3.603");
}

.kt30bpbvl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.734 5.078c-.437.552-1.765 2.56-1.765 4.985v2.03");
}

.l3-_crntu {
  d: path("M19.809 20c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .41-.34.75-.75.75");
}

.lhuli2tii {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.424 3.89c-.437.553-1.703 2.141-2.078 4.079");
}

.m7cdq810k {
  d: path("M13.989 5.95c-.65-1.43-1.6-2.75-2.79-3.71c-.2-.16-.45-.24-.7-.24s-.5.08-.7.24c-1.21.97-2.18 2.26-2.83 3.71z");
}

.mhdeakbvc {
  stop-color: var(--svg-color--f46639, #F46639);
}

.mpd-lbukd {
  stop-color: var(--svg-color--ffcb8c, #FFCB8C);
  stop-opacity: 0;
}

.n1mc1rm6x {
  d: path("m14.239 22.47l1.13 1.13c.34.34.89.34 1.23 0l1.13-1.13a.865.865 0 0 0-.61-1.48h-2.26c-.78 0-1.17.93-.62 1.48");
}

.n7rsoccit {
  stop-color: var(--svg-color--f9e58c, #F9E58C);
}

.ndexub-tq {
  stop-color: var(--svg-color--d87da0, #D87DA0);
  stop-opacity: 0;
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.plffaesge {
  stop-color: var(--svg-color--fc5737, #FC5737);
}

.pw3ptqfki {
  stop-color: var(--svg-color--c9510e, #C9510E);
}

.pwjl7efxd {
  stroke: var(--svg-color--665d5f, #665D5F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.58 2.664c.445.398 1.664 1.57 2.399 2.899");
}

.q56nwebze {
  stroke-linecap: round;
  d: path("M16 23.64c0 1.45 1.17 2.62 2.62 2.62");
}

.qqfribbdn {
  fill: var(--svg-color--cd5c25, #CD5C25);
  d: path("M11.982 20.281c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .41-.33.75-.75.75");
}

.rfo71i7jc {
  stop-color: var(--svg-color--f9e58c, #F9E58C);
  stop-opacity: 0;
}

.riuyvw7ly {
  fill: var(--svg-color--b66a7d, #B66A7D);
  d: path("m15.17 23.953l-1.109-1.11c-.54-.54-.157-1.452.61-1.452h2.218c.756 0 .138.475-.402 1.015l-.108 1.547a1 1 0 0 1-.097.083a2.08 2.08 0 0 0 2.081 2.039a.49.49 0 1 1 0 .982a3.06 3.06 0 0 1-2.583-1.415a3.06 3.06 0 0 1-2.584 1.415a.491.491 0 1 1 0-.982a2.08 2.08 0 0 0 2.08-2.032a1 1 0 0 1-.105-.09");
}

.rr7wogb_o {
  stop-color: var(--svg-color--ef7e3f, #EF7E3F);
}

.sb_btjo-h {
  stop-color: var(--svg-color--c9510e, #C9510E);
  stop-opacity: 0;
}

.sd85qxbgu {
  stop-color: var(--svg-color--bf5733, #BF5733);
}

.t-tt_4b-g {
  stop-color: var(--svg-color--ff8d28, #FF8D28);
}

.tfdaz8bcd {
  stroke: var(--svg-color--ffc177, #FFC177);
  d: path("M23.408 15.188c0 .218.011 2.46.031 2.659c.213 2.081 1.5 3.122 3.126 3.122");
}

.u_jgfhb_o {
  fill: var(--svg-color--cd5c25, #CD5C25);
  d: path("M19.562 20.281c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .41-.34.75-.75.75");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.uxj0sia3i {
  stop-color: var(--svg-color--c55188, #C55188);
  stop-opacity: 0;
}

.vs-fs57-d {
  stop-color: var(--svg-color--eba582, #EBA582);
}

.vw11j7btk {
  cx: 17.088px;
  cy: 21.836px;
  r: 0.32px;
  fill: var(--svg-color--6a6566, #6A6566);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.womdddchv {
  stop-color: var(--svg-color--bf5733, #BF5733);
  stop-opacity: 0;
}

.wvpirfbnw {
  stroke-linecap: round;
  d: path("M15.977 23.64c0 1.45-1.17 2.62-2.62 2.62");
}

.xfrgn9bhk {
  d: path("M22.169 2.24c-.2-.16-.45-.24-.7-.24s-.5.08-.7.24c-1.2.97-2.16 2.31-2.81 3.76h7.07c-.66-1.47-1.63-2.78-2.86-3.76");
}

.xhvfkz60h {
  stop-color: var(--svg-color--e83525, #E83525);
  stop-opacity: 0;
}

.ykw3u9bdx {
  stop-color: var(--svg-color--f46639, #F46639);
  stop-opacity: 0;
}

.ytcgr7bhg {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.511 2.664c-.445.398-1.664 1.57-2.398 2.899");
}

.yx-bms0gr {
  stop-color: var(--svg-color--261317, #261317);
  stop-opacity: 0;
}

.z6-ovubwn {
  stop-color: var(--svg-color--2f172a, #2F172A);
}

</style>
