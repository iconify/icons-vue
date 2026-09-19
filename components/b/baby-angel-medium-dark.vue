<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNvMiyd)"><path fill="url(#iNTi2fe)" class="ywohpebwn"/><path fill="url(#irbEekc)" class="ywohpebwn"/><path fill="url(#incElTb)" class="ywohpebwn"/><path fill="url(#iBlqCCc)" class="ywohpebwn"/><path fill="url(#iennZle)" class="ywohpebwn"/><path fill="url(#iaL1Oie)" class="ywohpebwn"/></g><path fill="url(#ipsNAie)" class="ywohpebwn"/><path class="hykvrnb0y"/><path fill="url(#i8r0Hdl)" class="r9wcr6b9p"/><path fill="url(#ijcGTXZ)" class="r9wcr6b9p"/><path fill="url(#iLXtHde)" class="r9wcr6b9p"/><path fill="url(#iNkvV8G)" class="r9wcr6b9p"/><g filter="url(#iPa4yjb)"><path class="xz2m9v3-o"/><path fill="url(#iwhB4tc)" class="kzt_lzn7v"/><path fill="url(#i632jsc)" class="kzt_lzn7v"/><path fill="url(#inxOwZc)" class="kzt_lzn7v"/></g><g filter="url(#ihWQETM)"><path class="jqc12gbsm"/><path fill="url(#ib8Kq5c)" class="lazjcfbjw"/><path fill="url(#i1xSJOc)" class="lazjcfbjw"/><path fill="url(#itH6Lpc)" class="lazjcfbjw"/></g><g filter="url(#iD4XSze)"><rect transform="matrix(-1 0 0 1 24.129 23.735)" class="ljzk3pb-v"/><rect fill="url(#ir52G6c)" transform="matrix(-1 0 0 1 24.129 23.735)" class="spx4avb5u"/></g><g filter="url(#iN27NeT)"><path class="zplk-99ou"/><path fill="url(#ilfgume)" class="e-4uaceev"/><path fill="url(#iJ6KiOd)" class="e-4uaceev"/></g><g filter="url(#iln6TOx)"><path class="tdltysjsw"/><path fill="url(#iPmakUb)" class="p6cf66phm"/><path fill="url(#imLm9Md)" class="p6cf66phm"/></g><path fill="url(#ihdgAVv)" class="p6cf66phm"/><g filter="url(#i2aoCZc)"><path class="av7xpgbbj"/><path class="a39lvdbux"/><path fill="url(#i8kKBxe)" class="jwp60wb8m"/></g><path fill="url(#ix2eaDb)" class="jwp60wb8m"/><g filter="url(#i1NnR1d)"><rect fill="url(#iTAEgZb)" class="oue28w9rl"/><rect fill="url(#i5qn6wc)" class="oue28w9rl"/></g><path fill="url(#i4ke6ge)" class="u9ablbbcv"/><path fill="url(#ietlcHf)" class="u9ablbbcv"/><g filter="url(#iPl11Rq)"><path fill="url(#iPdWJOe)" class="khenu3ejr"/></g><path fill="url(#iA2J3qe)" class="pswtblb_m"/><path fill="url(#imKyYbd)" class="pswtblb_m"/><path fill="url(#iaKiSQb)" class="pswtblb_m"/><path fill="url(#igTZu8d)" class="pswtblb_m"/><g filter="url(#iAnzrbl)"><path fill="url(#ieC9GMc)" class="na5dmdzfr"/></g><g filter="url(#iuG8Pbe)"><path class="yps4sacnd"/><path fill="url(#idpHFLd)" class="z88u0kbpm"/><path fill="url(#iZE41Ac)" class="z88u0kbpm"/><path fill="url(#i0S77Ed)" class="z88u0kbpm"/><path fill="url(#iB4HERf)" class="z88u0kbpm"/></g><g filter="url(#i7hmwed)"><path class="uu51xw1-r"/></g><path stroke="url(#ibaYjGb)" class="rtoaqy-6x"/><path class="oz7nf8xrp"/><path fill="url(#inr5lNb)" class="k2e_me28k"/><path fill="url(#iFAFwWb)" class="c1v_o8rei"/><path class="b65n-zbqt"/><g filter="url(#ilscuBe)"><path class="xwtmpuoza"/></g><g filter="url(#iHA4j9d)"><path stroke="url(#iPNghKb)" class="zl2x6ll0q"/></g><g filter="url(#iaBu2Je)"><path class="rr18izb3v"/></g><g filter="url(#ifehMac)"><path stroke="url(#i9uhOwc)" class="dqcd3ebdx"/></g><g filter="url(#indjmLb)"><path fill="url(#i8EpjOd)" class="gdsc7fbzn"/></g><g filter="url(#izNppMe)"><path class="xhrk0abmo"/><path fill="url(#iH3nVBb)" class="lc9ays6do"/><path fill="url(#iizZsvb)" class="lc9ays6do"/><path fill="url(#i1rbxcd)" class="lc9ays6do"/><path fill="url(#i4HJt7b)" class="lc9ays6do"/></g><g filter="url(#i5xSbhc)"><path class="bigf05bqp"/></g><g filter="url(#i9V82Fd)"><path fill="url(#ikOacYb)" class="p7xtf1c-v"/><path fill="url(#ij2Igub)" class="p7xtf1c-v"/></g><g filter="url(#iZv3gCc)"><path class="twy3qqhil"/><path fill="url(#iZmJDbd)" class="au39pc0zw"/></g><g filter="url(#iOKvj4b)"><path fill="url(#i8sejZc)" class="fnjs_tx3o"/></g><g filter="url(#ivlJjJb)"><path fill="url(#iWIFXbd)" class="g4bl-0aqs"/></g><g filter="url(#iYg6Zkd)"><ellipse transform="rotate(-27.914 10.99 19.6)" class="hl0z-hb8c"/><ellipse fill="url(#iHLm5dd)" transform="rotate(-27.914 10.99 19.6)" class="jalxyzjbw"/></g><g filter="url(#iKjuB6d)"><path fill="url(#iorQGJe)" class="xlileyb_c"/></g><defs><radialGradient id="iNTi2fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.75003 3.6875 -9.72121 -1.97727 20.936 3.29)" gradientUnits="userSpaceOnUse"><stop class="j4e9jliyw"/><stop offset="1" class="t7aapjj0e"/></radialGradient><radialGradient id="irbEekc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.45 10.96 -4.15)scale(5.22735 10.6403)" gradientUnits="userSpaceOnUse"><stop class="v_ro-mcce"/><stop offset="1" class="ak0e0gbla"/></radialGradient><radialGradient id="incElTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.46875 -1.11569 1.02074 9.827 6.884)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="t82mlk1zf"/><stop offset="1" class="hrncwbz_t"/></radialGradient><radialGradient id="iBlqCCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 -.98438 .58816 -.61616 10.327 7.337)" gradientUnits="userSpaceOnUse"><stop class="oxnp2k1qi"/><stop offset="1" class="ih62nvbvg"/></radialGradient><radialGradient id="iennZle" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 1.85939 -1.34213 -1.93987 23.265 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="i2to8tbny"/><stop offset="1" class="rr59_uoqr"/></radialGradient><radialGradient id="iaL1Oie" cx="0" cy="0" r="1" gradientTransform="rotate(144.605 10.248 6.89)scale(1.45673 1.05149)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="ohd-ppblk"/><stop offset="1" class="c62dirbjk"/></radialGradient><radialGradient id="ipsNAie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93752 -7.271 18.54198 -4.94092 11.718 9.749)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="op4ic3bzn"/><stop offset="1" class="uoj15rbmy"/></radialGradient><radialGradient id="ijcGTXZ" cx="0" cy="0" r="1" gradientTransform="matrix(.6072 2.64774 -4.70572 1.07914 25.39 27.535)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="iLXtHde" cx="0" cy="0" r="1" gradientTransform="matrix(-.52434 .60868 -.33593 -.28939 26.855 28.037)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="i632jsc" cx="0" cy="0" r="1" gradientTransform="matrix(.76907 2.71875 -5.8088 1.64318 26.539 25.43)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="inxOwZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.66412 .625 -.34814 -.36993 28.395 25.946)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="i1xSJOc" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 2.71875 -6.83491 2.35687 27.733 23.337)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="m63xmacvx"/><stop offset=".922" class="ghrfdpdai"/></radialGradient><radialGradient id="itH6Lpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.80957 .625 -.33743 -.43707 29.996 23.852)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="ilfgume" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 1.73438 -1.37456 -.54486 8.812 28.509)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="y7rsoxb6i"/><stop offset="1" class="i8um3jglr"/></radialGradient><radialGradient id="iJ6KiOd" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 -2.21094 5.39927 1.3355 6.765 30.134)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="bs3nz4btd"/><stop offset="1" class="qxhhvqurd"/></radialGradient><radialGradient id="iPmakUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 2.25 -2.22312 -.80279 8.78 26.227)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="mjdwlzfcx"/><stop offset="1" class="cb_xa0byd"/></radialGradient><radialGradient id="imLm9Md" cx="0" cy="0" r="1" gradientTransform="matrix(.84155 -2.27023 6.63898 2.461 5.657 28.1)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="a-hxohb_j"/><stop offset="1" class="yi34m9bam"/></radialGradient><radialGradient id="ihdgAVv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0827 3.1875 -5.20641 -1.76845 5.832 25.227)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="ix2eaDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 3.46875 -6.65848 -2.33947 4.718 23.134)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="iTAEgZb" cx="0" cy="0" r="1" gradientTransform="rotate(122.4 -2.43 16.412)scale(1.9246 3.13561)" gradientUnits="userSpaceOnUse"><stop class="uqd9t5bdt"/><stop offset="1" class="vsxpbmbdw"/></radialGradient><radialGradient id="ietlcHf" cx="0" cy="0" r="1" gradientTransform="rotate(171.523 2.86 10.567)scale(3.03477 3.15575)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="e83j1pbzf"/><stop offset="1" class="tsnuc-o7q"/></radialGradient><radialGradient id="iPdWJOe" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.676 13.92)scale(1.86529)" gradientUnits="userSpaceOnUse"><stop class="ssu63ccnp"/><stop offset="1" class="j68-af44h"/></radialGradient><radialGradient id="imKyYbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.07215 4.35811 -4.17658 -.06915 25.113 19.5)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="q2gi06hfo"/><stop offset="1" class="di4fd-qzw"/></radialGradient><radialGradient id="iaKiSQb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.351 35.08 -17.86)scale(2.56855 2.53463)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="t1bdvwm2a"/><stop offset=".883" class="uygxvob5o"/></radialGradient><radialGradient id="igTZu8d" cx="0" cy="0" r="1" gradientTransform="matrix(.7504 -3.52112 2.76508 .58928 25.29 21.42)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="kw5jt0gxx"/><stop offset="1" class="t217_nbyf"/></radialGradient><radialGradient id="ieC9GMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.37093 .21646 -.32001 2.02675 25.42 20.741)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="kc3i_q84r"/><stop offset="1" class="h0sp3fbhr"/></radialGradient><radialGradient id="i0S77Ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.26992 9.23572 -2.816 .3872 6.198 20.424)" gradientUnits="userSpaceOnUse"><stop class="j8sqz220e"/><stop offset="1" class="tt6l6i3qr"/></radialGradient><radialGradient id="iB4HERf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15446 -12.00643 18.8398 -1.81151 11.105 29.991)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="f90e_5b5t"/><stop offset="1" class="eocuezbnh"/></radialGradient><radialGradient id="inr5lNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84715 -2.93809 0 19.893 19.818)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="s28fv4bdt"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="p9hqzqn3a"/></radialGradient><radialGradient id="iFAFwWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84715 -2.93809 0 11.608 19.818)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="s28fv4bdt"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="p9hqzqn3a"/></radialGradient><radialGradient id="iH3nVBb" cx="0" cy="0" r="1" gradientTransform="matrix(7.22389 -1.40934 1.1757 6.02634 12.23 8.244)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="stsoanbmy"/><stop offset="1" class="ovwdp-bik"/></radialGradient><radialGradient id="iizZsvb" cx="0" cy="0" r="1" gradientTransform="rotate(-23.69 26.939 -24.79)scale(6.17756 5.96472)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="ovwdp-bik"/><stop offset=".912" class="stsoanbmy"/></radialGradient><radialGradient id="i1rbxcd" cx="0" cy="0" r="1" gradientTransform="rotate(-122.764 11.006 .433)scale(6.20809 6.40045)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="aj460xbwf"/><stop offset="1" class="rfngthbki"/></radialGradient><radialGradient id="i4HJt7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.82844 4.50242 -4.3245 2.71667 15.261 6.974)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="yjjmn1b0t"/><stop offset=".966" class="q4ez5acay"/></radialGradient><radialGradient id="ikOacYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.76056 .0433 -.02239 .91034 15.304 22.358)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="re6r14slg"/><stop offset="1" class="bdxxkoblu"/></radialGradient><radialGradient id="ij2Igub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3132 -1.65751 0 16.018 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="pv8_wtbzz"/><stop offset="1" class="qdbiq-bpb"/></radialGradient><radialGradient id="iZmJDbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.528 -.68041 .93677 -.72694 19.374 20.009)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHLm5dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01761 -1.12483 1.3521 -.02117 10.956 20.317)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iNvMiyd" width="17.94" height="7.94" x="7.011" y="1.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.596078 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="iPa4yjb" width="7.412" height="2.194" x="20.982" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="ihWQETM" width="9.014" height="2.194" x="20.982" y="23.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="iD4XSze" width="4.369" height="6.627" x="20.16" y="23.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.54902 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="iN27NeT" width="6.273" height="2.439" x="4.645" y="27.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.541176 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="iln6TOx" width="7.813" height="2.494" x="3.105" y="25.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="i2aoCZc" width="9.414" height="2.494" x="1.504" y="23.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="i1NnR1d" width="4.369" height="6.627" x="7.471" y="23.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.54902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="iPl11Rq" width="4.231" height="4.231" x="5.129" y="18.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".125"/></filter><filter id="iAnzrbl" width="4.345" height="4.345" x="22.62" y="18.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".125"/></filter><filter id="iuG8Pbe" width="21.969" height="24.013" x="5.478" y="5.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.333333 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.490196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22274" result="effect2_innerShadow_3987_22274"/></filter><filter id="i7hmwed" width="6.465" height="2.217" x="12.786" y="23.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="ilscuBe" width="3.531" height="1.57" x="9.497" y="15.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="iHA4j9d" width="2.981" height=".969" x="9.697" y="15.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".1"/></filter><filter id="iaBu2Je" width="3.531" height="1.57" x="18.575" y="15.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0784314 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="ifehMac" width="2.981" height=".969" x="18.975" y="15.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".1"/></filter><filter id="indjmLb" width="7.351" height="8.128" x="12.313" y="4.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".25"/></filter><filter id="izNppMe" width="7.489" height="7.893" x="12.13" y="4.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0313726 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22274"/></filter><filter id="i5xSbhc" width="3.437" height="2.481" x="14.177" y="21.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".25"/></filter><filter id="i9V82Fd" width="2.937" height="1.981" x="14.55" y="21.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".125"/></filter><filter id="iZv3gCc" width="1.536" height="1.33" x="18.349" y="18.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".05"/></filter><filter id="iOKvj4b" width="1.518" height="1.569" x="20.389" y="19.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".1"/></filter><filter id="ivlJjJb" width="1.735" height="1.858" x="11.925" y="19.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".1"/></filter><filter id="iYg6Zkd" width="1.823" height="1.349" x="10.079" y="18.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation=".05"/></filter><filter id="iKjuB6d" width="12.928" height="11.805" x="14.379" y="6.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22274" stdDeviation="1.25"/></filter><linearGradient id="i8r0Hdl" x1="24.585" x2="24.585" y1="30.185" y2="28.69" gradientUnits="userSpaceOnUse"><stop offset=".079" class="ja2ta5btn"/><stop offset="1" class="oci36vbzb"/></linearGradient><linearGradient id="iNkvV8G" x1="24.436" x2="24.436" y1="27.923" y2="28.321" gradientUnits="userSpaceOnUse"><stop class="quz6sacji"/><stop offset="1" class="hw65_7bjg"/></linearGradient><linearGradient id="iwhB4tc" x1="25.518" x2="25.518" y1="27.923" y2="26.876" gradientUnits="userSpaceOnUse"><stop offset=".216" class="e6rsc3sik"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="ib8Kq5c" x1="26.49" x2="26.49" y1="25.829" y2="24.782" gradientUnits="userSpaceOnUse"><stop offset=".216" class="rhghrobxp"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="ir52G6c" x1="0" x2=".958" y1="5.398" y2="5.398" gradientUnits="userSpaceOnUse"><stop class="lwh7ev7yo"/><stop offset="1" class="lesqr_bdp"/></linearGradient><linearGradient id="i8kKBxe" x1="6.461" x2="6.461" y1="23.735" y2="24.618" gradientUnits="userSpaceOnUse"><stop class="gjp7xwfce"/><stop offset="1" class="lo1zrhbvw"/></linearGradient><linearGradient id="i5qn6wc" x1="7.871" x2="9.124" y1="29.134" y2="29.134" gradientUnits="userSpaceOnUse"><stop class="gw5f7-xty"/><stop offset="1" class="v8imspx_m"/></linearGradient><linearGradient id="i4ke6ge" x1="4.727" x2="6.891" y1="18.057" y2="23.599" gradientUnits="userSpaceOnUse"><stop class="jzuduyb2o"/><stop offset="1" class="y0i156btv"/></linearGradient><linearGradient id="iA2J3qe" x1="27.455" x2="25.07" y1="19.039" y2="22.906" gradientUnits="userSpaceOnUse"><stop class="kzj9y0b0j"/><stop offset="1" class="ekonz16jg"/></linearGradient><linearGradient id="idpHFLd" x1="16.037" x2="16.037" y1="30.525" y2="25.792" gradientUnits="userSpaceOnUse"><stop offset=".195" class="n54r9cbvw"/><stop offset="1" class="dxeyl9_7p"/></linearGradient><linearGradient id="iZE41Ac" x1="7.526" x2="17.916" y1="18.981" y2="21.636" gradientUnits="userSpaceOnUse"><stop class="w39e-ubuo"/><stop offset="1" class="nvpd1fzwj"/></linearGradient><linearGradient id="ibaYjGb" x1="13.861" x2="14.323" y1="25.431" y2="24.594" gradientUnits="userSpaceOnUse"><stop class="y8yymsbkp"/><stop offset="1" class="f5plm9-fv"/></linearGradient><linearGradient id="iPNghKb" x1="12.692" x2="9.763" y1="15.82" y2="16.198" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="i9uhOwc" x1="21.97" x2="19.041" y1="15.772" y2="16.15" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="i8EpjOd" x1="16.32" x2="15.36" y1="5.123" y2="12.044" gradientUnits="userSpaceOnUse"><stop class="w78w6v86k"/><stop offset="1" class="quv0ho30c"/></linearGradient><linearGradient id="i8sejZc" x1="21.664" x2="20.95" y1="19.941" y2="20.381" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWIFXbd" x1="13.302" x2="12.588" y1="19.941" y2="20.381" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iorQGJe" x1="17.562" x2="26.517" y1="15.719" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="e1m7epfuh"/><stop offset="1" class="ybfagfbdb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-angel-medium-dark" /></template>
<style>
.a-hxohb_j {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
  stop-opacity: 0;
}

.a39lvdbux {
  fill: var(--svg-color--f1d2d6, #F1D2D6);
  d: path("M2.004 24.234c0-.276.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.aj460xbwf {
  stop-color: var(--svg-color--3e3431, #3E3431);
  stop-opacity: 0;
}

.ak0e0gbla {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
  stop-opacity: 0;
}

.au39pc0zw {
  d: path("M19.748 19.161c.145.194-.158.43-.502.687s-.6.438-.744.245c-.145-.194.017-.56.36-.817c.345-.257.741-.308.886-.115");
}

.av7xpgbbj {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M2.004 24.234c0-.276.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.b65n-zbqt {
  fill: var(--svg-color--000, #000);
  d: path("M18.734 20.764c0-.647.517-1.164 1.164-1.164s1.163.517 1.163 1.164c0 .194-.046.378-.129.535h-2.06a1.05 1.05 0 0 1-.138-.535m-5.966 0a1.16 1.16 0 0 0-1.164-1.164c-.647 0-1.164.517-1.164 1.164c0 .194.046.378.13.535h2.06c.082-.157.138-.341.138-.535");
}

.bdxxkoblu {
  stop-color: var(--svg-color--98726a, #98726A);
}

.bigf05bqp {
  fill: var(--svg-color--753f4c, #753F4C);
  d: path("M15.898 23.599c.47 0 .89-.26 1.13-.649c.22-.356-.01-.832-.41-.832h-1.44c-.401 0-.641.486-.411.832c.24.4.66.649 1.13.649");
}

.bs3nz4btd {
  stop-color: var(--svg-color--e7cbd8, #E7CBD8);
  stop-opacity: 0;
}

.c1v_o8rei {
  d: path("M11.604 18.732a2.032 2.032 0 0 0-1.958 2.567h3.925a2 2 0 0 0 .074-.535a2.046 2.046 0 0 0-2.041-2.032");
}

.c62dirbjk {
  stop-color: var(--svg-color--439fb2, #439FB2);
  stop-opacity: 0;
}

.cb_xa0byd {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.di4fd-qzw {
  stop-color: var(--svg-color--794566, #794566);
}

.dqcd3ebdx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.606 16.15c-.545-.194-1.302-.333-2.28-.24");
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.dxeyl9_7p {
  stop-color: var(--svg-color--7d4271, #7D4271);
  stop-opacity: 0;
}

.e-4uaceev {
  d: path("M5.145 28.408c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.e1m7epfuh {
  stop-color: var(--svg-color--b08579, #B08579);
}

.e6rsc3sik {
  stop-color: var(--svg-color--c6bec8, #C6BEC8);
}

.e83j1pbzf {
  stop-color: var(--svg-color--825d58, #825D58);
  stop-opacity: 0;
}

.ekonz16jg {
  stop-color: var(--svg-color--7f5258, #7F5258);
}

.eocuezbnh {
  stop-color: var(--svg-color--733f59, #733F59);
  stop-opacity: 0;
}

.f5plm9-fv {
  stop-color: var(--svg-color--845b5f, #845B5F);
  stop-opacity: 0;
}

.f90e_5b5t {
  stop-color: var(--svg-color--733f59, #733F59);
}

.fnjs_tx3o {
  d: path("M21.708 20.496a1.9 1.9 0 0 0-.527-1.053l-.592.649l.267.52z");
}

.fr51zgblk {
  stop-color: var(--svg-color--f7f1f1, #F7F1F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4bl-0aqs {
  d: path("M13.46 20.525c0-.657-.534-1.094-.678-1.227l-.656.635l.404.823z");
}

.gdsc7fbzn {
  d: path("M16.129 5.097c-1.36-.206-2.547-.003-3.316 1.025c1.842 0 4.122 1.545 3.995 3.549a2.74 2.74 0 0 1-.919 1.677a.454.454 0 0 0 .372.797a3.58 3.58 0 0 0 2.867-3.025c.276-1.926-1.075-3.731-3-4.023");
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

.h0sp3fbhr {
  stop-color: var(--svg-color--7b4941, #7B4941);
}

.hl0z-hb8c {
  cx: 10.991px;
  cy: 19.6px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.887px;
  ry: 0.449px;
}

.hrncwbz_t {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
  stop-opacity: 0;
}

.hw65_7bjg {
  stop-color: var(--svg-color--feeeec, #FEEEEC);
  stop-opacity: 0;
}

.hykvrnb0y {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M26.856 28.408a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.i2to8tbny {
  stop-color: var(--svg-color--4997c1, #4997C1);
}

.i8um3jglr {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
  stop-opacity: 0;
}

.ih62nvbvg {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
  stop-opacity: 0;
}

.j4e9jliyw {
  stop-color: var(--svg-color--4de2ff, #4DE2FF);
}

.j68-af44h {
  stop-color: var(--svg-color--5a343a, #5A343A);
}

.j8sqz220e {
  stop-color: var(--svg-color--836059, #836059);
}

.ja2ta5btn {
  stop-color: var(--svg-color--9a84af, #9A84AF);
}

.jalxyzjbw {
  cx: 10.991px;
  cy: 19.6px;
  rx: 0.887px;
  ry: 0.449px;
}

.jqc12gbsm {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M29.996 24.234a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.jwp60wb8m {
  d: path("M2.004 24.234c0-.276.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.jzuduyb2o {
  stop-color: var(--svg-color--65423d, #65423D);
}

.k2e_me28k {
  d: path("M19.898 18.732a2.032 2.032 0 0 1 1.957 2.567H17.93a2 2 0 0 1-.074-.535a2.04 2.04 0 0 1 2.041-2.032");
}

.kc3i_q84r {
  stop-color: var(--svg-color--835e58, #835E58);
}

.khenu3ejr {
  d: path("M7.245 22.462a1.865 1.865 0 1 0 0-3.73a1.865 1.865 0 0 0 0 3.73");
}

.ki9dlqbnk {
  stop-color: var(--svg-color--d4c7cd, #D4C7CD);
  stop-opacity: 0;
}

.kw5jt0gxx {
  stop-color: var(--svg-color--8e6d5e, #8E6D5E);
  stop-opacity: 0;
}

.kzj9y0b0j {
  stop-color: var(--svg-color--997768, #997768);
}

.kzt_lzn7v {
  d: path("M28.395 26.328a.5.5 0 0 0-.499-.499h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.lazjcfbjw {
  d: path("M29.996 24.234a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.lc9ays6do {
  d: path("M15.74 4.204a3.94 3.94 0 0 0-3.51 2.05a8 8 0 0 1 1.737-.203h.138c1.672 0 3.076 1.367 3.067 3.039a3.02 3.02 0 0 1-.748 1.967a.501.501 0 0 0 .526.813a3.94 3.94 0 0 0 2.669-3.732c.01-2.142-1.736-3.906-3.879-3.934");
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

.m63xmacvx {
  stop-color: var(--svg-color--cebfd0, #CEBFD0);
  stop-opacity: 0;
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

.n54r9cbvw {
  stop-color: var(--svg-color--7d4271, #7D4271);
}

.na5dmdzfr {
  d: path("M24.793 22.52a1.922 1.922 0 1 0 0-3.846a1.922 1.922 0 0 0 0 3.845");
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.nvpd1fzwj {
  stop-color: var(--svg-color--734a4b, #734A4B);
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

.oue28w9rl {
  width: 3.969px;
  height: 6.227px;
  x: 7.871px;
  y: 23.735px;
  rx: 1px;
}

.ovwdp-bik {
  stop-color: var(--svg-color--4b4849, #4B4849);
}

.oxnp2k1qi {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
}

.oz7nf8xrp {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.369 18.113a3.18 3.18 0 0 1 3.084 2.41a.624.624 0 0 1-.61.776h-5.079a.524.524 0 0 1-.517-.618a3.18 3.18 0 0 1 3.122-2.568m-9.236 0a3.18 3.18 0 0 0-3.085 2.41a.624.624 0 0 0 .61.776h5.08a.524.524 0 0 0 .516-.618a3.19 3.19 0 0 0-3.121-2.568");
}

.p6cf66phm {
  d: path("M3.605 26.328a.5.5 0 0 1 .499-.499h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.p7xtf1c-v {
  d: path("M16.02 23.275c.47 0 .891-.259 1.131-.648c.22-.357-.01-.832-.41-.832H15.3c-.4 0-.64.486-.41.832c.24.4.66.648 1.13.648");
}

.p9hqzqn3a {
  stop-color: var(--svg-color--6d4c4a, #6D4C4A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pswtblb_m {
  d: path("M24.793 23.599a3.002 3.002 0 1 0 0-6.003a3.002 3.002 0 0 0 0 6.003");
}

.pv8_wtbzz {
  stop-color: var(--svg-color--7c4457, #7C4457);
  stop-opacity: 0;
}

.q2gi06hfo {
  stop-color: var(--svg-color--794566, #794566);
  stop-opacity: 0;
}

.q4ez5acay {
  stop-color: var(--svg-color--1a1118, #1A1118);
}

.qdbiq-bpb {
  stop-color: var(--svg-color--7c4457, #7C4457);
}

.quv0ho30c {
  stop-color: var(--svg-color--724139, #724139);
}

.quz6sacji {
  stop-color: var(--svg-color--cfcacf, #CFCACF);
}

.qxhhvqurd {
  stop-color: var(--svg-color--bfa9ad, #BFA9AD);
}

.r9wcr6b9p {
  d: path("M26.856 28.408a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.re6r14slg {
  stop-color: var(--svg-color--8e6559, #8E6559);
}

.rfngthbki {
  stop-color: var(--svg-color--3e3431, #3E3431);
}

.rhghrobxp {
  stop-color: var(--svg-color--d3c5cf, #D3C5CF);
}

.rr18izb3v {
  stroke: var(--svg-color--332422, #332422);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M21.606 16.284c-.545-.194-1.302-.332-2.28-.24");
}

.rr59_uoqr {
  stop-color: var(--svg-color--4997c1, #4997C1);
  stop-opacity: 0;
}

.rtoaqy-6x {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.27 23.745c-.345-.185-.711.21-.494.543l.063-.04z");
}

.s28fv4bdt {
  stop-color: var(--svg-color--865f54, #865F54);
}

.s781d-sgv {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
}

.spx4avb5u {
  width: 3.969px;
  height: 6.227px;
  rx: 1px;
}

.ssu63ccnp {
  stop-color: var(--svg-color--5a2f2f, #5A2F2F);
}

.stsoanbmy {
  stop-color: var(--svg-color--4c494a, #4C494A);
  stop-opacity: 0;
}

.t1bdvwm2a {
  stop-color: var(--svg-color--7a4941, #7A4941);
}

.t217_nbyf {
  stop-color: var(--svg-color--8e6d5e, #8E6D5E);
}

.t7aapjj0e {
  stop-color: var(--svg-color--33aed4, #33AED4);
}

.t82mlk1zf {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
}

.tdltysjsw {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M3.605 26.328a.5.5 0 0 1 .499-.499h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.tsnuc-o7q {
  stop-color: var(--svg-color--825d58, #825D58);
}

.tt6l6i3qr {
  stop-color: var(--svg-color--836059, #836059);
  stop-opacity: 0;
}

.twy3qqhil {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.748 19.161c.145.194-.158.43-.502.687s-.6.438-.744.245c-.145-.194.017-.56.36-.817c.345-.257.741-.308.886-.115");
}

.u9ablbbcv {
  d: path("M7.245 23.599a3.002 3.002 0 1 0 0-6.004a3.002 3.002 0 0 0 0 6.004");
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

.uu51xw1-r {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.011 24.488a5.9 5.9 0 0 1-2.777-.677c-.276-.148-.57.167-.395.436a3.78 3.78 0 0 0 3.181 1.743a3.79 3.79 0 0 0 3.182-1.743c.166-.26-.12-.575-.395-.436a6.05 6.05 0 0 1-2.796.677");
}

.uygxvob5o {
  stop-color: var(--svg-color--7a4941, #7A4941);
  stop-opacity: 0;
}

.v_ro-mcce {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
}

.v8imspx_m {
  stop-color: var(--svg-color--dac4cc, #DAC4CC);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vsxpbmbdw {
  stop-color: var(--svg-color--dcbdc9, #DCBDC9);
}

.w39e-ubuo {
  stop-color: var(--svg-color--734a4b, #734A4B);
}

.w78w6v86k {
  stop-color: var(--svg-color--553327, #553327);
}

.xhrk0abmo {
  fill: var(--svg-color--211b1d, #211B1D);
  d: path("M15.74 4.204a3.94 3.94 0 0 0-3.51 2.05a8 8 0 0 1 1.737-.203h.138c1.672 0 3.076 1.367 3.067 3.039a3.02 3.02 0 0 1-.748 1.967a.501.501 0 0 0 .526.813a3.94 3.94 0 0 0 2.669-3.732c.01-2.142-1.736-3.906-3.879-3.934");
}

.xlileyb_c {
  d: path("m18.189 10.768l4.028-2.149c2.56 1.848 2.676 5.186 2.56 6.09l-5.09.693a2.474 2.474 0 0 1-1.498-4.634");
}

.xwtmpuoza {
  stroke: var(--svg-color--2d1e1d, #2D1E1D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.997 16.284c.545-.194 1.302-.332 2.281-.24");
}

.xz2m9v3-o {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M28.395 26.328a.5.5 0 0 0-.499-.499h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.y0i156btv {
  stop-color: var(--svg-color--653549, #653549);
}

.y7rsoxb6i {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
}

.y8yymsbkp {
  stop-color: var(--svg-color--845b5f, #845B5F);
}

.ybfagfbdb {
  stop-color: var(--svg-color--b08579, #B08579);
  stop-opacity: 0;
}

.yi34m9bam {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
}

.yjjmn1b0t {
  stop-color: var(--svg-color--1a1118, #1A1118);
  stop-opacity: 0;
}

.yps4sacnd {
  fill: var(--svg-color--9a6b5e, #9A6B5E);
  d: path("M22.695 7.632a8.2 8.2 0 0 0-4.9-1.653h-3.516a8.2 8.2 0 0 0-4.9 1.653c-2.441 1.838-3.76 4.895-3.459 8.027l.83 7.49c.273 2.9 2.195 5.34 4.862 6.17c2.884.896 5.966.896 8.85 0c2.667-.83 4.59-3.27 4.863-6.17l.829-7.49c.301-3.132-1.018-6.189-3.459-8.027");
}

.ywohpebwn {
  d: path("M15.972 3.509c2.16 0 4.26.37 5.75 1.01c1.25.54 1.72 1.12 1.72 1.36s-.47.82-1.72 1.36c-1.49.64-3.58 1.01-5.75 1.01s-4.26-.36-5.74-1c-1.26-.54-1.72-1.13-1.72-1.37s.47-.82 1.72-1.36c1.48-.64 3.58-1.01 5.74-1.01m0-1.5c-4.95 0-8.96 1.73-8.96 3.87s4.01 3.87 8.97 3.87s8.97-1.73 8.97-3.87s-4.02-3.87-8.98-3.87");
}

.z88u0kbpm {
  d: path("M22.695 7.632a8.2 8.2 0 0 0-4.9-1.653h-3.516a8.2 8.2 0 0 0-4.9 1.653c-2.441 1.838-3.76 4.895-3.459 8.027l.83 7.49c.273 2.9 2.195 5.34 4.862 6.17c2.884.896 5.966.896 8.85 0c2.667-.83 4.59-3.27 4.863-6.17l.829-7.49c.301-3.132-1.018-6.189-3.459-8.027");
}

.zl2x6ll0q {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.047 16.198c.545-.194 1.303-.333 2.282-.24");
}

.zplk-99ou {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M5.145 28.408c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

</style>
