<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i19O0ud)" class="clwbcd6-k"/><path fill="url(#i9HtKic)" class="iyetsnbcc"/><path class="d_-4zr8fj"/><path fill="url(#icJHVtj)" class="ni42iccyp"/><path fill="url(#ixcn1cb)" class="r73emubqg"/><path fill="url(#ifadCTb)" class="r73emubqg"/><path fill="url(#iniseFs)" class="gd11xjopk"/><path fill="url(#iFBlABb)" class="gd11xjopk"/><path fill="url(#iPMtyod)" class="gd11xjopk"/><path fill="url(#id9iyue)" class="gd11xjopk"/><g filter="url(#ifsU8Tc)"><path fill="url(#ii4k26d)" class="c3weeebxy"/><path fill="url(#isXMRlc)" class="c3weeebxy"/></g><path fill="url(#iY5RiDc)" class="c3weeebxy"/><path fill="url(#iYRfEzj)" class="c3weeebxy"/><g filter="url(#iqs2nMb)"><path fill="url(#i54Diib)" class="dlz8fwbma"/></g><path fill="url(#iZO70ib)" class="dwp-1frtz"/><path fill="url(#iuF7Ptd)" class="dwp-1frtz"/><g filter="url(#idLS0ee)"><path class="xdemcobmc"/></g><g filter="url(#iIaoKnN)"><path class="fs84khn_h"/></g><g filter="url(#ihOEYub)"><path class="n8px-g5sz"/></g><g filter="url(#itYVMCe)"><path fill="url(#idIDP1R)" class="gf0ecxend"/></g><g filter="url(#idgJAzc)"><path fill="url(#i4XMXcd)" class="xfryo5b2y"/></g><g filter="url(#itH15Rb)"><path fill="url(#ixNv87c)" class="ovn99jb4z"/></g><path fill="url(#iUDC1ab)" class="r1ve_2b_j"/><path fill="url(#iumliMc)" class="r1ve_2b_j"/><path fill="url(#ityvIPq)" class="qnufep55k"/><path fill="url(#iVHdzdA)" class="ocshmqb7l"/><g filter="url(#i0uqgcd)"><path fill="url(#iiM63PV)" class="eqjk3s4mq"/></g><path fill="url(#iAfzpdc)" class="eqjk3s4mq"/><path fill="url(#imOzd4b)" class="eqjk3s4mq"/><path fill="url(#izHluDc)" class="eqjk3s4mq"/><path fill="url(#ieye1Lc)" class="eqjk3s4mq"/><path fill="url(#iyaIurY)" class="eqjk3s4mq"/><path fill="url(#inGHlBx)" class="eqjk3s4mq"/><path fill="url(#i5aqlqp)" class="eqjk3s4mq"/><path fill="url(#iPM5Skc)" class="eqjk3s4mq"/><path fill="url(#i0Ia2Qb)" class="eqjk3s4mq"/><g filter="url(#inLoJ1d)"><path class="mrieobbjs"/></g><g filter="url(#iTLtJUb)"><path fill="url(#ivTdfOc)" class="ltyemwqpv"/><path fill="url(#itNQ2me)" class="ltyemwqpv"/><path fill="url(#iwZdw6l)" class="ltyemwqpv"/><path fill="url(#idi5ilc)" class="ltyemwqpv"/></g><g filter="url(#ivFaQwd)"><path stroke="url(#ip2B3Bc)" class="aatnh2b7u"/></g><path fill="url(#iOyf1re)" class="n26mtac8k"/><g filter="url(#iwEZdQe)"><path class="w4ffscnyz"/></g><g filter="url(#iqXIa2b)"><path class="ec8xe10jz"/></g><path class="nblo607_t"/><path fill="url(#iK1dAJb)" class="xobxtdqdz"/><path class="hy5x434iq"/><g filter="url(#iDwcMBe)"><path class="o-79f8n4o"/><path fill="url(#i8MqYFb)" class="zpc74dlcp"/></g><g filter="url(#iQ2hyEh)"><path fill="url(#ioGrONL)" class="thtl7hbqy"/></g><path class="so0134bfv"/><path fill="url(#iOh54rb)" class="er2-0gj_l"/><path class="u-19d9bdt"/><g filter="url(#ibaVsZb)"><path fill="url(#iK8G4cb)" class="a_yooeola"/></g><g filter="url(#iM00VGP)"><ellipse transform="rotate(-27.914 13.193 9.873)" class="dnt6qhbmo"/><ellipse fill="url(#iOW0Lzh)" transform="rotate(-27.914 13.193 9.873)" class="t8o9b3fch"/></g><path fill="url(#i4mODYB)" class="q4v93xbif"/><path fill="url(#iCphltc)" class="q4v93xbif"/><path fill="url(#iWGcR8c)" class="q4v93xbif"/><path fill="url(#ieT1ajd)" class="cgnu7mxef"/><path fill="url(#i2QWKec)" class="cgnu7mxef"/><g filter="url(#igr0D2c)"><path class="b5tqnes0a"/></g><g filter="url(#iqppkcc)"><path class="twgdwy8sb"/></g><g filter="url(#i8vjSAd)"><path class="oracvnb6j"/></g><g filter="url(#iVS3tKe)"><path class="pm23dyb1u"/></g><g filter="url(#ikO8q4b)"><path fill="url(#iHhanOd)" class="il79l0ryo"/><path fill="url(#itlGdsj)" class="il79l0ryo"/><path fill="url(#icBn4Be)" class="il79l0ryo"/></g><path fill="url(#iT3jDKd)" class="kvpd_pghm"/><path fill="url(#iA0rGzd)" class="kvpd_pghm"/><g filter="url(#iE29YeM)"><path fill="url(#ifn5WEd)" clip-rule="evenodd" class="t4c7gdbng"/></g><g filter="url(#ipH0d4d)"><path fill="url(#iAMQGkc)" clip-rule="evenodd" class="fij3-cbvh"/></g><g filter="url(#iZPIOBd)"><path fill="url(#iebELdi)" class="n9euf4but"/></g><path fill="url(#iLFqHQb)" class="z0saicbwe"/><path fill="url(#ir6a2cg)" class="z0saicbwe"/><path fill="url(#iHAbCbc)" class="z0saicbwe"/><path fill="url(#iGddC9A)" class="z8vyvsujj"/><path fill="url(#i9dGtBd)" class="z8vyvsujj"/><path fill="url(#iuH4NEW)" class="z8vyvsujj"/><path fill="url(#iXfEFwc)" class="z8vyvsujj"/><g filter="url(#ig7iVAe)"><path fill="url(#ilEM8Tb)" class="bq6f2zbqj"/></g><g filter="url(#iudqHBb)"><path class="umjjh0bmj"/><path fill="url(#igwg9RO)" class="tm5k9n0yq"/></g><g filter="url(#i36GRuh)"><ellipse fill="url(#iOU8Mny)" class="v35e4abfb"/></g><g filter="url(#iUApjNR)"><path fill="url(#i3ehsGd)" class="oj5bkmbam"/><path fill="url(#iN9AjYZ)" class="oj5bkmbam"/><path fill="url(#ihn1AOe)" class="oj5bkmbam"/><path fill="url(#iYINv1d)" class="oj5bkmbam"/><path fill="url(#ilULTWc)" class="oj5bkmbam"/></g><g filter="url(#iLn4c2G)"><path stroke="url(#i4aB3Ec)" class="x2ty5u7bf"/></g><g filter="url(#iG0IhDb)"><path stroke="url(#iybtq3d)" class="hfpav8v_t"/></g><g filter="url(#i8jvD6d)"><path stroke="url(#iLSvS1S)" class="qzsw2yonp"/></g><defs><radialGradient id="icJHVtj" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.738 57.515)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="ifadCTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.684 30.208)" gradientUnits="userSpaceOnUse"><stop class="br4vp4byh"/><stop offset="1" class="fs29nabkl"/></radialGradient><radialGradient id="iPMtyod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.125 30.711)" gradientUnits="userSpaceOnUse"><stop class="gt-1-ac7u"/><stop offset="1" class="yrzv-0byt"/></radialGradient><radialGradient id="id9iyue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.94559 0 0 -18.6532 9.212 29.422)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="blny5fbqc"/><stop offset="1" class="ql78zhb7e"/></radialGradient><radialGradient id="ii4k26d" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.726 19.683)" gradientUnits="userSpaceOnUse"><stop class="b3mtuebqr"/><stop offset="1" class="txq537bby"/></radialGradient><radialGradient id="isXMRlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.39 32.456)" gradientUnits="userSpaceOnUse"><stop class="ygyrfpbde"/><stop offset="1" class="r7svlnonw"/></radialGradient><radialGradient id="iY5RiDc" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.503 16.03)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iZO70ib" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 8.994 10.11)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iuF7Ptd" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.602 8.62)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="fjyr3161v"/><stop offset="1" class="vuu318b4c"/></radialGradient><radialGradient id="iUDC1ab" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.322 16.16)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iumliMc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.386 23.543)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="ityvIPq" cx="0" cy="0" r="1" gradientTransform="rotate(75.254 2.53 19.145)scale(2.8752 3.41552)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="isy8u3b-w"/><stop offset="1" class="ulo0skb3n"/></radialGradient><radialGradient id="iVHdzdA" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.59 12.316)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="ejuirjdrv"/><stop offset="1" class="pnnonnt5s"/></radialGradient><radialGradient id="iiM63PV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26686 0 0 -9.24801 18.479 10.885)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="imOzd4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.9986 -10.8435 0 16.156 4.714)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="tnwv9mbkd"/><stop offset="1" class="ce0z6ljwu"/></radialGradient><radialGradient id="izHluDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3409 1.67175 0 18.115 9.764)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ieye1Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0585 -1.1034 1.20967 -.06414 13.395 9.628)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iyaIurY" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 0 0 6.13397 10.733 11.27)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="inGHlBx" cx="0" cy="0" r="1" gradientTransform="matrix(2.63428 -3.65397 .8296 .59809 9.753 7.884)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i5aqlqp" cx="0" cy="0" r="1" gradientTransform="rotate(-103.355 13.658 1.355)scale(10.5276 11.6738)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iPM5Skc" cx="0" cy="0" r="1" gradientTransform="matrix(2.06013 .72073 -.42986 1.22872 17.622 5.503)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i0Ia2Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08991 -12.7429 0 15.697 7.067)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="mkts3-b3r"/><stop offset="1" class="t4ctysbhn"/></radialGradient><radialGradient id="ip2B3Bc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.356 -5.304)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="c1d5sgupt"/><stop offset="1" class="zj9picbxt"/></radialGradient><radialGradient id="iOyf1re" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.647 14.424)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iK1dAJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.829 9.968)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8MqYFb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.262 .716)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOh54rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.465 9.969)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOW0Lzh" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.178 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCphltc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.264 9.982)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iWGcR8c" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.625 10.527)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i2QWKec" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.752 4.923)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iHhanOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.531 6.055)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="zqw5laobm"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="itlGdsj" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.344 2.899)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="icBn4Be" cx="0" cy="0" r="1" gradientTransform="matrix(2.67803 0 0 3.53252 8.307 4)" gradientUnits="userSpaceOnUse"><stop class="cxaqe9bxy"/><stop offset="1" class="p0efopw-a"/></radialGradient><radialGradient id="iT3jDKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.46875 8.0624 -.10205 18.781 7.305)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="rfhmcsbwp"/><stop offset="1" class="n6auyzb6w"/></radialGradient><radialGradient id="iLFqHQb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.86 19.29)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="ir6a2cg" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.219 18.164)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="iHAbCbc" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.33 20.461)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iGddC9A" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.196 18.58)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iuH4NEW" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.75 18.883)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iXfEFwc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.687 21.29)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="igwg9RO" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.697 11.244)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="iOU8Mny" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.156 20.064)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="iN9AjYZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.74 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ihn1AOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.74 26.575)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iYINv1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.74 27.825)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ilULTWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.74 29.176)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><filter id="ifsU8Tc" width="14.3" height="12.3" x="8.372" y="18.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/></filter><filter id="iqs2nMb" width="6.538" height="5.771" x="12.014" y="16.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".325"/></filter><filter id="idLS0ee" width="2.5" height="2.5" x="18.462" y="27.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".25"/></filter><filter id="iIaoKnN" width="2.5" height="2.5" x="18.462" y="23.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".25"/></filter><filter id="ihOEYub" width="2.5" height="2.5" x="18.462" y="19.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".25"/></filter><filter id="itYVMCe" width="1.7" height="1.7" x="19.132" y="27.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1883" result="effect2_innerShadow_4002_1883"/></filter><filter id="idgJAzc" width="1.7" height="1.7" x="19.132" y="23.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1883" result="effect2_innerShadow_4002_1883"/></filter><filter id="itH15Rb" width="1.7" height="1.7" x="19.132" y="20.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1883" result="effect2_innerShadow_4002_1883"/></filter><filter id="i0uqgcd" width="11.047" height="12.542" x="10.549" y="4.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1883" result="effect2_innerShadow_4002_1883"/></filter><filter id="inLoJ1d" width="3.877" height="4.9" x="13.501" y="9.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".5"/></filter><filter id="iTLtJUb" width="2.077" height="3.1" x="14.608" y="9.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="ivFaQwd" width="3.718" height="1.573" x="13.787" y="13.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="iwEZdQe" width="2.339" height="1.19" x="17.236" y="7.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/></filter><filter id="iqXIa2b" width="2.339" height="1.176" x="11.979" y="7.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/></filter><filter id="iDwcMBe" width=".787" height=".696" x="17.095" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="iQ2hyEh" width=".891" height=".913" x="17.934" y="9.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".1"/></filter><filter id="ibaVsZb" width=".986" height="1.04" x="13.492" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".1"/></filter><filter id="iM00VGP" width=".913" height=".705" x="12.737" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="igr0D2c" width="1.329" height="2.379" x="9.614" y="9.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".125"/></filter><filter id="iqppkcc" width="1.447" height="2.403" x="20.358" y="9.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".125"/></filter><filter id="i8vjSAd" width="2.205" height=".96" x="11.998" y="7.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".1"/></filter><filter id="iVS3tKe" width="2.205" height=".969" x="17.278" y="7.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".1"/></filter><filter id="ikO8q4b" width="14.779" height="5.543" x="8.307" y="2.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/></filter><filter id="iE29YeM" width=".675" height="2.047" x="12.554" y="3.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="ipH0d4d" width=".675" height="2.047" x="18.142" y="3.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="iZPIOBd" width=".98" height="2.537" x="15.211" y="3.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".1"/></filter><filter id="ig7iVAe" width="2.238" height="1.809" x="14.522" y="17.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1883" result="effect2_innerShadow_4002_1883"/></filter><filter id="iudqHBb" width="5.047" height="11.336" x="23.075" y="14.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/></filter><filter id="i36GRuh" width="3.672" height="4.703" x="23.537" y="15.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/><feGaussianBlur result="effect2_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="iUApjNR" width="4.468" height="5.556" x="23.304" y="24.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1883"/></filter><filter id="iLn4c2G" width="2.097" height=".3" x="23.674" y="25.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="iG0IhDb" width="2.097" height=".3" x="23.596" y="27.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><filter id="i8jvD6d" width="2.097" height=".3" x="23.674" y="28.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1883" stdDeviation=".05"/></filter><linearGradient id="i19O0ud" x1="10.476" x2="10.476" y1="7.867" y2="9.96" gradientUnits="userSpaceOnUse"><stop class="yyf5_sbtz"/><stop offset="1" class="x-_vdabdz"/></linearGradient><linearGradient id="i9HtKic" x1="20.818" x2="20.818" y1="7.696" y2="9.258" gradientUnits="userSpaceOnUse"><stop class="x6rvzacks"/><stop offset="1" class="qw7p3db1b"/></linearGradient><linearGradient id="ixcn1cb" x1="22.829" x2="26.073" y1="25.873" y2="25.873" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iniseFs" x1="7.812" x2="7.812" y1="30.992" y2="16.93" gradientUnits="userSpaceOnUse"><stop class="da7b97bvf"/><stop offset="1" class="si_znv48i"/></linearGradient><linearGradient id="iFBlABb" x1="8.672" x2="8.094" y1="26.617" y2="26.617" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iYRfEzj" x1="8.672" x2="12.608" y1="27.204" y2="27.204" gradientUnits="userSpaceOnUse"><stop class="t81o0ct1j"/><stop offset="1" class="v6vn_tcph"/></linearGradient><linearGradient id="i54Diib" x1="16.28" x2="13.319" y1="22.123" y2="18.739" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="idIDP1R" x1="20.5" x2="19.232" y1="27.637" y2="29.044" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i4XMXcd" x1="20.5" x2="19.232" y1="23.997" y2="25.404" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="ixNv87c" x1="20.5" x2="19.232" y1="20.367" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iAfzpdc" x1="20.846" x2="16.46" y1="12.57" y2="12.57" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ivTdfOc" x1="15.647" x2="16.502" y1="11.713" y2="11.713" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="itNQ2me" x1="14.574" x2="15.648" y1="11.558" y2="11.617" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iwZdw6l" x1="15.647" x2="15.647" y1="12.112" y2="12.964" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="idi5ilc" x1="15.647" x2="15.647" y1="9.864" y2="10.284" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ioGrONL" x1="18.607" x2="18.293" y1="10.022" y2="10.216" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iK8G4cb" x1="14.209" x2="13.895" y1="10.022" y2="10.216" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4mODYB" x1="22.083" x2="20.876" y1="10.049" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ieT1ajd" x1="9.797" x2="11.255" y1="10.753" y2="10.626" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iA0rGzd" x1="16.281" x2="16.281" y1="7.774" y2="7.086" gradientUnits="userSpaceOnUse"><stop class="co6smusrg"/><stop offset="1" class="bs-097z7j"/></linearGradient><linearGradient id="ifn5WEd" x1="13.027" x2="12.449" y1="5.626" y2="5.528" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ka0ki7btw"/><stop offset="1" class="r64vbvf7r"/></linearGradient><linearGradient id="iAMQGkc" x1="18.289" x2="18.922" y1="5.435" y2="5.528" gradientUnits="userSpaceOnUse"><stop offset=".246" class="qu7pewj0n"/><stop offset="1" class="g79jbcb8w"/></linearGradient><linearGradient id="iebELdi" x1="15.991" x2="15.991" y1="5.771" y2="3.743" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mzy53gozy"/><stop offset="1" class="zwaih9noa"/></linearGradient><linearGradient id="i9dGtBd" x1="16.375" x2="17.359" y1="17.992" y2="19.164" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="ilEM8Tb" x1="15.891" x2="15.891" y1="18.883" y2="17.444" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="i3ehsGd" x1="27.332" x2="23.304" y1="28.038" y2="28.038" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="i4aB3Ec" x1="23.824" x2="25.533" y1="26.032" y2="26.032" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iybtq3d" x1="23.746" x2="25.455" y1="27.336" y2="27.336" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iLSvS1S" x1="23.824" x2="25.533" y1="28.641" y2="28.641" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cook-medium-light" /></template>
<style>
.a_yooeola {
  d: path("M14.278 10.279c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.aatnh2b7u {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.296 13.386c.39.204.855.32 1.35.32c.502 0 .962-.117 1.351-.32h.001a.23.23 0 0 1 .27.045a.214.214 0 0 1 .025.272m-2.997-.317l2.934.276m-2.934-.276a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27m.295-.317l-.233.276m3.23.041l-.063-.041m.063.041l-.063-.041m.063.041c-.349.528-.956.88-1.646.88s-1.297-.352-1.646-.88m3.229-.041a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.584-.846m-.062.042l.062-.042m-.062.042l.062-.042");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3mtuebqr {
  stop-color: var(--svg-color--e9dae3, #E9DAE3);
}

.b5tqnes0a {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.61 9.687a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.blny5fbqc {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
  stop-opacity: 0;
}

.bq6f2zbqj {
  d: path("M14.984 17.563c.19-.063.44-.119.707-.119s.517.056.707.12a.39.39 0 0 1 .255.45c-.093.486-.27.8-.464.989a.5.5 0 0 1-.267.13a1.5 1.5 0 0 1-.477 0a.43.43 0 0 1-.252-.13c-.194-.189-.371-.503-.463-.99a.39.39 0 0 1 .254-.45");
}

.br4vp4byh {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
}

.bs-097z7j {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
  stop-opacity: 0;
}

.c1d5sgupt {
  stop-color: var(--svg-color--d39c8f, #D39C8F);
}

.c3weeebxy {
  d: path("M8.672 18.006h10.052c2.177 0 3.948 1.796 3.948 4.003v7.997h-14z");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ce0z6ljwu {
  stop-color: var(--svg-color--ab5d55, #AB5D55);
}

.cgnu7mxef {
  d: path("M10.593 9.026a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clwbcd6-k {
  d: path("M9.996 7.352h.96V9.96h-.96z");
}

.co6smusrg {
  stop-color: var(--svg-color--ab8bb8, #AB8BB8);
}

.cxaqe9bxy {
  stop-color: var(--svg-color--e7d1cd, #E7D1CD);
}

.d_-4zr8fj {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.652 15.476c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.502c0-3.422-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
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

.dlz8fwbma {
  d: path("M15.385 17.5c-.385.033-1.404.253-2.102 1.143c-.47.6-.498 1.44-.52 2.069q-.005.176-.014.326c-.01.145-.035.263-.07.363c-.054.154.04.341.2.331c.58-.036 1.018-.162 1.664-.705c.493-.413.743-1.062.851-1.716c.044.661.228 1.332.677 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.232-.31a1.3 1.3 0 0 1-.034-.368q.005-.151.018-.326c.04-.628.095-1.468-.313-2.11c-.607-.955-1.6-1.274-1.979-1.344c-.047.16-.092.359-.128.582a5 5 0 0 0-.07-.592");
}

.dnt6qhbmo {
  cx: 13.193px;
  cy: 9.873px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.dwp-1frtz {
  d: path("M23.081 18.36H8.232a10.94 10.94 0 0 1 7.42-2.884c3.484 0 5.153.81 7.43 2.885");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ec8xe10jz {
  fill: var(--svg-color--8e5834, #8E5834);
  d: path("M12.236 8.053a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ejuirjdrv {
  stop-color: var(--svg-color--f3bc92, #F3BC92);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.eqjk3s4mq {
  d: path("M10.822 13.65a3.916 3.916 0 0 0 3.885 3.405h1.887a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.278-4.388.366-6.27c-.011-.768-.657-.773-1.421-.805h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.376.799-3.376 2.665c0 1.861.15 4.405.273 6.27");
}

.er2-0gj_l {
  d: path("M13.463 9.491a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fij3-cbvh {
  fill-rule: evenodd;
  d: path("m18.242 5.88l.475-1.847V5.88z");
}

.fjyr3161v {
  stop-color: var(--svg-color--730620, #730620);
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.fs84khn_h {
  fill: var(--svg-color--b2a7be, #B2A7BE);
  d: path("M19.712 25.39a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.ft5dv1b6b {
  fill: none;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g79jbcb8w {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
  stop-opacity: 0;
}

.gd11xjopk {
  d: path("M8.672 17.979a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.gf0ecxend {
  d: path("M20.732 28.136a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gt-1-ac7u {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hfpav8v_t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.746 27.258h1.797");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hy5x434iq {
  fill: var(--svg-color--000, #000);
  d: path("M17.32 10.384c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.il79l0ryo {
  d: path("M10.241 2.09a1.933 1.933 0 0 0-.681 3.744a.215.215 0 0 1 .142.198v1.051c0 .249.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.028c0-.088.058-.165.141-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.isy8u3b-w {
  stop-color: var(--svg-color--ffdead, #FFDEAD);
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.iyetsnbcc {
  d: path("M20.338 7.352h.96V9.96h-.96z");
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.ka0ki7btw {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvpd_pghm {
  d: path("M21.727 5.93H9.675q.026.046.027.102v1.051c0 .249.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.028a.2.2 0 0 1 .025-.098");
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
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

.ltyemwqpv {
  d: path("m15.264 10.17l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mkts3-b3r {
  stop-color: var(--svg-color--bb7c74, #BB7C74);
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mrieobbjs {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.16 10.366l-.634 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.407-.542-.407-.661 0");
}

.mzy53gozy {
  stop-color: var(--svg-color--a990c1, #A990C1);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n26mtac8k {
  d: path("M15.647 13.781c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.n6auyzb6w {
  stop-color: var(--svg-color--b1a3bf, #B1A3BF);
}

.n8px-g5sz {
  fill: var(--svg-color--b29aac, #B29AAC);
  d: path("M19.712 21.76a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.n9euf4but {
  d: path("M15.411 3.743h.58V5.88h-.58z");
}

.nblo607_t {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.038 9.22c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ni42iccyp {
  d: path("M15.652 15.476c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.502c0-3.422-1.554-6.482-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.o-79f8n4o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.765 9.68c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.ocshmqb7l {
  d: path("M10.785 12.135a1.64 1.64 0 0 1-.904-.31v.932c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.oj5bkmbam {
  d: path("M23.304 25.301c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1H24.03a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.oracvnb6j {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.273 8.333c.257-.185.898-.509 1.656-.382");
}

.ovn99jb4z {
  d: path("M19.982 21.616a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.p0efopw-a {
  stop-color: var(--svg-color--b8a5ca, #B8A5CA);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm23dyb1u {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.208 8.294c-.282-.297-.898-.509-1.655-.381");
}

.pnnonnt5s {
  stop-color: var(--svg-color--e29f81, #E29F81);
}

.q4v93xbif {
  d: path("M20.569 12.226c.065-1.065.129-2.128.184-3.192a1.61 1.61 0 0 1-.184 3.191");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.ql78zhb7e {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
}

.qnufep55k {
  d: path("M20.508 12.135c.335-.011.65-.125.905-.31v.932c0 .893-.532 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.qu7pewj0n {
  stop-color: var(--svg-color--b39fc7, #B39FC7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw7p3db1b {
  stop-color: var(--svg-color--f9dba2, #F9DBA2);
}

.qzsw2yonp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 28.563h1.797");
}

.r1ve_2b_j {
  d: path("M26.655 23.062a.97.97 0 0 1 .967.967v2.215h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r64vbvf7r {
  stop-color: var(--svg-color--a28cb9, #A28CB9);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r73emubqg {
  d: path("M22.672 30.006h4v-3.502c0-3.422-1.554-6.482-4-8.498z");
}

.r7svlnonw {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
  stop-opacity: 0;
}

.rfhmcsbwp {
  stop-color: var(--svg-color--eee3f8, #EEE3F8);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.so0134bfv {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.256 9.22c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.t4c7gdbng {
  fill-rule: evenodd;
  d: path("m13.129 5.88l-.475-1.847V5.88z");
}

.t4ctysbhn {
  stop-color: var(--svg-color--bb7c74, #BB7C74);
  stop-opacity: 0;
}

.t81o0ct1j {
  stop-color: var(--svg-color--9e8fad, #9E8FAD);
}

.t8o9b3fch {
  cx: 13.193px;
  cy: 9.873px;
  rx: 0.39px;
  ry: 0.197px;
}

.thtl7hbqy {
  d: path("M18.626 10.266a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.tm5k9n0yq {
  d: path("M26.051 21.179c0-.406.26-.758.568-1.021c.605-.517 1.003-1.392 1.003-2.384c0-1.588-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.287-2.273 2.875c0 .992.398 1.867 1.002 2.384c.309.263.568.615.568 1.02v5.057h1.406z");
}

.tnwv9mbkd {
  stop-color: var(--svg-color--c07c7d, #C07C7D);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.twgdwy8sb {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.609 11.575q.057-.953.11-1.904a.955.955 0 0 1-.11 1.904");
}

.txq537bby {
  stop-color: var(--svg-color--d8c4e9, #D8C4E9);
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u-19d9bdt {
  fill: var(--svg-color--000, #000);
  d: path("M13.974 10.384a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.ulo0skb3n {
  stop-color: var(--svg-color--e4a284, #E4A284);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.umjjh0bmj {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.051 21.179c0-.406.26-.758.568-1.021c.605-.517 1.003-1.392 1.003-2.384c0-1.588-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.287-2.273 2.875c0 .992.398 1.867 1.002 2.384c.309.263.568.615.568 1.02v5.057h1.406z");
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v35e4abfb {
  cx: 25.348px;
  cy: 17.719px;
  rx: 1.711px;
  ry: 2.227px;
}

.v6vn_tcph {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
  stop-opacity: 0;
}

.vuu318b4c {
  stop-color: var(--svg-color--730620, #730620);
  stop-opacity: 0;
}

.w4ffscnyz {
  fill: var(--svg-color--8e5834, #8E5834);
  d: path("M19.38 8.17a1.85 1.85 0 0 0-.688-.412c-.304-.096-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.028.979.036c.198.063.332.164.49.3a.277.277 0 0 0 .364-.417");
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x-_vdabdz {
  stop-color: var(--svg-color--e3b782, #E3B782);
}

.x2ty5u7bf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 25.953h1.797");
}

.x6rvzacks {
  stop-color: var(--svg-color--fff5ba, #FFF5BA);
}

.xdemcobmc {
  fill: var(--svg-color--b5a5c4, #B5A5C4);
  d: path("M20.462 28.28a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.xfryo5b2y {
  d: path("M19.982 25.246a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xobxtdqdz {
  d: path("M17.83 9.491a.893.893 0 0 1 .86 1.128h-1.723a.896.896 0 0 1 .864-1.128");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.ygyrfpbde {
  stop-color: var(--svg-color--cfaee5, #CFAEE5);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yrzv-0byt {
  stop-color: var(--svg-color--b8a1d0, #B8A1D0);
  stop-opacity: 0;
}

.yyf5_sbtz {
  stop-color: var(--svg-color--f4ca9a, #F4CA9A);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z0saicbwe {
  d: path("M13.46 18.69c.67-.924 1.703-1.195 2.096-1.246c.205.83.308 2.667-.684 3.564c-.635.574-1.078.722-1.67.786c-.163.018-.27-.164-.222-.321c.03-.101.051-.22.053-.366c.01-.634-.108-1.68.426-2.418");
}

.z8vyvsujj {
  d: path("M17.855 18.69c-.67-.924-1.704-1.195-2.097-1.246c-.205.83-.308 2.667.684 3.564c.635.574 1.077.722 1.67.786c.163.018.269-.164.221-.321c-.03-.101-.05-.22-.053-.366c-.009-.634.11-1.68-.425-2.418");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zj9picbxt {
  stop-color: var(--svg-color--d39c8f, #D39C8F);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zpc74dlcp {
  d: path("M17.765 9.68c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zwaih9noa {
  stop-color: var(--svg-color--a990c1, #A990C1);
  stop-opacity: 0;
}

</style>
