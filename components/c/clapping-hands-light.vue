<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iujI1Pb)"><path fill="url(#i4Cg75P)" class="w05axs7ko"/><path fill="url(#immTpwc)" class="w05axs7ko"/></g><path fill="url(#iNU4ziS)" class="z7wy6obpq"/><path fill="url(#icLy0Lc)" class="z7wy6obpq"/><path fill="url(#ijJo5Xb)" class="i36s1qb_g"/><path fill="url(#iVEzdMe)" class="i36s1qb_g"/><path fill="url(#iVv6EBc)" class="tjvmr_b3b"/><path fill="url(#i6ETSWc)" class="tjvmr_b3b"/><rect fill="url(#ixqYDiv)" transform="rotate(-31.647 4.757 15.519)" class="fssmy6bpn"/><g filter="url(#i7wiljb)"><path stroke="url(#icAgw9d)" class="vc46r_c8i"/></g><g filter="url(#i1R6yrb)"><path stroke="url(#iLpjWZZ)" class="asqc_1_dp"/></g><g filter="url(#iVQVJLM)"><path stroke="url(#iNDXmwd)" class="w_ccelber"/></g><g filter="url(#i52m0Mb)"><path class="ihs0mo99f"/></g><g filter="url(#iFS81Mb)"><path class="x28j_obaq"/></g><g filter="url(#iwSskYd)"><path class="l79n4x80f"/></g><g filter="url(#i7VR16d)"><path fill="url(#iKpicfb)" class="ma8v-lhgu"/></g><path fill="url(#ivvZcRd)" class="ma8v-lhgu"/><g filter="url(#iTnw33b)"><path fill="url(#iD7Jdhd)" class="at05xybeo"/></g><rect fill="url(#i3OkUBc)" transform="rotate(-31.647 10.257 15.458)" class="z7kzdbcte"/><path fill="url(#i2ym6le)" class="gwznzxt3m"/><path fill="url(#i42wUfe)" class="gwznzxt3m"/><path fill="url(#iMIhr4b)" class="e2mbiomkg"/><path fill="url(#iovFoae)" class="e2mbiomkg"/><path fill="url(#iaNeOEd)" class="yet1k9bwh"/><path fill="url(#i0Kzbxe)" class="yet1k9bwh"/><path fill="url(#i3A5uoe)" class="fdnjngwjh"/><g filter="url(#iiB2D7v)"><path class="yjan3rbwm"/></g><g filter="url(#iNUehee)"><path class="shnmtibet"/></g><g filter="url(#i4Df9yc)"><path class="azatxnbcy"/></g><g filter="url(#i2QKi2e)"><path class="extfw-zmg"/></g><g filter="url(#iHmSd8c)"><path stroke="url(#ikHnpYc)" class="m25qys66g"/></g><defs><radialGradient id="i4Cg75P" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46518 -21.55686 14.94831 -1.016 16.805 27.696)" gradientUnits="userSpaceOnUse"><stop class="wxpqfzpjq"/><stop offset="1" class="b5dt48bim"/></radialGradient><radialGradient id="immTpwc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.68861 -6.09785 3.14876 -3.97019 19.203 24.54)" gradientUnits="userSpaceOnUse"><stop class="aahvt4qvi"/><stop offset="1" class="lu58bbcnf"/></radialGradient><radialGradient id="iNU4ziS" cx="0" cy="0" r="1" gradientTransform="matrix(2.43965 3.91822 -1.52236 .94788 9.74 16.667)" gradientUnits="userSpaceOnUse"><stop class="ezsjccx6w"/><stop offset="1" class="mwjeh-ubq"/></radialGradient><radialGradient id="icLy0Lc" cx="0" cy="0" r="1" gradientTransform="matrix(.08511 3.29874 -4.08121 .1053 9.593 10.339)" gradientUnits="userSpaceOnUse"><stop class="q4kuhe-hc"/><stop offset="1" class="ma39larlc"/><stop offset="1" class="krzj9mbxi"/></radialGradient><radialGradient id="ijJo5Xb" cx="0" cy="0" r="1" gradientTransform="matrix(2.99844 4.92595 -1.93444 1.1775 11.51 13.144)" gradientUnits="userSpaceOnUse"><stop class="u6ccby5ry"/><stop offset="1" class="apbyrzbvr"/></radialGradient><radialGradient id="iVEzdMe" cx="0" cy="0" r="1" gradientTransform="rotate(92.162 2.468 9.218)scale(2.99948 2.97789)" gradientUnits="userSpaceOnUse"><stop class="f4y457lcp"/><stop offset="1" class="qebft8bbw"/></radialGradient><radialGradient id="iVv6EBc" cx="0" cy="0" r="1" gradientTransform="rotate(56.246 -2.72 18.709)scale(7.9164 3.09735)" gradientUnits="userSpaceOnUse"><stop class="h600k8bzc"/><stop offset="1" class="m60jghblk"/></radialGradient><radialGradient id="i6ETSWc" cx="0" cy="0" r="1" gradientTransform="rotate(106.04 6.453 9.033)scale(4.45696 4.3873)" gradientUnits="userSpaceOnUse"><stop class="sqw-hybma"/><stop offset="1" class="g8len4apb"/></radialGradient><radialGradient id="ixqYDiv" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09956 3.33701 -3.63466 -2.28683 8.991 16.052)" gradientUnits="userSpaceOnUse"><stop class="jzyxoybxr"/><stop offset="1" class="gptanyfmh"/></radialGradient><radialGradient id="iKpicfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.9047 -12.2669 0 20.662 15.035)" gradientUnits="userSpaceOnUse"><stop class="cv5c98b9j"/><stop offset="1" class="w8zycbpzz"/></radialGradient><radialGradient id="ivvZcRd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.0596 .40152 -1.54153 -23.26408 32.917 21.709)" gradientUnits="userSpaceOnUse"><stop class="s5diuqbxo"/><stop offset="1" class="xw4am2b_q"/></radialGradient><radialGradient id="iD7Jdhd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03764 19.68894 -21.35266 -2.20982 25.1 15.873)" gradientUnits="userSpaceOnUse"><stop class="wibfg_jba"/><stop offset="1" class="kgna9sqpj"/></radialGradient><radialGradient id="i3OkUBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.48237 2.16901 -2.50769 -.55769 13.099 15.078)" gradientUnits="userSpaceOnUse"><stop class="g26mbfbxl"/><stop offset="1" class="rap9jfb3d"/></radialGradient><radialGradient id="i2ym6le" cx="0" cy="0" r="1" gradientTransform="matrix(4.03802 5.4702 -1.94688 1.43716 13.981 15.115)" gradientUnits="userSpaceOnUse"><stop class="ib_ba5bio"/><stop offset="1" class="kp6__jbnq"/></radialGradient><radialGradient id="i42wUfe" cx="0" cy="0" r="1" gradientTransform="rotate(71.222 .884 14.309)scale(3.49228 5.58798)" gradientUnits="userSpaceOnUse"><stop class="l58yxtbgg"/><stop offset="1" class="hzaqgvboq"/></radialGradient><radialGradient id="iMIhr4b" cx="0" cy="0" r="1" gradientTransform="rotate(48.528 -4.835 22.6)scale(7.97563 2.8404)" gradientUnits="userSpaceOnUse"><stop class="xe87prbmt"/><stop offset="1" class="omucezuxm"/></radialGradient><radialGradient id="iovFoae" cx="0" cy="0" r="1" gradientTransform="rotate(90.603 5.583 11.703)scale(3.66287 5.87108)" gradientUnits="userSpaceOnUse"><stop class="tzs413jvo"/><stop offset="1" class="h80tg8bto"/></radialGradient><radialGradient id="iaNeOEd" cx="0" cy="0" r="1" gradientTransform="matrix(6.05303 7.17112 -2.51201 2.12035 18.848 9.906)" gradientUnits="userSpaceOnUse"><stop class="mrh-ynbsm"/><stop offset="1" class="wags-nb2o"/></radialGradient><radialGradient id="i0Kzbxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.21918 2.84874 -4.22103 -.32476 21.547 5.896)" gradientUnits="userSpaceOnUse"><stop class="plbz0d_5y"/><stop offset="1" class="h29qz23ui"/></radialGradient><radialGradient id="i3A5uoe" cx="0" cy="0" r="1" gradientTransform="rotate(-89.085 20.117 -5.626)scale(6.20883 3.51252)" gradientUnits="userSpaceOnUse"><stop offset=".124" class="a87iyodzq"/><stop offset="1" class="yv8jl-bju"/></radialGradient><filter id="iujI1Pb" width="16.138" height="23.306" x="5.537" y="6.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.6 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3561"/></filter><filter id="i7wiljb" width="4.97" height="6.745" x="7.313" y="13.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".375"/></filter><filter id="i1R6yrb" width="4.694" height="6.195" x="8.842" y="10.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".375"/></filter><filter id="iVQVJLM" width="5.517" height="7.481" x="10.772" y="7.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".375"/></filter><filter id="i52m0Mb" width="2.662" height="3.25" x="6.875" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.580392 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3561"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.317647 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3561" result="effect2_innerShadow_20020_3561"/></filter><filter id="iFS81Mb" width="3.158" height="2.858" x="3.69" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3561"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3561" result="effect2_innerShadow_20020_3561"/></filter><filter id="iwSskYd" width="3.4" height="2.513" x="2.19" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.556863 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3561"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.301961 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3561" result="effect2_innerShadow_20020_3561"/></filter><filter id="i7VR16d" width="20.222" height="24.355" x="11.051" y="5.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.552941 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3561"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.35"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.588235 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3561" result="effect2_innerShadow_20020_3561"/></filter><filter id="iTnw33b" width="18.929" height="22.689" x="12.209" y="6.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation="1"/></filter><filter id="iiB2D7v" width="7.187" height="8.888" x="11.868" y="14.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".625"/></filter><filter id="iNUehee" width="8.754" height="11.125" x="13.556" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".625"/></filter><filter id="i4Df9yc" width="9.312" height="12.363" x="15.65" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".625"/></filter><filter id="i2QKi2e" width="7.879" height="10.948" x="19.462" y="6.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".625"/></filter><filter id="iHmSd8c" width="3.934" height="12.452" x="26.451" y="10.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3561" stdDeviation=".625"/></filter><linearGradient id="icAgw9d" x1="11.159" x2="7.065" y1="19.583" y2="15.141" gradientUnits="userSpaceOnUse"><stop class="aihg8urgv"/><stop offset="1" class="m46cb7bak"/></linearGradient><linearGradient id="iLpjWZZ" x1="10.092" x2="15.985" y1="12.01" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="vmz6nkntt"/><stop offset="1" class="yzkaexbuy"/></linearGradient><linearGradient id="iNDXmwd" x1="12.809" x2="19.133" y1="7.722" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="p3xj3_l9g"/><stop offset="1" class="h6jk3tbmj"/><stop offset="1" class="w-6j43beb"/></linearGradient><linearGradient id="ikHnpYc" x1="28.418" x2="28.418" y1="12.587" y2="21.288" gradientUnits="userSpaceOnUse"><stop class="py05vebrj"/><stop offset="1" class="btubfmbhj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clapping-hands-light" /></template>
<style>
.a87iyodzq {
  stop-color: var(--svg-color--c88c6b, #C88C6B);
}

.aahvt4qvi {
  stop-color: var(--svg-color--b0736c, #B0736C);
}

.aihg8urgv {
  stop-color: var(--svg-color--d3a48d, #D3A48D);
}

.apbyrzbvr {
  stop-color: var(--svg-color--bc8067, #BC8067);
  stop-opacity: 0;
}

.asqc_1_dp {
  stroke-linecap: round;
  d: path("m10.092 11.67l2.194 3.695");
}

.at05xybeo {
  d: path("m18.68 24.347l-4.347-7.37a.894.894 0 0 1 1.51-.954l2.457 3.631a.667.667 0 0 0 1.115-.73l-3.83-6.036a.866.866 0 1 1 1.473-.91l3.733 6.205a.627.627 0 0 0 1.08-.636l-4.28-7.421a.956.956 0 0 1 1.654-.96l4.405 7.54a.553.553 0 0 0 .963-.544l-2.878-5.264a.908.908 0 0 1 1.586-.883l3.335 5.889c.004-.124.076-.751.173-1.153c.33-1.359.774-1.89 1.258-1.89c.501 0 1.091.214.93 1.788c-.32 3.126-.058 5.292 0 5.7c.058.406.953 4.761-3.176 6.593c-3.303 1.466-6.24-1.093-7.16-2.596");
}

.azatxnbcy {
  stroke: var(--svg-color--ffe3c8, #FFE3C8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m17.525 8.397l5.561 8.613");
}

.b5dt48bim {
  stop-color: var(--svg-color--cf9a84, #CF9A84);
}

.btubfmbhj {
  stop-color: var(--svg-color--ffe4c8, #FFE4C8);
  stop-opacity: 0;
}

.cv5c98b9j {
  stop-color: var(--svg-color--e8b49c, #E8B49C);
}

.e2mbiomkg {
  d: path("M15.905 7.055a2.114 2.114 0 0 0-.691 2.907l.084.137c.57.097 1.099.43 1.427.962l5.314 8.622a2.114 2.114 0 0 0 2.167-3.19l-5.393-8.75a2.114 2.114 0 0 0-2.908-.688");
}

.extfw-zmg {
  stroke: var(--svg-color--ffe4c9, #FFE4C9);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m21.337 8.125l4.13 7.198");
}

.ezsjccx6w {
  stop-color: var(--svg-color--b87c69, #B87C69);
}

.f4y457lcp {
  stop-color: var(--svg-color--e6bfa5, #E6BFA5);
}

.fdnjngwjh {
  d: path("m28.594 18.323l-2.753-5.217l.01-.195a2.183 2.183 0 1 1 4.36.21l-.156 3.246a2.18 2.18 0 0 1-1.462 1.956");
}

.fssmy6bpn {
  width: 4.224px;
  height: 14.575px;
  x: 4.757px;
  y: 15.519px;
  rx: 2.112px;
}

.ft5dv1b6b {
  fill: none;
}

.g26mbfbxl {
  stop-color: var(--svg-color--e5b399, #E5B399);
}

.g8len4apb {
  stop-color: var(--svg-color--ddb49a, #DDB49A);
  stop-opacity: 0;
}

.gptanyfmh {
  stop-color: var(--svg-color--ce9f87, #CE9F87);
  stop-opacity: 0;
}

.gwznzxt3m {
  d: path("M13.854 10.38a2.087 2.087 0 0 0-.682 2.87l.527.855c.507.133.965.454 1.262.935l4.887 7.93a2.087 2.087 0 0 0 2.296-3.116l-5.42-8.793a2.087 2.087 0 0 0-2.87-.681");
}

.h29qz23ui {
  stop-color: var(--svg-color--fed3b6, #FED3B6);
  stop-opacity: 0;
}

.h600k8bzc {
  stop-color: var(--svg-color--ba8567, #BA8567);
}

.h6jk3tbmj {
  stop-color: var(--svg-color--cda587, #CDA587);
  stop-opacity: 0;
}

.h80tg8bto {
  stop-color: var(--svg-color--faceb2, #FACEB2);
  stop-opacity: 0;
}

.hzaqgvboq {
  stop-color: var(--svg-color--e3b398, #E3B398);
  stop-opacity: 0;
}

.i36s1qb_g {
  d: path("M10.307 7.382a2.107 2.107 0 0 0-.787 2.85l.077.14a2.07 2.07 0 0 1 1.43 1.004l3.569 6.183a2.27 2.27 0 0 0 2.284-3.436l-3.727-6.024a2.107 2.107 0 0 0-2.846-.717");
}

.ib_ba5bio {
  stop-color: var(--svg-color--e29f7f, #E29F7F);
}

.ihs0mo99f {
  fill: var(--svg-color--187ec9, #187EC9);
  d: path("m8.336 4.887l-1.22-1.651a.468.468 0 0 1 .23-.723l1.36-.423c.3-.093.6.155.58.475l-.14 2.075c-.04.423-.56.588-.81.247");
}

.jzyxoybxr {
  stop-color: var(--svg-color--ce9f87, #CE9F87);
}

.kgna9sqpj {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
  stop-opacity: 0;
}

.kp6__jbnq {
  stop-color: var(--svg-color--e29f7f, #E29F7F);
  stop-opacity: 0;
}

.krzj9mbxi {
  stop-color: var(--svg-color--deb198, #DEB198);
  stop-opacity: 0;
}

.l58yxtbgg {
  stop-color: var(--svg-color--e3b398, #E3B398);
}

.l79n4x80f {
  fill: var(--svg-color--1c75c1, #1C75C1);
  d: path("m4.932 9.305l-2.072.27a.463.463 0 0 1-.507-.57l.341-1.433a.472.472 0 0 1 .715-.28l1.73 1.162c.352.25.217.8-.207.851");
}

.lu58bbcnf {
  stop-color: var(--svg-color--b0736c, #B0736C);
  stop-opacity: 0;
}

.m25qys66g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M28.51 12.587c-.311 2.733-.17 6.34 0 8.702");
}

.m46cb7bak {
  stop-color: var(--svg-color--d3a48d, #D3A48D);
  stop-opacity: 0;
}

.m60jghblk {
  stop-color: var(--svg-color--ba8567, #BA8567);
  stop-opacity: 0;
}

.ma39larlc {
  stop-color: var(--svg-color--b48e70, #B48E70);
  stop-opacity: 0;
}

.ma8v-lhgu {
  d: path("M20.308 29.269a6.863 6.863 0 0 0 9.199-3.32l.018.004c.955-1.96.778-3.607.632-4.972c-.036-.334-.07-.65-.085-.95c-.047-.907-.039-2.446-.02-3.605l.003-.06l.156-3.245a2.183 2.183 0 1 0-4.36-.21l-.01.192l-2.846-5.392a2.114 2.114 0 0 0-3.917.462l-.265-.43a2.114 2.114 0 0 0-3.6 2.22l.085.136a2.087 2.087 0 0 0-2.125 3.152l.526.854a2.112 2.112 0 0 0-2.334 3.15l5.378 8.726c1.11 1.753 2.528 2.79 3.565 3.288");
}

.mrh-ynbsm {
  stop-color: var(--svg-color--e6a580, #E6A580);
}

.mwjeh-ubq {
  stop-color: var(--svg-color--b87c69, #B87C69);
  stop-opacity: 0;
}

.omucezuxm {
  stop-color: var(--svg-color--e5a584, #E5A584);
  stop-opacity: 0;
}

.p3xj3_l9g {
  stop-color: var(--svg-color--eec9b3, #EEC9B3);
}

.plbz0d_5y {
  stop-color: var(--svg-color--fed3b6, #FED3B6);
}

.py05vebrj {
  stop-color: var(--svg-color--ffe4c8, #FFE4C8);
}

.q4kuhe-hc {
  stop-color: var(--svg-color--deb198, #DEB198);
}

.qebft8bbw {
  stop-color: var(--svg-color--e6bfa5, #E6BFA5);
  stop-opacity: 0;
}

.rap9jfb3d {
  stop-color: var(--svg-color--e5b399, #E5B399);
  stop-opacity: 0;
}

.s5diuqbxo {
  stop-color: var(--svg-color--ffe1c4, #FFE1C4);
}

.shnmtibet {
  stroke: var(--svg-color--ffe0c7, #FFE0C7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.431 11.594l5.004 7.375");
}

.sqw-hybma {
  stop-color: var(--svg-color--ddb49a, #DDB49A);
}

.tjvmr_b3b {
  d: path("m13.64 8.885l3.24 5.238a2.26 2.26 0 0 1 .289 1.67l.26.466a2.184 2.184 0 1 0 3.766-2.21l-3.808-6.173a2.025 2.025 0 0 0-3.747 1.01");
}

.tzs413jvo {
  stop-color: var(--svg-color--faceb2, #FACEB2);
}

.u6ccby5ry {
  stop-color: var(--svg-color--bc8067, #BC8067);
}

.vc46r_c8i {
  stroke-linecap: round;
  d: path("m8.563 15.194l2.47 4.245");
}

.vmz6nkntt {
  stop-color: var(--svg-color--e2b49d, #E2B49D);
}

.w_ccelber {
  stroke-linecap: round;
  d: path("m12.022 8.397l3.017 4.981");
}

.w-6j43beb {
  stop-color: var(--svg-color--f7cbb1, #F7CBB1);
  stop-opacity: 0;
}

.w05axs7ko {
  d: path("M13.64 8.885a2.024 2.024 0 0 1 3.747-1.009l3.808 6.172a2.184 2.184 0 1 1-3.766 2.211l-.26-.466a2.26 2.26 0 0 1-1.096 1.496a2.26 2.26 0 0 1-1.477.27l.03.053c.331.573.366 1.236.152 1.811l6.747 9.655c-.781.469-2.867 1.36-5.805.594c-2.71-.875-4.055-2.422-4.992-4.016L5.826 17.29a2.119 2.119 0 0 1 1.97-3.183l-.38-.683a2.075 2.075 0 0 1 2.181-3.053l-.077-.138a2.107 2.107 0 0 1 3.633-2.135z");
}

.w8zycbpzz {
  stop-color: var(--svg-color--e8b0ab, #E8B0AB);
}

.wags-nb2o {
  stop-color: var(--svg-color--e6a580, #E6A580);
  stop-opacity: 0;
}

.wibfg_jba {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
}

.wxpqfzpjq {
  stop-color: var(--svg-color--b17883, #B17883);
}

.x28j_obaq {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m5.976 6.51l-1.86-.78a.443.443 0 0 1-.15-.72l.97-1.03a.45.45 0 0 1 .73.11l.89 1.81c.17.37-.2.77-.58.61");
}

.xe87prbmt {
  stop-color: var(--svg-color--e5a584, #E5A584);
}

.xw4am2b_q {
  stop-color: var(--svg-color--ffe1c4, #FFE1C4);
  stop-opacity: 0;
}

.yet1k9bwh {
  d: path("m19.078 8.173l5.128 8.32a2.11 2.11 0 0 1-.104 2.369a2.114 2.114 0 0 0 3.69-2.062l-4.797-9.09a2.114 2.114 0 0 0-3.917.463");
}

.yjan3rbwm {
  stroke: var(--svg-color--ffddc7, #FFDDC7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m13.744 16l3.437 5.138");
}

.yv8jl-bju {
  stop-color: var(--svg-color--e5a886, #E5A886);
  stop-opacity: 0;
}

.yzkaexbuy {
  stop-color: var(--svg-color--e2b49d, #E2B49D);
  stop-opacity: 0;
}

.z7kzdbcte {
  width: 4.224px;
  height: 14.575px;
  x: 10.257px;
  y: 15.458px;
  rx: 2.112px;
}

.z7wy6obpq {
  d: path("M8.191 10.617a2.075 2.075 0 0 0-.775 2.807l.38.683c.681.046 1.328.42 1.694 1.055l3.26 5.646a2.13 2.13 0 0 0 1.877-3.196l-3.6-6.236a2.075 2.075 0 0 0-2.836-.76");
}

</style>
