<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iI7T97c)"><path fill="url(#iyQ82we)" class="af31zpb0d"/><path fill="url(#ifgyDkb)" class="af31zpb0d"/><path fill="url(#itMJt2c)" class="af31zpb0d"/><path fill="url(#iEfLHFc)" class="af31zpb0d"/><path fill="url(#iPu2zie)" class="af31zpb0d"/><path fill="url(#ielWmNb)" class="af31zpb0d"/></g><path fill="url(#idYP94V)" class="af31zpb0d"/><path class="u9bwpabbo"/><path fill="url(#iHd15qp)" class="o-3x93b0m"/><path fill="url(#ihi74Bp)" class="o-3x93b0m"/><path fill="url(#i85ZoQd)" class="o-3x93b0m"/><path fill="url(#if2iEBb)" class="o-3x93b0m"/><g filter="url(#ilSatEj)"><path class="w95zwrbjz"/><path fill="url(#i7cxlYc)" class="f0fbhp9yx"/><path fill="url(#iF1r13b)" class="f0fbhp9yx"/><path fill="url(#i7Zci0d)" class="f0fbhp9yx"/></g><g filter="url(#ibXL2Ub)"><path class="miwwmqbrp"/><path fill="url(#it0mF8c)" class="bdydfn1qm"/><path fill="url(#i97aOyb)" class="bdydfn1qm"/><path fill="url(#i7SbiKc)" class="bdydfn1qm"/></g><g filter="url(#iTX4Ddd)"><rect transform="matrix(-1 0 0 1 24.129 23.743)" class="ljzk3pb-v"/><rect fill="url(#ir52G6c)" transform="matrix(-1 0 0 1 24.129 23.743)" class="spx4avb5u"/></g><g filter="url(#iqE5MLb)"><path class="wqcum5dmg"/><path fill="url(#iHUwX1a)" class="usttnhbcs"/><path fill="url(#iG1r2Nc)" class="usttnhbcs"/></g><g filter="url(#iMpvRbb)"><path class="crynubcyk"/><path fill="url(#ixl1pIe)" class="ksyzaeb-n"/><path fill="url(#i5T8Jic)" class="ksyzaeb-n"/></g><path fill="url(#iCjDJVd)" class="ksyzaeb-n"/><g filter="url(#igM1zDd)"><path class="ig3l7cbvh"/><path class="jqpgylbbm"/><path fill="url(#iOyMMrd)" class="in1g3hwez"/></g><path fill="url(#iZOws4D)" class="in1g3hwez"/><g filter="url(#ifQO8Qb)"><rect fill="url(#iq6tqtb)" class="nk16h7bld"/><rect fill="url(#iSkOz4c)" class="nk16h7bld"/></g><path fill="url(#iTb6UCb)" class="m_qsudb6l"/><path fill="url(#iNm0Lrb)" class="m_qsudb6l"/><g filter="url(#iNO8Jge)"><path fill="url(#i7yxuAd)" class="pxszltyjp"/></g><path fill="url(#ia6IoVb)" class="nfwqa0qct"/><path fill="url(#i2nZ12d)" class="nfwqa0qct"/><path fill="url(#iEtgKJb)" class="nfwqa0qct"/><path fill="url(#i1I9JyA)" class="nfwqa0qct"/><g filter="url(#iObIpQe)"><path fill="url(#il3ENVc)" class="m2w9adb4t"/></g><g filter="url(#iiVR7kg)"><path class="qun0utbbe"/><path fill="url(#iQ0P5ib)" class="z_zeshbfj"/><path fill="url(#i1gZndq)" class="z_zeshbfj"/><path fill="url(#ijiKsbe)" class="z_zeshbfj"/><path fill="url(#ic92wbg)" class="z_zeshbfj"/><path fill="url(#inFzq1d)" class="z_zeshbfj"/><path fill="url(#i9kELjJ)" class="z_zeshbfj"/><path fill="url(#icoY47L)" class="z_zeshbfj"/></g><path fill="url(#im8Ykab)" class="z_zeshbfj"/><g filter="url(#iQV0MWb)"><path stroke="url(#iVNUsYd)" class="u2cxhpbvc"/></g><g filter="url(#idRnqRc)"><path class="m2oi_-b6w"/></g><path class="i2gyir6hb"/><path fill="url(#i0zdGXb)" class="za_vhkb0q"/><path fill="url(#iFwAUre)" class="ktbn5wbmp"/><path class="v0f07bbqc"/><g filter="url(#iJDGC4d)"><path class="lriminx-c"/></g><g filter="url(#idEYvCc)"><path stroke="url(#iijIKcb)" class="e6jw-egmf"/></g><g filter="url(#iguChuX)"><path class="fz5-lhf3x"/></g><g filter="url(#iMowV7d)"><path stroke="url(#irviNJc)" class="fdnor7b2b"/></g><g filter="url(#iG0Paac)"><path fill="url(#ij2RvNd)" class="v1l185vsn"/></g><g filter="url(#ipgcApc)"><path class="vu12mdbei"/><path fill="url(#iiU27uc)" class="slnkgtbtd"/><path fill="url(#ioZc8sd)" class="slnkgtbtd"/><path fill="url(#i0YAAmc)" class="slnkgtbtd"/><path fill="url(#iXBmFos)" class="slnkgtbtd"/></g><g filter="url(#inOVQ2b)"><path class="f8vzw1g0n"/></g><g filter="url(#ipJ9kod)"><path fill="url(#ixJAzkd)" class="cr9f_ib3r"/><path fill="url(#ixXRULb)" class="cr9f_ib3r"/></g><g filter="url(#iOMG9De)"><path class="o3v_y_bdc"/><path fill="url(#iss9Gpd)" class="xq4jz8bqp"/></g><g filter="url(#igRzHid)"><path fill="url(#iVgiOrd)" class="r0dqso0ai"/></g><g filter="url(#ifuA0Zb)"><path fill="url(#iEc2ESK)" class="u-gllc3ei"/></g><g filter="url(#iOsUx7b)"><ellipse transform="rotate(-27.914 11.015 19.605)" class="zlv8vac-h"/><ellipse fill="url(#iO1c12h)" transform="rotate(-27.914 11.015 19.605)" class="kisbt1b6g"/></g><g filter="url(#iDfhCPe)"><path fill="url(#iQMuIwc)" class="npzm1n6vp"/></g><defs><radialGradient id="iyQ82we" cx="0" cy="0" r="1" gradientTransform="matrix(-.75003 3.6875 -9.72121 -1.97727 20.936 3.298)" gradientUnits="userSpaceOnUse"><stop class="j4e9jliyw"/><stop offset="1" class="t7aapjj0e"/></radialGradient><radialGradient id="ifgyDkb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.45 10.967 -4.146)scale(5.22735 10.6403)" gradientUnits="userSpaceOnUse"><stop class="v_ro-mcce"/><stop offset="1" class="ak0e0gbla"/></radialGradient><radialGradient id="itMJt2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.46875 -1.11569 1.02074 9.827 6.892)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="t82mlk1zf"/><stop offset="1" class="hrncwbz_t"/></radialGradient><radialGradient id="iEfLHFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 -.98438 .58816 -.61616 10.327 7.345)" gradientUnits="userSpaceOnUse"><stop class="oxnp2k1qi"/><stop offset="1" class="ih62nvbvg"/></radialGradient><radialGradient id="iPu2zie" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 1.85939 -1.34213 -1.93987 23.265 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="i2to8tbny"/><stop offset="1" class="rr59_uoqr"/></radialGradient><radialGradient id="ielWmNb" cx="0" cy="0" r="1" gradientTransform="rotate(144.605 10.247 6.894)scale(1.45673 1.05149)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="ohd-ppblk"/><stop offset="1" class="c62dirbjk"/></radialGradient><radialGradient id="idYP94V" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93752 -7.271 18.54198 -4.94092 11.718 9.756)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="op4ic3bzn"/><stop offset="1" class="uoj15rbmy"/></radialGradient><radialGradient id="ihi74Bp" cx="0" cy="0" r="1" gradientTransform="matrix(.6072 2.64774 -4.70572 1.07914 25.39 27.543)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="i85ZoQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52434 .60868 -.33593 -.28939 26.855 28.045)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iF1r13b" cx="0" cy="0" r="1" gradientTransform="matrix(.76907 2.71875 -5.8088 1.64318 26.539 25.439)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="i7Zci0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.66412 .625 -.34814 -.36993 28.395 25.954)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="i97aOyb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 2.71875 -6.83491 2.35687 27.733 23.345)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="m63xmacvx"/><stop offset=".922" class="ghrfdpdai"/></radialGradient><radialGradient id="i7SbiKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.80957 .625 -.33743 -.43707 29.996 23.86)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iHUwX1a" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 1.73438 -1.37456 -.54486 8.812 28.517)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="y7rsoxb6i"/><stop offset="1" class="i8um3jglr"/></radialGradient><radialGradient id="iG1r2Nc" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 -2.21094 5.39927 1.3355 6.765 30.142)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="bs3nz4btd"/><stop offset="1" class="qxhhvqurd"/></radialGradient><radialGradient id="ixl1pIe" cx="0" cy="0" r="1" gradientTransform="rotate(109.855 -4.82 16.2)scale(2.39221 2.36363)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="mjdwlzfcx"/><stop offset="1" class="cb_xa0byd"/></radialGradient><radialGradient id="i5T8Jic" cx="0" cy="0" r="1" gradientTransform="rotate(-69.661 23.026 9.988)scale(2.42119 7.08044)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="a-hxohb_j"/><stop offset="1" class="yi34m9bam"/></radialGradient><radialGradient id="iCjDJVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0827 3.1875 -5.20641 -1.76845 5.832 25.235)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="iZOws4D" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 3.46875 -6.65848 -2.33947 4.718 23.142)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="iq6tqtb" cx="0" cy="0" r="1" gradientTransform="rotate(122.4 -2.433 16.416)scale(1.9246 3.13561)" gradientUnits="userSpaceOnUse"><stop class="uqd9t5bdt"/><stop offset="1" class="vsxpbmbdw"/></radialGradient><radialGradient id="iNm0Lrb" cx="0" cy="0" r="1" gradientTransform="rotate(176.967 3.362 10.483)scale(3.26919 3.39952)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="wg-tntuud"/><stop offset="1" class="nihqa2baf"/></radialGradient><radialGradient id="i7yxuAd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.663 13.937)scale(1.86302)" gradientUnits="userSpaceOnUse"><stop class="wfxx9nv4c"/><stop offset="1" class="ninfq3frf"/></radialGradient><radialGradient id="i2nZ12d" cx="0" cy="0" r="1" gradientTransform="matrix(-.07207 4.35281 -4.1715 -.06906 25.12 19.505)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="odq_-wbka"/><stop offset="1" class="y9vn05b-v"/></radialGradient><radialGradient id="iEtgKJb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.351 35.088 -17.867)scale(2.56543 2.53155)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="mt_8occxo"/><stop offset=".883" class="ozb2o_bkz"/></radialGradient><radialGradient id="i1I9JyA" cx="0" cy="0" r="1" gradientTransform="rotate(-77.969 25.883 -4.917)scale(3.59582 2.82373)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="m7zyjydub"/><stop offset="1" class="oyazfkryc"/></radialGradient><radialGradient id="il3ENVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36927 .2162 -.31963 2.0243 25.427 20.745)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="krpelr-dy"/><stop offset="1" class="h0sp3fbhr"/><stop offset="1" class="dj5h63b0t"/></radialGradient><radialGradient id="ijiKsbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.26837 9.2245 -2.81258 .38673 6.229 20.428)" gradientUnits="userSpaceOnUse"><stop class="ys531713j"/><stop offset="1" class="ze0tbybyr"/></radialGradient><radialGradient id="ic92wbg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15306 -11.9919 18.81691 -1.80931 11.13 29.984)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="ks11w6lcu"/><stop offset="1" class="kfl3l4fgs"/></radialGradient><radialGradient id="inFzq1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.29721 -2.42143 3.22857 1.72962 11.36 19.303)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="y6boe1tam"/><stop offset="1" class="vq9_y_brm"/></radialGradient><radialGradient id="i9kELjJ" cx="0" cy="0" r="1" gradientTransform="rotate(-79.579 22.163 -2.764)scale(2.54997 2.98566)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="wv8qmacqf"/><stop offset="1" class="emk327bbe"/></radialGradient><radialGradient id="icoY47L" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.34388 -5.44822 0 22.804 20.86)" gradientUnits="userSpaceOnUse"><stop class="d1lzds90y"/><stop offset="1" class="uzuzhyonh"/></radialGradient><radialGradient id="i0zdGXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8449 -2.93452 0 19.907 19.822)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="zcm4rt3mf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qd5yj9hln"/></radialGradient><radialGradient id="iFwAUre" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8449 -2.93452 0 11.632 19.822)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="zcm4rt3mf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qd5yj9hln"/></radialGradient><radialGradient id="iiU27uc" cx="0" cy="0" r="1" gradientTransform="matrix(7.21511 -1.40763 1.17428 6.01902 12.253 8.263)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="qzo7cgy3w"/><stop offset="1" class="i-ygrlbjq"/></radialGradient><radialGradient id="ioZc8sd" cx="0" cy="0" r="1" gradientTransform="matrix(5.65011 -2.47909 2.39367 5.45545 12.253 8.753)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="g4qjalbqo"/><stop offset=".912" class="tkvzged3s"/></radialGradient><radialGradient id="i0YAAmc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.764 11.02 .437)scale(6.20054 6.39267)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="aj460xbwf"/><stop offset="1" class="rfngthbki"/></radialGradient><radialGradient id="iXBmFos" cx="0" cy="0" r="1" gradientTransform="matrix(2.825 4.49695 -4.31925 2.71337 15.28 6.994)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="d17xcmnsa"/><stop offset=".966" class="f5-lme9vp"/></radialGradient><radialGradient id="ixJAzkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75842 .04325 -.02236 .90924 15.327 22.365)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="ryjew175t"/><stop offset="1" class="b3obg0rjr"/></radialGradient><radialGradient id="ixXRULb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.31161 -1.65549 0 16.037 21.797)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="vvvztm6zj"/><stop offset="1" class="fyf7sp4uy"/></radialGradient><radialGradient id="iss9Gpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52737 -.67959 .93563 -.72606 19.388 20.014)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iO1c12h" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 15.493 4.755)scale(1.1236 1.35062)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iI7T97c" width="17.94" height="7.94" x="7.011" y="1.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.596078 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="ilSatEj" width="7.412" height="2.194" x="20.982" y="25.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="ibXL2Ub" width="9.014" height="2.194" x="20.982" y="23.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="iTX4Ddd" width="4.369" height="6.627" x="20.16" y="23.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.54902 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="iqE5MLb" width="6.273" height="2.439" x="4.645" y="27.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.541176 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="iMpvRbb" width="7.813" height="2.494" x="3.105" y="25.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="igM1zDd" width="9.414" height="2.494" x="1.504" y="23.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="ifQO8Qb" width="4.369" height="6.627" x="7.471" y="23.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.54902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="iNO8Jge" width="4.226" height="4.226" x="5.161" y="18.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".125"/></filter><filter id="iObIpQe" width="4.34" height="4.34" x="22.63" y="18.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".125"/></filter><filter id="iiVR7kg" width="21.944" height="23.984" x="5.508" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.47451 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22282" result="effect2_innerShadow_3987_22282"/></filter><filter id="iQV0MWb" width="6.959" height="2.715" x="12.557" y="23.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".05"/></filter><filter id="idRnqRc" width="6.457" height="2.214" x="12.808" y="23.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="iJDGC4d" width="3.529" height="1.569" x="9.522" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.121569 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="idEYvCc" width="2.979" height=".969" x="9.723" y="15.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".1"/></filter><filter id="iguChuX" width="3.529" height="1.569" x="18.589" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.141176 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="iMowV7d" width="2.979" height=".969" x="18.989" y="15.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".1"/></filter><filter id="iG0Paac" width="7.343" height="8.12" x="12.335" y="4.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".25"/></filter><filter id="ipgcApc" width="7.48" height="7.883" x="12.153" y="4.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.129412 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22282"/></filter><filter id="inOVQ2b" width="3.434" height="2.479" x="14.197" y="21.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".25"/></filter><filter id="ipJ9kod" width="2.934" height="1.979" x="14.57" y="21.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".125"/></filter><filter id="iOMG9De" width="1.534" height="1.329" x="18.365" y="18.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".05"/></filter><filter id="igRzHid" width="1.517" height="1.567" x="20.402" y="19.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".1"/></filter><filter id="ifuA0Zb" width="1.733" height="1.856" x="11.948" y="19.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".1"/></filter><filter id="iOsUx7b" width="1.821" height="1.347" x="10.104" y="18.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation=".05"/></filter><filter id="iDfhCPe" width="12.918" height="11.797" x="14.396" y="6.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22282" stdDeviation="1.25"/></filter><linearGradient id="iHd15qp" x1="24.585" x2="24.585" y1="30.192" y2="28.698" gradientUnits="userSpaceOnUse"><stop offset=".079" class="ja2ta5btn"/><stop offset="1" class="oci36vbzb"/></linearGradient><linearGradient id="if2iEBb" x1="24.436" x2="24.436" y1="27.931" y2="28.329" gradientUnits="userSpaceOnUse"><stop class="quz6sacji"/><stop offset="1" class="hw65_7bjg"/></linearGradient><linearGradient id="i7cxlYc" x1="25.518" x2="25.518" y1="27.931" y2="26.884" gradientUnits="userSpaceOnUse"><stop offset=".216" class="e6rsc3sik"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="it0mF8c" x1="26.49" x2="26.49" y1="25.837" y2="24.79" gradientUnits="userSpaceOnUse"><stop offset=".216" class="rhghrobxp"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="ir52G6c" x1="0" x2=".958" y1="5.398" y2="5.398" gradientUnits="userSpaceOnUse"><stop class="lwh7ev7yo"/><stop offset="1" class="lesqr_bdp"/></linearGradient><linearGradient id="iOyMMrd" x1="6.461" x2="6.461" y1="23.743" y2="24.626" gradientUnits="userSpaceOnUse"><stop class="gjp7xwfce"/><stop offset="1" class="lo1zrhbvw"/></linearGradient><linearGradient id="iSkOz4c" x1="7.871" x2="9.124" y1="29.142" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="gw5f7-xty"/><stop offset="1" class="v8imspx_m"/></linearGradient><linearGradient id="iTb6UCb" x1="4.759" x2="6.921" y1="18.064" y2="23.599" gradientUnits="userSpaceOnUse"><stop class="ayvhgf5zf"/><stop offset="1" class="yesg_ogxc"/></linearGradient><linearGradient id="ia6IoVb" x1="27.459" x2="25.077" y1="19.044" y2="22.907" gradientUnits="userSpaceOnUse"><stop class="ftn-nj88l"/><stop offset="1" class="tjrs2-6ue"/></linearGradient><linearGradient id="iQ0P5ib" x1="16.055" x2="16.055" y1="30.517" y2="25.789" gradientUnits="userSpaceOnUse"><stop offset=".195" class="lpw6rzl4p"/><stop offset="1" class="dv66n_pwa"/></linearGradient><linearGradient id="i1gZndq" x1="7.555" x2="17.932" y1="18.986" y2="21.638" gradientUnits="userSpaceOnUse"><stop class="ipusrib9d"/><stop offset="1" class="csf9q1tkj"/></linearGradient><linearGradient id="im8Ykab" x1="16.055" x2="16.055" y1="30.517" y2="27.288" gradientUnits="userSpaceOnUse"><stop offset=".195" class="wr40bdb9p"/><stop offset="1" class="dv66n_pwa"/></linearGradient><linearGradient id="iVNUsYd" x1="13.882" x2="14.343" y1="25.429" y2="24.593" gradientUnits="userSpaceOnUse"><stop class="w2gkbnbqe"/><stop offset="1" class="d0-zinb4r"/></linearGradient><linearGradient id="iijIKcb" x1="12.715" x2="9.789" y1="15.83" y2="16.207" gradientUnits="userSpaceOnUse"><stop class="vd4_eobzz"/><stop offset="1" class="aan57zrte"/></linearGradient><linearGradient id="irviNJc" x1="21.981" x2="19.055" y1="15.782" y2="16.159" gradientUnits="userSpaceOnUse"><stop class="vd4_eobzz"/><stop offset="1" class="aan57zrte"/></linearGradient><linearGradient id="ij2RvNd" x1="16.335" x2="15.377" y1="5.145" y2="12.058" gradientUnits="userSpaceOnUse"><stop offset=".709" class="z4tn41bcd"/><stop offset="1" class="jq3hskb9d"/></linearGradient><linearGradient id="iVgiOrd" x1="21.676" x2="20.962" y1="19.945" y2="20.384" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEc2ESK" x1="13.324" x2="12.61" y1="19.945" y2="20.384" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQMuIwc" x1="17.579" x2="26.523" y1="15.729" y2="10.338" gradientUnits="userSpaceOnUse"><stop class="vsbipxzeq"/><stop offset="1" class="vl9mo9edt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-angel-medium" /></template>
<style>
.a-hxohb_j {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
  stop-opacity: 0;
}

.aan57zrte {
  stop-color: var(--svg-color--543d3e, #543D3E);
  stop-opacity: 0;
}

.af31zpb0d {
  d: path("M15.972 3.516c2.16 0 4.26.37 5.75 1.01c1.25.54 1.72 1.12 1.72 1.36s-.47.82-1.72 1.36c-1.49.64-3.58 1.01-5.75 1.01s-4.26-.36-5.74-1c-1.26-.54-1.72-1.13-1.72-1.37s.47-.82 1.72-1.36c1.48-.64 3.58-1.01 5.74-1.01m0-1.5c-4.95 0-8.96 1.73-8.96 3.87s4.01 3.87 8.97 3.87s8.97-1.73 8.97-3.87s-4.02-3.87-8.98-3.87");
}

.aj460xbwf {
  stop-color: var(--svg-color--3e3431, #3E3431);
  stop-opacity: 0;
}

.ak0e0gbla {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
  stop-opacity: 0;
}

.ayvhgf5zf {
  stop-color: var(--svg-color--7c554f, #7C554F);
}

.b3obg0rjr {
  stop-color: var(--svg-color--ca9f87, #CA9F87);
}

.bdydfn1qm {
  d: path("M29.996 24.242a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.bs3nz4btd {
  stop-color: var(--svg-color--e7cbd8, #E7CBD8);
  stop-opacity: 0;
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

.cr9f_ib3r {
  d: path("M16.04 23.276c.469 0 .889-.26 1.129-.648c.22-.356-.01-.831-.41-.831h-1.44c-.4 0-.64.486-.41.831c.24.4.66.648 1.13.648");
}

.crynubcyk {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M3.605 26.335c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.596");
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

.dj5h63b0t {
  stop-color: var(--svg-color--9d6959, #9D6959);
}

.dv66n_pwa {
  stop-color: var(--svg-color--9a5886, #9A5886);
  stop-opacity: 0;
}

.e6jw-egmf {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.073 16.207c.544-.194 1.3-.333 2.278-.24");
}

.e6rsc3sik {
  stop-color: var(--svg-color--c6bec8, #C6BEC8);
}

.emk327bbe {
  stop-color: var(--svg-color--ad7974, #AD7974);
  stop-opacity: 0;
}

.f0fbhp9yx {
  d: path("M28.395 26.335a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.715 1.596-1.596");
}

.f5-lme9vp {
  stop-color: var(--svg-color--3b212b, #3B212B);
}

.f8vzw1g0n {
  fill: var(--svg-color--905966, #905966);
  d: path("M15.917 23.599c.47 0 .89-.26 1.129-.648c.22-.356-.01-.831-.41-.831h-1.44c-.399 0-.639.485-.409.83c.24.4.66.649 1.13.649");
}

.fdnor7b2b {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.618 16.159c-.544-.194-1.3-.333-2.279-.24");
}

.fr51zgblk {
  stop-color: var(--svg-color--f7f1f1, #F7F1F1);
  stop-opacity: 0;
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

.fz5-lhf3x {
  stroke: var(--svg-color--4c3230, #4C3230);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M21.618 16.293c-.544-.194-1.3-.332-2.279-.24");
}

.g4qjalbqo {
  stop-color: var(--svg-color--483431, #483431);
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

.hrncwbz_t {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
  stop-opacity: 0;
}

.hw65_7bjg {
  stop-color: var(--svg-color--feeeec, #FEEEEC);
  stop-opacity: 0;
}

.i-ygrlbjq {
  stop-color: var(--svg-color--584444, #584444);
}

.i2gyir6hb {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.382 18.12a3.176 3.176 0 0 1 3.08 2.407a.623.623 0 0 1-.608.775H17.78a.523.523 0 0 1-.516-.618a3.18 3.18 0 0 1 3.118-2.564m-9.225 0a3.176 3.176 0 0 0-3.08 2.407a.623.623 0 0 0 .608.775h5.074a.523.523 0 0 0 .516-.618a3.186 3.186 0 0 0-3.118-2.564");
}

.i2to8tbny {
  stop-color: var(--svg-color--4997c1, #4997C1);
}

.i8um3jglr {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
  stop-opacity: 0;
}

.ig3l7cbvh {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M2.004 24.242c0-.276.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.ih62nvbvg {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
  stop-opacity: 0;
}

.in1g3hwez {
  d: path("M2.004 24.242c0-.276.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.ipusrib9d {
  stop-color: var(--svg-color--916f5c, #916F5C);
}

.j4e9jliyw {
  stop-color: var(--svg-color--4de2ff, #4DE2FF);
}

.ja2ta5btn {
  stop-color: var(--svg-color--9a84af, #9A84AF);
}

.jq3hskb9d {
  stop-color: var(--svg-color--81554e, #81554E);
}

.jqpgylbbm {
  fill: var(--svg-color--f1d2d6, #F1D2D6);
  d: path("M2.004 24.242c0-.276.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.kfl3l4fgs {
  stop-color: var(--svg-color--935c6f, #935C6F);
  stop-opacity: 0;
}

.ki9dlqbnk {
  stop-color: var(--svg-color--d4c7cd, #D4C7CD);
  stop-opacity: 0;
}

.kisbt1b6g {
  cx: 11.015px;
  cy: 19.605px;
  rx: 0.886px;
  ry: 0.448px;
}

.krpelr-dy {
  stop-color: var(--svg-color--b08471, #B08471);
}

.ks11w6lcu {
  stop-color: var(--svg-color--935c6f, #935C6F);
}

.ksyzaeb-n {
  d: path("M3.605 26.335c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.596");
}

.ktbn5wbmp {
  d: path("M11.628 18.738a2.03 2.03 0 0 0-1.956 2.564h3.92a2 2 0 0 0 .074-.535a2.043 2.043 0 0 0-2.039-2.03");
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

.lpw6rzl4p {
  stop-color: var(--svg-color--9a5886, #9A5886);
}

.lriminx-c {
  stroke: var(--svg-color--472d2c, #472D2C);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M10.023 16.293c.544-.194 1.3-.332 2.278-.24");
}

.lwh7ev7yo {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
}

.m_qsudb6l {
  d: path("M7.274 23.599a2.998 2.998 0 1 0 0-5.996a2.998 2.998 0 0 0 0 5.996");
}

.m2oi_-b6w {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.03 24.487a5.9 5.9 0 0 1-2.774-.676c-.276-.148-.57.167-.395.435a3.77 3.77 0 0 0 3.178 1.741a3.79 3.79 0 0 0 3.178-1.74c.165-.26-.12-.575-.395-.436a6.04 6.04 0 0 1-2.793.676");
}

.m2w9adb4t {
  d: path("M24.8 22.52a1.92 1.92 0 1 0 0-3.84a1.92 1.92 0 0 0 0 3.84");
}

.m63xmacvx {
  stop-color: var(--svg-color--cebfd0, #CEBFD0);
  stop-opacity: 0;
}

.m7zyjydub {
  stop-color: var(--svg-color--bc987a, #BC987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.miwwmqbrp {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M29.996 24.242a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.mjdwlzfcx {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
}

.mm6hvvbia {
  stop-color: var(--svg-color--a797b5, #A797B5);
}

.mt_8occxo {
  stop-color: var(--svg-color--9b6859, #9B6859);
}

.nfwqa0qct {
  d: path("M24.8 23.599a2.998 2.998 0 1 0 0-5.996a2.998 2.998 0 0 0 0 5.996");
}

.nihqa2baf {
  stop-color: var(--svg-color--9d7668, #9D7668);
}

.ninfq3frf {
  stop-color: var(--svg-color--744745, #744745);
}

.nk16h7bld {
  width: 3.969px;
  height: 6.227px;
  x: 7.871px;
  y: 23.743px;
  rx: 1px;
}

.npzm1n6vp {
  d: path("m18.205 10.783l4.023-2.145c2.557 1.845 2.673 5.179 2.557 6.082l-5.084.692a2.471 2.471 0 0 1-1.496-4.629");
}

.o-3x93b0m {
  d: path("M26.856 28.416a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.o3v_y_bdc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.762 19.167c.145.193-.158.429-.501.686c-.344.256-.599.437-.743.244s.016-.558.36-.815s.74-.309.884-.115");
}

.oci36vbzb {
  stop-color: var(--svg-color--c4b7cf, #C4B7CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odq_-wbka {
  stop-color: var(--svg-color--935977, #935977);
  stop-opacity: 0;
}

.ohd-ppblk {
  stop-color: var(--svg-color--439fb2, #439FB2);
}

.op4ic3bzn {
  stop-color: var(--svg-color--43acc0, #43ACC0);
  stop-opacity: 0;
}

.oxnp2k1qi {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
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

.pxszltyjp {
  d: path("M7.274 22.464a1.863 1.863 0 1 0 0-3.726a1.863 1.863 0 0 0 0 3.726");
}

.qd5yj9hln {
  stop-color: var(--svg-color--6f4b49, #6F4B49);
}

.qun0utbbe {
  fill: var(--svg-color--c49380, #C49380);
  d: path("M22.706 7.651A8.18 8.18 0 0 0 17.81 6H14.3c-1.75 0-3.464.581-4.895 1.651c-2.438 1.836-3.755 4.89-3.454 8.017l.828 7.482c.273 2.897 2.193 5.332 4.857 6.163a14.9 14.9 0 0 0 8.839 0c2.663-.83 4.584-3.266 4.857-6.163l.828-7.482c.301-3.127-1.017-6.18-3.454-8.017");
}

.quz6sacji {
  stop-color: var(--svg-color--cfcacf, #CFCACF);
}

.qxhhvqurd {
  stop-color: var(--svg-color--bfa9ad, #BFA9AD);
}

.qzo7cgy3w {
  stop-color: var(--svg-color--584444, #584444);
  stop-opacity: 0;
}

.r0dqso0ai {
  d: path("M21.719 20.5a1.9 1.9 0 0 0-.526-1.052l-.591.648l.267.519z");
}

.rfngthbki {
  stop-color: var(--svg-color--3e3431, #3E3431);
}

.rhghrobxp {
  stop-color: var(--svg-color--d3c5cf, #D3C5CF);
}

.rr59_uoqr {
  stop-color: var(--svg-color--4997c1, #4997C1);
  stop-opacity: 0;
}

.ryjew175t {
  stop-color: var(--svg-color--aa816e, #AA816E);
}

.s781d-sgv {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
}

.slnkgtbtd {
  d: path("M15.759 4.227a3.94 3.94 0 0 0-3.506 2.048a8 8 0 0 1 1.735-.203h.138c1.67 0 3.072 1.365 3.063 3.035a3 3 0 0 1-.748 1.965a.5.5 0 0 0 .526.812a3.93 3.93 0 0 0 2.666-3.727c.01-2.14-1.734-3.902-3.874-3.93");
}

.spx4avb5u {
  width: 3.969px;
  height: 6.227px;
  rx: 1px;
}

.t7aapjj0e {
  stop-color: var(--svg-color--33aed4, #33AED4);
}

.t82mlk1zf {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
}

.tjrs2-6ue {
  stop-color: var(--svg-color--ae7e73, #AE7E73);
}

.tkvzged3s {
  stop-color: var(--svg-color--483431, #483431);
  stop-opacity: 0;
}

.u-gllc3ei {
  d: path("M13.482 20.529c0-.656-.534-1.093-.678-1.226l-.656.635l.404.821z");
}

.u2cxhpbvc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.291 23.745c-.344-.185-.71.209-.493.542l.063-.04z");
}

.u9bwpabbo {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M26.856 28.416a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
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

.usttnhbcs {
  d: path("M5.145 28.416c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.uzuzhyonh {
  stop-color: var(--svg-color--c5977d, #C5977D);
  stop-opacity: 0;
}

.v_ro-mcce {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
}

.v0f07bbqc {
  fill: var(--svg-color--000, #000);
  d: path("M18.749 20.767c0-.646.517-1.162 1.162-1.162c.646 0 1.163.516 1.163 1.162c0 .194-.047.378-.13.535h-2.057a1.05 1.05 0 0 1-.138-.535m-5.959 0c0-.646-.517-1.162-1.162-1.162c-.646 0-1.163.516-1.163 1.162c0 .194.046.378.13.535h2.057c.083-.157.138-.341.138-.535");
}

.v1l185vsn {
  d: path("M16.147 5.12c-1.358-.206-2.543-.003-3.312 1.024c1.84 0 4.355 1.128 3.99 3.544a2.74 2.74 0 0 1-.917 1.675a.454.454 0 0 0 .372.796a3.57 3.57 0 0 0 2.863-3.021c.275-1.924-1.074-3.727-2.996-4.019");
}

.v8imspx_m {
  stop-color: var(--svg-color--dac4cc, #DAC4CC);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vd4_eobzz {
  stop-color: var(--svg-color--543d3e, #543D3E);
}

.vl9mo9edt {
  stop-color: var(--svg-color--c99f8b, #C99F8B);
  stop-opacity: 0;
}

.vq9_y_brm {
  stop-color: var(--svg-color--8e5a67, #8E5A67);
  stop-opacity: 0;
}

.vsbipxzeq {
  stop-color: var(--svg-color--c99f8b, #C99F8B);
}

.vsxpbmbdw {
  stop-color: var(--svg-color--dcbdc9, #DCBDC9);
}

.vu12mdbei {
  fill: var(--svg-color--402b29, #402B29);
  d: path("M15.759 4.227a3.94 3.94 0 0 0-3.506 2.048a8 8 0 0 1 1.735-.203h.138c1.67 0 3.072 1.365 3.063 3.035a3 3 0 0 1-.748 1.965a.5.5 0 0 0 .526.812a3.93 3.93 0 0 0 2.666-3.727c.01-2.14-1.734-3.902-3.874-3.93");
}

.vvvztm6zj {
  stop-color: var(--svg-color--96596f, #96596F);
  stop-opacity: 0;
}

.w2gkbnbqe {
  stop-color: var(--svg-color--ab807d, #AB807D);
}

.w95zwrbjz {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M28.395 26.335a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.715 1.596-1.596");
}

.wfxx9nv4c {
  stop-color: var(--svg-color--744c4d, #744C4D);
}

.wg-tntuud {
  stop-color: var(--svg-color--9d7668, #9D7668);
  stop-opacity: 0;
}

.wqcum5dmg {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M5.145 28.416c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.wr40bdb9p {
  stop-color: var(--svg-color--985683, #985683);
}

.wv8qmacqf {
  stop-color: var(--svg-color--ad7974, #AD7974);
}

.xq4jz8bqp {
  d: path("M19.762 19.167c.145.193-.158.429-.501.686c-.344.256-.599.437-.743.244s.016-.558.36-.815s.74-.309.884-.115");
}

.y6boe1tam {
  stop-color: var(--svg-color--8e5a67, #8E5A67);
}

.y7rsoxb6i {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
}

.y9vn05b-v {
  stop-color: var(--svg-color--935977, #935977);
}

.yesg_ogxc {
  stop-color: var(--svg-color--864d67, #864D67);
}

.yi34m9bam {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
}

.ys531713j {
  stop-color: var(--svg-color--9c7469, #9C7469);
}

.z_zeshbfj {
  d: path("M22.706 7.651A8.18 8.18 0 0 0 17.81 6H14.3c-1.75 0-3.464.581-4.895 1.651c-2.438 1.836-3.755 4.89-3.454 8.017l.828 7.482c.273 2.897 2.193 5.332 4.857 6.163a14.9 14.9 0 0 0 8.839 0c2.663-.83 4.584-3.266 4.857-6.163l.828-7.482c.301-3.127-1.017-6.18-3.454-8.017");
}

.z4tn41bcd {
  stop-color: var(--svg-color--614635, #614635);
}

.za_vhkb0q {
  d: path("M19.911 18.738a2.03 2.03 0 0 1 1.956 2.564h-3.92a2 2 0 0 1-.074-.535c0-1.116.913-2.03 2.038-2.03");
}

.zcm4rt3mf {
  stop-color: var(--svg-color--835a50, #835A50);
}

.ze0tbybyr {
  stop-color: var(--svg-color--9c7469, #9C7469);
  stop-opacity: 0;
}

.zlv8vac-h {
  cx: 11.015px;
  cy: 19.605px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.886px;
  ry: 0.448px;
}

</style>
