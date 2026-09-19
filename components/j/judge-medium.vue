<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irFwZVP)" class="jbe938blf"/><path fill="url(#i01RONd)" class="jbe938blf"/><path fill="url(#iSE4sxc)" class="jbe938blf"/><path fill="url(#ikDLleb)" class="kive_m_gh"/><path fill="url(#ipsLuux)" class="kive_m_gh"/><path fill="url(#iq8admc)" class="kive_m_gh"/><path fill="url(#ibTF1ga)" class="kive_m_gh"/><path fill="url(#i148L8d)" class="u-gok8e3r"/><path fill="url(#igcKJFS)" class="u-gok8e3r"/><g filter="url(#iNV8aac)"><path fill="url(#iW8z5Od)" class="or38gufwt"/><path fill="url(#iH80ASb)" class="or38gufwt"/><path fill="url(#iqadcVc)" class="or38gufwt"/></g><path fill="url(#iTbQwld)" class="dxre8vbsy"/><path fill="url(#ihwcoKc)" class="q436rjb1t"/><path fill="url(#iGjnkFl)" class="wdm99-b0x"/><path fill="url(#isJ4GCd)" class="wdm99-b0x"/><path fill="url(#iUL9O7c)" class="p87wxxb3p"/><path fill="url(#iB2IYkd)" class="p87wxxb3p"/><path fill="url(#iRaci0c)" class="v41pyom1m"/><path fill="url(#ika8r8d)" class="v41pyom1m"/><path fill="url(#ildZYyW)" class="v41pyom1m"/><path fill="url(#i13smgc)" class="v41pyom1m"/><path fill="url(#iJXRQJb)" class="v41pyom1m"/><path fill="url(#iBTxFGc)" class="na9bapb1u"/><path fill="url(#i2NyFwc)" class="na9bapb1u"/><path fill="url(#iiZxJqd)" class="na9bapb1u"/><path fill="url(#ihkD1Gc)" class="na9bapb1u"/><path fill="url(#ickswid)" class="c95hs9n7z"/><path fill="url(#iGbGINd)" class="c95hs9n7z"/><path fill="url(#itE8tnd)" class="c95hs9n7z"/><path fill="url(#iscWgIJ)" class="mfj8x92sx"/><path fill="url(#iA7GnDc)" class="mfj8x92sx"/><g filter="url(#ive64ft)"><path fill="url(#is4jU2c)" class="g__d7mboh"/><path fill="url(#iXgMZIc)" class="g__d7mboh"/><path fill="url(#iqw5Ueb)" class="g__d7mboh"/><path fill="url(#iaX1gnd)" class="g__d7mboh"/><path fill="url(#iQwWL4b)" class="g__d7mboh"/></g><rect fill="url(#iXlK71f)" class="sy7sk-bit"/><rect fill="url(#i7WLuKb)" class="sy7sk-bit"/><g filter="url(#it7KGMb)"><path fill="url(#iuHJhgp)" class="k77tk4b5f"/></g><g filter="url(#iCzjNCe)"><path fill="url(#i1HplYd)" class="ni9ok2yqm"/></g><g filter="url(#iOPLs3J)"><path fill="url(#iQR5FFy)" class="csyw8e_zo"/></g><g filter="url(#ioYPlQd)"><path stroke="url(#iH8ph0c)" class="vn0i-3-9o"/></g><g filter="url(#i3JZFwe)"><path stroke="url(#i45gRLe)" class="i7r8nrzil"/></g><g filter="url(#ibCPzEe)"><path stroke="url(#ibOxtBe)" class="u_cllgbfr"/></g><path fill="url(#ilMgjnp)" class="b12rqybcc"/><path fill="url(#iBj4aMb)" class="bgvn65brt"/><g filter="url(#i5vjwKr)"><path fill="url(#iOUnJFd)" class="izs2z8pto"/><path fill="url(#iueFYId)" class="izs2z8pto"/></g><path fill="url(#iHxJV5d)" class="izs2z8pto"/><path fill="url(#ilSNJHb)" class="izs2z8pto"/><path fill="url(#i15hXlb)" class="izs2z8pto"/><path fill="url(#il8IsWd)" class="izs2z8pto"/><path fill="url(#iImAe2b)" class="izs2z8pto"/><path fill="url(#i2sgB6b)" class="izs2z8pto"/><path fill="url(#iTtEvwe)" class="izs2z8pto"/><path fill="url(#iJ6lXJd)" class="izs2z8pto"/><g filter="url(#ikaQywb)"><path class="wycd9cbrf"/></g><g filter="url(#iqPygxc)"><path class="qesbwhu6x"/><path fill="url(#ipjqBcd)" class="xm9q3m5hd"/><path fill="url(#isH7TEN)" class="xm9q3m5hd"/><path fill="url(#i4exrac)" class="xm9q3m5hd"/><path fill="url(#iRIqyfc)" class="xm9q3m5hd"/><path fill="url(#iQt8eDg)" class="xm9q3m5hd"/></g><path fill="url(#is6GwMd)" class="xm9q3m5hd"/><path fill="url(#iqvr6bb)" class="xm9q3m5hd"/><g filter="url(#iLL6Zee)"><path stroke="url(#ipg7QYc)" class="covdgtuis"/></g><path fill="url(#i5uGzur)" class="j57pz9gky"/><g filter="url(#iQJvzAd)"><path fill="url(#iT2YPTc)" class="btcphcbyj"/></g><path fill="url(#ihmC5Rb)" class="btcphcbyj"/><path fill="url(#iHBvJee)" class="btcphcbyj"/><path fill="url(#iNSpyab)" class="btcphcbyj"/><g filter="url(#iXADOKb)"><path class="wd7ykhbml"/></g><g filter="url(#i1SPdHb)"><path class="yos9ueveo"/></g><g filter="url(#ifBHIAb)"><path class="nx9s0ob9q"/><path fill="url(#icp4yxd)" class="lt7qe9bnc"/><path fill="url(#i2axakb)" class="lt7qe9bnc"/></g><g filter="url(#iwYYTyc)"><path class="i51qb4bvo"/><path fill="url(#iCmvhLe)" class="ua37rzaqz"/><path fill="url(#iTOjEyc)" class="ua37rzaqz"/><path fill="url(#ioR83ud)" class="ua37rzaqz"/></g><path class="u4yr2t84f"/><path fill="url(#iYmwQcb)" class="rm9gqqi4t"/><path class="dg7d8bcvt"/><g filter="url(#imCSnQc)"><path class="dcw3_lbai"/><path fill="url(#iQN3wyb)" class="m--70bckn"/></g><g filter="url(#iSqJ49w)"><path fill="url(#i6EFoRl)" class="s1hge_b0w"/></g><path class="fw60b3gol"/><path fill="url(#iSLzJ2b)" class="xdh23sgqk"/><path class="t0guptbkt"/><g filter="url(#iKfmn8c)"><path fill="url(#iCDkhkK)" class="z86scdcth"/></g><g filter="url(#i1wdlrd)"><ellipse transform="rotate(-27.914 13.722 9.804)" class="qwsiv7prr"/><ellipse fill="url(#iFNNgCe)" transform="rotate(-27.914 13.722 9.804)" class="ekp-5bvbp"/></g><path fill="url(#ih4DGeb)" class="s-0q55xsm"/><path fill="url(#ifwAFPq)" class="s-0q55xsm"/><path fill="url(#icg8n0t)" class="s-0q55xsm"/><path fill="url(#imukCDe)" class="s-0q55xsm"/><path fill="url(#iWJAiAd)" class="qr_6k0brn"/><path fill="url(#i65Ntmb)" class="qr_6k0brn"/><g filter="url(#i3aEMib)"><path fill="url(#iv5BPed)" class="gbhjhfb2j"/></g><g filter="url(#iET11He)"><path fill="url(#iGLf0Kb)" class="oy9slob8t"/></g><g filter="url(#ijrl5Qg)"><path class="ecl0zjrag"/></g><g filter="url(#iY937re)"><path class="g0_-i5b1o"/></g><g filter="url(#iDh04fe)"><path class="q-n3w0bgw"/></g><defs><radialGradient id="ikDLleb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.085 30.031)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="ipsLuux" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.933 30.031)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iq8admc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.933 23.082)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="i148L8d" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.105 4.523)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="igcKJFS" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.216 23.185)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iH80ASb" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.175 14.844)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="iqadcVc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.175 16.422)" gradientUnits="userSpaceOnUse"><stop class="o-r-orbbu"/><stop offset="1" class="smcyj7aql"/></radialGradient><radialGradient id="ihwcoKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.163 18.531)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="iGjnkFl" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -1.38289 0 16.936 16.494)" gradientUnits="userSpaceOnUse"><stop class="frwkbz6el"/><stop offset="1" class="os3chxbhl"/></radialGradient><radialGradient id="isJ4GCd" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.165 15.406)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="n626tzb0r"/><stop offset=".957" class="dys9kie4i"/></radialGradient><radialGradient id="iUL9O7c" cx="0" cy="0" r="1" gradientTransform="rotate(145.605 10.47 16.162)scale(2.31047 2.27126)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iB2IYkd" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.492 -29.195)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="ildZYyW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.86 17.424)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="ihkD1Gc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.574 17.25)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="itE8tnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.34 17.5)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iscWgIJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.261 24.316)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iXgMZIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.03 25.336)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iqw5Ueb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.03 26.63)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iaX1gnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.03 27.88)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iQwWL4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.03 29.232)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iXlK71f" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.707 21.492)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="ilMgjnp" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 2.015 20.919)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iBj4aMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 10.119 12.247)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iOUnJFd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.983 10.816)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iueFYId" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.655 8.164)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ilSNJHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 17.756 4.902)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="i15hXlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.622 9.503)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="il8IsWd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.73 -2.188)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iImAe2b" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.618 6.211)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i2sgB6b" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.383 8.083)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iTtEvwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23467 2.49744 -.99833 -.0938 21.72 7.9)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iJ6lXJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.96 10.32)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="isH7TEN" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.641 12.176)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iRIqyfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.758 11.607)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iqvr6bb" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 6.037 8.985)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="i5uGzur" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.684 14.439)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ihmC5Rb" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 10.468 8.892)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iHBvJee" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.48 -4.205)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iNSpyab" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.175 -3.802)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="icp4yxd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.428 3.624)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="i2axakb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.236 -5.963)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iCmvhLe" cx="0" cy="0" r="1" gradientTransform="matrix(3.5152 -2.83003 4.38594 5.4478 18.094 6.18)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iTOjEyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.809 7.438)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="ioR83ud" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 17.945 5.617)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iYmwQcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.357 9.9)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iQN3wyb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.51 .552)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSLzJ2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.993 9.9)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iFNNgCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.706 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifwAFPq" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.793 9.913)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="icg8n0t" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.153 10.458)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="imukCDe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.267 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="i65Ntmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.26 10.555)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iv5BPed" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.26 10.557)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><linearGradient id="irFwZVP" x1="16.162" x2="16.162" y1="15.572" y2="30.457" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="i01RONd" x1="23.59" x2="21.058" y1="26.625" y2="26.657" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="iSE4sxc" x1="8.617" x2="10.833" y1="26.441" y2="26.441" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="ibTF1ga" x1="9.081" x2="8.646" y1="28.098" y2="28.098" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iW8z5Od" x1="22.902" x2="17.027" y1="18.532" y2="18.532" gradientUnits="userSpaceOnUse"><stop class="b-744zb0c"/><stop offset="1" class="jz3pzrmrk"/></linearGradient><linearGradient id="iTbQwld" x1="17.293" x2="15.996" y1="19.11" y2="20.032" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="iRaci0c" x1="27.902" x2="24.527" y1="20.75" y2="20.375" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="ika8r8d" x1="25.622" x2="25.622" y1="21.016" y2="20.5" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="i13smgc" x1="25.622" x2="25.622" y1="16.87" y2="17.501" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iJXRQJb" x1="23.325" x2="24.067" y1="19.217" y2="19.217" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iBTxFGc" x1="23.496" x2="22.199" y1="19.001" y2="19.001" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="i2NyFwc" x1="23.746" x2="23.355" y1="19.281" y2="19.281" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iiZxJqd" x1="22.95" x2="22.95" y1="21.112" y2="20.449" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="ickswid" x1="29.197" x2="27.577" y1="19.449" y2="19.449" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iGbGINd" x1="28.496" x2="28.496" y1="21.086" y2="20.563" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iA7GnDc" x1="25.624" x2="25.652" y1="22.027" y2="22.383" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="is4jU2c" x1="27.621" x2="23.593" y1="28.094" y2="28.094" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="i7WLuKb" x1="25.634" x2="25.634" y1="20.844" y2="21.305" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iuHJhgp" x1="17.212" x2="17.212" y1="29.635" y2="22.958" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="i1HplYd" x1="13.205" x2="13.205" y1="29.635" y2="22.958" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iQR5FFy" x1="21.199" x2="21.199" y1="29.635" y2="22.958" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iH8ph0c" x1="24.113" x2="25.822" y1="26.102" y2="26.102" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i45gRLe" x1="24.035" x2="25.744" y1="27.407" y2="27.407" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ibOxtBe" x1="24.113" x2="25.822" y1="28.711" y2="28.711" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iHxJV5d" x1="21.332" x2="18.803" y1="12.501" y2="12.501" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ipjqBcd" x1="17.013" x2="16.175" y1="11.491" y2="11.525" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i4exrac" x1="16.175" x2="16.175" y1="12.63" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iQt8eDg" x1="16.175" x2="16.175" y1="9.925" y2="10.471" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="is6GwMd" x1="16.591" x2="16.591" y1="12.768" y2="12.575" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="ipg7QYc" x1="14.973" x2="15.292" y1="14.201" y2="13.366" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iT2YPTc" x1="23.027" x2="11.415" y1="5.153" y2="5.153" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="i6EFoRl" x1="19.135" x2="18.821" y1="9.954" y2="10.147" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCDkhkK" x1="14.737" x2="14.423" y1="9.953" y2="10.147" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih4DGeb" x1="22.611" x2="21.404" y1="9.98" y2="12.157" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iWJAiAd" x1="10.325" x2="11.784" y1="10.684" y2="10.557" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iGLf0Kb" x1="21.628" x2="21.628" y1="9.671" y2="11.429" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><filter id="iNV8aac" width="14.254" height="7.618" x="9.149" y="15.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1734" result="effect2_innerShadow_4002_1734"/></filter><filter id="ive64ft" width="4.468" height="5.556" x="23.593" y="24.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/></filter><filter id="it7KGMb" width="1.192" height="6.826" x="15.579" y="23.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="iCzjNCe" width="1.192" height="6.826" x="11.573" y="23.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="iOPLs3J" width="1.192" height="6.826" x="19.566" y="23.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="ioYPlQd" width="2.097" height=".3" x="23.963" y="25.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".05"/></filter><filter id="i3JZFwe" width="2.097" height=".3" x="23.885" y="27.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".05"/></filter><filter id="ibCPzEe" width="2.097" height=".3" x="23.963" y="28.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".05"/></filter><filter id="i5vjwKr" width="11.22" height="12.442" x="11.112" y="4.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1734" result="effect2_innerShadow_4002_1734"/></filter><filter id="ikaQywb" width="3.747" height="4.9" x="14.16" y="8.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".5"/></filter><filter id="iqPygxc" width="2.277" height="3.3" x="15.036" y="9.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".1"/></filter><filter id="iLL6Zee" width="3.718" height="1.573" x="14.316" y="13.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".05"/></filter><filter id="iQJvzAd" width="12.873" height="8.356" x="9.739" y="1.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1734" result="effect2_innerShadow_4002_1734"/></filter><filter id="iXADOKb" width="2.339" height="1.19" x="17.764" y="7.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/></filter><filter id="i1SPdHb" width="2.339" height="1.176" x="12.508" y="7.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/></filter><filter id="ifBHIAb" width="6.584" height="5.992" x="10.094" y="2.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/><feGaussianBlur result="effect2_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="iwYYTyc" width="7.112" height="5.986" x="16.016" y="2.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1734"/><feGaussianBlur result="effect2_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="imCSnQc" width=".787" height=".696" x="17.623" y="9.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".05"/></filter><filter id="iSqJ49w" width=".891" height=".913" x="18.463" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".1"/></filter><filter id="iKfmn8c" width=".986" height="1.04" x="14.02" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".1"/></filter><filter id="i1wdlrd" width=".913" height=".705" x="13.265" y="9.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".05"/></filter><filter id="i3aEMib" width="1.329" height="2.379" x="10.094" y="9.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="iET11He" width="1.806" height="2.758" x="20.725" y="9.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".25"/></filter><filter id="ijrl5Qg" width="2.405" height="1.16" x="12.427" y="7.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="iY937re" width="2.405" height="1.16" x="17.743" y="7.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".125"/></filter><filter id="iDh04fe" width="5.367" height="3.046" x="17.191" y="3.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1734" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:judge-medium" /></template>
<style>
.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.b-744zb0c {
  stop-color: var(--svg-color--4a4251, #4A4251);
}

.b12rqybcc {
  d: path("M21.036 12.066a1.64 1.64 0 0 0 .905-.309v.931c0 .893-.532 1.689-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bgvn65brt {
  d: path("M11.314 12.066a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.btcphcbyj {
  d: path("M21.03 4.173c.514.177.976.536 1.268 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.271.875v1.188a1.7 1.7 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.35 2.35 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.891-.912a1.5 1.5 0 0 0 1.193 0c.281-.118.59-.187.913-.187c.843 0 1.58.455 1.988 1.131c.308.51.79.88 1.353 1.073");
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c95hs9n7z {
  d: path("M28.694 16.987h-.614a.505.505 0 0 0-.503.503v3.022c0 .272.221.504.503.504h.614a.505.505 0 0 0 .503-.504V17.49a.51.51 0 0 0-.503-.503");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.covdgtuis {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.824 13.317a.23.23 0 0 0-.271.047a.21.21 0 0 0-.024.27c.349.529.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.csyw8e_zo {
  d: path("M19.816 23.575h.692v6.326h-.692z");
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dcw3_lbai {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.294 9.611c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.dg7d8bcvt {
  fill: var(--svg-color--000, #000);
  d: path("M17.848 10.315c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dxre8vbsy {
  d: path("m17.092 19.793l-.655.584a.416.416 0 0 1-.554 0l-.654-.584a3.47 3.47 0 0 1-1.149-2.569v-3.112a2.085 2.085 0 0 1 2.086-2.065c1.148 0 2.075.926 2.075 2.075v3.112a3.5 3.5 0 0 1-1.149 2.559");
}

.dys9kie4i {
  stop-color: var(--svg-color--533028, #533028);
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

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ecl0zjrag {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.802 8.007c.257-.185.897-.51 1.655-.382");
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.ekp-5bvbp {
  cx: 13.722px;
  cy: 9.804px;
  rx: 0.39px;
  ry: 0.197px;
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.frwkbz6el {
  stop-color: var(--svg-color--83505f, #83505F);
}

.ft5dv1b6b {
  fill: none;
}

.fw60b3gol {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.784 9.15c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.g__d7mboh {
  d: path("M23.593 25.357c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.g0_-i5b1o {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.773 7.951c-.257-.184-.897-.508-1.655-.38");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gbhjhfb2j {
  d: path("M11.09 9.617a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i51qb4bvo {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.388 8.467l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.i7r8nrzil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.035 27.328h1.797");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.izs2z8pto {
  d: path("M11.35 13.58a3.916 3.916 0 0 0 3.886 3.407h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j57pz9gky {
  d: path("M16.175 13.712c-.508 0-.985-.119-1.385-.328c-.137-.07-.285.085-.198.209c.335.508.918.846 1.583.846s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.328");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jbe938blf {
  d: path("M16.165 15.572c-6.114 0-11.08 4.906-11.08 10.97v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.064-4.955-10.97-11.07-10.97");
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jz3pzrmrk {
  stop-color: var(--svg-color--3e3646, #3E3646);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k77tk4b5f {
  d: path("M15.829 23.575h.692v6.326h-.692z");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kive_m_gh {
  d: path("M8.933 30.031v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lt7qe9bnc {
  d: path("m16.407 5.2l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m--70bckn {
  d: path("M18.294 9.611c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
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

.mfj8x92sx {
  d: path("M24.869 21.102v6.427h1.51v-6.427z");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n626tzb0r {
  stop-color: var(--svg-color--533028, #533028);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.na9bapb1u {
  d: path("M23.168 16.987h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504V17.49a.51.51 0 0 0-.504-.503");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.ni9ok2yqm {
  d: path("M11.823 23.575h.692v6.326h-.692z");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nx9s0ob9q {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.407 5.2l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.o-r-orbbu {
  stop-color: var(--svg-color--1c1124, #1C1124);
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.or38gufwt {
  d: path("M9.236 17.9c1.974-1.647 4.386-2.423 6.94-2.423c2.553 0 4.965.776 6.939 2.423a.24.24 0 0 1 .061.295c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.295");
}

.os3chxbhl {
  stop-color: var(--svg-color--937062, #937062);
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oy9slob8t {
  d: path("M21.225 11.43q.05-.88.095-1.759c.4.055.711.426.711.876c0 .484-.36.878-.806.882");
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p87wxxb3p {
  d: path("M26.949 22.964c.531 0 .959.428.959.959v2.188H26v-2.188a.94.94 0 0 1 .948-.959");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
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

.q-n3w0bgw {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.574 5.203h-2.137a.496.496 0 1 1 .079-.987c.554.088 1.29.211 1.784.334c1.114.276 1.422.819 1.508 1.206a1.55 1.55 0 0 0-1.234-.553");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q436rjb1t {
  d: path("m16.956 19.914l.136-.121a3.5 3.5 0 0 0 1.148-2.549V15.28h-4.15l-.005 1.912c0 .051.003.146 0 .2a3.47 3.47 0 0 0 1.144 2.4l.16.144l.666-1.01a.13.13 0 0 1 .22 0z");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qesbwhu6x {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.793 10.101l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qr_6k0brn {
  d: path("M11.13 8.952a1.62 1.62 0 0 0-1.39 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwsiv7prr {
  cx: 13.722px;
  cy: 9.804px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rm9gqqi4t {
  d: path("M18.36 9.423a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s-0q55xsm {
  d: path("M21.097 12.157q.101-1.596.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.s1hge_b0w {
  d: path("M19.154 10.198a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
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

.sy7sk-bit {
  width: 2.773px;
  height: 1.082px;
  x: 24.247px;
  y: 21.016px;
  rx: 0.541px;
}

.t0guptbkt {
  fill: var(--svg-color--000, #000);
  d: path("M14.502 10.315a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.u_cllgbfr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 28.633h1.797");
}

.u-gok8e3r {
  d: path("M23.388 30.031v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u4yr2t84f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.566 9.15c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.127");
}

.ua37rzaqz {
  d: path("m21.388 8.467l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
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

.v41pyom1m {
  d: path("M27.073 16.987h-2.901a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h2.9a.505.505 0 0 0 .505-.504V17.49a.51.51 0 0 0-.504-.503");
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vn0i-3-9o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 26.024h1.797");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wd7ykhbml {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.908 7.836a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.wdm99-b0x {
  d: path("M16.165 18.765a2.07 2.07 0 0 1-2.075-2.075v-2.578a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.926 2.075 2.075V16.7a2.083 2.083 0 0 1-2.075 2.065");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wycd9cbrf {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.774 10.297l-.591 1.838c-.101.378.141.757.484.757h.732c.343 0 .585-.384.484-.757l-.494-1.838c-.106-.407-.504-.407-.615 0");
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xdh23sgqk {
  d: path("M13.991 9.422a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xm9q3m5hd {
  d: path("m15.793 10.101l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yos9ueveo {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.764 7.727a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.067.551a2.22 2.22 0 0 0-1.387.285q-.052.03-.075.048l-.017.012l-.003.002a.277.277 0 0 1-.34-.439z");
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.z86scdcth {
  d: path("M14.806 10.21c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
