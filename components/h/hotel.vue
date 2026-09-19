<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVcDKOc)" class="jhro0xp-l"/><path fill="url(#iPfpfHy)" class="jhro0xp-l"/><path fill="url(#ienXoqc)" class="jhro0xp-l"/><path fill="url(#iPhTL9M)" class="w5ct_u5aa"/><path fill="url(#i2QWsXb)" class="w5ct_u5aa"/><path fill="url(#iHYHvEe)" class="w5ct_u5aa"/><path fill="url(#if2SHgT)" class="dfttn_vfh"/><path fill="url(#if8qGoe)" class="dfttn_vfh"/><g filter="url(#iBmrTRb)"><path class="lhku8vzkd"/></g><path fill="url(#i7UthPb)" class="dhqmz8beo"/><path fill="url(#i7vEtAd)" class="dhqmz8beo"/><path fill="url(#iDGnvCu)" class="dhqmz8beo"/><path fill="url(#iMqKieb)" class="dhqmz8beo"/><g filter="url(#ixDNcSd)"><path class="jt30tqbie"/></g><g filter="url(#iqjwBsc)"><path class="pph510bfn"/></g><g filter="url(#isDk7ob)"><path class="bh_hjhw0y"/></g><path fill="url(#iOFmCvI)" class="a11qiib_z"/><path fill="url(#inXumYc)" class="a11qiib_z"/><g filter="url(#i2i9kfk)"><path fill="url(#iQZmOxe)" class="pfm97kdmc"/><path fill="url(#ilWv3cd)" class="pfm97kdmc"/><path fill="url(#iuultNp)" class="pfm97kdmc"/></g><g filter="url(#idPv9zb)"><path fill="url(#iscR5ce)" class="bbbl8jc7f"/><path fill="url(#i7W08tW)" class="bbbl8jc7f"/><path fill="url(#iWvvsRc)" class="bbbl8jc7f"/></g><path fill="url(#i8rqqbc)" class="vo-b_nbxk"/><path fill="url(#iyEsMkb)" class="tw525xbsn"/><path fill="url(#iBdeuCW)" class="uhugk756d"/><path fill="url(#iKVVEWb)" class="uhugk756d"/><path fill="url(#i3qZRze)" class="uhugk756d"/><path fill="url(#i7Fp5Dd)" class="uhugk756d"/><g filter="url(#ijBSi0d)"><path fill="url(#iY2O4Kb)" class="p5-oqpblo"/><path fill="url(#i9k6zll)" class="p5-oqpblo"/></g><g filter="url(#iSyYY2x)"><path fill="url(#inKUhMb)" class="zxhi77_fa"/><path fill="url(#iJ1Wsqb)" class="zxhi77_fa"/></g><g filter="url(#iWySCKb)"><rect fill="url(#ikzNNqo)" class="mn57zsbox"/><rect fill="url(#i3h7cBe)" class="mn57zsbox"/></g><g filter="url(#iDm8fad)"><rect fill="url(#ijbeQGc)" class="jt2x23b1b"/><rect fill="url(#i6aikec)" class="jt2x23b1b"/></g><g filter="url(#iLZ0VSc)"><rect fill="url(#i5xlIJd)" class="cc5bb6bgg"/><rect fill="url(#i1q3Ocd)" class="cc5bb6bgg"/></g><g filter="url(#irhgN2d)"><rect fill="url(#izY2FGc)" class="of1-__bsc"/><rect fill="url(#iT9pUcd)" class="of1-__bsc"/></g><g filter="url(#ij1QGVc)"><rect fill="url(#inwc2TK)" class="zrnpzqbnj"/><rect fill="url(#iqPW38d)" class="zrnpzqbnj"/></g><g filter="url(#imGTsSd)"><rect fill="url(#iP7v7rJ)" class="iy9p0-ngs"/><rect fill="url(#iG76QBm)" class="iy9p0-ngs"/></g><g filter="url(#i3JZomc)"><rect fill="url(#i0PaShd)" class="m1tm-_lmx"/><rect fill="url(#iSftrck)" class="m1tm-_lmx"/></g><g filter="url(#iLUDvQb)"><rect fill="url(#ic9vlqd)" class="spqj4wtsc"/><rect fill="url(#il91Cxc)" class="spqj4wtsc"/></g><g filter="url(#iKlEuZc)"><rect fill="url(#iPlKedd)" class="rj-zxu-7d"/><rect fill="url(#ibhUUsc)" class="rj-zxu-7d"/></g><g filter="url(#ilbsdVJ)"><rect fill="url(#iKrMgcd)" class="ytz78yb3e"/><rect fill="url(#ikmVnld)" class="ytz78yb3e"/></g><g filter="url(#i45U10d)"><rect fill="url(#ipGeiib)" class="k0n-__-5p"/><rect fill="url(#irrOGwd)" class="k0n-__-5p"/></g><g filter="url(#ioO8Whd)"><rect fill="url(#iUXMGNb)" class="gz97c0tmv"/><rect fill="url(#iJeCqee)" class="gz97c0tmv"/></g><g filter="url(#igM5Mcz)"><path stroke="url(#iSvAgqv)" class="fxzc3mb4o"/></g><g filter="url(#iQvDMmc)"><path class="o3_fpwbux"/></g><g filter="url(#iYCRHNb)"><path fill="url(#ivDRdcb)" class="crbdq43cj"/><path fill="url(#i6Xkror)" class="crbdq43cj"/></g><defs><linearGradient id="iVcDKOc" x1="16.01" x2="16.01" y1="22.912" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="rsi8qvbch"/><stop offset="1" class="oenc1kelj"/></linearGradient><linearGradient id="iPfpfHy" x1="3.104" x2="3.408" y1="19.852" y2="19.852" gradientUnits="userSpaceOnUse"><stop class="yu-f9d7yq"/><stop offset="1" class="q-mpw4bea"/></linearGradient><linearGradient id="ienXoqc" x1="28.916" x2="28.432" y1="19.346" y2="19.346" gradientUnits="userSpaceOnUse"><stop offset=".29" class="aroe0acxf"/><stop offset="1" class="inqspbcku"/></linearGradient><linearGradient id="iPhTL9M" x1="11.01" x2="10.088" y1="20.562" y2="20.562" gradientUnits="userSpaceOnUse"><stop class="nvmvalbxf"/><stop offset="1" class="immql8lby"/></linearGradient><linearGradient id="i2QWsXb" x1="8.557" x2="8.557" y1="7.954" y2="8.426" gradientUnits="userSpaceOnUse"><stop class="mocxno6fj"/><stop offset="1" class="ia4rjbccp"/></linearGradient><linearGradient id="if2SHgT" x1="20.948" x2="21.573" y1="25.691" y2="25.691" gradientUnits="userSpaceOnUse"><stop class="reuivyb7z"/><stop offset="1" class="xqc7zzbji"/></linearGradient><linearGradient id="if8qGoe" x1="23.463" x2="23.463" y1="7.954" y2="8.426" gradientUnits="userSpaceOnUse"><stop class="mocxno6fj"/><stop offset="1" class="ia4rjbccp"/></linearGradient><linearGradient id="i7UthPb" x1="16" x2="16" y1="2.969" y2="29.91" gradientUnits="userSpaceOnUse"><stop class="jocl05brn"/><stop offset="1" class="tqr-y285g"/></linearGradient><linearGradient id="iDGnvCu" x1="20.924" x2="20.596" y1="20.316" y2="20.316" gradientUnits="userSpaceOnUse"><stop class="g4c4tt79s"/><stop offset="1" class="vkuhkbmvu"/></linearGradient><linearGradient id="iMqKieb" x1="11.016" x2="11.26" y1="20.348" y2="20.348" gradientUnits="userSpaceOnUse"><stop class="xly9pqbjw"/><stop offset="1" class="yd4xqujwf"/></linearGradient><linearGradient id="iOFmCvI" x1="16.01" x2="16.01" y1="20.577" y2="27.973" gradientUnits="userSpaceOnUse"><stop class="nzbi-xnai"/><stop offset="1" class="q_0c7ac5v"/></linearGradient><linearGradient id="iQZmOxe" x1="13.141" x2="17.838" y1="26.973" y2="23.386" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="ilWv3cd" x1="13.01" x2="13.445" y1="23.473" y2="23.473" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iuultNp" x1="14.26" x2="14.26" y1="20.467" y2="22.03" gradientUnits="userSpaceOnUse"><stop class="v20scwbbo"/><stop offset="1" class="p17j_n1tp"/></linearGradient><linearGradient id="iscR5ce" x1="16.641" x2="21.338" y1="26.973" y2="23.386" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="i7W08tW" x1="16.51" x2="16.945" y1="23.473" y2="23.473" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iWvvsRc" x1="17.76" x2="17.76" y1="20.467" y2="22.03" gradientUnits="userSpaceOnUse"><stop class="v20scwbbo"/><stop offset="1" class="p17j_n1tp"/></linearGradient><linearGradient id="i8rqqbc" x1="16.01" x2="16.01" y1="28.973" y2="30.026" gradientUnits="userSpaceOnUse"><stop offset=".361" class="iowg-5bhu"/><stop offset="1" class="ycvwj1wna"/></linearGradient><linearGradient id="iyEsMkb" x1="16.01" x2="16.01" y1="27.973" y2="29.132" gradientUnits="userSpaceOnUse"><stop offset=".361" class="m11oyeb-q"/><stop offset="1" class="a5vh5hbqb"/></linearGradient><linearGradient id="i3qZRze" x1="16.01" x2="16.01" y1="21.185" y2="20.507" gradientUnits="userSpaceOnUse"><stop class="e3qbdg5dv"/><stop offset=".645" class="xki2gobsi"/><stop offset="1" class="ugi5gcclg"/></linearGradient><linearGradient id="iY2O4Kb" x1="13.115" x2="15.077" y1="15.973" y2="13.176" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="i9k6zll" x1="13.01" x2="13.555" y1="14.473" y2="14.473" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="inKUhMb" x1="17.115" x2="19.077" y1="15.973" y2="13.176" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iJ1Wsqb" x1="17.01" x2="17.555" y1="14.473" y2="14.473" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="ikzNNqo" x1="4.156" x2="6.092" y1="14.021" y2="11.19" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="i3h7cBe" x1="4.049" x2="4.605" y1="12.528" y2="12.528" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="ijbeQGc" x1="7.129" x2="9.065" y1="14.021" y2="11.19" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="i6aikec" x1="7.021" x2="7.578" y1="12.528" y2="12.528" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="i5xlIJd" x1="4.156" x2="6.092" y1="18.987" y2="16.155" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="i1q3Ocd" x1="4.049" x2="4.605" y1="17.494" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="izY2FGc" x1="7.129" x2="9.065" y1="18.987" y2="16.155" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iT9pUcd" x1="7.021" x2="7.578" y1="17.494" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="inwc2TK" x1="4.156" x2="6.092" y1="23.953" y2="21.122" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iqPW38d" x1="4.049" x2="4.605" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iP7v7rJ" x1="7.129" x2="9.065" y1="23.953" y2="21.122" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iG76QBm" x1="7.021" x2="7.578" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="i0PaShd" x1="23.043" x2="24.979" y1="14.021" y2="11.19" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iSftrck" x1="22.935" x2="23.492" y1="12.528" y2="12.528" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="ic9vlqd" x1="26.015" x2="27.951" y1="14.021" y2="11.19" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="il91Cxc" x1="25.908" x2="26.465" y1="12.528" y2="12.528" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iPlKedd" x1="23.043" x2="24.979" y1="18.987" y2="16.155" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="ibhUUsc" x1="22.935" x2="23.492" y1="17.494" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iKrMgcd" x1="26.015" x2="27.951" y1="18.987" y2="16.155" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="ikmVnld" x1="25.908" x2="26.465" y1="17.494" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="ipGeiib" x1="23.043" x2="24.979" y1="23.953" y2="21.122" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="irrOGwd" x1="22.935" x2="23.492" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="iUXMGNb" x1="26.015" x2="27.951" y1="23.953" y2="21.122" gradientUnits="userSpaceOnUse"><stop class="g12vzib_v"/><stop offset="1" class="fk6fa6byv"/></linearGradient><linearGradient id="iJeCqee" x1="25.908" x2="26.465" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="ngob4nbyz"/><stop offset=".909" class="aclvogb1n"/></linearGradient><linearGradient id="i6Xkror" x1="16" x2="16" y1="8.974" y2="5.919" gradientUnits="userSpaceOnUse"><stop offset=".235" class="sgnf7tblj"/><stop offset="1" class="jm8w5xkwm"/></linearGradient><filter id="iBmrTRb" width="13.306" height="3.582" x="8.434" y="27.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6399" stdDeviation=".5"/></filter><filter id="ixDNcSd" width="4.4" height="5.4" x="13.732" y="5.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6399" stdDeviation=".1"/></filter><filter id="iqjwBsc" width="4.3" height="5.05" x="13.81" y="5.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.2125 0 0 0 0 0.30908 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.109804 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6399" result="effect2_innerShadow_18_6399"/></filter><filter id="isDk7ob" width="9.708" height="10.86" x="10.619" y="17.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6399" stdDeviation=".25"/></filter><filter id="i2i9kfk" width="2.9" height="7.25" x="12.61" y="19.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="idPv9zb" width="2.9" height="7.25" x="16.11" y="19.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="ijBSi0d" width="2.25" height="3.25" x="12.76" y="12.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="iSyYY2x" width="2.25" height="3.25" x="16.76" y="12.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="iWySCKb" width="2.293" height="3.237" x="3.799" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="iDm8fad" width="2.293" height="3.237" x="6.771" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="iLZ0VSc" width="2.293" height="3.237" x="3.799" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="irhgN2d" width="2.293" height="3.237" x="6.771" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="ij1QGVc" width="2.293" height="3.237" x="3.799" y="20.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="imGTsSd" width="2.293" height="3.237" x="6.771" y="20.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="i3JZomc" width="2.293" height="3.237" x="22.685" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="iLUDvQb" width="2.293" height="3.237" x="25.658" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="iKlEuZc" width="2.293" height="3.237" x="22.685" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="ilbsdVJ" width="2.293" height="3.237" x="25.658" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="i45U10d" width="2.293" height="3.237" x="22.685" y="20.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="ioO8Whd" width="2.293" height="3.237" x="25.658" y="20.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.466667 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><filter id="igM5Mcz" width="6.192" height="3.61" x="15.061" y="2.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6399" stdDeviation=".125"/></filter><filter id="iQvDMmc" width="7.864" height="6.095" x="14.127" y="2.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6399" stdDeviation=".15"/></filter><filter id="iYCRHNb" width="28.08" height="6.12" x="2.01" y="1.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.141176 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6399"/></filter><radialGradient id="iHYHvEe" cx="0" cy="0" r="1" gradientTransform="rotate(-105.524 17.053 11.38)scale(2.17976 1.10367)" gradientUnits="userSpaceOnUse"><stop class="lrk1i7bem"/><stop offset="1" class="rrc98qeot"/></radialGradient><radialGradient id="i7vEtAd" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 -3.21875 4.98246 11.6096 10.01 25.598)" gradientUnits="userSpaceOnUse"><stop class="b73eu2bav"/><stop offset="1" class="xn7mezbaz"/></radialGradient><radialGradient id="inXumYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.21348 -5.81019 0 16.01 20.657)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="frob6hb0i"/><stop offset="1" class="j4e1cd4ym"/></radialGradient><radialGradient id="iBdeuCW" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.78057 -5.84427 0 16.01 17.763)" gradientUnits="userSpaceOnUse"><stop class="f-_r84bbg"/><stop offset="1" class="m457-4bps"/></radialGradient><radialGradient id="iKVVEWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.75953 5.0015 0 18.478 20.973)" gradientUnits="userSpaceOnUse"><stop class="upqok7b4g"/><stop offset="1" class="nw8quvbdy"/></radialGradient><radialGradient id="i7Fp5Dd" cx="0" cy="0" r="1" gradientTransform="rotate(110.674 2.142 13.826)scale(5.07676 14.2339)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="pumq45phv"/><stop offset="1" class="wef-b4bdp"/></radialGradient><radialGradient id="iSvAgqv" cx="0" cy="0" r="1" gradientTransform="matrix(-.69302 1.3214 -3.50406 -1.83772 18.686 3.022)" gradientUnits="userSpaceOnUse"><stop class="cjvuzhbpa"/><stop offset="1" class="z0uv38b9b"/></radialGradient><radialGradient id="ivDRdcb" cx="0" cy="0" r="1" gradientTransform="rotate(96.009 8.148 9.557)scale(4.9312 16.0652)" gradientUnits="userSpaceOnUse"><stop class="asrevoaam"/><stop offset="1" class="y92-23pcb"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hotel" /></template>
<style>
.a11qiib_z {
  d: path("M20.01 19.973h-8v8h8z");
}

.a5vh5hbqb {
  stop-color: var(--svg-color--f43239, #F43239);
}

.aclvogb1n {
  stop-color: var(--svg-color--5adfff, #5ADFFF);
  stop-opacity: 0;
}

.aroe0acxf {
  stop-color: var(--svg-color--ffcda6, #FFCDA6);
}

.asrevoaam {
  stop-color: var(--svg-color--f05f3a, #F05F3A);
}

.b73eu2bav {
  stop-color: var(--svg-color--db8d81, #DB8D81);
}

.bbbl8jc7f {
  d: path("M18.647 26.973h-1.774a.365.365 0 0 1-.363-.37v-6.26c0-.2.157-.37.363-.37h1.774c.196 0 .363.16.363.37v6.26c0 .21-.167.37-.363.37");
}

.bh_hjhw0y {
  fill: var(--svg-color--ac625b, #AC625B);
  d: path("M19.783 20.783q-.001.012.005.02c.03.048.04.116.04.183a.435.435 0 0 1-.44.435h-.045v6.76h-7.74v-6.76h-.044a.435.435 0 0 1-.44-.435a.45.45 0 0 1 .059-.203c.01-.01.01-.01.01-.019a4.99 4.99 0 0 1 4.295-2.443a4.99 4.99 0 0 1 4.295 2.443q.006.008.005.02");
}

.cc5bb6bgg {
  width: 2.043px;
  height: 2.987px;
  x: 4.049px;
  y: 16px;
  rx: 0.35px;
}

.cjvuzhbpa {
  stop-color: var(--svg-color--f87b42, #F87B42);
}

.crbdq43cj {
  d: path("M27.85 4.993h-6.399a.53.53 0 0 1-.44-.25a5.95 5.95 0 0 0-5.021-2.77a5.95 5.95 0 0 0-5.02 2.77a.53.53 0 0 1-.441.25H4.13c-1.11 0-2.01.96-2.12 2.19c.06.45.43.81.9.81h8.02c.055 0 .1-.045.101-.1a5.6 5.6 0 0 1 .109-.9c.14-.74.46-1.41.89-2c.9-1.22 2.34-2.02 3.97-2.02s3.07.8 3.97 2.02c.43.59.75 1.26.89 2c.057.284.1.62.108.9c.002.055.047.1.102.1h8.02c.47 0 .84-.36.9-.81c-.13-1.23-1.03-2.19-2.14-2.19");
}

.dfttn_vfh {
  d: path("M18.01 7.664h10.906v22.309H18.01z");
}

.dhqmz8beo {
  d: path("M11.016 7.953a4.984 4.984 0 0 1 9.968 0v20.973h-9.968z");
}

.e3qbdg5dv {
  stop-color: var(--svg-color--e61938, #E61938);
}

.f-_r84bbg {
  stop-color: var(--svg-color--ff6b2d, #FF6B2D);
}

.fk6fa6byv {
  stop-color: var(--svg-color--3892e6, #3892E6);
}

.frob6hb0i {
  stop-color: var(--svg-color--9c4539, #9C4539);
}

.ft5dv1b6b {
  fill: none;
}

.fxzc3mb4o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.436 2.538c1.236-.254 4.026.22 5.442 2.8");
}

.g12vzib_v {
  stop-color: var(--svg-color--47caff, #47CAFF);
}

.g4c4tt79s {
  stop-color: var(--svg-color--ffc7a1, #FFC7A1);
}

.gz97c0tmv {
  width: 2.043px;
  height: 2.987px;
  x: 25.908px;
  y: 20.966px;
  rx: 0.35px;
}

.ia4rjbccp {
  stop-color: var(--svg-color--b34347, #B34347);
  stop-opacity: 0;
}

.immql8lby {
  stop-color: var(--svg-color--e08f7f, #E08F7F);
  stop-opacity: 0;
}

.inqspbcku {
  stop-color: var(--svg-color--ffcda6, #FFCDA6);
  stop-opacity: 0;
}

.iowg-5bhu {
  stop-color: var(--svg-color--fc5328, #FC5328);
}

.iy9p0-ngs {
  width: 2.043px;
  height: 2.987px;
  x: 7.021px;
  y: 20.966px;
  rx: 0.35px;
}

.j4e1cd4ym {
  stop-color: var(--svg-color--9c4539, #9C4539);
  stop-opacity: 0;
}

.jhro0xp-l {
  d: path("M3.104 7.664h25.813v22.309H3.104z");
}

.jm8w5xkwm {
  stop-color: var(--svg-color--ca1630, #CA1630);
  stop-opacity: 0;
}

.jocl05brn {
  stop-color: var(--svg-color--fcae95, #FCAE95);
}

.jt2x23b1b {
  width: 2.043px;
  height: 2.987px;
  x: 7.021px;
  y: 11.034px;
  rx: 0.35px;
}

.jt30tqbie {
  fill: var(--svg-color--c9645e, #C9645E);
  d: path("M17.443 6.008h-.02a.49.49 0 0 0-.488.49v1.51H14.93v-1.51a.49.49 0 0 0-.49-.49h-.02a.49.49 0 0 0-.488.49v4.02c0 .27.22.49.489.49h.02a.49.49 0 0 0 .489-.49v-1.5h2.005v1.5c0 .27.22.49.488.49h.02a.49.49 0 0 0 .49-.49v-4.02a.49.49 0 0 0-.49-.49");
}

.k0n-__-5p {
  width: 2.043px;
  height: 2.987px;
  x: 22.935px;
  y: 20.966px;
  rx: 0.35px;
}

.lhku8vzkd {
  fill: var(--svg-color--ba615f, #BA615F);
  d: path("M10.376 28.543v.344h-.357c-.32 0-.585.221-.585.49v.3H20.74v-.3c0-.269-.265-.49-.586-.49h-.357v-.344c0-.247-.235-.447-.528-.447h-8.365c-.292 0-.528.2-.528.447");
}

.lrk1i7bem {
  stop-color: var(--svg-color--ba615f, #BA615F);
}

.m11oyeb-q {
  stop-color: var(--svg-color--fc5430, #FC5430);
}

.m1tm-_lmx {
  width: 2.043px;
  height: 2.987px;
  x: 22.935px;
  y: 11.034px;
  rx: 0.35px;
}

.m457-4bps {
  stop-color: var(--svg-color--c12c2c, #C12C2C);
}

.mn57zsbox {
  width: 2.043px;
  height: 2.987px;
  x: 4.049px;
  y: 11.034px;
  rx: 0.35px;
}

.mocxno6fj {
  stop-color: var(--svg-color--b34347, #B34347);
}

.ngob4nbyz {
  stop-color: var(--svg-color--5adfff, #5ADFFF);
}

.nvmvalbxf {
  stop-color: var(--svg-color--bd5b55, #BD5B55);
}

.nw8quvbdy {
  stop-color: var(--svg-color--fa4d54, #FA4D54);
  stop-opacity: 0;
}

.nzbi-xnai {
  stop-color: var(--svg-color--d78a5d, #D78A5D);
}

.o3_fpwbux {
  fill: var(--svg-color--b53f3a, #B53F3A);
  d: path("M20.995 7.652c-1-3.753-3.369-4.787-6.473-4.59c-.044.002-.087-.024-.092-.067c-.053-.418.725-1.068 3.486-.147c2.824.941 3.681 3.59 3.774 4.924a.097.097 0 0 1-.125.099l-.5-.148a.1.1 0 0 1-.07-.071");
}

.oenc1kelj {
  stop-color: var(--svg-color--ffaf9b, #FFAF9B);
}

.of1-__bsc {
  width: 2.043px;
  height: 2.987px;
  x: 7.021px;
  y: 16px;
  rx: 0.35px;
}

.p17j_n1tp {
  stop-color: var(--svg-color--2a63af, #2A63AF);
  stop-opacity: 0;
}

.p5-oqpblo {
  d: path("M15.01 15.663v-2.38c0-.17-.14-.31-.312-.31h-1.376a.313.313 0 0 0-.312.31v2.38c0 .17.14.31.312.31h1.377c.17 0 .311-.14.311-.31");
}

.pfm97kdmc {
  d: path("M15.147 26.973h-1.774a.365.365 0 0 1-.363-.37v-6.26c0-.2.157-.37.363-.37h1.774c.196 0 .363.16.363.37v6.26c0 .21-.167.37-.363.37");
}

.pph510bfn {
  fill: var(--svg-color--e51230, #E51230);
  d: path("M17.521 5.973h-.02a.49.49 0 0 0-.489.49v1.51h-2.005v-1.51a.49.49 0 0 0-.488-.49h-.02a.49.49 0 0 0-.489.49v4.02c0 .27.22.49.489.49h.02a.49.49 0 0 0 .489-.49v-1.5h2.005v1.5c0 .27.219.49.488.49h.02a.49.49 0 0 0 .489-.49v-4.02a.49.49 0 0 0-.489-.49");
}

.pumq45phv {
  stop-color: var(--svg-color--c61734, #C61734);
  stop-opacity: 0;
}

.q_0c7ac5v {
  stop-color: var(--svg-color--ffc8a6, #FFC8A6);
}

.q-mpw4bea {
  stop-color: var(--svg-color--a56e61, #A56E61);
  stop-opacity: 0;
}

.reuivyb7z {
  stop-color: var(--svg-color--ffa882, #FFA882);
}

.rj-zxu-7d {
  width: 2.043px;
  height: 2.987px;
  x: 22.935px;
  y: 16px;
  rx: 0.35px;
}

.rrc98qeot {
  stop-color: var(--svg-color--ba615f, #BA615F);
  stop-opacity: 0;
}

.rsi8qvbch {
  stop-color: var(--svg-color--ffaf96, #FFAF96);
}

.sgnf7tblj {
  stop-color: var(--svg-color--ca1630, #CA1630);
}

.spqj4wtsc {
  width: 2.043px;
  height: 2.987px;
  x: 25.908px;
  y: 11.034px;
  rx: 0.35px;
}

.tqr-y285g {
  stop-color: var(--svg-color--ffb395, #FFB395);
}

.tw525xbsn {
  d: path("M21.01 28.973h-10v-.435c0-.313.25-.565.56-.565h8.88c.31 0 .56.252.56.565z");
}

.ugi5gcclg {
  stop-color: var(--svg-color--e61938, #E61938);
  stop-opacity: 0;
}

.uhugk756d {
  d: path("M20.47 20.333c-.01-.01 0-.03-.01-.04a5.16 5.16 0 0 0-4.44-2.53a5.16 5.16 0 0 0-4.44 2.53c0 .01 0 .01-.01.02c-.03.06-.06.13-.06.21c0 .25.202.45.454.45h8.092a.45.45 0 0 0 .454-.45a.4.4 0 0 0-.04-.19");
}

.upqok7b4g {
  stop-color: var(--svg-color--fa4d54, #FA4D54);
}

.v20scwbbo {
  stop-color: var(--svg-color--2a63af, #2A63AF);
}

.vkuhkbmvu {
  stop-color: var(--svg-color--ffc7a1, #FFC7A1);
  stop-opacity: 0;
}

.vo-b_nbxk {
  d: path("M22 29.973H10.01v-.38c0-.34.28-.62.621-.62h10.758c.34 0 .621.28.621.62v.38z");
}

.w5ct_u5aa {
  d: path("M3.104 7.664H14.01v22.309H3.104z");
}

.wef-b4bdp {
  stop-color: var(--svg-color--c61734, #C61734);
}

.xki2gobsi {
  stop-color: var(--svg-color--e61938, #E61938);
  stop-opacity: 0.908;
}

.xly9pqbjw {
  stop-color: var(--svg-color--be7a6b, #BE7A6B);
}

.xn7mezbaz {
  stop-color: var(--svg-color--db8d81, #DB8D81);
  stop-opacity: 0;
}

.xqc7zzbji {
  stop-color: var(--svg-color--ffa882, #FFA882);
  stop-opacity: 0;
}

.y92-23pcb {
  stop-color: var(--svg-color--e94239, #E94239);
}

.ycvwj1wna {
  stop-color: var(--svg-color--f72f3e, #F72F3E);
}

.yd4xqujwf {
  stop-color: var(--svg-color--be7a6b, #BE7A6B);
  stop-opacity: 0;
}

.ytz78yb3e {
  width: 2.043px;
  height: 2.987px;
  x: 25.908px;
  y: 16px;
  rx: 0.35px;
}

.yu-f9d7yq {
  stop-color: var(--svg-color--a56e61, #A56E61);
}

.z0uv38b9b {
  stop-color: var(--svg-color--f87b42, #F87B42);
  stop-opacity: 0;
}

.zrnpzqbnj {
  width: 2.043px;
  height: 2.987px;
  x: 4.049px;
  y: 20.966px;
  rx: 0.35px;
}

.zxhi77_fa {
  d: path("M19.01 15.663v-2.38c0-.17-.14-.31-.312-.31h-1.376a.313.313 0 0 0-.312.31v2.38c0 .17.14.31.312.31h1.377c.17 0 .311-.14.311-.31");
}

</style>
