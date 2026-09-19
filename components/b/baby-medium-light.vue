<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLdmtye)" class="hjnup67lg"/><path fill="url(#iYwApze)" class="hjnup67lg"/><g filter="url(#iBRxQLc)"><path fill="url(#izwUdCe)" class="h9yhkdybs"/></g><path fill="url(#ifc4Kzc)" class="lue5vkbks"/><path fill="url(#izyyW1d)" class="lue5vkbks"/><path fill="url(#iC1HJWd)" class="lue5vkbks"/><path fill="url(#iARwalQ)" class="lue5vkbks"/><g filter="url(#icWqPtc)"><path fill="url(#ih409ic)" class="xejiqs87d"/></g><g filter="url(#izBxjfL)"><path class="l5d4zs5_u"/><path fill="url(#iHvjmgc)" class="us11zs37i"/><path fill="url(#imsLsyc)" class="us11zs37i"/><path fill="url(#imvlAeb)" class="us11zs37i"/><path fill="url(#iBPbthe)" class="us11zs37i"/><path fill="url(#iOUI3Tb)" class="us11zs37i"/><path fill="url(#i5BDvcd)" class="us11zs37i"/><path fill="url(#iw1mJpc)" class="us11zs37i"/></g><path fill="url(#ipKIDJA)" class="us11zs37i"/><path fill="url(#iPNv49S)" class="us11zs37i"/><g filter="url(#iYdQTJe)"><path stroke="url(#i0aDfMJ)" class="i2uazfh8t"/></g><g filter="url(#iVEHjHx)"><path class="x4sksh0rm"/></g><path class="u_5l6bbbo"/><path fill="url(#i7nzOId)" class="ebltgib8r"/><path fill="url(#iBTrJCd)" class="mfcd_tu4f"/><path class="nui2pvb6n"/><g filter="url(#i2Eh2Hd)"><path class="t9fz_tb_s"/></g><g filter="url(#iZETQ0j)"><path stroke="url(#iI0OCDz)" class="mh-87m9bc"/></g><g filter="url(#iLeFcYc)"><path class="tx7vsk2hu"/></g><g filter="url(#i8Nmukb)"><path stroke="url(#i4QCPJc)" class="kpdq24bfz"/></g><g filter="url(#i3kBykc)"><path fill="url(#ioLS6lb)" class="wwljv4b0n"/></g><g filter="url(#iPm9dsb)"><path class="y0vrmxqpx"/><path fill="url(#iqSeM0b)" class="btd4kvbkw"/><path fill="url(#iJkqp8d)" class="btd4kvbkw"/><path fill="url(#iCspNRd)" class="btd4kvbkw"/><path fill="url(#idXsRpb)" class="btd4kvbkw"/></g><g filter="url(#iDby2Jc)"><path class="c9asshrpv"/></g><g filter="url(#ih8Ez9d)"><path fill="url(#iik6czb)" class="y6ws5i6hc"/><path fill="url(#iYGjNHd)" class="y6ws5i6hc"/></g><g filter="url(#iUkXX3d)"><path class="uuomzi7ol"/><path fill="url(#iONJGGb)" class="vxam15b5n"/></g><g filter="url(#iHRWiec)"><path fill="url(#izNfCjb)" class="kyomsccgu"/></g><g filter="url(#itGuhed)"><path fill="url(#iCzXc4K)" class="at5ezfbka"/></g><g filter="url(#iDIR8od)"><ellipse transform="rotate(-27.914 10.689 19.014)" class="fynu7rbso"/><ellipse fill="url(#iDoKz5K)" transform="rotate(-27.914 10.689 19.014)" class="vxbv9ibrd"/></g><g filter="url(#ieIzTEb)"><path fill="url(#iedvesb)" class="krktqqb9i"/></g><defs><radialGradient id="iYwApze" cx="0" cy="0" r="1" gradientTransform="rotate(176.967 3.048 10.228)scale(3.54403 3.68531)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="ymutrvb0h"/><stop offset="1" class="dcp108bys"/></radialGradient><radialGradient id="izwUdCe" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.73 13.363)scale(2.01965)" gradientUnits="userSpaceOnUse"><stop class="vdhu5sbwc"/><stop offset="1" class="xdhwqtbkz"/></radialGradient><radialGradient id="izyyW1d" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 3.692 22.23)scale(4.7194 4.52281)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="f_manrjbp"/><stop offset="1" class="a4f2nm63s"/></radialGradient><radialGradient id="iC1HJWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.84823 -2.07813 2.05068 1.82382 25.98 19.688)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="vnf59qbgc"/><stop offset=".883" class="wjpixgrsk"/></radialGradient><radialGradient id="iARwalQ" cx="0" cy="0" r="1" gradientTransform="rotate(-77.969 26.05 -5.676)scale(3.89812 3.06112)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="ypa0dqb5t"/><stop offset="1" class="op74yoooa"/></radialGradient><radialGradient id="ih409ic" cx="0" cy="0" r="1" gradientTransform="matrix(1.48437 .23437 -.3465 2.19446 26.313 20.25)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="n6775zkib"/><stop offset="1" class="a8evesbiu"/></radialGradient><radialGradient id="imvlAeb" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 10.00001 -3.04902 .41924 5.5 19.906)" gradientUnits="userSpaceOnUse"><stop class="j04i2bc2h"/><stop offset="1" class="ika7xqbdn"/></radialGradient><radialGradient id="iBPbthe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 -13.00004 20.39882 -1.96142 10.813 30.266)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="a4f2nm63s"/><stop offset="1" class="f_manrjbp"/></radialGradient><radialGradient id="iOUI3Tb" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 -2.625 3.5 1.875 11.063 18.688)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="yap3dzbqh"/><stop offset="1" class="pkhanubeu"/></radialGradient><radialGradient id="i5BDvcd" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -2.71875 3.18328 .58543 21.375 18.938)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="be1prbbvx"/><stop offset="1" class="piifpilex"/></radialGradient><radialGradient id="iw1mJpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.625 -5.90625 0 23.469 20.375)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yse4ebceo"/></radialGradient><radialGradient id="iPNv49S" cx="0" cy="0" r="1" gradientTransform="rotate(-106.498 17.155 4.786)scale(18.7077 27.0296)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="wu77zvqhp"/><stop offset="1" class="mmztprbmz"/></radialGradient><radialGradient id="i7nzOId" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 20.328 19.25)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ynn7rr4al"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="tzlh-yb0a"/></radialGradient><radialGradient id="iBTrJCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 11.358 19.25)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ynn7rr4al"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="tzlh-yb0a"/></radialGradient><radialGradient id="iqSeM0b" cx="0" cy="0" r="1" gradientTransform="matrix(7.82169 -1.5259 1.27295 6.52504 12.03 6.719)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="gqs8qobxe"/><stop offset="1" class="wxdt1jb_s"/></radialGradient><radialGradient id="iJkqp8d" cx="0" cy="0" r="1" gradientTransform="rotate(-23.69 23.3 -25.057)scale(6.68877 6.45832)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="uhbk1cbqf"/><stop offset=".912" class="qcx_m5b9c"/></radialGradient><radialGradient id="iCspNRd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63771 -5.65242 5.82757 -3.75043 16.76 8.537)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="itfb13gqc"/><stop offset="1" class="vder1tbnm"/></radialGradient><radialGradient id="idXsRpb" cx="0" cy="0" r="1" gradientTransform="rotate(57.863 2.822 16.523)scale(5.75713 5.52963)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="yq-pa7bnx"/><stop offset=".966" class="e2nc-mb3x"/></radialGradient><radialGradient id="iik6czb" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 .04688 -.02424 .98567 15.36 22)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="gyv3q3b9l"/><stop offset="1" class="fl5tp5bfj"/></radialGradient><radialGradient id="iYGjNHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.79467 0 16.133 21.39)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="k-93cikvm"/><stop offset="1" class="xujuduamj"/></radialGradient><radialGradient id="iONJGGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5717 -.73672 1.01428 -.7871 19.765 19.457)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDoKz5K" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 15.067 4.652)scale(1.21806 1.46416)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iBRxQLc" width="4.539" height="4.539" x="4.363" y="17.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".125"/></filter><filter id="icWqPtc" width="4.663" height="4.663" x="23.301" y="17.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".125"/></filter><filter id="izBxjfL" width="23.65" height="26" x="4.753" y="4.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24661"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.760784 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24661" result="effect2_innerShadow_3987_24661"/></filter><filter id="iYdQTJe" width="7.502" height="2.901" x="12.382" y="23.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".05"/></filter><filter id="iVEHjHx" width="7" height="2.4" x="12.633" y="23.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24661"/></filter><filter id="i2Eh2Hd" width="3.72" height="1.592" x="9.113" y="14.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.247059 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24661"/></filter><filter id="iZETQ0j" width="3.17" height=".992" x="9.317" y="14.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".1"/></filter><filter id="iLeFcYc" width="3.72" height="1.592" x="19.213" y="14.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24661"/></filter><filter id="i8Nmukb" width="3.17" height=".992" x="19.363" y="14.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".1"/></filter><filter id="i3kBykc" width="7.877" height="8.718" x="12.162" y="2.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".25"/></filter><filter id="iPm9dsb" width="8.1" height="8.529" x="11.931" y="2.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.721569 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24661"/></filter><filter id="iDby2Jc" width="3.638" height="2.603" x="14.181" y="21.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".25"/></filter><filter id="ih8Ez9d" width="3.138" height="2.103" x="14.564" y="21.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".125"/></filter><filter id="iUkXX3d" width="1.647" height="1.423" x="18.665" y="18.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".05"/></filter><filter id="iHRWiec" width="1.611" height="1.666" x="20.881" y="18.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".1"/></filter><filter id="itGuhed" width="1.845" height="1.978" x="11.717" y="18.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".1"/></filter><filter id="iDIR8od" width="1.958" height="1.444" x="9.71" y="18.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation=".05"/></filter><filter id="ieIzTEb" width="13.584" height="12.368" x="14.564" y="4.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24661" stdDeviation="1.25"/></filter><linearGradient id="iLdmtye" x1="3.906" x2="6.25" y1="17.344" y2="23.344" gradientUnits="userSpaceOnUse"><stop class="fmllmi0vm"/><stop offset="1" class="ex13nsb1n"/></linearGradient><linearGradient id="ifc4Kzc" x1="28.516" x2="25.933" y1="18.406" y2="22.594" gradientUnits="userSpaceOnUse"><stop class="iw08qbcjx"/><stop offset="1" class="k8yy-p62i"/></linearGradient><linearGradient id="iHvjmgc" x1="16.153" x2="16.153" y1="30.844" y2="25.719" gradientUnits="userSpaceOnUse"><stop offset=".195" class="ep5muxxmd"/><stop offset="1" class="bp184cb9v"/></linearGradient><linearGradient id="imsLsyc" x1="6.938" x2="18.188" y1="18.344" y2="21.219" gradientUnits="userSpaceOnUse"><stop class="dvexzpbfd"/><stop offset="1" class="rtvwugb3k"/></linearGradient><linearGradient id="ipKIDJA" x1="16.153" x2="16.153" y1="30.844" y2="27.344" gradientUnits="userSpaceOnUse"><stop offset=".195" class="kfuvhdcxh"/><stop offset="1" class="y8qlx76pm"/></linearGradient><linearGradient id="i0aDfMJ" x1="13.797" x2="14.297" y1="25.328" y2="24.422" gradientUnits="userSpaceOnUse"><stop class="g87cs9b-d"/><stop offset="1" class="ylr-iebya"/></linearGradient><linearGradient id="iI0OCDz" x1="9.969" x2="12.344" y1="15.688" y2="15.33" gradientUnits="userSpaceOnUse"><stop class="w9x82yb4n"/><stop offset="1" class="ysf50-btc"/></linearGradient><linearGradient id="i4QCPJc" x1="21.969" x2="18.875" y1="15.875" y2="15.594" gradientUnits="userSpaceOnUse"><stop class="w9x82yb4n"/><stop offset="1" class="ysf50-btc"/></linearGradient><linearGradient id="ioLS6lb" x1="16.456" x2="15.417" y1="3.338" y2="10.833" gradientUnits="userSpaceOnUse"><stop offset=".709" class="opjqgdepo"/><stop offset="1" class="jezlerabr"/></linearGradient><linearGradient id="izNfCjb" x1="22.245" x2="21.472" y1="19.383" y2="19.859" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCzXc4K" x1="13.191" x2="12.418" y1="19.383" y2="19.859" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iedvesb" x1="17.804" x2="27.5" y1="14.813" y2="8.969" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-medium-light" /></template>
<style>
.a4f2nm63s {
  stop-color: var(--svg-color--bc7c81, #BC7C81);
}

.a8evesbiu {
  stop-color: var(--svg-color--dd9d78, #DD9D78);
}

.at5ezfbka {
  d: path("M13.363 20.016c0-.711-.578-1.185-.735-1.328l-.71.687l.437.89z");
}

.be1prbbvx {
  stop-color: var(--svg-color--e1a08c, #E1A08C);
}

.bp184cb9v {
  stop-color: var(--svg-color--b46f93, #B46F93);
  stop-opacity: 0;
}

.btd4kvbkw {
  d: path("M15.831 2.344a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.c9asshrpv {
  fill: var(--svg-color--cb877e, #CB877E);
  d: path("M16.002 23.344c.51 0 .965-.281 1.225-.702c.238-.386-.011-.901-.445-.901h-1.56c-.433 0-.693.526-.444.9c.26.434.715.703 1.224.703");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dcp108bys {
  stop-color: var(--svg-color--dda388, #DDA388);
}

.dvexzpbfd {
  stop-color: var(--svg-color--ca957a, #CA957A);
}

.e2nc-mb3x {
  stop-color: var(--svg-color--ffcda4, #FFCDA4);
}

.ebltgib8r {
  d: path("M20.333 18.074a2.2 2.2 0 0 1 2.12 2.78h-4.25c-.05-.19-.08-.38-.08-.58c0-1.21.99-2.2 2.21-2.2");
}

.ep5muxxmd {
  stop-color: var(--svg-color--b46f93, #B46F93);
}

.ex13nsb1n {
  stop-color: var(--svg-color--b97373, #B97373);
}

.f_manrjbp {
  stop-color: var(--svg-color--bc7c81, #BC7C81);
  stop-opacity: 0;
}

.fl5tp5bfj {
  stop-color: var(--svg-color--f8c2a3, #F8C2A3);
}

.fmllmi0vm {
  stop-color: var(--svg-color--bf8265, #BF8265);
}

.ft5dv1b6b {
  fill: none;
}

.fynu7rbso {
  cx: 10.689px;
  cy: 19.014px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.96px;
  ry: 0.486px;
}

.g87cs9b-d {
  stop-color: var(--svg-color--d29992, #D29992);
}

.gqs8qobxe {
  stop-color: var(--svg-color--fffbbe, #FFFBBE);
  stop-opacity: 0;
}

.gyv3q3b9l {
  stop-color: var(--svg-color--dc9f8f, #DC9F8F);
}

.h9yhkdybs {
  d: path("M6.633 22.113a2.02 2.02 0 1 0 0-4.039a2.02 2.02 0 0 0 0 4.04");
}

.hjnup67lg {
  d: path("M6.633 23.344a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.i2uazfh8t {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.153 23.508c-.367-.197-.757.223-.526.579l.063-.041a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.281-.13-.622-.428-.472a6.55 6.55 0 0 1-3.027.733a6.4 6.4 0 0 1-3.007-.733z");
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.ika7xqbdn {
  stop-color: var(--svg-color--da9f86, #DA9F86);
  stop-opacity: 0;
}

.itfb13gqc {
  stop-color: var(--svg-color--dfc38e, #DFC38E);
  stop-opacity: 0;
}

.iw08qbcjx {
  stop-color: var(--svg-color--f4c4a2, #F4C4A2);
}

.j04i2bc2h {
  stop-color: var(--svg-color--da9f86, #DA9F86);
}

.jezlerabr {
  stop-color: var(--svg-color--d59471, #D59471);
}

.k-93cikvm {
  stop-color: var(--svg-color--c9847d, #C9847D);
  stop-opacity: 0;
}

.k8yy-p62i {
  stop-color: var(--svg-color--daa087, #DAA087);
}

.kfuvhdcxh {
  stop-color: var(--svg-color--b57096, #B57096);
}

.kpdq24bfz {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22.183 15.278c-.59-.21-1.41-.36-2.47-.26");
}

.krktqqb9i {
  d: path("m18.483 9.45l4.36-2.325c2.774 2 2.899 5.615 2.774 6.594l-5.513.75a2.679 2.679 0 0 1-1.621-5.018");
}

.kyomsccgu {
  d: path("M22.292 19.984a2.07 2.07 0 0 0-.57-1.14l-.64.703l.288.562z");
}

.l5d4zs5_u {
  fill: var(--svg-color--f0b39b, #F0B39B);
  d: path("M23.362 6.056a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.111c.296 3.14 2.377 5.781 5.265 6.681c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.701-3.745-8.691");
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lue5vkbks {
  d: path("M25.633 23.344a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfcd_tu4f {
  d: path("M11.353 18.074a2.2 2.2 0 0 0-2.12 2.78h4.25c.05-.19.08-.38.08-.58c-.01-1.21-.99-2.2-2.21-2.2");
}

.mh-87m9bc {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.668 15.33c.59-.21 1.41-.36 2.47-.26");
}

.mmztprbmz {
  stop-color: var(--svg-color--c29d81, #C29D81);
}

.n6775zkib {
  stop-color: var(--svg-color--dfa689, #DFA689);
}

.nui2pvb6n {
  fill: var(--svg-color--000, #000);
  d: path("M19.073 20.274c0-.7.56-1.26 1.26-1.26s1.26.56 1.26 1.26c0 .21-.05.41-.14.58h-2.23c-.1-.17-.15-.37-.15-.58m-6.46 0c0-.7-.56-1.26-1.26-1.26s-1.26.56-1.26 1.26c0 .21.05.41.14.58h2.23c.09-.17.15-.37.15-.58");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op74yoooa {
  stop-color: var(--svg-color--e3b792, #E3B792);
}

.opjqgdepo {
  stop-color: var(--svg-color--c88b60, #C88B60);
}

.piifpilex {
  stop-color: var(--svg-color--e1a08c, #E1A08C);
  stop-opacity: 0;
}

.pkhanubeu {
  stop-color: var(--svg-color--c0817c, #C0817C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qcx_m5b9c {
  stop-color: var(--svg-color--e4c089, #E4C089);
  stop-opacity: 0;
}

.rtvwugb3k {
  stop-color: var(--svg-color--ca957a, #CA957A);
  stop-opacity: 0;
}

.t9fz_tb_s {
  stroke: var(--svg-color--935d2c, #935D2C);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.613 15.424c.59-.21 1.41-.36 2.47-.26");
}

.tx7vsk2hu {
  stroke: var(--svg-color--9b6433, #9B6433);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.183 15.424c-.59-.21-1.41-.36-2.47-.26");
}

.tzlh-yb0a {
  stop-color: var(--svg-color--704d49, #704D49);
}

.u_5l6bbbo {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.843 17.404c1.61 0 2.97 1.11 3.34 2.61c.11.43-.22.84-.66.84h-5.5c-.35 0-.63-.32-.56-.67c.31-1.58 1.7-2.78 3.38-2.78m-10 0c-1.61 0-2.97 1.11-3.34 2.61c-.11.43.22.84.66.84h5.5c.35 0 .63-.32.56-.67a3.454 3.454 0 0 0-3.38-2.78");
}

.uhbk1cbqf {
  stop-color: var(--svg-color--e4c089, #E4C089);
}

.us11zs37i {
  d: path("M23.362 6.056a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.111c.296 3.14 2.377 5.781 5.265 6.681c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.701-3.745-8.691");
}

.uuomzi7ol {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.171 18.54c.157.209-.17.464-.543.743s-.65.474-.806.265c-.157-.21.018-.606.39-.884c.373-.279.802-.335.959-.125");
}

.vder1tbnm {
  stop-color: var(--svg-color--dfc38e, #DFC38E);
}

.vdhu5sbwc {
  stop-color: var(--svg-color--b67663, #B67663);
}

.vnf59qbgc {
  stop-color: var(--svg-color--db9c78, #DB9C78);
}

.vxam15b5n {
  d: path("M20.171 18.54c.157.209-.17.464-.543.743s-.65.474-.806.265c-.157-.21.018-.606.39-.884c.373-.279.802-.335.959-.125");
}

.vxbv9ibrd {
  cx: 10.689px;
  cy: 19.014px;
  rx: 0.96px;
  ry: 0.486px;
}

.w9x82yb4n {
  stop-color: var(--svg-color--935d37, #935D37);
}

.wjpixgrsk {
  stop-color: var(--svg-color--db9c78, #DB9C78);
  stop-opacity: 0;
}

.wu77zvqhp {
  stop-color: var(--svg-color--c29d81, #C29D81);
  stop-opacity: 0;
}

.wwljv4b0n {
  d: path("M16.252 3.31c-1.473-.222-2.757-.002-3.59 1.111c1.994 0 4.72 1.224 4.325 3.843a2.97 2.97 0 0 1-.994 1.815a.492.492 0 0 0 .403.863A3.87 3.87 0 0 0 19.5 7.667c.298-2.086-1.164-4.04-3.248-4.356");
}

.wxdt1jb_s {
  stop-color: var(--svg-color--fffbbe, #FFFBBE);
}

.x4sksh0rm {
  fill: var(--svg-color--89024e, #89024E);
  d: path("M16.125 24.307a6.4 6.4 0 0 1-3.007-.733c-.299-.16-.617.181-.428.472a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.281-.13-.622-.428-.472a6.55 6.55 0 0 1-3.027.733");
}

.xdhwqtbkz {
  stop-color: var(--svg-color--ba7660, #BA7660);
}

.xejiqs87d {
  d: path("M25.633 22.175a2.081 2.081 0 1 0 0-4.163a2.081 2.081 0 0 0 0 4.163");
}

.xujuduamj {
  stop-color: var(--svg-color--c9847d, #C9847D);
}

.y0vrmxqpx {
  fill: var(--svg-color--ecc991, #ECC991);
  d: path("M15.831 2.344a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.y6ws5i6hc {
  d: path("M16.135 22.994c.51 0 .964-.281 1.225-.702c.238-.387-.011-.901-.445-.901h-1.56c-.434 0-.694.526-.444.9c.26.434.715.703 1.224.703");
}

.y8qlx76pm {
  stop-color: var(--svg-color--b57096, #B57096);
  stop-opacity: 0;
}

.yap3dzbqh {
  stop-color: var(--svg-color--c0817c, #C0817C);
}

.ylr-iebya {
  stop-color: var(--svg-color--d29992, #D29992);
  stop-opacity: 0;
}

.ymutrvb0h {
  stop-color: var(--svg-color--dda388, #DDA388);
  stop-opacity: 0;
}

.ynn7rr4al {
  stop-color: var(--svg-color--865b4f, #865B4F);
}

.ypa0dqb5t {
  stop-color: var(--svg-color--e3b792, #E3B792);
  stop-opacity: 0;
}

.yq-pa7bnx {
  stop-color: var(--svg-color--ffcda4, #FFCDA4);
  stop-opacity: 0;
}

.yse4ebceo {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
  stop-opacity: 0;
}

.ysf50-btc {
  stop-color: var(--svg-color--935d37, #935D37);
  stop-opacity: 0;
}

</style>
