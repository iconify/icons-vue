<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i72FtsV)"><path fill="url(#i5ZERgd)" class="pcfnb1bnp"/><path fill="url(#iLUxmEd)" class="pcfnb1bnp"/></g><path fill="url(#ib2hHkc)" class="eyk2tn4-r"/><path fill="url(#iFUwTZb)" class="eyk2tn4-r"/><path fill="url(#ipGsYje)" class="vfev9ybss"/><path fill="url(#iUj51ke)" class="vfev9ybss"/><path fill="url(#ioyZNrd)" class="nl9gheb2o"/><path fill="url(#iYKXRSc)" class="nl9gheb2o"/><rect fill="url(#iCSm4ee)" transform="rotate(-31.647 4.338 15.519)" class="m07v0_-pq"/><g filter="url(#i0hPwIc)"><path stroke="url(#ivllVFd)" class="uecdko76d"/></g><g filter="url(#iAvIENc)"><path stroke="url(#itF83Zd)" class="a-vv_ndrg"/></g><g filter="url(#iEafdTx)"><path stroke="url(#iaK5vud)" class="wf2m7bbev"/></g><g filter="url(#iZuo3cc)"><path class="qh58g99ty"/></g><g filter="url(#ibpWLPd)"><path class="jeyihjnqg"/></g><g filter="url(#ikQFQCb)"><path class="b2nt1accl"/></g><g filter="url(#ihlMgrb)"><path fill="url(#iYuVzcb)" class="sv_-5usyo"/></g><path fill="url(#i2Q5rDe)" class="sv_-5usyo"/><g filter="url(#icA74zc)"><path fill="url(#iYNyvsb)" class="gxu5vkc5b"/></g><rect fill="url(#iX6h9bc)" transform="rotate(-31.647 9.838 15.458)" class="kugmxmeke"/><path fill="url(#ichDm1d)" class="wvhcwbccy"/><path fill="url(#i3ewlFe)" class="wvhcwbccy"/><path fill="url(#ijtQ1Lb)" class="y79u9ibku"/><path fill="url(#iZF2zRp)" class="y79u9ibku"/><path fill="url(#iVOwsxe)" class="tq_6dz1iz"/><path fill="url(#iwENvSz)" class="tq_6dz1iz"/><path fill="url(#iIJafvP)" class="d3o9x91qq"/><g filter="url(#i4WinRb)"><path class="zos2jibgo"/></g><g filter="url(#iYkcZvd)"><path class="l86ej0btg"/></g><g filter="url(#ipF2wZc)"><path class="v-u6usbto"/></g><g filter="url(#iJFFJHc)"><path class="lhgmtq07t"/></g><g filter="url(#iKiOG1L)"><path stroke="url(#imvjOJd)" class="djb35nr9z"/></g><defs><radialGradient id="i5ZERgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46518 -21.55686 14.94831 -1.016 16.386 27.696)" gradientUnits="userSpaceOnUse"><stop class="xmltm9bsi"/><stop offset="1" class="r1t-jsbwe"/><stop offset="1" class="xr5fdybvb"/></radialGradient><radialGradient id="iLUxmEd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.68861 -6.09785 3.14876 -3.97019 18.784 24.54)" gradientUnits="userSpaceOnUse"><stop class="q78g4bcgl"/><stop offset="1" class="zw-4t_mcn"/></radialGradient><radialGradient id="ib2hHkc" cx="0" cy="0" r="1" gradientTransform="matrix(2.43965 3.91822 -1.52236 .94788 9.321 16.667)" gradientUnits="userSpaceOnUse"><stop class="axi25jnsq"/><stop offset="1" class="qy6htccfe"/></radialGradient><radialGradient id="iFUwTZb" cx="0" cy="0" r="1" gradientTransform="matrix(.2555 4.19791 -4.06757 .24757 9.536 8.714)" gradientUnits="userSpaceOnUse"><stop class="yr7vcibzf"/><stop offset="1" class="v62_09chs"/></radialGradient><radialGradient id="ipGsYje" cx="0" cy="0" r="1" gradientTransform="rotate(57.875 -6.509 16.482)scale(5.63049 1.95545)" gradientUnits="userSpaceOnUse"><stop class="axi25jnsq"/><stop offset="1" class="qy6htccfe"/></radialGradient><radialGradient id="iUj51ke" cx="0" cy="0" r="1" gradientTransform="matrix(-.07301 3.86938 -3.84317 -.07252 12.056 6.852)" gradientUnits="userSpaceOnUse"><stop class="yr7vcibzf"/><stop offset="1" class="v62_09chs"/></radialGradient><radialGradient id="ioyZNrd" cx="0" cy="0" r="1" gradientTransform="matrix(3.94053 6.40474 -3.28048 2.01832 13.221 10.974)" gradientUnits="userSpaceOnUse"><stop class="axi25jnsq"/><stop offset="1" class="qy6htccfe"/></radialGradient><radialGradient id="iYKXRSc" cx="0" cy="0" r="1" gradientTransform="rotate(90.731 5.484 10.846)scale(5.02777 4.95055)" gradientUnits="userSpaceOnUse"><stop class="yr7vcibzf"/><stop offset="1" class="v62_09chs"/></radialGradient><radialGradient id="iCSm4ee" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09956 3.33701 -3.63466 -2.28683 8.572 16.052)" gradientUnits="userSpaceOnUse"><stop class="r_y5avbtc"/><stop offset="1" class="v2ljpibpn"/></radialGradient><radialGradient id="iYuVzcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.9047 -12.2669 0 20.24 15.054)" gradientUnits="userSpaceOnUse"><stop class="mhxfvkb8l"/><stop offset="1" class="mj_prhp-u"/></radialGradient><radialGradient id="i2Q5rDe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.0596 .40152 -1.54153 -23.26408 32.498 21.709)" gradientUnits="userSpaceOnUse"><stop class="bcsvc3b7q"/><stop offset="1" class="vaoqi81jx"/></radialGradient><radialGradient id="iYNyvsb" cx="0" cy="0" r="1" gradientTransform="rotate(101.704 4.353 19.183)scale(15.1907 16.4744)" gradientUnits="userSpaceOnUse"><stop class="c3frvkbxg"/><stop offset="1" class="jw1j8wrph"/></radialGradient><radialGradient id="iX6h9bc" cx="0" cy="0" r="1" gradientTransform="matrix(-.48237 2.16901 -2.50769 -.55769 12.68 15.078)" gradientUnits="userSpaceOnUse"><stop class="xu-6znbqk"/><stop offset="1" class="ic436bc1m"/></radialGradient><radialGradient id="ichDm1d" cx="0" cy="0" r="1" gradientTransform="matrix(4.03802 5.4702 -1.94688 1.43716 13.562 15.115)" gradientUnits="userSpaceOnUse"><stop class="bzck41b3w"/><stop offset="1" class="k-37q4apu"/></radialGradient><radialGradient id="i3ewlFe" cx="0" cy="0" r="1" gradientTransform="rotate(71.222 .674 14.016)scale(3.49228 5.58798)" gradientUnits="userSpaceOnUse"><stop class="dfbfvpbwu"/><stop offset="1" class="xumekwshu"/></radialGradient><radialGradient id="ijtQ1Lb" cx="0" cy="0" r="1" gradientTransform="rotate(48.528 -5.044 22.136)scale(7.97563 2.8404)" gradientUnits="userSpaceOnUse"><stop class="bzck41b3w"/><stop offset="1" class="k-37q4apu"/></radialGradient><radialGradient id="iZF2zRp" cx="0" cy="0" r="1" gradientTransform="rotate(90.603 5.374 11.496)scale(3.66287 5.87108)" gradientUnits="userSpaceOnUse"><stop class="dfbfvpbwu"/><stop offset="1" class="xumekwshu"/></radialGradient><radialGradient id="iVOwsxe" cx="0" cy="0" r="1" gradientTransform="matrix(6.05303 7.17112 -2.51201 2.12035 18.429 9.906)" gradientUnits="userSpaceOnUse"><stop class="bzck41b3w"/><stop offset="1" class="k-37q4apu"/></radialGradient><radialGradient id="iwENvSz" cx="0" cy="0" r="1" gradientTransform="matrix(-.21918 2.84874 -4.22103 -.32476 21.128 5.896)" gradientUnits="userSpaceOnUse"><stop class="dfbfvpbwu"/><stop offset="1" class="xumekwshu"/></radialGradient><radialGradient id="iIJafvP" cx="0" cy="0" r="1" gradientTransform="matrix(.0992 -6.20804 2.80932 .04489 25.002 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".124" class="otv_ve-ci"/><stop offset="1" class="tn07w3ffw"/></radialGradient><filter id="i72FtsV" width="16.138" height="23.306" x="5.118" y="6.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.364706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3511"/></filter><filter id="i0hPwIc" width="4.97" height="6.745" x="6.894" y="13.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".375"/></filter><filter id="iAvIENc" width="4.694" height="6.195" x="8.423" y="10.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".375"/></filter><filter id="iEafdTx" width="5.517" height="7.481" x="10.353" y="7.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".375"/></filter><filter id="iZuo3cc" width="2.662" height="3.25" x="6.456" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.580392 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.317647 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3511" result="effect2_innerShadow_20020_3511"/></filter><filter id="ibpWLPd" width="3.158" height="2.858" x="3.271" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3511" result="effect2_innerShadow_20020_3511"/></filter><filter id="ikQFQCb" width="3.4" height="2.513" x="1.771" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.556863 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.301961 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3511" result="effect2_innerShadow_20020_3511"/></filter><filter id="ihlMgrb" width="20.222" height="24.355" x="10.632" y="5.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.419608 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.629167 0 0 0 0 0.44566 0 0 0 0 0.482361 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3511" result="effect2_innerShadow_20020_3511"/></filter><filter id="icA74zc" width="18.929" height="22.689" x="11.622" y="6.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation="1"/></filter><filter id="i4WinRb" width="7.187" height="8.888" x="11.449" y="14.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".625"/></filter><filter id="iYkcZvd" width="8.754" height="11.125" x="13.137" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".625"/></filter><filter id="ipF2wZc" width="9.312" height="12.363" x="15.231" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".625"/></filter><filter id="iJFFJHc" width="7.879" height="10.948" x="19.043" y="6.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".625"/></filter><filter id="iKiOG1L" width="3.934" height="12.452" x="26.032" y="10.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3511" stdDeviation=".625"/></filter><linearGradient id="ivllVFd" x1="10.74" x2="6.646" y1="19.583" y2="15.141" gradientUnits="userSpaceOnUse"><stop class="sa36ev_ej"/><stop offset="1" class="y9clnibqj"/></linearGradient><linearGradient id="itF83Zd" x1="9.673" x2="15.566" y1="12.01" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="jq_2k07we"/><stop offset="1" class="dfv8ieppm"/></linearGradient><linearGradient id="iaK5vud" x1="12.389" x2="18.714" y1="7.722" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="qzv58jbzf"/><stop offset="1" class="p_zcpv0xf"/></linearGradient><linearGradient id="imvjOJd" x1="27.998" x2="27.998" y1="12.587" y2="21.288" gradientUnits="userSpaceOnUse"><stop class="v3b5nab-t"/><stop offset="1" class="l87e85bei"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clapping-hands-medium" /></template>
<style>
.a-vv_ndrg {
  stroke-linecap: round;
  d: path("m9.673 11.67l2.194 3.695");
}

.axi25jnsq {
  stop-color: var(--svg-color--3d2a1e, #3D2A1E);
}

.b2nt1accl {
  fill: var(--svg-color--1c75c1, #1C75C1);
  d: path("m4.513 9.305l-2.072.27a.463.463 0 0 1-.507-.57l.341-1.433a.472.472 0 0 1 .715-.28l1.73 1.162c.352.25.217.8-.207.851");
}

.bcsvc3b7q {
  stop-color: var(--svg-color--c8a185, #C8A185);
}

.bzck41b3w {
  stop-color: var(--svg-color--75513e, #75513E);
}

.c3frvkbxg {
  stop-color: var(--svg-color--cba28d, #CBA28D);
}

.d3o9x91qq {
  d: path("m28.174 18.323l-2.752-5.217l.01-.195a2.183 2.183 0 0 1 4.36.21l-.156 3.246a2.18 2.18 0 0 1-1.462 1.956");
}

.dfbfvpbwu {
  stop-color: var(--svg-color--b9987c, #B9987C);
}

.dfv8ieppm {
  stop-color: var(--svg-color--786155, #786155);
  stop-opacity: 0;
}

.djb35nr9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M28.09 12.587c-.31 2.733-.168 6.34 0 8.702");
}

.eyk2tn4-r {
  d: path("M7.772 10.617a2.075 2.075 0 0 0-.775 2.807l.38.683c.681.046 1.328.42 1.694 1.055l3.26 5.646a2.13 2.13 0 0 0 1.877-3.196l-3.6-6.236a2.075 2.075 0 0 0-2.836-.76");
}

.ft5dv1b6b {
  fill: none;
}

.gxu5vkc5b {
  d: path("m18.093 24.509l-4.347-7.369a.893.893 0 0 1 1.51-.955l2.457 3.632a.667.667 0 0 0 1.115-.731l-3.83-6.036a.866.866 0 1 1 1.473-.91l3.733 6.205a.627.627 0 0 0 1.08-.636l-4.28-7.42a.956.956 0 0 1 1.654-.96l4.405 7.54a.553.553 0 0 0 .963-.544l-2.878-5.264a.908.908 0 0 1 1.586-.883l3.335 5.888c.004-.124.076-.75.173-1.153c.33-1.359.774-1.89 1.258-1.89c.501 0 1.091.214.93 1.788c-.32 3.126-.058 5.293 0 5.7s.953 4.762-3.176 6.594c-3.303 1.465-6.24-1.094-7.16-2.596");
}

.ic436bc1m {
  stop-color: var(--svg-color--957660, #957660);
  stop-opacity: 0;
}

.jeyihjnqg {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m5.557 6.51l-1.86-.78a.443.443 0 0 1-.15-.72l.97-1.03a.45.45 0 0 1 .73.11l.89 1.81c.17.37-.2.77-.58.61");
}

.jq_2k07we {
  stop-color: var(--svg-color--786155, #786155);
}

.jw1j8wrph {
  stop-color: var(--svg-color--cba28d, #CBA28D);
  stop-opacity: 0;
}

.k-37q4apu {
  stop-color: var(--svg-color--8e625d, #8E625D);
  stop-opacity: 0;
}

.kugmxmeke {
  width: 4.224px;
  height: 14.575px;
  x: 9.838px;
  y: 15.458px;
  rx: 2.112px;
}

.l86ej0btg {
  stroke: var(--svg-color--cea58f, #CEA58F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.012 11.594l5.004 7.375");
}

.l87e85bei {
  stop-color: var(--svg-color--d0a88f, #D0A88F);
  stop-opacity: 0;
}

.lhgmtq07t {
  stroke: var(--svg-color--d0a88f, #D0A88F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m20.918 8.125l4.13 7.198");
}

.m07v0_-pq {
  width: 4.224px;
  height: 14.575px;
  x: 4.338px;
  y: 15.519px;
  rx: 2.112px;
}

.mhxfvkb8l {
  stop-color: var(--svg-color--9b7466, #9B7466);
}

.mj_prhp-u {
  stop-color: var(--svg-color--b57f81, #B57F81);
}

.nl9gheb2o {
  d: path("m13.22 8.885l3.24 5.238a2.26 2.26 0 0 1 .29 1.67l.26.466a2.184 2.184 0 1 0 3.766-2.21l-3.808-6.173a2.025 2.025 0 0 0-3.747 1.01");
}

.otv_ve-ci {
  stop-color: var(--svg-color--76533e, #76533E);
}

.p_zcpv0xf {
  stop-color: var(--svg-color--9e8270, #9E8270);
  stop-opacity: 0;
}

.pcfnb1bnp {
  d: path("M13.22 8.885a2.023 2.023 0 0 1 3.748-1.009l3.808 6.172a2.184 2.184 0 1 1-3.766 2.211l-.26-.466a2.26 2.26 0 0 1-1.097 1.496a2.26 2.26 0 0 1-1.476.27l.03.053c.331.573.366 1.236.151 1.811l6.748 9.655c-.782.469-2.868 1.36-5.805.594c-2.71-.875-4.055-2.422-4.992-4.016L5.407 17.29a2.119 2.119 0 0 1 1.97-3.183l-.38-.683a2.075 2.075 0 0 1 2.181-3.053l-.077-.138a2.107 2.107 0 0 1 3.633-2.135z");
}

.q78g4bcgl {
  stop-color: var(--svg-color--59363a, #59363A);
}

.qh58g99ty {
  fill: var(--svg-color--187ec9, #187EC9);
  d: path("m7.917 4.887l-1.22-1.651a.468.468 0 0 1 .23-.723l1.36-.423c.3-.093.6.155.58.475l-.14 2.075c-.04.423-.56.588-.81.247");
}

.qy6htccfe {
  stop-color: var(--svg-color--3d2a1e, #3D2A1E);
  stop-opacity: 0;
}

.qzv58jbzf {
  stop-color: var(--svg-color--9e8270, #9E8270);
}

.r_y5avbtc {
  stop-color: var(--svg-color--745a46, #745A46);
}

.r1t-jsbwe {
  stop-color: var(--svg-color--5c433a, #5C433A);
}

.sa36ev_ej {
  stop-color: var(--svg-color--72584e, #72584E);
}

.sv_-5usyo {
  d: path("M19.889 29.269a6.863 6.863 0 0 0 9.199-3.32l.018.004c.954-1.96.778-3.607.631-4.972c-.035-.334-.07-.65-.084-.95c-.047-.907-.039-2.446-.02-3.605l.003-.06l.156-3.245a2.183 2.183 0 1 0-4.36-.21l-.01.192l-2.846-5.392a2.114 2.114 0 0 0-3.917.462l-.265-.43a2.114 2.114 0 0 0-3.6 2.22l.085.136a2.087 2.087 0 0 0-2.125 3.152l.526.854a2.112 2.112 0 0 0-2.334 3.15l5.378 8.726c1.11 1.753 2.528 2.79 3.565 3.288");
}

.tn07w3ffw {
  stop-color: var(--svg-color--76533e, #76533E);
  stop-opacity: 0;
}

.tq_6dz1iz {
  d: path("m18.66 8.173l5.127 8.32a2.11 2.11 0 0 1-.104 2.369a2.114 2.114 0 0 0 3.69-2.062l-4.797-9.09a2.114 2.114 0 0 0-3.917.463");
}

.uecdko76d {
  stroke-linecap: round;
  d: path("m8.144 15.194l2.47 4.245");
}

.v-u6usbto {
  stroke: var(--svg-color--d0a78e, #D0A78E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m17.106 8.397l5.561 8.613");
}

.v2ljpibpn {
  stop-color: var(--svg-color--745a46, #745A46);
  stop-opacity: 0;
}

.v3b5nab-t {
  stop-color: var(--svg-color--d0a88f, #D0A88F);
}

.v62_09chs {
  stop-color: var(--svg-color--967b66, #967B66);
  stop-opacity: 0;
}

.vaoqi81jx {
  stop-color: var(--svg-color--c8a185, #C8A185);
  stop-opacity: 0;
}

.vfev9ybss {
  d: path("M9.888 7.382a2.107 2.107 0 0 0-.787 2.85l.077.14a2.07 2.07 0 0 1 1.43 1.004l3.569 6.183a2.27 2.27 0 0 0 2.284-3.436l-3.727-6.024a2.107 2.107 0 0 0-2.846-.717");
}

.wf2m7bbev {
  stroke-linecap: round;
  d: path("m11.603 8.397l3.017 4.981");
}

.wvhcwbccy {
  d: path("M13.435 10.38a2.087 2.087 0 0 0-.682 2.87l.527.855c.507.133.965.454 1.262.935l4.887 7.93a2.087 2.087 0 0 0 2.296-3.116l-5.42-8.793a2.087 2.087 0 0 0-2.87-.681");
}

.xmltm9bsi {
  stop-color: var(--svg-color--72415c, #72415C);
}

.xr5fdybvb {
  stop-color: var(--svg-color--785d4e, #785D4E);
}

.xu-6znbqk {
  stop-color: var(--svg-color--957660, #957660);
}

.xumekwshu {
  stop-color: var(--svg-color--b9987c, #B9987C);
  stop-opacity: 0;
}

.y79u9ibku {
  d: path("M15.486 7.055a2.114 2.114 0 0 0-.692 2.907l.085.137c.57.097 1.099.43 1.427.962l5.313 8.622a2.114 2.114 0 0 0 2.167-3.19l-5.392-8.75a2.114 2.114 0 0 0-2.908-.688");
}

.y9clnibqj {
  stop-color: var(--svg-color--72584e, #72584E);
  stop-opacity: 0;
}

.yr7vcibzf {
  stop-color: var(--svg-color--967b66, #967B66);
}

.zos2jibgo {
  stroke: var(--svg-color--cca38e, #CCA38E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m13.325 16l3.437 5.138");
}

.zw-4t_mcn {
  stop-color: var(--svg-color--59363a, #59363A);
  stop-opacity: 0;
}

</style>
