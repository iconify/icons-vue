<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ilCwTAb)" class="yblx39b-o"/><path fill="url(#irpCsoe)" class="yblx39b-o"/><g filter="url(#i1VnjcU)"><path fill="url(#ioOlUUb)" class="wpfvvtbjo"/></g><path fill="url(#iUTGkgd)" class="ijo70fbwd"/><path fill="url(#iuyrjyb)" class="ijo70fbwd"/><path fill="url(#iuOBUpb)" class="ijo70fbwd"/><path fill="url(#iodBcae)" class="ijo70fbwd"/><g filter="url(#iKmBXIb)"><path fill="url(#iyABfTr)" class="yk051b8kx"/></g><g filter="url(#iz9oRte)"><path fill="url(#iV2QGwd)" class="t7z8qfb-u"/><path fill="url(#i9GgV5b)" class="t7z8qfb-u"/><path fill="url(#ikbz0qe)" class="t7z8qfb-u"/><path fill="url(#iIUJpCe)" class="t7z8qfb-u"/><path fill="url(#imrqIPe)" class="t7z8qfb-u"/><path fill="url(#i3mpUzc)" class="t7z8qfb-u"/><path fill="url(#igwTzZE)" class="t7z8qfb-u"/><path fill="url(#i3PXbun)" class="t7z8qfb-u"/><path fill="url(#ikBgWBc)" class="t7z8qfb-u"/></g><path fill="url(#ixEgtwe)" class="t7z8qfb-u"/><path fill="url(#ikllpDq)" class="t7z8qfb-u"/><g filter="url(#ie4VPbb)"><path stroke="url(#ilf0iXb)" class="zs25280ps"/></g><g filter="url(#iYeruae)"><path class="uk6dvmbah"/></g><path class="hbmt10b_q"/><path fill="url(#irZZCOc)" class="gnsmnbsiz"/><path fill="url(#igQrkuc)" class="itqfu5aet"/><path class="df30j9bms"/><g filter="url(#i4BQH9L)"><path class="drtc3eb2u"/></g><g filter="url(#i9QAHDc)"><path stroke="url(#iqKotpN)" class="s8ndzosdx"/></g><g filter="url(#ib3QnsW)"><path fill="url(#ijdAVqd)" class="o7w_zk5zp"/></g><g filter="url(#ia8TnFd)"><path fill="url(#iu8RoZb)" class="l-rsu_beu"/></g><g filter="url(#i7PJnse)"><path class="ymsrhk7tq"/><path fill="url(#iw5kcJd)" class="nrujh8kqd"/><path fill="url(#irzEpoe)" class="nrujh8kqd"/><path fill="url(#iO93hgc)" class="nrujh8kqd"/><path fill="url(#i5xRL4b)" class="nrujh8kqd"/></g><g filter="url(#iU1WxKP)"><path class="adex90brn"/></g><g filter="url(#iWdzDXd)"><path fill="url(#iSXsC8b)" class="dzbw1fbmj"/><path fill="url(#iglyfqb)" class="dzbw1fbmj"/></g><g filter="url(#iUlIBRb)"><path class="fk3-b0ocx"/><path fill="url(#irbLrOb)" class="zwwykac4x"/></g><g filter="url(#ix4kvzQ)"><path fill="url(#i9IjLOd)" class="s70ylbbla"/></g><g filter="url(#iZFSiRd)"><path fill="url(#iHk95Sb)" class="g8knucmkh"/></g><g filter="url(#iccc4be)"><ellipse transform="rotate(-27.914 10.689 18.71)" class="qj22awqlb"/><ellipse fill="url(#idbZ8Ab)" transform="rotate(-27.914 10.689 18.71)" class="iey7ulbyh"/></g><g filter="url(#iG68JNd)"><path class="yjqgb79zy"/></g><g filter="url(#ihWKGab)"><path stroke="url(#iPr3T3b)" class="u49b3vb3j"/></g><defs><radialGradient id="irpCsoe" cx="0" cy="0" r="1" gradientTransform="rotate(176.967 3.052 10.076)scale(3.54403 3.68531)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="c9iqmzbng"/><stop offset="1" class="dcp108bys"/><stop offset="1" class="jo8030bae"/></radialGradient><radialGradient id="ioOlUUb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.578 13.21)scale(2.01965)" gradientUnits="userSpaceOnUse"><stop class="fwffekbor"/><stop offset="1" class="r0v2vlbgk"/></radialGradient><radialGradient id="iuyrjyb" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 3.842 22.077)scale(4.7194 4.52281)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="n7lmvsb2k"/><stop offset="1" class="stwkobs1a"/></radialGradient><radialGradient id="iuOBUpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.84823 -2.07813 2.05068 1.82382 25.98 19.383)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="hbea-bc5v"/><stop offset=".883" class="l5siy7byl"/></radialGradient><radialGradient id="iodBcae" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -3.8125 2.99389 .63804 26.172 20.68)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="j8el7wzke"/><stop offset="1" class="nrbt5ebfe"/></radialGradient><radialGradient id="iyABfTr" cx="0" cy="0" r="1" gradientTransform="rotate(8.973 -113.946 177.65)scale(1.50276 2.22165)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="yuy9sybmk"/><stop offset="1" class="n92c82b9s"/></radialGradient><radialGradient id="iIUJpCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 10.00001 -3.04902 .41924 5.5 19.602)" gradientUnits="userSpaceOnUse"><stop class="nejl5yq8a"/><stop offset="1" class="aesu2cceh"/></radialGradient><radialGradient id="imrqIPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 -13.00004 20.39882 -1.96142 10.813 29.96)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="w08uk8bon"/><stop offset="1" class="nmnfd5eqz"/></radialGradient><radialGradient id="i3mpUzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 -2.625 3.5 1.875 11.063 18.383)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="p9ql87tca"/><stop offset="1" class="yno1gvw4k"/></radialGradient><radialGradient id="igwTzZE" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -2.71875 3.18328 .58543 21.375 18.633)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ryj7-4gyv"/><stop offset="1" class="cz0em3bor"/></radialGradient><radialGradient id="i3PXbun" cx="0" cy="0" r="1" gradientTransform="rotate(108.435 5.589 18.73)scale(5.73163 9.3386)" gradientUnits="userSpaceOnUse"><stop class="g3c2qj6we"/><stop offset="1" class="ae4egub9n"/></radialGradient><radialGradient id="ikBgWBc" cx="0" cy="0" r="1" gradientTransform="matrix(5.68753 3.68746 -6.9501 10.71982 5.563 8.851)" gradientUnits="userSpaceOnUse"><stop class="u9fdqbaet"/><stop offset="1" class="txg4hwwfh"/></radialGradient><radialGradient id="ikllpDq" cx="0" cy="0" r="1" gradientTransform="rotate(-106.498 17.041 4.634)scale(18.7077 27.0296)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="ae7hy4r0i"/><stop offset="1" class="ayu2969he"/></radialGradient><radialGradient id="irZZCOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 20.328 18.945)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ynn7rr4al"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="tzlh-yb0a"/></radialGradient><radialGradient id="igQrkuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.18122 0 11.358 18.945)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ynn7rr4al"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="tzlh-yb0a"/></radialGradient><radialGradient id="iw5kcJd" cx="0" cy="0" r="1" gradientTransform="matrix(7.82168 -1.52596 1.273 6.52503 12.031 6.414)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="ezvtlgcbx"/><stop offset="1" class="a3qzqqb_g"/></radialGradient><radialGradient id="irzEpoe" cx="0" cy="0" r="1" gradientTransform="rotate(-23.69 22.573 -25.21)scale(6.68877 6.45832)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="hz37rgt6h"/><stop offset=".969" class="umuzl0bbi"/></radialGradient><radialGradient id="iO93hgc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63771 -5.65242 5.82757 -3.75043 16.76 8.232)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="ga-0zkbvq"/><stop offset="1" class="gg33iht6c"/></radialGradient><radialGradient id="i5xRL4b" cx="0" cy="0" r="1" gradientTransform="rotate(57.863 3.098 16.37)scale(5.75713 5.52963)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="syes77bfe"/><stop offset=".966" class="bstw1xboe"/></radialGradient><radialGradient id="iSXsC8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 .04688 -.02424 .98567 15.36 21.695)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="jo859-bba"/><stop offset="1" class="zl44ewbhw"/></radialGradient><radialGradient id="iglyfqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.79467 0 16.133 21.086)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="aim42zngm"/><stop offset="1" class="wfzqwb0tx"/></radialGradient><radialGradient id="irbLrOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5717 -.73672 1.01428 -.7871 19.765 19.153)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idbZ8Ab" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.917 4.5)scale(1.21806 1.46416)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i1VnjcU" width="4.539" height="4.539" x="4.363" y="17.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".125"/></filter><filter id="iKmBXIb" width="4.663" height="4.663" x="23.301" y="17.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".125"/></filter><filter id="iz9oRte" width="23.65" height="26" x="4.753" y="3.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.682353 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24662"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.85098 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24662" result="effect2_innerShadow_3987_24662"/></filter><filter id="ie4VPbb" width="7.502" height="2.901" x="12.382" y="22.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".05"/></filter><filter id="iYeruae" width="7" height="2.4" x="12.633" y="23.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24662"/></filter><filter id="i4BQH9L" width="3.72" height="1.592" x="9.113" y="14.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0666667 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24662"/></filter><filter id="i9QAHDc" width="3.17" height=".992" x="9.317" y="14.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".1"/></filter><filter id="ib3QnsW" width="13.584" height="12.368" x="14.564" y="4.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation="1.25"/></filter><filter id="ia8TnFd" width="7.877" height="8.573" x="12.162" y="2.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".25"/></filter><filter id="i7PJnse" width="8.1" height="8.529" x="11.931" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.129412 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24662"/></filter><filter id="iU1WxKP" width="3.638" height="2.603" x="14.181" y="20.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".25"/></filter><filter id="iWdzDXd" width="3.138" height="2.103" x="14.564" y="20.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".125"/></filter><filter id="iUlIBRb" width="1.647" height="1.423" x="18.665" y="18.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".05"/></filter><filter id="ix4kvzQ" width="1.611" height="1.666" x="20.881" y="18.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".1"/></filter><filter id="iZFSiRd" width="1.845" height="1.978" x="11.717" y="18.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".1"/></filter><filter id="iccc4be" width="1.958" height="1.444" x="9.71" y="17.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".05"/></filter><filter id="iG68JNd" width="3.72" height="1.592" x="18.963" y="14.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0666667 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24662"/></filter><filter id="ihWKGab" width="3.17" height=".992" x="19.363" y="14.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24662" stdDeviation=".1"/></filter><linearGradient id="ilCwTAb" x1="3.906" x2="6.25" y1="17.039" y2="23.039" gradientUnits="userSpaceOnUse"><stop class="mi7u3w2ok"/><stop offset="1" class="u1966abxn"/></linearGradient><linearGradient id="iUTGkgd" x1="28.516" x2="25.933" y1="18.102" y2="22.289" gradientUnits="userSpaceOnUse"><stop class="g4x2unb_n"/><stop offset="1" class="lw4wqxbbr"/></linearGradient><linearGradient id="iV2QGwd" x1="9.5" x2="20.875" y1="16.961" y2="16.961" gradientUnits="userSpaceOnUse"><stop class="txuuu1bbi"/><stop offset="1" class="veu0oe0gg"/></linearGradient><linearGradient id="i9GgV5b" x1="16.153" x2="16.153" y1="30.539" y2="25.414" gradientUnits="userSpaceOnUse"><stop offset=".195" class="swfw66bun"/><stop offset="1" class="ojhofxb7r"/></linearGradient><linearGradient id="ikbz0qe" x1="6.938" x2="18.188" y1="18.039" y2="20.914" gradientUnits="userSpaceOnUse"><stop class="jxzf_1b9i"/><stop offset="1" class="mj66iwbmb"/></linearGradient><linearGradient id="ixEgtwe" x1="16.153" x2="16.153" y1="30.539" y2="27.039" gradientUnits="userSpaceOnUse"><stop offset=".195" class="zw7-dbbgc"/><stop offset="1" class="mmjp_rjub"/></linearGradient><linearGradient id="ilf0iXb" x1="13.797" x2="14.297" y1="25.023" y2="24.117" gradientUnits="userSpaceOnUse"><stop class="t7i9p8b0n"/><stop offset="1" class="fbge-acob"/></linearGradient><linearGradient id="iqKotpN" x1="9.668" x2="12.438" y1="15.351" y2="14.828" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="ijdAVqd" x1="18.5" x2="31.063" y1="13.414" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="wibfg_jba"/><stop offset="1" class="kgna9sqpj"/></linearGradient><linearGradient id="iu8RoZb" x1="16.456" x2="15.417" y1="3.034" y2="10.528" gradientUnits="userSpaceOnUse"><stop offset=".568" class="mcaf30bnb"/><stop offset="1" class="jezlerabr"/><stop offset="1" class="irzp_cb7o"/></linearGradient><linearGradient id="i9IjLOd" x1="22.245" x2="21.472" y1="19.078" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHk95Sb" x1="13.191" x2="12.418" y1="19.078" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPr3T3b" x1="22.047" x2="19.359" y1="15.258" y2="14.682" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-light" /></template>
<style>
.a3qzqqb_g {
  stop-color: var(--svg-color--3d3d3e, #3D3D3E);
}

.adex90brn {
  fill: var(--svg-color--da9c94, #DA9C94);
  d: path("M16.002 23.039c.51 0 .965-.28 1.225-.702c.238-.386-.011-.901-.445-.901h-1.56c-.433 0-.693.526-.444.9c.26.434.715.703 1.224.703");
}

.ae4egub9n {
  stop-color: var(--svg-color--ffddc0, #FFDDC0);
  stop-opacity: 0;
}

.ae7hy4r0i {
  stop-color: var(--svg-color--d3b19d, #D3B19D);
  stop-opacity: 0;
}

.aesu2cceh {
  stop-color: var(--svg-color--eab09a, #EAB09A);
  stop-opacity: 0;
}

.aim42zngm {
  stop-color: var(--svg-color--e0a39c, #E0A39C);
  stop-opacity: 0;
}

.ayu2969he {
  stop-color: var(--svg-color--d3b19d, #D3B19D);
}

.bstw1xboe {
  stop-color: var(--svg-color--251d20, #251D20);
}

.c9iqmzbng {
  stop-color: var(--svg-color--ecb099, #ECB099);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cz0em3bor {
  stop-color: var(--svg-color--f5b8a9, #F5B8A9);
  stop-opacity: 0;
}

.dcp108bys {
  stop-color: var(--svg-color--dda388, #DDA388);
}

.df30j9bms {
  fill: var(--svg-color--000, #000);
  d: path("M19.073 19.97c0-.7.56-1.26 1.26-1.26s1.26.56 1.26 1.26c0 .21-.05.41-.14.58h-2.23c-.1-.17-.15-.37-.15-.58m-6.46 0c0-.7-.56-1.26-1.26-1.26s-1.26.56-1.26 1.26c0 .21.05.41.14.58h2.23c.09-.17.15-.37.15-.58");
}

.drtc3eb2u {
  stroke: var(--svg-color--1f1917, #1F1917);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.613 15.12c.59-.21 1.41-.36 2.47-.26");
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.dzbw1fbmj {
  d: path("M16.135 22.69c.51 0 .964-.282 1.225-.703c.238-.386-.011-.901-.445-.901h-1.56c-.434 0-.694.527-.444.901c.26.433.715.702 1.224.702");
}

.ezvtlgcbx {
  stop-color: var(--svg-color--3d3d3e, #3D3D3E);
  stop-opacity: 0;
}

.fbge-acob {
  stop-color: var(--svg-color--deaba7, #DEABA7);
  stop-opacity: 0;
}

.fk3-b0ocx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.171 18.234c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.125");
}

.ft5dv1b6b {
  fill: none;
}

.fwffekbor {
  stop-color: var(--svg-color--cc8a77, #CC8A77);
}

.g3c2qj6we {
  stop-color: var(--svg-color--ffddc0, #FFDDC0);
}

.g4x2unb_n {
  stop-color: var(--svg-color--ffdbc1, #FFDBC1);
}

.g8knucmkh {
  d: path("M13.363 19.71c0-.71-.578-1.184-.735-1.327l-.71.687l.437.89z");
}

.ga-0zkbvq {
  stop-color: var(--svg-color--453b36, #453B36);
  stop-opacity: 0;
}

.gg33iht6c {
  stop-color: var(--svg-color--453b36, #453B36);
}

.gnsmnbsiz {
  d: path("M20.333 17.77a2.2 2.2 0 0 1 2.12 2.78h-4.25c-.05-.19-.08-.38-.08-.58c0-1.21.99-2.2 2.21-2.2");
}

.hbea-bc5v {
  stop-color: var(--svg-color--f7b899, #F7B899);
}

.hbmt10b_q {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.843 17.1c1.61 0 2.97 1.11 3.34 2.61c.11.43-.22.84-.66.84h-5.5c-.35 0-.63-.32-.56-.67c.31-1.58 1.7-2.78 3.38-2.78m-10 0c-1.61 0-2.97 1.11-3.34 2.61c-.11.43.22.84.66.84h5.5c.35 0 .63-.32.56-.67a3.454 3.454 0 0 0-3.38-2.78");
}

.hz37rgt6h {
  stop-color: var(--svg-color--443934, #443934);
}

.iey7ulbyh {
  cx: 10.689px;
  cy: 18.709px;
  rx: 0.96px;
  ry: 0.486px;
}

.ijo70fbwd {
  d: path("M25.633 23.039a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.itqfu5aet {
  d: path("M11.353 17.77a2.2 2.2 0 0 0-2.12 2.78h4.25c.05-.19.08-.38.08-.58c-.01-1.21-.99-2.2-2.21-2.2");
}

.j8el7wzke {
  stop-color: var(--svg-color--f5c9ae, #F5C9AE);
  stop-opacity: 0;
}

.jezlerabr {
  stop-color: var(--svg-color--d59471, #D59471);
}

.jo8030bae {
  stop-color: var(--svg-color--ecb099, #ECB099);
}

.jo859-bba {
  stop-color: var(--svg-color--e6afa3, #E6AFA3);
}

.jxzf_1b9i {
  stop-color: var(--svg-color--d6a091, #D6A091);
}

.kgna9sqpj {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
  stop-opacity: 0;
}

.l-rsu_beu {
  d: path("M16.252 3.006c-1.473-.222-2.757-.003-3.59 1.11c1.994 0 4.72 1.224 4.325 3.843c-.111.736-.214 1.22-.735 1.67a.492.492 0 0 0 .403.863c1.583-.303 2.61-1.438 2.845-3.13c.298-2.085-1.164-4.04-3.248-4.356");
}

.l5siy7byl {
  stop-color: var(--svg-color--f7b899, #F7B899);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw4wqxbbr {
  stop-color: var(--svg-color--ebb2a3, #EBB2A3);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcaf30bnb {
  stop-color: var(--svg-color--c49275, #C49275);
}

.mi7u3w2ok {
  stop-color: var(--svg-color--d5967d, #D5967D);
}

.mj66iwbmb {
  stop-color: var(--svg-color--d6a091, #D6A091);
  stop-opacity: 0;
}

.mmjp_rjub {
  stop-color: var(--svg-color--b47999, #B47999);
  stop-opacity: 0;
}

.n7lmvsb2k {
  stop-color: var(--svg-color--c88e90, #C88E90);
  stop-opacity: 0;
}

.n92c82b9s {
  stop-color: var(--svg-color--f6b799, #F6B799);
}

.nejl5yq8a {
  stop-color: var(--svg-color--eab09a, #EAB09A);
}

.nmnfd5eqz {
  stop-color: var(--svg-color--c48a90, #C48A90);
  stop-opacity: 0;
}

.nrbt5ebfe {
  stop-color: var(--svg-color--f5c9ae, #F5C9AE);
}

.nrujh8kqd {
  d: path("M15.831 2.04a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.o7w_zk5zp {
  d: path("m18.483 9.146l4.36-2.326c2.774 2 2.899 5.615 2.774 6.594l-5.513.75a2.679 2.679 0 0 1-1.621-5.018");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojhofxb7r {
  stop-color: var(--svg-color--bc7f90, #BC7F90);
  stop-opacity: 0;
}

.p9ql87tca {
  stop-color: var(--svg-color--ce9390, #CE9390);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qj22awqlb {
  cx: 10.689px;
  cy: 18.709px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.96px;
  ry: 0.486px;
}

.r0v2vlbgk {
  stop-color: var(--svg-color--cf8b77, #CF8B77);
}

.ryj7-4gyv {
  stop-color: var(--svg-color--f3b6a7, #F3B6A7);
}

.s70ylbbla {
  d: path("M22.292 19.68a2.07 2.07 0 0 0-.57-1.14l-.64.702l.288.563z");
}

.s8ndzosdx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.668 15.026c.59-.21 1.41-.36 2.47-.26");
}

.stwkobs1a {
  stop-color: var(--svg-color--c88e90, #C88E90);
}

.swfw66bun {
  stop-color: var(--svg-color--bc7f90, #BC7F90);
}

.syes77bfe {
  stop-color: var(--svg-color--251d20, #251D20);
  stop-opacity: 0;
}

.t7i9p8b0n {
  stop-color: var(--svg-color--deaba7, #DEABA7);
}

.t7z8qfb-u {
  d: path("M23.362 5.751a8.87 8.87 0 0 0-5.306-1.79H14.25c-1.898 0-3.755.63-5.306 1.79c-2.643 1.99-4.072 5.3-3.745 8.69l.898 8.112c.296 3.14 2.377 5.78 5.265 6.68c3.123.97 6.46.97 9.582 0c2.887-.9 4.969-3.54 5.265-6.68l.898-8.111c.326-3.39-1.102-6.7-3.745-8.69");
}

.txg4hwwfh {
  stop-color: var(--svg-color--e5b095, #E5B095);
  stop-opacity: 0;
}

.txuuu1bbi {
  stop-color: var(--svg-color--f7c2ad, #F7C2AD);
}

.tzlh-yb0a {
  stop-color: var(--svg-color--704d49, #704D49);
}

.u1966abxn {
  stop-color: var(--svg-color--ca8581, #CA8581);
}

.u49b3vb3j {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22.183 14.974c-.59-.21-1.41-.36-2.47-.26");
}

.u9fdqbaet {
  stop-color: var(--svg-color--e5b095, #E5B095);
}

.uk6dvmbah {
  fill: var(--svg-color--89024e, #89024E);
  d: path("M16.125 24.002a6.4 6.4 0 0 1-3.007-.732c-.299-.161-.617.18-.428.471a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.28-.13-.622-.428-.471a6.55 6.55 0 0 1-3.027.732");
}

.umuzl0bbi {
  stop-color: var(--svg-color--443934, #443934);
  stop-opacity: 0;
}

.veu0oe0gg {
  stop-color: var(--svg-color--ffd0ba, #FFD0BA);
}

.w08uk8bon {
  stop-color: var(--svg-color--c48a90, #C48A90);
}

.wfzqwb0tx {
  stop-color: var(--svg-color--e0a39c, #E0A39C);
}

.wibfg_jba {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
}

.wpfvvtbjo {
  d: path("M6.633 21.809a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.yblx39b-o {
  d: path("M6.633 23.039a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.yjqgb79zy {
  stroke: var(--svg-color--1f1917, #1F1917);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22.183 15.12c-.59-.21-1.41-.36-2.47-.26");
}

.yk051b8kx {
  d: path("M25.633 21.87a2.081 2.081 0 1 0 0-4.162a2.081 2.081 0 0 0 0 4.163");
}

.ymsrhk7tq {
  fill: var(--svg-color--222120, #222120);
  d: path("M15.831 2.04a4.27 4.27 0 0 0-3.8 2.22c.62-.14 1.25-.22 1.88-.22h.15c1.81 0 3.33 1.48 3.32 3.29c-.01.82-.31 1.56-.81 2.13a.542.542 0 0 0 .57.88a4.26 4.26 0 0 0 2.89-4.04c.01-2.32-1.88-4.23-4.2-4.26");
}

.ynn7rr4al {
  stop-color: var(--svg-color--865b4f, #865B4F);
}

.yno1gvw4k {
  stop-color: var(--svg-color--ce9390, #CE9390);
  stop-opacity: 0;
}

.yuy9sybmk {
  stop-color: var(--svg-color--f7bca4, #F7BCA4);
}

.zl44ewbhw {
  stop-color: var(--svg-color--ffd4bf, #FFD4BF);
}

.zs25280ps {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.153 23.203c-.367-.197-.757.223-.526.58l.063-.042a4.09 4.09 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.179-.28-.13-.622-.428-.471a6.55 6.55 0 0 1-3.027.732a6.4 6.4 0 0 1-3.007-.732z");
}

.zw7-dbbgc {
  stop-color: var(--svg-color--b47999, #B47999);
}

.zwwykac4x {
  d: path("M20.171 18.234c.157.21-.17.466-.543.744c-.373.279-.65.475-.806.265s.018-.605.39-.884c.373-.278.802-.334.959-.125");
}

</style>
