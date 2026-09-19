<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itJ9RWd)" class="vs7i14bwp"/><path fill="url(#iYkRQPd)" class="rgv3pnaae"/><path class="jklnyabdf"/><path fill="url(#ilNxD9d)" class="kx30krbxo"/><path fill="url(#iJyjz6W)" class="ze2krdbds"/><path fill="url(#iLhTtHb)" class="ze2krdbds"/><path fill="url(#izMn9Be)" class="d1nilib6v"/><path fill="url(#izg4ujd)" class="d1nilib6v"/><path fill="url(#iadzyib)" class="d1nilib6v"/><g filter="url(#imAE2le)"><path fill="url(#ilIiLdb)" class="wixo2vhvi"/><path fill="url(#ibmah7c)" class="wixo2vhvi"/></g><path fill="url(#iu2CgnC)" class="wixo2vhvi"/><path fill="url(#iKwowTT)" class="wixo2vhvi"/><g filter="url(#iHyeqSc)"><path fill="url(#iB3cuXc)" class="yrk4jtuzm"/></g><path fill="url(#iybTVVb)" class="fq6-97b5m"/><path fill="url(#iWhpX3Q)" class="fq6-97b5m"/><g filter="url(#iefLDid)"><path class="v-_09sj7i"/></g><g filter="url(#ienkdPd)"><path class="c1lnl-bba"/></g><g filter="url(#is3fiMc)"><path class="ngx9a8tav"/></g><g filter="url(#iXhctyb)"><path fill="url(#iylJlyq)" class="z9gqgc34p"/></g><g filter="url(#iokfXvV)"><path fill="url(#i9YFNsd)" class="z3ftesbhm"/></g><g filter="url(#ijfvEOc)"><path fill="url(#iDFVa0d)" class="vhnkeebzf"/></g><path fill="url(#iN8VP0b)" class="uzx7kb0jh"/><path fill="url(#iCawxvb)" class="uzx7kb0jh"/><path fill="url(#iC0Ru6c)" class="hx-kju0_z"/><path fill="url(#iymKRfd)" class="oc1urvbvv"/><g filter="url(#iRLRNFd)"><path fill="url(#iAsnnre)" class="stgrfub0r"/><path fill="url(#iFBFABe)" class="stgrfub0r"/></g><path fill="url(#ircd4Me)" class="stgrfub0r"/><path fill="url(#ie0RlUK)" class="stgrfub0r"/><path fill="url(#iv6QMdd)" class="stgrfub0r"/><path fill="url(#iljUWph)" class="stgrfub0r"/><path fill="url(#iTd204c)" class="stgrfub0r"/><path fill="url(#iW8qG7b)" class="stgrfub0r"/><path fill="url(#iLCHy1N)" class="stgrfub0r"/><path fill="url(#iR9GIre)" class="stgrfub0r"/><path fill="url(#i8xAi3d)" class="stgrfub0r"/><g filter="url(#ikWr8dd)"><path class="m36ppvaty"/></g><g filter="url(#iOWebYj)"><path class="drn-1v8aa"/><path fill="url(#ipDq9bc)" class="ebwue-s6u"/><path fill="url(#ib0cp8d)" class="ebwue-s6u"/><path fill="url(#iZ42Mud)" class="ebwue-s6u"/><path fill="url(#i8M9CGc)" class="ebwue-s6u"/><path fill="url(#ii8gwvd)" class="ebwue-s6u"/></g><g filter="url(#i15tk6b)"><path stroke="url(#iuw9Nuc)" class="xvtfmpbqz"/></g><path fill="url(#iGH6WKd)" class="q-hhhxy_x"/><g filter="url(#i6xD8Qd)"><path class="n3z_d94xy"/></g><g filter="url(#iqRq07R)"><path class="l84jxbbtx"/></g><path class="rnw048_8t"/><path fill="url(#ilNcOyb)" class="lk41zp1da"/><path class="sbaza5b1y"/><g filter="url(#iS6oRLe)"><path class="a8osuacyr"/><path fill="url(#inrIhqc)" class="i7myy-bgx"/></g><g filter="url(#i0uFLAb)"><path fill="url(#iZXgXfp)" class="i0lle--vv"/></g><path class="eviszrbmr"/><path fill="url(#icw8N9c)" class="zfaxe6b8m"/><path class="unnb4-bbn"/><g filter="url(#iqzr8Od)"><path fill="url(#im7MOjW)" class="okug90hku"/></g><g filter="url(#iN2MuEc)"><ellipse transform="rotate(-27.914 13.193 9.885)" class="a71nw_fqf"/><ellipse fill="url(#iqUSgiE)" transform="rotate(-27.914 13.193 9.885)" class="g-tjae_8i"/></g><path fill="url(#iif9FYb)" class="t0jyp1y0r"/><path fill="url(#iNJSaee)" class="t0jyp1y0r"/><path fill="url(#iwWzn5c)" class="t0jyp1y0r"/><path fill="url(#ihCu64c)" class="t0jyp1y0r"/><path fill="url(#iDVgDxA)" class="rpc314bjd"/><path fill="url(#iC01Gsd)" class="rpc314bjd"/><g filter="url(#ipSBXGd)"><path fill="url(#iImsJ5b)" class="kv_8libph"/></g><g filter="url(#iNNWi4b)"><path fill="url(#iOw2omz)" class="pszaw0b_k"/></g><g filter="url(#imN007c)"><path class="w4iz7ybcp"/></g><g filter="url(#imm1C3d)"><path class="gtp-tibpy"/></g><g filter="url(#ikSooAc)"><path fill="url(#iFc7nxb)" class="ze51fklbe"/><path fill="url(#iPgMwDc)" class="ze51fklbe"/></g><path fill="url(#iKoypMc)" class="q22au23-l"/><path fill="url(#iDSL7lb)" class="q22au23-l"/><g filter="url(#iiVUJob)"><path fill="url(#iQ2Sfxb)" clip-rule="evenodd" class="i9fz1kmqr"/></g><g filter="url(#iP4Q8re)"><path fill="url(#imlgqWb)" clip-rule="evenodd" class="k45b5tb5m"/></g><g filter="url(#iC5plJb)"><path fill="url(#i03oEVd)" class="x_-frjb5x"/></g><path fill="url(#iuMo1ac)" class="md5-y-73v"/><path fill="url(#imTOvDe)" class="md5-y-73v"/><path fill="url(#ieiv4fc)" class="md5-y-73v"/><path fill="url(#iYegtGb)" class="bnintsiuq"/><path fill="url(#iomqm8c)" class="bnintsiuq"/><path fill="url(#iS32H7d)" class="bnintsiuq"/><path fill="url(#ietW27m)" class="bnintsiuq"/><g filter="url(#iqp8xKb)"><path fill="url(#iOvfMSs)" class="uc2f6sq3u"/></g><g filter="url(#iijJHJN)"><path class="dvxn-dhsv"/><path fill="url(#iyDgeoc)" class="wir2rpblj"/></g><g filter="url(#iDM0Z4q)"><ellipse fill="url(#ieePuMd)" class="yv1mslsfh"/></g><g filter="url(#iCddL6d)"><path fill="url(#itE4wOd)" class="hq0dwd71w"/><path fill="url(#iuOlwVQ)" class="hq0dwd71w"/><path fill="url(#iqtmZFc)" class="hq0dwd71w"/><path fill="url(#iSqf0ab)" class="hq0dwd71w"/><path fill="url(#ihL5Ucc)" class="hq0dwd71w"/></g><g filter="url(#ix7vOJc)"><path stroke="url(#idGTO4b)" class="zzjo1ibos"/></g><g filter="url(#ifhxxPo)"><path stroke="url(#iFaIPre)" class="yxoc4gg5p"/></g><g filter="url(#i9N43Oc)"><path stroke="url(#iIZTlbc)" class="g0su58b4b"/></g><defs><radialGradient id="ilNxD9d" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.77 57.521)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="iLhTtHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.684 30.22)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="iadzyib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.125 30.724)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="ilIiLdb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.726 19.696)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="ibmah7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.39 32.468)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="iu2CgnC" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.512 16.036)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iybTVVb" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 8.993 10.116)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iWhpX3Q" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.601 8.626)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="fjyr3161v"/><stop offset="1" class="vuu318b4c"/></radialGradient><radialGradient id="iN8VP0b" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.32 16.167)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iCawxvb" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.386 23.556)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iC0Ru6c" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.692 20.58)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="yc6yhhbng"/><stop offset="1" class="acsx37bmr"/></radialGradient><radialGradient id="iymKRfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.59 12.329)" gradientUnits="userSpaceOnUse"><stop class="a8hir8afg"/><stop offset=".746" class="o43_m0brr"/></radialGradient><radialGradient id="iAsnnre" cx="0" cy="0" r="1" gradientTransform="matrix(-4.74014 0 0 -8.32315 18.479 10.897)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iFBFABe" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.385 8.042)scale(3.37573 2.79652)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ie0RlUK" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.6809 -10.5786 0 16.217 4.73)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="aaa-k8z4r"/><stop offset=".987" class="tv4gqpb-i"/></radialGradient><radialGradient id="iv6QMdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.43169 0 18.115 9.585)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iljUWph" cx="0" cy="0" r="1" gradientTransform="matrix(.00395 -1.09427 1.19972 .00433 13.333 9.632)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iTd204c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.55937 .53641 -1.36019 -21.70422 19.108 11.885)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iW8qG7b" cx="0" cy="0" r="1" gradientTransform="matrix(3.41105 -2.91647 .8605 1.00643 8.808 8.164)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iLCHy1N" cx="0" cy="0" r="1" gradientTransform="matrix(-.23643 2.49743 -1.00564 -.0952 21.236 7.98)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iR9GIre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.68569 0 13.418 10.402)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i8xAi3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.40686 -7.05834 0 15.697 7.042)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="agyxz7tke"/><stop offset="1" class="obgykv3mo"/></radialGradient><radialGradient id="ib0cp8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.113 12.258)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="i8M9CGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.23 11.688)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iGH6WKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.156 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ilNcOyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.829 9.981)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="inrIhqc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.265 .723)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icw8N9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.465 9.981)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iqUSgiE" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.179 10.2)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNJSaee" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.264 9.995)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iwWzn5c" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.625 10.54)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="ihCu64c" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.739 10.712)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iC01Gsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.84893 10.731 10.639)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iImsJ5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 10.78 10.64)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iFc7nxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.531 6.068)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iPgMwDc" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.344 2.911)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iKoypMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 18.781 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><radialGradient id="iuMo1ac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.86 19.302)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="imTOvDe" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.219 18.177)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="ieiv4fc" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.33 20.474)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iYegtGb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.196 18.593)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iS32H7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.75 18.895)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="ietW27m" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.687 21.302)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iyDgeoc" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.695 11.25)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="ieePuMd" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.15 20.07)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="iuOlwVQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.74 25.293)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iqtmZFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.74 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iSqf0ab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.74 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ihL5Ucc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.74 29.189)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><filter id="imAE2le" width="14.3" height="12.3" x="8.372" y="18.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/></filter><filter id="iHyeqSc" width="6.538" height="5.771" x="12.014" y="16.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".325"/></filter><filter id="iefLDid" width="2.5" height="2.5" x="18.462" y="27.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".25"/></filter><filter id="ienkdPd" width="2.5" height="2.5" x="18.462" y="23.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".25"/></filter><filter id="is3fiMc" width="2.5" height="2.5" x="18.462" y="19.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".25"/></filter><filter id="iXhctyb" width="1.7" height="1.7" x="19.132" y="27.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1880" result="effect2_innerShadow_4002_1880"/></filter><filter id="iokfXvV" width="1.7" height="1.7" x="19.132" y="23.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1880" result="effect2_innerShadow_4002_1880"/></filter><filter id="ijfvEOc" width="1.7" height="1.7" x="19.132" y="20.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1880" result="effect2_innerShadow_4002_1880"/></filter><filter id="iRLRNFd" width="11.297" height="12.442" x="10.549" y="4.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1880" result="effect2_innerShadow_4002_1880"/></filter><filter id="ikWr8dd" width="3.877" height="4.9" x="13.501" y="9.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".5"/></filter><filter id="iOWebYj" width="2.277" height="3.3" x="14.508" y="9.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".1"/></filter><filter id="i15tk6b" width="3.618" height="1.473" x="13.838" y="13.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="i6xD8Qd" width="2.339" height="1.19" x="17.236" y="7.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/></filter><filter id="iqRq07R" width="2.339" height="1.176" x="11.979" y="7.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/></filter><filter id="iS6oRLe" width=".787" height=".696" x="17.095" y="9.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="i0uFLAb" width=".891" height=".913" x="17.934" y="9.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".1"/></filter><filter id="iqzr8Od" width=".986" height="1.04" x="13.492" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".1"/></filter><filter id="iN2MuEc" width=".913" height=".705" x="12.737" y="9.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="ipSBXGd" width="1.329" height="2.379" x="9.614" y="9.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".125"/></filter><filter id="iNNWi4b" width="1.947" height="2.903" x="20.108" y="9.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".25"/></filter><filter id="imN007c" width="2.305" height="1.06" x="11.948" y="7.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".125"/></filter><filter id="imm1C3d" width="2.305" height="1.069" x="17.228" y="7.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".125"/></filter><filter id="ikSooAc" width="14.779" height="5.543" x="8.307" y="2.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/></filter><filter id="iiVUJob" width=".675" height="2.047" x="12.554" y="3.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="iP4Q8re" width=".675" height="2.047" x="18.142" y="3.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="iC5plJb" width=".98" height="2.537" x="15.211" y="3.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".1"/></filter><filter id="iqp8xKb" width="2.238" height="1.809" x="14.522" y="17.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1880" result="effect2_innerShadow_4002_1880"/></filter><filter id="iijJHJN" width="5.047" height="11.336" x="23.075" y="14.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/></filter><filter id="iDM0Z4q" width="3.672" height="4.703" x="23.537" y="15.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/><feGaussianBlur result="effect2_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="iCddL6d" width="4.468" height="5.556" x="23.304" y="24.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1880"/></filter><filter id="ix7vOJc" width="2.097" height=".3" x="23.674" y="25.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="ifhxxPo" width="2.097" height=".3" x="23.596" y="27.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><filter id="i9N43Oc" width="2.097" height=".3" x="23.674" y="28.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1880" stdDeviation=".05"/></filter><linearGradient id="itJ9RWd" x1="10.476" x2="10.476" y1="7.88" y2="9.973" gradientUnits="userSpaceOnUse"><stop class="lfase3b3t"/><stop offset="1" class="r3tk9bbjl"/></linearGradient><linearGradient id="iYkRQPd" x1="20.818" x2="20.818" y1="7.708" y2="9.271" gradientUnits="userSpaceOnUse"><stop class="wvczyl5hy"/><stop offset="1" class="v0x9vt1yz"/></linearGradient><linearGradient id="iJyjz6W" x1="22.829" x2="26.073" y1="25.886" y2="25.886" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="izMn9Be" x1="7.812" x2="7.812" y1="31.005" y2="16.943" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="izg4ujd" x1="8.672" x2="8.094" y1="26.63" y2="26.63" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iKwowTT" x1="8.672" x2="12.608" y1="27.217" y2="27.217" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="iB3cuXc" x1="16.28" x2="13.319" y1="22.136" y2="18.752" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iylJlyq" x1="20.5" x2="19.232" y1="27.65" y2="29.056" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i9YFNsd" x1="20.5" x2="19.232" y1="24.01" y2="25.416" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iDFVa0d" x1="20.5" x2="19.232" y1="20.38" y2="21.786" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="ircd4Me" x1="20.846" x2="18.298" y1="12.583" y2="12.583" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ipDq9bc" x1="16.485" x2="15.647" y1="11.572" y2="11.607" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iZ42Mud" x1="15.647" x2="15.647" y1="12.711" y2="12.246" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ii8gwvd" x1="15.647" x2="15.647" y1="10.006" y2="10.553" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iuw9Nuc" x1="14.445" x2="14.763" y1="14.282" y2="13.448" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iZXgXfp" x1="18.607" x2="18.293" y1="10.035" y2="10.228" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im7MOjW" x1="14.209" x2="13.895" y1="10.035" y2="10.228" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iif9FYb" x1="22.083" x2="20.876" y1="10.062" y2="12.238" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iDVgDxA" x1="9.797" x2="11.255" y1="10.768" y2="10.64" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iOw2omz" x1="21.082" x2="21.082" y1="9.684" y2="11.587" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iDSL7lb" x1="16.281" x2="16.281" y1="7.786" y2="7.099" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="iQ2Sfxb" x1="13.027" x2="12.449" y1="5.639" y2="5.541" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="imlgqWb" x1="18.289" x2="18.922" y1="5.447" y2="5.541" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="i03oEVd" x1="15.991" x2="15.991" y1="5.783" y2="3.756" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient><linearGradient id="iomqm8c" x1="16.375" x2="17.359" y1="18.005" y2="19.177" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iOvfMSs" x1="15.891" x2="15.891" y1="18.896" y2="17.457" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="itE4wOd" x1="27.332" x2="23.304" y1="28.051" y2="28.051" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="idGTO4b" x1="23.824" x2="25.533" y1="26.044" y2="26.044" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iFaIPre" x1="23.746" x2="25.455" y1="27.349" y2="27.349" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iIZTlbc" x1="23.824" x2="25.533" y1="28.654" y2="28.654" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cook-medium" /></template>
<style>
.a71nw_fqf {
  cx: 13.193px;
  cy: 9.885px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.a8hir8afg {
  stop-color: var(--svg-color--4c3a38, #4C3A38);
}

.a8osuacyr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.765 9.693c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.326-.135.39-.05");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aaa-k8z4r {
  stop-color: var(--svg-color--9a6470, #9A6470);
  stop-opacity: 0;
}

.acsx37bmr {
  stop-color: var(--svg-color--33212e, #33212E);
}

.agyxz7tke {
  stop-color: var(--svg-color--83505e, #83505E);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.bnintsiuq {
  d: path("M17.855 18.702c-.67-.924-1.704-1.194-2.097-1.245c-.205.83-.308 2.667.684 3.563c.635.574 1.077.722 1.67.787c.163.018.269-.165.221-.322q-.047-.149-.053-.365c-.009-.634.11-1.681-.425-2.418");
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c1lnl-bba {
  fill: var(--svg-color--b2a7be, #B2A7BE);
  d: path("M19.712 25.403a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.d1nilib6v {
  d: path("M8.672 17.991a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.da7b97bvf {
  stop-color: var(--svg-color--b59ccc, #B59CCC);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.drn-1v8aa {
  fill: var(--svg-color--946964, #946964);
  d: path("m15.264 10.183l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.766 0");
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.dvxn-dhsv {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.051 21.192c0-.406.26-.758.568-1.021c.605-.517 1.003-1.392 1.003-2.385c0-1.587-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.288-2.273 2.875c0 .993.398 1.868 1.002 2.384c.309.264.568.616.568 1.021v5.056h1.406z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ebwue-s6u {
  d: path("m15.264 10.183l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.766 0");
}

.eviszrbmr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.256 9.232c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fjyr3161v {
  stop-color: var(--svg-color--730620, #730620);
}

.fq6-97b5m {
  d: path("M23.081 18.373H8.232a10.94 10.94 0 0 1 7.42-2.885c3.484 0 5.153.812 7.43 2.885");
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-tjae_8i {
  cx: 13.193px;
  cy: 9.885px;
  rx: 0.39px;
  ry: 0.197px;
}

.g0su58b4b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 28.575h1.797");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gtp-tibpy {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.208 8.307c-.282-.297-.898-.509-1.655-.382");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hq0dwd71w {
  d: path("M23.304 25.314c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.03a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.hx-kju0_z {
  d: path("M20.508 12.147c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i0lle--vv {
  d: path("M18.626 10.28a.84.84 0 0 0-.232-.464l-.26.286l.118.228z");
}

.i7myy-bgx {
  d: path("M17.765 9.693c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.326-.135.39-.05");
}

.i9fz1kmqr {
  fill-rule: evenodd;
  d: path("m13.129 5.893l-.475-1.847v1.847z");
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jklnyabdf {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.652 15.488c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k45b5tb5m {
  fill-rule: evenodd;
  d: path("m18.242 5.893l.475-1.847v1.847z");
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kv_8libph {
  d: path("M10.61 9.7a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.kx30krbxo {
  d: path("M15.652 15.488c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l84jxbbtx {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.236 8.066a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.lfase3b3t {
  stop-color: var(--svg-color--583e3c, #583E3C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk41zp1da {
  d: path("M17.83 9.504a.893.893 0 0 1 .86 1.128h-1.723a.896.896 0 0 1 .864-1.128");
}

.m36ppvaty {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.16 10.378l-.634 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.542-.407-.661 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.md5-y-73v {
  d: path("M13.46 18.702c.67-.924 1.703-1.194 2.096-1.245c.205.83.308 2.667-.684 3.563c-.635.574-1.078.722-1.67.787c-.163.018-.27-.165-.222-.322c.03-.1.051-.22.053-.365c.01-.634-.108-1.681.426-2.418");
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n3z_d94xy {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.38 8.182a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.ngx9a8tav {
  fill: var(--svg-color--b29aac, #B29AAC);
  d: path("M19.712 21.773a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o43_m0brr {
  stop-color: var(--svg-color--302028, #302028);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.obgykv3mo {
  stop-color: var(--svg-color--83505e, #83505E);
  stop-opacity: 0;
}

.oc1urvbvv {
  d: path("M10.785 12.147a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.okug90hku {
  d: path("M14.278 10.292c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pszaw0b_k {
  d: path("M20.609 11.587q.057-.951.11-1.903a.955.955 0 0 1-.11 1.903");
}

.q-hhhxy_x {
  d: path("M15.647 13.794c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.584.845c.664 0 1.248-.338 1.583-.845c.086-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.q22au23-l {
  d: path("M21.727 5.943H9.675q.026.046.027.101v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.04a.2.2 0 0 1 .025-.098");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r3tk9bbjl {
  stop-color: var(--svg-color--422c2c, #422C2C);
}

.r64vbvf7r {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r7svlnonw {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
  stop-opacity: 0;
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rgv3pnaae {
  d: path("M20.338 7.364h.96v2.608h-.96z");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rnw048_8t {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.038 9.232c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.rpc314bjd {
  d: path("M10.593 9.039a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.sbaza5b1y {
  fill: var(--svg-color--000, #000);
  d: path("M17.32 10.397c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.stgrfub0r {
  d: path("M10.822 13.662a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.278-4.387.366-6.27c-.011-.767-.657-.772-1.421-.804h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.376.798-3.376 2.665c0 1.86.15 4.405.273 6.27");
}

.t0jyp1y0r {
  d: path("M20.569 12.238c.065-1.064.129-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.tv4gqpb-i {
  stop-color: var(--svg-color--85414e, #85414E);
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.uc2f6sq3u {
  d: path("M14.984 17.576c.19-.063.44-.12.707-.12s.517.057.707.12a.39.39 0 0 1 .255.45c-.093.487-.27.8-.464.99a.5.5 0 0 1-.267.13a1.5 1.5 0 0 1-.477 0a.43.43 0 0 1-.252-.13c-.194-.19-.371-.503-.463-.99a.39.39 0 0 1 .254-.45");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.unnb4-bbn {
  fill: var(--svg-color--000, #000);
  d: path("M13.974 10.397a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.uzx7kb0jh {
  d: path("M26.655 23.075a.97.97 0 0 1 .967.967v2.215h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.v-_09sj7i {
  fill: var(--svg-color--b5a5c4, #B5A5C4);
  d: path("M20.462 28.293a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v0x9vt1yz {
  stop-color: var(--svg-color--573a38, #573A38);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.vhnkeebzf {
  d: path("M19.982 21.628a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.vs7i14bwp {
  d: path("M9.996 7.364h.96v2.608h-.96z");
}

.vuu318b4c {
  stop-color: var(--svg-color--730620, #730620);
  stop-opacity: 0;
}

.w4iz7ybcp {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.273 8.346c.257-.185.898-.51 1.656-.382");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wir2rpblj {
  d: path("M26.051 21.192c0-.406.26-.758.568-1.021c.605-.517 1.003-1.392 1.003-2.385c0-1.587-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.288-2.273 2.875c0 .993.398 1.868 1.002 2.384c.309.264.568.616.568 1.021v5.056h1.406z");
}

.wixo2vhvi {
  d: path("M8.672 18.018h10.052c2.177 0 3.948 1.796 3.948 4.004v7.996h-14z");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wvczyl5hy {
  stop-color: var(--svg-color--6b4a49, #6B4A49);
}

.x_-frjb5x {
  d: path("M15.411 3.756h.58v2.137h-.58z");
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xvtfmpbqz {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.284 13.421a2.96 2.96 0 0 0 1.363.323a2.94 2.94 0 0 0 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.987-.28l2.946.252m-2.946-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.208.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.868a1.95 1.95 0 0 1-1.625-.867m3.208-.028a1.9 1.9 0 0 1-1.583.845a1.9 1.9 0 0 1-1.584-.845m-.041.027v.001l.041-.028m-.041.027l.041-.027");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yc6yhhbng {
  stop-color: var(--svg-color--52403f, #52403F);
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrk4jtuzm {
  d: path("M15.385 17.514c-.385.032-1.404.252-2.102 1.143c-.47.598-.498 1.44-.52 2.068q-.005.177-.014.326c-.01.145-.035.263-.07.363c-.054.154.04.341.2.331c.58-.036 1.018-.162 1.664-.705c.493-.413.743-1.062.851-1.716c.044.661.228 1.332.677 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.232-.31a1.3 1.3 0 0 1-.034-.368q.005-.151.018-.326c.04-.628.095-1.468-.313-2.11c-.607-.955-1.6-1.274-1.979-1.344c-.047.16-.092.359-.128.582a5 5 0 0 0-.07-.592");
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.yv1mslsfh {
  cx: 25.348px;
  cy: 17.732px;
  rx: 1.711px;
  ry: 2.227px;
}

.yxoc4gg5p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.746 27.27h1.797");
}

.z3ftesbhm {
  d: path("M19.982 25.258a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.z9gqgc34p {
  d: path("M20.732 28.148a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.ze2krdbds {
  d: path("M22.672 30.018h4v-3.501c0-3.422-1.554-6.482-4-8.499z");
}

.ze51fklbe {
  d: path("M10.241 2.103a1.933 1.933 0 0 0-.681 3.744a.215.215 0 0 1 .142.197v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.04c0-.089.058-.166.141-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.zfaxe6b8m {
  d: path("M13.463 9.504a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

.zzjo1ibos {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 25.966h1.797");
}

</style>
