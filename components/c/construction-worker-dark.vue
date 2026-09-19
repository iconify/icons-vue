<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iE9FFab)" class="i-dm14m_a"/><path fill="url(#iI1mSLC)" class="osull4brl"/><path fill="url(#iyf9wGc)" class="rihmkq8le"/><path fill="url(#iKEcTfe)" class="rihmkq8le"/><path fill="url(#iRNOrCe)" class="f3ael5nnj"/><path fill="url(#izlspBK)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iFGqZ7b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iH7QLPe)" class="a1zqpmsoh"/><path fill="url(#ipVLI1y)" class="a1zqpmsoh"/><path fill="url(#i1aP5Bc)" class="a1zqpmsoh"/><path fill="url(#iYuYzlb)" class="u4akr2zeg"/><path fill="url(#ibXHnbd)" class="u4akr2zeg"/><path class="cwhvcxb2p"/><path fill="url(#in3x4bd)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="bkw3kzb2o"/><path fill="url(#iwPt3uy)" class="bkw3kzb2o"/><path fill="url(#icpxGTb)" class="qq72wjb7t"/><path fill="url(#imgUjVb)" class="qq72wjb7t"/><path fill="url(#iIiLQQc)" class="ix2bq6sxv"/><path fill="url(#ii4eH6l)" class="ix2bq6sxv"/><path fill="url(#icA71qb)" class="i-ycf-bxl"/><path fill="url(#i7qs3Jb)" class="i-ycf-bxl"/><path fill="url(#ikTHrNE)" class="i-ycf-bxl"/><g filter="url(#ibcsXJc)"><ellipse class="bhyojfbed"/></g><g filter="url(#ioIgOpb)"><ellipse class="nt-_wr80m"/></g><path fill="url(#ih7IZNa)" class="kkry50b6m"/><path fill="url(#iK6raQb)" class="wzrsj2b8q"/><g filter="url(#i6B1KJd)"><path fill="url(#i2Dyocd)" class="t31-qxb4n"/></g><path fill="url(#iH2dVOx)" class="t31-qxb4n"/><path fill="url(#iOYFOlb)" class="t31-qxb4n"/><path fill="url(#iJLPI6c)" class="t31-qxb4n"/><path fill="url(#iCcjfTc)" class="t31-qxb4n"/><path fill="url(#i6zrwbc)" class="t31-qxb4n"/><path fill="url(#iGjkATb)" class="t31-qxb4n"/><path fill="url(#ikfauMd)" class="t31-qxb4n"/><path fill="url(#iZOjTqc)" class="t31-qxb4n"/><path fill="url(#iCqGNOd)" class="t31-qxb4n"/><path fill="url(#inWIGKb)" class="t31-qxb4n"/><g filter="url(#il4DZ8b)"><path class="v66z6_bsl"/></g><g filter="url(#iwvxR3b)"><path class="leo4bq8nb"/><path fill="url(#ij9OdYd)" class="h00r2lgmp"/><path fill="url(#i2vdAHc)" class="h00r2lgmp"/><path fill="url(#iFWtMNe)" class="h00r2lgmp"/><path fill="url(#ir4tNxc)" class="h00r2lgmp"/><path fill="url(#iTqP9Ec)" class="h00r2lgmp"/></g><g filter="url(#iTuI4Yc)"><path stroke="url(#i0x7SPc)" class="ez7omxbsy"/></g><path fill="url(#i7eWOKb)" class="ytxmz6b3n"/><path class="cvsoxlb2u"/><path fill="url(#ikXQqIe)" class="cutdmmbic"/><path class="sy_t_w8tl"/><g filter="url(#iIy5xub)"><path class="fusk52boe"/><path fill="url(#iEmjGtb)" class="uxudkbbsa"/></g><g filter="url(#izGQb3d)"><path fill="url(#ikIM15c)" class="byv605qup"/></g><path class="xaeuz0i0v"/><path fill="url(#iN9ZSUc)" class="occfzzbbh"/><path class="gfwd1rskj"/><g filter="url(#i7nNLKb)"><path fill="url(#ihjx6De)" class="m8mk3pbae"/></g><g filter="url(#iUG9l3N)"><ellipse transform="rotate(-27.914 13.315 13.07)" class="nf04obcjm"/><ellipse fill="url(#iO4bnoe)" transform="rotate(-27.914 13.315 13.07)" class="u-8uslbqd"/></g><path fill="url(#ikjLgsd)" class="itbzcxrok"/><path fill="url(#ipWphSc)" class="itbzcxrok"/><path fill="url(#ix3D0tb)" class="itbzcxrok"/><path fill="url(#iRyoNid)" class="itbzcxrok"/><path fill="url(#i8CPM8b)" class="yehhcjbrc"/><path fill="url(#ipv7Ndu)" class="yehhcjbrc"/><g filter="url(#iC4kZXj)"><path fill="url(#iAFFvue)" class="y5nbp5-nf"/></g><g filter="url(#iSqb7ke)"><path fill="url(#iWuPy1D)" class="cgy6jzbzi"/></g><path fill="url(#it84Uce)" class="yacjacccz"/><path fill="url(#iAvECrc)" class="yacjacccz"/><path fill="url(#iPHUYFd)" class="yacjacccz"/><path fill="url(#iXMTIBb)" class="yacjacccz"/><path fill="url(#iajAx2b)" class="yacjacccz"/><path fill="url(#iXqASBd)" class="yacjacccz"/><path fill="url(#iMLgQTb)" class="yacjacccz"/><path fill="url(#i3tCWcc)" class="yacjacccz"/><g filter="url(#ilynBee)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="iv9aw-bqp"/><path fill="url(#ihRfG7d)" class="iv9aw-bqp"/><path fill="url(#iQi1jdd)" class="iv9aw-bqp"/><path fill="url(#iRrXLNd)" class="iv9aw-bqp"/><defs><radialGradient id="iyf9wGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.625 6.57257 0 16.011 29.734)" gradientUnits="userSpaceOnUse"><stop class="rj0sd-b5f"/><stop offset="1" class="yrhyj2blb"/></radialGradient><radialGradient id="iKEcTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -12.5036 18.677 26.172)" gradientUnits="userSpaceOnUse"><stop class="rredkdkgz"/><stop offset="1" class="ci5tu_5bf"/></radialGradient><radialGradient id="iRNOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="izlspBK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iFGqZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="ipVLI1y" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.884)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="iYuYzlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.543)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ibXHnbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.937)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="in3x4bd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.12)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="icpxGTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.89)" gradientUnits="userSpaceOnUse"><stop class="hkp0jqbkb"/><stop offset="1" class="fnpqbob3w"/></radialGradient><radialGradient id="iIiLQQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.93)" gradientUnits="userSpaceOnUse"><stop class="eluvk9b8d"/><stop offset="1" class="oymutzb3n"/></radialGradient><radialGradient id="ii4eH6l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="hsoncjbem"/><stop offset="1" class="gh3m30bhl"/></radialGradient><radialGradient id="icA71qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.968 0 16.021 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="blqobpb3p"/><stop offset=".88" class="pxzodtb2t"/></radialGradient><radialGradient id="i7qs3Jb" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.823 15.175)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="y_e22dbsz"/><stop offset="1" class="kr6jsomty"/></radialGradient><radialGradient id="ikTHrNE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64062 1.4375 -2.5012 -4.5946 16.693 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="c8dzu-gul"/><stop offset="1" class="zwzf7pbvi"/></radialGradient><radialGradient id="ih7IZNa" cx="0" cy="0" r="1" gradientTransform="matrix(.81 2.18465 -2.5952 .96221 21.111 15.182)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iK6raQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.59718 .50197 -1.54861 4.9274 9.418 15.713)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="i2Dyocd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65527 0 0 -10.0041 19.007 14.164)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iOYFOlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10585 13.43928 -11.12929 -.91578 17.68 7.767)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iJLPI6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24224 1.53727 0 18.616 12.744)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iCcjfTc" cx="0" cy="0" r="1" gradientTransform="matrix(.00425 -1.18374 1.2882 .00463 13.481 12.794)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i6zrwbc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.601 7.927)scale(9.2089 23.5241)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iGjkATb" cx="0" cy="0" r="1" gradientTransform="matrix(4.406 -2.86481 1.04872 1.6129 10.055 9.485)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="ikfauMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25384 2.70162 -1.07995 -.10147 21.967 11.008)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iZOjTqc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.822 9.632)scale(3.64443 3.00877)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="inWIGKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.34325 -3.86516 0 16.02 11.82)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="wdeqzz96y"/><stop offset="1" class="oh42-dbwb"/></radialGradient><radialGradient id="i2vdAHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .26406 -.8299 0 16.474 15.636)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="ir4tNxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6455 .75445 -1.21247 -2.64448 16.6 15.02)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i7eWOKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77966 3.13678 0 15.97 17.993)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="ikXQqIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87765 -1.396 0 18.33 13.173)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iEmjGtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25088 -.3233 .4451 -.3454 18.083 13.265)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iN9ZSUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8777 -1.39608 0 13.609 13.173)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iO4bnoe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.25 .159)scale(.53455 .64254)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipWphSc" cx="0" cy="0" r="1" gradientTransform="matrix(.67994 2.42668 -2.31524 .64872 20.965 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ix3D0tb" cx="0" cy="0" r="1" gradientTransform="matrix(.8522 -1.1695 .98027 .7143 21.354 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iRyoNid" cx="0" cy="0" r="1" gradientTransform="matrix(.635 -1.67718 2.24094 .84844 21.478 13.964)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="ipv7Ndu" cx="0" cy="0" r="1" gradientTransform="matrix(-.44663 2.24576 -2.20778 -.43908 10.276 13.37)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iAFFvue" cx="0" cy="0" r="1" gradientTransform="matrix(-.99141 .17018 -.07506 -.43727 10.653 13.884)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="it84Uce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.584 6.797)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iE9FFab" x1="10.558" x2="9.521" y1="12.164" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="ymyjruwrb"/><stop offset="1" class="osvrbmbgh"/></linearGradient><linearGradient id="iI1mSLC" x1="21.396" x2="22.084" y1="12.203" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="mnu548xdh"/><stop offset="1" class="igfnq7b1m"/></linearGradient><linearGradient id="iH7QLPe" x1="9.158" x2="9.158" y1="21.199" y2="29.929" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="imgUjVb" x1="8.468" x2="7.09" y1="29.929" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nhznusr0x"/><stop offset="1" class="zdrlg3bmy"/></linearGradient><linearGradient id="iH2dVOx" x1="21.548" x2="16.84" y1="15.987" y2="15.987" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iCqGNOd" x1="16.02" x2="16.02" y1="20.927" y2="20.235" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="ij9OdYd" x1="16.876" x2="15.969" y1="14.894" y2="14.932" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iFWtMNe" x1="15.969" x2="15.969" y1="16.126" y2="15.623" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iTqP9Ec" x1="15.969" x2="15.969" y1="12.93" y2="13.791" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="i0x7SPc" x1="14.669" x2="15.014" y1="17.826" y2="16.923" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="ikIM15c" x1="19.171" x2="18.832" y1="13.231" y2="13.44" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihjx6De" x1="14.414" x2="14.074" y1="13.231" y2="13.441" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikjLgsd" x1="22.932" x2="21.626" y1="13.26" y2="15.614" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i8CPM8b" x1="9.641" x2="11.219" y1="14.022" y2="13.884" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iWuPy1D" x1="21.828" x2="21.828" y1="12.847" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="ihRfG7d" x1="15.587" x2="15.587" y1="9.842" y2="10.155" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iQi1jdd" x1="16.505" x2="16.505" y1="12.148" y2="10.895" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="ibcsXJc" width="8.369" height="2.215" x="15.115" y="9.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".375"/></filter><filter id="ioIgOpb" width="7.654" height="2.528" x="15.502" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".5"/></filter><filter id="i6B1KJd" width="12.056" height="13.551" x="10.492" y="7.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2948"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2948" result="effect2_innerShadow_4002_2948"/></filter><filter id="il4DZ8b" width="3.89" height="5.137" x="13.871" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".5"/></filter><filter id="iwvxR3b" width="2.431" height="3.537" x="14.754" y="12.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".1"/></filter><filter id="iTuI4Yc" width="3.982" height="1.661" x="13.979" y="16.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".05"/></filter><filter id="iIy5xub" width=".835" height=".737" x="17.544" y="12.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".05"/></filter><filter id="izGQb3d" width=".931" height=".955" x="18.461" y="12.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".1"/></filter><filter id="i7nNLKb" width="1.034" height="1.093" x="13.654" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".1"/></filter><filter id="iUG9l3N" width=".971" height=".746" x="12.83" y="12.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".05"/></filter><filter id="iC4kZXj" width="1.397" height="2.533" x="9.412" y="12.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".125"/></filter><filter id="iSqb7ke" width="2.024" height="3.059" x="20.816" y="12.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2948" stdDeviation=".25"/></filter><filter id="ilynBee" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2948"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2948" result="effect2_innerShadow_4002_2948"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction-worker-dark" /></template>
<style>
.a1zqpmsoh {
  d: path("M8.389 22.017a.15.15 0 0 0-.048.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bhyojfbed {
  cx: 19.299px;
  cy: 10.856px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 3.435px;
  ry: 0.358px;
}

.bkw3kzb2o {
  d: path("M22.025 20.77v9.16h-1.983V19.735c.698.28 1.355.62 1.983 1.034");
}

.blqobpb3p {
  stop-color: var(--svg-color--381a27, #381A27);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.byv605qup {
  d: path("M19.192 13.495a.9.9 0 0 0-.25-.5l-.281.308l.126.247z");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c8dzu-gul {
  stop-color: var(--svg-color--381b17, #381B17);
  stop-opacity: 0;
}

.cgy6jzbzi {
  d: path("M21.316 14.906q.063-1.029.12-2.059a1.034 1.034 0 0 1-.12 2.06");
}

.ci5tu_5bf {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cutdmmbic {
  d: path("M18.332 12.657a.966.966 0 0 1 .93 1.22h-1.865a.97.97 0 0 1 .935-1.22");
}

.cvsoxlb2u {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.556 12.363a1.51 1.51 0 0 1 1.465 1.145a.297.297 0 0 1-.29.369h-2.413a.25.25 0 0 1-.245-.294a1.51 1.51 0 0 1 1.483-1.22");
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.eluvk9b8d {
  stop-color: var(--svg-color--ff9c5e, #FF9C5E);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.ez7omxbsy {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.505 16.876c.423.22.927.346 1.464.346c.543 0 1.042-.126 1.464-.347h.001a.24.24 0 0 1 .286.047a.23.23 0 0 1 .025.288m-3.24-.335l3.177.293m-3.177-.293a.24.24 0 0 0-.286.05a.22.22 0 0 0-.025.285m.311-.335l-.248.293m3.488.042l-.063-.042m.063.042l-.063-.042m.063.042a2.12 2.12 0 0 1-1.776.948a2.13 2.13 0 0 1-1.775-.948m3.488-.042c-.362.55-.993.915-1.713.915c-.719 0-1.35-.366-1.712-.915m-.063.042l.063-.042m-.063.042l.063-.042");
}

.f-z5vk62h {
  d: path("M14.615 2.07h2.39c.829 0 1.5.603 1.5 1.633v6.795h-5.39V3.703c0-1.03.671-1.633 1.5-1.633");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f3ael5nnj {
  d: path("M13.721 19.198c-.608.134-1.196.31-1.763.537V29.93h1.763z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fnpqbob3w {
  stop-color: var(--svg-color--ce763c, #CE763C);
}

.ft5dv1b6b {
  fill: none;
}

.fusk52boe {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.26 12.861c.07.092-.074.204-.238.326s-.284.209-.353.117s.008-.266.171-.388c.164-.122.352-.147.42-.055");
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gfwd1rskj {
  fill: var(--svg-color--000, #000);
  d: path("M14.16 13.622a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.492.808h.979a.55.55 0 0 0 .066-.255");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
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

.h00r2lgmp {
  d: path("m15.556 13.39l-.575 1.99c-.117.409.164.818.563.818h.85c.4 0 .681-.416.564-.818l-.575-1.99c-.123-.44-.698-.44-.827 0");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
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

.i-dm14m_a {
  d: path("M9.605 11.855h.953v1.082h-.953z");
}

.i-ycf-bxl {
  d: path("M13.81 20.406c.06.76.585 2.282 2.211 2.282s2.151-1.521 2.211-2.282z");
}

.igfnq7b1m {
  stop-color: var(--svg-color--4f4c4d, #4F4C4D);
}

.itbzcxrok {
  d: path("M21.294 15.614c.07-1.15.14-2.3.2-3.452a1.741 1.741 0 0 1-.2 3.452");
}

.iv9aw-bqp {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.306h12.594c.642 0 1.153-.52 1.153-1.153a1.147 1.147 0 0 0-1.153-1.153");
}

.ix2bq6sxv {
  d: path("M27.399 29.93c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.804z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kkry50b6m {
  d: path("M21.228 15.516c.363-.012.702-.135.978-.334v1.007a2.35 2.35 0 0 1-1.45 2.184q.277-.59.374-1.276z");
}

.kr6jsomty {
  stop-color: var(--svg-color--472928, #472928);
  stop-opacity: 0;
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.leo4bq8nb {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.556 13.39l-.575 1.99c-.117.409.164.818.563.818h.85c.4 0 .681-.416.564-.818l-.575-1.99c-.123-.44-.698-.44-.827 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m8mk3pbae {
  d: path("M14.489 13.51c0-.313-.254-.52-.323-.584l-.312.302l.192.39z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mnu548xdh {
  stop-color: var(--svg-color--2d2425, #2D2425);
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

.nf04obcjm {
  cx: 13.315px;
  cy: 13.069px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.421px;
  ry: 0.213px;
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

.nt-_wr80m {
  cx: 19.329px;
  cy: 10.856px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.occfzzbbh {
  d: path("M13.607 12.657a.965.965 0 0 0-.93 1.22h1.864a1 1 0 0 0 .035-.255a.97.97 0 0 0-.97-.965");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh42-dbwb {
  stop-color: var(--svg-color--3d2427, #3D2427);
  stop-opacity: 0;
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.osull4brl {
  d: path("M21.33 11.855h.836v1.082h-.836z");
}

.osvrbmbgh {
  stop-color: var(--svg-color--4a4545, #4A4545);
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.oymutzb3n {
  stop-color: var(--svg-color--ff9457, #FF9457);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.pxzodtb2t {
  stop-color: var(--svg-color--44242e, #44242E);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
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

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.rj0sd-b5f {
  stop-color: var(--svg-color--ff804b, #FF804B);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rredkdkgz {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.sy_t_w8tl {
  fill: var(--svg-color--000, #000);
  d: path("M17.779 13.622a.55.55 0 0 1 .553-.553a.55.55 0 0 1 .491.808h-.978a.5.5 0 0 1-.066-.255");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t31-qxb4n {
  d: path("M10.75 17.155a4.236 4.236 0 0 0 4.203 3.685h2.041a4.236 4.236 0 0 0 4.204-3.685c.127-2.038.255-4.067.35-6.104a1.57 1.57 0 0 0-1.492-1.549h-1.514a2.62 2.62 0 0 1-2.393-1.56a.72.72 0 0 0-.665-.453h-1.377c-1.997 0-3.615 1.636-3.615 3.655c0 2.013.126 3.993.258 6.011");
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u-8uslbqd {
  cx: 13.315px;
  cy: 13.069px;
  rx: 0.421px;
  ry: 0.213px;
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u4akr2zeg {
  d: path("M23.659 22.061v7.868h-1.634v-9.16c.578.383 1.126.817 1.634 1.292");
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.uxudkbbsa {
  d: path("M18.26 12.861c.07.092-.074.204-.238.326s-.284.209-.353.117s.008-.266.171-.388c.164-.122.352-.147.42-.055");
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v66z6_bsl {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.535 13.603l-.639 1.989c-.11.409.153.818.524.818h.792c.37 0 .633-.416.524-.819l-.535-1.988c-.115-.44-.546-.44-.666 0");
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wdeqzz96y {
  stop-color: var(--svg-color--3d2427, #3D2427);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.wzrsj2b8q {
  d: path("M10.71 15.516a1.77 1.77 0 0 1-.978-.334v1.007a2.35 2.35 0 0 0 1.45 2.184a4.4 4.4 0 0 1-.373-1.276z");
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xaeuz0i0v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.383 12.363a1.51 1.51 0 0 0-1.466 1.145a.297.297 0 0 0 .29.369h2.413c.154 0 .277-.14.246-.294a1.516 1.516 0 0 0-1.483-1.22");
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
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

.y_e22dbsz {
  stop-color: var(--svg-color--472928, #472928);
}

.y5nbp5-nf {
  d: path("M10.468 12.868a1.034 1.034 0 0 0 .09 2.033a84 84 0 0 1-.09-2.033");
}

.yacjacccz {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.86H9.77z");
}

.yehhcjbrc {
  d: path("M10.502 12.153a1.741 1.741 0 0 0 .15 3.462a85 85 0 0 1-.15-3.462");
}

.ymyjruwrb {
  stop-color: var(--svg-color--3a2d2b, #3A2D2B);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yrhyj2blb {
  stop-color: var(--svg-color--ff8b3c, #FF8B3C);
}

.ytxmz6b3n {
  d: path("M15.97 17.297a3.25 3.25 0 0 1-1.5-.355c-.148-.075-.307.092-.213.226c.362.55.993.915 1.712.915c.72 0 1.35-.366 1.713-.915c.094-.14-.066-.301-.214-.226a3.2 3.2 0 0 1-1.499.355");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.zdrlg3bmy {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zwzf7pbvi {
  stop-color: var(--svg-color--381b17, #381B17);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
