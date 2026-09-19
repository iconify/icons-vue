<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><g filter="url(#iFyWrBM)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#iHzqzWU)"><path class="ii_vcdblz"/></g><g filter="url(#ix7r19d)"><path class="x9-b3hbfy"/></g><g filter="url(#iS08beb)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iZLtlOc)" class="ndlc49hkf"/><path fill="url(#iHff3Oe)" class="ndlc49hkf"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOpcCOc)" class="u-q3e7b8s"/><path fill="url(#iaOlMpd)" class="mrp1fzb0j"/><path fill="url(#iWrosSc)" class="fbjx3y-qb"/><path fill="url(#iCaej1b)" class="fbjx3y-qb"/><g filter="url(#iv5TUde)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iUEJUid)" class="ue1gv6enh"/><path fill="url(#i294t4w)" class="ue1gv6enh"/><g filter="url(#izl3Cic)"><path fill="url(#igKMsTc)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#ihrn5ae)"><path fill="url(#iihSoeM)" class="qtzewq2gr"/><path fill="url(#iF0Rg2f)" class="qtzewq2gr"/><path fill="url(#ipTDZnb)" class="qtzewq2gr"/><path fill="url(#iYLl5be)" class="qtzewq2gr"/><path fill="url(#iraLl9d)" class="qtzewq2gr"/></g><g filter="url(#i6IPcue)"><path stroke="url(#imDQL6b)" class="bzs2-ddka"/></g><g filter="url(#iT39vIc)"><path stroke="url(#izU3q4b)" class="pjsi77bhr"/></g><g filter="url(#iLVSPcD)"><path stroke="url(#iRvkNBs)" class="oool1tdti"/></g><path fill="url(#i01FGlb)" class="tagaeklzk"/><path fill="url(#iCjKjhc)" class="gepvdybmy"/><g filter="url(#iSbEi6c)"><path fill="url(#ij1kVUc)" class="fytj70bfu"/></g><path fill="url(#iUy5fpc)" class="fytj70bfu"/><path fill="url(#ip3zo2d)" class="fytj70bfu"/><path fill="url(#i7vBaXb)" class="fytj70bfu"/><path fill="url(#inuKOMd)" class="fytj70bfu"/><path fill="url(#izj6nnb)" class="fytj70bfu"/><path fill="url(#idsWaFd)" class="fytj70bfu"/><path fill="url(#i3M2UVc)" class="fytj70bfu"/><path fill="url(#iWrvs0c)" class="fytj70bfu"/><path fill="url(#iDiuGPc)" class="fytj70bfu"/><path fill="url(#ipyi0Jc)" class="fytj70bfu"/><g filter="url(#iCNDzHd)"><path class="scfy24bxc"/></g><g filter="url(#iyPhfJe)"><path class="u34cyqbih"/><path fill="url(#iN2W5wZ)" class="pdszzxbwx"/><path fill="url(#isPz7Pb)" class="pdszzxbwx"/><path fill="url(#izmDKAb)" class="pdszzxbwx"/><path fill="url(#im9Xitb)" class="pdszzxbwx"/><path fill="url(#i9PmPEd)" class="pdszzxbwx"/></g><g filter="url(#iT5OYEc)"><path stroke="url(#iTUS2mc)" class="tadvv5bzp"/></g><path fill="url(#i0NEE3N)" class="a--_rwbzu"/><g filter="url(#iCjZWjd)"><path class="u_8m62q9h"/></g><g filter="url(#iF89wwb)"><path class="ggyazjbvt"/></g><path class="hbd74rbhc"/><path fill="url(#iJSBhrc)" class="i7-q4i4gv"/><path class="t6zrydbnh"/><g filter="url(#i3k30Kc)"><path class="hm1urwb5k"/><path fill="url(#i7Dd5Gb)" class="dnhtcubjq"/></g><g filter="url(#ig7s70b)"><path fill="url(#iOAeqAb)" class="gg9zsqq5x"/></g><path class="k0j70z43j"/><path fill="url(#i1p7mTd)" class="wqouu2b2u"/><path class="rvb3y3bkj"/><g filter="url(#i6Ch7Jc)"><path fill="url(#iFXRo5c)" class="oexjz8u4y"/></g><g filter="url(#iPR3yld)"><ellipse transform="rotate(-27.914 12.232 9.819)" class="e3vivxbiw"/><ellipse fill="url(#iV8gmXc)" transform="rotate(-27.914 12.232 9.819)" class="py0n-wnry"/></g><path fill="url(#i8PJI9d)" class="x1_659jhp"/><path fill="url(#i8ASaxb)" class="vm6kozbyx"/><path fill="url(#iE6f4pe)" class="vm6kozbyx"/><g filter="url(#ipWkUzc)"><path fill="url(#iJ2r5De)" class="wub42gcda"/></g><g filter="url(#ijkDMuc)"><path fill="url(#iOTSlsv)" class="fg1b9sbrt"/></g><g filter="url(#iTeJmGe)"><path class="e1qleybzx"/></g><g filter="url(#i7tNkne)"><path class="qpqhz-bxq"/></g><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#iZ3Mxad)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#iJNcUHb)"><path class="ojb-ttbmo"/></g><g filter="url(#ibWzSJe)"><path class="ac3zfwb5z"/></g><path fill="url(#id2fsop)" class="juswexddr"/><path class="fky_p_b8b"/><defs><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOpcCOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ap92plmur"/><stop offset="1" class="c5np98r4l"/></radialGradient><radialGradient id="iaOlMpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.27186 -2.19763 0 14.734 16.875)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="cno2zybqp"/><stop offset="1" class="ydiwmubvk"/></radialGradient><radialGradient id="iWrosSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7453 1.74043 -2.1505 -2.15651 26.541 23.373)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iCaej1b" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 26.205 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="i294t4w" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="wp6rq3sqk"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="iF0Rg2f" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ipTDZnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iYLl5be" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iraLl9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i01FGlb" cx="0" cy="0" r="1" gradientTransform="rotate(79.857 2.687 17.858)scale(1.73016 1.88552)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="iiczbibai"/><stop offset="1" class="vtyalwber"/></radialGradient><radialGradient id="ij1kVUc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33067 0 0 -9.4299 17.597 10.85)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="ip3zo2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04238 12.66789 -10.49045 -.8632 16.347 4.821)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i7vBaXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17094 1.44903 0 17.229 9.512)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="inuKOMd" cx="0" cy="0" r="1" gradientTransform="matrix(.004 -1.1158 1.21425 .00436 12.388 9.56)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="izj6nnb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.93 6.217)scale(8.68032 22.1739)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="idsWaFd" cx="0" cy="0" r="1" gradientTransform="matrix(4.1531 -2.70038 .98852 1.52032 9.159 6.44)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="i3M2UVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23027 2.78124 -2.47793 -1.0961 16.012 6.772)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="r11xmpxbx"/><stop offset="1" class="fd7ydq-_q"/></radialGradient><radialGradient id="iDiuGPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.53125 -4.1875 0 19.793 7.647)" gradientUnits="userSpaceOnUse"><stop class="vfg64cc9d"/><stop offset="1" class="d1dzdpbjg"/></radialGradient><radialGradient id="isPz7Pb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2489 -.78227 0 15.21 12.395)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="im9Xitb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55106 .71115 -1.14287 -2.49268 15.328 11.814)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i0NEE3N" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73491 2.95674 0 14.734 14.46)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iJSBhrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82728 -1.31588 0 16.959 9.917)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7Dd5Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23648 -.30473 .41955 -.32557 16.726 10.002)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1p7mTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82732 -1.31594 0 12.509 9.917)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iV8gmXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00789 -.5038 .60559 -.00948 12.217 10.14)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iE6f4pe" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .538 8.895)scale(2.15831 2.12182)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iJ2r5De" cx="0" cy="0" r="1" gradientTransform="matrix(-.9345 .1604 -.07075 -.41217 9.772 10.588)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><radialGradient id="id2fsop" cx="0" cy="0" r="1" gradientTransform="matrix(.76716 -1.1875 .58464 .3777 8.815 9.178)" gradientUnits="userSpaceOnUse"><stop class="x5dswhbpl"/><stop offset="1" class="di274ba4w"/></radialGradient><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iZLtlOc" x1="8.242" x2="21.651" y1="9.948" y2="9.948" gradientUnits="userSpaceOnUse"><stop offset=".006" class="z-f4zlb4n"/><stop offset="1" class="z88owpbip"/></linearGradient><linearGradient id="iHff3Oe" x1="17.985" x2="17.985" y1="10.031" y2="9.742" gradientUnits="userSpaceOnUse"><stop class="q9u3nxbxg"/><stop offset="1" class="lvlvw7bgp"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="iUEJUid" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop class="ec1jnjbjz"/><stop offset="1" class="yd41utmlw"/></linearGradient><linearGradient id="igKMsTc" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="avgmeibok"/><stop offset="1" class="lasn3qwok"/></linearGradient><linearGradient id="iihSoeM" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="imDQL6b" x1="22.748" x2="24.458" y1="26.08" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="izU3q4b" x1="22.67" x2="24.38" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iRvkNBs" x1="22.748" x2="24.458" y1="28.689" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iCjKjhc" x1="8.854" x2="9.676" y1="12.655" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="n2adl7bcq"/><stop offset="1" class="x_ag45brq"/></linearGradient><linearGradient id="iUy5fpc" x1="19.992" x2="15.554" y1="12.569" y2="12.569" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iWrvs0c" x1="14.782" x2="14.782" y1="17.226" y2="16.573" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="ipyi0Jc" x1="14.782" x2="14.782" y1="6.991" y2="7.741" gradientUnits="userSpaceOnUse"><stop class="avceakoex"/><stop offset="1" class="ip_vqma3v"/></linearGradient><linearGradient id="iN2W5wZ" x1="15.588" x2="14.734" y1="11.696" y2="11.731" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="izmDKAb" x1="14.734" x2="14.734" y1="12.857" y2="12.383" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="i9PmPEd" x1="14.734" x2="14.734" y1="9.845" y2="10.656" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iTUS2mc" x1="13.508" x2="13.833" y1="14.302" y2="13.451" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iOAeqAb" x1="17.752" x2="17.432" y1="9.972" y2="10.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFXRo5c" x1="13.267" x2="12.947" y1="9.972" y2="10.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8PJI9d" x1="20.027" x2="20.668" y1="12.218" y2="9.156" gradientUnits="userSpaceOnUse"><stop offset=".397" class="he-2_t6fu"/><stop offset="1" class="sffy0dbuv"/></linearGradient><linearGradient id="i8ASaxb" x1="8.769" x2="10.256" y1="10.717" y2="10.587" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iOTSlsv" x1="20.354" x2="20.354" y1="9.621" y2="11.561" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient><filter id="iFyWrBM" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="iHzqzWU" width="5.492" height="8.119" x="9.76" y="14.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".5"/></filter><filter id="ix7r19d" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".5"/></filter><filter id="iS08beb" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="iv5TUde" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="izl3Cic" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="ihrn5ae" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="i6IPcue" width="2.097" height=".3" x="22.598" y="25.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".05"/></filter><filter id="iT39vIc" width="2.097" height=".3" x="22.52" y="27.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".05"/></filter><filter id="iLVSPcD" width="2.097" height=".3" x="22.598" y="28.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".05"/></filter><filter id="iSbEi6c" width="11.421" height="12.784" x="9.571" y="4.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2020" result="effect2_innerShadow_4002_2020"/></filter><filter id="iCNDzHd" width="3.914" height="4.957" x="12.565" y="9.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".5"/></filter><filter id="iyPhfJe" width="2.314" height="3.357" x="13.577" y="9.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".1"/></filter><filter id="iT5OYEc" width="3.682" height="1.494" x="12.893" y="13.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".05"/></filter><filter id="iCjZWjd" width="2.383" height="1.21" x="16.354" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="iF89wwb" width="2.383" height="1.195" x="10.994" y="7.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="i3k30Kc" width=".798" height=".706" x="16.212" y="9.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".05"/></filter><filter id="ig7s70b" width=".901" height=".923" x="17.07" y="9.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".1"/></filter><filter id="i6Ch7Jc" width=".998" height="1.053" x="12.54" y="9.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".1"/></filter><filter id="iPR3yld" width=".927" height=".714" x="11.769" y="9.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".05"/></filter><filter id="ipWkUzc" width="1.345" height="2.416" x="8.587" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".125"/></filter><filter id="ijkDMuc" width="1.465" height="2.441" x="19.621" y="9.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".125"/></filter><filter id="iTeJmGe" width="2.238" height=".968" x="11.019" y="7.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".1"/></filter><filter id="i7tNkne" width="2.238" height=".97" x="16.402" y="7.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2020" stdDeviation=".1"/></filter><filter id="iZ3Mxad" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2020" result="effect2_innerShadow_4002_2020"/></filter><filter id="iJNcUHb" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter><filter id="ibWzSJe" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2020"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:factory-worker-dark" /></template>
<style>
.a--_rwbzu {
  d: path("M14.734 13.804a3.06 3.06 0 0 1-1.413-.335c-.14-.07-.29.087-.202.214a1.93 1.93 0 0 0 1.615.862a1.93 1.93 0 0 0 1.614-.862c.088-.132-.062-.284-.202-.213c-.409.213-.89.334-1.412.334");
}

.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ap92plmur {
  stop-color: var(--svg-color--655676, #655676);
  stop-opacity: 0;
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.avceakoex {
  stop-color: var(--svg-color--3c2129, #3C2129);
}

.avgmeibok {
  stop-color: var(--svg-color--73d7ff, #73D7FF);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.bzs2-ddka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 26.002h1.797");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5np98r4l {
  stop-color: var(--svg-color--655676, #655676);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cno2zybqp {
  stop-color: var(--svg-color--3e1d2a, #3E1D2A);
}

.d1dzdpbjg {
  stop-color: var(--svg-color--4c2f2c, #4C2F2C);
  stop-opacity: 0;
}

.d7sh3eboe {
  stop-color: var(--svg-color--26386d, #26386D);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.di274ba4w {
  stop-color: var(--svg-color--130618, #130618);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dnhtcubjq {
  d: path("M16.894 9.623c.065.086-.07.192-.225.307c-.154.116-.268.197-.333.11s.007-.25.161-.366s.332-.138.397-.051");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1qleybzx {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.294 8.249c.262-.188.915-.519 1.688-.389");
}

.e3vivxbiw {
  cx: 12.232px;
  cy: 9.819px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.ec1jnjbjz {
  stop-color: var(--svg-color--675479, #675479);
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fd7ydq-_q {
  stop-color: var(--svg-color--473438, #473438);
  stop-opacity: 0;
}

.fg1b9sbrt {
  d: path("M19.871 11.561q.06-.97.113-1.94a.974.974 0 0 1-.113 1.94");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fky_p_b8b {
  fill: var(--svg-color--0d0413, #0D0413);
  d: path("M19.94 7.598c.24.172.54.448.756.691v1.024a2.1 2.1 0 0 0-.765-.357q.01-.475.01-.952c0-.096.008-.312 0-.406");
}

.ft5dv1b6b {
  fill: none;
}

.fytj70bfu {
  d: path("M9.814 13.67a3.99 3.99 0 0 0 3.962 3.473H15.7c2.005 0 3.7-1.482 3.962-3.473c.12-1.92.241-3.834.33-5.753a1.48 1.48 0 0 0-1.406-1.46H17.16a2.47 2.47 0 0 1-2.256-1.472a.68.68 0 0 0-.627-.426h-1.298c-1.882 0-3.407 1.542-3.407 3.445c0 1.897.118 3.764.243 5.666");
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.gepvdybmy {
  d: path("M9.777 12.125a1.67 1.67 0 0 1-.923-.315v.95c0 .91.543 1.722 1.368 2.059a4.2 4.2 0 0 1-.353-1.204z");
}

.gg9zsqq5x {
  d: path("M17.771 10.22a.86.86 0 0 0-.236-.471l-.265.29l.12.233z");
}

.ggyazjbvt {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.256 7.963a2.83 2.83 0 0 1 1.773-.366a.283.283 0 0 1-.069.561a2.26 2.26 0 0 0-1.414.29a1 1 0 0 0-.093.062l-.003.002a.283.283 0 0 1-.346-.447z");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hbd74rbhc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.172 9.153c.666 0 1.228.46 1.381 1.08a.28.28 0 0 1-.273.347h-2.275a.235.235 0 0 1-.231-.277a1.425 1.425 0 0 1 1.398-1.15");
}

.he-2_t6fu {
  stop-color: var(--svg-color--432c30, #432C30);
}

.hm1urwb5k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.894 9.623c.065.086-.07.192-.225.307c-.154.116-.268.197-.333.11s.007-.25.161-.366s.332-.138.397-.051");
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.i7-q4i4gv {
  d: path("M16.96 9.43a.91.91 0 0 1 .878 1.15H16.08a.914.914 0 0 1 .881-1.15");
}

.ii_vcdblz {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M10.76 16.494v4.63c-.002.26.024.579.25.72c.234.144.581-.02.743-.142l2.5-1.765V15.78a11 11 0 0 0-3.492.713");
}

.iiczbibai {
  stop-color: var(--svg-color--3e3d3d, #3E3D3D);
}

.ip_vqma3v {
  stop-color: var(--svg-color--3c2129, #3C2129);
  stop-opacity: 0;
}

.it1_ig0bc {
  stop-color: var(--svg-color--57525e, #57525E);
}

.iv7bj_baj {
  stop-color: var(--svg-color--4680db, #4680DB);
  stop-opacity: 0;
}

.ixw-oi7aq {
  stop-color: var(--svg-color--3d3248, #3D3248);
}

.iycy_sbnz {
  d: path("M7.366 8.01h-.707a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.707c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j0xtzac4y {
  stop-color: var(--svg-color--4d79b0, #4D79B0);
  stop-opacity: 0;
}

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
}

.javsik_yi {
  fill: var(--svg-color--f3d8ed, #F3D8ED);
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.juswexddr {
  d: path("M9.582 7.718a7 7 0 0 0-.767.739v.82c.219-.168.48-.281.765-.321q-.01-.475-.01-.952q0-.144.012-.286");
}

.k0j70z43j {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.296 9.153c-.666 0-1.229.459-1.382 1.08a.28.28 0 0 0 .273.347h2.275a.235.235 0 0 0 .232-.277a1.43 1.43 0 0 0-1.398-1.15");
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kc9q3mbff {
  fill: var(--svg-color--c6c6c6, #C6C6C6);
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.ky_dg6bhp {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.lasn3qwok {
  stop-color: var(--svg-color--93ffff, #93FFFF);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo1ogpbbw {
  stop-color: var(--svg-color--391f48, #391F48);
  stop-opacity: 0;
}

.lt_b3wboz {
  d: path("m3.769 30l4-.02l-.06-11.94a11 11 0 0 0-3.563 5.482c-.262.948-.4 1.947-.397 2.978z");
}

.ltwsa8bld {
  d: path("M7.757 10.031c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.47c.27 0 .48-.22.48-.48v-3.24c0-2.36-1.91-4.27-4.27-4.27h-7.45a4.253 4.253 0 0 0-4.27 4.26v3.24c0 .27.21.49.48.49z");
}

.lvlvw7bgp {
  stop-color: var(--svg-color--513a64, #513A64);
  stop-opacity: 0;
}

.m1_q07_me {
  stop-color: var(--svg-color--6899f0, #6899F0);
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
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

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mrp1fzb0j {
  d: path("M14.734 18.039c-1.216 0-2.198-.93-2.198-2.083v-2.589c0-1.142.982-2.073 2.198-2.073s2.197.93 2.197 2.083v2.59c-.01 1.142-.992 2.072-2.197 2.072");
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.n2adl7bcq {
  stop-color: var(--svg-color--443b38, #443B38);
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ndlc49hkf {
  d: path("M21.974 6.741H7.744v3.29h14.23z");
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oexjz8u4y {
  d: path("M13.338 10.234c0-.295-.239-.49-.304-.55l-.294.284l.181.369z");
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oool1tdti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 28.611h1.797");
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p3_97vb4n {
  stop-color: var(--svg-color--465e8a, #465E8A);
  stop-opacity: 0;
}

.p64oiyb7x {
  stop-color: var(--svg-color--55406a, #55406A);
}

.p7prpqhjw {
  stop-color: var(--svg-color--5da7f2, #5DA7F2);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pdszzxbwx {
  d: path("m14.344 10.279l-.542 1.874c-.11.386.155.772.53.772h.803c.376 0 .641-.392.53-.772l-.541-1.874c-.117-.415-.659-.415-.78 0");
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pjsi77bhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.67 27.307h1.797");
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

.py0n-wnry {
  cx: 12.232px;
  cy: 9.819px;
  rx: 0.397px;
  ry: 0.201px;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q9u3nxbxg {
  stop-color: var(--svg-color--513a64, #513A64);
}

.qgmif2bih {
  stop-color: var(--svg-color--57525e, #57525E);
  stop-opacity: 0;
}

.qo28zhh9b {
  stop-color: var(--svg-color--3a2252, #3A2252);
}

.qpqhz-bxq {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M18.365 8.21c-.22-.237-.818-.515-1.688-.39");
}

.qtzewq2gr {
  d: path("M22.13 25.326c0-.402.326-.732.727-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qv8wc6zla {
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r11xmpxbx {
  stop-color: var(--svg-color--473438, #473438);
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rq76sybla {
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.rtj8_6bqg {
  stop-color: var(--svg-color--2a3765, #2A3765);
}

.rvb3y3bkj {
  fill: var(--svg-color--000, #000);
  d: path("M13.028 10.34a.52.52 0 0 0-.521-.521a.52.52 0 0 0-.464.761h.923a.5.5 0 0 0 .062-.24");
}

.s1a8ycb7r {
  stop-color: var(--svg-color--362d41, #362D41);
}

.s1rw4px-b {
  stop-color: var(--svg-color--465e8a, #465E8A);
}

.s21zh4b3w {
  stop-color: var(--svg-color--3d78d0, #3D78D0);
  stop-opacity: 0;
}

.s5pm96b_v {
  stop-color: var(--svg-color--3578e5, #3578E5);
  stop-opacity: 0;
}

.sb1phf9zd {
  d: path("M20.979 4.68H8.719v2.65h12.26z");
}

.scfy24bxc {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.238 10.478l-.647 1.875c-.111.386.155.771.53.771h.802c.376 0 .642-.391.531-.771l-.542-1.875c-.116-.415-.552-.415-.674 0");
}

.sffy0dbuv {
  stop-color: var(--svg-color--1c0c13, #1C0C13);
}

.sq-bwm1qa {
  stop-color: var(--svg-color--1f54c5, #1F54C5);
}

.t6zrydbnh {
  fill: var(--svg-color--000, #000);
  d: path("M16.44 10.34c0-.29.231-.521.52-.521a.52.52 0 0 1 .464.76h-.922a.5.5 0 0 1-.062-.239");
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.tadvv5bzp {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.344 13.425c.402.21.88.33 1.39.33a3 3 0 0 0 1.39-.33a.21.21 0 0 1 .245.04a.19.19 0 0 1 .02.245m-3.045-.285l3.004.258m-3.004-.258a.21.21 0 0 0-.246.042a.19.19 0 0 0-.02.244m.266-.286l-.225.258m3.27.027l-.04-.027m.04.027l-.04-.027m.04.027a1.98 1.98 0 0 1-1.655.885a1.98 1.98 0 0 1-1.656-.884m3.27-.028a1.93 1.93 0 0 1-1.614.862a1.93 1.93 0 0 1-1.615-.862m-.041.028l.041-.028m-.041.028l.041-.028");
}

.tagaeklzk {
  d: path("M19.69 12.125c.342-.01.662-.127.923-.315v.95c0 .91-.543 1.722-1.367 2.059q.261-.556.352-1.204z");
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u_8m62q9h {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.54 8.082a1.9 1.9 0 0 0-.701-.42c-.31-.097-.699-.123-1.236-.057a.283.283 0 1 0 .068.561c.491-.06.792-.029.998.036c.202.064.34.167.5.307a.283.283 0 0 0 .371-.427");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u34cyqbih {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.344 10.279l-.542 1.874c-.11.386.155.772.53.772h.803c.376 0 .641-.392.53-.772l-.541-1.874c-.117-.415-.659-.415-.78 0");
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.vfg64cc9d {
  stop-color: var(--svg-color--210c18, #210C18);
}

.vm6kozbyx {
  d: path("M9.58 8.956a1.641 1.641 0 0 0 .142 3.263a80 80 0 0 1-.142-3.263");
}

.vtyalwber {
  stop-color: var(--svg-color--1e1a21, #1E1A21);
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wp6rq3sqk {
  stop-color: var(--svg-color--6e5981, #6E5981);
}

.wqouu2b2u {
  d: path("M12.507 9.43a.91.91 0 0 0-.877 1.15h1.758a1 1 0 0 0 .033-.24a.916.916 0 0 0-.914-.91");
}

.wub42gcda {
  d: path("M9.598 9.63a.975.975 0 0 0 .085 1.916a79 79 0 0 1-.085-1.917");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x_ag45brq {
  stop-color: var(--svg-color--1d1a1a, #1D1A1A);
}

.x1_659jhp {
  d: path("M19.752 12.218q.102-1.627.189-3.254a1.641 1.641 0 0 1-.189 3.254");
}

.x5dswhbpl {
  stop-color: var(--svg-color--322622, #322622);
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.yd41utmlw {
  stop-color: var(--svg-color--32263f, #32263F);
}

.ydiwmubvk {
  stop-color: var(--svg-color--1a0910, #1A0910);
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.z-f4zlb4n {
  stop-color: var(--svg-color--251229, #251229);
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z88owpbip {
  stop-color: var(--svg-color--24132c, #24132C);
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
