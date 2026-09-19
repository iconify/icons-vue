<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ifc5Utb)" class="i7yjj4z6i"/><path fill="url(#iPsed6b)" class="pg0sa2a_j"/><path fill="url(#i2XK6se)" class="pg0sa2a_j"/><path fill="url(#igAGWwd)" class="g87bhacxy"/><path fill="url(#iCnzvcb)" class="wqh_ygxao"/><path fill="url(#ipCl0Kc)" class="wqh_ygxao"/><path fill="url(#i3HiLvc)" class="sy46vuugu"/><path fill="url(#i1puFBd)" class="v8a_hkb_s"/><path fill="url(#iShBiZd)" class="v8a_hkb_s"/><path fill="url(#idLFxfc)" class="sbaic95wn"/><path fill="url(#iB3bq9c)" class="sbaic95wn"/><path fill="url(#inVW0Db)" class="mu5a1n5sl"/><path fill="url(#itcSVXb)" class="mu5a1n5sl"/><path fill="url(#iKe0q1c)" class="b8ibh4bdb"/><path fill="url(#i8j8Ekb)" class="b8ibh4bdb"/><g filter="url(#iCATmDT)"><path fill="url(#i1S2yze)" class="f7n7_44ip"/><path fill="url(#iV2bx2d)" class="f7n7_44ip"/><path fill="url(#iWiCSkc)" class="f7n7_44ip"/></g><path fill="url(#ilKA11d)" class="y7f04ybxx"/><path fill="url(#iiXoQSb)" class="y7f04ybxx"/><path fill="url(#i3LaBTb)" class="y7f04ybxx"/><path fill="url(#iNJWmhr)" class="yyjxy1bqn"/><path fill="url(#iDLt9st)" class="yyjxy1bqn"/><path fill="url(#igosxAc)" class="d45_bzbaz"/><path fill="url(#i0P4FWm)" class="d45_bzbaz"/><path fill="url(#i83j81c)" class="mt9hohb4d"/><path fill="url(#i9uO5sd)" class="mt9hohb4d"/><path fill="url(#i0QGaib)" class="s-6wpublr"/><path fill="url(#iQtxLcs)" class="sw7gfr83a"/><path fill="url(#i6Kq8Nc)" class="sw7gfr83a"/><path fill="url(#ipW3jLc)" class="mq8q5cuov"/><path fill="url(#iroKYdc)" class="mq8q5cuov"/><path fill="url(#ipxXJ7c)" class="os-6heblz"/><path fill="url(#iyyxcte)" class="aotij57vc"/><path fill="url(#iO37Oed)" class="juk1bd46w"/><path fill="url(#iKJz3nd)" class="juk1bd46w"/><path fill="url(#ivSwKVo)" class="lk8-7bc8s"/><path fill="url(#iMg60od)" class="lk8-7bc8s"/><path fill="url(#ixm0b4d)" class="wgfjs1egm"/><path fill="url(#i1ji5Rd)" class="wgfjs1egm"/><path fill="url(#iMpwyCd)" class="wgfjs1egm"/><path class="jpjsq0bns"/><path fill="url(#icH7SHn)" class="u3fccnbtm"/><path fill="url(#i0vp3xb)" class="u3fccnbtm"/><path fill="url(#iYDga0b)" class="u3fccnbtm"/><g filter="url(#icr3gjb)"><path fill="url(#iJDyVzb)" class="dasjh-n8f"/><path fill="url(#izsvM6r)" class="dasjh-n8f"/></g><path fill="url(#ijnojBe)" class="cjmz3kkxk"/><path fill="url(#inGqmfj)" class="cjmz3kkxk"/><path fill="url(#iZjtSJc)" class="cjmz3kkxk"/><path class="dwam7_8mf"/><path fill="url(#ign2bpe)" class="s2t19_bjf"/><path fill="url(#iRdnPoM)" class="s2t19_bjf"/><path fill="url(#i6Cd84P)" class="s2t19_bjf"/><path fill="url(#i4meV6b)" class="s2t19_bjf"/><path class="i6sjzlbqf"/><path fill="url(#iBn1cUb)" class="uhlr6xbeq"/><path fill="url(#izelhFb)" class="uhlr6xbeq"/><path fill="url(#iNyGZsu)" class="uhlr6xbeq"/><path fill="url(#i2p4nGe)" class="wdm9dgblm"/><path class="ptbwqunxm"/><path fill="url(#iGFYqyb)" class="w2d1if6fy"/><path fill="url(#iyc7Dqb)" class="w2d1if6fy"/><path fill="url(#iIWfi9b)" class="w2d1if6fy"/><path fill="url(#i5S3R0h)" class="h_dnlc_1p"/><path fill="url(#iuKSmkd)" class="h_dnlc_1p"/><g filter="url(#iHSIIqe)"><path fill="url(#iXhZS3b)" class="qumyj0baz"/></g><defs><linearGradient id="ifc5Utb" x1="27.559" x2="27.559" y1="27.939" y2="30.243" gradientUnits="userSpaceOnUse"><stop class="a6uy6z3_s"/><stop offset="1" class="vbks4vevi"/></linearGradient><linearGradient id="iPsed6b" x1="5.112" x2="5.112" y1="27.197" y2="30.159" gradientUnits="userSpaceOnUse"><stop class="lx6rxrb_t"/><stop offset="1" class="cv_4o38bv"/><stop offset="1" class="sgtjuabua"/></linearGradient><linearGradient id="i2XK6se" x1="3.149" x2="3.513" y1="28.984" y2="28.984" gradientUnits="userSpaceOnUse"><stop class="jky-j58gr"/><stop offset="1" class="lw35x9b6g"/></linearGradient><linearGradient id="igAGWwd" x1="26.729" x2="26.729" y1="24.91" y2="27.349" gradientUnits="userSpaceOnUse"><stop class="ldjd0hbit"/><stop offset="1" class="ujky65brv"/></linearGradient><linearGradient id="iCnzvcb" x1="5.928" x2="5.928" y1="24.222" y2="27.06" gradientUnits="userSpaceOnUse"><stop class="vpzm4_b7z"/><stop offset="1" class="cv_4o38bv"/><stop offset="1" class="t_l_jr8ov"/></linearGradient><linearGradient id="ipCl0Kc" x1="4.112" x2="4.449" y1="26.044" y2="26.044" gradientUnits="userSpaceOnUse"><stop class="ufo7rvrwz"/><stop offset="1" class="r7gc1nakk"/></linearGradient><linearGradient id="i3HiLvc" x1="25.851" x2="25.851" y1="21.89" y2="24.249" gradientUnits="userSpaceOnUse"><stop class="ldjd0hbit"/><stop offset="1" class="ujky65brv"/></linearGradient><linearGradient id="i1puFBd" x1="6.707" x2="6.707" y1="21.224" y2="23.97" gradientUnits="userSpaceOnUse"><stop class="chn57cbqn"/><stop offset="1" class="cv_4o38bv"/><stop offset="1" class="axuvuwpca"/></linearGradient><linearGradient id="iShBiZd" x1="5.103" x2="5.401" y1="22.987" y2="22.987" gradientUnits="userSpaceOnUse"><stop class="so-u2ccpu"/><stop offset="1" class="jzhnmb74t"/></linearGradient><linearGradient id="iB3bq9c" x1="19.166" x2="18.633" y1="8.577" y2="8.577" gradientUnits="userSpaceOnUse"><stop class="k3vn7ob2v"/><stop offset="1" class="z483ahb9o"/></linearGradient><linearGradient id="i1S2yze" x1="15.473" x2="17.038" y1="3.525" y2="3.527" gradientUnits="userSpaceOnUse"><stop class="ap45r8uut"/><stop offset=".419" class="n0zgxjb6e"/><stop offset=".971" class="v08vs4bgu"/></linearGradient><linearGradient id="iV2bx2d" x1="16.113" x2="16.113" y1="5.089" y2="4.136" gradientUnits="userSpaceOnUse"><stop class="nzkoedb-r"/><stop offset=".466" class="nzkoedb-r"/><stop offset="1" class="cahcukb8j"/></linearGradient><linearGradient id="iWiCSkc" x1="16.035" x2="16.035" y1="5.246" y2="4.855" gradientUnits="userSpaceOnUse"><stop offset=".6" class="n29y5ob9p"/><stop offset="1" class="b3vj22bbc"/></linearGradient><linearGradient id="ilKA11d" x1="15.832" x2="15.832" y1="4.99" y2="6.12" gradientUnits="userSpaceOnUse"><stop offset=".499" class="q21gbz2ll"/><stop offset="1" class="jky5fxb6k"/></linearGradient><linearGradient id="iiXoQSb" x1="14.926" x2="15.605" y1="5.667" y2="5.667" gradientUnits="userSpaceOnUse"><stop offset=".274" class="s-jskprsq"/><stop offset="1" class="zypmh6yin"/></linearGradient><linearGradient id="iNJWmhr" x1="2.043" x2="30.05" y1="27.455" y2="27.455" gradientUnits="userSpaceOnUse"><stop class="hjhkwibps"/><stop offset="1" class="el-dufmch"/></linearGradient><linearGradient id="iDLt9st" x1="30.136" x2="29.428" y1="27.46" y2="27.46" gradientUnits="userSpaceOnUse"><stop class="h3t2i7bgi"/><stop offset="1" class="qf3llldgt"/></linearGradient><linearGradient id="igosxAc" x1="3.013" x2="28.999" y1="24.465" y2="24.465" gradientUnits="userSpaceOnUse"><stop class="hjhkwibps"/><stop offset="1" class="el-dufmch"/></linearGradient><linearGradient id="i0P4FWm" x1="29.079" x2="28.423" y1="24.47" y2="24.47" gradientUnits="userSpaceOnUse"><stop class="h3t2i7bgi"/><stop offset="1" class="qf3llldgt"/></linearGradient><linearGradient id="i83j81c" x1="4.052" x2="28.039" y1="21.475" y2="21.475" gradientUnits="userSpaceOnUse"><stop class="hjhkwibps"/><stop offset="1" class="el-dufmch"/></linearGradient><linearGradient id="i9uO5sd" x1="28.113" x2="27.507" y1="21.48" y2="21.48" gradientUnits="userSpaceOnUse"><stop class="h3t2i7bgi"/><stop offset="1" class="qf3llldgt"/></linearGradient><linearGradient id="i0QGaib" x1="24.923" x2="24.923" y1="18.9" y2="21.259" gradientUnits="userSpaceOnUse"><stop class="ldjd0hbit"/><stop offset="1" class="ujky65brv"/></linearGradient><linearGradient id="iQtxLcs" x1="7.569" x2="7.569" y1="18.234" y2="20.98" gradientUnits="userSpaceOnUse"><stop class="chn57cbqn"/><stop offset="1" class="cv_4o38bv"/><stop offset="1" class="axuvuwpca"/></linearGradient><linearGradient id="i6Kq8Nc" x1="6.088" x2="6.363" y1="19.997" y2="19.997" gradientUnits="userSpaceOnUse"><stop class="so-u2ccpu"/><stop offset="1" class="jzhnmb74t"/></linearGradient><linearGradient id="ipW3jLc" x1="5.002" x2="27.079" y1="18.465" y2="18.465" gradientUnits="userSpaceOnUse"><stop class="hjhkwibps"/><stop offset="1" class="el-dufmch"/></linearGradient><linearGradient id="iroKYdc" x1="27.147" x2="26.589" y1="18.47" y2="18.47" gradientUnits="userSpaceOnUse"><stop class="h3t2i7bgi"/><stop offset="1" class="qf3llldgt"/></linearGradient><linearGradient id="ipxXJ7c" x1="16.038" x2="16.038" y1="14.98" y2="17.98" gradientUnits="userSpaceOnUse"><stop class="hlonkzbio"/><stop offset="1" class="uid_4-bee"/></linearGradient><linearGradient id="iyyxcte" x1="23.16" x2="23.16" y1="15.886" y2="18.261" gradientUnits="userSpaceOnUse"><stop class="ldjd0hbit"/><stop offset="1" class="ujky65brv"/></linearGradient><linearGradient id="iO37Oed" x1="9.259" x2="9.259" y1="15.216" y2="17.98" gradientUnits="userSpaceOnUse"><stop class="wvz89qexh"/><stop offset="1" class="cv_4o38bv"/><stop offset="1" class="hk6h6db-d"/></linearGradient><linearGradient id="iKJz3nd" x1="8.085" x2="8.303" y1="16.991" y2="16.991" gradientUnits="userSpaceOnUse"><stop class="swaa01bkm"/><stop offset="1" class="n3yxg9bab"/></linearGradient><linearGradient id="ivSwKVo" x1="6.94" x2="25.038" y1="15.475" y2="15.475" gradientUnits="userSpaceOnUse"><stop class="hjhkwibps"/><stop offset="1" class="el-dufmch"/></linearGradient><linearGradient id="iMg60od" x1="25.094" x2="24.637" y1="15.48" y2="15.48" gradientUnits="userSpaceOnUse"><stop class="h3t2i7bgi"/><stop offset="1" class="qf3llldgt"/></linearGradient><linearGradient id="ixm0b4d" x1="9.038" x2="23.038" y1="19.475" y2="19.475" gradientUnits="userSpaceOnUse"><stop class="o68okgbmr"/><stop offset="1" class="bp0yexutn"/></linearGradient><linearGradient id="iMpwyCd" x1="16.035" x2="16.035" y1="8.777" y2="9.003" gradientUnits="userSpaceOnUse"><stop offset=".207" class="n97xw4bws"/><stop offset="1" class="jw6n6kwii"/></linearGradient><linearGradient id="i0vp3xb" x1="20.324" x2="19.09" y1="27.118" y2="27.118" gradientUnits="userSpaceOnUse"><stop class="bwll6oe0j"/><stop offset="1" class="jjq5zku4r"/></linearGradient><linearGradient id="iYDga0b" x1="12.035" x2="12.693" y1="27.492" y2="27.492" gradientUnits="userSpaceOnUse"><stop class="bwll6oe0j"/><stop offset="1" class="jjq5zku4r"/></linearGradient><linearGradient id="iJDyVzb" x1="14.035" x2="18.341" y1="27.884" y2="27.716" gradientUnits="userSpaceOnUse"><stop class="ixddwybat"/><stop offset="1" class="zs-mzd-bv"/></linearGradient><linearGradient id="izsvM6r" x1="14.035" x2="14.53" y1="28.325" y2="28.325" gradientUnits="userSpaceOnUse"><stop class="iju6_gr_u"/><stop offset="1" class="x9f0oobkd"/></linearGradient><linearGradient id="ijnojBe" x1="16.441" x2="16.441" y1="22.95" y2="18.168" gradientUnits="userSpaceOnUse"><stop class="of49turua"/><stop offset="1" class="u5vmmoa0n"/></linearGradient><linearGradient id="iRdnPoM" x1="15.047" x2="15.047" y1="24.215" y2="23.333" gradientUnits="userSpaceOnUse"><stop offset=".432" class="elt15hq2e"/><stop offset="1" class="hq7nzhy3q"/></linearGradient><linearGradient id="izelhFb" x1="15.226" x2="15.226" y1="21.217" y2="20.329" gradientUnits="userSpaceOnUse"><stop offset=".432" class="elt15hq2e"/><stop offset="1" class="hq7nzhy3q"/></linearGradient><linearGradient id="i2p4nGe" x1="14.038" x2="18.026" y1="15.489" y2="15.489" gradientUnits="userSpaceOnUse"><stop class="czsgrhb9l"/><stop offset="1" class="dlg1h5ffy"/></linearGradient><linearGradient id="iyc7Dqb" x1="15.39" x2="15.39" y1="18.214" y2="17.336" gradientUnits="userSpaceOnUse"><stop offset=".432" class="elt15hq2e"/><stop offset="1" class="hq7nzhy3q"/></linearGradient><linearGradient id="iuKSmkd" x1="16.035" x2="16.035" y1="15.079" y2="14.781" gradientUnits="userSpaceOnUse"><stop class="s1whs2b5n"/><stop offset="1" class="xo2q7x1zb"/></linearGradient><radialGradient id="idLFxfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.47017 -4.34899 0 16.035 7.98)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="slkg0wbub"/><stop offset="1" class="a91-o4bbg"/></radialGradient><radialGradient id="inVW0Db" cx="0" cy="0" r="1" gradientTransform="matrix(-5.83345 0 0 -1.6165 19.049 7.48)" gradientUnits="userSpaceOnUse"><stop class="p77m720kg"/><stop offset="1" class="yw9hyh44o"/></radialGradient><radialGradient id="itcSVXb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.08399 0 0 -.55407 18.746 7.383)" gradientUnits="userSpaceOnUse"><stop class="eg4ywi-fe"/><stop offset="1" class="j4ugox3hk"/></radialGradient><radialGradient id="iKe0q1c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.35938 0 0 -1.25007 17.629 6.98)" gradientUnits="userSpaceOnUse"><stop class="ofvir99da"/><stop offset="1" class="ueso2mbef"/></radialGradient><radialGradient id="i8j8Ekb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26099 0 0 -31.8795 18.296 6.98)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="ivm9wr4gw"/><stop offset="1" class="d8ny32h0h"/></radialGradient><radialGradient id="i3LaBTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.66624 0 0 -.70313 17.045 5.3)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="fgax9ko8y"/><stop offset="1" class="tq2al3bwg"/></radialGradient><radialGradient id="i1ji5Rd" cx="0" cy="0" r="1" gradientTransform="rotate(-121.562 16.708 7.191)scale(17.9899 16.9883)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="skyqirbvh"/><stop offset="1" class="l0-guebfu"/></radialGradient><radialGradient id="icH7SHn" cx="0" cy="0" r="1" gradientTransform="matrix(0 .6079 -5.91125 0 16.04 23.776)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="w5zy1ac4d"/><stop offset="1" class="bgs9e0bfo"/></radialGradient><radialGradient id="inGqmfj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .5 -3.83375 0 15.9 17.855)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="w5zy1ac4d"/><stop offset="1" class="bgs9e0bfo"/></radialGradient><radialGradient id="iZjtSJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46875 -3.59414 0 15.9 20.996)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="w5zy1ac4d"/><stop offset="1" class="bgs9e0bfo"/></radialGradient><radialGradient id="ign2bpe" cx="0" cy="0" r="1" gradientTransform="matrix(7.99072 1.7295 -.76148 3.51824 13.143 21.591)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="i1r45dlcd"/><stop offset="1" class="cw0mlsimd"/></radialGradient><radialGradient id="i6Cd84P" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.95237 2.68781 0 20.493 24.345)" gradientUnits="userSpaceOnUse"><stop class="xlnfxybxa"/><stop offset=".822" class="goygyeb-s"/></radialGradient><radialGradient id="i4meV6b" cx="0" cy="0" r="1" gradientTransform="rotate(-27.991 52.246 -8.337)scale(1.20568 1.37028)" gradientUnits="userSpaceOnUse"><stop class="u03ba0w4b"/><stop offset="1" class="ifk7n7p4r"/></radialGradient><radialGradient id="iBn1cUb" cx="0" cy="0" r="1" gradientTransform="matrix(6.6517 1.73814 -.9054 3.46487 13.64 18.58)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="i1r45dlcd"/><stop offset="1" class="cw0mlsimd"/></radialGradient><radialGradient id="iNyGZsu" cx="0" cy="0" r="1" gradientTransform="rotate(-32.688 40.55 -8.56)scale(1.05301 1.31256)" gradientUnits="userSpaceOnUse"><stop class="u03ba0w4b"/><stop offset="1" class="ifk7n7p4r"/></radialGradient><radialGradient id="iGFYqyb" cx="0" cy="0" r="1" gradientTransform="rotate(17.897 -42.485 52.638)scale(5.59966 3.48729)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="i1r45dlcd"/><stop offset="1" class="cw0mlsimd"/></radialGradient><radialGradient id="iIWfi9b" cx="0" cy="0" r="1" gradientTransform="matrix(.70996 -.56304 .75172 .9479 12.04 17.548)" gradientUnits="userSpaceOnUse"><stop class="u03ba0w4b"/><stop offset="1" class="ifk7n7p4r"/></radialGradient><radialGradient id="i5S3R0h" cx="0" cy="0" r="1" gradientTransform="rotate(133.122 5.057 10.72)scale(.75687)" gradientUnits="userSpaceOnUse"><stop class="aguw_3bek"/><stop offset="1" class="y6wx2ac9k"/></radialGradient><radialGradient id="iXhZS3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.99246 -4.65319 5.54277 -1.1822 19.736 13.367)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="ua8qkzf2i"/><stop offset="1" class="hdut1xhbb"/></radialGradient><filter id="iCATmDT" width="2.1" height="3.05" x="15.035" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745833 0 0 0 0 0.621759 0 0 0 0 0.313872 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7284"/></filter><filter id="icr3gjb" width="4.24" height="5.25" x="13.785" y="24.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.141176 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7284"/></filter><filter id="iHSIIqe" width="11.493" height="4.932" x="11.845" y="8.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7284" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hindu-temple" /></template>
<style>
.a6uy6z3_s {
  stop-color: var(--svg-color--85524f, #85524F);
}

.a91-o4bbg {
  stop-color: var(--svg-color--9a6450, #9A6450);
}

.aguw_3bek {
  stop-color: var(--svg-color--ffe863, #FFE863);
}

.aotij57vc {
  d: path("M24.035 14.98h-8.114v3h8.114z");
}

.ap45r8uut {
  stop-color: var(--svg-color--ebb932, #EBB932);
}

.axuvuwpca {
  stop-color: var(--svg-color--89584d, #89584D);
}

.b3vj22bbc {
  stop-color: var(--svg-color--b86c16, #B86C16);
  stop-opacity: 0;
}

.b8ibh4bdb {
  d: path("M19.035 6.98h-6c0-.55.45-.99.99-.99h4.01c.56-.01 1 .44 1 .99");
}

.bgs9e0bfo {
  stop-color: var(--svg-color--864840, #864840);
  stop-opacity: 0;
}

.bp0yexutn {
  stop-color: var(--svg-color--ffb336, #FFB336);
}

.bwll6oe0j {
  stop-color: var(--svg-color--96695b, #96695B);
}

.cahcukb8j {
  stop-color: var(--svg-color--ffba23, #FFBA23);
  stop-opacity: 0;
}

.chn57cbqn {
  stop-color: var(--svg-color--7d514c, #7D514C);
}

.cjmz3kkxk {
  d: path("m13.555 17.25l-1.58 5.7h7.85l-1.61-5.7z");
}

.cv_4o38bv {
  stop-color: var(--svg-color--9d6860, #9D6860);
}

.cw0mlsimd {
  stop-color: var(--svg-color--ffe666, #FFE666);
}

.czsgrhb9l {
  stop-color: var(--svg-color--3a2b47, #3A2B47);
}

.d45_bzbaz {
  d: path("M28.495 24.98H3.505c-.27 0-.5-.22-.5-.5v-.02c0-.27.22-.5.5-.5h24.99c.27 0 .5.22.5.5v.02c-.01.28-.23.5-.5.5");
}

.d8ny32h0h {
  stop-color: var(--svg-color--a96f48, #A96F48);
}

.dasjh-n8f {
  d: path("M18.025 29.98h-3.99v-4.11c0-.49.4-.89.89-.89h2.2c.49 0 .89.4.89.89v4.11z");
}

.dlg1h5ffy {
  stop-color: var(--svg-color--59466a, #59466A);
}

.dwam7_8mf {
  fill: var(--svg-color--ffce38, #FFCE38);
  d: path("M10.615 23.98h10.81c.44 0 .73-.44.53-.81l-.48-.89c-.1-.19-.3-.3-.53-.3h-9.85c-.22 0-.43.12-.53.3l-.48.89c-.19.37.09.81.53.81");
}

.eg4ywi-fe {
  stop-color: var(--svg-color--5e4a70, #5E4A70);
}

.el-dufmch {
  stop-color: var(--svg-color--503659, #503659);
}

.elt15hq2e {
  stop-color: var(--svg-color--e19620, #E19620);
}

.f7n7_44ip {
  d: path("M16.035 5.05c-.55 0-1-.44-1-.99v-.03c0-.54.45-2.03 1-2.03s1 1.49 1 2.03v.04c0 .54-.44.98-1 .98");
}

.fgax9ko8y {
  stop-color: var(--svg-color--fff169, #FFF169);
}

.ft5dv1b6b {
  fill: none;
}

.g87bhacxy {
  d: path("M28.035 23.98H15.921v3.08h12.114z");
}

.goygyeb-s {
  stop-color: var(--svg-color--ce8440, #CE8440);
  stop-opacity: 0;
}

.h_dnlc_1p {
  d: path("M16.035 14.98a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.h3t2i7bgi {
  stop-color: var(--svg-color--5d486e, #5D486E);
}

.hdut1xhbb {
  stop-color: var(--svg-color--ffc960, #FFC960);
  stop-opacity: 0;
}

.hjhkwibps {
  stop-color: var(--svg-color--271830, #271830);
}

.hk6h6db-d {
  stop-color: var(--svg-color--7a5246, #7A5246);
}

.hlonkzbio {
  stop-color: var(--svg-color--6a4532, #6A4532);
}

.hq7nzhy3q {
  stop-color: var(--svg-color--e19620, #E19620);
  stop-opacity: 0;
}

.i1r45dlcd {
  stop-color: var(--svg-color--ffe666, #FFE666);
  stop-opacity: 0;
}

.i6sjzlbqf {
  fill: var(--svg-color--ffce38, #FFCE38);
  d: path("M11.635 20.98h8.8c.44 0 .73-.44.53-.81l-.48-.89a.59.59 0 0 0-.53-.31h-7.84c-.22 0-.43.12-.53.31l-.48.89c-.19.37.09.81.53.81");
}

.i7yjj4z6i {
  d: path("M28.995 27.06H15.681v2.91h13.314z");
}

.ifk7n7p4r {
  stop-color: var(--svg-color--fcbf50, #FCBF50);
  stop-opacity: 0;
}

.iju6_gr_u {
  stop-color: var(--svg-color--5b4972, #5B4972);
}

.ivm9wr4gw {
  stop-color: var(--svg-color--a96f48, #A96F48);
  stop-opacity: 0;
}

.ixddwybat {
  stop-color: var(--svg-color--432e5a, #432E5A);
}

.j4ugox3hk {
  stop-color: var(--svg-color--5e4a70, #5E4A70);
  stop-opacity: 0;
}

.jjq5zku4r {
  stop-color: var(--svg-color--96695b, #96695B);
  stop-opacity: 0;
}

.jky-j58gr {
  stop-color: var(--svg-color--8d685d, #8D685D);
}

.jky5fxb6k {
  stop-color: var(--svg-color--db7207, #DB7207);
}

.jpjsq0bns {
  fill: var(--svg-color--aa7369, #AA7369);
  d: path("M20.045 23.04h-8.01v6.93h8.01z");
}

.juk1bd46w {
  d: path("M15.72 14.98H8.036v3h7.686z");
}

.jw6n6kwii {
  stop-color: var(--svg-color--8f4021, #8F4021);
  stop-opacity: 0;
}

.jzhnmb74t {
  stop-color: var(--svg-color--7d584c, #7D584C);
  stop-opacity: 0;
}

.k3vn7ob2v {
  stop-color: var(--svg-color--997061, #997061);
}

.l0-guebfu {
  stop-color: var(--svg-color--bd8063, #BD8063);
}

.ldjd0hbit {
  stop-color: var(--svg-color--875141, #875141);
}

.lk8-7bc8s {
  d: path("M24.525 15.99H7.445c-.28 0-.51-.23-.51-.51s.23-.51.51-.51h17.08c.28 0 .51.23.51.51s-.22.51-.51.51");
}

.lw35x9b6g {
  stop-color: var(--svg-color--896256, #896256);
  stop-opacity: 0;
}

.lx6rxrb_t {
  stop-color: var(--svg-color--895855, #895855);
}

.mq8q5cuov {
  d: path("M26.595 18.98H5.485a.49.49 0 0 1-.49-.49v-.04c0-.27.22-.49.49-.49h21.07c.29 0 .52.23.52.52v.01c0 .27-.22.49-.48.49");
}

.mt9hohb4d {
  d: path("M27.535 21.98H4.545c-.28 0-.5-.23-.5-.5c0-.28.23-.5.5-.5h22.99c.28 0 .5.23.5.5s-.22.5-.5.5");
}

.mu5a1n5sl {
  d: path("M19.485 7.98h-6.82a.49.49 0 0 1-.49-.49v-.02c0-.27.22-.49.49-.49h6.82c.27 0 .49.22.49.49v.01a.5.5 0 0 1-.49.5");
}

.n0zgxjb6e {
  stop-color: var(--svg-color--ffd94c, #FFD94C);
}

.n29y5ob9p {
  stop-color: var(--svg-color--b86c16, #B86C16);
}

.n3yxg9bab {
  stop-color: var(--svg-color--704f43, #704F43);
  stop-opacity: 0;
}

.n97xw4bws {
  stop-color: var(--svg-color--8f4021, #8F4021);
}

.nzkoedb-r {
  stop-color: var(--svg-color--ffba23, #FFBA23);
}

.o68okgbmr {
  stop-color: var(--svg-color--ea7b3a, #EA7B3A);
}

.of49turua {
  stop-color: var(--svg-color--8f5e52, #8F5E52);
}

.ofvir99da {
  stop-color: var(--svg-color--ffc866, #FFC866);
}

.os-6heblz {
  d: path("M24.035 14.98h-16v3h16z");
}

.p77m720kg {
  stop-color: var(--svg-color--50335c, #50335C);
}

.pg0sa2a_j {
  d: path("M15.92 26.96H3.066v3.02h12.856z");
}

.ptbwqunxm {
  fill: var(--svg-color--ffce38, #FFCE38);
  d: path("M12.635 17.98h6.81c.44 0 .73-.44.53-.81l-.48-.88c-.1-.19-.3-.3-.53-.3h-5.85c-.22 0-.43.12-.53.3l-.48.88c-.2.37.09.81.53.81");
}

.q21gbz2ll {
  stop-color: var(--svg-color--ffcc38, #FFCC38);
}

.qf3llldgt {
  stop-color: var(--svg-color--5d486e, #5D486E);
  stop-opacity: 0;
}

.qumyj0baz {
  d: path("M12.845 12.902h9.493c0-2.183-1.837-2.864-2.756-2.932h-6.737z");
}

.r7gc1nakk {
  stop-color: var(--svg-color--846055, #846055);
  stop-opacity: 0;
}

.s-6wpublr {
  d: path("M26.035 18H15.721v2.98h10.314z");
}

.s-jskprsq {
  stop-color: var(--svg-color--c4a25c, #C4A25C);
}

.s1whs2b5n {
  stop-color: var(--svg-color--3d2a1d, #3D2A1D);
}

.s2t19_bjf {
  d: path("M10.615 23.98h10.81c.44 0 .73-.44.53-.81l-.48-.89c-.1-.19-.3-.3-.53-.3h-9.85c-.22 0-.43.12-.53.3l-.48.89c-.19.37.09.81.53.81");
}

.sbaic95wn {
  d: path("M19.035 7.98h-6v1.99h6z");
}

.sgtjuabua {
  stop-color: var(--svg-color--9c675f, #9C675F);
}

.skyqirbvh {
  stop-color: var(--svg-color--bd8063, #BD8063);
  stop-opacity: 0;
}

.slkg0wbub {
  stop-color: var(--svg-color--74382b, #74382B);
}

.so-u2ccpu {
  stop-color: var(--svg-color--7d584c, #7D584C);
}

.sw7gfr83a {
  d: path("M15.72 18H6.026v2.98h9.696z");
}

.swaa01bkm {
  stop-color: var(--svg-color--704f43, #704F43);
}

.sy46vuugu {
  d: path("M27.075 20.99H15.721v2.98h11.354z");
}

.t_l_jr8ov {
  stop-color: var(--svg-color--87564a, #87564A);
}

.tq2al3bwg {
  stop-color: var(--svg-color--fff169, #FFF169);
  stop-opacity: 0;
}

.u03ba0w4b {
  stop-color: var(--svg-color--fcbf50, #FCBF50);
}

.u3fccnbtm {
  d: path("M20.045 23.04h-8.01v6.93h8.01z");
}

.u5vmmoa0n {
  stop-color: var(--svg-color--905d53, #905D53);
}

.ua8qkzf2i {
  stop-color: var(--svg-color--ffc960, #FFC960);
}

.ueso2mbef {
  stop-color: var(--svg-color--ec9130, #EC9130);
}

.ufo7rvrwz {
  stop-color: var(--svg-color--846055, #846055);
}

.uhlr6xbeq {
  d: path("M11.635 20.98h8.8c.44 0 .73-.44.53-.81l-.48-.89a.59.59 0 0 0-.53-.31h-7.84c-.22 0-.43.12-.53.31l-.48.89c-.19.37.09.81.53.81");
}

.uid_4-bee {
  stop-color: var(--svg-color--a2694f, #A2694F);
}

.ujky65brv {
  stop-color: var(--svg-color--876355, #876355);
}

.v08vs4bgu {
  stop-color: var(--svg-color--ffef6c, #FFEF6C);
}

.v8a_hkb_s {
  d: path("M15.535 20.99h-10.5v2.98h10.5z");
}

.vbks4vevi {
  stop-color: var(--svg-color--925f59, #925F59);
}

.vpzm4_b7z {
  stop-color: var(--svg-color--8f5a53, #8F5A53);
}

.w2d1if6fy {
  d: path("M12.635 17.98h6.81c.44 0 .73-.44.53-.81l-.48-.88c-.1-.19-.3-.3-.53-.3h-5.85c-.22 0-.43.12-.53.3l-.48.88c-.2.37.09.81.53.81");
}

.w5zy1ac4d {
  stop-color: var(--svg-color--864840, #864840);
}

.wdm9dgblm {
  d: path("M18.025 16h-3.99c0-.56.46-1.02 1.02-1.02h1.95c.57 0 1.02.46 1.02 1.02");
}

.wgfjs1egm {
  d: path("M23.035 29.98h-14v-17c0-2.21 1.761-3.843 4-4s3.99-.13 6 0s4 1.79 4 4z");
}

.wqh_ygxao {
  d: path("M15.92 23.98H4.036v3.08h11.886z");
}

.wvz89qexh {
  stop-color: var(--svg-color--85584b, #85584B);
}

.x9f0oobkd {
  stop-color: var(--svg-color--5b4972, #5B4972);
  stop-opacity: 0;
}

.xlnfxybxa {
  stop-color: var(--svg-color--ce8440, #CE8440);
}

.xo2q7x1zb {
  stop-color: var(--svg-color--3d2a1d, #3D2A1D);
  stop-opacity: 0;
}

.y6wx2ac9k {
  stop-color: var(--svg-color--c29827, #C29827);
}

.y7f04ybxx {
  d: path("M16.545 5.99h-1.01c-.27 0-.5-.22-.5-.5c0-.27.22-.5.5-.5h1.01c.27 0 .5.22.5.5c-.01.28-.23.5-.5.5");
}

.yw9hyh44o {
  stop-color: var(--svg-color--2e263a, #2E263A);
}

.yyjxy1bqn {
  d: path("M29.535 27.97H2.545c-.28 0-.51-.23-.51-.51s.23-.51.51-.51h26.99c.28 0 .51.23.51.51c-.01.28-.23.51-.51.51");
}

.z483ahb9o {
  stop-color: var(--svg-color--997061, #997061);
  stop-opacity: 0;
}

.zs-mzd-bv {
  stop-color: var(--svg-color--4a3260, #4A3260);
}

.zypmh6yin {
  stop-color: var(--svg-color--c4a25c, #C4A25C);
  stop-opacity: 0;
}

</style>
