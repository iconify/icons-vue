<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iJgg5sb)" class="d2kvgvbvc"><path fill="url(#iI0znWd)" class="vwn1d4b1p"/><path fill="url(#iksbhAr)" class="vwn1d4b1p"/><path fill="url(#irNgTce)" class="vwn1d4b1p"/><path fill="url(#i12RqEb)" class="vwn1d4b1p"/><path fill="url(#iVu6PEc)" class="vwn1d4b1p"/><path fill="url(#i5YjKDc)" class="vwn1d4b1p"/><path fill="url(#ipj9dRc)" class="vwn1d4b1p"/><path fill="url(#inFjWne)" class="vwn1d4b1p"/><path fill="url(#iHYBfob)" class="vwn1d4b1p"/><path fill="url(#iVqjJBb)" class="vwn1d4b1p"/></g><path class="u1zn18zmi"/><path fill="url(#iynQxtM)" class="ilt675bqi"/><path fill="url(#iZQkIpe)" class="mujxyf7za"/><path fill="url(#i5QsWPe)" class="mujxyf7za"/><path fill="url(#ijt6gMc)" class="mujxyf7za"/><path fill="url(#i2Fbc4Y)" class="mujxyf7za"/><path fill="url(#iHZyEQc)" class="nl-c4e4xq"/><path fill="url(#iMiqFkb)" class="nl-c4e4xq"/><path fill="url(#iFqLLpd)" class="nl-c4e4xq"/><g filter="url(#iqev7lb)"><path fill="url(#i54qHIe)" class="yhwzdxbte"/><path fill="url(#iSOcTod)" class="yhwzdxbte"/><path fill="url(#i8kc3Ah)" class="yhwzdxbte"/><path fill="url(#iOA85ac)" class="yhwzdxbte"/></g><g filter="url(#iHQ2ePc)"><path fill="url(#i9zj7Tc)" class="k7zt1gbjg"/></g><g filter="url(#iSD4Dqd)"><path stroke="url(#iOhkFTd)" class="cd5b-kb9y"/></g><g filter="url(#iR7ynbb)"><path fill="url(#icIERhd)" class="q55omib7e"/></g><g filter="url(#iwHuWJe)"><path stroke="url(#i7KzMRb)" class="oi6iyacka"/></g><g filter="url(#icLcSeb)"><path fill="url(#ii6jdYd)" class="bmf08op0i"/><path fill="url(#ioEmbwd)" class="bmf08op0i"/></g><g filter="url(#iVJIzVi)"><path class="arsyfvbsk"/><path fill="url(#ihL8Pee)" class="npmp30b8c"/><path fill="url(#i2lgMJs)" class="npmp30b8c"/><path fill="url(#ipEqElc)" class="npmp30b8c"/><path fill="url(#iQV2oJe)" class="npmp30b8c"/></g><path fill="url(#idycZ0k)" class="kwq6xetnq"/><path fill="url(#izDPRDe)" class="kwq6xetnq"/><path fill="url(#iGhNH1d)" class="l7ojjeadx"/><path fill="url(#iicGn0Q)" class="l7ojjeadx"/><g filter="url(#illy8Yc)"><path fill="url(#ihk7twn)" class="cv7qblb2e"/></g><g filter="url(#iXEAwhe)"><path fill="url(#imTiK4b)" class="cv7qblb2e"/><path fill="url(#iu72mhc)" class="cv7qblb2e"/><path fill="url(#inyGMTT)" class="cv7qblb2e"/><path fill="url(#iI7DACc)" class="cv7qblb2e"/><path fill="url(#ipKe3Nd)" class="cv7qblb2e"/></g><path fill="url(#iHxzS7a)" class="cv7qblb2e"/><g filter="url(#iYdeU5b)"><path fill="url(#iGZvHCJ)" class="i08nc5kmh"/></g><g filter="url(#isBJoDe)"><path stroke="url(#i4BS7Gd)" class="xlfd0lbte"/></g><g filter="url(#ireoYqd)"><path stroke="url(#iFGK8WK)" class="gr1zvxbwq"/></g><g filter="url(#iXXLFqb)"><path stroke="url(#iAcNhSb)" class="a3h4q-bko"/></g><g filter="url(#insiq8d)"><path stroke="url(#ioXOYOc)" class="pvstcpbcm"/></g><g filter="url(#iPKMEYc)"><path stroke="url(#ivKPd0d)" class="z3dsw3evh"/></g><g filter="url(#iRKNJgb)"><path stroke="url(#iXQ9tTc)" class="kipcy4rpo"/></g><g filter="url(#i11L9pe)"><path fill="url(#ix3Vijd)" class="un_ysrbes"/></g><g filter="url(#iJJH3Hb)"><path fill="url(#igEewoc)" class="jbci68byv"/><path fill="url(#irx5C3b)" class="jbci68byv"/></g><g filter="url(#iVTS4Dd)"><path class="qyvp3x_ro"/><path fill="url(#ixgOsUc)" class="wj1bd858m"/></g><g filter="url(#iEKS0ad)"><path class="yg13ih15u"/><path fill="url(#iEeGDKe)" class="yghn3nr2v"/></g><g filter="url(#iD6VSWb)"><path fill="url(#iYBQ7Vc)" class="x59y2qb9p"/><path fill="url(#iQ5jbRb)" class="x59y2qb9p"/><path fill="url(#iAqT3qd)" class="x59y2qb9p"/><path fill="url(#i1qFfOd)" class="x59y2qb9p"/><path fill="url(#iHKLBle)" class="x59y2qb9p"/></g><path fill="url(#iz2H1Jb)" class="dyn64notx"/><path fill="url(#iwIzFWe)" class="dyn64notx"/><g filter="url(#i0si5tG)"><path class="aa1vmtrmd"/></g><g filter="url(#ivSCn0b)"><path class="xmkl394ic"/><path fill="url(#ith3ggn)" class="cx4kbf-7l"/><path fill="url(#ibMK9tZ)" class="cx4kbf-7l"/><path fill="url(#i2UhMFd)" class="cx4kbf-7l"/></g><g filter="url(#i6mX17c)"><path fill="url(#ijoiFsc)" class="m9x_67b1p"/></g><g filter="url(#iuGZcqc)"><path stroke="url(#i9N054d)" class="mxqilsb2s"/></g><path class="m3q0hebnp"/><g filter="url(#isJdWTd)"><path class="x2holubxf"/></g><g filter="url(#itngjob)"><path class="tlfh-zb5z"/></g><g filter="url(#idsEZBd)"><path fill="url(#i2DE7Ob)" class="lm4i8acfa"/><path fill="url(#i4rikgd)" class="lm4i8acfa"/></g><g filter="url(#iUgYNre)"><path fill="url(#i7w8oEe)" class="pikvlhblk"/><path fill="url(#iofCBrd)" class="pikvlhblk"/><path fill="url(#izHMhnb)" class="pikvlhblk"/></g><g filter="url(#iTvUgPc)"><path stroke="url(#iTyVMwd)" class="dqz0i8shm"/></g><g filter="url(#iVqi0ac)"><path fill="url(#iKHUPhd)" class="r9l9cddzl"/></g><g filter="url(#iYT05Kb)"><path fill="url(#ig9BDhd)" class="b1o8v8piu"/></g><path fill="url(#ia8ygBF)" class="ku10bybhf"/><path fill="url(#i8F2lKb)" class="kk9uf1qim"/><g filter="url(#iMwgQTd)" class="tryqaac1t"><path stroke="url(#ieTRn5c)" class="gltd2oydu"/><path stroke="url(#iw7Juqe)" class="gltd2oydu"/></g><g filter="url(#i584dxi)" class="tryqaac1t"><path stroke="url(#inJblJK)" class="rp9_zob9u"/><path stroke="url(#iYE6tHc)" class="rp9_zob9u"/></g><g filter="url(#iSj0JVd)"><path clip-rule="evenodd" class="dwu8q7oyh"/></g><g filter="url(#iqn1Ise)"><path class="q11mtobpa"/></g><defs><radialGradient id="iksbhAr" cx="0" cy="0" r="1" gradientTransform="matrix(1.13393 -4.11554 9.3837 2.58544 22.033 16.54)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="irNgTce" cx="0" cy="0" r="1" gradientTransform="matrix(-.93582 6.06747 -5.67953 -.87599 15.656 13.321)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="i12RqEb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82855 3.15679 -3.88584 -3.4818 13.29 14.837)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iVu6PEc" cx="0" cy="0" r="1" gradientTransform="rotate(114.733 1.498 9.773)scale(1.89211 1.71984)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i5YjKDc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53398 -.10031 .14746 -3.72496 11.278 10.84)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ipj9dRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.8622 2.90023 -5.0613 4.99494 10.57 4.164)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="inFjWne" cx="0" cy="0" r="1" gradientTransform="rotate(122.205 9.152 7.856)scale(1.73925 2.43057)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iHYBfob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82512 .91105 -1.98232 -3.97122 23.709 9.033)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iVqjJBb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03883 2.00047 -3.18736 -4.84178 23.957 11.992)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iynQxtM" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 1.9893 19.511 29.966)" gradientUnits="userSpaceOnUse"><stop class="n2a634bwb"/><stop offset="1" class="y9owwpbix"/></radialGradient><radialGradient id="iZQkIpe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50378 0 0 -5.6875 21.761 19.19)" gradientUnits="userSpaceOnUse"><stop class="z_i15q2zj"/><stop offset="1" class="uejyh8b9c"/></radialGradient><radialGradient id="i5QsWPe" cx="0" cy="0" r="1" gradientTransform="rotate(-154.983 12.47 9.038)scale(2.5864 3.5607)" gradientUnits="userSpaceOnUse"><stop class="tkrf14blt"/><stop offset="1" class="yv8ccsbrb"/></radialGradient><radialGradient id="ijt6gMc" cx="0" cy="0" r="1" gradientTransform="rotate(64.824 -4.786 21.049)scale(2.19716 4.32137)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="ml73qs-pc"/><stop offset="1" class="uerx76sxw"/></radialGradient><radialGradient id="i2Fbc4Y" cx="0" cy="0" r="1" gradientTransform="matrix(2.21876 -7 9.86052 3.12544 19.268 23.181)" gradientUnits="userSpaceOnUse"><stop offset=".783" class="cy9n5wbpf"/><stop offset="1" class="ptxa2ybkv"/></radialGradient><radialGradient id="iMiqFkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.79688 2.04686 -1.95763 2.67496 23.417 27.408)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tkcxzncwj"/><stop offset="1" class="mqicc-u0l"/></radialGradient><radialGradient id="iFqLLpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.3125 -2.12008 2.12008 22.011 27.846)" gradientUnits="userSpaceOnUse"><stop class="c14jvicyx"/><stop offset="1" class="i8x7p37cq"/></radialGradient><radialGradient id="iSOcTod" cx="0" cy="0" r="1" gradientTransform="rotate(126.08 3.113 12.145)scale(4.98797 9.68383)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7fe64b-m"/><stop offset="1" class="o3yqmrbrg"/></radialGradient><radialGradient id="i8kc3Ah" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45313 -.6875 0 13.87 28.345)" gradientUnits="userSpaceOnUse"><stop class="la4e9obft"/><stop offset="1" class="sq95r4vix"/></radialGradient><radialGradient id="iOA85ac" cx="0" cy="0" r="1" gradientTransform="rotate(-117.519 14.648 7.186)scale(1.35267 2.95016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="kc6luf8ah"/><stop offset="1" class="yit44gm3t"/></radialGradient><radialGradient id="i9zj7Tc" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 -1.6057 .88152 .74629 11.761 25.767)" gradientUnits="userSpaceOnUse"><stop class="c_e6lvb0e"/><stop offset="1" class="bzrv_p78g"/></radialGradient><radialGradient id="iOhkFTd" cx="0" cy="0" r="1" gradientTransform="rotate(-162.16 15.547 12.082)scale(.71402 1.53504)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></radialGradient><radialGradient id="ioEmbwd" cx="0" cy="0" r="1" gradientTransform="rotate(163.67 9.086 15.513)scale(5.1125 7.55864)" gradientUnits="userSpaceOnUse"><stop class="khg6a5-nz"/><stop offset="1" class="jyzijgb5l"/></radialGradient><radialGradient id="i2lgMJs" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 -1.0625 .82137 1.8964 14.8 30.764)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="smmag_bln"/><stop offset="1" class="w7g29ccgc"/></radialGradient><radialGradient id="ipEqElc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .36719 -.26111 -.32778 16.792 26.373)" gradientUnits="userSpaceOnUse"><stop class="zok0ncc-e"/><stop offset="1" class="kvdi0yb6u"/></radialGradient><radialGradient id="iQV2oJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 0 0 -.59662 16.175 28.244)" gradientUnits="userSpaceOnUse"><stop class="kd5gihbvg"/><stop offset="1" class="q45grmb6f"/></radialGradient><radialGradient id="idycZ0k" cx="0" cy="0" r="1" gradientTransform="rotate(154.496 10.79 13.826)scale(3.77401 4.40797)" gradientUnits="userSpaceOnUse"><stop class="w-wd4mb8i"/><stop offset="1" class="jswq_j2dq"/></radialGradient><radialGradient id="izDPRDe" cx="0" cy="0" r="1" gradientTransform="rotate(42.983 -16.037 40.648)scale(5.22527)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="i54m18vgp"/><stop offset=".995" class="nybv-x_bu"/></radialGradient><radialGradient id="iicGn0Q" cx="0" cy="0" r="1" gradientTransform="matrix(.39062 -3.01563 4.79304 .62086 19.418 24.439)" gradientUnits="userSpaceOnUse"><stop class="l99uylilx"/><stop offset="1" class="xjvfic_gd"/></radialGradient><radialGradient id="ihk7twn" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.355 27.845)" gradientUnits="userSpaceOnUse"><stop class="rq4-grb6j"/><stop offset="1" class="w6mxzsbgv"/></radialGradient><radialGradient id="imTiK4b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.355 27.845)" gradientUnits="userSpaceOnUse"><stop class="w1z7uu-9l"/><stop offset="1" class="tdfvsjb1z"/></radialGradient><radialGradient id="iu72mhc" cx="0" cy="0" r="1" gradientTransform="matrix(2.49219 1.72656 -.24906 .3595 19.44 23.4)" gradientUnits="userSpaceOnUse"><stop class="el-m6zb6s"/><stop offset="1" class="rfhjj0qfz"/></radialGradient><radialGradient id="inyGMTT" cx="0" cy="0" r="1" gradientTransform="matrix(1.89062 2.04687 -.34125 .3152 20.784 22.571)" gradientUnits="userSpaceOnUse"><stop class="el-m6zb6s"/><stop offset="1" class="rfhjj0qfz"/></radialGradient><radialGradient id="iI7DACc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 1.26562 -.211 .3178 19.721 25.212)" gradientUnits="userSpaceOnUse"><stop class="el-m6zb6s"/><stop offset="1" class="rfhjj0qfz"/></radialGradient><radialGradient id="ipKe3Nd" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 2.11719 -.35298 .03386 23.69 22.407)" gradientUnits="userSpaceOnUse"><stop class="el-m6zb6s"/><stop offset="1" class="rfhjj0qfz"/></radialGradient><radialGradient id="igEewoc" cx="0" cy="0" r="1" gradientTransform="rotate(-34.75 27.808 -26.962)scale(2.90468 3.54648)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="irx5C3b" cx="0" cy="0" r="1" gradientTransform="matrix(1.09658 .10829 -.05693 .57651 20.974 8.526)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="ixgOsUc" cx="0" cy="0" r="1" gradientTransform="rotate(-30.603 30.037 -32.772)scale(1.38596)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iEeGDKe" cx="0" cy="0" r="1" gradientTransform="rotate(169.694 5.02 6.62)scale(1.29277 1.23661)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iYBQ7Vc" cx="0" cy="0" r="1" gradientTransform="rotate(146.03 7.89 8.01)scale(6.60361 7.0438)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="o2dl4_b2z"/></radialGradient><radialGradient id="iQ5jbRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9931 1.56735 -1.32978 -1.691 18.038 11.157)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iAqT3qd" cx="0" cy="0" r="1" gradientTransform="matrix(.106 -4.3872 5.56654 .13449 14.93 18.293)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i1qFfOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2603 7.38141 -10.0059 1.7084 15.865 10.489)" gradientUnits="userSpaceOnUse"><stop offset=".783" class="qqu8h2bhn"/><stop offset="1" class="y-tmj9but"/></radialGradient><radialGradient id="iHKLBle" cx="0" cy="0" r="1" gradientTransform="rotate(162.034 7.478 7.9)scale(6.14479 10.5794)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iz2H1Jb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40788 .256 -.84279 -4.6348 21.449 10.938)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iwIzFWe" cx="0" cy="0" r="1" gradientTransform="matrix(2.01038 4.18985 -8.6581 4.15435 12.26 5.51)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ith3ggn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.19458 -2.42803 1.38935 -.68355 17.08 12.517)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i2DE7Ob" cx="0" cy="0" r="1" gradientTransform="matrix(2.5321 2.4354 -4.83913 5.0313 8.607 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i4rikgd" cx="0" cy="0" r="1" gradientTransform="rotate(116.812 4.304 6.493)scale(3.30504 2.59201)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="i7w8oEe" cx="0" cy="0" r="1" gradientTransform="rotate(105.378 7.226 7.644)scale(5.17687 7.3613)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iofCBrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.286 3.51515 -6.27466 -.51052 17.156 3.854)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="izHMhnb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.8595 -5.92153 5.30062 -4.34995 17.126 9.76)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iw7Juqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 19.144 10.458)" gradientUnits="userSpaceOnUse"><stop class="kjki5ab4n"/><stop offset="1" class="ql2-nbc9p"/></radialGradient><radialGradient id="iYE6tHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 14.677 11.21)" gradientUnits="userSpaceOnUse"><stop class="kjki5ab4n"/><stop offset="1" class="ql2-nbc9p"/></radialGradient><filter id="iJgg5sb" width="16.686" height="17.376" x="8.113" y="1.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iqev7lb" width="12.107" height="12.935" x="4.292" y="17.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iHQ2ePc" width="3.547" height="2.605" x="10.246" y="23.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".25"/></filter><filter id="iSD4Dqd" width="1.338" height="3.484" x="25.65" y="26.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".05"/></filter><filter id="iR7ynbb" width="8.034" height="4.188" x="6.668" y="26.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".5"/></filter><filter id="iwHuWJe" width="1.907" height="4.376" x="11.205" y="20.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".125"/></filter><filter id="icLcSeb" width="10.856" height="8.359" x="11.765" y="21.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iVJIzVi" width="6.652" height="4.473" x="14.118" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="illy8Yc" width="6.654" height="7.23" x="19.111" y="21.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.337255 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iXEAwhe" width="6.654" height="7.23" x="19.111" y="21.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.45098 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iYdeU5b" width="5.813" height="5.503" x="7.73" y="21.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".5"/></filter><filter id="isBJoDe" width="3.309" height="3.341" x="20.88" y="21.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".2"/></filter><filter id="ireoYqd" width="2.013" height="4.911" x="23.891" y="22.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".2"/></filter><filter id="iXXLFqb" width="3.294" height="2.926" x="19.598" y="22.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".2"/></filter><filter id="insiq8d" width="3.106" height="2.411" x="19.224" y="23.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".2"/></filter><filter id="iPKMEYc" width="3.043" height="2.122" x="19.208" y="25.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".2"/></filter><filter id="iRKNJgb" width="5.798" height=".972" x="14.85" y="28.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".15"/></filter><filter id="i11L9pe" width="3.57" height="3.669" x="9.414" y="10.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iJJH3Hb" width="3.42" height="3.669" x="19.358" y="8.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iVTS4Dd" width="3.283" height="3.283" x="19.426" y="8.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".25"/></filter><filter id="iEKS0ad" width="3.083" height="3.083" x="9.603" y="10.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".2"/></filter><filter id="iD6VSWb" width="11.204" height="11.213" x="10.317" y="6.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="i0si5tG" width="2.98" height="3.907" x="14.674" y="10.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".25"/></filter><filter id="ivSCn0b" width="2.48" height="3.396" x="15.067" y="10.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".125"/></filter><filter id="i6mX17c" width="2.48" height="3.396" x="15.021" y="10.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".125"/></filter><filter id="iuGZcqc" width="3.856" height="1.897" x="14.608" y="13.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".05"/></filter><filter id="isJdWTd" width="2.503" height="1.432" x="11.656" y="8.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="itngjob" width="2.27" height="1.277" x="11.665" y="8.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".1"/></filter><filter id="idsEZBd" width="4.252" height="5.924" x="8.699" y="4.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".25"/></filter><filter id="iUgYNre" width="10.031" height="4.981" x="11.346" y="3.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".125"/></filter><filter id="iTvUgPc" width="1.494" height="2.284" x="11.456" y="4.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".1"/></filter><filter id="iVqi0ac" width="3.89" height="2.988" x="11.525" y="9.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".3"/></filter><filter id="iYT05Kb" width="3.682" height="2.915" x="16.395" y="8.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".3"/></filter><filter id="iMwgQTd" width="2.582" height="1.236" x="16.902" y="10.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".075"/></filter><filter id="i584dxi" width="2.582" height="1.236" x="12.435" y="10.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".075"/></filter><filter id="iSj0JVd" width="2.625" height=".929" x="16.929" y="7.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3508"/></filter><filter id="iqn1Ise" width="2.401" height=".789" x="16.97" y="8.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3508" stdDeviation=".1"/></filter><linearGradient id="iI0znWd" x1="19.606" x2="14.889" y1="3.191" y2="17.659" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iHZyEQc" x1="26.793" x2="24.491" y1="25.127" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="up7b_htug"/><stop offset="1" class="bvctw1bkc"/></linearGradient><linearGradient id="i54qHIe" x1="15.261" x2="6.793" y1="19.282" y2="29.965" gradientUnits="userSpaceOnUse"><stop class="eoa632ltp"/><stop offset="1" class="rlw3b4b7i"/></linearGradient><linearGradient id="icIERhd" x1="13.48" x2="7.929" y1="28.97" y2="28.946" gradientUnits="userSpaceOnUse"><stop class="lzdnytbwv"/><stop offset="1" class="yasfqbb-e"/></linearGradient><linearGradient id="i7KzMRb" x1="13.155" x2="13.105" y1="24.358" y2="21.409" gradientUnits="userSpaceOnUse"><stop class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></linearGradient><linearGradient id="ii6jdYd" x1="21.355" x2="14.293" y1="27.689" y2="27.252" gradientUnits="userSpaceOnUse"><stop class="vrjrrpcnz"/><stop offset="1" class="qarzv5b-l"/></linearGradient><linearGradient id="ihL8Pee" x1="18.565" x2="18.55" y1="30.119" y2="29.306" gradientUnits="userSpaceOnUse"><stop offset=".204" class="v0__z17ai"/><stop offset="1" class="b6n4u8zgu"/></linearGradient><linearGradient id="iGhNH1d" x1="21.668" x2="20.168" y1="18.686" y2="23.282" gradientUnits="userSpaceOnUse"><stop class="rm6lemo-n"/><stop offset=".635" class="uny69rbro"/></linearGradient><linearGradient id="iHxzS7a" x1="25.558" x2="24.87" y1="25.302" y2="25.452" gradientUnits="userSpaceOnUse"><stop offset=".049" class="a8yl23ual"/><stop offset="1" class="phl_c1swt"/></linearGradient><linearGradient id="iGZvHCJ" x1="10.636" x2="13.293" y1="25.693" y2="22.445" gradientUnits="userSpaceOnUse"><stop class="lk8w5cclk"/><stop offset="1" class="qrasocbfu"/></linearGradient><linearGradient id="i4BS7Gd" x1="22.142" x2="24.279" y1="22.86" y2="24.715" gradientUnits="userSpaceOnUse"><stop offset=".076" class="p7s10-b8k"/><stop offset="1" class="zxz4xdh7g"/></linearGradient><linearGradient id="iFGK8WK" x1="24.746" x2="26.137" y1="23.656" y2="23.924" gradientUnits="userSpaceOnUse"><stop offset=".076" class="p7s10-b8k"/><stop offset="1" class="zxz4xdh7g"/></linearGradient><linearGradient id="iAcNhSb" x1="20.855" x2="22.592" y1="23.48" y2="25.336" gradientUnits="userSpaceOnUse"><stop offset=".076" class="p7s10-b8k"/><stop offset="1" class="zxz4xdh7g"/></linearGradient><linearGradient id="ioXOYOc" x1="20.422" x2="21.581" y1="24.65" y2="26.257" gradientUnits="userSpaceOnUse"><stop offset=".076" class="p7s10-b8k"/><stop offset="1" class="zxz4xdh7g"/></linearGradient><linearGradient id="ivKPd0d" x1="20.387" x2="21.186" y1="26.107" y2="27.514" gradientUnits="userSpaceOnUse"><stop offset=".076" class="p7s10-b8k"/><stop offset="1" class="zxz4xdh7g"/></linearGradient><linearGradient id="iXQ9tTc" x1="19.922" x2="15.689" y1="29.067" y2="29.011" gradientUnits="userSpaceOnUse"><stop class="aff71h6gc"/><stop offset="1" class="t5goepbug"/></linearGradient><linearGradient id="ix3Vijd" x1="9.459" x2="12.552" y1="12.638" y2="12.076" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="ibMK9tZ" x1="15.17" x2="16.083" y1="12.883" y2="12.83" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="i2UhMFd" x1="16.427" x2="16.311" y1="13.577" y2="12.94" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ijoiFsc" x1="15.853" x2="16.108" y1="10.576" y2="11.978" gradientUnits="userSpaceOnUse"><stop class="s7k33p2vn"/><stop offset="1" class="npl7d4bom"/></linearGradient><linearGradient id="i9N054d" x1="15.945" x2="16.253" y1="15.26" y2="14.263" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iTyVMwd" x1="11.822" x2="12.633" y1="5.422" y2="6.65" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iKHUPhd" x1="14.352" x2="11.665" y1="10.613" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="sv4maabhu"/><stop offset="1" class="hoafb6buw"/></linearGradient><linearGradient id="ig9BDhd" x1="19.092" x2="15.618" y1="10.083" y2="8.929" gradientUnits="userSpaceOnUse"><stop offset=".394" class="hdettxboa"/><stop offset="1" class="rf88abbhx"/></linearGradient><linearGradient id="ia8ygBF" x1="17.784" x2="19.315" y1="11.562" y2="10.437" gradientUnits="userSpaceOnUse"><stop offset=".048" class="zft5ozi2a"/><stop offset="1" class="zs6y5wbab"/></linearGradient><linearGradient id="i8F2lKb" x1="13.286" x2="14.824" y1="12.326" y2="11.203" gradientUnits="userSpaceOnUse"><stop offset=".048" class="zft5ozi2a"/><stop offset="1" class="zs6y5wbab"/></linearGradient><linearGradient id="ieTRn5c" x1="17.003" x2="19.332" y1="10.918" y2="11.079" gradientUnits="userSpaceOnUse"><stop class="ytn_p5bjt"/><stop offset="1" class="sel15-yew"/></linearGradient><linearGradient id="inJblJK" x1="12.536" x2="14.865" y1="11.67" y2="11.832" gradientUnits="userSpaceOnUse"><stop class="ytn_p5bjt"/><stop offset="1" class="sel15-yew"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:breast-feeding-medium-light" /></template>
<style>
.a3h4q-bko {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m20.198 23.078l2.093 1.727");
}

.a8yl23ual {
  stop-color: var(--svg-color--ecc2a4, #ECC2A4);
}

.aa1vmtrmd {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.57 11.192l-.392 1.907a.573.573 0 0 0 .677.632l.822-.15c.385-.07.59-.49.411-.83l-.878-1.676c-.191-.372-.588-.3-.64.117");
}

.aff71h6gc {
  stop-color: var(--svg-color--cc9e93, #CC9E93);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.arsyfvbsk {
  fill: var(--svg-color--dca694, #DCA694);
  d: path("M14.318 29.965h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.b1o8v8piu {
  d: path("M17.077 8.806c1.041-.328 2.4.235 2.4 1.624c-.672-.374-2.007-.519-2.482-.374z");
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b6n4u8zgu {
  stop-color: var(--svg-color--c0828c, #C0828C);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bmf08op0i {
  d: path("m13.45 23.88l.07-.038c.504-.273.896-.5 1.455-.825l.495-.286l.04-.023l.69-.397l-.005-.007a4.254 4.254 0 0 1 5.603 1.673c1.18 2.04.48 4.64-1.56 5.8l-.3.18h-5.585c.103-.706.152-1.978-.054-3.12c-.11-.613-.72-.997-1.341-.997h-1.193q.071-.167.156-.329a4.8 4.8 0 0 1 .8-1.066q.327-.316.73-.565");
}

.bvctw1bkc {
  stop-color: var(--svg-color--9c69f1, #9C69F1);
}

.bzrv_p78g {
  stop-color: var(--svg-color--44327f, #44327F);
  stop-opacity: 0;
}

.c_e6lvb0e {
  stop-color: var(--svg-color--44327f, #44327F);
}

.c14jvicyx {
  stop-color: var(--svg-color--603eb7, #603EB7);
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cd5b-kb9y {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.613 26.525c.274.907.367 2.165-.797 3.18");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cv7qblb2e {
  d: path("M20.935 22.07a.64.64 0 0 1 .913.018c.447.475 1.16 1.226 1.82 1.887a.05.05 0 0 0 .085-.04l-.089-.926a.67.67 0 0 1 1.32-.21l.692 3.103q.088.294.089.615c0 1.065-.766 1.95-1.777 2.136c-.697.2-1.485-.121-1.794-.308l-2.78-1.689a.632.632 0 0 1 .626-1.098l-.596-.429a.62.62 0 1 1 .737-.999l.186.141l-.656-.52a.648.648 0 1 1 .837-.989l1.156 1.046l-.79-.853a.636.636 0 0 1 .02-.886");
}

.cx4kbf-7l {
  d: path("m15.553 11.046l-.232 1.878a.573.573 0 0 0 .677.632l.822-.15c.385-.07.59-.49.411-.83l-.878-1.675c-.191-.372-.747-.271-.8.145");
}

.cy9n5wbpf {
  stop-color: var(--svg-color--dda47a, #DDA47A);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dqz0i8shm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.756 5.063c.07.25.465 1.164.895 1.683");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dwu8q7oyh {
  fill: var(--svg-color--966333, #966333);
  fill-rule: evenodd;
  d: path("m19.17 8.35l-.1.267za.285.285 0 0 1-.2.533h-.001l-.005-.002a1 1 0 0 0-.13-.039a3 3 0 0 0-.383-.076a2.4 2.4 0 0 0-1.138.108a.285.285 0 0 1-.198-.535a3 3 0 0 1 1.41-.138a3.5 3.5 0 0 1 .628.143l.011.004l.004.001z");
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dyn64notx {
  d: path("m10.464 10.998l.013-.002l-.06-.276l-.07-.318c-.159-.995.35-1.485.574-1.657l.05-.032l.049-.03c.51-.358.88-.888 1.009-1.517l.049-.218a.28.28 0 0 1 .472-.141a4.1 4.1 0 0 0 3.652 1.142l3.365-.611c.189-.035 1.148-.115 1.441 1.176l.46 3.235c.404 2.952-1.526 5.335-4.318 5.843c-2.793.508-5.438-1.043-6.1-3.949z");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.el-m6zb6s {
  stop-color: var(--svg-color--b98578, #B98578);
}

.eoa632ltp {
  stop-color: var(--svg-color--9165d0, #9165D0);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gltd2oydu {
  d: path("M17.152 10.828c.13.122.518.353 1.022.298s.947-.543 1.06-.728");
}

.gr1zvxbwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m24.49 22.791l.813 3.711");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hdettxboa {
  stop-color: var(--svg-color--f1b493, #F1B493);
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hoafb6buw {
  stop-color: var(--svg-color--c78979, #C78979);
  stop-opacity: 0;
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i08nc5kmh {
  d: path("M8.73 25.693h2.453c.425-.689 1.037-1.514 1.36-1.84a7 7 0 0 0-.531-1.664c-1.126.974-2.657 2.742-3.282 3.504");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i54m18vgp {
  stop-color: var(--svg-color--51e398, #51E398);
  stop-opacity: 0;
}

.i8x7p37cq {
  stop-color: var(--svg-color--603eb7, #603EB7);
  stop-opacity: 0;
}

.ilt675bqi {
  d: path("M25.578 29.966c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jbci68byv {
  d: path("M21.373 12.115a1.71 1.71 0 1 0-.611-3.364a1.71 1.71 0 0 0 .611 3.364");
}

.jswq_j2dq {
  stop-color: var(--svg-color--34e38b, #34E38B);
}

.jyzijgb5l {
  stop-color: var(--svg-color--248571, #248571);
  stop-opacity: 0;
}

.k7zt1gbjg {
  d: path("M10.746 25.767h1.57l.977-1.594c-1.675-.139-2.396 1.005-2.547 1.594");
}

.kc6luf8ah {
  stop-color: var(--svg-color--7556b0, #7556B0);
}

.kd5gihbvg {
  stop-color: var(--svg-color--dcaa92, #DCAA92);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.khg6a5-nz {
  stop-color: var(--svg-color--248571, #248571);
}

.kipcy4rpo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.3 29.067c.886.054 3.107.13 4.898 0");
}

.kjki5ab4n {
  stop-color: var(--svg-color--9a6b40, #9A6B40);
}

.kk9uf1qim {
  d: path("M14.607 10.981c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51c-.31.06-.62-.03-.86-.22a.25.25 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.4");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ku10bybhf {
  d: path("M19.106 10.228c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51s-.63-.03-.86-.23a.3.3 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.39");
}

.kvdi0yb6u {
  stop-color: var(--svg-color--d7aa95, #D7AA95);
  stop-opacity: 0;
}

.kwq6xetnq {
  d: path("M23.408 27.126a4.3 4.3 0 0 0 0-8.6c-2.375 0-3.553 1.925-3.553 4.3s1.178 4.3 3.553 4.3");
}

.l7ojjeadx {
  d: path("M21.538 23.906a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.l99uylilx {
  stop-color: var(--svg-color--309972, #309972);
}

.la4e9obft {
  stop-color: var(--svg-color--ac7ff8, #AC7FF8);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lk8w5cclk {
  stop-color: var(--svg-color--a176df, #A176DF);
}

.lm4i8acfa {
  d: path("M9.763 5.995c.544-.696 1.48-.872 2.022-.875l.666 1.273c-.276.008-.498.145-.665.374c-.154 1.838-1.99 1.9-2.1 3.278c-.442-1.53-.862-2.848.077-4.05");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lzdnytbwv {
  stop-color: var(--svg-color--a673ff, #A673FF);
}

.m3q0hebnp {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16.575 14.394a3.2 3.2 0 0 1-1.551-.09c-.16-.05-.288.148-.17.268a2.052 2.052 0 0 0 3.396-.618c.066-.159-.121-.294-.254-.19a3.2 3.2 0 0 1-1.42.63");
}

.m9x_67b1p {
  d: path("m15.508 10.944l-.233 1.878a.573.573 0 0 0 .677.632l.822-.15c.386-.07.59-.49.411-.83l-.878-1.675c-.19-.372-.746-.27-.8.145");
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.ml73qs-pc {
  stop-color: var(--svg-color--af7051, #AF7051);
}

.mqicc-u0l {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
  stop-opacity: 0;
}

.mujxyf7za {
  d: path("M17.348 16.426c-.72 0-1.42.08-2.09.22v2.42c0 3.48 2.93 6.25 6.41 6.06l5.58-.31c-.7-4.74-4.86-8.39-9.9-8.39");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mxqilsb2s {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.575 14.394a3.2 3.2 0 0 1-1.551-.09c-.16-.05-.288.148-.17.268a2.052 2.052 0 0 0 3.396-.618c.066-.159-.121-.294-.254-.19a3.2 3.2 0 0 1-1.42.63Z");
}

.n2a634bwb {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
}

.n7fe64b-m {
  stop-color: var(--svg-color--6a428c, #6A428C);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nl-c4e4xq {
  d: path("M27.515 27.47c-.013-.404-.165-2.416-.222-3.116l-2.825.18l-3.008 3.324c0 1.263.513 1.95.805 2.108h4.39c.969-.964.868-2.21.86-2.495");
}

.npl7d4bom {
  stop-color: var(--svg-color--eeb696, #EEB696);
  stop-opacity: 0;
}

.npmp30b8c {
  d: path("M14.318 29.965h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.nybv-x_bu {
  stop-color: var(--svg-color--51e398, #51E398);
}

.o2dl4_b2z {
  stop-color: var(--svg-color--cd9682, #CD9682);
}

.o3yqmrbrg {
  stop-color: var(--svg-color--885ebc, #885EBC);
  stop-opacity: 0;
}

.oi6iyacka {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.631 21.127c.344.635 1.032 2.281 1.032 3.781");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p7s10-b8k {
  stop-color: var(--svg-color--d6aa9b, #D6AA9B);
}

.phl_c1swt {
  stop-color: var(--svg-color--e4b49c, #E4B49C);
  stop-opacity: 0;
}

.pikvlhblk {
  d: path("M13.91 3.322c-1.231-.046-2.27 1.445-2.314 1.905c2.3 3.491 4.71 2.68 7.4 1.876c1.61-.482 1.925.235 2.131.572c-1.226-4.157-4.41-4.248-7.217-4.353");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.ptxa2ybkv {
  stop-color: var(--svg-color--dda47a, #DDA47A);
}

.pvstcpbcm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.824 24.368l1.906 1.211");
}

.q11mtobpa {
  stroke: var(--svg-color--98693e, #98693E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.27 8.547c.323-.144 1.168-.255 1.802.044");
}

.q45grmb6f {
  stop-color: var(--svg-color--dba591, #DBA591);
  stop-opacity: 0;
}

.q55omib7e {
  d: path("M7.668 27.126h6.034v2.188H7.668z");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qarzv5b-l {
  stop-color: var(--svg-color--37ba71, #37BA71);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.ql2-nbc9p {
  stop-color: var(--svg-color--9a6b40, #9A6B40);
  stop-opacity: 0;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qqu8h2bhn {
  stop-color: var(--svg-color--b47d76, #B47D76);
  stop-opacity: 0;
}

.qrasocbfu {
  stop-color: var(--svg-color--a176df, #A176DF);
  stop-opacity: 0;
}

.qtbzeirls {
  stop-color: var(--svg-color--a980f3, #A980F3);
}

.qyvp3x_ro {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M21.272 11.556a1.141 1.141 0 1 0-.408-2.245a1.141 1.141 0 0 0 .408 2.245");
}

.r9l9cddzl {
  d: path("M12.125 9.754c1.375-.263 2.41.604 2.69 1.37c-1.413.208-2.056.135-2.494.37z");
}

.rf88abbhx {
  stop-color: var(--svg-color--f1b493, #F1B493);
  stop-opacity: 0;
}

.rfhjj0qfz {
  stop-color: var(--svg-color--b98578, #B98578);
  stop-opacity: 0;
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rlw3b4b7i {
  stop-color: var(--svg-color--9565e9, #9565E9);
}

.rm6lemo-n {
  stop-color: var(--svg-color--3db155, #3DB155);
}

.rp9_zob9u {
  d: path("M12.685 11.58c.13.122.517.353 1.021.298s.947-.543 1.06-.728");
}

.rq4-grb6j {
  stop-color: var(--svg-color--b1817b, #B1817B);
}

.s7k33p2vn {
  stop-color: var(--svg-color--eeb696, #EEB696);
}

.sel15-yew {
  stop-color: var(--svg-color--95663c, #95663C);
  stop-opacity: 0;
}

.smmag_bln {
  stop-color: var(--svg-color--dc9b97, #DC9B97);
}

.sq95r4vix {
  stop-color: var(--svg-color--a476f3, #A476F3);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sv4maabhu {
  stop-color: var(--svg-color--c78979, #C78979);
}

.t5goepbug {
  stop-color: var(--svg-color--cc9e93, #CC9E93);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tce23o4qc {
  stop-color: var(--svg-color--a980f3, #A980F3);
  stop-opacity: 0;
}

.tdfvsjb1z {
  stop-color: var(--svg-color--ca998c, #CA998C);
}

.tkcxzncwj {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
}

.tkrf14blt {
  stop-color: var(--svg-color--bd9873, #BD9873);
}

.tlfh-zb5z {
  stroke: var(--svg-color--98693e, #98693E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.636 9.222c-.352-.02-1.183.173-1.67.676");
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u1zn18zmi {
  fill: var(--svg-color--642fc5, #642FC5);
  d: path("M25.578 29.966c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uejyh8b9c {
  stop-color: var(--svg-color--dba787, #DBA787);
}

.uerx76sxw {
  stop-color: var(--svg-color--b2775e, #B2775E);
  stop-opacity: 0;
}

.un_ysrbes {
  d: path("M11.43 13.923a1.71 1.71 0 1 0-.612-3.364a1.71 1.71 0 0 0 .612 3.364");
}

.uny69rbro {
  stop-color: var(--svg-color--38aa6f, #38AA6F);
}

.up7b_htug {
  stop-color: var(--svg-color--ab84ee, #AB84EE);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v0__z17ai {
  stop-color: var(--svg-color--c0828c, #C0828C);
}

.vrjrrpcnz {
  stop-color: var(--svg-color--349373, #349373);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vwn1d4b1p {
  d: path("M23.8 11.458c.14-.495.164-1.024.067-1.553a3.5 3.5 0 0 0-.528-1.314h.005a3.4 3.4 0 0 0-.391-.483l-.003-.003a3.44 3.44 0 0 1-.887-1.751l-.002-.01a3.506 3.506 0 0 0-4.075-2.822a.57.57 0 0 1-.52-.157a3.51 3.51 0 0 0-3.065-.929a3.51 3.51 0 0 0-2.542 1.948a.6.6 0 0 1-.431.33l-.09.018A3.506 3.506 0 0 0 8.607 8.79l.002.01a3.44 3.44 0 0 1-.213 1.951l-.002.005a3.5 3.5 0 0 0 .387 3.433a.55.55 0 0 1 .086.476a3.5 3.5 0 0 0-.071 1.532a3.414 3.414 0 0 0 3.975 2.752l8.97-1.63a3.414 3.414 0 0 0 2.753-3.976a3.5 3.5 0 0 0-.606-1.41a.55.55 0 0 1-.087-.475m-13.323-.463l-.013.002l1.701 2.234c.662 2.906 1.272-.23 4.065-.739c2.792-.507 4.602 2.532 4.198-.421l.58-3.558c-.293-1.29-1.252-1.21-1.44-1.176l-3.366.612a4.1 4.1 0 0 1-3.652-1.143a.28.28 0 0 0-.472.141l-.05.218a2.44 2.44 0 0 1-1.008 1.517l-.05.03q-.026.019-.05.032c-.223.173-.732.662-.573 1.658l.07.318z");
}

.w-wd4mb8i {
  stop-color: var(--svg-color--53ffa2, #53FFA2);
}

.w1z7uu-9l {
  stop-color: var(--svg-color--dca897, #DCA897);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w7g29ccgc {
  stop-color: var(--svg-color--e3af9a, #E3AF9A);
  stop-opacity: 0;
}

.wj1bd858m {
  d: path("M21.272 11.556a1.141 1.141 0 1 0-.408-2.245a1.141 1.141 0 0 0 .408 2.245");
}

.x2holubxf {
  fill: var(--svg-color--966333, #966333);
  d: path("m12.133 10.138l-.005.003a.285.285 0 0 1-.375-.428l.001-.001l.003-.003l.009-.007a2 2 0 0 1 .14-.109a4 4 0 0 1 .398-.247a3 3 0 0 1 1.368-.366a.285.285 0 0 1 .003.57c-.43.002-.817.147-1.103.3a3 3 0 0 0-.44.288");
}

.x59y2qb9p {
  d: path("m10.416 10.72l-.069-.318c-.159-.995.35-1.485.574-1.657l.05-.032l.049-.03c.51-.358.88-.888 1.009-1.517l.049-.218a.28.28 0 0 1 .472-.141a4.1 4.1 0 0 0 3.652 1.142l3.365-.611c.189-.035 1.148-.115 1.441 1.176l.46 3.235c.404 2.952-1.526 5.335-4.318 5.843c-2.793.508-5.438-1.043-6.1-3.949z");
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xjvfic_gd {
  stop-color: var(--svg-color--309972, #309972);
  stop-opacity: 0;
}

.xlfd0lbte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m21.48 22.361l2.11 2.141");
}

.xmkl394ic {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.553 11.046l-.232 1.878a.573.573 0 0 0 .677.632l.822-.15c.385-.07.59-.49.411-.83l-.878-1.675c-.191-.372-.747-.271-.8.145");
}

.y-tmj9but {
  stop-color: var(--svg-color--b97e66, #B97E66);
}

.y9owwpbix {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
  stop-opacity: 0;
}

.yasfqbb-e {
  stop-color: var(--svg-color--a673ff, #A673FF);
  stop-opacity: 0;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yg13ih15u {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.348 13.36a1.141 1.141 0 1 0-.408-2.246a1.141 1.141 0 0 0 .408 2.246");
}

.yghn3nr2v {
  d: path("M11.348 13.36a1.141 1.141 0 1 0-.408-2.246a1.141 1.141 0 0 0 .408 2.246");
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yhwzdxbte {
  d: path("M13.57 17.03c-3.353 1.353-6.48 5.4-8.312 7.956c-.71.854-1.718 2.662-.086 4.979h9.18c.104-.703.154-1.982-.053-3.129c-.11-.612-.72-.996-1.341-.996H11.76c.102-.265.73-1.357 1.801-1.937c.505-.273.854-.563 1.413-.886l.495-.287l.73-.42a6.03 6.03 0 0 1-.942-3.245v-1.452a5.2 5.2 0 0 1-1.689-.583");
}

.yit44gm3t {
  stop-color: var(--svg-color--9165d2, #9165D2);
  stop-opacity: 0;
}

.ytn_p5bjt {
  stop-color: var(--svg-color--95663c, #95663C);
}

.yv8ccsbrb {
  stop-color: var(--svg-color--bd9873, #BD9873);
  stop-opacity: 0;
}

.z_i15q2zj {
  stop-color: var(--svg-color--f6c498, #F6C498);
}

.z3dsw3evh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.808 25.893l1.843.922");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zft5ozi2a {
  stop-color: var(--svg-color--724520, #724520);
}

.zok0ncc-e {
  stop-color: var(--svg-color--d7aa95, #D7AA95);
}

.zs6y5wbab {
  stop-color: var(--svg-color--9f6a39, #9F6A39);
}

.zxz4xdh7g {
  stop-color: var(--svg-color--d6aa9b, #D6AA9B);
  stop-opacity: 0;
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
