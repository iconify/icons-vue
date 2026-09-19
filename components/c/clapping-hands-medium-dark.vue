<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i31O5cd)"><path fill="url(#ibuhVfj)" class="a6z-psbxb"/><path fill="url(#i9NPmEe)" class="a6z-psbxb"/></g><path fill="url(#i3nycOd)" class="o7y0xmbyb"/><path fill="url(#iMPe3ab)" class="w9cvwxbmu"/><path fill="url(#i0tPqqb)" class="bccljzkvo"/><g filter="url(#iq2MYee)"><path stroke="url(#iwCnlrb)" class="fr_c0cblf"/></g><g filter="url(#iutIA4c)"><path stroke="url(#i2Rt6Ad)" class="ep79rq54n"/></g><g filter="url(#iXdNior)"><path stroke="url(#il3aBwc)" class="ba9_x8x_n"/></g><g filter="url(#iHfa1ie)"><path class="c4es6_5qd"/></g><g filter="url(#i6p7Zhb)"><path class="e-m12xbnk"/></g><g filter="url(#ipKXNBc)"><path class="loiapwenw"/></g><g filter="url(#if738Gb)"><path fill="url(#iL3WUrc)" class="l49q68bef"/></g><g filter="url(#ieNghGK)"><path fill="url(#iI7wo5d)" class="nlo98hbtv"/></g><rect fill="url(#idxPDYc)" transform="rotate(-31.647 10.379 15.458)" class="w6kor5f-c"/><path fill="url(#i2J9aSb)" class="royb3ebkh"/><path fill="url(#iV4TOoe)" class="royb3ebkh"/><path fill="url(#i6N6bib)" class="ijqbtybbg"/><path fill="url(#iXraaUB)" class="ijqbtybbg"/><path fill="url(#iIs9usb)" class="xz4pyseqb"/><path fill="url(#iLDiu4b)" class="xz4pyseqb"/><path fill="url(#iDIbgOc)" class="o3f0-54ho"/><g filter="url(#iA51zOd)"><path class="xfr9rcb7w"/></g><g filter="url(#irPdYHf)"><path class="eszb1ybnh"/></g><g filter="url(#iRRiQwd)"><path class="sywhtk4_z"/></g><g filter="url(#iM02Bqd)"><path class="lor08h0la"/></g><g filter="url(#iexFbnn)"><path stroke="url(#iZcjzie)" class="ekrr-97pv"/></g><defs><radialGradient id="ibuhVfj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46518 -21.55686 14.94831 -1.016 16.926 27.696)" gradientUnits="userSpaceOnUse"><stop class="ks823t2xs"/><stop offset="1" class="r1t-jsbwe"/><stop offset="1" class="r1t-jsbwe"/></radialGradient><radialGradient id="i9NPmEe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.68861 -6.09785 3.14876 -3.97019 19.325 24.54)" gradientUnits="userSpaceOnUse"><stop class="wge3vm3rw"/><stop offset="1" class="nln1ywbzf"/></radialGradient><radialGradient id="i3nycOd" cx="0" cy="0" r="1" gradientTransform="matrix(2.43965 3.91822 -1.52236 .94788 9.862 16.667)" gradientUnits="userSpaceOnUse"><stop class="gujjb_h-d"/><stop offset="1" class="l26yj7bmf"/></radialGradient><radialGradient id="iMPe3ab" cx="0" cy="0" r="1" gradientTransform="rotate(57.875 -6.239 16.97)scale(5.63049 1.95545)" gradientUnits="userSpaceOnUse"><stop class="gujjb_h-d"/><stop offset="1" class="l26yj7bmf"/></radialGradient><radialGradient id="i0tPqqb" cx="0" cy="0" r="1" gradientTransform="matrix(3.94053 6.40474 -3.28048 2.01832 13.761 10.974)" gradientUnits="userSpaceOnUse"><stop class="gujjb_h-d"/><stop offset="1" class="l26yj7bmf"/></radialGradient><radialGradient id="iL3WUrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.9047 -12.2669 0 20.783 15.035)" gradientUnits="userSpaceOnUse"><stop class="x28dt-ugo"/><stop offset="1" class="ksb9eucwa"/></radialGradient><radialGradient id="iI7wo5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50634 16.4443 -17.83375 -2.71812 23.984 17.243)" gradientUnits="userSpaceOnUse"><stop class="ep4r49b6b"/><stop offset="1" class="v9v3t3bso"/></radialGradient><radialGradient id="idxPDYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.48237 2.16901 -2.50769 -.55769 13.22 15.078)" gradientUnits="userSpaceOnUse"><stop class="df7vpfiis"/><stop offset="1" class="dwtr_r_-h"/></radialGradient><radialGradient id="i2J9aSb" cx="0" cy="0" r="1" gradientTransform="matrix(3.10797 5.09187 -1.81223 1.10614 14.102 15.115)" gradientUnits="userSpaceOnUse"><stop class="s8hx4zbzf"/><stop offset="1" class="p_14-tbrj"/></radialGradient><radialGradient id="iV4TOoe" cx="0" cy="0" r="1" gradientTransform="rotate(71.222 .944 14.393)scale(3.49228 5.58798)" gradientUnits="userSpaceOnUse"><stop class="df7vpfiis"/><stop offset="1" class="dwtr_r_-h"/></radialGradient><radialGradient id="i6N6bib" cx="0" cy="0" r="1" gradientTransform="rotate(55.602 -3.109 21.204)scale(7.15572 2.54491)" gradientUnits="userSpaceOnUse"><stop class="s8hx4zbzf"/><stop offset="1" class="p_14-tbrj"/></radialGradient><radialGradient id="iXraaUB" cx="0" cy="0" r="1" gradientTransform="rotate(78.146 5.27 12.698)scale(3.99899 6.40983)" gradientUnits="userSpaceOnUse"><stop class="df7vpfiis"/><stop offset="1" class="dwtr_r_-h"/></radialGradient><radialGradient id="iIs9usb" cx="0" cy="0" r="1" gradientTransform="matrix(3.62466 6.34826 -2.1711 1.23963 20.054 11.213)" gradientUnits="userSpaceOnUse"><stop class="s8hx4zbzf"/><stop offset="1" class="p_14-tbrj"/></radialGradient><radialGradient id="iLDiu4b" cx="0" cy="0" r="1" gradientTransform="matrix(2.94267 2.64513 -3.87622 4.31224 18.93 6.287)" gradientUnits="userSpaceOnUse"><stop class="df7vpfiis"/><stop offset="1" class="dwtr_r_-h"/></radialGradient><radialGradient id="iDIbgOc" cx="0" cy="0" r="1" gradientTransform="matrix(.0992 -6.20804 2.80932 .04489 25.542 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="o8tax_-ek"/><stop offset="1" class="q1yutzb-i"/></radialGradient><filter id="i31O5cd" width="16.138" height="23.306" x="5.658" y="6.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.266667 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3488"/></filter><filter id="iq2MYee" width="4.97" height="6.745" x="7.434" y="13.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".375"/></filter><filter id="iutIA4c" width="4.694" height="6.195" x="8.963" y="10.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".375"/></filter><filter id="iXdNior" width="5.517" height="7.481" x="10.893" y="7.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".375"/></filter><filter id="iHfa1ie" width="2.662" height="3.25" x="6.996" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.580392 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3488"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.317647 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3488" result="effect2_innerShadow_20020_3488"/></filter><filter id="i6p7Zhb" width="3.158" height="2.858" x="3.811" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3488"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3488" result="effect2_innerShadow_20020_3488"/></filter><filter id="ipKXNBc" width="3.4" height="2.513" x="2.311" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.556863 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3488"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.301961 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3488" result="effect2_innerShadow_20020_3488"/></filter><filter id="if738Gb" width="19.722" height="24.355" x="11.172" y="5.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.25098 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3488"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.290196 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3488" result="effect2_innerShadow_20020_3488"/></filter><filter id="ieNghGK" width="18.929" height="22.689" x="12.162" y="6.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation="1"/></filter><filter id="iA51zOd" width="7.187" height="8.888" x="11.99" y="14.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".625"/></filter><filter id="irPdYHf" width="8.754" height="11.125" x="13.677" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".625"/></filter><filter id="iRRiQwd" width="9.312" height="12.363" x="15.771" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".625"/></filter><filter id="iM02Bqd" width="7.879" height="10.948" x="19.583" y="6.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".625"/></filter><filter id="iexFbnn" width="3.934" height="12.452" x="26.572" y="10.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3488" stdDeviation=".625"/></filter><linearGradient id="iwCnlrb" x1="11.28" x2="7.186" y1="19.583" y2="15.141" gradientUnits="userSpaceOnUse"><stop class="yeo7ntfqz"/><stop offset="1" class="f48gv0bng"/></linearGradient><linearGradient id="i2Rt6Ad" x1="10.213" x2="16.106" y1="12.01" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="wfnvfzbhh"/><stop offset="1" class="oytm2mbjp"/></linearGradient><linearGradient id="il3aBwc" x1="12.93" x2="19.254" y1="7.722" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="jav8ehb2l"/><stop offset="1" class="tbgtmqbhd"/></linearGradient><linearGradient id="iZcjzie" x1="28.539" x2="28.539" y1="12.587" y2="21.288" gradientUnits="userSpaceOnUse"><stop class="mkjy0qbit"/><stop offset="1" class="bthtdek_k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clapping-hands-medium-dark" /></template>
<style>
.a6z-psbxb {
  d: path("M13.761 8.885a2.023 2.023 0 0 1 3.747-1.009l3.808 6.172a2.184 2.184 0 1 1-3.766 2.211l-.26-.466a2.26 2.26 0 0 1-1.096 1.496a2.26 2.26 0 0 1-1.477.27l.031.053c.33.573.365 1.236.15 1.811l6.748 9.655c-.781.469-2.867 1.36-5.805.594c-2.71-.875-4.054-2.422-4.992-4.016L5.947 17.29a2.119 2.119 0 0 1 1.97-3.183l-.38-.683a2.075 2.075 0 0 1 2.181-3.053l-.077-.138a2.107 2.107 0 0 1 3.633-2.135z");
}

.ba9_x8x_n {
  stroke-linecap: round;
  d: path("m12.143 8.397l3.017 4.981");
}

.bccljzkvo {
  d: path("m13.761 8.885l3.24 5.238a2.26 2.26 0 0 1 .29 1.67l.26.466a2.184 2.184 0 1 0 3.765-2.21l-3.808-6.173a2.025 2.025 0 0 0-3.747 1.01");
}

.bthtdek_k {
  stop-color: var(--svg-color--a37e73, #A37E73);
  stop-opacity: 0;
}

.c4es6_5qd {
  fill: var(--svg-color--187ec9, #187EC9);
  d: path("m8.457 4.887l-1.22-1.651a.468.468 0 0 1 .23-.723l1.36-.423c.3-.093.6.155.58.475l-.14 2.075c-.04.423-.56.588-.81.247");
}

.df7vpfiis {
  stop-color: var(--svg-color--73564a, #73564A);
}

.dwtr_r_-h {
  stop-color: var(--svg-color--73564a, #73564A);
  stop-opacity: 0;
}

.e-m12xbnk {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m6.097 6.51l-1.86-.78a.443.443 0 0 1-.15-.72l.97-1.03a.45.45 0 0 1 .73.11l.89 1.81c.17.37-.2.77-.58.61");
}

.ekrr-97pv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M28.63 12.587c-.31 2.733-.168 6.34 0 8.702");
}

.ep4r49b6b {
  stop-color: var(--svg-color--a47f74, #A47F74);
}

.ep79rq54n {
  stroke-linecap: round;
  d: path("m10.213 11.67l2.194 3.695");
}

.eszb1ybnh {
  stroke: var(--svg-color--a37e73, #A37E73);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.552 11.594l5.004 7.375");
}

.f48gv0bng {
  stop-color: var(--svg-color--68504f, #68504F);
  stop-opacity: 0;
}

.fr_c0cblf {
  stroke-linecap: round;
  d: path("m8.685 15.194l2.47 4.245");
}

.ft5dv1b6b {
  fill: none;
}

.gujjb_h-d {
  stop-color: var(--svg-color--3b241d, #3B241D);
}

.ijqbtybbg {
  d: path("M16.027 7.055a2.114 2.114 0 0 0-.692 2.907l.084.137c.571.097 1.1.43 1.427.962l5.314 8.622a2.114 2.114 0 0 0 2.167-3.19l-5.393-8.75a2.114 2.114 0 0 0-2.907-.688");
}

.jav8ehb2l {
  stop-color: var(--svg-color--76625b, #76625B);
}

.ks823t2xs {
  stop-color: var(--svg-color--532a47, #532A47);
}

.ksb9eucwa {
  stop-color: var(--svg-color--976961, #976961);
}

.l26yj7bmf {
  stop-color: var(--svg-color--110808, #110808);
  stop-opacity: 0;
}

.l49q68bef {
  d: path("M20.43 29.269a6.863 6.863 0 0 0 9.199-3.32l.017.004c.955-1.96.778-3.607.632-4.972c-.036-.334-.07-.65-.085-.95c-.047-.907-.039-2.446-.02-3.605l.003-.06l.156-3.245a2.183 2.183 0 0 0-4.36-.21l-.01.192l-2.846-5.392a2.114 2.114 0 0 0-3.917.462l-.265-.43a2.114 2.114 0 0 0-3.6 2.22l.085.136a2.087 2.087 0 0 0-2.125 3.152l.526.854a2.112 2.112 0 0 0-2.334 3.15l5.378 8.726c1.11 1.753 2.528 2.79 3.565 3.288");
}

.loiapwenw {
  fill: var(--svg-color--1c75c1, #1C75C1);
  d: path("m5.053 9.305l-2.072.27a.463.463 0 0 1-.507-.57l.342-1.433a.472.472 0 0 1 .714-.28l1.73 1.162c.352.25.217.8-.207.851");
}

.lor08h0la {
  stroke: var(--svg-color--a37e73, #A37E73);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m21.458 8.125l4.13 7.198");
}

.mkjy0qbit {
  stop-color: var(--svg-color--a37e73, #A37E73);
}

.nln1ywbzf {
  stop-color: var(--svg-color--3b1f26, #3B1F26);
  stop-opacity: 0;
}

.nlo98hbtv {
  d: path("m18.633 24.509l-4.347-7.369a.893.893 0 0 1 1.51-.955l2.457 3.632a.667.667 0 0 0 1.115-.731l-3.83-6.036a.866.866 0 1 1 1.473-.91l3.733 6.205a.627.627 0 0 0 1.08-.636l-4.28-7.42a.956.956 0 0 1 1.654-.96l4.406 7.54a.553.553 0 0 0 .963-.544l-2.88-5.264a.908.908 0 0 1 1.587-.883l3.335 5.888c.004-.124.076-.75.173-1.153c.33-1.359.775-1.89 1.258-1.89c.502 0 1.092.214.93 1.788c-.32 3.126-.058 5.293 0 5.7s.953 4.762-3.176 6.594c-3.303 1.465-6.24-1.094-7.16-2.596");
}

.o3f0-54ho {
  d: path("m28.715 18.323l-2.753-5.217l.01-.195a2.183 2.183 0 0 1 4.36.21l-.156 3.246a2.18 2.18 0 0 1-1.461 1.956");
}

.o7y0xmbyb {
  d: path("M8.313 10.617a2.075 2.075 0 0 0-.776 2.807l.38.683c.682.046 1.328.42 1.695 1.055l3.26 5.646a2.13 2.13 0 0 0 1.877-3.196l-3.601-6.236a2.075 2.075 0 0 0-2.835-.76");
}

.o8tax_-ek {
  stop-color: var(--svg-color--5c382b, #5C382B);
}

.oytm2mbjp {
  stop-color: var(--svg-color--6c5952, #6C5952);
  stop-opacity: 0;
}

.p_14-tbrj {
  stop-color: var(--svg-color--643a2e, #643A2E);
  stop-opacity: 0;
}

.q1yutzb-i {
  stop-color: var(--svg-color--7f594c, #7F594C);
  stop-opacity: 0;
}

.r1t-jsbwe {
  stop-color: var(--svg-color--5c433a, #5C433A);
}

.royb3ebkh {
  d: path("M13.975 10.38a2.087 2.087 0 0 0-.681 2.87l.526.855c.507.133.965.454 1.262.935l4.887 7.93a2.087 2.087 0 0 0 2.296-3.116l-5.419-8.793a2.087 2.087 0 0 0-2.871-.681");
}

.s8hx4zbzf {
  stop-color: var(--svg-color--643a2e, #643A2E);
}

.sywhtk4_z {
  stroke: var(--svg-color--a37e73, #A37E73);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m17.646 8.397l5.561 8.613");
}

.tbgtmqbhd {
  stop-color: var(--svg-color--76625b, #76625B);
  stop-opacity: 0;
}

.v9v3t3bso {
  stop-color: var(--svg-color--a47f74, #A47F74);
  stop-opacity: 0;
}

.w6kor5f-c {
  width: 4.224px;
  height: 14.575px;
  x: 10.379px;
  y: 15.458px;
  rx: 2.112px;
}

.w9cvwxbmu {
  d: path("M10.428 7.382a2.107 2.107 0 0 0-.787 2.85l.077.14a2.07 2.07 0 0 1 1.43 1.004l3.57 6.183a2.27 2.27 0 0 0 2.284-3.436l-3.728-6.024a2.107 2.107 0 0 0-2.846-.717");
}

.wfnvfzbhh {
  stop-color: var(--svg-color--6c5952, #6C5952);
}

.wge3vm3rw {
  stop-color: var(--svg-color--3b1f26, #3B1F26);
}

.x28dt-ugo {
  stop-color: var(--svg-color--81554a, #81554A);
}

.xfr9rcb7w {
  stroke: var(--svg-color--a37e73, #A37E73);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m13.865 16l3.437 5.138");
}

.xz4pyseqb {
  d: path("m19.2 8.173l5.127 8.32a2.11 2.11 0 0 1-.104 2.369a2.114 2.114 0 0 0 3.69-2.062l-4.797-9.09a2.114 2.114 0 0 0-3.917.463");
}

.yeo7ntfqz {
  stop-color: var(--svg-color--68504f, #68504F);
}

</style>
