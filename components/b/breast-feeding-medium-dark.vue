<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iulVaBd" class="jfldkvbwq"/></defs><g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#ifaQRje)" class="d2kvgvbvc"><path fill="url(#ih4gMYb)" class="xclicpbbr"/><path fill="url(#iaJvGWb)" class="xclicpbbr"/><path fill="url(#iUAVn3c)" class="xclicpbbr"/><path fill="url(#iDMUFId)" class="xclicpbbr"/><path fill="url(#iRyLg7T)" class="xclicpbbr"/><path fill="url(#inWKGOd)" class="xclicpbbr"/><path fill="url(#ixcNisc)" class="xclicpbbr"/><path fill="url(#iQNXk0c)" class="xclicpbbr"/><path fill="url(#i5UFD9d)" class="xclicpbbr"/><path fill="url(#iRl2Q4b)" class="xclicpbbr"/><path fill="url(#i5BFnpb)" class="xclicpbbr"/></g><path class="taon73bed"/><path fill="url(#iocxV8c)" class="jm-439s-j"/><g filter="url(#iSHoDHc)"><path fill="url(#iLBt6sc)" class="h_95yizme"/><path fill="url(#iz79kcc)" class="h_95yizme"/><path fill="url(#iA7VsTc)" class="h_95yizme"/></g><path fill="url(#iesuGjd)" class="rayfp7gzx"/><path fill="url(#i74cXxb)" class="rayfp7gzx"/><path fill="url(#iKsutNc)" class="rayfp7gzx"/><g filter="url(#iDS1MoW)"><path fill="url(#iQaMYad)" class="b2urkdb1t"/><path fill="url(#ijv70te)" class="b2urkdb1t"/><path fill="url(#izsdHDc)" class="b2urkdb1t"/><path fill="url(#ixbdoub)" class="b2urkdb1t"/></g><g filter="url(#iLbpxAE)"><path fill="url(#ixsNjnb)" class="gqn1rtbus"/></g><g filter="url(#iJBXsEl)"><path stroke="url(#iOa3fhe)" class="g6_0qwvjo"/></g><g filter="url(#ioOFvNe)"><path fill="url(#ik7CKjd)" class="aoijljbln"/></g><g filter="url(#it4DjCb)"><path stroke="url(#iwshOOd)" class="odoj2cbmh"/></g><g filter="url(#iq3KJde)"><path fill="url(#iYeW7Pb)" class="uoxk537no"/><path fill="url(#ivsQDfb)" class="uoxk537no"/></g><g filter="url(#iehFZnc)"><path class="z8z8xbc2c"/><path fill="url(#iJGDHpc)" class="l46nk9b7k"/><path fill="url(#ixzuHvc)" class="l46nk9b7k"/><path fill="url(#ityPdBB)" class="l46nk9b7k"/><path fill="url(#ibzkaAd)" class="l46nk9b7k"/></g><path fill="url(#iabpvod)" class="imrh5gb1z"/><path fill="url(#i4iidZo)" class="imrh5gb1z"/><path fill="url(#inl1dBb)" class="qdl5fk-3x"/><path fill="url(#ihFCb6b)" class="qdl5fk-3x"/><g filter="url(#i6Mt8Bd)"><path fill="url(#i0XAphd)" class="sm7d_tbpd"/></g><path fill="url(#ijgyFZc)" class="sm7d_tbpd"/><g filter="url(#iifYI8c)"><path fill="url(#i5dTkSc)" class="zqd5umbnr"/></g><g filter="url(#iVLh4hc)"><path stroke="url(#ibezS6t)" class="zjg6tabva"/></g><g filter="url(#iCj8Mqe)"><path stroke="url(#iYqITMe)" class="q3sy4o6la"/></g><g filter="url(#iwtmTle)"><path stroke="url(#ipV1ETd)" class="lkluujvkl"/></g><g filter="url(#iHsWIxc)"><path stroke="url(#iJweIdd)" class="f6jzx-84m"/></g><g filter="url(#iygaA1c)"><path stroke="url(#ij64Oxd)" class="hdox3xlqz"/></g><g filter="url(#io9wNde)"><path stroke="url(#i7qejDe)" class="rvvqwc-ve"/></g><g filter="url(#idAFYEc)"><path fill="url(#iHCOdJe)" class="fu_kl8bwl"/></g><g filter="url(#i7PXuJc)"><path fill="url(#iGcOqGe)" class="ia_ffdbjo"/><path fill="url(#i2OxLVO)" class="ia_ffdbjo"/></g><g filter="url(#ijR8lce)"><path class="qlr7-6b8s"/><path fill="url(#i9k8Nae)" class="ix37dvbfr"/></g><g filter="url(#iuHBGPc)"><path class="pgroe865u"/><path fill="url(#iUF9pdc)" class="yxwh0zb6l"/></g><g filter="url(#ikfSJ1M)"><path fill="url(#iBiThdc)" class="pq__6sdbe"/><path fill="url(#iO6Rwab)" class="pq__6sdbe"/><path fill="url(#ijEqr9c)" class="pq__6sdbe"/><path fill="url(#ijUafQd)" class="pq__6sdbe"/><path fill="url(#iY5Gdvb)" class="pq__6sdbe"/></g><path fill="url(#i4dstqc)" class="pq__6sdbe"/><path fill="url(#i9AEE3d)" class="pq__6sdbe"/><path fill="url(#imPqUab)" class="pq__6sdbe"/><path fill="url(#iyhPbyK)" class="pq__6sdbe"/><g filter="url(#iZEuhok)"><path class="ftvmb3bna"/></g><g filter="url(#ibnVAAL)"><path class="pg7c8_bem"/><path fill="url(#i2LqZZp)" class="rh0cl8bzr"/><path fill="url(#iTZ47vb)" class="rh0cl8bzr"/><path fill="url(#ipZQOJk)" class="rh0cl8bzr"/><path fill="url(#iAwzF3b)" class="rh0cl8bzr"/></g><g filter="url(#iBFXoIc)"><use href="#iulVaBd"/><path stroke="url(#imekyJe)" class="jnzxs_b5h"/></g><use href="#iulVaBd"/><g filter="url(#ighE6Cc)"><path class="b9gj8debp"/></g><g filter="url(#i1VaDnd)"><path clip-rule="evenodd" class="aubse-b7w"/></g><g filter="url(#ihW8lEb)"><path class="ix0orgbpn"/></g><g filter="url(#iyA909b)"><path class="p5e7kfbhf"/></g><g filter="url(#i85CxCc)"><path class="akrhvrbgm"/><path fill="url(#i1nZvfd)" class="e550nqbyq"/></g><g filter="url(#iCrn2nb)"><path class="oqe30ac8a"/><path fill="url(#iTD094d)" class="wbn_mm1xd"/><path fill="url(#i6dkVge)" class="wbn_mm1xd"/></g><g filter="url(#ipzkeud)"><path stroke="url(#im7vjUd)" class="sdsijabyc"/></g><g filter="url(#i0Pc1Hc)"><path fill="url(#iLzlmOe)" class="dssl6dbzd"/></g><g filter="url(#i6coXSb)"><path fill="url(#iTGW2Rc)" class="tuzs6gnlm"/></g><g filter="url(#iR4gpte)"><path class="t0enfxe1b"/></g><path fill="url(#icOQvee)" class="fod3ajbdi"/><path fill="url(#iLYUGSc)" class="dft05p0rf"/><g filter="url(#iSGHG5b)" class="tryqaac1t"><path stroke="url(#iiJ0FFd)" class="qonrj45re"/><path stroke="url(#i97Z5Wd)" class="qonrj45re"/></g><g filter="url(#iDT52Md)" class="tryqaac1t"><path stroke="url(#iszdKob)" class="a1ce1yj4x"/><path stroke="url(#ilu8Nyc)" class="a1ce1yj4x"/></g><defs><radialGradient id="iaJvGWb" cx="0" cy="0" r="1" gradientTransform="matrix(.26716 4.91045 -6.10639 .33223 16.111 13.853)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iUAVn3c" cx="0" cy="0" r="1" gradientTransform="rotate(135.261 3.587 10.063)scale(3.70683 4.87902)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iDMUFId" cx="0" cy="0" r="1" gradientTransform="rotate(116.657 1.646 9.54)scale(2.29769 1.76212)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iRyLg7T" cx="0" cy="0" r="1" gradientTransform="rotate(110.691 1.992 8.86)scale(2.64352 1.85813)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="inWKGOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.95319 2.47883 -3.4318 2.70409 10.664 3.385)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ixcNisc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2239 1.79787 -2.51246 -1.71035 20.858 3.735)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iQNXk0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82311 .9254 -1.9375 -3.81705 23.622 8.797)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i5UFD9d" cx="0" cy="0" r="1" gradientTransform="rotate(155.281 10.462 8.848)scale(3.0903 3.95292)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iRl2Q4b" cx="0" cy="0" r="1" gradientTransform="rotate(-119.38 12.102 -2.524)scale(2.99329 2.35873)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i5BFnpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.60447 -.12917 .21025 2.61167 9.334 11.437)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iocxV8c" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 1.9893 19.511 29.842)" gradientUnits="userSpaceOnUse"><stop class="n2a634bwb"/><stop offset="1" class="y9owwpbix"/></radialGradient><radialGradient id="iLBt6sc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50378 0 0 -5.6875 21.761 19.065)" gradientUnits="userSpaceOnUse"><stop class="ym__citvk"/><stop offset="1" class="fo2qq07hm"/></radialGradient><radialGradient id="iz79kcc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.983 12.457 8.976)scale(2.5864 3.5607)" gradientUnits="userSpaceOnUse"><stop class="cqpaw5wjj"/><stop offset="1" class="pp6b3x_re"/></radialGradient><radialGradient id="iA7VsTc" cx="0" cy="0" r="1" gradientTransform="rotate(68.199 -3.741 20.602)scale(2.27187 4.46829)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="nozadwzyp"/><stop offset="1" class="mvhkmcb9y"/></radialGradient><radialGradient id="i74cXxb" cx="0" cy="0" r="1" gradientTransform="matrix(2.79688 2.04686 -1.95763 2.67496 23.418 27.284)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tkcxzncwj"/><stop offset="1" class="mqicc-u0l"/></radialGradient><radialGradient id="iKsutNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.3125 -2.12008 2.12008 22.01 27.722)" gradientUnits="userSpaceOnUse"><stop class="c14jvicyx"/><stop offset="1" class="i8x7p37cq"/></radialGradient><radialGradient id="ijv70te" cx="0" cy="0" r="1" gradientTransform="rotate(126.08 3.144 12.084)scale(4.98797 9.68383)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7fe64b-m"/><stop offset="1" class="o3yqmrbrg"/></radialGradient><radialGradient id="izsdHDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45313 -.6875 0 13.87 28.222)" gradientUnits="userSpaceOnUse"><stop class="la4e9obft"/><stop offset="1" class="sq95r4vix"/></radialGradient><radialGradient id="ixbdoub" cx="0" cy="0" r="1" gradientTransform="rotate(-117.519 14.61 7.125)scale(1.35267 2.95016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="kc6luf8ah"/><stop offset="1" class="yit44gm3t"/></radialGradient><radialGradient id="ixsNjnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 -1.6057 .88152 .74629 11.761 25.644)" gradientUnits="userSpaceOnUse"><stop class="c_e6lvb0e"/><stop offset="1" class="bzrv_p78g"/></radialGradient><radialGradient id="iOa3fhe" cx="0" cy="0" r="1" gradientTransform="rotate(-162.16 15.537 12.02)scale(.71402 1.53504)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></radialGradient><radialGradient id="ivsQDfb" cx="0" cy="0" r="1" gradientTransform="rotate(163.67 9.095 15.451)scale(5.1125 7.55864)" gradientUnits="userSpaceOnUse"><stop class="khg6a5-nz"/><stop offset="1" class="jyzijgb5l"/></radialGradient><radialGradient id="iJGDHpc" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 -1.0625 .82137 1.8964 14.8 30.64)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="k9qs7hygt"/><stop offset="1" class="uuy1468ob"/></radialGradient><radialGradient id="ixzuHvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .36719 -.26111 -.32778 16.792 26.25)" gradientUnits="userSpaceOnUse"><stop class="t4qc1db7w"/><stop offset="1" class="m5ze59kvt"/></radialGradient><radialGradient id="ityPdBB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 0 0 -.59662 16.175 28.12)" gradientUnits="userSpaceOnUse"><stop class="a9jj3ebfn"/><stop offset="1" class="ar7c0uvzi"/></radialGradient><radialGradient id="iabpvod" cx="0" cy="0" r="1" gradientTransform="rotate(154.496 10.803 13.764)scale(3.77401 4.40797)" gradientUnits="userSpaceOnUse"><stop class="w-wd4mb8i"/><stop offset="1" class="jswq_j2dq"/></radialGradient><radialGradient id="i4iidZo" cx="0" cy="0" r="1" gradientTransform="rotate(42.983 -15.88 40.586)scale(5.22527)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="i54m18vgp"/><stop offset=".995" class="nybv-x_bu"/></radialGradient><radialGradient id="ihFCb6b" cx="0" cy="0" r="1" gradientTransform="matrix(.39062 -3.01563 4.79304 .62086 19.418 24.316)" gradientUnits="userSpaceOnUse"><stop class="l99uylilx"/><stop offset="1" class="xjvfic_gd"/></radialGradient><radialGradient id="i0XAphd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.355 27.721)" gradientUnits="userSpaceOnUse"><stop class="obau_hbgt"/><stop offset="1" class="egq8jpikc"/></radialGradient><radialGradient id="iGcOqGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.38075 -1.6772 2.05411 2.91575 20.247 10.834)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="i2OxLVO" cx="0" cy="0" r="1" gradientTransform="matrix(1.52167 .51705 -.14653 .43125 20.907 8.404)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i9k8Nae" cx="0" cy="0" r="1" gradientTransform="matrix(1.55729 -.41415 .32526 1.22304 20.55 10.421)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iUF9pdc" cx="0" cy="0" r="1" gradientTransform="rotate(169.381 5 6.55)scale(1.12384 1.12913)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iBiThdc" cx="0" cy="0" r="1" gradientTransform="rotate(149.788 8.187 7.899)scale(7.674 8.79046)" gradientUnits="userSpaceOnUse"><stop class="hix_jbcwc"/><stop offset=".777" class="g4tdpvbfe"/></radialGradient><radialGradient id="iO6Rwab" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09192 1.43607 -1.00323 -1.4614 18.057 11.11)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ijEqr9c" cx="0" cy="0" r="1" gradientTransform="matrix(.57454 -4.382 5.53892 .72623 14.848 17.863)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="ijUafQd" cx="0" cy="0" r="1" gradientTransform="matrix(.109 8.00202 -9.9583 .13565 16.815 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="iY5Gdvb" cx="0" cy="0" r="1" gradientTransform="rotate(158.227 7.871 7.769)scale(7.492 12.9551)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i4dstqc" cx="0" cy="0" r="1" gradientTransform="rotate(169.381 10.186 6.355)scale(1.36807 6.89305)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="i9AEE3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08925 -1.20685 1.27966 -1.15497 20.763 15.924)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="imPqUab" cx="0" cy="0" r="1" gradientTransform="matrix(1.5229 -1.98562 2.35888 1.80918 12.733 17.413)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iyhPbyK" cx="0" cy="0" r="1" gradientTransform="rotate(126.339 7.112 7.92)scale(3.37515 3.1707)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="iv3uqpblx"/><stop offset="1" class="cjzjy7zus"/></radialGradient><radialGradient id="i2LqZZp" cx="0" cy="0" r="1" gradientTransform="matrix(-.87925 -2.05888 .63183 -.26983 17.174 12.428)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iAwzF3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.8153 .15286 -.04294 -.229 16.965 12.697)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i1nZvfd" cx="0" cy="0" r="1" gradientTransform="matrix(.77721 -3.1434 1.60314 .39638 9.479 9.418)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iTD094d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34406 5.03015 -8.19987 -2.19101 16.37 2.46)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i6dkVge" cx="0" cy="0" r="1" gradientTransform="rotate(88.087 5.687 9.173)scale(1.47915 3.1681)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="i97Z5Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 19.263 10.271)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><radialGradient id="ilu8Nyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 14.796 11.024)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><filter id="ifaQRje" width="16.732" height="17.497" x="8.013" y="1.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="iSHoDHc" width="12.09" height="8.809" x="15.158" y="16.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.34902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="iDS1MoW" width="12.107" height="12.935" x="4.292" y="16.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="iLbpxAE" width="3.547" height="2.605" x="10.246" y="23.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".25"/></filter><filter id="iJBXsEl" width="1.338" height="3.484" x="25.65" y="26.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".05"/></filter><filter id="ioOFvNe" width="8.034" height="4.188" x="6.668" y="26.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".5"/></filter><filter id="it4DjCb" width="1.907" height="4.376" x="11.205" y="20.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".125"/></filter><filter id="iq3KJde" width="10.856" height="8.359" x="11.765" y="21.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="iehFZnc" width="6.652" height="4.473" x="14.118" y="25.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="i6Mt8Bd" width="6.654" height="7.23" x="19.111" y="21.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="iifYI8c" width="5.813" height="5.503" x="7.73" y="21.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".5"/></filter><filter id="iVLh4hc" width="3.309" height="3.341" x="20.88" y="21.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".2"/></filter><filter id="iCj8Mqe" width="2.013" height="4.911" x="23.891" y="22.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".2"/></filter><filter id="iwtmTle" width="3.294" height="2.926" x="19.598" y="22.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".2"/></filter><filter id="iHsWIxc" width="3.106" height="2.411" x="19.224" y="23.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".2"/></filter><filter id="iygaA1c" width="3.043" height="2.122" x="19.208" y="25.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".2"/></filter><filter id="io9wNde" width="5.798" height=".972" x="14.85" y="28.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".15"/></filter><filter id="idAFYEc" width="3.576" height="3.441" x="9.318" y="10.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="i7PXuJc" width="3.426" height="3.691" x="19.271" y="8.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="ijR8lce" width="3.287" height="3.297" x="19.341" y="8.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".25"/></filter><filter id="iuHBGPc" width="2.787" height="2.797" x="9.658" y="10.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".125"/></filter><filter id="ikfSJ1M" width="11.243" height="11.267" x="10.208" y="6.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="iZEuhok" width="2.983" height="3.925" x="14.767" y="10.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".25"/></filter><filter id="ibnVAAL" width="2.483" height="3.414" x="15.159" y="10.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".125"/></filter><filter id="iBFXoIc" width="3.86" height="1.914" x="14.653" y="13.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".05"/></filter><filter id="ighE6Cc" width="2.53" height="1.374" x="11.592" y="8.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="i1VaDnd" width="2.63" height=".929" x="17.007" y="7.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/></filter><filter id="ihW8lEb" width="2.404" height=".786" x="17.049" y="7.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".1"/></filter><filter id="iyA909b" width="2.297" height="1.219" x="11.605" y="8.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".1"/></filter><filter id="i85CxCc" width="4.238" height="5.342" x="8.509" y="4.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/><feGaussianBlur result="effect2_foregroundBlur_4002_3506" stdDeviation=".2"/></filter><filter id="iCrn2nb" width="9.925" height="4.96" x="11.351" y="2.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3506"/><feGaussianBlur result="effect2_foregroundBlur_4002_3506" stdDeviation=".125"/></filter><filter id="ipzkeud" width="1.506" height="2.289" x="11.319" y="4.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".1"/></filter><filter id="i0Pc1Hc" width="3.872" height="3.001" x="11.644" y="8.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".3"/></filter><filter id="i6coXSb" width="3.682" height="2.915" x="16.514" y="7.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".3"/></filter><filter id="iR4gpte" width="7.4" height="3.952" x="14.192" y="3.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".5"/></filter><filter id="iSGHG5b" width="2.582" height="1.236" x="17.021" y="9.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".075"/></filter><filter id="iDT52Md" width="2.582" height="1.236" x="12.554" y="10.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3506" stdDeviation=".075"/></filter><linearGradient id="ih4gMYb" x1="19.474" x2="14.781" y1="2.937" y2="17.502" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iesuGjd" x1="26.793" x2="24.491" y1="25.003" y2="29.842" gradientUnits="userSpaceOnUse"><stop class="up7b_htug"/><stop offset="1" class="bvctw1bkc"/></linearGradient><linearGradient id="iQaMYad" x1="15.261" x2="6.793" y1="19.159" y2="29.842" gradientUnits="userSpaceOnUse"><stop class="eoa632ltp"/><stop offset="1" class="rlw3b4b7i"/></linearGradient><linearGradient id="ik7CKjd" x1="13.48" x2="7.928" y1="28.846" y2="28.822" gradientUnits="userSpaceOnUse"><stop class="lzdnytbwv"/><stop offset="1" class="yasfqbb-e"/></linearGradient><linearGradient id="iwshOOd" x1="13.155" x2="13.104" y1="24.234" y2="21.285" gradientUnits="userSpaceOnUse"><stop class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></linearGradient><linearGradient id="iYeW7Pb" x1="21.355" x2="14.293" y1="27.565" y2="27.128" gradientUnits="userSpaceOnUse"><stop class="vrjrrpcnz"/><stop offset="1" class="qarzv5b-l"/></linearGradient><linearGradient id="ibzkaAd" x1="18.565" x2="18.55" y1="29.995" y2="29.182" gradientUnits="userSpaceOnUse"><stop offset=".204" class="pr7qiqnmi"/><stop offset="1" class="eyp_upbhp"/></linearGradient><linearGradient id="inl1dBb" x1="21.668" x2="20.168" y1="18.563" y2="23.159" gradientUnits="userSpaceOnUse"><stop class="rm6lemo-n"/><stop offset=".635" class="uny69rbro"/></linearGradient><linearGradient id="ijgyFZc" x1="25.558" x2="25.003" y1="25.177" y2="25.297" gradientUnits="userSpaceOnUse"><stop offset=".049" class="h16wjhl7w"/><stop offset="1" class="jn_j6eb5x"/></linearGradient><linearGradient id="i5dTkSc" x1="10.636" x2="13.293" y1="25.569" y2="22.322" gradientUnits="userSpaceOnUse"><stop class="lk8w5cclk"/><stop offset="1" class="qrasocbfu"/></linearGradient><linearGradient id="ibezS6t" x1="22.142" x2="24.193" y1="22.736" y2="24.658" gradientUnits="userSpaceOnUse"><stop offset=".076" class="m-i_kny6s"/><stop offset="1" class="kl_w5nx3p"/></linearGradient><linearGradient id="iYqITMe" x1="24.746" x2="25.784" y1="23.532" y2="23.729" gradientUnits="userSpaceOnUse"><stop offset=".076" class="m-i_kny6s"/><stop offset="1" class="kl_w5nx3p"/></linearGradient><linearGradient id="ipV1ETd" x1="20.855" x2="22.732" y1="23.356" y2="25.384" gradientUnits="userSpaceOnUse"><stop offset=".076" class="m-i_kny6s"/><stop offset="1" class="kl_w5nx3p"/></linearGradient><linearGradient id="iJweIdd" x1="20.422" x2="21.631" y1="24.527" y2="26.419" gradientUnits="userSpaceOnUse"><stop offset=".076" class="m-i_kny6s"/><stop offset="1" class="kl_w5nx3p"/></linearGradient><linearGradient id="ij64Oxd" x1="20.386" x2="20.997" y1="25.983" y2="27.04" gradientUnits="userSpaceOnUse"><stop offset=".076" class="m-i_kny6s"/><stop offset="1" class="kl_w5nx3p"/></linearGradient><linearGradient id="i7qejDe" x1="19.922" x2="15.689" y1="28.944" y2="28.888" gradientUnits="userSpaceOnUse"><stop class="i6i839zlx"/><stop offset="1" class="j-pk_xb5x"/></linearGradient><linearGradient id="iHCOdJe" x1="9.419" x2="10.716" y1="12.481" y2="12.238" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iTZ47vb" x1="15.386" x2="16.368" y1="12.842" y2="12.658" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ipZQOJk" x1="16.525" x2="16.405" y1="13.498" y2="12.856" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="imekyJe" x1="15.635" x2="15.98" y1="15.244" y2="14.406" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="im7vjUd" x1="11.687" x2="12.512" y1="5.216" y2="6.445" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iLzlmOe" x1="14.471" x2="11.784" y1="10.427" y2="10.136" gradientUnits="userSpaceOnUse"><stop offset=".249" class="ty9b1kbqd"/><stop offset="1" class="qwt3z0bcj"/></linearGradient><linearGradient id="iTGW2Rc" x1="19.211" x2="15.737" y1="9.896" y2="8.742" gradientUnits="userSpaceOnUse"><stop offset=".394" class="vx130hb0m"/><stop offset="1" class="nvx95vy5s"/></linearGradient><linearGradient id="icOQvee" x1="19.154" x2="17.591" y1="10.633" y2="11.457" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="iLYUGSc" x1="14.655" x2="13.088" y1="11.392" y2="12.213" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="iiJ0FFd" x1="17.123" x2="19.451" y1="10.731" y2="10.893" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iszdKob" x1="12.655" x2="14.984" y1="11.483" y2="11.645" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:breast-feeding-medium-dark" /></template>
<style>
.a1ce1yj4x {
  d: path("M12.804 11.394c.13.122.518.352 1.021.298c.505-.055.947-.544 1.06-.728");
}

.a9jj3ebfn {
  stop-color: var(--svg-color--93716c, #93716C);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.akrhvrbgm {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M9.45 5.865c.474-.74 1.594-.952 2.129-.955l.668 1.28c-.272.008-.49.146-.652.377c-.221 1.412-1.696 2.445-2.406 2.785c-.449-1.539-.355-2.523.261-3.487");
}

.aoijljbln {
  d: path("M7.668 27.002h6.034v2.188H7.668z");
}

.ar7c0uvzi {
  stop-color: var(--svg-color--7e5851, #7E5851);
  stop-opacity: 0;
}

.aubse-b7w {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.25 7.96l-.099.27zc.147.056.223.22.168.37a.285.285 0 0 1-.366.168l-.006-.002a1 1 0 0 0-.13-.039a3 3 0 0 0-.384-.075a2.4 2.4 0 0 0-1.14.114a.287.287 0 0 1-.202-.537a3 3 0 0 1 1.412-.146a3.5 3.5 0 0 1 .631.142l.011.003l.003.002z");
}

.b2urkdb1t {
  d: path("M13.57 16.907c-3.353 1.353-6.48 5.4-8.312 7.956c-.71.854-1.718 2.662-.086 4.979h9.18c.104-.703.154-1.982-.053-3.129c-.11-.613-.72-.996-1.342-.996h-1.196c.102-.265.73-1.357 1.801-1.937c.505-.273.854-.563 1.413-.886l.495-.287l.73-.42a6.03 6.03 0 0 1-.942-3.245V17.49a5.2 5.2 0 0 1-1.689-.583");
}

.b9gj8debp {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.062 9.707l-.004.004a.285.285 0 0 1-.402-.042a.29.29 0 0 1 .042-.404l.001-.001l.003-.002l.01-.007a2 2 0 0 1 .144-.104a3.4 3.4 0 0 1 .408-.233a3 3 0 0 1 1.383-.316a.287.287 0 0 1-.019.574a2.4 2.4 0 0 0-1.115.258a3 3 0 0 0-.45.273");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bvctw1bkc {
  stop-color: var(--svg-color--9c69f1, #9C69F1);
}

.bzrv_p78g {
  stop-color: var(--svg-color--44327f, #44327F);
  stop-opacity: 0;
}

.c_e6lvb0e {
  stop-color: var(--svg-color--44327f, #44327F);
}

.c14jvicyx {
  stop-color: var(--svg-color--603eb7, #603EB7);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cjzjy7zus {
  stop-color: var(--svg-color--926c64, #926C64);
  stop-opacity: 0;
}

.cqpaw5wjj {
  stop-color: var(--svg-color--664b41, #664B41);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dft05p0rf {
  d: path("M14.726 10.795c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51c-.31.06-.62-.03-.86-.22a.25.25 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.4");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dssl6dbzd {
  d: path("M12.244 9.568c1.375-.263 2.39.36 2.672 1.125c-1.413.208-2.038.38-2.476.615z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e550nqbyq {
  d: path("M9.45 5.865c.474-.74 1.594-.952 2.129-.955l.668 1.28c-.272.008-.49.146-.652.377c-.221 1.412-1.696 2.445-2.406 2.785c-.449-1.539-.355-2.523.261-3.487");
}

.egq8jpikc {
  stop-color: var(--svg-color--6a443e, #6A443E);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eoa632ltp {
  stop-color: var(--svg-color--9165d0, #9165D0);
}

.eyp_upbhp {
  stop-color: var(--svg-color--7d495f, #7D495F);
  stop-opacity: 0;
}

.f6jzx-84m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.824 24.245l1.906 1.211");
}

.fo2qq07hm {
  stop-color: var(--svg-color--7e584d, #7E584D);
}

.fod3ajbdi {
  d: path("M19.225 10.042c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51s-.63-.03-.86-.23a.3.3 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.39");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftvmb3bna {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.651 11.102l-.38 1.921a.576.576 0 0 0 .682.633l.823-.154a.578.578 0 0 0 .407-.838l-.891-1.682c-.194-.373-.59-.299-.641.12");
}

.fu_kl8bwl {
  d: path("M11.349 13.775a1.717 1.717 0 0 0 1.366-2.007a1.717 1.717 0 0 0-2-1.376A1.717 1.717 0 0 0 9.347 12.4a1.717 1.717 0 0 0 2 1.376");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4tdpvbfe {
  stop-color: var(--svg-color--754b4f, #754B4F);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6_0qwvjo {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.613 26.401c.273.907.367 2.164-.797 3.18");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gqn1rtbus {
  d: path("M10.746 25.644h1.57l.977-1.594c-1.675-.139-2.396 1.005-2.547 1.594");
}

.h_95yizme {
  d: path("M17.348 16.302c-.72 0-1.42.08-2.09.22v2.42c0 3.48 2.93 6.25 6.41 6.06l5.58-.31c-.7-4.74-4.86-8.39-9.9-8.39");
}

.h16wjhl7w {
  stop-color: var(--svg-color--95786b, #95786B);
}

.hdox3xlqz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.808 25.769l1.843.922");
}

.hix_jbcwc {
  stop-color: var(--svg-color--996c5d, #996C5D);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i54m18vgp {
  stop-color: var(--svg-color--51e398, #51E398);
  stop-opacity: 0;
}

.i6i839zlx {
  stop-color: var(--svg-color--836463, #836463);
}

.i8x7p37cq {
  stop-color: var(--svg-color--603eb7, #603EB7);
  stop-opacity: 0;
}

.ia_ffdbjo {
  d: path("M21.301 11.91a1.717 1.717 0 0 0 1.366-2.007a1.717 1.717 0 0 0-2-1.376a1.717 1.717 0 0 0-1.366 2.007a1.716 1.716 0 0 0 2 1.375");
}

.imrh5gb1z {
  d: path("M23.408 27.002a4.3 4.3 0 1 0 0-8.6c-2.375 0-3.553 1.925-3.553 4.3s1.178 4.3 3.553 4.3");
}

.incjljb4q {
  stop-color: var(--svg-color--090c09, #090C09);
}

.iv3uqpblx {
  stop-color: var(--svg-color--926c64, #926C64);
}

.ix0orgbpn {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.349 8.168c.322-.146 1.168-.262 1.804.036");
}

.ix37dvbfr {
  d: path("M21.196 11.347a1.146 1.146 0 0 0 .912-1.34a1.146 1.146 0 0 0-1.335-.918a1.146 1.146 0 0 0-.912 1.34a1.146 1.146 0 0 0 1.335.918");
}

.j-pk_xb5x {
  stop-color: var(--svg-color--836463, #836463);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j9v6w1g-o {
  stop-color: var(--svg-color--0a0909, #0A0909);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jfldkvbwq {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.624 14.374a3.2 3.2 0 0 1-1.555-.083c-.161-.05-.287.15-.17.27a2.05 2.05 0 0 0 1.875.615a2.05 2.05 0 0 0 1.525-1.252c.066-.16-.123-.295-.256-.19a3.2 3.2 0 0 1-1.419.64");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jm-439s-j {
  d: path("M25.578 29.842c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.jn_j6eb5x {
  stop-color: var(--svg-color--835858, #835858);
  stop-opacity: 0;
}

.jnzxs_b5h {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.624 14.374a3.2 3.2 0 0 1-1.555-.083c-.161-.05-.287.15-.17.27a2.05 2.05 0 0 0 1.875.615a2.05 2.05 0 0 0 1.525-1.252c.066-.16-.123-.295-.256-.19a3.2 3.2 0 0 1-1.419.64Z");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jswq_j2dq {
  stop-color: var(--svg-color--34e38b, #34E38B);
}

.jyzijgb5l {
  stop-color: var(--svg-color--248571, #248571);
  stop-opacity: 0;
}

.k9qs7hygt {
  stop-color: var(--svg-color--885660, #885660);
}

.ka236wzgl {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc6luf8ah {
  stop-color: var(--svg-color--7556b0, #7556B0);
}

.khg6a5-nz {
  stop-color: var(--svg-color--248571, #248571);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kl_w5nx3p {
  stop-color: var(--svg-color--876d69, #876D69);
  stop-opacity: 0;
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l46nk9b7k {
  d: path("M14.318 29.841h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.l99uylilx {
  stop-color: var(--svg-color--309972, #309972);
}

.la4e9obft {
  stop-color: var(--svg-color--ac7ff8, #AC7FF8);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lk8w5cclk {
  stop-color: var(--svg-color--a176df, #A176DF);
}

.lkluujvkl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m20.198 22.954l2.093 1.726");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lzdnytbwv {
  stop-color: var(--svg-color--a673ff, #A673FF);
}

.m-i_kny6s {
  stop-color: var(--svg-color--876d69, #876D69);
}

.m-leh6bjs {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
}

.m5ze59kvt {
  stop-color: var(--svg-color--8b6c69, #8B6C69);
  stop-opacity: 0;
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqicc-u0l {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mvhkmcb9y {
  stop-color: var(--svg-color--684136, #684136);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n2a634bwb {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
}

.n7fe64b-m {
  stop-color: var(--svg-color--6a428c, #6A428C);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nozadwzyp {
  stop-color: var(--svg-color--552c26, #552C26);
}

.nvx95vy5s {
  stop-color: var(--svg-color--8e5d56, #8E5D56);
  stop-opacity: 0;
}

.nybv-x_bu {
  stop-color: var(--svg-color--51e398, #51E398);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o3yqmrbrg {
  stop-color: var(--svg-color--885ebc, #885EBC);
  stop-opacity: 0;
}

.obau_hbgt {
  stop-color: var(--svg-color--895d5f, #895D5F);
}

.odoj2cbmh {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.631 21.003c.344.635 1.031 2.281 1.031 3.781");
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.oqe30ac8a {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M13.767 3.095c-1.234-.04-2.076 1.346-2.116 1.81c1.8 3.52 4.545 2.794 7.236 1.972c1.61-.492 1.93.227 2.139.565c-.775-4.134-4.42-4.254-7.228-4.346z");
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p5e7kfbhf {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.601 8.845c-.351-.035-1.19.128-1.696.614");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pg7c8_bem {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.635 10.954l-.221 1.891a.576.576 0 0 0 .682.633l.823-.154a.578.578 0 0 0 .406-.837l-.89-1.683c-.194-.373-.75-.269-.8.15");
}

.pgroe865u {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.264 13.21a1.146 1.146 0 0 0 .912-1.34a1.146 1.146 0 0 0-1.336-.918a1.146 1.146 0 0 0-.912 1.339a1.146 1.146 0 0 0 1.336.918");
}

.pp6b3x_re {
  stop-color: var(--svg-color--664b41, #664B41);
  stop-opacity: 0;
}

.pq__6sdbe {
  d: path("m10.362 10.835l.013-.003l-.063-.277l-.071-.32c-.166-1 .341-1.495.564-1.67l.05-.032l.05-.031a2.46 2.46 0 0 0 1-1.531l.048-.22a.28.28 0 0 1 .473-.144a4.1 4.1 0 0 0 3.666 1.133l3.369-.632c.188-.035 1.15-.12 1.45 1.178l.482 3.253c.423 2.97-1.495 5.377-4.29 5.901s-5.456-1.024-6.137-3.946z");
}

.pr7qiqnmi {
  stop-color: var(--svg-color--7d495f, #7D495F);
}

.q3sy4o6la {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m24.49 22.667l.813 3.71");
}

.qarzv5b-l {
  stop-color: var(--svg-color--37ba71, #37BA71);
}

.qdl5fk-3x {
  d: path("M21.538 23.783a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.qlr7-6b8s {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M21.196 11.347a1.146 1.146 0 0 0 .912-1.34a1.146 1.146 0 0 0-1.335-.918a1.146 1.146 0 0 0-.912 1.34a1.146 1.146 0 0 0 1.335.918");
}

.qonrj45re {
  d: path("M17.271 10.642c.13.122.518.352 1.022.298c.504-.055.947-.544 1.06-.728");
}

.qrasocbfu {
  stop-color: var(--svg-color--a176df, #A176DF);
  stop-opacity: 0;
}

.qtbzeirls {
  stop-color: var(--svg-color--a980f3, #A980F3);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qwt3z0bcj {
  stop-color: var(--svg-color--70434c, #70434C);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rayfp7gzx {
  d: path("M27.515 27.347c-.013-.405-.165-2.417-.222-3.117l-2.825.18l-3.008 3.323c0 1.264.513 1.95.805 2.109h4.39c.97-.964.868-2.211.86-2.495");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rh0cl8bzr {
  d: path("m15.635 10.954l-.221 1.891a.576.576 0 0 0 .682.633l.823-.154a.578.578 0 0 0 .406-.837l-.89-1.683c-.194-.373-.75-.269-.8.15");
}

.rlw3b4b7i {
  stop-color: var(--svg-color--9565e9, #9565E9);
}

.rm6lemo-n {
  stop-color: var(--svg-color--3db155, #3DB155);
}

.rvvqwc-ve {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.3 28.944c.886.054 3.107.13 4.898 0");
}

.sdsijabyc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.62 4.855c.072.251.473 1.17.906 1.69");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sm7d_tbpd {
  d: path("M20.935 21.945a.64.64 0 0 1 .913.02a93 93 0 0 0 1.82 1.886a.05.05 0 0 0 .085-.04l-.089-.926a.67.67 0 0 1 1.32-.21l.692 3.103q.088.294.089.615c0 1.065-.766 1.95-1.777 2.136c-.697.2-1.485-.121-1.794-.308l-2.78-1.689a.632.632 0 0 1 .626-1.098l-.596-.429a.621.621 0 1 1 .737-.999l.186.141l-.656-.52a.648.648 0 1 1 .837-.988l1.156 1.045l-.79-.853a.636.636 0 0 1 .02-.886");
}

.sq95r4vix {
  stop-color: var(--svg-color--a476f3, #A476F3);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t0enfxe1b {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m17.624 6.3l-1.432.552a.736.736 0 1 1-.4-1.41l2.445-.458c1.448-.271 2.202 1.105 2.355 1.595a3.34 3.34 0 0 0-2.968-.28");
}

.t4qc1db7w {
  stop-color: var(--svg-color--8b6c69, #8B6C69);
}

.taon73bed {
  fill: var(--svg-color--642fc5, #642FC5);
  d: path("M25.578 29.842c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.tce23o4qc {
  stop-color: var(--svg-color--a980f3, #A980F3);
  stop-opacity: 0;
}

.tkcxzncwj {
  stop-color: var(--svg-color--7f5acc, #7F5ACC);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tuzs6gnlm {
  d: path("M17.196 8.619c1.041-.327 2.4.235 2.4 1.625c-.671-.375-2.007-.52-2.482-.375z");
}

.ty9b1kbqd {
  stop-color: var(--svg-color--70434c, #70434C);
}

.uny69rbro {
  stop-color: var(--svg-color--38aa6f, #38AA6F);
}

.uoxk537no {
  d: path("m13.45 23.756l.07-.038c.504-.273.896-.5 1.455-.825l.495-.286l.04-.023l.69-.397l-.005-.007a4.253 4.253 0 0 1 5.603 1.673c1.18 2.04.48 4.64-1.56 5.8l-.3.18h-5.585c.103-.705.152-1.978-.054-3.12c-.11-.613-.72-.997-1.341-.997h-1.193q.071-.167.156-.329a4.8 4.8 0 0 1 .8-1.066q.326-.316.73-.565");
}

.up7b_htug {
  stop-color: var(--svg-color--ab84ee, #AB84EE);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uuy1468ob {
  stop-color: var(--svg-color--916d6c, #916D6C);
  stop-opacity: 0;
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vrjrrpcnz {
  stop-color: var(--svg-color--349373, #349373);
}

.vx130hb0m {
  stop-color: var(--svg-color--8e5d56, #8E5D56);
}

.w-wd4mb8i {
  stop-color: var(--svg-color--53ffa2, #53FFA2);
}

.wbn_mm1xd {
  d: path("M13.767 3.095c-1.234-.04-2.076 1.346-2.116 1.81c1.8 3.52 4.545 2.794 7.236 1.972c1.61-.492 1.93.227 2.139.565c-.775-4.134-4.42-4.254-7.228-4.346z");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.xclicpbbr {
  d: path("M23.729 11.237a3.5 3.5 0 0 0 .058-1.563a3.5 3.5 0 0 0-.539-1.32h.006a3.4 3.4 0 0 0-.395-.485l-.003-.002a3.5 3.5 0 0 1-.9-1.759l-.002-.01a3.52 3.52 0 0 0-4.101-2.821a.57.57 0 0 1-.523-.155a3.51 3.51 0 0 0-3.077-.921a3.51 3.51 0 0 0-2.534 1.973a.6.6 0 0 1-.43.334l-.09.017a3.52 3.52 0 0 0-2.712 4.098l.002.01c.124.66.055 1.344-.202 1.965l-.001.004a3.54 3.54 0 0 0-.211 2.018a3.6 3.6 0 0 0 .62 1.436a.55.55 0 0 1 .09.479a3.5 3.5 0 0 0-.062 1.542a3.43 3.43 0 0 0 4.001 2.751l8.978-1.683a3.43 3.43 0 0 0 2.733-4.014a3.5 3.5 0 0 0-.616-1.415a.55.55 0 0 1-.09-.479m-13.353-.404l-.013.003l1.718 2.24c.682 2.922 1.274-.238 4.068-.762c2.795-.524 4.629 2.526 4.205-.444l.559-3.583c-.302-1.298-1.263-1.213-1.451-1.178l-3.369.632a4.1 4.1 0 0 1-3.666-1.133a.28.28 0 0 0-.473.144l-.048.22a2.46 2.46 0 0 1-1 1.53q-.024.014-.05.032l-.05.032c-.223.175-.73.67-.564 1.67l.071.32z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xjvfic_gd {
  stop-color: var(--svg-color--309972, #309972);
  stop-opacity: 0;
}

.y9owwpbix {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
  stop-opacity: 0;
}

.yasfqbb-e {
  stop-color: var(--svg-color--a673ff, #A673FF);
  stop-opacity: 0;
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yit44gm3t {
  stop-color: var(--svg-color--9165d2, #9165D2);
  stop-opacity: 0;
}

.ym__citvk {
  stop-color: var(--svg-color--936d5c, #936D5C);
}

.yxwh0zb6l {
  d: path("M11.264 13.21a1.146 1.146 0 0 0 .912-1.34a1.146 1.146 0 0 0-1.336-.918a1.146 1.146 0 0 0-.912 1.339a1.146 1.146 0 0 0 1.336.918");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z8z8xbc2c {
  fill: var(--svg-color--7d5751, #7D5751);
  d: path("M14.318 29.841h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.zjg6tabva {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m21.48 22.237l2.11 2.14");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zqd5umbnr {
  d: path("M8.73 25.569h2.453c.425-.689 1.037-1.514 1.36-1.84a7 7 0 0 0-.532-1.664c-1.125.974-2.656 2.742-3.28 3.504");
}

</style>
