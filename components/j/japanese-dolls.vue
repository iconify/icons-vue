<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iwHXpCd)" class="t10t-nbrq"/><circle fill="url(#iqctqzG)" class="eu5rqvfaa"/><path fill="url(#iVMJynb)" class="ydd72cf-d"/><path fill="url(#iM7nehH)" class="ux-zzj3ci"/><path fill="url(#iMAEV3b)" class="ux-zzj3ci"/><path fill="url(#itLiWcj)" class="ux-zzj3ci"/><g filter="url(#ilmL6bb)"><path fill="url(#iwQnF6b)" class="g3o9brb_b"/><path fill="url(#iQEFMEd)" class="g3o9brb_b"/><path fill="url(#ivJy5he)" class="g3o9brb_b"/></g><g filter="url(#iL5dz3b)"><path fill="url(#ij1hd6c)" class="i53x9yb4t"/></g><path fill="url(#iL915xb)" class="wuveq6bek"/><path fill="url(#id8TUvc)" class="rp69ixb2y"/><path fill="url(#i5RJaZc)" class="rp69ixb2y"/><path fill="url(#iWDl0MD)" class="rp69ixb2y"/><path fill="url(#iPC9xud)" class="rp69ixb2y"/><path fill="url(#izlQunx)" class="rp69ixb2y"/><path fill="url(#iDPDfzd)" class="rp69ixb2y"/><g filter="url(#iMGrVxd)"><path fill="url(#iF2Sskh)" class="boe1nrb9c"/></g><path fill="url(#igwpZUd)" class="coca8obnt"/><path fill="url(#i6C6CeO)" class="coca8obnt"/><path fill="url(#iWjMPYc)" class="coca8obnt"/><path fill="url(#idmzzHe)" class="coca8obnt"/><g filter="url(#i6zjSeC)"><path class="d57rpqboi"/></g><path fill="url(#ilg0pTS)" class="dkdygs0uc"/><path fill="url(#iPJYemc)" class="dkdygs0uc"/><g filter="url(#ij9pBsb)"><path class="shi1es7ad"/></g><g filter="url(#iMkCbHr)"><path fill="url(#i8aCRze)" class="c31m0acqm"/><path fill="url(#it4HczJ)" class="c31m0acqm"/></g><g filter="url(#iBzkFle)"><path fill="url(#iH65Hbe)" class="erx-dmber"/></g><path fill="url(#igfyC5d)" class="erx-dmber"/><g filter="url(#iugxSCd)"><path fill="url(#itj72Mg)" class="p4ppiuczb"/></g><g filter="url(#iXxuTNe)"><path fill="url(#iSeEMPd)" class="bughnhbqc"/><path fill="url(#igIpwdc)" class="bughnhbqc"/><path fill="url(#iFoKFgd)" class="bughnhbqc"/></g><path fill="url(#iNVm2Db)" clip-rule="evenodd" class="z7g92dbrf"/><path fill="url(#iChlGre)" clip-rule="evenodd" class="z7g92dbrf"/><path fill="url(#ihInj4c)" clip-rule="evenodd" class="z7g92dbrf"/><path fill="url(#iWSkAub)" clip-rule="evenodd" class="z7g92dbrf"/><path fill="url(#i0uW5Cd)" clip-rule="evenodd" class="z7g92dbrf"/><g filter="url(#itUwSCe)"><path stroke="url(#iaC5vsd)" class="u2w07cpxx"/></g><g filter="url(#i0Dxxhd)"><path fill="url(#iKuaHwc)" class="gfyu3s4vb"/></g><g filter="url(#imbjjeU)"><path class="dh3smnbph"/></g><path fill="url(#ivd7KVc)" class="s_a4yubzj"/><path fill="url(#iAy6Ltc)" class="s_a4yubzj"/><g filter="url(#iUi64He)"><path class="kbcbd3b1e"/></g><path fill="url(#inRhwBa)" class="q8gasb5lc"/><path fill="url(#itOunSb)" class="q8gasb5lc"/><path fill="url(#ipVkXyT)" class="t255isx1g"/><path fill="url(#igjznBc)" class="t255isx1g"/><path fill="url(#ifkiwbb)" class="kyb2dtbed"/><path fill="url(#iTiRKGc)" class="kyb2dtbed"/><g filter="url(#izsy1QR)"><rect class="i5u1koihs"/></g><g filter="url(#iseUare)"><path stroke="url(#iU2MNce)" class="jzeyf1bta"/></g><g filter="url(#iCHz7Md)"><path fill="url(#i4mpocc)" class="g8h36hkcw"/><path fill="url(#isDkeqc)" class="g8h36hkcw"/></g><defs><radialGradient id="iwHXpCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96875 .4375 -.64583 2.90625 17.828 11.313)" gradientUnits="userSpaceOnUse"><stop class="th6hfnfit"/><stop offset="1" class="g2f905bpn"/></radialGradient><radialGradient id="iqctqzG" cx="0" cy="0" r="1" gradientTransform="rotate(-16.026 54.1 -82.77)scale(1.52814 1.35058)" gradientUnits="userSpaceOnUse"><stop class="je-_ucyet"/><stop offset="1" class="rs1z8acua"/></radialGradient><radialGradient id="iVMJynb" cx="0" cy="0" r="1" gradientTransform="rotate(4.086 -123.585 298.06)scale(2.41238)" gradientUnits="userSpaceOnUse"><stop class="zr4oiyuhj"/><stop offset="1" class="gind88bhl"/></radialGradient><radialGradient id="iM7nehH" cx="0" cy="0" r="1" gradientTransform="matrix(-.74218 1.01563 -.96685 -.70654 22.797 6.438)" gradientUnits="userSpaceOnUse"><stop class="nqvejbtdd"/><stop offset="1" class="tf6m4s0ca"/></radialGradient><radialGradient id="iwQnF6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.1885 1.25 -1.6707 -.25196 20.89 7.094)" gradientUnits="userSpaceOnUse"><stop class="ots3m5bsh"/><stop offset="1" class="l9pckb_7h"/></radialGradient><radialGradient id="iQEFMEd" cx="0" cy="0" r="1" gradientTransform="rotate(-151.586 11.761 1.487)scale(.26788 .6139)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="xkk8xxbls"/><stop offset="1" class="t2wlzhben"/></radialGradient><radialGradient id="ij1hd6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .65626 -.54879 -.65984 24.281 7.375)" gradientUnits="userSpaceOnUse"><stop class="w2n-vzi6a"/><stop offset="1" class="f63b1vbdb"/></radialGradient><radialGradient id="iL915xb" cx="0" cy="0" r="1" gradientTransform="rotate(127.933 9.446 9.762)scale(1.34711)" gradientUnits="userSpaceOnUse"><stop class="nt_n5e7ue"/><stop offset="1" class="xrmjy5bfl"/></radialGradient><radialGradient id="i5RJaZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.58177 4.03103 -7.49501 2.94104 18.53 13.77)" gradientUnits="userSpaceOnUse"><stop class="k3e18ejek"/><stop offset="1" class="y5la4-bas"/></radialGradient><radialGradient id="iPC9xud" cx="0" cy="0" r="1" gradientTransform="rotate(153.153 9.267 9.9)scale(2.8338 2.66448)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="f02jr_bjn"/><stop offset="1" class="tofnqza8z"/></radialGradient><radialGradient id="i6C6CeO" cx="0" cy="0" r="1" gradientTransform="matrix(3.67428 2.48001 -3.189 4.72468 18.556 18.125)" gradientUnits="userSpaceOnUse"><stop class="xch9my-bj"/><stop offset="1" class="prrt7gb1y"/></radialGradient><radialGradient id="iWjMPYc" cx="0" cy="0" r="1" gradientTransform="rotate(142.261 9.801 13.646)scale(2.96127 2.16049)" gradientUnits="userSpaceOnUse"><stop class="p01umtm_a"/><stop offset="1" class="ymxx_xers"/></radialGradient><radialGradient id="iPJYemc" cx="0" cy="0" r="1" gradientTransform="matrix(2.28124 -1.65626 1.35652 1.8684 10.656 18.125)" gradientUnits="userSpaceOnUse"><stop class="gt_o3ittk"/><stop offset="1" class="c8q7m0wbc"/></radialGradient><radialGradient id="i8aCRze" cx="0" cy="0" r="1" gradientTransform="rotate(97.989 -2.071 13.427)scale(5.39612 1.71944)" gradientUnits="userSpaceOnUse"><stop class="x7gkbqb8w"/><stop offset="1" class="aprou-k5e"/></radialGradient><radialGradient id="itj72Mg" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.46 -5.70418 0 23.173 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="y-i8y-xbq"/><stop offset="1" class="o_h807b_b"/></radialGradient><radialGradient id="iSeEMPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.625 1.71385 0 23.278 12.156)" gradientUnits="userSpaceOnUse"><stop class="pl6sdv8pe"/><stop offset="1" class="xyz1deaev"/></radialGradient><radialGradient id="iFoKFgd" cx="0" cy="0" r="1" gradientTransform="rotate(8.49 -59.908 133.993)scale(2.59089 6.08263)" gradientUnits="userSpaceOnUse"><stop class="le1x95bza"/><stop offset="1" class="f66pd3byc"/></radialGradient><radialGradient id="ihInj4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.20313 -.57071 0 9.203 8.297)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="jo3pn9bup"/><stop offset="1" class="qoewk7b2i"/></radialGradient><radialGradient id="i0uW5Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 0 0 -.85387 12.422 8.41)" gradientUnits="userSpaceOnUse"><stop class="opqj0fbov"/><stop offset="1" class="zjkmvtk0o"/></radialGradient><radialGradient id="iKuaHwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.8225 -3.62625 0 10.656 12.688)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="y-i8y-xbq"/><stop offset="1" class="o_h807b_b"/></radialGradient><radialGradient id="iAy6Ltc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88645 -.3572 0 8.752 13.292)" gradientUnits="userSpaceOnUse"><stop class="jsg34sbje"/><stop offset="1" class="un12mvbcy"/></radialGradient><radialGradient id="itOunSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88645 -.3572 0 11.002 13.292)" gradientUnits="userSpaceOnUse"><stop class="jsg34sbje"/><stop offset="1" class="un12mvbcy"/></radialGradient><radialGradient id="igjznBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88645 -.3572 0 21.282 13.292)" gradientUnits="userSpaceOnUse"><stop class="jsg34sbje"/><stop offset="1" class="un12mvbcy"/></radialGradient><radialGradient id="iTiRKGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88645 -.3572 0 23.532 13.292)" gradientUnits="userSpaceOnUse"><stop class="jsg34sbje"/><stop offset="1" class="un12mvbcy"/></radialGradient><radialGradient id="i4mpocc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.67689 2.22991 0 10.748 11.696)" gradientUnits="userSpaceOnUse"><stop class="w31fiiy0a"/><stop offset="1" class="pb35n8-2j"/></radialGradient><linearGradient id="iMAEV3b" x1="21.891" x2="22.035" y1="7.672" y2="7.59" gradientUnits="userSpaceOnUse"><stop class="it4yr4snu"/><stop offset="1" class="rhh1sln3b"/></linearGradient><linearGradient id="itLiWcj" x1="22.703" x2="22.477" y1="7.844" y2="7.711" gradientUnits="userSpaceOnUse"><stop class="it4yr4snu"/><stop offset="1" class="rhh1sln3b"/></linearGradient><linearGradient id="ivJy5he" x1="20.617" x2="20.648" y1="8.465" y2="8.25" gradientUnits="userSpaceOnUse"><stop class="q6ndyfw0a"/><stop offset="1" class="h-9cz2cok"/></linearGradient><linearGradient id="id8TUvc" x1="17.597" x2="25.597" y1="24.961" y2="24.961" gradientUnits="userSpaceOnUse"><stop class="zya7nifln"/><stop offset="1" class="idff6m3hh"/></linearGradient><linearGradient id="iWDl0MD" x1="16.029" x2="18.835" y1="23.873" y2="23.873" gradientUnits="userSpaceOnUse"><stop class="ilejznbvr"/><stop offset="1" class="m5-3l8byc"/></linearGradient><linearGradient id="izlQunx" x1="22.656" x2="22.656" y1="28.406" y2="26.594" gradientUnits="userSpaceOnUse"><stop class="nn7rblbwp"/><stop offset="1" class="s4f0ggbmr"/></linearGradient><linearGradient id="iDPDfzd" x1="28.594" x2="26.344" y1="24.344" y2="24.344" gradientUnits="userSpaceOnUse"><stop class="h9un4kbfp"/><stop offset="1" class="z-jnqiw9s"/></linearGradient><linearGradient id="iF2Sskh" x1="22.224" x2="18.306" y1="23.686" y2="19.451" gradientUnits="userSpaceOnUse"><stop class="fg8tbyb8i"/><stop offset="1" class="our4jdbuz"/></linearGradient><linearGradient id="igwpZUd" x1="22.23" x2="22.23" y1="17.47" y2="23.74" gradientUnits="userSpaceOnUse"><stop class="lunjvlbzg"/><stop offset="1" class="io0asw68z"/></linearGradient><linearGradient id="idmzzHe" x1="24.754" x2="23.616" y1="22.549" y2="21.51" gradientUnits="userSpaceOnUse"><stop class="f5978eb2q"/><stop offset="1" class="pd1kjfbix"/></linearGradient><linearGradient id="ilg0pTS" x1="9.313" x2="9.313" y1="28" y2="26.938" gradientUnits="userSpaceOnUse"><stop class="d3z7xm8tk"/><stop offset="1" class="btb287bpv"/></linearGradient><linearGradient id="it4HczJ" x1="9.73" x2="9.73" y1="24.031" y2="23.281" gradientUnits="userSpaceOnUse"><stop class="iowdsmh0u"/><stop offset="1" class="as90xs0qs"/></linearGradient><linearGradient id="iH65Hbe" x1="3.229" x2="29.452" y1="28.75" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="xlsbkujxn"/><stop offset="1" class="le2r_ylah"/></linearGradient><linearGradient id="igfyC5d" x1="16" x2="16" y1="27.75" y2="27.93" gradientUnits="userSpaceOnUse"><stop class="qkuvs9b1q"/><stop offset="1" class="o--keccps"/></linearGradient><linearGradient id="igIpwdc" x1="22.858" x2="22.858" y1="12.098" y2="11.891" gradientUnits="userSpaceOnUse"><stop class="izmmnfb2b"/><stop offset="1" class="rk6uj8bdr"/></linearGradient><linearGradient id="iNVm2Db" x1="7.5" x2="12.094" y1="8.41" y2="8.41" gradientUnits="userSpaceOnUse"><stop class="t6hpihbkj"/><stop offset="1" class="u8tt1se-f"/></linearGradient><linearGradient id="iChlGre" x1="9.797" x2="9.797" y1="9.109" y2="8.563" gradientUnits="userSpaceOnUse"><stop class="rl0aw956o"/><stop offset="1" class="gthh3-bns"/></linearGradient><linearGradient id="iWSkAub" x1="7.375" x2="7.891" y1="8.578" y2="8.578" gradientUnits="userSpaceOnUse"><stop class="tg883bqij"/><stop offset="1" class="qbhjn3keg"/></linearGradient><linearGradient id="iaC5vsd" x1="9.547" x2="7.938" y1="8.352" y2="8.352" gradientUnits="userSpaceOnUse"><stop class="nw6-tdxgw"/><stop offset="1" class="g4x4fooxn"/></linearGradient><linearGradient id="ivd7KVc" x1="8.607" x2="8.607" y1="12.935" y2="14.344" gradientUnits="userSpaceOnUse"><stop offset=".006" class="wopruvb4g"/><stop offset="1" class="abwob_bay"/></linearGradient><linearGradient id="inRhwBa" x1="10.857" x2="10.857" y1="12.935" y2="14.344" gradientUnits="userSpaceOnUse"><stop offset=".006" class="wopruvb4g"/><stop offset="1" class="abwob_bay"/></linearGradient><linearGradient id="ipVkXyT" x1="21.137" x2="21.137" y1="12.935" y2="14.344" gradientUnits="userSpaceOnUse"><stop offset=".006" class="wopruvb4g"/><stop offset="1" class="abwob_bay"/></linearGradient><linearGradient id="ifkiwbb" x1="23.387" x2="23.387" y1="12.935" y2="14.344" gradientUnits="userSpaceOnUse"><stop offset=".006" class="wopruvb4g"/><stop offset="1" class="abwob_bay"/></linearGradient><linearGradient id="iU2MNce" x1="9.875" x2="9.875" y1="7.055" y2="9.547" gradientUnits="userSpaceOnUse"><stop class="cvqf82bsw"/><stop offset="1" class="pg3nh_1yo"/></linearGradient><linearGradient id="isDkeqc" x1="10.328" x2="10.328" y1="12.098" y2="11.891" gradientUnits="userSpaceOnUse"><stop class="abeot0vkf"/><stop offset="1" class="i1-0jwb4p"/></linearGradient><filter id="ilmL6bb" width="1.805" height="1.603" x="19.787" y="6.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".025"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.698039 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="iL5dz3b" width="1.826" height="1.653" x="22.922" y="6.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.075"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.415686 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="iMGrVxd" width="8.149" height="7.07" x="17.906" y="17.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_806" stdDeviation=".2"/></filter><filter id="i6zjSeC" width="14.45" height="15.48" x="2.51" y="13.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.682353 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.545098 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_806" result="effect2_innerShadow_18_806"/></filter><filter id="ij9pBsb" width="2.259" height="6.627" x="8.444" y="17.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_806" stdDeviation=".125"/></filter><filter id="iMkCbHr" width="1.973" height="6.35" x="8.819" y="17.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.690196 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="iBzkFle" width="28.3" height="2.3" x="1.85" y="27.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.27451 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.552941 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_806" result="effect2_innerShadow_18_806"/></filter><filter id="iugxSCd" width="5.56" height="4.56" x="19.54" y="11.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.596078 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="iXxuTNe" width="5.55" height="2.81" x="19.56" y="9.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.25098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="itUwSCe" width="2.922" height=".797" x="9.188" y="7.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_806" stdDeviation=".125"/></filter><filter id="i0Dxxhd" width="5.55" height="7.27" x="7.03" y="9.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.654902 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="imbjjeU" width="1.5" height="1.832" x="7.788" y="12.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_806" stdDeviation=".125"/></filter><filter id="iUi64He" width="1.5" height="1.832" x="10.028" y="12.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_806" stdDeviation=".125"/></filter><filter id="izsy1QR" width="1.584" height="4.507" x="9.088" y="6.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.333333 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter><filter id="iseUare" width=".95" height="4.013" x="9.4" y="6.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_806" stdDeviation=".175"/></filter><filter id="iCHz7Md" width="5.55" height="2.81" x="7.03" y="9.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.262745 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_806"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:japanese-dolls" /></template>
<style>
.abeot0vkf {
  stop-color: var(--svg-color--4f4773, #4F4773);
}

.abwob_bay {
  stop-color: var(--svg-color--321f43, #321F43);
}

.aprou-k5e {
  stop-color: var(--svg-color--ecca54, #ECCA54);
}

.as90xs0qs {
  stop-color: var(--svg-color--dc9c49, #DC9C49);
  stop-opacity: 0;
}

.boe1nrb9c {
  d: path("m22.49 23.747l2.59-2.65c1.24-1.27.34-3.41-1.44-3.41h-3.32c-1.78 0-2.68 2.14-1.44 3.41l2.59 2.65c.29.28.75.28 1.02 0");
}

.btb287bpv {
  stop-color: var(--svg-color--4347a5, #4347A5);
  stop-opacity: 0;
}

.bughnhbqc {
  d: path("M24.96 12.05c0-1.5-1.21-2.71-2.7-2.71s-2.7 1.21-2.7 2.7v.01z");
}

.c31m0acqm {
  d: path("M9.23 17.51h1c.24 0 .43.21.41.45l-.5 5.53a.412.412 0 0 1-.82 0l-.5-5.53c-.02-.24.17-.45.41-.45");
}

.c8q7m0wbc {
  stop-color: var(--svg-color--82d8fb, #82D8FB);
  stop-opacity: 0;
}

.coca8obnt {
  d: path("m22.74 23.53l2.59-2.65c1.24-1.27.34-3.41-1.44-3.41h-3.32c-1.78 0-2.68 2.14-1.44 3.41l2.59 2.65c.29.28.75.28 1.02 0");
}

.cvqf82bsw {
  stop-color: var(--svg-color--8380b1, #8380B1);
}

.d3z7xm8tk {
  stop-color: var(--svg-color--4347a5, #4347A5);
}

.d57rpqboi {
  fill: var(--svg-color--7ed2fb, #7ED2FB);
  d: path("M10.3 13.77H9.17a5.16 5.16 0 0 0-5.16 5.16v7.76c0 .58.47 1.06 1.06 1.06h9.33c.58 0 1.06-.47 1.06-1.06v-7.76a5.16 5.16 0 0 0-5.16-5.16");
}

.dh3smnbph {
  fill: var(--svg-color--caab9f, #CAAB9F);
  d: path("M8.538 14.38c-.28 0-.5-.209-.5-.475v-.38c0-.267.22-.476.5-.476s.5.209.5.475v.39c0 .257-.23.466-.5.466");
}

.dkdygs0uc {
  d: path("M10.3 13.77H9.17a5.16 5.16 0 0 0-5.16 5.16v7.76c0 .58.47 1.06 1.06 1.06h9.33c.58 0 1.06-.47 1.06-1.06v-7.76a5.16 5.16 0 0 0-5.16-5.16");
}

.erx-dmber {
  d: path("M29 27.75H3c-.55 0-1 .45-1 1s.45 1 1 1h26c.55 0 1-.45 1-1s-.45-1-1-1");
}

.eu5rqvfaa {
  cx: 24.734px;
  cy: 12.125px;
  r: 1.969px;
}

.f02jr_bjn {
  stop-color: var(--svg-color--ab3140, #AB3140);
}

.f5978eb2q {
  stop-color: var(--svg-color--ebac4c, #EBAC4C);
}

.f63b1vbdb {
  stop-color: var(--svg-color--eaaf4a, #EAAF4A);
}

.f66pd3byc {
  stop-color: var(--svg-color--70687a, #70687A);
  stop-opacity: 0;
}

.fg8tbyb8i {
  stop-color: var(--svg-color--ab2e4d, #AB2E4D);
}

.ft5dv1b6b {
  fill: none;
}

.g2f905bpn {
  stop-color: var(--svg-color--3c243b, #3C243B);
}

.g3o9brb_b {
  d: path("m21.57 8.13l-.33-.79c-.22-.53-.93-.61-1.28-.16a.742.742 0 0 0 .5 1.18l.85.1c.19.04.34-.15.26-.33");
}

.g4x4fooxn {
  stop-color: var(--svg-color--e3e1e7, #E3E1E7);
  stop-opacity: 0;
}

.g8h36hkcw {
  d: path("M12.43 12.05h-5.4v-.01c0-1.49 1.21-2.7 2.7-2.7c1.5 0 2.71 1.21 2.7 2.7z");
}

.gfyu3s4vb {
  d: path("M9.73 9.34c-1.49 0-2.7 1.21-2.7 2.7v1.77c0 1.49 1.21 2.7 2.7 2.7s2.7-1.21 2.7-2.7v-1.77c.01-1.49-1.2-2.7-2.7-2.7");
}

.gind88bhl {
  stop-color: var(--svg-color--584e64, #584E64);
}

.gt_o3ittk {
  stop-color: var(--svg-color--82d8fb, #82D8FB);
}

.gthh3-bns {
  stop-color: var(--svg-color--636071, #636071);
  stop-opacity: 0;
}

.h-9cz2cok {
  stop-color: var(--svg-color--ad7a41, #AD7A41);
  stop-opacity: 0;
}

.h9un4kbfp {
  stop-color: var(--svg-color--d34f8a, #D34F8A);
}

.i1-0jwb4p {
  stop-color: var(--svg-color--4f4773, #4F4773);
  stop-opacity: 0;
}

.i53x9yb4t {
  d: path("m22.94 8.13l.33-.79c.22-.53.93-.61 1.28-.16c.34.46.06 1.11-.5 1.18l-.85.1c-.19.04-.33-.15-.26-.33");
}

.i5u1koihs {
  width: 1.284px;
  height: 4.507px;
  x: 9.088px;
  y: 6.333px;
  fill: var(--svg-color--5f5a94, #5F5A94);
  rx: 0.642px;
}

.idff6m3hh {
  stop-color: var(--svg-color--ec5d92, #EC5D92);
}

.ilejznbvr {
  stop-color: var(--svg-color--c36472, #C36472);
}

.io0asw68z {
  stop-color: var(--svg-color--f5c056, #F5C056);
}

.iowdsmh0u {
  stop-color: var(--svg-color--dc9c49, #DC9C49);
}

.it4yr4snu {
  stop-color: var(--svg-color--ce9658, #CE9658);
}

.izmmnfb2b {
  stop-color: var(--svg-color--46345d, #46345D);
}

.je-_ucyet {
  stop-color: var(--svg-color--6e6975, #6E6975);
}

.jo3pn9bup {
  stop-color: var(--svg-color--76737f, #76737F);
}

.jsg34sbje {
  stop-color: var(--svg-color--695d77, #695D77);
}

.jzeyf1bta {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.875 6.797v3.062");
}

.k3e18ejek {
  stop-color: var(--svg-color--b55965, #B55965);
}

.kbcbd3b1e {
  fill: var(--svg-color--d3aea3, #D3AEA3);
  d: path("M10.778 14.38c-.28 0-.5-.209-.5-.475v-.38c0-.267.22-.476.5-.476s.5.209.5.475v.39c0 .257-.23.466-.5.466");
}

.kyb2dtbed {
  d: path("M23.39 14.34c-.28 0-.5-.22-.5-.5v-.4c0-.28.22-.5.5-.5s.5.22.5.5v.41c0 .27-.22.49-.5.49");
}

.l9pckb_7h {
  stop-color: var(--svg-color--e1a747, #E1A747);
}

.le1x95bza {
  stop-color: var(--svg-color--70687a, #70687A);
}

.le2r_ylah {
  stop-color: var(--svg-color--bd7659, #BD7659);
}

.lunjvlbzg {
  stop-color: var(--svg-color--fbe46c, #FBE46C);
}

.m5-3l8byc {
  stop-color: var(--svg-color--c36472, #C36472);
  stop-opacity: 0;
}

.nn7rblbwp {
  stop-color: var(--svg-color--ad2b62, #AD2B62);
}

.nqvejbtdd {
  stop-color: var(--svg-color--fdf57b, #FDF57B);
}

.nt_n5e7ue {
  stop-color: var(--svg-color--f9db78, #F9DB78);
}

.nw6-tdxgw {
  stop-color: var(--svg-color--e3e1e7, #E3E1E7);
}

.o_h807b_b {
  stop-color: var(--svg-color--edc6c0, #EDC6C0);
}

.o--keccps {
  stop-color: var(--svg-color--b6674c, #B6674C);
  stop-opacity: 0;
}

.opqj0fbov {
  stop-color: var(--svg-color--e9e6ed, #E9E6ED);
}

.ots3m5bsh {
  stop-color: var(--svg-color--fbe673, #FBE673);
}

.our4jdbuz {
  stop-color: var(--svg-color--ab2e4d, #AB2E4D);
  stop-opacity: 0;
}

.p01umtm_a {
  stop-color: var(--svg-color--fbe47a, #FBE47A);
}

.p4ppiuczb {
  d: path("M19.55 13.81c0 1.49 1.21 2.7 2.7 2.7s2.7-1.21 2.7-2.7v-1.76h-5.41v1.76z");
}

.pb35n8-2j {
  stop-color: var(--svg-color--56517e, #56517E);
}

.pd1kjfbix {
  stop-color: var(--svg-color--ebac4c, #EBAC4C);
  stop-opacity: 0;
}

.pg3nh_1yo {
  stop-color: var(--svg-color--726e9b, #726E9B);
}

.pl6sdv8pe {
  stop-color: var(--svg-color--766c82, #766C82);
}

.prrt7gb1y {
  stop-color: var(--svg-color--fbe774, #FBE774);
  stop-opacity: 0;
}

.q6ndyfw0a {
  stop-color: var(--svg-color--ad7a41, #AD7A41);
}

.q8gasb5lc {
  d: path("M10.86 14.34c-.28 0-.5-.22-.5-.5v-.4c0-.28.22-.5.5-.5s.5.22.5.5v.41a.5.5 0 0 1-.5.49");
}

.qbhjn3keg {
  stop-color: var(--svg-color--a6a3aa, #A6A3AA);
  stop-opacity: 0;
}

.qkuvs9b1q {
  stop-color: var(--svg-color--b6674c, #B6674C);
}

.qoewk7b2i {
  stop-color: var(--svg-color--76737f, #76737F);
  stop-opacity: 0;
}

.rhh1sln3b {
  stop-color: var(--svg-color--ce9658, #CE9658);
  stop-opacity: 0;
}

.rk6uj8bdr {
  stop-color: var(--svg-color--46345d, #46345D);
  stop-opacity: 0;
}

.rl0aw956o {
  stop-color: var(--svg-color--636071, #636071);
}

.rp69ixb2y {
  d: path("M22.83 13.77H21.7a5.16 5.16 0 0 0-5.16 5.16v7.76c0 .58.47 1.06 1.06 1.06h9.33c.58 0 1.06-.47 1.06-1.06v-7.76a5.16 5.16 0 0 0-5.16-5.16");
}

.rs1z8acua {
  stop-color: var(--svg-color--311742, #311742);
}

.s_a4yubzj {
  d: path("M8.61 14.34c-.28 0-.5-.22-.5-.5v-.4c0-.28.22-.5.5-.5s.5.22.5.5v.41a.5.5 0 0 1-.5.49");
}

.s4f0ggbmr {
  stop-color: var(--svg-color--ad2b62, #AD2B62);
  stop-opacity: 0;
}

.shi1es7ad {
  fill: var(--svg-color--4e8db3, #4E8DB3);
  d: path("M9.091 17.778h.965a.4.4 0 0 1 .396.434l-.483 5.336a.398.398 0 0 1-.79 0l-.483-5.336a.4.4 0 0 1 .395-.434");
}

.t10t-nbrq {
  cx: 19.796px;
  cy: 12.125px;
  r: 1.969px;
}

.t255isx1g {
  d: path("M21.14 14.34c-.28 0-.5-.22-.5-.5v-.4c0-.28.22-.5.5-.5s.5.22.5.5v.41c0 .27-.22.49-.5.49");
}

.t2wlzhben {
  stop-color: var(--svg-color--cd8937, #CD8937);
  stop-opacity: 0;
}

.t6hpihbkj {
  stop-color: var(--svg-color--b3b2b4, #B3B2B4);
}

.tf6m4s0ca {
  stop-color: var(--svg-color--f1ba51, #F1BA51);
}

.tg883bqij {
  stop-color: var(--svg-color--a6a3aa, #A6A3AA);
}

.th6hfnfit {
  stop-color: var(--svg-color--6c6772, #6C6772);
}

.tofnqza8z {
  stop-color: var(--svg-color--ab3140, #AB3140);
  stop-opacity: 0;
}

.u2w07cpxx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m9.563 8.398l2.171-.046");
}

.u8tt1se-f {
  stop-color: var(--svg-color--c7c7c8, #C7C7C8);
}

.un12mvbcy {
  stop-color: var(--svg-color--695d77, #695D77);
  stop-opacity: 0;
}

.ux-zzj3ci {
  d: path("m22.47 7.85l.43-.74A.742.742 0 0 0 22.26 6c-.57 0-.93.62-.64 1.11l.43.74c.09.17.33.17.42 0");
}

.w2n-vzi6a {
  stop-color: var(--svg-color--fbe878, #FBE878);
}

.w31fiiy0a {
  stop-color: var(--svg-color--7e78a4, #7E78A4);
}

.wopruvb4g {
  stop-color: var(--svg-color--4c3f56, #4C3F56);
}

.wuveq6bek {
  d: path("M22.26 10a1.13 1.13 0 1 0 0-2.26a1.13 1.13 0 0 0 0 2.26");
}

.x7gkbqb8w {
  stop-color: var(--svg-color--fef67e, #FEF67E);
}

.xch9my-bj {
  stop-color: var(--svg-color--fbe774, #FBE774);
}

.xkk8xxbls {
  stop-color: var(--svg-color--cd8937, #CD8937);
}

.xlsbkujxn {
  stop-color: var(--svg-color--ee9463, #EE9463);
}

.xrmjy5bfl {
  stop-color: var(--svg-color--e5ab48, #E5AB48);
}

.xyz1deaev {
  stop-color: var(--svg-color--4f3c62, #4F3C62);
}

.y-i8y-xbq {
  stop-color: var(--svg-color--fdf4d3, #FDF4D3);
}

.y5la4-bas {
  stop-color: var(--svg-color--b55965, #B55965);
  stop-opacity: 0;
}

.ydd72cf-d {
  d: path("M22.26 12.07a1.81 1.81 0 1 0 0-3.62a1.81 1.81 0 0 0 0 3.62");
}

.ymxx_xers {
  stop-color: var(--svg-color--fbe47a, #FBE47A);
  stop-opacity: 0;
}

.z-jnqiw9s {
  stop-color: var(--svg-color--d34f8a, #D34F8A);
  stop-opacity: 0;
}

.z7g92dbrf {
  fill-rule: evenodd;
  d: path("M7.5 8.41a.5.5 0 0 1 .5-.5h3.594a.5.5 0 0 1 0 1H8a.5.5 0 0 1-.5-.5");
}

.zjkmvtk0o {
  stop-color: var(--svg-color--e9e6ed, #E9E6ED);
  stop-opacity: 0;
}

.zr4oiyuhj {
  stop-color: var(--svg-color--706878, #706878);
}

.zya7nifln {
  stop-color: var(--svg-color--db4c66, #DB4C66);
}

</style>
