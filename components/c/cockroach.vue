<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4aATsd)" class="sv02bu-li"/><path fill="url(#iJhiGxd)" class="sv02bu-li"/><path fill="url(#iS1hS9c)" class="f0l3w9bnw"/><path fill="url(#itMGiSc)" class="f0l3w9bnw"/><g filter="url(#iIbsRQd)"><path stroke="url(#iX3cAuj)" class="p510_1bcz"/></g><g filter="url(#iLK1LTb)"><path stroke="url(#i5UvENB)" class="q79k-p7ig"/></g><path class="h9rcw8xwx"/><path fill="url(#icxTJFc)" class="a0ccrof_a"/><path fill="url(#iblHeId)" class="a0ccrof_a"/><path fill="url(#iCpHhJc)" class="a0ccrof_a"/><path fill="url(#iIIDBWD)" class="a0ccrof_a"/><g filter="url(#iZ9IJ7c)" class="g6vo9yehj"><path stroke="url(#iZA2Jgc)" class="kr4ikd3sv"/><path stroke="url(#isZmuNx)" class="kr4ikd3sv"/></g><path class="w3fgaud-r"/><path fill="url(#ilmPZdc)" class="apsjgnqzd"/><path fill="url(#iCxvhpe)" class="apsjgnqzd"/><path fill="url(#ikssMoe)" class="apsjgnqzd"/><path fill="url(#i1FZfXc)" class="apsjgnqzd"/><path fill="url(#iGDHxbd)" class="apsjgnqzd"/><g filter="url(#iNUrWbe)"><path stroke="url(#i3igKqd)" class="hunqegb2m"/></g><g filter="url(#iwpSu0d)"><path fill="url(#iJOH6QD)" class="fao1accsc"/><path fill="url(#ipTXpJb)" class="fao1accsc"/><path fill="url(#i2zJf9d)" class="fao1accsc"/></g><g filter="url(#ipbwZAt)"><path class="p2l14hztc"/><path fill="url(#i2NTyid)" class="xu8jff5wh"/><path fill="url(#ia6xbib)" class="xu8jff5wh"/><path fill="url(#iBISsGt)" class="xu8jff5wh"/><path fill="url(#i8lwE5c)" class="xu8jff5wh"/></g><g filter="url(#imLH2mb)"><path stroke="url(#iqSVA4c)" class="n6h4v9jdv"/></g><path fill="url(#i20a0qd)" class="z_twmlb2a"/><path fill="url(#iaMI7qc)" class="z_twmlb2a"/><path fill="url(#ik3zjGd)" class="z_twmlb2a"/><path fill="url(#iDAAHZd)" class="z_twmlb2a"/><path class="t9b57-bxi"/><path fill="url(#iIf2pCd)" class="kboedpbum"/><path fill="url(#iYcRTac)" class="kboedpbum"/><path fill="url(#iLFkVMc)" class="kboedpbum"/><path fill="url(#isLua6d)" class="kboedpbum"/><g filter="url(#im7MmKd)"><path fill="url(#i7nzzTc)" class="d2_rfacbv"/><path fill="url(#izCeI2c)" class="d2_rfacbv"/></g><g filter="url(#iMQdRmN)"><path stroke="url(#ihGBIjd)" class="z65bblbry"/></g><g filter="url(#i6S3Und)"><path stroke="url(#i9PyBgb)" class="l3h-k10hb"/></g><path fill="url(#iRBF2Xs)" class="di8egubhl"/><path fill="url(#iY3tI3b)" class="di8egubhl"/><path fill="url(#iuu8UBb)" class="di8egubhl"/><path fill="url(#ii3vAop)" class="di8egubhl"/><path fill="url(#izf9abe)" class="di8egubhl"/><path fill="url(#i9JSM1d)" class="di8egubhl"/><g filter="url(#iLBI2Zb)"><path class="vbouujb0r"/></g><g filter="url(#iZnxoTb)"><path fill="url(#i51Dkwc)" class="e51sjw1ie"/><path fill="url(#iJTTAEc)" class="e51sjw1ie"/></g><path fill="url(#iFclZSc)" class="e51sjw1ie"/><path fill="url(#ijVxYoe)" class="e51sjw1ie"/><path fill="url(#i4T1ywc)" class="e51sjw1ie"/><path fill="url(#isziAIb)" class="e51sjw1ie"/><g filter="url(#iBymyGe)"><path class="zpt3dibpf"/></g><g filter="url(#iHJioKc)"><path class="rhwjd89vh"/></g><path class="wak17tm2o"/><path fill="url(#iOca1tc)" class="obn46v5st"/><path fill="url(#iLxJ7Jd)" class="obn46v5st"/><path fill="url(#iWyQi8b)" class="obn46v5st"/><path fill="url(#iRbscge)" class="obn46v5st"/><path fill="url(#ijHvBxe)" class="obn46v5st"/><path fill="url(#iLIPbUc)" class="obn46v5st"/><g filter="url(#iFJQbNc)"><path stroke="url(#ibtKI6b)" class="z9g1wdzst"/></g><path fill="url(#ie2RZmm)" class="v2c3h7bev"/><path fill="url(#iq4assq)" class="v2c3h7bev"/><path fill="url(#iN8AQ3d)" class="v2c3h7bev"/><path fill="url(#ifbocUE)" class="v2c3h7bev"/><path fill="url(#iQlS8dd)" class="v2c3h7bev"/><path fill="url(#izEDKRU)" class="v2c3h7bev"/><path fill="url(#iw7XkDe)" class="v2c3h7bev"/><path fill="url(#iQVugqc)" class="v2c3h7bev"/><g filter="url(#iswVzie)"><path fill="url(#iVgoIte)" class="qwa9k5bpy"/></g><g filter="url(#i7AvaLB)"><path fill="url(#iuf2Zgc)" class="sk819zb8t"/></g><g filter="url(#iwFnPRb)"><path stroke="url(#iwOBQOb)" class="jr1eewbzh"/></g><defs><radialGradient id="icxTJFc" cx="0" cy="0" r="1" gradientTransform="matrix(1.04687 .32813 -1.49918 4.78302 22.47 24.986)" gradientUnits="userSpaceOnUse"><stop class="i6y975b1b"/><stop offset=".839" class="ms3r5q4gx"/></radialGradient><radialGradient id="iCpHhJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60938 2.67188 0 21.345 21.626)" gradientUnits="userSpaceOnUse"><stop class="rormvuhzh"/><stop offset="1" class="skjs3epbi"/></radialGradient><radialGradient id="iIIDBWD" cx="0" cy="0" r="1" gradientTransform="matrix(-.55469 0 0 -.5251 24.634 27.642)" gradientUnits="userSpaceOnUse"><stop class="we87y8v-a"/><stop offset=".857" class="blr2-qnko"/></radialGradient><radialGradient id="iZA2Jgc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 3.96872 -8.54508 -9.55447 25.501 21.782)" gradientUnits="userSpaceOnUse"><stop class="q54my30yn"/><stop offset="1" class="z65w2qfou"/></radialGradient><radialGradient id="isZmuNx" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 -1.21875 2.62409 2.11946 22.423 28.189)" gradientUnits="userSpaceOnUse"><stop class="q54my30yn"/><stop offset="1" class="z65w2qfou"/></radialGradient><radialGradient id="ikssMoe" cx="0" cy="0" r="1" gradientTransform="rotate(-44.596 31.36 -17.097)scale(4.69575 1.99451)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="q5-4t2mwz"/><stop offset="1" class="byjzqv51o"/></radialGradient><radialGradient id="iGDHxbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.54688 0 0 -.60156 27.634 18.142)" gradientUnits="userSpaceOnUse"><stop class="we87y8v-a"/><stop offset=".857" class="blr2-qnko"/></radialGradient><radialGradient id="ipTXpJb" cx="0" cy="0" r="1" gradientTransform="rotate(-154.146 11.043 3.436)scale(1.97069 1.03032)" gradientUnits="userSpaceOnUse"><stop class="zrdr7-bvs"/><stop offset="1" class="ritxrdbjb"/></radialGradient><radialGradient id="i2zJf9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 .41407 -.29221 -.51826 23.751 5.133)" gradientUnits="userSpaceOnUse"><stop class="k777esbaq"/><stop offset="1" class="ml5g0rb-o"/></radialGradient><radialGradient id="iBISsGt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.625 2.40625 0 10.439 21.673)" gradientUnits="userSpaceOnUse"><stop class="vkycqyzjn"/><stop offset="1" class="mtiw__nho"/></radialGradient><radialGradient id="i8lwE5c" cx="0" cy="0" r="1" gradientTransform="rotate(166.516 3.362 12.835)scale(1.54122 3.8152)" gradientUnits="userSpaceOnUse"><stop class="ctcprbbla"/><stop offset="1" class="wahgxirtu"/></radialGradient><radialGradient id="iqSVA4c" cx="0" cy="0" r="1" gradientTransform="matrix(4.98779 .3125 -.67284 10.73924 6.001 25.439)" gradientUnits="userSpaceOnUse"><stop class="q54my30yn"/><stop offset="1" class="z65w2qfou"/></radialGradient><radialGradient id="ik3zjGd" cx="0" cy="0" r="1" gradientTransform="matrix(.1914 .16016 -1.57457 1.8818 7.216 15.72)" gradientUnits="userSpaceOnUse"><stop class="mf-9r_bvd"/><stop offset="1" class="o98zdlb1k"/></radialGradient><radialGradient id="iDAAHZd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.36375 0 0 -4.12701 12.178 18.157)" gradientUnits="userSpaceOnUse"><stop offset=".939" class="o98zdlb1k"/><stop offset="1" class="mf-9r_bvd"/></radialGradient><radialGradient id="iIf2pCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 .78125 -1.27597 -.30624 17.345 7.767)" gradientUnits="userSpaceOnUse"><stop class="sw4acwbyl"/><stop offset="1" class="y3f0vn5br"/></radialGradient><radialGradient id="iYcRTac" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 .8125 -1.03802 .97814 13.751 6.313)" gradientUnits="userSpaceOnUse"><stop class="sw4acwbyl"/><stop offset="1" class="y3f0vn5br"/></radialGradient><radialGradient id="iLFkVMc" cx="0" cy="0" r="1" gradientTransform="matrix(2.1797 -1.14844 .3182 .60393 14.868 7.587)" gradientUnits="userSpaceOnUse"><stop class="f_60ibc2t"/><stop offset="1" class="kqfgrsbxs"/></radialGradient><radialGradient id="isLua6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 3.66427 0 16 8.532)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="urt1a2nbs"/><stop offset=".974" class="zfsoae3ii"/></radialGradient><radialGradient id="izCeI2c" cx="0" cy="0" r="1" gradientTransform="rotate(-154.146 7.05 4.357)scale(1.97069 1.03032)" gradientUnits="userSpaceOnUse"><stop class="zrdr7-bvs"/><stop offset="1" class="ritxrdbjb"/></radialGradient><radialGradient id="iuu8UBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.4375 7.41748 0 15.99 30.626)" gradientUnits="userSpaceOnUse"><stop class="d2z39yyup"/><stop offset="1" class="rv0nyds8s"/></radialGradient><radialGradient id="ii3vAop" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -.90625 17.314 13.376)" gradientUnits="userSpaceOnUse"><stop class="u9tmf8bpo"/><stop offset="1" class="j0pip4bta"/></radialGradient><radialGradient id="izf9abe" cx="0" cy="0" r="1" gradientTransform="matrix(1.35498 1.5 -.76167 .68803 10.99 25.751)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="iuhkohg-j"/><stop offset="1" class="pnmcazbbh"/></radialGradient><radialGradient id="i9JSM1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.25 1.06818 0 13.033 29.095)" gradientUnits="userSpaceOnUse"><stop class="ejab76bje"/><stop offset="1" class="jq3mqhb6f"/></radialGradient><radialGradient id="iJTTAEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 -5.34625 1.75804 .66795 11.47 25.566)" gradientUnits="userSpaceOnUse"><stop class="c68td1bge"/><stop offset="1" class="ex4tf88ri"/></radialGradient><radialGradient id="iOca1tc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.877 19.16 5.972)scale(7.19083 2.3646)" gradientUnits="userSpaceOnUse"><stop class="c68td1bge"/><stop offset="1" class="ex4tf88ri"/></radialGradient><radialGradient id="iLIPbUc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 5.405 -8.39001 -10.38079 25.032 18.846)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="z08bqbb7j"/><stop offset="1" class="xys4gbbxf"/></radialGradient><radialGradient id="ie2RZmm" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -23.7848 0 16 7.938)" gradientUnits="userSpaceOnUse"><stop class="rcpcy6b7s"/><stop offset=".986" class="ihb7lpbku"/></radialGradient><radialGradient id="iq4assq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.03125 4.3125 0 16.095 12.126)" gradientUnits="userSpaceOnUse"><stop class="ad6zeqbpi"/><stop offset="1" class="o08qs6aub"/></radialGradient><radialGradient id="iN8AQ3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .73438 -2.20193 0 16 11.142)" gradientUnits="userSpaceOnUse"><stop class="pi6qpvbbj"/><stop offset="1" class="rz5ayachu"/></radialGradient><radialGradient id="ifbocUE" cx="0" cy="0" r="1" gradientTransform="matrix(-8.84375 1.1406 -.558 -4.32654 20.001 9.751)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="qy9mb3rbw"/><stop offset="1" class="hx7nlwbgf"/></radialGradient><radialGradient id="iQlS8dd" cx="0" cy="0" r="1" gradientTransform="matrix(1.76562 -.9375 .26976 .50804 11.892 9.33)" gradientUnits="userSpaceOnUse"><stop class="t-6pn2bbc"/><stop offset="1" class="j1fmssbab"/></radialGradient><radialGradient id="izEDKRU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.67187 6.80397 0 16 13.751)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="qx1lvqb6i"/><stop offset="1" class="xmqa5uc_c"/></radialGradient><radialGradient id="iw7XkDe" cx="0" cy="0" r="1" gradientTransform="rotate(-21.655 40.387 -22.088)scale(10.5009 7.39492)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="qx1lvqb6i"/><stop offset="1" class="xmqa5uc_c"/></radialGradient><radialGradient id="iQVugqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.6875 -5.78566 0 16 6.313)" gradientUnits="userSpaceOnUse"><stop class="xmqa5uc_c"/><stop offset=".902" class="qx1lvqb6i"/></radialGradient><linearGradient id="i4aATsd" x1="4.98" x2="15.994" y1="7.627" y2="7.627" gradientUnits="userSpaceOnUse"><stop class="lngya5nsm"/><stop offset="1" class="z_h861bih"/></linearGradient><linearGradient id="iJhiGxd" x1="6.97" x2="6.97" y1="13.126" y2="12.376" gradientUnits="userSpaceOnUse"><stop class="lmbdijbmo"/><stop offset="1" class="dn9ov4dwr"/></linearGradient><linearGradient id="iS1hS9c" x1="15.99" x2="27.004" y1="7.627" y2="7.627" gradientUnits="userSpaceOnUse"><stop class="z_h861bih"/><stop offset="1" class="lngya5nsm"/></linearGradient><linearGradient id="itMGiSc" x1="17.98" x2="17.98" y1="13.126" y2="12.376" gradientUnits="userSpaceOnUse"><stop class="lmbdijbmo"/><stop offset="1" class="dn9ov4dwr"/></linearGradient><linearGradient id="iX3cAuj" x1="15.689" x2="9.781" y1="6.329" y2="10.916" gradientUnits="userSpaceOnUse"><stop class="n1wktlb8l"/><stop offset="1" class="gp87kf6yg"/></linearGradient><linearGradient id="i5UvENB" x1="16.464" x2="22.371" y1="6.329" y2="10.916" gradientUnits="userSpaceOnUse"><stop class="msojp8ceo"/><stop offset="1" class="cgz8hqjlh"/></linearGradient><linearGradient id="iblHeId" x1="23.126" x2="23.126" y1="29.032" y2="27.439" gradientUnits="userSpaceOnUse"><stop class="rormvuhzh"/><stop offset="1" class="skjs3epbi"/></linearGradient><linearGradient id="ilmPZdc" x1="24.111" x2="25.032" y1="17.579" y2="16.78" gradientUnits="userSpaceOnUse"><stop class="n46o8jb1u"/><stop offset="1" class="wcg9l2bzo"/></linearGradient><linearGradient id="iCxvhpe" x1="26.392" x2="26.392" y1="19.314" y2="18.22" gradientUnits="userSpaceOnUse"><stop class="n46o8jb1u"/><stop offset="1" class="wcg9l2bzo"/></linearGradient><linearGradient id="i1FZfXc" x1="21.704" x2="22.423" y1="14.798" y2="15.501" gradientUnits="userSpaceOnUse"><stop class="bfuqf9bfs"/><stop offset="1" class="ajtnvmgys"/></linearGradient><linearGradient id="i3igKqd" x1="27.439" x2="22.186" y1="18.439" y2="20.207" gradientUnits="userSpaceOnUse"><stop class="z65w2qfou"/><stop offset=".419" class="kc9php6zk"/><stop offset="1" class="z65w2qfou"/></linearGradient><linearGradient id="iJOH6QD" x1="21.246" x2="22.215" y1="7.07" y2="10.429" gradientUnits="userSpaceOnUse"><stop class="bdy_jjb2s"/><stop offset="1" class="qxwhtii8y"/></linearGradient><linearGradient id="i2NTyid" x1="7.189" x2="10.876" y1="27.657" y2="27.626" gradientUnits="userSpaceOnUse"><stop class="k8pmttfax"/><stop offset="1" class="mj_u4hwco"/></linearGradient><linearGradient id="ia6xbib" x1="9.625" x2="9.625" y1="27.392" y2="28.876" gradientUnits="userSpaceOnUse"><stop class="xjbb_0yag"/><stop offset="1" class="vx02bjbie"/></linearGradient><linearGradient id="i20a0qd" x1="8.907" x2="7.217" y1="19.126" y2="15.236" gradientUnits="userSpaceOnUse"><stop class="tye4zebhv"/><stop offset="1" class="q5-4t2mwz"/></linearGradient><linearGradient id="iaMI7qc" x1="11.376" x2="9.439" y1="17.567" y2="17.567" gradientUnits="userSpaceOnUse"><stop class="xdybvkbnq"/><stop offset="1" class="ht_ms2bkc"/></linearGradient><linearGradient id="i7nzzTc" x1="11.314" x2="9.22" y1="7.829" y2="8.907" gradientUnits="userSpaceOnUse"><stop class="bdy_jjb2s"/><stop offset="1" class="qxwhtii8y"/></linearGradient><linearGradient id="ihGBIjd" x1="10.033" x2="12.061" y1="7.923" y2="9.828" gradientUnits="userSpaceOnUse"><stop class="pgho8vbrv"/><stop offset="1" class="b247ykm2f"/></linearGradient><linearGradient id="i9PyBgb" x1="22.158" x2="20.133" y1="7.923" y2="9.773" gradientUnits="userSpaceOnUse"><stop class="pgho8vbrv"/><stop offset="1" class="b247ykm2f"/></linearGradient><linearGradient id="iRBF2Xs" x1="16.084" x2="16.084" y1="14.188" y2="28.564" gradientUnits="userSpaceOnUse"><stop class="aatjjup3s"/><stop offset="1" class="ib2734bii"/></linearGradient><linearGradient id="iY3tI3b" x1="15.99" x2="15.99" y1="11.954" y2="12.688" gradientUnits="userSpaceOnUse"><stop class="vfjb4cd9m"/><stop offset="1" class="b0ltscyzf"/></linearGradient><linearGradient id="i51Dkwc" x1="11.704" x2="10.99" y1="17.814" y2="17.798" gradientUnits="userSpaceOnUse"><stop class="ej3vnibmd"/><stop offset="1" class="lpk78ebid"/></linearGradient><linearGradient id="iFclZSc" x1="15.158" x2="14.454" y1="14.938" y2="14.938" gradientUnits="userSpaceOnUse"><stop class="n3r8l7-uy"/><stop offset="1" class="igq8a-b6w"/></linearGradient><linearGradient id="ijVxYoe" x1="10.931" x2="11.314" y1="14.938" y2="14.938" gradientUnits="userSpaceOnUse"><stop class="n3r8l7-uy"/><stop offset="1" class="igq8a-b6w"/></linearGradient><linearGradient id="i4T1ywc" x1="14.345" x2="14.345" y1="12.126" y2="13.001" gradientUnits="userSpaceOnUse"><stop class="eoooz0q0t"/><stop offset="1" class="x-urrubjj"/></linearGradient><linearGradient id="isziAIb" x1="14.095" x2="12.783" y1="24.61" y2="23.267" gradientUnits="userSpaceOnUse"><stop class="a1heqcbgo"/><stop offset="1" class="fiio_s-gq"/></linearGradient><linearGradient id="iLxJ7Jd" x1="21.407" x2="20.251" y1="14.938" y2="14.938" gradientUnits="userSpaceOnUse"><stop class="n3r8l7-uy"/><stop offset="1" class="igq8a-b6w"/></linearGradient><linearGradient id="iWyQi8b" x1="20.345" x2="20.345" y1="12.126" y2="13.001" gradientUnits="userSpaceOnUse"><stop class="eoooz0q0t"/><stop offset="1" class="x-urrubjj"/></linearGradient><linearGradient id="iRbscge" x1="20.095" x2="18.782" y1="24.61" y2="23.267" gradientUnits="userSpaceOnUse"><stop class="a1heqcbgo"/><stop offset="1" class="fiio_s-gq"/></linearGradient><linearGradient id="ijHvBxe" x1="16.657" x2="17.782" y1="15.938" y2="15.938" gradientUnits="userSpaceOnUse"><stop class="xys4gbbxf"/><stop offset="1" class="z08bqbb7j"/></linearGradient><linearGradient id="ibtKI6b" x1="5.829" x2="7.119" y1="18.767" y2="14.557" gradientUnits="userSpaceOnUse"><stop class="c5-hwxb-y"/><stop offset="1" class="j1skkzvrn"/></linearGradient><linearGradient id="iVgoIte" x1="17.878" x2="17.221" y1="11.679" y2="9.811" gradientUnits="userSpaceOnUse"><stop class="vdroh7bgc"/><stop offset="1" class="whm89lbaw"/></linearGradient><linearGradient id="iuf2Zgc" x1="13.004" x2="12.741" y1="11.562" y2="10.833" gradientUnits="userSpaceOnUse"><stop class="vdroh7bgc"/><stop offset="1" class="whm89lbaw"/></linearGradient><linearGradient id="iwOBQOb" x1="19.972" x2="19.972" y1="12.61" y2="21.22" gradientUnits="userSpaceOnUse"><stop class="q54my30yn"/><stop offset="1" class="obo-zj96e"/></linearGradient><filter id="iIbsRQd" width="10.912" height="7.256" x="5.201" y="2.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".175"/></filter><filter id="iLK1LTb" width="10.912" height="10.819" x="16.039" y="2.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".175"/></filter><filter id="iZ9IJ7c" width="4.449" height="7.79" x="20.364" y="20.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".15"/></filter><filter id="iNUrWbe" width="7.416" height="4.012" x="20.311" y="14.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".15"/></filter><filter id="iwpSu0d" width="8.139" height="7.962" x="15.977" y="4.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.498039 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6567"/></filter><filter id="ipbwZAt" width="5.42" height="8.61" x="6.99" y="20.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.529412 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6567"/></filter><filter id="imLH2mb" width="4.449" height="7.79" x="7.24" y="20.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".15"/></filter><filter id="im7MmKd" width="8.139" height="7.962" x="7.988" y="4.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.498039 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6567"/></filter><filter id="iMQdRmN" width="3.803" height="6.022" x="8.42" y="4.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".15"/></filter><filter id="i6S3Und" width="3.725" height="6.022" x="20.014" y="4.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".15"/></filter><filter id="iLBI2Zb" width="3.839" height="14.125" x="11.49" y="11.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".25"/></filter><filter id="iZnxoTb" width="4.2" height="13.447" x="10.99" y="12.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.215686 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6567"/></filter><filter id="iBymyGe" width="4.58" height="10.211" x="15.49" y="17.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".75"/></filter><filter id="iHJioKc" width="3.969" height="14.066" x="16.814" y="12.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".25"/></filter><filter id="iFJQbNc" width="4.931" height="4.025" x="4.332" y="14.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".15"/></filter><filter id="iswVzie" width="6.096" height="2.414" x="14.376" y="9.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".25"/></filter><filter id="i7AvaLB" width="3.063" height="1.555" x="11.353" y="10.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".25"/></filter><filter id="iwFnPRb" width="1.938" height="11.891" x="19.003" y="12.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6567" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cockroach" /></template>
<style>
.a0ccrof_a {
  d: path("M23.53 28.636h.71c.41 0 .75-.34.75-.75s-.34-.75-.75-.75h-.71c-.01 0-.02 0-.04-.02c-.01-.02-.01-.03-.01-.04l1.43-4.99c.13-.47.04-.96-.25-1.34c-.3-.4-.74-.62-1.23-.62h-2.96c-.41 0-.75.34-.75.75s.34.75.75.75h2.96c.01 0 .02 0 .03.01s.01.02.01.03l-1.43 4.99c-.13.47-.04.96.25 1.36c.3.39.75.62 1.24.62");
}

.a1heqcbgo {
  stop-color: var(--svg-color--7d4149, #7D4149);
}

.aatjjup3s {
  stop-color: var(--svg-color--693f45, #693F45);
}

.ad6zeqbpi {
  stop-color: var(--svg-color--3d1711, #3D1711);
}

.ajtnvmgys {
  stop-color: var(--svg-color--60332c, #60332C);
  stop-opacity: 0;
}

.apsjgnqzd {
  d: path("M26.77 19.126h.57c.41 0 .75-.34.75-.75s-.34-.75-.75-.75h-.57c-.15 0-.3-.07-.4-.18l-1.99-2.36a1.83 1.83 0 0 0-2.69-.12l-1.59 1.59c-.29.29-.29.77 0 1.06s.455.69.745.4l1.905-1.99c.09-.09.19-.1.24-.09c.05 0 .15.02.23.12l1.99 2.36c.4.45.96.71 1.56.71");
}

.b0ltscyzf {
  stop-color: var(--svg-color--37100d, #37100D);
  stop-opacity: 0;
}

.b247ykm2f {
  stop-color: var(--svg-color--80625f, #80625F);
  stop-opacity: 0;
}

.bdy_jjb2s {
  stop-color: var(--svg-color--643e38, #643E38);
}

.bfuqf9bfs {
  stop-color: var(--svg-color--60332c, #60332C);
}

.blr2-qnko {
  stop-color: var(--svg-color--9a7c77, #9A7C77);
  stop-opacity: 0;
}

.byjzqv51o {
  stop-color: var(--svg-color--724b44, #724B44);
  stop-opacity: 0;
}

.c5-hwxb-y {
  stop-color: var(--svg-color--775053, #775053);
}

.c68td1bge {
  stop-color: var(--svg-color--7e4166, #7E4166);
}

.cgz8hqjlh {
  stop-color: var(--svg-color--d18e8d, #D18E8D);
}

.ctcprbbla {
  stop-color: var(--svg-color--6a3234, #6A3234);
}

.d2_rfacbv {
  d: path("M15.23 12.526c-.07 0-.15-.01-.22-.03l-4.06-1.28c-.95-.3-1.59-1.17-1.59-2.17v-1.98c0-.28-.15-.54-.4-.68l-.58-.31c-.36-.2-.5-.65-.3-1.02c.2-.36.65-.5 1.02-.3l.57.31c.73.4 1.18 1.16 1.18 1.99v1.98c0 .34.22.64.54.74l4.06 1.27c.4.12.62.54.49.94c-.09.33-.39.54-.71.54");
}

.d2z39yyup {
  stop-color: var(--svg-color--a14b7a, #A14B7A);
}

.di8egubhl {
  d: path("M19.11 12.126h-6.24c-1.04 0-1.88.84-1.88 1.88v9.87c0 1.83.83 3.56 2.26 4.71l1.31 1.04a2.3 2.3 0 0 0 2.87 0l1.3-1.04a6 6 0 0 0 2.26-4.7v-9.87c0-1.05-.84-1.89-1.88-1.89");
}

.dn9ov4dwr {
  stop-color: var(--svg-color--9d5469, #9D5469);
  stop-opacity: 0;
}

.e51sjw1ie {
  d: path("M14.99 19.836v-7.71h-2.12c-1.04 0-1.88.84-1.88 1.88v9.87c0 .387.036.77.107 1.141a.435.435 0 0 0 .64.301a6.24 6.24 0 0 0 3.253-5.482");
}

.ej3vnibmd {
  stop-color: var(--svg-color--7f4f58, #7F4F58);
}

.ejab76bje {
  stop-color: var(--svg-color--a46a7f, #A46A7F);
}

.eoooz0q0t {
  stop-color: var(--svg-color--714d46, #714D46);
}

.ex4tf88ri {
  stop-color: var(--svg-color--7e4166, #7E4166);
  stop-opacity: 0;
}

.f_60ibc2t {
  stop-color: var(--svg-color--67453e, #67453E);
}

.f0l3w9bnw {
  d: path("M21.49 2.126c3.04 0 5.51 2.47 5.51 5.51c0 .04 0 .08-.01.11v4.89a.49.49 0 0 1-.98 0v-4.94c0-2.52-2.03-4.59-4.55-4.57c-2.46.02-4.46 2.03-4.47 4.5c0 .23-.15.44-.37.5a.505.505 0 0 1-.63-.48a5.51 5.51 0 0 1 5.5-5.52");
}

.fao1accsc {
  d: path("M16.735 12.517c.07 0 .15-.01.22-.03l4.06-1.27c.95-.3 1.59-1.17 1.59-2.17v-1.99c0-.28.15-.54.4-.68l.57-.31c.36-.2.5-.65.3-1.02c-.2-.36-.65-.5-1.02-.3l-.57.31c-.73.4-1.18 1.16-1.18 1.99v1.98c0 .34-.22.64-.54.74l-4.06 1.27c-.4.12-.62.54-.49.94c.11.33.4.54.72.54");
}

.fiio_s-gq {
  stop-color: var(--svg-color--7d4149, #7D4149);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g6vo9yehj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.gp87kf6yg {
  stop-color: var(--svg-color--b57675, #B57675);
}

.h9rcw8xwx {
  fill: var(--svg-color--764c42, #764C42);
  d: path("M23.53 28.636h.71c.41 0 .75-.34.75-.75s-.34-.75-.75-.75h-.71c-.01 0-.02 0-.04-.02c-.01-.02-.01-.03-.01-.04l1.43-4.99c.13-.47.04-.96-.25-1.34c-.3-.4-.74-.62-1.23-.62h-2.96c-.41 0-.75.34-.75.75s.34.75.75.75h2.96c.01 0 .02 0 .03.01s.01.02.01.03l-1.43 4.99c-.13.47-.04.96.25 1.36c.3.39.75.62 1.24.62");
}

.ht_ms2bkc {
  stop-color: var(--svg-color--4e2220, #4E2220);
  stop-opacity: 0;
}

.hunqegb2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m20.761 17.118l1.816-1.828a.75.75 0 0 1 1.103.043l2.125 2.496a1 1 0 0 0 .762.352h.71");
}

.hx7nlwbgf {
  stop-color: var(--svg-color--8f8280, #8F8280);
}

.i6y975b1b {
  stop-color: var(--svg-color--763c39, #763C39);
}

.ib2734bii {
  stop-color: var(--svg-color--a6636a, #A6636A);
}

.igq8a-b6w {
  stop-color: var(--svg-color--907773, #907773);
  stop-opacity: 0;
}

.ihb7lpbku {
  stop-color: var(--svg-color--481c21, #481C21);
}

.iuhkohg-j {
  stop-color: var(--svg-color--894951, #894951);
}

.j0pip4bta {
  stop-color: var(--svg-color--6e5355, #6E5355);
  stop-opacity: 0;
}

.j1fmssbab {
  stop-color: var(--svg-color--67413d, #67413D);
  stop-opacity: 0;
}

.j1skkzvrn {
  stop-color: var(--svg-color--775053, #775053);
  stop-opacity: 0;
}

.jq3mqhb6f {
  stop-color: var(--svg-color--a46a7f, #A46A7F);
  stop-opacity: 0;
}

.jr1eewbzh {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.378 12.61c.396.073 1.188.47 1.188 1.47v9.671");
}

.k777esbaq {
  stop-color: var(--svg-color--8f7673, #8F7673);
}

.k8pmttfax {
  stop-color: var(--svg-color--7d4f4a, #7D4F4A);
}

.kboedpbum {
  d: path("M16 9.345c1.42 0 2.57-.77 2.57-1.719S17.42 5.907 16 5.907s-2.57.77-2.57 1.719S14.58 9.345 16 9.345");
}

.kc9php6zk {
  stop-color: var(--svg-color--92736f, #92736F);
}

.kqfgrsbxs {
  stop-color: var(--svg-color--67453e, #67453E);
  stop-opacity: 0;
}

.kr4ikd3sv {
  d: path("M20.814 20.876h2.798a.75.75 0 0 1 .717.97l-1.614 5.274a.5.5 0 0 0 .478.647h1.105");
}

.l3h-k10hb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m23.314 5.235l-.09.037a2 2 0 0 0-1.238 1.85v1.616a1.5 1.5 0 0 1-.88 1.366l-.667.303");
}

.lmbdijbmo {
  stop-color: var(--svg-color--9d5469, #9D5469);
}

.lngya5nsm {
  stop-color: var(--svg-color--a36256, #A36256);
}

.lpk78ebid {
  stop-color: var(--svg-color--704144, #704144);
}

.mf-9r_bvd {
  stop-color: var(--svg-color--988480, #988480);
}

.mj_u4hwco {
  stop-color: var(--svg-color--7d4f4a, #7D4F4A);
  stop-opacity: 0;
}

.ml5g0rb-o {
  stop-color: var(--svg-color--8f7673, #8F7673);
  stop-opacity: 0;
}

.ms3r5q4gx {
  stop-color: var(--svg-color--763c39, #763C39);
  stop-opacity: 0;
}

.msojp8ceo {
  stop-color: var(--svg-color--826661, #826661);
}

.mtiw__nho {
  stop-color: var(--svg-color--692e57, #692E57);
  stop-opacity: 0;
}

.n1wktlb8l {
  stop-color: var(--svg-color--ac8f89, #AC8F89);
}

.n3r8l7-uy {
  stop-color: var(--svg-color--907773, #907773);
}

.n46o8jb1u {
  stop-color: var(--svg-color--75385d, #75385D);
}

.n6h4v9jdv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.239 20.876H8.44a.75.75 0 0 0-.717.97l1.615 5.274a.5.5 0 0 1-.478.647H7.755");
}

.o08qs6aub {
  stop-color: var(--svg-color--3d1711, #3D1711);
  stop-opacity: 0;
}

.o98zdlb1k {
  stop-color: var(--svg-color--988480, #988480);
  stop-opacity: 0;
}

.obn46v5st {
  d: path("M19.11 12.126h-2.12v7.71a6.24 6.24 0 0 0 3.253 5.482a.435.435 0 0 0 .64-.3q.107-.56.107-1.142v-9.87c0-1.04-.84-1.88-1.88-1.88");
}

.obo-zj96e {
  stop-color: var(--svg-color--9b7b76, #9B7B76);
  stop-opacity: 0;
}

.p2l14hztc {
  fill: var(--svg-color--663e3d, #663E3D);
  d: path("M8.45 28.636h-.71c-.41 0-.75-.34-.75-.75s.34-.75.75-.75h.71c.01 0 .02 0 .04-.02c.01-.02.01-.03.01-.04l-1.43-4.99c-.13-.47-.04-.96.25-1.35s.74-.61 1.23-.61h2.96c.41 0 .75.34.75.75s-.34.75-.75.75H8.55c-.01 0-.02 0-.03.01s-.01.02-.01.03l1.43 4.99c.13.47.04.96-.25 1.36c-.3.39-.75.62-1.24.62");
}

.p510_1bcz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.626 8.954V7.767c0-2.922 2.138-5.22 5.157-5.22c3.093 0 4.708 3 4.906 4.5");
}

.pgho8vbrv {
  stop-color: var(--svg-color--80625f, #80625F);
}

.pi6qpvbbj {
  stop-color: var(--svg-color--622c51, #622C51);
}

.pnmcazbbh {
  stop-color: var(--svg-color--91535b, #91535B);
  stop-opacity: 0;
}

.q5-4t2mwz {
  stop-color: var(--svg-color--724b44, #724B44);
}

.q54my30yn {
  stop-color: var(--svg-color--9b7b76, #9B7B76);
}

.q79k-p7ig {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.526 12.517v-4.75c0-2.922-2.138-5.22-5.156-5.22c-3.094 0-4.708 3-4.906 4.5");
}

.qwa9k5bpy {
  d: path("M19.972 11.125h-5.097c.171-.459.958-1.415 2.816-1.415s2.28 1.26 2.28 1.414");
}

.qx1lvqb6i {
  stop-color: var(--svg-color--745a55, #745A55);
  stop-opacity: 0;
}

.qxwhtii8y {
  stop-color: var(--svg-color--663749, #663749);
}

.qy9mb3rbw {
  stop-color: var(--svg-color--8f8280, #8F8280);
  stop-opacity: 0;
}

.rcpcy6b7s {
  stop-color: var(--svg-color--6b4640, #6B4640);
}

.rhwjd89vh {
  fill: var(--svg-color--863b45, #863B45);
  d: path("M18.887 12.61h-1.573v7.664c0 2.198.859 4.194 2.228 5.306c.263.214.636.051.678-.285q.063-.494.063-1.005v-9.81c0-1.035-.624-1.87-1.396-1.87");
}

.ritxrdbjb {
  stop-color: var(--svg-color--5a293f, #5A293F);
  stop-opacity: 0;
}

.rormvuhzh {
  stop-color: var(--svg-color--874368, #874368);
}

.rv0nyds8s {
  stop-color: var(--svg-color--a14b7a, #A14B7A);
  stop-opacity: 0;
}

.rz5ayachu {
  stop-color: var(--svg-color--663356, #663356);
  stop-opacity: 0;
}

.sk819zb8t {
  d: path("M13.915 11.345h-2.062v-.555z");
}

.skjs3epbi {
  stop-color: var(--svg-color--874368, #874368);
  stop-opacity: 0;
}

.sv02bu-li {
  d: path("M10.49 2.126c-3.04 0-5.51 2.47-5.51 5.51c0 .04 0 .08.01.11v4.89a.49.49 0 0 0 .98 0v-4.94c0-2.52 2.03-4.59 4.55-4.57c2.46.02 4.46 2.03 4.47 4.5c0 .23.15.44.37.5c.33.08.63-.17.63-.48c0-3.05-2.47-5.52-5.5-5.52");
}

.sw4acwbyl {
  stop-color: var(--svg-color--89706b, #89706B);
}

.t-6pn2bbc {
  stop-color: var(--svg-color--67413d, #67413D);
}

.t9b57-bxi {
  fill: var(--svg-color--6a473f, #6A473F);
  d: path("M16 9.345c1.42 0 2.57-.77 2.57-1.719S17.42 5.907 16 5.907s-2.57.77-2.57 1.719S14.58 9.345 16 9.345");
}

.tye4zebhv {
  stop-color: var(--svg-color--73375d, #73375D);
}

.u9tmf8bpo {
  stop-color: var(--svg-color--6e5355, #6E5355);
}

.urt1a2nbs {
  stop-color: var(--svg-color--7e6b67, #7E6B67);
  stop-opacity: 0;
}

.v2c3h7bev {
  d: path("M15.957 7.376h.087c2.33.02 4.073 1.39 4.683 3.375c.171.766-.29 1.375-1.618 1.375h-6.218c-1.328 0-1.79-.61-1.617-1.375c.609-1.984 2.353-3.356 4.683-3.375");
}

.vbouujb0r {
  fill: var(--svg-color--863b45, #863B45);
  d: path("M14.83 19.836v-7.71h-1.505c-.739 0-1.335.84-1.335 1.88v9.87q0 .503.057.99c.04.344.423.507.683.28c1.291-1.124 2.1-3.117 2.1-5.31");
}

.vdroh7bgc {
  stop-color: var(--svg-color--8d7371, #8D7371);
}

.vfjb4cd9m {
  stop-color: var(--svg-color--37100d, #37100D);
}

.vkycqyzjn {
  stop-color: var(--svg-color--692e57, #692E57);
}

.vx02bjbie {
  stop-color: var(--svg-color--83406b, #83406B);
}

.w3fgaud-r {
  fill: var(--svg-color--724b44, #724B44);
  d: path("M26.77 19.126h.57c.41 0 .75-.34.75-.75s-.34-.75-.75-.75h-.57c-.15 0-.3-.07-.4-.18l-1.99-2.36a1.83 1.83 0 0 0-2.69-.12l-1.59 1.59c-.29.29-.29.77 0 1.06s.455.69.745.4l1.905-1.99c.09-.09.19-.1.24-.09c.05 0 .15.02.23.12l1.99 2.36c.4.45.96.71 1.56.71");
}

.wahgxirtu {
  stop-color: var(--svg-color--6a3234, #6A3234);
  stop-opacity: 0;
}

.wak17tm2o {
  fill: var(--svg-color--7f4f58, #7F4F58);
  d: path("M19.11 12.126h-2.12v7.71a6.24 6.24 0 0 0 3.253 5.482a.435.435 0 0 0 .64-.3q.107-.56.107-1.142v-9.87c0-1.04-.84-1.88-1.88-1.88");
}

.wcg9l2bzo {
  stop-color: var(--svg-color--75385d, #75385D);
  stop-opacity: 0;
}

.we87y8v-a {
  stop-color: var(--svg-color--9a7c77, #9A7C77);
}

.whm89lbaw {
  stop-color: var(--svg-color--8d7371, #8D7371);
  stop-opacity: 0;
}

.x-urrubjj {
  stop-color: var(--svg-color--714d46, #714D46);
  stop-opacity: 0;
}

.xdybvkbnq {
  stop-color: var(--svg-color--4e2220, #4E2220);
}

.xjbb_0yag {
  stop-color: var(--svg-color--83406b, #83406B);
  stop-opacity: 0;
}

.xmqa5uc_c {
  stop-color: var(--svg-color--745a55, #745A55);
}

.xu8jff5wh {
  d: path("M8.45 28.636h-.71c-.41 0-.75-.34-.75-.75s.34-.75.75-.75h.71c.01 0 .02 0 .04-.02c.01-.02.01-.03.01-.04l-1.43-4.99c-.13-.47-.04-.96.25-1.35s.74-.61 1.23-.61h2.96c.41 0 .75.34.75.75s-.34.75-.75.75H8.55c-.01 0-.02 0-.03.01s-.01.02-.01.03l1.43 4.99c.13.47.04.96-.25 1.36c-.3.39-.75.62-1.24.62");
}

.xys4gbbxf {
  stop-color: var(--svg-color--662e32, #662E32);
}

.y3f0vn5br {
  stop-color: var(--svg-color--89706b, #89706B);
  stop-opacity: 0;
}

.z_h861bih {
  stop-color: var(--svg-color--5d3334, #5D3334);
}

.z_twmlb2a {
  d: path("M5.29 19.126h-.57c-.41 0-.75-.317-.75-.72s.34-.719.75-.719h.57c.15 0 .3-.067.4-.172l1.99-2.264A1.86 1.86 0 0 1 9 14.627a1.88 1.88 0 0 1 1.37.509l1.59 1.525c.29.278.29.738 0 1.017a.777.777 0 0 1-1.06 0l-1.59-1.526a.29.29 0 0 0-.24-.086a.31.31 0 0 0-.23.115l-1.99 2.264c-.4.432-.96.681-1.56.681");
}

.z08bqbb7j {
  stop-color: var(--svg-color--662e32, #662E32);
  stop-opacity: 0;
}

.z65bblbry {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m8.845 5.235l.38.186a2 2 0 0 1 1.12 1.796v1.615c0 .635.4 1.201.998 1.414l.455.161");
}

.z65w2qfou {
  stop-color: var(--svg-color--92736f, #92736F);
  stop-opacity: 0;
}

.z9g1wdzst {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M4.782 18.407h.863a.5.5 0 0 0 .364-.156l2.805-2.969");
}

.zfsoae3ii {
  stop-color: var(--svg-color--7e6b67, #7E6B67);
}

.zpt3dibpf {
  fill: var(--svg-color--b07776, #B07776);
  d: path("M16.99 19.29h1.58v7.211h-1.58z");
}

.zrdr7-bvs {
  stop-color: var(--svg-color--5a293f, #5A293F);
}

</style>
