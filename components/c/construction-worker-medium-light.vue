<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYl9Gdb)" class="rihmkq8le"/><path fill="url(#iKEcTfe)" class="rihmkq8le"/><path fill="url(#iRNOrCe)" class="f3ael5nnj"/><path fill="url(#izlspBK)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iFGqZ7b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iTFP0od)" class="pkk1wtbcw"/><path fill="url(#i0QFqKc)" class="pkk1wtbcw"/><path fill="url(#i1aP5Bc)" class="pkk1wtbcw"/><path fill="url(#i8sZbpU)" class="njvu41bsf"/><path fill="url(#ilGfS8d)" class="njvu41bsf"/><path class="cwhvcxb2p"/><path fill="url(#in3x4bd)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="bkw3kzb2o"/><path fill="url(#iwPt3uy)" class="bkw3kzb2o"/><path fill="url(#icpxGTb)" class="qq72wjb7t"/><path fill="url(#imgUjVb)" class="qq72wjb7t"/><path fill="url(#iIiLQQc)" class="ix2bq6sxv"/><path fill="url(#ii4eH6l)" class="ix2bq6sxv"/><path fill="url(#itdPJze)" class="i-ycf-bxl"/><path fill="url(#iUEIsZX)" class="i-ycf-bxl"/><path fill="url(#im5jrSc)" class="i-ycf-bxl"/><path fill="url(#i9kOXxe)" class="eoq_gfb2k"/><path fill="url(#ijMRwmd)" class="mf8z32bzn"/><path fill="url(#icEJU9b)" class="njlwwc_yu"/><path fill="url(#idBM44d)" class="j3jjd4dvk"/><path fill="url(#iFzGJnc)" class="j3jjd4dvk"/><path fill="url(#idBM44d)" class="j3jjd4dvk"/><path fill="url(#iFzGJnc)" class="j3jjd4dvk"/><g filter="url(#i2dpDFe)"><path fill="url(#iexAshb)" class="g3lriqg_w"/></g><path fill="url(#ind2BIy)" class="g3lriqg_w"/><path fill="url(#isW8eTb)" class="g3lriqg_w"/><path fill="url(#iyhGWre)" class="g3lriqg_w"/><path fill="url(#ilYEMwd)" class="g3lriqg_w"/><path fill="url(#iRJPnJb)" class="g3lriqg_w"/><path fill="url(#i5RCt9c)" class="g3lriqg_w"/><path fill="url(#iH395Jc)" class="g3lriqg_w"/><path fill="url(#iVihoje)" class="g3lriqg_w"/><path fill="url(#igZRLmr)" class="g3lriqg_w"/><g filter="url(#iLkzIZd)"><path class="zk2nbivde"/></g><g filter="url(#i3qDj4P)"><path class="ceeda_gim"/><path fill="url(#iKZ6VUj)" class="rxdmffbbk"/><path fill="url(#izsR8ld)" class="rxdmffbbk"/><path fill="url(#icZ7Yyb)" class="rxdmffbbk"/><path fill="url(#iFoGs2c)" class="rxdmffbbk"/></g><g filter="url(#iUR3qxc)"><path fill="url(#iYPjOjd)" class="lcgw7f2xl"/></g><g filter="url(#itgtbZc)"><path stroke="url(#iQUq2dd)" class="hkw_e0x6f"/></g><path fill="url(#ineAhuc)" class="irzbcmbfc"/><path class="xq18zzb3b"/><path fill="url(#iHYPszc)" class="d5uoodbfb"/><path class="wbiobrlkg"/><g filter="url(#iDCQnce)"><path class="aq968ebqc"/><path fill="url(#iDIfoPb)" class="crnq3pbte"/></g><g filter="url(#iTz9Vje)"><path fill="url(#inu1Fpc)" class="zhthombij"/></g><path class="ubh3gubgi"/><path fill="url(#iVtUAyc)" class="dzgm_qnry"/><path class="qe4auobkh"/><g filter="url(#iC2G1Kc)"><path fill="url(#iP0fLre)" class="c_-ib7xvg"/></g><g filter="url(#iyi2aVB)"><ellipse transform="rotate(-27.914 13.362 13.085)" class="x2087tpqs"/><ellipse fill="url(#i4T4usb)" transform="rotate(-27.914 13.362 13.085)" class="ynnae2bqv"/></g><path fill="url(#i58erAb)" class="ar9n_hfmf"/><path fill="url(#iWN6Otq)" class="ar9n_hfmf"/><path fill="url(#iNTpcyb)" class="ar9n_hfmf"/><path fill="url(#iCM8POb)" class="xok2u8gxe"/><path fill="url(#iSpXNcd)" class="xok2u8gxe"/><g filter="url(#iTAW8Wd)"><path class="lq2w2xq6o"/></g><g filter="url(#iD91Ubg)"><path class="uds267byw"/></g><path fill="url(#it84Uce)" class="yacjacccz"/><path fill="url(#iAvECrc)" class="yacjacccz"/><path fill="url(#iPHUYFd)" class="yacjacccz"/><path fill="url(#iXMTIBb)" class="yacjacccz"/><path fill="url(#iajAx2b)" class="yacjacccz"/><path fill="url(#iXqASBd)" class="yacjacccz"/><path fill="url(#iMLgQTb)" class="yacjacccz"/><path fill="url(#i3tCWcc)" class="yacjacccz"/><g filter="url(#iwNbi1b)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="fe6f5np8m"/><path fill="url(#iLaLawe)" class="fe6f5np8m"/><path fill="url(#iu2HU3b)" class="fe6f5np8m"/><path fill="url(#iRrXLNd)" class="fe6f5np8m"/><defs><radialGradient id="iYl9Gdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.625 6.57257 0 16.011 29.735)" gradientUnits="userSpaceOnUse"><stop class="rj0sd-b5f"/><stop offset="1" class="yrhyj2blb"/></radialGradient><radialGradient id="iKEcTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -12.5036 18.677 26.172)" gradientUnits="userSpaceOnUse"><stop class="rredkdkgz"/><stop offset="1" class="ci5tu_5bf"/></radialGradient><radialGradient id="iRNOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="izlspBK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iFGqZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="i0QFqKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.885)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="i8sZbpU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.544)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ilGfS8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.938)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="in3x4bd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.12)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="icpxGTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.89)" gradientUnits="userSpaceOnUse"><stop class="hkp0jqbkb"/><stop offset="1" class="fnpqbob3w"/></radialGradient><radialGradient id="iIiLQQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.93)" gradientUnits="userSpaceOnUse"><stop class="eluvk9b8d"/><stop offset="1" class="oymutzb3n"/></radialGradient><radialGradient id="ii4eH6l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="hsoncjbem"/><stop offset="1" class="gh3m30bhl"/></radialGradient><radialGradient id="itdPJze" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -4.86609 0 16.021 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="wrph9toqr"/><stop offset=".88" class="hu9lhi_7w"/></radialGradient><radialGradient id="iUEIsZX" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.823 15.175)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="qxkuxlbzm"/><stop offset="1" class="vs-iu_byp"/></radialGradient><radialGradient id="im5jrSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.61608 1.94033 -2.53687 -3.42038 16.693 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="ayau2esmr"/><stop offset="1" class="r4ovxnbcr"/></radialGradient><radialGradient id="icEJU9b" cx="0" cy="0" r="1" gradientTransform="rotate(99.782 4.628 16.733)scale(3.87223 4.59991)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="idBM44d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3753 2.89538 -1.31608 .62514 10.021 15.32)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iFzGJnc" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -3.325 13.872)scale(1.30314 1.14313)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iexAshb" cx="0" cy="0" r="1" gradientTransform="rotate(179.651 9.804 7.624)scale(5.12509 7.2815)" gradientUnits="userSpaceOnUse"><stop class="mn_9tvwdv"/><stop offset=".946" class="huud-kn4h"/></radialGradient><radialGradient id="isW8eTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.234 13.9953 -11.58983 -1.0219 17.718 7.793)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iyhGWre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44769 1.79152 0 18.653 12.968)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ilYEMwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06269 -1.19127 1.29639 -.06822 13.595 12.82)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iRJPnJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.30292 0 0 6.62246 10.742 14.593)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="i5RCt9c" cx="0" cy="0" r="1" gradientTransform="matrix(2.823 -3.94496 .89354 .63941 9.692 10.937)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iH395Jc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 15.275 3.014)scale(11.3615 12.5151)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iVihoje" cx="0" cy="0" r="1" gradientTransform="matrix(2.20773 .77814 -.4668 1.3244 18.125 8.368)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="izsR8ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 0 0 -.25781 16.624 15.502)" gradientUnits="userSpaceOnUse"><stop class="nh2d_e3ja"/><stop offset="1" class="gtdityyfz"/></radialGradient><radialGradient id="iQUq2dd" cx="0" cy="0" r="1" gradientTransform="matrix(.3748 -.66877 1.94617 1.09071 14.795 17.728)" gradientUnits="userSpaceOnUse"><stop class="x6cgiccjf"/><stop offset="1" class="l06tlib-h"/></radialGradient><radialGradient id="ineAhuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77813 3.13063 0 16.011 17.998)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iHYPszc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87593 -1.39327 0 18.367 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iDIfoPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25039 -.32266 .44422 -.34472 18.12 13.279)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVtUAyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87597 -1.39334 0 13.655 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4T4usb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00835 -.53343 .6412 -.01004 13.346 13.425)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWN6Otq" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.793 20.446)scale(2.5152 2.39969)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iNTpcyb" cx="0" cy="0" r="1" gradientTransform="matrix(.85052 -1.1672 .97834 .7129 21.386 13.791)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iSpXNcd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.857 6.56)scale(1.82764 1.79674)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="it84Uce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.584 6.797)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iTFP0od" x1="9.158" x2="9.158" y1="21.199" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="imgUjVb" x1="8.468" x2="7.09" y1="29.929" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nhznusr0x"/><stop offset="1" class="zdrlg3bmy"/></linearGradient><linearGradient id="i9kOXxe" x1="10.558" x2="9.521" y1="11.93" y2="11.93" gradientUnits="userSpaceOnUse"><stop class="ppy_-dzmj"/><stop offset="1" class="hz55jnp4y"/></linearGradient><linearGradient id="ijMRwmd" x1="21.396" x2="22.084" y1="11.969" y2="11.969" gradientUnits="userSpaceOnUse"><stop class="hf98upb6x"/><stop offset="1" class="xedf3mbfk"/></linearGradient><linearGradient id="ind2BIy" x1="21.579" x2="16.88" y1="15.997" y2="15.997" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="igZRLmr" x1="16.062" x2="16.062" y1="11.97" y2="13.783" gradientUnits="userSpaceOnUse"><stop class="a8_gqoe6z"/><stop offset="1" class="iw-bpebrt"/></linearGradient><linearGradient id="iKZ6VUj" x1="14.853" x2="16.013" y1="14.904" y2="14.968" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="icZ7Yyb" x1="17.024" x2="16.069" y1="14.939" y2="15.041" gradientUnits="userSpaceOnUse"><stop offset=".197" class="nh2d_e3ja"/><stop offset="1" class="gtdityyfz"/></linearGradient><linearGradient id="iFoGs2c" x1="16.011" x2="16.011" y1="15.503" y2="16.422" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iYPjOjd" x1="16.011" x2="16.011" y1="12.942" y2="14.507" gradientUnits="userSpaceOnUse"><stop class="pv56owbkr"/><stop offset="1" class="gby5whb9o"/></linearGradient><linearGradient id="inu1Fpc" x1="19.207" x2="18.868" y1="13.246" y2="13.455" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iP0fLre" x1="14.459" x2="14.12" y1="13.246" y2="13.455" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i58erAb" x1="22.96" x2="21.657" y1="13.276" y2="15.625" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iCM8POb" x1="9.695" x2="11.27" y1="14.035" y2="13.898" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iLaLawe" x1="15.587" x2="15.587" y1="9.842" y2="10.156" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iu2HU3b" x1="16.505" x2="16.505" y1="12.149" y2="10.896" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="i2dpDFe" width="11.784" height="13.325" x="10.545" y="7.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2957"/></filter><filter id="iLkzIZd" width="3.894" height="5.048" x="13.774" y="12.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".5"/></filter><filter id="i3qDj4P" width="2.227" height="3.331" x="14.898" y="12.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".05"/></filter><filter id="iUR3qxc" width="2.227" height="3.331" x="14.898" y="12.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".05"/></filter><filter id="itgtbZc" width="3.875" height="1.558" x="14.074" y="16.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".05"/></filter><filter id="iDCQnce" width=".834" height=".736" x="17.582" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".05"/></filter><filter id="iTz9Vje" width=".93" height=".954" x="18.497" y="12.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".1"/></filter><filter id="iC2G1Kc" width="1.033" height="1.091" x="13.7" y="12.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".1"/></filter><filter id="iyi2aVB" width=".97" height=".745" x="12.877" y="12.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".05"/></filter><filter id="iTAW8Wd" width="1.395" height="2.529" x="9.518" y="12.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".125"/></filter><filter id="iD91Ubg" width="1.522" height="2.555" x="21.118" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2957" stdDeviation=".125"/></filter><filter id="iwNbi1b" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2957"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2957" result="effect2_innerShadow_4002_2957"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction-worker-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.a8_gqoe6z {
  stop-color: var(--svg-color--c37c74, #C37C74);
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.aq968ebqc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.298 12.877c.069.092-.075.204-.238.326s-.284.207-.353.116c-.068-.092.008-.266.171-.388c.164-.121.352-.146.42-.054");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.ar9n_hfmf {
  d: path("M21.325 15.625c.07-1.149.14-2.296.2-3.445a1.738 1.738 0 0 1-.2 3.445");
}

.ayau2esmr {
  stop-color: var(--svg-color--ca7973, #CA7973);
  stop-opacity: 0;
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.bkw3kzb2o {
  d: path("M22.025 20.77v9.16h-1.983V19.735c.698.28 1.355.62 1.983 1.034");
}

.c_-ib7xvg {
  d: path("M14.534 13.524c0-.312-.254-.52-.322-.582l-.312.301l.192.39z");
}

.ceeda_gim {
  fill: var(--svg-color--ce9582, #CE9582);
  d: path("m15.598 13.406l-.574 1.985c-.117.408.165.816.563.816h.849c.398 0 .679-.414.562-.816l-.574-1.985c-.123-.44-.697-.44-.826 0");
}

.ci5tu_5bf {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crnq3pbte {
  d: path("M18.298 12.877c.069.092-.075.204-.238.326s-.284.207-.353.116c-.068-.092.008-.266.171-.388c.164-.121.352-.146.42-.054");
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.d5uoodbfb {
  d: path("M18.37 12.673a.964.964 0 0 1 .928 1.218h-1.862a.967.967 0 0 1 .933-1.218");
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.dzgm_qnry {
  d: path("M13.653 12.673a.964.964 0 0 0-.928 1.218h1.861a1 1 0 0 0 .035-.254a.97.97 0 0 0-.968-.964");
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eluvk9b8d {
  stop-color: var(--svg-color--ff9c5e, #FF9C5E);
}

.eoq_gfb2k {
  d: path("M9.605 11.621h.953v1.082h-.953z");
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

.fe6f5np8m {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.153a1.147 1.147 0 0 0-1.153-1.154");
}

.fnpqbob3w {
  stop-color: var(--svg-color--ce763c, #CE763C);
}

.ft5dv1b6b {
  fill: none;
}

.g3lriqg_w {
  d: path("M10.802 17.163a4.23 4.23 0 0 0 4.195 3.677h2.037a4.23 4.23 0 0 0 4.195-3.677c.127-2.034.255-4.06.35-6.092a1.565 1.565 0 0 0-1.489-1.546h-1.512a2.62 2.62 0 0 1-2.387-1.558a.72.72 0 0 0-.665-.452h-1.374c-1.993 0-3.607 1.633-3.607 3.648c0 2.01.125 3.986.257 6");
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gby5whb9o {
  stop-color: var(--svg-color--cc8c7e, #CC8C7E);
  stop-opacity: 0;
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gh3m30bhl {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.gtdityyfz {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hf98upb6x {
  stop-color: var(--svg-color--d8b079, #D8B079);
}

.hkp0jqbkb {
  stop-color: var(--svg-color--f37d42, #F37D42);
}

.hkw_e0x6f {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.011 17.304a3.24 3.24 0 0 1-1.496-.354c-.148-.075-.306.091-.213.226c.361.548.991.913 1.71.913c.717 0 1.347-.365 1.709-.913c.093-.14-.066-.301-.214-.226a3.2 3.2 0 0 1-1.496.354Z");
}

.hsoncjbem {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.hu9lhi_7w {
  stop-color: var(--svg-color--d28a8a, #D28A8A);
}

.huud-kn4h {
  stop-color: var(--svg-color--ce9582, #CE9582);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.hz55jnp4y {
  stop-color: var(--svg-color--f8c89b, #F8C89B);
}

.i-ycf-bxl {
  d: path("M13.81 20.406c.06.76.585 2.282 2.211 2.282s2.151-1.521 2.211-2.282z");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.irzbcmbfc {
  d: path("M16.011 17.304a3.24 3.24 0 0 1-1.496-.354c-.148-.075-.306.091-.213.226c.361.548.991.913 1.71.913c.717 0 1.347-.365 1.709-.913c.093-.14-.066-.301-.214-.226a3.2 3.2 0 0 1-1.496.354");
}

.iw-bpebrt {
  stop-color: var(--svg-color--c37c74, #C37C74);
  stop-opacity: 0;
}

.ix2bq6sxv {
  d: path("M27.399 29.93c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.804z");
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j3jjd4dvk {
  d: path("M10.763 15.527a1.77 1.77 0 0 1-.977-.333v1.005c0 .964.574 1.823 1.448 2.18a4.4 4.4 0 0 1-.374-1.274z");
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l06tlib-h {
  stop-color: var(--svg-color--d59f91, #D59F91);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lcgw7f2xl {
  d: path("m15.598 13.272l-.574 1.984c-.117.409.165.817.563.817h.849c.398 0 .679-.415.562-.817l-.574-1.984c-.123-.44-.697-.44-.826 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lq2w2xq6o {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.573 12.884a1.032 1.032 0 0 0 .09 2.03a84 84 0 0 1-.09-2.03");
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf8z32bzn {
  d: path("M21.33 11.621h.836v1.082h-.836z");
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mn_9tvwdv {
  stop-color: var(--svg-color--fdc19a, #FDC19A);
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

.nh2d_e3ja {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
}

.nhznusr0x {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
}

.njlwwc_yu {
  d: path("M21.26 15.527c.361-.012.7-.134.976-.333v1.005c0 .964-.574 1.823-1.448 2.18q.277-.589.374-1.274z");
}

.njvu41bsf {
  d: path("M23.659 22.062v7.868h-1.634v-9.16c.578.382 1.126.816 1.634 1.292");
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
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

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
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

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkk1wtbcw {
  d: path("M8.389 22.018a.15.15 0 0 0-.048.109v7.803h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.ppy_-dzmj {
  stop-color: var(--svg-color--e5b182, #E5B182);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.pv56owbkr {
  stop-color: var(--svg-color--cc8c7e, #CC8C7E);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qe4auobkh {
  fill: var(--svg-color--000, #000);
  d: path("M14.205 13.637a.55.55 0 0 0-.552-.552a.55.55 0 0 0-.49.806h.976a.55.55 0 0 0 .066-.254");
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
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

.qxkuxlbzm {
  stop-color: var(--svg-color--e19582, #E19582);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r4ovxnbcr {
  stop-color: var(--svg-color--ca7973, #CA7973);
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.rj0sd-b5f {
  stop-color: var(--svg-color--ff804b, #FF804B);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rredkdkgz {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.rxdmffbbk {
  d: path("m15.598 13.406l-.574 1.985c-.117.408.165.816.563.816h.849c.398 0 .679-.414.562-.816l-.574-1.985c-.123-.44-.697-.44-.826 0");
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
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

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.ubh3gubgi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.43 12.38c-.705 0-1.301.486-1.463 1.143a.296.296 0 0 0 .289.368h2.409c.153 0 .276-.14.245-.293a1.51 1.51 0 0 0-1.48-1.218");
}

.uds267byw {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.368 14.922q.063-1.027.12-2.055a1.032 1.032 0 0 1-.12 2.055");
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vs-iu_byp {
  stop-color: var(--svg-color--e19582, #E19582);
  stop-opacity: 0;
}

.wbiobrlkg {
  fill: var(--svg-color--000, #000);
  d: path("M17.817 13.637a.55.55 0 0 1 .552-.552a.55.55 0 0 1 .49.806h-.976a.5.5 0 0 1-.066-.254");
}

.wrph9toqr {
  stop-color: var(--svg-color--cc757c, #CC757C);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x2087tpqs {
  cx: 13.362px;
  cy: 13.085px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.421px;
  ry: 0.213px;
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x6cgiccjf {
  stop-color: var(--svg-color--d59f91, #D59F91);
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xedf3mbfk {
  stop-color: var(--svg-color--fbdeac, #FBDEAC);
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xok2u8gxe {
  d: path("M10.555 12.17a1.738 1.738 0 0 0 .149 3.455c-.07-1.153-.127-2.3-.15-3.455");
}

.xq18zzb3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.592 12.38c.706 0 1.301.486 1.463 1.143a.296.296 0 0 1-.289.368h-2.409a.25.25 0 0 1-.245-.294a1.51 1.51 0 0 1 1.48-1.217");
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.yacjacccz {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.86H9.77z");
}

.ynnae2bqv {
  cx: 13.362px;
  cy: 13.085px;
  rx: 0.421px;
  ry: 0.213px;
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yrhyj2blb {
  stop-color: var(--svg-color--ff8b3c, #FF8B3C);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.zdrlg3bmy {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
  stop-opacity: 0;
}

.zhthombij {
  d: path("M19.227 13.51a.9.9 0 0 0-.25-.5l-.28.308l.127.247z");
}

.zk2nbivde {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.546 13.815l-.747 1.787c-.11.408.153.817.525.817h.794c.372 0 .634-.415.525-.817l-.536-1.985c-.115-.44-.44-.242-.561.198");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

</style>
