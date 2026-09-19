<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijvNgwd)"><path fill="url(#iIZzXOb)" class="w05axs7ko"/><path fill="url(#iRlupEd)" class="w05axs7ko"/></g><path fill="url(#iKEdD8u)" class="z7wy6obpq"/><path fill="url(#iIGyrAe)" class="z7wy6obpq"/><path fill="url(#ikIlALb)" class="i36s1qb_g"/><path fill="url(#i4i75Nc)" class="i36s1qb_g"/><path fill="url(#i1P0Std)" class="tjvmr_b3b"/><path fill="url(#i3G7Ynf)" class="tjvmr_b3b"/><rect fill="url(#iCPtYZc)" transform="rotate(-31.647 4.757 15.519)" class="fssmy6bpn"/><g filter="url(#iMcEuvb)"><path stroke="url(#ia7Y1He)" class="vc46r_c8i"/></g><g filter="url(#in8F2Ec)"><path stroke="url(#i13d88b)" class="asqc_1_dp"/></g><g filter="url(#imn2EKb)"><path stroke="url(#is6s9Ec)" class="w_ccelber"/></g><g filter="url(#iLA5R6c)"><path class="ihs0mo99f"/></g><g filter="url(#izdg7we)"><path class="x28j_obaq"/></g><g filter="url(#i5VRhyb)"><path class="l79n4x80f"/></g><g filter="url(#i8YCUic)"><path fill="url(#ixTbKSd)" class="ma8v-lhgu"/></g><path fill="url(#i5PosSw)" class="ma8v-lhgu"/><g filter="url(#iqmjjif)"><path fill="url(#i5VwAbc)" class="at05xybeo"/></g><rect fill="url(#iVfZnIb)" transform="rotate(-31.647 10.257 15.458)" class="z7kzdbcte"/><path fill="url(#i3g8GSd)" class="gwznzxt3m"/><path fill="url(#i5gfBOd)" class="gwznzxt3m"/><path fill="url(#ibUDxgc)" class="e2mbiomkg"/><path fill="url(#i122Tec)" class="e2mbiomkg"/><path fill="url(#iFgp5Le)" class="yet1k9bwh"/><path fill="url(#iQHfldC)" class="yet1k9bwh"/><path fill="url(#iTml3Wc)" class="fdnjngwjh"/><g filter="url(#iKchtwd)"><path class="r_s_w9-vw"/></g><g filter="url(#iEwtaDB)"><path class="dks2s3bwa"/></g><g filter="url(#iPJxigd)"><path class="uq8cwck3n"/></g><g filter="url(#ikJUabb)"><path class="onehqlohp"/></g><g filter="url(#iGhdtJz)"><path stroke="url(#iKte4qd)" class="m25qys66g"/></g><defs><radialGradient id="iIZzXOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46518 -21.55686 14.94831 -1.016 16.805 27.696)" gradientUnits="userSpaceOnUse"><stop class="jr1omn8rw"/><stop offset="1" class="t_r9idbvp"/></radialGradient><radialGradient id="iRlupEd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.68861 -6.09785 3.14876 -3.97019 19.203 24.54)" gradientUnits="userSpaceOnUse"><stop class="cp1hi53fn"/><stop offset="1" class="tsl9knb3d"/></radialGradient><radialGradient id="iKEdD8u" cx="0" cy="0" r="1" gradientTransform="matrix(2.43965 3.91822 -1.52236 .94788 9.74 16.667)" gradientUnits="userSpaceOnUse"><stop class="vfbfb-6go"/><stop offset="1" class="v6h1a9bpm"/></radialGradient><radialGradient id="iIGyrAe" cx="0" cy="0" r="1" gradientTransform="matrix(.2819 3.00606 -2.91273 .27314 9.93 9.906)" gradientUnits="userSpaceOnUse"><stop class="voqk07baz"/><stop offset="1" class="ma39larlc"/><stop offset="1" class="ofvrpqb3w"/></radialGradient><radialGradient id="ikIlALb" cx="0" cy="0" r="1" gradientTransform="matrix(2.99844 4.92595 -1.93444 1.1775 11.51 13.144)" gradientUnits="userSpaceOnUse"><stop class="vfbfb-6go"/><stop offset="1" class="v6h1a9bpm"/></radialGradient><radialGradient id="i4i75Nc" cx="0" cy="0" r="1" gradientTransform="rotate(92.162 2.468 9.218)scale(2.99948 2.97789)" gradientUnits="userSpaceOnUse"><stop class="azdrq3fkw"/><stop offset="1" class="dqlb3ab4y"/></radialGradient><radialGradient id="i1P0Std" cx="0" cy="0" r="1" gradientTransform="rotate(56.246 -2.72 18.709)scale(7.9164 3.09735)" gradientUnits="userSpaceOnUse"><stop class="vfbfb-6go"/><stop offset="1" class="v6h1a9bpm"/></radialGradient><radialGradient id="i3G7Ynf" cx="0" cy="0" r="1" gradientTransform="rotate(106.04 6.453 9.033)scale(4.45696 4.3873)" gradientUnits="userSpaceOnUse"><stop class="biona6bwi"/><stop offset="1" class="ma39larlc"/></radialGradient><radialGradient id="iCPtYZc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09956 3.33701 -3.63466 -2.28683 8.991 16.052)" gradientUnits="userSpaceOnUse"><stop class="ws-w_lbeb"/><stop offset="1" class="yaj7vcbgd"/></radialGradient><radialGradient id="ixTbKSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.9047 -12.2669 0 20.662 15.035)" gradientUnits="userSpaceOnUse"><stop class="mpj6i3b2o"/><stop offset="1" class="as4u9vbtv"/></radialGradient><radialGradient id="i5PosSw" cx="0" cy="0" r="1" gradientTransform="matrix(-6.0596 .40152 -1.54153 -23.26408 32.917 21.709)" gradientUnits="userSpaceOnUse"><stop class="aa-qc_bpq"/><stop offset="1" class="sgzkazbng"/></radialGradient><radialGradient id="i5VwAbc" cx="0" cy="0" r="1" gradientTransform="rotate(97.806 5.627 18.884)scale(14.8428 16.097)" gradientUnits="userSpaceOnUse"><stop class="eju2vgt4d"/><stop offset="1" class="bxw6lab7o"/></radialGradient><radialGradient id="iVfZnIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.48237 2.16901 -2.50769 -.55769 13.099 15.078)" gradientUnits="userSpaceOnUse"><stop class="yop830m0b"/><stop offset="1" class="gswkbmlax"/></radialGradient><radialGradient id="i3g8GSd" cx="0" cy="0" r="1" gradientTransform="matrix(4.03802 5.4702 -1.94688 1.43716 13.981 15.115)" gradientUnits="userSpaceOnUse"><stop class="g6q5-wbfz"/><stop offset="1" class="e_ied2bjo"/></radialGradient><radialGradient id="i5gfBOd" cx="0" cy="0" r="1" gradientTransform="rotate(71.222 .884 14.309)scale(3.49228 5.58798)" gradientUnits="userSpaceOnUse"><stop class="ui2_0ybdj"/><stop offset="1" class="w2uktjmgi"/></radialGradient><radialGradient id="ibUDxgc" cx="0" cy="0" r="1" gradientTransform="rotate(48.528 -4.835 22.6)scale(7.97563 2.8404)" gradientUnits="userSpaceOnUse"><stop class="bjk5668ju"/><stop offset="1" class="bwycwac1y"/></radialGradient><radialGradient id="i122Tec" cx="0" cy="0" r="1" gradientTransform="rotate(90.603 5.583 11.703)scale(3.66287 5.87108)" gradientUnits="userSpaceOnUse"><stop class="qxi29kb9m"/><stop offset="1" class="actvtrbjk"/></radialGradient><radialGradient id="iFgp5Le" cx="0" cy="0" r="1" gradientTransform="matrix(6.05303 7.17112 -2.51201 2.12035 18.848 9.906)" gradientUnits="userSpaceOnUse"><stop class="v8zp64jiy"/><stop offset="1" class="bkeaszb1k"/></radialGradient><radialGradient id="iQHfldC" cx="0" cy="0" r="1" gradientTransform="matrix(-.21918 2.84874 -4.22103 -.32476 21.547 5.896)" gradientUnits="userSpaceOnUse"><stop class="cgh5w0d_z"/><stop offset="1" class="rk98v1bpu"/></radialGradient><radialGradient id="iTml3Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.085 20.117 -5.626)scale(6.20883 3.51252)" gradientUnits="userSpaceOnUse"><stop offset=".124" class="j1elw6aib"/><stop offset="1" class="yigpgkbbf"/></radialGradient><filter id="ijvNgwd" width="16.138" height="23.306" x="5.537" y="6.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.501961 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3536"/></filter><filter id="iMcEuvb" width="4.97" height="6.745" x="7.313" y="13.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".375"/></filter><filter id="in8F2Ec" width="4.694" height="6.195" x="8.842" y="10.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".375"/></filter><filter id="imn2EKb" width="5.517" height="7.481" x="10.772" y="7.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".375"/></filter><filter id="iLA5R6c" width="2.662" height="3.25" x="6.875" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.580392 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3536"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.317647 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3536" result="effect2_innerShadow_20020_3536"/></filter><filter id="izdg7we" width="3.158" height="2.858" x="3.69" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3536"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3536" result="effect2_innerShadow_20020_3536"/></filter><filter id="i5VRhyb" width="3.4" height="2.513" x="2.19" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.556863 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3536"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.301961 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3536" result="effect2_innerShadow_20020_3536"/></filter><filter id="i8YCUic" width="20.222" height="24.355" x="11.051" y="5.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.501961 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3536"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.35"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.529412 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3536" result="effect2_innerShadow_20020_3536"/></filter><filter id="iqmjjif" width="18.929" height="22.689" x="12.209" y="6.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation="1"/></filter><filter id="iKchtwd" width="7.187" height="8.888" x="11.868" y="14.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".625"/></filter><filter id="iEwtaDB" width="8.754" height="11.125" x="13.556" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".625"/></filter><filter id="iPJxigd" width="9.312" height="12.363" x="15.65" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".625"/></filter><filter id="ikJUabb" width="7.879" height="10.948" x="19.462" y="6.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".625"/></filter><filter id="iGhdtJz" width="3.934" height="12.452" x="26.451" y="10.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3536" stdDeviation=".625"/></filter><linearGradient id="ia7Y1He" x1="11.159" x2="7.065" y1="19.583" y2="15.141" gradientUnits="userSpaceOnUse"><stop class="ztleqlboe"/><stop offset="1" class="bphh2sb-w"/></linearGradient><linearGradient id="i13d88b" x1="10.092" x2="15.985" y1="12.01" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="kmtcovb0e"/><stop offset="1" class="zowzc7szw"/></linearGradient><linearGradient id="is6s9Ec" x1="12.809" x2="19.133" y1="7.722" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="z-yd28h4i"/><stop offset="1" class="h6jk3tbmj"/></linearGradient><linearGradient id="iKte4qd" x1="28.418" x2="28.418" y1="12.587" y2="21.288" gradientUnits="userSpaceOnUse"><stop class="rgoh73t2m"/><stop offset="1" class="m82u6cb-f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clapping-hands-medium-light" /></template>
<style>
.aa-qc_bpq {
  stop-color: var(--svg-color--dfa57d, #DFA57D);
}

.actvtrbjk {
  stop-color: var(--svg-color--d3a986, #D3A986);
  stop-opacity: 0;
}

.as4u9vbtv {
  stop-color: var(--svg-color--eaaf9c, #EAAF9C);
}

.asqc_1_dp {
  stroke-linecap: round;
  d: path("m10.092 11.67l2.194 3.695");
}

.at05xybeo {
  d: path("m18.68 24.347l-4.347-7.37a.894.894 0 0 1 1.51-.954l2.457 3.631a.667.667 0 0 0 1.115-.73l-3.83-6.036a.866.866 0 1 1 1.473-.91l3.733 6.205a.627.627 0 0 0 1.08-.636l-4.28-7.421a.956.956 0 0 1 1.654-.96l4.405 7.54a.553.553 0 0 0 .963-.544l-2.878-5.264a.908.908 0 0 1 1.586-.883l3.335 5.889c.004-.124.076-.751.173-1.153c.33-1.359.774-1.89 1.258-1.89c.501 0 1.091.214.93 1.788c-.32 3.126-.058 5.292 0 5.7c.058.406.953 4.761-3.176 6.593c-3.303 1.466-6.24-1.093-7.16-2.596");
}

.azdrq3fkw {
  stop-color: var(--svg-color--c6a180, #C6A180);
}

.biona6bwi {
  stop-color: var(--svg-color--b48e70, #B48E70);
}

.bjk5668ju {
  stop-color: var(--svg-color--e6a480, #E6A480);
}

.bkeaszb1k {
  stop-color: var(--svg-color--d89a6e, #D89A6E);
  stop-opacity: 0;
}

.bphh2sb-w {
  stop-color: var(--svg-color--a98167, #A98167);
  stop-opacity: 0;
}

.bwycwac1y {
  stop-color: var(--svg-color--e6a480, #E6A480);
  stop-opacity: 0;
}

.bxw6lab7o {
  stop-color: var(--svg-color--ffd0a8, #FFD0A8);
  stop-opacity: 0;
}

.cgh5w0d_z {
  stop-color: var(--svg-color--d7ac88, #D7AC88);
}

.cp1hi53fn {
  stop-color: var(--svg-color--8a564f, #8A564F);
}

.dks2s3bwa {
  stroke: var(--svg-color--ffcdab, #FFCDAB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m15.431 11.594l5.004 7.375");
}

.dqlb3ab4y {
  stop-color: var(--svg-color--c6a180, #C6A180);
  stop-opacity: 0;
}

.e_ied2bjo {
  stop-color: var(--svg-color--df9f7c, #DF9F7C);
  stop-opacity: 0;
}

.e2mbiomkg {
  d: path("M15.905 7.055a2.114 2.114 0 0 0-.691 2.907l.084.137c.57.097 1.099.43 1.427.962l5.314 8.622a2.114 2.114 0 0 0 2.167-3.19l-5.393-8.75a2.114 2.114 0 0 0-2.908-.688");
}

.eju2vgt4d {
  stop-color: var(--svg-color--ffd0a8, #FFD0A8);
}

.fdnjngwjh {
  d: path("m28.594 18.323l-2.753-5.217l.01-.195a2.183 2.183 0 1 1 4.36.21l-.156 3.246a2.18 2.18 0 0 1-1.462 1.956");
}

.fssmy6bpn {
  width: 4.224px;
  height: 14.575px;
  x: 4.757px;
  y: 15.519px;
  rx: 2.112px;
}

.ft5dv1b6b {
  fill: none;
}

.g6q5-wbfz {
  stop-color: var(--svg-color--df9f7c, #DF9F7C);
}

.gswkbmlax {
  stop-color: var(--svg-color--ce9c7b, #CE9C7B);
  stop-opacity: 0;
}

.gwznzxt3m {
  d: path("M13.854 10.38a2.087 2.087 0 0 0-.682 2.87l.527.855c.507.133.965.454 1.262.935l4.887 7.93a2.087 2.087 0 0 0 2.296-3.116l-5.42-8.793a2.087 2.087 0 0 0-2.87-.681");
}

.h6jk3tbmj {
  stop-color: var(--svg-color--cda587, #CDA587);
  stop-opacity: 0;
}

.i36s1qb_g {
  d: path("M10.307 7.382a2.107 2.107 0 0 0-.787 2.85l.077.14a2.07 2.07 0 0 1 1.43 1.004l3.569 6.183a2.27 2.27 0 0 0 2.284-3.436l-3.727-6.024a2.107 2.107 0 0 0-2.846-.717");
}

.ihs0mo99f {
  fill: var(--svg-color--187ec9, #187EC9);
  d: path("m8.336 4.887l-1.22-1.651a.468.468 0 0 1 .23-.723l1.36-.423c.3-.093.6.155.58.475l-.14 2.075c-.04.423-.56.588-.81.247");
}

.j1elw6aib {
  stop-color: var(--svg-color--b67d54, #B67D54);
}

.jr1omn8rw {
  stop-color: var(--svg-color--97606b, #97606B);
}

.kmtcovb0e {
  stop-color: var(--svg-color--ba9378, #BA9378);
}

.l79n4x80f {
  fill: var(--svg-color--1c75c1, #1C75C1);
  d: path("m4.932 9.305l-2.072.27a.463.463 0 0 1-.507-.57l.341-1.433a.472.472 0 0 1 .715-.28l1.73 1.162c.352.25.217.8-.207.851");
}

.m25qys66g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M28.51 12.587c-.311 2.733-.17 6.34 0 8.702");
}

.m82u6cb-f {
  stop-color: var(--svg-color--ffd0ab, #FFD0AB);
  stop-opacity: 0;
}

.ma39larlc {
  stop-color: var(--svg-color--b48e70, #B48E70);
  stop-opacity: 0;
}

.ma8v-lhgu {
  d: path("M20.308 29.269a6.863 6.863 0 0 0 9.199-3.32l.018.004c.955-1.96.778-3.607.632-4.972c-.036-.334-.07-.65-.085-.95c-.047-.907-.039-2.446-.02-3.605l.003-.06l.156-3.245a2.183 2.183 0 1 0-4.36-.21l-.01.192l-2.846-5.392a2.114 2.114 0 0 0-3.917.462l-.265-.43a2.114 2.114 0 0 0-3.6 2.22l.085.136a2.087 2.087 0 0 0-2.125 3.152l.526.854a2.112 2.112 0 0 0-2.334 3.15l5.378 8.726c1.11 1.753 2.528 2.79 3.565 3.288");
}

.mpj6i3b2o {
  stop-color: var(--svg-color--dea287, #DEA287);
}

.ofvrpqb3w {
  stop-color: var(--svg-color--b89174, #B89174);
  stop-opacity: 0;
}

.onehqlohp {
  stroke: var(--svg-color--ffd0a9, #FFD0A9);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m21.337 8.125l4.13 7.198");
}

.qxi29kb9m {
  stop-color: var(--svg-color--d3a986, #D3A986);
}

.r_s_w9-vw {
  stroke: var(--svg-color--fcc8a8, #FCC8A8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m13.744 16l3.437 5.138");
}

.rgoh73t2m {
  stop-color: var(--svg-color--ffd0ab, #FFD0AB);
}

.rk98v1bpu {
  stop-color: var(--svg-color--d7ac88, #D7AC88);
  stop-opacity: 0;
}

.sgzkazbng {
  stop-color: var(--svg-color--dfa57d, #DFA57D);
  stop-opacity: 0;
}

.t_r9idbvp {
  stop-color: var(--svg-color--a87b67, #A87B67);
}

.tjvmr_b3b {
  d: path("m13.64 8.885l3.24 5.238a2.26 2.26 0 0 1 .289 1.67l.26.466a2.184 2.184 0 1 0 3.766-2.21l-3.808-6.173a2.025 2.025 0 0 0-3.747 1.01");
}

.tsl9knb3d {
  stop-color: var(--svg-color--8a564f, #8A564F);
  stop-opacity: 0;
}

.ui2_0ybdj {
  stop-color: var(--svg-color--d1a281, #D1A281);
}

.uq8cwck3n {
  stroke: var(--svg-color--ffcea8, #FFCEA8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m17.525 8.397l5.561 8.613");
}

.v6h1a9bpm {
  stop-color: var(--svg-color--865645, #865645);
  stop-opacity: 0;
}

.v8zp64jiy {
  stop-color: var(--svg-color--d89a6e, #D89A6E);
}

.vc46r_c8i {
  stroke-linecap: round;
  d: path("m8.563 15.194l2.47 4.245");
}

.vfbfb-6go {
  stop-color: var(--svg-color--865645, #865645);
}

.voqk07baz {
  stop-color: var(--svg-color--b89174, #B89174);
}

.w_ccelber {
  stroke-linecap: round;
  d: path("m12.022 8.397l3.017 4.981");
}

.w05axs7ko {
  d: path("M13.64 8.885a2.024 2.024 0 0 1 3.747-1.009l3.808 6.172a2.184 2.184 0 1 1-3.766 2.211l-.26-.466a2.26 2.26 0 0 1-1.096 1.496a2.26 2.26 0 0 1-1.477.27l.03.053c.331.573.366 1.236.152 1.811l6.747 9.655c-.781.469-2.867 1.36-5.805.594c-2.71-.875-4.055-2.422-4.992-4.016L5.826 17.29a2.119 2.119 0 0 1 1.97-3.183l-.38-.683a2.075 2.075 0 0 1 2.181-3.053l-.077-.138a2.107 2.107 0 0 1 3.633-2.135z");
}

.w2uktjmgi {
  stop-color: var(--svg-color--d1a281, #D1A281);
  stop-opacity: 0;
}

.ws-w_lbeb {
  stop-color: var(--svg-color--a98367, #A98367);
}

.x28j_obaq {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m5.976 6.51l-1.86-.78a.443.443 0 0 1-.15-.72l.97-1.03a.45.45 0 0 1 .73.11l.89 1.81c.17.37-.2.77-.58.61");
}

.yaj7vcbgd {
  stop-color: var(--svg-color--a98367, #A98367);
  stop-opacity: 0;
}

.yet1k9bwh {
  d: path("m19.078 8.173l5.128 8.32a2.11 2.11 0 0 1-.104 2.369a2.114 2.114 0 0 0 3.69-2.062l-4.797-9.09a2.114 2.114 0 0 0-3.917.463");
}

.yigpgkbbf {
  stop-color: var(--svg-color--d99d70, #D99D70);
  stop-opacity: 0;
}

.yop830m0b {
  stop-color: var(--svg-color--ce9c7b, #CE9C7B);
}

.z-yd28h4i {
  stop-color: var(--svg-color--cda587, #CDA587);
}

.z7kzdbcte {
  width: 4.224px;
  height: 14.575px;
  x: 10.257px;
  y: 15.458px;
  rx: 2.112px;
}

.z7wy6obpq {
  d: path("M8.191 10.617a2.075 2.075 0 0 0-.775 2.807l.38.683c.681.046 1.328.42 1.694 1.055l3.26 5.646a2.13 2.13 0 0 0 1.877-3.196l-3.6-6.236a2.075 2.075 0 0 0-2.836-.76");
}

.zowzc7szw {
  stop-color: var(--svg-color--ba9378, #BA9378);
  stop-opacity: 0;
}

.ztleqlboe {
  stop-color: var(--svg-color--a98167, #A98167);
}

</style>
