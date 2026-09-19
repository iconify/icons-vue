<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="o-m2accnh"/><path fill="url(#ijE72Gd)" class="jy5ziozje"/><path fill="url(#ifN9LWc)" class="t1hpzx_jo"/><path fill="url(#i2LArOe)" class="g40pm_btx"/><path fill="url(#iYq7NNc)" class="yeahgsb6k"/><path fill="url(#ilMEFoA)" class="butrocbrn"/><path fill="url(#iyDu79b)" class="butrocbrn"/><path fill="url(#iMHwzoc)" class="d5qhtknfx"/><path fill="url(#i55m0QW)" class="wucpt0bvm"/><path class="ukr738bor"/><path fill="url(#igJwnme)" class="nu47yacom"/><path class="cky6dx4yb"/><path fill="url(#izPRTXc)" class="nn3h6bb4s"/><path fill="url(#iDl5fke)" class="nn3h6bb4s"/><path fill="url(#inlITrd)" class="nn3h6bb4s"/><path fill="url(#ii7pVre)" class="nn3h6bb4s"/><path fill="url(#ieA0aPd)" class="nn3h6bb4s"/><g filter="url(#iAtM5vd)"><path clip-rule="evenodd" class="ngkfjzbpc"/></g><g filter="url(#iXTxaab)"><path stroke="url(#iacdA5b)" class="lw35ocqzs"/></g><g filter="url(#iqYBX1d)"><path stroke="url(#iVhNsmb)" class="khjq9208f"/></g><g filter="url(#i3urCPd)"><path stroke="url(#icqdaud)" class="f35lrjb7a"/></g><g filter="url(#iQwzLjd)"><path stroke="url(#iRteEBb)" class="iydjqdb3g"/></g><g filter="url(#inVtrfc)"><path stroke="url(#itIi83d)" class="kg-46h68l"/></g><g filter="url(#iHsZhBn)"><path stroke="url(#i4s9nvd)" class="g9w9_rbjt"/></g><g filter="url(#isJWTUd)"><path stroke="url(#iem9Tgd)" class="e7xy98byx"/></g><g filter="url(#iTd3mQd)"><path fill="url(#im6AIVc)" clip-rule="evenodd" class="s57p5bfun"/></g><g filter="url(#iAlcgne)"><path fill="url(#iu2lLQy)" clip-rule="evenodd" class="c6418fb3w"/></g><path fill="url(#iv3fYHb)" class="fv0v_ebpu"/><path fill="url(#iGGjxob)" class="fv0v_ebpu"/><path fill="url(#iFSFOTb)" class="fv0v_ebpu"/><path fill="url(#ij06eIp)" class="fv0v_ebpu"/><path fill="url(#iV7oZfd)" class="fv0v_ebpu"/><path fill="url(#iO0Cqnc)" class="fv0v_ebpu"/><g filter="url(#izxkaco)"><path fill="url(#iTd8qHb)" class="hl2mn-rsx"/><path fill="url(#isAg7oc)" class="hl2mn-rsx"/></g><g filter="url(#iQ9pVLe)"><circle class="bgq3ejbuh"/></g><g filter="url(#iGuECGb)"><circle class="acmzumb1r"/></g><g filter="url(#ikHkAKc)"><circle class="bk321llui"/></g><g filter="url(#ii29EOd)"><circle class="num8wjb6y"/></g><g filter="url(#ibb2QQc)"><circle class="d39ijacga"/></g><g filter="url(#iVGTNlY)"><circle class="b8urqqrmv"/></g><g filter="url(#iHNDkvc)"><ellipse transform="rotate(34.993 21.024 10.028)" class="upngrabwy"/></g><g filter="url(#i0HZWAC)"><ellipse transform="rotate(34.993 9.274 19.778)" class="etjg9f6ij"/></g><g filter="url(#i0izoKd)"><circle class="uu78lrbyq"/></g><g filter="url(#iaq6tiG)"><path class="pqrll2b3h"/></g><g filter="url(#iQ4KoFc)"><path class="f27wv-bcn"/></g><g filter="url(#iESMRFe)"><path class="c0t7wobvu"/></g><g filter="url(#ih3cxBe)"><path class="k-yh91bid"/></g><defs><filter id="iAtM5vd" width="6.219" height="12.656" x="18.859" y="16.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="iXTxaab" width="2.406" height="12.844" x="11.047" y="14.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="iqYBX1d" width="3.531" height="14.031" x="22.859" y="1.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="i3urCPd" width="2.406" height="6.594" x="26.734" y="8.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="iQwzLjd" width="5.219" height="12.344" x="7.234" y="1.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="inVtrfc" width="3.906" height="4.234" x="3.234" y="5.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="iHsZhBn" width="3.781" height="4.625" x="14.609" y="15.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="isJWTUd" width="5.313" height="7.406" x="11.734" y="7.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="iTd3mQd" width="5.469" height="8.031" x="15.766" y="13.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="iAlcgne" width="3.844" height="9.156" x="14.703" y="18.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".438"/></filter><filter id="izxkaco" width="21.513" height="4.031" x="5.156" y="26.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".297"/></filter><filter id="iQ9pVLe" width="2.688" height="2.688" x="6.906" y="1.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="iGuECGb" width="2.625" height="2.625" x="2.969" y="5.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="ikHkAKc" width="2.625" height="2.625" x="14.469" y="7.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="ii29EOd" width="2.563" height="2.563" x="18.781" y="13.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="ibb2QQc" width="2.625" height="2.625" x="22.656" y="1.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="iVGTNlY" width="2.563" height="2.563" x="26.625" y="8.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="iHNDkvc" width="2.99" height="2.729" x="19.529" y="8.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="i0HZWAC" width="2.99" height="2.729" x="7.779" y="18.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="i0izoKd" width="2.563" height="2.563" x="14.406" y="15.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".391"/></filter><filter id="iaq6tiG" width="6.25" height="7.219" x="8.719" y="11.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".375"/></filter><filter id="iQ4KoFc" width="5.719" height="7.375" x="14.625" y="16.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".406"/></filter><filter id="iESMRFe" width="6" height="7.344" x="22.813" y="12.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".406"/></filter><filter id="ih3cxBe" width="4.344" height="4.438" x="8.438" y="18.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_8031" stdDeviation=".359"/></filter><linearGradient id="ijE72Gd" x1="23.532" x2="23.532" y1="2" y2="27.969" gradientUnits="userSpaceOnUse"><stop offset=".319" class="glwuqabow"/><stop offset=".55" class="f-ab535jf"/></linearGradient><linearGradient id="igJwnme" x1="17.571" x2="17.571" y1="13.448" y2="27.682" gradientUnits="userSpaceOnUse"><stop offset=".098" class="z69k69bex"/><stop offset=".818" class="eaejiub5t"/></linearGradient><linearGradient id="izPRTXc" x1="9.641" x2="9.641" y1="2.026" y2="26.531" gradientUnits="userSpaceOnUse"><stop offset=".426" class="chqb3ku-a"/><stop offset=".73" class="f-ab535jf"/></linearGradient><linearGradient id="iacdA5b" x1="12.25" x2="12.25" y1="25.844" y2="-3.718" gradientUnits="userSpaceOnUse"><stop offset=".237" class="y7hb43rul"/><stop offset="1" class="qw07uw_ui"/></linearGradient><linearGradient id="iVhNsmb" x1="20.438" x2="28.125" y1="4.531" y2="18.218" gradientUnits="userSpaceOnUse"><stop offset=".494" class="e67iwcber"/><stop offset="1" class="xgq3e5b0i"/></linearGradient><linearGradient id="icqdaud" x1="28.438" x2="28.438" y1="10.156" y2="17.781" gradientUnits="userSpaceOnUse"><stop class="e67iwcber"/><stop offset="1" class="xgq3e5b0i"/></linearGradient><linearGradient id="iRteEBb" x1="9.844" x2="14.875" y1="3.156" y2="14.656" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e67iwcber"/><stop offset="1" class="xgq3e5b0i"/></linearGradient><linearGradient id="itIi83d" x1="4.744" x2="6.38" y1="6.041" y2="9.364" gradientUnits="userSpaceOnUse"><stop offset=".397" class="e67iwcber"/><stop offset=".979" class="xgq3e5b0i"/></linearGradient><linearGradient id="i4s9nvd" x1="16.094" x2="17.656" y1="15.969" y2="19.063" gradientUnits="userSpaceOnUse"><stop offset=".397" class="e67iwcber"/><stop offset=".979" class="xgq3e5b0i"/></linearGradient><linearGradient id="iem9Tgd" x1="16.563" x2="12" y1="8.594" y2="16.032" gradientUnits="userSpaceOnUse"><stop class="e67iwcber"/><stop offset="1" class="xgq3e5b0i"/></linearGradient><linearGradient id="im6AIVc" x1="20.359" x2="16.063" y1="15.095" y2="23.095" gradientUnits="userSpaceOnUse"><stop class="e67iwcber"/><stop offset="1" class="xgq3e5b0i"/></linearGradient><linearGradient id="iu2lLQy" x1="15.063" x2="17.672" y1="26.985" y2="19.579" gradientUnits="userSpaceOnUse"><stop offset=".292" class="qljgqobpl"/><stop offset="1" class="xgq3e5b0i"/></linearGradient><linearGradient id="iv3fYHb" x1="16.01" x2="16.01" y1="26.011" y2="30.013" gradientUnits="userSpaceOnUse"><stop offset=".692" class="jvkz25bbn"/><stop offset="1" class="pg_rg__kg"/></linearGradient><linearGradient id="iGGjxob" x1="16.01" x2="16.01" y1="27.594" y2="30.013" gradientUnits="userSpaceOnUse"><stop offset=".661" class="auxfgqb3n"/><stop offset=".844" class="skba2fo6q"/><stop offset="1" class="umv6v2b7l"/></linearGradient><linearGradient id="iO0Cqnc" x1="16.01" x2="16.01" y1="26.011" y2="30.013" gradientUnits="userSpaceOnUse"><stop offset=".911" class="uivaxaccg"/><stop offset="1" class="umv6v2b7l"/></linearGradient><linearGradient id="iTd8qHb" x1="15.913" x2="15.913" y1="26.781" y2="29.625" gradientUnits="userSpaceOnUse"><stop offset=".619" class="ssvd7k35k"/><stop offset="1" class="vo_tnwb6r"/></linearGradient><radialGradient id="ifN9LWc" cx="0" cy="0" r="1" gradientTransform="rotate(111.221 7.328 20.063)scale(1.34421)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="kfgq72i_u"/><stop offset=".461" class="pevgrxbzv"/><stop offset=".957" class="k7_c1yhtd"/></radialGradient><radialGradient id="i2LArOe" cx="0" cy="0" r="1" gradientTransform="rotate(111.221 5.748 20.867)scale(2.73925)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="h0ykatbif"/><stop offset=".461" class="rnf81acdv"/><stop offset=".957" class="arjci5bgz"/></radialGradient><radialGradient id="iYq7NNc" cx="0" cy="0" r="1" gradientTransform="rotate(111.221 7.014 21.624)scale(.93191)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="pbw9n0jhh"/><stop offset=".461" class="u4hq3-flf"/><stop offset=".818" class="t0dzig64x"/></radialGradient><radialGradient id="ilMEFoA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 3 -3 -1.09375 5.844 17.782)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="h0ykatbif"/><stop offset=".461" class="pshc_hb0u"/><stop offset=".957" class="arjci5bgz"/></radialGradient><radialGradient id="iyDu79b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.7 10.797)scale(6.53589)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="uoxp7ftft"/><stop offset=".876" class="cy2qagdrj"/></radialGradient><radialGradient id="iMHwzoc" cx="0" cy="0" r="1" gradientTransform="rotate(103.926 -5.375 13.503)scale(1.27534)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="vfbzk8bpo"/><stop offset=".53" class="anmxslb4w"/><stop offset="1" class="z0d2xxb3n"/></radialGradient><radialGradient id="i55m0QW" cx="0" cy="0" r="1" gradientTransform="rotate(106.467 -6.675 12.811)scale(1.92261)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="vrcpxzbyc"/><stop offset=".577" class="qy7l3qbgo"/><stop offset="1" class="yti69759f"/></radialGradient><radialGradient id="iDl5fke" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.0625 -2.04591 0 5.625 4.594)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="bdhjh1vho"/><stop offset="1" class="atn9e4efy"/></radialGradient><radialGradient id="inlITrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.25 -1.67606 0 2.25 7.031)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="bdhjh1vho"/><stop offset="1" class="atn9e4efy"/></radialGradient><radialGradient id="ii7pVre" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 0 0 2 3.812 10.594)" gradientUnits="userSpaceOnUse"><stop class="xi8pfzbzr"/><stop offset="1" class="co0lo_d5a"/></radialGradient><radialGradient id="ieA0aPd" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 4 -1.4307 1.38599 6.937 12.406)" gradientUnits="userSpaceOnUse"><stop class="xi8pfzbzr"/><stop offset="1" class="co0lo_d5a"/></radialGradient><radialGradient id="iFSFOTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.61514 2.00115 -5.67981 -1.74593 16.625 28.012)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="ldxhz6b5n"/><stop offset="1" class="bg_b5bctm"/></radialGradient><radialGradient id="ij06eIp" cx="0" cy="0" r="1" gradientTransform="rotate(128.55 6.002 20.149)scale(1.30375 3.83392)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="o-9ld_bjg"/><stop offset="1" class="bg_b5bctm"/></radialGradient><radialGradient id="iV7oZfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48154 -6.16284 0 11 27.531)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="u87hq_bbh"/><stop offset=".822" class="y5v5-2uwe"/></radialGradient><radialGradient id="isAg7oc" cx="0" cy="0" r="1" gradientTransform="rotate(137.211 7.513 19.21)scale(1.31109 9.25153)" gradientUnits="userSpaceOnUse"><stop class="lgjf8zwet"/><stop offset="1" class="vahc6tbib"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:coral" /></template>
<style>
.acmzumb1r {
  cx: 4.281px;
  cy: 6.594px;
  r: 0.531px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.anmxslb4w {
  stop-color: var(--svg-color--5db3ed, #5DB3ED);
}

.arjci5bgz {
  stop-color: var(--svg-color--4d77c9, #4D77C9);
}

.atn9e4efy {
  stop-color: var(--svg-color--c3762e, #C3762E);
  stop-opacity: 0;
}

.auxfgqb3n {
  stop-color: var(--svg-color--ac95c4, #AC95C4);
  stop-opacity: 0;
}

.b8urqqrmv {
  cx: 27.906px;
  cy: 10.125px;
  r: 0.5px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.bdhjh1vho {
  stop-color: var(--svg-color--ca7924, #CA7924);
}

.bg_b5bctm {
  stop-color: var(--svg-color--bdb4c5, #BDB4C5);
  stop-opacity: 0;
}

.bgq3ejbuh {
  cx: 8.25px;
  cy: 3.188px;
  r: 0.563px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.bk321llui {
  cx: 15.781px;
  cy: 9.156px;
  r: 0.531px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.butrocbrn {
  d: path("M5.098 20.248a1.876 1.876 0 1 0 0-3.752a1.876 1.876 0 0 0 0 3.752");
}

.c0t7wobvu {
  fill: var(--svg-color--ee8246, #EE8246);
  d: path("M23.625 19.25v-5.72c1.25 1.97 2.989.845 4.375.845c-1.344 1.656-3.781 3.312-3.781 3.312c-.242.405-.494 1.135-.594 1.563");
}

.c6418fb3w {
  fill-rule: evenodd;
  d: path("M17.557 19.657a.33.33 0 0 1 .037.463l-.55.645a3.4 3.4 0 0 0-.81 2.199v3.693a.328.328 0 0 1-.656 0v-3.693c0-.962.343-1.892.966-2.625l.55-.645a.33.33 0 0 1 .462-.037");
}

.chqb3ku-a {
  stop-color: var(--svg-color--d7882c, #D7882C);
}

.cky6dx4yb {
  fill: var(--svg-color--e68245, #E68245);
  d: path("M14.026 9.335v.744c0 .801-.407 1.549-1.08 1.985l-.02.013a2.33 2.33 0 0 1-2.527 0l-.029-.02a2.37 2.37 0 0 1-1.087-1.988V3.357a1.332 1.332 0 0 0-2.662 0v3.922a.68.68 0 0 1-.683.683a.68.68 0 0 1-.683-.683v-.436a1.332 1.332 0 0 0-2.662 0v2.254c0 .84.68 1.524 1.524 1.524h1.821c.379 0 .686.307.686.686c0 .933.475 1.806 1.258 2.312l1.667 1.078c.484.31.776.85.776 1.424v2.809a.28.28 0 0 1-.452.221l-.186-.144a1.332 1.332 0 0 0-1.629 2.104l1.972 1.523a.76.76 0 0 1 .295.603v6.777h2.662V16.126c0-.577.292-1.113.776-1.424l1.212-.782a3.75 3.75 0 0 0 1.713-3.146V9.338a1.332 1.332 0 0 0-2.662-.003");
}

.co0lo_d5a {
  stop-color: var(--svg-color--c1683d, #C1683D);
  stop-opacity: 0;
}

.cy2qagdrj {
  stop-color: var(--svg-color--3c7ed4, #3C7ED4);
}

.d39ijacga {
  cx: 23.969px;
  cy: 3.094px;
  r: 0.531px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.d5qhtknfx {
  d: path("M6.13 23.012a.763.763 0 1 0 0-1.526a.763.763 0 0 0 0 1.526");
}

.e67iwcber {
  stop-color: var(--svg-color--f6b461, #F6B461);
}

.e7xy98byx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M15.844 9.094v1.657c0 1.812-2.906 3.343-2.906 3.343");
}

.eaejiub5t {
  stop-color: var(--svg-color--df4909, #DF4909);
}

.etjg9f6ij {
  cx: 9.274px;
  cy: 19.778px;
  fill: var(--svg-color--e8844b, #E8844B);
  rx: 0.82px;
  ry: 0.422px;
}

.f-ab535jf {
  stop-color: var(--svg-color--df5a25, #DF5A25);
}

.f27wv-bcn {
  fill: var(--svg-color--e58c47, #E58C47);
  d: path("M15.438 23.094v-5.75c1.418 1.656 2.707 1.25 4.093 1.25c-2.192.625-3.642 3.625-4.093 4.5");
}

.f35lrjb7a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M27.938 10.156v4.187");
}

.ft5dv1b6b {
  fill: none;
}

.fv0v_ebpu {
  d: path("m4.944 29.272l1.36-1.62a4.6 4.6 0 0 1 3.521-1.641h4.095a4.6 4.6 0 0 1 3.137 1.238l.041.041a2.7 2.7 0 0 0 1.835.725h1.388c.677 0 1.318-.311 1.735-.843a2.09 2.09 0 0 1 3.255-.039l1.767 2.142a.45.45 0 0 1-.35.738H5.29a.45.45 0 0 1-.346-.74");
}

.g40pm_btx {
  d: path("M26.578 25.173a1.555 1.555 0 1 0 0-3.11a1.555 1.555 0 0 0 0 3.11");
}

.g9w9_rbjt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M15.813 16.313v1.096c0 .529.312 1.122 1.374 1.122");
}

.glwuqabow {
  stop-color: var(--svg-color--da8930, #DA8930);
}

.h0ykatbif {
  stop-color: var(--svg-color--84e4ff, #84E4FF);
}

.hl2mn-rsx {
  d: path("m5.856 29.098l1.135-1.057c.868-.738 1.585-1.26 2.938-1.26h3.925c2.54 0 1.808 1.777 4.618 1.777h1.899c2.307 0 1.892-1.52 3.288-1.52c1.425 0 1.403 1.035 2.309 2.062c.253.287.031.524-.348.524H6.2c-.382 0-.59-.316-.344-.526");
}

.iydjqdb3g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M8.438 3.156v7.281c0 .688.937 2.656 2.812 2.656");
}

.jvkz25bbn {
  stop-color: var(--svg-color--77767e, #77767E);
}

.jy5ziozje {
  d: path("M27.48 9.135a1.29 1.29 0 0 0-1.29 1.29v2.921a.649.649 0 1 1-1.299 0V3.29a1.29 1.29 0 0 0-2.578 0v5.98a.35.35 0 0 1-.568.273l-.292-.24a1.287 1.287 0 0 0-1.811.201a1.287 1.287 0 0 0 .202 1.812l2.04 1.639c.272.218.429.545.429.895v4.807c0 .532-.244 1.036-.657 1.37l-2.55 2.039a2.16 2.16 0 0 0-.811 1.69v6.167h2.578V24.42a.98.98 0 0 1 .362-.757l2.999-2.399a1.75 1.75 0 0 0 .657-1.37v-1.346c0-.35.158-.677.43-.895l2.902-2.322c.344-.275.546-.692.546-1.132v-3.774a1.29 1.29 0 0 0-1.29-1.29");
}

.k-yh91bid {
  fill: var(--svg-color--ee7546, #EE7546);
  d: path("M10.938 19.844c-.485 0-1.782-.219-1.782-.219l2.906 3v-2.781z");
}

.k7_c1yhtd {
  stop-color: var(--svg-color--4daaec, #4DAAEC);
}

.kfgq72i_u {
  stop-color: var(--svg-color--86e6ff, #86E6FF);
}

.kg-46h68l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M4.438 6.938v.565c0 .528.437 1.263 1.5 1.263");
}

.khjq9208f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M24.063 3.156V13.5c.02.374.274 1.28 1.125 1.28");
}

.ldxhz6b5n {
  stop-color: var(--svg-color--beb5c5, #BEB5C5);
}

.lgjf8zwet {
  stop-color: var(--svg-color--c8c2ce, #C8C2CE);
}

.lw35ocqzs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-656px, 0.656px);
  d: path("M12.25 15.97v10.437");
}

.ngkfjzbpc {
  fill: var(--svg-color--fa7f50, #FA7F50);
  fill-rule: evenodd;
  d: path("M23.875 17.454c.181 0 .328.147.328.328v1.76a1.89 1.89 0 0 1-.692 1.463l-2.668 2.187a1.24 1.24 0 0 0-.452.955v3.885a.328.328 0 0 1-.657 0v-3.885c0-.567.254-1.103.692-1.463l2.669-2.187c.286-.234.452-.585.452-.955v-1.76c0-.181.147-.328.328-.328");
}

.nn3h6bb4s {
  d: path("M14.026 9.335v.744c0 .801-.407 1.549-1.08 1.985l-.02.013a2.33 2.33 0 0 1-2.527 0l-.029-.02a2.37 2.37 0 0 1-1.087-1.988V3.357a1.332 1.332 0 0 0-2.662 0v3.922a.68.68 0 0 1-.683.683a.68.68 0 0 1-.683-.683v-.436a1.332 1.332 0 0 0-2.662 0v2.254c0 .84.68 1.524 1.524 1.524h1.821c.379 0 .686.307.686.686c0 .933.475 1.806 1.258 2.312l1.667 1.078c.484.31.776.85.776 1.424v2.809a.28.28 0 0 1-.452.221l-.186-.144a1.332 1.332 0 0 0-1.629 2.104l1.972 1.523a.76.76 0 0 1 .295.603v6.777h2.662V16.126c0-.577.292-1.113.776-1.424l1.212-.782a3.75 3.75 0 0 0 1.713-3.146V9.338a1.332 1.332 0 0 0-2.662-.003");
}

.nu47yacom {
  d: path("M19.635 13.448c-.699 0-1.263.564-1.263 1.264v2.337a.8.8 0 0 1-1.6 0v-.327c0-.699-.565-1.263-1.264-1.263s-1.264.564-1.264 1.263v12.982h2.527V23.46a3.57 3.57 0 0 1 1.658-3.014l1.251-.796a2.62 2.62 0 0 0 1.219-2.216v-2.722c0-.7-.565-1.264-1.264-1.264");
}

.num8wjb6y {
  cx: 20.063px;
  cy: 14.438px;
  r: 0.5px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.o-9ld_bjg {
  stop-color: var(--svg-color--cac4d0, #CAC4D0);
}

.o-m2accnh {
  fill: var(--svg-color--e68245, #E68245);
  d: path("M27.48 9.135a1.29 1.29 0 0 0-1.29 1.29v2.921a.649.649 0 1 1-1.299 0V3.29a1.29 1.29 0 0 0-2.578 0v5.98a.35.35 0 0 1-.568.273l-.292-.24a1.287 1.287 0 0 0-1.811.201a1.287 1.287 0 0 0 .202 1.812l2.04 1.639c.272.218.429.545.429.895v4.807c0 .532-.244 1.036-.657 1.37l-2.55 2.039a2.16 2.16 0 0 0-.811 1.69v6.167h2.578V24.42a.98.98 0 0 1 .362-.757l2.999-2.399a1.75 1.75 0 0 0 .657-1.37v-1.346c0-.35.158-.677.43-.895l2.902-2.322c.344-.275.546-.692.546-1.132v-3.774a1.29 1.29 0 0 0-1.29-1.29");
}

.pbw9n0jhh {
  stop-color: var(--svg-color--83dfff, #83DFFF);
}

.pevgrxbzv {
  stop-color: var(--svg-color--64c9ff, #64C9FF);
}

.pg_rg__kg {
  stop-color: var(--svg-color--8a5fad, #8A5FAD);
}

.pqrll2b3h {
  fill: var(--svg-color--e98847, #E98847);
  d: path("M12.031 18.344c0-2.875-1.5-4.969-2.562-5.719c1.625.844 4.75.344 4.75.344c-1.594 1-2.188 5.375-2.188 5.375");
}

.pshc_hb0u {
  stop-color: var(--svg-color--66bfff, #66BFFF);
}

.qljgqobpl {
  stop-color: var(--svg-color--f7814f, #F7814F);
}

.qw07uw_ui {
  stop-color: var(--svg-color--f68151, #F68151);
  stop-opacity: 0;
}

.qy7l3qbgo {
  stop-color: var(--svg-color--62bdfb, #62BDFB);
}

.rnf81acdv {
  stop-color: var(--svg-color--72cbff, #72CBFF);
}

.s57p5bfun {
  fill-rule: evenodd;
  d: path("M20.031 14.141c.181 0 .328.147.328.329v1.85a3.86 3.86 0 0 1-1.996 3.381l-1.236.68a.328.328 0 0 1-.317-.574l1.236-.68a3.2 3.2 0 0 0 1.657-2.806v-1.852c0-.18.147-.328.328-.328");
}

.skba2fo6q {
  stop-color: var(--svg-color--9b73be, #9B73BE);
}

.ssvd7k35k {
  stop-color: var(--svg-color--ad9ac1, #AD9AC1);
}

.t0dzig64x {
  stop-color: var(--svg-color--53abee, #53ABEE);
}

.t1hpzx_jo {
  d: path("M28.339 21.53a.763.763 0 1 0 0-1.526a.763.763 0 0 0 0 1.526");
}

.u4hq3-flf {
  stop-color: var(--svg-color--67cdff, #67CDFF);
}

.u87hq_bbh {
  stop-color: var(--svg-color--a598a0, #A598A0);
}

.uivaxaccg {
  stop-color: var(--svg-color--8b60af, #8B60AF);
  stop-opacity: 0;
}

.ukr738bor {
  fill: var(--svg-color--e68245, #E68245);
  d: path("M19.635 13.448c-.699 0-1.263.564-1.263 1.264v2.337a.8.8 0 0 1-1.6 0v-.327c0-.699-.565-1.263-1.264-1.263s-1.264.564-1.264 1.263v12.982h2.527V23.46a3.57 3.57 0 0 1 1.658-3.014l1.251-.796a2.62 2.62 0 0 0 1.219-2.216v-2.722c0-.7-.565-1.264-1.264-1.264");
}

.umv6v2b7l {
  stop-color: var(--svg-color--8d64b0, #8D64B0);
}

.uoxp7ftft {
  stop-color: var(--svg-color--4579cc, #4579CC);
  stop-opacity: 0;
}

.upngrabwy {
  cx: 21.024px;
  cy: 10.028px;
  fill: var(--svg-color--f4b35c, #F4B35C);
  rx: 0.82px;
  ry: 0.422px;
}

.uu78lrbyq {
  cx: 15.688px;
  cy: 16.375px;
  r: 0.5px;
  fill: var(--svg-color--f4b35c, #F4B35C);
}

.vahc6tbib {
  stop-color: var(--svg-color--cac4d1, #CAC4D1);
  stop-opacity: 0;
}

.vfbzk8bpo {
  stop-color: var(--svg-color--78c3f2, #78C3F2);
}

.vo_tnwb6r {
  stop-color: var(--svg-color--a27bc4, #A27BC4);
}

.vrcpxzbyc {
  stop-color: var(--svg-color--7ad5ff, #7AD5FF);
}

.wucpt0bvm {
  d: path("M3.174 24.388a1.174 1.174 0 1 0 0-2.348a1.174 1.174 0 0 0 0 2.348");
}

.xgq3e5b0i {
  stop-color: var(--svg-color--f6b461, #F6B461);
  stop-opacity: 0;
}

.xi8pfzbzr {
  stop-color: var(--svg-color--be6543, #BE6543);
}

.y5v5-2uwe {
  stop-color: var(--svg-color--a598a1, #A598A1);
  stop-opacity: 0;
}

.y7hb43rul {
  stop-color: var(--svg-color--ff8d5e, #FF8D5E);
}

.yeahgsb6k {
  d: path("M29.47 23.631a.53.53 0 1 0 0-1.058a.53.53 0 0 0 0 1.058");
}

.yti69759f {
  stop-color: var(--svg-color--4a88db, #4A88DB);
}

.z0d2xxb3n {
  stop-color: var(--svg-color--508ccf, #508CCF);
}

.z69k69bex {
  stop-color: var(--svg-color--d27b25, #D27B25);
}

</style>
