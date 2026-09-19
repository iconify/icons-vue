<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="g32wlt45e"/><path fill="url(#iaTUUpb)" class="sfjwbcb-x"/><path fill="url(#iNUkUTb)" class="sfjwbcb-x"/><path fill="url(#insgrni)" class="mh4dp7bat"/><path fill="url(#iRFo5Pb)" class="mh4dp7bat"/><path fill="url(#ijjQ9ic)" class="w_xdtob7b"/><path fill="url(#idkRQPb)" class="w_xdtob7b"/><path fill="url(#is20R5b)" class="w_xdtob7b"/><path fill="url(#izwmvFt)" class="fopy3bvxv"/><path fill="url(#iJUWizd)" class="qcvj0gbex"/><path fill="url(#iVdjsxK)" class="qcvj0gbex"/><path fill="url(#i2HeT2F)" class="qcvj0gbex"/><path fill="url(#iihx1mc)" class="qcvj0gbex"/><path fill="url(#iUHtYCc)" class="qcvj0gbex"/><path class="wnr6kunic"/><path fill="url(#iQ42icb)" class="fwf51yihr"/><path fill="url(#iZtRQcb)" class="fwf51yihr"/><path fill="url(#ib4oaPZ)" class="fwf51yihr"/><path class="fe4j9ob_f"/><path fill="url(#iz7tESb)" class="lw_27mc8s"/><path fill="url(#iqB9G3b)" class="lw_27mc8s"/><path fill="url(#isHj1re)" class="lw_27mc8s"/><path fill="url(#iNCPnQd)" class="lw_27mc8s"/><g filter="url(#iP4rPMe)"><path fill="url(#iLp8k6d)" class="hl8e7dbsa"/><path fill="url(#iKtcaza)" class="hl8e7dbsa"/><path fill="url(#iu4EaKb)" class="hl8e7dbsa"/><path fill="url(#irzmxbb)" class="hl8e7dbsa"/><path fill="url(#ixbbNzd)" class="hl8e7dbsa"/><path fill="url(#iO8zlbb)" class="hl8e7dbsa"/><path fill="url(#ipFlp8d)" class="hl8e7dbsa"/></g><path fill="url(#i6mgotb)" class="hl8e7dbsa"/><path fill="url(#i9ZKItc)" class="hl8e7dbsa"/><path fill="url(#iauFX1b)" class="hl8e7dbsa"/><g filter="url(#iHwn86d)"><path fill="url(#ibkF0gc)" class="a5whq9lor"/></g><path fill="url(#i4c7Ulc)" class="opi0ugblw"/><path fill="url(#iaxXXkb)" class="opi0ugblw"/><path fill="url(#i9trOdI)" class="opi0ugblw"/><path fill="url(#ifVy7sU)" class="opi0ugblw"/><path fill="url(#iQoglFe)" class="z1d5_j39w"/><path fill="url(#i9sNQsb)" class="z1d5_j39w"/><path fill="url(#iqCyK9E)" class="z1d5_j39w"/><path fill="url(#iNkeNsc)" class="nu7lwng9n"/><path fill="url(#iymELrp)" class="qgx435bwi"/><path fill="url(#i3gi8eb)" class="ar59qcbly"/><path fill="url(#iFRlNoX)" class="ar59qcbly"/><path fill="url(#idO933e)" class="ar59qcbly"/><path fill="url(#inw3Cfe)" class="ar59qcbly"/><path fill="url(#i25S2Tb)" class="ar59qcbly"/><g filter="url(#ievk9He)"><path stroke="url(#i2HZ9Yd)" class="db3p49aaa"/></g><g filter="url(#i9FHoFb)"><path fill="url(#in53aWv)" class="u3l9-71on"/></g><g filter="url(#iH6UTab)"><path stroke="url(#iYDpnkb)" class="fz62myebs"/></g><g filter="url(#ilGPXre)"><path class="uzmp_lqil"/></g><g filter="url(#i1euIeE)"><path fill="url(#iXp5Lke)" class="xze5rvixq"/></g><g filter="url(#iRLFs0c)"><path fill="url(#i4qGVTc)" class="fdxd9pb8r"/></g><defs><linearGradient id="iaTUUpb" x1="11.025" x2="11.025" y1="21.938" y2="26.625" gradientUnits="userSpaceOnUse"><stop class="ihkljfbkz"/><stop offset="1" class="thjj84bru"/></linearGradient><linearGradient id="iNUkUTb" x1="8.859" x2="9.313" y1="24.938" y2="24.938" gradientUnits="userSpaceOnUse"><stop class="zczubmbiz"/><stop offset="1" class="c45wmnb4u"/></linearGradient><linearGradient id="insgrni" x1="10.086" x2="11.611" y1="27.75" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="v8t4bs_gr"/><stop offset="1" class="ymqdvbijo"/></linearGradient><linearGradient id="iRFo5Pb" x1="10.545" x2="10.545" y1="28.981" y2="28.05" gradientUnits="userSpaceOnUse"><stop class="z055jt8rg"/><stop offset="1" class="ccjbm_brj"/></linearGradient><linearGradient id="idkRQPb" x1="19.209" x2="20.49" y1="24.563" y2="24.563" gradientUnits="userSpaceOnUse"><stop class="dgt7pqr8u"/><stop offset="1" class="uaurr1bqq"/></linearGradient><linearGradient id="izwmvFt" x1="22.281" x2="21.406" y1="22.281" y2="23.469" gradientUnits="userSpaceOnUse"><stop class="bvwlkdb1l"/><stop offset="1" class="tjhdkxihf"/></linearGradient><linearGradient id="iJUWizd" x1="19" x2="22.35" y1="27.75" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="v8t4bs_gr"/><stop offset="1" class="ymqdvbijo"/></linearGradient><linearGradient id="iVdjsxK" x1="20.624" x2="20.624" y1="28.969" y2="28.047" gradientUnits="userSpaceOnUse"><stop class="z055jt8rg"/><stop offset="1" class="ccjbm_brj"/></linearGradient><linearGradient id="iihx1mc" x1="18.344" x2="18.938" y1="27.75" y2="28.172" gradientUnits="userSpaceOnUse"><stop class="r4iofnb-j"/><stop offset=".994" class="klbh0c2mx"/></linearGradient><linearGradient id="iUHtYCc" x1="17.969" x2="18.75" y1="27.625" y2="28.125" gradientUnits="userSpaceOnUse"><stop class="fsrvss9hi"/><stop offset="1" class="gf_krnbkn"/></linearGradient><linearGradient id="iQ42icb" x1="5.234" x2="4.641" y1="13.75" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="cv_pv5blk"/><stop offset="1" class="ghf0lby8r"/></linearGradient><linearGradient id="iZtRQcb" x1="4.578" x2="4.578" y1="11.703" y2="11.93" gradientUnits="userSpaceOnUse"><stop class="cv_pv5blk"/><stop offset="1" class="ghf0lby8r"/></linearGradient><linearGradient id="ib4oaPZ" x1="5" x2="5" y1="14.516" y2="13.172" gradientUnits="userSpaceOnUse"><stop class="swb29-h5o"/><stop offset="1" class="ip1sc_bbu"/></linearGradient><linearGradient id="isHj1re" x1="17.5" x2="10.313" y1="5.719" y2="5.719" gradientUnits="userSpaceOnUse"><stop class="fyc-4abkn"/><stop offset="1" class="qqrguzb7l"/></linearGradient><linearGradient id="iLp8k6d" x1="16" x2="16" y1="8.063" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="wxdpcmb4d"/><stop offset="1" class="m1itpp0ta"/></linearGradient><linearGradient id="iu4EaKb" x1="4.359" x2="4.784" y1="7.484" y2="7.921" gradientUnits="userSpaceOnUse"><stop class="pmliezbwq"/><stop offset="1" class="w9jli312m"/></linearGradient><linearGradient id="irzmxbb" x1="6.914" x2="6.962" y1="5.898" y2="6.587" gradientUnits="userSpaceOnUse"><stop class="pmliezbwq"/><stop offset="1" class="w9jli312m"/></linearGradient><linearGradient id="ibkF0gc" x1="10.766" x2="14.828" y1="7.031" y2="16.234" gradientUnits="userSpaceOnUse"><stop class="bd4q4v_3f"/><stop offset="1" class="ccrhbefnm"/></linearGradient><linearGradient id="i4c7Ulc" x1="10.5" x2="12.563" y1="27.75" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="v8t4bs_gr"/><stop offset="1" class="ymqdvbijo"/></linearGradient><linearGradient id="iaxXXkb" x1="11.5" x2="11.5" y1="28.969" y2="28.047" gradientUnits="userSpaceOnUse"><stop class="z055jt8rg"/><stop offset="1" class="ccjbm_brj"/></linearGradient><linearGradient id="ifVy7sU" x1="9.859" x2="10.281" y1="28.109" y2="28.109" gradientUnits="userSpaceOnUse"><stop class="fsrvss9hi"/><stop offset="1" class="gf_krnbkn"/></linearGradient><linearGradient id="iQoglFe" x1="27.5" x2="29.563" y1="27.75" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="v8t4bs_gr"/><stop offset="1" class="ymqdvbijo"/></linearGradient><linearGradient id="i9sNQsb" x1="28.5" x2="28.5" y1="28.969" y2="28.047" gradientUnits="userSpaceOnUse"><stop class="z055jt8rg"/><stop offset="1" class="ccjbm_brj"/></linearGradient><linearGradient id="i3gi8eb" x1="9.25" x2="10.641" y1="8.422" y2="10.906" gradientUnits="userSpaceOnUse"><stop class="de10q8ijx"/><stop offset="1" class="rckfg0wkx"/></linearGradient><linearGradient id="iFRlNoX" x1="11.094" x2="10.125" y1="11.906" y2="10.609" gradientUnits="userSpaceOnUse"><stop class="w713edc-u"/><stop offset="1" class="l6n77kbkb"/></linearGradient><linearGradient id="inw3Cfe" x1="11.43" x2="10.938" y1="9.66" y2="9.984" gradientUnits="userSpaceOnUse"><stop offset=".374" class="zw1cumbgm"/><stop offset=".717" class="w9jli312m"/></linearGradient><linearGradient id="i2HZ9Yd" x1="29.813" x2="29.813" y1="27.922" y2="18.375" gradientUnits="userSpaceOnUse"><stop class="sk6zy067z"/><stop offset=".985" class="v3m_ugmll"/></linearGradient><linearGradient id="iYDpnkb" x1="16.031" x2="10.656" y1="4.563" y2="5.359" gradientUnits="userSpaceOnUse"><stop class="tsxieuaax"/><stop offset="1" class="tk8b2rg-x"/></linearGradient><linearGradient id="iXp5Lke" x1="14.395" x2="12.238" y1="24.594" y2="24.594" gradientUnits="userSpaceOnUse"><stop class="flrjexbrq"/><stop offset="1" class="a_734ybsi"/></linearGradient><linearGradient id="i4qGVTc" x1="27.724" x2="28.59" y1="9.844" y2="11.196" gradientUnits="userSpaceOnUse"><stop class="bd4q4v_3f"/><stop offset="1" class="ccrhbefnm"/></linearGradient><radialGradient id="ijjQ9ic" cx="0" cy="0" r="1" gradientTransform="matrix(1.26001 -7.34375 4.97635 .85382 21.677 24.469)" gradientUnits="userSpaceOnUse"><stop class="nfz20qi0y"/><stop offset="1" class="slq0uobcb"/></radialGradient><radialGradient id="is20R5b" cx="0" cy="0" r="1" gradientTransform="rotate(-57.804 34.317 -4.233)scale(1.99413 1.44862)" gradientUnits="userSpaceOnUse"><stop class="nfz20qi0y"/><stop offset="1" class="xr2depxri"/></radialGradient><radialGradient id="i2HeT2F" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04686 1.32813 -.81725 -.64417 22.063 26.422)" gradientUnits="userSpaceOnUse"><stop class="r4iofnb-j"/><stop offset=".994" class="klbh0c2mx"/></radialGradient><radialGradient id="iz7tESb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62498 -2.53126 3.13022 -2.00949 13.906 5.5)" gradientUnits="userSpaceOnUse"><stop class="in79t5xxu"/><stop offset="1" class="zlmarccne"/></radialGradient><radialGradient id="iqB9G3b" cx="0" cy="0" r="1" gradientTransform="rotate(-152.851 7.287 1.829)scale(5.68427 5.03229)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="tk8b2rg-x"/><stop offset=".987" class="tsxieuaax"/></radialGradient><radialGradient id="iNCPnQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.14844 -1.47657 2.51144 -.25247 11.18 6.133)" gradientUnits="userSpaceOnUse"><stop class="li_eerpsf"/><stop offset="1" class="hf5ptib8a"/></radialGradient><radialGradient id="iKtcaza" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 -3.4375 2.49577 2.2235 2.906 14.156)" gradientUnits="userSpaceOnUse"><stop class="l6y5qb8ul"/><stop offset="1" class="zi7dalv6c"/></radialGradient><radialGradient id="ixbbNzd" cx="0" cy="0" r="1" gradientTransform="rotate(142.001 5.388 5.316)scale(3.80699 4.51561)" gradientUnits="userSpaceOnUse"><stop class="pmliezbwq"/><stop offset="1" class="w9jli312m"/></radialGradient><radialGradient id="iO8zlbb" cx="0" cy="0" r="1" gradientTransform="rotate(-15.018 79.257 -13.913)scale(7.95937 13.0378)" gradientUnits="userSpaceOnUse"><stop class="ixbywdoml"/><stop offset="1" class="eq-5p5h-d"/></radialGradient><radialGradient id="ipFlp8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.9375 14.6875 0 18.063 23.5)" gradientUnits="userSpaceOnUse"><stop class="ixbywdoml"/><stop offset="1" class="eq-5p5h-d"/></radialGradient><radialGradient id="i6mgotb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.06245 -11.81255 6.91592 -5.30581 20.625 27.063)" gradientUnits="userSpaceOnUse"><stop class="l6y5qb8ul"/><stop offset=".785" class="zi7dalv6c"/></radialGradient><radialGradient id="i9ZKItc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.96875 -8.53125 0 20.344 10.719)" gradientUnits="userSpaceOnUse"><stop class="xrtnzub7r"/><stop offset="1" class="grqd8bwrj"/></radialGradient><radialGradient id="iauFX1b" cx="0" cy="0" r="1" gradientTransform="rotate(57.061 3.015 28.149)scale(2.64372 2.1746)" gradientUnits="userSpaceOnUse"><stop class="ckd42ub3v"/><stop offset="1" class="grqd8bwrj"/></radialGradient><radialGradient id="i9trOdI" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -.59375 0 12.36 26.656)" gradientUnits="userSpaceOnUse"><stop class="r4iofnb-j"/><stop offset="1" class="klbh0c2mx"/></radialGradient><radialGradient id="iqCyK9E" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -.59375 0 29.36 26.656)" gradientUnits="userSpaceOnUse"><stop class="r4iofnb-j"/><stop offset="1" class="klbh0c2mx"/></radialGradient><radialGradient id="iNkeNsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4919 -2.17473 0 3.44 10.06)" gradientUnits="userSpaceOnUse"><stop class="mqpbk469p"/><stop offset="1" class="ldgjpwb0m"/></radialGradient><radialGradient id="iymELrp" cx="0" cy="0" r="1" gradientTransform="matrix(-.29167 0 0 -1.19336 6.644 8.75)" gradientUnits="userSpaceOnUse"><stop class="mqpbk469p"/><stop offset="1" class="ldgjpwb0m"/></radialGradient><radialGradient id="idO933e" cx="0" cy="0" r="1" gradientTransform="rotate(115.899 2.998 7.891)scale(3.00492 4.34224)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="q4q5f9p5h"/><stop offset="1" class="a91l79bzd"/></radialGradient><radialGradient id="i25S2Tb" cx="0" cy="0" r="1" gradientTransform="matrix(-.89844 -.10157 .07985 -.70633 12.133 10.945)" gradientUnits="userSpaceOnUse"><stop class="zw1cumbgm"/><stop offset=".794" class="w9jli312m"/></radialGradient><radialGradient id="in53aWv" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.25195 -3.53106 0 25.206 14.347)" gradientUnits="userSpaceOnUse"><stop class="l3j7gju_q"/><stop offset="1" class="a_734ybsi"/></radialGradient><filter id="iP4rPMe" width="28.25" height="23.25" x="2" y="5.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.666667 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3233"/></filter><filter id="iHwn86d" width="7.812" height="11.966" x="8.006" y="4.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".8"/></filter><filter id="ievk9He" width="5.105" height="9.493" x="24.926" y="19.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".5"/></filter><filter id="i9FHoFb" width="6.537" height="10.255" x="21.463" y="12.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".5"/></filter><filter id="iH6UTab" width="6.98" height="2.762" x="9.131" y="2.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".15"/></filter><filter id="ilGPXre" width=".711" height="2.082" x="4.357" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".125"/></filter><filter id="i1euIeE" width="3.672" height="6.719" x="10.785" y="20.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".5"/></filter><filter id="iRLFs0c" width="2.281" height="4.625" x="26.094" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3233" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:goat" /></template>
<style>
.a_734ybsi {
  stop-color: var(--svg-color--ebad78, #EBAD78);
  stop-opacity: 0;
}

.a5whq9lor {
  d: path("m14.219 13.203l-3.34-6.252a.676.676 0 0 0-1.253.479l1.937 7.93z");
}

.a91l79bzd {
  stop-color: var(--svg-color--be764d, #BE764D);
}

.ar59qcbly {
  d: path("M9.668 10.686L8.597 9.343l1.287-1.157a.25.25 0 0 1 .381.058l1.548 2.587a.4.4 0 0 1-.343.605h-.239a2 2 0 0 1-1.563-.751");
}

.bd4q4v_3f {
  stop-color: var(--svg-color--f6b883, #F6B883);
}

.bvwlkdb1l {
  stop-color: var(--svg-color--9f4834, #9F4834);
}

.c45wmnb4u {
  stop-color: var(--svg-color--c18d71, #C18D71);
  stop-opacity: 0;
}

.ccjbm_brj {
  stop-color: var(--svg-color--6a3568, #6A3568);
  stop-opacity: 0;
}

.ccrhbefnm {
  stop-color: var(--svg-color--f6b883, #F6B883);
  stop-opacity: 0;
}

.ckd42ub3v {
  stop-color: var(--svg-color--c77c41, #C77C41);
}

.cv_pv5blk {
  stop-color: var(--svg-color--7d6776, #7D6776);
}

.db3p49aaa {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m26.016 20.516l2.89 2.968v4.438");
}

.de10q8ijx {
  stop-color: var(--svg-color--dd9f64, #DD9F64);
}

.dgt7pqr8u {
  stop-color: var(--svg-color--cfb1a2, #CFB1A2);
}

.eq-5p5h-d {
  stop-color: var(--svg-color--b36b43, #B36B43);
  stop-opacity: 0;
}

.fdxd9pb8r {
  d: path("M26.844 9.336v3.125h.781V10.18z");
}

.fe4j9ob_f {
  fill: var(--svg-color--888485, #888485);
  d: path("M16 4.55a.4.4 0 0 0-.08-.23a4.5 4.5 0 0 0-3.42-1.57c-2.05 0-4.054 1.445-4.594 3.375c-.18.64.584 1.345 1.244 1.345c.46 0 .86-.32.98-.77c.38-1.5 1.85-2.45 3.37-2.45c.72 0 1.39.177 1.95.547c.24.16.55.033.55-.247");
}

.flrjexbrq {
  stop-color: var(--svg-color--ebad78, #EBAD78);
}

.fopy3bvxv {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.99 20.75v4.78c0 .15-.03.29-.1.42l-1.67 2.35c-.1.21.05.45.28.45h2.03c.3 0 .57-.14.75-.38l2.41-2.2c.2-.27.31-.6.31-.94v-4.48z");
}

.fsrvss9hi {
  stop-color: var(--svg-color--968887, #968887);
}

.ft5dv1b6b {
  fill: none;
}

.fwf51yihr {
  d: path("M5 13.75h-.09c-.69 0-1.24-.56-1.24-1.24v-1.42H5z");
}

.fyc-4abkn {
  stop-color: var(--svg-color--bcb6be, #BCB6BE);
}

.fz62myebs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.71 4.484c-.442-.427-1.716-1.318-3.429-1.03c-1.616.27-2.5 1.437-2.75 1.905");
}

.g32wlt45e {
  fill: var(--svg-color--aa5e40, #AA5E40);
  d: path("M9.05 28.45c0 .17.14.31.31.31l2.38-.01c.17 0 .31-.14.31-.31l-.01-2.42c0-.17.06-.33.18-.44c.52-.53.81-1.24.81-1.98l-.01-3.85l-4 .02z");
}

.gf_krnbkn {
  stop-color: var(--svg-color--968887, #968887);
  stop-opacity: 0;
}

.ghf0lby8r {
  stop-color: var(--svg-color--7d6776, #7D6776);
  stop-opacity: 0;
}

.grqd8bwrj {
  stop-color: var(--svg-color--cb844b, #CB844B);
  stop-opacity: 0;
}

.hf5ptib8a {
  stop-color: var(--svg-color--7b7072, #7B7072);
  stop-opacity: 0;
}

.hl8e7dbsa {
  d: path("M28.27 21.03a.98.98 0 0 1-.27-.66v-9.62c0-.88-.57-1.62-1.35-1.89a.486.486 0 0 0-.65.46v1.93c0 .28-.22.5-.5.5H15.16c-.71 0-1.36-.4-1.68-1.04l-1.79-3.58a2.51 2.51 0 0 0-2.24-1.38H6.91c-.58 0-1.14.23-1.55.64L2.31 9.44c-.2.2-.31.47-.31.75c0 .86.7 1.56 1.56 1.56h1.43c.2 0 .38.13.44.33l1.78 7a3.93 3.93 0 0 0 2.027 2.408c.425.204.763.6.763 1.07v5.872c0 .18.14.32.31.32h2.38c.17 0 .31-.14.31-.31v-2.42c0-.17.07-.32.18-.44c.53-.53.82-1.24.82-1.98v-1.35a.5.5 0 0 1 .5-.5h6.6c.2 0 .39.06.55.17l5.09 3.64c.16.12.26.31.26.52v2.36c0 .17.14.31.31.31h2.38c.17 0 .31-.14.31-.31V23.4c0-.41-.16-.81-.46-1.1z");
}

.ihkljfbkz {
  stop-color: var(--svg-color--a85735, #A85735);
}

.in79t5xxu {
  stop-color: var(--svg-color--aa8eb6, #AA8EB6);
}

.ip1sc_bbu {
  stop-color: var(--svg-color--8b607e, #8B607E);
  stop-opacity: 0;
}

.ixbywdoml {
  stop-color: var(--svg-color--b36b43, #B36B43);
}

.klbh0c2mx {
  stop-color: var(--svg-color--7a5559, #7A5559);
  stop-opacity: 0;
}

.l3j7gju_q {
  stop-color: var(--svg-color--ebad78, #EBAD78);
  stop-opacity: 0.5;
}

.l6n77kbkb {
  stop-color: var(--svg-color--cf8769, #CF8769);
  stop-opacity: 0;
}

.l6y5qb8ul {
  stop-color: var(--svg-color--b13e76, #B13E76);
}

.ldgjpwb0m {
  stop-color: var(--svg-color--3c2b34, #3C2B34);
}

.li_eerpsf {
  stop-color: var(--svg-color--7b7072, #7B7072);
}

.lw_27mc8s {
  d: path("M16 4.55a.4.4 0 0 0-.08-.23a4.5 4.5 0 0 0-3.42-1.57c-2.05 0-4.054 1.445-4.594 3.375c-.18.64.584 1.345 1.244 1.345c.46 0 .86-.32.98-.77c.38-1.5 1.85-2.45 3.37-2.45c.72 0 1.39.177 1.95.547c.24.16.55.033.55-.247");
}

.m1itpp0ta {
  stop-color: var(--svg-color--be6a36, #BE6A36);
}

.mh4dp7bat {
  d: path("m12.05 28.43l-.01-1.69l-3 .02l.01 1.69c0 .17.14.31.31.31l2.38-.01c.17 0 .31-.15.31-.32");
}

.mqpbk469p {
  stop-color: var(--svg-color--67545f, #67545F);
}

.nfz20qi0y {
  stop-color: var(--svg-color--b87051, #B87051);
}

.nu7lwng9n {
  d: path("M3 10.75h.06c.64-.04.6-1-.04-1H2.1c-.07.14-.1.28-.1.44c0 .2.04.39.1.56z");
}

.opi0ugblw {
  d: path("M13 28.44v-1.69h-3v1.69c0 .17.14.31.31.31h2.38c.17 0 .31-.14.31-.31");
}

.pmliezbwq {
  stop-color: var(--svg-color--eaba8b, #EABA8B);
}

.q4q5f9p5h {
  stop-color: var(--svg-color--be764d, #BE764D);
  stop-opacity: 0;
}

.qcvj0gbex {
  d: path("m19.33 26.75l-1.11 1.55c-.1.21.05.45.28.45h2.03c.3 0 .57-.14.75-.38l1.78-1.62z");
}

.qgx435bwi {
  d: path("M6.5 9.75c-.28 0-.5-.251-.5-.571V8.32c0-.32.22-.571.5-.571S7 8 7 8.32v.858c0 .32-.22.571-.5.571");
}

.qqrguzb7l {
  stop-color: var(--svg-color--bcb6be, #BCB6BE);
  stop-opacity: 0;
}

.r4iofnb-j {
  stop-color: var(--svg-color--7a5559, #7A5559);
}

.rckfg0wkx {
  stop-color: var(--svg-color--cc8b5d, #CC8B5D);
}

.sfjwbcb-x {
  d: path("M9.05 28.45c0 .17.14.31.31.31l2.38-.01c.17 0 .31-.14.31-.31l-.01-2.42c0-.17.06-.33.18-.44c.52-.53.81-1.24.81-1.98l-.01-3.85l-4 .02z");
}

.sk6zy067z {
  stop-color: var(--svg-color--fcc18f, #FCC18F);
}

.slq0uobcb {
  stop-color: var(--svg-color--a8503d, #A8503D);
}

.swb29-h5o {
  stop-color: var(--svg-color--8b607e, #8B607E);
}

.thjj84bru {
  stop-color: var(--svg-color--a85735, #A85735);
  stop-opacity: 0;
}

.tjhdkxihf {
  stop-color: var(--svg-color--9f4834, #9F4834);
  stop-opacity: 0;
}

.tk8b2rg-x {
  stop-color: var(--svg-color--c5c5c5, #C5C5C5);
  stop-opacity: 0;
}

.tsxieuaax {
  stop-color: var(--svg-color--c5c5c5, #C5C5C5);
}

.u3l9-71on {
  d: path("M22.493 15.978A2.268 2.268 0 1 1 27 15.612v5.987h-3.587z");
}

.uaurr1bqq {
  stop-color: var(--svg-color--cfb1a2, #CFB1A2);
  stop-opacity: 0;
}

.uzmp_lqil {
  fill: var(--svg-color--a394ab, #A394AB);
  d: path("M4.819 11.883v1.582c-.15-.038-.212-.186-.212-.315v-1.267z");
}

.v3m_ugmll {
  stop-color: var(--svg-color--fcc18f, #FCC18F);
  stop-opacity: 0;
}

.v8t4bs_gr {
  stop-color: var(--svg-color--5e353e, #5E353E);
}

.w_xdtob7b {
  d: path("M19.99 20.75v4.78c0 .15-.03.29-.1.42l-1.67 2.35c-.1.21.05.45.28.45h2.03c.3 0 .57-.14.75-.38l2.41-2.2c.2-.27.31-.6.31-.94v-4.48z");
}

.w713edc-u {
  stop-color: var(--svg-color--cf8769, #CF8769);
}

.w9jli312m {
  stop-color: var(--svg-color--e1af7f, #E1AF7F);
  stop-opacity: 0;
}

.wnr6kunic {
  fill: var(--svg-color--84788c, #84788C);
  d: path("M5 13.75h-.09c-.69 0-1.24-.56-1.24-1.24v-1.42H5z");
}

.wxdpcmb4d {
  stop-color: var(--svg-color--dc9f64, #DC9F64);
}

.xr2depxri {
  stop-color: var(--svg-color--b87051, #B87051);
  stop-opacity: 0;
}

.xrtnzub7r {
  stop-color: var(--svg-color--cb844b, #CB844B);
}

.xze5rvixq {
  d: path("M13.457 24.625v-3.25h-1.672v4.719z");
}

.ymqdvbijo {
  stop-color: var(--svg-color--6f4350, #6F4350);
}

.z055jt8rg {
  stop-color: var(--svg-color--6a3568, #6A3568);
}

.z1d5_j39w {
  d: path("M30 28.44v-1.69h-3v1.69c0 .17.14.31.31.31h2.38c.17 0 .31-.14.31-.31");
}

.zczubmbiz {
  stop-color: var(--svg-color--c18d71, #C18D71);
}

.zi7dalv6c {
  stop-color: var(--svg-color--b13e76, #B13E76);
  stop-opacity: 0;
}

.zlmarccne {
  stop-color: var(--svg-color--aa8eb6, #AA8EB6);
  stop-opacity: 0;
}

.zw1cumbgm {
  stop-color: var(--svg-color--e1af7f, #E1AF7F);
}

</style>
