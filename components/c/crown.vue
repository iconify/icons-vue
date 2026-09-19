<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ieOa1vc)" class="jbr-uubej"/><circle fill="url(#i2RDuae)" class="nvm-o_ysl"/><circle fill="url(#i8hgKZd)" class="nvm-o_ysl"/><path fill="url(#iWHdgUb)" class="a3t6lobbz"/><path fill="url(#inRDnab)" class="a3t6lobbz"/><path fill="url(#i6JH2Md)" class="sbimbtb-b"/><path fill="url(#ivA7Zfd)" class="sbimbtb-b"/><path fill="url(#i8sbZ1c)" class="sbimbtb-b"/><g filter="url(#iibl7Rd)"><path fill="url(#iMlGjyc)" class="t3gn0bb2o"/><path fill="url(#iitjIRb)" class="t3gn0bb2o"/></g><path fill="url(#iWCmyOy)" class="t3gn0bb2o"/><path fill="url(#iYdAkpd)" class="t3gn0bb2o"/><path fill="url(#iHbE8hd)" class="t3gn0bb2o"/><path fill="url(#ioKsF3d)" class="t3gn0bb2o"/><path fill="url(#ivzpSZt)" class="t3gn0bb2o"/><path fill="url(#i8sgxcc)" class="t3gn0bb2o"/><g filter="url(#ikiDyle)"><path fill="url(#iYWVkse)" class="elf10wb7r"/><path fill="url(#iLY13Kc)" class="elf10wb7r"/></g><g filter="url(#iZ0gSOd)"><path fill="url(#ikFsTZb)" class="r9h-csj8s"/><path fill="url(#i2Aj9Md)" class="r9h-csj8s"/></g><path fill="url(#ivmcQMd)" class="ve3mgtwcd"/><path fill="url(#iGTCYhd)" class="ve3mgtwcd"/><path fill="url(#iAT3Qwc)" class="ve3mgtwcd"/><path fill="url(#iRYknUb)" class="ve3mgtwcd"/><path fill="url(#i3QHX6Y)" class="d0--_wkev"/><path fill="url(#ixVjIuD)" class="d0--_wkev"/><path fill="url(#ijSrj0f)" class="d0--_wkev"/><path fill="url(#i7UqZNe)" class="d0--_wkev"/><g filter="url(#iZe0XId)"><path fill="url(#iq8e1sd)" class="ot3o82bed"/><path fill="url(#iVioK5G)" class="ot3o82bed"/></g><g filter="url(#iWEGpNh)"><circle fill="url(#iBqCG3c)" class="x0yaqlbzt"/></g><g filter="url(#iQdE1Kd)" class="h_1ye1b_p"><path stroke="url(#ilOoQTd)" class="uprthnupi"/><path stroke="url(#iRsgaEb)" class="uprthnupi"/></g><circle fill="url(#iRboedC)" class="gbxbrxb5v"/><circle fill="url(#i9uUWre)" class="gbxbrxb5v"/><circle fill="url(#iolVG1c)" class="gbxbrxb5v"/><circle fill="url(#i9ibAoc)" class="gbxbrxb5v"/><path fill="url(#ig0REJd)" class="jde4mv73k"/><path fill="url(#i9jIBCc)" class="jde4mv73k"/><path fill="url(#ivyhxtc)" class="jde4mv73k"/><path fill="url(#i9TOA5d)" class="jde4mv73k"/><defs><radialGradient id="ieOa1vc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.54 11.846 9.505)scale(1.75182 2.1567)" gradientUnits="userSpaceOnUse"><stop class="wjchek1or"/><stop offset="1" class="o_jbilb1x"/></radialGradient><radialGradient id="i2RDuae" cx="0" cy="0" r="1" gradientTransform="rotate(108.743 6.278 20.379)scale(2.99062)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="rcwhp_6lf"/><stop offset="1" class="sngwovi4n"/></radialGradient><radialGradient id="i8hgKZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32813 .45312 -.28728 -.84206 28.092 21.654)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="o1fmq71ux"/><stop offset="1" class="ie_wo1b6i"/></radialGradient><radialGradient id="iWHdgUb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 .875 -2.18396 7.64387 8.656 13.56)" gradientUnits="userSpaceOnUse"><stop class="c9runn0-p"/><stop offset="1" class="dhd9pjbry"/></radialGradient><radialGradient id="inRDnab" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21876 -.95312 2.86654 -6.67303 10.531 14.247)" gradientUnits="userSpaceOnUse"><stop offset=".765" class="vjslz02ih"/><stop offset=".911" class="gilvygbxh"/></radialGradient><radialGradient id="i6JH2Md" cx="0" cy="0" r="1" gradientTransform="rotate(-125.455 15.932 1.594)scale(2.53202 2.59683)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="eo-azjdsa"/><stop offset="1" class="s0ozj_b9c"/></radialGradient><radialGradient id="ivA7Zfd" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.85936 2.23878 5.25103 21.922 14.262)" gradientUnits="userSpaceOnUse"><stop offset=".734" class="lr5ndbbxh"/><stop offset=".929" class="pbn865-um"/></radialGradient><radialGradient id="i8sbZ1c" cx="0" cy="0" r="1" gradientTransform="rotate(-142.922 14.106 3.55)scale(3.4469 5.81507)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="qgxrhsblf"/><stop offset=".948" class="nl3zrzblp"/></radialGradient><radialGradient id="iitjIRb" cx="0" cy="0" r="1" gradientTransform="matrix(3.86736 -10.30052 20.04813 7.52713 12.133 31.859)" gradientUnits="userSpaceOnUse"><stop class="lcz853b7u"/><stop offset="1" class="y6l-nie2b"/></radialGradient><radialGradient id="ioKsF3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.99999 2.3125 -1.91688 -.82891 28.063 12.403)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="onrj3hb8w"/><stop offset="1" class="g285loupo"/></radialGradient><radialGradient id="ivzpSZt" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 1.84375 -1.00848 .48715 4.047 12.544)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="td8nqqbzo"/><stop offset="1" class="p0gv6bhbw"/></radialGradient><radialGradient id="i8sgxcc" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.1328 -2.4807 .6159 16 8.833)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="l9bn98bkk"/><stop offset="1" class="kqroa3bpg"/></radialGradient><radialGradient id="iYWVkse" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -1.8125 1.16953 .92756 22.031 23.06)" gradientUnits="userSpaceOnUse"><stop class="k0eqlrbwt"/><stop offset="1" class="yw55l3jck"/></radialGradient><radialGradient id="iLY13Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50001 .875 -.55423 -.95013 23.625 21.84)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="mby2vgfke"/><stop offset="1" class="fhp4khbcw"/></radialGradient><radialGradient id="ikFsTZb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.281 13.893 7.747)scale(1.77356 1.69812)" gradientUnits="userSpaceOnUse"><stop class="qfcludbgv"/><stop offset="1" class="jxmh18ong"/></radialGradient><radialGradient id="i2Aj9Md" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 .35937 -.31478 -.698 10.547 22.044)" gradientUnits="userSpaceOnUse"><stop class="f6aevqbhs"/><stop offset="1" class="x3umq11nx"/></radialGradient><radialGradient id="ivmcQMd" cx="0" cy="0" r="1" gradientTransform="rotate(135.198 .066 6.447)scale(2.97287 3.09287)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="krw174xgy"/><stop offset="1" class="gp8_3ccbr"/></radialGradient><radialGradient id="iGTCYhd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.331 11.013 4.506)scale(1.65959 1.79772)" gradientUnits="userSpaceOnUse"><stop offset=".065" class="k-w36wbhr"/><stop offset="1" class="xq72p_bnx"/></radialGradient><radialGradient id="iAT3Qwc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 .88517 -.45743 -.56522 4.767 11.039)" gradientUnits="userSpaceOnUse"><stop class="knbpk3f1n"/><stop offset="1" class="g__87vbka"/></radialGradient><radialGradient id="iRYknUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 0 0 -1.94872 4.016 12.014)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="vy5x54b1e"/><stop offset="1" class="sfs5ihb4d"/></radialGradient><radialGradient id="i3QHX6Y" cx="0" cy="0" r="1" gradientTransform="rotate(136.302 3.344 7.152)scale(2.91757 3.03227)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="krw174xgy"/><stop offset="1" class="gp8_3ccbr"/></radialGradient><radialGradient id="ixVjIuD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09376 .85168 -.4363 -.5603 10.812 10.075)" gradientUnits="userSpaceOnUse"><stop class="knbpk3f1n"/><stop offset="1" class="g__87vbka"/></radialGradient><radialGradient id="ijSrj0f" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 -1.26563 1.68798 .39595 9.578 12.434)" gradientUnits="userSpaceOnUse"><stop class="tbyz8qbbb"/><stop offset="1" class="n0wio5b4i"/></radialGradient><radialGradient id="i7UqZNe" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.031 5.506)scale(1.875)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="vy5x54b1e"/><stop offset="1" class="sfs5ihb4d"/></radialGradient><radialGradient id="iq8e1sd" cx="0" cy="0" r="1" gradientTransform="rotate(136.32 9.637 9.936)scale(2.39817 2.49246)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="fbxjv7-xe"/><stop offset="1" class="vy5c4kbkn"/></radialGradient><radialGradient id="iVioK5G" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 .72668 -.37226 -.5763 23.672 10.2)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="knbpk3f1n"/><stop offset="1" class="g__87vbka"/></radialGradient><radialGradient id="iBqCG3c" cx="0" cy="0" r="1" gradientTransform="rotate(138.155 4.441 14.053)scale(2.81059)" gradientUnits="userSpaceOnUse"><stop class="vom2jxbnm"/><stop offset="1" class="rfsfztbwa"/></radialGradient><radialGradient id="iRsgaEb" cx="0" cy="0" r="1" gradientTransform="matrix(5.34375 -3.69576 .98987 1.43127 22.555 16.372)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="pquhzacex"/><stop offset="1" class="nmf6ggb6q"/></radialGradient><radialGradient id="iRboedC" cx="0" cy="0" r="1" gradientTransform="rotate(125.606 7.01 7.807)scale(3.43521 2.91657)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="k7hsoabmu"/><stop offset="1" class="ekubg4lpf"/></radialGradient><radialGradient id="i9uUWre" cx="0" cy="0" r="1" gradientTransform="matrix(.33984 -1.80078 2.14062 .40398 15.656 9.446)" gradientUnits="userSpaceOnUse"><stop class="rqf_cwaqn"/><stop offset="1" class="asf5oobrf"/></radialGradient><radialGradient id="iolVG1c" cx="0" cy="0" r="1" gradientTransform="matrix(-3 -1.96876 2.35473 -3.58814 16.75 8.247)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="r-aoht6kv"/><stop offset="1" class="tx29gjbvi"/></radialGradient><radialGradient id="i9ibAoc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8125 .8047 -.61925 -1.3948 18.063 6.84)" gradientUnits="userSpaceOnUse"><stop class="k8bnz56tw"/><stop offset="1" class="qa7h_3bpy"/></radialGradient><radialGradient id="ig0REJd" cx="0" cy="0" r="1" gradientTransform="rotate(135.198 12.566 11.6)scale(2.97287 3.09287)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="j64lh4wbe"/><stop offset="1" class="qrnf5nryk"/></radialGradient><radialGradient id="i9jIBCc" cx="0" cy="0" r="1" gradientTransform="matrix(.53124 -1.57227 2.12523 .71807 28.22 13.497)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="ixnnpmbjr"/><stop offset="1" class="b1lswfb9f"/></radialGradient><radialGradient id="ivyhxtc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 .88517 -.45743 -.56522 29.768 11.04)" gradientUnits="userSpaceOnUse"><stop class="knbpk3f1n"/><stop offset="1" class="g__87vbka"/></radialGradient><radialGradient id="i9TOA5d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 0 0 -1.94872 29.016 12.014)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="nn8qj63hg"/><stop offset="1" class="ocbrq8zsi"/></radialGradient><filter id="iibl7Rd" width="26.55" height="19.858" x="2.725" y="8.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.580392 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17387"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.686275 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17387" result="effect2_innerShadow_18_17387"/></filter><filter id="ikiDyle" width="4.23" height="4.496" x="20.132" y="20.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.54902 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_17387"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_17387" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.219608 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_17387"/></filter><filter id="iZ0gSOd" width="4.23" height="4.496" x="7.215" y="20.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.439216 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_17387"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_17387" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_17387"/></filter><filter id="iZe0XId" width="2.781" height="2.676" x="21.031" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.619608 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17387"/></filter><filter id="iWEGpNh" width="7.436" height="7.436" x="11.82" y="19.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.443137 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_17387"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_17387" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.384314 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_17387"/></filter><filter id="iQdE1Kd" width="11.476" height="7.098" x="16.052" y="9.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17387" stdDeviation=".075"/></filter><linearGradient id="iMlGjyc" x1="23.206" x2="5.54" y1="20.58" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="jfmsa2bxw"/><stop offset=".304" class="ods6tnygk"/><stop offset="1" class="qv5kxxb3k"/></linearGradient><linearGradient id="iWCmyOy" x1="5.281" x2="8" y1="24.278" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="r-tnopb2n"/><stop offset="1" class="h5kyjbcpd"/></linearGradient><linearGradient id="iYdAkpd" x1="26.625" x2="22" y1="26.028" y2="24.966" gradientUnits="userSpaceOnUse"><stop offset=".129" class="mv_7fcb7o"/><stop offset="1" class="p-niyvb0t"/></linearGradient><linearGradient id="iHbE8hd" x1="17.438" x2="17.438" y1="28.872" y2="27.684" gradientUnits="userSpaceOnUse"><stop offset=".184" class="vubn71l_o"/><stop offset="1" class="d8y3jvhnx"/></linearGradient><linearGradient id="ilOoQTd" x1="16.211" x2="22.555" y1="9.153" y2="17.153" gradientUnits="userSpaceOnUse"><stop class="cq4n3ib5h"/><stop offset="1" class="xbtaaib8x"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crown" /></template>
<style>
.a3t6lobbz {
  d: path("M9.008 12.083c-.6.9-1.037 2.125-1.188 2.594l2.344 1.687l1.79-2.266a30 30 0 0 0-1-1.425a13 13 0 0 0-.9-1.016z");
}

.asf5oobrf {
  stop-color: var(--svg-color--e78f5e, #E78F5E);
  stop-opacity: 0;
}

.b1lswfb9f {
  stop-color: var(--svg-color--f1907c, #F1907C);
  stop-opacity: 0;
}

.c9runn0-p {
  stop-color: var(--svg-color--fbc96e, #FBC96E);
}

.cq4n3ib5h {
  stop-color: var(--svg-color--ffd678, #FFD678);
}

.d0--_wkev {
  d: path("M10.28 12.18a1.39 1.39 0 1 0-1.355.028a.67.67 0 0 1 .419-.02c.214.062.566.14.937-.008");
}

.d8y3jvhnx {
  stop-color: var(--svg-color--ff7a6a, #FF7A6A);
  stop-opacity: 0;
}

.dhd9pjbry {
  stop-color: var(--svg-color--fac567, #FAC567);
}

.ekubg4lpf {
  stop-color: var(--svg-color--cc9848, #CC9848);
}

.elf10wb7r {
  d: path("M23.78 22.743c-.266.814-1.118 1.222-1.932.957c-.614-.25-.879-.951-.614-1.765c.265-.815 1.1-1.282 1.606-1.118c.814.265 1.204 1.111.94 1.926");
}

.eo-azjdsa {
  stop-color: var(--svg-color--bf812a, #BF812A);
}

.f6aevqbhs {
  stop-color: var(--svg-color--fe536f, #FE536F);
}

.fbxjv7-xe {
  stop-color: var(--svg-color--f0c950, #F0C950);
}

.fhp4khbcw {
  stop-color: var(--svg-color--ff5873, #FF5873);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g__87vbka {
  stop-color: var(--svg-color--ffde71, #FFDE71);
  stop-opacity: 0;
}

.g285loupo {
  stop-color: var(--svg-color--f8bf60, #F8BF60);
  stop-opacity: 0;
}

.gbxbrxb5v {
  cx: 15.996px;
  cy: 7.645px;
  r: 1.801px;
}

.gilvygbxh {
  stop-color: var(--svg-color--daa139, #DAA139);
}

.gp8_3ccbr {
  stop-color: var(--svg-color--d9972a, #D9972A);
}

.h_1ye1b_p {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.h5kyjbcpd {
  stop-color: var(--svg-color--e07648, #E07648);
  stop-opacity: 0;
}

.ie_wo1b6i {
  stop-color: var(--svg-color--5fbeff, #5FBEFF);
  stop-opacity: 0;
}

.ixnnpmbjr {
  stop-color: var(--svg-color--f1907c, #F1907C);
}

.j64lh4wbe {
  stop-color: var(--svg-color--f8cb54, #F8CB54);
}

.jbr-uubej {
  cx: 5.379px;
  cy: 22.251px;
  r: 1.551px;
}

.jde4mv73k {
  d: path("M29.922 11.925a1.39 1.39 0 1 1-2.781 0a1.39 1.39 0 0 1 2.78 0");
}

.jfmsa2bxw {
  stop-color: var(--svg-color--ffbc5d, #FFBC5D);
}

.jxmh18ong {
  stop-color: var(--svg-color--e42047, #E42047);
}

.k-w36wbhr {
  stop-color: var(--svg-color--df8089, #DF8089);
}

.k0eqlrbwt {
  stop-color: var(--svg-color--ff196c, #FF196C);
}

.k7hsoabmu {
  stop-color: var(--svg-color--f3d154, #F3D154);
}

.k8bnz56tw {
  stop-color: var(--svg-color--ffed77, #FFED77);
}

.knbpk3f1n {
  stop-color: var(--svg-color--ffde71, #FFDE71);
}

.kqroa3bpg {
  stop-color: var(--svg-color--feb16a, #FEB16A);
  stop-opacity: 0;
}

.krw174xgy {
  stop-color: var(--svg-color--e7c04e, #E7C04E);
}

.l9bn98bkk {
  stop-color: var(--svg-color--d48c33, #D48C33);
}

.lcz853b7u {
  stop-color: var(--svg-color--f67b4e, #F67B4E);
}

.lr5ndbbxh {
  stop-color: var(--svg-color--e9bb61, #E9BB61);
  stop-opacity: 0;
}

.mby2vgfke {
  stop-color: var(--svg-color--ff5873, #FF5873);
}

.mv_7fcb7o {
  stop-color: var(--svg-color--ffbb5b, #FFBB5B);
}

.n0wio5b4i {
  stop-color: var(--svg-color--e4a122, #E4A122);
  stop-opacity: 0;
}

.nl3zrzblp {
  stop-color: var(--svg-color--c18739, #C18739);
}

.nmf6ggb6q {
  stop-color: var(--svg-color--ffd175, #FFD175);
  stop-opacity: 0;
}

.nn8qj63hg {
  stop-color: var(--svg-color--e0a444, #E0A444);
  stop-opacity: 0;
}

.nvm-o_ysl {
  cx: 26.633px;
  cy: 22.263px;
  r: 1.551px;
}

.o_jbilb1x {
  stop-color: var(--svg-color--2c68a3, #2C68A3);
}

.o1fmq71ux {
  stop-color: var(--svg-color--5fbeff, #5FBEFF);
}

.ocbrq8zsi {
  stop-color: var(--svg-color--c6924d, #C6924D);
}

.ods6tnygk {
  stop-color: var(--svg-color--fcad6a, #FCAD6A);
}

.onrj3hb8w {
  stop-color: var(--svg-color--dd9049, #DD9049);
}

.ot3o82bed {
  d: path("M21.72 12.18a1.39 1.39 0 1 1 1.355.028a.67.67 0 0 0-.419-.02c-.214.062-.566.14-.937-.008");
}

.p-niyvb0t {
  stop-color: var(--svg-color--ffbb5b, #FFBB5B);
  stop-opacity: 0;
}

.p0gv6bhbw {
  stop-color: var(--svg-color--d7783d, #D7783D);
  stop-opacity: 0;
}

.pbn865-um {
  stop-color: var(--svg-color--e9bb61, #E9BB61);
}

.pquhzacex {
  stop-color: var(--svg-color--ffd175, #FFD175);
}

.qa7h_3bpy {
  stop-color: var(--svg-color--ffed77, #FFED77);
  stop-opacity: 0;
}

.qfcludbgv {
  stop-color: var(--svg-color--f6196c, #F6196C);
}

.qgxrhsblf {
  stop-color: var(--svg-color--c18739, #C18739);
  stop-opacity: 0;
}

.qrnf5nryk {
  stop-color: var(--svg-color--eaa34b, #EAA34B);
}

.qv5kxxb3k {
  stop-color: var(--svg-color--cb7547, #CB7547);
}

.r-aoht6kv {
  stop-color: var(--svg-color--e9c251, #E9C251);
  stop-opacity: 0;
}

.r-tnopb2n {
  stop-color: var(--svg-color--c2794c, #C2794C);
}

.r9h-csj8s {
  d: path("M8.297 22.743c.265.814 1.117 1.222 1.932.957c.613-.25.878-.951.613-1.765c-.265-.815-1.1-1.282-1.605-1.118c-.815.265-1.205 1.111-.94 1.926");
}

.rcwhp_6lf {
  stop-color: var(--svg-color--3db3f3, #3DB3F3);
}

.rfsfztbwa {
  stop-color: var(--svg-color--3e94ff, #3E94FF);
}

.rqf_cwaqn {
  stop-color: var(--svg-color--e78f5e, #E78F5E);
}

.s0ozj_b9c {
  stop-color: var(--svg-color--ce9333, #CE9333);
}

.sbimbtb-b {
  d: path("M22.992 12.083c.6.9 1.037 2.125 1.188 2.594l-2.344 1.687l-1.79-2.266c.212-.325.713-1.05 1-1.425s.722-.834.9-1.016z");
}

.sfs5ihb4d {
  stop-color: var(--svg-color--b9894b, #B9894B);
}

.sngwovi4n {
  stop-color: var(--svg-color--5b73f4, #5B73F4);
}

.t3gn0bb2o {
  d: path("m3.125 12.153l3.106 15.159A1.6 1.6 0 0 0 7.8 28.59h16.4a1.6 1.6 0 0 0 1.568-1.28l3.106-15.158l-.992-.484c-1.484 1.078-4.592 3.289-5.394 3.773c-.64.386-1.228-.243-1.35-.422c-1.117-1.64-2.822-4.028-3.46-4.867c-.652-.86-1.39-1.284-1.679-1.32c-.289.036-1.027.46-1.68 1.32c-.637.839-2.341 3.227-3.459 4.867c-.122.179-.71.809-1.35.422c-.802-.484-3.91-2.695-5.394-3.773z");
}

.tbyz8qbbb {
  stop-color: var(--svg-color--e4a122, #E4A122);
}

.td8nqqbzo {
  stop-color: var(--svg-color--d7783d, #D7783D);
}

.tx29gjbvi {
  stop-color: var(--svg-color--b49858, #B49858);
}

.uprthnupi {
  d: path("M16.21 9.355c.173-.02.613.069 1 .594c.388.525 2.746 3.885 3.876 5.5c.219.338.866.872 1.703.297s3.531-2.525 4.547-3.202");
}

.ve3mgtwcd {
  d: path("M4.922 11.925a1.39 1.39 0 1 1-2.781 0a1.39 1.39 0 0 1 2.78 0");
}

.vjslz02ih {
  stop-color: var(--svg-color--d89f3a, #D89F3A);
  stop-opacity: 0;
}

.vom2jxbnm {
  stop-color: var(--svg-color--5fbfff, #5FBFFF);
}

.vubn71l_o {
  stop-color: var(--svg-color--ff6f8c, #FF6F8C);
}

.vy5c4kbkn {
  stop-color: var(--svg-color--c8861f, #C8861F);
}

.vy5x54b1e {
  stop-color: var(--svg-color--e1ad3d, #E1AD3D);
  stop-opacity: 0;
}

.wjchek1or {
  stop-color: var(--svg-color--395de0, #395DE0);
}

.x0yaqlbzt {
  cx: 16.038px;
  cy: 22.326px;
  r: 2.468px;
}

.x3umq11nx {
  stop-color: var(--svg-color--fe536f, #FE536F);
  stop-opacity: 0;
}

.xbtaaib8x {
  stop-color: var(--svg-color--ffd678, #FFD678);
  stop-opacity: 0;
}

.xq72p_bnx {
  stop-color: var(--svg-color--df8089, #DF8089);
  stop-opacity: 0;
}

.y6l-nie2b {
  stop-color: var(--svg-color--f67b4e, #F67B4E);
  stop-opacity: 0;
}

.yw55l3jck {
  stop-color: var(--svg-color--ff1f4a, #FF1F4A);
}

</style>
