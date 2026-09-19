<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iWeowpe)" class="yew86uyab"/><path fill="url(#iJswBvd)" class="yew86uyab"/><path fill="url(#iPvk5Jb)" class="p78tugbna"/><path fill="url(#iAUdnyd)" class="h7wryruqh"/><g filter="url(#i1HR5ye)"><path stroke="url(#imeLemc)" class="t-yt8ubbz"/></g><path fill="url(#i9ecqlb)" class="oqdw5ibes"/><path fill="url(#il5Yblb)" class="oqdw5ibes"/><path fill="url(#idtaMsb)" class="oqdw5ibes"/><path fill="url(#iil0oIy)" class="oqdw5ibes"/><g filter="url(#iBTiUrC)"><ellipse transform="rotate(-23.4 23.566 10.32)" class="blokxutvf"/></g><g filter="url(#iZkb8Xb)"><ellipse transform="rotate(-90 16 4.203)" class="ytdj9bb-u"/></g><g filter="url(#iDJEBZc)"><path class="ozj39bl-w"/></g><path fill="url(#iZz0gyh)" class="u-gpd1b0z"/><path fill="url(#iySTSGc)" class="u-gpd1b0z"/><path fill="url(#i9k8vWb)" class="u-gpd1b0z"/><g filter="url(#iVWdSub)"><path stroke="url(#ipuM6Vg)" class="sdm3me6ro"/></g><g filter="url(#iztC3kd)"><path stroke="url(#iv8iF2c)" class="latd1ib6x"/></g><g filter="url(#iGCOfeb)"><path stroke="url(#iJOZ8mb)" class="bh4bgub8f"/></g><g filter="url(#i6CLUkb)"><path stroke="url(#iMjjzIp)" class="t4lfiq0_t"/></g><path fill="url(#iTqziGe)" class="fm222stqc"/><rect fill="url(#i8YFO4B)" class="ybkzee88j"/><rect fill="url(#iCskg9P)" class="ybkzee88j"/><rect fill="url(#iw27NYd)" class="ybkzee88j"/><rect fill="url(#ienhQNc)" class="ybkzee88j"/><g filter="url(#ioapeRa)"><circle transform="matrix(-1 0 0 1 3.421 10.152)" class="zpyw908pn"/></g><rect fill="url(#im9Z7ut)" class="joyhgwsxa"/><rect fill="url(#iidbkJd)" class="gwuoe4bem"/><rect fill="url(#i58tlWd)" class="joyhgwsxa"/><rect fill="url(#iXxrtqi)" class="joyhgwsxa"/><rect fill="url(#iXxrtqi)" class="joyhgwsxa"/><rect fill="url(#iqsEFsd)" class="joyhgwsxa"/><g filter="url(#iC1iRse)"><path class="pvz603e8x"/></g><g filter="url(#i7UeMyc)"><circle transform="matrix(-1 0 0 1 4.406 11.383)" class="sezrx5b4p"/></g><path fill="url(#i7rEe2d)" class="gpa4gleeg"/><path fill="url(#i0H5pVd)" class="fvi3jzbhc"/><path fill="url(#iYSqlLd)" class="gpa4gleeg"/><path fill="url(#iJu0CJb)" class="gpa4gleeg"/><path fill="url(#io46j1b)" class="gpa4gleeg"/><g filter="url(#i1AtdVq)"><path fill="url(#ivuoSNc)" clip-rule="evenodd" class="m5-row7gr"/></g><rect fill="url(#iBFuDgc)" transform="matrix(-1 0 0 1 31.066 8.934)" class="hu9t65l4i"/><rect fill="url(#iKTCHMb)" transform="matrix(-1 0 0 1 31.066 8.934)" class="hu9t65l4i"/><rect fill="url(#isA50Wb)" transform="matrix(-1 0 0 1 31.066 8.934)" class="hu9t65l4i"/><rect fill="url(#iCM0Kzk)" transform="matrix(-1 0 0 1 31.066 8.934)" class="hu9t65l4i"/><rect fill="url(#iUF6tic)" transform="matrix(-1 0 0 1 30.048 10.246)" class="hu9t65l4i"/><rect fill="url(#iz99mfR)" transform="matrix(-1 0 0 1 30.048 10.246)" class="hu9t65l4i"/><rect fill="url(#ine0rEb)" transform="matrix(-1 0 0 1 30.048 10.246)" class="hu9t65l4i"/><rect fill="url(#ic1JTye)" transform="matrix(-1 0 0 1 30.048 10.246)" class="hu9t65l4i"/><g filter="url(#inz31Ie)"><path class="vi_7z_ibl"/></g><path fill="url(#iY5neMd)" class="sogvqubdp"/><path fill="url(#ijnruse)" class="i3oy3eber"/><path fill="url(#izED8JX)" class="sogvqubdp"/><path fill="url(#iLdUDZb)" class="sogvqubdp"/><path fill="url(#i8MzCoe)" class="sogvqubdp"/><g filter="url(#ijPtV7c)"><path fill="url(#iGBvAHd)" clip-rule="evenodd" class="g39i6rbsn"/></g><g filter="url(#i7cyDGe)"><rect class="wa_6d_87n"/></g><g filter="url(#itHS4Ac)"><rect class="idon5e5ai"/></g><rect fill="url(#ig28mid)" class="mgezp7i8x"/><rect fill="url(#i4n9AAe)" class="mgezp7i8x"/><rect fill="url(#iwJc7Gc)" class="tn7_jpb3z"/><rect fill="url(#ijSVsob)" class="tn7_jpb3z"/><g filter="url(#iOREKsJ)"><rect class="ny2ywmblj"/></g><rect fill="url(#iQo9q8c)" class="lb7ji7bml"/><rect fill="url(#imjXpPa)" class="lb7ji7bml"/><circle fill="url(#iD8FZFd)" class="rezydgbxw"/><circle fill="url(#ixlkQ9b)" class="sbxpzgbjo"/><g filter="url(#iYphwfc)"><circle class="cbhq1mb-n"/></g><g filter="url(#imkL74b)"><circle class="j3rn0ubim"/></g><g filter="url(#i5sKnvc)"><circle class="wzyihibxy"/></g><g filter="url(#iaAItae)"><circle class="va1jcwbtb"/></g><g filter="url(#i7VSLBZ)"><path stroke="url(#iwXhDbz)" class="e-x-kn-yd"/></g></g><defs><linearGradient id="iWeowpe" x1="6.664" x2="6.664" y1="10.586" y2="21.523" gradientUnits="userSpaceOnUse"><stop class="ck7f4woko"/><stop offset="1" class="eiejd2bux"/></linearGradient><linearGradient id="iJswBvd" x1="6.664" x2="6.664" y1="13.836" y2="22.023" gradientUnits="userSpaceOnUse"><stop class="ua19fnf6s"/><stop offset="1" class="qb49ptbxt"/></linearGradient><linearGradient id="iAUdnyd" x1="25.582" x2="25.582" y1="11.773" y2="22.023" gradientUnits="userSpaceOnUse"><stop offset=".094" class="i3zfssahs"/><stop offset="1" class="tklvtbcin"/></linearGradient><linearGradient id="il5Yblb" x1="16.149" x2="16.149" y1="14.806" y2="31.663" gradientUnits="userSpaceOnUse"><stop class="m4eoz0qca"/><stop offset="1" class="qt5w41b2y"/></linearGradient><linearGradient id="iZz0gyh" x1="16.149" x2="16.149" y1="6.281" y2="24.328" gradientUnits="userSpaceOnUse"><stop class="yrar24m3w"/><stop offset=".188" class="i3zfssahs"/><stop offset=".895" class="ppkfmqblg"/></linearGradient><linearGradient id="ipuM6Vg" x1="6.795" x2="4.332" y1="20.964" y2="8.295" gradientUnits="userSpaceOnUse"><stop class="p9uo3pblo"/><stop offset=".503" class="qf38a13vx"/><stop offset="1" class="p9uo3pblo"/></linearGradient><linearGradient id="iv8iF2c" x1="25.127" x2="28.418" y1="20.336" y2="12.395" gradientUnits="userSpaceOnUse"><stop class="v3_xnsbbc"/><stop offset=".296" class="oi7ddwbfc"/><stop offset=".808" class="v3_xnsbbc"/></linearGradient><linearGradient id="iJOZ8mb" x1="24.677" x2="21.065" y1="12.213" y2="6.795" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".557" class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></linearGradient><linearGradient id="iMjjzIp" x1="22.916" x2="22.235" y1="20.09" y2="16.016" gradientUnits="userSpaceOnUse"><stop offset=".026" class="g-3jcm1lb"/><stop offset="1" class="mebto9quo"/></linearGradient><linearGradient id="i8YFO4B" x1="3.267" x2="3.11" y1="8.934" y2="13.573" gradientUnits="userSpaceOnUse"><stop class="fl54c8b_q"/><stop offset="1" class="uexfrlbgb"/></linearGradient><linearGradient id="iCskg9P" x1="-.733" x2="2.731" y1="17.703" y2="11.415" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ypq_y2bvs"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="iw27NYd" x1="2.799" x2="3.039" y1="16.109" y2="11.246" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="ienhQNc" x1=".829" x2="2.407" y1="11.234" y2="11.234" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="im9Z7ut" x1="3.267" x2="5.046" y1="15.828" y2="15.888" gradientUnits="userSpaceOnUse"><stop class="ou2ynqzxi"/><stop offset="1" class="r6cfx8yti"/></linearGradient><linearGradient id="i58tlWd" x1="1.798" x2="2.361" y1="15.109" y2="15.106" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iXxrtqi" x1="6.066" x2="3.823" y1="15.063" y2="14.952" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iqsEFsd" x1="2.032" x2="3.236" y1="9.375" y2="11.262" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="i7rEe2d" x1="14.135" x2="1.279" y1="20.109" y2="19.943" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="eh2madfru"/></linearGradient><linearGradient id="i0H5pVd" x1="8.642" x2="2.829" y1="23.896" y2="23.896" gradientUnits="userSpaceOnUse"><stop offset=".214" class="igy6jjbiv"/><stop offset=".505" class="wighr6c3a"/><stop offset="1" class="igy6jjbiv"/></linearGradient><linearGradient id="ivuoSNc" x1="6.236" x2="6.236" y1="17.656" y2="26.241" gradientUnits="userSpaceOnUse"><stop class="sc0snxbpi"/><stop offset="1" class="c8z2d5d6a"/></linearGradient><linearGradient id="iBFuDgc" x1="1.971" x2=".258" y1="4.816" y2="-.445" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="mx--mj3gu"/></linearGradient><linearGradient id="isA50Wb" x1="3.922" x2=".932" y1="4.816" y2="4.669" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iCM0Kzk" x1="-.794" x2=".359" y1="4.816" y2="4.873" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iz99mfR" x1="5.844" x2=".58" y1="5.895" y2="4.411" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ypq_y2bvs"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="ine0rEb" x1="-.843" x2=".14" y1="4.832" y2="4.865" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="ic1JTye" x1="3.922" x2="1.679" y1="4.816" y2="4.706" gradientUnits="userSpaceOnUse"><stop class="rvow0325u"/><stop offset="1" class="bkm85hboo"/></linearGradient><linearGradient id="iY5neMd" x1="31.954" x2="23.625" y1="23.578" y2="22.857" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="n_zbjcblp"/></linearGradient><linearGradient id="ijnruse" x1="29.704" x2="23.579" y1="23.896" y2="23.896" gradientUnits="userSpaceOnUse"><stop offset=".214" class="igy6jjbiv"/><stop offset=".505" class="wighr6c3a"/><stop offset="1" class="igy6jjbiv"/></linearGradient><linearGradient id="iGBvAHd" x1="29.005" x2="29.005" y1="16.984" y2="26.241" gradientUnits="userSpaceOnUse"><stop class="sc0snxbpi"/><stop offset="1" class="c8z2d5d6a"/></linearGradient><linearGradient id="ig28mid" x1="15.96" x2="11.277" y1="10.693" y2="10.693" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="i4n9AAe" x1="13.258" x2="13.258" y1="10.521" y2="13.059" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="iwJc7Gc" x1="22.476" x2="17.792" y1="10.693" y2="10.693" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="ijSVsob" x1="19.774" x2="19.774" y1="10.521" y2="13.059" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="iQo9q8c" x1="16.149" x2="16.149" y1="13.768" y2="15.906" gradientUnits="userSpaceOnUse"><stop class="sq6bhdbbn"/><stop offset="1" class="p6w626lsj"/></linearGradient><linearGradient id="imjXpPa" x1="15.642" x2="14.902" y1="18.703" y2="15.088" gradientUnits="userSpaceOnUse"><stop offset=".07" class="xh0ps3bnm"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="iwXhDbz" x1="17.829" x2="17.829" y1="14.371" y2="15.094" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".349" class="vpk0l0bon"/></linearGradient><filter id="i1HR5ye" width="4.75" height="9.763" x="26.336" y="9.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".2"/></filter><filter id="iBTiUrC" width="11.833" height="15.089" x="17.65" y="2.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation="1.75"/></filter><filter id="iZkb8Xb" width="13.721" height="7.656" x="9.14" y=".375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation="1.75"/></filter><filter id="iDJEBZc" width="21.121" height="21.129" x="5.267" y="4.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation="1"/></filter><filter id="iVWdSub" width="3.023" height="13.73" x="3.966" y="7.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".2"/></filter><filter id="iztC3kd" width="2.477" height="11.2" x="25.719" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".2"/></filter><filter id="iGCOfeb" width="4.02" height="7.085" x="20.968" y="6.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".2"/></filter><filter id="i6CLUkb" width="2.619" height="6.931" x="21.118" y="14.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".2"/></filter><filter id="ioapeRa" width="2.984" height="2.984" x="1.929" y="8.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="iC1iRse" width="2.582" height="6.375" x="3.316" y="10.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="i7UeMyc" width="2.984" height="2.984" x="2.914" y="9.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="i1AtdVq" width="6.491" height="13.585" x="2.991" y="15.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation="1.25"/></filter><filter id="inz31Ie" width="2.582" height="6.375" x="28.005" y="10.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="ijPtV7c" width="6.164" height="14.257" x="25.923" y="14.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation="1.25"/></filter><filter id="i7cyDGe" width="3.625" height="5.25" x="10.833" y="8.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="itHS4Ac" width="3.625" height="5.25" x="17.303" y="8.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="iOREKsJ" width="7.344" height="4.418" x="12.25" y="13.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="iYphwfc" width="2.984" height="2.984" x="27.648" y="9.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="imkL74b" width="2.567" height="2.567" x="11.891" y="8.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="i5sKnvc" width="2.567" height="2.567" x="18.36" y="8.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="iaAItae" width="2.745" height="2.745" x="28.691" y="8.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".5"/></filter><filter id="i7VSLBZ" width="1.305" height="1.15" x="17.187" y="14.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6986_5090" stdDeviation=".1"/></filter><radialGradient id="iPvk5Jb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.25001 -11.12504 13.27885 -13.42801 10.533 20.46)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="tbqmcsbon"/><stop offset="1" class="d91dz_s7m"/></radialGradient><radialGradient id="imeLemc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.49997 -6.31252 13.2979 -11.5862 29.17 17.93)" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".448" class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></radialGradient><radialGradient id="i9ecqlb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.21655 16.56519 -29.35678 -14.56134 21.688 10.188)" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="j823ctb-q"/></radialGradient><radialGradient id="idtaMsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 20.6725 -18.4611 0 16.15 11.82)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="qudiit10p"/><stop offset="1" class="yw57-9naf"/></radialGradient><radialGradient id="iil0oIy" cx="0" cy="0" r="1" gradientTransform="rotate(120.14 9.373 10.098)scale(12.4 19.2555)" gradientUnits="userSpaceOnUse"><stop class="v290nq5uq"/><stop offset="1" class="ragfnwbnv"/></radialGradient><radialGradient id="iySTSGc" cx="0" cy="0" r="1" gradientTransform="rotate(159.382 11.845 7.167)scale(20.2335 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="ovqobxb3d"/><stop offset="1" class="kt15-irns"/></radialGradient><radialGradient id="i9k8vWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00069 12.7039 -10.8463 -.00059 16.15 12.777)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="t9ynm6bcv"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="iTqziGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.57812 19.0867 0 16.096 20.844)" gradientUnits="userSpaceOnUse"><stop class="di9ro-btr"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iidbkJd" cx="0" cy="0" r="1" gradientTransform="rotate(15.781 -44.9 17.2)scale(1.4938 1.63756)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ypq_y2bvs"/><stop offset="1" class="oiv2fhbci"/></radialGradient><radialGradient id="iYSqlLd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.474 12.672 12.384)scale(7.12843 7.63605)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="y7p5z931p"/><stop offset="1" class="m4eoz0qca"/></radialGradient><radialGradient id="iJu0CJb" cx="0" cy="0" r="1" gradientTransform="matrix(3.62496 -.0478 .30664 23.25318 .266 22.606)" gradientUnits="userSpaceOnUse"><stop class="tyhuxbb-o"/><stop offset=".437" class="m9wdx7_yx"/></radialGradient><radialGradient id="io46j1b" cx="0" cy="0" r="1" gradientTransform="rotate(178.401 4.687 10.991)scale(5.07154 30.2371)" gradientUnits="userSpaceOnUse"><stop class="n43ik0btk"/><stop offset=".344" class="lv6eztbmt"/></radialGradient><radialGradient id="iKTCHMb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53124 .89065 -1.8448 -5.24297 2.315 .848)" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="m_b5cmj5b"/></radialGradient><radialGradient id="iUF6tic" cx="0" cy="0" r="1" gradientTransform="rotate(111.092 .433 2.15)scale(4.68917 21.8243)" gradientUnits="userSpaceOnUse"><stop class="qu6c0n3kh"/><stop offset="1" class="uexfrlbgb"/></radialGradient><radialGradient id="izED8JX" cx="0" cy="0" r="1" gradientTransform="rotate(-119.474 23.666 5.969)scale(7.12843 7.63605)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="y7p5z931p"/><stop offset="1" class="m4eoz0qca"/></radialGradient><radialGradient id="iLdUDZb" cx="0" cy="0" r="1" gradientTransform="matrix(3.62496 -.0478 .30664 23.25318 22.255 22.606)" gradientUnits="userSpaceOnUse"><stop class="tyhuxbb-o"/><stop offset=".437" class="m9wdx7_yx"/></radialGradient><radialGradient id="i8MzCoe" cx="0" cy="0" r="1" gradientTransform="rotate(178.401 15.681 11.145)scale(5.07154 30.2371)" gradientUnits="userSpaceOnUse"><stop class="n43ik0btk"/><stop offset=".344" class="lv6eztbmt"/></radialGradient><radialGradient id="iD8FZFd" cx="0" cy="0" r="1" gradientTransform="rotate(133.174 4.295 10.721)scale(1.90311 1.14415)" gradientUnits="userSpaceOnUse"><stop class="sf_wn9jlw"/><stop offset="1" class="ixqsitb8q"/></radialGradient><radialGradient id="ixlkQ9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.774 .94202 -1.47397 -1.21107 17.757 14.925)" gradientUnits="userSpaceOnUse"><stop class="go-58hbeq"/><stop offset="1" class="ixqsitb8q"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hear-no-evil-monkey" /></template>
<style>
.bh4bgub8f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.568 6.896c1.297.51 3.69 2.496 2.496 5.885");
}

.bkm85hboo {
  stop-color: var(--svg-color--d79d95, #D79D95);
  stop-opacity: 0;
}

.blokxutvf {
  cx: 23.566px;
  cy: 10.32px;
  fill: var(--svg-color--c58e7d, #C58E7D);
  rx: 1.849px;
  ry: 4.333px;
}

.c8z2d5d6a {
  stop-color: var(--svg-color--a07a76, #A07A76);
}

.cbhq1mb-n {
  cx: 29.14px;
  cy: 11.406px;
  r: 0.492px;
  fill: var(--svg-color--ffe5dd, #FFE5DD);
}

.ck7f4woko {
  stop-color: var(--svg-color--a67874, #A67874);
}

.d91dz_s7m {
  stop-color: var(--svg-color--f39585, #F39585);
}

.dcdi0_bfz {
  stop-color: var(--svg-color--432a3d, #432A3D);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.e-x-kn-yd {
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M17.392 14.383c.343-.07.82.187.875.71");
}

.eh2madfru {
  stop-color: var(--svg-color--6b423e, #6B423E);
}

.eiejd2bux {
  stop-color: var(--svg-color--8f5872, #8F5872);
}

.fl54c8b_q {
  stop-color: var(--svg-color--f1b4aa, #F1B4AA);
}

.fm222stqc {
  d: path("M13.143 17.949c.08 1.613 1.372 2.895 2.953 2.895s2.872-1.282 2.953-2.896z");
}

.ft5dv1b6b {
  fill: none;
}

.fvi3jzbhc {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M1.126 14.925c4.611 0 7.951 2.34 7.951 4.825v5.591a3.976 3.976 0 1 1-7.951 0z");
}

.g-3jcm1lb {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
  stop-opacity: 0;
}

.g39i6rbsn {
  fill-rule: evenodd;
  d: path("M29.005 16.984c.321 0 .582.203.582.452v8.354c0 .25-.261.451-.582.451c-.322 0-.582-.202-.582-.451v-8.354c0-.25.26-.452.582-.452");
}

.go-58hbeq {
  stop-color: var(--svg-color--3c2737, #3C2737);
}

.gpa4gleeg {
  d: path("M1.126 14.925c4.611 0 7.951 2.34 7.951 4.825v5.591a3.976 3.976 0 1 1-7.951 0z");
}

.gwuoe4bem {
  width: 3.348px;
  height: 8.223px;
  x: 2.143px;
  y: 10.246px;
  fill-opacity: var(--svg-fill-opacity--0-15, 0.15);
  rx: 1.674px;
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h7wryruqh {
  d: path("M25.582 19.805c3.029 0 5.484-2.418 5.484-5.399s-2.455-5.398-5.484-5.398s-5.485 2.417-5.485 5.398s2.456 5.399 5.485 5.399");
}

.hu9t65l4i {
  width: 3.348px;
  height: 8.223px;
  rx: 1.674px;
}

.i3oy3eber {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M31.066 14.925c-4.611 0-7.951 2.34-7.951 4.825v5.591a3.976 3.976 0 1 0 7.951 0z");
}

.i3zfssahs {
  stop-color: var(--svg-color--fab8a9, #FAB8A9);
}

.idon5e5ai {
  width: 1.625px;
  height: 3.25px;
  x: 18.303px;
  y: 9.758px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.813px;
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.igy6jjbiv {
  stop-color: var(--svg-color--975077, #975077);
  stop-opacity: 0;
}

.ixqsitb8q {
  stop-color: var(--svg-color--684e61, #684E61);
}

.j3rn0ubim {
  cx: 13.175px;
  cy: 10.123px;
  r: 0.284px;
  fill: var(--svg-color--795d72, #795D72);
}

.j823ctb-q {
  stop-color: var(--svg-color--5b3838, #5B3838);
}

.joyhgwsxa {
  width: 3.348px;
  height: 8.223px;
  x: 2.143px;
  y: 10.246px;
  rx: 1.674px;
}

.kt15-irns {
  stop-color: var(--svg-color--a55f89, #A55F89);
}

.latd1ib6x {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M27.069 10.336c.83 3.28.75 7.562-.75 10");
}

.lb7ji7bml {
  width: 4.891px;
  height: 2.232px;
  x: 13.703px;
  y: 13.768px;
  rx: 1.116px;
}

.lv6eztbmt {
  stop-color: var(--svg-color--7f5575, #7F5575);
  stop-opacity: 0;
}

.lyklk88ly {
  stop-color: var(--svg-color--a06857, #A06857);
}

.m_b5cmj5b {
  stop-color: var(--svg-color--f9b4a9, #F9B4A9);
  stop-opacity: 0;
}

.m4eoz0qca {
  stop-color: var(--svg-color--682b5b, #682B5B);
  stop-opacity: 0;
}

.m5-row7gr {
  fill-rule: evenodd;
  d: path("M6.236 17.656c.412 0 .746.188.746.42v7.746c0 .232-.334.42-.746.42c-.411 0-.745-.188-.745-.42v-7.747c0-.231.334-.419.745-.419");
}

.m9wdx7_yx {
  stop-color: var(--svg-color--705c5a, #705C5A);
  stop-opacity: 0;
}

.mebto9quo {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
}

.mgezp7i8x {
  width: 1.625px;
  height: 3.25px;
  x: 12.078px;
  y: 9.516px;
  rx: 0.813px;
}

.mx--mj3gu {
  stop-color: var(--svg-color--ffdfda, #FFDFDA);
}

.n_zbjcblp {
  stop-color: var(--svg-color--64332e, #64332E);
}

.n43ik0btk {
  stop-color: var(--svg-color--915d88, #915D88);
}

.n7wvbnb3x {
  stop-color: var(--svg-color--43253d, #43253D);
  stop-opacity: 0;
}

.ny2ywmblj {
  width: 5.344px;
  height: 2.418px;
  x: 13.25px;
  y: 14.172px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  rx: 1.116px;
}

.oi7ddwbfc {
  stop-color: var(--svg-color--be8b89, #BE8B89);
  stop-opacity: 0.6;
}

.oiv2fhbci {
  stop-color: var(--svg-color--dc90cc, #DC90CC);
  stop-opacity: 0;
}

.oqdw5ibes {
  d: path("M16.149 26.753c7.966 0 11.947-5.35 11.947-11.947c0-6.599-3.98-11.948-11.947-11.948S4.202 8.208 4.202 14.806s3.98 11.947 11.947 11.947");
}

.ou2ynqzxi {
  stop-color: var(--svg-color--fdb1a4, #FDB1A4);
}

.ovqobxb3d {
  stop-color: var(--svg-color--a55f89, #A55F89);
  stop-opacity: 0;
}

.ozj39bl-w {
  fill: var(--svg-color--561e25, #561E25);
  d: path("M12.026 6.53a4.76 4.76 0 0 0-3.653 7.81a.56.56 0 0 1 .121.457q-.129.68-.13 1.398a7.464 7.464 0 1 0 14.796-1.398a.56.56 0 0 1 .122-.458a4.76 4.76 0 0 0-3.653-7.81z");
}

.p6w626lsj {
  stop-color: var(--svg-color--dc89a8, #DC89A8);
}

.p78tugbna {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M6.664 19.805c3.03 0 5.485-2.418 5.485-5.399S9.693 9.008 6.664 9.008S1.18 11.425 1.18 14.406s2.455 5.399 5.484 5.399");
}

.p9uo3pblo {
  stop-color: var(--svg-color--7c6160, #7C6160);
  stop-opacity: 0;
}

.ppkfmqblg {
  stop-color: var(--svg-color--ac628e, #AC628E);
}

.pvz603e8x {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M4.898 11.828h-.582v4.375h.582z");
}

.qb49ptbxt {
  stop-color: var(--svg-color--ca6fa6, #CA6FA6);
}

.qf38a13vx {
  stop-color: var(--svg-color--7c6160, #7C6160);
}

.qt5w41b2y {
  stop-color: var(--svg-color--682b5b, #682B5B);
}

.qu6c0n3kh {
  stop-color: var(--svg-color--f9b4a9, #F9B4A9);
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r6cfx8yti {
  stop-color: var(--svg-color--ffc6bd, #FFC6BD);
}

.ragfnwbnv {
  stop-color: var(--svg-color--ac7463, #AC7463);
  stop-opacity: 0;
}

.rezydgbxw {
  cx: 14.697px;
  cy: 15.285px;
  r: 0.512px;
}

.rvow0325u {
  stop-color: var(--svg-color--aa6c64, #AA6C64);
}

.sbxpzgbjo {
  cx: 17.494px;
  cy: 15.285px;
  r: 0.512px;
}

.sc0snxbpi {
  stop-color: var(--svg-color--bc938f, #BC938F);
}

.sdm3me6ro {
  stroke-linecap: round;
  stroke-opacity: 0.4;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M5.859 8.206c-1.593 3.93-1.412 9.682.33 12.13");
}

.sezrx5b4p {
  r: 0.492px;
  fill: var(--svg-color--ffe5dd, #FFE5DD);
}

.sf_wn9jlw {
  stop-color: var(--svg-color--3e2739, #3E2739);
}

.sogvqubdp {
  d: path("M31.066 14.925c-4.611 0-7.951 2.34-7.951 4.825v5.591a3.976 3.976 0 1 0 7.951 0z");
}

.sq6bhdbbn {
  stop-color: var(--svg-color--e9a4a2, #E9A4A2);
}

.t-yt8ubbz {
  stroke-linecap: round;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.986 9.78c.979.147 2.874 1.437 3.293 3.509c.484 1.781-.172 4.062-1.672 4.953");
}

.t4lfiq0_t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.162 14.64c.5 2.938-.594 5.126-1.594 6.032");
}

.t9ynm6bcv {
  stop-color: var(--svg-color--ef5cf2, #EF5CF2);
  stop-opacity: 0;
}

.tbqmcsbon {
  stop-color: var(--svg-color--f39585, #F39585);
  stop-opacity: 0;
}

.tklvtbcin {
  stop-color: var(--svg-color--b56595, #B56595);
}

.tn7_jpb3z {
  width: 1.625px;
  height: 3.25px;
  x: 18.594px;
  y: 9.516px;
  rx: 0.813px;
}

.tyhuxbb-o {
  stop-color: var(--svg-color--937976, #937976);
}

.u-gpd1b0z {
  d: path("M12.305 6.281a4.813 4.813 0 0 0-3.692 7.9a.55.55 0 0 1 .121.458a7.547 7.547 0 1 0 14.829 0a.55.55 0 0 1 .121-.458a4.813 4.813 0 0 0-3.692-7.9z");
}

.ua19fnf6s {
  stop-color: var(--svg-color--b56595, #B56595);
  stop-opacity: 0;
}

.uexfrlbgb {
  stop-color: var(--svg-color--d79d95, #D79D95);
}

.v290nq5uq {
  stop-color: var(--svg-color--ac7463, #AC7463);
}

.v3_xnsbbc {
  stop-color: var(--svg-color--be8b89, #BE8B89);
  stop-opacity: 0;
}

.va1jcwbtb {
  cx: 30.064px;
  cy: 9.888px;
  r: 0.372px;
  fill: var(--svg-color--ffe5dd, #FFE5DD);
}

.vi_7z_ibl {
  fill: var(--svg-color--ffd5c9, #FFD5C9);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M29.005 11.828h.582v4.375h-.582z");
}

.vpk0l0bon {
  stop-color: var(--svg-color--ffebe3, #FFEBE3);
}

.wa_6d_87n {
  width: 1.625px;
  height: 3.25px;
  x: 11.833px;
  y: 9.758px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.813px;
}

.whjaerb5v {
  stop-color: var(--svg-color--43253d, #43253D);
}

.wighr6c3a {
  stop-color: var(--svg-color--975077, #975077);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wzyihibxy {
  cx: 19.644px;
  cy: 10.123px;
  r: 0.284px;
  fill: var(--svg-color--795d72, #795D72);
}

.xh0ps3bnm {
  stop-color: var(--svg-color--c971b6, #C971B6);
}

.y7p5z931p {
  stop-color: var(--svg-color--7a326b, #7A326B);
}

.ybkzee88j {
  width: 3.348px;
  height: 8.223px;
  x: 1.126px;
  y: 8.934px;
  rx: 1.674px;
}

.yew86uyab {
  d: path("M6.664 19.805c3.03 0 5.485-2.418 5.485-5.399S9.693 9.008 6.664 9.008S1.18 11.425 1.18 14.406s2.455 5.399 5.484 5.399");
}

.ypq_y2bvs {
  stop-color: var(--svg-color--dc90cc, #DC90CC);
}

.yrar24m3w {
  stop-color: var(--svg-color--ffc8bc, #FFC8BC);
}

.ytdj9bb-u {
  cx: 16px;
  cy: 4.203px;
  fill: var(--svg-color--c58e7d, #C58E7D);
  rx: 0.328px;
  ry: 3.36px;
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.zpyw908pn {
  r: 0.492px;
  fill: var(--svg-color--ffc9ba, #FFC9BA);
}

</style>
