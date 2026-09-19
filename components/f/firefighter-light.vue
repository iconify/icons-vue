<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ic8fRGr)"><path fill="url(#idOqQfb)" class="xaw01bbos"/><path fill="url(#i0T1tZb)" class="xaw01bbos"/></g><path class="jdxmb52mf"/><path fill="url(#iUpMsAc)" class="ch1z91b1l"/><path fill="url(#icZGiLb)" class="ch1z91b1l"/><path fill="url(#iu6Wrod)" class="ch1z91b1l"/><path fill="url(#iMlRJxc)" class="ch1z91b1l"/><path fill="url(#iXNg7ee)" class="ch1z91b1l"/><path fill="url(#iTWP8fb)" class="ch1z91b1l"/><path fill="url(#i0OnRmT)" class="l3ncvzbdn"/><path fill="url(#iKExcgc)" class="l3ncvzbdn"/><path fill="url(#ihW1CSc)" class="l3ncvzbdn"/><path fill="url(#ii9duvP)" class="ngoxnf3cj"/><path fill="url(#iOkhOub)" class="ngoxnf3cj"/><path fill="url(#iW91Exd)" class="k1i9p0bsc"/><path fill="url(#ibvao2d)" class="iv8z07bee"/><path fill="url(#iBJI7CF)" class="o7ecqy6er"/><path class="idtgv5oha"/><path class="fu_oxfbmp"/><g filter="url(#iqO9HTc)"><path fill="url(#ikM9Agb)" class="czdt2zbwf"/></g><path fill="url(#ilZeI1b)" class="czdt2zbwf"/><path fill="url(#iS0y3xo)" class="czdt2zbwf"/><path fill="url(#iAP8VId)" class="czdt2zbwf"/><path fill="url(#iJ7nJid)" class="czdt2zbwf"/><path fill="url(#if8dLAd)" class="czdt2zbwf"/><path fill="url(#iqkVWXc)" class="czdt2zbwf"/><path fill="url(#ikjW83d)" class="czdt2zbwf"/><path fill="url(#iCAfxed)" class="czdt2zbwf"/><g filter="url(#iesLbkG)"><path class="a7tc-5n0k"/></g><g filter="url(#icztznb)"><path class="xshacufje"/><path fill="url(#iYmHPjc)" class="mnvcpv1ta"/><path fill="url(#i0bYqih)" class="mnvcpv1ta"/><path fill="url(#i6bTfBc)" class="mnvcpv1ta"/><path fill="url(#ikcEeFd)" class="mnvcpv1ta"/><path fill="url(#ilIEbWc)" class="mnvcpv1ta"/><path fill="url(#iEX93yr)" class="mnvcpv1ta"/></g><g filter="url(#io9xa4c)"><path stroke="url(#i9cdkHc)" class="dvn_dpgso"/></g><path fill="url(#iFpa2Ed)" class="t78ap5knf"/><g filter="url(#iV4tlid)"><path class="uqd0hrbrc"/></g><g filter="url(#iWtedtd)"><path class="e7wmyp--e"/></g><path class="vhb-9rbjm"/><path fill="url(#i8zMfre)" class="bqyd3xsoj"/><path class="xd_f5751e"/><g filter="url(#iVrFsFe)"><path class="yf5fg-b3d"/><path fill="url(#ix1ifII)" class="c2fvupbhm"/></g><g filter="url(#i13dbxd)"><path fill="url(#iVEGhQc)" class="hfwqocc6k"/></g><path class="a_wlscc0j"/><path fill="url(#iNacCpb)" class="r_b3_hmve"/><path class="tc24b9b-k"/><g filter="url(#iAtu2Mc)"><path fill="url(#izYmlAo)" class="pyppa9bhc"/></g><g filter="url(#iRLVFbS)"><ellipse transform="rotate(-27.914 12.144 9.741)" class="lrfxelb0q"/><ellipse fill="url(#iz7oSFd)" transform="rotate(-27.914 12.144 9.741)" class="klf5_8xkp"/></g><path fill="url(#iQQ8Ohc)" class="x2ucuew1i"/><path fill="url(#imDWjgc)" class="x2ucuew1i"/><path fill="url(#iD9Vzqb)" class="lmxjjuxmu"/><path fill="url(#i7B1lLe)" class="lmxjjuxmu"/><g filter="url(#il7XZbb)"><path fill="url(#is0LUUg)" class="ol86facts"/></g><g filter="url(#iDqqrme)"><path fill="url(#iSpaHoc)" class="nmwx-my4c"/></g><path fill="url(#iAZwTjc)" class="hcoiftubs"/><path fill="url(#inAvhPe)" class="hcoiftubs"/><path fill="url(#iQCHywe)" class="hcoiftubs"/><path fill="url(#i8DKRyc)" class="hcoiftubs"/><path fill="url(#iXXnzAb)" class="hcoiftubs"/><g filter="url(#iHS4Fqc)"><path clip-rule="evenodd" class="m1r_ulisi"/><path fill="url(#iI6TmFd)" clip-rule="evenodd" class="xn32oub6d"/><path fill="url(#ip6gvad)" clip-rule="evenodd" class="xn32oub6d"/></g><g filter="url(#irOfISd)"><path fill="url(#igmNIve)" class="qd0uvdb-t"/></g><path fill="url(#i2AbEQu)" class="qd0uvdb-t"/><path fill="url(#iFpgHgb)" class="qd0uvdb-t"/><path class="n5n8hnbyl"/><path fill="url(#iUU1Dmp)" class="vytbrlpyt"/><path fill="url(#iHXsOFc)" class="vytbrlpyt"/><path fill="url(#imYeUjc)" class="vytbrlpyt"/><path fill="url(#ittKgdb)" class="vytbrlpyt"/><path fill="url(#i74C6Ge)" class="fel_7_bsv"/><path fill="url(#ir6g17d)" class="fel_7_bsv"/><path fill="url(#izP8X1d)" class="fel_7_bsv"/><path fill="url(#iIkB8SW)" class="fel_7_bsv"/><path fill="url(#i1NN5Jg)" class="fel_7_bsv"/><path fill="url(#i6fWVwc)" class="fpq8mcn4d"/><path fill="url(#i41fx8b)" class="fpq8mcn4d"/><path fill="url(#iXacfhc)" class="fpq8mcn4d"/><g filter="url(#iV9yfrb)"><path fill="url(#iO3h6Cc)" class="y3u79wbum"/><path fill="url(#icqQFkA)" class="y3u79wbum"/></g><g filter="url(#i4E9nMe)"><path fill="url(#i1BHX9W)" class="qocu5my9d"/><path fill="url(#iptIHld)" class="qocu5my9d"/></g><path fill="url(#i42OoDp)" class="qocu5my9d"/><path fill="url(#iwrTr9h)" class="qocu5my9d"/><g filter="url(#ivwU2jd)"><path fill="url(#iKLYvjb)" class="tneymrbip"/><path fill="url(#inkihGb)" class="tneymrbip"/><path fill="url(#iJYQuxe)" class="tneymrbip"/></g><g filter="url(#ius7Ppc)"><path fill="url(#iVVkgte)" class="kknssvxhe"/><path fill="url(#iKwUsJd)" class="kknssvxhe"/><path fill="url(#ip6zegb)" class="kknssvxhe"/></g><g filter="url(#ihRwOLF)"><path fill="url(#iHml9hb)" class="zu_qc9wey"/></g><g filter="url(#iwtIauW)"><path stroke="url(#ifV5Vgb)" class="ae53iocyb"/></g><g filter="url(#iKUJrIe)"><path class="z7587oiyb"/></g><defs><radialGradient id="iUpMsAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.915)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="icZGiLb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.227)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iu6Wrod" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.102)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iMlRJxc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.914)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iXNg7ee" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.695)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="iTWP8fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.233)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="i0OnRmT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.865 29.727)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="ihW1CSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.945)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="ii9duvP" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.95)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iOkhOub" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.945)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="ibvao2d" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.27 19.753)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iBJI7CF" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 8.54 12.185)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="ikM9Agb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -4.9375 16.568 12.605)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="d5o6as12m"/></radialGradient><radialGradient id="iS0y3xo" cx="0" cy="0" r="1" gradientTransform="scale(10.4477 12.6162)rotate(90 .52 .882)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="www4dfogh"/><stop offset=".998" class="dp0wpobtc"/></radialGradient><radialGradient id="iAP8VId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.044 9.44)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iJ7nJid" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 12.297 9.487)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="if8dLAd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 18.03 11.741)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iqkVWXc" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 9.13 6.428)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ikjW83d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 17.024 5.774)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iCAfxed" cx="0" cy="0" r="1" gradientTransform="rotate(-90 15 .355)scale(8.40625 10.9554)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="atz-d10et"/><stop offset=".926" class="sbgwyibuw"/></radialGradient><radialGradient id="i0bYqih" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.063 12.114)" gradientUnits="userSpaceOnUse"><stop class="btsp6rbtk"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="ikcEeFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 15.18 11.545)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iFpa2Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 14.597 14.293)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="i8zMfre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.78 9.837)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ix1ifII" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.705 .908)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNacCpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.415 9.837)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iz7oSFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.128 10.056)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imDWjgc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 19.215 9.85)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="i7B1lLe" cx="0" cy="0" r="1" gradientTransform="rotate(147.548 3.533 6.593)scale(2.24216 2.40686)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="is0LUUg" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 9.682 10.495)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iAZwTjc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.049 7.08)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="iQCHywe" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.039)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="i8DKRyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.07)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="iXXnzAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.164)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="iI6TmFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.156 16.039)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="ip6gvad" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94025 -.49362 1.26336 12.19 16.04)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="igmNIve" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.792 11.69)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="iFpgHgb" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.994 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iUU1Dmp" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.789)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="ittKgdb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.757 20.734)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="ir6g17d" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.147)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="izP8X1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.117)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="iIkB8SW" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.102)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i1NN5Jg" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.008)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="i41fx8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.728)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="iXacfhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.8)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iO3h6Cc" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.465 3.47)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="icqQFkA" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.258)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iptIHld" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .538 19.622)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="i42OoDp" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.367)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iwrTr9h" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.304)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="inkihGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.853 16.92)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="iJYQuxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.352)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="iVVkgte" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.033 15.763)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iKwUsJd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.476)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="ip6zegb" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.066 12.537)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><linearGradient id="idOqQfb" x1="14.587" x2="14.587" y1="7.945" y2="19.445" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="i0T1tZb" x1="14.587" x2="14.587" y1="7.222" y2="10.816" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="iKExcgc" x1="7.607" x2="6.49" y1="26.633" y2="26.602" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iW91Exd" x1="15.654" x2="15.654" y1="14.998" y2="21.335" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ilZeI1b" x1="19.754" x2="15.402" y1="12.439" y2="12.439" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iYmHPjc" x1="15.435" x2="14.597" y1="11.428" y2="11.463" gradientUnits="userSpaceOnUse"><stop offset=".36" class="ufuwm4b_g"/><stop offset="1" class="btg3hq-4h"/></linearGradient><linearGradient id="i6bTfBc" x1="14.597" x2="14.597" y1="12.568" y2="12.102" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="ilIEbWc" x1="14.597" x2="14.597" y1="9.733" y2="10.409" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iEX93yr" x1="13.658" x2="14.74" y1="11.543" y2="11.761" gradientUnits="userSpaceOnUse"><stop offset=".267" class="l3tmebbqj"/><stop offset="1" class="ll-mw-ixu"/></linearGradient><linearGradient id="i9cdkHc" x1="13.395" x2="13.714" y1="14.138" y2="13.304" gradientUnits="userSpaceOnUse"><stop class="snoqkbcuc"/><stop offset="1" class="wnvueqbtf"/></linearGradient><linearGradient id="iVEGhQc" x1="17.557" x2="17.243" y1="9.891" y2="10.084" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izYmlAo" x1="13.159" x2="12.845" y1="9.891" y2="10.084" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQQ8Ohc" x1="21.033" x2="19.826" y1="9.918" y2="12.094" gradientUnits="userSpaceOnUse"><stop offset=".259" class="hiucezb5p"/><stop offset="1" class="e55r0nb3z"/></linearGradient><linearGradient id="iD9Vzqb" x1="8.747" x2="9.412" y1="10.622" y2="9.136" gradientUnits="userSpaceOnUse"><stop class="f_83_eqnj"/><stop offset="1" class="mnq27woiv"/></linearGradient><linearGradient id="iSpaHoc" x1="20.076" x2="19.603" y1="9.547" y2="10.964" gradientUnits="userSpaceOnUse"><stop class="cryv69bud"/><stop offset="1" class="tzrhvuzsh"/></linearGradient><linearGradient id="inAvhPe" x1="10.646" x2="16.99" y1="6.695" y2="6.695" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i2AbEQu" x1="13.277" x2="13.489" y1="18.07" y2="18.07" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iHXsOFc" x1="14.592" x2="14.592" y1="30.289" y2="28.695" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="imYeUjc" x1="14.592" x2="14.592" y1="26.145" y2="27.414" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i74C6Ge" x1="14.582" x2="14.582" y1="6.945" y2="11.727" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="i6fWVwc" x1="14.582" x2="14.582" y1="19.578" y2="26.148" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="i1BHX9W" x1="22.021" x2="18.333" y1="16.726" y2="29.945" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="iKLYvjb" x1="20.021" x2="28.208" y1="22.164" y2="18.852" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="iHml9hb" x1="14.458" x2="14.458" y1="4.193" y2="6.639" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="ifV5Vgb" x1="18.689" x2="20.193" y1="21.62" y2="16.43" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="ic8fRGr" width="17.197" height="11.9" x="5.989" y="7.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/></filter><filter id="iqO9HTc" width="11.22" height="12.542" x="9.534" y="4.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2616" result="effect2_innerShadow_4002_2616"/></filter><filter id="iesLbkG" width="3.747" height="4.9" x="12.582" y="8.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".5"/></filter><filter id="icztznb" width="2.277" height="3.3" x="13.458" y="9.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".1"/></filter><filter id="io9xa4c" width="3.718" height="1.573" x="12.738" y="13.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".05"/></filter><filter id="iV4tlid" width="2.339" height="1.19" x="16.186" y="7.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/></filter><filter id="iWtedtd" width="2.339" height="1.176" x="10.93" y="7.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/></filter><filter id="iVrFsFe" width=".787" height=".696" x="16.045" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".05"/></filter><filter id="i13dbxd" width=".891" height=".913" x="16.885" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".1"/></filter><filter id="iAtu2Mc" width=".986" height="1.04" x="12.442" y="9.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".1"/></filter><filter id="iRLVFbS" width=".913" height=".704" x="11.687" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".05"/></filter><filter id="il7XZbb" width="1.329" height="2.379" x="8.516" y="9.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".125"/></filter><filter id="iDqqrme" width="1.947" height="2.903" x="19.103" y="9.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".25"/></filter><filter id="iHS4Fqc" width="6.88" height="3.666" x="11.157" y="15.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/></filter><filter id="irOfISd" width="4.97" height="3.828" x="13.277" y="15.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/></filter><filter id="iV9yfrb" width="5.52" height="4.05" x="11.827" y="2.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2616" result="effect2_innerShadow_4002_2616"/></filter><filter id="i4E9nMe" width="6.94" height="14.221" x="16.577" y="15.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2616" result="effect2_innerShadow_4002_2616"/></filter><filter id="ivwU2jd" width="11.012" height="8.855" x="17.86" y="16.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2616" result="effect2_innerShadow_4002_2616"/></filter><filter id="ius7Ppc" width="4.557" height="7.476" x="23.816" y="17.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2616"/></filter><filter id="ihRwOLF" width="2.509" height="3.213" x="13.154" y="3.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2616"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2616" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2616" result="effect3_innerShadow_4002_2616"/></filter><filter id="iwtIauW" width="1.83" height="4.718" x="18.091" y="17.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".125"/></filter><filter id="iKUJrIe" width="2.769" height="7.081" x="18.396" y="23.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2616" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:firefighter-light" /></template>
<style>
.a_wlscc0j {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.206 9.088c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.a7tc-5n0k {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.196 10.23l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.839c-.106-.407-.504-.407-.615 0");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ae53iocyb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 17.945l-1.08 3.968");
}

.atz-d10et {
  stop-color: var(--svg-color--c97c69, #C97C69);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.bqyd3xsoj {
  d: path("M16.781 9.36a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.btg3hq-4h {
  stop-color: var(--svg-color--ffceb9, #FFCEB9);
  stop-opacity: 0;
}

.btsp6rbtk {
  stop-color: var(--svg-color--fec8b8, #FEC8B8);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c2fvupbhm {
  d: path("M16.716 9.549c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.ch1z91b1l {
  d: path("M14.587 15.445c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cryv69bud {
  stop-color: var(--svg-color--d99a87, #D99A87);
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.czdt2zbwf {
  d: path("M9.772 13.518a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.69.238 5.556");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d5o6as12m {
  stop-color: var(--svg-color--d8a195, #D8A195);
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dp0wpobtc {
  stop-color: var(--svg-color--cb8281, #CB8281);
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dvn_dpgso {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.246 13.255a.23.23 0 0 0-.271.046a.21.21 0 0 0-.024.271c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e55r0nb3z {
  stop-color: var(--svg-color--e9aa98, #E9AA98);
}

.e7wmyp--e {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.186 7.906a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.002.001a.277.277 0 0 1-.34-.438z");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f_83_eqnj {
  stop-color: var(--svg-color--cb897b, #CB897B);
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.fel_7_bsv {
  d: path("M8.659 7.945h11.847c.948 0 1.988.485 1.988 2.68h.692V9.32c0-1.43-.848-2.375-2.457-2.375H8.436c-1.61 0-2.457.946-2.457 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fpq8mcn4d {
  d: path("M15.167 19.578h-1.17v6.57h1.17z");
}

.ft5dv1b6b {
  fill: none;
}

.fu_oxfbmp {
  fill: var(--svg-color--1e080a, #1E080A);
  d: path("M19.686 7.51q.046.172.049.357l-.079 1.606c.234.042.48.138.667.269V8.554c0-.311.096-.617.27-.875a1 1 0 0 0 .093-.168z");
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hcoiftubs {
  d: path("M20.886 7.305H8.289v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.166 2.193 5.166 4.927z");
}

.hfwqocc6k {
  d: path("M17.576 10.135a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.hiucezb5p {
  stop-color: var(--svg-color--ce8f7e, #CE8F7E);
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.idtgv5oha {
  fill: var(--svg-color--251314, #251314);
  d: path("M8.528 7.52q.037.086.093.168c.172.258.266.563.266.874v1.2c.197-.14.458-.226.708-.263l-.03-1.537q0-.226.028-.442z");
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iv8z07bee {
  d: path("M19.458 12.003c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jdxmb52mf {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.445c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k1i9p0bsc {
  d: path("M13.277 15.945v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kknssvxhe {
  d: path("M25.649 17.983a3.5 3.5 0 0 0 .85-.171l.148-.055c.179-.062.401-.054.555.107c1.071 1.126 1.43 2.622.983 4.236c-.447 1.615-1.732 2.764-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.003-1.472-3.735z");
}

.klf5_8xkp {
  cx: 12.144px;
  cy: 9.741px;
  rx: 0.39px;
  ry: 0.197px;
}

.kmg6h4b5x {
  stop-color: var(--svg-color--bd585d, #BD585D);
  stop-opacity: 0;
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l3ncvzbdn {
  d: path("M7.607 29.945V17.943a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.l3tmebbqj {
  stop-color: var(--svg-color--e1ac9e, #E1AC9E);
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll-mw-ixu {
  stop-color: var(--svg-color--e1ac9e, #E1AC9E);
  stop-opacity: 0;
}

.lmxjjuxmu {
  d: path("M9.553 8.894a1.62 1.62 0 0 0-1.392 1.594c0 .859.673 1.56 1.52 1.607a78 78 0 0 1-.128-3.201");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lrfxelb0q {
  cx: 12.144px;
  cy: 9.741px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m1r_ulisi {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.157 16.04v1.585c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnq27woiv {
  stop-color: var(--svg-color--ad6c5e, #AD6C5E);
}

.mnvcpv1ta {
  d: path("m14.215 10.039l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n5n8hnbyl {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.145H7.607v3.8h13.97z");
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.ngoxnf3cj {
  d: path("M21.577 17.955v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nmwx-my4c {
  d: path("M19.603 11.45q.058-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o7ecqy6er {
  d: path("M9.736 12.003a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ol86facts {
  d: path("M9.512 9.555a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.pyppa9bhc {
  d: path("M13.228 10.148c0-.289-.234-.481-.298-.54l-.288.28l.178.361z");
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qd0uvdb-t {
  d: path("M13.277 16.907v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.95 3.95 0 0 1-2.498.887h-1.896a4 4 0 0 1-.376-.017");
}

.qocu5my9d {
  d: path("m22.636 16.11l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_b3_hmve {
  d: path("M12.413 9.36a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rz-l4sb2t {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
}

.rzbfz4btw {
  stop-color: var(--svg-color--b3576b, #B3576B);
  stop-opacity: 0;
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.sbgwyibuw {
  stop-color: var(--svg-color--c97c69, #C97C69);
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.snoqkbcuc {
  stop-color: var(--svg-color--efc4bc, #EFC4BC);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t78ap5knf {
  d: path("M14.597 13.65c-.508 0-.984-.12-1.385-.328c-.137-.07-.285.084-.198.209c.335.507.918.845 1.583.845s1.248-.338 1.583-.845c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.tbz0q_48a {
  stop-color: var(--svg-color--dd365e, #DD365E);
  stop-opacity: 0;
}

.tc24b9b-k {
  fill: var(--svg-color--000, #000);
  d: path("M12.924 10.252a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.tc4y5tbfa {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
}

.tcape2laf {
  stop-color: var(--svg-color--edb63d, #EDB63D);
}

.tneymrbip {
  d: path("m20.012 16.705l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.764-2.98 3.034c-.084.02-.348.046-.505-.158l-.142-.14a3.5 3.5 0 0 0-1.745-1.11l-4.243-1.203a.61.61 0 0 1-.43-.78l1.25-4.674c.045-.22.37-.43.622-.364");
}

.tzrhvuzsh {
  stop-color: var(--svg-color--e8aa95, #E8AA95);
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.ufuwm4b_g {
  stop-color: var(--svg-color--ffceb9, #FFCEB9);
}

.uqd0hrbrc {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.33 8.015a1.85 1.85 0 0 0-.688-.412c-.304-.095-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.027.979.036c.198.063.332.164.49.301a.277.277 0 0 0 .364-.418");
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vhb-9rbjm {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.988 9.088c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vytbrlpyt {
  d: path("M21.577 26.145H7.607v3.8h13.97z");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wnvueqbtf {
  stop-color: var(--svg-color--efc4bc, #EFC4BC);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.x2ucuew1i {
  d: path("M19.519 12.094q.101-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xaw01bbos {
  d: path("M22.174 7.945H7.152c-.395.32-.779 1.337-1.163 1.657v1.343c0 4.69 3.854 8.5 8.598 8.5s8.599-3.81 8.599-8.5V9.602c-.355-.42-.688-1.207-1.012-1.657");
}

.xd_f5751e {
  fill: var(--svg-color--000, #000);
  d: path("M16.27 10.253c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xn32oub6d {
  fill-rule: evenodd;
  d: path("M11.157 16.04v1.585c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xshacufje {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m14.215 10.039l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y3u79wbum {
  d: path("M17.247 6.945h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.yf5fg-b3d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.716 9.549c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z7587oiyb {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.602c0-.2 1.146-4.105 1.719-6.032");
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.zu_qc9wey {
  d: path("M13.304 4.882c0-.153.183-.23.293-.125l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.179-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195V5.05a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

</style>
