<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iK6KhGb)"><path fill="url(#idV156d)" class="n84f5-zlw"/></g><g filter="url(#iqfS4zH)"><path fill="url(#iXT5Hye)" class="cscgdab2w"/><path fill="url(#itvlYKc)" class="cscgdab2w"/></g><path fill="url(#iyz80Ec)" class="gqiidcbws"/><path fill="url(#igSJYxe)" class="gqiidcbws"/><g filter="url(#iR9xRzK)"><path fill="url(#i6JVzxe)" class="igp9ofjoe"/></g><path fill="url(#iMnjkJd)" class="vhynypboj"/><path fill="url(#i5Xfg3R)" class="vhynypboj"/><path fill="url(#iriczYd)" class="vhynypboj"/><path fill="url(#izM5kld)" class="vhynypboj"/><g filter="url(#i8ZV5nd)"><path class="xpg952bxd"/><path fill="url(#iAlmELb)" class="fpzbso49g"/></g><g filter="url(#iDQqt7b)"><path fill="url(#ieW4ZUc)" class="t5g9rc8rf"/><path fill="url(#i8HNUie)" class="t5g9rc8rf"/><path fill="url(#i0j88lb)" class="t5g9rc8rf"/><path fill="url(#ifMhfab)" class="t5g9rc8rf"/><path fill="url(#iLMMWpe)" class="t5g9rc8rf"/><path fill="url(#i4ZuXKb)" class="t5g9rc8rf"/><path fill="url(#iCuBZfd)" class="t5g9rc8rf"/></g><path fill="url(#i0PugGx)" class="t5g9rc8rf"/><g filter="url(#iKXbjXn)"><path class="b-kfkccge"/></g><g filter="url(#iwgZbwe)"><path stroke="url(#i3fwE4c)" class="ovm4fz9bk"/></g><g filter="url(#iZOtahe)"><path class="grbc4cfiy"/></g><g filter="url(#iK9o1nd)"><path stroke="url(#irdXhCh)" class="a9mazdbzp"/></g><g filter="url(#is8qu4d)"><path stroke="url(#iKmwybb)" class="s_dkcrb9f"/></g><path fill="url(#iJV48CP)" class="mkp00ewzb"/><g filter="url(#iggTfsF)"><path fill="url(#iry89gc)" class="m5tb_kf8z"/><path fill="url(#iWcXd2B)" class="m5tb_kf8z"/><path fill="url(#iiLXlBc)" class="m5tb_kf8z"/><path fill="url(#i1Fz2mc)" class="m5tb_kf8z"/><path fill="url(#inhtbfe)" class="m5tb_kf8z"/><path fill="url(#iAut00c)" class="m5tb_kf8z"/></g><path class="zzwbldb1e"/><path fill="url(#ibQhW6T)" class="o0v3r5bmy"/><path class="s9p-zwrbm"/><g filter="url(#i5ktl4d)"><path class="o-bf9y82x"/><path fill="url(#iHXciZq)" class="lbav6vzde"/></g><g filter="url(#iqi1DOe)"><path fill="url(#iSb1xXb)" class="t22fi4biz"/></g><path class="tpbplcvwu"/><path fill="url(#iSEPMzd)" class="f00qs0b-f"/><path class="ltoj0umds"/><g filter="url(#ipnqhHe)"><path fill="url(#igDgXBe)" class="wacst-b2m"/></g><g filter="url(#iwP0Ssw)"><ellipse transform="rotate(-27.914 11.027 16.791)" class="s8yvf_his"/><ellipse fill="url(#i98dFwb)" transform="rotate(-27.914 11.027 16.791)" class="e6x5vbbok"/></g><g filter="url(#ier43Dz)"><path fill="url(#iI2iDud)" class="mj-mjpbko"/></g><g filter="url(#iaeA7Ib)"><path class="pgf6e852p"/><path fill="url(#iaojxNb)" class="v0h_8im1g"/><path fill="url(#ixDYE7c)" class="v0h_8im1g"/><path fill="url(#iof8OOc)" class="v0h_8im1g"/><path fill="url(#iHbZIde)" class="v0h_8im1g"/><path fill="url(#iwLYx4d)" class="v0h_8im1g"/></g><g filter="url(#i3lG3Md)"><path class="q38p_f6yh"/></g><g filter="url(#iRwrwAd)"><path stroke="url(#isdtrVD)" class="marsr6ypu"/></g><g filter="url(#i7347pd)"><path fill="url(#iAglThe)" class="mewlhkh5h"/></g><g filter="url(#iC9XbHb)"><rect fill="url(#iHB7g6b)" transform="rotate(3.302 26.657 13.999)" class="c7fvhv-bx"/></g><g filter="url(#iZM3scb)"><rect fill="url(#ipb0gcx)" transform="scale(-1 1)rotate(2.31 -336.193 -124.449)" class="aso1-lbeu"/></g><defs><radialGradient id="itvlYKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.5 -1.36374 0 26.989 20.984)" gradientUnits="userSpaceOnUse"><stop class="t5746lb4i"/><stop offset="1" class="mwtwv_b2o"/></radialGradient><radialGradient id="igSJYxe" cx="0" cy="0" r="1" gradientTransform="rotate(177.563 3.503 8.774)scale(4.41024 4.4422)" gradientUnits="userSpaceOnUse"><stop offset=".871" class="t_rh1hboe"/><stop offset="1" class="kqgb41brv"/></radialGradient><radialGradient id="i6JVzxe" cx="0" cy="0" r="1" gradientTransform="rotate(143.843 .365 9.845)scale(2.0127)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="afo2t7i-q"/><stop offset="1" class="am6rpvb4a"/></radialGradient><radialGradient id="iMnjkJd" cx="0" cy="0" r="1" gradientTransform="rotate(-43.409 36.551 -22.195)scale(4.77481 4.46833)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="rh4jrfbaa"/><stop offset=".862" class="z-bv-oxvq"/></radialGradient><radialGradient id="i5Xfg3R" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.336 21.133)scale(4.03125)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="hwxb5d_9d"/><stop offset="1" class="pty4jtb4p"/></radialGradient><radialGradient id="iriczYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24996 1.8125 -1.91141 -.2636 26.313 16.985)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="kctjs1b8o"/><stop offset="1" class="tggdw4bom"/></radialGradient><radialGradient id="izM5kld" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 .9453 -2.90303 -.9117 27.515 14.547)" gradientUnits="userSpaceOnUse"><stop class="bm7vou7ae"/><stop offset="1" class="vjqcfia8z"/></radialGradient><radialGradient id="iAlmELb" cx="0" cy="0" r="1" gradientTransform="rotate(91.255 4.959 20.906)scale(2.14114 1.84922)" gradientUnits="userSpaceOnUse"><stop offset=".564" class="s35hpeiun"/><stop offset="1" class="hvqc5_8wx"/></radialGradient><radialGradient id="ieW4ZUc" cx="0" cy="0" r="1" gradientTransform="matrix(-13.25 0 0 -14.629 22.969 17.567)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="g3c2qj6we"/><stop offset="1" class="fyv3-s07j"/></radialGradient><radialGradient id="i8HNUie" cx="0" cy="0" r="1" gradientTransform="scale(14.0937 14.76)rotate(90 .06 1.085)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="pvarcdbuv"/><stop offset="1" class="nc5tcfbln"/></radialGradient><radialGradient id="i0j88lb" cx="0" cy="0" r="1" gradientTransform="matrix(4.6875 -6.875 14.48665 9.87727 12.625 27.89)" gradientUnits="userSpaceOnUse"><stop class="ag1zz2jgo"/><stop offset="1" class="vvbjhdcqg"/></radialGradient><radialGradient id="ifMhfab" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 2.625 -1.76484 3.52969 17.344 8.504)" gradientUnits="userSpaceOnUse"><stop offset=".292" class="yd2u2ebxj"/><stop offset="1" class="rx4mm1p7b"/></radialGradient><radialGradient id="iLMMWpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.92982 2.72446 0 20.816 16.4)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="ncgi8ey9a"/><stop offset="1" class="qbvx72b3e"/></radialGradient><radialGradient id="i4ZuXKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4066 3.39756 0 11.349 16.423)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="syke_4bqt"/><stop offset="1" class="vlvzkbbli"/></radialGradient><radialGradient id="iCuBZfd" cx="0" cy="0" r="1" gradientTransform="rotate(54.678 -1.355 17.09)scale(3.13938 1.54467)" gradientUnits="userSpaceOnUse"><stop class="p8wxdabxq"/><stop offset="1" class="c4fgm1b9g"/></radialGradient><radialGradient id="i0PugGx" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.4755 -19.5285 0 17.521 14.97)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="cxq1u6gtz"/><stop offset=".963" class="ly6w9fiti"/></radialGradient><radialGradient id="iWcXd2B" cx="0" cy="0" r="1" gradientTransform="rotate(-64.14 14.01 -4.07)scale(3.97631 .96206)" gradientUnits="userSpaceOnUse"><stop class="q0d30yu1f"/><stop offset="1" class="chn55su5c"/></radialGradient><radialGradient id="iiLXlBc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 3.644 5.56)scale(1.5934 2.5542)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="i3jdubc3v"/><stop offset="1" class="ltu56dbfo"/></radialGradient><radialGradient id="i1Fz2mc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.25003 -8.31247 3.74065 -2.81254 6.875 12.64)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="fp4-9_bbl"/><stop offset="1" class="llx_l6b2w"/></radialGradient><radialGradient id="inhtbfe" cx="0" cy="0" r="1" gradientTransform="rotate(-152.7 14.123 -.51)scale(5.45086 1.22812)" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></radialGradient><radialGradient id="iAut00c" cx="0" cy="0" r="1" gradientTransform="matrix(4.0625 .375 -.11476 1.24322 20.563 4.422)" gradientUnits="userSpaceOnUse"><stop class="ysl_u5bjy"/><stop offset="1" class="lxhfm0bgl"/></radialGradient><radialGradient id="ibQhW6T" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80763 -2.87524 0 20.315 16.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="gmv2megzv"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="rdnstubca"/></radialGradient><radialGradient id="iHXciZq" cx="0" cy="0" r="1" gradientTransform="matrix(-.51672 -.66586 .91673 -.7114 19.806 17.186)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSEPMzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80073 -2.86427 0 11.63 17.004)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="gmv2megzv"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="rdnstubca"/></radialGradient><radialGradient id="i98dFwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01717 -1.09657 1.31812 -.02064 10.994 17.49)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaojxNb" cx="0" cy="0" r="1" gradientTransform="matrix(.8827 4.4066 -1.54781 .31005 16.833 18.076)" gradientUnits="userSpaceOnUse"><stop class="m2qxnw_1z"/><stop offset="1" class="xce4m4bva"/></radialGradient><radialGradient id="ixDYE7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36842 0 0 -.36842 16.807 20.472)" gradientUnits="userSpaceOnUse"><stop class="tug0m0bta"/><stop offset="1" class="uuuwecb0o"/></radialGradient><radialGradient id="iHbZIde" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.6875 -6.12314 0 16.125 18.14)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="mso7nhtgw"/><stop offset="1" class="gz9ldr7cw"/></radialGradient><radialGradient id="iAglThe" cx="0" cy="0" r="1" gradientTransform="rotate(66.71 5.946 19.085)scale(5.13737 18.2387)" gradientUnits="userSpaceOnUse"><stop class="oju6c_bmm"/><stop offset="1" class="t39rzsbyn"/></radialGradient><filter id="iK6KhGb" width="5.56" height="7.75" x="4.969" y="20.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.270588 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3607"/></filter><filter id="iqfS4zH" width="5.56" height="8.25" x="21.679" y="19.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0784314 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3607"/></filter><filter id="iR9xRzK" width="4.625" height="4.625" x="4.156" y="15.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".125"/></filter><filter id="i8ZV5nd" width="4.5" height="4.5" x="23.219" y="15.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".125"/></filter><filter id="iDQqt7b" width="22.388" height="26" x="5.306" y="3.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.65098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3607" result="effect2_innerShadow_4002_3607"/></filter><filter id="iKXbjXn" width="3.72" height="1.592" x="9.189" y="12.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.117647 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3607"/></filter><filter id="iwgZbwe" width="3.22" height="1.042" x="9.344" y="13.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".125"/></filter><filter id="iZOtahe" width="3.72" height="1.592" x="19.299" y="12.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.117647 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3607"/></filter><filter id="iK9o1nd" width="3.22" height="1.042" x="19.424" y="13.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".125"/></filter><filter id="is8qu4d" width="7.502" height="2.901" x="12.218" y="21.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".05"/></filter><filter id="iggTfsF" width="26" height="16.75" x="3.094" y="1.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.101961 0 0 0 0 0.0431373 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0352941 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3607" result="effect2_innerShadow_4002_3607"/></filter><filter id="i5ktl4d" width="1.507" height="1.306" x="18.802" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".05"/></filter><filter id="iqi1DOe" width="1.494" height="1.544" x="20.796" y="16.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".1"/></filter><filter id="ipnqhHe" width="1.701" height="1.821" x="11.933" y="16.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".1"/></filter><filter id="iwP0Ssw" width="1.783" height="1.32" x="10.136" y="16.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".05"/></filter><filter id="ier43Dz" width="4.857" height="5.91" x="13.249" y="17.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".3"/></filter><filter id="iaeA7Ib" width="3.897" height="4.9" x="14.019" y="17.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".1"/></filter><filter id="i3lG3Md" width="7.544" height="2.763" x="17.463" y="3.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".3"/></filter><filter id="iRwrwAd" width="3.613" height="5.144" x="11.926" y="5.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".2"/></filter><filter id="i7347pd" width="12.937" height="7.417" x="13.965" y="3.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".75"/></filter><filter id="iC9XbHb" width="1.131" height="3.652" x="26.238" y="13.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".125"/></filter><filter id="iZM3scb" width=".969" height="4.298" x="4.716" y="13.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3607" stdDeviation=".125"/></filter><linearGradient id="idV156d" x1="7.624" x2="7.624" y1="20.098" y2="27.848" gradientUnits="userSpaceOnUse"><stop class="llmb719iq"/><stop offset="1" class="a_mom71mo"/></linearGradient><linearGradient id="iXT5Hye" x1="24.334" x2="24.334" y1="19.703" y2="27.848" gradientUnits="userSpaceOnUse"><stop class="bzc3ant0w"/><stop offset="1" class="igqnw3w5s"/></linearGradient><linearGradient id="iyz80Ec" x1="4" x2="6.469" y1="15.953" y2="19.922" gradientUnits="userSpaceOnUse"><stop class="ko-und01s"/><stop offset="1" class="uuq28ubib"/></linearGradient><linearGradient id="i3fwE4c" x1="12.279" x2="8.873" y1="13.958" y2="13.678" gradientUnits="userSpaceOnUse"><stop class="car3btb1d"/><stop offset="1" class="jsyw4i05b"/></linearGradient><linearGradient id="irdXhCh" x1="22.359" x2="18.953" y1="13.906" y2="13.626" gradientUnits="userSpaceOnUse"><stop class="car3btb1d"/><stop offset="1" class="jsyw4i05b"/></linearGradient><linearGradient id="iKmwybb" x1="13.702" x2="14.561" y1="24.191" y2="22.77" gradientUnits="userSpaceOnUse"><stop offset=".224" class="c0dmimbkh"/><stop offset=".51" class="f5qee8-wa"/></linearGradient><linearGradient id="iJV48CP" x1="13.875" x2="19.469" y1="24.391" y2="22.797" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="iazz9lb4s"/></linearGradient><linearGradient id="iry89gc" x1="11.219" x2="27.25" y1="14.453" y2="6.078" gradientUnits="userSpaceOnUse"><stop class="srk4qcc8w"/><stop offset="1" class="xsgkrbcbf"/></linearGradient><linearGradient id="iSb1xXb" x1="22.048" x2="21.349" y1="17.118" y2="17.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igDgXBe" x1="13.28" x2="12.584" y1="17.123" y2="17.552" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iI2iDud" x1="15.775" x2="15.355" y1="17.629" y2="22.328" gradientUnits="userSpaceOnUse"><stop class="tx1b2ez5i"/><stop offset="1" class="fx860actu"/></linearGradient><linearGradient id="iof8OOc" x1="13.737" x2="15.246" y1="19.893" y2="20.174" gradientUnits="userSpaceOnUse"><stop class="qbe_zlbft"/><stop offset="1" class="ie442fb6r"/></linearGradient><linearGradient id="iwLYx4d" x1="15.609" x2="15.967" y1="17.328" y2="18.297" gradientUnits="userSpaceOnUse"><stop class="dsjamub1l"/><stop offset="1" class="td4fdrbgb"/></linearGradient><linearGradient id="isdtrVD" x1="12.655" x2="15.608" y1="6.813" y2="10.563" gradientUnits="userSpaceOnUse"><stop class="sivog3tbh"/><stop offset="1" class="e-u8rac0c"/></linearGradient><linearGradient id="iHB7g6b" x1="27.169" x2="27.167" y1="16.969" y2="12.392" gradientUnits="userSpaceOnUse"><stop class="oequmbcil"/><stop offset="1" class="rmar7zbjy"/></linearGradient><linearGradient id="ipb0gcx" x1=".354" x2=".351" y1="3.577" y2="-1.935" gradientUnits="userSpaceOnUse"><stop offset=".385" class="kxsfm8nnr"/><stop offset="1" class="f46lsccka"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:child-light" /></template>
<style>
.a_mom71mo {
  stop-color: var(--svg-color--18111d, #18111D);
}

.a9mazdbzp {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.269 13.772c-.59-.21-1.41-.36-2.47-.26");
}

.afo2t7i-q {
  stop-color: var(--svg-color--b87c6d, #B87C6D);
}

.ag1zz2jgo {
  stop-color: var(--svg-color--bf838f, #BF838F);
}

.am6rpvb4a {
  stop-color: var(--svg-color--c88e80, #C88E80);
}

.aso1-lbeu {
  width: 0.329px;
  height: 3.8px;
  rx: 0.165px;
}

.b-kfkccge {
  stroke: var(--svg-color--111, #111);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.689 13.918c.59-.21 1.41-.36 2.47-.26");
}

.bm7vou7ae {
  stop-color: var(--svg-color--c3977a, #C3977A);
}

.bzc3ant0w {
  stop-color: var(--svg-color--422f33, #422F33);
}

.c0dmimbkh {
  stop-color: var(--svg-color--c28a8e, #C28A8E);
}

.c4fgm1b9g {
  stop-color: var(--svg-color--a26f61, #A26F61);
  stop-opacity: 0;
}

.c7fvhv-bx {
  width: 0.477px;
  height: 3.156px;
  x: 26.657px;
  y: 13.999px;
  rx: 0.238px;
}

.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.chn55su5c {
  stop-color: var(--svg-color--2c242a, #2C242A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cscgdab2w {
  d: path("M21.679 27.848h1.05c2.35 0 4.26-1.91 4.26-4.26v-3.49h-5.3v7.75z");
}

.cxq1u6gtz {
  stop-color: var(--svg-color--bb7f90, #BB7F90);
  stop-opacity: 0;
}

.dsjamub1l {
  stop-color: var(--svg-color--f0c5b1, #F0C5B1);
}

.e-u8rac0c {
  stop-color: var(--svg-color--403637, #403637);
  stop-opacity: 0;
}

.e6x5vbbok {
  cx: 11.027px;
  cy: 16.791px;
  rx: 0.865px;
  ry: 0.438px;
}

.f00qs0b-f {
  d: path("M11.625 15.945a1.98 1.98 0 0 0-1.909 2.503h3.827a2 2 0 0 0 .072-.522a1.994 1.994 0 0 0-1.99-1.98");
}

.f46lsccka {
  stop-color: var(--svg-color--362c2a, #362C2A);
  stop-opacity: 0;
}

.f5qee8-wa {
  stop-color: var(--svg-color--c28a8e, #C28A8E);
  stop-opacity: 0;
}

.fp4-9_bbl {
  stop-color: var(--svg-color--4e413c, #4E413C);
}

.fpzbso49g {
  d: path("M25.469 19.578a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.ft5dv1b6b {
  fill: none;
}

.fx860actu {
  stop-color: var(--svg-color--cf918f, #CF918F);
}

.fyv3-s07j {
  stop-color: var(--svg-color--dfab9f, #DFAB9F);
}

.g3c2qj6we {
  stop-color: var(--svg-color--ffddc0, #FFDDC0);
}

.gmv2megzv {
  stop-color: var(--svg-color--7f594c, #7F594C);
}

.gqiidcbws {
  d: path("M6.469 20.828a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.grbc4cfiy {
  stroke: var(--svg-color--111, #111);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.269 13.918c-.59-.21-1.41-.36-2.47-.26");
}

.gz9ldr7cw {
  stop-color: var(--svg-color--d19193, #D19193);
}

.hvqc5_8wx {
  stop-color: var(--svg-color--dba084, #DBA084);
  stop-opacity: 0;
}

.hwxb5d_9d {
  stop-color: var(--svg-color--d59d93, #D59D93);
  stop-opacity: 0;
}

.i3jdubc3v {
  stop-color: var(--svg-color--454243, #454243);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ie442fb6r {
  stop-color: var(--svg-color--dea791, #DEA791);
  stop-opacity: 0;
}

.igp9ofjoe {
  d: path("M6.469 19.64a2.062 2.062 0 1 0 0-4.124a2.062 2.062 0 0 0 0 4.125");
}

.igqnw3w5s {
  stop-color: var(--svg-color--2e232c, #2E232C);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jsyw4i05b {
  stop-color: var(--svg-color--323232, #323232);
  stop-opacity: 0;
}

.kctjs1b8o {
  stop-color: var(--svg-color--d9a48b, #D9A48B);
}

.ko-und01s {
  stop-color: var(--svg-color--bb8875, #BB8875);
}

.kqgb41brv {
  stop-color: var(--svg-color--eab19a, #EAB19A);
}

.kxsfm8nnr {
  stop-color: var(--svg-color--362c2a, #362C2A);
}

.lbav6vzde {
  d: path("M20.173 16.356c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llmb719iq {
  stop-color: var(--svg-color--1c181b, #1C181B);
}

.llx_l6b2w {
  stop-color: var(--svg-color--4e413c, #4E413C);
  stop-opacity: 0;
}

.ltoj0umds {
  fill: var(--svg-color--000, #000);
  d: path("M12.76 17.926a1.13 1.13 0 0 0-1.135-1.135a1.13 1.13 0 0 0-1.134 1.135c0 .189.045.369.126.522h2.007c.082-.153.135-.333.135-.522");
}

.ltu56dbfo {
  stop-color: var(--svg-color--454243, #454243);
  stop-opacity: 0;
}

.lxhfm0bgl {
  stop-color: var(--svg-color--433d3f, #433D3F);
  stop-opacity: 0;
}

.ly6w9fiti {
  stop-color: var(--svg-color--bb7f90, #BB7F90);
}

.m2qxnw_1z {
  stop-color: var(--svg-color--ffddc3, #FFDDC3);
}

.m5tb_kf8z {
  d: path("M27.114 4.612a.93.93 0 0 1-.88 1.221h-.463c-.105 0-.14.141-.047.19a6.36 6.36 0 0 1 3.37 5.657v1.873c0 .71-.58 1.291-1.29 1.291h-.29a.25.25 0 0 0-.25.24l-.01.281l-.06 1.482c-.02.55-.47.981-1.02.981l.12-3.674a2.233 2.233 0 0 0-2.23-2.313h-5.17a6.8 6.8 0 0 1-5.628-2.991c-.05-.074-.168-.054-.193.032a4.1 4.1 0 0 1-3.93 2.959h-1.24a2.01 2.01 0 0 0-2.01 2.062c.036 1.309.097 2.613.142 3.921c-.55 0-1.021-.426-1.041-.977l-.062-1.678a.25.25 0 0 0-.25-.24h-.338c-.845 0-1.25-.7-1.25-1.546v-2.904a6.525 6.525 0 0 1 6.52-6.528c.291 0 .53-.222.623-.498a2.365 2.365 0 0 1 2.237-1.625h10.83c1.78 0 3.3 1.172 3.81 2.784");
}

.map3_rs3n {
  stop-color: var(--svg-color--4e4649, #4E4649);
}

.marsr6ypu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.451 6.031c.198.792.988 2.719 2.563 4.094");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mewlhkh5h {
  d: path("M18.848 5.487c-2.284 1.043-3.207 2.995-3.383 3.841c.599-.2 2.375-.606 4.686-.634s3.877.411 4.37.634l.881-3.84c-1.233-.436-4.27-1.044-6.554 0");
}

.mj-mjpbko {
  d: path("M17.432 20.78a.76.76 0 0 1-.095.806a2.04 2.04 0 0 1-3.394-.303a.76.76 0 0 1 .05-.81l1.346-2.483a.66.66 0 0 1 1.207.108z");
}

.mkp00ewzb {
  d: path("M15.97 23.002a6.5 6.5 0 0 1-3.015-.733a.329.329 0 0 0-.43.472a4.1 4.1 0 0 0 3.446 1.887a4.1 4.1 0 0 0 3.445-1.887c.18-.281-.13-.622-.43-.472a6.35 6.35 0 0 1-3.015.733");
}

.mso7nhtgw {
  stop-color: var(--svg-color--d19193, #D19193);
  stop-opacity: 0;
}

.mwtwv_b2o {
  stop-color: var(--svg-color--333233, #333233);
  stop-opacity: 0;
}

.n84f5-zlw {
  d: path("M10.279 27.848h-1.05c-2.35 0-4.26-1.91-4.26-4.26v-3.49h5.3v7.75z");
}

.nc5tcfbln {
  stop-color: var(--svg-color--b47896, #B47896);
}

.ncgi8ey9a {
  stop-color: var(--svg-color--fabeac, #FABEAC);
}

.o-bf9y82x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.173 16.356c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.o0v3r5bmy {
  d: path("M20.32 15.936a1.988 1.988 0 0 1 1.915 2.512h-3.84a2 2 0 0 1-.073-.524c0-1.094.895-1.989 1.997-1.989");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oequmbcil {
  stop-color: var(--svg-color--3b3639, #3B3639);
}

.oju6c_bmm {
  stop-color: var(--svg-color--4d4749, #4D4749);
}

.ovm4fz9bk {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.719 13.824c.59-.21 1.41-.36 2.47-.26");
}

.p8wxdabxq {
  stop-color: var(--svg-color--a26f61, #A26F61);
}

.pgf6e852p {
  fill: var(--svg-color--f9c5ae, #F9C5AE);
  d: path("M17.614 20.182a.72.72 0 0 1-.022.773a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.021-.773l1.068-2.474a.63.63 0 0 1 1.156 0z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pty4jtb4p {
  stop-color: var(--svg-color--d59d93, #D59D93);
}

.pvarcdbuv {
  stop-color: var(--svg-color--b47896, #B47896);
  stop-opacity: 0;
}

.q0d30yu1f {
  stop-color: var(--svg-color--3e333b, #3E333B);
}

.q38p_f6yh {
  stroke: var(--svg-color--443e40, #443E40);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M24.281 5.828c-.843-.333-3.243-1.062-6.093-1.312");
}

.qbe_zlbft {
  stop-color: var(--svg-color--dea791, #DEA791);
}

.qbvx72b3e {
  stop-color: var(--svg-color--fabeac, #FABEAC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rdnstubca {
  stop-color: var(--svg-color--644844, #644844);
}

.rh4jrfbaa {
  stop-color: var(--svg-color--f2bba8, #F2BBA8);
}

.rmar7zbjy {
  stop-color: var(--svg-color--3b3639, #3B3639);
  stop-opacity: 0;
}

.rx4mm1p7b {
  stop-color: var(--svg-color--c38d7f, #C38D7F);
  stop-opacity: 0;
}

.s_dkcrb9f {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.479 22.782c.221-.347-.16-.764-.526-.58l-.002.001a6.3 6.3 0 0 1-2.98.724a6.4 6.4 0 0 1-2.98-.724a.404.404 0 0 0-.528.579l.063-.04l-.063.04a4.18 4.18 0 0 0 3.508 1.921a4.18 4.18 0 0 0 3.508-1.921Z");
}

.s35hpeiun {
  stop-color: var(--svg-color--dba084, #DBA084);
}

.s8yvf_his {
  cx: 11.027px;
  cy: 16.791px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.865px;
  ry: 0.438px;
}

.s9p-zwrbm {
  fill: var(--svg-color--000, #000);
  d: path("M19.18 17.924c0-.633.507-1.139 1.14-1.139s1.138.506 1.138 1.139c0 .19-.045.37-.127.524h-2.015a1.03 1.03 0 0 1-.136-.524");
}

.sivog3tbh {
  stop-color: var(--svg-color--403637, #403637);
}

.srk4qcc8w {
  stop-color: var(--svg-color--2b2b2c, #2B2B2C);
}

.syke_4bqt {
  stop-color: var(--svg-color--d0978f, #D0978F);
}

.t_rh1hboe {
  stop-color: var(--svg-color--eab19a, #EAB19A);
  stop-opacity: 0;
}

.t22fi4biz {
  d: path("M22.09 17.662a1.87 1.87 0 0 0-.515-1.03l-.58.635l.262.508z");
}

.t39rzsbyn {
  stop-color: var(--svg-color--4d4749, #4D4749);
  stop-opacity: 0;
}

.t5746lb4i {
  stop-color: var(--svg-color--333233, #333233);
}

.t5g9rc8rf {
  d: path("M13.493 3.889c-4.344 0-7.86 3.617-7.68 7.978l.306 8.238c.24 5.852 4.634 9.784 9.975 9.784s9.735-3.931 9.974-9.784l.37-8.21c.179-4.362-3.4-8.006-7.743-8.006z");
}

.td4fdrbgb {
  stop-color: var(--svg-color--f0c5b1, #F0C5B1);
  stop-opacity: 0;
}

.tggdw4bom {
  stop-color: var(--svg-color--d9a48b, #D9A48B);
  stop-opacity: 0;
}

.tpbplcvwu {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.166 15.342a3.1 3.1 0 0 0-3.007 2.35a.608.608 0 0 0 .594.756h4.952a.51.51 0 0 0 .504-.603a3.11 3.11 0 0 0-3.043-2.503");
}

.tug0m0bta {
  stop-color: var(--svg-color--ffd7c3, #FFD7C3);
}

.tx1b2ez5i {
  stop-color: var(--svg-color--d79e8f, #D79E8F);
}

.uuq28ubib {
  stop-color: var(--svg-color--c6877d, #C6877D);
}

.uuuwecb0o {
  stop-color: var(--svg-color--ffd7c3, #FFD7C3);
  stop-opacity: 0;
}

.v0h_8im1g {
  d: path("M17.614 20.182a.72.72 0 0 1-.022.773a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.021-.773l1.068-2.474a.63.63 0 0 1 1.156 0z");
}

.vhynypboj {
  d: path("M25.469 20.828a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.vjqcfia8z {
  stop-color: var(--svg-color--c3977a, #C3977A);
  stop-opacity: 0;
}

.vlvzkbbli {
  stop-color: var(--svg-color--d0978f, #D0978F);
  stop-opacity: 0;
}

.vvbjhdcqg {
  stop-color: var(--svg-color--bf838f, #BF838F);
  stop-opacity: 0;
}

.wacst-b2m {
  d: path("M13.435 17.693c0-.64-.52-1.067-.662-1.196l-.64.62l.394.801z");
}

.xce4m4bva {
  stop-color: var(--svg-color--ffddc3, #FFDDC3);
  stop-opacity: 0;
}

.xpg952bxd {
  fill: var(--svg-color--e8b19a, #E8B19A);
  d: path("M25.469 19.578a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.yd2u2ebxj {
  stop-color: var(--svg-color--c38d7f, #C38D7F);
}

.ymkmd4kjm {
  stop-color: var(--svg-color--4e4649, #4E4649);
  stop-opacity: 0;
}

.ysl_u5bjy {
  stop-color: var(--svg-color--433d3f, #433D3F);
}

.z-bv-oxvq {
  stop-color: var(--svg-color--ffd7c0, #FFD7C0);
}

.zzwbldb1e {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.78 15.33a3.11 3.11 0 0 1 3.019 2.359a.61.61 0 0 1-.597.76h-4.97a.513.513 0 0 1-.507-.606a3.114 3.114 0 0 1 3.055-2.513");
}

</style>
