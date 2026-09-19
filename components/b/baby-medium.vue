<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWogLqd)" class="y6_96bc0u"/><path fill="url(#ivR3J5d)" class="y6_96bc0u"/><g filter="url(#ixQCi5R)"><path fill="url(#il8jfue)" class="aeq3b5eaz"/></g><path fill="url(#iGTZOpd)" class="sg8_yd1ki"/><path fill="url(#il6HrUc)" class="sg8_yd1ki"/><path fill="url(#iCz5yNc)" class="sg8_yd1ki"/><path fill="url(#iSN6oZd)" class="sg8_yd1ki"/><g filter="url(#iNkC9Bb)"><path fill="url(#itBbXKS)" class="dfyl80b-o"/></g><g filter="url(#iFTZXpb)"><path class="voi7bsp-n"/><path fill="url(#i3hRwIb)" class="mg_atlbaz"/><path fill="url(#iGqY9Bc)" class="mg_atlbaz"/><path fill="url(#ijy2cZc)" class="mg_atlbaz"/><path fill="url(#irHopGb)" class="mg_atlbaz"/><path fill="url(#iaDhLWc)" class="mg_atlbaz"/><path fill="url(#ijXTZve)" class="mg_atlbaz"/><path fill="url(#iWQIWhe)" class="mg_atlbaz"/></g><path fill="url(#iW19Zwd)" class="mg_atlbaz"/><g filter="url(#iJvXZNb)"><path stroke="url(#iGxUnZb)" class="m_5n1fdcs"/></g><g filter="url(#iRFEWsd)"><path class="vxo60ibid"/></g><path class="vzt7qccog"/><path fill="url(#iD3yGyN)" class="ff94iibzr"/><path fill="url(#ixdTmbc)" class="jzvo7dbde"/><path class="ppzwdooyh"/><g filter="url(#iioDTld)"><path class="pwql01bzt"/></g><g filter="url(#i4qkOSb)"><path stroke="url(#ij8QPkd)" class="v6wnqjbhz"/></g><g filter="url(#iA7cw1c)"><path class="s6paz2s8i"/></g><g filter="url(#i7yV3pe)"><path stroke="url(#i1jBF8b)" class="s9j2c3bac"/></g><g filter="url(#igIdshe)"><path fill="url(#iVepHUc)" class="fmpz47b8m"/></g><g filter="url(#iZf7GFN)"><path class="pnrar_k6f"/><path fill="url(#iVPhvic)" class="o0a2zx15p"/><path fill="url(#i1EpOwe)" class="o0a2zx15p"/><path fill="url(#iaNXKac)" class="o0a2zx15p"/><path fill="url(#ixQaPMd)" class="o0a2zx15p"/></g><g filter="url(#iofCIXc)"><path class="oehfy885c"/></g><g filter="url(#i3YQ3Vb)"><path fill="url(#ibdU67c)" class="jpz13g5lx"/><path fill="url(#iUbWUFb)" class="jpz13g5lx"/></g><g filter="url(#i7pub3c)"><path class="t42aur0hp"/><path fill="url(#iOGxgFd)" class="ol7lm4ezu"/></g><g filter="url(#iZSYeWd)"><path fill="url(#iDGf3sh)" class="l4zna2bvp"/></g><g filter="url(#i21qjob)"><path fill="url(#iDtNiQb)" class="tya6kmb_o"/></g><g filter="url(#i0nmNad)"><ellipse transform="rotate(-27.914 10.689 18.824)" class="tsloc8bkm"/><ellipse fill="url(#iokWMuc)" transform="rotate(-27.914 10.689 18.824)" class="ty6h_vbkp"/></g><g filter="url(#iXOPdse)"><path fill="url(#iNsZihj)" class="m9kkbzbxx"/></g><defs><radialGradient id="ivR3J5d" cx="0" cy="0" r="1" gradientTransform="rotate(176.967 3.05 10.133)scale(3.54403 3.68531)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="wg-tntuud"/><stop offset="1" class="nihqa2baf"/></radialGradient><radialGradient id="il8jfue" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.635 13.268)scale(2.01965)" gradientUnits="userSpaceOnUse"><stop class="wfxx9nv4c"/><stop offset="1" class="ninfq3frf"/></radialGradient><radialGradient id="il6HrUc" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 3.786 22.135)scale(4.7194 4.52281)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="odq_-wbka"/><stop offset="1" class="y9vn05b-v"/></radialGradient><radialGradient id="iCz5yNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.84823 -2.07813 2.05068 1.82382 25.98 19.497)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="mt_8occxo"/><stop offset=".883" class="ozb2o_bkz"/></radialGradient><radialGradient id="iSN6oZd" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -3.8125 2.99389 .63804 26.172 20.794)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="m7zyjydub"/><stop offset="1" class="oyazfkryc"/></radialGradient><radialGradient id="itBbXKS" cx="0" cy="0" r="1" gradientTransform="matrix(1.48437 .23437 -.3465 2.19446 26.313 20.06)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="krpelr-dy"/><stop offset="1" class="h0sp3fbhr"/><stop offset="1" class="dj5h63b0t"/></radialGradient><radialGradient id="ijy2cZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 10.00001 -3.04902 .41924 5.5 19.716)" gradientUnits="userSpaceOnUse"><stop class="ys531713j"/><stop offset="1" class="ze0tbybyr"/></radialGradient><radialGradient id="irHopGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 -13.00004 20.39882 -1.96142 10.813 30.075)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="ks11w6lcu"/><stop offset="1" class="kfl3l4fgs"/></radialGradient><radialGradient id="iaDhLWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 -2.625 3.5 1.875 11.063 18.497)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="y6boe1tam"/><stop offset="1" class="vq9_y_brm"/></radialGradient><radialGradient id="ijXTZve" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -2.71875 3.18328 .58543 21.375 18.747)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="wv8qmacqf"/><stop offset="1" class="emk327bbe"/></radialGradient><radialGradient id="iWQIWhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.625 -5.90625 0 23.469 20.184)" gradientUnits="userSpaceOnUse"><stop class="d1lzds90y"/><stop offset="1" class="uzuzhyonh"/></radialGradient><radialGradient id="iD3yGyN" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 20.328 19.06)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="zcm4rt3mf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qd5yj9hln"/></radialGradient><radialGradient id="ixdTmbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 11.358 19.06)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="zcm4rt3mf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qd5yj9hln"/></radialGradient><radialGradient id="iVPhvic" cx="0" cy="0" r="1" gradientTransform="matrix(7.82168 -1.52596 1.273 6.52503 12.031 6.528)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="qzo7cgy3w"/><stop offset="1" class="i-ygrlbjq"/></radialGradient><radialGradient id="i1EpOwe" cx="0" cy="0" r="1" gradientTransform="matrix(6.12511 -2.6875 2.5949 5.91408 12.031 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="g4qjalbqo"/><stop offset=".912" class="tkvzged3s"/></radialGradient><radialGradient id="iaNXKac" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63771 -5.65242 5.82757 -3.75043 16.76 8.346)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="aj460xbwf"/><stop offset="1" class="rfngthbki"/></radialGradient><radialGradient id="ixQaPMd" cx="0" cy="0" r="1" gradientTransform="rotate(57.863 2.995 16.428)scale(5.75713 5.52963)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="d17xcmnsa"/><stop offset=".966" class="f5-lme9vp"/></radialGradient><radialGradient id="ibdU67c" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 .04688 -.02424 .98567 15.36 21.81)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="sne2xccwl"/><stop offset="1" class="b3obg0rjr"/></radialGradient><radialGradient id="iUbWUFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.79467 0 16.133 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="vvvztm6zj"/><stop offset="1" class="fyf7sp4uy"/></radialGradient><radialGradient id="iOGxgFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5717 -.73672 1.01428 -.7871 19.765 19.267)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iokWMuc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.974 4.557)scale(1.21806 1.46416)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ixQCi5R" width="4.539" height="4.539" x="4.363" y="17.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".125"/></filter><filter id="iNkC9Bb" width="4.663" height="4.663" x="23.301" y="17.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".125"/></filter><filter id="iFTZXpb" width="23.65" height="26" x="4.753" y="4.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.47451 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24660"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24660" result="effect2_innerShadow_3987_24660"/></filter><filter id="iJvXZNb" width="7.502" height="2.901" x="12.382" y="23.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".05"/></filter><filter id="iRFEWsd" width="7" height="2.4" x="12.633" y="23.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24660"/></filter><filter id="iioDTld" width="3.72" height="1.592" x="9.113" y="14.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.121569 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24660"/></filter><filter id="i4qkOSb" width="3.17" height=".992" x="9.317" y="14.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".1"/></filter><filter id="iA7cw1c" width="3.72" height="1.592" x="18.963" y="14.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.141176 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24660"/></filter><filter id="i7yV3pe" width="3.17" height=".992" x="19.363" y="14.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".1"/></filter><filter id="igIdshe" width="7.877" height="8.718" x="12.162" y="2.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".25"/></filter><filter id="iZf7GFN" width="8.1" height="8.529" x="11.931" y="1.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.129412 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24660"/></filter><filter id="iofCIXc" width="3.638" height="2.603" x="14.181" y="21.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".25"/></filter><filter id="i3YQ3Vb" width="3.138" height="2.103" x="14.564" y="20.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".125"/></filter><filter id="i7pub3c" width="1.647" height="1.423" x="18.665" y="18.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".05"/></filter><filter id="iZSYeWd" width="1.611" height="1.666" x="20.881" y="18.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".1"/></filter><filter id="i21qjob" width="1.845" height="1.978" x="11.717" y="18.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".1"/></filter><filter id="i0nmNad" width="1.958" height="1.444" x="9.71" y="18.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation=".05"/></filter><filter id="iXOPdse" width="13.584" height="12.368" x="14.564" y="4.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24660" stdDeviation="1.25"/></filter><linearGradient id="iWogLqd" x1="3.906" x2="6.25" y1="17.153" y2="23.153" gradientUnits="userSpaceOnUse"><stop class="ayvhgf5zf"/><stop offset="1" class="yesg_ogxc"/></linearGradient><linearGradient id="iGTZOpd" x1="28.516" x2="25.933" y1="18.216" y2="22.403" gradientUnits="userSpaceOnUse"><stop class="ftn-nj88l"/><stop offset="1" class="tjrs2-6ue"/></linearGradient><linearGradient id="i3hRwIb" x1="16.153" x2="16.153" y1="30.653" y2="25.528" gradientUnits="userSpaceOnUse"><stop offset=".195" class="lpw6rzl4p"/><stop offset="1" class="dv66n_pwa"/></linearGradient><linearGradient id="iGqY9Bc" x1="6.938" x2="18.188" y1="18.153" y2="21.028" gradientUnits="userSpaceOnUse"><stop class="ipusrib9d"/><stop offset="1" class="csf9q1tkj"/></linearGradient><linearGradient id="iW19Zwd" x1="16.153" x2="16.153" y1="30.653" y2="27.153" gradientUnits="userSpaceOnUse"><stop offset=".195" class="wr40bdb9p"/><stop offset="1" class="dv66n_pwa"/></linearGradient><linearGradient id="iGxUnZb" x1="13.797" x2="14.297" y1="25.138" y2="24.231" gradientUnits="userSpaceOnUse"><stop class="w2gkbnbqe"/><stop offset="1" class="d0-zinb4r"/></linearGradient><linearGradient id="ij8QPkd" x1="12.531" x2="9.359" y1="14.731" y2="15.14" gradientUnits="userSpaceOnUse"><stop class="vd4_eobzz"/><stop offset="1" class="aan57zrte"/></linearGradient><linearGradient id="i1jBF8b" x1="22.577" x2="19.405" y1="14.679" y2="15.088" gradientUnits="userSpaceOnUse"><stop class="vd4_eobzz"/><stop offset="1" class="aan57zrte"/></linearGradient><linearGradient id="iVepHUc" x1="16.456" x2="15.417" y1="3.148" y2="10.642" gradientUnits="userSpaceOnUse"><stop offset=".709" class="z4tn41bcd"/><stop offset="1" class="jq3hskb9d"/></linearGradient><linearGradient id="iDGf3sh" x1="22.245" x2="21.472" y1="19.192" y2="19.669" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDtNiQb" x1="13.191" x2="12.418" y1="19.192" y2="19.669" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNsZihj" x1="17.804" x2="27.5" y1="14.622" y2="8.778" gradientUnits="userSpaceOnUse"><stop class="vsbipxzeq"/><stop offset="1" class="vl9mo9edt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-medium" /></template>
<style>
.aan57zrte {
  stop-color: var(--svg-color--543d3e, #543D3E);
  stop-opacity: 0;
}

.aeq3b5eaz {
  d: path("M6.633 21.923a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.aj460xbwf {
  stop-color: var(--svg-color--3e3431, #3E3431);
  stop-opacity: 0;
}

.ayvhgf5zf {
  stop-color: var(--svg-color--7c554f, #7C554F);
}

.b3obg0rjr {
  stop-color: var(--svg-color--ca9f87, #CA9F87);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.csf9q1tkj {
  stop-color: var(--svg-color--916f5c, #916F5C);
  stop-opacity: 0;
}

.d0-zinb4r {
  stop-color: var(--svg-color--ab807d, #AB807D);
  stop-opacity: 0;
}

.d17xcmnsa {
  stop-color: var(--svg-color--3b212b, #3B212B);
  stop-opacity: 0;
}

.d1lzds90y {
  stop-color: var(--svg-color--c5977d, #C5977D);
}

.dfyl80b-o {
  d: path("M25.633 21.985a2.081 2.081 0 1 0 0-4.163a2.081 2.081 0 0 0 0 4.163");
}

.dj5h63b0t {
  stop-color: var(--svg-color--9d6959, #9D6959);
}

.dv66n_pwa {
  stop-color: var(--svg-color--9a5886, #9A5886);
  stop-opacity: 0;
}

.emk327bbe {
  stop-color: var(--svg-color--ad7974, #AD7974);
  stop-opacity: 0;
}

.f5-lme9vp {
  stop-color: var(--svg-color--3b212b, #3B212B);
}

.ff94iibzr {
  d: path("M20.333 17.884a2.2 2.2 0 0 1 2.12 2.78h-4.25c-.05-.19-.08-.38-.08-.58c0-1.21.99-2.2 2.21-2.2");
}

.fmpz47b8m {
  d: path("M16.252 3.12c-1.473-.222-2.757-.002-3.59 1.11c1.994 0 4.72 1.225 4.325 3.843a2.97 2.97 0 0 1-.994 1.816a.492.492 0 0 0 .403.863A3.87 3.87 0 0 0 19.5 7.476c.298-2.086-1.164-4.04-3.248-4.357");
}

.ft5dv1b6b {
  fill: none;
}

.ftn-nj88l {
  stop-color: var(--svg-color--cca389, #CCA389);
}

.fyf7sp4uy {
  stop-color: var(--svg-color--96596f, #96596F);
}

.g4qjalbqo {
  stop-color: var(--svg-color--483431, #483431);
}

.h0sp3fbhr {
  stop-color: var(--svg-color--7b4941, #7B4941);
}

.i-ygrlbjq {
  stop-color: var(--svg-color--584444, #584444);
}

.ipusrib9d {
  stop-color: var(--svg-color--916f5c, #916F5C);
}

.jpz13g5lx {
  d: path("M16.135 22.803c.51 0 .964-.28 1.225-.702c.238-.386-.011-.9-.445-.9h-1.56c-.434 0-.694.526-.444.9c.26.433.715.702 1.224.702");
}

.jq3hskb9d {
  stop-color: var(--svg-color--81554e, #81554E);
}

.jzvo7dbde {
  d: path("M11.353 17.884a2.2 2.2 0 0 0-2.12 2.78h4.25c.05-.19.08-.38.08-.58c-.01-1.21-.99-2.2-2.21-2.2");
}

.kfl3l4fgs {
  stop-color: var(--svg-color--935c6f, #935C6F);
  stop-opacity: 0;
}

.krpelr-dy {
  stop-color: var(--svg-color--b08471, #B08471);
}

.ks11w6lcu {
  stop-color: var(--svg-color--935c6f, #935C6F);
}

.l4zna2bvp {
  d: path("M22.292 19.794a2.07 2.07 0 0 0-.57-1.14l-.64.702l.288.563z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpw6rzl4p {
  stop-color: var(--svg-color--9a5886, #9A5886);
}

.m_5n1fdcs {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.153 23.318c-.367-.198-.757.223-.526.578l.063-.04a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.282-.13-.623-.428-.472a6.55 6.55 0 0 1-3.027.732a6.4 6.4 0 0 1-3.007-.732z");
}

.m7zyjydub {
  stop-color: var(--svg-color--bc987a, #BC987A);
  stop-opacity: 0;
}

.m9kkbzbxx {
  d: path("m18.483 9.26l4.36-2.325c2.774 2 2.899 5.614 2.774 6.593l-5.513.75a2.679 2.679 0 0 1-1.621-5.018");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg_atlbaz {
  d: path("M23.362 5.865a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.691l.898 8.11c.296 3.141 2.377 5.782 5.265 6.682c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.681l.898-8.11c.326-3.391-1.102-6.701-3.745-8.692");
}

.mt_8occxo {
  stop-color: var(--svg-color--9b6859, #9B6859);
}

.nihqa2baf {
  stop-color: var(--svg-color--9d7668, #9D7668);
}

.ninfq3frf {
  stop-color: var(--svg-color--744745, #744745);
}

.o0a2zx15p {
  d: path("M15.831 2.154a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odq_-wbka {
  stop-color: var(--svg-color--935977, #935977);
  stop-opacity: 0;
}

.oehfy885c {
  fill: var(--svg-color--905966, #905966);
  d: path("M16.002 23.153c.51 0 .965-.28 1.225-.702c.238-.386-.011-.9-.445-.9h-1.56c-.433 0-.693.526-.444.9c.26.433.715.702 1.224.702");
}

.ol7lm4ezu {
  d: path("M20.171 18.349c.157.21-.17.465-.543.743c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.124");
}

.oyazfkryc {
  stop-color: var(--svg-color--bc987a, #BC987A);
}

.ozb2o_bkz {
  stop-color: var(--svg-color--9b6859, #9B6859);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnrar_k6f {
  fill: var(--svg-color--402b29, #402B29);
  d: path("M15.831 2.154a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.ppzwdooyh {
  fill: var(--svg-color--000, #000);
  d: path("M19.073 20.084c0-.7.56-1.26 1.26-1.26s1.26.56 1.26 1.26c0 .21-.05.41-.14.58h-2.23c-.1-.17-.15-.37-.15-.58m-6.46 0c0-.7-.56-1.26-1.26-1.26s-1.26.56-1.26 1.26c0 .21.05.41.14.58h2.23c.09-.17.15-.37.15-.58");
}

.pwql01bzt {
  stroke: var(--svg-color--472d2c, #472D2C);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.613 15.234c.59-.21 1.41-.36 2.47-.26");
}

.qd5yj9hln {
  stop-color: var(--svg-color--6f4b49, #6F4B49);
}

.qzo7cgy3w {
  stop-color: var(--svg-color--584444, #584444);
  stop-opacity: 0;
}

.rfngthbki {
  stop-color: var(--svg-color--3e3431, #3E3431);
}

.s6paz2s8i {
  stroke: var(--svg-color--4c3230, #4C3230);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.183 15.234c-.59-.21-1.41-.36-2.47-.26");
}

.s9j2c3bac {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22.183 15.088c-.59-.21-1.41-.36-2.47-.26");
}

.sg8_yd1ki {
  d: path("M25.633 23.153a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.sne2xccwl {
  stop-color: var(--svg-color--b58b73, #B58B73);
}

.t42aur0hp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.171 18.349c.157.21-.17.465-.543.743c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.124");
}

.tjrs2-6ue {
  stop-color: var(--svg-color--ae7e73, #AE7E73);
}

.tkvzged3s {
  stop-color: var(--svg-color--483431, #483431);
  stop-opacity: 0;
}

.tsloc8bkm {
  cx: 10.689px;
  cy: 18.824px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.96px;
  ry: 0.486px;
}

.ty6h_vbkp {
  cx: 10.689px;
  cy: 18.824px;
  rx: 0.96px;
  ry: 0.486px;
}

.tya6kmb_o {
  d: path("M13.363 19.825c0-.71-.578-1.185-.735-1.328l-.71.688l.437.89z");
}

.uzuzhyonh {
  stop-color: var(--svg-color--c5977d, #C5977D);
  stop-opacity: 0;
}

.v6wnqjbhz {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.668 15.14c.59-.21 1.41-.36 2.47-.26");
}

.vd4_eobzz {
  stop-color: var(--svg-color--543d3e, #543D3E);
}

.vl9mo9edt {
  stop-color: var(--svg-color--c99f8b, #C99F8B);
  stop-opacity: 0;
}

.voi7bsp-n {
  fill: var(--svg-color--c49380, #C49380);
  d: path("M23.362 5.865a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.691l.898 8.11c.296 3.141 2.377 5.782 5.265 6.682c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.681l.898-8.11c.326-3.391-1.102-6.701-3.745-8.692");
}

.vq9_y_brm {
  stop-color: var(--svg-color--8e5a67, #8E5A67);
  stop-opacity: 0;
}

.vsbipxzeq {
  stop-color: var(--svg-color--c99f8b, #C99F8B);
}

.vvvztm6zj {
  stop-color: var(--svg-color--96596f, #96596F);
  stop-opacity: 0;
}

.vxo60ibid {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.125 24.117a6.4 6.4 0 0 1-3.007-.733c-.299-.16-.617.18-.428.471a4.09 4.09 0 0 0 3.445 1.888a4.1 4.1 0 0 0 3.445-1.887c.179-.282-.13-.623-.428-.472a6.55 6.55 0 0 1-3.027.732");
}

.vzt7qccog {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.843 17.214c1.61 0 2.97 1.11 3.34 2.61c.11.43-.22.84-.66.84h-5.5c-.35 0-.63-.32-.56-.67c.31-1.58 1.7-2.78 3.38-2.78m-10 0c-1.61 0-2.97 1.11-3.34 2.61c-.11.43.22.84.66.84h5.5c.35 0 .63-.32.56-.67a3.454 3.454 0 0 0-3.38-2.78");
}

.w2gkbnbqe {
  stop-color: var(--svg-color--ab807d, #AB807D);
}

.wfxx9nv4c {
  stop-color: var(--svg-color--744c4d, #744C4D);
}

.wg-tntuud {
  stop-color: var(--svg-color--9d7668, #9D7668);
  stop-opacity: 0;
}

.wr40bdb9p {
  stop-color: var(--svg-color--985683, #985683);
}

.wv8qmacqf {
  stop-color: var(--svg-color--ad7974, #AD7974);
}

.y6_96bc0u {
  d: path("M6.633 23.153a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.y6boe1tam {
  stop-color: var(--svg-color--8e5a67, #8E5A67);
}

.y9vn05b-v {
  stop-color: var(--svg-color--935977, #935977);
}

.yesg_ogxc {
  stop-color: var(--svg-color--864d67, #864D67);
}

.ys531713j {
  stop-color: var(--svg-color--9c7469, #9C7469);
}

.z4tn41bcd {
  stop-color: var(--svg-color--614635, #614635);
}

.zcm4rt3mf {
  stop-color: var(--svg-color--835a50, #835A50);
}

.ze0tbybyr {
  stop-color: var(--svg-color--9c7469, #9C7469);
  stop-opacity: 0;
}

</style>
