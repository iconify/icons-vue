<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQiRM2d)" class="zbs2xvbkg"/><path fill="url(#inA3Tpe)" class="zbs2xvbkg"/><path fill="url(#iP1im0c)" class="zbs2xvbkg"/><path fill="url(#i04jDnj)" class="zbs2xvbkg"/><g filter="url(#iSYLvld)"><path clip-rule="evenodd" class="z22rj_0ie"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iiTgSIb)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#iWXnalc)"><path fill="url(#iZYJJTd)" class="fawsh83wa"/><path fill="url(#in5HY3d)" class="fawsh83wa"/></g><g filter="url(#iWsg67b)"><path fill="url(#iCgYo9c)" class="qs7c013mg"/><path fill="url(#izKufic)" class="qs7c013mg"/><path fill="url(#i8efCLe)" class="qs7c013mg"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#ip7cfvd)"><path fill="url(#iIo36rp)" class="pepvmtr_g"/><path fill="url(#ignAelv)" class="pepvmtr_g"/></g><path fill="url(#iqkeVzb)" class="l29svp3cg"/><path fill="url(#ib6zMLd)" class="l29svp3cg"/><g filter="url(#iNVGFVc)"><path fill="url(#izcCUib)" class="vx8yiwdcw"/></g><g filter="url(#iexWYqe)"><path class="oh_l9db2x"/></g><g filter="url(#iQ6rINb)"><path class="teu3yl5ky"/></g><g filter="url(#iwK83Gb)"><path class="waw2uhbiy"/></g><g filter="url(#iYmKCBd)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iGY3dOd)"><path fill="url(#iyQIgyc)" class="k1aaqobwu"/></g><g filter="url(#i1AObdi)"><path fill="url(#iO8TsTc)" class="i20220bfm"/></g><path fill="url(#i4gM3yb)" class="i20220bfm"/><path fill="url(#iV8Mmud)" class="fomm8__lp"/><path fill="url(#iHCrQkX)" class="fomm8__lp"/><path fill="url(#i5sdV9b)" class="hfzp6f8qe"/><path fill="url(#ipDnGwe)" class="hfzp6f8qe"/><path fill="url(#iTfdAvb)" class="kb0m86bqf"/><path fill="url(#iTkYgvd)" class="kb0m86bqf"/><path fill="url(#iqMfzad)" class="kb0m86bqf"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iMs2ZOe)" class="s80w1fafw"/><g filter="url(#isgg88e)"><path fill="url(#i1FSYJc)" class="iouks0fsc"/><path fill="url(#iZLdWle)" class="iouks0fsc"/><path fill="url(#iZaoaBd)" class="iouks0fsc"/><path fill="url(#iP3rqkj)" class="iouks0fsc"/></g><path fill="url(#ieEgdTd)" class="yf6m5abnn"/><g filter="url(#iupEWhc)"><path fill="url(#iSbgAfc)" class="uhuv92bap"/><path fill="url(#ibiMAze)" class="uhuv92bap"/><path fill="url(#iR3m9Xd)" class="uhuv92bap"/><path fill="url(#ixbEKEd)" class="uhuv92bap"/></g><g filter="url(#ifR7JDb)"><path fill="url(#iZhxhxc)" class="m2-b5ia7e"/><path fill="url(#i7IXbwv)" class="m2-b5ia7e"/><path fill="url(#iKkzrpi)" class="m2-b5ia7e"/><path fill="url(#ibg8boe)" class="m2-b5ia7e"/><path fill="url(#iLHHOUb)" class="m2-b5ia7e"/></g><g filter="url(#iaBVcDX)"><path stroke="url(#iYsvVDb)" class="erhzk6yjc"/></g><g filter="url(#i99YS3c)"><path stroke="url(#i1gnNXd)" class="ze5nteb_r"/></g><g filter="url(#iRjQVcj)"><path stroke="url(#ipiokXd)" class="jz78atb4u"/></g><path fill="url(#iGlLfCv)" class="losru4bel"/><path fill="url(#iKqtpKd)" class="tf0p7nbln"/><g filter="url(#ipDecwb)"><path fill="url(#id87gEe)" class="ywk3e-b4z"/><path fill="url(#iKScPub)" class="ywk3e-b4z"/></g><path fill="url(#iEtsCZd)" class="ywk3e-b4z"/><path fill="url(#ibtJK6d)" class="ywk3e-b4z"/><path fill="url(#iUgdNFc)" class="ywk3e-b4z"/><path fill="url(#ipc2ZvK)" class="ywk3e-b4z"/><path fill="url(#i9zJuVb)" class="ywk3e-b4z"/><path fill="url(#imfxmyb)" class="ywk3e-b4z"/><path fill="url(#idn35qe)" class="ywk3e-b4z"/><path fill="url(#i7PTyhb)" class="ywk3e-b4z"/><g filter="url(#ivxgvBd)"><path class="loah0bb2w"/></g><g filter="url(#i97QgHd)"><path class="aj4yjnbth"/><path fill="url(#imqcu6b)" class="lp61y1zgl"/><path fill="url(#irZg2te)" class="lp61y1zgl"/><path fill="url(#iVp38ib)" class="lp61y1zgl"/><path fill="url(#iKi6slb)" class="lp61y1zgl"/><path fill="url(#imL429b)" class="lp61y1zgl"/></g><path fill="url(#iIeGANd)" class="lp61y1zgl"/><path fill="url(#iNxu3xe)" class="lp61y1zgl"/><g filter="url(#idr6wOm)"><path stroke="url(#iD8gNLb)" class="cv8tjdzfs"/></g><path fill="url(#i8otUtb)" class="e7peg26gt"/><g filter="url(#ibwgIRc)"><path class="q79l5g4-a"/></g><g filter="url(#iP01V8M)"><path class="w82jcmbhc"/></g><path class="ehb5frb3h"/><path fill="url(#i8DhG3c)" class="l4zdmcczi"/><path class="a0howkbme"/><g filter="url(#i4Chlyd)"><path class="ji4uo5i0x"/><path fill="url(#ikTtkCc)" class="m8ouzbazk"/></g><g filter="url(#i4tjFcb)"><path fill="url(#iib5ztb)" class="bvjmbzl3c"/></g><path class="j3cb57bqs"/><path fill="url(#i3hgtHe)" class="z95djebnq"/><path class="gq90w5buk"/><g filter="url(#ifZMRMX)"><path fill="url(#ia5x5bc)" class="s5c612bqd"/></g><g filter="url(#iMUAzad)"><ellipse transform="rotate(-27.914 13.665 9.884)" class="ovba5yo4d"/><ellipse fill="url(#i2xgk8c)" transform="rotate(-27.914 13.665 9.884)" class="rqu2pe9rw"/></g><path fill="url(#iU6rKve)" class="loiafdb0j"/><path fill="url(#iJYhArb)" class="loiafdb0j"/><path fill="url(#iYIYJfw)" class="loiafdb0j"/><path fill="url(#ic5xgje)" class="loiafdb0j"/><path fill="url(#ixqE1Ly)" class="fkfj26tkv"/><path fill="url(#iNHG25b)" class="fkfj26tkv"/><g filter="url(#ivlgsSb)"><path fill="url(#izPgB8c)" class="b_l67obrv"/></g><g filter="url(#iIIi5ee)"><path fill="url(#iI2mfRb)" class="te2-39nwx"/></g><g filter="url(#iuvMV2d)"><path class="mpkw_8ozd"/></g><g filter="url(#i8pXYlc)"><path class="klu_4pupl"/></g><path fill="url(#i4GvNkv)" class="j35-nnb-y"/><path fill="url(#iIKEmrd)" class="j35-nnb-y"/><path fill="url(#im5NIWZ)" class="cko565ilp"/><path fill="url(#iqaLjtd)" class="cko565ilp"/><path fill="url(#ivLslwb)" class="h64lsvfht"/><path fill="url(#iwwwWqe)" class="h64lsvfht"/><path fill="url(#iOqiw5c)" class="h64lsvfht"/><g filter="url(#i80jV1b)"><path fill="url(#iExHvEe)" class="wsy30g7or"/></g><g filter="url(#iWYg9DM)"><path fill="url(#iIsDzIe)" class="bf_i2h2gj"/></g><defs><radialGradient id="iQiRM2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.974)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="iP1im0c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.974)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="in5HY3d" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.421 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iyQIgyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.784)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="iV8Mmud" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.707 -2.70976 0 16.143 17.096)" gradientUnits="userSpaceOnUse"><stop class="p0j4b-lzn"/><stop offset=".302" class="oag6sccml"/><stop offset=".541" class="oag6sccml"/><stop offset=".86" class="nn_fvmbqn"/></radialGradient><radialGradient id="iHCrQkX" cx="0" cy="0" r="1" gradientTransform="matrix(4.11096 1.03855 -.6137 2.42921 14.233 16.566)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="tmsrz7obr"/><stop offset=".952" class="hhhkmvb_w"/></radialGradient><radialGradient id="i5sdV9b" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.869 16.305)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="ipDnGwe" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibiMAze" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.594)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="i7IXbwv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iKkzrpi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.573)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ibg8boe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.823)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iLHHOUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iGlLfCv" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.93 20.918)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iKqtpKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 10.062 12.327)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="id87gEe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.926 10.895)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iKScPub" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.604 8.187)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ibtJK6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.4062 -9.93973 0 16.677 5.274)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="ri6vmsbau"/><stop offset="1" class="vm3mqb_2t"/></radialGradient><radialGradient id="iUgdNFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.565 9.582)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="ipc2ZvK" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.74 -2.12)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="i9zJuVb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.588 6.25)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="imfxmyb" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.327 8.162)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="idn35qe" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.2 13.85)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i7PTyhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.902 10.4)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="irZg2te" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.585 12.256)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iKi6slb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.7 11.687)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iNxu3xe" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.993 9.014)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="i8otUtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.627 14.519)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i8DhG3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.3 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ikTtkCc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.5 .606)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3hgtHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.936 9.98)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i2xgk8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.65 10.198)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJYhArb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.736 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iYIYJfw" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.096 10.538)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="ic5xgje" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.21 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iNHG25b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.203 10.634)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="izPgB8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.204 10.637)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="i4GvNkv" cx="0" cy="0" r="1" gradientTransform="matrix(.10988 2.06825 -.2705 .01437 21.685 6.576)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="qwl9q8o9t"/><stop offset="1" class="n_ukvtboy"/></radialGradient><radialGradient id="iIKEmrd" cx="0" cy="0" r="1" gradientTransform="matrix(.77484 2.11719 -.88881 .32528 20.631 6.936)" gradientUnits="userSpaceOnUse"><stop offset=".498" class="p55q20b3x"/><stop offset="1" class="ijc6fwbiz"/></radialGradient><radialGradient id="iqaLjtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75581 -.2665 0 10.678 6.809)" gradientUnits="userSpaceOnUse"><stop class="ewa7x-bzc"/><stop offset="1" class="d_3euloor"/></radialGradient><radialGradient id="iwwwWqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.61 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iExHvEe" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.587 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="iIsDzIe" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.194 3.218)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iSYLvld" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".75"/></filter><filter id="iiTgSIb" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".2"/></filter><filter id="iWXnalc" width="2.812" height="4.17" x="13.354" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="iWsg67b" width="2.762" height="4.17" x="16.118" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="ip7cfvd" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="iNVGFVc" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2391" result="effect2_innerShadow_4002_2391"/></filter><filter id="iexWYqe" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".075"/></filter><filter id="iQ6rINb" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".075"/></filter><filter id="iwK83Gb" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".075"/></filter><filter id="iYmKCBd" width="2.58" height="2.68" x="7.143" y="22.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2391" result="effect2_innerShadow_4002_2391"/></filter><filter id="iGY3dOd" width="2.58" height="2.68" x="10.143" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2391" result="effect2_innerShadow_4002_2391"/></filter><filter id="i1AObdi" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2391" result="effect2_innerShadow_4002_2391"/></filter><filter id="isgg88e" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="iupEWhc" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="ifR7JDb" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="iaBVcDX" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".05"/></filter><filter id="i99YS3c" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".05"/></filter><filter id="iRjQVcj" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".05"/></filter><filter id="ipDecwb" width="11.22" height="12.442" x="11.055" y="4.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2391" result="effect2_innerShadow_4002_2391"/></filter><filter id="ivxgvBd" width="3.633" height="4.9" x="14.103" y="9.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".5"/></filter><filter id="i97QgHd" width="2.277" height="3.3" x="14.98" y="9.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".1"/></filter><filter id="idr6wOm" width="3.718" height="1.573" x="14.259" y="13.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".05"/></filter><filter id="ibwgIRc" width="2.339" height="1.19" x="17.707" y="7.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="iP01V8M" width="2.339" height="1.176" x="12.451" y="7.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2391"/></filter><filter id="i4Chlyd" width=".787" height=".696" x="17.566" y="9.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".05"/></filter><filter id="i4tjFcb" width=".891" height=".913" x="18.406" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".1"/></filter><filter id="ifZMRMX" width=".986" height="1.04" x="13.963" y="9.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".1"/></filter><filter id="iMUAzad" width=".913" height=".705" x="13.209" y="9.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".05"/></filter><filter id="ivlgsSb" width="1.329" height="2.379" x="10.037" y="9.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".125"/></filter><filter id="iIIi5ee" width="1.806" height="2.758" x="20.669" y="9.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".25"/></filter><filter id="iuvMV2d" width="2.305" height="1.06" x="12.42" y="7.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".1"/></filter><filter id="i8pXYlc" width="2.255" height="1.01" x="17.761" y="7.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".1"/></filter><filter id="i80jV1b" width="9.346" height="5.558" x="13.961" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".5"/></filter><filter id="iWYg9DM" width="7.084" height="4.956" x="7.644" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2391" stdDeviation=".75"/></filter><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="izKufic" x1="16.549" x2="17.449" y1="19.058" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iMs2ZOe" x1="26.353" x2="26.353" y1="20.724" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="iP3rqkj" x1="26.502" x2="26.502" y1="20.724" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iZhxhxc" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="a87gyab7w"/></linearGradient><linearGradient id="iYsvVDb" x1="24.525" x2="26.234" y1="26.031" y2="26.031" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i1gnNXd" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ipiokXd" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iEtsCZd" x1="21.275" x2="18.747" y1="12.581" y2="12.581" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="imqcu6b" x1="16.957" x2="16.118" y1="11.57" y2="11.605" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iVp38ib" x1="16.118" x2="16.118" y1="12.709" y2="12.245" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="imL429b" x1="16.118" x2="16.118" y1="10.004" y2="10.551" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iIeGANd" x1="16.534" x2="16.534" y1="12.847" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="iD8gNLb" x1="14.917" x2="15.235" y1="14.28" y2="13.446" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iib5ztb" x1="19.078" x2="18.765" y1="10.033" y2="10.226" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ia5x5bc" x1="14.68" x2="14.366" y1="10.033" y2="10.226" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iU6rKve" x1="22.555" x2="21.348" y1="10.06" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="ixqE1Ly" x1="10.269" x2="11.727" y1="10.764" y2="10.637" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iI2mfRb" x1="21.572" x2="21.572" y1="9.751" y2="11.509" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="im5NIWZ" x1="11.29" x2="10.302" y1="7.342" y2="7.342" gradientUnits="userSpaceOnUse"><stop offset=".476" class="a6lkn19wf"/><stop offset="1" class="ilv7egb3p"/></linearGradient><linearGradient id="ivLslwb" x1="15.61" x2="16.448" y1="2.025" y2="6.974" gradientUnits="userSpaceOnUse"><stop class="nblx7ib8n"/><stop offset="1" class="h7is5ynaf"/></linearGradient><linearGradient id="iOqiw5c" x1="17.167" x2="17.167" y1="6.928" y2="6.599" gradientUnits="userSpaceOnUse"><stop class="hj8-3eb_v"/><stop offset="1" class="zofh5ufwh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:artist-medium" /></template>
<style>
.a0howkbme {
  fill: var(--svg-color--000, #000);
  d: path("M17.791 10.395a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a6lkn19wf {
  stop-color: var(--svg-color--4d2840, #4D2840);
}

.a87gyab7w {
  stop-color: var(--svg-color--a57c6f, #A57C6F);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
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

.aj4yjnbth {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.736 10.18l-.532 1.84c-.108.377.152.755.521.755h.787c.368 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.b_l67obrv {
  d: path("M11.033 9.697a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bf_i2h2gj {
  d: path("M12.65 4.726c-.973-.093-2.504.103-3.147.212c-.174.136-.48.541-.31 1.082c.17.54.573.65.754.637c3.302-.637 3.92-1.815 2.703-1.931");
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bvjmbzl3c {
  d: path("M19.097 10.277a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cko565ilp {
  d: path("m11.55 6.901l-.402.96c-.088.268-.06.68-.06 1.18a1.6 1.6 0 0 0-.537.176v-.5c0-.15 0-.312-.154-.776l-.04-.12c-.172-.51-.274-.81-.123-1.302z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.cv8tjdzfs {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.768 13.397h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.044c-.39.203-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.d_3euloor {
  stop-color: var(--svg-color--5e4b48, #5E4B48);
  stop-opacity: 0;
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7peg26gt {
  d: path("M16.118 13.792c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.ehb5frb3h {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.51 9.23c.652 0 1.204.45 1.354 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272A1.4 1.4 0 0 1 18.51 9.23");
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

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.erhzk6yjc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.953h1.797");
}

.ewa7x-bzc {
  stop-color: var(--svg-color--5e4b48, #5E4B48);
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fawsh83wa {
  d: path("M14.064 19.957c.824-.79 1.717-.938 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.466-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fkfj26tkv {
  d: path("M11.074 9.032a1.62 1.62 0 0 0-1.392 1.598c0 .859.673 1.56 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.fomm8__lp {
  d: path("M16.142 18.394c-1.05 0-1.908-.507-1.908-1.291V14.41c0-1.109.858-2.016 1.908-2.016s1.91.907 1.91 2.017v2.692c0 .796-.86 1.29-1.91 1.29");
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gq90w5buk {
  fill: var(--svg-color--000, #000);
  d: path("M14.445 10.395a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.235");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.h64lsvfht {
  d: path("M8.641 5.835c0-.45.345-.983.735-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.737.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H9.9c-.685 0-1.258-.429-1.258-1.139");
}

.h7is5ynaf {
  stop-color: var(--svg-color--3f334f, #3F334F);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hfzp6f8qe {
  d: path("M27.734 23.018a.97.97 0 0 1 .967.967V26.2h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.hhhkmvb_w {
  stop-color: var(--svg-color--6c2a39, #6C2A39);
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hj8-3eb_v {
  stop-color: var(--svg-color--481b64, #481B64);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i20220bfm {
  d: path("M7.383 29.104a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ijc6fwbiz {
  stop-color: var(--svg-color--4b2b3f, #4B2B3F);
  stop-opacity: 0;
}

.ilv7egb3p {
  stop-color: var(--svg-color--564140, #564140);
}

.iouks0fsc {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.115c-.099-.66-.234-1.26-.432-1.875h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.111z");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
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

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j35-nnb-y {
  d: path("M20.632 6.933c.182.152.604.55.604 1.08c0 .324-.02.72-.04 1.04c.183.032.305.074.47.155c.003-.293.045-.701.14-.99c.049-.146.104-.28.157-.408c.158-.382.296-.715.167-1.189h-1.498z");
}

.j3cb57bqs {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.728 9.23c-.654 0-1.205.45-1.355 1.06a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.ji4uo5i0x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.237 9.69c.063.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
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

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k1aaqobwu {
  d: path("M11.383 28.264a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.kb0m86bqf {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.505z");
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.klu_4pupl {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.716 8.03c-.257-.183-.897-.508-1.655-.38");
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l29svp3cg {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.532-4.61-2.954c-2.718.334-4.203 3.217-3.156 6.123z");
}

.l4zdmcczi {
  d: path("M18.302 9.502a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.loah0bb2w {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.677 10.377l-.553 1.838c-.094.378.133.756.453.756h.684c.32 0 .547-.384.453-.756l-.462-1.838c-.1-.408-.471-.408-.575 0");
}

.loiafdb0j {
  d: path("M21.04 12.236q.1-1.595.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.losru4bel {
  d: path("M20.98 12.145c.335-.01.649-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.lp61y1zgl {
  d: path("m15.736 10.18l-.532 1.84c-.108.377.152.755.521.755h.787c.368 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.m2-b5ia7e {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.m8ouzbazk {
  d: path("M18.237 9.69c.063.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.m9kxmpbyp {
  stop-color: var(--svg-color--603a3e, #603A3E);
}

.mbdolbbcq {
  stop-color: var(--svg-color--ff5aaa, #FF5AAA);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mpkw_8ozd {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.745 8.086c.257-.184.898-.508 1.655-.381");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n_ukvtboy {
  stop-color: var(--svg-color--4f3739, #4F3739);
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

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nblx7ib8n {
  stop-color: var(--svg-color--352b40, #352B40);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nn_fvmbqn {
  stop-color: var(--svg-color--974e6d, #974E6D);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.oag6sccml {
  stop-color: var(--svg-color--a66471, #A66471);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.ovba5yo4d {
  cx: 13.665px;
  cy: 9.884px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p0j4b-lzn {
  stop-color: var(--svg-color--a2546f, #A2546F);
}

.p55q20b3x {
  stop-color: var(--svg-color--4b2b3f, #4B2B3F);
}

.pepvmtr_g {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.441");
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q79l5g4-a {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.851 7.916a1.85 1.85 0 0 0-.687-.412c-.305-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.55c.48-.058.776-.027.978.036c.198.063.333.164.49.301a.277.277 0 0 0 .364-.418");
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
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

.qs7c013mg {
  d: path("M18.221 19.957c-.824-.79-1.717-.938-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.466 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwl9q8o9t {
  stop-color: var(--svg-color--5f4948, #5F4948);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.ri6vmsbau {
  stop-color: var(--svg-color--9c6173, #9C6173);
  stop-opacity: 0;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rqu2pe9rw {
  cx: 13.665px;
  cy: 9.884px;
  rx: 0.39px;
  ry: 0.197px;
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s5c612bqd {
  d: path("M14.75 10.29c0-.288-.235-.48-.298-.539l-.289.279l.178.361z");
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.te2-39nwx {
  d: path("m21.169 11.509l.094-1.758c.401.054.711.426.711.876c0 .484-.36.878-.805.882");
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

.tmsrz7obr {
  stop-color: var(--svg-color--6c2a39, #6C2A39);
  stop-opacity: 0;
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uhuv92bap {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.076c-1.248.083-2.375.65-2.978 1.74a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.366.87-.828c0-.054-.01-.107-.02-.161v-.01c-.162-.7-.054-1.291.279-1.882a.33.33 0 0 0-.075-.387");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vm3mqb_2t {
  stop-color: var(--svg-color--a14d77, #A14D77);
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.vx8yiwdcw {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.976c-2.718.336-4.203 3.242-3.156 6.171z");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w82jcmbhc {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.707 7.807a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.002.001a.277.277 0 0 1-.34-.438z");
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wsy30g7or {
  d: path("M19.941 2.79c2.009.772 2.24 2.384 2.366 3.36c-3.464-.783-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.848-1.338");
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yf6m5abnn {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.059.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.ywk3e-b4z {
  d: path("M11.293 13.66a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.378-1.432h-1.4c-.955 0-1.82-.564-2.212-1.443a.66.66 0 0 0-.616-.419h-1.273c-1.845 0-3.34 1.513-3.34 3.38c0 1.86.115 3.69.237 5.556");
}

.z22rj_0ie {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.424-1.683-2.579-3.759-2.579s-3.758 1.155-3.758 2.579c0 .979.795 1.83 1.967 2.267c-.389.437-.404.981-.404 1.486l-.014.924c-.002.177.152.312.323.267c.381-.101.909-.316 1.264-.707c.378-.414.565-.813.622-1.433c.058.62.245 1.019.622 1.433c.356.391.883.606 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.z95djebnq {
  d: path("M13.934 9.502a.892.892 0 0 0-.86 1.128H14.8a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.zbs2xvbkg {
  d: path("M9.143 17.989a10.96 10.96 0 0 1 7-2.514c2.658 0 5.097.943 7 2.514v11.985h-14z");
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zofh5ufwh {
  stop-color: var(--svg-color--481b64, #481B64);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
