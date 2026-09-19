<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijPjMte)" class="bc-2qpb5b"/><path fill="url(#iOmhMQb)" class="p750yccxl"/><path class="epnzf5-dx"/><path fill="url(#iZGJcac)" class="slc7u1bug"/><path fill="url(#i1rRcnc)" class="dc3v0owwm"/><path fill="url(#ihaOL5d)" class="dc3v0owwm"/><path fill="url(#iTQKLKe)" class="d6ddfyb2n"/><path fill="url(#ikd4lae)" class="d6ddfyb2n"/><path fill="url(#i61Vp2N)" class="d6ddfyb2n"/><g filter="url(#i9uPFOd)"><path fill="url(#idI8Cln)" class="av4-_ybmd"/><path fill="url(#izRoFTb)" class="av4-_ybmd"/></g><path fill="url(#i049TPb)" class="av4-_ybmd"/><path fill="url(#iWoG0tb)" class="av4-_ybmd"/><g filter="url(#iFEzDMd)"><path fill="url(#iYq11bc)" class="pc71sv8vm"/></g><path fill="url(#ijIl64b)" class="dm7whed5a"/><path fill="url(#iSYIF6c)" class="dm7whed5a"/><g filter="url(#iohPy0c)"><path class="x08c7hbso"/></g><g filter="url(#iOGij2c)"><path class="kq58x0xbj"/></g><g filter="url(#iyIkSdc)"><path class="euneelbzl"/></g><g filter="url(#iUBUiDc)"><path fill="url(#ipWwuPt)" class="n7pplacao"/></g><g filter="url(#iLJn5zb)"><path fill="url(#iWbWcfG)" class="e_5ocxb0z"/></g><g filter="url(#iRMSWAe)"><path fill="url(#iFz7p1d)" class="shbjl-jcw"/></g><g filter="url(#iWGseXd)"><path fill="url(#i8A5Xfe)" class="j0yutqbzg"/></g><path fill="url(#i6XPvux)" class="jl8kp8gbp"/><path fill="url(#iKHjIfS)" class="jl8kp8gbp"/><path fill="url(#iYF8Uom)" class="ysi_t1blv"/><path fill="url(#igxYGEp)" class="ysi_t1blv"/><g filter="url(#isyoTjd)"><path fill="url(#ilEDWGe)" class="b-9oyybra"/></g><path fill="url(#icc9edf)" class="b-9oyybra"/><path fill="url(#iCyu3Ad)" class="b-9oyybra"/><path fill="url(#iOGEgdb)" class="b-9oyybra"/><path fill="url(#iu0ZiFe)" class="b-9oyybra"/><path fill="url(#iE9PaTc)" class="b-9oyybra"/><path fill="url(#iXL8QNe)" class="b-9oyybra"/><g filter="url(#isCrVGc)"><path class="x4yu4vb5t"/></g><g filter="url(#iP4Z9dc)"><path fill="url(#i1MqXPe)" class="a6nw635my"/><path fill="url(#ikqmWib)" class="a6nw635my"/><path fill="url(#iOOdjpe)" class="a6nw635my"/><path fill="url(#igQRupe)" class="a6nw635my"/></g><g filter="url(#ihpDajc)"><path stroke="url(#iFIXkXc)" class="qe0sk9b7e"/></g><path fill="url(#i596tVV)" class="oekjo5bba"/><g filter="url(#iG2UmAC)"><path class="r5exg_tya"/></g><g filter="url(#i2Vqe1b)"><path class="ykqsx6bkp"/></g><path class="f9p1q0b2i"/><path fill="url(#i0jLZfc)" class="gk3mjpbzm"/><path class="uneoyobli"/><g filter="url(#irEhrJe)"><path class="upkq7-l7k"/><path fill="url(#iNcBcee)" class="rwnhukbud"/></g><g filter="url(#iayjD9Y)"><path fill="url(#i1AscGe)" class="zgc4hbsrx"/></g><path class="siuyidtxn"/><path fill="url(#irBGN9b)" class="t63ey2gcg"/><path class="s6smc1bpq"/><g filter="url(#i1G2Yih)"><path fill="url(#iDLGRJb)" class="em_ledbkv"/></g><g filter="url(#iSi2BBU)"><ellipse transform="rotate(-27.914 13.228 9.867)" class="xt9gtbcqr"/><ellipse fill="url(#iIt63Fb)" transform="rotate(-27.914 13.228 9.867)" class="ujs1exfci"/></g><path fill="url(#imKFURd)" class="m-0xesbcc"/><path fill="url(#iWZINlb)" class="m-0xesbcc"/><path fill="url(#iDI2npd)" class="m-0xesbcc"/><path fill="url(#irnxJZH)" class="krqo7c8vg"/><path fill="url(#i0pGG6c)" class="krqo7c8vg"/><g filter="url(#iurwscL)"><path class="ynjzy7beo"/></g><g filter="url(#iGaDF9q)"><path class="cqpan2b2c"/></g><g filter="url(#iqiWXzc)"><path class="jic3pmbna"/></g><g filter="url(#iO7OGWd)"><path class="wp3xn_yhz"/></g><g filter="url(#iU4jGjd)"><path fill="url(#ikzJD3l)" class="d02p6mb2m"/><path fill="url(#ij1hppd)" class="d02p6mb2m"/></g><path fill="url(#ilOlAPb)" class="zy0_7e_ev"/><path fill="url(#iVmKS9d)" class="zy0_7e_ev"/><g filter="url(#iUFaYme)"><path fill="url(#if0T0dd)" clip-rule="evenodd" class="yrbuqdehl"/></g><g filter="url(#i2LbVxc)"><path fill="url(#if3LS0b)" clip-rule="evenodd" class="grb1dk3io"/></g><g filter="url(#iVIZsXb)"><path fill="url(#i9RXG7b)" class="dtw_seb9e"/></g><path fill="url(#iCveDib)" class="ikrrfabfh"/><path fill="url(#iEAM58b)" class="ikrrfabfh"/><path fill="url(#iEQscnd)" class="ikrrfabfh"/><path fill="url(#iNSTFXb)" class="lg-7fqbqa"/><path fill="url(#ifwdUUc)" class="lg-7fqbqa"/><path fill="url(#igMfV0b)" class="lg-7fqbqa"/><path fill="url(#iAH0xUN)" class="lg-7fqbqa"/><g filter="url(#iAAuSUb)"><path fill="url(#iAIInnb)" class="ikvxrebvi"/></g><g filter="url(#iotYixd)"><path class="x1lqll9-o"/><path fill="url(#iRIXV5U)" class="kc15ybcai"/></g><g filter="url(#iSgDGRc)"><ellipse fill="url(#i5aXntb)" class="f9xme5bst"/></g><g filter="url(#iO6ToOb)"><path fill="url(#ibDMvjg)" class="c4_7v1ben"/><path fill="url(#iAIRvOd)" class="c4_7v1ben"/><path fill="url(#ip62qjT)" class="c4_7v1ben"/><path fill="url(#inZPrnc)" class="c4_7v1ben"/><path fill="url(#i4qI0uP)" class="c4_7v1ben"/></g><g filter="url(#ikljiUd)"><path stroke="url(#iOzkmcd)" class="j0gtlg__p"/></g><g filter="url(#iUzDYpe)"><path stroke="url(#i25yFOd)" class="kq1o8bc_z"/></g><g filter="url(#iuNze5d)"><path stroke="url(#ik4W35b)" class="tlnan5bzo"/></g><defs><radialGradient id="iZGJcac" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.706 57.6)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="ihaOL5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.72 30.202)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="i61Vp2N" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.16 30.706)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="idI8Cln" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.76 19.677)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="izRoFTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.425 32.45)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="i049TPb" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.482 16.05)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="ijIl64b" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9.012 10.11)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iSYIF6c" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.62 8.62)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="i8A5Xfe" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.617 19.917)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="phvlv-hdf"/><stop offset=".828" class="ty_drcd_b"/></radialGradient><radialGradient id="i6XPvux" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 5.928 14.328)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iKHjIfS" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.646 26.188)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iYF8Uom" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.134 11.938)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="igxYGEp" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.768 13.355)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="ilEDWGe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.49 10.88)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="icc9edf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.38582 16.7329 0 15.49 17.214)" gradientUnits="userSpaceOnUse"><stop class="hvidiga6z"/><stop offset="1" class="lwvr3bb3f"/></radialGradient><radialGradient id="iCyu3Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.40557 6.10192 -2.25991 -.1502 20.88 10.647)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iOGEgdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.71491 0 13.578 9.699)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iu0ZiFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 2.00611 0 18.192 9.287)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iE9PaTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.15625 -6.47713 0 15.732 7.018)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="a-sob5bdm"/><stop offset="1" class="v9o654bxh"/></radialGradient><radialGradient id="iXL8QNe" cx="0" cy="0" r="1" gradientTransform="rotate(173.991 10.405 3.892)scale(2.98515 1.68477)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="zzxhreusb"/><stop offset="1" class="fdlwix82n"/></radialGradient><radialGradient id="iFIXkXc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.369 -5.337)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i596tVV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.681 14.419)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i0jLZfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.864 9.963)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iNcBcee" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.278 .705)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irBGN9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.5 9.963)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iIt63Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.214 10.182)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWZINlb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.3 9.977)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iDI2npd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.66 10.522)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i0pGG6c" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.046 9.347)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="ikzJD3l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.566 6.05)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="ij1hppd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.378 2.893)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="ilOlAPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 18.816 7.3)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><radialGradient id="iCveDib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.894 19.284)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iEAM58b" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.254 18.159)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="iEQscnd" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.365 20.455)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iNSTFXb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.23 18.574)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="igMfV0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.784 18.877)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iAH0xUN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.722 21.284)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iRIXV5U" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.715 11.246)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="i5aXntb" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.176 20.077)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="iAIRvOd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.656 24.564)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="ip62qjT" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.525 25.94)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="inZPrnc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.338 27.267)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="i4qI0uP" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.243 28.534)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><filter id="i9uPFOd" width="14.3" height="12.3" x="8.406" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="iFEzDMd" width="6.538" height="5.771" x="12.049" y="16.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".325"/></filter><filter id="iohPy0c" width="2.5" height="2.5" x="18.497" y="27.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".25"/></filter><filter id="iOGij2c" width="2.5" height="2.5" x="18.497" y="23.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".25"/></filter><filter id="iyIkSdc" width="2.5" height="2.5" x="18.497" y="19.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".25"/></filter><filter id="iUBUiDc" width="1.7" height="1.7" x="19.166" y="27.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1871" result="effect2_innerShadow_4002_1871"/></filter><filter id="iLJn5zb" width="1.7" height="1.7" x="19.166" y="23.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1871" result="effect2_innerShadow_4002_1871"/></filter><filter id="iRMSWAe" width="1.7" height="1.7" x="19.166" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1871" result="effect2_innerShadow_4002_1871"/></filter><filter id="iWGseXd" width="2.584" height="3.682" x="25.722" y="22.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.529412 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="isyoTjd" width="10.797" height="12.542" x="10.584" y="4.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1871" result="effect2_innerShadow_4002_1871"/></filter><filter id="isCrVGc" width="3.877" height="4.9" x="13.536" y="9.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".5"/></filter><filter id="iP4Z9dc" width="2.077" height="3.1" x="14.643" y="9.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="ihpDajc" width="3.718" height="1.573" x="13.822" y="13.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iG2UmAC" width="2.339" height="1.19" x="17.271" y="7.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="i2Vqe1b" width="2.339" height="1.176" x="12.014" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="irEhrJe" width=".787" height=".696" x="17.129" y="9.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iayjD9Y" width=".891" height=".913" x="17.969" y="9.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".1"/></filter><filter id="i1G2Yih" width=".986" height="1.04" x="13.526" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".1"/></filter><filter id="iSi2BBU" width=".913" height=".705" x="12.772" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iurwscL" width="1.329" height="2.379" x="9.649" y="9.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".125"/></filter><filter id="iGaDF9q" width="1.447" height="2.403" x="20.393" y="9.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".125"/></filter><filter id="iqiWXzc" width="2.305" height="1.06" x="11.983" y="7.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".125"/></filter><filter id="iO7OGWd" width="2.305" height="1.069" x="17.262" y="7.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".125"/></filter><filter id="iU4jGjd" width="14.779" height="5.543" x="8.342" y="2.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="iUFaYme" width=".675" height="2.047" x="12.589" y="3.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="i2LbVxc" width=".675" height="2.047" x="18.177" y="3.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iVIZsXb" width=".98" height="2.537" x="15.246" y="3.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".1"/></filter><filter id="iAAuSUb" width="2.238" height="1.809" x="14.557" y="17.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1871" result="effect2_innerShadow_4002_1871"/></filter><filter id="iotYixd" width="5.047" height="11.336" x="23.11" y="14.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="iSgDGRc" width="3.672" height="4.703" x="23.572" y="15.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/><feGaussianBlur result="effect2_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iO6ToOb" width="4.618" height="5.556" x="23.338" y="24.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1871"/></filter><filter id="ikljiUd" width="2.047" height=".25" x="23.734" y="25.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iUzDYpe" width="2.047" height=".25" x="23.656" y="27.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><filter id="iuNze5d" width="2.047" height=".25" x="23.734" y="28.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1871" stdDeviation=".05"/></filter><linearGradient id="ijPjMte" x1="10.511" x2="10.511" y1="7.862" y2="9.954" gradientUnits="userSpaceOnUse"><stop class="ng77g0bfn"/><stop offset="1" class="ya6f3fvsd"/></linearGradient><linearGradient id="iOmhMQb" x1="20.852" x2="20.852" y1="7.69" y2="9.252" gradientUnits="userSpaceOnUse"><stop class="w_1c4jmvf"/><stop offset="1" class="yzthd-bab"/></linearGradient><linearGradient id="i1rRcnc" x1="22.864" x2="26.107" y1="25.868" y2="25.868" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iTQKLKe" x1="7.847" x2="7.847" y1="30.987" y2="16.924" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="ikd4lae" x1="8.706" x2="8.128" y1="26.612" y2="26.612" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iWoG0tb" x1="8.706" x2="12.643" y1="27.198" y2="27.198" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="iYq11bc" x1="16.315" x2="13.354" y1="22.118" y2="18.733" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="ipWwuPt" x1="20.535" x2="19.267" y1="27.632" y2="29.038" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iWbWcfG" x1="20.535" x2="19.267" y1="23.992" y2="25.398" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iFz7p1d" x1="20.535" x2="19.267" y1="20.362" y2="21.768" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i1MqXPe" x1="15.682" x2="16.536" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ikqmWib" x1="14.609" x2="15.683" y1="11.552" y2="11.612" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iOOdjpe" x1="15.682" x2="15.682" y1="12.107" y2="12.959" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="igQRupe" x1="15.682" x2="15.682" y1="9.859" y2="10.278" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i1AscGe" x1="18.642" x2="18.328" y1="10.017" y2="10.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDLGRJb" x1="14.243" x2="13.93" y1="10.017" y2="10.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imKFURd" x1="22.118" x2="20.911" y1="10.044" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="irnxJZH" x1="9.832" x2="11.29" y1="10.748" y2="10.62" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iVmKS9d" x1="16.316" x2="16.316" y1="7.768" y2="7.081" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="if0T0dd" x1="13.062" x2="12.484" y1="5.621" y2="5.523" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="if3LS0b" x1="18.324" x2="18.957" y1="5.429" y2="5.523" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="i9RXG7b" x1="16.025" x2="16.025" y1="5.765" y2="3.738" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient><linearGradient id="ifwdUUc" x1="16.41" x2="17.394" y1="17.987" y2="19.159" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iAIInnb" x1="15.925" x2="15.925" y1="18.877" y2="17.439" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="ibDMvjg" x1="27.366" x2="23.338" y1="28.032" y2="28.032" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="iOzkmcd" x1="25.539" x2="23.703" y1="25.948" y2="25.948" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="i25yFOd" x1="25.461" x2="23.625" y1="27.252" y2="27.252" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="ik4W35b" x1="25.539" x2="23.703" y1="28.557" y2="28.557" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cook" /></template>
<style>
.a-sob5bdm {
  stop-color: var(--svg-color--e98b2a, #E98B2A);
}

.a6nw635my {
  d: path("m15.3 10.165l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.av4-_ybmd {
  d: path("M8.706 18H18.76c2.176 0 3.947 1.796 3.947 4.003V30h-14z");
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b-9oyybra {
  d: path("M10.857 13.644a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.278-4.388.365-6.27c-.01-.767-.657-.772-1.42-.805h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.616-.419H13.96c-1.846 0-3.376.8-3.376 2.666c0 1.86.15 4.405.273 6.27");
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bc-2qpb5b {
  d: path("M10.031 7.346h.96v2.608h-.96z");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c4_7v1ben {
  d: path("M23.339 25.296a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.cqpan2b2c {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.643 11.569q.059-.952.11-1.903a.955.955 0 0 1-.11 1.903");
}

.d02p6mb2m {
  d: path("M10.276 2.085a1.933 1.933 0 0 0-.682 3.743a.215.215 0 0 1 .143.198v1.052c0 .248.201.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.023c0-.089.058-.166.14-.198a1.934 1.934 0 0 0-.689-3.74z");
}

.d6ddfyb2n {
  d: path("M8.706 17.973a10.96 10.96 0 0 0-4 8.477V30h4z");
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

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dc3v0owwm {
  d: path("M22.706 30h4v-3.502c0-3.421-1.553-6.481-4-8.498z");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dm7whed5a {
  d: path("M23.116 18.355H8.267a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.811 7.429 2.885");
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.dtw_seb9e {
  d: path("M15.446 3.738h.58v2.137h-.58z");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e_5ocxb0z {
  d: path("M20.017 25.24a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.em_ledbkv {
  d: path("M14.313 10.273c0-.288-.235-.48-.298-.538l-.289.279l.178.36z");
}

.epnzf5-dx {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.686 15.47c-6.07 0-10.98 4.92-10.98 10.98V30h4v-.06h14V30h4v-3.502c0-3.421-1.553-6.481-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.euneelbzl {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M19.747 21.755a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.f9p1q0b2i {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.073 9.214c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.f9xme5bst {
  cx: 25.383px;
  cy: 17.713px;
  rx: 1.711px;
  ry: 2.227px;
}

.fdlwix82n {
  stop-color: var(--svg-color--c09040, #C09040);
  stop-opacity: 0;
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

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gk3mjpbzm {
  d: path("M17.866 9.486a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.grb1dk3io {
  fill-rule: evenodd;
  d: path("m18.277 5.875l.474-1.847v1.847z");
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hvidiga6z {
  stop-color: var(--svg-color--bf660b, #BF660B);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ikrrfabfh {
  d: path("M13.494 18.684c.67-.924 1.704-1.194 2.096-1.245c.206.83.308 2.666-.683 3.563c-.635.574-1.078.722-1.67.787c-.164.018-.27-.165-.222-.322c.03-.1.051-.22.053-.365c.01-.634-.109-1.681.426-2.418");
}

.ikvxrebvi {
  d: path("M15.019 17.558c.19-.063.44-.12.707-.12s.517.057.707.12a.39.39 0 0 1 .254.45c-.092.486-.269.8-.463.99a.5.5 0 0 1-.268.13a1.5 1.5 0 0 1-.476 0a.43.43 0 0 1-.252-.13c-.194-.19-.371-.504-.464-.99a.39.39 0 0 1 .255-.45");
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j0gtlg__p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.859 25.948h1.797");
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j0yutqbzg {
  d: path("M26.69 23.057a.97.97 0 0 1 .966.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jic3pmbna {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.308 8.327c.257-.184.898-.509 1.655-.381");
}

.jl8kp8gbp {
  d: path("M20.543 12.129a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc15ybcai {
  d: path("M26.086 21.173c0-.405.26-.757.568-1.02c.605-.517 1.002-1.392 1.002-2.385c0-1.588-1.017-2.875-2.273-2.875s-2.273 1.287-2.273 2.875c0 .992.397 1.867 1.002 2.384c.308.264.568.616.568 1.021v5.056h1.406z");
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kq1o8bc_z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.78 27.252h1.797");
}

.kq58x0xbj {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M19.747 25.385a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.krqo7c8vg {
  d: path("M10.628 9.02a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lg-7fqbqa {
  d: path("M17.89 18.684c-.67-.924-1.705-1.194-2.097-1.245c-.205.83-.308 2.666.684 3.563c.634.574 1.077.722 1.67.787c.163.018.269-.165.221-.322q-.047-.149-.053-.365c-.01-.634.109-1.681-.426-2.418");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lwvr3bb3f {
  stop-color: var(--svg-color--efa033, #EFA033);
  stop-opacity: 0;
}

.m-0xesbcc {
  d: path("M20.603 12.22q.1-1.596.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
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

.n7pplacao {
  d: path("M20.767 28.13a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ng77g0bfn {
  stop-color: var(--svg-color--d8891e, #D8891E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oekjo5bba {
  d: path("M15.682 13.776c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.129-.061-.278-.198-.209a3 3 0 0 1-1.386.329");
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.p750yccxl {
  d: path("M20.373 7.346h.96v2.608h-.96z");
}

.pc71sv8vm {
  d: path("M15.42 17.496c-.385.032-1.405.252-2.102 1.142c-.47.599-.499 1.44-.52 2.068q-.005.177-.014.327a1.4 1.4 0 0 1-.07.362c-.054.155.04.342.2.332c.58-.036 1.018-.163 1.664-.705c.492-.414.742-1.063.851-1.717c.043.662.228 1.332.677 1.792c.59.604 1.013.773 1.587.867c.158.025.27-.152.231-.31a1.4 1.4 0 0 1-.033-.369q.005-.15.018-.326c.04-.627.095-1.467-.313-2.11c-.607-.954-1.6-1.274-1.98-1.344c-.046.16-.091.36-.127.583a5 5 0 0 0-.07-.593");
}

.phvlv-hdf {
  stop-color: var(--svg-color--ffdf46, #FFDF46);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.qe0sk9b7e {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.33 13.38c.39.204.856.32 1.351.32c.501 0 .961-.116 1.351-.32a.23.23 0 0 1 .272.045a.214.214 0 0 1 .023.273m-2.996-.317l2.934.275m-2.934-.275h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.271m.295-.317l-.233.275m3.23.042l-.063-.042m.062.042l-.062-.042m.062.042c-.348.528-.955.88-1.646.88c-.69 0-1.297-.352-1.645-.88m3.229-.042a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r5exg_tya {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.414 8.164a1.85 1.85 0 0 0-.687-.412c-.304-.095-.685-.121-1.213-.057a.277.277 0 1 0 .068.551c.481-.059.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 0 0 .364-.418");
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

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rwnhukbud {
  d: path("M17.8 9.675c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.389-.05");
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.s6smc1bpq {
  fill: var(--svg-color--000, #000);
  d: path("M14.009 10.378a.51.51 0 0 0-.512-.51a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.236");
}

.shbjl-jcw {
  d: path("M20.017 21.61a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.siuyidtxn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.29 9.214c-.652 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.slc7u1bug {
  d: path("M15.686 15.47c-6.07 0-10.98 4.92-10.98 10.98V30h4v-.06h14V30h4v-3.502c0-3.421-1.553-6.481-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t63ey2gcg {
  d: path("M13.497 9.486a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.tlnan5bzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.859 28.557h1.797");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.ty_drcd_b {
  stop-color: var(--svg-color--f9c116, #F9C116);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ujs1exfci {
  cx: 13.228px;
  cy: 9.867px;
  rx: 0.39px;
  ry: 0.197px;
}

.uneoyobli {
  fill: var(--svg-color--000, #000);
  d: path("M17.354 10.378c0-.284.227-.51.512-.51a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.236");
}

.upkq7-l7k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.8 9.675c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.389-.05");
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.v9o654bxh {
  stop-color: var(--svg-color--e98b2a, #E98B2A);
  stop-opacity: 0;
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w_1c4jmvf {
  stop-color: var(--svg-color--ffda33, #FFDA33);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wp3xn_yhz {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.243 8.288c-.282-.297-.898-.508-1.656-.38");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x08c7hbso {
  fill: var(--svg-color--c4abda, #C4ABDA);
  d: path("M20.497 28.275a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.x1lqll9-o {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.086 21.173c0-.405.26-.757.568-1.02c.605-.517 1.002-1.392 1.002-2.385c0-1.588-1.017-2.875-2.273-2.875s-2.273 1.287-2.273 2.875c0 .992.397 1.867 1.002 2.384c.308.264.568.616.568 1.021v5.056h1.406z");
}

.x4yu4vb5t {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.195 10.36l-.635 1.84c-.108.378.152.756.521.756h.786c.37 0 .63-.384.521-.756l-.532-1.839c-.113-.407-.541-.407-.66 0");
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xt9gtbcqr {
  cx: 13.228px;
  cy: 9.867px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ya6f3fvsd {
  stop-color: var(--svg-color--cb9440, #CB9440);
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yidy664bk {
  stop-color: var(--svg-color--c88714, #C88714);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.ykqsx6bkp {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.27 8.047a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.552a2.22 2.22 0 0 0-1.387.284a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.ynjzy7beo {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.644 9.681a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrbuqdehl {
  fill-rule: evenodd;
  d: path("m13.164 5.875l-.475-1.847v1.847z");
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.ysi_t1blv {
  d: path("M10.82 12.129a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.yzthd-bab {
  stop-color: var(--svg-color--ffc11f, #FFC11F);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zgc4hbsrx {
  d: path("M18.66 10.26a.84.84 0 0 0-.23-.462l-.26.285l.117.229z");
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

.zy0_7e_ev {
  d: path("M21.762 5.925H9.709q.027.046.028.101v1.052c0 .248.201.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.023q0-.054.025-.098");
}

.zzxhreusb {
  stop-color: var(--svg-color--c09040, #C09040);
}

</style>
