<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#il4J9vb)" class="rxk-dwzrq"/><path fill="url(#iqkzpyc)" class="rxk-dwzrq"/><path fill="url(#iT2RwTd)" class="rxk-dwzrq"/><path fill="url(#i6myPqe)" class="rxk-dwzrq"/><path fill="url(#iQagAqd)" class="rxk-dwzrq"/><path fill="url(#iixI3Ud)" class="rxk-dwzrq"/><g filter="url(#iXgyTbM)"><rect class="i-z_mxb9r"/></g><g filter="url(#iWwgzjc)"><path fill="url(#iSaXy3Z)" class="tl707w_ul"/></g><path fill="url(#i0gj9ZI)" class="xku4sqbgj"/><g filter="url(#ilV5MzD)"><path fill="url(#iU2c24d)" class="x1zr6fbzn"/></g><g filter="url(#iWbBTNl)"><path class="yy6-s-urx"/></g><g filter="url(#inIoIAc)"><path fill="url(#i3IWAje)" class="jke0lga3i"/></g><g filter="url(#io2mDfT)"><path clip-rule="evenodd" class="fz_ww44we"/></g><path stroke="url(#i4sgO4j)" class="es051ydzc"/><path stroke="url(#iPDa0fe)" class="k5b8itzkz"/><path fill="url(#ihgskQd)" class="nrvpd5bzi"/><g filter="url(#iXC3kxc)"><ellipse fill="url(#iOntEAd)" class="p9g7-b3yb"/></g><g filter="url(#iITWSek)"><path stroke="url(#iK1kjZb)" class="pc_dkijkh"/></g><g filter="url(#iFcSa1c)"><path stroke="url(#iKmFbSb)" class="g6jl-98yn"/></g><path stroke="url(#isXkd2K)" class="f765u6bgr"/><g filter="url(#iDufR4d)"><path class="e23i5rq_z"/></g><g filter="url(#iN8vBMc)"><ellipse transform="rotate(28.298 29.583 25.675)" class="unhzk0ucp"/></g><g filter="url(#iPkvtsG)"><path class="vre-o0bdf"/></g><path stroke="url(#i4qxCIe)" class="q__-mygvv"/><g filter="url(#iDPUkZd)"><path class="j55fys4vq"/></g><g filter="url(#iGdTCHd)"><ellipse transform="scale(-1 1)rotate(-19.477 66.028 31.392)" class="i4304abpf"/></g><path stroke="url(#iyJ6mYb)" class="ajctuwq7q"/><g filter="url(#ic13NNc)"><path class="acoz2ac6y"/></g><g filter="url(#iv8d8FJ)"><ellipse transform="scale(-1 1)rotate(-70.238 12.11 15.735)" class="i4304abpf"/></g><g filter="url(#inYlLtd)"><path fill="url(#iyQl01c)" class="xc1f0x17u"/></g><path stroke="url(#isbByFc)" class="eyds6abpk"/><g filter="url(#iwgMZ2b)"><path class="ix23knlks"/></g><path class="axgsn5hod"/><path fill="url(#iTsr2Jb)" class="t-5q0y2_j"/><g filter="url(#iU8fjcJ)"><path fill="url(#iVdnIrd)" class="w801yrbwk"/></g><g filter="url(#iHr7Lvc)"><path stroke="url(#itK0YGc)" class="z__dh0bsp"/></g><g filter="url(#ib7E7ib)"><path class="ugfrvi2um"/></g><g filter="url(#i7GRpCe)"><path class="ohi9f6bkt"/></g><g filter="url(#ijyxIAc)"><ellipse transform="scale(-1 1)rotate(-22.746 48.01 17.042)" class="i4304abpf"/></g><g filter="url(#ilLLr4d)"><ellipse transform="rotate(-22.745 29.648 19.888)" class="r17kpg5ls"/></g><g filter="url(#ivw0RRb)"><path fill="url(#i8ZQsnb)" clip-rule="evenodd" class="ozz659bsw"/></g><g filter="url(#i3DVQab)"><path fill="url(#itFLImS)" clip-rule="evenodd" class="cbhl4sbfp"/></g><path stroke="url(#iIL9jib)" class="o97vprbtp"/><path stroke="url(#i7Pge0b)" class="tdqfdg9vp"/><path fill="url(#iBoUD5c)" class="f67sxyb7x"/><path fill="url(#is3nY6R)" class="f67sxyb7x"/><path fill="url(#i1y3ZKb)" class="f67sxyb7x"/><g filter="url(#ilZgStc)"><path class="lh8j1tblm"/></g><g filter="url(#irpcI6O)"><circle transform="scale(-1.02441 .97498)rotate(45 -31.12 -.58)" class="o4p39sb-j"/></g><defs><filter id="iXgyTbM" width="5.727" height="6.698" x="3.596" y="19.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".75"/></filter><filter id="iWwgzjc" width="6.971" height="10.195" x="20.58" y="4.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="ilV5MzD" width="3.417" height="4.625" x="24.848" y="4.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".5"/></filter><filter id="iWbBTNl" width="8.95" height="10.729" x="2.765" y="3.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation="1"/></filter><filter id="inIoIAc" width="3.661" height="3.024" x="13.79" y="20.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="io2mDfT" width="2.317" height="4.85" x="14.495" y="21.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iXC3kxc" width="2.723" height="1.748" x="14.951" y="20.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".3"/></filter><filter id="iITWSek" width="6.005" height="4.013" x="23.727" y="19.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iFcSa1c" width="4.127" height="3.566" x="23.727" y="23.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iDufR4d" width="4.297" height="2.693" x="25.645" y="23.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iN8vBMc" width="1.36" height="1.34" x="28.903" y="25.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iPkvtsG" width="5.172" height="8.045" x="5.735" y="19.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".5"/></filter><filter id="iDPUkZd" width="5.102" height="3.119" x="2.184" y="23.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iGdTCHd" width="1.364" height="1.336" x="6.006" y="23.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="ic13NNc" width="5.114" height="3.094" x="2.253" y="19.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iv8d8FJ" width="1.336" height="1.364" x="6.125" y="21.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="inYlLtd" width="12.585" height="22.186" x="18.145" y="5.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation="2"/></filter><filter id="iwgMZ2b" width="5.105" height="3.113" x="24.959" y="19.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="iU8fjcJ" width="4.825" height="7.138" x="22.451" y="6.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".3"/></filter><filter id="iHr7Lvc" width="4.531" height="4.734" x="22.77" y="8.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".375"/></filter><filter id="ib7E7ib" width="4.469" height="6.908" x="4.765" y="6.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="i7GRpCe" width="1.15" height="6.337" x="4.69" y="6.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="ijyxIAc" width="1.363" height="1.337" x="2.174" y="19.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="ilLLr4d" width="1.363" height="1.337" x="28.967" y="19.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="ivw0RRb" width="4.763" height="3.463" x="18.047" y="17.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="i3DVQab" width="4.763" height="3.463" x="9.087" y="17.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation=".25"/></filter><filter id="ilZgStc" width="5.096" height="8.593" x="7.801" y="19.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation="1"/></filter><filter id="irpcI6O" width="5.214" height="5.156" x="7.151" y="18.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6905_5272" stdDeviation="1"/></filter><linearGradient id="il4J9vb" x1="7.907" x2="7.907" y1="1.35" y2="30.99" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ce9hnwylf"/><stop offset=".762" class="gq9h7lsld"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iqkzpyc" x1="8.831" x2="1.17" y1="12.033" y2="12.033" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="iT2RwTd" x1="26.791" x2="30.245" y1="12.033" y2="12.033" gradientUnits="userSpaceOnUse"><stop class="f6xjhkepg"/><stop offset=".993" class="wf44tw33q"/><stop offset="1" class="pt1exccow"/></linearGradient><linearGradient id="i6myPqe" x1="16.001" x2="16" y1="-1.595" y2="30.99" gradientUnits="userSpaceOnUse"><stop offset=".771" class="og2_-db3e"/><stop offset="1" class="iedbks3oi"/></linearGradient><linearGradient id="iQagAqd" x1="16" x2="16" y1="11.252" y2="32.475" gradientUnits="userSpaceOnUse"><stop offset=".854" class="stui2mbih"/><stop offset=".985" class="vc--wpv5i"/></linearGradient><linearGradient id="iSaXy3Z" x1="21.95" x2="28.207" y1="6.159" y2="13.002" gradientUnits="userSpaceOnUse"><stop class="x5la94b6u"/><stop offset="1" class="t246kz1qf"/></linearGradient><linearGradient id="i0gj9ZI" x1="10.645" x2="4.785" y1="9.924" y2="9.377" gradientUnits="userSpaceOnUse"><stop offset=".437" class="xon4_gnbq"/><stop offset="1" class="q5x9unbmu"/></linearGradient><linearGradient id="iU2c24d" x1="27.082" x2="26.486" y1="4.617" y2="6.958" gradientUnits="userSpaceOnUse"><stop offset=".286" class="j_4i6w0ng"/><stop offset="1" class="z84gitb5w"/></linearGradient><linearGradient id="i3IWAje" x1="15.793" x2="15.121" y1="22.489" y2="23.583" gradientUnits="userSpaceOnUse"><stop class="fd6xzxk0h"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="iPDa0fe" x1="18.183" x2="10.886" y1="24.447" y2="24.447" gradientUnits="userSpaceOnUse"><stop offset=".135" class="ovz69fb_x"/><stop offset=".276" class="hd0nr3bzk"/><stop offset=".411" class="ccr58nbuz"/></linearGradient><linearGradient id="iOntEAd" x1="17.246" x2="15.722" y1="20.879" y2="20.879" gradientUnits="userSpaceOnUse"><stop class="mno0o_bwq"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iK1kjZb" x1="24.332" x2="28.067" y1="22.543" y2="20.627" gradientUnits="userSpaceOnUse"><stop class="p3zloackg"/><stop offset="1" class="enakum12e"/></linearGradient><linearGradient id="iKmFbSb" x1="24.332" x2="28.067" y1="23.887" y2="25.803" gradientUnits="userSpaceOnUse"><stop offset=".286" class="mlskkyb7u"/><stop offset=".818" class="enakum12e"/></linearGradient><linearGradient id="isXkd2K" x1="25.116" x2="29.189" y1="24.017" y2="25.972" gradientUnits="userSpaceOnUse"><stop class="m-_zadbzh"/><stop offset=".365" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="i4qxCIe" x1="7.06" x2="2.988" y1="24.029" y2="25.984" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iyJ6mYb" x1="6.861" x2="2.77" y1="22.236" y2="20.319" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bc88ifbby"/><stop offset="1" class="ycz1ylytj"/></linearGradient><linearGradient id="iyQl01c" x1="23.395" x2="22.998" y1="10.146" y2="22.196" gradientUnits="userSpaceOnUse"><stop offset=".548" class="n5rbp-b1w"/><stop offset="1" class="z84gitb5w"/></linearGradient><linearGradient id="isbByFc" x1="25.332" x2="29.413" y1="22.252" y2="20.315" gradientUnits="userSpaceOnUse"><stop offset=".156" class="hr-u17bme"/><stop offset="1" class="vsmb0ub4v"/></linearGradient><linearGradient id="iTsr2Jb" x1="26.582" x2="25.332" y1="14.815" y2="11.346" gradientUnits="userSpaceOnUse"><stop class="f1yr_dbcd"/><stop offset="1" class="id4j66bti"/></linearGradient><linearGradient id="itK0YGc" x1="25.098" x2="25.098" y1="9.784" y2="12.127" gradientUnits="userSpaceOnUse"><stop offset=".432" class="g5d5gfbbl"/><stop offset="1" class="uekqj6-lf"/></linearGradient><linearGradient id="i8ZQsnb" x1="17.547" x2="18.383" y1="17.825" y2="15.801" gradientUnits="userSpaceOnUse"><stop class="ymt-nfbsb"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="itFLImS" x1="14.349" x2="13.513" y1="17.861" y2="15.838" gradientUnits="userSpaceOnUse"><stop class="j-jodrb5y"/><stop offset="1" class="xvb0lxf4e"/></linearGradient><linearGradient id="i1y3ZKb" x1="13.15" x2="6.107" y1="24.265" y2="24.151" gradientUnits="userSpaceOnUse"><stop offset=".585" class="jgd1sfbvg"/><stop offset="1" class="g__5jtbfk"/></linearGradient><radialGradient id="iixI3Ud" cx="0" cy="0" r="1" gradientTransform="matrix(3.04569 4.424 -8.78922 6.0509 22.175 4.477)" gradientUnits="userSpaceOnUse"><stop class="x5la94b6u"/><stop offset=".921" class="t246kz1qf"/></radialGradient><radialGradient id="i4sgO4j" cx="0" cy="0" r="1" gradientTransform="matrix(-.01653 -5.21875 10.18765 -.03227 16.198 27.275)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ccr58nbuz"/><stop offset=".312" class="hd0nr3bzk"/><stop offset=".386" class="cqs25qqpc"/></radialGradient><radialGradient id="ihgskQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89063 -.95312 .95876 -1.9018 16.488 21.318)" gradientUnits="userSpaceOnUse"><stop class="rj5_8-btj"/><stop offset="1" class="px6tpwb-q"/></radialGradient><radialGradient id="iVdnIrd" cx="0" cy="0" r="1" gradientTransform="matrix(4.40625 6.46875 -7.7559 5.283 22.91 7.08)" gradientUnits="userSpaceOnUse"><stop class="n_w31cdgy"/><stop offset="1" class="prf81acwx"/></radialGradient><radialGradient id="iIL9jib" cx="0" cy="0" r="1" gradientTransform="matrix(.97142 3.34519 -6.48458 1.88309 11.22 18.447)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="ovz69fb_x"/><stop offset=".276" class="hd0nr3bzk"/><stop offset=".411" class="ccr58nbuz"/></radialGradient><radialGradient id="i7Pge0b" cx="0" cy="0" r="1" gradientTransform="rotate(106.193 3.506 17.057)scale(3.48338 6.75247)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="ovz69fb_x"/><stop offset=".276" class="hd0nr3bzk"/><stop offset=".411" class="ccr58nbuz"/></radialGradient><radialGradient id="iBoUD5c" cx="0" cy="0" r="1" gradientTransform="rotate(-48.58 34.258 4.779)scale(8.69623 14.7041)" gradientUnits="userSpaceOnUse"><stop class="uospscb_d"/><stop offset="1" class="flip35zyj"/></radialGradient><radialGradient id="is3nY6R" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4469 8.59304 -6.01856 -2.4142 11.504 20.047)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="jgd1sfbvg"/><stop offset=".956" class="g__5jtbfk"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crying-cat" /></template>
<style>
.acoz2ac6y {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m6.716 21.806l-3.813-1.794");
}

.ajctuwq7q {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m6.582 21.831l-3.814-1.793");
}

.axgsn5hod {
  fill: var(--svg-color--ffb915, #FFB915);
  d: path("m25.875 12.81l-2.8-2.6a.716.716 0 0 1 0-1.07l3.015-2.677c.383-.336 1.175-.226 1.175.607v5.2c0 .834-.88 1.02-1.39.54");
}

.bc88ifbby {
  stop-color: var(--svg-color--d64a38, #D64A38);
}

.cbhl4sbfp {
  fill-rule: evenodd;
  d: path("M12.281 18.569c-.47 1.047-1.491 1.12-1.93.947a.559.559 0 1 0-.41 1.04c.877.346 2.597.17 3.36-1.53a.559.559 0 1 0-1.02-.457");
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.ce9hnwylf {
  stop-color: var(--svg-color--f2cc26, #F2CC26);
}

.cqs25qqpc {
  stop-color: var(--svg-color--483334, #483334);
}

.e23i5rq_z {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.245 24.182l3.097 1.493");
}

.enakum12e {
  stop-color: var(--svg-color--e37d02, #E37D02);
  stop-opacity: 0;
}

.es051ydzc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M13.14 26.885c.922-.912 3.204-2.149 5.735 0");
}

.eyds6abpk {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m25.609 21.846l3.683-1.734");
}

.f1yr_dbcd {
  stop-color: var(--svg-color--ef8a47, #EF8A47);
}

.f67sxyb7x {
  d: path("M11.57 22.053a1.826 1.826 0 1 0-3.653.004l.007 3.312a1.823 1.823 0 0 0 3.645-.004z");
}

.f6xjhkepg {
  stop-color: var(--svg-color--e99e20, #E99E20);
  stop-opacity: 0;
}

.f765u6bgr {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m25.606 23.976l3.801 1.82");
}

.fd6xzxk0h {
  stop-color: var(--svg-color--e3900e, #E3900E);
}

.flip35zyj {
  stop-color: var(--svg-color--5c98ff, #5C98FF);
}

.ft5dv1b6b {
  fill: none;
}

.fz_ww44we {
  fill: var(--svg-color--dc8400, #DC8400);
  fill-rule: evenodd;
  d: path("M15.654 22.274c.364 0 .659.246.659.55v2.75c0 .304-.295.55-.659.55s-.659-.246-.659-.55v-2.75c0-.304.295-.55.659-.55");
}

.g__5jtbfk {
  stop-color: var(--svg-color--1f2d75, #1F2D75);
  stop-opacity: 0.75;
}

.g5d5gfbbl {
  stop-color: var(--svg-color--ffe7a3, #FFE7A3);
}

.g6jl-98yn {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m24.827 24.23l1.927 1.366");
}

.gq9h7lsld {
  stop-color: var(--svg-color--e99e20, #E99E20);
}

.hd0nr3bzk {
  stop-color: var(--svg-color--594253, #594253);
}

.hr-u17bme {
  stop-color: var(--svg-color--c83f2d, #C83F2D);
}

.i-z_mxb9r {
  width: 2.727px;
  height: 3.698px;
  x: 5.096px;
  y: 21.127px;
  fill: var(--svg-color--d67908, #D67908);
  rx: 1.363px;
}

.i4304abpf {
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.id4j66bti {
  stop-color: var(--svg-color--ef8a47, #EF8A47);
  stop-opacity: 0;
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.ix23knlks {
  stroke: var(--svg-color--ff5b5d, #FF5B5D);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m25.609 22.018l3.804-1.812");
}

.j_4i6w0ng {
  stop-color: var(--svg-color--ffe792, #FFE792);
}

.j-jodrb5y {
  stop-color: var(--svg-color--e69518, #E69518);
}

.j55fys4vq {
  stroke: var(--svg-color--ff8485, #FF8485);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m6.636 23.868l-3.802 1.819");
}

.jgd1sfbvg {
  stop-color: var(--svg-color--1f2d75, #1F2D75);
  stop-opacity: 0;
}

.jke0lga3i {
  d: path("m14.848 20.788l.064-.015a3.04 3.04 0 0 1 1.438.015c.521.098.832.696.392 1.126l-.55.601c-.27.27-.863.27-1.133 0l-.543-.601c-.45-.508-.168-1.016.332-1.126");
}

.k5b8itzkz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M16 25.408v-2.75");
}

.lh8j1tblm {
  stroke: var(--svg-color--6bafff, #6BAFFF);
  stroke-linecap: round;
  d: path("m10.313 21.588l.072 3.617");
}

.m-_zadbzh {
  stop-color: var(--svg-color--b9230f, #B9230F);
}

.mlskkyb7u {
  stop-color: var(--svg-color--de7d07, #DE7D07);
}

.mno0o_bwq {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.9;
}

.n_w31cdgy {
  stop-color: var(--svg-color--ffdf70, #FFDF70);
}

.n5rbp-b1w {
  stop-color: var(--svg-color--ffdd65, #FFDD65);
}

.nrvpd5bzi {
  d: path("m15.269 20.345l.064-.015a3 3 0 0 1 1.438.015c.521.098.832.695.392 1.125l-.55.602c-.27.27-.863.27-1.133 0l-.543-.602c-.45-.508-.168-1.016.332-1.125");
}

.o4p39sb-j {
  r: 0.593px;
  fill: var(--svg-color--6bafff, #6BAFFF);
}

.o97vprbtp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M12.814 18.228c-.274.72-1.422 1.688-2.82 1.102");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ohi9f6bkt {
  stroke: var(--svg-color--ffe7a3, #FFE7A3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.265 7.034v5.187");
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.ozz659bsw {
  fill-rule: evenodd;
  d: path("M19.615 18.532c.47 1.047 1.492 1.121 1.93.948a.559.559 0 1 1 .41 1.039c-.877.347-2.597.17-3.36-1.53a.559.559 0 0 1 1.02-.457");
}

.p3zloackg {
  stop-color: var(--svg-color--e88105, #E88105);
}

.p9g7-b3yb {
  cx: 16.313px;
  cy: 20.879px;
  rx: 0.762px;
  ry: 0.274px;
}

.pc_dkijkh {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m24.827 22.2l3.805-1.813");
}

.prf81acwx {
  stop-color: var(--svg-color--ffdf70, #FFDF70);
  stop-opacity: 0;
}

.pt1exccow {
  stop-color: var(--svg-color--e3801d, #E3801D);
}

.px6tpwb-q {
  stop-color: var(--svg-color--e61e27, #E61E27);
}

.q__-mygvv {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("m6.57 23.988l-3.801 1.82");
}

.q5x9unbmu {
  stop-color: var(--svg-color--ffb03a, #FFB03A);
}

.r17kpg5ls {
  cx: 29.648px;
  cy: 19.888px;
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.rj5_8-btj {
  stop-color: var(--svg-color--ea088b, #EA088B);
}

.rxk-dwzrq {
  d: path("M4 25.942C4 28.174 5.763 30 7.918 30h16.164C26.237 30 28 28.073 28 25.84V6.43c0-1.3-1.59-1.9-2.485-1L20.975 10h-9.812L6.5 5.43c-.9-.9-2.5-.3-2.5 1z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t-5q0y2_j {
  d: path("m25.875 12.81l-2.8-2.6a.716.716 0 0 1 0-1.07l3.015-2.677c.383-.336 1.175-.226 1.175.607v5.2c0 .834-.88 1.02-1.39.54");
}

.t246kz1qf {
  stop-color: var(--svg-color--ffa720, #FFA720);
  stop-opacity: 0;
}

.tdqfdg9vp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("M19.27 18.228c.274.72 1.422 1.688 2.821 1.102");
}

.tl707w_ul {
  d: path("m26.02 14.461l1.028-8.634c.054-.46-.714-.935-1.6-.113L21.88 9.22c-2.304 2.269.761 3.248 4.139 5.241");
}

.uekqj6-lf {
  stop-color: var(--svg-color--ffdf83, #FFDF83);
  stop-opacity: 0;
}

.ugfrvi2um {
  fill: var(--svg-color--feb33e, #FEB33E);
  d: path("M5.265 6.806v5.908l3.47-3.09z");
}

.unhzk0ucp {
  cx: 29.583px;
  cy: 25.675px;
  fill: var(--svg-color--ffdd86, #FFDD86);
  rx: 0.184px;
  ry: 0.166px;
}

.uospscb_d {
  stop-color: var(--svg-color--3d5bf1, #3D5BF1);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vre-o0bdf {
  fill: var(--svg-color--cd7b00, #CD7B00);
  d: path("M9.907 22.265a1.586 1.586 0 1 0-3.172.004l.007 2.875a1.583 1.583 0 0 0 3.166-.004z");
}

.vsmb0ub4v {
  stop-color: var(--svg-color--e7671c, #E7671C);
}

.w801yrbwk {
  d: path("M26.676 6.674L23.05 9.8l3.547 2.813z");
}

.wf44tw33q {
  stop-color: var(--svg-color--e3821d, #E3821D);
}

.x1zr6fbzn {
  d: path("M26.533 5.308a.38.38 0 0 1 .732.142v2.245l-1.417-.688z");
}

.x5la94b6u {
  stop-color: var(--svg-color--ffa720, #FFA720);
}

.xc1f0x17u {
  d: path("M22.145 9.409h4.585v14.186h-4.585z");
}

.xku4sqbgj {
  d: path("m6.175 12.81l2.8-2.6c.32-.3.32-.78 0-1.07L5.96 6.463c-.383-.336-1.175-.226-1.175.607v5.2c0 .834.88 1.02 1.39.54");
}

.xon4_gnbq {
  stop-color: var(--svg-color--ed8c1b, #ED8C1B);
}

.xvb0lxf4e {
  stop-color: var(--svg-color--ea9d26, #EA9D26);
  stop-opacity: 0;
}

.ycz1ylytj {
  stop-color: var(--svg-color--fb7425, #FB7425);
}

.ymt-nfbsb {
  stop-color: var(--svg-color--de8d0f, #DE8D0F);
}

.yy6-s-urx {
  stroke: var(--svg-color--ffdf70, #FFDF70);
  stroke-linecap: round;
  d: path("m5.265 5.627l3.375 3.22c.755.72.769 1.918.032 2.655v0");
}

.z__dh0bsp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.77 9.596l2.53 2.735");
}

.z84gitb5w {
  stop-color: var(--svg-color--ffdd65, #FFDD65);
  stop-opacity: 0;
}

</style>
