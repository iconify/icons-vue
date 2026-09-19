<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i1FP2He)" class="hi5n24owa"/><path fill="url(#iXGwAFd)" class="j7-lx-buf"/><path class="m15k4yz6i"/><path fill="url(#iXGJFEd)" class="kpw-d1bli"/><path fill="url(#iApFAXd)" class="toc3mjbcb"/><path fill="url(#i6kHG7d)" class="toc3mjbcb"/><path fill="url(#i6CCOue)" class="hrm61ulxz"/><path fill="url(#i1LZgJN)" class="hrm61ulxz"/><path fill="url(#iGiEnRb)" class="hrm61ulxz"/><g filter="url(#ikYdAKe)"><path fill="url(#i7uo4Be)" class="gvv34ibsn"/><path fill="url(#itGy8Fc)" class="gvv34ibsn"/></g><path fill="url(#iLYsQ8c)" class="gvv34ibsn"/><path fill="url(#iWrhjjb)" class="gvv34ibsn"/><g filter="url(#i4VXZEG)"><path fill="url(#iOggUJb)" class="s8wwykopu"/></g><path fill="url(#iREfs9l)" class="mbtutfv6l"/><path fill="url(#iPhC8oe)" class="mbtutfv6l"/><g filter="url(#i3L3zkC)"><path class="beoi27bcu"/></g><g filter="url(#i86f0kb)"><path class="h6z8hobkh"/></g><g filter="url(#iKF3yHb)"><path class="dleyoln5x"/></g><g filter="url(#iTA18sb)"><path fill="url(#iyOmAwc)" class="jy18srelc"/></g><g filter="url(#iTHuqme)"><path fill="url(#isflWdd)" class="hmjk95b9j"/></g><g filter="url(#i6rkoqd)"><path fill="url(#i9wpO8b)" class="o2hkdibzn"/></g><path fill="url(#iRiGhid)" class="qw3_czmna"/><path fill="url(#ixbxRAd)" class="qw3_czmna"/><path fill="url(#iw6Kvsg)" class="z_tmohbaf"/><path fill="url(#iJYb5Hd)" class="daz2wrb4j"/><g filter="url(#igr9YXd)"><path fill="url(#iOQUSEX)" class="wir9txusx"/><path fill="url(#i0ediPb)" class="wir9txusx"/></g><path fill="url(#iPIXyBb)" class="wir9txusx"/><path fill="url(#iVskYKn)" class="wir9txusx"/><path fill="url(#i6w6JMe)" class="wir9txusx"/><path fill="url(#i1piJDb)" class="wir9txusx"/><path fill="url(#iz432Mb)" class="wir9txusx"/><path fill="url(#ith93hc)" class="wir9txusx"/><path fill="url(#igDxvxc)" class="wir9txusx"/><path fill="url(#iKW9Nld)" class="wir9txusx"/><g filter="url(#iimS7Db)"><path class="yf96yoa0h"/></g><g filter="url(#iJXtx0b)"><path class="kg6j19b7w"/><path fill="url(#iLcYHvd)" class="t4ycnmrng"/><path fill="url(#i6uCllc)" class="t4ycnmrng"/><path fill="url(#i6LNTFb)" class="t4ycnmrng"/><path fill="url(#iZ4oV1t)" class="t4ycnmrng"/><path fill="url(#iAHGjIb)" class="t4ycnmrng"/></g><g filter="url(#iOXqX5b)"><path stroke="url(#iO34Xte)" class="o-gay1b3i"/></g><path fill="url(#ieN58ce)" class="vmgtc1ecl"/><g filter="url(#ioWcw5d)"><path class="tddkrwb-v"/></g><g filter="url(#imiu07c)"><path class="u91v0ebbj"/></g><path class="r9v3grw-v"/><path fill="url(#i9USYne)" class="z2t4-fbkt"/><path class="ak2ynqn6o"/><g filter="url(#iZ7GhTc)"><path class="paq1r_bcl"/><path fill="url(#inpjh6W)" class="c10x5bcsu"/></g><g filter="url(#inIrp7d)"><path fill="url(#iZZr1kc)" class="ttlvurbri"/></g><path class="cgwmhgbmz"/><path fill="url(#iR88IHd)" class="zi7ici7iu"/><path class="q2-xacyrz"/><g filter="url(#ioLvDxf)"><path fill="url(#iyZbMYd)" class="kc__dv0sq"/></g><g filter="url(#iTdZ3ce)"><ellipse transform="rotate(-27.914 13.193 9.868)" class="zvrj6jbon"/><ellipse fill="url(#i4bHrUk)" transform="rotate(-27.914 13.193 9.868)" class="ca-kocctu"/></g><path fill="url(#iXOeGXt)" class="r0zatwb2r"/><path fill="url(#img7rnq)" class="r0zatwb2r"/><path fill="url(#iqphrDd)" class="r0zatwb2r"/><path fill="url(#ifN7Urb)" class="r0zatwb2r"/><path fill="url(#iQKMCqe)" class="wxvfeccof"/><path fill="url(#iMd8Kpc)" class="wxvfeccof"/><g filter="url(#icvfhac)"><path fill="url(#iuTupFe)" class="mgyw9iept"/></g><g filter="url(#iDxRamc)"><path fill="url(#iAlRame)" class="op2t_gg2x"/></g><g filter="url(#iQOyVOe)"><path class="m1qbrybjx"/></g><g filter="url(#i27wLoc)"><path class="wl_jqnblm"/></g><g filter="url(#ity6V1d)"><path fill="url(#iUs9Sac)" class="g2a8vhbns"/><path fill="url(#iulCiIb)" class="g2a8vhbns"/></g><path fill="url(#i7P9oSl)" class="uxt3imbne"/><path fill="url(#iIt5XUJ)" class="uxt3imbne"/><g filter="url(#iNIaxJc)"><path fill="url(#iK1SIgL)" clip-rule="evenodd" class="mhf6g8b4g"/></g><g filter="url(#iRJYUId)"><path fill="url(#iX3JT4r)" clip-rule="evenodd" class="ozqls6q-b"/></g><g filter="url(#ixw1HPd)"><path fill="url(#i2lq7ec)" class="bh63c6z5s"/></g><path fill="url(#i4jWYid)" class="is4qt5bjz"/><path fill="url(#iBByOEe)" class="is4qt5bjz"/><path fill="url(#i2lKm4b)" class="is4qt5bjz"/><path fill="url(#ihDEVgd)" class="qgc7u1v2q"/><path fill="url(#iEWOOjl)" class="qgc7u1v2q"/><path fill="url(#iJh6DXd)" class="qgc7u1v2q"/><path fill="url(#ivyZ2Pd)" class="qgc7u1v2q"/><g filter="url(#iTtgkUa)"><path fill="url(#icIpgIc)" class="v1m3xdvgj"/></g><g filter="url(#iqtrKzd)"><path class="sadlm6lao"/><path fill="url(#iwXrrEq)" class="x6cxz4mml"/></g><g filter="url(#i7Qc7qd)"><ellipse fill="url(#iCS2BLb)" class="z__b2obbo"/></g><g filter="url(#iUyzece)"><path fill="url(#incyxSc)" class="sierzcbjv"/><path fill="url(#ibWmTGb)" class="sierzcbjv"/><path fill="url(#i1c9nEe)" class="sierzcbjv"/><path fill="url(#iLz01Cc)" class="sierzcbjv"/><path fill="url(#i7GxKLb)" class="sierzcbjv"/></g><g filter="url(#iyRASFd)"><path stroke="url(#iuQML5c)" class="g7beg1b7x"/></g><g filter="url(#iPXmRud)"><path stroke="url(#iprFTwD)" class="d4i9tqbhe"/></g><g filter="url(#i4Pt4KR)"><path stroke="url(#i5FfYLe)" class="vsb_6zy7g"/></g><defs><radialGradient id="iXGJFEd" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.724 57.512)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="i6kHG7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.684 30.202)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="iGiEnRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.125 30.706)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="i7uo4Be" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.726 19.677)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="itGy8Fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.39 32.45)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="iLYsQ8c" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.5 16.027)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iREfs9l" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 8.994 10.107)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iPhC8oe" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.603 8.617)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="fjyr3161v"/><stop offset="1" class="vuu318b4c"/></radialGradient><radialGradient id="iRiGhid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59797 1.31329 -1.29023 -1.56991 27.622 23.69)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="ixbxRAd" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.386 23.538)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iw6Kvsg" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.705 20.57)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iJYb5Hd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.59 12.31)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iOQUSEX" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26686 0 0 -9.24801 18.479 10.88)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i0ediPb" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.39 8.033)scale(3.37573 2.79652)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iVskYKn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.43169 0 18.115 9.566)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i6w6JMe" cx="0" cy="0" r="1" gradientTransform="matrix(.00395 -1.09427 1.19972 .00433 13.332 9.613)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i1piJDb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.55937 .53641 -1.36019 -21.70422 19.108 11.867)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iz432Mb" cx="0" cy="0" r="1" gradientTransform="matrix(3.41105 -2.91647 .8605 1.00643 8.808 8.146)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ith93hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23643 2.49743 -1.00564 -.0952 21.236 7.962)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="igDxvxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.09375 -12.2181 0 15.697 8.281)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="qoe9pbqhg"/><stop offset="1" class="gzsdakb9r"/></radialGradient><radialGradient id="iKW9Nld" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5625 -7.75972 0 15.697 6.812)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="zhltjbs8q"/><stop offset="1" class="g62mlfbwr"/></radialGradient><radialGradient id="i6uCllc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.113 12.24)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iZ4oV1t" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.23 11.67)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ieN58ce" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.156 14.503)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i9USYne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.829 9.963)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="inpjh6W" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.26 .714)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iR88IHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.465 9.963)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i4bHrUk" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.178 10.182)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="img7rnq" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.264 9.977)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iqphrDd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.625 10.522)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ifN7Urb" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.739 10.694)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iMd8Kpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.84893 10.731 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iuTupFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 10.78 10.622)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iUs9Sac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.531 6.05)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iulCiIb" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.344 2.893)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="i7P9oSl" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 18.781 7.3)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><radialGradient id="i4jWYid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.86 19.284)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iBByOEe" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.219 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="i2lKm4b" cx="0" cy="0" r="1" gradientTransform="matrix(.6856 -1.32813 .78813 .40685 14.33 20.456)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="ihDEVgd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.196 18.575)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iJh6DXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.75 18.877)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="ivyZ2Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.688 21.284)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iwXrrEq" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.697 11.242)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="via-_dbpm"/><stop offset="1" class="bt1_2zb2r"/></radialGradient><radialGradient id="iCS2BLb" cx="0" cy="0" r="1" gradientTransform="matrix(2.27907 0 0 3.27907 24.419 17.893)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="uelaalb7d"/><stop offset=".746" class="i5m4wsx9z"/></radialGradient><radialGradient id="ibWmTGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.74 25.275)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i1c9nEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.74 26.57)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iLz01Cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.74 27.82)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i7GxKLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.74 29.17)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><filter id="ikYdAKe" width="14.3" height="12.3" x="8.372" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/></filter><filter id="i4VXZEG" width="6.538" height="5.771" x="12.014" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".325"/></filter><filter id="i3L3zkC" width="2.5" height="2.5" x="18.462" y="27.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".25"/></filter><filter id="i86f0kb" width="2.5" height="2.5" x="18.462" y="23.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".25"/></filter><filter id="iKF3yHb" width="2.5" height="2.5" x="18.462" y="19.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".25"/></filter><filter id="iTA18sb" width="1.7" height="1.7" x="19.132" y="27.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1877" result="effect2_innerShadow_4002_1877"/></filter><filter id="iTHuqme" width="1.7" height="1.7" x="19.132" y="23.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1877" result="effect2_innerShadow_4002_1877"/></filter><filter id="i6rkoqd" width="1.7" height="1.7" x="19.132" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1877" result="effect2_innerShadow_4002_1877"/></filter><filter id="igr9YXd" width="11.297" height="12.542" x="10.549" y="4.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1877" result="effect2_innerShadow_4002_1877"/></filter><filter id="iimS7Db" width="3.877" height="4.9" x="13.501" y="9.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".5"/></filter><filter id="iJXtx0b" width="2.277" height="3.3" x="14.508" y="9.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".1"/></filter><filter id="iOXqX5b" width="3.718" height="1.573" x="13.787" y="13.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="ioWcw5d" width="2.339" height="1.19" x="17.236" y="7.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/></filter><filter id="imiu07c" width="2.339" height="1.176" x="11.98" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/></filter><filter id="iZ7GhTc" width=".787" height=".696" x="17.095" y="9.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="inIrp7d" width=".891" height=".913" x="17.934" y="9.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".1"/></filter><filter id="ioLvDxf" width=".986" height="1.04" x="13.492" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".1"/></filter><filter id="iTdZ3ce" width=".913" height=".705" x="12.737" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="icvfhac" width="1.329" height="2.379" x="9.614" y="9.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".125"/></filter><filter id="iDxRamc" width="1.947" height="2.903" x="20.108" y="9.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".25"/></filter><filter id="iQOyVOe" width="2.405" height="1.16" x="11.899" y="7.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".125"/></filter><filter id="i27wLoc" width="2.405" height="1.169" x="17.177" y="7.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".125"/></filter><filter id="ity6V1d" width="14.779" height="5.543" x="8.307" y="2.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/></filter><filter id="iNIaxJc" width=".675" height="2.047" x="12.554" y="3.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="iRJYUId" width=".675" height="2.047" x="18.142" y="3.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="ixw1HPd" width=".98" height="2.537" x="15.211" y="3.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".1"/></filter><filter id="iTtgkUa" width="2.238" height="1.809" x="14.522" y="17.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1877" result="effect2_innerShadow_4002_1877"/></filter><filter id="iqtrKzd" width="5.047" height="11.336" x="23.075" y="14.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.521569 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/></filter><filter id="i7Qc7qd" width="3.672" height="4.703" x="23.537" y="15.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.647059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/><feGaussianBlur result="effect2_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="iUyzece" width="4.468" height="5.556" x="23.304" y="24.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1877"/></filter><filter id="iyRASFd" width="2.097" height=".3" x="23.674" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="iPXmRud" width="2.097" height=".3" x="23.596" y="27.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><filter id="i4Pt4KR" width="2.097" height=".3" x="23.674" y="28.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1877" stdDeviation=".05"/></filter><linearGradient id="i1FP2He" x1="10.476" x2="10.476" y1="7.862" y2="9.955" gradientUnits="userSpaceOnUse"><stop class="qi731gbjb"/><stop offset="1" class="zmama0ttw"/></linearGradient><linearGradient id="iXGwAFd" x1="20.818" x2="20.818" y1="7.69" y2="9.253" gradientUnits="userSpaceOnUse"><stop class="ty8nzq04x"/><stop offset="1" class="uf4kgmbxa"/></linearGradient><linearGradient id="iApFAXd" x1="22.829" x2="26.073" y1="25.868" y2="25.868" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="i6CCOue" x1="7.813" x2="7.813" y1="30.987" y2="16.925" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="i1LZgJN" x1="8.672" x2="8.094" y1="26.612" y2="26.612" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iWrhjjb" x1="8.672" x2="12.608" y1="27.198" y2="27.198" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="iOggUJb" x1="16.28" x2="13.319" y1="22.118" y2="18.734" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iyOmAwc" x1="20.5" x2="19.232" y1="27.632" y2="29.038" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="isflWdd" x1="20.5" x2="19.232" y1="23.992" y2="25.398" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i9wpO8b" x1="20.5" x2="19.232" y1="20.362" y2="21.768" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iPIXyBb" x1="20.846" x2="18.298" y1="12.565" y2="12.565" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iLcYHvd" x1="16.485" x2="15.647" y1="11.554" y2="11.589" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="i6LNTFb" x1="15.647" x2="15.647" y1="12.693" y2="12.229" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iAHGjIb" x1="15.647" x2="15.647" y1="9.988" y2="10.535" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iO34Xte" x1="14.445" x2="14.763" y1="14.264" y2="13.43" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iZZr1kc" x1="18.607" x2="18.293" y1="10.017" y2="10.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyZbMYd" x1="14.209" x2="13.895" y1="10.017" y2="10.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXOeGXt" x1="22.083" x2="20.876" y1="10.044" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iQKMCqe" x1="9.797" x2="11.255" y1="10.75" y2="10.623" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iAlRame" x1="21.082" x2="21.082" y1="9.666" y2="11.569" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iIt5XUJ" x1="16.281" x2="16.281" y1="7.768" y2="7.081" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="iK1SIgL" x1="13.027" x2="12.449" y1="5.621" y2="5.523" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="iX3JT4r" x1="18.289" x2="18.922" y1="5.43" y2="5.523" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="i2lq7ec" x1="15.991" x2="15.991" y1="5.766" y2="3.738" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient><linearGradient id="iEWOOjl" x1="16.375" x2="17.359" y1="17.987" y2="19.159" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="icIpgIc" x1="15.891" x2="15.891" y1="18.878" y2="17.439" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="incyxSc" x1="27.332" x2="23.304" y1="28.033" y2="28.033" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iuQML5c" x1="23.824" x2="25.533" y1="26.026" y2="26.026" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iprFTwD" x1="23.746" x2="25.455" y1="27.331" y2="27.331" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i5FfYLe" x1="23.824" x2="25.533" y1="28.636" y2="28.636" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cook-medium-dark" /></template>
<style>
.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ak2ynqn6o {
  fill: var(--svg-color--000, #000);
  d: path("M17.32 10.379a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.904a.46.46 0 0 1-.061-.235");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.beoi27bcu {
  fill: var(--svg-color--b5a5c4, #B5A5C4);
  d: path("M20.462 28.275a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.bh63c6z5s {
  d: path("M15.411 3.738h.58v2.137h-.58z");
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.bt1_2zb2r {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
  stop-opacity: 0;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c10x5bcsu {
  d: path("M17.765 9.675c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.135.39-.05");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.ca-kocctu {
  cx: 13.193px;
  cy: 9.868px;
  rx: 0.39px;
  ry: 0.197px;
}

.cgwmhgbmz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.256 9.214c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.d4i9tqbhe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.746 27.253h1.797");
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.da7b97bvf {
  stop-color: var(--svg-color--b59ccc, #B59CCC);
}

.daz2wrb4j {
  d: path("M10.785 12.13a1.64 1.64 0 0 1-.904-.31v.932c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dleyoln5x {
  fill: var(--svg-color--b29aac, #B29AAC);
  d: path("M19.712 21.755a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fjyr3161v {
  stop-color: var(--svg-color--730620, #730620);
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.g2a8vhbns {
  d: path("M10.241 2.085A1.933 1.933 0 0 0 9.56 5.83a.215.215 0 0 1 .142.197v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.023c0-.089.058-.166.141-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.g62mlfbwr {
  stop-color: var(--svg-color--6c3d49, #6C3D49);
  stop-opacity: 0;
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.g7beg1b7x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 25.948h1.797");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gvv34ibsn {
  d: path("M8.672 18h10.052c2.177 0 3.948 1.796 3.948 4.004V30h-14z");
}

.gzsdakb9r {
  stop-color: var(--svg-color--662a35, #662A35);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h6z8hobkh {
  fill: var(--svg-color--b2a7be, #B2A7BE);
  d: path("M19.712 25.385a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hi5n24owa {
  d: path("M9.996 7.347h.96v2.608h-.96z");
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hmjk95b9j {
  d: path("M19.982 25.24a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hrm61ulxz {
  d: path("M8.672 17.973a10.96 10.96 0 0 0-4 8.477V30h4z");
}

.i5m4wsx9z {
  stop-color: var(--svg-color--d68e4a, #D68E4A);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.is4qt5bjz {
  d: path("M13.46 18.684c.67-.924 1.703-1.194 2.096-1.245c.205.83.308 2.667-.684 3.564c-.635.573-1.078.721-1.67.786c-.163.018-.27-.164-.222-.321c.03-.101.051-.22.053-.366c.01-.634-.109-1.68.426-2.418");
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.j7-lx-buf {
  d: path("M20.338 7.347h.96v2.608h-.96z");
}

.jy18srelc {
  d: path("M20.732 28.13a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kc__dv0sq {
  d: path("M14.278 10.274c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.kg6j19b7w {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.264 10.165l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kpw-d1bli {
  d: path("M15.652 15.47c-6.07 0-10.98 4.92-10.98 10.98V30h4v-.06h14V30h4v-3.5c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m15k4yz6i {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.652 15.47c-6.07 0-10.98 4.92-10.98 10.98V30h4v-.06h14V30h4v-3.5c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.m1qbrybjx {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.274 8.327c.257-.184.897-.508 1.655-.38");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbtutfv6l {
  d: path("M23.081 18.355H8.232a10.94 10.94 0 0 1 7.42-2.885c3.484 0 5.153.812 7.43 2.885");
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mgyw9iept {
  d: path("M10.61 9.682a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.mhf6g8b4g {
  fill-rule: evenodd;
  d: path("m13.129 5.875l-.475-1.847v1.847z");
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.o-gay1b3i {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.296 13.381c.39.203.855.32 1.35.32c.502 0 .962-.117 1.351-.32h.001a.23.23 0 0 1 .27.044a.214.214 0 0 1 .025.273m-2.997-.317l2.934.276m-2.934-.276a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27m.295-.317l-.233.276m3.23.041l-.063-.041m.063.041l-.063-.041m.063.041c-.349.528-.956.88-1.646.88s-1.297-.352-1.646-.88m3.229-.041a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.584-.846m-.062.042l.062-.042m-.062.042v-.001l.062-.041");
}

.o2hkdibzn {
  d: path("M19.982 21.61a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2t_gg2x {
  d: path("M20.609 11.57q.057-.953.11-1.904a.955.955 0 0 1-.11 1.903");
}

.ozqls6q-b {
  fill-rule: evenodd;
  d: path("m18.242 5.875l.475-1.847v1.847z");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.paq1r_bcl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.765 9.675c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.135.39-.05");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q2-xacyrz {
  fill: var(--svg-color--000, #000);
  d: path("M13.974 10.379a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.235");
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qgc7u1v2q {
  d: path("M17.855 18.684c-.67-.924-1.704-1.194-2.097-1.245c-.205.83-.308 2.667.684 3.564c.635.573 1.077.721 1.67.786c.163.018.269-.164.221-.321c-.03-.101-.05-.22-.053-.366c-.009-.634.11-1.68-.425-2.418");
}

.qi731gbjb {
  stop-color: var(--svg-color--282121, #282121);
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qoe9pbqhg {
  stop-color: var(--svg-color--7e4d5c, #7E4D5C);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3_czmna {
  d: path("M26.655 23.057a.97.97 0 0 1 .967.967v2.215h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r0zatwb2r {
  d: path("M20.569 12.22q.1-1.596.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.r64vbvf7r {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r7svlnonw {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
  stop-opacity: 0;
}

.r9v3grw-v {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.038 9.214c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.s8wwykopu {
  d: path("M15.385 17.496c-.385.032-1.404.252-2.102 1.142c-.47.6-.499 1.44-.52 2.069q-.005.176-.014.326a1.4 1.4 0 0 1-.07.362c-.054.155.04.342.2.332c.58-.036 1.018-.162 1.664-.705c.492-.413.743-1.062.851-1.716c.044.661.228 1.332.677 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.232-.31a1.4 1.4 0 0 1-.034-.368q.005-.151.018-.326c.04-.628.095-1.468-.313-2.11c-.607-.955-1.6-1.274-1.979-1.344c-.047.16-.092.359-.128.582a5 5 0 0 0-.07-.592");
}

.sadlm6lao {
  fill: var(--svg-color--e1a474, #E1A474);
  d: path("M26.051 21.174c0-.406.26-.758.568-1.021c.605-.517 1.003-1.392 1.003-2.384c0-1.588-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.287-2.273 2.875c0 .992.398 1.867 1.002 2.384c.309.263.568.615.568 1.02v5.057h1.406z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sierzcbjv {
  d: path("M23.304 25.296c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.03a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t4ycnmrng {
  d: path("m15.264 10.165l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.tddkrwb-v {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.38 8.164a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.toc3mjbcb {
  d: path("M22.672 30h4v-3.5c0-3.422-1.554-6.482-4-8.499z");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.ttlvurbri {
  d: path("M18.626 10.261a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.ty8nzq04x {
  stop-color: var(--svg-color--373032, #373032);
}

.u91v0ebbj {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.236 8.048a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.001a.277.277 0 0 1-.34-.438z");
}

.uelaalb7d {
  stop-color: var(--svg-color--da9766, #DA9766);
}

.uf4kgmbxa {
  stop-color: var(--svg-color--271d21, #271D21);
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.uxt3imbne {
  d: path("M21.727 5.925H9.675q.026.046.027.101v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.023a.2.2 0 0 1 .025-.098");
}

.v1m3xdvgj {
  d: path("M14.984 17.558c.19-.063.44-.119.707-.119s.517.056.707.12a.39.39 0 0 1 .255.45c-.093.486-.27.8-.464.989a.5.5 0 0 1-.267.13c-.11.02-.338.032-.477 0a.43.43 0 0 1-.252-.13c-.194-.189-.371-.503-.463-.99a.39.39 0 0 1 .254-.45");
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.via-_dbpm {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
}

.vmgtc1ecl {
  d: path("M15.647 13.776c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.vsb_6zy7g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 28.558h1.797");
}

.vuu318b4c {
  stop-color: var(--svg-color--730620, #730620);
  stop-opacity: 0;
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wir9txusx {
  d: path("M10.822 13.644a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.278-4.387.366-6.27c-.011-.767-.657-.772-1.421-.804h-1.4c-.955 0-1.82-.564-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.376.798-3.376 2.665c0 1.86.15 4.405.273 6.27");
}

.wl_jqnblm {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.208 8.289c-.282-.297-.898-.509-1.655-.382");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wxvfeccof {
  d: path("M10.593 9.02a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.x6cxz4mml {
  d: path("M26.051 21.174c0-.406.26-.758.568-1.021c.605-.517 1.003-1.392 1.003-2.384c0-1.588-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.287-2.273 2.875c0 .992.398 1.867 1.002 2.384c.309.263.568.615.568 1.02v5.057h1.406z");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yf96yoa0h {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.16 10.36l-.634 1.839c-.109.378.152.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.542-.408-.661 0");
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.z__b2obbo {
  cx: 25.348px;
  cy: 17.714px;
  rx: 1.711px;
  ry: 2.227px;
}

.z_tmohbaf {
  d: path("M20.508 12.13c.335-.012.65-.125.905-.31v.932c0 .893-.532 1.689-1.341 2.019a4.1 4.1 0 0 0 .346-1.18z");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z2t4-fbkt {
  d: path("M17.83 9.486a.892.892 0 0 1 .86 1.128h-1.723a.896.896 0 0 1 .864-1.128");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zhltjbs8q {
  stop-color: var(--svg-color--6c3d49, #6C3D49);
}

.zi7ici7iu {
  d: path("M13.463 9.486a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.zmama0ttw {
  stop-color: var(--svg-color--46403d, #46403D);
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zvrj6jbon {
  cx: 13.193px;
  cy: 9.868px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

</style>
