<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZyFstc)" class="bmdpf4wuk"/><path fill="url(#i3QoCfc)" class="bmdpf4wuk"/><path fill="url(#iqoVp8c)" class="bmdpf4wuk"/><path fill="url(#iEMJ8Bb)" class="bmdpf4wuk"/><path fill="url(#i8KCMtW)" class="bmdpf4wuk"/><path class="xf2opsb3a"/><path fill="url(#izCZMmi)" class="rrk_4bb5u"/><path fill="url(#iwycdCV)" class="rrk_4bb5u"/><path fill="url(#iIzbeSd)" class="rrk_4bb5u"/><path fill="url(#iRPAmNc)" class="rrk_4bb5u"/><path class="wrhte8bsl"/><path fill="url(#isNLGfq)" class="i1nu_80dz"/><path fill="url(#iaRjLEb)" class="i1nu_80dz"/><path fill="url(#iA0Y7Qb)" class="i1nu_80dz"/><g filter="url(#ikuOWhc)"><path fill="url(#i5kEYjc)" class="bk54hjl7x"/></g><g filter="url(#irKG9Ad)"><path class="dnazjxbei"/></g><g filter="url(#i3kBXPe)"><path class="c0156tydt"/></g><g filter="url(#il8EKhW)"><path fill="url(#iPWyAEc)" class="ej4qybc4v"/></g><g filter="url(#id0VgAq)"><path fill="url(#iZEHnib)" class="aymqfdc9h"/></g><g filter="url(#idWCBzW)"><path stroke="url(#iveJrlx)" class="vlvwenz1w"/></g><g filter="url(#iCRrFgt)"><path stroke="url(#iyXpkGB)" class="sa_ie2xef"/></g><path fill="url(#iufSQfF)" class="wx8zj3ibb"/><g filter="url(#iooBYpe)"><path fill="url(#ilrndMd)" class="dl0akgbkb"/><path fill="url(#iQWxelH)" class="dl0akgbkb"/><path fill="url(#ihUkBIe)" class="dl0akgbkb"/></g><path fill="url(#iC85Iad)" class="dl0akgbkb"/><path fill="url(#ish3Mwd)" class="dl0akgbkb"/><rect fill="url(#iiwzqab)" class="c5mifpswx"/><rect fill="url(#iTCRhDv)" class="c5mifpswx"/><rect fill="url(#i9HiKBe)" class="c5mifpswx"/><rect fill="url(#iR6N5Zd)" class="nzcbnhq8h"/><rect fill="url(#isHF8Xc)" class="nzcbnhq8h"/><rect fill="url(#i9Wns5d)" class="nzcbnhq8h"/><path fill="url(#itaRmTc)" class="k14mqzbhm"/><path fill="url(#im5VnDe)" class="k14mqzbhm"/><path fill="url(#ieDqMib)" class="k14mqzbhm"/><g filter="url(#i1J4Qgb)"><path fill="url(#iC8bZFb)" class="nv0wgac0g"/></g><g filter="url(#i3FD35d)"><path fill="url(#iAxGs6b)" class="yz039z2rc"/></g><path fill="url(#ihRbpqd)" class="dm1r4g2jn"/><path fill="url(#idxLs5c)" class="dm1r4g2jn"/><g filter="url(#ihBaFme)"><path class="htvtykbql"/></g><g filter="url(#i0kz6fc)"><path fill="url(#idH4t1c)" class="nsik4xocu"/><path fill="url(#i9KTvzn)" class="nsik4xocu"/></g><path fill="url(#ielUk3d)" class="nsik4xocu"/><path fill="url(#i5Nxjub)" class="nsik4xocu"/><path fill="url(#i8b76Je)" class="nsik4xocu"/><path fill="url(#iJgEjqb)" class="nsik4xocu"/><path fill="url(#i9gOLfd)" class="nsik4xocu"/><path fill="url(#ivtWLHA)" class="nsik4xocu"/><path fill="url(#iQTYFKc)" class="nsik4xocu"/><g filter="url(#iPuQSTc)"><path fill="url(#inZh9qR)" class="yzst-9bbx"/></g><g filter="url(#il4QPzb)"><path fill="url(#iikd7ac)" class="kpwp29bmt"/><path fill="url(#iWSTU6d)" class="kpwp29bmt"/><path fill="url(#iSZHKEw)" class="kpwp29bmt"/><path fill="url(#inD6Ond)" class="kpwp29bmt"/><path fill="url(#ib6yY1c)" class="kpwp29bmt"/></g><g filter="url(#icWER8b)"><path stroke="url(#iEINpMb)" class="pg65_q4kh"/></g><path class="wxtwq7bjt"/><g filter="url(#iSp56Je)"><path class="e8npywbws"/></g><g filter="url(#id3ZKuj)"><path class="rsdcxubqx"/></g><path class="u3xl1jrbt"/><path fill="url(#i6AWuKe)" class="d16zejbjl"/><path class="fgfgdzjij"/><g filter="url(#i4aCs8z)"><path class="ci99a2ldy"/><path fill="url(#iwg1ruA)" class="i1xqauzdh"/></g><g filter="url(#iQBXxjb)"><path fill="url(#iQHeArd)" class="pistz2vjn"/></g><path class="zg51kvbob"/><path fill="url(#in3nFLe)" class="qws58tb6l"/><path class="sgzwgj7jw"/><g filter="url(#iHBStHc)"><path fill="url(#iaPuPec)" class="dyk7schbu"/></g><g filter="url(#icwzacb)"><ellipse transform="rotate(-27.914 13.449 9.88)" class="ll6ajcb_a"/><ellipse fill="url(#iS1535d)" transform="rotate(-27.914 13.449 9.88)" class="cfs_zza-h"/></g><g filter="url(#isalTAe)"><path fill="url(#iN6oLec)" class="mlm971bus"/><path fill="url(#iSjejDe)" class="mlm971bus"/><path fill="url(#iuf1hzb)" class="mlm971bus"/><path fill="url(#ifncxyb)" class="mlm971bus"/></g><path fill="url(#iaBY2Ge)" class="k0nkw8byw"/><path fill="url(#iVIA33q)" class="k0nkw8byw"/><path fill="url(#ii73fFb)" class="k0nkw8byw"/><g filter="url(#iO4r4ix)"><rect fill="url(#ikIaz7d)" class="h7_adxbnt"/></g><g filter="url(#i6sx8Bm)"><path class="hajtz3bpg"/></g><defs><radialGradient id="iqoVp8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.67857 -3.21429 0 22.929 24.694)" gradientUnits="userSpaceOnUse"><stop class="f26p0p1be"/><stop offset="1" class="tb_z1g16m"/></radialGradient><radialGradient id="iEMJ8Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90626 2.7154 -1.39838 -4.07159 16.688 18.47)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="v130ylbqw"/><stop offset="1" class="cvz68p03p"/></radialGradient><radialGradient id="izCZMmi" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 0 0 11.8756 21.844 29.467)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="rl--s2bxn"/><stop offset="1" class="v-kyyuk0w"/></radialGradient><radialGradient id="iRPAmNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.53821 -7.17442 0 25 21.806)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="sy5bxccsg"/><stop offset="1" class="veojd009w"/></radialGradient><radialGradient id="isNLGfq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.26999 0 0 -10.4063 9.02 28.998)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="pisufpbzg"/><stop offset="1" class="d6clut5cf"/></radialGradient><radialGradient id="iA0Y7Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 3.70797 0 7.625 30.342)" gradientUnits="userSpaceOnUse"><stop class="z_vepkinu"/><stop offset="1" class="a_7m96h7b"/></radialGradient><radialGradient id="iPWyAEc" cx="0" cy="0" r="1" gradientTransform="rotate(53.881 -16.076 24.92)scale(2.14706)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rdedbifir"/><stop offset="1" class="co8wuy7pr"/></radialGradient><radialGradient id="iufSQfF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 0 0 -4.97705 7.188 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="wi08z5bgf"/><stop offset="1" class="d0gbo-tip"/></radialGradient><radialGradient id="iQWxelH" cx="0" cy="0" r="1" gradientTransform="rotate(-169.849 7.12 8.488)scale(4.49245 1.66714)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="lewnpt48t"/><stop offset="1" class="cmgaqknre"/></radialGradient><radialGradient id="ihUkBIe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61229 2.22988 -.54256 -1.36555 22.928 18.83)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="eckdnoofv"/></radialGradient><radialGradient id="iC85Iad" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09385 -11.9992 0 16 18.136)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="m8nvn-czs"/><stop offset=".943" class="dtg8x0b5w"/></radialGradient><radialGradient id="ish3Mwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.01366 -3.3941 0 16 19.276)" gradientUnits="userSpaceOnUse"><stop class="rsw_em86r"/><stop offset="1" class="xfk5_2xnq"/></radialGradient><radialGradient id="i9HiKBe" cx="0" cy="0" r="1" gradientTransform="matrix(.61774 0 0 2.761 6.093 11.904)" gradientUnits="userSpaceOnUse"><stop class="h2db6f6fo"/><stop offset="1" class="eqvqhkbwy"/></radialGradient><radialGradient id="isHF8Xc" cx="0" cy="0" r="1" gradientTransform="matrix(.98754 0 0 2.55399 24.583 10.638)" gradientUnits="userSpaceOnUse"><stop class="jg30e8bxd"/><stop offset="1" class="djf9lpl6o"/></radialGradient><radialGradient id="i9Wns5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9456 -.49377 0 25.622 10.247)" gradientUnits="userSpaceOnUse"><stop class="s5nmtcc-t"/><stop offset="1" class="teoxnoh1q"/></radialGradient><radialGradient id="im5VnDe" cx="0" cy="0" r="1" gradientTransform="rotate(72.208 .425 16.438)scale(9.27527 14.5186)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="mj0fjsb8e"/><stop offset="1" class="gwnz45kfq"/></radialGradient><radialGradient id="ieDqMib" cx="0" cy="0" r="1" gradientTransform="rotate(-137.406 9.643 7.237)scale(5.26375 2.32464)" gradientUnits="userSpaceOnUse"><stop class="zdd7s4gqs"/><stop offset="1" class="a2dspgbsf"/></radialGradient><radialGradient id="iAxGs6b" cx="0" cy="0" r="1" gradientTransform="rotate(123.891 7.389 7.971)scale(12.2137)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="yx5v_dk3v"/><stop offset="1" class="y2y8kppey"/></radialGradient><radialGradient id="idxLs5c" cx="0" cy="0" r="1" gradientTransform="rotate(6.45 -87.936 138.738)scale(8.5401)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="vzafmqbsv"/><stop offset="1" class="kfjcj3jmf"/></radialGradient><radialGradient id="idH4t1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.24745 -6.27497 0 15.995 12.404)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="d710g-wsf"/><stop offset="1" class="amafqjqmi"/></radialGradient><radialGradient id="i9KTvzn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 -.79113 1.295 -4.09225 20.657 14.693)" gradientUnits="userSpaceOnUse"><stop class="bwk05gb1x"/><stop offset="1" class="u4zaaccli"/></radialGradient><radialGradient id="i5Nxjub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.125 8.75502 0 15.995 16.28)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zvqco6bxg"/><stop offset="1" class="zmd91vtsf"/></radialGradient><radialGradient id="i8b76Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.81982 -7.24372 0 15.995 9.56)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="xatg-0b0x"/><stop offset="1" class="ruc7gjbis"/></radialGradient><radialGradient id="iJgEjqb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 0 0 -1.26563 20.25 15.748)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="oeydhsg5m"/><stop offset="1" class="tjqzhbfva"/></radialGradient><radialGradient id="i9gOLfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.50028 -6.12674 0 15.995 8.021)" gradientUnits="userSpaceOnUse"><stop class="s9e05lb0u"/><stop offset="1" class="n5e1pv9su"/></radialGradient><radialGradient id="ivtWLHA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.18986 1.26423 0 14.074 9.735)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bf05anboq"/><stop offset="1" class="vuvzbfb1p"/></radialGradient><radialGradient id="iQTYFKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 .43601 -.29198 -.84753 13.876 10.474)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="b0i_kim7g"/><stop offset="1" class="nabvopa2q"/></radialGradient><radialGradient id="inZh9qR" cx="0" cy="0" r="1" gradientTransform="rotate(146.924 6.147 8.133)scale(1.04487 1.23672)" gradientUnits="userSpaceOnUse"><stop class="ow13h05mk"/><stop offset="1" class="ew748zu8t"/></radialGradient><radialGradient id="iWSTU6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.70313 0 0 -.32031 16.298 12.219)" gradientUnits="userSpaceOnUse"><stop class="mu8mz0bgu"/><stop offset="1" class="rbflw3tvt"/></radialGradient><radialGradient id="iSZHKEw" cx="0" cy="0" r="1" gradientTransform="matrix(.2554 2.91155 -.39026 .03423 16.212 9.608)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="qx_em3bfz"/><stop offset="1" class="qs77v6cuq"/></radialGradient><radialGradient id="iEINpMb" cx="0" cy="0" r="1" gradientTransform="matrix(.62856 -.66852 2.11441 1.98802 14.525 14.297)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="dt77-pbao"/><stop offset="1" class="fftwuebwt"/></radialGradient><radialGradient id="i6AWuKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82614 -1.31407 0 18.169 9.977)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="m_2s0rt2o"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dwsv4tgiz"/></radialGradient><radialGradient id="iwg1ruA" cx="0" cy="0" r="1" gradientTransform="matrix(-.23615 -.30432 .41897 -.32513 17.937 10.063)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="in3nFLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82618 -1.31413 0 13.725 9.977)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="m_2s0rt2o"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dwsv4tgiz"/></radialGradient><radialGradient id="iS1535d" cx="0" cy="0" r="1" gradientTransform="matrix(-.00788 -.5031 .60476 -.00947 13.434 10.2)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iN6oLec" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50166 -9.15821 0 16 3.5)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="lalxu4bkj"/><stop offset="1" class="w-jvyybfs"/></radialGradient><radialGradient id="iSjejDe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 -2.42187 2.377 1.01214 9.328 9.045)" gradientUnits="userSpaceOnUse"><stop class="f2tw_xhyp"/><stop offset="1" class="h8vr8dbmo"/></radialGradient><radialGradient id="iuf1hzb" cx="0" cy="0" r="1" gradientTransform="rotate(-147.95 12.02 3.515)scale(12.72 10.6468)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="d1-tygbiz"/><stop offset="1" class="ijavpvb5h"/></radialGradient><radialGradient id="iaBY2Ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.07812 0 0 1.2594 18.172 15.16)" gradientUnits="userSpaceOnUse"><stop class="xnke96byi"/><stop offset=".78" class="gvh11p6ie"/></radialGradient><linearGradient id="iZyFstc" x1="10.179" x2="21.429" y1="30.516" y2="30.516" gradientUnits="userSpaceOnUse"><stop offset=".006" class="hwnz8bbgx"/><stop offset="1" class="efhowwcgb"/></linearGradient><linearGradient id="i3QoCfc" x1="8.688" x2="10.844" y1="26.123" y2="26.154" gradientUnits="userSpaceOnUse"><stop class="nqsdswamn"/><stop offset=".231" class="cdku7hg9b"/><stop offset="1" class="oj2-77bel"/></linearGradient><linearGradient id="i8KCMtW" x1="16.594" x2="16.594" y1="30.529" y2="29.623" gradientUnits="userSpaceOnUse"><stop class="v-k4gup8y"/><stop offset="1" class="wjgrr3bwb"/></linearGradient><linearGradient id="iwycdCV" x1="22.797" x2="23.438" y1="26.607" y2="26.592" gradientUnits="userSpaceOnUse"><stop offset=".127" class="t-c91xbtu"/><stop offset="1" class="zl1nvac2j"/></linearGradient><linearGradient id="iIzbeSd" x1="27" x2="26.281" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset="1" class="arric2tqt"/></linearGradient><linearGradient id="iaRjLEb" x1="9.07" x2="8.695" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="og0r_u8md"/><stop offset="1" class="y1qnskbjy"/></linearGradient><linearGradient id="i5kEYjc" x1="20.5" x2="11.49" y1="29.685" y2="29.685" gradientUnits="userSpaceOnUse"><stop class="fatndpbme"/><stop offset="1" class="skyfyac-t"/></linearGradient><linearGradient id="iZEHnib" x1="17.344" x2="18.766" y1="24.764" y2="23.357" gradientUnits="userSpaceOnUse"><stop class="rm14ccb4q"/><stop offset="1" class="d6v2o-bft"/></linearGradient><linearGradient id="iveJrlx" x1="18.875" x2="17.383" y1="23.271" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="btagy7mof"/><stop offset=".531" class="qzlgi0c-c"/></linearGradient><linearGradient id="iyXpkGB" x1="14.875" x2="13.383" y1="23.271" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="s5ud30bqo"/><stop offset=".531" class="rwl3x2rgk"/></linearGradient><linearGradient id="ilrndMd" x1="21.612" x2="8.017" y1="19.604" y2="19.604" gradientUnits="userSpaceOnUse"><stop class="bvm_ssbmv"/><stop offset="1" class="qox001bns"/></linearGradient><linearGradient id="iiwzqab" x1="8.296" x2="8.296" y1="8.927" y2="12.498" gradientUnits="userSpaceOnUse"><stop class="okcn0pbqd"/><stop offset="1" class="zd-keimcv"/></linearGradient><linearGradient id="iTCRhDv" x1="7.125" x2="7.125" y1="13.912" y2="13.185" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></linearGradient><linearGradient id="iR6N5Zd" x1="25.191" x2="25.191" y1="8.927" y2="14.062" gradientUnits="userSpaceOnUse"><stop class="wgw2105cx"/><stop offset=".743" class="tkxxt2z6p"/><stop offset="1" class="umazj-pya"/></linearGradient><linearGradient id="itaRmTc" x1="23.938" x2="8.094" y1="6.435" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="yt0sjmb1z"/><stop offset="1" class="egb-_obih"/></linearGradient><linearGradient id="iC8bZFb" x1="23.726" x2="8.302" y1="6.556" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="g4r6pf4wm"/><stop offset="1" class="xpw6t3bxs"/></linearGradient><linearGradient id="ihRbpqd" x1="9.875" x2="23.344" y1="12.154" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="k8zoqmmdl"/><stop offset=".276" class="s6m-cnbld"/></linearGradient><linearGradient id="ielUk3d" x1="21.198" x2="19.954" y1="12.06" y2="12.021" gradientUnits="userSpaceOnUse"><stop class="f6jhdrc8u"/><stop offset="1" class="q_33ekmzw"/></linearGradient><linearGradient id="iikd7ac" x1="15.947" x2="16.818" y1="11.754" y2="11.754" gradientUnits="userSpaceOnUse"><stop class="lzngnw3he"/><stop offset="1" class="q6_c5eb2e"/></linearGradient><linearGradient id="inD6Ond" x1="15.947" x2="15.947" y1="12.865" y2="12.334" gradientUnits="userSpaceOnUse"><stop class="zbimuxzqc"/><stop offset="1" class="fal0e6bzl"/></linearGradient><linearGradient id="ib6yY1c" x1="15.947" x2="15.947" y1="9.699" y2="10.495" gradientUnits="userSpaceOnUse"><stop class="y_chkab7d"/><stop offset="1" class="gi1pt5b7k"/></linearGradient><linearGradient id="iQHeArd" x1="18.961" x2="18.642" y1="10.032" y2="10.229" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaPuPec" x1="14.483" x2="14.163" y1="10.032" y2="10.229" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifncxyb" x1="23.3" x2="21.625" y1="9.404" y2="7.342" gradientUnits="userSpaceOnUse"><stop class="m9pa3mbws"/><stop offset="1" class="u_tn6mbuw"/></linearGradient><linearGradient id="iVIA33q" x1="17.586" x2="17.961" y1="15.201" y2="15.201" gradientUnits="userSpaceOnUse"><stop class="rvgaerxsl"/><stop offset="1" class="wdhp9kbzq"/></linearGradient><linearGradient id="ii73fFb" x1="19.234" x2="19.234" y1="15.764" y2="15.568" gradientUnits="userSpaceOnUse"><stop class="u9byv1bdc"/><stop offset="1" class="zk7oijy-r"/></linearGradient><linearGradient id="ikIaz7d" x1="18.216" x2="20.402" y1="15.224" y2="15.224" gradientUnits="userSpaceOnUse"><stop class="ueq20f_ji"/><stop offset="1" class="o69d91bgq"/></linearGradient><filter id="ikuOWhc" width="9.31" height="4.17" x="11.34" y="25.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.811765 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.635294 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2540" result="effect2_innerShadow_4002_2540"/></filter><filter id="irKG9Ad" width="3.12" height="3.12" x="12.255" y="22.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".25"/></filter><filter id="i3kBXPe" width="3.12" height="3.12" x="16.325" y="22.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".25"/></filter><filter id="il8EKhW" width="2.12" height="2.12" x="12.94" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.498039 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter><filter id="id0VgAq" width="2.12" height="2.12" x="16.94" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.180392 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter><filter id="idWCBzW" width="2.05" height="2.05" x="16.975" y="22.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".05"/></filter><filter id="iCRrFgt" width="2.05" height="2.05" x="12.975" y="22.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".05"/></filter><filter id="iooBYpe" width="14.359" height="6.364" x="8.82" y="15.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.87451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter><filter id="i1J4Qgb" width="18.043" height="18.043" x="6.926" y="1.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".125"/></filter><filter id="i3FD35d" width="16.155" height="16.155" x="7.869" y="2.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".15"/></filter><filter id="ihBaFme" width="14.583" height="16.385" x="9.073" y="2.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".75"/></filter><filter id="i0kz6fc" width="10.407" height="12.567" x="10.791" y="4.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.290196 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter><filter id="iPuQSTc" width="3.912" height="4.953" x="13.78" y="9.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".5"/></filter><filter id="il4QPzb" width="2.112" height="3.153" x="14.892" y="9.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.552941 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/><feGaussianBlur result="effect2_foregroundBlur_4002_2540" stdDeviation=".05"/></filter><filter id="icWER8b" width="3.677" height="1.492" x="14.108" y="13.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".05"/></filter><filter id="iSp56Je" width="2.28" height="1.259" x="17.565" y="7.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter><filter id="id3ZKuj" width="2.28" height="1.244" x="12.213" y="7.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter><filter id="i4aCs8z" width=".798" height=".705" x="17.423" y="9.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".05"/></filter><filter id="iQBXxjb" width=".9" height=".923" x="18.28" y="9.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".1"/></filter><filter id="iHBStHc" width=".997" height="1.052" x="13.756" y="9.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".1"/></filter><filter id="icwzacb" width=".926" height=".714" x="12.986" y="9.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".05"/></filter><filter id="isalTAe" width="14.6" height="5.86" x="8.7" y="3.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.215686 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.219608 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2540" result="effect2_innerShadow_4002_2540"/></filter><filter id="iO4r4ix" width="3.344" height=".781" x="17.797" y="14.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2540" stdDeviation=".125"/></filter><filter id="i6sx8Bm" width="6.686" height="4.857" x="16.38" y="13.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.486275 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2540"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:astronaut-medium-light" /></template>
<style>
.a_7m96h7b {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
  stop-opacity: 0;
}

.a2dspgbsf {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
  stop-opacity: 0;
}

.amafqjqmi {
  stop-color: var(--svg-color--825640, #825640);
}

.arric2tqt {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
  stop-opacity: 0;
}

.aymqfdc9h {
  d: path("M18 25.05a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.b0i_kim7g {
  stop-color: var(--svg-color--ba886e, #BA886E);
}

.bf05anboq {
  stop-color: var(--svg-color--b37e6e, #B37E6E);
}

.bk54hjl7x {
  d: path("M19.68 25.98h-7.37c-.45 0-.82.37-.82.82V30h9.01v-3.2c0-.46-.36-.82-.82-.82");
}

.bmdpf4wuk {
  d: path("M21.6 18.47H10.39c-3.23 1.92-5.4 5.44-5.4 9.47v2.05h22.02v-2.05c0-4.03-2.17-7.55-5.41-9.47");
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.btagy7mof {
  stop-color: var(--svg-color--fb4f70, #FB4F70);
}

.bvm_ssbmv {
  stop-color: var(--svg-color--f0e4fc, #F0E4FC);
}

.bwk05gb1x {
  stop-color: var(--svg-color--8a664e, #8A664E);
}

.c0156tydt {
  fill: var(--svg-color--d1b8d6, #D1B8D6);
  d: path("M17.885 25.235a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.c5mifpswx {
  width: 4.406px;
  height: 4.984px;
  x: 6.093px;
  y: 8.927px;
  rx: 0.75px;
}

.cdku7hg9b {
  stop-color: var(--svg-color--d3cade, #D3CADE);
}

.cfs_zza-h {
  cx: 13.449px;
  cy: 9.88px;
  rx: 0.397px;
  ry: 0.201px;
}

.ci99a2ldy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.683c.065.087-.07.192-.224.307s-.268.197-.333.11s.008-.25.161-.365c.154-.115.332-.138.396-.052");
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

.d16zejbjl {
  d: path("M18.171 9.491a.91.91 0 0 1 .876 1.149H17.29a.912.912 0 0 1 .88-1.148");
}

.d6clut5cf {
  stop-color: var(--svg-color--c4c1c5, #C4C1C5);
}

.d6v2o-bft {
  stop-color: var(--svg-color--f13c6a, #F13C6A);
}

.d710g-wsf {
  stop-color: var(--svg-color--d7a190, #D7A190);
}

.djf9lpl6o {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
  stop-opacity: 0;
}

.dl0akgbkb {
  d: path("M23.18 18.396c0 1.463-2.782 3.516-7.18 3.516c-4.469-.047-7.18-2.053-7.18-3.516s3.215-2.648 7.18-2.648s7.18 1.185 7.18 2.648");
}

.dm1r4g2jn {
  d: path("M16 18.526a7.516 7.516 0 1 0 0-15.031a7.516 7.516 0 0 0 0 15.03");
}

.dnazjxbei {
  fill: var(--svg-color--d6bcdb, #D6BCDB);
  d: path("M13.815 25.235a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.dt77-pbao {
  stop-color: var(--svg-color--d0a090, #D0A090);
}

.dtg8x0b5w {
  stop-color: var(--svg-color--c9a7ef, #C9A7EF);
}

.dwsv4tgiz {
  stop-color: var(--svg-color--5f3f37, #5F3F37);
}

.dyk7schbu {
  d: path("M14.554 10.293c0-.293-.24-.49-.304-.548l-.294.284l.181.367z");
}

.e8npywbws {
  fill: var(--svg-color--703f2c, #703F2C);
  d: path("M19.748 7.876a1.9 1.9 0 0 0-.7-.419c-.31-.097-.698-.124-1.234-.058a.282.282 0 0 0 .068.56c.49-.06.79-.028.997.037c.201.063.338.166.498.306a.282.282 0 0 0 .371-.426");
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

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.ej4qybc4v {
  d: path("M14 25.05a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.eqvqhkbwy {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
  stop-opacity: 0;
}

.ew748zu8t {
  stop-color: var(--svg-color--c9907c, #C9907C);
}

.f26p0p1be {
  stop-color: var(--svg-color--f7efff, #F7EFFF);
}

.f2tw_xhyp {
  stop-color: var(--svg-color--6c6176, #6C6176);
}

.f6jhdrc8u {
  stop-color: var(--svg-color--6b4538, #6B4538);
}

.fal0e6bzl {
  stop-color: var(--svg-color--cb917f, #CB917F);
  stop-opacity: 0;
}

.fatndpbme {
  stop-color: var(--svg-color--cdc0da, #CDC0DA);
}

.fftwuebwt {
  stop-color: var(--svg-color--d0a090, #D0A090);
  stop-opacity: 0;
}

.fgfgdzjij {
  fill: var(--svg-color--000, #000);
  d: path("M17.65 10.4c0-.289.232-.52.521-.52a.518.518 0 0 1 .463.76h-.921a.47.47 0 0 1-.062-.24");
}

.ft5dv1b6b {
  fill: none;
}

.g4r6pf4wm {
  stop-color: var(--svg-color--bab4c1, #BAB4C1);
}

.gi1pt5b7k {
  stop-color: var(--svg-color--b38074, #B38074);
  stop-opacity: 0;
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

.h7_adxbnt {
  width: 2.844px;
  height: 0.281px;
  x: 18.047px;
  y: 14.943px;
  rx: 0.141px;
}

.h8vr8dbmo {
  stop-color: var(--svg-color--6c6176, #6C6176);
  stop-opacity: 0;
}

.hajtz3bpg {
  fill: var(--svg-color--b9b2bf, #B9B2BF);
  d: path("M23.016 13.71h-.956c-.4-.01-.78.19-1 .53a6.04 6.04 0 0 1-3.92 2.67c-.44.08-.76.46-.76.91v.696a7.52 7.52 0 0 0 6.636-4.806");
}

.htvtykbql {
  fill: var(--svg-color--1f1428, #1F1428);
  d: path("M10.843 14.054c.292 2.117 2.175 3.694 4.404 3.694h2.138c2.23 0 4.112-1.577 4.404-3.694c.133-2.043.268-4.078.367-6.12c-.012-.831-.697-1.518-1.563-1.552h-1.587c-1.082 0-2.061-.611-2.506-1.565a.75.75 0 0 0-.697-.454H14.36c-2.092 0-3.787 1.64-3.787 3.665c0 2.018.132 4.003.27 6.026");
}

.hwnz8bbgx {
  stop-color: var(--svg-color--dbcfea, #DBCFEA);
}

.i1nu_80dz {
  d: path("m9.003 29.99l.017-.01V19.43a10.98 10.98 0 0 0-4.03 8.509v2.05z");
}

.i1xqauzdh {
  d: path("M18.104 9.683c.065.087-.07.192-.224.307s-.268.197-.333.11s.008-.25.161-.365c.154-.115.332-.138.396-.052");
}

.ijavpvb5h {
  stop-color: var(--svg-color--493b54, #493B54);
}

.jg30e8bxd {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
}

.k0nkw8byw {
  d: path("M18.02 15.66h2.97c.28 0 .5-.22.5-.5s-.22-.5-.5-.5h-2.97c-.28 0-.5.22-.5.5s.23.5.5.5");
}

.k14mqzbhm {
  d: path("M15.947 2c-4.98 0-9.01 4.03-9.01 9.01s4.03 9.01 9.01 9.01s9.01-4.03 9.01-9.01S20.917 2 15.947 2");
}

.k8zoqmmdl {
  stop-color: var(--svg-color--4e4257, #4E4257);
}

.kfjcj3jmf {
  stop-color: var(--svg-color--362b3d, #362B3D);
}

.kpwp29bmt {
  d: path("m15.558 10.182l-.541 1.872c-.11.385.154.77.53.77h.8c.376 0 .641-.39.53-.77l-.54-1.872c-.116-.414-.658-.414-.78 0");
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

.ll6ajcb_a {
  cx: 13.449px;
  cy: 9.88px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.lzngnw3he {
  stop-color: var(--svg-color--cd9a80, #CD9A80);
}

.m_2s0rt2o {
  stop-color: var(--svg-color--6c4941, #6C4941);
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

.mlm971bus {
  d: path("M16 6.8a12 12 0 0 1 7.3 2.46c-.79-3.3-3.76-5.76-7.3-5.76S9.49 5.96 8.7 9.26A12 12 0 0 1 16 6.8");
}

.mu8mz0bgu {
  stop-color: var(--svg-color--e1b29b, #E1B29B);
}

.n5e1pv9su {
  stop-color: var(--svg-color--a06f6c, #A06F6C);
  stop-opacity: 0;
}

.nabvopa2q {
  stop-color: var(--svg-color--ba886e, #BA886E);
  stop-opacity: 0;
}

.nqsdswamn {
  stop-color: var(--svg-color--baa7d0, #BAA7D0);
}

.nsik4xocu {
  d: path("M11.034 13.726a3.99 3.99 0 0 0 3.957 3.468h1.92a3.99 3.99 0 0 0 3.957-3.468c.12-1.919.241-3.829.33-5.746a1.476 1.476 0 0 0-1.404-1.458H18.37a2.47 2.47 0 0 1-2.253-1.47a.68.68 0 0 0-.626-.426h-1.296c-1.88 0-3.403 1.54-3.403 3.441c0 1.895.119 3.759.243 5.659");
}

.nv0wgac0g {
  d: path("M15.947 2.238a8.767 8.767 0 0 0-8.771 8.772a8.767 8.767 0 0 0 8.771 8.772a8.767 8.767 0 0 0 8.772-8.772c0-4.848-3.933-8.772-8.772-8.772");
}

.nzcbnhq8h {
  width: 4.406px;
  height: 4.984px;
  x: 21.499px;
  y: 8.927px;
  rx: 0.75px;
}

.o69d91bgq {
  stop-color: var(--svg-color--5c595d, #5C595D);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeydhsg5m {
  stop-color: var(--svg-color--663d28, #663D28);
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

.ow13h05mk {
  stop-color: var(--svg-color--c49176, #C49176);
}

.pg65_q4kh {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.947 13.86a3.06 3.06 0 0 1-1.41-.335c-.14-.07-.29.086-.202.213c.34.517.935.861 1.612.861s1.271-.344 1.612-.861c.088-.132-.062-.284-.201-.213a3.04 3.04 0 0 1-1.41.335Z");
}

.pistz2vjn {
  d: path("M18.98 10.28a.86.86 0 0 0-.235-.47l-.265.29l.12.232z");
}

.pisufpbzg {
  stop-color: var(--svg-color--c4c1c5, #C4C1C5);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_33ekmzw {
  stop-color: var(--svg-color--8e6855, #8E6855);
  stop-opacity: 0;
}

.q6_c5eb2e {
  stop-color: var(--svg-color--ddaa8f, #DDAA8F);
}

.qox001bns {
  stop-color: var(--svg-color--d8d0e0, #D8D0E0);
}

.qs77v6cuq {
  stop-color: var(--svg-color--d7a88f, #D7A88F);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qws58tb6l {
  d: path("M13.723 9.491a.91.91 0 0 0-.876 1.149h1.756a1 1 0 0 0 .033-.24a.915.915 0 0 0-.913-.909");
}

.qx_em3bfz {
  stop-color: var(--svg-color--d7a88f, #D7A88F);
}

.qzlgi0c-c {
  stop-color: var(--svg-color--f34b6c, #F34B6C);
  stop-opacity: 0;
}

.rbflw3tvt {
  stop-color: var(--svg-color--e1b29b, #E1B29B);
  stop-opacity: 0;
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

.rrk_4bb5u {
  d: path("M23 19.45v10.54h4v-2.37c-.09-3.29-1.63-6.21-4-8.17");
}

.rsdcxubqx {
  fill: var(--svg-color--703f2c, #703F2C);
  d: path("M12.474 7.765a2.82 2.82 0 0 1 1.77-.366a.282.282 0 1 1-.068.56a2.26 2.26 0 0 0-1.412.29a1 1 0 0 0-.093.061l-.003.002a.282.282 0 0 1-.346-.446z");
}

.rsw_em86r {
  stop-color: var(--svg-color--d7d2dd, #D7D2DD);
}

.ruc7gjbis {
  stop-color: var(--svg-color--603926, #603926);
}

.rvgaerxsl {
  stop-color: var(--svg-color--615962, #615962);
}

.rwl3x2rgk {
  stop-color: var(--svg-color--4d90df, #4D90DF);
  stop-opacity: 0;
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

.s9e05lb0u {
  stop-color: var(--svg-color--a06f6c, #A06F6C);
}

.sa_ie2xef {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14 24.865a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.sgzwgj7jw {
  fill: var(--svg-color--000, #000);
  d: path("M14.244 10.4a.52.52 0 0 0-.52-.52a.518.518 0 0 0-.463.76h.92a.5.5 0 0 0 .063-.24");
}

.skyfyac-t {
  stop-color: var(--svg-color--beb1cc, #BEB1CC);
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

.tjqzhbfva {
  stop-color: var(--svg-color--82553f, #82553F);
  stop-opacity: 0;
}

.tkxxt2z6p {
  stop-color: var(--svg-color--afa9b7, #AFA9B7);
}

.u_tn6mbuw {
  stop-color: var(--svg-color--726080, #726080);
  stop-opacity: 0;
}

.u3xl1jrbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.382 9.215c.665 0 1.227.458 1.38 1.078a.28.28 0 0 1-.273.347h-2.272a.234.234 0 0 1-.231-.277a1.42 1.42 0 0 1 1.396-1.148");
}

.u4zaaccli {
  stop-color: var(--svg-color--c69c82, #C69C82);
  stop-opacity: 0;
}

.u9byv1bdc {
  stop-color: var(--svg-color--3d3438, #3D3438);
}

.ueq20f_ji {
  stop-color: var(--svg-color--797278, #797278);
}

.umazj-pya {
  stop-color: var(--svg-color--8e8895, #8E8895);
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

.vlvwenz1w {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18 24.865a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.vuvzbfb1p {
  stop-color: var(--svg-color--b37e6e, #B37E6E);
  stop-opacity: 0;
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

.wrhte8bsl {
  fill: var(--svg-color--d9cde8, #D9CDE8);
  d: path("m9.003 29.99l.017-.01V19.43a10.98 10.98 0 0 0-4.03 8.509v2.05z");
}

.wx8zj3ibb {
  d: path("M7.36 28.66v-1.62c0-.19-.15-.34-.34-.34H5.06c-.03.26-.05.53-.06.8l.01 1.5h2.02c.18 0 .33-.15.33-.34");
}

.wxtwq7bjt {
  fill: var(--svg-color--89014e, #89014E);
  d: path("M15.947 13.86a3.06 3.06 0 0 1-1.41-.335c-.14-.07-.29.086-.202.213c.34.517.935.861 1.612.861s1.271-.344 1.612-.861c.088-.132-.062-.284-.201-.213a3.04 3.04 0 0 1-1.41.335");
}

.xatg-0b0x {
  stop-color: var(--svg-color--825743, #825743);
  stop-opacity: 0;
}

.xf2opsb3a {
  fill: var(--svg-color--ebdef9, #EBDEF9);
  d: path("M23 19.45v10.54h4v-2.37c-.09-3.29-1.63-6.21-4-8.17");
}

.xfk5_2xnq {
  stop-color: var(--svg-color--d7d2dd, #D7D2DD);
  stop-opacity: 0;
}

.xnke96byi {
  stop-color: var(--svg-color--736a6c, #736A6C);
}

.xpw6t3bxs {
  stop-color: var(--svg-color--bdb7c4, #BDB7C4);
}

.y_chkab7d {
  stop-color: var(--svg-color--b38074, #B38074);
}

.y1qnskbjy {
  stop-color: var(--svg-color--c1b1d5, #C1B1D5);
  stop-opacity: 0;
}

.y2y8kppey {
  stop-color: var(--svg-color--c8bebf, #C8BEBF);
}

.yt0sjmb1z {
  stop-color: var(--svg-color--d4d0d7, #D4D0D7);
}

.yx5v_dk3v {
  stop-color: var(--svg-color--877f8d, #877F8D);
}

.yz039z2rc {
  d: path("M15.947 3.232A7.773 7.773 0 0 0 8.17 11.01a7.773 7.773 0 0 0 7.778 7.778a7.779 7.779 0 0 0 0-15.555");
}

.yzst-9bbx {
  d: path("m15.452 10.382l-.646 1.872c-.11.385.154.77.53.77h.8c.376 0 .641-.391.53-.77l-.54-1.872c-.117-.415-.552-.415-.674 0");
}

.z_vepkinu {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
}

.zbimuxzqc {
  stop-color: var(--svg-color--cb917f, #CB917F);
}

.zd-keimcv {
  stop-color: var(--svg-color--938b9c, #938B9C);
}

.zdd7s4gqs {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
}

.zg51kvbob {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.513 9.215c-.665 0-1.227.458-1.38 1.078a.28.28 0 0 0 .273.347h2.271c.145 0 .26-.132.232-.277a1.43 1.43 0 0 0-1.396-1.148");
}

.zk7oijy-r {
  stop-color: var(--svg-color--3d3438, #3D3438);
  stop-opacity: 0;
}

.zl1nvac2j {
  stop-color: var(--svg-color--c8b9da, #C8B9DA);
  stop-opacity: 0;
}

.zmd91vtsf {
  stop-color: var(--svg-color--794846, #794846);
}

.zvqco6bxg {
  stop-color: var(--svg-color--946260, #946260);
  stop-opacity: 0;
}

</style>
