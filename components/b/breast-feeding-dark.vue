<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#in7uHXd)" class="d2kvgvbvc"><path fill="url(#ic2PxpX)" class="ircz7pywi"/><path fill="url(#ijSlzje)" class="ircz7pywi"/><path fill="url(#iDABSQc)" class="ircz7pywi"/><path fill="url(#iCPltfd)" class="ircz7pywi"/><path fill="url(#iyhfMmd)" class="ircz7pywi"/><path fill="url(#iGgZVHk)" class="ircz7pywi"/><path fill="url(#iSjnMkb)" class="ircz7pywi"/><path fill="url(#igLhXRc)" class="ircz7pywi"/><path fill="url(#i1D6Wxb)" class="ircz7pywi"/><path fill="url(#iT9bShc)" class="ircz7pywi"/><path fill="url(#iiBOvNe)" class="ircz7pywi"/><path fill="url(#itk8FIe)" class="ircz7pywi"/></g><path class="yx79t1bkw"/><path fill="url(#ibWhi8b)" class="s1cf9tber"/><g filter="url(#izBfGhd)"><path fill="url(#idheORs)" class="colo4gb9j"/><path fill="url(#i9azUNi)" class="colo4gb9j"/><path fill="url(#ipikEwb)" class="colo4gb9j"/></g><path fill="url(#imTFoYd)" class="imbi5bytp"/><path fill="url(#ikm7kQF)" class="imbi5bytp"/><path fill="url(#i4T8mJc)" class="imbi5bytp"/><g filter="url(#iKFeRAb)"><path fill="url(#iM3Riyd)" class="r-z89tihi"/><path fill="url(#iyz6Q8d)" class="r-z89tihi"/><path fill="url(#i7EzqAK)" class="r-z89tihi"/><path fill="url(#itULX2c)" class="r-z89tihi"/></g><g filter="url(#ieE1PJc)"><path fill="url(#iWCkoMe)" class="q-aaiix-z"/></g><g filter="url(#iLHiBkb)"><path stroke="url(#ivQyXSb)" class="f1ve1bkev"/></g><g filter="url(#ir3XSPc)"><path fill="url(#iYh1Uwc)" class="la9dsgkmp"/></g><g filter="url(#i9IRb4c)"><path stroke="url(#i7IYe4t)" class="kps_ioocu"/></g><g filter="url(#i6xjVfc)"><path fill="url(#i801bud)" class="qc_w1fbvk"/><path fill="url(#istjXed)" class="qc_w1fbvk"/></g><g filter="url(#i5J9wod)"><path class="m_x1ijbvd"/><path fill="url(#iAQ8lBb)" class="hkznzswfh"/><path fill="url(#iGEvN2F)" class="hkznzswfh"/><path fill="url(#i7wwAhA)" class="hkznzswfh"/></g><path fill="url(#ii26aKh)" class="z9ycn4bpc"/><path fill="url(#iBQGkId)" class="z9ycn4bpc"/><path fill="url(#iQXsSld)" class="k2mzbyb_j"/><path fill="url(#iNHKRhc)" class="k2mzbyb_j"/><g filter="url(#i5wTx2I)"><path fill="url(#iPGW2bd)" class="gwbt5yb7w"/></g><path fill="url(#iy69tDG)" class="gwbt5yb7w"/><g filter="url(#i8rU5Lb)"><path fill="url(#i6PldEd)" class="k-jxi0b3h"/></g><g filter="url(#i8EGs9d)"><path stroke="url(#i4bh8Rb)" class="u9ngu4jqg"/></g><g filter="url(#iQDk9CJ)"><path stroke="url(#iHuRQJi)" class="iniincbch"/></g><g filter="url(#imyCrhb)"><path stroke="url(#iPlX90d)" class="bxwbfndky"/></g><g filter="url(#ixbgJbe)"><path stroke="url(#i3KFRnm)" class="uy76obb3m"/></g><g filter="url(#iZeXKpb)"><path stroke="url(#iBftRrQ)" class="i4h173hua"/></g><g filter="url(#iwdpNoO)"><path fill="url(#iX8z5Kd)" class="xa6h1kbgj"/></g><g filter="url(#iQ46Qnc)"><path fill="url(#ieisQMd)" class="ok4rdjbzr"/><path fill="url(#iCyrlSc)" class="ok4rdjbzr"/></g><g filter="url(#i9PGVte)"><path class="rmgxvebia"/><path fill="url(#ibTc5Rc)" class="wxc0gnbwp"/></g><g filter="url(#iyrbf4b)"><path class="x2de6rb3o"/><path fill="url(#iDHhV7c)" class="ksxjjbc2z"/></g><g filter="url(#iabiMJe)"><path fill="url(#iyxsHlc)" class="jgemidcqa"/><path fill="url(#iRBOEhd)" class="jgemidcqa"/><path fill="url(#ihFwQCF)" class="jgemidcqa"/><path fill="url(#itfcuUd)" class="jgemidcqa"/><path fill="url(#iT9yWMb)" class="jgemidcqa"/><path fill="url(#i6YQKXJ)" class="jgemidcqa"/></g><path fill="url(#iSEW3Lc)" class="jgemidcqa"/><path fill="url(#iP5JKHe)" class="jgemidcqa"/><path fill="url(#iOHIAfb)" class="jgemidcqa"/><g filter="url(#iheQMmf)"><path class="fx7q6qb1q"/></g><g filter="url(#irqvUpe)"><path class="wmzvvebap"/><path fill="url(#iHK6EQd)" class="qv5odnbzx"/><path fill="url(#iw54Efb)" class="qv5odnbzx"/><path fill="url(#ijScA3d)" class="qv5odnbzx"/><path fill="url(#i1Y58qe)" class="qv5odnbzx"/></g><g filter="url(#igM5EWb)"><path stroke="url(#iYFRVKe)" class="k8p3hxk8k"/></g><path class="j8lvqy2yf"/><g filter="url(#inlCAXc)"><path class="qjtrs2fcd"/><path fill="url(#iyvibgO)" class="xxzrunbeh"/></g><g filter="url(#inUldAb)"><path class="i480ycc_q"/><path fill="url(#iHNs4qe)" class="odbm06j0h"/><path fill="url(#iVv7Icd)" class="odbm06j0h"/></g><g filter="url(#iQYmH3b)"><path stroke="url(#i8MvZMk)" class="gbg89sblw"/></g><g filter="url(#icmzfcd)"><path class="by50_jblf"/></g><path fill="url(#iz8Lo6d)" class="m9pmqacgd"/><path fill="url(#iwkfH7d)" class="z0z_2hbrb"/><g filter="url(#iKyjeMb)" class="tryqaac1t"><path stroke="url(#ipBkasc)" class="zxae2smgf"/><path stroke="url(#iFbBY6c)" class="zxae2smgf"/></g><g filter="url(#inhQjKe)" class="tryqaac1t"><path stroke="url(#iWuNHzc)" class="p81z8obsf"/><path stroke="url(#i4cB8zd)" class="p81z8obsf"/></g><g filter="url(#iLc4cJf)"><path fill="url(#ivhbEac)" class="rv7q59vgs"/></g><g filter="url(#iOvNxDc)"><path fill="url(#iYu2Cvb)" class="nelidqblo"/></g><g filter="url(#iZrleoe)"><path clip-rule="evenodd" class="jxfn-fkht"/></g><g filter="url(#ilIcDEP)"><path class="nwswa4bip"/></g><g filter="url(#icWvAqb)"><path class="m2w648t-a"/></g><g filter="url(#ibVQg5d)"><path class="j75829juo"/></g><g filter="url(#iMxAOgd)"><path stroke="url(#i7qjTNB)" class="rwhi2406o"/></g><defs><radialGradient id="ijSlzje" cx="0" cy="0" r="1" gradientTransform="matrix(.11974 4.92003 -6.14612 .14959 16.028 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iDABSQc" cx="0" cy="0" r="1" gradientTransform="rotate(137.071 3.63 9.997)scale(3.72136 4.88957)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iCPltfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09803 2.02467 -1.55466 -.84313 10.847 12.439)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iyhfMmd" cx="0" cy="0" r="1" gradientTransform="rotate(112.496 2.08 8.781)scale(2.64871 1.86578)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iGgZVHk" cx="0" cy="0" r="1" gradientTransform="matrix(1.88756 2.53586 -3.52015 2.62021 10.87 3.465)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iSjnMkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28426 1.76342 -2.46436 -1.79474 21.104 4.108)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="igLhXRc" cx="0" cy="0" r="1" gradientTransform="rotate(154.846 10.832 7.273)scale(2.05481 4.28515)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i1D6Wxb" cx="0" cy="0" r="1" gradientTransform="rotate(157.03 10.512 8.887)scale(3.10612 3.95674)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iT9bShc" cx="0" cy="0" r="1" gradientTransform="rotate(-117.777 12.349 -2.582)scale(2.99681 2.37031)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iiBOvNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.61612 -.08316 .13474 2.61859 9.29 11.482)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="itk8FIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45908 3.09067 -2.849 -.42318 9.317 8.131)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="ibWhi8b" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 1.9893 19.511 29.545)" gradientUnits="userSpaceOnUse"><stop class="n2a634bwb"/><stop offset="1" class="y9owwpbix"/></radialGradient><radialGradient id="idheORs" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50378 0 0 -5.6875 21.761 18.769)" gradientUnits="userSpaceOnUse"><stop class="qmkf_qbpe"/><stop offset="1" class="u_pi4nbrf"/></radialGradient><radialGradient id="i9azUNi" cx="0" cy="0" r="1" gradientTransform="rotate(-154.983 12.424 8.828)scale(2.5864 3.5607)" gradientUnits="userSpaceOnUse"><stop class="ktc3a-h9z"/><stop offset="1" class="umbbe5bjg"/></radialGradient><radialGradient id="ipikEwb" cx="0" cy="0" r="1" gradientTransform="rotate(68.199 -3.522 20.454)scale(2.27187 4.46829)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="g24_b6jej"/><stop offset="1" class="yczry_bxo"/></radialGradient><radialGradient id="ikm7kQF" cx="0" cy="0" r="1" gradientTransform="matrix(2.79688 2.04686 -1.95763 2.67496 23.418 26.987)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tkcxzncwj"/><stop offset="1" class="mqicc-u0l"/></radialGradient><radialGradient id="i4T8mJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.3125 -2.12008 2.12008 22.01 27.425)" gradientUnits="userSpaceOnUse"><stop class="c14jvicyx"/><stop offset="1" class="i8x7p37cq"/></radialGradient><radialGradient id="iyz6Q8d" cx="0" cy="0" r="1" gradientTransform="rotate(126.08 3.22 11.935)scale(4.98797 9.68383)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="n7fe64b-m"/><stop offset="1" class="o3yqmrbrg"/></radialGradient><radialGradient id="i7EzqAK" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45313 -.6875 0 13.87 27.925)" gradientUnits="userSpaceOnUse"><stop class="la4e9obft"/><stop offset="1" class="sq95r4vix"/></radialGradient><radialGradient id="itULX2c" cx="0" cy="0" r="1" gradientTransform="rotate(-117.519 14.52 6.976)scale(1.35267 2.95016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="kc6luf8ah"/><stop offset="1" class="yit44gm3t"/></radialGradient><radialGradient id="iWCkoMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 -1.6057 .88152 .74629 11.761 25.347)" gradientUnits="userSpaceOnUse"><stop class="c_e6lvb0e"/><stop offset="1" class="bzrv_p78g"/></radialGradient><radialGradient id="ivQyXSb" cx="0" cy="0" r="1" gradientTransform="rotate(-162.16 15.514 11.871)scale(.71402 1.53504)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></radialGradient><radialGradient id="istjXed" cx="0" cy="0" r="1" gradientTransform="rotate(163.67 9.116 15.303)scale(5.1125 7.55864)" gradientUnits="userSpaceOnUse"><stop class="khg6a5-nz"/><stop offset="1" class="jyzijgb5l"/></radialGradient><radialGradient id="iAQ8lBb" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 -1.0625 .82137 1.8964 14.8 30.344)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="boldgwb7d"/><stop offset="1" class="mrac7ieme"/></radialGradient><radialGradient id="iGEvN2F" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .36719 -.26111 -.32778 16.792 25.954)" gradientUnits="userSpaceOnUse"><stop class="m4iiy9b5x"/><stop offset="1" class="c9by_kflp"/></radialGradient><radialGradient id="i7wwAhA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13282 -.44531 .29187 -.74248 15.987 27.797)" gradientUnits="userSpaceOnUse"><stop class="m85hxmbfx"/><stop offset="1" class="rctukzbng"/></radialGradient><radialGradient id="ii26aKh" cx="0" cy="0" r="1" gradientTransform="rotate(154.496 10.837 13.615)scale(3.77401 4.40797)" gradientUnits="userSpaceOnUse"><stop class="w-wd4mb8i"/><stop offset="1" class="jswq_j2dq"/></radialGradient><radialGradient id="iBQGkId" cx="0" cy="0" r="1" gradientTransform="rotate(42.983 -15.503 40.437)scale(5.22527)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="i54m18vgp"/><stop offset=".995" class="nybv-x_bu"/></radialGradient><radialGradient id="iNHKRhc" cx="0" cy="0" r="1" gradientTransform="matrix(.39062 -3.01563 4.79304 .62086 19.418 24.019)" gradientUnits="userSpaceOnUse"><stop class="l99uylilx"/><stop offset="1" class="xjvfic_gd"/></radialGradient><radialGradient id="iPGW2bd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -3.96872 3.86667 -4.32342 24.355 27.424)" gradientUnits="userSpaceOnUse"><stop class="x-f0kqu0p"/><stop offset="1" class="ce95enlhz"/></radialGradient><radialGradient id="ieisQMd" cx="0" cy="0" r="1" gradientTransform="rotate(-33.378 28.805 -28.217)scale(2.92595 3.57245)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iCyrlSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.51356 .561 -.1586 .4279 21.012 8.78)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="ibTc5Rc" cx="0" cy="0" r="1" gradientTransform="matrix(1.57756 -.36966 .28897 1.23322 20.593 10.789)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iDHhV7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27581 .20056 -.15822 -1.00646 11.067 12.164)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iyxsHlc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.37709 4.25122 -5.69018 -8.53561 18.865 10.357)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="zpqiekbmq"/><stop offset=".868" class="v2xpqhbrh"/></radialGradient><radialGradient id="iRBOEhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99157 1.36468 -.95034 -1.3869 17.914 11.42)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ihFwQCF" cx="0" cy="0" r="1" gradientTransform="matrix(.55718 -3.85322 4.88903 .70696 14.665 18.365)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="itfcuUd" cx="0" cy="0" r="1" gradientTransform="rotate(87.793 2.551 13.996)scale(7.32754 7.36678)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iT9yWMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09132 6.94239 -6.97956 1.09716 15.63 11.288)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="i6YQKXJ" cx="0" cy="0" r="1" gradientTransform="matrix(-7.07528 2.58037 -4.4426 -12.18147 18.044 12.361)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iSEW3Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35877 .2136 -1.0712 -6.8141 21.407 11.115)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iP5JKHe" cx="0" cy="0" r="1" gradientTransform="rotate(130.346 6.813 12.614)scale(2.58257 1.7309)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iOHIAfb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62498 2.15626 -1.50234 -1.82891 17.706 7.063)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="k7xyk1boq"/><stop offset="1" class="zpi5yt9_e"/></radialGradient><radialGradient id="iHK6EQd" cx="0" cy="0" r="1" gradientTransform="rotate(-111.497 12.848 .552)scale(2.24108 .69068)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="i1Y58qe" cx="0" cy="0" r="1" gradientTransform="matrix(-.82396 .12953 -.03621 -.23036 16.825 12.971)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iyvibgO" cx="0" cy="0" r="1" gradientTransform="matrix(.87628 -3.12271 1.5975 .44828 9.498 9.467)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iHNs4qe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50288 4.99352 -8.16413 -2.45712 16.635 2.704)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iVv7Icd" cx="0" cy="0" r="1" gradientTransform="matrix(.00484 1.48032 -3.18484 .01042 14.898 3.377)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iFbBY6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 19.074 10.458)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><radialGradient id="i4cB8zd" cx="0" cy="0" r="1" gradientTransform="matrix(-.12314 .21283 -.20557 -.11894 14.607 11.211)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><filter id="in7uHXd" width="16.759" height="17.426" x="7.947" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="izBfGhd" width="12.09" height="8.809" x="15.158" y="16.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.172549 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="iKFeRAb" width="12.107" height="12.935" x="4.292" y="16.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="ieE1PJc" width="3.547" height="2.605" x="10.246" y="23.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".25"/></filter><filter id="iLHiBkb" width="1.338" height="3.484" x="25.65" y="25.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".05"/></filter><filter id="ir3XSPc" width="8.034" height="4.188" x="6.668" y="25.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".5"/></filter><filter id="i9IRb4c" width="1.907" height="4.376" x="11.205" y="20.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".125"/></filter><filter id="i6xjVfc" width="10.856" height="8.359" x="11.765" y="21.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.682353 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="i5J9wod" width="6.652" height="4.473" x="14.118" y="25.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.145098 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="i5wTx2I" width="6.654" height="7.23" x="19.111" y="21.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.129412 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="i8rU5Lb" width="5.813" height="5.503" x="7.73" y="20.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".5"/></filter><filter id="i8EGs9d" width="3.309" height="3.341" x="20.88" y="21.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".2"/></filter><filter id="iQDk9CJ" width="2.013" height="4.911" x="23.891" y="21.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".2"/></filter><filter id="imyCrhb" width="3.294" height="2.926" x="19.598" y="22.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".2"/></filter><filter id="ixbgJbe" width="3.106" height="2.411" x="19.224" y="23.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".2"/></filter><filter id="iZeXKpb" width="2.356" height="1.81" x="19.208" y="24.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".2"/></filter><filter id="iwdpNoO" width="3.594" height="3.444" x="9.256" y="10.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="iQ46Qnc" width="3.444" height="3.694" x="19.312" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="i9PGVte" width="3.299" height="3.299" x="19.385" y="8.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".25"/></filter><filter id="iyrbf4b" width="2.799" height="2.799" x="9.599" y="10.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".125"/></filter><filter id="iabiMJe" width="11.225" height="11.283" x="10.218" y="6.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="iheQMmf" width="2.998" height="3.924" x="14.606" y="10.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".25"/></filter><filter id="irqvUpe" width="2.498" height="3.414" x="15.005" y="10.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".125"/></filter><filter id="igM5EWb" width="3.894" height="1.866" x="14.581" y="13.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".05"/></filter><filter id="inlCAXc" width="4.401" height="5.375" x="8.477" y="4.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/><feGaussianBlur result="effect2_foregroundBlur_4002_3505" stdDeviation=".25"/></filter><filter id="inUldAb" width="9.893" height="5.061" x="11.518" y="3.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/><feGaussianBlur result="effect2_foregroundBlur_4002_3505" stdDeviation=".125"/></filter><filter id="iQYmH3b" width="1.46" height="2.317" x="11.488" y="4.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".1"/></filter><filter id="icmzfcd" width="6.915" height="3.379" x="14.587" y="4.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".375"/></filter><filter id="iKyjeMb" width="2.582" height="1.236" x="16.832" y="10.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".075"/></filter><filter id="inhQjKe" width="2.582" height="1.236" x="12.365" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".075"/></filter><filter id="iLc4cJf" width="3.872" height="2.503" x="11.644" y="8.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".3"/></filter><filter id="iOvNxDc" width="3.682" height="2.825" x="16.407" y="8.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".3"/></filter><filter id="iZrleoe" width="2.642" height=".959" x="17.242" y="8.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="ilIcDEP" width="2.413" height=".814" x="17.288" y="8.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".1"/></filter><filter id="icWvAqb" width="2.535" height="1.4" x="11.569" y="8.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3505"/></filter><filter id="ibVQg5d" width="2.299" height="1.243" x="11.581" y="8.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".1"/></filter><filter id="iMxAOgd" width="5.798" height=".972" x="14.85" y="28.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3505" stdDeviation=".15"/></filter><linearGradient id="ic2PxpX" x1="19.738" x2="14.638" y1="3.27" y2="17.726" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="imTFoYd" x1="26.793" x2="24.491" y1="24.706" y2="29.545" gradientUnits="userSpaceOnUse"><stop class="up7b_htug"/><stop offset="1" class="bvctw1bkc"/></linearGradient><linearGradient id="iM3Riyd" x1="15.261" x2="6.793" y1="18.862" y2="29.545" gradientUnits="userSpaceOnUse"><stop class="eoa632ltp"/><stop offset="1" class="rlw3b4b7i"/></linearGradient><linearGradient id="iYh1Uwc" x1="13.48" x2="7.928" y1="28.549" y2="28.525" gradientUnits="userSpaceOnUse"><stop class="lzdnytbwv"/><stop offset="1" class="yasfqbb-e"/></linearGradient><linearGradient id="i7IYe4t" x1="13.155" x2="13.104" y1="23.938" y2="20.988" gradientUnits="userSpaceOnUse"><stop class="qtbzeirls"/><stop offset="1" class="tce23o4qc"/></linearGradient><linearGradient id="i801bud" x1="21.355" x2="14.293" y1="27.269" y2="26.831" gradientUnits="userSpaceOnUse"><stop class="vrjrrpcnz"/><stop offset="1" class="qarzv5b-l"/></linearGradient><linearGradient id="iQXsSld" x1="21.668" x2="20.168" y1="18.266" y2="22.863" gradientUnits="userSpaceOnUse"><stop class="rm6lemo-n"/><stop offset=".635" class="uny69rbro"/></linearGradient><linearGradient id="iy69tDG" x1="25.558" x2="25.003" y1="24.881" y2="25" gradientUnits="userSpaceOnUse"><stop offset=".049" class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></linearGradient><linearGradient id="i6PldEd" x1="10.636" x2="13.293" y1="25.272" y2="22.025" gradientUnits="userSpaceOnUse"><stop class="lk8w5cclk"/><stop offset="1" class="qrasocbfu"/></linearGradient><linearGradient id="i4bh8Rb" x1="21.965" x2="24.246" y1="22.144" y2="24.44" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="nszro3xnj"/></linearGradient><linearGradient id="iHuRQJi" x1="24.945" x2="27.226" y1="22.764" y2="25.061" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="nszro3xnj"/></linearGradient><linearGradient id="iPlX90d" x1="20.679" x2="23.118" y1="22.821" y2="25.557" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="nszro3xnj"/></linearGradient><linearGradient id="i3KFRnm" x1="20.777" x2="22.09" y1="24.375" y2="26.261" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="nszro3xnj"/></linearGradient><linearGradient id="iBftRrQ" x1="20.386" x2="20.997" y1="25.686" y2="26.743" gradientUnits="userSpaceOnUse"><stop offset=".076" class="l20_z6baj"/><stop offset="1" class="nszro3xnj"/></linearGradient><linearGradient id="iX8z5Kd" x1="9.291" x2="12.42" y1="12.538" y2="12.047" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iw54Efb" x1="15.233" x2="16.226" y1="13.071" y2="12.915" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ijScA3d" x1="16.358" x2="16.257" y1="13.76" y2="13.115" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iYFRVKe" x1="15.542" x2="15.911" y1="15.595" y2="14.765" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i8MvZMk" x1="11.845" x2="12.632" y1="5.327" y2="6.583" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iz8Lo6d" x1="18.965" x2="17.402" y1="10.819" y2="11.644" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="iwkfH7d" x1="14.466" x2="12.899" y1="11.578" y2="12.399" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="ipBkasc" x1="16.934" x2="19.262" y1="10.918" y2="11.079" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iWuNHzc" x1="12.466" x2="14.795" y1="11.671" y2="11.832" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="ivhbEac" x1="14.471" x2="12.416" y1="10.493" y2="10.2" gradientUnits="userSpaceOnUse"><stop offset=".329" class="t4dyfpxnt"/><stop offset="1" class="hkxvz0u3y"/></linearGradient><linearGradient id="iYu2Cvb" x1="19.104" x2="15.63" y1="9.975" y2="8.821" gradientUnits="userSpaceOnUse"><stop offset=".329" class="sexb1etbn"/><stop offset="1" class="ct55v9jwv"/></linearGradient><linearGradient id="i7qjTNB" x1="19.922" x2="15.689" y1="28.648" y2="28.591" gradientUnits="userSpaceOnUse"><stop class="bid6u6m3r"/><stop offset="1" class="qdkymkf8x"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:breast-feeding-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bid6u6m3r {
  stop-color: var(--svg-color--584748, #584748);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.boldgwb7d {
  stop-color: var(--svg-color--5e4c4c, #5E4C4C);
}

.bvctw1bkc {
  stop-color: var(--svg-color--9c69f1, #9C69F1);
}

.bxwbfndky {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m20.198 22.657l2.093 1.727");
}

.by50_jblf {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.78 6.58l-1.463.514a.736.736 0 1 1-.359-1.422l2.475-.39c1.463-.23 2.18 1.17 2.318 1.664a3.37 3.37 0 0 0-2.97-.366");
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

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c9by_kflp {
  stop-color: var(--svg-color--615252, #615252);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ce95enlhz {
  stop-color: var(--svg-color--452933, #452933);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.colo4gb9j {
  d: path("M17.348 16.005c-.72 0-1.42.08-2.09.22v2.42c0 3.48 2.93 6.25 6.41 6.06l5.58-.31c-.7-4.74-4.86-8.39-9.9-8.39");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.ct55v9jwv {
  stop-color: var(--svg-color--472b2b, #472B2B);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.eoa632ltp {
  stop-color: var(--svg-color--9165d0, #9165D0);
}

.f1ve1bkev {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.613 26.105c.273.906.367 2.164-.797 3.18");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fx7q6qb1q {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.553 11.337l-.44 1.91a.577.577 0 0 0 .666.654l.831-.13a.58.58 0 0 0 .434-.827l-.844-1.709c-.183-.379-.584-.316-.647.102");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g24_b6jej {
  stop-color: var(--svg-color--200d0e, #200D0E);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gbg89sblw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.788 4.964c.065.253.44 1.184.86 1.717");
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gwbt5yb7w {
  d: path("M20.935 21.649a.64.64 0 0 1 .913.018c.447.475 1.16 1.226 1.82 1.887a.05.05 0 0 0 .085-.04l-.089-.926a.67.67 0 0 1 1.32-.21l.692 3.103q.088.294.089.615c0 1.065-.766 1.95-1.777 2.136c-.697.2-1.485-.121-1.794-.308l-2.78-1.689a.632.632 0 0 1 .626-1.098l-.596-.428a.621.621 0 1 1 .737-1l.186.141l-.656-.52a.648.648 0 1 1 .837-.988l1.156 1.045l-.79-.853a.636.636 0 0 1 .02-.886");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hkxvz0u3y {
  stop-color: var(--svg-color--351e25, #351E25);
  stop-opacity: 0;
}

.hkznzswfh {
  d: path("M14.318 29.545h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i480ycc_q {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M13.999 3.264c-1.239-.077-2.126 1.287-2.18 1.75c1.7 3.573 4.481 2.925 7.21 2.18c1.634-.446 1.933.283 2.132.627c-.653-4.158-4.311-4.382-7.13-4.556z");
}

.i4h173hua {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.808 25.472l1.157.61");
}

.i54m18vgp {
  stop-color: var(--svg-color--51e398, #51E398);
  stop-opacity: 0;
}

.i8x7p37cq {
  stop-color: var(--svg-color--603eb7, #603EB7);
  stop-opacity: 0;
}

.imbi5bytp {
  d: path("M27.515 27.05c-.013-.405-.165-2.417-.222-3.117l-2.825.18l-3.008 3.324c0 1.263.513 1.95.805 2.108h4.39c.97-.964.868-2.21.86-2.495");
}

.incjljb4q {
  stop-color: var(--svg-color--090c09, #090C09);
}

.iniincbch {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m24.49 22.37l.813 3.711");
}

.ircz7pywi {
  d: path("M23.762 11.696a3.46 3.46 0 0 0 .105-1.562a3.5 3.5 0 0 0-.5-1.336h.005a3.4 3.4 0 0 0-.383-.496l-.003-.003a3.47 3.47 0 0 1-.85-1.785l-.002-.01a3.53 3.53 0 0 0-4.036-2.94a.58.58 0 0 1-.52-.17a3.54 3.54 0 0 0-3.064-1.01a3.54 3.54 0 0 0-2.606 1.9a.6.6 0 0 1-.443.322l-.09.016a3.53 3.53 0 0 0-2.85 4.02l.002.011a3.47 3.47 0 0 1-.262 1.96l-.002.004a3.53 3.53 0 0 0 .307 3.467a.55.55 0 0 1 .075.482a3.5 3.5 0 0 0-.108 1.54a3.44 3.44 0 0 0 3.937 2.868l9.072-1.426a3.44 3.44 0 0 0 2.868-3.937a3.5 3.5 0 0 0-.577-1.434a.55.55 0 0 1-.075-.481m-13.405-.788l-.013.002l1.658 2.291c.596 2.942 1.287-.202 4.11-.646c2.825-.444 4.575 2.66 4.24-.323l.67-3.569c-.264-1.307-1.233-1.25-1.423-1.22l-3.404.536a4.13 4.13 0 0 1-3.65-1.24a.282.282 0 0 0-.48.131l-.054.22a2.47 2.47 0 0 1-1.052 1.502l-.051.03l-.05.03c-.23.169-.754.65-.618 1.656l.062.322z");
}

.izaac2bev {
  stop-color: var(--svg-color--6a5654, #6A5654);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j75829juo {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.58 9.2c-.354-.03-1.196.145-1.699.64");
}

.j8lvqy2yf {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.563 14.753a3.24 3.24 0 0 1-1.56-.128c-.161-.054-.294.142-.179.266a2.068 2.068 0 0 0 3.435-.54c.071-.159-.114-.3-.25-.198c-.4.3-.89.513-1.447.6");
}

.j9v6w1g-o {
  stop-color: var(--svg-color--0a0909, #0A0909);
}

.jgemidcqa {
  d: path("m10.344 10.91l.013-.001l-.055-.28l-.062-.32c-.136-1.007.388-1.488.617-1.656l.051-.03q.027-.019.05-.03a2.47 2.47 0 0 0 1.053-1.503l.055-.22a.282.282 0 0 1 .48-.13a4.13 4.13 0 0 0 3.649 1.24l3.404-.536c.19-.03 1.159-.087 1.422 1.22l.385 3.268c.336 2.983-1.665 5.337-4.49 5.78c-2.824.445-5.45-1.181-6.046-4.123z");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jswq_j2dq {
  stop-color: var(--svg-color--34e38b, #34E38B);
}

.jxfn-fkht {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.505 8.416l-.108.266za.287.287 0 0 1-.215.532l-.005-.002a1 1 0 0 0-.13-.043a3 3 0 0 0-.384-.085a2.4 2.4 0 0 0-1.149.08a.287.287 0 1 1-.186-.542a3 3 0 0 1 1.422-.106a3.5 3.5 0 0 1 .63.16l.012.004l.003.001z");
}

.jyzijgb5l {
  stop-color: var(--svg-color--248571, #248571);
  stop-opacity: 0;
}

.k-jxi0b3h {
  d: path("M8.73 25.272h2.453c.425-.689 1.037-1.514 1.36-1.84a7 7 0 0 0-.532-1.663c-1.125.973-2.656 2.741-3.28 3.503");
}

.k2mzbyb_j {
  d: path("M21.538 23.486a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.k7xyk1boq {
  stop-color: var(--svg-color--594947, #594947);
}

.k8p3hxk8k {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.563 14.753a3.24 3.24 0 0 1-1.56-.128c-.161-.054-.294.142-.179.266a2.068 2.068 0 0 0 3.435-.54c.071-.159-.114-.3-.25-.198c-.4.3-.89.513-1.447.6Z");
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

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.kps_ioocu {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.631 20.706c.344.636 1.031 2.281 1.031 3.781");
}

.ksxjjbc2z {
  d: path("M11.177 13.31a1.15 1.15 0 1 0-.357-2.27a1.15 1.15 0 0 0 .357 2.27");
}

.ktc3a-h9z {
  stop-color: var(--svg-color--3e2f2c, #3E2F2C);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l20_z6baj {
  stop-color: var(--svg-color--695857, #695857);
}

.l99uylilx {
  stop-color: var(--svg-color--309972, #309972);
}

.la4e9obft {
  stop-color: var(--svg-color--ac7ff8, #AC7FF8);
}

.la9dsgkmp {
  d: path("M7.668 26.705h6.034v2.188H7.668z");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lk8w5cclk {
  stop-color: var(--svg-color--a176df, #A176DF);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lzdnytbwv {
  stop-color: var(--svg-color--a673ff, #A673FF);
}

.m_x1ijbvd {
  fill: var(--svg-color--482d35, #482D35);
  d: path("M14.318 29.545h5.601c.47 0 .85-.38.85-.85c0-.545-.507-.957-1.05-.9c-1.243.13-2.714.11-3.596.067a.05.05 0 0 1-.028-.089l1.002-.802a.954.954 0 0 0-1.128-1.536l-1.651 1.11c.185 1.102.097 2.307 0 3");
}

.m-leh6bjs {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
}

.m2w648t-a {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.044 10.085l-.004.003a.287.287 0 0 1-.368-.44v-.001h.001l.003-.003l.01-.007a2 2 0 0 1 .143-.106a4 4 0 0 1 .407-.24a3 3 0 0 1 1.386-.336a.287.287 0 1 1-.01.574a2.4 2.4 0 0 0-1.119.276a3 3 0 0 0-.428.263q-.015.011-.02.017");
}

.m4iiy9b5x {
  stop-color: var(--svg-color--615252, #615252);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m85hxmbfx {
  stop-color: var(--svg-color--635252, #635252);
}

.m9pmqacgd {
  d: path("M19.036 10.228c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51s-.63-.03-.86-.23a.3.3 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.39");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
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

.mrac7ieme {
  stop-color: var(--svg-color--5e4c4c, #5E4C4C);
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

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nelidqblo {
  d: path("M17.088 8.698c1.4.01 2.275.819 2.401 1.624c-1.197-.582-2.007-.519-2.482-.374z");
}

.nszro3xnj {
  stop-color: var(--svg-color--695857, #695857);
  stop-opacity: 0;
}

.nwswa4bip {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.588 8.57c.328-.137 1.182-.229 1.813.088");
}

.nybv-x_bu {
  stop-color: var(--svg-color--51e398, #51E398);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o3yqmrbrg {
  stop-color: var(--svg-color--885ebc, #885EBC);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.odbm06j0h {
  d: path("M13.999 3.264c-1.239-.077-2.126 1.287-2.18 1.75c1.7 3.573 4.481 2.925 7.21 2.18c1.634-.446 1.933.283 2.132.627c-.653-4.158-4.311-4.382-7.13-4.556z");
}

.ok4rdjbzr {
  d: path("M21.302 12.299a1.722 1.722 0 1 0-.535-3.402a1.722 1.722 0 0 0 .535 3.402");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p81z8obsf {
  d: path("M12.615 11.581c.13.122.518.353 1.021.298c.505-.054.947-.543 1.06-.728");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.q-aaiix-z {
  d: path("M10.746 25.347h1.57l.977-1.594c-1.675-.139-2.396 1.005-2.547 1.594");
}

.qarzv5b-l {
  stop-color: var(--svg-color--37ba71, #37BA71);
}

.qc_w1fbvk {
  d: path("m13.45 23.459l.07-.038c.504-.273.896-.5 1.455-.824l.495-.287l.04-.023l.69-.397l-.005-.006c1.997-1.01 4.472-.3 5.603 1.672c1.18 2.04.48 4.64-1.56 5.8l-.3.18h-5.585c.103-.705.152-1.978-.054-3.12c-.11-.613-.72-.996-1.341-.996h-1.193q.071-.168.156-.33a4.8 4.8 0 0 1 .8-1.066q.326-.316.73-.565");
}

.qdkymkf8x {
  stop-color: var(--svg-color--584748, #584748);
  stop-opacity: 0;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qjtrs2fcd {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M9.577 5.912c.499-.728 1.63-.907 2.168-.894l.633 1.298c-.274 0-.497.133-.667.36c-.265 1.406-1.778 2.397-2.502 2.717c-.405-1.553-.28-2.535.368-3.481");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qmkf_qbpe {
  stop-color: var(--svg-color--533a36, #533A36);
}

.qrasocbfu {
  stop-color: var(--svg-color--a176df, #A176DF);
  stop-opacity: 0;
}

.qtbzeirls {
  stop-color: var(--svg-color--a980f3, #A980F3);
}

.qv5odnbzx {
  d: path("m15.54 11.19l-.28 1.885a.577.577 0 0 0 .668.653l.83-.13a.58.58 0 0 0 .435-.827l-.844-1.709c-.183-.379-.745-.29-.809.128");
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-z89tihi {
  d: path("M13.57 16.61c-3.353 1.353-6.48 5.4-8.312 7.957c-.71.853-1.718 2.66-.086 4.978h9.18c.104-.703.154-1.982-.053-3.129c-.11-.612-.72-.996-1.342-.996h-1.196c.102-.265.73-1.357 1.801-1.937c.505-.273.854-.562 1.413-.886l.495-.287l.73-.42a6.03 6.03 0 0 1-.942-3.245v-1.452a5.2 5.2 0 0 1-1.689-.583");
}

.rctukzbng {
  stop-color: var(--svg-color--492e36, #492E36);
  stop-opacity: 0;
}

.rlw3b4b7i {
  stop-color: var(--svg-color--9565e9, #9565E9);
}

.rm6lemo-n {
  stop-color: var(--svg-color--3db155, #3DB155);
}

.rmgxvebia {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M21.213 11.733a1.15 1.15 0 1 0-.357-2.27a1.15 1.15 0 0 0 .357 2.27");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rv7q59vgs {
  d: path("M12.244 9.633c1.375-.262 2.39.36 2.672 1.125c-1.287-.337-2.07-.117-2.508.118z");
}

.rwhi2406o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.3 28.648c.886.053 3.107.13 4.898 0");
}

.s1cf9tber {
  d: path("M25.578 29.545c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sexb1etbn {
  stop-color: var(--svg-color--472b2b, #472B2B);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sq95r4vix {
  stop-color: var(--svg-color--a476f3, #A476F3);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t4dyfpxnt {
  stop-color: var(--svg-color--351e25, #351E25);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
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

.u_pi4nbrf {
  stop-color: var(--svg-color--462f2d, #462F2D);
}

.u9ngu4jqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m21.48 21.94l2.11 2.141");
}

.umbbe5bjg {
  stop-color: var(--svg-color--3e2f2c, #3E2F2C);
  stop-opacity: 0;
}

.uny69rbro {
  stop-color: var(--svg-color--38aa6f, #38AA6F);
}

.up7b_htug {
  stop-color: var(--svg-color--ab84ee, #AB84EE);
}

.uy76obb3m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.824 23.948l1.906 1.211");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vrjrrpcnz {
  stop-color: var(--svg-color--349373, #349373);
}

.w-wd4mb8i {
  stop-color: var(--svg-color--53ffa2, #53FFA2);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wmzvvebap {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.54 11.19l-.28 1.885a.577.577 0 0 0 .668.653l.83-.13a.58.58 0 0 0 .435-.827l-.844-1.709c-.183-.379-.745-.29-.809.128");
}

.wxc0gnbwp {
  d: path("M21.213 11.733a1.15 1.15 0 1 0-.357-2.27a1.15 1.15 0 0 0 .357 2.27");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x-f0kqu0p {
  stop-color: var(--svg-color--4b3035, #4B3035);
}

.x2de6rb3o {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.177 13.31a1.15 1.15 0 1 0-.357-2.27a1.15 1.15 0 0 0 .357 2.27");
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xa6h1kbgj {
  d: path("M11.245 13.88a1.722 1.722 0 1 0-.535-3.402a1.722 1.722 0 0 0 .535 3.402");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xjvfic_gd {
  stop-color: var(--svg-color--309972, #309972);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xxzrunbeh {
  d: path("M9.577 5.912c.499-.728 1.63-.907 2.168-.894l.633 1.298c-.274 0-.497.133-.667.36c-.265 1.406-1.778 2.397-2.502 2.717c-.405-1.553-.28-2.535.368-3.481");
}

.y9owwpbix {
  stop-color: var(--svg-color--7b42dc, #7B42DC);
  stop-opacity: 0;
}

.yasfqbb-e {
  stop-color: var(--svg-color--a673ff, #A673FF);
  stop-opacity: 0;
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yczry_bxo {
  stop-color: var(--svg-color--36201e, #36201E);
  stop-opacity: 0;
}

.yit44gm3t {
  stop-color: var(--svg-color--9165d2, #9165D2);
  stop-opacity: 0;
}

.yx79t1bkw {
  fill: var(--svg-color--642fc5, #642FC5);
  d: path("M25.578 29.545c.98 0 1.77-.8 1.77-1.78l-.01-1.99c0-5.39-4.47-9.77-9.99-9.77c-5.51 0-9.99 4.37-9.99 9.77l-.15 3.77z");
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z0z_2hbrb {
  d: path("M14.537 10.981c-.08.01-.14.06-.19.13c-.16.26-.42.45-.74.51c-.31.06-.62-.03-.86-.22a.25.25 0 0 0-.22-.06c-.22.04-.3.32-.12.47c.35.29.82.43 1.3.34c.48-.08.87-.37 1.11-.77c.11-.19-.06-.43-.28-.4");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z9ycn4bpc {
  d: path("M23.408 26.706a4.3 4.3 0 0 0 0-8.6c-2.375 0-3.553 1.925-3.553 4.3s1.178 4.3 3.553 4.3");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zpi5yt9_e {
  stop-color: var(--svg-color--594947, #594947);
  stop-opacity: 0;
}

.zpqiekbmq {
  stop-color: var(--svg-color--543733, #543733);
}

.zxae2smgf {
  d: path("M17.082 10.828c.13.122.518.353 1.022.298s.947-.543 1.06-.728");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
