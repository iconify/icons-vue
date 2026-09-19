<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iE9FFab)" class="i-dm14m_a"/><path fill="url(#iI1mSLC)" class="osull4brl"/><path fill="url(#iyf9wGc)" class="rihmkq8le"/><path fill="url(#iKEcTfe)" class="rihmkq8le"/><path fill="url(#iBN2qLb)" class="f3ael5nnj"/><path fill="url(#inKc7Tb)" class="f3ael5nnj"/><path fill="url(#i3kJV0d)" class="f3ael5nnj"/><path fill="url(#iM0Lg2b)" class="aja9ggbky"/><path fill="url(#intQq8b)" class="aja9ggbky"/><path fill="url(#iTFP0od)" class="b3numobjj"/><path fill="url(#ipVLI1y)" class="b3numobjj"/><path fill="url(#i1aP5Bc)" class="b3numobjj"/><path fill="url(#i8sZbpU)" class="njvu41bsf"/><path fill="url(#ilGfS8d)" class="njvu41bsf"/><path class="kebk6vb7p"/><path fill="url(#iJiYnAD)" class="b-jd-2l9s"/><path fill="url(#izLDsQc)" class="vse2rygyc"/><path fill="url(#iwPt3uy)" class="vse2rygyc"/><path fill="url(#icpxGTb)" class="rzlaa0gmj"/><path fill="url(#iNY8xOd)" class="rzlaa0gmj"/><path fill="url(#iIiLQQc)" class="yfsg16eua"/><path fill="url(#ii4eH6l)" class="yfsg16eua"/><path fill="url(#imWK7Pe)" class="kyehk2bgv"/><path fill="url(#iG14Dib)" class="kyehk2bgv"/><path fill="url(#iHbjNsc)" class="kyehk2bgv"/><g filter="url(#iBfKt0d)"><ellipse class="bhyojfbed"/></g><g filter="url(#iFDV85d)"><ellipse class="nt-_wr80m"/></g><path fill="url(#iNpDUKe)" class="fkobv194j"/><path fill="url(#iO6qIge)" class="zf1kpzbqc"/><g filter="url(#ijvTsDd)"><path fill="url(#i3HV6Ne)" class="x4wtvpeua"/><path fill="url(#iLjXzld)" class="x4wtvpeua"/></g><path fill="url(#iVn67Md)" class="x4wtvpeua"/><path fill="url(#i5pzlDB)" class="x4wtvpeua"/><path fill="url(#iwMVeHc)" class="x4wtvpeua"/><path fill="url(#inVpi8c)" class="x4wtvpeua"/><path fill="url(#iYQjJyb)" class="x4wtvpeua"/><path fill="url(#iQ1Wdde)" class="x4wtvpeua"/><path fill="url(#iYmEyOd)" class="x4wtvpeua"/><path fill="url(#iNHfmKd)" class="x4wtvpeua"/><g filter="url(#iYO4wPb)"><path class="z1m_06brq"/></g><g filter="url(#iYJAdFy)"><path class="en970la8y"/><path fill="url(#ifweIcd)" class="zm3fyksng"/><path fill="url(#i1Xq5vp)" class="zm3fyksng"/><path fill="url(#iG2EiNe)" class="zm3fyksng"/><path fill="url(#iSfseDe)" class="zm3fyksng"/></g><g filter="url(#ihFhmle)"><path fill="url(#iukaMHd)" class="tr7_h_b0z"/></g><g filter="url(#io8p69g)"><path stroke="url(#iJg9Aod)" class="tws1sccvb"/></g><path fill="url(#iDbgQId)" class="o74308uug"/><path class="uwbp-acze"/><path fill="url(#iJCrZ2c)" class="xwhta25pw"/><path class="j601opbui"/><g filter="url(#ilwmnrG)"><path class="m1n91cyjq"/><path fill="url(#iLiLcoc)" class="gwosjacqh"/></g><g filter="url(#iGITHRb)"><path fill="url(#iBFc2Sb)" class="i2yoo88ek"/></g><path class="vdo1-b9pv"/><path fill="url(#iulVPkQ)" class="occfzzbbh"/><path class="a0xerbckg"/><g filter="url(#i772uVj)"><path fill="url(#iTyivoc)" class="l29vsqf5g"/></g><g filter="url(#iDkeyQi)"><ellipse transform="rotate(-27.914 13.315 13.07)" class="nf04obcjm"/><ellipse fill="url(#iXBrfXu)" transform="rotate(-27.914 13.315 13.07)" class="u-8uslbqd"/></g><path fill="url(#iRQ6LmD)" class="okwcqabci"/><path fill="url(#ieM83Fe)" class="okwcqabci"/><path fill="url(#i0iby3b)" class="okwcqabci"/><path fill="url(#iJm2l5c)" class="okwcqabci"/><path fill="url(#i1mOUtc)" class="gltzj84dy"/><path fill="url(#iotDfab)" class="gltzj84dy"/><g filter="url(#i3tkIve)"><path fill="url(#iwMkbAs)" class="ekzu1hbou"/></g><g filter="url(#ilNMlDd)"><path fill="url(#isCJ4jb)" class="cgy6jzbzi"/></g><path fill="url(#it84Uce)" class="khi3h3kra"/><path fill="url(#iAvECrc)" class="khi3h3kra"/><path fill="url(#iPHUYFd)" class="khi3h3kra"/><path fill="url(#iXMTIBb)" class="khi3h3kra"/><path fill="url(#iajAx2b)" class="khi3h3kra"/><path fill="url(#iXqASBd)" class="khi3h3kra"/><path fill="url(#iMLgQTb)" class="khi3h3kra"/><path fill="url(#i3tCWcc)" class="khi3h3kra"/><g filter="url(#iYjqnCp)"><path fill="url(#i0JBewd)" class="fl8cmpb7i"/><path fill="url(#iA7KXld)" class="fl8cmpb7i"/><path fill="url(#iszGV9b)" class="fl8cmpb7i"/><path fill="url(#i351hfc)" class="fl8cmpb7i"/></g><path fill="url(#iDJTnsb)" class="x9nrh1bge"/><path fill="url(#iLaLawe)" class="x9nrh1bge"/><path fill="url(#iu2HU3b)" class="x9nrh1bge"/><path fill="url(#iRrXLNd)" class="x9nrh1bge"/><defs><radialGradient id="iyf9wGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.625 6.57257 0 16.011 29.734)" gradientUnits="userSpaceOnUse"><stop class="rj0sd-b5f"/><stop offset="1" class="yrhyj2blb"/></radialGradient><radialGradient id="iKEcTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -12.5036 18.677 26.172)" gradientUnits="userSpaceOnUse"><stop class="rredkdkgz"/><stop offset="1" class="ci5tu_5bf"/></radialGradient><radialGradient id="iBN2qLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.563)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="inKc7Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.23)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="i3kJV0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.037)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="iM0Lg2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.265)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="intQq8b" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.384)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="ipVLI1y" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.884)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="i1aP5Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="i8sZbpU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.544)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="ilGfS8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.938)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="iJiYnAD" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.473 10.121)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iwPt3uy" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.36)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="icpxGTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.89)" gradientUnits="userSpaceOnUse"><stop class="hkp0jqbkb"/><stop offset="1" class="fnpqbob3w"/></radialGradient><radialGradient id="iIiLQQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.93)" gradientUnits="userSpaceOnUse"><stop class="eluvk9b8d"/><stop offset="1" class="oymutzb3n"/></radialGradient><radialGradient id="ii4eH6l" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.93)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="hsoncjbem"/><stop offset="1" class="gh3m30bhl"/></radialGradient><radialGradient id="imWK7Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.968 0 16.021 20.687)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="m1krp90gd"/><stop offset=".88" class="axk9i_bqi"/></radialGradient><radialGradient id="iG14Dib" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.823 15.174)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="gkq-c9gry"/><stop offset="1" class="f77kqjbon"/></radialGradient><radialGradient id="iHbjNsc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64062 1.4375 -2.5012 -4.5946 16.693 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="hhsev0bnv"/><stop offset="1" class="vck3ny32q"/></radialGradient><radialGradient id="iNpDUKe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.355 22.763)scale(2.33001 2.76788)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iO6qIge" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -46.492 38.543)scale(1.67423 5.1651)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="i3HV6Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65537 0 0 -10.0043 19.006 14.164)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iLjXzld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8857 3.1187 -2.57475 -1.5568 18.595 8.778)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i5pzlDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.77325 27.0491 0 15.95 21.639)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ndsnw2bud"/><stop offset=".429" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iwMVeHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24226 1.53729 0 18.616 12.744)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="inVpi8c" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.16 -.368)scale(1.18377 1.28822)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iYQjJyb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19076 .58017 -1.48203 -23.47777 19.683 15.233)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iQ1Wdde" cx="0" cy="0" r="1" gradientTransform="matrix(3.66266 -3.15497 .93192 1.08189 8.622 11.207)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iYmEyOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25385 2.70167 -1.07997 -.10147 21.967 11.008)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iNHfmKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.12915 -6.70875 0 16.02 12.035)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="tpp8-4lcr"/><stop offset="1" class="cpspdbz7z"/></radialGradient><radialGradient id="i1Xq5vp" cx="0" cy="0" r="1" gradientTransform="matrix(0 .26407 -.8299 0 16.475 15.635)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iSfseDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64554 .75446 -1.21248 -2.64451 16.6 15.02)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iDbgQId" cx="0" cy="0" r="1" gradientTransform="matrix(2.36042 -1.16045 4.66879 9.4966 15.438 18.084)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iJCrZ2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87767 -1.39603 0 18.33 13.173)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iLiLcoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25088 -.3233 .4451 -.3454 18.083 13.264)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iulVPkQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87771 -1.3961 0 13.609 13.173)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iXBrfXu" cx="0" cy="0" r="1" gradientTransform="matrix(-.00837 -.53449 .64248 -.01006 13.299 13.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieM83Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.67995 2.42672 -2.31528 .64873 20.965 13.188)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="i0iby3b" cx="0" cy="0" r="1" gradientTransform="matrix(.8522 -1.16952 .98028 .71431 21.354 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iJm2l5c" cx="0" cy="0" r="1" gradientTransform="matrix(.635 -1.6772 2.24098 .84845 21.478 13.964)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iotDfab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79386 0 0 -2.0031 10.652 13.882)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iwMkbAs" cx="0" cy="0" r="1" gradientTransform="matrix(-.99143 .17018 -.17449 -1.01652 10.653 13.884)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="it84Uce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.584 6.797)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="iAvECrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.834 9.86)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="iPHUYFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.24 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iXMTIBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.177 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="iajAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.302 2.703)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXqASBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.74 9.703)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="i3tCWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.959 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iszGV9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.459 9.86)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="i351hfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.334 9.922)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iRrXLNd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.697 8.935)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="iE9FFab" x1="10.558" x2="9.521" y1="12.164" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="ymyjruwrb"/><stop offset="1" class="osvrbmbgh"/></linearGradient><linearGradient id="iI1mSLC" x1="21.396" x2="22.084" y1="12.203" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="mnu548xdh"/><stop offset="1" class="igfnq7b1m"/></linearGradient><linearGradient id="iTFP0od" x1="9.158" x2="9.158" y1="21.199" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="izLDsQc" x1="21.034" x2="21.034" y1="19.736" y2="29.93" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="iNY8xOd" x1="8.468" x2="7.09" y1="29.93" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nhznusr0x"/><stop offset="1" class="zdrlg3bmy"/></linearGradient><linearGradient id="iVn67Md" x1="21.548" x2="18.812" y1="15.987" y2="15.987" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ifweIcd" x1="16.985" x2="15.969" y1="14.847" y2="14.931" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iG2EiNe" x1="15.969" x2="15.969" y1="16.126" y2="15.623" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iukaMHd" x1="15.969" x2="15.969" y1="12.926" y2="14.495" gradientUnits="userSpaceOnUse"><stop class="le1d5jtzd"/><stop offset="1" class="ee6wt0otk"/></linearGradient><linearGradient id="iJg9Aod" x1="14.669" x2="15.014" y1="17.826" y2="16.923" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iBFc2Sb" x1="19.171" x2="18.832" y1="13.231" y2="13.441" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTyivoc" x1="14.414" x2="14.074" y1="13.231" y2="13.44" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRQ6LmD" x1="22.932" x2="21.626" y1="13.26" y2="15.615" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i1mOUtc" x1="9.641" x2="11.219" y1="14.022" y2="13.884" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="isCJ4jb" x1="21.828" x2="21.828" y1="12.847" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iMLgQTb" x1="9.771" x2="10.584" y1="9.234" y2="9.234" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="i0JBewd" x1="15.81" x2="15.81" y1="2.07" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="iA7KXld" x1="15.81" x2="15.81" y1="2.07" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iDJTnsb" x1="21.786" x2="5.158" y1="11.243" y2="11.243" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iLaLawe" x1="15.587" x2="15.587" y1="9.842" y2="10.156" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iu2HU3b" x1="16.505" x2="16.505" y1="12.149" y2="10.896" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="iBfKt0d" width="8.369" height="2.215" x="15.115" y="9.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".375"/></filter><filter id="iFDV85d" width="7.654" height="2.528" x="15.502" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".5"/></filter><filter id="ijvTsDd" width="12.056" height="13.551" x="10.492" y="7.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2951"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2951" result="effect2_innerShadow_4002_2951"/></filter><filter id="iYO4wPb" width="3.89" height="5.137" x="13.871" y="12.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".5"/></filter><filter id="iYJAdFy" width="2.431" height="3.537" x="14.754" y="12.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".1"/></filter><filter id="ihFhmle" width="2.431" height="3.537" x="14.754" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".1"/></filter><filter id="io8p69g" width="3.882" height="1.561" x="14.028" y="16.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".05"/></filter><filter id="ilwmnrG" width=".835" height=".737" x="17.544" y="12.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".05"/></filter><filter id="iGITHRb" width=".931" height=".955" x="18.46" y="12.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".1"/></filter><filter id="i772uVj" width="1.034" height="1.093" x="13.654" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".1"/></filter><filter id="iDkeyQi" width=".971" height=".746" x="12.83" y="12.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".05"/></filter><filter id="i3tkIve" width="1.397" height="2.533" x="9.412" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".125"/></filter><filter id="ilNMlDd" width="2.024" height="3.059" x="20.816" y="12.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2951" stdDeviation=".25"/></filter><filter id="iYjqnCp" width="5.791" height="8.428" x="12.915" y="2.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2951"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2951" result="effect2_innerShadow_4002_2951"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction-worker-medium-dark" /></template>
<style>
.a0xerbckg {
  fill: var(--svg-color--000, #000);
  d: path("M14.16 13.623a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.492.807h.979a.55.55 0 0 0 .065-.255");
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aja9ggbky {
  d: path("M18.279 19.198c.608.134 1.195.31 1.763.537V29.93H18.28z");
}

.axk9i_bqi {
  stop-color: var(--svg-color--7e4655, #7E4655);
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b-jd-2l9s {
  d: path("M9.975 20.77v9.16h1.983V19.736c-.698.279-1.355.62-1.983 1.034");
}

.b3numobjj {
  d: path("M8.389 22.017a.15.15 0 0 0-.048.11v7.803h1.634v-9.16c-.56.37-1.092.79-1.586 1.247");
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

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cgy6jzbzi {
  d: path("M21.316 14.906q.063-1.029.12-2.059a1.034 1.034 0 0 1-.12 2.06");
}

.ci5tu_5bf {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpspdbz7z {
  stop-color: var(--svg-color--79454d, #79454D);
  stop-opacity: 0;
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
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

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.ee6wt0otk {
  stop-color: var(--svg-color--7c4a50, #7C4A50);
  stop-opacity: 0;
}

.ekzu1hbou {
  d: path("M10.468 12.867a1.034 1.034 0 0 0 .09 2.033a84 84 0 0 1-.09-2.033");
}

.eluvk9b8d {
  stop-color: var(--svg-color--ff9c5e, #FF9C5E);
}

.en970la8y {
  fill: var(--svg-color--7b5050, #7B5050);
  d: path("m15.556 13.39l-.575 1.99c-.118.408.164.818.563.818h.85c.4 0 .681-.416.564-.819l-.575-1.988c-.123-.44-.698-.44-.827 0");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f3ael5nnj {
  d: path("M13.721 19.198c-.608.134-1.196.31-1.763.537V29.93h1.763z");
}

.f77kqjbon {
  stop-color: var(--svg-color--8a5756, #8A5756);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fkobv194j {
  d: path("M21.228 15.516c.363-.012.702-.134.979-.334v1.007a2.35 2.35 0 0 1-1.451 2.185q.277-.59.374-1.277z");
}

.fl8cmpb7i {
  d: path("M14.615 2.07h2.39c.829 0 1.5.603 1.5 1.632v6.796h-5.39V3.702c0-1.03.671-1.632 1.5-1.632");
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

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gh3m30bhl {
  stop-color: var(--svg-color--ee6a13, #EE6A13);
  stop-opacity: 0;
}

.gkq-c9gry {
  stop-color: var(--svg-color--8a5756, #8A5756);
}

.gltzj84dy {
  d: path("M10.512 12.148c-.845.12-1.505.85-1.505 1.729c0 .93.728 1.688 1.645 1.738a85 85 0 0 1-.14-3.467");
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.gwosjacqh {
  d: path("M18.26 12.86c.07.093-.074.205-.238.327s-.284.209-.353.117c-.069-.093.008-.266.171-.388c.164-.123.352-.147.42-.055");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hhsev0bnv {
  stop-color: var(--svg-color--743b49, #743B49);
  stop-opacity: 0;
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
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

.i2yoo88ek {
  d: path("M19.192 13.495a.9.9 0 0 0-.25-.5l-.282.308l.127.247z");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.igfnq7b1m {
  stop-color: var(--svg-color--4f4c4d, #4F4C4D);
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j601opbui {
  fill: var(--svg-color--000, #000);
  d: path("M17.78 13.623a.55.55 0 0 1 .552-.553a.55.55 0 0 1 .491.807h-.978a.5.5 0 0 1-.066-.255");
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.kebk6vb7p {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.77v9.16h1.983V19.736c-.698.279-1.355.62-1.983 1.034");
}

.khi3h3kra {
  d: path("M9.771 7.178a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1v2.681H9.77z");
}

.kyehk2bgv {
  d: path("M13.81 20.406c.06.76.585 2.281 2.211 2.281s2.151-1.52 2.211-2.281z");
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l29vsqf5g {
  d: path("M14.489 13.509c0-.312-.254-.52-.323-.583l-.312.302l.192.39z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.le1d5jtzd {
  stop-color: var(--svg-color--7c4a50, #7C4A50);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m1krp90gd {
  stop-color: var(--svg-color--793a4b, #793A4B);
}

.m1n91cyjq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.26 12.86c.07.093-.074.205-.238.327s-.284.209-.353.117c-.069-.093.008-.266.171-.388c.164-.123.352-.147.42-.055");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
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

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ndsnw2bud {
  stop-color: var(--svg-color--8b4363, #8B4363);
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

.njvu41bsf {
  d: path("M23.659 22.062v7.868h-1.634v-9.16c.578.382 1.126.816 1.634 1.292");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
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

.o74308uug {
  d: path("M15.97 17.298a3.25 3.25 0 0 1-1.5-.356c-.148-.075-.307.092-.214.226c.363.55.994.916 1.713.916s1.35-.366 1.713-.916c.093-.14-.066-.301-.214-.226a3.2 3.2 0 0 1-1.499.356");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.occfzzbbh {
  d: path("M13.607 12.657a.965.965 0 0 0-.93 1.22h1.864a1 1 0 0 0 .035-.255a.97.97 0 0 0-.97-.965");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.okwcqabci {
  d: path("M21.294 15.615c.07-1.152.14-2.301.2-3.453a1.741 1.741 0 0 1-.2 3.453");
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

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
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

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.rihmkq8le {
  d: path("M16.021 19.32c-.78 0-1.55.08-2.3.23v10.38h4.58V19.55c-.74-.15-1.5-.23-2.28-.23");
}

.rj0sd-b5f {
  stop-color: var(--svg-color--ff804b, #FF804B);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rredkdkgz {
  stop-color: var(--svg-color--ff8e3d, #FF8E3D);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.rzlaa0gmj {
  d: path("M4.601 29.93c.14-.946.34-1.882.62-2.787a11.56 11.56 0 0 1 3.12-5.018v7.805z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
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

.tpp8-4lcr {
  stop-color: var(--svg-color--79454d, #79454D);
}

.tr7_h_b0z {
  d: path("m15.556 13.256l-.575 1.99c-.118.408.164.817.563.817h.85c.4 0 .681-.415.564-.818l-.575-1.989c-.123-.44-.698-.44-.827 0");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tws1sccvb {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.97 17.298a3.25 3.25 0 0 1-1.5-.356c-.148-.075-.307.092-.214.226c.363.55.994.916 1.713.916s1.35-.366 1.713-.916c.093-.14-.066-.301-.214-.226a3.2 3.2 0 0 1-1.499.356Z");
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

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.uwbp-acze {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.556 12.363a1.51 1.51 0 0 1 1.465 1.145a.297.297 0 0 1-.29.369h-2.413a.25.25 0 0 1-.246-.294a1.51 1.51 0 0 1 1.484-1.22");
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vck3ny32q {
  stop-color: var(--svg-color--743b49, #743B49);
}

.vdo1-b9pv {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.383 12.363a1.51 1.51 0 0 0-1.466 1.145a.297.297 0 0 0 .29.37h2.413a.25.25 0 0 0 .246-.295a1.516 1.516 0 0 0-1.483-1.22");
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vse2rygyc {
  d: path("M22.025 20.77v9.16h-1.983V19.736c.698.279 1.355.62 1.983 1.034");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x4wtvpeua {
  d: path("M10.75 17.155a4.236 4.236 0 0 0 4.203 3.685h2.041a4.236 4.236 0 0 0 4.203-3.685c.128-2.038.256-4.067.351-6.104a1.57 1.57 0 0 0-1.492-1.55h-1.514a2.62 2.62 0 0 1-2.393-1.56a.72.72 0 0 0-.666-.452h-1.376c-1.997 0-3.615 1.636-3.615 3.655c0 2.013.126 3.993.258 6.011");
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.x9nrh1bge {
  d: path("M22.266 9.842H9.672a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.154a1.147 1.147 0 0 0-1.153-1.153");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
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

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xwhta25pw {
  d: path("M18.332 12.657a.965.965 0 0 1 .93 1.22h-1.865a.97.97 0 0 1 .935-1.22");
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.yfsg16eua {
  d: path("M27.399 29.93c-.14-.946-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018v7.805z");
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

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z1m_06brq {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.535 13.603l-.64 1.988c-.108.41.154.818.525.818h.792c.37 0 .633-.415.523-.818l-.534-1.988c-.115-.44-.546-.44-.666 0");
}

.zdrlg3bmy {
  stop-color: var(--svg-color--d15d2a, #D15D2A);
  stop-opacity: 0;
}

.zf1kpzbqc {
  d: path("M10.71 15.516a1.77 1.77 0 0 1-.978-.334v1.007a2.35 2.35 0 0 0 1.45 2.185a4.4 4.4 0 0 1-.374-1.277z");
}

.zm3fyksng {
  d: path("m15.556 13.39l-.575 1.99c-.118.408.164.818.563.818h.85c.4 0 .681-.416.564-.819l-.575-1.988c-.123-.44-.698-.44-.827 0");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
