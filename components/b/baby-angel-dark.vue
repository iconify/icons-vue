<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXkZvJD)"><path fill="url(#iBAAyXb)" class="supagvb8e"/><path fill="url(#iXzKLxO)" class="supagvb8e"/><path fill="url(#iMgR3jc)" class="supagvb8e"/><path fill="url(#imaWdXc)" class="supagvb8e"/><path fill="url(#iE53qfd)" class="supagvb8e"/><path fill="url(#iV9G0zc)" class="supagvb8e"/></g><path fill="url(#i3fNjDd)" class="supagvb8e"/><path class="n55r6jbfn"/><path fill="url(#i5WXbjp)" class="m3509-fun"/><path fill="url(#i2xADqb)" class="m3509-fun"/><path fill="url(#iWPrc4b)" class="m3509-fun"/><path fill="url(#iXhITfc)" class="m3509-fun"/><g filter="url(#iRmWrib)"><path class="cb8d3wr7z"/><path fill="url(#i8MjDSb)" class="bfq3a8bij"/><path fill="url(#i6lWiWc)" class="bfq3a8bij"/><path fill="url(#ijstj6d)" class="bfq3a8bij"/></g><g filter="url(#iZaQrab)"><path class="qkfc8pbqb"/><path fill="url(#iLeoLWc)" class="f9ktgbb3y"/><path fill="url(#iI5sZoL)" class="f9ktgbb3y"/><path fill="url(#iJ2pQrb)" class="f9ktgbb3y"/></g><g filter="url(#ivv9Yse)"><rect transform="matrix(-1 0 0 1 24.129 23.738)" class="ljzk3pb-v"/><rect fill="url(#ir52G6c)" transform="matrix(-1 0 0 1 24.129 23.738)" class="spx4avb5u"/></g><g filter="url(#ixLfHBW)"><path class="kvq6_-e8h"/><path fill="url(#ishF73y)" class="k3o3btb6u"/><path fill="url(#il62gBM)" class="k3o3btb6u"/></g><g filter="url(#iLDzOrb)"><path class="p0z-iacrr"/><path fill="url(#ixjXyKa)" class="zz-7yrklx"/><path fill="url(#iS6Xqld)" class="zz-7yrklx"/></g><path fill="url(#iXS1URc)" class="zz-7yrklx"/><g filter="url(#iVBswOd)"><path class="a_m6jqbkr"/><path class="erpp2bb9q"/><path fill="url(#i5g2eCb)" class="w67ysfbnv"/></g><path fill="url(#iGtm0ze)" class="w67ysfbnv"/><g filter="url(#iGNQUWb)"><rect fill="url(#ibi5ode)" class="w58rbbcmh"/><rect fill="url(#iOpFwlb)" class="w58rbbcmh"/></g><path fill="url(#imrfTcN)" class="vmq252bnf"/><path fill="url(#idBVune)" class="vmq252bnf"/><g filter="url(#iwsGHBe)"><path fill="url(#iZcxDsf)" class="km6m6cbfe"/></g><path fill="url(#iSkDbKe)" class="fhvehqbbs"/><path fill="url(#iObWOQd)" class="fhvehqbbs"/><path fill="url(#iUrRlVc)" class="fhvehqbbs"/><path fill="url(#iTxzY5d)" class="fhvehqbbs"/><g filter="url(#iP5dUac)"><path fill="url(#ioG6dBd)" class="jjaqfib2v"/></g><g filter="url(#iuiYCrb)"><path class="t3yx6e33e"/><path fill="url(#iacfoCc)" class="hrf4n-qjg"/><path fill="url(#i4S9KHQ)" class="hrf4n-qjg"/><path fill="url(#iPQ43Ed)" class="hrf4n-qjg"/><path fill="url(#i60cvBe)" class="hrf4n-qjg"/><path fill="url(#il7iVLd)" class="hrf4n-qjg"/></g><g filter="url(#iMwXNTd)"><path class="ilm110bkf"/></g><path stroke="url(#i0R0Xdc)" class="n2-3kmtlx"/><path class="czl2b-bpm"/><path fill="url(#ioOuhlR)" class="mb-hq_3bu"/><path fill="url(#ib1N0Kb)" class="yg5yzvips"/><path class="z6pg27wxm"/><g filter="url(#iPAQdUb)"><path class="ff3mybbqg"/></g><g filter="url(#i2Pjp5d)"><path stroke="url(#iTjtpfd)" class="mae-6ub-y"/></g><g filter="url(#iDne2qc)"><path class="asaqcxbwa"/></g><g filter="url(#iTLqfdb)"><path stroke="url(#iJduDjJ)" class="vp-vdhfeg"/></g><g filter="url(#iKXrrje)"><path fill="url(#iHSDLLb)" class="uunj1cc5z"/></g><g filter="url(#igCm1Me)"><path class="zvd0h7dvn"/><path fill="url(#i6Gce5c)" class="ipc410grf"/><path fill="url(#iTVZi5c)" class="ipc410grf"/><path fill="url(#ilasv7d)" class="ipc410grf"/><path fill="url(#i8DWP4d)" class="ipc410grf"/></g><g filter="url(#itNjx9l)"><path class="xys9--bzn"/></g><g filter="url(#i2MVL6b)"><path fill="url(#igGsBvc)" class="va3q0ub8j"/><path fill="url(#i6gTEme)" class="va3q0ub8j"/></g><g filter="url(#irNqBCe)"><path class="iccldcbrh"/><path fill="url(#iK9o5Pb)" class="ih7fn7ksh"/></g><g filter="url(#iKId2me)"><path fill="url(#i5oizfe)" class="e-hbjebbs"/></g><g filter="url(#iiRH1mo)"><path fill="url(#iwnFyUI)" class="eys72vr0c"/></g><g filter="url(#iN4ftde)"><ellipse transform="rotate(-27.914 10.968 19.589)" class="y-hwcqblh"/><ellipse fill="url(#isNrFBd)" transform="rotate(-27.914 10.968 19.589)" class="tjfu52b6y"/></g><g filter="url(#i033Jse)"><path fill="url(#i52nfCe)" class="mmkgihbhj"/></g><defs><radialGradient id="iBAAyXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75003 3.6875 -9.72121 -1.97727 20.936 3.293)" gradientUnits="userSpaceOnUse"><stop class="j4e9jliyw"/><stop offset="1" class="t7aapjj0e"/></radialGradient><radialGradient id="iXzKLxO" cx="0" cy="0" r="1" gradientTransform="rotate(-57.45 10.963 -4.149)scale(5.22735 10.6403)" gradientUnits="userSpaceOnUse"><stop class="v_ro-mcce"/><stop offset="1" class="ak0e0gbla"/></radialGradient><radialGradient id="iMgR3jc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.46875 -1.11569 1.02074 9.827 6.887)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="t82mlk1zf"/><stop offset="1" class="hrncwbz_t"/></radialGradient><radialGradient id="imaWdXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 -.98438 .58816 -.61616 10.327 7.34)" gradientUnits="userSpaceOnUse"><stop class="oxnp2k1qi"/><stop offset="1" class="ih62nvbvg"/></radialGradient><radialGradient id="iE53qfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 1.85939 -1.34213 -1.93987 23.265 7.684)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="i2to8tbny"/><stop offset="1" class="rr59_uoqr"/></radialGradient><radialGradient id="iV9G0zc" cx="0" cy="0" r="1" gradientTransform="rotate(144.605 10.248 6.892)scale(1.45673 1.05149)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="ohd-ppblk"/><stop offset="1" class="c62dirbjk"/></radialGradient><radialGradient id="i3fNjDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93752 -7.271 18.54198 -4.94092 11.718 9.751)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="op4ic3bzn"/><stop offset="1" class="uoj15rbmy"/></radialGradient><radialGradient id="i2xADqb" cx="0" cy="0" r="1" gradientTransform="matrix(.6072 2.64774 -4.70572 1.07914 25.39 27.538)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="iWPrc4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.52434 .60868 -.33593 -.28939 26.855 28.04)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="i6lWiWc" cx="0" cy="0" r="1" gradientTransform="matrix(.76907 2.71875 -5.8088 1.64318 26.538 25.434)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="ijstj6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.66412 .625 -.34814 -.36993 28.395 25.95)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iI5sZoL" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 2.71875 -6.83491 2.35687 27.733 23.34)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="m63xmacvx"/><stop offset=".922" class="ghrfdpdai"/></radialGradient><radialGradient id="iJ2pQrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80957 .625 -.33743 -.43707 29.996 23.855)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="ishF73y" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 1.73438 -1.37456 -.54486 8.812 28.512)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="y7rsoxb6i"/><stop offset="1" class="i8um3jglr"/></radialGradient><radialGradient id="il62gBM" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 -2.21094 5.39927 1.3355 6.765 30.137)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="bs3nz4btd"/><stop offset="1" class="qxhhvqurd"/></radialGradient><radialGradient id="ixjXyKa" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 2.25 -2.22312 -.80279 8.78 26.23)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="mjdwlzfcx"/><stop offset="1" class="cb_xa0byd"/></radialGradient><radialGradient id="iS6Xqld" cx="0" cy="0" r="1" gradientTransform="rotate(-69.661 23.023 9.986)scale(2.42119 7.08044)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="a-hxohb_j"/><stop offset="1" class="yi34m9bam"/></radialGradient><radialGradient id="iXS1URc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0827 3.1875 -5.20641 -1.76845 5.832 25.23)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="iGtm0ze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 3.46875 -6.65848 -2.33947 4.718 23.137)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="ibi5ode" cx="0" cy="0" r="1" gradientTransform="rotate(122.4 -2.432 16.414)scale(1.9246 3.13561)" gradientUnits="userSpaceOnUse"><stop class="uqd9t5bdt"/><stop offset="1" class="vsxpbmbdw"/></radialGradient><radialGradient id="idBVune" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00391 .4477 -.46555 -3.12367 7.22 20.587)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="dfgrzob2o"/><stop offset="1" class="a7g-75b1j"/></radialGradient><radialGradient id="iZcxDsf" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.684 13.903)scale(1.86672)" gradientUnits="userSpaceOnUse"><stop class="p4z5r-b-d"/><stop offset="1" class="dp-1ekdei"/></radialGradient><radialGradient id="iObWOQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0722 4.36145 -4.17978 -.0692 25.102 19.49)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="o3p45rbvx"/><stop offset="1" class="amvclhbwx"/></radialGradient><radialGradient id="iUrRlVc" cx="0" cy="0" r="1" gradientTransform="rotate(-48.351 35.063 -17.853)scale(2.57052 2.53657)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="qvuai0b6y"/><stop offset=".883" class="tbvggbbed"/></radialGradient><radialGradient id="iTxzY5d" cx="0" cy="0" r="1" gradientTransform="matrix(.75098 -3.52382 2.7672 .58973 25.279 21.41)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rwi7dob8k"/><stop offset="1" class="x4eddproi"/></radialGradient><radialGradient id="iPQ43Ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.27089 9.2428 -2.81815 .3875 6.172 20.413)" gradientUnits="userSpaceOnUse"><stop class="sz3vslbub"/><stop offset="1" class="il6zdacve"/></radialGradient><radialGradient id="i60cvBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.44419 -2.0652 2.60031 1.8184 20.73 19.402)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="ky2i9gfwu"/><stop offset="1" class="rjxs4hg5m"/></radialGradient><radialGradient id="il7iVLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.19867 -1.70415 2.39715 1.68612 11.602 18.926)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="tvui7dbha"/><stop offset="1" class="zlafz0bxq"/></radialGradient><radialGradient id="ioOuhlR" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84856 -2.94034 0 19.877 19.807)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="uyq-lepzm"/><stop offset="1" class="mbk9t98yd"/></radialGradient><radialGradient id="ib1N0Kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84856 -2.94034 0 11.586 19.807)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="uyq-lepzm"/><stop offset="1" class="mbk9t98yd"/></radialGradient><radialGradient id="i6Gce5c" cx="0" cy="0" r="1" gradientTransform="matrix(7.22942 -1.41042 1.1766 6.03097 12.209 8.225)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="stsoanbmy"/><stop offset="1" class="ovwdp-bik"/></radialGradient><radialGradient id="iTVZi5c" cx="0" cy="0" r="1" gradientTransform="matrix(5.66132 -2.484 2.39842 5.46627 12.209 8.716)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="ovwdp-bik"/><stop offset=".912" class="stsoanbmy"/></radialGradient><radialGradient id="ilasv7d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.36227 -5.22443 5.38631 -3.46645 16.58 9.905)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="aj460xbwf"/><stop offset="1" class="rfngthbki"/></radialGradient><radialGradient id="i8DWP4d" cx="0" cy="0" r="1" gradientTransform="matrix(2.83059 4.50588 -4.32783 2.71874 15.241 6.954)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="yjjmn1b0t"/><stop offset=".966" class="q4ez5acay"/></radialGradient><radialGradient id="igGsBvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.7619 .04333 -.0224 .91104 15.285 22.349)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="oy5ype34t"/><stop offset=".955" class="szge83bkx"/></radialGradient><radialGradient id="i6gTEme" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.31421 -1.65878 0 16 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="jotp8y14r"/><stop offset="1" class="zlgw_eb1n"/></radialGradient><radialGradient id="iK9o5Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-.52841 -.68093 .9375 -.7275 19.357 19.999)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isNrFBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01762 -1.1257 1.35313 -.02119 10.934 20.306)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iXkZvJD" width="17.94" height="7.94" x="7.011" y="1.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.596078 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iRmWrib" width="7.412" height="2.194" x="20.982" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iZaQrab" width="9.014" height="2.194" x="20.982" y="23.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="ivv9Yse" width="4.369" height="6.627" x="20.16" y="23.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.54902 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="ixLfHBW" width="6.273" height="2.439" x="4.645" y="27.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.541176 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iLDzOrb" width="7.813" height="2.494" x="3.105" y="25.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iVBswOd" width="9.414" height="2.494" x="1.504" y="23.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iGNQUWb" width="4.369" height="6.627" x="7.471" y="23.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.54902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iwsGHBe" width="4.233" height="4.233" x="5.103" y="18.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".125"/></filter><filter id="iP5dUac" width="4.348" height="4.348" x="22.607" y="18.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".125"/></filter><filter id="iuiYCrb" width="21.984" height="24.031" x="5.452" y="5.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.34902 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.4 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22266" result="effect2_innerShadow_3987_22266"/></filter><filter id="iMwXNTd" width="6.47" height="2.218" x="12.765" y="23.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iPAQdUb" width="3.533" height="1.57" x="9.473" y="15.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0313726 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="i2Pjp5d" width="2.983" height=".97" x="9.674" y="15.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".1"/></filter><filter id="iDne2qc" width="3.533" height="1.57" x="18.559" y="15.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0313726 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="iTLqfdb" width="2.983" height=".97" x="18.959" y="15.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".1"/></filter><filter id="iKXrrje" width="7.356" height="8.134" x="12.292" y="4.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".25"/></filter><filter id="igCm1Me" width="7.494" height="7.898" x="12.109" y="3.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0313726 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22266"/></filter><filter id="itNjx9l" width="3.439" height="2.482" x="14.158" y="21.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".25"/></filter><filter id="i2MVL6b" width="2.939" height="1.982" x="14.531" y="21.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".125"/></filter><filter id="irNqBCe" width="1.537" height="1.331" x="18.332" y="18.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".05"/></filter><filter id="iKId2me" width="1.519" height="1.57" x="20.374" y="19.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".1"/></filter><filter id="iiRH1mo" width="1.736" height="1.859" x="11.904" y="19.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".1"/></filter><filter id="iN4ftde" width="1.825" height="1.349" x="10.056" y="18.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation=".05"/></filter><filter id="i033Jse" width="12.934" height="11.81" x="14.361" y="6.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22266" stdDeviation="1.25"/></filter><linearGradient id="i5WXbjp" x1="24.585" x2="24.585" y1="30.188" y2="28.693" gradientUnits="userSpaceOnUse"><stop offset=".079" class="ja2ta5btn"/><stop offset="1" class="oci36vbzb"/></linearGradient><linearGradient id="iXhITfc" x1="24.436" x2="24.436" y1="27.926" y2="28.324" gradientUnits="userSpaceOnUse"><stop class="quz6sacji"/><stop offset="1" class="hw65_7bjg"/></linearGradient><linearGradient id="i8MjDSb" x1="25.518" x2="25.518" y1="27.926" y2="26.879" gradientUnits="userSpaceOnUse"><stop offset=".216" class="e6rsc3sik"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="iLeoLWc" x1="26.49" x2="26.49" y1="25.832" y2="24.785" gradientUnits="userSpaceOnUse"><stop offset=".216" class="rhghrobxp"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="ir52G6c" x1="0" x2=".958" y1="5.398" y2="5.398" gradientUnits="userSpaceOnUse"><stop class="lwh7ev7yo"/><stop offset="1" class="lesqr_bdp"/></linearGradient><linearGradient id="i5g2eCb" x1="6.461" x2="6.461" y1="23.738" y2="24.621" gradientUnits="userSpaceOnUse"><stop class="gjp7xwfce"/><stop offset="1" class="lo1zrhbvw"/></linearGradient><linearGradient id="iOpFwlb" x1="7.871" x2="9.124" y1="29.137" y2="29.137" gradientUnits="userSpaceOnUse"><stop class="gw5f7-xty"/><stop offset="1" class="v8imspx_m"/></linearGradient><linearGradient id="imrfTcN" x1="4.608" x2="7.219" y1="20.587" y2="20.356" gradientUnits="userSpaceOnUse"><stop class="cl9_9ccwm"/><stop offset="1" class="k1igulbhf"/></linearGradient><linearGradient id="iSkDbKe" x1="27.445" x2="25.058" y1="19.027" y2="22.898" gradientUnits="userSpaceOnUse"><stop class="hxeei7fsy"/><stop offset="1" class="trn388btv"/></linearGradient><linearGradient id="ioG6dBd" x1="25.91" x2="26.507" y1="21.655" y2="19.417" gradientUnits="userSpaceOnUse"><stop class="j_83df0sk"/><stop offset="1" class="ngd5fmf0i"/></linearGradient><linearGradient id="iacfoCc" x1="16.019" x2="16.019" y1="30.523" y2="24.284" gradientUnits="userSpaceOnUse"><stop class="zwtu7acdo"/><stop offset="1" class="tqbblz5ki"/></linearGradient><linearGradient id="i4S9KHQ" x1="9.35" x2="14.318" y1="21.858" y2="21.858" gradientUnits="userSpaceOnUse"><stop class="b8g00zlka"/><stop offset="1" class="wr31gnb3a"/></linearGradient><linearGradient id="i0R0Xdc" x1="13.841" x2="14.303" y1="25.425" y2="24.587" gradientUnits="userSpaceOnUse"><stop class="c62ncdc9p"/><stop offset="1" class="mo9bgo9qn"/></linearGradient><linearGradient id="iTjtpfd" x1="12.671" x2="9.74" y1="15.806" y2="16.184" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iJduDjJ" x1="21.956" x2="19.024" y1="15.758" y2="16.136" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iHSDLLb" x1="16.301" x2="15.341" y1="5.101" y2="12.027" gradientUnits="userSpaceOnUse"><stop class="s4p8h2blt"/><stop offset="1" class="q2fusinmo"/></linearGradient><linearGradient id="i5oizfe" x1="21.65" x2="20.935" y1="19.93" y2="20.37" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwnFyUI" x1="13.281" x2="12.566" y1="19.93" y2="20.37" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i52nfCe" x1="17.545" x2="26.506" y1="15.705" y2="10.304" gradientUnits="userSpaceOnUse"><stop class="v4hf23p3e"/><stop offset="1" class="td_i0pbtq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-angel-dark" /></template>
<style>
.a_m6jqbkr {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M2.004 24.237c0-.275.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.a-hxohb_j {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
  stop-opacity: 0;
}

.a7g-75b1j {
  stop-color: var(--svg-color--695752, #695752);
}

.aj460xbwf {
  stop-color: var(--svg-color--3e3431, #3E3431);
  stop-opacity: 0;
}

.ak0e0gbla {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
  stop-opacity: 0;
}

.amvclhbwx {
  stop-color: var(--svg-color--472d49, #472D49);
}

.asaqcxbwa {
  stroke: var(--svg-color--161515, #161515);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M21.592 16.27c-.545-.193-1.303-.332-2.283-.24");
}

.b8g00zlka {
  stop-color: var(--svg-color--402e2d, #402E2D);
}

.bfq3a8bij {
  d: path("M28.395 26.33a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.bs3nz4btd {
  stop-color: var(--svg-color--e7cbd8, #E7CBD8);
  stop-opacity: 0;
}

.c62dirbjk {
  stop-color: var(--svg-color--439fb2, #439FB2);
  stop-opacity: 0;
}

.c62ncdc9p {
  stop-color: var(--svg-color--6d6262, #6D6262);
}

.cb_xa0byd {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
  stop-opacity: 0;
}

.cb8d3wr7z {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M28.395 26.33a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl9_9ccwm {
  stop-color: var(--svg-color--382829, #382829);
}

.czl2b-bpm {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.353 18.1a3.18 3.18 0 0 1 3.087 2.413a.625.625 0 0 1-.61.777h-5.083a.524.524 0 0 1-.518-.62a3.185 3.185 0 0 1 3.124-2.57m-9.243 0a3.18 3.18 0 0 0-3.086 2.413a.625.625 0 0 0 .61.777h5.083a.524.524 0 0 0 .518-.62a3.19 3.19 0 0 0-3.124-2.57");
}

.dfgrzob2o {
  stop-color: var(--svg-color--695752, #695752);
  stop-opacity: 0;
}

.dp-1ekdei {
  stop-color: var(--svg-color--251215, #251215);
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.e-hbjebbs {
  d: path("M21.693 20.486a1.9 1.9 0 0 0-.527-1.055l-.592.65l.267.52z");
}

.e6rsc3sik {
  stop-color: var(--svg-color--c6bec8, #C6BEC8);
}

.erpp2bb9q {
  fill: var(--svg-color--f1d2d6, #F1D2D6);
  d: path("M2.004 24.237c0-.275.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.eys72vr0c {
  d: path("M13.44 20.515c0-.658-.535-1.096-.68-1.228l-.656.635l.404.824z");
}

.f9ktgbb3y {
  d: path("M29.996 24.237a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.ff3mybbqg {
  stroke: var(--svg-color--161515, #161515);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.974 16.27c.545-.193 1.303-.332 2.283-.24");
}

.fhvehqbbs {
  d: path("M24.78 23.59a3.004 3.004 0 1 0 0-6.007a3.004 3.004 0 0 0 0 6.008");
}

.fr51zgblk {
  stop-color: var(--svg-color--f7f1f1, #F7F1F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ghrfdpdai {
  stop-color: var(--svg-color--a89bb4, #A89BB4);
}

.gjp7xwfce {
  stop-color: var(--svg-color--cab1a7, #CAB1A7);
}

.gw5f7-xty {
  stop-color: var(--svg-color--e7d1d9, #E7D1D9);
}

.hrf4n-qjg {
  d: path("M22.682 7.612a8.2 8.2 0 0 0-4.904-1.655H14.26a8.2 8.2 0 0 0-4.905 1.655c-2.442 1.84-3.763 4.899-3.46 8.033l.83 7.496c.273 2.903 2.197 5.343 4.866 6.175c2.886.897 5.97.897 8.856 0c2.669-.832 4.593-3.272 4.866-6.175l.83-7.496c.302-3.134-1.018-6.194-3.461-8.033");
}

.hrncwbz_t {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
  stop-opacity: 0;
}

.hw65_7bjg {
  stop-color: var(--svg-color--feeeec, #FEEEEC);
  stop-opacity: 0;
}

.hxeei7fsy {
  stop-color: var(--svg-color--716362, #716362);
}

.i2to8tbny {
  stop-color: var(--svg-color--4997c1, #4997C1);
}

.i8um3jglr {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
  stop-opacity: 0;
}

.iccldcbrh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.732 19.15c.145.194-.158.43-.502.687s-.6.439-.745.245c-.144-.194.017-.56.362-.817c.344-.257.74-.309.885-.115");
}

.ih62nvbvg {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
  stop-opacity: 0;
}

.ih7fn7ksh {
  d: path("M19.732 19.15c.145.194-.158.43-.502.687s-.6.439-.745.245c-.144-.194.017-.56.362-.817c.344-.257.74-.309.885-.115");
}

.il6zdacve {
  stop-color: var(--svg-color--6b5853, #6B5853);
  stop-opacity: 0;
}

.ilm110bkf {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.993 24.481a5.9 5.9 0 0 1-2.78-.677c-.276-.149-.57.167-.395.436a3.78 3.78 0 0 0 3.184 1.744a3.8 3.8 0 0 0 3.184-1.744c.166-.26-.12-.575-.396-.436a6.06 6.06 0 0 1-2.797.677");
}

.ipc410grf {
  d: path("M15.721 4.181a3.95 3.95 0 0 0-3.512 2.052a8 8 0 0 1 1.738-.203h.138c1.673 0 3.078 1.368 3.069 3.04a3.02 3.02 0 0 1-.749 1.97a.5.5 0 0 0 .527.813a3.94 3.94 0 0 0 2.671-3.734c.01-2.145-1.737-3.91-3.882-3.938");
}

.j_83df0sk {
  stop-color: var(--svg-color--432e2e, #432E2E);
}

.j4e9jliyw {
  stop-color: var(--svg-color--4de2ff, #4DE2FF);
}

.ja2ta5btn {
  stop-color: var(--svg-color--9a84af, #9A84AF);
}

.jjaqfib2v {
  d: path("M24.78 22.51a1.924 1.924 0 1 0 0-3.847a1.924 1.924 0 0 0 0 3.848");
}

.jotp8y14r {
  stop-color: var(--svg-color--402336, #402336);
  stop-opacity: 0;
}

.k1igulbhf {
  stop-color: var(--svg-color--302325, #302325);
}

.k3o3btb6u {
  d: path("M5.145 28.411c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.ki9dlqbnk {
  stop-color: var(--svg-color--d4c7cd, #D4C7CD);
  stop-opacity: 0;
}

.km6m6cbfe {
  d: path("M7.22 22.454a1.867 1.867 0 1 0 0-3.734a1.867 1.867 0 0 0 0 3.733");
}

.kvq6_-e8h {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M5.145 28.411c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.ky2i9gfwu {
  stop-color: var(--svg-color--422628, #422628);
}

.lesqr_bdp {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljzk3pb-v {
  width: 3.969px;
  height: 6.227px;
  fill: var(--svg-color--f7e1ed, #F7E1ED);
  rx: 1px;
}

.lo1zrhbvw {
  stop-color: var(--svg-color--f2d3d7, #F2D3D7);
  stop-opacity: 0;
}

.lwh7ev7yo {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
}

.m3509-fun {
  d: path("M26.856 28.411a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.m63xmacvx {
  stop-color: var(--svg-color--cebfd0, #CEBFD0);
  stop-opacity: 0;
}

.mae-6ub-y {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.024 16.184c.546-.194 1.304-.333 2.283-.24");
}

.mb-hq_3bu {
  d: path("M19.882 18.72a2.033 2.033 0 0 1 1.96 2.57h-3.929a2 2 0 0 1-.074-.537c0-1.118.915-2.033 2.043-2.033");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjdwlzfcx {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
}

.mm6hvvbia {
  stop-color: var(--svg-color--a797b5, #A797B5);
}

.mmkgihbhj {
  d: path("m18.172 10.75l4.03-2.15c2.564 1.848 2.68 5.19 2.564 6.095l-5.095.693a2.476 2.476 0 0 1-1.5-4.638");
}

.mo9bgo9qn {
  stop-color: var(--svg-color--6d6262, #6D6262);
  stop-opacity: 0;
}

.n2-3kmtlx {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.249 23.738c-.345-.186-.711.209-.494.543l.063-.041z");
}

.n55r6jbfn {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M26.856 28.411a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.ngd5fmf0i {
  stop-color: var(--svg-color--554445, #554445);
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.o3p45rbvx {
  stop-color: var(--svg-color--472d49, #472D49);
  stop-opacity: 0;
}

.oci36vbzb {
  stop-color: var(--svg-color--c4b7cf, #C4B7CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohd-ppblk {
  stop-color: var(--svg-color--439fb2, #439FB2);
}

.op4ic3bzn {
  stop-color: var(--svg-color--43acc0, #43ACC0);
  stop-opacity: 0;
}

.ovwdp-bik {
  stop-color: var(--svg-color--4b4849, #4B4849);
}

.oxnp2k1qi {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
}

.oy5ype34t {
  stop-color: var(--svg-color--4d3533, #4D3533);
}

.p0z-iacrr {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M3.605 26.33c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.p4z5r-b-d {
  stop-color: var(--svg-color--312329, #312329);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q2fusinmo {
  stop-color: var(--svg-color--2f1718, #2F1718);
}

.q4ez5acay {
  stop-color: var(--svg-color--1a1118, #1A1118);
}

.qkfc8pbqb {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M29.996 24.237a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.quz6sacji {
  stop-color: var(--svg-color--cfcacf, #CFCACF);
}

.qvuai0b6y {
  stop-color: var(--svg-color--371e1f, #371E1F);
}

.qxhhvqurd {
  stop-color: var(--svg-color--bfa9ad, #BFA9AD);
}

.rfngthbki {
  stop-color: var(--svg-color--3e3431, #3E3431);
}

.rhghrobxp {
  stop-color: var(--svg-color--d3c5cf, #D3C5CF);
}

.rjxs4hg5m {
  stop-color: var(--svg-color--422628, #422628);
  stop-opacity: 0;
}

.rr59_uoqr {
  stop-color: var(--svg-color--4997c1, #4997C1);
  stop-opacity: 0;
}

.rwi7dob8k {
  stop-color: var(--svg-color--56403d, #56403D);
  stop-opacity: 0.058;
}

.s4p8h2blt {
  stop-color: var(--svg-color--291816, #291816);
}

.s781d-sgv {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
}

.spx4avb5u {
  width: 3.969px;
  height: 6.227px;
  rx: 1px;
}

.stsoanbmy {
  stop-color: var(--svg-color--4c494a, #4C494A);
  stop-opacity: 0;
}

.supagvb8e {
  d: path("M15.972 3.511c2.16 0 4.26.37 5.75 1.01c1.25.54 1.72 1.12 1.72 1.36s-.47.82-1.72 1.36c-1.49.64-3.58 1.01-5.75 1.01s-4.26-.36-5.74-1c-1.26-.54-1.72-1.13-1.72-1.37s.47-.82 1.72-1.36c1.48-.64 3.58-1.01 5.74-1.01m0-1.5c-4.95 0-8.96 1.73-8.96 3.87s4.01 3.87 8.97 3.87s8.97-1.73 8.97-3.87s-4.02-3.87-8.98-3.87");
}

.sz3vslbub {
  stop-color: var(--svg-color--6b5853, #6B5853);
}

.szge83bkx {
  stop-color: var(--svg-color--6d5b59, #6D5B59);
}

.t3yx6e33e {
  fill: var(--svg-color--4e302f, #4E302F);
  d: path("M22.682 7.612a8.2 8.2 0 0 0-4.904-1.655H14.26a8.2 8.2 0 0 0-4.905 1.655c-2.442 1.84-3.763 4.899-3.46 8.033l.83 7.496c.273 2.903 2.197 5.343 4.866 6.175c2.886.897 5.97.897 8.856 0c2.669-.832 4.593-3.272 4.866-6.175l.83-7.496c.302-3.134-1.018-6.194-3.461-8.033");
}

.t7aapjj0e {
  stop-color: var(--svg-color--33aed4, #33AED4);
}

.t82mlk1zf {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
}

.tbvggbbed {
  stop-color: var(--svg-color--371e1f, #371E1F);
  stop-opacity: 0;
}

.td_i0pbtq {
  stop-color: var(--svg-color--776867, #776867);
  stop-opacity: 0;
}

.tjfu52b6y {
  cx: 10.968px;
  cy: 19.589px;
  rx: 0.888px;
  ry: 0.449px;
}

.tqbblz5ki {
  stop-color: var(--svg-color--4b2e50, #4B2E50);
  stop-opacity: 0;
}

.trn388btv {
  stop-color: var(--svg-color--432935, #432935);
}

.tvui7dbha {
  stop-color: var(--svg-color--39222e, #39222E);
}

.uh_-bgsil {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
  stop-opacity: 0;
}

.uoj15rbmy {
  stop-color: var(--svg-color--43acc0, #43ACC0);
}

.uqd9t5bdt {
  stop-color: var(--svg-color--d7b5ca, #D7B5CA);
}

.uunj1cc5z {
  d: path("M16.11 5.075c-1.361-.206-2.548-.003-3.318 1.026c1.843 0 4.125 1.546 3.998 3.551a2.74 2.74 0 0 1-.92 1.678a.455.455 0 0 0 .373.798a3.58 3.58 0 0 0 2.87-3.027c.275-1.928-1.077-3.734-3.002-4.026");
}

.uyq-lepzm {
  stop-color: var(--svg-color--886457, #886457);
}

.v_ro-mcce {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
}

.v4hf23p3e {
  stop-color: var(--svg-color--776867, #776867);
}

.v8imspx_m {
  stop-color: var(--svg-color--dac4cc, #DAC4CC);
  stop-opacity: 0;
}

.va3q0ub8j {
  d: path("M16.002 23.267c.47 0 .892-.26 1.132-.649c.22-.357-.01-.832-.41-.832H15.28c-.4 0-.64.486-.41.832c.24.4.66.65 1.131.65");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmq252bnf {
  d: path("M7.22 23.59a3.004 3.004 0 1 0 0-6.007a3.004 3.004 0 0 0 0 6.008");
}

.vp-vdhfeg {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.592 16.136c-.545-.194-1.303-.333-2.283-.24");
}

.vsxpbmbdw {
  stop-color: var(--svg-color--dcbdc9, #DCBDC9);
}

.w58rbbcmh {
  width: 3.969px;
  height: 6.227px;
  x: 7.871px;
  y: 23.738px;
  rx: 1px;
}

.w67ysfbnv {
  d: path("M2.004 24.237c0-.275.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.wr31gnb3a {
  stop-color: var(--svg-color--402e2d, #402E2D);
  stop-opacity: 0;
}

.x4eddproi {
  stop-color: var(--svg-color--56403d, #56403D);
}

.xys9--bzn {
  fill: var(--svg-color--381c2e, #381C2E);
  d: path("M15.88 23.59c.47 0 .89-.259 1.131-.648c.22-.357-.01-.833-.41-.833h-1.443c-.4 0-.64.487-.41.833c.24.4.66.649 1.131.649");
}

.y-hwcqblh {
  cx: 10.968px;
  cy: 19.589px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.888px;
  ry: 0.449px;
}

.y7rsoxb6i {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
}

.yg5yzvips {
  d: path("M11.582 18.72a2.033 2.033 0 0 0-1.96 2.57h3.928c.047-.176.074-.352.074-.537a2.047 2.047 0 0 0-2.042-2.033");
}

.yi34m9bam {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
}

.yjjmn1b0t {
  stop-color: var(--svg-color--1a1118, #1A1118);
  stop-opacity: 0;
}

.z6pg27wxm {
  fill: var(--svg-color--000, #000);
  d: path("M18.717 20.754a1.16 1.16 0 0 1 1.165-1.165a1.16 1.16 0 0 1 1.165 1.165c0 .194-.047.378-.13.535h-2.061a1.05 1.05 0 0 1-.139-.536m-5.97.001a1.16 1.16 0 0 0-1.165-1.165a1.16 1.16 0 0 0-1.165 1.165c0 .194.047.378.13.535h2.061c.083-.157.139-.341.139-.536");
}

.zlafz0bxq {
  stop-color: var(--svg-color--39222e, #39222E);
  stop-opacity: 0;
}

.zlgw_eb1n {
  stop-color: var(--svg-color--402336, #402336);
}

.zvd0h7dvn {
  fill: var(--svg-color--211b1d, #211B1D);
  d: path("M15.721 4.181a3.95 3.95 0 0 0-3.512 2.052a8 8 0 0 1 1.738-.203h.138c1.673 0 3.078 1.368 3.069 3.04a3.02 3.02 0 0 1-.749 1.97a.5.5 0 0 0 .527.813a3.94 3.94 0 0 0 2.671-3.734c.01-2.145-1.737-3.91-3.882-3.938");
}

.zwtu7acdo {
  stop-color: var(--svg-color--4b2e50, #4B2E50);
}

.zz-7yrklx {
  d: path("M3.605 26.33c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

</style>
