<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHzmtfe)" class="vbuc_sdez"/><path fill="url(#inA3Tpe)" class="vbuc_sdez"/><path fill="url(#i6KXFTY)" class="vbuc_sdez"/><path fill="url(#i04jDnj)" class="vbuc_sdez"/><g filter="url(#iITw9jb)"><path clip-rule="evenodd" class="cvzy-mbfm"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iXpTLGb)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#iQuQzOk)"><path fill="url(#iZYJJTd)" class="rqxxjhbor"/><path fill="url(#iYcv9Wc)" class="rqxxjhbor"/></g><g filter="url(#iIpB3Zz)"><path fill="url(#iCgYo9c)" class="r1d1qpblj"/><path fill="url(#iNSLv7d)" class="r1d1qpblj"/><path fill="url(#i8efCLe)" class="r1d1qpblj"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#ijoZcfd)"><path fill="url(#iIo36rp)" class="c2bk9yb6a"/><path fill="url(#ignAelv)" class="c2bk9yb6a"/></g><path fill="url(#iqkeVzb)" class="b8wkgccyf"/><path fill="url(#ib6zMLd)" class="b8wkgccyf"/><g filter="url(#i4Sjibe)"><path fill="url(#izcCUib)" class="uj-94poim"/></g><g filter="url(#idlDa7c)"><path class="oh_l9db2x"/></g><g filter="url(#imy8w9y)"><path class="teu3yl5ky"/></g><g filter="url(#iUJ16ib)"><path class="waw2uhbiy"/></g><g filter="url(#iDRNBte)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#imeFDoc)"><path fill="url(#iV1Av9c)" class="yx08hybsl"/></g><g filter="url(#iv0RUCe)"><path fill="url(#iO8TsTc)" class="hvyevjb_p"/></g><path fill="url(#i4gM3yb)" class="hvyevjb_p"/><path fill="url(#invPMbd)" class="h36ax9_yz"/><path fill="url(#iohldYb)" class="h36ax9_yz"/><path fill="url(#ira6IAb)" class="hfzp6f8qe"/><path fill="url(#iG6Zyic)" class="hfzp6f8qe"/><path fill="url(#iTfdAvb)" class="vfzn0su_w"/><path fill="url(#iTkYgvd)" class="vfzn0su_w"/><path fill="url(#iqMfzad)" class="vfzn0su_w"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iw1p9ce)" class="s80w1fafw"/><g filter="url(#ilblIMb)"><path fill="url(#i1FSYJc)" class="o7yoj0s6u"/><path fill="url(#iZLdWle)" class="o7yoj0s6u"/><path fill="url(#iZaoaBd)" class="o7yoj0s6u"/><path fill="url(#izMYsjd)" class="o7yoj0s6u"/></g><path fill="url(#ieEgdTd)" class="d2y5bebri"/><g filter="url(#i2nbVvd)"><path fill="url(#iSbgAfc)" class="i9gy75kqp"/><path fill="url(#ibRVbPt)" class="i9gy75kqp"/><path fill="url(#iR3m9Xd)" class="i9gy75kqp"/><path fill="url(#ixbEKEd)" class="i9gy75kqp"/></g><g filter="url(#itlogue)"><path fill="url(#iSUOq4d)" class="qppq5ybfo"/><path fill="url(#iMKyiCb)" class="qppq5ybfo"/><path fill="url(#iqjonuc)" class="qppq5ybfo"/><path fill="url(#iXj5Yfb)" class="qppq5ybfo"/><path fill="url(#ioyKhxe)" class="qppq5ybfo"/></g><g filter="url(#igqB0Md)"><path stroke="url(#i6AMKhc)" class="ct65j078y"/></g><g filter="url(#iFTt4Vb)"><path stroke="url(#iWhXobb)" class="ze5nteb_r"/></g><g filter="url(#iMvjXyb)"><path stroke="url(#izVZxIb)" class="jz78atb4u"/></g><path fill="url(#iIHqNzb)" class="hw5lu9yyj"/><path fill="url(#iqtBZhc)" class="hw5lu9yyj"/><path fill="url(#iOeh8Mb)" class="ozk4sobpj"/><path fill="url(#i9lKGQd)" class="ozk4sobpj"/><path fill="url(#i0DRq7e)" class="ftv--lbpz"/><path fill="url(#iRgfdpZ)" class="tf0p7nbln"/><path fill="url(#iRvsUZc)" class="tf0p7nbln"/><path fill="url(#iRgfdpZ)" class="tf0p7nbln"/><path fill="url(#iRvsUZc)" class="tf0p7nbln"/><g filter="url(#iANY4kc)"><path fill="url(#i440uXP)" class="dnzn18v5b"/></g><path fill="url(#iTfhu5b)" class="dnzn18v5b"/><path fill="url(#iRm5Fve)" class="dnzn18v5b"/><path fill="url(#iwtDQ6d)" class="dnzn18v5b"/><path fill="url(#iBE51Tl)" class="dnzn18v5b"/><path fill="url(#i02Q7yd)" class="dnzn18v5b"/><path fill="url(#ipuXVmd)" class="dnzn18v5b"/><path fill="url(#ie2onDc)" class="dnzn18v5b"/><path fill="url(#iGIu4qb)" class="dnzn18v5b"/><path fill="url(#iyI2iLc)" class="dnzn18v5b"/><path fill="url(#iFAz6db)" class="dnzn18v5b"/><g filter="url(#ifz38Be)"><path class="rau6qubfz"/></g><g filter="url(#iMMMO7c)"><path fill="url(#iYDZZ7b)" class="jcgt77k7b"/><path fill="url(#ijDLAuc)" class="jcgt77k7b"/><path fill="url(#ixCjyfN)" class="jcgt77k7b"/><path fill="url(#ieCgTJd)" class="jcgt77k7b"/></g><path fill="url(#iRxxrzR)" class="jcgt77k7b"/><path fill="url(#iAzRnqG)" class="jcgt77k7b"/><g filter="url(#iKfjTEb)"><path stroke="url(#iX9Tbxb)" class="obwtwsb6t"/></g><path fill="url(#idpYrmc)" class="eoleip7ll"/><g filter="url(#iuX7zRb)"><path class="m6v4brbmr"/></g><g filter="url(#iK6Zrge)"><path class="juvd2nbnb"/></g><path class="ngbdmdb3y"/><path fill="url(#iwysxLe)" class="l4zdmcczi"/><path class="v4czdmhgy"/><g filter="url(#inpvuId)"><path class="lqp2zsoyq"/><path fill="url(#ibwS6ac)" class="v42uwm11n"/></g><g filter="url(#iDOvS3c)"><path fill="url(#iib5ztb)" class="bvjmbzl3c"/></g><path class="j3cb57bqs"/><path fill="url(#ig46YIe)" class="z95djebnq"/><path class="vn7kb0bii"/><g filter="url(#it55VFY)"><path fill="url(#iBnjObd)" class="wzx61gbre"/></g><g filter="url(#iq7bGpc)"><ellipse transform="rotate(-27.914 13.665 9.883)" class="rm6ykeb5n"/><ellipse fill="url(#iUpkvUM)" transform="rotate(-27.914 13.665 9.883)" class="q6lw3_bhj"/></g><path fill="url(#i9Fyyzd)" class="i109d8bkc"/><path fill="url(#iSqRjCe)" class="i109d8bkc"/><path fill="url(#iFoXJFz)" class="i109d8bkc"/><path fill="url(#io6ryIb)" class="h22tlzbbg"/><path fill="url(#iP9ippb)" class="h22tlzbbg"/><g filter="url(#i53dR4c)"><path class="bkq0d2bxg"/></g><g filter="url(#iXxaa6d)"><path class="ggci8dbyq"/></g><g filter="url(#ikXFcNd)"><path class="zfyulebzw"/></g><g filter="url(#iDKk9vd)"><path class="ysenjr7ha"/></g><path fill="url(#imIJaub)" class="h64lsvfht"/><path fill="url(#iwwwWqe)" class="h64lsvfht"/><path fill="url(#iTcwEZo)" class="h64lsvfht"/><g filter="url(#ilugPid)"><path fill="url(#iExHvEe)" class="y8wf08jsl"/></g><g filter="url(#imUwHje)"><path fill="url(#iIsDzIe)" class="v481tou4o"/></g><defs><radialGradient id="iHzmtfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.975)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="i6KXFTY" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.975)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="iYcv9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.422 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iV1Av9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.783)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="invPMbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.707 -2.70976 0 16.143 17.096)" gradientUnits="userSpaceOnUse"><stop class="bu9ytxb6t"/><stop offset=".302" class="yjpqpnbll"/><stop offset=".541" class="yjpqpnbll"/><stop offset=".86" class="wyj_je-fl"/></radialGradient><radialGradient id="iohldYb" cx="0" cy="0" r="1" gradientTransform="matrix(4.11096 1.03855 -.6137 2.42921 14.233 16.566)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="t_g-bg-vr"/><stop offset=".952" class="qkhnolb2a"/></radialGradient><radialGradient id="ira6IAb" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.869 16.305)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iG6Zyic" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibRVbPt" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.595)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="iMKyiCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iqjonuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iXj5Yfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ioyKhxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iIHqNzb" cx="0" cy="0" r="1" gradientTransform="rotate(95.497 8.126 13.172)scale(2.31015 1.16557)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="f2_-00bry"/><stop offset="1" class="vm7-77bnv"/></radialGradient><radialGradient id="iqtBZhc" cx="0" cy="0" r="1" gradientTransform="matrix(.77484 2.11719 -.88881 .32528 20.631 6.936)" gradientUnits="userSpaceOnUse"><stop offset=".498" class="ufs9nbc8t"/><stop offset="1" class="a93s_6r2o"/></radialGradient><radialGradient id="i9lKGQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75581 -.2665 0 10.678 6.808)" gradientUnits="userSpaceOnUse"><stop class="wfmah7bqg"/><stop offset="1" class="li_sy3bgw"/></radialGradient><radialGradient id="i0DRq7e" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.577 11.67)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iRgfdpZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.571 11.953)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iRvsUZc" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.137 12.478)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="i440uXP" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.926 10.896)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iRm5Fve" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0058 -18.7218 0 16.55 4.37)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="xd-s89ceh"/><stop offset=".95" class="nqhjuybwz"/><stop offset="1" class="nde0zwcij"/></radialGradient><radialGradient id="iwtDQ6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.565 9.775)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iBE51Tl" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.512 -1.765)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i02Q7yd" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.237 11.28)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="ipuXVmd" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.265 7.894)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ie2onDc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.964 14.968)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iGIu4qb" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 18.076 5.514)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iyI2iLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.375 -.57307 .52029 20.25 6.267)" gradientUnits="userSpaceOnUse"><stop class="ku64mcgez"/><stop offset="1" class="ncfwzvbyn"/></radialGradient><radialGradient id="iAzRnqG" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.335 8.947)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iX9Tbxb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.6 -5.701)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="idpYrmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.119 14.435)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iwysxLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.3 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ibwS6ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 18.072 10.063)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ig46YIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.936 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iUpkvUM" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.65 10.198)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSqRjCe" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.737 9.992)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iFoXJFz" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.096 10.538)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iP9ippb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.988 4.91)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iwwwWqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.61 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iExHvEe" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.587 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="iIsDzIe" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.194 3.218)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iITw9jb" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".75"/></filter><filter id="iXpTLGb" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".2"/></filter><filter id="iQuQzOk" width="2.812" height="4.17" x="13.354" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="iIpB3Zz" width="2.762" height="4.17" x="16.118" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="ijoZcfd" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="i4Sjibe" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2394" result="effect2_innerShadow_4002_2394"/></filter><filter id="idlDa7c" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".075"/></filter><filter id="imy8w9y" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".075"/></filter><filter id="iUJ16ib" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".075"/></filter><filter id="iDRNBte" width="2.58" height="2.68" x="7.143" y="22.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2394" result="effect2_innerShadow_4002_2394"/></filter><filter id="imeFDoc" width="2.58" height="2.68" x="10.143" y="25.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2394" result="effect2_innerShadow_4002_2394"/></filter><filter id="iv0RUCe" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2394" result="effect2_innerShadow_4002_2394"/></filter><filter id="ilblIMb" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="i2nbVvd" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="itlogue" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.486275 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="igqB0Md" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="iFTt4Vb" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="iMvjXyb" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="iANY4kc" width="10.97" height="12.542" x="11.055" y="4.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2394" result="effect2_innerShadow_4002_2394"/></filter><filter id="ifz38Be" width="3.754" height="4.824" x="13.973" y="9.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".5"/></filter><filter id="iMMMO7c" width="2.077" height="3.1" x="15.08" y="9.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="iKfjTEb" width="3.718" height="1.573" x="14.259" y="13.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="iuX7zRb" width="2.339" height="1.19" x="17.708" y="7.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="iK6Zrge" width="2.339" height="1.176" x="12.451" y="7.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2394"/></filter><filter id="inpvuId" width=".787" height=".696" x="17.566" y="9.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="iDOvS3c" width=".891" height=".913" x="18.406" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".1"/></filter><filter id="it55VFY" width=".986" height="1.04" x="13.963" y="9.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".1"/></filter><filter id="iq7bGpc" width=".913" height=".705" x="13.209" y="9.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".05"/></filter><filter id="i53dR4c" width="1.329" height="2.379" x="10.086" y="9.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".125"/></filter><filter id="iXxaa6d" width="1.447" height="2.403" x="20.83" y="9.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".125"/></filter><filter id="ikXFcNd" width="2.405" height="1.16" x="12.37" y="7.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".125"/></filter><filter id="iDKk9vd" width="2.405" height="1.16" x="17.649" y="7.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".125"/></filter><filter id="ilugPid" width="9.346" height="5.558" x="13.961" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".5"/></filter><filter id="imUwHje" width="7.084" height="4.956" x="7.644" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2394" stdDeviation=".75"/></filter><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="iNSLv7d" x1="16.549" x2="17.449" y1="19.059" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iw1p9ce" x1="26.353" x2="26.353" y1="20.725" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="izMYsjd" x1="26.502" x2="26.502" y1="20.725" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iSUOq4d" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="yrzi8mt9l"/><stop offset=".861" class="sib0ikb9x"/></linearGradient><linearGradient id="i6AMKhc" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iWhXobb" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="izVZxIb" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iOeh8Mb" x1="11.29" x2="10.302" y1="7.341" y2="7.341" gradientUnits="userSpaceOnUse"><stop offset=".476" class="odxedybku"/><stop offset="1" class="dcrgqccad"/></linearGradient><linearGradient id="iTfhu5b" x1="21.276" x2="16.923" y1="12.581" y2="12.581" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iFAz6db" x1="16.165" x2="16.165" y1="6.564" y2="7.236" gradientUnits="userSpaceOnUse"><stop class="xdv6n4djf"/><stop offset="1" class="mapmex31y"/></linearGradient><linearGradient id="iYDZZ7b" x1="16.118" x2="16.973" y1="11.724" y2="11.724" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="ijDLAuc" x1="15.046" x2="16.12" y1="11.569" y2="11.628" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ixCjyfN" x1="16.118" x2="16.118" y1="12.123" y2="12.975" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="ieCgTJd" x1="16.118" x2="16.118" y1="9.875" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iRxxrzR" x1="16.249" x2="16.249" y1="12.797" y2="12.738" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iib5ztb" x1="19.078" x2="18.765" y1="10.033" y2="10.226" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBnjObd" x1="14.68" x2="14.367" y1="10.033" y2="10.226" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9Fyyzd" x1="22.555" x2="21.348" y1="10.06" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="io6ryIb" x1="10.269" x2="11.727" y1="10.764" y2="10.637" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="imIJaub" x1="15.61" x2="16.448" y1="2.025" y2="6.975" gradientUnits="userSpaceOnUse"><stop class="nblx7ib8n"/><stop offset="1" class="h7is5ynaf"/></linearGradient><linearGradient id="iTcwEZo" x1="17.167" x2="17.167" y1="6.928" y2="6.6" gradientUnits="userSpaceOnUse"><stop class="hj8-3eb_v"/><stop offset="1" class="zofh5ufwh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:artist-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.a93s_6r2o {
  stop-color: var(--svg-color--f2c7a3, #F2C7A3);
  stop-opacity: 0;
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b8wkgccyf {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.533-4.61-2.954c-2.718.333-4.203 3.217-3.156 6.123z");
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bkq0d2bxg {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.081 9.698a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.bu9ytxb6t {
  stop-color: var(--svg-color--ce7180, #CE7180);
}

.bvjmbzl3c {
  d: path("M19.097 10.277a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.c2bk9yb6a {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.44");
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.ct65j078y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.952h1.797");
}

.cvzy-mbfm {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.425-1.683-2.58-3.759-2.58s-3.758 1.155-3.758 2.58c0 .979.795 1.83 1.967 2.267c-.389.436-.404.98-.404 1.486l-.014.924c-.002.176.152.312.323.266c.381-.1.909-.315 1.264-.706c.378-.415.565-.814.622-1.433c.058.62.245 1.018.622 1.433c.356.391.883.605 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d2y5bebri {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.058.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.dcrgqccad {
  stop-color: var(--svg-color--f2c29b, #F2C29B);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.dnzn18v5b {
  d: path("M11.293 13.66a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.883.237-3.76.325-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.512-3.34 3.379c0 1.86.115 3.691.237 5.556");
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.ekxbkpvzc {
  d: path("M5.143 26.475c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.eoleip7ll {
  d: path("M16.119 13.792c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.208c.335.508.919.846 1.584.846c.664 0 1.248-.338 1.583-.846c.086-.129-.061-.278-.198-.209a3 3 0 0 1-1.386.329");
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.f2_-00bry {
  stop-color: var(--svg-color--ffe4b1, #FFE4B1);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftv--lbpz {
  d: path("M20.98 12.145c.335-.01.649-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02q.257-.546.345-1.18z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.ggci8dbyq {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.08 11.585q.059-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.h22tlzbbg {
  d: path("M11.064 9.037a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.h36ax9_yz {
  d: path("M16.142 18.394c-1.05 0-1.908-.507-1.908-1.291V14.41c0-1.11.858-2.017 1.908-2.017s1.91.907 1.91 2.017v2.692c0 .796-.86 1.29-1.91 1.29");
}

.h64lsvfht {
  d: path("M8.641 5.835c0-.45.345-.983.735-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.737.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H9.9c-.685 0-1.258-.429-1.258-1.139");
}

.h7is5ynaf {
  stop-color: var(--svg-color--3f334f, #3F334F);
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hfzp6f8qe {
  d: path("M27.734 23.018a.97.97 0 0 1 .967.967V26.2h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hj8-3eb_v {
  stop-color: var(--svg-color--481b64, #481B64);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hvyevjb_p {
  d: path("M7.383 29.105a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hw5lu9yyj {
  d: path("M20.632 6.934c.182.15.604.549.604 1.08c0 .323-.02.719-.04 1.039c.183.032.305.074.47.155c.003-.293.045-.701.14-.99c.049-.146.104-.28.157-.408c.158-.382.296-.715.167-1.189h-1.498z");
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i109d8bkc {
  d: path("M21.04 12.236q.1-1.596.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.i9gy75kqp {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.075c-1.248.082-2.375.649-2.978 1.739a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.365.87-.828c0-.053-.01-.107-.02-.161v-.01c-.162-.7-.054-1.29.279-1.882a.33.33 0 0 0-.075-.387");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.izb4o5hjh {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
  stop-opacity: 0;
}

.j_c7fcbhg {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
}

.j-4y6njnd {
  stop-color: var(--svg-color--41225a, #41225A);
}

.j-p-7tbjt {
  stop-color: var(--svg-color--5eccf3, #5ECCF3);
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.j3cb57bqs {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.728 9.23c-.654 0-1.205.45-1.355 1.06a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.jcgt77k7b {
  d: path("m15.736 10.18l-.531 1.839c-.109.378.152.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jujuy5bla {
  stop-color: var(--svg-color--8e5e5c, #8E5E5C);
}

.juq22w2kb {
  stop-color: var(--svg-color--ab95b9, #AB95B9);
}

.juvd2nbnb {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.708 7.807a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.jvqqj3hdm {
  stop-color: var(--svg-color--c01b54, #C01B54);
}

.jyboxmbnp {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
}

.jz78atb4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 28.562h1.797");
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.ku64mcgez {
  stop-color: var(--svg-color--cc8e73, #CC8E73);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l4zdmcczi {
  d: path("M18.302 9.502a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li_sy3bgw {
  stop-color: var(--svg-color--f0c39d, #F0C39D);
  stop-opacity: 0;
}

.lqp2zsoyq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.237 9.69c.063.086-.07.19-.22.303c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.m6v4brbmr {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.851 7.916a1.85 1.85 0 0 0-.687-.412c-.304-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.551c.48-.059.776-.028.978.035c.198.063.333.164.49.301a.277.277 0 0 0 .364-.418");
}

.m9kxmpbyp {
  stop-color: var(--svg-color--603a3e, #603A3E);
}

.mapmex31y {
  stop-color: var(--svg-color--bc7d74, #BC7D74);
  stop-opacity: 0;
}

.mbdolbbcq {
  stop-color: var(--svg-color--ff5aaa, #FF5AAA);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n2f566bzz {
  stop-color: var(--svg-color--66606e, #66606E);
  stop-opacity: 0;
}

.n39vpub1b {
  cx: 16.142px;
  cy: 17.066px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 3.844px;
  ry: 2.219px;
}

.n4l67hb-g {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
}

.nblx7ib8n {
  stop-color: var(--svg-color--352b40, #352B40);
}

.ncfwzvbyn {
  stop-color: var(--svg-color--cc8e73, #CC8E73);
  stop-opacity: 0;
}

.nde0zwcij {
  stop-color: var(--svg-color--c66683, #C66683);
}

.ngbdmdb3y {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.51 9.23c.652 0 1.204.45 1.354 1.06a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nqhjuybwz {
  stop-color: var(--svg-color--c98589, #C98589);
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o7yoj0s6u {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.114a11.5 11.5 0 0 0-.432-1.876h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.112z");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.obwtwsb6t {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.768 13.397h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.044c-.39.203-.85.32-1.351.32c-.496 0-.961-.117-1.351-.32Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odxedybku {
  stop-color: var(--svg-color--dfad98, #DFAD98);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ozk4sobpj {
  d: path("m11.55 6.901l-.402.96c-.088.268-.06.68-.06 1.18a1.6 1.6 0 0 0-.537.176v-.5c0-.15 0-.312-.154-.776l-.04-.12c-.172-.51-.274-.811-.123-1.302z");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q6lw3_bhj {
  cx: 13.665px;
  cy: 9.883px;
  rx: 0.39px;
  ry: 0.197px;
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qkhnolb2a {
  stop-color: var(--svg-color--a84f50, #A84F50);
}

.qmqo746eg {
  stop-color: var(--svg-color--e0ad88, #E0AD88);
}

.qn-z6_0fu {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
  stop-opacity: 0;
}

.qob7fubko {
  stop-color: var(--svg-color--d42045, #D42045);
}

.qppq5ybfo {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1d1qpblj {
  d: path("M18.221 19.957c-.824-.79-1.717-.937-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.467 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rau6qubfz {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.688 10.56l-.692 1.655c-.102.378.142.756.486.756h.735c.345 0 .588-.384.487-.756l-.497-1.838c-.106-.408-.408-.225-.52.182");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rm6ykeb5n {
  cx: 13.665px;
  cy: 9.883px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rqxxjhbor {
  d: path("M14.064 19.957c.824-.79 1.717-.937 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.467-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sib0ikb9x {
  stop-color: var(--svg-color--dca48b, #DCA48B);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.t_g-bg-vr {
  stop-color: var(--svg-color--a84f50, #A84F50);
  stop-opacity: 0;
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.teu3yl5ky {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M11.32 28.314a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.tf0p7nbln {
  d: path("M11.257 12.145a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.tm2bmw9uh {
  stop-color: var(--svg-color--4cc6ef, #4CC6EF);
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.ufs9nbc8t {
  stop-color: var(--svg-color--f2c7a3, #F2C7A3);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.uj-94poim {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.977c-2.718.336-4.203 3.243-3.156 6.172z");
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
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

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v42uwm11n {
  d: path("M18.237 9.69c.063.086-.07.19-.22.303c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.v481tou4o {
  d: path("M12.65 4.726c-.973-.093-2.504.103-3.147.213c-.174.135-.48.54-.31 1.08c.17.542.573.651.754.638c3.302-.637 3.92-1.815 2.703-1.93");
}

.v4czdmhgy {
  fill: var(--svg-color--000, #000);
  d: path("M17.791 10.395a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbuc_sdez {
  d: path("M9.143 17.99a10.96 10.96 0 0 1 7-2.515c2.658 0 5.097.943 7 2.514v11.986h-14z");
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vfzn0su_w {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.506z");
}

.vm7-77bnv {
  stop-color: var(--svg-color--f8cda6, #F8CDA6);
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vn7kb0bii {
  fill: var(--svg-color--000, #000);
  d: path("M14.446 10.395a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wfmah7bqg {
  stop-color: var(--svg-color--f0c39d, #F0C39D);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.wyj_je-fl {
  stop-color: var(--svg-color--c06776, #C06776);
}

.wzx61gbre {
  d: path("M14.75 10.29c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xd-s89ceh {
  stop-color: var(--svg-color--c98589, #C98589);
  stop-opacity: 0;
}

.xdv6n4djf {
  stop-color: var(--svg-color--bc7d74, #BC7D74);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.y8wf08jsl {
  d: path("M19.941 2.79c2.009.772 2.24 2.384 2.366 3.36c-3.464-.784-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.848-1.338");
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yjpqpnbll {
  stop-color: var(--svg-color--d6807d, #D6807D);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yrzi8mt9l {
  stop-color: var(--svg-color--fdc6a0, #FDC6A0);
}

.ysenjr7ha {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.68 8.04c-.258-.184-.898-.508-1.656-.381");
}

.yx08hybsl {
  d: path("M11.383 28.263a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.z95djebnq {
  d: path("M13.934 9.502a.892.892 0 0 0-.86 1.128H14.8a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zfyulebzw {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.745 8.086c.257-.184.898-.508 1.655-.38");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zofh5ufwh {
  stop-color: var(--svg-color--481b64, #481B64);
  stop-opacity: 0;
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
