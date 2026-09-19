<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ix46zXc)" class="k1w1t75ku"/><path fill="url(#ijXeoKb)" class="k1w1t75ku"/><path fill="url(#i1JiZgd)" class="k1w1t75ku"/><path fill="url(#ifKe6sd)" class="klo0xacki"/><path fill="url(#iv9nIVb)" class="klo0xacki"/><path fill="url(#iXQXadd)" class="klo0xacki"/><path fill="url(#iUosxFc)" class="klo0xacki"/><path fill="url(#i25HGGS)" class="umtdafb5k"/><path fill="url(#i0oMUKb)" class="umtdafb5k"/><g filter="url(#iyZ7llb)"><path fill="url(#ijqYFVb)" class="rax5ir8yp"/><path fill="url(#i2PJZJb)" class="rax5ir8yp"/><path fill="url(#iRI5XZc)" class="rax5ir8yp"/></g><path fill="url(#iTxvzib)" class="f1_mi5b6m"/><path fill="url(#iB4Odkb)" class="kozp32b2e"/><path fill="url(#in6s5Hb)" class="cnueaqb5f"/><path fill="url(#iZT63Nd)" class="cnueaqb5f"/><path fill="url(#iVfNLtd)" class="f9qxz5bxy"/><path fill="url(#izIGRqd)" class="f9qxz5bxy"/><path fill="url(#iRVUIOc)" class="p9z3vnb5g"/><path fill="url(#i5Oqj0d)" class="p9z3vnb5g"/><path fill="url(#i9dQhwe)" class="p9z3vnb5g"/><path fill="url(#ii2SFlF)" class="p9z3vnb5g"/><path fill="url(#iBdWIHu)" class="p9z3vnb5g"/><path fill="url(#ixnEfLe)" class="do2hnz1yg"/><path fill="url(#iPwJlzc)" class="do2hnz1yg"/><path fill="url(#i4F9MJd)" class="do2hnz1yg"/><path fill="url(#ie3NmPc)" class="do2hnz1yg"/><path fill="url(#i7n0KGe)" class="i07zy6rcn"/><path fill="url(#iUtG43b)" class="i07zy6rcn"/><path fill="url(#ijN52Nd)" class="i07zy6rcn"/><path fill="url(#i8pVGid)" class="at9o4r03z"/><path fill="url(#ic81wvb)" class="at9o4r03z"/><g filter="url(#ipYkoxd)"><path fill="url(#iyP1oVc)" class="caf9i5bzt"/><path fill="url(#iZYZqPb)" class="caf9i5bzt"/><path fill="url(#iomz2Zd)" class="caf9i5bzt"/><path fill="url(#iRt936b)" class="caf9i5bzt"/><path fill="url(#ijIPW6Z)" class="caf9i5bzt"/></g><rect fill="url(#iBezdWc)" class="e7y3krprr"/><rect fill="url(#ivbEq3d)" class="e7y3krprr"/><g filter="url(#i1jQExd)"><path fill="url(#iD77VKc)" class="k81aawbxh"/></g><g filter="url(#i9Qu9Ob)"><path fill="url(#i2dkTNe)" class="r-n0qjbzg"/></g><g filter="url(#i3fliee)"><path fill="url(#ieUBnUb)" class="xowpd3eje"/></g><g filter="url(#ig7iTbe)"><path stroke="url(#imKGRbc)" class="n2u-spbei"/></g><g filter="url(#iE5X9Gd)"><path stroke="url(#iAkaigc)" class="nggdytb3q"/></g><g filter="url(#iP1yoqd)"><path stroke="url(#i79Vvud)" class="nlzxd2qep"/></g><path fill="url(#isJ7lOe)" class="bkinyfbxs"/><path fill="url(#ibwrCwL)" class="dwyn7o23y"/><g filter="url(#i4h2Gtc)"><path fill="url(#iRBkVTd)" class="cz0aljbzd"/></g><path fill="url(#i300pDd)" class="cz0aljbzd"/><path fill="url(#iRESoub)" class="cz0aljbzd"/><path fill="url(#iSATCee)" class="cz0aljbzd"/><path fill="url(#iCqSFcc)" class="cz0aljbzd"/><path fill="url(#irxFp9c)" class="cz0aljbzd"/><path fill="url(#iVcPbcd)" class="cz0aljbzd"/><path fill="url(#iFrTW4d)" class="cz0aljbzd"/><path fill="url(#iXteF0d)" class="cz0aljbzd"/><path fill="url(#ibEJzCe)" class="cz0aljbzd"/><g filter="url(#iiBp01t)"><path class="ejd5zxj7a"/></g><g filter="url(#i7kzX2b)"><path class="cx48n3b6k"/><path fill="url(#iC1Hdqb)" class="f41hwlbui"/><path fill="url(#iG9t4zd)" class="f41hwlbui"/><path fill="url(#iri4Kdd)" class="f41hwlbui"/><path fill="url(#idBLpDb)" class="f41hwlbui"/><path fill="url(#i1keAFe)" class="f41hwlbui"/></g><g filter="url(#iM2xrSb)"><path stroke="url(#i4Gyb0d)" class="hyg-hl9jd"/></g><path fill="url(#i6K4gie)" class="tvu7k4-ob"/><g filter="url(#idQkhHb)"><path fill="url(#iqr2jzd)" class="bp1xxmupk"/><path fill="url(#iMv5YKs)" class="bp1xxmupk"/><path fill="url(#iDMSdMd)" class="bp1xxmupk"/><path fill="url(#ivmb3Lb)" class="bp1xxmupk"/><path fill="url(#iQEAwkd)" class="bp1xxmupk"/></g><g filter="url(#iPnLyXk)"><path class="vwh3f-bue"/></g><g filter="url(#iqiPkoc)"><path class="cqi4te5uv"/></g><g filter="url(#iuNRife)"><path class="pjqekq-rv"/><path fill="url(#iJbsExx)" class="lqzem-jtj"/><path fill="url(#iPbHPgd)" class="lqzem-jtj"/></g><g filter="url(#i8IZ3Ee)"><path class="ml6ylf7-s"/><path fill="url(#iGVofjd)" class="lotj4e1fa"/></g><path class="fh3hznbop"/><path fill="url(#ima70tI)" class="b_85pngwn"/><path class="d973j_bkb"/><g filter="url(#i4ZvtLc)"><path class="ccf2k6brr"/><path fill="url(#igJGZJc)" class="e9qtgrb7m"/></g><g filter="url(#iijoPpb)"><path fill="url(#ibdQyAd)" class="a_c0xdzvq"/></g><path class="ipb7ow-jq"/><path fill="url(#iNXyKLB)" class="r71mc5okb"/><path class="uvdq98mqb"/><g filter="url(#izyPiye)"><path fill="url(#iVA4Evd)" class="gxpz1sbfe"/></g><g filter="url(#irU0Jtc)"><ellipse transform="rotate(-27.914 13.703 9.852)" class="ddbi53b0i"/><ellipse fill="url(#iivO7Rd)" transform="rotate(-27.914 13.703 9.852)" class="sfh8v7b3x"/></g><path fill="url(#irmkiGd)" class="ag5wwbbya"/><path fill="url(#ipglSlC)" class="ag5wwbbya"/><path fill="url(#iyZFXQc)" class="ag5wwbbya"/><path fill="url(#iINyhIc)" class="ag5wwbbya"/><path fill="url(#iywXCne)" class="bqjfh3b9b"/><path fill="url(#i5QcT4p)" class="bqjfh3b9b"/><g filter="url(#irMwNDc)"><path fill="url(#iMOgXle)" class="darjmoblb"/></g><g filter="url(#ihqPXDo)"><path fill="url(#i2QP9ne)" class="cf_e6ib-j"/></g><g filter="url(#i5ofECx)"><path class="yndxn23og"/></g><g filter="url(#imDacGb)"><path class="p6o2odyur"/></g><g filter="url(#irrZazd)"><path class="kg565scpw"/></g><defs><radialGradient id="ifKe6sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.085 29.983)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iv9nIVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.933 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iXQXadd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.933 23.034)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="i25HGGS" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.085 4.499)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="i0oMUKb" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.216 23.137)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i2PJZJb" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.175 14.796)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="iRI5XZc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.175 16.373)" gradientUnits="userSpaceOnUse"><stop class="o-r-orbbu"/><stop offset="1" class="smcyj7aql"/></radialGradient><radialGradient id="iB4Odkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.163 18.483)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="in6s5Hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -1.38289 0 16.936 16.446)" gradientUnits="userSpaceOnUse"><stop class="p498pv-fl"/><stop offset="1" class="z5u-cdbhr"/></radialGradient><radialGradient id="iZT63Nd" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.165 15.358)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="evpkpfxcx"/><stop offset="1" class="od7_1ac9s"/></radialGradient><radialGradient id="iVfNLtd" cx="0" cy="0" r="1" gradientTransform="rotate(141.307 9.814 16.69)scale(2.01873 2.49606)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="k7qyxzbsl"/><stop offset="1" class="zdypug-8z"/></radialGradient><radialGradient id="izIGRqd" cx="0" cy="0" r="1" gradientTransform="matrix(.75156 -.57402 .30002 .3928 27.675 23.392)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="i9dQhwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.86 17.376)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="ie3NmPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.574 17.202)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="ijN52Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.34 17.452)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="i8pVGid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.261 24.267)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iZYZqPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.03 25.288)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iomz2Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.03 26.582)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iRt936b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.03 27.832)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ijIPW6Z" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.03 29.184)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iBezdWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.707 21.444)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="isJ7lOe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.97 20.929)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="ibwrCwL" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 10.1 12.296)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iRBkVTd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.963 10.864)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iRESoub" cx="0" cy="0" r="1" gradientTransform="matrix(.29714 12.34172 -10.22044 .24607 16.42 4.693)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="wfsx43b1c"/><stop offset="1" class="xsml3j68x"/></radialGradient><radialGradient id="iSATCee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.603 9.551)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iCqSFcc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.744 -2.154)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="irxFp9c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.588 11.852)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iVcPbcd" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.688 6.539)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iFrTW4d" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.233 13.852)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iXteF0d" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.632 8.182)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iG9t4zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.622 12.225)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="idBLpDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.738 11.655)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i6K4gie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.156 14.403)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iMv5YKs" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.926 7.972)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iDMSdMd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.365 -6.355)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ivmb3Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.262 3.006)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iQEAwkd" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.25 1.413)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iJbsExx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.41 3.673)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iPbHPgd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.27 -5.922)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iGVofjd" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -42.644 156.7)scale(3.27033 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ima70tI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.338 9.948)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="igJGZJc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.512 .581)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNXyKLB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.974 9.948)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iivO7Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.687 10.167)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipglSlC" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.773 9.962)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iyZFXQc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.134 10.506)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iINyhIc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.248 10.679)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="i5QcT4p" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.29 9.535)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iMOgXle" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.241 10.604)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><linearGradient id="ix46zXc" x1="16.162" x2="16.162" y1="15.524" y2="30.408" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="ijXeoKb" x1="23.59" x2="21.058" y1="26.577" y2="26.608" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="i1JiZgd" x1="8.617" x2="10.833" y1="26.393" y2="26.393" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iUosxFc" x1="9.081" x2="8.646" y1="28.05" y2="28.05" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ijqYFVb" x1="22.902" x2="17.027" y1="18.483" y2="18.483" gradientUnits="userSpaceOnUse"><stop class="b-744zb0c"/><stop offset="1" class="jz3pzrmrk"/></linearGradient><linearGradient id="iTxvzib" x1="17.293" x2="15.996" y1="19.061" y2="19.983" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="iRVUIOc" x1="27.902" x2="24.527" y1="20.702" y2="20.327" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="i5Oqj0d" x1="25.622" x2="25.622" y1="20.968" y2="20.452" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="ii2SFlF" x1="25.622" x2="25.622" y1="16.822" y2="17.453" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iBdWIHu" x1="23.325" x2="24.067" y1="19.169" y2="19.169" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="ixnEfLe" x1="23.496" x2="22.199" y1="18.953" y2="18.953" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iPwJlzc" x1="23.746" x2="23.355" y1="19.233" y2="19.233" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="i4F9MJd" x1="22.95" x2="22.95" y1="21.064" y2="20.401" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="i7n0KGe" x1="29.197" x2="27.577" y1="19.401" y2="19.401" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iUtG43b" x1="28.496" x2="28.496" y1="21.038" y2="20.515" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="ic81wvb" x1="25.624" x2="25.652" y1="21.979" y2="22.335" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iyP1oVc" x1="27.621" x2="23.593" y1="28.046" y2="28.046" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="ivbEq3d" x1="25.634" x2="25.634" y1="20.796" y2="21.257" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iD77VKc" x1="17.212" x2="17.212" y1="29.586" y2="22.91" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="i2dkTNe" x1="13.205" x2="13.205" y1="29.586" y2="22.91" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ieUBnUb" x1="21.199" x2="21.199" y1="29.586" y2="22.91" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="imKGRbc" x1="24.113" x2="25.822" y1="26.053" y2="26.053" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iAkaigc" x1="24.035" x2="25.744" y1="27.358" y2="27.358" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i79Vvud" x1="24.113" x2="25.822" y1="28.663" y2="28.663" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i300pDd" x1="21.313" x2="16.96" y1="12.549" y2="12.549" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ibEJzCe" x1="16.203" x2="16.203" y1="17.035" y2="16.356" gradientUnits="userSpaceOnUse"><stop class="rfipr3bpk"/><stop offset="1" class="k-32-75fj"/></linearGradient><linearGradient id="iC1Hdqb" x1="16.994" x2="16.156" y1="11.539" y2="11.574" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iri4Kdd" x1="16.156" x2="16.156" y1="12.678" y2="12.213" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="i1keAFe" x1="16.156" x2="16.156" y1="9.723" y2="10.52" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="i4Gyb0d" x1="14.954" x2="15.272" y1="14.249" y2="13.415" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iqr2jzd" x1="23.008" x2="11.396" y1="5.202" y2="5.202" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ibdQyAd" x1="19.116" x2="18.802" y1="10.002" y2="10.195" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVA4Evd" x1="14.718" x2="14.404" y1="10.002" y2="10.195" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irmkiGd" x1="22.592" x2="21.385" y1="10.029" y2="12.205" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iywXCne" x1="10.306" x2="11.764" y1="10.733" y2="10.605" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="i2QP9ne" x1="21.572" x2="21.572" y1="9.647" y2="11.55" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><filter id="iyZ7llb" width="14.254" height="7.618" x="9.149" y="15.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1728" result="effect2_innerShadow_4002_1728"/></filter><filter id="ipYkoxd" width="4.468" height="5.556" x="23.593" y="24.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/></filter><filter id="i1jQExd" width="1.192" height="6.826" x="15.579" y="23.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="i9Qu9Ob" width="1.192" height="6.826" x="11.573" y="23.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="i3fliee" width="1.192" height="6.826" x="19.566" y="23.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="ig7iTbe" width="2.097" height=".3" x="23.963" y="25.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".05"/></filter><filter id="iE5X9Gd" width="2.097" height=".3" x="23.885" y="27.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".05"/></filter><filter id="iP1yoqd" width="2.097" height=".3" x="23.963" y="28.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".05"/></filter><filter id="i4h2Gtc" width="11.22" height="12.542" x="11.092" y="4.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1728" result="effect2_innerShadow_4002_1728"/></filter><filter id="iiBp01t" width="3.747" height="4.9" x="14.14" y="9.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".5"/></filter><filter id="i7kzX2b" width="2.277" height="3.3" x="15.017" y="9.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".1"/></filter><filter id="iM2xrSb" width="3.718" height="1.573" x="14.296" y="13.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".05"/></filter><filter id="idQkhHb" width="12.873" height="8.356" x="9.719" y="1.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1728" result="effect2_innerShadow_4002_1728"/></filter><filter id="iPnLyXk" width="2.339" height="1.19" x="17.745" y="7.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/></filter><filter id="iqiPkoc" width="2.339" height="1.176" x="12.489" y="7.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/></filter><filter id="iuNRife" width="6.734" height="5.992" x="10.075" y="2.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/><feGaussianBlur result="effect2_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="i8IZ3Ee" width="6.362" height="5.736" x="15.997" y="3.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1728"/><feGaussianBlur result="effect2_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="i4ZvtLc" width=".787" height=".696" x="17.604" y="9.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".05"/></filter><filter id="iijoPpb" width=".891" height=".913" x="18.444" y="9.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".1"/></filter><filter id="izyPiye" width=".986" height="1.04" x="14.001" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".1"/></filter><filter id="irU0Jtc" width=".913" height=".705" x="13.246" y="9.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".05"/></filter><filter id="irMwNDc" width="1.329" height="2.379" x="10.075" y="9.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="ihqPXDo" width="1.947" height="2.903" x="20.599" y="9.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".25"/></filter><filter id="i5ofECx" width="2.405" height="1.16" x="12.408" y="7.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="imDacGb" width="2.405" height="1.16" x="17.687" y="7.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".125"/></filter><filter id="irrZazd" width="5.266" height="3.005" x="17.035" y="3.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1728" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:judge-dark" /></template>
<style>
.a_c0xdzvq {
  d: path("M19.135 10.246a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.ag5wwbbya {
  d: path("M21.078 12.205c.065-1.064.129-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.at9o4r03z {
  d: path("M24.869 21.054v6.427h1.51v-6.427z");
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b_85pngwn {
  d: path("M18.34 9.47a.892.892 0 0 1 .86 1.129h-1.724a.896.896 0 0 1 .864-1.128");
}

.b-744zb0c {
  stop-color: var(--svg-color--4a4251, #4A4251);
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bkinyfbxs {
  d: path("M21.017 12.114c.335-.01.65-.125.905-.309v.931c0 .893-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bp1xxmupk {
  d: path("M21.01 4.221a2.32 2.32 0 0 1 1.268 1.052a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.379-1.433h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.072");
}

.bqjfh3b9b {
  d: path("M11.102 9.005a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.caf9i5bzt {
  d: path("M23.593 25.309a.73.73 0 0 1 .726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592A.731.731 0 0 1 24 28.594a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.ccf2k6brr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.274 9.66c.064.084-.069.188-.22.301s-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.cf_e6ib-j {
  d: path("M21.099 11.55q.058-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnueaqb5f {
  d: path("M16.165 18.717a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.927 2.075 2.075v2.58a2.083 2.083 0 0 1-2.075 2.064");
}

.cqi4te5uv {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.745 7.775a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.552a2.22 2.22 0 0 0-1.386.284a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.cx48n3b6k {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.774 10.15l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.cz0aljbzd {
  d: path("M11.33 13.629a3.916 3.916 0 0 0 3.887 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d973j_bkb {
  fill: var(--svg-color--000, #000);
  d: path("M17.829 10.363c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.061-.235");
}

.darjmoblb {
  d: path("M11.07 9.666a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.ddbi53b0i {
  cx: 13.703px;
  cy: 9.852px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.do2hnz1yg {
  d: path("M23.168 16.939h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dwyn7o23y {
  d: path("M11.295 12.114a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e7y3krprr {
  width: 2.773px;
  height: 1.082px;
  x: 24.247px;
  y: 20.968px;
  rx: 0.541px;
}

.e9qtgrb7m {
  d: path("M18.274 9.66c.064.084-.069.188-.22.301s-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ejd5zxj7a {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.754 10.345l-.59 1.839c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.839c-.106-.407-.505-.407-.616 0");
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.evpkpfxcx {
  stop-color: var(--svg-color--18080a, #18080A);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f1_mi5b6m {
  d: path("m17.092 19.745l-.655.584a.415.415 0 0 1-.554 0l-.654-.585a3.47 3.47 0 0 1-1.149-2.568v-3.113a2.085 2.085 0 0 1 2.086-2.065c1.148 0 2.075.927 2.075 2.075v3.113a3.5 3.5 0 0 1-1.149 2.558");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f41hwlbui {
  d: path("m15.774 10.15l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.f9qxz5bxy {
  d: path("M26.949 22.916c.531 0 .959.427.959.959v2.188H26v-2.188a.94.94 0 0 1 .948-.959");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fh3hznbop {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.547 9.199c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gxpz1sbfe {
  d: path("M14.787 10.259c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.hyg-hl9jd {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.805 13.366a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.i07zy6rcn {
  d: path("M28.694 16.939h-.614a.505.505 0 0 0-.503.503v3.022c0 .272.221.504.503.504h.614a.505.505 0 0 0 .503-.504v-3.022a.51.51 0 0 0-.503-.503");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.ipb7ow-jq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.765 9.199c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jz3pzrmrk {
  stop-color: var(--svg-color--3e3646, #3E3646);
}

.k-32-75fj {
  stop-color: var(--svg-color--42363b, #42363B);
  stop-opacity: 0;
}

.k1w1t75ku {
  d: path("M16.165 15.524c-6.114 0-11.08 4.906-11.08 10.969v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.955-10.97-11.07-10.97");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k81aawbxh {
  d: path("M15.829 23.527h.692v6.326h-.692z");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kg565scpw {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.349 5.266h-2.081a.483.483 0 1 1 .077-.961c.54.086 1.257.206 1.737.325c1.085.269 1.385.797 1.469 1.174a1.51 1.51 0 0 0-1.202-.538");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.klo0xacki {
  d: path("M8.933 29.983v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kozp32b2e {
  d: path("m16.956 19.866l.136-.121a3.5 3.5 0 0 0 1.148-2.549v-1.964h-4.15l-.005 1.912c0 .051.003.146 0 .2c.045.916.46 1.783 1.144 2.4l.16.144l.666-1.01a.13.13 0 0 1 .22 0z");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lotj4e1fa {
  d: path("m21.368 8.515l-.029-.631c-.01-.763-.641-1.393-1.405-1.425h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.136-.12-.368c-.256-.97.67-1.713 1.656-1.522c.973.19 2.082.517 2.902 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lqzem-jtj {
  d: path("m16.388 5.248l-.066-.136a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.275c-.34-.26-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.33-.253q.046-.046.1-.105c.35-.37.973-1.03 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.ml6ylf7-s {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.368 8.515l-.029-.631c-.01-.763-.641-1.393-1.405-1.425h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.136-.12-.368c-.256-.97.67-1.713 1.656-1.522c.973.19 2.082.517 2.902 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.n2u-spbei {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 25.975h1.797");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nggdytb3q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.035 27.28h1.797");
}

.nlzxd2qep {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 28.585h1.797");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o-r-orbbu {
  stop-color: var(--svg-color--1c1124, #1C1124);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od7_1ac9s {
  stop-color: var(--svg-color--18080a, #18080A);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p498pv-fl {
  stop-color: var(--svg-color--301a21, #301A21);
}

.p6o2odyur {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.717 8.009c-.257-.185-.898-.509-1.655-.381");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p9z3vnb5g {
  d: path("M27.073 16.939h-2.901a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h2.9a.505.505 0 0 0 .505-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pjqekq-rv {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.388 5.248l-.066-.136a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.275c-.34-.26-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.33-.253q.046-.046.1-.105c.35-.37.973-1.03 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
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

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r-n0qjbzg {
  d: path("M11.823 23.527h.692v6.326h-.692z");
}

.r71mc5okb {
  d: path("M13.972 9.47a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rax5ir8yp {
  d: path("M9.236 17.851c1.974-1.646 4.386-2.422 6.94-2.422c2.553 0 4.965.776 6.939 2.422a.24.24 0 0 1 .061.296c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.296");
}

.rfipr3bpk {
  stop-color: var(--svg-color--42363b, #42363B);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sfh8v7b3x {
  cx: 13.703px;
  cy: 9.852px;
  rx: 0.39px;
  ry: 0.197px;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.smcyj7aql {
  stop-color: var(--svg-color--1c1124, #1C1124);
  stop-opacity: 0;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tvu7k4-ob {
  d: path("M16.156 13.76c-.508 0-.985-.119-1.386-.328c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.086-.13-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.umtdafb5k {
  d: path("M23.388 29.983v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uvdq98mqb {
  fill: var(--svg-color--000, #000);
  d: path("M14.483 10.363a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.745h.904a.5.5 0 0 0 .061-.235");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vwh3f-bue {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.889 7.884a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 0 0 .067.55c.481-.058.776-.028.979.036c.198.062.332.164.49.3a.277.277 0 0 0 .364-.418");
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wfsx43b1c {
  stop-color: var(--svg-color--432632, #432632);
  stop-opacity: 0;
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xowpd3eje {
  d: path("M19.816 23.527h.692v6.326h-.692z");
}

.xsml3j68x {
  stop-color: var(--svg-color--2d1821, #2D1821);
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yndxn23og {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.783 8.055c.257-.184.897-.509 1.655-.381");
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z5u-cdbhr {
  stop-color: var(--svg-color--3b2322, #3B2322);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
