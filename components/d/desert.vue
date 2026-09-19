<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#i70lSNe)"><path fill="url(#iTC6hUb)" class="q8rpxkbbi"/></g><g filter="url(#i5NIvXb)"><path fill="url(#iPWeO2c)" class="nnnr_gbum"/></g><g filter="url(#iAQ7Jek)"><path fill="url(#iic28ec)" class="i67jo6bmb"/></g><path fill="url(#iVXEHbq)" class="i67jo6bmb"/><path fill="url(#iZZAWeb)" class="i67jo6bmb"/><path fill="url(#iuIkx5d)" class="i67jo6bmb"/><path fill="url(#iPiGEvd)" class="nnnr_gbum"/><path fill="url(#iIH8RVb)" class="nnnr_gbum"/><g filter="url(#i6eZYcc)"><path fill="url(#iCoDzxb)" class="fxiaypb3q"/></g><g filter="url(#itX5Xec)"><path fill="url(#iQ4FeIb)" class="tdlbrqt_m"/><path fill="url(#ighL3Vb)" class="tdlbrqt_m"/></g><g filter="url(#izC2cfd)"><path fill="url(#i5xbslc)" class="n3i0dwdxz"/><path fill="url(#iBclCFe)" class="n3i0dwdxz"/><path fill="url(#iLvp4xK)" class="n3i0dwdxz"/><path fill="url(#ivOGoDd)" class="n3i0dwdxz"/></g><g filter="url(#iaA3Pee)"><path fill="url(#iK9qBDD)" class="pfyuowcey"/></g><g filter="url(#iI59Ulc)"><path stroke="url(#iE1N6Vc)" class="kth0fu50a"/><path stroke="url(#i3P5z5d)" class="kth0fu50a"/><path stroke="url(#i4fqwrd)" class="kth0fu50a"/><path stroke="url(#iOy0svd)" class="kth0fu50a"/><path stroke="url(#iqPn9Qb)" class="kth0fu50a"/></g><path fill="url(#i3K6p8c)" class="od6dsvyzt"/><path fill="url(#iCorXFb)" class="od6dsvyzt"/><path fill="url(#i99XSDe)" class="od6dsvyzt"/><g filter="url(#i6vU8Id)"><path stroke="url(#iilxUNB)" class="xoc4iy7so"/></g><g filter="url(#i4kmH8c)"><path class="gro-6hbvt"/></g><g filter="url(#itMMCde)"><path fill="url(#iItP3uc)" clip-rule="evenodd" class="e9ql4k6xp"/><path fill="url(#iXNn81b)" clip-rule="evenodd" class="e9ql4k6xp"/><path fill="url(#ig12sRc)" clip-rule="evenodd" class="e9ql4k6xp"/><path fill="url(#iLhrelb)" clip-rule="evenodd" class="e9ql4k6xp"/><path fill="url(#ima00se)" clip-rule="evenodd" class="e9ql4k6xp"/><path fill="url(#ifVkEac)" clip-rule="evenodd" class="e9ql4k6xp"/></g><path fill="url(#iQYoxre)" clip-rule="evenodd" class="e9ql4k6xp"/><g filter="url(#iQbhuub)"><rect class="si--k3b1h"/></g><g filter="url(#i1ohuMc)"><ellipse transform="rotate(36.373 8.543 13.787)" class="hzgblcbqv"/></g><g filter="url(#iiPvuDc)"><circle fill="url(#iNuEaSd)" class="si0r81bxu"/></g><path fill="url(#ihb71YE)" clip-rule="evenodd" class="ks3oiybkr"/><g filter="url(#iYy3oQe)"><path stroke="url(#ioOsOYd)" class="frvoxdbxn"/></g><g filter="url(#ixOIejd)"><path fill="url(#iaytGId)" clip-rule="evenodd" class="va1-8_muw"/><path fill="url(#iiL64de)" clip-rule="evenodd" class="va1-8_muw"/><path fill="url(#i74gode)" clip-rule="evenodd" class="va1-8_muw"/><path fill="url(#irxZyGc)" clip-rule="evenodd" class="va1-8_muw"/><path fill="url(#iO3NFEZ)" clip-rule="evenodd" class="va1-8_muw"/></g><g filter="url(#iJVjqtP)"><path stroke="url(#iIRFfIc)" class="fm4cjacic"/></g><g filter="url(#iZTDPrd)"><ellipse class="hphlgd5ch"/></g><g filter="url(#i9L8cOw)"><ellipse class="cbdtxtetj"/></g><g filter="url(#iqU5Wde)"><ellipse transform="rotate(37.529 7.126 12.584)" class="bzdlppsil"/></g><g filter="url(#iKrJXQd)"><ellipse class="unmi71bbo"/></g><path fill="url(#iUuXZvd)" class="yon40acwh"/><path fill="url(#ij3ZCdc)" class="yon40acwh"/><path fill="url(#iUJNV1c)" class="yon40acwh"/><path fill="url(#i9lPhSd)" class="m0iw8lvga"/><path fill="url(#iPEGyOb)" class="m0iw8lvga"/><path fill="url(#iFycqTc)" class="whs02o7-r"/><path fill="url(#itc9Ace)" class="whs02o7-r"/><path fill="url(#iLdpeDe)" class="f9qx4db6g"/><path fill="url(#iquFBhb)" class="yhmwj7bym"/><path fill="url(#iQUOvje)" class="yhmwj7bym"/><path fill="url(#iUJXu7c)" class="yoz11vbqy"/><path fill="url(#i1XhBIb)" class="yoz11vbqy"/><g filter="url(#iCQ0t5d)"><path fill="url(#iXcehBc)" class="l1mr_zbyl"/><path fill="url(#idzEQEd)" class="l1mr_zbyl"/></g><path fill="url(#ixPnlZd)" class="x_cgdbc_q"/><path fill="url(#ipi3bRd)" class="x_cgdbc_q"/><g filter="url(#iRVc6dd)"><path fill="url(#i3dAE8b)" class="ea87wdb1s"/><path fill="url(#iwW8Nxd)" class="ea87wdb1s"/></g><g filter="url(#itGXqwQ)"><path fill="url(#iZv5Vie)" class="rhcjz5b3y"/><path fill="url(#iyCtHDK)" class="rhcjz5b3y"/></g><g filter="url(#iQDIpFe)"><path stroke="url(#iS2TeND)" class="rtghpro6c"/></g><g filter="url(#i5YfiUd)"><path stroke="url(#i5biIwc)" class="ztey84_sy"/></g><g filter="url(#iDTc7Fr)"><ellipse transform="rotate(-45 12.264 12.695)" class="jw98zgqzj"/></g><path fill="url(#iA1UahY)" class="sysxfe8la"/><path fill="url(#iOuMNod)" class="sysxfe8la"/><path fill="url(#iBtBJ7c)" class="sysxfe8la"/><g filter="url(#ixzryNe)"><path class="x3j6zwbza"/></g><path fill="url(#iM9iSzb)" class="abq1bubez"/><g filter="url(#iPyeoeb)"><path class="a_h3q1mbx"/></g></g><defs><linearGradient id="iTC6hUb" x1="16.016" x2="16.016" y1="1.809" y2="18.216" gradientUnits="userSpaceOnUse"><stop class="v3m9hcc-j"/><stop offset="1" class="kbvvs9tgo"/></linearGradient><linearGradient id="iic28ec" x1="20.734" x2="20.734" y1="15.103" y2="30.113" gradientUnits="userSpaceOnUse"><stop class="o19w1-bzz"/><stop offset=".595" class="rpdbctbri"/><stop offset=".921" class="budj3ibly"/></linearGradient><linearGradient id="iuIkx5d" x1="20.734" x2="20.734" y1="28.634" y2="22.608" gradientUnits="userSpaceOnUse"><stop class="wsrp1092z"/><stop offset="1" class="pddz8bbnv"/></linearGradient><linearGradient id="iPiGEvd" x1="16" x2="16" y1="30.79" y2="28.915" gradientUnits="userSpaceOnUse"><stop class="ku4cima9f"/><stop offset="1" class="v2xob-bms"/></linearGradient><linearGradient id="iIH8RVb" x1="2.432" x2="8.744" y1="28.728" y2="25.29" gradientUnits="userSpaceOnUse"><stop class="o504a6ltw"/><stop offset="1" class="cbofsibsa"/></linearGradient><linearGradient id="iCoDzxb" x1="22.506" x2="22.506" y1="5.182" y2="13.597" gradientUnits="userSpaceOnUse"><stop class="qkon2bbue"/><stop offset="1" class="v1zxeg2cn"/></linearGradient><linearGradient id="iQ4FeIb" x1="22.563" x2="22.563" y1="5.106" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="wwc08g1ih"/><stop offset="1" class="y91eqos9r"/></linearGradient><linearGradient id="i5xbslc" x1="13.125" x2="17.763" y1="20.596" y2="13.794" gradientUnits="userSpaceOnUse"><stop class="kx3v9p-is"/><stop offset="1" class="ftefj8kwb"/></linearGradient><linearGradient id="iK9qBDD" x1="17.94" x2="17.94" y1="14.037" y2="20.044" gradientUnits="userSpaceOnUse"><stop class="iv2v15bau"/><stop offset="1" class="w1l4wl4lo"/></linearGradient><linearGradient id="i3K6p8c" x1="14.98" x2="17.542" y1="20.861" y2="17.063" gradientUnits="userSpaceOnUse"><stop class="pzz0q1fii"/><stop offset="1" class="i2jd32b9u"/></linearGradient><linearGradient id="iCorXFb" x1="15.234" x2="15.234" y1="20.928" y2="20.718" gradientUnits="userSpaceOnUse"><stop class="ca4k7zb1j"/><stop offset="1" class="x7th1qq_j"/></linearGradient><linearGradient id="iItP3uc" x1="6.229" x2="6.229" y1="30.747" y2="12.991" gradientUnits="userSpaceOnUse"><stop class="hb_i703ab"/><stop offset="1" class="hz3zf-blc"/></linearGradient><linearGradient id="iXNn81b" x1="10.212" x2="10.252" y1="31.101" y2="29.864" gradientUnits="userSpaceOnUse"><stop class="fz0chvzue"/><stop offset="1" class="gl5c37tng"/></linearGradient><linearGradient id="ima00se" x1="-2.58" x2="1.501" y1="24.263" y2="24.263" gradientUnits="userSpaceOnUse"><stop class="mmiff3blk"/><stop offset="1" class="rbo_s-jjr"/></linearGradient><linearGradient id="iQYoxre" x1="1.682" x2="3.619" y1="25.603" y2="25.603" gradientUnits="userSpaceOnUse"><stop class="pxc84fh2i"/><stop offset="1" class="i4ygtp_or"/></linearGradient><linearGradient id="ihb71YE" x1="10.917" x2="10.917" y1="14.987" y2="30.535" gradientUnits="userSpaceOnUse"><stop class="j7hnwx2qq"/><stop offset="1" class="yewi5lbgy"/></linearGradient><linearGradient id="ioOsOYd" x1="11.458" x2="13.247" y1="15.563" y2="15.796" gradientUnits="userSpaceOnUse"><stop class="ro_5gddxj"/><stop offset="1" class="lv4qp2-ew"/></linearGradient><linearGradient id="iaytGId" x1="6.545" x2="6.545" y1="19.769" y2="30.601" gradientUnits="userSpaceOnUse"><stop class="e4_j17b8e"/><stop offset="1" class="m70-9iycy"/></linearGradient><linearGradient id="iiL64de" x1="8.474" x2="8.222" y1="21.436" y2="21.436" gradientUnits="userSpaceOnUse"><stop class="lz315bcby"/><stop offset="1" class="oxtivy4zd"/></linearGradient><linearGradient id="iIRFfIc" x1="7.924" x2="9.713" y1="15.563" y2="15.796" gradientUnits="userSpaceOnUse"><stop class="l3fx-cchf"/><stop offset="1" class="lv4qp2-ew"/></linearGradient><linearGradient id="iUuXZvd" x1="17.059" x2="17.976" y1="20.659" y2="21.575" gradientUnits="userSpaceOnUse"><stop class="pno2nxw-q"/><stop offset="1" class="jomfc9b8f"/></linearGradient><linearGradient id="iUJNV1c" x1="17.426" x2="17.658" y1="21.314" y2="21.071" gradientUnits="userSpaceOnUse"><stop class="hd9pe2bmk"/><stop offset="1" class="rep9lgbin"/></linearGradient><linearGradient id="i9lPhSd" x1="16.631" x2="15.649" y1="14.909" y2="13.876" gradientUnits="userSpaceOnUse"><stop class="jgr65gdmw"/><stop offset="1" class="mr-h662wk"/></linearGradient><linearGradient id="iPEGyOb" x1="15.759" x2="16.023" y1="14.755" y2="14.54" gradientUnits="userSpaceOnUse"><stop class="e27u0yb7u"/><stop offset="1" class="pmnn8bcah"/></linearGradient><linearGradient id="iFycqTc" x1="3.096" x2="2.097" y1="19.545" y2="20.544" gradientUnits="userSpaceOnUse"><stop class="xi5a2nbde"/><stop offset="1" class="yt-4_jbks"/></linearGradient><linearGradient id="iLdpeDe" x1="5.528" x2="6.737" y1="28.172" y2="28.172" gradientUnits="userSpaceOnUse"><stop class="a3-58qdsq"/><stop offset="1" class="gg0f93b8q"/><stop offset="1" class="cn_sc0vcm"/></linearGradient><linearGradient id="iquFBhb" x1="14.009" x2="12.822" y1="26.869" y2="26.869" gradientUnits="userSpaceOnUse"><stop class="k34ypyjwp"/><stop offset="1" class="gg0f93b8q"/></linearGradient><linearGradient id="iUJXu7c" x1="11.546" x2="12.567" y1="25.091" y2="23.368" gradientUnits="userSpaceOnUse"><stop class="bclz0xn3o"/><stop offset="1" class="pgg4nwb8e"/></linearGradient><linearGradient id="iXcehBc" x1="8.454" x2="7.195" y1="21.789" y2="20.475" gradientUnits="userSpaceOnUse"><stop class="bclz0xn3o"/><stop offset="1" class="pgg4nwb8e"/></linearGradient><linearGradient id="idzEQEd" x1="6.969" x2="7.482" y1="20.36" y2="20.906" gradientUnits="userSpaceOnUse"><stop class="phya_shmn"/><stop offset="1" class="bd2b-8b4v"/></linearGradient><linearGradient id="ixPnlZd" x1="11.182" x2="12.595" y1="17.681" y2="17.681" gradientUnits="userSpaceOnUse"><stop class="osu878trg"/><stop offset="1" class="rrksbku7e"/></linearGradient><linearGradient id="i3dAE8b" x1="5.528" x2="6.941" y1="16.268" y2="16.268" gradientUnits="userSpaceOnUse"><stop class="s-zkkvaky"/><stop offset="1" class="qug8vqbjp"/></linearGradient><linearGradient id="iZv5Vie" x1="7.415" x2="6.691" y1="12.538" y2="11.539" gradientUnits="userSpaceOnUse"><stop class="bclz0xn3o"/><stop offset="1" class="pgg4nwb8e"/></linearGradient><linearGradient id="iyCtHDK" x1="6.227" x2="6.521" y1="11.674" y2="12.087" gradientUnits="userSpaceOnUse"><stop class="phya_shmn"/><stop offset="1" class="bd2b-8b4v"/></linearGradient><linearGradient id="iS2TeND" x1="18.023" x2="17.343" y1="21.209" y2="20.558" gradientUnits="userSpaceOnUse"><stop class="rt1s6ex_z"/><stop offset="1" class="dv1opcdad"/></linearGradient><linearGradient id="i5biIwc" x1="16.405" x2="15.747" y1="14.633" y2="13.988" gradientUnits="userSpaceOnUse"><stop class="oy0jjgbly"/><stop offset="1" class="iecbuu4_i"/></linearGradient><linearGradient id="iA1UahY" x1="13.207" x2="12.208" y1="11.773" y2="12.773" gradientUnits="userSpaceOnUse"><stop class="ygcq6___g"/><stop offset="1" class="pr1bl8nwg"/></linearGradient><linearGradient id="iOuMNod" x1="12.413" x2="12.612" y1="11.978" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="n7n8j7bun"/><stop offset="1" class="mj1634v-j"/></linearGradient><radialGradient id="iPWeO2c" cx="0" cy="0" r="1" gradientTransform="rotate(134.157 8.2 14.331)scale(18.2627 25.3822)" gradientUnits="userSpaceOnUse"><stop class="bsvqu1bwn"/><stop offset="1" class="st-mzsb5l"/></radialGradient><radialGradient id="iVXEHbq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .86123 -.64092 0 28.67 19.525)" gradientUnits="userSpaceOnUse"><stop offset=".507" class="ebuny0gmv"/><stop offset="1" class="qk_b_8byf"/></radialGradient><radialGradient id="iZZAWeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.31752 -19.8125 0 21.307 21.29)" gradientUnits="userSpaceOnUse"><stop class="e9xz5ffid"/><stop offset="1" class="f5e-hlbpn"/></radialGradient><radialGradient id="ighL3Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33387 0 0 -7.49148 24.29 8.593)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="ywgoclbrb"/><stop offset="1" class="v3m5c3d3b"/></radialGradient><radialGradient id="iBclCFe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6026 4.55454 -5.4028 3.08732 14.597 17.099)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="ochscsbud"/><stop offset="1" class="jb87ofoqn"/></radialGradient><radialGradient id="iLvp4xK" cx="0" cy="0" r="1" gradientTransform="matrix(1.70057 0 0 1.74474 13.28 20.663)" gradientUnits="userSpaceOnUse"><stop class="cas1bibmw"/><stop offset="1" class="eqtocubaz"/></radialGradient><radialGradient id="ivOGoDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01641 .88144 -2.11656 -2.44066 18.956 14.191)" gradientUnits="userSpaceOnUse"><stop class="xczfe0g-o"/><stop offset="1" class="lhjq19zcb"/></radialGradient><radialGradient id="iE1N6Vc" cx="0" cy="0" r="1" gradientTransform="matrix(.59596 1.575 -5.6836 2.1506 15.5 18.668)" gradientUnits="userSpaceOnUse"><stop class="lvlqg1bio"/><stop offset="1" class="u3523xabg"/></radialGradient><radialGradient id="i3P5z5d" cx="0" cy="0" r="1" gradientTransform="matrix(.62943 .12147 -.53893 2.79266 16.648 17.836)" gradientUnits="userSpaceOnUse"><stop class="lvlqg1bio"/><stop offset="1" class="u3523xabg"/></radialGradient><radialGradient id="i4fqwrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.50017 -.36183 4.68953 -6.48262 16.85 20.115)" gradientUnits="userSpaceOnUse"><stop class="jsnt1acdf"/><stop offset="1" class="a-9e1knvo"/></radialGradient><radialGradient id="iOy0svd" cx="0" cy="0" r="1" gradientTransform="matrix(-.04257 -.6066 9.74986 -.6842 15.126 21.009)" gradientUnits="userSpaceOnUse"><stop class="jsnt1acdf"/><stop offset="1" class="a-9e1knvo"/></radialGradient><radialGradient id="iqPn9Qb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.771 9.304 8.67)scale(.75678 2.19774)" gradientUnits="userSpaceOnUse"><stop class="jsnt1acdf"/><stop offset="1" class="a-9e1knvo"/></radialGradient><radialGradient id="i99XSDe" cx="0" cy="0" r="1" gradientTransform="matrix(.58527 2.23062 -.7375 .1935 16.516 16.985)" gradientUnits="userSpaceOnUse"><stop class="wceq6d_3s"/><stop offset="1" class="vuk6hhbbg"/></radialGradient><radialGradient id="iilxUNB" cx="0" cy="0" r="1" gradientTransform="rotate(-133.1 12.717 6.11)scale(1.64847 6.95051)" gradientUnits="userSpaceOnUse"><stop class="m1amb3xdn"/><stop offset="1" class="bs0_ywbus"/></radialGradient><radialGradient id="ig12sRc" cx="0" cy="0" r="1" gradientTransform="rotate(127.484 -.57 15.039)scale(.75955 .41936)" gradientUnits="userSpaceOnUse"><stop offset=".474" class="k3rcqtbgh"/><stop offset="1" class="t6zp_vbou"/></radialGradient><radialGradient id="iLhrelb" cx="0" cy="0" r="1" gradientTransform="matrix(2.63064 -3.35697 8.02005 6.2848 .985 27.62)" gradientUnits="userSpaceOnUse"><stop class="mmiff3blk"/><stop offset="1" class="rbo_s-jjr"/></radialGradient><radialGradient id="ifVkEac" cx="0" cy="0" r="1" gradientTransform="rotate(133.705 -3.071 12.167)scale(1.51225 1.75331)" gradientUnits="userSpaceOnUse"><stop class="ph6oltr7q"/><stop offset="1" class="k6q60wqyz"/></radialGradient><radialGradient id="iNuEaSd" cx="0" cy="0" r="1" gradientTransform="rotate(143.49 3.58 8.682)scale(3.45304 2.67526)" gradientUnits="userSpaceOnUse"><stop class="f9pnbdchn"/><stop offset="1" class="hjqhzccrw"/></radialGradient><radialGradient id="i74gode" cx="0" cy="0" r="1" gradientTransform="matrix(-.46592 .76195 -.65397 -.39989 7.622 21.811)" gradientUnits="userSpaceOnUse"><stop class="az_czogtx"/><stop offset="1" class="rcxid8v0e"/></radialGradient><radialGradient id="irxZyGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.14588 -2.43471 0 1.086 17.593)" gradientUnits="userSpaceOnUse"><stop class="q5-sar3gn"/><stop offset="1" class="atg4m0bwe"/></radialGradient><radialGradient id="iO3NFEZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.42598 3.04336 -3.67858 -.5149 8.221 14.396)" gradientUnits="userSpaceOnUse"><stop class="z5g7nxrjl"/><stop offset="1" class="j3mnzh9sq"/></radialGradient><radialGradient id="ij3ZCdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.33459 -.30969 .31104 -.33604 18.256 21.54)" gradientUnits="userSpaceOnUse"><stop class="vz2jq3bwf"/><stop offset="1" class="sn4t7ybex"/></radialGradient><radialGradient id="itc9Ace" cx="0" cy="0" r="1" gradientTransform="rotate(135 -2.567 10.536)scale(.8433 .39892)" gradientUnits="userSpaceOnUse"><stop class="o8cz93b2v"/><stop offset="1" class="xowusrb5d"/></radialGradient><radialGradient id="iQUOvje" cx="0" cy="0" r="1" gradientTransform="matrix(-.28264 0 0 -.27433 13.884 26.751)" gradientUnits="userSpaceOnUse"><stop class="qq23hkxyl"/><stop offset="1" class="xohfwn0yn"/></radialGradient><radialGradient id="i1XhBIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1935 .172 -.16804 -.18905 12.357 23.632)" gradientUnits="userSpaceOnUse"><stop class="s1y2gac1n"/><stop offset="1" class="xohfwn0yn"/></radialGradient><radialGradient id="ipi3bRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26167 0 0 -.21018 12.307 17.59)" gradientUnits="userSpaceOnUse"><stop class="s1y2gac1n"/><stop offset="1" class="xohfwn0yn"/></radialGradient><radialGradient id="iwW8Nxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67084 0 0 -.17668 6.798 16.268)" gradientUnits="userSpaceOnUse"><stop class="d7v28gw8g"/><stop offset="1" class="rjzrd0bnq"/></radialGradient><radialGradient id="iBtBJ7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2546 .1206 -.09618 -.20305 13.194 11.94)" gradientUnits="userSpaceOnUse"><stop class="pvv72w7rp"/><stop offset="1" class="mi77ykdnk"/></radialGradient><radialGradient id="iM9iSzb" cx="0" cy="0" r="1" gradientTransform="matrix(1.10426 -1.61224 .66886 .45812 5.925 27.82)" gradientUnits="userSpaceOnUse"><stop class="mmiff3blk"/><stop offset="1" class="rbo_s-jjr"/></radialGradient><filter id="i70lSNe" width="27.989" height="28.51" x="2.006" y="2.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="i5NIvXb" width="28.239" height="15.01" x="2.006" y="15.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.294118 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.45098 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5074" result="effect2_innerShadow_18_5074"/></filter><filter id="iAQ7Jek" width="18.72" height="15.21" x="11.274" y="15.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.490196 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="i6eZYcc" width="9.505" height="9.01" x="17.803" y="4.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.580392 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.529412 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5074" result="effect2_innerShadow_18_5074"/></filter><filter id="itX5Xec" width="7.33" height="7.23" x="18.706" y="5.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.81419 0 0 0 0 0.320833 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="izC2cfd" width="9.891" height="8.481" x="9.464" y="13.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.831373 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="iaA3Pee" width="3.281" height="6.258" x="16.299" y="13.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".5"/></filter><filter id="iI59Ulc" width="4.975" height="5.574" x="12.968" y="15.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".1"/></filter><filter id="i6vU8Id" width="4.026" height="4.622" x="13.538" y="16.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".125"/></filter><filter id="i4kmH8c" width="5.347" height="19.785" x="5.361" y="11.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation="1"/></filter><filter id="itMMCde" width="12.004" height="19.154" x="2.006" y="10.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".7"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.858824 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="iQbhuub" width="5.14" height="20.171" x="8.963" y="12.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation="1"/></filter><filter id="i1ohuMc" width="6.609" height="6.813" x="5.238" y="10.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation="1"/></filter><filter id="iiPvuDc" width="7.762" height="7.762" x="7.029" y="10.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation="1"/></filter><filter id="iYy3oQe" width=".65" height="15.418" x="11.133" y="14.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".125"/></filter><filter id="ixOIejd" width="14.349" height="23.718" x="-1.994" y="14.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_5074"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_5074" result="shape"/></filter><filter id="iJVjqtP" width=".65" height="15.132" x="7.599" y="15.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".125"/></filter><filter id="iZTDPrd" width="1.084" height="1.35" x="12.462" y="26.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".15"/></filter><filter id="i9L8cOw" width=".969" height="1.307" x="6.141" y="27.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".15"/></filter><filter id="iqU5Wde" width="1.225" height="1.316" x="6.514" y="11.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".15"/></filter><filter id="iKrJXQd" width=".976" height="1.321" x="6.166" y="15.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".15"/></filter><filter id="iCQ0t5d" width="1.485" height="2.015" x="6.969" y="20.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658297 0 0 0 0 0.716667 0 0 0 0 0.495694 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="iRVc6dd" width="1.298" height=".707" x="5.528" y="15.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.776471 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="itGXqwQ" width="1.208" height="1.258" x="6.227" y="11.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658297 0 0 0 0 0.716667 0 0 0 0 0.495694 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5074"/></filter><filter id="iQDIpFe" width="1.315" height="1.311" x="17.095" y="20.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".125"/></filter><filter id="i5YfiUd" width="1.367" height="1.359" x="15.409" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".125"/></filter><filter id="iDTc7Fr" width="1.247" height="1.247" x="11.64" y="12.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".15"/></filter><filter id="ixzryNe" width="1.572" height="1.581" x="7.022" y="20.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".125"/></filter><filter id="iPyeoeb" width="1.087" height="1.078" x="6.368" y="11.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5074" stdDeviation=".1"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:desert" /></template>
<style>
.a_h3q1mbx {
  stroke: var(--svg-color--aac28f, #AAC28F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m6.668 11.92l.487.478");
}

.a-9e1knvo {
  stop-color: var(--svg-color--47ae4a, #47AE4A);
  stop-opacity: 0;
}

.a3-58qdsq {
  stop-color: var(--svg-color--989258, #989258);
}

.abq1bubez {
  d: path("M7.659 26.206c-.345.83-1.056.981-1.37.977c-1.468 0-2.38-.634-2.462-.977z");
}

.atg4m0bwe {
  stop-color: var(--svg-color--40a047, #40A047);
  stop-opacity: 0;
}

.az_czogtx {
  stop-color: var(--svg-color--2b6b33, #2B6B33);
}

.bclz0xn3o {
  stop-color: var(--svg-color--9ab584, #9AB584);
}

.bd2b-8b4v {
  stop-color: var(--svg-color--9f9652, #9F9652);
  stop-opacity: 0;
}

.bs0_ywbus {
  stop-color: var(--svg-color--5c9f65, #5C9F65);
  stop-opacity: 0;
}

.bsvqu1bwn {
  stop-color: var(--svg-color--9c5043, #9C5043);
}

.budj3ibly {
  stop-color: var(--svg-color--b45e49, #B45E49);
  stop-opacity: 0;
}

.bzdlppsil {
  cx: 7.126px;
  cy: 12.584px;
  fill: var(--svg-color--58b651, #58B651);
  rx: 0.232px;
  ry: 0.414px;
}

.ca4k7zb1j {
  stop-color: var(--svg-color--30733e, #30733E);
}

.cas1bibmw {
  stop-color: var(--svg-color--5aba57, #5ABA57);
}

.cbdtxtetj {
  cx: 6.626px;
  cy: 28.282px;
  fill: var(--svg-color--488f42, #488F42);
  rx: 0.185px;
  ry: 0.353px;
}

.cbofsibsa {
  stop-color: var(--svg-color--4f2930, #4F2930);
  stop-opacity: 0;
}

.cn_sc0vcm {
  stop-color: var(--svg-color--7f9d72, #7F9D72);
}

.d7v28gw8g {
  stop-color: var(--svg-color--97b27f, #97B27F);
}

.dv1opcdad {
  stop-color: var(--svg-color--c5c58f, #C5C58F);
  stop-opacity: 0;
}

.e27u0yb7u {
  stop-color: var(--svg-color--a6ba82, #A6BA82);
}

.e4_j17b8e {
  stop-color: var(--svg-color--279e65, #279E65);
}

.e9ql4k6xp {
  fill-rule: evenodd;
  d: path("M9.776 10.959a3.535 3.535 0 0 0-3.534 3.534v9.187H3.87c-.657 0-1.187-.53-1.187-1.187v-4.785c0-.565-.265-1.079-.676-1.412v10.536a4.7 4.7 0 0 0 1.863.382h2.373v2.87l.001.029h7.066v-15.62a3.535 3.535 0 0 0-3.533-3.534");
}

.e9xz5ffid {
  stop-color: var(--svg-color--b35f48, #B35F48);
}

.ea87wdb1s {
  d: path("M6.48 16.621h-.599a.35.35 0 0 1-.353-.353a.35.35 0 0 1 .353-.354h.6c.197 0 .245.156.245.354s-.048.353-.246.353");
}

.ebuny0gmv {
  stop-color: var(--svg-color--8f442e, #8F442E);
}

.eqtocubaz {
  stop-color: var(--svg-color--5aba57, #5ABA57);
  stop-opacity: 0;
}

.f5e-hlbpn {
  stop-color: var(--svg-color--b35f48, #B35F48);
  stop-opacity: 0;
}

.f9pnbdchn {
  stop-color: var(--svg-color--63ea9c, #63EA9C);
}

.f9qx4db6g {
  d: path("M6.53 28.636h-.649a.35.35 0 0 1-.353-.354a.35.35 0 0 1 .353-.353h.649c.198 0 .207.155.207.353s-.01.354-.207.354");
}

.fm4cjacic {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.924 15.252v14.632");
}

.frvoxdbxn {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.458 14.857v14.918");
}

.ft5dv1b6b {
  fill: none;
}

.ftefj8kwb {
  stop-color: var(--svg-color--2ccd71, #2CCD71);
}

.fxiaypb3q {
  d: path("M21.636 4.643c.36-.74 1.42-.73 1.77.01c.13.28.47.39.75.24l.17-.09c.66-.35 1.44.21 1.3.94l-.04.19c-.06.3.15.59.46.63l.19.03c.74.1 1.04 1 .49 1.51l-.14.13c-.23.21-.23.56 0 .77l.14.13c.54.51.24 1.41-.5 1.51l-.2.02c-.31.04-.52.32-.46.62l.03.19c.13.73-.65 1.28-1.3.93l-.17-.09a.544.544 0 0 0-.75.24c-.36.74-1.42.73-1.77-.01a.54.54 0 0 0-.75-.24l-.17.09c-.66.35-1.44-.21-1.3-.94l.04-.19c.06-.3-.15-.59-.46-.63l-.19-.03c-.74-.1-1.04-1-.49-1.51l.14-.13c.23-.21.23-.56 0-.77l-.14-.13c-.54-.51-.24-1.41.5-1.51l.19-.02c.31-.04.52-.32.46-.62l-.03-.19c-.13-.73.65-1.28 1.3-.93l.17.09c.29.15.63.04.76-.24");
}

.fz0chvzue {
  stop-color: var(--svg-color--518761, #518761);
}

.gg0f93b8q {
  stop-color: var(--svg-color--a0c784, #A0C784);
}

.gl5c37tng {
  stop-color: var(--svg-color--518761, #518761);
  stop-opacity: 0;
}

.gro-6hbvt {
  fill: var(--svg-color--5db65a, #5DB65A);
  d: path("M7.361 13.794h1.347v15.785H7.361z");
}

.hb_i703ab {
  stop-color: var(--svg-color--28ac6b, #28AC6B);
}

.hd9pe2bmk {
  stop-color: var(--svg-color--93a880, #93A880);
}

.hjqhzccrw {
  stop-color: var(--svg-color--63ea9c, #63EA9C);
  stop-opacity: 0;
}

.hphlgd5ch {
  cx: 13.004px;
  cy: 26.938px;
  fill: var(--svg-color--3cac34, #3CAC34);
  rx: 0.242px;
  ry: 0.375px;
}

.hz3zf-blc {
  stop-color: var(--svg-color--3ad27e, #3AD27E);
}

.hzgblcbqv {
  cx: 8.543px;
  cy: 13.787px;
  fill: var(--svg-color--5db65a, #5DB65A);
  rx: 1.173px;
  ry: 1.518px;
}

.i2jd32b9u {
  stop-color: var(--svg-color--38b47d, #38B47D);
}

.i4ygtp_or {
  stop-color: var(--svg-color--5cc253, #5CC253);
  stop-opacity: 0;
}

.i67jo6bmb {
  d: path("M29.994 19.509a.54.54 0 0 0-.52-.406a.47.47 0 0 0-.484.484c0 .28-.208.52-.488.52a.51.51 0 0 1-.496-.52v-1.973c0-.313-.252-.515-.532-.515h-.01c-.28 0-.47-.23-.47-.51v-.976c0-.28-.248-.51-.528-.51h-1.473v2.97c0 .56.421 1.02.981 1.02c.557 0 1.015.455 1.02 1.01a1.024 1.024 0 0 1-1.02 1.011h-9.33c-.86 0-1.56.7-1.56 1.56c0 .76.62 1.429 1.38 1.429h6.52c1.1 0 2 .9 2 2s-.9 2-2 2h-11.2c-.17 0-.31.14-.31.31v1.7h15.36a3.16 3.16 0 0 0 3.16-3.16v-5.11h-.007l.007-.89z");
}

.iecbuu4_i {
  stop-color: var(--svg-color--c0c682, #C0C682);
  stop-opacity: 0;
}

.iv2v15bau {
  stop-color: var(--svg-color--91e38b, #91E38B);
}

.j3mnzh9sq {
  stop-color: var(--svg-color--489e4f, #489E4F);
  stop-opacity: 0;
}

.j7hnwx2qq {
  stop-color: var(--svg-color--3ebf87, #3EBF87);
}

.jb87ofoqn {
  stop-color: var(--svg-color--5c9e61, #5C9E61);
}

.jgr65gdmw {
  stop-color: var(--svg-color--92bb7c, #92BB7C);
}

.jomfc9b8f {
  stop-color: var(--svg-color--a5a96d, #A5A96D);
}

.jsnt1acdf {
  stop-color: var(--svg-color--47ae4a, #47AE4A);
}

.jw98zgqzj {
  cx: 12.264px;
  cy: 12.695px;
  fill: var(--svg-color--53c84c, #53C84C);
  rx: 0.265px;
  ry: 0.373px;
}

.k34ypyjwp {
  stop-color: var(--svg-color--bebd70, #BEBD70);
}

.k3rcqtbgh {
  stop-color: var(--svg-color--278620, #278620);
}

.k6q60wqyz {
  stop-color: var(--svg-color--4bad46, #4BAD46);
  stop-opacity: 0;
}

.kbvvs9tgo {
  stop-color: var(--svg-color--f58137, #F58137);
}

.ks3oiybkr {
  fill-rule: evenodd;
  d: path("M11.182 14.748a.353.353 0 1 1 .706 0v15.365h-.706z");
}

.kth0fu50a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.39 20.06h-.111l.012.11l.065.615l.01.09h.989a3.29 3.29 0 0 0 3.287-3.288V16.34a.44.44 0 0 0-.88 0v1.247c0 1.327-1.146 2.473-2.473 2.473z");
}

.ku4cima9f {
  stop-color: var(--svg-color--5a2141, #5A2141);
}

.kx3v9p-is {
  stop-color: var(--svg-color--3edb81, #3EDB81);
}

.l1mr_zbyl {
  d: path("m7.075 20.968l1.28 1.307v-1.018l-.778-.791a.35.35 0 0 0-.502 0a.35.35 0 0 0 0 .502");
}

.l3fx-cchf {
  stop-color: var(--svg-color--58b159, #58B159);
}

.lhjq19zcb {
  stop-color: var(--svg-color--91db89, #91DB89);
  stop-opacity: 0;
}

.lv4qp2-ew {
  stop-color: var(--svg-color--668b74, #668B74);
}

.lvlqg1bio {
  stop-color: var(--svg-color--7ccd79, #7CCD79);
}

.lz315bcby {
  stop-color: var(--svg-color--5a9b5b, #5A9B5B);
}

.m0iw8lvga {
  d: path("m16.023 14.897l-.502-.502a.35.35 0 0 1 0-.502a.35.35 0 0 1 .502 0l.502.502a.35.35 0 0 1 0 .502a.35.35 0 0 1-.502 0");
}

.m1amb3xdn {
  stop-color: var(--svg-color--5c9f65, #5C9F65);
}

.m70-9iycy {
  stop-color: var(--svg-color--236d5b, #236D5B);
}

.mi77ykdnk {
  stop-color: var(--svg-color--d2d18e, #D2D18E);
  stop-opacity: 0;
}

.mj1634v-j {
  stop-color: var(--svg-color--afc786, #AFC786);
  stop-opacity: 0;
}

.mmiff3blk {
  stop-color: var(--svg-color--469747, #469747);
}

.mr-h662wk {
  stop-color: var(--svg-color--b3b75e, #B3B75E);
}

.n3i0dwdxz {
  d: path("M14.235 22.275H11.23a1.768 1.768 0 0 1 0-3.534h3.004c.657 0 1.187-.53 1.187-1.187v-1.993a1.767 1.767 0 0 1 3.534 0v1.993a4.73 4.73 0 0 1-4.721 4.721");
}

.n7n8j7bun {
  stop-color: var(--svg-color--b8d18c, #B8D18C);
}

.nnnr_gbum {
  d: path("M29.994 19.508a.54.54 0 0 0-.519-.405a.47.47 0 0 0-.483.484c0 .28-.208.52-.487.52a.51.51 0 0 1-.496-.52v-1.973c0-.313-.251-.515-.53-.515h-.01c-.28 0-.47-.23-.47-.51v-.976c0-.28-.248-.51-.528-.51h-2.188c-.71 0-1.288.58-1.288 1.29v1.204c0 .28-.21.51-.49.51h-.995c-.28 0-.509.23-.509.51v.985c0 .28-.23.51-.51.51h-3.977a.48.48 0 0 0-.49.49c0 .28-.23.51-.51.51H2.007v5.84c0 1.74 1.408 3.16 3.155 3.16H26.84a3.16 3.16 0 0 0 3.155-3.16v-5.11h-.007l.007-.87z");
}

.o19w1-bzz {
  stop-color: var(--svg-color--b76246, #B76246);
}

.o504a6ltw {
  stop-color: var(--svg-color--4f2930, #4F2930);
}

.o8cz93b2v {
  stop-color: var(--svg-color--bec284, #BEC284);
}

.ochscsbud {
  stop-color: var(--svg-color--5c9e61, #5C9E61);
  stop-opacity: 0;
}

.od6dsvyzt {
  d: path("M17.189 15.907a.353.353 0 0 0-.354.354v1.293c0 1.435-1.166 2.6-2.6 2.6h-.933v.707h.933a3.31 3.31 0 0 0 3.307-3.307v-1.293a.353.353 0 0 0-.353-.354");
}

.osu878trg {
  stop-color: var(--svg-color--9ebb83, #9EBB83);
}

.oxtivy4zd {
  stop-color: var(--svg-color--5a9b5b, #5A9B5B);
  stop-opacity: 0;
}

.oy0jjgbly {
  stop-color: var(--svg-color--bad39f, #BAD39F);
}

.pddz8bbnv {
  stop-color: var(--svg-color--713c3f, #713C3F);
  stop-opacity: 0;
}

.pfyuowcey {
  d: path("M17.3 15.3a.64.64 0 0 1 1.281 0v2.337c0 .707-.574 1.281-1.282 1.281z");
}

.pgg4nwb8e {
  stop-color: var(--svg-color--b2ac5e, #B2AC5E);
}

.ph6oltr7q {
  stop-color: var(--svg-color--4bad46, #4BAD46);
}

.phya_shmn {
  stop-color: var(--svg-color--9f9652, #9F9652);
}

.pmnn8bcah {
  stop-color: var(--svg-color--a6ba82, #A6BA82);
  stop-opacity: 0;
}

.pno2nxw-q {
  stop-color: var(--svg-color--86b372, #86B372);
}

.pr1bl8nwg {
  stop-color: var(--svg-color--96c47d, #96C47D);
}

.pvv72w7rp {
  stop-color: var(--svg-color--d2d18e, #D2D18E);
}

.pxc84fh2i {
  stop-color: var(--svg-color--3ac87b, #3AC87B);
}

.pzz0q1fii {
  stop-color: var(--svg-color--11875f, #11875F);
}

.q5-sar3gn {
  stop-color: var(--svg-color--40a047, #40A047);
}

.q8rpxkbbi {
  d: path("M26.824 2.103H5.166c-1.75 0-3.16 1.41-3.16 3.16v21.69a3.16 3.16 0 0 0 3.16 3.16h21.668a3.16 3.16 0 0 0 3.16-3.16V5.263a3.17 3.17 0 0 0-3.17-3.16");
}

.qk_b_8byf {
  stop-color: var(--svg-color--8f442e, #8F442E);
  stop-opacity: 0;
}

.qkon2bbue {
  stop-color: var(--svg-color--f78d1e, #F78D1E);
}

.qq23hkxyl {
  stop-color: var(--svg-color--d2d090, #D2D090);
}

.qug8vqbjp {
  stop-color: var(--svg-color--87a972, #87A972);
}

.rbo_s-jjr {
  stop-color: var(--svg-color--469747, #469747);
  stop-opacity: 0;
}

.rcxid8v0e {
  stop-color: var(--svg-color--2b6b33, #2B6B33);
  stop-opacity: 0;
}

.rep9lgbin {
  stop-color: var(--svg-color--93a880, #93A880);
  stop-opacity: 0;
}

.rhcjz5b3y {
  d: path("m7.256 12.185l-.42-.405a.35.35 0 0 0-.503 0a.35.35 0 0 0 0 .502l.474.473c.141.142.25.084.419-.14c.157-.21.124-.336.03-.43");
}

.rjzrd0bnq {
  stop-color: var(--svg-color--97b27f, #97B27F);
  stop-opacity: 0;
}

.ro_5gddxj {
  stop-color: var(--svg-color--75c876, #75C876);
}

.rpdbctbri {
  stop-color: var(--svg-color--b45e49, #B45E49);
}

.rrksbku7e {
  stop-color: var(--svg-color--bebc71, #BEBC71);
}

.rt1s6ex_z {
  stop-color: var(--svg-color--c5c58f, #C5C58F);
}

.rtghpro6c {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m17.433 20.588l.64.632");
}

.s-zkkvaky {
  stop-color: var(--svg-color--a8a75a, #A8A75A);
}

.s1y2gac1n {
  stop-color: var(--svg-color--cfcd8d, #CFCD8D);
}

.si--k3b1h {
  width: 1.14px;
  height: 16.171px;
  x: 10.963px;
  y: 14.11px;
  fill: var(--svg-color--7bd377, #7BD377);
  rx: 0.57px;
}

.si0r81bxu {
  cx: 10.91px;
  cy: 14.026px;
  r: 1.881px;
}

.sn4t7ybex {
  stop-color: var(--svg-color--a79c66, #A79C66);
  stop-opacity: 0;
}

.st-mzsb5l {
  stop-color: var(--svg-color--723d3e, #723D3E);
}

.sysxfe8la {
  d: path("m12.2 12.275l.501-.502a.35.35 0 0 1 .502 0a.35.35 0 0 1 0 .502l-.502.502a.35.35 0 0 1-.502 0a.35.35 0 0 1 0-.502");
}

.t6zp_vbou {
  stop-color: var(--svg-color--278620, #278620);
  stop-opacity: 0;
}

.tdlbrqt_m {
  d: path("M22.496 12.083c1.955 0 3.54-1.563 3.54-3.49s-1.585-3.49-3.54-3.49s-3.54 1.562-3.54 3.49c0 1.927 1.585 3.49 3.54 3.49");
}

.u3523xabg {
  stop-color: var(--svg-color--7ccd79, #7CCD79);
  stop-opacity: 0;
}

.unmi71bbo {
  cx: 6.654px;
  cy: 16.268px;
  fill: var(--svg-color--58b651, #58B651);
  rx: 0.188px;
  ry: 0.36px;
}

.v1zxeg2cn {
  stop-color: var(--svg-color--ff8f23, #FF8F23);
}

.v2xob-bms {
  stop-color: var(--svg-color--5a2141, #5A2141);
  stop-opacity: 0;
}

.v3m5c3d3b {
  stop-color: var(--svg-color--fbcd38, #FBCD38);
}

.v3m9hcc-j {
  stop-color: var(--svg-color--e45056, #E45056);
}

.va1-8_muw {
  fill-rule: evenodd;
  d: path("M8.001 14.395a.353.353 0 0 0-.353.353v10.354H3.994c-.797 0-1.511-.36-1.988-.926v.966a3.3 3.3 0 0 0 1.988.667h3.654v4.304h.707V14.748A.353.353 0 0 0 8 14.395");
}

.vuk6hhbbg {
  stop-color: var(--svg-color--6cb26e, #6CB26E);
  stop-opacity: 0;
}

.vz2jq3bwf {
  stop-color: var(--svg-color--a79c66, #A79C66);
}

.w1l4wl4lo {
  stop-color: var(--svg-color--91e38b, #91E38B);
  stop-opacity: 0;
}

.wceq6d_3s {
  stop-color: var(--svg-color--6cb26e, #6CB26E);
}

.whs02o7-r {
  d: path("m2.343 19.785l.246-.238a.35.35 0 0 1 .502 0a.35.35 0 0 1 0 .502l-.502.502c-.141.141-.315.285-.393 0c-.077-.286.005-.625.147-.766");
}

.wsrp1092z {
  stop-color: var(--svg-color--6b3a3f, #6B3A3F);
}

.wwc08g1ih {
  stop-color: var(--svg-color--fbcf1c, #FBCF1C);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x_cgdbc_q {
  d: path("M12.084 17.328h-.802a.1.1 0 0 0-.1.1v.507a.1.1 0 0 0 .1.1h.802a.35.35 0 0 0 .354-.354a.35.35 0 0 0-.354-.353");
}

.x3j6zwbza {
  stroke: var(--svg-color--b4b987, #B4B987);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m7.36 20.64l.895.906");
}

.x7th1qq_j {
  stop-color: var(--svg-color--30733e, #30733E);
  stop-opacity: 0;
}

.xczfe0g-o {
  stop-color: var(--svg-color--91db89, #91DB89);
}

.xi5a2nbde {
  stop-color: var(--svg-color--acb05e, #ACB05E);
}

.xoc4iy7so {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.788 20.53a3.4 3.4 0 0 0 3.4-3.4v-.597");
}

.xohfwn0yn {
  stop-color: var(--svg-color--cfcd8d, #CFCD8D);
  stop-opacity: 0;
}

.xowusrb5d {
  stop-color: var(--svg-color--bec284, #BEC284);
  stop-opacity: 0;
}

.y91eqos9r {
  stop-color: var(--svg-color--ebb91f, #EBB91F);
}

.yewi5lbgy {
  stop-color: var(--svg-color--29836d, #29836D);
}

.ygcq6___g {
  stop-color: var(--svg-color--bdbb6b, #BDBB6B);
}

.yhmwj7bym {
  d: path("M13.109 26.515h.546a.35.35 0 0 1 .354.354a.35.35 0 0 1-.354.353h-.546c-.198 0-.287-.155-.287-.353s.089-.354.287-.354");
}

.yon40acwh {
  d: path("m17.648 20.466l.502.502a.35.35 0 0 1 0 .501a.35.35 0 0 1-.502 0l-.502-.502c-.14-.14-.098-.304.043-.445c.134-.141.318-.198.46-.056");
}

.yoz11vbqy {
  d: path("m12.46 23.89l-1.278 1.308V24.18l.777-.791a.35.35 0 0 1 .502 0a.35.35 0 0 1 0 .501");
}

.yt-4_jbks {
  stop-color: var(--svg-color--90b779, #90B779);
}

.ywgoclbrb {
  stop-color: var(--svg-color--fbcd38, #FBCD38);
  stop-opacity: 0;
}

.z5g7nxrjl {
  stop-color: var(--svg-color--489e4f, #489E4F);
}

.ztey84_sy {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.438 14.661l-.691-.681");
}

</style>
