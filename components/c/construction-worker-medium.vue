<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYl9Gdb)" class="rihmkq8le"/><path fill="url(#iKEcTfe)" class="rihmkq8le"/><path fill="url(#iRNOrCe)" class="f3ael5nnj"/><path fill="url(#izlspBK)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iFGqZ7b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iTFP0od)" class="pkk1wtbcw"/><path fill="url(#i0QFqKc)" class="pkk1wtbcw"/><path fill="url(#i1aP5Bc)" class="pkk1wtbcw"/><path fill="url(#i8sZbpU)" class="njvu41bsf"/><path fill="url(#ilGfS8d)" class="njvu41bsf"/><path class="cwhvcxb2p"/><path fill="url(#in3x4bd)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="bkw3kzb2o"/><path fill="url(#iwPt3uy)" class="bkw3kzb2o"/><path fill="url(#izX9lmb)" class="m1bnqqb6k"/><path fill="url(#izox6Ge)" class="m1bnqqb6k"/><path fill="url(#iIiLQQc)" class="wgxfwnb9g"/><path fill="url(#ii4eH6l)" class="wgxfwnb9g"/><path fill="url(#ijNpyWb)" class="i-ycf-bxl"/><path fill="url(#iuUcttc)" class="i-ycf-bxl"/><path fill="url(#iqlRfqc)" class="i-ycf-bxl"/><path fill="url(#i6Hx1XR)" class="k_jucyxfa"/><path fill="url(#iBm87Fd)" class="rb96brbhl"/><path fill="url(#itSUjHc)" class="eoq_gfb2k"/><path fill="url(#i9OEToc)" class="mf8z32bzn"/><g filter="url(#ixGjCHe)"><path fill="url(#iCQOe1c)" class="zhek-5bdo"/><path fill="url(#ibea8tM)" class="zhek-5bdo"/></g><path fill="url(#iCKkWzB)" class="zhek-5bdo"/><path fill="url(#ijkSbwQ)" class="zhek-5bdo"/><path fill="url(#i33DKKe)" class="zhek-5bdo"/><path fill="url(#iS8y0fc)" class="zhek-5bdo"/><path fill="url(#igA6Frb)" class="zhek-5bdo"/><path fill="url(#i9OnNkY)" class="zhek-5bdo"/><path fill="url(#iFFvEKc)" class="zhek-5bdo"/><path fill="url(#i6rAEoG)" class="zhek-5bdo"/><path fill="url(#iKWYexV)" class="zhek-5bdo"/><g filter="url(#iU3Vlie)"><path class="k8r9hrb_g"/></g><g filter="url(#iQSBoLc)"><path class="ihkes3c8a"/><path fill="url(#izgxuWc)" class="x3o-keblz"/><path fill="url(#idISWld)" class="x3o-keblz"/><path fill="url(#iGRmezb)" class="x3o-keblz"/><path fill="url(#isGz9sd)" class="x3o-keblz"/></g><g filter="url(#iIeobec)"><path fill="url(#iYfOOJc)" class="cngoi9bwz"/></g><g filter="url(#iLK70Ke)"><path stroke="url(#iXquKwv)" class="hxltt9ifj"/></g><path fill="url(#iJZSxFd)" class="hd2jtf3us"/><path class="euw3wkz4u"/><path fill="url(#ibUVEvd)" class="t_7gewwjv"/><path class="mp5sp9k_i"/><g filter="url(#iaVC54b)"><path class="jb6hrqxbx"/><path fill="url(#iLmfBuR)" class="nb4nv6byl"/></g><g filter="url(#iBNursd)"><path fill="url(#iLi3zMb)" class="ncaqcbc5e"/></g><path class="di8hc5bev"/><path fill="url(#ibnYRry)" class="q9fjvcbsc"/><path class="vxvsd1bzh"/><g filter="url(#iuEWgKe)"><path fill="url(#iFNwHCb)" class="yc798xb9y"/></g><g filter="url(#iQBNtbc)"><ellipse transform="rotate(-27.914 13.367 13.07)" class="gq-960njj"/><ellipse fill="url(#iY1GMed)" transform="rotate(-27.914 13.367 13.07)" class="w-3g65lfw"/></g><path fill="url(#inQ3Foc)" class="rgtt66b9m"/><path fill="url(#isJSmEc)" class="rgtt66b9m"/><path fill="url(#icByACe)" class="rgtt66b9m"/><path fill="url(#iuk07Pd)" class="rgtt66b9m"/><path fill="url(#irE1Zic)" class="fmyzxtbus"/><path fill="url(#irLXqUc)" class="fmyzxtbus"/><g filter="url(#iEx8Kzd)"><path fill="url(#i9s4ute)" class="g0kuxjbxx"/></g><g filter="url(#i0eVtwO)"><path fill="url(#iF0Igry)" class="ap6dz0d5l"/></g><path fill="url(#it84Uce)" class="yacjacccz"/><path fill="url(#iAvECrc)" class="yacjacccz"/><path fill="url(#iPHUYFd)" class="yacjacccz"/><path fill="url(#iXMTIBb)" class="yacjacccz"/><path fill="url(#iajAx2b)" class="yacjacccz"/><path fill="url(#iXqASBd)" class="yacjacccz"/><path fill="url(#iMLgQTb)" class="yacjacccz"/><path fill="url(#i3tCWcc)" class="yacjacccz"/><g filter="url(#iE6IcTb)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="fe6f5np8m"/><path fill="url(#iLaLawe)" class="fe6f5np8m"/><path fill="url(#iu2HU3b)" class="fe6f5np8m"/><path fill="url(#iRrXLNd)" class="fe6f5np8m"/><defs><radialGradient id="iYl9Gdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.625 6.57257 0 16.011 29.735)" gradientUnits="userSpaceOnUse"><stop class="rj0sd-b5f"/><stop offset="1" class="yrhyj2blb"/></radialGradient><radialGradient id="iKEcTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -12.5036 18.677 26.172)" gradientUnits="userSpaceOnUse"><stop class="rredkdkgz"/><stop offset="1" class="ci5tu_5bf"/></radialGradient><radialGradient id="iRNOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="izlspBK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iFGqZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="i0QFqKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.885)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="i8sZbpU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.544)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ilGfS8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.938)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="in3x4bd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.12)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="izX9lmb" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.891)" gradientUnits="userSpaceOnUse"><stop class="hkp0jqbkb"/><stop offset="1" class="fnpqbob3w"/></radialGradient><radialGradient id="iIiLQQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.93)" gradientUnits="userSpaceOnUse"><stop class="eluvk9b8d"/><stop offset="1" class="oymutzb3n"/></radialGradient><radialGradient id="ii4eH6l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="hsoncjbem"/><stop offset="1" class="gh3m30bhl"/></radialGradient><radialGradient id="ijNpyWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -4.86609 0 16.021 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="rmeqmu2gr"/><stop offset=".88" class="y43e-qb0b"/></radialGradient><radialGradient id="iuUcttc" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.823 15.175)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="vsv0dabls"/><stop offset="1" class="smwrkvbhh"/></radialGradient><radialGradient id="iqlRfqc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.61608 1.94033 -2.53687 -3.42038 16.693 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="j20988b2t"/><stop offset="1" class="vck3ny32q"/><stop offset="1" class="p5tw2j66v"/></radialGradient><radialGradient id="i6Hx1XR" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.33 22.8)scale(2.33004 2.76791)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iBm87Fd" cx="0" cy="0" r="1" gradientTransform="matrix(1.59723 .50198 -1.54864 4.92754 9.47 15.713)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iCQOe1c" cx="0" cy="0" r="1" gradientTransform="rotate(172.694 9.26 7.786)scale(4.9149 9.9878)" gradientUnits="userSpaceOnUse"><stop class="u05m3mb1z"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ibea8tM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88573 3.11875 -2.57478 -1.55682 18.647 8.778)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ijkSbwQ" cx="0" cy="0" r="1" gradientTransform="rotate(91.404 4.846 12.038)scale(14.0342 23.8913)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="d_pq49_jz"/><stop offset=".981" class="eji22p4un"/></radialGradient><radialGradient id="i33DKKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24227 1.53731 0 18.668 12.744)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iS8y0fc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.187 -.393)scale(1.18378 1.28824)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="igA6Frb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.627 7.928)scale(9.20915 23.5248)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i9OnNkY" cx="0" cy="0" r="1" gradientTransform="matrix(3.6627 -3.155 .93194 1.0819 8.674 11.208)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iFFvEKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25386 2.7017 -1.07998 -.10148 22.019 11.009)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i6rAEoG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94287 -1.81005 0 13.624 13.628)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iKWYexV" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.0625 -8.3449 0 16.072 11.769)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="dzrzb_e4u"/><stop offset="1" class="kpupscd1w"/></radialGradient><radialGradient id="idISWld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .26407 -.82993 0 16.525 15.636)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="isGz9sd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.83045 .81145 -1.30406 -2.94168 16.651 15.02)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iJZSxFd" cx="0" cy="0" r="1" gradientTransform="matrix(2.36045 -1.16046 4.66883 9.49669 15.49 18.083)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ibUVEvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87768 -1.39604 0 18.382 13.173)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iLmfBuR" cx="0" cy="0" r="1" gradientTransform="matrix(-.25089 -.3233 .4451 -.3454 18.136 13.264)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibnYRry" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87772 -1.39611 0 13.66 13.173)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iY1GMed" cx="0" cy="0" r="1" gradientTransform="matrix(-.00837 -.5345 .64248 -.01006 13.35 13.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isJSmEc" cx="0" cy="0" r="1" gradientTransform="matrix(.67996 2.42675 -2.3153 .64873 21.016 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="icByACe" cx="0" cy="0" r="1" gradientTransform="matrix(.85222 -1.16953 .9803 .71433 21.406 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iuk07Pd" cx="0" cy="0" r="1" gradientTransform="matrix(.635 -1.67723 2.24101 .84846 21.53 13.963)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="irLXqUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79388 0 0 -2.00312 10.704 13.881)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i9s4ute" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 4.76 7.398)scale(1.00594 1.0314)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="it84Uce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.584 6.797)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iTFP0od" x1="9.158" x2="9.158" y1="21.199" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="izox6Ge" x1="8.468" x2="7.09" y1="29.93" y2="29.773" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nhznusr0x"/><stop offset="1" class="zdrlg3bmy"/></linearGradient><linearGradient id="itSUjHc" x1="10.558" x2="9.521" y1="11.93" y2="11.93" gradientUnits="userSpaceOnUse"><stop class="ymyjruwrb"/><stop offset="1" class="osvrbmbgh"/></linearGradient><linearGradient id="i9OEToc" x1="21.396" x2="22.084" y1="11.969" y2="11.969" gradientUnits="userSpaceOnUse"><stop class="mnu548xdh"/><stop offset="1" class="igfnq7b1m"/></linearGradient><linearGradient id="iCKkWzB" x1="21.6" x2="18.864" y1="15.988" y2="15.988" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="izgxuWc" x1="17.186" x2="15.874" y1="14.94" y2="14.847" gradientUnits="userSpaceOnUse"><stop class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iGRmezb" x1="16.021" x2="16.021" y1="16.126" y2="15.623" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iYfOOJc" x1="16.021" x2="16.343" y1="12.868" y2="14.794" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gfp0_jbqk"/><stop offset="1" class="j8331kbgg"/></linearGradient><linearGradient id="iXquKwv" x1="14.721" x2="15.066" y1="17.826" y2="16.923" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iLi3zMb" x1="19.223" x2="18.884" y1="13.231" y2="13.44" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFNwHCb" x1="14.465" x2="14.126" y1="13.231" y2="13.441" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inQ3Foc" x1="22.984" x2="21.678" y1="13.26" y2="15.614" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="irE1Zic" x1="9.693" x2="11.27" y1="14.022" y2="13.884" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iF0Igry" x1="21.92" x2="21.92" y1="12.926" y2="14.828" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iLaLawe" x1="15.587" x2="15.587" y1="9.842" y2="10.156" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iu2HU3b" x1="16.505" x2="16.505" y1="12.149" y2="10.896" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="ixGjCHe" width="12.056" height="13.451" x="10.544" y="7.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2954"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2954" result="effect2_innerShadow_4002_2954"/></filter><filter id="iU3Vlie" width="3.795" height="5.137" x="13.922" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".5"/></filter><filter id="iQSBoLc" width="2.431" height="3.537" x="14.806" y="12.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".1"/></filter><filter id="iIeobec" width="2.431" height="3.537" x="14.806" y="12.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".1"/></filter><filter id="iLK70Ke" width="3.982" height="1.661" x="14.03" y="16.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".05"/></filter><filter id="iaVC54b" width=".835" height=".737" x="17.596" y="12.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".05"/></filter><filter id="iBNursd" width=".931" height=".955" x="18.512" y="12.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".1"/></filter><filter id="iuEWgKe" width="1.034" height="1.093" x="13.706" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".1"/></filter><filter id="iQBNtbc" width=".971" height=".746" x="12.881" y="12.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".05"/></filter><filter id="iEx8Kzd" width="1.397" height="2.533" x="9.463" y="12.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".125"/></filter><filter id="i0eVtwO" width="1.872" height="2.902" x="20.984" y="12.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2954" stdDeviation=".25"/></filter><filter id="iE6IcTb" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2954"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2954" result="effect2_innerShadow_4002_2954"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction-worker-medium" /></template>
<style>
.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.ap6dz0d5l {
  d: path("M21.484 14.828q.054-.951.102-1.902c.434.059.77.46.77.947c0 .525-.39.95-.872.955");
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bkw3kzb2o {
  d: path("M22.025 20.77v9.16h-1.983V19.735c.698.28 1.355.62 1.983 1.034");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ci5tu_5bf {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cngoi9bwz {
  d: path("m15.607 13.198l-.575 1.989c-.117.409.165.818.564.818h.85c.4 0 .68-.415.563-.818l-.574-1.989c-.124-.44-.699-.44-.828 0");
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.d_pq49_jz {
  stop-color: var(--svg-color--9d6074, #9D6074);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.di8hc5bev {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.435 12.363a1.51 1.51 0 0 0-1.466 1.145a.297.297 0 0 0 .29.369h2.413a.25.25 0 0 0 .246-.294a1.516 1.516 0 0 0-1.483-1.22");
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.dzrzb_e4u {
  stop-color: var(--svg-color--8d565b, #8D565B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.eji22p4un {
  stop-color: var(--svg-color--b0597d, #B0597D);
}

.eluvk9b8d {
  stop-color: var(--svg-color--ff9c5e, #FF9C5E);
}

.eoq_gfb2k {
  d: path("M9.605 11.621h.953v1.082h-.953z");
}

.euw3wkz4u {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.608 12.363a1.51 1.51 0 0 1 1.465 1.145a.296.296 0 0 1-.29.369H17.37a.25.25 0 0 1-.246-.294a1.51 1.51 0 0 1 1.484-1.22");
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

.f3ael5nnj {
  d: path("M13.721 19.198c-.608.134-1.196.31-1.763.537V29.93h1.763z");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fe6f5np8m {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.153a1.147 1.147 0 0 0-1.153-1.154");
}

.fmyzxtbus {
  d: path("M10.564 12.148c-.845.12-1.506.85-1.506 1.729c0 .929.729 1.688 1.646 1.738a85 85 0 0 1-.14-3.467");
}

.fnpqbob3w {
  stop-color: var(--svg-color--ce763c, #CE763C);
}

.ft5dv1b6b {
  fill: none;
}

.g0kuxjbxx {
  d: path("M10.52 12.868a1.034 1.034 0 0 0 .09 2.033a84 84 0 0 1-.09-2.033");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gfp0_jbqk {
  stop-color: var(--svg-color--915d5e, #915D5E);
}

.gh3m30bhl {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
  stop-opacity: 0;
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gq-960njj {
  cx: 13.367px;
  cy: 13.069px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.421px;
  ry: 0.213px;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hd2jtf3us {
  d: path("M16.021 17.297a3.25 3.25 0 0 1-1.499-.355c-.148-.075-.307.092-.214.226c.363.55.994.915 1.713.915s1.35-.366 1.713-.915c.093-.14-.066-.301-.214-.226a3.2 3.2 0 0 1-1.499.355");
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

.hxltt9ifj {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.557 16.876a.24.24 0 0 0-.287.049a.22.22 0 0 0-.024.285c.376.57 1.03.948 1.775.948s1.4-.379 1.776-.948a.225.225 0 0 0-.025-.288a.24.24 0 0 0-.286-.047c-.423.22-.922.347-1.465.347a3.2 3.2 0 0 1-1.464-.347Z");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i-ycf-bxl {
  d: path("M13.81 20.406c.06.76.585 2.282 2.211 2.282s2.151-1.521 2.211-2.282z");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.igfnq7b1m {
  stop-color: var(--svg-color--4f4c4d, #4F4C4D);
}

.ihkes3c8a {
  fill: var(--svg-color--946964, #946964);
  d: path("m15.607 13.39l-.575 1.99c-.117.409.165.818.564.818h.85c.4 0 .68-.416.563-.818l-.574-1.99c-.124-.44-.699-.44-.828 0");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j20988b2t {
  stop-color: var(--svg-color--8d4e5b, #8D4E5B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8331kbgg {
  stop-color: var(--svg-color--915d5e, #915D5E);
  stop-opacity: 0;
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jb6hrqxbx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.313 12.861c.069.092-.075.204-.239.326s-.284.209-.353.117s.008-.266.171-.388c.164-.122.352-.147.42-.055");
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k_jucyxfa {
  d: path("M21.28 15.516c.363-.011.702-.134.979-.333v1.007a2.35 2.35 0 0 1-1.45 2.184q.276-.59.373-1.277z");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k8r9hrb_g {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.553 13.603l-.607 1.989c-.103.409.146.818.498.818h.752c.352 0 .601-.416.498-.818l-.508-1.99c-.11-.44-.518-.44-.633 0");
}

.kpupscd1w {
  stop-color: var(--svg-color--8d565b, #8D565B);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
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

.m1bnqqb6k {
  d: path("M4.601 29.93c.14-.946.34-1.882.62-2.786a11.56 11.56 0 0 1 3.12-5.019v7.805z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mf8z32bzn {
  d: path("M21.33 11.621h.836v1.082h-.836z");
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mnu548xdh {
  stop-color: var(--svg-color--2d2425, #2D2425);
}

.mp5sp9k_i {
  fill: var(--svg-color--000, #000);
  d: path("M17.83 13.622a.55.55 0 0 1 .554-.553a.55.55 0 0 1 .491.808h-.978a.5.5 0 0 1-.066-.255");
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nb4nv6byl {
  d: path("M18.313 12.861c.069.092-.075.204-.239.326s-.284.209-.353.117s.008-.266.171-.388c.164-.122.352-.147.42-.055");
}

.ncaqcbc5e {
  d: path("M19.244 13.495a.9.9 0 0 0-.25-.5l-.282.308l.127.247z");
}

.nhznusr0x {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
}

.njvu41bsf {
  d: path("M23.659 22.062v7.868h-1.634v-9.16c.578.382 1.126.816 1.634 1.292");
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
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

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
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

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.p5tw2j66v {
  stop-color: var(--svg-color--8d4e5b, #8D4E5B);
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

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q9fjvcbsc {
  d: path("M13.659 12.657a.965.965 0 0 0-.93 1.22h1.864a1 1 0 0 0 .035-.255a.97.97 0 0 0-.97-.965");
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rb96brbhl {
  d: path("M10.762 15.516a1.77 1.77 0 0 1-.978-.333v1.007a2.35 2.35 0 0 0 1.45 2.184a4.4 4.4 0 0 1-.374-1.277z");
}

.rgtt66b9m {
  d: path("M21.345 15.614q.109-1.724.2-3.452a1.741 1.741 0 0 1-.2 3.452");
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.rj0sd-b5f {
  stop-color: var(--svg-color--ff804b, #FF804B);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rmeqmu2gr {
  stop-color: var(--svg-color--9c5a69, #9C5A69);
}

.rredkdkgz {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.smwrkvbhh {
  stop-color: var(--svg-color--bb7f71, #BB7F71);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.t_7gewwjv {
  d: path("M18.384 12.657a.966.966 0 0 1 .93 1.22H17.45a.97.97 0 0 1 .935-1.22");
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.u05m3mb1z {
  stop-color: var(--svg-color--c7977f, #C7977F);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vck3ny32q {
  stop-color: var(--svg-color--743b49, #743B49);
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vsv0dabls {
  stop-color: var(--svg-color--bb7f71, #BB7F71);
}

.vxvsd1bzh {
  fill: var(--svg-color--000, #000);
  d: path("M14.211 13.622a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.491.808h.979a.55.55 0 0 0 .065-.255");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w-3g65lfw {
  cx: 13.367px;
  cy: 13.069px;
  rx: 0.421px;
  ry: 0.213px;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wgxfwnb9g {
  d: path("M27.399 29.93c-.14-.946-.34-1.882-.62-2.786a11.56 11.56 0 0 0-3.12-5.019v7.805z");
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x3o-keblz {
  d: path("m15.607 13.39l-.575 1.99c-.117.409.165.818.564.818h.85c.4 0 .68-.416.563-.818l-.574-1.99c-.124-.44-.699-.44-.828 0");
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

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.y43e-qb0b {
  stop-color: var(--svg-color--ad717a, #AD717A);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yacjacccz {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.86H9.77z");
}

.yc798xb9y {
  d: path("M14.54 13.51c0-.313-.253-.52-.322-.584l-.312.302l.192.39z");
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

.zdrlg3bmy {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
  stop-opacity: 0;
}

.zhek-5bdo {
  d: path("M10.801 17.155a4.236 4.236 0 0 0 4.204 3.685h2.04a4.236 4.236 0 0 0 4.204-3.685c.128-2.037.256-4.067.35-6.104a1.57 1.57 0 0 0-1.49-1.549h-1.516a2.62 2.62 0 0 1-2.392-1.56a.72.72 0 0 0-.666-.453h-1.377c-1.996 0-3.614 1.636-3.614 3.655c0 2.013.125 3.993.257 6.011");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
