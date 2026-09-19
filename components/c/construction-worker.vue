<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMwahQe)" class="k8ug8ebtt"/><path fill="url(#ioEMYee)" class="osull4brl"/><path fill="url(#iyf9wGc)" class="rihmkq8le"/><path fill="url(#iKEcTfe)" class="rihmkq8le"/><path fill="url(#iRNOrCe)" class="f3ael5nnj"/><path fill="url(#izlspBK)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iFGqZ7b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iH7QLPe)" class="a1zqpmsoh"/><path fill="url(#ipVLI1y)" class="a1zqpmsoh"/><path fill="url(#i1aP5Bc)" class="a1zqpmsoh"/><path fill="url(#iYuYzlb)" class="u4akr2zeg"/><path fill="url(#ibXHnbd)" class="u4akr2zeg"/><path class="cwhvcxb2p"/><path fill="url(#in3x4bd)" class="julhe_bku"/><path fill="url(#igUtr8b)" class="bkw3kzb2o"/><path fill="url(#iwPt3uy)" class="bkw3kzb2o"/><path fill="url(#icpxGTb)" class="qq72wjb7t"/><path fill="url(#imgUjVb)" class="qq72wjb7t"/><path fill="url(#iIiLQQc)" class="ix2bq6sxv"/><path fill="url(#ii4eH6l)" class="ix2bq6sxv"/><path fill="url(#ikFzlHn)" class="i-ycf-bxl"/><path fill="url(#iR8Xjfd)" class="i-ycf-bxl"/><path fill="url(#iNpvyTd)" class="i-ycf-bxl"/><path fill="url(#iHz8RNo)" class="bit7z4bda"/><path fill="url(#iR3sJJe)" class="bit7z4bda"/><path fill="url(#iOb7RSd)" class="fjnit9gkl"/><path fill="url(#ia2GiAI)" class="fjnit9gkl"/><g filter="url(#inWBC6W)"><path fill="url(#iMZC1pb)" class="qtq_3bbcs"/></g><path fill="url(#iiGiHJV)" class="qtq_3bbcs"/><path fill="url(#iqIe8Kb)" class="qtq_3bbcs"/><path fill="url(#iGwjfld)" class="qtq_3bbcs"/><path fill="url(#ixNNG8c)" class="qtq_3bbcs"/><path fill="url(#imNmArG)" class="qtq_3bbcs"/><path fill="url(#iCd5jXd)" class="qtq_3bbcs"/><g filter="url(#iZonSqd)"><path class="c9nrk6bwa"/></g><g filter="url(#iTlREOb)"><path class="pf4jvfo9k"/><path fill="url(#i7fQDpe)" class="sw9xzybis"/><path fill="url(#iU2mXee)" class="sw9xzybis"/><path fill="url(#ijoHPTc)" class="sw9xzybis"/></g><g filter="url(#i0LwJRd)"><path fill="url(#iEDfbfc)" class="uyqd-gm2n"/></g><g filter="url(#iW3ejod)"><path stroke="url(#iYmXs3u)" class="v56lp8b_e"/></g><path fill="url(#iAOLWMc)" class="mrn7eq9nn"/><path class="leq9-jbwz"/><path fill="url(#iNpg7Ke)" class="entyo_uev"/><path class="kpa2a-b3l"/><g filter="url(#iGWUafe)"><path class="sf_sezb9c"/><path fill="url(#iWJpZjF)" class="gse3qubck"/></g><g filter="url(#iJP9fPd)"><path fill="url(#i9sbdhd)" class="t2l_-cbwn"/></g><path class="in80zbcxn"/><path fill="url(#iootL7c)" class="r3wp3py3u"/><path class="x3b-gbeox"/><g filter="url(#i5UMwYj)"><path fill="url(#iEg2fZC)" class="nioglctmp"/></g><g filter="url(#ilEYTuw)"><ellipse transform="rotate(-27.914 13.265 13.07)" class="ec393m10e"/><ellipse fill="url(#ifNRgge)" transform="rotate(-27.914 13.265 13.07)" class="bakicmzva"/></g><path fill="url(#iamUiCe)" class="ae-nw_j6b"/><path fill="url(#ikqkild)" class="ae-nw_j6b"/><path fill="url(#iETP3Mc)" class="ae-nw_j6b"/><path fill="url(#il8iDdb)" class="j-c9smy2j"/><path fill="url(#imEfEwd)" class="j-c9smy2j"/><g filter="url(#i5aeYeN)"><path class="n3reafb-c"/></g><g filter="url(#idvifpd)"><path class="egpyad4lp"/></g><g filter="url(#iAAzS6c)"><ellipse class="bhyojfbed"/></g><path fill="url(#it84Uce)" class="yacjacccz"/><path fill="url(#iAvECrc)" class="yacjacccz"/><path fill="url(#iPHUYFd)" class="yacjacccz"/><path fill="url(#iXMTIBb)" class="yacjacccz"/><path fill="url(#iajAx2b)" class="yacjacccz"/><path fill="url(#iXqASBd)" class="yacjacccz"/><path fill="url(#iMLgQTb)" class="yacjacccz"/><path fill="url(#i3tCWcc)" class="yacjacccz"/><g filter="url(#iihMlDd)"><path fill="url(#i0JBewd)" class="f-z5vk62h"/><path fill="url(#iA7KXld)" class="f-z5vk62h"/><path fill="url(#iszGV9b)" class="f-z5vk62h"/><path fill="url(#i351hfc)" class="f-z5vk62h"/></g><path fill="url(#iDJTnsb)" class="iv9aw-bqp"/><path fill="url(#ihRfG7d)" class="iv9aw-bqp"/><path fill="url(#iQi1jdd)" class="iv9aw-bqp"/><path fill="url(#iRrXLNd)" class="iv9aw-bqp"/><g filter="url(#iHzoF1c)"><ellipse class="nt-_wr80m"/></g><defs><radialGradient id="iyf9wGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.625 6.57257 0 16.011 29.734)" gradientUnits="userSpaceOnUse"><stop class="rj0sd-b5f"/><stop offset="1" class="yrhyj2blb"/></radialGradient><radialGradient id="iKEcTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -12.5036 18.677 26.172)" gradientUnits="userSpaceOnUse"><stop class="rredkdkgz"/><stop offset="1" class="ci5tu_5bf"/></radialGradient><radialGradient id="iRNOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.564)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="izlspBK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.231)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iFGqZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.266)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="ipVLI1y" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.884)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="iYuYzlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.543)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ibXHnbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.937)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="in3x4bd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.12)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="icpxGTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.89)" gradientUnits="userSpaceOnUse"><stop class="hkp0jqbkb"/><stop offset="1" class="fnpqbob3w"/></radialGradient><radialGradient id="iIiLQQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.93)" gradientUnits="userSpaceOnUse"><stop class="eluvk9b8d"/><stop offset="1" class="oymutzb3n"/></radialGradient><radialGradient id="ii4eH6l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="hsoncjbem"/><stop offset="1" class="gh3m30bhl"/></radialGradient><radialGradient id="ikFzlHn" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.968 0 16.021 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="evjtz5bic"/><stop offset=".88" class="k_5oi18_f"/></radialGradient><radialGradient id="iR8Xjfd" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.823 15.175)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="trtw9eqsx"/><stop offset="1" class="n5hwk-_ts"/></radialGradient><radialGradient id="iNpvyTd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64062 1.4375 -2.5012 -4.5946 16.693 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="x__bgvnia"/><stop offset="1" class="d_rzkbbzn"/></radialGradient><radialGradient id="iHz8RNo" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 4.94 16.283)scale(4.1421 4.9205)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iR3sJJe" cx="0" cy="0" r="1" gradientTransform="matrix(.31731 .43517 -.36968 .26956 21.113 15.473)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iOb7RSd" cx="0" cy="0" r="1" gradientTransform="rotate(71.234 -5.727 14.576)scale(4.48261 2.03755)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="ia2GiAI" cx="0" cy="0" r="1" gradientTransform="matrix(.3445 1.07886 -.94638 .3022 10.633 15.3)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iMZC1pb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.93464 0 0 -7.89855 18.956 14.164)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="xemglgbde"/><stop offset="1" class="cv4o6x_2x"/></radialGradient><radialGradient id="iiGiHJV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.66272 14.2484 0 15.709 21.018)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iqIe8Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.43548 6.60094 -2.42677 -.1601 21.497 13.914)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iGwjfld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.52949 1.84142 0 13.656 12.887)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="ixNNG8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.66079 2.1541 0 18.61 12.442)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="imNmArG" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.40625 -11.2188 0 15.709 12.235)" gradientUnits="userSpaceOnUse"><stop class="dnm8hk9wr"/><stop offset="1" class="ui0z4ebky"/></radialGradient><radialGradient id="iCd5jXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.6875 -14.5246 0 15.97 12.516)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="mss9knzet"/><stop offset="1" class="dzulvctvh"/></radialGradient><radialGradient id="iU2mXee" cx="0" cy="0" r="1" gradientTransform="rotate(-99.998 14.861 .696)scale(3.45877 1.35106)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="posyr3b3x"/><stop offset="1" class="z9mmonbrn"/></radialGradient><radialGradient id="iYmXs3u" cx="0" cy="0" r="1" gradientTransform="matrix(.37555 -.6701 1.95003 1.09287 14.7 17.722)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iAOLWMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77968 3.13684 0 15.918 17.993)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iNpg7Ke" cx="0" cy="0" r="1" gradientTransform="rotate(-90 16.078 -2.2)scale(1.21996)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="p2mda1olw"/><stop offset="1" class="jwfq5tbke"/></radialGradient><radialGradient id="iWJpZjF" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.265 2.216)scale(.41014 .56467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iootL7c" cx="0" cy="0" r="1" gradientTransform="rotate(-90 13.717 .16)scale(1.22002)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="p2mda1olw"/><stop offset="1" class="jwfq5tbke"/></radialGradient><radialGradient id="ifNRgge" cx="0" cy="0" r="1" gradientTransform="matrix(-.00839 -.53569 .64392 -.01008 13.25 13.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikqkild" cx="0" cy="0" r="1" gradientTransform="matrix(.67995 2.42673 -2.31528 .64873 20.914 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iETP3Mc" cx="0" cy="0" r="1" gradientTransform="matrix(.8522 -1.16952 .9803 .71432 21.304 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="imEfEwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.44664 2.2458 -2.20783 -.43908 10.225 13.37)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="it84Uce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.584 6.797)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iMwahQe" x1="10.441" x2="9.531" y1="12.164" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="q0_zbabeh"/><stop offset="1" class="qtrqcsbac"/></linearGradient><linearGradient id="ioEMYee" x1="21.396" x2="22.084" y1="12.203" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="ynmkrlb7n"/><stop offset="1" class="zsz6wjbfy"/></linearGradient><linearGradient id="iH7QLPe" x1="9.158" x2="9.158" y1="21.199" y2="29.929" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="igUtr8b" x1="21.034" x2="21.034" y1="19.735" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="imgUjVb" x1="8.468" x2="7.09" y1="29.929" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nhznusr0x"/><stop offset="1" class="zdrlg3bmy"/></linearGradient><linearGradient id="i7fQDpe" x1="14.758" x2="15.92" y1="14.892" y2="14.956" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ijoHPTc" x1="15.918" x2="15.918" y1="15.492" y2="16.413" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iEDfbfc" x1="15.918" x2="16.155" y1="12.869" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="ophd9gb5u"/><stop offset="1" class="w9x1r56ae"/></linearGradient><linearGradient id="i9sbdhd" x1="19.122" x2="18.781" y1="13.232" y2="13.441" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEg2fZC" x1="14.364" x2="14.024" y1="13.232" y2="13.442" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iamUiCe" x1="22.881" x2="21.576" y1="13.261" y2="15.615" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="il8iDdb" x1="9.59" x2="11.168" y1="14.022" y2="13.884" gradientUnits="userSpaceOnUse"><stop class="f7p1si-tf"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="ihRfG7d" x1="15.587" x2="15.587" y1="9.842" y2="10.155" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iQi1jdd" x1="16.505" x2="16.505" y1="12.148" y2="10.895" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="inWBC6W" width="11.556" height="13.551" x="10.441" y="7.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2945"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2945" result="effect2_innerShadow_4002_2945"/></filter><filter id="iZonSqd" width="4.031" height="5.137" x="13.679" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".5"/></filter><filter id="iTlREOb" width="2.231" height="3.337" x="14.803" y="12.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".05"/></filter><filter id="i0LwJRd" width="2.231" height="3.337" x="14.803" y="12.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".05"/></filter><filter id="iW3ejod" width="3.982" height="1.661" x="13.928" y="16.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".05"/></filter><filter id="iGWUafe" width=".836" height=".738" x="17.493" y="12.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".05"/></filter><filter id="iJP9fPd" width=".933" height=".957" x="18.41" y="12.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".1"/></filter><filter id="i5UMwYj" width="1.036" height="1.094" x="13.604" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".1"/></filter><filter id="ilEYTuw" width=".973" height=".747" x="12.779" y="12.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".05"/></filter><filter id="i5aeYeN" width="1.397" height="2.533" x="9.413" y="12.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".125"/></filter><filter id="idvifpd" width="1.524" height="2.559" x="21.036" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".125"/></filter><filter id="iAAzS6c" width="8.369" height="2.215" x="15.115" y="9.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".375"/></filter><filter id="iihMlDd" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2945"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2945" result="effect2_innerShadow_4002_2945"/></filter><filter id="iHzoF1c" width="7.654" height="2.528" x="15.502" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2945" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction-worker" /></template>
<style>
.a1zqpmsoh {
  d: path("M8.389 22.017a.15.15 0 0 0-.048.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ae-nw_j6b {
  d: path("M21.243 15.615c.07-1.151.14-2.301.2-3.452a1.741 1.741 0 0 1-.2 3.452");
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bakicmzva {
  cx: 13.265px;
  cy: 13.069px;
  rx: 0.422px;
  ry: 0.214px;
}

.bhyojfbed {
  cx: 19.299px;
  cy: 10.856px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 3.435px;
  ry: 0.358px;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bit7z4bda {
  d: path("M21.177 15.516c.363-.011.703-.134.979-.333v1.007a2.35 2.35 0 0 1-1.45 2.184q.277-.59.373-1.277z");
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkw3kzb2o {
  d: path("M22.025 20.77v9.16h-1.983V19.735c.698.28 1.355.62 1.983 1.034");
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c9nrk6bwa {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.393 13.603l-.687 1.989c-.118.409.164.818.563.818h.85c.4 0 .681-.416.564-.818l-.575-1.99c-.123-.44-.586-.44-.715 0");
}

.ci5tu_5bf {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv4o6x_2x {
  stop-color: var(--svg-color--f5a02b, #F5A02B);
}

.cwhvcxb2p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.d_rzkbbzn {
  stop-color: var(--svg-color--d87934, #D87934);
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dnm8hk9wr {
  stop-color: var(--svg-color--f38e22, #F38E22);
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dzulvctvh {
  stop-color: var(--svg-color--f77a61, #F77A61);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.ec393m10e {
  cx: 13.265px;
  cy: 13.069px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.422px;
  ry: 0.214px;
}

.egpyad4lp {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.286 14.91q.063-1.029.12-2.058a1.034 1.034 0 0 1-.12 2.059");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.eluvk9b8d {
  stop-color: var(--svg-color--ff9c5e, #FF9C5E);
}

.entyo_uev {
  d: path("M18.281 12.657a.966.966 0 0 1 .93 1.22h-1.865a.97.97 0 0 1 .935-1.22");
}

.evjtz5bic {
  stop-color: var(--svg-color--f7803a, #F7803A);
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

.f7p1si-tf {
  stop-color: var(--svg-color--e58f2c, #E58F2C);
}

.fjnit9gkl {
  d: path("M10.66 15.516a1.77 1.77 0 0 1-.98-.333v1.007a2.35 2.35 0 0 0 1.451 2.184a4.4 4.4 0 0 1-.374-1.277z");
}

.fnpqbob3w {
  stop-color: var(--svg-color--ce763c, #CE763C);
}

.ft5dv1b6b {
  fill: none;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gh3m30bhl {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
  stop-opacity: 0;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gse3qubck {
  d: path("M18.212 12.86c.069.093-.075.205-.24.328c-.163.122-.285.208-.354.116s.008-.266.172-.389c.164-.122.353-.147.422-.054");
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
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

.i-ycf-bxl {
  d: path("M13.81 20.406c.06.76.585 2.282 2.211 2.282s2.151-1.521 2.211-2.282z");
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

.in80zbcxn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.332 12.363a1.51 1.51 0 0 0-1.466 1.145a.297.297 0 0 0 .29.369h2.413c.154 0 .277-.14.246-.294a1.516 1.516 0 0 0-1.483-1.22");
}

.iv9aw-bqp {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.306h12.594c.642 0 1.153-.52 1.153-1.153a1.147 1.147 0 0 0-1.153-1.153");
}

.ix2bq6sxv {
  d: path("M27.399 29.93c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.804z");
}

.j-c9smy2j {
  d: path("M10.451 12.153a1.741 1.741 0 0 0 .15 3.462a84 84 0 0 1-.15-3.462");
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.julhe_bku {
  d: path("M9.975 20.77v9.16h1.983V19.735c-.698.28-1.355.62-1.983 1.034");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.jwfq5tbke {
  stop-color: var(--svg-color--604038, #604038);
}

.k_5oi18_f {
  stop-color: var(--svg-color--ffa040, #FFA040);
}

.k8ug8ebtt {
  d: path("M9.605 11.855h.836v1.082h-.836z");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kpa2a-b3l {
  fill: var(--svg-color--000, #000);
  d: path("M17.728 13.622a.55.55 0 0 1 .553-.553a.55.55 0 0 1 .492.808h-.979a.5.5 0 0 1-.066-.255");
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.leq9-jbwz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.505 12.363c.707 0 1.303.487 1.466 1.145a.297.297 0 0 1-.29.369h-2.413a.25.25 0 0 1-.246-.294a1.51 1.51 0 0 1 1.483-1.22");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mrn7eq9nn {
  d: path("M15.918 17.298a3.25 3.25 0 0 1-1.498-.355c-.149-.076-.308.091-.214.226c.362.549.993.915 1.712.915c.72 0 1.35-.366 1.713-.915c.093-.14-.066-.302-.214-.227a3.2 3.2 0 0 1-1.499.356");
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mss9knzet {
  stop-color: var(--svg-color--f77a61, #F77A61);
  stop-opacity: 0;
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n3reafb-c {
  fill: var(--svg-color--e08126, #E08126);
  d: path("M10.47 12.869a1.034 1.034 0 0 0 .09 2.033a84 84 0 0 1-.09-2.033");
}

.n5hwk-_ts {
  stop-color: var(--svg-color--ffb32d, #FFB32D);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nhznusr0x {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nioglctmp {
  d: path("M14.44 13.51c0-.312-.255-.52-.324-.584l-.312.303l.192.391z");
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

.ophd9gb5u {
  stop-color: var(--svg-color--f6a328, #F6A328);
}

.osull4brl {
  d: path("M21.33 11.855h.836v1.082h-.836z");
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

.p2mda1olw {
  stop-color: var(--svg-color--805250, #805250);
}

.pf4jvfo9k {
  fill: var(--svg-color--ffb120, #FFB120);
  d: path("m15.505 13.39l-.575 1.99c-.117.409.164.818.563.818h.85c.4 0 .681-.416.564-.818l-.575-1.99c-.123-.44-.698-.44-.827 0");
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.posyr3b3x {
  stop-color: var(--svg-color--ffdc43, #FFDC43);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q0_zbabeh {
  stop-color: var(--svg-color--d18235, #D18235);
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

.qtq_3bbcs {
  d: path("M10.699 17.155a4.236 4.236 0 0 0 4.203 3.685h2.041a4.236 4.236 0 0 0 4.204-3.685c.127-2.037.256-4.067.35-6.104a1.57 1.57 0 0 0-1.491-1.549H18.49a2.62 2.62 0 0 1-2.393-1.56a.72.72 0 0 0-.665-.453h-1.377c-1.997 0-3.615 1.636-3.615 3.655c0 2.013.126 3.993.258 6.011");
}

.qtrqcsbac {
  stop-color: var(--svg-color--d2923f, #D2923F);
}

.r3wp3py3u {
  d: path("M13.556 12.657a.966.966 0 0 0-.93 1.22h1.865a1 1 0 0 0 .035-.255a.97.97 0 0 0-.97-.965");
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
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

.sf_sezb9c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.212 12.86c.069.093-.075.205-.24.328c-.163.122-.285.208-.354.116s.008-.266.172-.389c.164-.122.353-.147.422-.054");
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.sw9xzybis {
  d: path("m15.505 13.39l-.575 1.99c-.117.409.164.818.563.818h.85c.4 0 .681-.416.564-.818l-.575-1.99c-.123-.44-.698-.44-.827 0");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t2l_-cbwn {
  d: path("M19.142 13.496a.9.9 0 0 0-.25-.501l-.282.309l.127.247z");
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.trtw9eqsx {
  stop-color: var(--svg-color--ffb32d, #FFB32D);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u4akr2zeg {
  d: path("M23.659 22.061v7.868h-1.634v-9.16c.578.383 1.126.817 1.634 1.292");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.ui0z4ebky {
  stop-color: var(--svg-color--f38e22, #F38E22);
  stop-opacity: 0;
}

.uyqd-gm2n {
  d: path("m15.505 13.2l-.575 1.988c-.117.409.164.818.563.818h.85c.4 0 .681-.415.564-.818l-.575-1.989c-.123-.44-.698-.44-.827 0");
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v56lp8b_e {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.454 16.876c.423.22.927.347 1.464.347a3.16 3.16 0 0 0 1.464-.347h.001a.24.24 0 0 1 .286.047c.068.07.093.184.025.287m-3.24-.334l3.177.293m-3.177-.293a.24.24 0 0 0-.286.05a.22.22 0 0 0-.025.285m.311-.335l-.248.293m3.488.041l-.063-.041m.063.041l-.063-.041m.063.041c-.376.57-1.03.949-1.776.949c-.744 0-1.399-.38-1.775-.948m3.488-.042c-.362.549-.994.915-1.713.915s-1.35-.366-1.712-.915m-.063.042l.063-.042m-.063.042v-.001l.063-.041");
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w9x1r56ae {
  stop-color: var(--svg-color--f6a328, #F6A328);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x__bgvnia {
  stop-color: var(--svg-color--f78b29, #F78B29);
  stop-opacity: 0;
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x3b-gbeox {
  fill: var(--svg-color--000, #000);
  d: path("M14.109 13.622a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.492.808h.979a.55.55 0 0 0 .066-.255");
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xemglgbde {
  stop-color: var(--svg-color--ffe233, #FFE233);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
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

.yacjacccz {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.86H9.77z");
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.ynmkrlb7n {
  stop-color: var(--svg-color--c88129, #C88129);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yrhyj2blb {
  stop-color: var(--svg-color--ff8b3c, #FF8B3C);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z9mmonbrn {
  stop-color: var(--svg-color--ffdc43, #FFDC43);
  stop-opacity: 0;
}

.zdrlg3bmy {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
  stop-opacity: 0;
}

.zsz6wjbfy {
  stop-color: var(--svg-color--ffc036, #FFC036);
}

</style>
