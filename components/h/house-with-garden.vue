<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imMDiSb)"><path fill="url(#iPzp9yJ)" class="lt46h0bvb"/><path fill="url(#ihwqm5d)" class="lt46h0bvb"/><path fill="url(#iym1FAd)" class="lt46h0bvb"/></g><g filter="url(#iH8cFMb)"><ellipse fill="url(#itcIM6b)" transform="rotate(-27.195 5.89 21.869)" class="dr1kg0txw"/></g><g filter="url(#iy1I4Dc)"><ellipse fill="url(#iCb7Ebb)" transform="rotate(50.517 6.831 16.36)" class="dl4foo5wf"/></g><path fill="url(#iwYzzCL)" class="zrqhxnbki"/><path fill="url(#io2dp0c)" class="zrqhxnbki"/><path fill="url(#if5EZde)" class="zrqhxnbki"/><path fill="url(#iyZhhQc)" class="zrqhxnbki"/><path fill="url(#iLOE34c)" class="zrqhxnbki"/><path fill="url(#ikMLu1b)" class="xm3w2fbrt"/><path fill="url(#i8l3Iuj)" class="xm3w2fbrt"/><path fill="url(#iz1Jh9b)" class="xm3w2fbrt"/><path fill="url(#iNheFyQ)" class="xm3w2fbrt"/><path fill="url(#iL6IcTd)" class="xm3w2fbrt"/><path fill="url(#iv8J0Zd)" class="xm3w2fbrt"/><path fill="url(#iJOpvwe)" class="xm3w2fbrt"/><g filter="url(#iLwVz9d)"><path fill="url(#imHFvud)" class="j870720pc"/></g><g filter="url(#iE55umb)"><path class="tzd8tgalg"/></g><g filter="url(#iK6oIDr)"><path fill="url(#iFE1y9q)" class="erjxitbgr"/><path fill="url(#i6K7VzX)" class="erjxitbgr"/></g><path fill="url(#ivtJcny)" class="erjxitbgr"/><path fill="url(#iu2wjcb)" class="erjxitbgr"/><g filter="url(#iWnKIEb)"><path fill="url(#i8GEhxb)" class="ugvrppuhr"/></g><g filter="url(#ir71BPk)"><path class="bll-m7ilq"/></g><g filter="url(#i07EmOc)"><path class="b0-ikxjbv"/></g><path fill="url(#iQf2Hdd)" class="l9ggrvi-p"/><path fill="url(#ivRmMic)" class="da1wtdbyp"/><path fill="url(#i9T3tye)" class="da1wtdbyp"/><path fill="url(#ig7Zahc)" class="da1wtdbyp"/><g filter="url(#ioPxixe)"><path class="sg5p9ubuv"/></g><path fill="url(#iBqcDFe)" class="ktxdwvbvu"/><path fill="url(#ip5y6jb)" class="ktxdwvbvu"/><path fill="url(#idTq6Eb)" class="ktxdwvbvu"/><g filter="url(#i2zc61b)"><path class="vkso9s2il"/><path fill="url(#iuppaid)" class="egcighbqt"/><path fill="url(#ifp6E5d)" class="egcighbqt"/><path fill="url(#isVO3jc)" class="egcighbqt"/></g><path fill="url(#ibNTXKe)" class="egcighbqt"/><g filter="url(#i82bs8d)"><path stroke="url(#iP7EGUP)" class="sh1a86b1h"/></g><g filter="url(#i7VIJQd)"><path stroke="url(#ilpQXWk)" class="t2jdy5b2y"/></g><g filter="url(#it7T1EU)"><path class="gqxsk9_sr"/></g><defs><linearGradient id="iPzp9yJ" x1="8.432" x2="8.432" y1="10.307" y2="24.821" gradientUnits="userSpaceOnUse"><stop class="zruu8o3cb"/><stop offset="1" class="bgphk3ngz"/></linearGradient><linearGradient id="ihwqm5d" x1="6.242" x2="6.242" y1="24.977" y2="24.211" gradientUnits="userSpaceOnUse"><stop class="c_d3xsq7a"/><stop offset="1" class="lkd-90bhe"/></linearGradient><linearGradient id="io2dp0c" x1="9.833" x2="11.082" y1="10.616" y2="10.616" gradientUnits="userSpaceOnUse"><stop class="zlve4xbhd"/><stop offset="1" class="mk0kxp2ew"/></linearGradient><linearGradient id="if5EZde" x1="12.278" x2="11.732" y1="11.598" y2="10.954" gradientUnits="userSpaceOnUse"><stop class="zq7du-bdj"/><stop offset="1" class="nw_qsv-ec"/></linearGradient><linearGradient id="iyZhhQc" x1="11.531" x2="11.531" y1="7.235" y2="7.375" gradientUnits="userSpaceOnUse"><stop class="xvg0squwb"/><stop offset="1" class="o3xwhwsse"/></linearGradient><linearGradient id="ikMLu1b" x1="9.492" x2="26.43" y1="20.993" y2="20.993" gradientUnits="userSpaceOnUse"><stop class="tniejuz7g"/><stop offset="1" class="mt-6s8beo"/></linearGradient><linearGradient id="i8l3Iuj" x1="9.969" x2="16.606" y1="28.505" y2="18.939" gradientUnits="userSpaceOnUse"><stop class="i6p-dub2h"/><stop offset="1" class="sqabk-b9d"/></linearGradient><linearGradient id="iNheFyQ" x1="26.929" x2="26.348" y1="23.764" y2="23.764" gradientUnits="userSpaceOnUse"><stop class="pv7n3io0c"/><stop offset="1" class="uliagebas"/></linearGradient><linearGradient id="iv8J0Zd" x1="20.927" x2="20.537" y1="11.209" y2="11.599" gradientUnits="userSpaceOnUse"><stop class="t7pzc9bko"/><stop offset="1" class="rakas7bcy"/></linearGradient><linearGradient id="iJOpvwe" x1="8.723" x2="9.341" y1="25.702" y2="25.702" gradientUnits="userSpaceOnUse"><stop class="q3hfn2asc"/><stop offset="1" class="rh7pjiozr"/></linearGradient><linearGradient id="imHFvud" x1="14.057" x2="14.057" y1="18.585" y2="28.032" gradientUnits="userSpaceOnUse"><stop class="vnara5bda"/><stop offset="1" class="bx90284fu"/></linearGradient><linearGradient id="iFE1y9q" x1="19.96" x2="25.275" y1="23.556" y2="18.259" gradientUnits="userSpaceOnUse"><stop class="joxkjnbrh"/><stop offset="1" class="ltv62lbpd"/></linearGradient><linearGradient id="i6K7VzX" x1="22.423" x2="22.423" y1="23.493" y2="22.524" gradientUnits="userSpaceOnUse"><stop class="d3e5ejb3h"/><stop offset="1" class="t14pfjqht"/></linearGradient><linearGradient id="ivtJcny" x1="19.96" x2="20.949" y1="21.932" y2="21.932" gradientUnits="userSpaceOnUse"><stop class="e2etblb5i"/><stop offset="1" class="o_i1ny-qt"/></linearGradient><linearGradient id="iu2wjcb" x1="20.705" x2="21.368" y1="17.397" y2="19.385" gradientUnits="userSpaceOnUse"><stop class="j1zlpsbpa"/><stop offset="1" class="cl26vbbfz"/></linearGradient><linearGradient id="i8GEhxb" x1="11.47" x2="17.973" y1="23.743" y2="23.701" gradientUnits="userSpaceOnUse"><stop class="c0ag3-bmb"/><stop offset="1" class="ujxwohptv"/></linearGradient><linearGradient id="iQf2Hdd" x1="17.855" x2="17.855" y1="6.012" y2="18.585" gradientUnits="userSpaceOnUse"><stop class="alduh6bry"/><stop offset="1" class="rpggkhbuy"/></linearGradient><linearGradient id="ivRmMic" x1="10.851" x2="18.438" y1="28.033" y2="28.033" gradientUnits="userSpaceOnUse"><stop class="ibux5fbxv"/><stop offset="1" class="w_5a8mv2g"/></linearGradient><linearGradient id="i9T3tye" x1="10.497" x2="11.463" y1="28.033" y2="28.033" gradientUnits="userSpaceOnUse"><stop class="hx6t6eb3x"/><stop offset="1" class="xyd7gvbgv"/></linearGradient><linearGradient id="ig7Zahc" x1="18.733" x2="17.836" y1="27.557" y2="28.033" gradientUnits="userSpaceOnUse"><stop class="h7id9xbgp"/><stop offset="1" class="uwl25k4xr"/></linearGradient><linearGradient id="iBqcDFe" x1="16" x2="16" y1="30.583" y2="29.04" gradientUnits="userSpaceOnUse"><stop offset=".107" class="d3-igac1w"/><stop offset="1" class="i_lfkbcly"/></linearGradient><linearGradient id="iuppaid" x1="23.04" x2="23.04" y1="30.654" y2="28.592" gradientUnits="userSpaceOnUse"><stop class="hw5_rcbgc"/><stop offset="1" class="nu-_8vbpz"/></linearGradient><linearGradient id="iP7EGUP" x1="17.712" x2="29.221" y1="6.651" y2="18.501" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="ilpQXWk" x1="18.371" x2="6.862" y1="6.651" y2="18.501" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><filter id="imMDiSb" width="10.915" height="14.713" x="3.074" y="10.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.592157 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6052"/></filter><filter id="iH8cFMb" width="6.472" height="7.033" x="2.655" y="18.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".5"/></filter><filter id="iy1I4Dc" width="6.848" height="6.657" x="3.407" y="13.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".5"/></filter><filter id="iLwVz9d" width="6.831" height="10.448" x="10.642" y="18.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".25"/></filter><filter id="iE55umb" width="9.101" height="1.951" x="9.79" y="26.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".25"/></filter><filter id="iK6oIDr" width="5.425" height="5.425" x="19.46" y="18.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.47451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6052"/></filter><filter id="iWnKIEb" width="6.953" height="8.956" x="11.27" y="18.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.188235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6052"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6052" result="effect2_innerShadow_18_6052"/></filter><filter id="ir71BPk" width="1.237" height="1.237" x="15.726" y="22.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".075"/></filter><filter id="i07EmOc" width="1.146" height=".946" x="15.892" y="22.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.482353 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6052"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.184314 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6052" result="effect2_innerShadow_18_6052"/></filter><filter id="ioPxixe" width="28.348" height="2.016" x="2.076" y="28.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.545098 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6052"/></filter><filter id="i2zc61b" width="8.172" height="6.152" x="19.96" y="24.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.564706 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6052"/></filter><filter id="i82bs8d" width="12.23" height="12.066" x="17.291" y="6.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".3"/></filter><filter id="i7VIJQd" width="12.23" height="12.066" x="6.561" y="6.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".3"/></filter><filter id="it7T1EU" width="3.828" height="4.063" x="20.179" y="26.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6052" stdDeviation=".375"/></filter><radialGradient id="iym1FAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.81682 -2.62539 0 10.204 9.57)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="s1v6coynz"/><stop offset="1" class="p25jjub6d"/></radialGradient><radialGradient id="itcIM6b" cx="0" cy="0" r="1" gradientTransform="matrix(3.98289 -.7388 1.23623 6.66453 5.017 22.274)" gradientUnits="userSpaceOnUse"><stop class="ejolebc2e"/><stop offset="1" class="pr8tgmbaa"/></radialGradient><radialGradient id="iCb7Ebb" cx="0" cy="0" r="1" gradientTransform="matrix(3.01153 -.52625 .88784 5.08076 5.312 16.436)" gradientUnits="userSpaceOnUse"><stop class="lb9rbetmo"/><stop offset="1" class="zazd7bbet"/></radialGradient><radialGradient id="iwYzzCL" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.83317 -1.9031 0 12.62 7.765)" gradientUnits="userSpaceOnUse"><stop class="olcdc20km"/><stop offset="1" class="h1je16bkl"/></radialGradient><radialGradient id="iLOE34c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06764 0 0 -.44445 13.374 7.436)" gradientUnits="userSpaceOnUse"><stop class="o_1pjbcxb"/><stop offset="1" class="y3_h8dezk"/></radialGradient><radialGradient id="iz1Jh9b" cx="0" cy="0" r="1" gradientTransform="rotate(-117.235 19.026 7.176)scale(3.17675 3.84262)" gradientUnits="userSpaceOnUse"><stop class="ivc3auy3b"/><stop offset="1" class="pq25vebpj"/></radialGradient><radialGradient id="iL6IcTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.96174 -.83806 0 27.143 16.07)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="kt2r_rbsm"/><stop offset="1" class="ixipe2brm"/></radialGradient><radialGradient id="ip5y6jb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1875 1.5147 -1.91085 -1.49808 20.774 29.04)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="r38az7bef"/><stop offset="1" class="bbq4fsb5d"/></radialGradient><radialGradient id="idTq6Eb" cx="0" cy="0" r="1" gradientTransform="rotate(147.147 10.873 18.282)scale(3.34109 5.47856)" gradientUnits="userSpaceOnUse"><stop class="rizlppb6v"/><stop offset="1" class="j511vwbtt"/></radialGradient><radialGradient id="ifp6E5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36256 -6.3769 2.90477 -1.07618 25.028 33.022)" gradientUnits="userSpaceOnUse"><stop class="v6xq5oj1z"/><stop offset="1" class="pv_zrhbhj"/></radialGradient><radialGradient id="isVO3jc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.97354 4.64827 -6.2916 -8.0854 26.046 26.184)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="pv_zrhbhj"/><stop offset=".966" class="v6xq5oj1z"/></radialGradient><radialGradient id="ibNTXKe" cx="0" cy="0" r="1" gradientTransform="rotate(148.884 10.26 16.632)scale(4.31431 4.10712)" gradientUnits="userSpaceOnUse"><stop class="f2hgsjbqb"/><stop offset="1" class="wkn48ebdp"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:house-with-garden" /></template>
<style>
.alduh6bry {
  stop-color: var(--svg-color--ea6d2e, #EA6D2E);
}

.b0-ikxjbv {
  fill: var(--svg-color--895d56, #895D56);
  d: path("M16.466 23.158a.473.473 0 1 0 0-.946a.473.473 0 0 0 0 .946");
}

.bbq4fsb5d {
  stop-color: var(--svg-color--228051, #228051);
  stop-opacity: 0;
}

.bgphk3ngz {
  stop-color: var(--svg-color--227341, #227341);
}

.bll-m7ilq {
  fill: var(--svg-color--62393d, #62393D);
  d: path("M16.344 23.229a.468.468 0 1 0 0-.937a.468.468 0 0 0 0 .937");
}

.bx90284fu {
  stop-color: var(--svg-color--6d4d2f, #6D4D2F);
}

.c_d3xsq7a {
  stop-color: var(--svg-color--4e7978, #4E7978);
}

.c0ag3-bmb {
  stop-color: var(--svg-color--70504d, #70504D);
}

.cl26vbbfz {
  stop-color: var(--svg-color--43b3f2, #43B3F2);
  stop-opacity: 0;
}

.d3-igac1w {
  stop-color: var(--svg-color--3fd17b, #3FD17B);
}

.d3e5ejb3h {
  stop-color: var(--svg-color--1e9fe4, #1E9FE4);
}

.da1wtdbyp {
  d: path("M10.633 27.832a.75.75 0 0 1 .75-.75h6.6a.75.75 0 0 1 .75.75v.2h-8.1z");
}

.dl4foo5wf {
  cx: 6.831px;
  cy: 16.36px;
  rx: 2.112px;
  ry: 2.614px;
}

.dr1kg0txw {
  cx: 5.891px;
  cy: 21.869px;
  rx: 2.126px;
  ry: 2.609px;
}

.e2etblb5i {
  stop-color: var(--svg-color--48e0ff, #48E0FF);
}

.egcighbqt {
  d: path("M25.897 30.048a3.075 3.075 0 0 0 2.036-2.88c0-1.697-1.397-3.072-3.119-3.072a3.13 3.13 0 0 0-2.552 1.305c-.345.483-.844.876-1.342 1.198a2.08 2.08 0 0 0-.96 1.75c0 .7.348 1.32.883 1.7z");
}

.ejolebc2e {
  stop-color: var(--svg-color--279d5a, #279D5A);
}

.erjxitbgr {
  d: path("M24.182 23.184h-3.518a.703.703 0 0 1-.704-.704v-3.518c0-.395.321-.703.704-.703h3.517c.395 0 .704.32.704.703v3.518a.696.696 0 0 1-.704.704");
}

.f2hgsjbqb {
  stop-color: var(--svg-color--60fb9a, #60FB9A);
}

.ft5dv1b6b {
  fill: none;
}

.gqxsk9_sr {
  fill: var(--svg-color--31b570, #31B570);
  d: path("M23.223 29.264a5.3 5.3 0 0 1-.994-2.128a.224.224 0 0 0-.294-.168l-.178.067a1.282 1.282 0 0 0 .454 2.482h.896c.127 0 .195-.154.116-.253");
}

.h1je16bkl {
  stop-color: var(--svg-color--dfa276, #DFA276);
}

.h7id9xbgp {
  stop-color: var(--svg-color--c8cac6, #C8CAC6);
}

.hw5_rcbgc {
  stop-color: var(--svg-color--3b8478, #3B8478);
}

.hx6t6eb3x {
  stop-color: var(--svg-color--59675c, #59675C);
}

.i_lfkbcly {
  stop-color: var(--svg-color--3fd17b, #3FD17B);
  stop-opacity: 0;
}

.i6p-dub2h {
  stop-color: var(--svg-color--ba8951, #BA8951);
}

.ibux5fbxv {
  stop-color: var(--svg-color--9fa1a3, #9FA1A3);
}

.ivc3auy3b {
  stop-color: var(--svg-color--beab75, #BEAB75);
}

.ixipe2brm {
  stop-color: var(--svg-color--9e413e, #9E413E);
  stop-opacity: 0;
}

.j1zlpsbpa {
  stop-color: var(--svg-color--43b3f2, #43B3F2);
}

.j511vwbtt {
  stop-color: var(--svg-color--5cee92, #5CEE92);
  stop-opacity: 0;
}

.j870720pc {
  d: path("M16.973 28.033h-5.831v-8.297c0-.632.447-1.151.991-1.151h3.849c.544 0 .99.519.99 1.151z");
}

.joxkjnbrh {
  stop-color: var(--svg-color--4cccff, #4CCCFF);
}

.kt2r_rbsm {
  stop-color: var(--svg-color--9e413e, #9E413E);
}

.ktxdwvbvu {
  d: path("M2.076 30.048c0-1.113.902-2.015 2.015-2.015H27.91c1.113 0 2.015.902 2.015 2.015z");
}

.l9ggrvi-p {
  d: path("M29.295 16.852L18.595 6.31a1.02 1.02 0 0 0-1.44 0s-.01 0-.01.011L6.42 16.874a.99.99 0 0 0 0 1.417a1.03 1.03 0 0 0 1.44 0l9.833-9.688a.25.25 0 0 1 .351 0l9.8 9.654a1.02 1.02 0 0 0 1.44 0c.396-.397.407-1.02.01-1.405");
}

.lb9rbetmo {
  stop-color: var(--svg-color--2ea75b, #2EA75B);
}

.lkd-90bhe {
  stop-color: var(--svg-color--4e7978, #4E7978);
  stop-opacity: 0;
}

.lt46h0bvb {
  d: path("M12.008 16.558a3.312 3.312 0 0 0-1.531-6.25a3.314 3.314 0 0 0-3.223 2.542a1.11 1.11 0 0 1-.802.809a3.288 3.288 0 0 0-2.157 4.645a.86.86 0 0 1-.188.998A3.176 3.176 0 0 0 6.25 24.82h5.757z");
}

.ltv62lbpd {
  stop-color: var(--svg-color--3a9ee6, #3A9EE6);
}

.mk0kxp2ew {
  stop-color: var(--svg-color--8e694b, #8E694B);
  stop-opacity: 0;
}

.mt-6s8beo {
  stop-color: var(--svg-color--e8bc97, #E8BC97);
}

.nu-_8vbpz {
  stop-color: var(--svg-color--3b8478, #3B8478);
  stop-opacity: 0;
}

.nw_qsv-ec {
  stop-color: var(--svg-color--c77958, #C77958);
  stop-opacity: 0;
}

.o_1pjbcxb {
  stop-color: var(--svg-color--ffe9b1, #FFE9B1);
}

.o_i1ny-qt {
  stop-color: var(--svg-color--48e0ff, #48E0FF);
  stop-opacity: 0;
}

.o3xwhwsse {
  stop-color: var(--svg-color--d5ad80, #D5AD80);
  stop-opacity: 0;
}

.olcdc20km {
  stop-color: var(--svg-color--ffd1a3, #FFD1A3);
}

.p25jjub6d {
  stop-color: var(--svg-color--4db56f, #4DB56F);
  stop-opacity: 0;
}

.pq25vebpj {
  stop-color: var(--svg-color--beab75, #BEAB75);
  stop-opacity: 0;
}

.pr8tgmbaa {
  stop-color: var(--svg-color--279d5a, #279D5A);
  stop-opacity: 0;
}

.pv_zrhbhj {
  stop-color: var(--svg-color--2c785b, #2C785B);
  stop-opacity: 0;
}

.pv7n3io0c {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
}

.q3hfn2asc {
  stop-color: var(--svg-color--845f3d, #845F3D);
}

.r38az7bef {
  stop-color: var(--svg-color--228051, #228051);
}

.rakas7bcy {
  stop-color: var(--svg-color--b55852, #B55852);
  stop-opacity: 0;
}

.rh7pjiozr {
  stop-color: var(--svg-color--845f3d, #845F3D);
  stop-opacity: 0;
}

.rizlppb6v {
  stop-color: var(--svg-color--5cee92, #5CEE92);
}

.rpggkhbuy {
  stop-color: var(--svg-color--ca222b, #CA222B);
}

.s1v6coynz {
  stop-color: var(--svg-color--4db56f, #4DB56F);
}

.sg5p9ubuv {
  fill: var(--svg-color--3fd47b, #3FD47B);
  d: path("M2.076 30.048c0-1.113.902-2.015 2.015-2.015H27.91c1.113 0 2.015.902 2.015 2.015z");
}

.sh1a86b1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m18.042 6.815l10.73 10.566");
}

.sqabk-b9d {
  stop-color: var(--svg-color--ba8951, #BA8951);
  stop-opacity: 0;
}

.t14pfjqht {
  stop-color: var(--svg-color--1e9fe4, #1E9FE4);
  stop-opacity: 0;
}

.t2jdy5b2y {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M18.042 6.815L7.311 17.381");
}

.t7pzc9bko {
  stop-color: var(--svg-color--b55852, #B55852);
}

.tniejuz7g {
  stop-color: var(--svg-color--d7905f, #D7905F);
}

.tzd8tgalg {
  fill: var(--svg-color--68552b, #68552B);
  d: path("M10.29 27.434h8.1v.95h-8.1z");
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.ugvrppuhr {
  d: path("M17.973 27.082H11.47v-7.865c0-.6.498-1.091 1.105-1.091h4.292c.607 0 1.106.492 1.106 1.09z");
}

.ujxwohptv {
  stop-color: var(--svg-color--9b665e, #9B665E);
}

.uliagebas {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
  stop-opacity: 0;
}

.uwl25k4xr {
  stop-color: var(--svg-color--c8cac6, #C8CAC6);
  stop-opacity: 0;
}

.v6xq5oj1z {
  stop-color: var(--svg-color--2c785b, #2C785B);
}

.vkso9s2il {
  fill: var(--svg-color--2ead69, #2EAD69);
  d: path("M25.897 30.048a3.075 3.075 0 0 0 2.036-2.88c0-1.697-1.397-3.072-3.119-3.072a3.13 3.13 0 0 0-2.552 1.305c-.345.483-.844.876-1.342 1.198a2.08 2.08 0 0 0-.96 1.75c0 .7.348 1.32.883 1.7z");
}

.vnara5bda {
  stop-color: var(--svg-color--805139, #805139);
}

.vttv7fbef {
  stop-color: var(--svg-color--f24747, #F24747);
}

.w_5a8mv2g {
  stop-color: var(--svg-color--c4c1c7, #C4C1C7);
}

.wkn48ebdp {
  stop-color: var(--svg-color--60fb9a, #60FB9A);
  stop-opacity: 0;
}

.xm3w2fbrt {
  d: path("M26.93 28.033H8.833v-11.29l9.048-9.03l9.047 9.03z");
}

.xvg0squwb {
  stop-color: var(--svg-color--d5ad80, #D5AD80);
}

.xyd7gvbgv {
  stop-color: var(--svg-color--59675c, #59675C);
  stop-opacity: 0;
}

.y3_h8dezk {
  stop-color: var(--svg-color--ffe9b1, #FFE9B1);
  stop-opacity: 0;
}

.zazd7bbet {
  stop-color: var(--svg-color--2ea75b, #2EA75B);
  stop-opacity: 0;
}

.zlve4xbhd {
  stop-color: var(--svg-color--8e694b, #8E694B);
}

.zq7du-bdj {
  stop-color: var(--svg-color--c77958, #C77958);
}

.zrqhxnbki {
  d: path("M10.04 7.632a.35.35 0 0 1 .35-.35h2.284a.35.35 0 0 1 .35.35v8.282h-2.985z");
}

.zruu8o3cb {
  stop-color: var(--svg-color--29884d, #29884D);
}

</style>
