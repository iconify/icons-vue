<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGYiiab)" class="govw1ktzb"/><path fill="url(#iuPQdme)" class="govw1ktzb"/><path fill="url(#ip5rFvF)" class="govw1ktzb"/><path fill="url(#iHcO2zd)" class="rikg1lxqe"/><path fill="url(#i3UCwvB)" class="rikg1lxqe"/><path fill="url(#iA0nITd)" class="rikg1lxqe"/><path fill="url(#i67d7wd)" class="rikg1lxqe"/><path fill="url(#inhi3Md)" class="epaqg5v3i"/><path fill="url(#i1khh7b)" class="epaqg5v3i"/><g filter="url(#iOzU59d)"><path fill="url(#iVAuv0b)" class="k7d_3u4gb"/><path fill="url(#i0Y48ve)" class="k7d_3u4gb"/><path fill="url(#iRlk6ge)" class="k7d_3u4gb"/></g><path fill="url(#imKmnXk)" class="b3sl-n5wo"/><path fill="url(#iF4gOBd)" class="o318p6rks"/><path fill="url(#iu5o61C)" class="zg8rqkl-p"/><path fill="url(#i9laKEN)" class="zg8rqkl-p"/><path fill="url(#iZiHFmw)" class="d8_rq0qdx"/><path fill="url(#idCWGfX)" class="d8_rq0qdx"/><path fill="url(#ivETtJe)" class="j-swt60sg"/><path fill="url(#idlJyJb)" class="j-swt60sg"/><path fill="url(#iifhNtb)" class="j-swt60sg"/><path fill="url(#iKkz3Nc)" class="j-swt60sg"/><path fill="url(#ilM5ThA)" class="j-swt60sg"/><path fill="url(#i27wJ3d)" class="u91xe1bko"/><path fill="url(#iMhEysc)" class="u91xe1bko"/><path fill="url(#iDIzUje)" class="u91xe1bko"/><path fill="url(#iVIaz3b)" class="u91xe1bko"/><path fill="url(#i0YwGdb)" class="fw-cdba2q"/><path fill="url(#iADzohc)" class="fw-cdba2q"/><path fill="url(#iFC9u7c)" class="fw-cdba2q"/><path fill="url(#i60GaqU)" class="jngxeltjt"/><path fill="url(#iQZgmHa)" class="jngxeltjt"/><g filter="url(#iILPoFc)"><path fill="url(#it2AY2d)" class="fi21nobeo"/><path fill="url(#iFB26xb)" class="fi21nobeo"/><path fill="url(#iYIQwrc)" class="fi21nobeo"/><path fill="url(#i1AvF4c)" class="fi21nobeo"/><path fill="url(#ii3xmle)" class="fi21nobeo"/></g><rect fill="url(#iCiMsXD)" class="b1ih56t7b"/><rect fill="url(#i5H8M6b)" class="b1ih56t7b"/><g filter="url(#ioOe0we)"><path fill="url(#iRaeKre)" class="shatsr3dk"/></g><g filter="url(#ievrJUc)"><path fill="url(#iqleWSc)" class="yilxh4bwb"/></g><g filter="url(#iMCRInd)"><path fill="url(#iXPsG0c)" class="xbzfhsboq"/></g><g filter="url(#i8dOZ9b)"><path stroke="url(#ioUqILd)" class="sw2_g7bmt"/></g><g filter="url(#iIrQbKc)"><path stroke="url(#imfs24b)" class="o4wwcacju"/></g><g filter="url(#iHMfWzc)"><path stroke="url(#imYk1jc)" class="f8oot5bnf"/></g><path fill="url(#i7s5T6d)" class="n5bxznf9s"/><path fill="url(#ih0luQd)" class="jeibj2-ce"/><path fill="url(#iBHPehe)" class="jeibj2-ce"/><path fill="url(#ih0luQd)" class="jeibj2-ce"/><path fill="url(#iBHPehe)" class="jeibj2-ce"/><g filter="url(#iFVJEab)"><path fill="url(#iU2Al6d)" class="erme_acgc"/></g><path fill="url(#iPl4V0k)" class="erme_acgc"/><path fill="url(#i9Dvjkc)" class="erme_acgc"/><path fill="url(#iUc6r8b)" class="erme_acgc"/><path fill="url(#iWHdkhe)" class="erme_acgc"/><path fill="url(#iZDsj4d)" class="erme_acgc"/><path fill="url(#iWmUJEd)" class="erme_acgc"/><path fill="url(#iHq1rzo)" class="erme_acgc"/><path fill="url(#iV1O6Td)" class="erme_acgc"/><g filter="url(#ir2nfNc)"><path class="r_or7nb2d"/></g><g filter="url(#iClyzWd)"><path fill="url(#iaa22rt)" class="ic4w6cc7v"/><path fill="url(#ivuVvyd)" class="ic4w6cc7v"/><path fill="url(#ijrLCgd)" class="ic4w6cc7v"/><path fill="url(#iwuJbZd)" class="ic4w6cc7v"/></g><path fill="url(#iEeDMHe)" class="ic4w6cc7v"/><path fill="url(#iKvcf0C)" class="ic4w6cc7v"/><g filter="url(#ig0o7ra)"><path stroke="url(#iohNYab)" class="h72tx_7tz"/></g><path fill="url(#izKENsO)" class="lk13a6ebr"/><g filter="url(#iqInwgd)"><path fill="url(#iKpa3Bd)" class="f4tyvcqux"/><path fill="url(#iBQveYd)" class="f4tyvcqux"/><path fill="url(#iytpOye)" class="f4tyvcqux"/><path fill="url(#iIhcjpj)" class="f4tyvcqux"/><path fill="url(#i6pvEKd)" class="f4tyvcqux"/></g><g filter="url(#iPBGK9c)"><path class="tt--ksvep"/></g><g filter="url(#iMD0AId)"><path class="qjkforbqo"/></g><g filter="url(#iLqBT6b)"><path fill="url(#isDwDGt)" class="tbi-ve1pa"/><path fill="url(#iFuOLXb)" class="tbi-ve1pa"/></g><g filter="url(#igBD6qd)"><path fill="url(#iZkKtrc)" class="hbxcpumsq"/><path fill="url(#i2h0Dte)" class="hbxcpumsq"/><path fill="url(#iVRmFqM)" class="hbxcpumsq"/><path fill="url(#iKhyv7Y)" class="hbxcpumsq"/><path fill="url(#iC0892d)" class="hbxcpumsq"/><path fill="url(#iKOKVhM)" class="hbxcpumsq"/></g><path class="ft94_jhbl"/><path fill="url(#iWnrsfe)" class="rj6oiwbuh"/><path class="iz7hhrjjq"/><g filter="url(#i9ApyNc)"><path class="d4dncky8d"/><path fill="url(#isxNldb)" class="x6zcp6e7f"/></g><g filter="url(#iDGfOWd)"><path fill="url(#iINtFNb)" class="e2qw_4bsl"/></g><path class="pbp6oxbyh"/><path fill="url(#i67ZDwc)" class="d7aup-bli"/><path class="j4trkuq1o"/><g filter="url(#iECT5pi)"><path fill="url(#ipnSPri)" class="uhkh_9j3h"/></g><g filter="url(#i4O2Iyb)"><ellipse transform="rotate(-27.914 13.722 10.397)" class="ckzn90b7s"/><ellipse fill="url(#iHAzeJc)" transform="rotate(-27.914 13.722 10.397)" class="zopwzac8s"/></g><path fill="url(#iCTas0b)" class="j78gxpvho"/><path fill="url(#i6LQ0qe)" class="j78gxpvho"/><path fill="url(#iQn0SDc)" class="j78gxpvho"/><path fill="url(#ifvO5Gc)" class="y20pcabnb"/><path fill="url(#ipdNG9d)" class="y20pcabnb"/><g filter="url(#i91tdRO)"><path class="qkkzyoy1t"/></g><g filter="url(#iGYdg8c)"><path class="zxi_25qfc"/></g><g filter="url(#iT3YwHe)"><path class="thxx4ccje"/></g><g filter="url(#ixnwdte)"><path class="oe3e53bjs"/></g><defs><radialGradient id="iHcO2zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.085 30.003)" gradientUnits="userSpaceOnUse"><stop class="ogfz3obbf"/><stop offset=".434" class="odeeueq9k"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="i3UCwvB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.933 30.003)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iA0nITd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.933 23.055)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="inhi3Md" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.094 4.509)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="i1khh7b" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.216 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i0Y48ve" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.175 14.815)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="iRlk6ge" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.175 16.394)" gradientUnits="userSpaceOnUse"><stop class="o-r-orbbu"/><stop offset="1" class="smcyj7aql"/></radialGradient><radialGradient id="iF4gOBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.163 18.503)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="iu5o61C" cx="0" cy="0" r="1" gradientTransform="rotate(90 .235 16.7)scale(1.82081 1.38289)" gradientUnits="userSpaceOnUse"><stop class="au64-mbre"/><stop offset="1" class="rw7egfg2v"/></radialGradient><radialGradient id="i9laKEN" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.165 15.378)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="ngwr-rbyk"/><stop offset=".957" class="m7pqytrhe"/></radialGradient><radialGradient id="iZiHFmw" cx="0" cy="0" r="1" gradientTransform="rotate(145.605 10.474 16.149)scale(2.31047 2.27126)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="idCWGfX" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.45 -29.208)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iifhNtb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.86 17.396)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iVIaz3b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.574 17.222)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iFC9u7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.34 17.472)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="i60GaqU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.261 24.288)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iFB26xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.03 25.308)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iYIQwrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.03 26.602)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i1AvF4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.03 27.852)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ii3xmle" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.03 29.204)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iCiMsXD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.707 21.464)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="i7s5T6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.634 12.185)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="ih0luQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.626 12.468)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iBHPehe" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.407 12.768)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iU2Al6d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.983 11.41)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="i9Dvjkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.9062 -10.6879 0 17.094 5.062)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="o43smzbtc"/></radialGradient><radialGradient id="iUc6r8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.622 10.289)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iWHdkhe" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.784 -1.535)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iZDsj4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.294 11.794)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iWmUJEd" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.322 8.408)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iHq1rzo" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 16.021 15.481)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iV1O6Td" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 18.133 6.028)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iKvcf0C" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.258 9.216)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iohNYab" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 20.067 -5.493)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="izKENsO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.175 14.948)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iBQveYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.945 9.827)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iytpOye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 21.036 9.827)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iIhcjpj" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.468 -.093)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="i6pvEKd" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.27 1.958)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="isDwDGt" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.917 3.137)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iFuOLXb" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 10.745 8.16)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iZkKtrc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.796 4.561)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="i2h0Dte" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.292 -1.552)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iVRmFqM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 20.684 8.866)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iKhyv7Y" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.969 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iC0892d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.628 4.32)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iKOKVhM" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.761 7.647)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iWnrsfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.357 10.493)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isxNldb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 18.129 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i67ZDwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.993 10.493)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHAzeJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.706 10.713)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6LQ0qe" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.793 10.507)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iQn0SDc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.153 11.051)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ipdNG9d" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 6.035 5.166)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="iGYiiab" x1="16.162" x2="16.162" y1="15.544" y2="30.429" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="iuPQdme" x1="23.59" x2="21.058" y1="26.597" y2="26.628" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="ip5rFvF" x1="8.617" x2="10.833" y1="26.413" y2="26.413" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="i67d7wd" x1="9.081" x2="8.646" y1="28.07" y2="28.07" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iVAuv0b" x1="22.902" x2="17.027" y1="18.503" y2="18.503" gradientUnits="userSpaceOnUse"><stop class="b-744zb0c"/><stop offset="1" class="jz3pzrmrk"/></linearGradient><linearGradient id="imKmnXk" x1="17.293" x2="15.996" y1="19.081" y2="20.003" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="ivETtJe" x1="27.902" x2="24.527" y1="20.722" y2="20.347" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="idlJyJb" x1="25.622" x2="25.622" y1="20.988" y2="20.472" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iKkz3Nc" x1="25.622" x2="25.622" y1="16.842" y2="17.473" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="ilM5ThA" x1="23.325" x2="24.067" y1="19.189" y2="19.189" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="i27wJ3d" x1="23.496" x2="22.199" y1="18.973" y2="18.973" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iMhEysc" x1="23.746" x2="23.355" y1="19.253" y2="19.253" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iDIzUje" x1="22.95" x2="22.95" y1="21.084" y2="20.421" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="i0YwGdb" x1="29.197" x2="27.577" y1="19.421" y2="19.421" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iADzohc" x1="28.496" x2="28.496" y1="21.058" y2="20.535" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iQZgmHa" x1="25.624" x2="25.652" y1="22" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="it2AY2d" x1="27.621" x2="23.593" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="nfkkf0b1d"/></linearGradient><linearGradient id="i5H8M6b" x1="25.634" x2="25.634" y1="20.816" y2="21.277" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iRaeKre" x1="17.212" x2="17.212" y1="29.607" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iqleWSc" x1="13.205" x2="13.205" y1="29.607" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iXPsG0c" x1="21.199" x2="21.199" y1="29.607" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ioUqILd" x1="24.113" x2="25.822" y1="26.074" y2="26.074" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="imfs24b" x1="24.035" x2="25.744" y1="27.378" y2="27.378" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="imYk1jc" x1="24.113" x2="25.822" y1="28.683" y2="28.683" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iPl4V0k" x1="21.332" x2="16.98" y1="13.095" y2="13.095" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iaa22rt" x1="16.175" x2="17.03" y1="12.238" y2="12.238" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="ivuVvyd" x1="15.102" x2="16.176" y1="12.082" y2="12.142" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ijrLCgd" x1="16.175" x2="16.175" y1="12.637" y2="13.489" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iwuJbZd" x1="16.175" x2="16.175" y1="10.389" y2="10.809" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iEeDMHe" x1="16.306" x2="16.306" y1="13.311" y2="13.252" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iKpa3Bd" x1="21.539" x2="11.415" y1="5.746" y2="5.746" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iINtFNb" x1="19.135" x2="18.821" y1="10.547" y2="10.74" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipnSPri" x1="14.737" x2="14.423" y1="10.547" y2="10.74" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCTas0b" x1="22.611" x2="21.404" y1="10.574" y2="12.75" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ifvO5Gc" x1="10.325" x2="11.784" y1="11.278" y2="11.15" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="iOzU59d" width="14.254" height="7.618" x="9.149" y="15.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1737"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1737" result="effect2_innerShadow_4002_1737"/></filter><filter id="iILPoFc" width="4.468" height="5.556" x="23.593" y="24.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1737"/></filter><filter id="ioOe0we" width="1.192" height="6.826" x="15.579" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="ievrJUc" width="1.192" height="6.826" x="11.573" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="iMCRInd" width="1.192" height="6.826" x="19.566" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="i8dOZ9b" width="2.097" height=".3" x="23.963" y="25.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="iIrQbKc" width="2.097" height=".3" x="23.885" y="27.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="iHMfWzc" width="2.097" height=".3" x="23.963" y="28.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="iFVJEab" width="10.97" height="12.542" x="11.112" y="5.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1737"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1737" result="effect2_innerShadow_4002_1737"/></filter><filter id="ir2nfNc" width="3.754" height="4.823" x="14.029" y="9.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".5"/></filter><filter id="iClyzWd" width="2.077" height="3.1" x="15.136" y="10.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="ig0o7ra" width="3.718" height="1.573" x="14.316" y="13.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="iqInwgd" width="12.873" height="8.356" x="9.739" y="2.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1737"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1737" result="effect2_innerShadow_4002_1737"/></filter><filter id="iPBGK9c" width="2.339" height="1.19" x="17.764" y="7.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1737"/></filter><filter id="iMD0AId" width="2.339" height="1.176" x="12.508" y="7.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1737"/></filter><filter id="iLqBT6b" width="6.584" height="5.992" x="10.094" y="3.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="igBD6qd" width="6.362" height="5.736" x="16.016" y="3.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="i9ApyNc" width=".787" height=".696" x="17.623" y="10.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="iDGfOWd" width=".891" height=".913" x="18.463" y="10.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".1"/></filter><filter id="iECT5pi" width=".986" height="1.04" x="14.02" y="10.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".1"/></filter><filter id="i4O2Iyb" width=".913" height=".705" x="13.265" y="10.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".05"/></filter><filter id="i91tdRO" width="1.329" height="2.379" x="10.142" y="9.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="iGYdg8c" width="1.447" height="2.403" x="20.887" y="9.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="iT3YwHe" width="2.405" height="1.16" x="12.427" y="7.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter><filter id="ixnwdte" width="2.405" height="1.16" x="17.706" y="7.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1737" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:judge-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.au64-mbre {
  stop-color: var(--svg-color--ac7271, #AC7271);
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.b-744zb0c {
  stop-color: var(--svg-color--4a4251, #4A4251);
}

.b1ih56t7b {
  width: 2.773px;
  height: 1.082px;
  x: 24.247px;
  y: 20.988px;
  rx: 0.541px;
}

.b3sl-n5wo {
  d: path("m17.092 19.765l-.655.584a.416.416 0 0 1-.554 0l-.654-.584a3.47 3.47 0 0 1-1.149-2.569v-3.113a2.085 2.085 0 0 1 2.086-2.064c1.148 0 2.075.926 2.075 2.075v3.112a3.5 3.5 0 0 1-1.149 2.559");
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzn90b7s {
  cx: 13.722px;
  cy: 10.397px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d4dncky8d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.294 10.205c.063.085-.07.188-.221.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.d7aup-bli {
  d: path("M13.991 10.016a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.d8_rq0qdx {
  d: path("M26.949 22.937c.531 0 .959.427.959.958v2.188H26v-2.188a.94.94 0 0 1 .948-.959");
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e2qw_4bsl {
  d: path("M19.154 10.79a.84.84 0 0 0-.231-.462l-.26.285l.117.229z");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.epaqg5v3i {
  d: path("M23.388 30.004V18.203c2.355 2.01 3.848 4.987 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.erme_acgc {
  d: path("M11.35 14.174a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.433h-1.4a2.42 2.42 0 0 1-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.f4tyvcqux {
  d: path("M21.03 4.766c.514.177.976.537 1.267 1.051a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.667-.268l.078-1.607A1.45 1.45 0 0 0 19.953 7.1h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.299-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.913a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.187.913-.187c.843 0 1.58.456 1.988 1.131c.308.51.79.88 1.353 1.073");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.f8oot5bnf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 28.605h1.797");
}

.fi21nobeo {
  d: path("M23.593 25.329c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592A.731.731 0 0 1 24 28.614a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ft94_jhbl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.566 9.744c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.fw-cdba2q {
  d: path("M28.694 16.959h-.614a.505.505 0 0 0-.503.503v3.022c0 .272.221.504.503.504h.614a.505.505 0 0 0 .503-.504v-3.022a.51.51 0 0 0-.503-.503");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.govw1ktzb {
  d: path("M16.165 15.544c-6.114 0-11.08 4.906-11.08 10.97v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.064-4.955-10.97-11.07-10.97");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h72tx_7tz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.824 13.91a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.271c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.hbxcpumsq {
  d: path("m21.388 9.166l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.744 1.137 1.439 3.188.52 4.154");
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
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

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ic4w6cc7v {
  d: path("m15.793 10.695l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.iz7hhrjjq {
  fill: var(--svg-color--000, #000);
  d: path("M17.848 10.908a.51.51 0 0 1 .511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.j-swt60sg {
  d: path("M27.073 16.959h-2.901a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h2.9a.505.505 0 0 0 .505-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j4trkuq1o {
  fill: var(--svg-color--000, #000);
  d: path("M14.502 10.908a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.j78gxpvho {
  d: path("M21.097 12.75q.101-1.596.184-3.191a1.61 1.61 0 0 1-.184 3.19");
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jeibj2-ce {
  d: path("M11.314 12.66a1.64 1.64 0 0 1-.905-.31v.932c0 .893.532 1.688 1.341 2.019a4.1 4.1 0 0 1-.346-1.18z");
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jngxeltjt {
  d: path("M24.869 21.074v6.427h1.51v-6.427z");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jz3pzrmrk {
  stop-color: var(--svg-color--3e3646, #3E3646);
}

.k7d_3u4gb {
  d: path("M9.236 17.872c1.974-1.647 4.386-2.423 6.94-2.423c2.553 0 4.965.776 6.939 2.423a.24.24 0 0 1 .061.295c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.295");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk13a6ebr {
  d: path("M16.175 14.306c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.249-.338 1.584-.846c.086-.13-.061-.278-.198-.209a3 3 0 0 1-1.386.329");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m7pqytrhe {
  stop-color: var(--svg-color--845033, #845033);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n5bxznf9s {
  d: path("M21.036 12.66c.336-.012.65-.125.905-.31v.932c0 .893-.532 1.688-1.341 2.019a4.1 4.1 0 0 0 .346-1.18z");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nfkkf0b1d {
  stop-color: var(--svg-color--c4907c, #C4907C);
}

.ngwr-rbyk {
  stop-color: var(--svg-color--845033, #845033);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o-r-orbbu {
  stop-color: var(--svg-color--1c1124, #1C1124);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o318p6rks {
  d: path("m16.956 19.886l.136-.121a3.5 3.5 0 0 0 1.148-2.549v-1.964h-4.15l-.005 1.911c0 .052.003.147 0 .2c.045.917.46 1.785 1.144 2.402l.16.143l.666-1.01a.13.13 0 0 1 .22 0z");
}

.o43smzbtc {
  stop-color: var(--svg-color--a46b72, #A46B72);
}

.o4wwcacju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.035 27.3h1.797");
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
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

.odeeueq9k {
  stop-color: var(--svg-color--675375, #675375);
}

.oe3e53bjs {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.736 8.554c-.257-.184-.898-.509-1.655-.381");
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ogfz3obbf {
  stop-color: var(--svg-color--957b8d, #957B8D);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.pbp6oxbyh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.784 9.744c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
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

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qjkforbqo {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.764 8.32a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.552a2.22 2.22 0 0 0-1.387.284a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.438z");
}

.qkkzyoy1t {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.138 10.211a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r_or7nb2d {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.744 11.073l-.692 1.656c-.101.378.142.756.487.756h.735c.344 0 .588-.384.486-.756l-.496-1.839c-.107-.407-.408-.224-.52.183");
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rikg1lxqe {
  d: path("M8.933 30.004V18.203c-2.356 2.01-3.848 4.987-3.848 8.31v3.49z");
}

.rj6oiwbuh {
  d: path("M18.36 10.016a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rw7egfg2v {
  stop-color: var(--svg-color--b2826e, #B2826E);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.shatsr3dk {
  d: path("M15.829 23.547h.692v6.326h-.692z");
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.smcyj7aql {
  stop-color: var(--svg-color--1c1124, #1C1124);
  stop-opacity: 0;
}

.sw2_g7bmt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 25.996h1.797");
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tbi-ve1pa {
  d: path("m16.407 5.794l-.066-.137a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.275c-.34-.26-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.331-.253l.1-.104c.35-.371.972-1.032 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892V5.78z");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.thxx4ccje {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.802 8.6c.257-.184.897-.509 1.655-.381");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tt--ksvep {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.908 8.43a1.85 1.85 0 0 0-.688-.412c-.304-.096-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.482-.058.776-.028.979.036c.198.063.332.164.49.3a.277.277 0 1 0 .364-.417");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u91xe1bko {
  d: path("M23.168 16.959h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhkh_9j3h {
  d: path("M14.806 10.803c0-.288-.234-.48-.297-.538l-.289.279l.178.36z");
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

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x6zcp6e7f {
  d: path("M18.294 10.205c.063.085-.07.188-.221.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.xbzfhsboq {
  d: path("M19.816 23.547h.692v6.326h-.692z");
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y20pcabnb {
  d: path("M11.121 9.55a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yilxh4bwb {
  d: path("M11.823 23.547h.692v6.326h-.692z");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zg8rqkl-p {
  d: path("M16.165 18.737a2.07 2.07 0 0 1-2.075-2.075v-2.578a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.926 2.075 2.075v2.578a2.083 2.083 0 0 1-2.075 2.065");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zopwzac8s {
  cx: 13.722px;
  cy: 10.397px;
  rx: 0.39px;
  ry: 0.197px;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

.zxi_25qfc {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.137 12.1q.058-.953.11-1.904a.956.956 0 0 1-.11 1.903");
}

</style>
