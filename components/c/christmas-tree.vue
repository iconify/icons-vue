<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xnwx-vb4o"/><path fill="url(#ixnMZ2d)" class="h2sfk_vrw"/><path fill="url(#i6vJqUb)" class="h2sfk_vrw"/><path fill="url(#i6TfbSb)" class="h2sfk_vrw"/><path fill="url(#iw3h9mZ)" class="h2sfk_vrw"/><path fill="url(#iKxPKNc)" class="h2sfk_vrw"/><path fill="url(#iIN9ZVv)" class="h2sfk_vrw"/><g filter="url(#ixIM3dc)"><path fill="url(#iYR3Ovb)" class="fzibvxb9x"/><path fill="url(#imOxikd)" class="fzibvxb9x"/><path fill="url(#ibLzCmc)" class="fzibvxb9x"/><path fill="url(#isyjAEd)" class="fzibvxb9x"/></g><path fill="url(#iSYB7Le)" class="fzibvxb9x"/><path fill="url(#irFrAId)" class="iu9v_tbpz"/><path fill="url(#iIdQgzd)" class="iu9v_tbpz"/><path fill="url(#iWQvYyb)" class="iu9v_tbpz"/><path fill="url(#ilnacDb)" class="iu9v_tbpz"/><path fill="url(#iFrSyAc)" class="iu9v_tbpz"/><path fill="url(#i25hPJe)" class="iu9v_tbpz"/><path fill="url(#iyZtaUd)" class="iu9v_tbpz"/><path fill="url(#iwYIiQb)" class="gcyu_dbud"/><path fill="url(#iWEecKb)" class="gcyu_dbud"/><path fill="url(#iiV8RYd)" class="gcyu_dbud"/><path fill="url(#iL21RHe)" class="gcyu_dbud"/><path fill="url(#ie4AFdb)" class="gcyu_dbud"/><path fill="url(#iLXvbmx)" class="gcyu_dbud"/><path fill="url(#i8rZXnc)" class="gcyu_dbud"/><g filter="url(#iiEBQLe)"><ellipse fill="url(#ia0kred)" class="ndl8cfxfk"/><ellipse fill="url(#i9TMX3b)" class="ndl8cfxfk"/></g><g filter="url(#i5HffNd)"><ellipse fill="url(#ijDJvGb)" class="o-zzfk8ga"/><ellipse fill="url(#iVjOzBb)" class="o-zzfk8ga"/></g><g filter="url(#iOMMcqc)"><path fill="url(#ia6gjge)" class="t63m-ocwb"/></g><g filter="url(#iWURgbd)"><path fill="url(#inmBfjb)" class="d7f2s2-_b"/></g><g filter="url(#i7hCyAu)"><path class="lv7ytbcps"/></g><g filter="url(#iA15rTd)"><path class="iz3q31z2f"/></g><g filter="url(#ifnclFy)"><path class="hzuhs1khy"/></g><g filter="url(#iJwzk3b)"><path class="tqligobcn"/></g><g filter="url(#ieahjid)"><path class="yizm4abxw"/></g><path fill="url(#i4eHIIc)" class="lkg8jcbth"/><path fill="url(#i04IuHd)" class="i-g2_tbru"/><path fill="url(#iac7aPb)" class="z0-7dwb4y"/><path fill="url(#i2xIipc)" class="ruin9y45n"/><path fill="url(#imFKPec)" class="nhhgjkxdk"/><g filter="url(#ij81QPe)"><path class="uf70v9iff"/></g><path fill="url(#ibLFX9d)" class="tb4pl2bss"/><g filter="url(#i0LeWIc)"><path fill="url(#iuHU7dq)" class="jy2551f1m"/><path fill="url(#iDuqE8d)" class="jy2551f1m"/><path fill="url(#iHzgeVd)" class="jy2551f1m"/><path fill="url(#iRGjuPe)" class="jy2551f1m"/></g><defs><radialGradient id="ixnMZ2d" cx="0" cy="0" r="1" gradientTransform="rotate(70.328 -9.842 25.195)scale(3.03988 1.95488)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="xrivgk6fv"/><stop offset="1" class="ueq16fb8c"/></radialGradient><radialGradient id="i6vJqUb" cx="0" cy="0" r="1" gradientTransform="rotate(102.416 -2.668 18.873)scale(5.35131 2.99668)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="xrivgk6fv"/><stop offset=".967" class="ueq16fb8c"/></radialGradient><radialGradient id="iYR3Ovb" cx="0" cy="0" r="1" gradientTransform="matrix(-16.4585 0 0 -9.1748 24.238 23.098)" gradientUnits="userSpaceOnUse"><stop class="fzobf6bft"/><stop offset="1" class="f001zybfp"/></radialGradient><radialGradient id="imOxikd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.01113 -22.6983 0 15.968 18.086)" gradientUnits="userSpaceOnUse"><stop class="u88cwb8jd"/><stop offset="1" class="ba0kdvpfm"/></radialGradient><radialGradient id="ibLzCmc" cx="0" cy="0" r="1" gradientTransform="matrix(10.0406 0 0 1.58933 10.262 26.918)" gradientUnits="userSpaceOnUse"><stop class="n0mn_dy-c"/><stop offset="0" class="spdnavk4y"/><stop offset="1" class="ml9jtga1m"/></radialGradient><radialGradient id="iSYB7Le" cx="0" cy="0" r="1" gradientTransform="rotate(173.698 7.725 9.913)scale(9.53308 2.17183)" gradientUnits="userSpaceOnUse"><stop class="n986iwbda"/><stop offset="1" class="ojvvjhb0k"/></radialGradient><radialGradient id="irFrAId" cx="0" cy="0" r="1" gradientTransform="matrix(-11.1275 0 0 -6.54807 21.544 16.55)" gradientUnits="userSpaceOnUse"><stop class="fzobf6bft"/><stop offset="1" class="f001zybfp"/></radialGradient><radialGradient id="iWQvYyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.57645 -15.3461 0 15.953 12.974)" gradientUnits="userSpaceOnUse"><stop class="u88cwb8jd"/><stop offset="1" class="ba0kdvpfm"/></radialGradient><radialGradient id="ilnacDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.80124 9.00368 0 15.953 19.666)" gradientUnits="userSpaceOnUse"><stop class="z9ejxxonq"/><stop offset="1" class="uh3hbsbrq"/></radialGradient><radialGradient id="iFrSyAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.84375 7.43741 0 15.953 19.418)" gradientUnits="userSpaceOnUse"><stop class="sqvqvi0de"/><stop offset="1" class="tjoej6pls"/></radialGradient><radialGradient id="i25hPJe" cx="0" cy="0" r="1" gradientTransform="rotate(-164.816 12.303 8.289)scale(12.5421 6.6444)" gradientUnits="userSpaceOnUse"><stop offset=".871" class="o1d-5wbgb"/><stop offset="1" class="nuknrdb6c"/></radialGradient><radialGradient id="iyZtaUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07813 -7.3989 0 15.015 13.293)" gradientUnits="userSpaceOnUse"><stop class="sqvqvi0de"/><stop offset="1" class="tjoej6pls"/></radialGradient><radialGradient id="iWEecKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.8125 8.0625 0 15.968 14.137)" gradientUnits="userSpaceOnUse"><stop class="mfthzox2b"/><stop offset="1" class="i07xb9bnx"/></radialGradient><radialGradient id="iiV8RYd" cx="0" cy="0" r="1" gradientTransform="matrix(3.89304 -.78575 .934 4.62756 11.461 13.445)" gradientUnits="userSpaceOnUse"><stop class="xyjj9wbjf"/><stop offset="1" class="xxmwjyb0l"/></radialGradient><radialGradient id="ie4AFdb" cx="0" cy="0" r="1" gradientTransform="matrix(.86717 -.95535 1.85992 1.68825 12.346 14.276)" gradientUnits="userSpaceOnUse"><stop class="yby9906zi"/><stop offset="1" class="jypwbywvm"/></radialGradient><radialGradient id="iLXvbmx" cx="0" cy="0" r="1" gradientTransform="matrix(4.37193 -.38214 .0865 .98966 11.596 14.334)" gradientUnits="userSpaceOnUse"><stop class="sqvqvi0de"/><stop offset="1" class="tjoej6pls"/></radialGradient><radialGradient id="ia0kred" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74151 0 0 -1.76903 24.434 23.098)" gradientUnits="userSpaceOnUse"><stop class="h1olwgbiv"/><stop offset="1" class="npo2z7pct"/></radialGradient><radialGradient id="i9TMX3b" cx="0" cy="0" r="1" gradientTransform="matrix(13.1471 0 0 4.03716 10.655 23.098)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="d3zqjfbhp"/><stop offset="1" class="c0q7qjbdq"/></radialGradient><radialGradient id="ijDJvGb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.72205 0 0 -1.08151 21.524 16.55)" gradientUnits="userSpaceOnUse"><stop class="h1olwgbiv"/><stop offset="1" class="npo2z7pct"/></radialGradient><radialGradient id="iVjOzBb" cx="0" cy="0" r="1" gradientTransform="matrix(10.4217 0 0 2.46816 10.602 16.55)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="d3zqjfbhp"/><stop offset="1" class="c0q7qjbdq"/></radialGradient><radialGradient id="i4eHIIc" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.98 10.797)scale(2.00675 2.41724)" gradientUnits="userSpaceOnUse"><stop class="s9kj_-fkd"/><stop offset="1" class="e94504qim"/></radialGradient><radialGradient id="i04IuHd" cx="0" cy="0" r="1" gradientTransform="rotate(147.923 7.369 11.024)scale(2.36833)" gradientUnits="userSpaceOnUse"><stop class="nc6gu9lux"/><stop offset="1" class="w07ls78vf"/></radialGradient><radialGradient id="iac7aPb" cx="0" cy="0" r="1" gradientTransform="rotate(147.923 2.56 13.517)scale(2.36833)" gradientUnits="userSpaceOnUse"><stop class="nc6gu9lux"/><stop offset="1" class="w07ls78vf"/></radialGradient><radialGradient id="i2xIipc" cx="0" cy="0" r="1" gradientTransform="rotate(147.923 7.995 14.966)scale(2.36833)" gradientUnits="userSpaceOnUse"><stop class="nc6gu9lux"/><stop offset="1" class="w07ls78vf"/></radialGradient><radialGradient id="imFKPec" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.984 14.196)scale(2.00675 2.41724)" gradientUnits="userSpaceOnUse"><stop class="s9kj_-fkd"/><stop offset="1" class="e94504qim"/></radialGradient><radialGradient id="ibLFX9d" cx="0" cy="0" r="1" gradientTransform="rotate(135 6.506 8.985)scale(2.00675 2.41724)" gradientUnits="userSpaceOnUse"><stop class="s9kj_-fkd"/><stop offset="1" class="e94504qim"/></radialGradient><radialGradient id="iuHU7dq" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8236 1.90688 -2.77938 -5.57312 18.084 3.722)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="l9mbtjwsw"/><stop offset=".616" class="aw-ew3e2w"/></radialGradient><radialGradient id="iDuqE8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.40625 -1.47016 0 15.92 6.703)" gradientUnits="userSpaceOnUse"><stop offset=".42" class="rhzaotb7j"/><stop offset="1" class="thgsixuhe"/></radialGradient><radialGradient id="iHzgeVd" cx="0" cy="0" r="1" gradientTransform="matrix(.48437 1.74516 -.84783 .23532 16.461 2.344)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="xqahyqb7e"/><stop offset="1" class="hm7zi-5-c"/></radialGradient><radialGradient id="iRGjuPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3125 .55766 -.17352 -.40838 18.257 3.531)" gradientUnits="userSpaceOnUse"><stop class="xqahyqb7e"/><stop offset="1" class="hm7zi-5-c"/></radialGradient><filter id="ixIM3dc" width="18.153" height="7.641" x="7.016" y="19.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.6 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_199"/></filter><filter id="iiEBQLe" width="15.193" height="9.188" x="10.772" y="18.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation="1"/></filter><filter id="i5HffNd" width="12.873" height="7.172" x="10.28" y="12.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation="1"/></filter><filter id="iOMMcqc" width="6.273" height="2.773" x="14.054" y="10.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".5"/></filter><filter id="iWURgbd" width="5.153" height="7.673" x="15.544" y="5.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".5"/></filter><filter id="i7hCyAu" width="3.58" height="3.58" x="16.862" y="15.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".25"/></filter><filter id="iA15rTd" width="3.58" height="3.58" x="14.111" y="20.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".25"/></filter><filter id="ifnclFy" width="3.58" height="3.58" x="20.051" y="22.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".25"/></filter><filter id="iJwzk3b" width="3.58" height="3.58" x="11.8" y="14.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".25"/></filter><filter id="ieahjid" width="3.58" height="3.58" x="9.22" y="22.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".25"/></filter><filter id="ij81QPe" width="3.58" height="3.58" x="14.754" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_199" stdDeviation=".25"/></filter><filter id="i0LeWIc" width="4.327" height="4.139" x="13.757" y="2.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.741176 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_199"/></filter><linearGradient id="i6TfbSb" x1="15.968" x2="15.82" y1="30.096" y2="28.878" gradientUnits="userSpaceOnUse"><stop class="h8g7ummha"/><stop offset="1" class="i44ymih6r"/></linearGradient><linearGradient id="iw3h9mZ" x1="11.505" x2="12.928" y1="27.817" y2="27.98" gradientUnits="userSpaceOnUse"><stop class="ftjuge8hl"/><stop offset="1" class="b0qt7bheb"/></linearGradient><linearGradient id="iKxPKNc" x1="20.124" x2="19.227" y1="27.622" y2="27.98" gradientUnits="userSpaceOnUse"><stop class="ftjuge8hl"/><stop offset="1" class="b0qt7bheb"/></linearGradient><linearGradient id="iIN9ZVv" x1="15.968" x2="15.968" y1="29.742" y2="30.044" gradientUnits="userSpaceOnUse"><stop class="fcsd2-b1c"/><stop offset="1" class="bif2ztb0a"/></linearGradient><linearGradient id="isyjAEd" x1="17.059" x2="17.059" y1="27.195" y2="26.453" gradientUnits="userSpaceOnUse"><stop class="n0mn_dy-c"/><stop offset="1" class="ml9jtga1m"/></linearGradient><linearGradient id="iIdQgzd" x1="11.038" x2="16.964" y1="16.551" y2="16.551" gradientUnits="userSpaceOnUse"><stop class="q5e4s7g5t"/><stop offset="1" class="n5aruue2y"/></linearGradient><linearGradient id="iwYIiQb" x1="14.593" x2="19.343" y1="11.068" y2="11.068" gradientUnits="userSpaceOnUse"><stop class="gi1j30bmu"/><stop offset="1" class="e2kpw2zoc"/></linearGradient><linearGradient id="iL21RHe" x1="11.905" x2="13.551" y1="10.117" y2="10.733" gradientUnits="userSpaceOnUse"><stop class="xyjj9wbjf"/><stop offset="1" class="xxmwjyb0l"/></linearGradient><linearGradient id="i8rZXnc" x1="15.968" x2="15.968" y1="6.41" y2="7.593" gradientUnits="userSpaceOnUse"><stop class="jtze1414o"/><stop offset="1" class="tss5i0b3g"/></linearGradient><linearGradient id="ia6gjge" x1="18.608" x2="15.271" y1="12.297" y2="12.297" gradientUnits="userSpaceOnUse"><stop class="e84bsccgx"/><stop offset="1" class="ayil1ivkq"/></linearGradient><linearGradient id="inmBfjb" x1="18.498" x2="16.555" y1="9.862" y2="10.382" gradientUnits="userSpaceOnUse"><stop class="gm5xec7wv"/><stop offset="1" class="gctnlrb3i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:christmas-tree" /></template>
<style>
.aw-ew3e2w {
  stop-color: var(--svg-color--f8cd3d, #F8CD3D);
}

.ayil1ivkq {
  stop-color: var(--svg-color--9dd573, #9DD573);
  stop-opacity: 0;
}

.b0qt7bheb {
  stop-color: var(--svg-color--826c6a, #826C6A);
  stop-opacity: 0;
}

.ba0kdvpfm {
  stop-color: var(--svg-color--57a22c, #57A22C);
  stop-opacity: 0;
}

.bif2ztb0a {
  stop-color: var(--svg-color--8f5790, #8F5790);
}

.c0q7qjbdq {
  stop-color: var(--svg-color--9fdf6b, #9FDF6B);
}

.d3zqjfbhp {
  stop-color: var(--svg-color--9fdf6b, #9FDF6B);
  stop-opacity: 0;
}

.d7f2s2-_b {
  d: path("M16.545 6.891v5.673h3.152z");
}

.e2kpw2zoc {
  stop-color: var(--svg-color--7fc43a, #7FC43A);
}

.e84bsccgx {
  stop-color: var(--svg-color--9dd573, #9DD573);
}

.e94504qim {
  stop-color: var(--svg-color--e19e4a, #E19E4A);
}

.f001zybfp {
  stop-color: var(--svg-color--52915c, #52915C);
}

.fcsd2-b1c {
  stop-color: var(--svg-color--8f5790, #8F5790);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftjuge8hl {
  stop-color: var(--svg-color--826c6a, #826C6A);
}

.fzibvxb9x {
  d: path("M12.323 19.277h7.29c2.09 0 2.937.303 4.035 1.469c.68.81 1.343 1.68 1.265 3.281c-.093 1.922-1.203 2.89-3.5 2.89h-10.89c-2.297 0-3.407-.968-3.5-2.89c-.078-1.6.586-2.471 1.265-3.281c1.098-1.166 1.946-1.469 4.034-1.469");
}

.fzobf6bft {
  stop-color: var(--svg-color--80c156, #80C156);
}

.gctnlrb3i {
  stop-color: var(--svg-color--9ad869, #9AD869);
  stop-opacity: 0;
}

.gcyu_dbud {
  d: path("M14.653 7.188a1.5 1.5 0 0 1 2.63 0l2.586 4.71a1.3 1.3 0 0 1-1.14 1.926h-5.522a1.3 1.3 0 0 1-1.14-1.925z");
}

.gi1j30bmu {
  stop-color: var(--svg-color--5a9d57, #5A9D57);
}

.gm5xec7wv {
  stop-color: var(--svg-color--9ad869, #9AD869);
}

.h1olwgbiv {
  stop-color: var(--svg-color--a2e070, #A2E070);
}

.h2sfk_vrw {
  d: path("M19.126 29.98h-6.312c-.536 0-.943-.608-.825-1.242l.514-2.758h6.933l.515 2.758c.107.634-.29 1.242-.826 1.242");
}

.h8g7ummha {
  stop-color: var(--svg-color--7b4064, #7B4064);
}

.hm7zi-5-c {
  stop-color: var(--svg-color--fff15d, #FFF15D);
  stop-opacity: 0;
}

.hzuhs1khy {
  fill: var(--svg-color--72ac3a, #72AC3A);
  d: path("M21.841 25.279a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.i-g2_tbru {
  d: path("M18.75 18.247a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.i07xb9bnx {
  stop-color: var(--svg-color--3b9017, #3B9017);
  stop-opacity: 0;
}

.i44ymih6r {
  stop-color: var(--svg-color--7b4064, #7B4064);
  stop-opacity: 0;
}

.iu9v_tbpz {
  d: path("M13.595 13.824c-.997 0-1.85.348-2.564 1.18l-.084.11c-.421.545-.877 1.136-1.041 2.183c-.07 1.332.583 1.98 1.687 1.98h8.719c1.105 0 1.758-.648 1.688-1.98c-.165-1.047-.62-1.638-1.041-2.184l-.084-.11c-.715-.831-1.568-1.179-2.564-1.179z");
}

.iz3q31z2f {
  fill: var(--svg-color--539835, #539835);
  d: path("M15.9 23.368a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.jtze1414o {
  stop-color: var(--svg-color--639e52, #639E52);
}

.jy2551f1m {
  d: path("m16.98 3.147l.72.11c.37.05.51.5.25.76l-.52.51a.44.44 0 0 0-.13.39l.12.72a.45.45 0 0 1-.65.47l-.64-.34a.45.45 0 0 0-.42 0l-.64.34a.45.45 0 0 1-.65-.47l.12-.72a.44.44 0 0 0-.13-.39l-.52-.51a.446.446 0 0 1 .25-.76l.72-.1a.45.45 0 0 0 .34-.24l.32-.65c.16-.33.64-.33.8 0l.32.65c.07.11.19.21.34.23");
}

.jypwbywvm {
  stop-color: var(--svg-color--637374, #637374);
  stop-opacity: 0;
}

.l9mbtjwsw {
  stop-color: var(--svg-color--fff754, #FFF754);
}

.lkg8jcbth {
  d: path("M13.76 17.387a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.lv7ytbcps {
  fill: var(--svg-color--539835, #539835);
  d: path("M18.652 18.372a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.mfthzox2b {
  stop-color: var(--svg-color--3b9017, #3B9017);
}

.ml9jtga1m {
  stop-color: var(--svg-color--7f779b, #7F779B);
  stop-opacity: 0;
}

.n0mn_dy-c {
  stop-color: var(--svg-color--7f779b, #7F779B);
}

.n5aruue2y {
  stop-color: var(--svg-color--529257, #529257);
  stop-opacity: 0;
}

.n986iwbda {
  stop-color: var(--svg-color--105b0d, #105B0D);
}

.nc6gu9lux {
  stop-color: var(--svg-color--ff62a7, #FF62A7);
}

.ndl8cfxfk {
  cx: 18.369px;
  cy: 23.098px;
  rx: 5.597px;
  ry: 2.594px;
}

.nhhgjkxdk {
  d: path("M16.17 23.187a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.npo2z7pct {
  stop-color: var(--svg-color--a2e070, #A2E070);
  stop-opacity: 0;
}

.nuknrdb6c {
  stop-color: var(--svg-color--75947d, #75947D);
}

.o-zzfk8ga {
  cx: 16.716px;
  cy: 16.551px;
  rx: 4.436px;
  ry: 1.586px;
}

.o1d-5wbgb {
  stop-color: var(--svg-color--75947d, #75947D);
  stop-opacity: 0;
}

.ojvvjhb0k {
  stop-color: var(--svg-color--105b0d, #105B0D);
  stop-opacity: 0;
}

.q5e4s7g5t {
  stop-color: var(--svg-color--529257, #529257);
}

.rhzaotb7j {
  stop-color: var(--svg-color--d2ae38, #D2AE38);
}

.ruin9y45n {
  d: path("M22 25.197a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.s9kj_-fkd {
  stop-color: var(--svg-color--fff863, #FFF863);
}

.spdnavk4y {
  stop-color: var(--svg-color--6f708d, #6F708D);
}

.sqvqvi0de {
  stop-color: var(--svg-color--15600b, #15600B);
}

.t63m-ocwb {
  d: path("M15.054 12.302c.691-.312 2.514-.734 4.274.079c-.758.244-2.673.571-4.274-.079");
}

.tb4pl2bss {
  d: path("M16.79 12.507a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.thgsixuhe {
  stop-color: var(--svg-color--d2ae38, #D2AE38);
  stop-opacity: 0;
}

.tjoej6pls {
  stop-color: var(--svg-color--15600b, #15600B);
  stop-opacity: 0;
}

.tqligobcn {
  fill: var(--svg-color--539835, #539835);
  d: path("M13.59 17.387a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.tss5i0b3g {
  stop-color: var(--svg-color--70a960, #70A960);
  stop-opacity: 0;
}

.u88cwb8jd {
  stop-color: var(--svg-color--57a22c, #57A22C);
}

.ueq16fb8c {
  stop-color: var(--svg-color--5f2f2e, #5F2F2E);
  stop-opacity: 0;
}

.uf70v9iff {
  fill: var(--svg-color--539835, #539835);
  d: path("M16.544 12.683a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.uh3hbsbrq {
  stop-color: var(--svg-color--479820, #479820);
  stop-opacity: 0;
}

.w07ls78vf {
  stop-color: var(--svg-color--c23436, #C23436);
}

.xnwx-vb4o {
  fill: var(--svg-color--795556, #795556);
  d: path("M19.126 29.98h-6.312c-.536 0-.943-.608-.825-1.242l.514-2.758h6.933l.515 2.758c.107.634-.29 1.242-.826 1.242");
}

.xqahyqb7e {
  stop-color: var(--svg-color--fff15d, #FFF15D);
}

.xrivgk6fv {
  stop-color: var(--svg-color--5f2f2e, #5F2F2E);
}

.xxmwjyb0l {
  stop-color: var(--svg-color--608371, #608371);
  stop-opacity: 0;
}

.xyjj9wbjf {
  stop-color: var(--svg-color--608371, #608371);
}

.yby9906zi {
  stop-color: var(--svg-color--637374, #637374);
}

.yizm4abxw {
  fill: var(--svg-color--4f7068, #4F7068);
  d: path("M11.01 25.54a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.z0-7dwb4y {
  d: path("M11.19 25.407a1.29 1.29 0 1 0 0-2.58a1.29 1.29 0 0 0 0 2.58");
}

.z9ejxxonq {
  stop-color: var(--svg-color--479820, #479820);
}

</style>
