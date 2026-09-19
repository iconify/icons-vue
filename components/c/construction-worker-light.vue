<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3DKvhc)" class="p-c6k8biy"/><path fill="url(#iKEcTfe)" class="p-c6k8biy"/><path fill="url(#i28OjCe)" class="qg_j7ubdy"/><path fill="url(#iPqmFFJ)" class="qg_j7ubdy"/><path fill="url(#i3kJV0d)" class="qg_j7ubdy"/><path fill="url(#imXXexe)" class="e4bdsyboh"/><path fill="url(#iEnSMRb)" class="e4bdsyboh"/><path fill="url(#iTFP0od)" class="pkk1wtbcw"/><path fill="url(#i0QFqKc)" class="pkk1wtbcw"/><path fill="url(#icxozNb)" class="pkk1wtbcw"/><path fill="url(#ikPHJTb)" class="r34_y1hcr"/><path fill="url(#ihBjoEc)" class="r34_y1hcr"/><path class="cwhvcxb2p"/><path fill="url(#iJiYnAD)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="zu703rbwl"/><path fill="url(#iwPt3uy)" class="zu703rbwl"/><path fill="url(#icpxGTb)" class="qq72wjb7t"/><path fill="url(#imgUjVb)" class="qq72wjb7t"/><path fill="url(#iIiLQQc)" class="ix2bq6sxv"/><path fill="url(#ii4eH6l)" class="ix2bq6sxv"/><path fill="url(#ivtVORd)" class="vxp0ejbky"/><path fill="url(#iK209Lc)" class="vxp0ejbky"/><path fill="url(#i1IZimd)" class="vxp0ejbky"/><path class="k-d_97bla"/><path class="t7mno3bqq"/><path fill="url(#i4t7mtb)" class="ngpr6qxue"/><path fill="url(#i4f8rbc)" class="gfo7xthak"/><g filter="url(#iqFVQ9w)"><path fill="url(#i28J4Wb)" class="jsueeceab"/></g><path fill="url(#iYur57c)" class="jsueeceab"/><path fill="url(#iBByQfU)" class="jsueeceab"/><path fill="url(#imqN31b)" class="jsueeceab"/><path fill="url(#iZmwOxC)" class="jsueeceab"/><path fill="url(#irrR6lc)" class="jsueeceab"/><path fill="url(#icMSN9c)" class="jsueeceab"/><path fill="url(#iqLBEwd)" class="jsueeceab"/><path fill="url(#iuZIKLe)" class="jsueeceab"/><g filter="url(#iKhb1ic)"><path class="w_11hlubg"/></g><g filter="url(#ibQ51LL)"><path class="qgv3m3b0u"/><path fill="url(#iTdY5Qc)" class="uj9af6b5p"/><path fill="url(#ibRzVke)" class="uj9af6b5p"/><path fill="url(#icCL4Lq)" class="uj9af6b5p"/></g><g filter="url(#iqfzRXa)"><path fill="url(#i34dfxR)" class="fbr2f6bbv"/></g><g filter="url(#iPMJd6b)"><path stroke="url(#ihBQeuc)" class="idolc974m"/></g><path fill="url(#i8PvSJb)" class="e2785zt1k"/><path class="da_us2b5a"/><path fill="url(#iexSgmc)" class="nz_iulboq"/><path class="shoas_jeh"/><g filter="url(#iPvfqRH)"><path class="ycj0s3b5r"/><path fill="url(#iO7t4Db)" class="bejh_ft2x"/></g><g filter="url(#ilErFYc)"><path fill="url(#iKpf9mT)" class="j8q6dfbgw"/></g><path class="pr6ywobyj"/><path fill="url(#izapaAd)" class="y3afv5bsc"/><path class="v992pynbw"/><g filter="url(#i6KpU6d)"><path fill="url(#iw4LhOb)" class="ryz3201py"/></g><g filter="url(#iqGS7Ac)"><ellipse transform="rotate(-27.914 13.377 13.098)" class="v_74hdcqi"/><ellipse fill="url(#iYe2YOb)" transform="rotate(-27.914 13.377 13.098)" class="aiaghgbkj"/></g><path fill="url(#iqgkWoc)" class="vg-prpble"/><path fill="url(#iwC8vZb)" class="vg-prpble"/><path fill="url(#iZqKKMb)" class="vg-prpble"/><path fill="url(#iUO3oob)" class="vg-prpble"/><path fill="url(#iLArhOb)" class="b9o4f8wwy"/><path fill="url(#iH7RrFF)" class="b9o4f8wwy"/><g filter="url(#iUU8Tfd)"><path fill="url(#i8AZXYd)" class="wl-h782-o"/></g><g filter="url(#iCBFH3d)"><path fill="url(#iK4QV2c)" class="kxmvcvb6m"/></g><path fill="url(#it84Uce)" class="qg-cgobis"/><path fill="url(#iAvECrc)" class="qg-cgobis"/><path fill="url(#iPHUYFd)" class="qg-cgobis"/><path fill="url(#iXMTIBb)" class="qg-cgobis"/><path fill="url(#iajAx2b)" class="qg-cgobis"/><path fill="url(#iXqASBd)" class="qg-cgobis"/><path fill="url(#iMLgQTb)" class="qg-cgobis"/><path fill="url(#i3tCWcc)" class="qg-cgobis"/><g filter="url(#iEabric)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="ppcwficln"/><path fill="url(#ihRfG7d)" class="ppcwficln"/><path fill="url(#iQi1jdd)" class="ppcwficln"/><path fill="url(#iRrXLNd)" class="ppcwficln"/><defs><radialGradient id="i3DKvhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.625 6.57257 0 16.01 29.734)" gradientUnits="userSpaceOnUse"><stop class="rj0sd-b5f"/><stop offset="1" class="yrhyj2blb"/></radialGradient><radialGradient id="iKEcTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -12.5036 18.677 26.172)" gradientUnits="userSpaceOnUse"><stop class="rredkdkgz"/><stop offset="1" class="ci5tu_5bf"/></radialGradient><radialGradient id="i28OjCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.72 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="iPqmFFJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.72 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="imXXexe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.043 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="iEnSMRb" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.28 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="i0QFqKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.885)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="icxozNb" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.34 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="ikPHJTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.66 22.544)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ihBjoEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.66 27.938)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="iJiYnAD" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.121)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="icpxGTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.89)" gradientUnits="userSpaceOnUse"><stop class="hkp0jqbkb"/><stop offset="1" class="fnpqbob3w"/></radialGradient><radialGradient id="iIiLQQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.93)" gradientUnits="userSpaceOnUse"><stop class="eluvk9b8d"/><stop offset="1" class="oymutzb3n"/></radialGradient><radialGradient id="ii4eH6l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="hsoncjbem"/><stop offset="1" class="gh3m30bhl"/></radialGradient><radialGradient id="ivtVORd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -4.86609 0 16.021 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="j6c345v2b"/><stop offset=".88" class="ofgai0yng"/></radialGradient><radialGradient id="iK209Lc" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.823 15.174)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="apucomv8k"/><stop offset="1" class="u3la45b8i"/></radialGradient><radialGradient id="i1IZimd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.61608 1.94033 -2.53687 -3.42038 16.693 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="d48qdibqs"/><stop offset="1" class="ea0g_ebwb"/></radialGradient><radialGradient id="i4t7mtb" cx="0" cy="0" r="1" gradientTransform="matrix(.80702 2.17664 -2.58568 .95868 21.145 15.203)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i4f8rbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59132 .50012 -1.54291 4.90932 9.493 15.731)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="i28J4Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.09375 0 0 -6.58694 18.968 14.485)" gradientUnits="userSpaceOnUse"><stop class="zf7wh6lvd"/><stop offset="1" class="a8x0gfb3l"/></radialGradient><radialGradient id="iBByQfU" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0386 -14.2137 0 16.65 7.538)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="www4dfogh"/><stop offset=".98" class="c0317ln8x"/></radialGradient><radialGradient id="imqN31b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.23768 1.53163 0 18.659 12.774)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iZmwOxC" cx="0" cy="0" r="1" gradientTransform="matrix(.00424 -1.1794 1.28347 .00461 13.542 12.824)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="irrR6lc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.1569 .57803 -1.47657 -23.39124 19.721 15.253)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="icMSN9c" cx="0" cy="0" r="1" gradientTransform="rotate(-46.611 16.122 -6.993)scale(4.86129 1.77957)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iqLBEwd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.831 9.666)scale(3.63106 2.99773)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="ibRzVke" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2631 -.82686 0 16.524 15.655)" gradientUnits="userSpaceOnUse"><stop class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i8PvSJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.7768 3.12528 0 16.021 18.003)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iexSgmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87443 -1.39088 0 18.373 13.201)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iO7t4Db" cx="0" cy="0" r="1" gradientTransform="matrix(-.24996 -.32211 .44346 -.34412 18.128 13.292)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izapaAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87448 -1.39095 0 13.67 13.201)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iYe2YOb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.295 .142)scale(.53258 .64019)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwC8vZb" cx="0" cy="0" r="1" gradientTransform="matrix(.67745 2.41779 -2.30675 .64634 20.998 13.216)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iZqKKMb" cx="0" cy="0" r="1" gradientTransform="matrix(.84907 -1.1652 .97667 .71168 21.387 13.803)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iUO3oob" cx="0" cy="0" r="1" gradientTransform="matrix(.63266 -1.67103 2.23273 .84532 21.51 13.99)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iH7RrFF" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.785 6.628)scale(1.75158 1.88025)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="i8AZXYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.98777 .16955 -.20805 -1.21205 10.724 13.91)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="it84Uce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.584 6.797)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iTFP0od" x1="9.158" x2="9.158" y1="21.199" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="imgUjVb" x1="8.468" x2="7.09" y1="29.929" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nhznusr0x"/><stop offset="1" class="zdrlg3bmy"/></linearGradient><linearGradient id="iYur57c" x1="21.58" x2="16.888" y1="16.005" y2="16.005" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iuZIKLe" x1="16.072" x2="16.072" y1="11.918" y2="13.996" gradientUnits="userSpaceOnUse"><stop offset=".253" class="e_-tfdbel"/><stop offset="1" class="a3g5ykeef"/></linearGradient><linearGradient id="iTdY5Qc" x1="16.901" x2="16.021" y1="14.842" y2="14.954" gradientUnits="userSpaceOnUse"><stop class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></linearGradient><linearGradient id="icCL4Lq" x1="16.021" x2="16.021" y1="16.144" y2="15.643" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i34dfxR" x1="16.104" x2="16.342" y1="12.695" y2="14.796" gradientUnits="userSpaceOnUse"><stop class="bu2mwxcxl"/><stop offset="1" class="a93f4subu"/></linearGradient><linearGradient id="ihBQeuc" x1="14.726" x2="15.069" y1="17.837" y2="16.938" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="iKpf9mT" x1="19.212" x2="18.873" y1="13.259" y2="13.467" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iw4LhOb" x1="14.471" x2="14.133" y1="13.259" y2="13.467" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqgkWoc" x1="22.958" x2="21.657" y1="13.288" y2="15.634" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iLArhOb" x1="9.716" x2="11.288" y1="14.047" y2="13.91" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iK4QV2c" x1="21.926" x2="21.926" y1="12.888" y2="14.94" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="ihRfG7d" x1="15.587" x2="15.587" y1="9.842" y2="10.155" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iQi1jdd" x1="16.505" x2="16.505" y1="12.148" y2="10.895" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="iqFVQ9w" width="12.015" height="13.502" x="10.564" y="7.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2960"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2960" result="effect2_innerShadow_4002_2960"/></filter><filter id="iKhb1ic" width="3.883" height="5.126" x="13.927" y="12.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".5"/></filter><filter id="ibQ51LL" width="2.423" height="3.526" x="14.809" y="12.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".1"/></filter><filter id="iqfzRXa" width="2.423" height="3.526" x="14.892" y="12.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".1"/></filter><filter id="iPMJd6b" width="3.969" height="1.656" x="14.037" y="16.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".05"/></filter><filter id="iPvfqRH" width=".832" height=".735" x="17.59" y="12.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".05"/></filter><filter id="ilErFYc" width=".929" height=".953" x="18.503" y="12.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".1"/></filter><filter id="i6KpU6d" width="1.032" height="1.09" x="13.714" y="12.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".1"/></filter><filter id="iqGS7Ac" width=".969" height=".744" x="12.893" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".05"/></filter><filter id="iUU8Tfd" width="1.393" height="2.526" x="9.487" y="12.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".125"/></filter><filter id="iCBFH3d" width="2.02" height="3.051" x="20.916" y="12.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2960" stdDeviation=".25"/></filter><filter id="iEabric" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2960"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2960" result="effect2_innerShadow_4002_2960"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction-worker-light" /></template>
<style>
.a3g5ykeef {
  stop-color: var(--svg-color--e59b89, #E59B89);
  stop-opacity: 0;
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.a8x0gfb3l {
  stop-color: var(--svg-color--dfa899, #DFA899);
}

.a93f4subu {
  stop-color: var(--svg-color--e59d8a, #E59D8A);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aiaghgbkj {
  cx: 13.377px;
  cy: 13.098px;
  rx: 0.42px;
  ry: 0.213px;
}

.apucomv8k {
  stop-color: var(--svg-color--f3a69a, #F3A69A);
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b9o4f8wwy {
  d: path("M10.584 12.185c-.842.118-1.5.842-1.5 1.717c0 .926.726 1.683 1.64 1.732a84 84 0 0 1-.14-3.45");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bejh_ft2x {
  d: path("M18.305 12.89c.068.092-.075.204-.238.326c-.163.121-.284.207-.352.116c-.069-.092.008-.265.17-.387c.163-.122.35-.146.42-.055");
}

.bu2mwxcxl {
  stop-color: var(--svg-color--e59d8a, #E59D8A);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.ci5tu_5bf {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.d48qdibqs {
  stop-color: var(--svg-color--d98e90, #D98E90);
  stop-opacity: 0;
}

.da_us2b5a {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.598 12.394c.704 0 1.299.485 1.46 1.141a.295.295 0 0 1-.288.367h-2.405a.248.248 0 0 1-.245-.292a1.51 1.51 0 0 1 1.478-1.216");
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.e_-tfdbel {
  stop-color: var(--svg-color--e59b89, #E59B89);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2785zt1k {
  d: path("M16.021 17.31a3.24 3.24 0 0 1-1.493-.353c-.148-.076-.306.09-.213.225c.36.547.99.912 1.706.912a2.04 2.04 0 0 0 1.707-.912c.093-.14-.066-.3-.214-.225c-.432.225-.94.354-1.493.354");
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e4bdsyboh {
  d: path("M18.28 19.198c.607.134 1.195.31 1.762.537V29.93H18.28z");
}

.ea0g_ebwb {
  stop-color: var(--svg-color--d98e90, #D98E90);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eluvk9b8d {
  stop-color: var(--svg-color--ff9c5e, #FF9C5E);
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f-z5vk62h {
  d: path("M14.615 2.07h2.39c.829 0 1.5.603 1.5 1.633v6.795h-5.39V3.703c0-1.03.671-1.633 1.5-1.633");
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.fbr2f6bbv {
  d: path("m15.692 13.419l-.573 1.98c-.117.409.164.816.561.816h.848c.397 0 .678-.414.56-.815l-.572-1.982c-.123-.438-.696-.438-.824 0");
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fnpqbob3w {
  stop-color: var(--svg-color--ce763c, #CE763C);
}

.ft5dv1b6b {
  fill: none;
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gfo7xthak {
  d: path("M10.782 15.536a1.77 1.77 0 0 1-.975-.333v1.004c0 .962.573 1.82 1.445 2.176a4.4 4.4 0 0 1-.373-1.272z");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gh3m30bhl {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
  stop-opacity: 0;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hkp0jqbkb {
  stop-color: var(--svg-color--f37d42, #F37D42);
}

.hsoncjbem {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.idolc974m {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.563 16.89h-.001a.24.24 0 0 0-.285.05a.22.22 0 0 0-.025.284a2.12 2.12 0 0 0 1.77.945c.742 0 1.394-.378 1.768-.946a.225.225 0 0 0-.025-.286a.24.24 0 0 0-.285-.047c-.421.22-.918.346-1.459.346a3.16 3.16 0 0 1-1.458-.346Z");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ix2bq6sxv {
  d: path("M27.399 29.93c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.804z");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j6c345v2b {
  stop-color: var(--svg-color--db898d, #DB898D);
}

.j8q6dfbgw {
  d: path("M19.232 13.522a.9.9 0 0 0-.25-.499l-.28.308l.127.246z");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jsueeceab {
  d: path("M10.821 17.169a4.22 4.22 0 0 0 4.188 3.67h2.033a4.22 4.22 0 0 0 4.188-3.67c.128-2.03.255-4.053.35-6.082a1.56 1.56 0 0 0-1.487-1.543h-1.509a2.61 2.61 0 0 1-2.383-1.556a.72.72 0 0 0-.664-.45h-1.372c-1.989 0-3.6 1.63-3.6 3.642c0 2.005.125 3.978.256 5.989");
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k-d_97bla {
  fill: var(--svg-color--2f2728, #2F2728);
  d: path("M9.677 11.621h.953v1.082h-.953z");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kxmvcvb6m {
  d: path("M21.416 14.94q.063-1.026.12-2.052a1.03 1.03 0 0 1-.12 2.052");
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.ngpr6qxue {
  d: path("M21.26 15.536c.362-.012.7-.134.976-.333v1.004c0 .962-.574 1.82-1.446 2.176q.277-.588.373-1.272z");
}

.nhznusr0x {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nz_iulboq {
  d: path("M18.375 12.687a.962.962 0 0 1 .927 1.216h-1.858a.966.966 0 0 1 .931-1.216");
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
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

.ofgai0yng {
  stop-color: var(--svg-color--e19a9b, #E19A9B);
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.oymutzb3n {
  stop-color: var(--svg-color--ff9457, #FF9457);
}

.p-c6k8biy {
  d: path("M16.02 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkk1wtbcw {
  d: path("M8.389 22.018a.15.15 0 0 0-.048.109v7.803h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.ppcwficln {
  d: path("M22.266 9.842H9.673a1.153 1.153 0 1 0 0 2.306h12.593c.642 0 1.153-.52 1.153-1.153a1.147 1.147 0 0 0-1.153-1.153");
}

.pr6ywobyj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.444 12.394c-.704 0-1.299.485-1.46 1.141a.296.296 0 0 0 .288.367h2.405c.153 0 .276-.14.245-.292a1.51 1.51 0 0 0-1.478-1.216");
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qg_j7ubdy {
  d: path("M13.72 19.198c-.607.134-1.195.31-1.763.537V29.93h1.764z");
}

.qg-cgobis {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.987a4.1 4.1 0 0 1 4.1 4.1V9.86H9.772z");
}

.qgv3m3b0u {
  fill: var(--svg-color--dfa598, #DFA598);
  d: path("m15.61 13.419l-.574 1.98c-.117.409.164.816.561.816h.848c.397 0 .678-.414.561-.815l-.573-1.982c-.122-.438-.695-.438-.824 0");
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qq72wjb7t {
  d: path("M4.601 29.93c.14-.947.34-1.882.62-2.787a11.56 11.56 0 0 1 3.12-5.018v7.804z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r34_y1hcr {
  d: path("M23.66 22.062v7.868h-1.635v-9.16c.578.382 1.126.816 1.634 1.292");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rj0sd-b5f {
  stop-color: var(--svg-color--ff804b, #FF804B);
}

.rredkdkgz {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.ryz3201py {
  d: path("M14.546 13.536c0-.311-.253-.518-.321-.58l-.31.3l.19.39z");
}

.shoas_jeh {
  fill: var(--svg-color--000, #000);
  d: path("M17.824 13.649c0-.306.245-.55.551-.55a.55.55 0 0 1 .49.804h-.975a.5.5 0 0 1-.066-.254");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t7mno3bqq {
  fill: var(--svg-color--2a282b, #2A282B);
  d: path("M21.33 11.621h.836v1.082h-.836z");
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u3la45b8i {
  stop-color: var(--svg-color--f3a69a, #F3A69A);
  stop-opacity: 0;
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.uj9af6b5p {
  d: path("m15.61 13.419l-.574 1.98c-.117.409.164.816.561.816h.848c.397 0 .678-.414.561-.815l-.573-1.982c-.122-.438-.695-.438-.824 0");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v_74hdcqi {
  cx: 13.377px;
  cy: 13.098px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.42px;
  ry: 0.213px;
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v992pynbw {
  fill: var(--svg-color--000, #000);
  d: path("M14.218 13.65a.55.55 0 0 0-.55-.552a.55.55 0 0 0-.49.805h.974a.55.55 0 0 0 .066-.254");
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vg-prpble {
  d: path("M21.326 15.634c.07-1.147.14-2.293.199-3.44a1.735 1.735 0 0 1-.2 3.44");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vxp0ejbky {
  d: path("M13.81 20.406c.06.76.585 2.282 2.211 2.282s2.151-1.521 2.21-2.282z");
}

.w_11hlubg {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.589 13.624l-.637 1.981c-.109.408.152.816.522.816h.789c.37 0 .63-.414.522-.816l-.533-1.98c-.114-.44-.544-.44-.663 0");
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wl-h782-o {
  d: path("M10.54 12.897a1.03 1.03 0 0 0 .09 2.025a84 84 0 0 1-.09-2.025");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y3afv5bsc {
  d: path("M13.667 12.687a.962.962 0 0 0-.927 1.216h1.86a1 1 0 0 0 .034-.254a.97.97 0 0 0-.966-.962");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ycj0s3b5r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.305 12.89c.068.092-.075.204-.238.326c-.163.121-.284.207-.352.116c-.069-.092.008-.265.17-.387c.163-.122.35-.146.42-.055");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yrhyj2blb {
  stop-color: var(--svg-color--ff8b3c, #FF8B3C);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zdrlg3bmy {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
  stop-opacity: 0;
}

.zf7wh6lvd {
  stop-color: var(--svg-color--ffd6b8, #FFD6B8);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zu703rbwl {
  d: path("M22.025 20.77v9.16h-1.982V19.735c.697.28 1.354.62 1.982 1.034");
}

</style>
