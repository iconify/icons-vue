<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iy70rYc)" class="v08f18bkr"/><path fill="url(#iVVbdve)" class="v08f18bkr"/><path fill="url(#i3VsFtd)" class="hyy4357km"/><path fill="url(#iZTVVLk)" class="cwe2eccpu"/><path fill="url(#isAUmRb)" class="fx102g0wm"/><path fill="url(#iZOEMkd)" class="fx102g0wm"/><path fill="url(#iAjaDcb)" class="un4xuobxq"/><path fill="url(#i8MevbN)" class="vpru11bwh"/><path fill="url(#iEVUj3d)" class="g549tr2qy"/><path fill="url(#im4zf9c)" class="g549tr2qy"/><path fill="url(#iFV6Gdb)" class="i7aeqlfla"/><path fill="url(#iVwHNDm)" class="jx41usbuy"/><path fill="url(#isaqojc)" class="sj55njb9u"/><path fill="url(#i2KMQ7b)" class="sj55njb9u"/><path fill="url(#igja39b)" class="sj55njb9u"/><path fill="url(#iyTFRvb)" class="ttgmoib7g"/><g filter="url(#i2Frc2Y)"><path fill="url(#iXKyJNd)" class="irstkhujs"/></g><path class="ei4belm6z"/><path fill="url(#iwO0k6c)" class="fueq3-bag"/><path fill="url(#i1wpHwe)" class="fueq3-bag"/><path fill="url(#i3wX0hc)" class="fueq3-bag"/><path fill="url(#idmQame)" class="fueq3-bag"/><path fill="url(#iJxbb3p)" class="fueq3-bag"/><path fill="url(#ijDCCyb)" class="fueq3-bag"/><path fill="url(#ih1rIEl)" class="fueq3-bag"/><path fill="url(#i1fU1xd)" class="fueq3-bag"/><g filter="url(#in3s1Xb)"><path class="l7cs6tedb"/><path fill="url(#is2Ff4d)" class="dlo938bpo"/><path fill="url(#ihrcydV)" class="dlo938bpo"/><path fill="url(#iqIyPve)" class="dlo938bpo"/><path fill="url(#iw1isxb)" class="dlo938bpo"/><path fill="url(#iTXUEee)" class="dlo938bpo"/><path fill="url(#iSGc6Ic)" class="dlo938bpo"/><path fill="url(#iKrQBRL)" class="dlo938bpo"/></g><g filter="url(#iaNil1d)"><path fill="url(#i0sIXFb)" class="l54jawxgn"/><path class="xt99w7bor"/></g><path fill="url(#iSpCYXb)" class="bo-q5jbnu"/><path fill="url(#i1cXAjl)" class="bo-q5jbnu"/><g filter="url(#iF1YVxe)"><path fill="url(#iwk3JXd)" class="lcgzh5bug"/><path fill="url(#iGWcfdd)" class="lcgzh5bug"/><path class="l4izs2bgh"/></g><path fill="url(#iUm4lJc)" class="rxs6_qb9z"/><path fill="url(#iUP3xed)" class="rxs6_qb9z"/><path fill="url(#iMGSkGd)" class="rxs6_qb9z"/><g filter="url(#i5s350g)"><path fill="url(#iqnS7ub)" class="j33yx1byq"/><path class="mr9nqbc9j"/></g><path fill="url(#iX9Uusc)" class="rz4-mbc-n"/><path fill="url(#iCuZAlb)" class="rz4-mbc-n"/><g filter="url(#iQospNb)"><path fill="url(#iXUg1Oq)" class="na3av3bii"/><path class="m9fgphbjm"/></g><path fill="url(#iyRdZhb)" class="jyc_8gbob"/><path fill="url(#iJc67Nb)" class="jyc_8gbob"/><g filter="url(#iFGFEHd)"><path class="znj3ozb3d"/></g><path fill="url(#imW4PWc)" class="pxn1hkjgz"/><defs><radialGradient id="iVVbdve" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50781 -.97656 0 9.93 6.516)" gradientUnits="userSpaceOnUse"><stop class="esvp03bdp"/><stop offset="1" class="licbqccbw"/></radialGradient><radialGradient id="i3VsFtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90626 3.71874 -9.24396 -4.73852 10.438 1.719)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="t2gpd45_x"/><stop offset=".814" class="vtznf8yot"/></radialGradient><radialGradient id="iZTVVLk" cx="0" cy="0" r="1" gradientTransform="rotate(106.757 3.676 5.204)scale(2.05937)" gradientUnits="userSpaceOnUse"><stop class="co7b1kboq"/><stop offset="1" class="w8pxngtjz"/></radialGradient><radialGradient id="iZOEMkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50781 -.97656 0 16.43 6.516)" gradientUnits="userSpaceOnUse"><stop class="esvp03bdp"/><stop offset="1" class="licbqccbw"/></radialGradient><radialGradient id="iAjaDcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90626 3.71874 -9.24396 -4.73852 16.948 1.719)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="t2gpd45_x"/><stop offset=".814" class="vtznf8yot"/></radialGradient><radialGradient id="i8MevbN" cx="0" cy="0" r="1" gradientTransform="rotate(106.686 6.915 7.64)scale(2.06788 2.06014)" gradientUnits="userSpaceOnUse"><stop class="co7b1kboq"/><stop offset="1" class="w8pxngtjz"/></radialGradient><radialGradient id="im4zf9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50781 -.97656 0 22.93 6.597)" gradientUnits="userSpaceOnUse"><stop class="esvp03bdp"/><stop offset="1" class="licbqccbw"/></radialGradient><radialGradient id="iFV6Gdb" cx="0" cy="0" r="1" gradientTransform="rotate(117.062 11.194 8.032)scale(4.17597 10.3602)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="t2gpd45_x"/><stop offset=".814" class="vtznf8yot"/></radialGradient><radialGradient id="iVwHNDm" cx="0" cy="0" r="1" gradientTransform="rotate(106.686 10.174 10.046)scale(2.06788 2.06014)" gradientUnits="userSpaceOnUse"><stop class="co7b1kboq"/><stop offset="1" class="w8pxngtjz"/></radialGradient><radialGradient id="i2KMQ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.4375 -6.67388 0 21.123 24.19)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="cx6icgbch"/><stop offset=".982" class="um-rn_epg"/></radialGradient><radialGradient id="iwO0k6c" cx="0" cy="0" r="1" gradientTransform="matrix(-17.18748 13.62507 -21.78108 -27.47596 26 11.563)" gradientUnits="userSpaceOnUse"><stop class="mjhn-4b2c"/><stop offset=".226" class="qgi89cuzr"/><stop offset=".636" class="x9a0d8alr"/></radialGradient><radialGradient id="i1wpHwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -8.5625 0 24.188 11.063)" gradientUnits="userSpaceOnUse"><stop class="tsx_qla0h"/><stop offset="1" class="l_jm_qb7a"/></radialGradient><radialGradient id="ijDCCyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.4375 -8.04767 0 16.005 18.313)" gradientUnits="userSpaceOnUse"><stop class="kj2hktbmz"/><stop offset="1" class="uvd-3-u4n"/></radialGradient><radialGradient id="ih1rIEl" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 7.10156 -5.47554 -.57828 23.25 19.023)" gradientUnits="userSpaceOnUse"><stop class="twlyecbub"/><stop offset="1" class="xf4qjyb0e"/></radialGradient><radialGradient id="is2Ff4d" cx="0" cy="0" r="1" gradientTransform="rotate(143.326 10.853 10.153)scale(20.7287 32.6077)" gradientUnits="userSpaceOnUse"><stop class="mjhn-4b2c"/><stop offset=".226" class="qgi89cuzr"/><stop offset=".636" class="x9a0d8alr"/></radialGradient><radialGradient id="ihrcydV" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.22102 -8.28241 0 23.868 11.36)" gradientUnits="userSpaceOnUse"><stop class="tsx_qla0h"/><stop offset="1" class="l_jm_qb7a"/></radialGradient><radialGradient id="iSGc6Ic" cx="0" cy="0" r="1" gradientTransform="scale(7.78442 9.48418)rotate(90 .078 1.97)" gradientUnits="userSpaceOnUse"><stop class="kj2hktbmz"/><stop offset="1" class="uvd-3-u4n"/></radialGradient><radialGradient id="iKrQBRL" cx="0" cy="0" r="1" gradientTransform="matrix(-.72547 6.45293 -5.28866 -.59457 22.961 18.594)" gradientUnits="userSpaceOnUse"><stop class="twlyecbub"/><stop offset="1" class="xf4qjyb0e"/></radialGradient><radialGradient id="i1cXAjl" cx="0" cy="0" r="1" gradientTransform="matrix(-.23367 .30907 -.3081 -.23294 21.356 15.457)" gradientUnits="userSpaceOnUse"><stop class="bc-8jccwp"/><stop offset="1" class="cf4b-x_fl"/></radialGradient><radialGradient id="iGWcfdd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46561 1.375 -1.07563 -1.14651 11.61 14.825)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="kkalcqr3r"/><stop offset="1" class="wdzivnbpe"/></radialGradient><radialGradient id="iUP3xed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46561 1.375 -1.07563 -1.14651 11.86 14.625)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="kkalcqr3r"/><stop offset="1" class="wdzivnbpe"/></radialGradient><radialGradient id="iMGSkGd" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .70313 -.49219 .49219 12.017 14.421)" gradientUnits="userSpaceOnUse"><stop class="lr9_p5obv"/><stop offset="1" class="ty6zhz5jh"/></radialGradient><radialGradient id="iCuZAlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 .26563 -.26449 -.28005 7.609 12.423)" gradientUnits="userSpaceOnUse"><stop class="bc-8jccwp"/><stop offset="1" class="cf4b-x_fl"/></radialGradient><radialGradient id="iJc67Nb" cx="0" cy="0" r="1" gradientTransform="rotate(-15.255 61.066 -83.511)scale(1.06891)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="z9lvwmfpo"/><stop offset="1" class="jlmw8lghs"/></radialGradient><linearGradient id="iy70rYc" x1="8.5" x2="10.5" y1="7.875" y2="7.875" gradientUnits="userSpaceOnUse"><stop class="lznnuzbkr"/><stop offset=".137" class="gnpoi19tv"/><stop offset=".563" class="xt6f7kbgb"/><stop offset=".816" class="aqewcachr"/><stop offset="1" class="rj2e9bbfn"/></linearGradient><linearGradient id="isAUmRb" x1="15" x2="17" y1="7.875" y2="7.875" gradientUnits="userSpaceOnUse"><stop class="lznnuzbkr"/><stop offset=".137" class="gnpoi19tv"/><stop offset=".563" class="xt6f7kbgb"/><stop offset=".816" class="aqewcachr"/><stop offset="1" class="rj2e9bbfn"/></linearGradient><linearGradient id="iEVUj3d" x1="21.5" x2="23.5" y1="7.956" y2="7.956" gradientUnits="userSpaceOnUse"><stop class="lznnuzbkr"/><stop offset=".137" class="gnpoi19tv"/><stop offset=".563" class="xt6f7kbgb"/><stop offset=".816" class="aqewcachr"/><stop offset="1" class="rj2e9bbfn"/></linearGradient><linearGradient id="isaqojc" x1="2" x2="29.563" y1="22.498" y2="22.498" gradientUnits="userSpaceOnUse"><stop offset=".006" class="xxwx0lb6n"/><stop offset=".129" class="qml5dsb4j"/><stop offset=".543" class="d-7-_ubls"/><stop offset=".698" class="bqe42u9xb"/><stop offset=".858" class="w01g0fo9n"/><stop offset=".939" class="f84q2rbhp"/><stop offset=".982" class="km_1ncxdg"/></linearGradient><linearGradient id="igja39b" x1="16" x2="16" y1="24.813" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".739" class="pcf-lsb3f"/><stop offset=".862" class="km308vusc"/><stop offset=".954" class="k_836ehzr"/></linearGradient><linearGradient id="iyTFRvb" x1="2.563" x2="29.563" y1="22.985" y2="22.985" gradientUnits="userSpaceOnUse"><stop offset=".006" class="btaaa9byy"/><stop offset=".038" class="i64ffbcqm"/><stop offset=".206" class="jqwwtseqi"/><stop offset=".511" class="tsc3_abvm"/><stop offset=".799" class="s74sgrbsn"/><stop offset=".933" class="v-drapbuc"/><stop offset=".992" class="f1152o_dv"/></linearGradient><linearGradient id="iXKyJNd" x1="3.698" x2="28.524" y1="18.813" y2="18.813" gradientUnits="userSpaceOnUse"><stop class="ve4gtbcts"/><stop offset=".388" class="qj3hjxban"/><stop offset=".679" class="kutjsqpit"/><stop offset="1" class="i3w_zve6f"/></linearGradient><linearGradient id="i3wX0hc" x1="30.01" x2="27.438" y1="15.125" y2="15.125" gradientUnits="userSpaceOnUse"><stop class="t2fkk9b6e"/><stop offset=".466" class="jixkrbb4i"/><stop offset=".903" class="rt9w2ibnd"/></linearGradient><linearGradient id="idmQame" x1="16.005" x2="16.005" y1="9.016" y2="19.023" gradientUnits="userSpaceOnUse"><stop class="a4551ibwp"/><stop offset=".03" class="uspsakbno"/><stop offset=".16" class="pw70_urzz"/></linearGradient><linearGradient id="iJxbb3p" x1="2" x2="8.063" y1="15.125" y2="15.125" gradientUnits="userSpaceOnUse"><stop class="lgag6tdnq"/><stop offset=".412" class="zwdk-xbgf"/><stop offset="1" class="ybau8sw7f"/></linearGradient><linearGradient id="i1fU1xd" x1="19.688" x2="19.688" y1="18.563" y2="14.02" gradientUnits="userSpaceOnUse"><stop class="l-yp-6bkl"/><stop offset=".358" class="tyz2q43dn"/></linearGradient><linearGradient id="iqIyPve" x1="29.5" x2="27.012" y1="15.051" y2="15.051" gradientUnits="userSpaceOnUse"><stop class="t2fkk9b6e"/><stop offset=".466" class="jixkrbb4i"/><stop offset=".903" class="rt9w2ibnd"/></linearGradient><linearGradient id="iw1isxb" x1="15.953" x2="15.953" y1="9.5" y2="18.594" gradientUnits="userSpaceOnUse"><stop class="a4551ibwp"/><stop offset=".03" class="uspsakbno"/><stop offset=".16" class="pw70_urzz"/></linearGradient><linearGradient id="iTXUEee" x1="2.406" x2="8.27" y1="15.051" y2="15.051" gradientUnits="userSpaceOnUse"><stop class="lgag6tdnq"/><stop offset=".412" class="zwdk-xbgf"/><stop offset="1" class="ybau8sw7f"/></linearGradient><linearGradient id="i0sIXFb" x1="20.96" x2="20.313" y1="14.932" y2="15.6" gradientUnits="userSpaceOnUse"><stop class="mw97txb9j"/><stop offset=".384" class="dlw69ommj"/><stop offset="1" class="mex93-rrb"/></linearGradient><linearGradient id="iSpCYXb" x1="21.109" x2="20.461" y1="14.849" y2="15.517" gradientUnits="userSpaceOnUse"><stop class="mw97txb9j"/><stop offset=".384" class="dlw69ommj"/><stop offset="1" class="mex93-rrb"/></linearGradient><linearGradient id="iwk3JXd" x1="10.645" x2="11.348" y1="14.986" y2="15.659" gradientUnits="userSpaceOnUse"><stop class="lsw9odb8z"/><stop offset=".31" class="ij94oabdv"/><stop offset=".635" class="s0xygeszp"/><stop offset="1" class="yfyaj9rse"/></linearGradient><linearGradient id="iUm4lJc" x1="10.894" x2="11.597" y1="14.786" y2="15.459" gradientUnits="userSpaceOnUse"><stop class="lsw9odb8z"/><stop offset=".31" class="ij94oabdv"/><stop offset=".635" class="s0xygeszp"/><stop offset="1" class="yfyaj9rse"/></linearGradient><linearGradient id="iqnS7ub" x1="7.175" x2="6.425" y1="11.903" y2="12.45" gradientUnits="userSpaceOnUse"><stop class="mw97txb9j"/><stop offset=".384" class="dlw69ommj"/><stop offset="1" class="mex93-rrb"/></linearGradient><linearGradient id="iX9Uusc" x1="7.469" x2="6.719" y1="11.781" y2="12.328" gradientUnits="userSpaceOnUse"><stop class="mw97txb9j"/><stop offset=".384" class="dlw69ommj"/><stop offset="1" class="mex93-rrb"/></linearGradient><linearGradient id="iXUg1Oq" x1="24.401" x2="25.198" y1="11.861" y2="12.423" gradientUnits="userSpaceOnUse"><stop class="wxcsmc9iy"/><stop offset=".31" class="qkkpb2bcy"/><stop offset=".635" class="r44qeks7t"/><stop offset="1" class="xg_lbec_x"/></linearGradient><linearGradient id="iyRdZhb" x1="24.516" x2="25.313" y1="11.719" y2="12.281" gradientUnits="userSpaceOnUse"><stop class="wxcsmc9iy"/><stop offset=".31" class="qkkpb2bcy"/><stop offset=".635" class="r44qeks7t"/><stop offset="1" class="xg_lbec_x"/></linearGradient><linearGradient id="imW4PWc" x1="16.406" x2="15.734" y1="11.672" y2="12.359" gradientUnits="userSpaceOnUse"><stop class="a_mav7b0z"/><stop offset=".371" class="mdwc99bda"/><stop offset="1" class="qk393xbqm"/></linearGradient><filter id="i2Frc2Y" width="26.366" height="5.413" x="2.75" y="14.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".125"/></filter><filter id="in3s1Xb" width="29.359" height="4.885" x="1.406" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".5"/></filter><filter id="iaNil1d" width="2.25" height="2.25" x="19.458" y="14.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".125"/></filter><filter id="iF1YVxe" width="2.242" height="2.25" x="9.894" y="14.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".125"/></filter><filter id="i5s350g" width="2.108" height="2.363" x="5.703" y="10.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".125"/></filter><filter id="iQospNb" width="2.129" height="2.353" x="23.756" y="10.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".125"/></filter><filter id="iFGFEHd" width="2.25" height="2.25" x="14.75" y="10.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32701" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:birthday-cake" /></template>
<style>
.a_mav7b0z {
  stop-color: var(--svg-color--4fc3ff, #4FC3FF);
}

.a4551ibwp {
  stop-color: var(--svg-color--d8b38b, #D8B38B);
}

.aqewcachr {
  stop-color: var(--svg-color--71e2fc, #71E2FC);
}

.bc-8jccwp {
  stop-color: var(--svg-color--ff80e2, #FF80E2);
}

.bo-q5jbnu {
  d: path("M21.456 15.857c-.2.2-.51.2-.71 0l-.74-.74c-.2-.2-.2-.51 0-.71s.51-.2.71 0l.74.74c.2.2.2.52 0 .71");
}

.bqe42u9xb {
  stop-color: var(--svg-color--f8a672, #F8A672);
}

.btaaa9byy {
  stop-color: var(--svg-color--c7a88a, #C7A88A);
}

.cf4b-x_fl {
  stop-color: var(--svg-color--ff80e2, #FF80E2);
  stop-opacity: 0;
}

.co7b1kboq {
  stop-color: var(--svg-color--fecf4d, #FECF4D);
}

.cwe2eccpu {
  d: path("m10.11 3.964l-.61-.78l-.61.78a.849.849 0 1 0 1.46.59c0-.23-.09-.43-.24-.59");
}

.cx6icgbch {
  stop-color: var(--svg-color--ffbe8a, #FFBE8A);
}

.d-7-_ubls {
  stop-color: var(--svg-color--f6a377, #F6A377);
}

.dlo938bpo {
  d: path("M2.406 17.262c0 .877.661 1.161 1.188 1.161c.682 0 .946-.465 1.406-.83c.34-.268 1.448-.001 1.828.282c.632.463 1.461.86 2.219.906c.923.056 2.073-.623 2.844-1.187c.532-.39 1.167-.374 1.678 0c.704.515 1.555 1.299 2.4 1.297c.838-.002 1.973-.645 2.672-1.157c.5-.366 1.533-.371 2.03-.006c1.506 1.102 3.519 1.052 4.673.194c1.224-.91 2.472.594 3.281.594c.56 0 1.14-.016 1.14-1v-.766c-.374-.987-27.359-1.156-27.359.512");
}

.dlw69ommj {
  stop-color: var(--svg-color--ff79d8, #FF79D8);
}

.ei4belm6z {
  fill: var(--svg-color--edc8ae, #EDC8AE);
  d: path("M2 12.297v5.26c0 .966 1.016 1.279 1.56 1.279c.706 0 1.035-.358 1.51-.758c.352-.297 1.193-.312 1.586 0a4.01 4.01 0 0 0 4.93 0c.551-.43 1.426-.412 1.954 0c.728.567 1.602.948 2.476.945c.866-.002 1.732-.383 2.454-.945c.518-.404 1.406-.41 1.92-.008c1.557 1.213 3.776.952 4.97.008c.752-.596 2.109.766 2.945.766c.578 0 1.705-.203 1.705-1.286v-5.261c0-2.735-1.948-3.281-4.01-3.281H6.39c-3.17 0-4.39 1.109-4.39 3.28");
}

.esvp03bdp {
  stop-color: var(--svg-color--8bfdff, #8BFDFF);
}

.f1152o_dv {
  stop-color: var(--svg-color--e9caa0, #E9CAA0);
}

.f84q2rbhp {
  stop-color: var(--svg-color--e99952, #E99952);
}

.ft5dv1b6b {
  fill: none;
}

.fueq3-bag {
  d: path("M2 12.297v5.26c0 .966 1.016 1.279 1.56 1.279c.706 0 1.035-.358 1.51-.758c.352-.297 1.193-.312 1.586 0a4.01 4.01 0 0 0 4.93 0c.551-.43 1.426-.412 1.954 0c.728.567 1.602.948 2.476.945c.866-.002 1.732-.383 2.454-.945c.518-.404 1.406-.41 1.92-.008c1.557 1.213 3.776.952 4.97.008c.752-.596 2.109.766 2.945.766c.578 0 1.705-.203 1.705-1.286v-5.261c0-2.735-1.948-3.281-4.01-3.281H6.39c-3.17 0-4.39 1.109-4.39 3.28");
}

.fx102g0wm {
  d: path("M17 10.92h-2V6.88c0-.29.12-.57.32-.77l.68-.67l.68.67c.2.2.32.48.32.77z");
}

.g549tr2qy {
  d: path("M23.5 11h-2V6.96c0-.29.12-.57.32-.77l.68-.67l.68.67c.21.2.32.48.32.77z");
}

.gnpoi19tv {
  stop-color: var(--svg-color--52b4cf, #52B4CF);
}

.hyy4357km {
  d: path("m10.78 3.774l-.9-1.51a.45.45 0 0 0-.77 0l-.89 1.51c-.17.28-.25.61-.21.96c.08.69.63 1.24 1.32 1.31c.9.1 1.67-.6 1.67-1.49a1.7 1.7 0 0 0-.22-.78");
}

.i3w_zve6f {
  stop-color: var(--svg-color--8e4229, #8E4229);
}

.i64ffbcqm {
  stop-color: var(--svg-color--d3b08f, #D3B08F);
}

.i7aeqlfla {
  d: path("m23.78 3.774l-.89-1.51a.45.45 0 0 0-.77 0l-.89 1.51c-.17.27-.25.61-.21.96c.08.69.63 1.24 1.31 1.31c.91.1 1.67-.6 1.67-1.49c0-.28-.08-.55-.22-.78");
}

.ij94oabdv {
  stop-color: var(--svg-color--e29b3e, #E29B3E);
}

.irstkhujs {
  d: path("M3.729 19.082c.702 0 1.038-.252 1.51-.652c.35-.297.836-.741 1.228-.43c1.443 1.13 3.655 1.56 5.099.43c.548-.43.644-.526 1.17-.114c.724.567 1.727.94 2.597.938c1.579 0 2.273-.383 2.992-.946c.515-.403.804-.401 1.317 0c1.549 1.213 3.805.952 4.993.008c.75-.596 1.968.715 2.8.715c.576 0 1.431-.152 1.431-1.236c-5.715-4.744-20.62-4.328-25.448-.42c-.752.609-.391 1.707.311 1.707");
}

.j33yx1byq {
  d: path("M7.353 12.956a.495.495 0 0 1-.7-.119l-.605-.854a.495.495 0 0 1 .12-.7a.495.495 0 0 1 .7.12l.605.853a.514.514 0 0 1-.12.7");
}

.jixkrbb4i {
  stop-color: var(--svg-color--fee6b8, #FEE6B8);
}

.jlmw8lghs {
  stop-color: var(--svg-color--d98044, #D98044);
  stop-opacity: 0;
}

.jqwwtseqi {
  stop-color: var(--svg-color--ffd0b4, #FFD0B4);
}

.jx41usbuy {
  d: path("m23.11 3.964l-.61-.78l-.61.79a.85.85 0 1 0 1.46.59c0-.24-.09-.44-.24-.6");
}

.jyc_8gbob {
  d: path("M25.543 11.172a.495.495 0 0 0-.702.106l-.62.843a.495.495 0 0 0 .106.702a.495.495 0 0 0 .702-.107l.62-.842a.495.495 0 0 0-.106-.702");
}

.k_836ehzr {
  stop-color: var(--svg-color--ba5ca3, #BA5CA3);
}

.kj2hktbmz {
  stop-color: var(--svg-color--fddac6, #FDDAC6);
}

.kkalcqr3r {
  stop-color: var(--svg-color--cf794b, #CF794B);
  stop-opacity: 0;
}

.km_1ncxdg {
  stop-color: var(--svg-color--cc894f, #CC894F);
}

.km308vusc {
  stop-color: var(--svg-color--e4828a, #E4828A);
}

.kutjsqpit {
  stop-color: var(--svg-color--a54d3b, #A54D3B);
}

.l_jm_qb7a {
  stop-color: var(--svg-color--fff9c7, #FFF9C7);
  stop-opacity: 0;
}

.l-yp-6bkl {
  stop-color: var(--svg-color--d697ac, #D697AC);
}

.l4izs2bgh {
  fill: var(--svg-color--cca39a, #CCA39A);
  d: path("M11.744 14.6c-.2-.2-.51-.2-.71 0l-.74.74c-.2.2-.2.51 0 .71s.51.2.71 0l.74-.74c.19-.2.19-.51 0-.71");
}

.l54jawxgn {
  d: path("M21.308 15.94c-.2.2-.51.2-.71 0l-.74-.74c-.2-.2-.2-.51 0-.71s.51-.2.71 0l.74.74c.2.2.2.52 0 .71");
}

.l7cs6tedb {
  fill: var(--svg-color--edc8ae, #EDC8AE);
  d: path("M2.406 17.262c0 .877.661 1.161 1.188 1.161c.682 0 .946-.465 1.406-.83c.34-.268 1.448-.001 1.828.282c.632.463 1.461.86 2.219.906c.923.056 2.073-.623 2.844-1.187c.532-.39 1.167-.374 1.678 0c.704.515 1.555 1.299 2.4 1.297c.838-.002 1.973-.645 2.672-1.157c.5-.366 1.533-.371 2.03-.006c1.506 1.102 3.519 1.052 4.673.194c1.224-.91 2.472.594 3.281.594c.56 0 1.14-.016 1.14-1v-.766c-.374-.987-27.359-1.156-27.359.512");
}

.lcgzh5bug {
  d: path("M11.744 14.6c-.2-.2-.51-.2-.71 0l-.74.74c-.2.2-.2.51 0 .71s.51.2.71 0l.74-.74c.19-.2.19-.51 0-.71");
}

.lgag6tdnq {
  stop-color: var(--svg-color--a9967b, #A9967B);
}

.licbqccbw {
  stop-color: var(--svg-color--8dffff, #8DFFFF);
  stop-opacity: 0;
}

.lr9_p5obv {
  stop-color: var(--svg-color--ffc054, #FFC054);
}

.lsw9odb8z {
  stop-color: var(--svg-color--d29440, #D29440);
}

.lznnuzbkr {
  stop-color: var(--svg-color--3f92a6, #3F92A6);
}

.m9fgphbjm {
  fill: var(--svg-color--f8ccad, #F8CCAD);
  d: path("M25.428 11.313a.495.495 0 0 0-.702.107l-.62.843a.495.495 0 0 0 .107.702a.495.495 0 0 0 .702-.107l.62-.843a.495.495 0 0 0-.107-.702");
}

.mdwc99bda {
  stop-color: var(--svg-color--45b2ff, #45B2FF);
}

.mex93-rrb {
  stop-color: var(--svg-color--c557ab, #C557AB);
}

.mjhn-4b2c {
  stop-color: var(--svg-color--fff2c2, #FFF2C2);
}

.mr9nqbc9j {
  fill: var(--svg-color--cea691, #CEA691);
  d: path("M7.353 12.956a.495.495 0 0 1-.7-.119l-.605-.854a.495.495 0 0 1 .12-.7a.495.495 0 0 1 .7.12l.605.853a.514.514 0 0 1-.12.7");
}

.mw97txb9j {
  stop-color: var(--svg-color--ff79c8, #FF79C8);
}

.na3av3bii {
  d: path("M25.428 11.313a.495.495 0 0 0-.702.107l-.62.843a.495.495 0 0 0 .107.702a.495.495 0 0 0 .702-.107l.62-.843a.495.495 0 0 0-.107-.702");
}

.pcf-lsb3f {
  stop-color: var(--svg-color--f7a378, #F7A378);
  stop-opacity: 0;
}

.pw70_urzz {
  stop-color: var(--svg-color--ffe59f, #FFE59F);
  stop-opacity: 0;
}

.pxn1hkjgz {
  d: path("M15.28 11.272c-.2.2-.2.51 0 .71l.74.74c.2.2.51.2.71 0s.2-.51 0-.71l-.74-.74c-.2-.2-.52-.2-.71 0");
}

.qgi89cuzr {
  stop-color: var(--svg-color--fff2c2, #FFF2C2);
  stop-opacity: 0.645;
}

.qj3hjxban {
  stop-color: var(--svg-color--bd6555, #BD6555);
}

.qk393xbqm {
  stop-color: var(--svg-color--417edd, #417EDD);
}

.qkkpb2bcy {
  stop-color: var(--svg-color--ffb841, #FFB841);
}

.qml5dsb4j {
  stop-color: var(--svg-color--dc9a6f, #DC9A6F);
}

.r44qeks7t {
  stop-color: var(--svg-color--ffc656, #FFC656);
}

.rj2e9bbfn {
  stop-color: var(--svg-color--5bd0ef, #5BD0EF);
}

.rt9w2ibnd {
  stop-color: var(--svg-color--fff0c2, #FFF0C2);
  stop-opacity: 0;
}

.rxs6_qb9z {
  d: path("M11.994 14.4c-.2-.2-.51-.2-.71 0l-.74.74c-.2.2-.2.51 0 .71s.51.2.71 0l.74-.74c.19-.2.19-.51 0-.71");
}

.rz4-mbc-n {
  d: path("M7.647 12.835a.495.495 0 0 1-.7-.12l-.605-.853a.495.495 0 0 1 .12-.7a.495.495 0 0 1 .7.119l.604.854a.513.513 0 0 1-.119.7");
}

.s0xygeszp {
  stop-color: var(--svg-color--ee9744, #EE9744);
}

.s74sgrbsn {
  stop-color: var(--svg-color--fff7cf, #FFF7CF);
}

.sj55njb9u {
  d: path("M26.984 29.998H4.922C3.656 29.998 3 29.312 3 28.03V14.998h26V28.03c0 1.25-.562 1.967-2.016 1.967");
}

.t2fkk9b6e {
  stop-color: var(--svg-color--ead3a8, #EAD3A8);
}

.t2gpd45_x {
  stop-color: var(--svg-color--ffef5b, #FFEF5B);
}

.tsc3_abvm {
  stop-color: var(--svg-color--ffe3ca, #FFE3CA);
}

.tsx_qla0h {
  stop-color: var(--svg-color--fffcc8, #FFFCC8);
}

.ttgmoib7g {
  d: path("M29 21.986H3v2h26z");
}

.twlyecbub {
  stop-color: var(--svg-color--fff4d0, #FFF4D0);
}

.ty6zhz5jh {
  stop-color: var(--svg-color--ffbd42, #FFBD42);
  stop-opacity: 0;
}

.tyz2q43dn {
  stop-color: var(--svg-color--d697ac, #D697AC);
  stop-opacity: 0;
}

.um-rn_epg {
  stop-color: var(--svg-color--ffbb8a, #FFBB8A);
  stop-opacity: 0;
}

.un4xuobxq {
  d: path("m17.28 3.774l-.89-1.51a.45.45 0 0 0-.77 0l-.89 1.51c-.17.27-.25.61-.21.96c.08.68.63 1.23 1.32 1.31c.9.1 1.67-.6 1.67-1.49c-.01-.28-.09-.55-.23-.78");
}

.uspsakbno {
  stop-color: var(--svg-color--f9c588, #F9C588);
}

.uvd-3-u4n {
  stop-color: var(--svg-color--fbd7c3, #FBD7C3);
  stop-opacity: 0;
}

.v-drapbuc {
  stop-color: var(--svg-color--ffe5b6, #FFE5B6);
}

.v08f18bkr {
  d: path("M10.5 10.92h-2V6.88c0-.29.12-.57.32-.77l.68-.67l.68.67c.2.2.32.48.32.77z");
}

.ve4gtbcts {
  stop-color: var(--svg-color--bf6245, #BF6245);
}

.vpru11bwh {
  d: path("M16.61 3.99L16 3.21l-.61.79a.85.85 0 1 0 1.46.59c0-.24-.09-.44-.24-.6");
}

.vtznf8yot {
  stop-color: var(--svg-color--fda43a, #FDA43A);
}

.w01g0fo9n {
  stop-color: var(--svg-color--fbaa6c, #FBAA6C);
}

.w8pxngtjz {
  stop-color: var(--svg-color--ff9b32, #FF9B32);
}

.wdzivnbpe {
  stop-color: var(--svg-color--cf794b, #CF794B);
}

.wxcsmc9iy {
  stop-color: var(--svg-color--fba947, #FBA947);
}

.x9a0d8alr {
  stop-color: var(--svg-color--fff1c1, #FFF1C1);
  stop-opacity: 0;
}

.xf4qjyb0e {
  stop-color: var(--svg-color--fff3d1, #FFF3D1);
  stop-opacity: 0;
}

.xg_lbec_x {
  stop-color: var(--svg-color--f3a740, #F3A740);
}

.xt6f7kbgb {
  stop-color: var(--svg-color--73e5ff, #73E5FF);
}

.xt99w7bor {
  fill: var(--svg-color--e6a9af, #E6A9AF);
  d: path("M21.308 15.94c-.2.2-.51.2-.71 0l-.74-.74c-.2-.2-.2-.51 0-.71s.51-.2.71 0l.74.74c.2.2.2.52 0 .71");
}

.xxwx0lb6n {
  stop-color: var(--svg-color--bb8960, #BB8960);
}

.ybau8sw7f {
  stop-color: var(--svg-color--dbbea7, #DBBEA7);
  stop-opacity: 0;
}

.yfyaj9rse {
  stop-color: var(--svg-color--f19542, #F19542);
}

.z9lvwmfpo {
  stop-color: var(--svg-color--d88043, #D88043);
}

.znj3ozb3d {
  fill: var(--svg-color--ad8994, #AD8994);
  d: path("M15.15 11.394c-.2.2-.2.51 0 .71l.74.74c.2.2.51.2.71 0s.2-.51 0-.71l-.74-.74c-.2-.2-.52-.2-.71 0");
}

.zwdk-xbgf {
  stop-color: var(--svg-color--d2b79e, #D2B79E);
}

</style>
