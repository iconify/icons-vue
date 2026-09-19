<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iTa1fPc)" class="qsciigb4e"/><path fill="url(#iFtIxvP)" class="qsciigb4e"/><path fill="url(#id4S8ne)" class="qsciigb4e"/><path fill="url(#if84PAe)" class="qsciigb4e"/><path fill="url(#iuyxrXd)" class="qsciigb4e"/><path class="ic9sl7fvp"/><path fill="url(#iYkYKBe)" class="wy1hr5y1h"/><path fill="url(#iXEZmnB)" class="wy1hr5y1h"/><path fill="url(#igdOShc)" class="wy1hr5y1h"/><path fill="url(#iVcGcne)" class="wy1hr5y1h"/><path class="vjc3-ibot"/><path fill="url(#ifXloae)" class="dxwb7ccll"/><path fill="url(#irMvW3b)" class="dxwb7ccll"/><path fill="url(#iv1KdXk)" class="dxwb7ccll"/><g filter="url(#ieMYujc)"><path fill="url(#i22hKye)" class="osfmtlx1e"/></g><g filter="url(#iPIGPob)"><path class="hdziacbem"/></g><g filter="url(#if75sHc)"><path class="g33-c_9jk"/></g><g filter="url(#ihy054G)"><path fill="url(#iok5KXY)" class="pz91rnbpw"/></g><g filter="url(#ifWrJqb)"><path fill="url(#iMQ2ymd)" class="x8sha6mnc"/></g><g filter="url(#i1oqe2d)"><path stroke="url(#ibC1QHd)" class="ja_1-iblr"/></g><g filter="url(#ii7O6Gc)"><path stroke="url(#iaoqoqd)" class="go7hdx5gj"/></g><path fill="url(#iGV6die)" class="fnokgubyt"/><g filter="url(#iWzJ2ye)"><path fill="url(#iYEovEb)" class="g-a9bmvor"/><path fill="url(#iCEOn8d)" class="g-a9bmvor"/><path fill="url(#iDBNFAU)" class="g-a9bmvor"/></g><path fill="url(#i1hN88b)" class="g-a9bmvor"/><path fill="url(#iBPWLTc)" class="g-a9bmvor"/><rect fill="url(#iLfgZnQ)" class="l_8bo9b_h"/><rect fill="url(#iD9HJXy)" class="l_8bo9b_h"/><rect fill="url(#itseIvb)" class="l_8bo9b_h"/><rect fill="url(#iHqE30d)" class="lzi9-9lsn"/><rect fill="url(#iE245we)" class="lzi9-9lsn"/><rect fill="url(#i5C9vxd)" class="lzi9-9lsn"/><path fill="url(#i9cL4uc)" class="yjx9o43ii"/><path fill="url(#izTEUTc)" class="yjx9o43ii"/><path fill="url(#i2gluUc)" class="yjx9o43ii"/><g filter="url(#ieVU3xd)"><path fill="url(#iEPgMfe)" class="j3rbinb3p"/></g><g filter="url(#iAdnn6d)"><path fill="url(#itXxkkR)" class="kt9jbkr4d"/></g><path fill="url(#iWlgU1d)" class="vwr1gibzz"/><path fill="url(#iY7tjad)" class="vwr1gibzz"/><g filter="url(#i7041bZ)"><path class="btl86m2cr"/></g><g filter="url(#isW7kmb)"><path fill="url(#iwPlDrL)" class="oofno8bxj"/><path fill="url(#irqrjxb)" class="oofno8bxj"/></g><path fill="url(#ieAXURc)" class="oofno8bxj"/><path fill="url(#imm5pTd)" class="oofno8bxj"/><path fill="url(#iQH9VUd)" class="oofno8bxj"/><path fill="url(#iN8NPFe)" class="oofno8bxj"/><path fill="url(#ivyvEjd)" class="oofno8bxj"/><path fill="url(#iJ2dA0c)" class="oofno8bxj"/><path fill="url(#iTKmK0c)" class="oofno8bxj"/><path fill="url(#iyWW0vc)" class="oofno8bxj"/><g filter="url(#i9LQajc)"><path fill="url(#iRWUiHc)" class="jtqvlcb2p"/></g><g filter="url(#iPNRUmd)"><path fill="url(#i32dSoD)" class="dsl-5mb_p"/><path fill="url(#ia8A36d)" class="dsl-5mb_p"/><path fill="url(#iWRg5ze)" class="dsl-5mb_p"/><path fill="url(#ilenF5c)" class="dsl-5mb_p"/></g><path fill="url(#iN5JQre)" class="nhtxuuo8z"/><g filter="url(#ievMC7b)"><path stroke="url(#iBeImub)" class="m5hrz_1-h"/></g><path class="e4qfcdcmd"/><g filter="url(#iJN6Cfd)"><path class="bxavwhb4h"/></g><g filter="url(#imKQmue)"><path class="ubnf6abnn"/></g><path class="n091nccyq"/><path fill="url(#iu6JK3b)" class="bts6x8bao"/><path class="cst82pbnc"/><g filter="url(#iplZ1sb)"><path class="l-4xtnccb"/><path fill="url(#iL5G0wb)" class="c309-hb5p"/></g><g filter="url(#iVnBMKb)"><path fill="url(#i5nlsHb)" class="uh4io2bju"/></g><path class="fgxenubxv"/><path fill="url(#i8g7ZHb)" class="z9sdo-btf"/><path class="p0z988bqc"/><g filter="url(#iJcXoMe)"><path fill="url(#i4xdRkd)" class="j24tcxbdl"/></g><g filter="url(#i90shPb)"><ellipse transform="rotate(-27.914 13.439 9.87)" class="ehf1sgbjv"/><ellipse fill="url(#il37jJb)" transform="rotate(-27.914 13.439 9.87)" class="qwvtw8brh"/></g><g filter="url(#iHQaqPd)"><path fill="url(#iLEKvIb)" class="s3ia2dt0g"/><path fill="url(#iJnm6oe)" class="s3ia2dt0g"/><path fill="url(#i4a3Lad)" class="s3ia2dt0g"/><path fill="url(#iuTsB9c)" class="s3ia2dt0g"/></g><path fill="url(#iTbR6Fd)" class="c0fx6j1jg"/><path fill="url(#i3MC88d)" class="c0fx6j1jg"/><path fill="url(#ivC7Ueb)" class="c0fx6j1jg"/><g filter="url(#iZ30yNc)"><rect fill="url(#i5yR0Yb)" class="nko-we3nt"/></g><g filter="url(#iyyseIe)"><path class="pgmdkub_l"/></g><defs><radialGradient id="id4S8ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.67857 -3.21429 0 22.919 24.685)" gradientUnits="userSpaceOnUse"><stop class="f26p0p1be"/><stop offset="1" class="tb_z1g16m"/></radialGradient><radialGradient id="if84PAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90626 2.7154 -1.39838 -4.07159 16.677 18.46)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="v130ylbqw"/><stop offset="1" class="cvz68p03p"/></radialGradient><radialGradient id="iYkYKBe" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 0 0 11.8756 21.834 29.457)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="rl--s2bxn"/><stop offset="1" class="v-kyyuk0w"/></radialGradient><radialGradient id="iVcGcne" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.53821 -7.17442 0 24.99 21.797)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="sy5bxccsg"/><stop offset="1" class="veojd009w"/></radialGradient><radialGradient id="ifXloae" cx="0" cy="0" r="1" gradientTransform="matrix(-4.26999 0 0 -10.4063 9.01 28.988)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="pisufpbzg"/><stop offset="1" class="d6clut5cf"/></radialGradient><radialGradient id="iv1KdXk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 3.70797 0 7.615 30.332)" gradientUnits="userSpaceOnUse"><stop class="z_vepkinu"/><stop offset="1" class="a_7m96h7b"/></radialGradient><radialGradient id="iok5KXY" cx="0" cy="0" r="1" gradientTransform="rotate(53.881 -16.071 24.906)scale(2.14706)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rdedbifir"/><stop offset="1" class="co8wuy7pr"/></radialGradient><radialGradient id="iGV6die" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 0 0 -4.97705 7.177 27.84)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="wi08z5bgf"/><stop offset="1" class="d0gbo-tip"/></radialGradient><radialGradient id="iCEOn8d" cx="0" cy="0" r="1" gradientTransform="rotate(-169.849 7.115 8.483)scale(4.49245 1.66714)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="lewnpt48t"/><stop offset="1" class="cmgaqknre"/></radialGradient><radialGradient id="iDBNFAU" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61229 2.22988 -.54256 -1.36555 22.918 18.82)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="eckdnoofv"/></radialGradient><radialGradient id="i1hN88b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09385 -11.9992 0 15.99 18.126)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="m8nvn-czs"/><stop offset=".943" class="dtg8x0b5w"/></radialGradient><radialGradient id="iBPWLTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.01366 -3.3941 0 15.99 19.266)" gradientUnits="userSpaceOnUse"><stop class="rsw_em86r"/><stop offset="1" class="xfk5_2xnq"/></radialGradient><radialGradient id="itseIvb" cx="0" cy="0" r="1" gradientTransform="matrix(.61774 0 0 2.761 6.083 11.894)" gradientUnits="userSpaceOnUse"><stop class="h2db6f6fo"/><stop offset="1" class="eqvqhkbwy"/></radialGradient><radialGradient id="iE245we" cx="0" cy="0" r="1" gradientTransform="matrix(.98754 0 0 2.55399 24.573 10.628)" gradientUnits="userSpaceOnUse"><stop class="jg30e8bxd"/><stop offset="1" class="djf9lpl6o"/></radialGradient><radialGradient id="i5C9vxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9456 -.49377 0 25.612 10.237)" gradientUnits="userSpaceOnUse"><stop class="s5nmtcc-t"/><stop offset="1" class="teoxnoh1q"/></radialGradient><radialGradient id="izTEUTc" cx="0" cy="0" r="1" gradientTransform="rotate(72.208 .427 16.426)scale(9.27527 14.5186)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="mj0fjsb8e"/><stop offset="1" class="gwnz45kfq"/></radialGradient><radialGradient id="i2gluUc" cx="0" cy="0" r="1" gradientTransform="rotate(-137.406 9.636 7.234)scale(5.26375 2.32464)" gradientUnits="userSpaceOnUse"><stop class="zdd7s4gqs"/><stop offset="1" class="a2dspgbsf"/></radialGradient><radialGradient id="itXxkkR" cx="0" cy="0" r="1" gradientTransform="rotate(123.891 7.386 7.964)scale(12.2137)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="yx5v_dk3v"/><stop offset="1" class="y2y8kppey"/></radialGradient><radialGradient id="iY7tjad" cx="0" cy="0" r="1" gradientTransform="rotate(6.45 -87.852 138.644)scale(8.5401)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="vzafmqbsv"/><stop offset="1" class="kfjcj3jmf"/></radialGradient><radialGradient id="iwPlDrL" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.08497 -6.18486 0 15.985 11.934)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="o84e_ktdp"/><stop offset=".799" class="ug9xy5boj"/></radialGradient><radialGradient id="irqrjxb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03126 -.78123 1.34858 -5.23264 20.647 14.683)" gradientUnits="userSpaceOnUse"><stop class="qo7x1rbmo"/><stop offset="1" class="ur88-2xnt"/></radialGradient><radialGradient id="imm5pTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.125 8.75502 0 15.985 16.27)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="uh1o8mbkd"/><stop offset="1" class="zpvtvnbep"/></radialGradient><radialGradient id="iQH9VUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.81982 -7.24372 0 15.985 9.55)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="a71oe-k9s"/><stop offset="1" class="dkl_m1bru"/></radialGradient><radialGradient id="iN8NPFe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 0 0 -1.26563 20.24 15.738)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="npttfobuh"/><stop offset="1" class="thfi-mb0h"/></radialGradient><radialGradient id="ivyvEjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.18781 -7.81147 0 15.985 7.324)" gradientUnits="userSpaceOnUse"><stop class="zzxdaxbga"/><stop offset="1" class="nwee25muj"/></radialGradient><radialGradient id="iJ2dA0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.18986 1.26423 0 14.064 9.725)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="y1trv655f"/><stop offset="1" class="lxmf49xhl"/></radialGradient><radialGradient id="iTKmK0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 .43601 -.29198 -.84753 13.866 10.464)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="jwb4ndb5j"/><stop offset="1" class="rnju5tb_g"/></radialGradient><radialGradient id="iyWW0vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -2.27319 0 18.429 10.62)" gradientUnits="userSpaceOnUse"><stop class="c--_ln7ym"/><stop offset="1" class="sl4ln-bdx"/></radialGradient><radialGradient id="iRWUiHc" cx="0" cy="0" r="1" gradientTransform="rotate(146.924 6.143 8.127)scale(1.04487 1.23672)" gradientUnits="userSpaceOnUse"><stop class="ja9w_kbpc"/><stop offset="1" class="m_uv-pbqs"/></radialGradient><radialGradient id="ia8A36d" cx="0" cy="0" r="1" gradientTransform="matrix(-.70313 0 0 -.32031 16.288 12.209)" gradientUnits="userSpaceOnUse"><stop class="xkdh7xtpc"/><stop offset="1" class="ruvs-5b3s"/></radialGradient><radialGradient id="iWRg5ze" cx="0" cy="0" r="1" gradientTransform="matrix(.2554 2.91155 -.39026 .03423 16.202 9.598)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="kgmorqb4d"/><stop offset="1" class="a9k63cbjk"/></radialGradient><radialGradient id="iBeImub" cx="0" cy="0" r="1" gradientTransform="matrix(.62856 -.66852 2.11441 1.98802 14.515 14.287)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="d3qat4bdm"/><stop offset="1" class="we38-qbsx"/></radialGradient><radialGradient id="iu6JK3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82614 -1.31407 0 18.159 9.967)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="m_2s0rt2o"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dwsv4tgiz"/></radialGradient><radialGradient id="iL5G0wb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23615 -.30432 .41897 -.32513 17.927 10.053)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8g7ZHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82618 -1.31413 0 13.715 9.967)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="m_2s0rt2o"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dwsv4tgiz"/></radialGradient><radialGradient id="il37jJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00788 -.5031 .60476 -.00947 13.424 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLEKvIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50166 -9.15821 0 15.99 3.49)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="lalxu4bkj"/><stop offset="1" class="w-jvyybfs"/></radialGradient><radialGradient id="iJnm6oe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03127 -2.42187 2.37699 1.01216 9.317 9.035)" gradientUnits="userSpaceOnUse"><stop class="f2tw_xhyp"/><stop offset="1" class="h8vr8dbmo"/></radialGradient><radialGradient id="i4a3Lad" cx="0" cy="0" r="1" gradientTransform="rotate(-147.95 12.014 3.511)scale(12.72 10.6468)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="d1-tygbiz"/><stop offset="1" class="ijavpvb5h"/></radialGradient><radialGradient id="iTbR6Fd" cx="0" cy="0" r="1" gradientTransform="matrix(3.07812 0 0 1.2594 18.162 15.15)" gradientUnits="userSpaceOnUse"><stop class="xnke96byi"/><stop offset=".78" class="gvh11p6ie"/></radialGradient><linearGradient id="iTa1fPc" x1="10.169" x2="21.419" y1="30.506" y2="30.506" gradientUnits="userSpaceOnUse"><stop offset=".006" class="hwnz8bbgx"/><stop offset="1" class="efhowwcgb"/></linearGradient><linearGradient id="iFtIxvP" x1="8.677" x2="10.834" y1="26.113" y2="26.144" gradientUnits="userSpaceOnUse"><stop class="nqsdswamn"/><stop offset=".231" class="cdku7hg9b"/><stop offset="1" class="oj2-77bel"/></linearGradient><linearGradient id="iuyxrXd" x1="16.584" x2="16.584" y1="30.519" y2="29.613" gradientUnits="userSpaceOnUse"><stop class="v-k4gup8y"/><stop offset="1" class="wjgrr3bwb"/></linearGradient><linearGradient id="iXEZmnB" x1="22.787" x2="23.427" y1="26.598" y2="26.582" gradientUnits="userSpaceOnUse"><stop offset=".127" class="t-c91xbtu"/><stop offset="1" class="zl1nvac2j"/></linearGradient><linearGradient id="igdOShc" x1="26.99" x2="26.271" y1="29.98" y2="29.98" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset="1" class="arric2tqt"/></linearGradient><linearGradient id="irMvW3b" x1="9.06" x2="8.685" y1="29.98" y2="29.98" gradientUnits="userSpaceOnUse"><stop class="og0r_u8md"/><stop offset="1" class="y1qnskbjy"/></linearGradient><linearGradient id="i22hKye" x1="20.49" x2="11.48" y1="29.675" y2="29.675" gradientUnits="userSpaceOnUse"><stop class="fatndpbme"/><stop offset="1" class="skyfyac-t"/></linearGradient><linearGradient id="iMQ2ymd" x1="17.334" x2="18.756" y1="24.754" y2="23.348" gradientUnits="userSpaceOnUse"><stop class="rm14ccb4q"/><stop offset="1" class="d6v2o-bft"/></linearGradient><linearGradient id="ibC1QHd" x1="18.865" x2="17.373" y1="23.261" y2="24.683" gradientUnits="userSpaceOnUse"><stop class="btagy7mof"/><stop offset=".531" class="qzlgi0c-c"/></linearGradient><linearGradient id="iaoqoqd" x1="14.865" x2="13.373" y1="23.261" y2="24.683" gradientUnits="userSpaceOnUse"><stop class="s5ud30bqo"/><stop offset=".531" class="rwl3x2rgk"/></linearGradient><linearGradient id="iYEovEb" x1="21.602" x2="8.007" y1="19.594" y2="19.594" gradientUnits="userSpaceOnUse"><stop class="bvm_ssbmv"/><stop offset="1" class="qox001bns"/></linearGradient><linearGradient id="iLfgZnQ" x1="8.286" x2="8.286" y1="8.918" y2="12.488" gradientUnits="userSpaceOnUse"><stop class="okcn0pbqd"/><stop offset="1" class="zd-keimcv"/></linearGradient><linearGradient id="iD9HJXy" x1="7.115" x2="7.115" y1="13.902" y2="13.175" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></linearGradient><linearGradient id="iHqE30d" x1="25.181" x2="25.181" y1="8.918" y2="14.052" gradientUnits="userSpaceOnUse"><stop class="wgw2105cx"/><stop offset=".743" class="tkxxt2z6p"/><stop offset="1" class="umazj-pya"/></linearGradient><linearGradient id="i9cL4uc" x1="23.927" x2="8.084" y1="6.425" y2="15.707" gradientUnits="userSpaceOnUse"><stop class="yt0sjmb1z"/><stop offset="1" class="egb-_obih"/></linearGradient><linearGradient id="iEPgMfe" x1="23.716" x2="8.292" y1="6.547" y2="15.582" gradientUnits="userSpaceOnUse"><stop class="g4r6pf4wm"/><stop offset="1" class="xpw6t3bxs"/></linearGradient><linearGradient id="iWlgU1d" x1="9.865" x2="23.334" y1="12.144" y2="12.144" gradientUnits="userSpaceOnUse"><stop class="k8zoqmmdl"/><stop offset=".276" class="s6m-cnbld"/></linearGradient><linearGradient id="ieAXURc" x1="21.188" x2="19.944" y1="12.05" y2="12.011" gradientUnits="userSpaceOnUse"><stop class="u_pi4nbrf"/><stop offset="1" class="py1dfcclx"/></linearGradient><linearGradient id="i32dSoD" x1="15.937" x2="16.808" y1="11.744" y2="11.744" gradientUnits="userSpaceOnUse"><stop class="b-ugtlb-t"/><stop offset="1" class="dl48aepdi"/></linearGradient><linearGradient id="ilenF5c" x1="15.937" x2="15.937" y1="12.855" y2="12.324" gradientUnits="userSpaceOnUse"><stop class="qzlzdubue"/><stop offset="1" class="ets_d_oqb"/></linearGradient><linearGradient id="iN5JQre" x1="15.937" x2="15.937" y1="9.799" y2="11.173" gradientUnits="userSpaceOnUse"><stop offset=".291" class="e99sa5w6k"/><stop offset="1" class="zgtcnu2sf"/></linearGradient><linearGradient id="i5nlsHb" x1="18.951" x2="18.632" y1="10.022" y2="10.219" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4xdRkd" x1="14.473" x2="14.153" y1="10.022" y2="10.219" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuTsB9c" x1="23.29" x2="21.615" y1="9.394" y2="7.332" gradientUnits="userSpaceOnUse"><stop class="m9pa3mbws"/><stop offset="1" class="u_tn6mbuw"/></linearGradient><linearGradient id="i3MC88d" x1="17.576" x2="17.951" y1="15.191" y2="15.191" gradientUnits="userSpaceOnUse"><stop class="rvgaerxsl"/><stop offset="1" class="wdhp9kbzq"/></linearGradient><linearGradient id="ivC7Ueb" x1="19.224" x2="19.224" y1="15.754" y2="15.558" gradientUnits="userSpaceOnUse"><stop class="u9byv1bdc"/><stop offset="1" class="zk7oijy-r"/></linearGradient><linearGradient id="i5yR0Yb" x1="18.206" x2="20.392" y1="15.215" y2="15.215" gradientUnits="userSpaceOnUse"><stop class="ueq20f_ji"/><stop offset="1" class="o69d91bgq"/></linearGradient><filter id="ieMYujc" width="9.31" height="4.17" x="11.33" y="25.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.811765 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.635294 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2537" result="effect2_innerShadow_4002_2537"/></filter><filter id="iPIGPob" width="3.12" height="3.12" x="12.245" y="22.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".25"/></filter><filter id="if75sHc" width="3.12" height="3.12" x="16.315" y="22.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".25"/></filter><filter id="ihy054G" width="2.12" height="2.12" x="12.93" y="22.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.498039 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter><filter id="ifWrJqb" width="2.12" height="2.12" x="16.93" y="22.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.180392 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter><filter id="i1oqe2d" width="2.05" height="2.05" x="16.965" y="22.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".05"/></filter><filter id="ii7O6Gc" width="2.05" height="2.05" x="12.965" y="22.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".05"/></filter><filter id="iWzJ2ye" width="14.359" height="6.364" x="8.81" y="15.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.87451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter><filter id="ieVU3xd" width="18.043" height="18.043" x="6.916" y="1.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".125"/></filter><filter id="iAdnn6d" width="16.155" height="16.155" x="7.859" y="2.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".15"/></filter><filter id="i7041bZ" width="14.583" height="16.385" x="9.063" y="2.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".75"/></filter><filter id="isW7kmb" width="10.407" height="12.567" x="10.781" y="4.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.176471 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter><filter id="i9LQajc" width="3.912" height="4.953" x="13.77" y="9.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".5"/></filter><filter id="iPNRUmd" width="2.112" height="3.153" x="14.881" y="9.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/><feGaussianBlur result="effect2_foregroundBlur_4002_2537" stdDeviation=".05"/></filter><filter id="ievMC7b" width="3.677" height="1.492" x="14.098" y="13.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".05"/></filter><filter id="iJN6Cfd" width="2.38" height="1.209" x="17.555" y="7.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter><filter id="imKQmue" width="2.38" height="1.194" x="12.203" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter><filter id="iplZ1sb" width=".798" height=".705" x="17.413" y="9.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".05"/></filter><filter id="iVnBMKb" width=".9" height=".923" x="18.27" y="9.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".1"/></filter><filter id="iJcXoMe" width=".997" height="1.052" x="13.746" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".1"/></filter><filter id="i90shPb" width=".926" height=".714" x="12.976" y="9.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".05"/></filter><filter id="iHQaqPd" width="14.6" height="5.86" x="8.69" y="3.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.215686 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.219608 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2537" result="effect2_innerShadow_4002_2537"/></filter><filter id="iZ30yNc" width="3.344" height=".781" x="17.787" y="14.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2537" stdDeviation=".125"/></filter><filter id="iyyseIe" width="6.686" height="4.857" x="16.37" y="13.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.486275 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2537"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:astronaut-medium" /></template>
<style>
.a_7m96h7b {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
  stop-opacity: 0;
}

.a2dspgbsf {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
  stop-opacity: 0;
}

.a71oe-k9s {
  stop-color: var(--svg-color--825a58, #825A58);
  stop-opacity: 0;
}

.a9k63cbjk {
  stop-color: var(--svg-color--b89381, #B89381);
  stop-opacity: 0;
}

.arric2tqt {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
  stop-opacity: 0;
}

.b-ugtlb-t {
  stop-color: var(--svg-color--9a726a, #9A726A);
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.btagy7mof {
  stop-color: var(--svg-color--fb4f70, #FB4F70);
}

.btl86m2cr {
  fill: var(--svg-color--1f1428, #1F1428);
  d: path("M10.833 14.044c.292 2.118 2.175 3.694 4.404 3.694h2.138c2.23 0 4.112-1.576 4.404-3.694c.134-2.043.268-4.077.367-6.12c-.012-.831-.697-1.517-1.563-1.552h-1.586c-1.082 0-2.062-.611-2.507-1.565a.75.75 0 0 0-.697-.454H14.35c-2.092 0-3.787 1.64-3.787 3.665c0 2.018.132 4.003.27 6.026");
}

.bts6x8bao {
  d: path("M18.161 9.481a.91.91 0 0 1 .876 1.149H17.28a.912.912 0 0 1 .88-1.148");
}

.bvm_ssbmv {
  stop-color: var(--svg-color--f0e4fc, #F0E4FC);
}

.bxavwhb4h {
  fill: var(--svg-color--3a1e2f, #3A1E2F);
  d: path("M19.738 7.866a1.9 1.9 0 0 0-.7-.419c-.31-.097-.698-.124-1.235-.058a.282.282 0 0 0 .07.56c.49-.06.79-.028.996.037c.201.063.338.166.498.306a.282.282 0 0 0 .371-.426");
}

.c--_ln7ym {
  stop-color: var(--svg-color--9a735f, #9A735F);
}

.c0fx6j1jg {
  d: path("M18.01 15.65h2.97c.28 0 .5-.22.5-.5s-.22-.5-.5-.5h-2.97c-.28 0-.5.22-.5.5s.23.5.5.5");
}

.c309-hb5p {
  d: path("M18.094 9.674c.065.086-.07.192-.224.307s-.268.196-.333.11s.008-.25.161-.366c.154-.115.331-.138.396-.051");
}

.cdku7hg9b {
  stop-color: var(--svg-color--d3cade, #D3CADE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmgaqknre {
  stop-color: var(--svg-color--b3b2b5, #B3B2B5);
  stop-opacity: 0;
}

.co8wuy7pr {
  stop-color: var(--svg-color--3e7cd9, #3E7CD9);
}

.cst82pbnc {
  fill: var(--svg-color--000, #000);
  d: path("M17.64 10.39c0-.29.232-.52.521-.52a.518.518 0 0 1 .463.76h-.921a.47.47 0 0 1-.062-.24");
}

.cvz68p03p {
  stop-color: var(--svg-color--c2b2d7, #C2B2D7);
  stop-opacity: 0;
}

.d0gbo-tip {
  stop-color: var(--svg-color--648cbc, #648CBC);
}

.d1-tygbiz {
  stop-color: var(--svg-color--493b54, #493B54);
  stop-opacity: 0;
}

.d3qat4bdm {
  stop-color: var(--svg-color--aa847b, #AA847B);
}

.d6clut5cf {
  stop-color: var(--svg-color--c4c1c5, #C4C1C5);
}

.d6v2o-bft {
  stop-color: var(--svg-color--f13c6a, #F13C6A);
}

.djf9lpl6o {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
  stop-opacity: 0;
}

.dkl_m1bru {
  stop-color: var(--svg-color--38251f, #38251F);
}

.dl48aepdi {
  stop-color: var(--svg-color--af8771, #AF8771);
}

.dsl-5mb_p {
  d: path("m15.548 10.172l-.541 1.872c-.11.385.154.77.53.77h.8c.376 0 .641-.39.53-.77l-.54-1.872c-.116-.414-.658-.414-.78 0");
}

.dtg8x0b5w {
  stop-color: var(--svg-color--c9a7ef, #C9A7EF);
}

.dwsv4tgiz {
  stop-color: var(--svg-color--5f3f37, #5F3F37);
}

.dxwb7ccll {
  d: path("m8.993 29.98l.017-.01V19.421a10.98 10.98 0 0 0-4.03 8.51v2.05z");
}

.e4qfcdcmd {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.937 13.85a3.06 3.06 0 0 1-1.41-.335c-.14-.07-.29.086-.202.213c.34.517.935.861 1.612.861s1.271-.344 1.612-.861c.088-.132-.062-.284-.201-.213a3.04 3.04 0 0 1-1.41.335");
}

.e99sa5w6k {
  stop-color: var(--svg-color--a17471, #A17471);
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.eckdnoofv {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
  stop-opacity: 0;
}

.efhowwcgb {
  stop-color: var(--svg-color--e7d8f7, #E7D8F7);
}

.egb-_obih {
  stop-color: var(--svg-color--a6a2ab, #A6A2AB);
}

.ehf1sgbjv {
  cx: 13.439px;
  cy: 9.87px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.eqvqhkbwy {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
  stop-opacity: 0;
}

.ets_d_oqb {
  stop-color: var(--svg-color--976568, #976568);
  stop-opacity: 0;
}

.f26p0p1be {
  stop-color: var(--svg-color--f7efff, #F7EFFF);
}

.f2tw_xhyp {
  stop-color: var(--svg-color--6c6176, #6C6176);
}

.fatndpbme {
  stop-color: var(--svg-color--cdc0da, #CDC0DA);
}

.fgxenubxv {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.503 9.205c-.665 0-1.227.458-1.38 1.078a.28.28 0 0 0 .273.347h2.271c.145 0 .26-.132.232-.277a1.43 1.43 0 0 0-1.396-1.148");
}

.fnokgubyt {
  d: path("M7.35 28.65v-1.62c0-.19-.15-.34-.34-.34H5.05c-.03.26-.05.53-.06.8l.01 1.5h2.02c.18 0 .33-.15.33-.34");
}

.ft5dv1b6b {
  fill: none;
}

.g-a9bmvor {
  d: path("M23.17 18.387c0 1.462-2.782 3.515-7.18 3.515c-4.469-.047-7.18-2.053-7.18-3.515s3.215-2.649 7.18-2.649s7.18 1.186 7.18 2.649");
}

.g33-c_9jk {
  fill: var(--svg-color--d1b8d6, #D1B8D6);
  d: path("M17.875 25.225a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.g4r6pf4wm {
  stop-color: var(--svg-color--bab4c1, #BAB4C1);
}

.go7hdx5gj {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.99 24.855a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.gvh11p6ie {
  stop-color: var(--svg-color--463d38, #463D38);
}

.gwnz45kfq {
  stop-color: var(--svg-color--9f98a6, #9F98A6);
}

.h2db6f6fo {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
}

.h8vr8dbmo {
  stop-color: var(--svg-color--6c6176, #6C6176);
  stop-opacity: 0;
}

.hdziacbem {
  fill: var(--svg-color--d6bcdb, #D6BCDB);
  d: path("M13.805 25.225a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.hwnz8bbgx {
  stop-color: var(--svg-color--dbcfea, #DBCFEA);
}

.ic9sl7fvp {
  fill: var(--svg-color--ebdef9, #EBDEF9);
  d: path("M22.99 19.44v10.54h4v-2.37c-.09-3.29-1.63-6.21-4-8.17");
}

.ijavpvb5h {
  stop-color: var(--svg-color--493b54, #493B54);
}

.j24tcxbdl {
  d: path("M14.544 10.284c0-.294-.24-.49-.304-.55l-.294.285l.181.368z");
}

.j3rbinb3p {
  d: path("M15.937 2.229A8.767 8.767 0 0 0 7.166 11a8.767 8.767 0 0 0 8.771 8.772A8.767 8.767 0 0 0 24.71 11c0-4.848-3.933-8.771-8.772-8.771");
}

.ja_1-iblr {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.99 24.855a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.ja9w_kbpc {
  stop-color: var(--svg-color--8a6254, #8A6254);
}

.jg30e8bxd {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
}

.jtqvlcb2p {
  d: path("m15.442 10.372l-.646 1.872c-.11.385.154.77.53.77h.8c.376 0 .641-.391.53-.77l-.54-1.872c-.117-.415-.552-.415-.674 0");
}

.jwb4ndb5j {
  stop-color: var(--svg-color--856152, #856152);
}

.k8zoqmmdl {
  stop-color: var(--svg-color--4e4257, #4E4257);
}

.kfjcj3jmf {
  stop-color: var(--svg-color--362b3d, #362B3D);
}

.kgmorqb4d {
  stop-color: var(--svg-color--b89381, #B89381);
}

.kt9jbkr4d {
  d: path("M15.937 3.222A7.773 7.773 0 0 0 8.16 11a7.773 7.773 0 0 0 7.778 7.778a7.779 7.779 0 0 0 0-15.555");
}

.l_8bo9b_h {
  width: 4.406px;
  height: 4.984px;
  x: 6.083px;
  y: 8.918px;
  rx: 0.75px;
}

.l-4xtnccb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.094 9.674c.065.086-.07.192-.224.307s-.268.196-.333.11s.008-.25.161-.366c.154-.115.331-.138.396-.051");
}

.lalxu4bkj {
  stop-color: var(--svg-color--848286, #848286);
}

.lewnpt48t {
  stop-color: var(--svg-color--a59eac, #A59EAC);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lxmf49xhl {
  stop-color: var(--svg-color--835a59, #835A59);
  stop-opacity: 0;
}

.lzi9-9lsn {
  width: 4.406px;
  height: 4.984px;
  x: 21.489px;
  y: 8.918px;
  rx: 0.75px;
}

.m_2s0rt2o {
  stop-color: var(--svg-color--6c4941, #6C4941);
}

.m_uv-pbqs {
  stop-color: var(--svg-color--956467, #956467);
}

.m5hrz_1-h {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.937 13.85a3.06 3.06 0 0 1-1.41-.335c-.14-.07-.29.086-.202.213c.34.517.935.861 1.612.861s1.271-.344 1.612-.861c.088-.132-.062-.284-.201-.213a3.04 3.04 0 0 1-1.41.335Z");
}

.m8nvn-czs {
  stop-color: var(--svg-color--c9a7ef, #C9A7EF);
  stop-opacity: 0;
}

.m9pa3mbws {
  stop-color: var(--svg-color--726080, #726080);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mj0fjsb8e {
  stop-color: var(--svg-color--9f98a6, #9F98A6);
  stop-opacity: 0;
}

.n091nccyq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.372 9.205c.665 0 1.227.458 1.38 1.078a.28.28 0 0 1-.273.347h-2.272a.234.234 0 0 1-.231-.277a1.42 1.42 0 0 1 1.396-1.148");
}

.nhtxuuo8z {
  d: path("m15.548 10.117l-.541 1.911c-.11.393.154.786.53.786h.8c.376 0 .641-.399.53-.786l-.54-1.911c-.116-.424-.658-.424-.78 0");
}

.nko-we3nt {
  width: 2.844px;
  height: 0.281px;
  x: 18.037px;
  y: 14.933px;
  rx: 0.141px;
}

.npttfobuh {
  stop-color: var(--svg-color--3a2820, #3A2820);
}

.nqsdswamn {
  stop-color: var(--svg-color--baa7d0, #BAA7D0);
}

.nwee25muj {
  stop-color: var(--svg-color--7c525a, #7C525A);
  stop-opacity: 0;
}

.o69d91bgq {
  stop-color: var(--svg-color--5c595d, #5C595D);
}

.o84e_ktdp {
  stop-color: var(--svg-color--ae807a, #AE807A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og0r_u8md {
  stop-color: var(--svg-color--bbb7c0, #BBB7C0);
}

.oj2-77bel {
  stop-color: var(--svg-color--d3cade, #D3CADE);
  stop-opacity: 0;
}

.okcn0pbqd {
  stop-color: var(--svg-color--919092, #919092);
}

.oofno8bxj {
  d: path("M11.024 13.715a3.99 3.99 0 0 0 3.957 3.469h1.92a3.99 3.99 0 0 0 3.957-3.469c.12-1.918.241-3.828.33-5.745a1.476 1.476 0 0 0-1.404-1.458H18.36a2.47 2.47 0 0 1-2.253-1.47a.68.68 0 0 0-.626-.426h-1.296c-1.88 0-3.403 1.54-3.403 3.441c0 1.895.119 3.759.243 5.658");
}

.osfmtlx1e {
  d: path("M19.67 25.97H12.3c-.45 0-.82.37-.82.82v3.2h9.01v-3.2c0-.46-.36-.82-.82-.82");
}

.p0z988bqc {
  fill: var(--svg-color--000, #000);
  d: path("M14.234 10.39a.52.52 0 0 0-.52-.52a.518.518 0 0 0-.463.76h.92a.5.5 0 0 0 .063-.24");
}

.pgmdkub_l {
  fill: var(--svg-color--b9b2bf, #B9B2BF);
  d: path("M23.006 13.7h-.956c-.4-.01-.78.19-1 .53a6.04 6.04 0 0 1-3.92 2.67c-.44.08-.76.46-.76.91v.696a7.52 7.52 0 0 0 6.636-4.806");
}

.pisufpbzg {
  stop-color: var(--svg-color--c4c1c5, #C4C1C5);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.py1dfcclx {
  stop-color: var(--svg-color--715544, #715544);
  stop-opacity: 0;
}

.pz91rnbpw {
  d: path("M13.99 25.04a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.qo7x1rbmo {
  stop-color: var(--svg-color--8b6c55, #8B6C55);
}

.qox001bns {
  stop-color: var(--svg-color--d8d0e0, #D8D0E0);
}

.qsciigb4e {
  d: path("M21.59 18.46H10.38c-3.23 1.92-5.4 5.44-5.4 9.47v2.05H27v-2.05c0-4.03-2.17-7.55-5.41-9.47");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwvtw8brh {
  cx: 13.439px;
  cy: 9.87px;
  rx: 0.397px;
  ry: 0.201px;
}

.qzlgi0c-c {
  stop-color: var(--svg-color--f34b6c, #F34B6C);
  stop-opacity: 0;
}

.qzlzdubue {
  stop-color: var(--svg-color--976568, #976568);
}

.rdedbifir {
  stop-color: var(--svg-color--3d8ee2, #3D8EE2);
}

.rl--s2bxn {
  stop-color: var(--svg-color--f6edff, #F6EDFF);
  stop-opacity: 0;
}

.rm14ccb4q {
  stop-color: var(--svg-color--ee3880, #EE3880);
}

.rnju5tb_g {
  stop-color: var(--svg-color--856152, #856152);
  stop-opacity: 0;
}

.rsw_em86r {
  stop-color: var(--svg-color--d7d2dd, #D7D2DD);
}

.ruvs-5b3s {
  stop-color: var(--svg-color--b99384, #B99384);
  stop-opacity: 0;
}

.rvgaerxsl {
  stop-color: var(--svg-color--615962, #615962);
}

.rwl3x2rgk {
  stop-color: var(--svg-color--4d90df, #4D90DF);
  stop-opacity: 0;
}

.s3ia2dt0g {
  d: path("M15.99 6.79a12 12 0 0 1 7.3 2.46c-.79-3.3-3.76-5.76-7.3-5.76s-6.51 2.46-7.3 5.76a12 12 0 0 1 7.3-2.46");
}

.s5nmtcc-t {
  stop-color: var(--svg-color--dcdade, #DCDADE);
}

.s5ud30bqo {
  stop-color: var(--svg-color--4d90df, #4D90DF);
}

.s6m-cnbld {
  stop-color: var(--svg-color--332640, #332640);
}

.skyfyac-t {
  stop-color: var(--svg-color--beb1cc, #BEB1CC);
}

.sl4ln-bdx {
  stop-color: var(--svg-color--9a735f, #9A735F);
  stop-opacity: 0;
}

.sy5bxccsg {
  stop-color: var(--svg-color--ded6eb, #DED6EB);
  stop-opacity: 0;
}

.t-c91xbtu {
  stop-color: var(--svg-color--c8b9da, #C8B9DA);
}

.tb_z1g16m {
  stop-color: var(--svg-color--f7efff, #F7EFFF);
  stop-opacity: 0;
}

.teoxnoh1q {
  stop-color: var(--svg-color--dcdade, #DCDADE);
  stop-opacity: 0;
}

.thfi-mb0h {
  stop-color: var(--svg-color--794f52, #794F52);
  stop-opacity: 0;
}

.tkxxt2z6p {
  stop-color: var(--svg-color--afa9b7, #AFA9B7);
}

.u_pi4nbrf {
  stop-color: var(--svg-color--462f2d, #462F2D);
}

.u_tn6mbuw {
  stop-color: var(--svg-color--726080, #726080);
  stop-opacity: 0;
}

.u9byv1bdc {
  stop-color: var(--svg-color--3d3438, #3D3438);
}

.ubnf6abnn {
  fill: var(--svg-color--3a1e2f, #3A1E2F);
  d: path("M12.464 7.755a2.82 2.82 0 0 1 1.77-.366a.282.282 0 1 1-.068.56a2.26 2.26 0 0 0-1.412.29a1 1 0 0 0-.093.062l-.003.002a.282.282 0 0 1-.346-.447z");
}

.ueq20f_ji {
  stop-color: var(--svg-color--797278, #797278);
}

.ug9xy5boj {
  stop-color: var(--svg-color--855c60, #855C60);
}

.uh1o8mbkd {
  stop-color: var(--svg-color--5e3a41, #5E3A41);
  stop-opacity: 0;
}

.uh4io2bju {
  d: path("M18.97 10.27a.86.86 0 0 0-.235-.47l-.265.29l.12.232z");
}

.umazj-pya {
  stop-color: var(--svg-color--8e8895, #8E8895);
}

.ur88-2xnt {
  stop-color: var(--svg-color--8b6c55, #8B6C55);
  stop-opacity: 0;
}

.uy-elybtc {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
}

.v-k4gup8y {
  stop-color: var(--svg-color--c9b4e0, #C9B4E0);
}

.v-kyyuk0w {
  stop-color: var(--svg-color--fdfaff, #FDFAFF);
}

.v130ylbqw {
  stop-color: var(--svg-color--b096cb, #B096CB);
}

.veojd009w {
  stop-color: var(--svg-color--d8c5ec, #D8C5EC);
}

.vjc3-ibot {
  fill: var(--svg-color--d9cde8, #D9CDE8);
  d: path("m8.993 29.98l.017-.01V19.421a10.98 10.98 0 0 0-4.03 8.51v2.05z");
}

.vwr1gibzz {
  d: path("M15.99 18.516a7.516 7.516 0 1 0 0-15.031a7.516 7.516 0 0 0 0 15.03");
}

.vzafmqbsv {
  stop-color: var(--svg-color--362b3d, #362B3D);
  stop-opacity: 0;
}

.w-jvyybfs {
  stop-color: var(--svg-color--655d6d, #655D6D);
}

.wdhp9kbzq {
  stop-color: var(--svg-color--615962, #615962);
  stop-opacity: 0;
}

.we38-qbsx {
  stop-color: var(--svg-color--aa847b, #AA847B);
  stop-opacity: 0;
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.wi08z5bgf {
  stop-color: var(--svg-color--3776c0, #3776C0);
}

.wjgrr3bwb {
  stop-color: var(--svg-color--c9b4e0, #C9B4E0);
  stop-opacity: 0;
}

.wy1hr5y1h {
  d: path("M22.99 19.44v10.54h4v-2.37c-.09-3.29-1.63-6.21-4-8.17");
}

.x8sha6mnc {
  d: path("M17.99 25.04a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.xfk5_2xnq {
  stop-color: var(--svg-color--d7d2dd, #D7D2DD);
  stop-opacity: 0;
}

.xkdh7xtpc {
  stop-color: var(--svg-color--b99384, #B99384);
}

.xnke96byi {
  stop-color: var(--svg-color--736a6c, #736A6C);
}

.xpw6t3bxs {
  stop-color: var(--svg-color--bdb7c4, #BDB7C4);
}

.y1qnskbjy {
  stop-color: var(--svg-color--c1b1d5, #C1B1D5);
  stop-opacity: 0;
}

.y1trv655f {
  stop-color: var(--svg-color--835a59, #835A59);
}

.y2y8kppey {
  stop-color: var(--svg-color--c8bebf, #C8BEBF);
}

.yjx9o43ii {
  d: path("M15.937 1.99c-4.98 0-9.01 4.03-9.01 9.01s4.03 9.01 9.01 9.01s9.01-4.03 9.01-9.01s-4.04-9.01-9.01-9.01");
}

.yt0sjmb1z {
  stop-color: var(--svg-color--d4d0d7, #D4D0D7);
}

.yx5v_dk3v {
  stop-color: var(--svg-color--877f8d, #877F8D);
}

.z_vepkinu {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
}

.z9sdo-btf {
  d: path("M13.713 9.481a.91.91 0 0 0-.876 1.149h1.756a1 1 0 0 0 .033-.24a.915.915 0 0 0-.913-.909");
}

.zd-keimcv {
  stop-color: var(--svg-color--938b9c, #938B9C);
}

.zdd7s4gqs {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
}

.zgtcnu2sf {
  stop-color: var(--svg-color--a17471, #A17471);
  stop-opacity: 0;
}

.zk7oijy-r {
  stop-color: var(--svg-color--3d3438, #3D3438);
  stop-opacity: 0;
}

.zl1nvac2j {
  stop-color: var(--svg-color--c8b9da, #C8B9DA);
  stop-opacity: 0;
}

.zpvtvnbep {
  stop-color: var(--svg-color--4c2e35, #4C2E35);
}

.zzxdaxbga {
  stop-color: var(--svg-color--7c525a, #7C525A);
}

</style>
