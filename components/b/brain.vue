<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ie6eq5d)" class="g32nxud2q"/><path fill="url(#ihJzHLd)" class="g32nxud2q"/><path fill="url(#ieVPN7d)" class="f-xdjubpn"/><path fill="url(#iNIFymc)" class="f-xdjubpn"/><path fill="url(#iAhKBeX)" class="f-xdjubpn"/><path fill="url(#i3vBzcv)" class="f-xdjubpn"/><path fill="url(#i8vYV2c)" class="f-xdjubpn"/><g filter="url(#iT7CvVd)"><circle stroke="url(#ibIwQcd)" class="a9i1q5b3f"/></g><g filter="url(#iXVnSqe)" class="a1jx2tbcc"><path class="ighdobcmy"/><path stroke="url(#itBqHzb)" class="pp1npubop"/></g><g filter="url(#i8JGqOc)"><path fill="url(#isLLord)" class="cp217hzrz"/></g><g filter="url(#inNT9Cb)"><path stroke="url(#ivfZslb)" clip-rule="evenodd" class="yhl2a0siy"/></g><g filter="url(#ifQTaEb)"><path fill="url(#iE313Gb)" clip-rule="evenodd" class="lyfw5451x"/></g><g filter="url(#i5LdAse)"><path class="k5l38rwfa"/></g><g filter="url(#iUiLoMe)" class="a1jx2tbcc"><path class="dmsl8vxuy"/><path stroke="url(#iwoEMSc)" class="oglh9zxsh"/><path stroke="url(#iKVXVke)" class="oglh9zxsh"/></g><g filter="url(#iay89Oc)"><path class="ze6qky5tg"/></g><g filter="url(#i7fSV4R)" class="a1jx2tbcc"><path class="t_fu81bpn"/><path stroke="url(#iPSPlMe)" class="tob3vvy2j"/></g><g filter="url(#irgcgOe)"><path fill="url(#iAnQwud)" class="ql65a_bdr"/></g><g filter="url(#iB0nJue)"><path fill="url(#iHrVAne)" class="ql65a_bdr"/></g><g filter="url(#ip2ZgKc)" class="y6dxxqbvo"><path class="wpfj19b6t"/><path stroke="url(#iGBvSTc)" class="t3hqum9nu"/><path stroke="url(#iBHrX9b)" class="t3hqum9nu"/></g><g filter="url(#iWI3JMT)"><path fill="url(#izDtkre)" class="qmgy1xm4d"/></g><g filter="url(#idGtMCE)"><path stroke="url(#iEi17se)" class="lwe6sgqds"/></g><g filter="url(#iGK0ICd)"><path stroke="url(#iY64Hue)" class="bf_73eb6l"/></g><g filter="url(#isP523R)"><path fill="url(#izCrkzQ)" class="gmgelrdch"/></g><g filter="url(#iggZ16d)"><path fill="url(#iA7Pvyc)" class="n57p5bcpj"/></g><defs><filter id="iT7CvVd" width="3.891" height="3.891" x="16.681" y="13.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".5"/></filter><filter id="iXVnSqe" width="9.394" height="11.941" x="2.945" y="5.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".4"/></filter><filter id="i8JGqOc" width="7.394" height="9.941" x="3.945" y="6.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.239216 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5011"/><feGaussianBlur result="effect2_foregroundBlur_20020_5011" stdDeviation=".1"/></filter><filter id="inNT9Cb" width="8.003" height="3.639" x="12.32" y="4.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".4"/></filter><filter id="ifQTaEb" width="5.803" height="1.438" x="13.42" y="5.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".05"/></filter><filter id="i5LdAse" width="2.714" height="1.059" x="13.499" y="5.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".05"/></filter><filter id="iUiLoMe" width="13.013" height="13.497" x="17.105" y="7.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5011"/><feGaussianBlur result="effect2_foregroundBlur_20020_5011" stdDeviation=".5"/></filter><filter id="iay89Oc" width="10.613" height="11.097" x="18.305" y="8.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5011"/><feGaussianBlur result="effect2_foregroundBlur_20020_5011" stdDeviation=".1"/></filter><filter id="i7fSV4R" width="8.139" height="8.816" x="6.965" y="13.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".4"/></filter><filter id="irgcgOe" width="6.006" height="7.022" x="7.998" y="14.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.196078 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5011"/><feGaussianBlur result="effect2_foregroundBlur_20020_5011" stdDeviation=".05"/></filter><filter id="iB0nJue" width="6.006" height="7.022" x="7.998" y="14.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".05"/></filter><filter id="ip2ZgKc" width="15.088" height="8.494" x="11.254" y="16.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".625"/></filter><filter id="iWI3JMT" width="11.738" height="5.144" x="12.93" y="18.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.32549 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5011"/><feGaussianBlur result="effect2_foregroundBlur_20020_5011" stdDeviation=".1"/></filter><filter id="idGtMCE" width="5.25" height="6.875" x="19.705" y="7.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".5"/></filter><filter id="iGK0ICd" width="8.156" height="7.813" x="21.048" y="12.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".75"/></filter><filter id="isP523R" width="6.175" height="7.858" x="23.467" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".5"/></filter><filter id="iggZ16d" width="4.153" height="5.906" x="6.349" y="12.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5011" stdDeviation=".25"/></filter><linearGradient id="ie6eq5d" x1="24.205" x2="20.455" y1="27.72" y2="27.72" gradientUnits="userSpaceOnUse"><stop class="fv3gkxczc"/><stop offset="1" class="zhbsv9dst"/></linearGradient><linearGradient id="ihJzHLd" x1="23.236" x2="23.236" y1="25.345" y2="26.876" gradientUnits="userSpaceOnUse"><stop class="w6kyxgb3g"/><stop offset="1" class="lei71bc-l"/></linearGradient><linearGradient id="i3vBzcv" x1="16.468" x2="16.468" y1="26.215" y2="25.552" gradientUnits="userSpaceOnUse"><stop class="vr7t62ztn"/><stop offset="1" class="togktq2pf"/></linearGradient><linearGradient id="ibIwQcd" x1="17.978" x2="18.969" y1="15.595" y2="14.312" gradientUnits="userSpaceOnUse"><stop class="kl9fmm9uh"/><stop offset="1" class="mju7lobqn"/></linearGradient><linearGradient id="isLLord" x1="6.014" x2="12.059" y1="12.955" y2="6.926" gradientUnits="userSpaceOnUse"><stop class="sz8qdsb_i"/><stop offset="1" class="rzh01fbcg"/></linearGradient><linearGradient id="ivfZslb" x1="13.52" x2="19.123" y1="6.376" y2="6.376" gradientUnits="userSpaceOnUse"><stop class="lvuo9p5_p"/><stop offset="1" class="v2tgkuemq"/></linearGradient><linearGradient id="iE313Gb" x1="13.959" x2="19.29" y1="6.483" y2="6.483" gradientUnits="userSpaceOnUse"><stop class="yk0rx7w0s"/><stop offset="1" class="i-l7nnvvt"/></linearGradient><linearGradient id="iAnQwud" x1="9.65" x2="13.926" y1="18.94" y2="13.989" gradientUnits="userSpaceOnUse"><stop class="vgc5kmt_a"/><stop offset="1" class="taevttb_u"/></linearGradient><linearGradient id="iGBvSTc" x1="13.13" x2="17.08" y1="20.866" y2="17.845" gradientUnits="userSpaceOnUse"><stop class="ty0-ihbrv"/><stop offset="1" class="tldakt0oz"/></linearGradient><linearGradient id="izDtkre" x1="15.173" x2="25.705" y1="20.126" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="dcn64x9fu"/><stop offset="1" class="ukd7oxxye"/></linearGradient><linearGradient id="iEi17se" x1="24.048" x2="20.923" y1="9.189" y2="14.001" gradientUnits="userSpaceOnUse"><stop class="rutrsfbfu"/><stop offset="1" class="i6pc9bbks"/></linearGradient><linearGradient id="iY64Hue" x1="23.736" x2="32.275" y1="13.939" y2="17.31" gradientUnits="userSpaceOnUse"><stop class="ln762cbgv"/><stop offset="1" class="crwyhkbkq"/></linearGradient><linearGradient id="izCrkzQ" x1="23.593" x2="28.804" y1="13.447" y2="13.447" gradientUnits="userSpaceOnUse"><stop offset=".286" class="d-7r496by"/><stop offset="1" class="s0e1f0bvh"/></linearGradient><radialGradient id="ieVPN7d" cx="0" cy="0" r="1" gradientTransform="matrix(13.54183 -15.45455 27.11604 23.76004 12.132 21.456)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="i_imqobti"/><stop offset=".906" class="sz6fvubde"/></radialGradient><radialGradient id="iNIFymc" cx="0" cy="0" r="1" gradientTransform="rotate(170.159 15.26 10.255)scale(12.4329 15.6948)" gradientUnits="userSpaceOnUse"><stop class="ugzgtz2au"/><stop offset="1" class="dgco33btd"/></radialGradient><radialGradient id="iAhKBeX" cx="0" cy="0" r="1" gradientTransform="rotate(-148.057 15.86 7.676)scale(24.4528 25.0635)" gradientUnits="userSpaceOnUse"><stop offset=".791" class="kxjixkbyf"/><stop offset="1" class="qot1ieb5a"/></radialGradient><radialGradient id="i8vYV2c" cx="0" cy="0" r="1" gradientTransform="rotate(-69.394 21.531 5.841)scale(8.3465 4.12598)" gradientUnits="userSpaceOnUse"><stop class="fo-yxvudw"/><stop offset="1" class="u04_3ubys"/></radialGradient><radialGradient id="itBqHzb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.203 7.029 5.025)scale(3.90853 6.19621)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="d3wxjx79v"/><stop offset="1" class="j8zktjb7b"/></radialGradient><radialGradient id="iwoEMSc" cx="0" cy="0" r="1" gradientTransform="rotate(106.928 8.562 13.637)scale(3.50452 4.03249)" gradientUnits="userSpaceOnUse"><stop class="ffovvfaww"/><stop offset="1" class="wze32bcum"/></radialGradient><radialGradient id="iKVXVke" cx="0" cy="0" r="1" gradientTransform="matrix(.90377 .0583 -.0671 1.03993 18.738 15.364)" gradientUnits="userSpaceOnUse"><stop class="z9yd4obqp"/><stop offset="1" class="h5ezrbc0c"/></radialGradient><radialGradient id="iPSPlMe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82812 -2.76564 4.2871 -4.38397 12.298 19.439)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="s2ikkphtb"/><stop offset="1" class="p-6jvcbdc"/></radialGradient><radialGradient id="iHrVAne" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 .49219 -.80077 1.47444 8.97 14.712)" gradientUnits="userSpaceOnUse"><stop class="vyqdsgbvd"/><stop offset="1" class="tl1tof8bm"/></radialGradient><radialGradient id="iBHrX9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -1 1.86944 2.45365 19.767 21.564)" gradientUnits="userSpaceOnUse"><stop class="ty0-ihbrv"/><stop offset="1" class="tldakt0oz"/></radialGradient><radialGradient id="iA7Pvyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24999 1.0469 -1.3889 -2.98504 9.814 15.658)" gradientUnits="userSpaceOnUse"><stop class="eq34akbcd"/><stop offset="1" class="n89svekgu"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:brain" /></template>
<style>
.a1jx2tbcc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
}

.a9i1q5b3f {
  cx: 18.627px;
  cy: 15.322px;
  r: 0.445px;
  stroke-linecap: round;
}

.bf_73eb6l {
  stroke-linecap: round;
  d: path("M23.048 14.47c.209.188.8.594 1.5.719c.875.156 2.313 1.031 2.657 3.094");
}

.cp217hzrz {
  d: path("M10.576 7.116a.2.2 0 0 0-.4.02c.015.278.006.905-.113 1.375c-2.17.524-3.604 1.789-4.514 3.209c-1.02 1.591-1.382 3.377-1.404 4.543a.2.2 0 0 0 .4.008c.02-1.105.367-2.816 1.34-4.335c.868-1.354 2.233-2.557 4.32-3.048a.2.2 0 0 0 .115-.026q.313-.069.647-.116a.2.2 0 0 0-.056-.396q-.213.03-.418.069a6 6 0 0 0 .083-1.303");
}

.crwyhkbkq {
  stop-color: var(--svg-color--ffbad9, #FFBAD9);
  stop-opacity: 0;
}

.d-7r496by {
  stop-color: var(--svg-color--ffacc7, #FFACC7);
}

.d3wxjx79v {
  stop-color: var(--svg-color--ff7daf, #FF7DAF);
  stop-opacity: 0;
}

.dcn64x9fu {
  stop-color: var(--svg-color--ff5ebf, #FF5EBF);
}

.dgco33btd {
  stop-color: var(--svg-color--ff94d4, #FF94D4);
  stop-opacity: 0;
}

.dmsl8vxuy {
  stroke: var(--svg-color--ff8dbd, #FF8DBD);
  d: path("M24.808 9.394a.2.2 0 0 0-.394-.066l-.01.057c-.043.257-.077.463-.154.718c-.084.275-.22.611-.474 1.121c-.38.76-.648 1.564-.764 1.97c-.257.07-.52.194-.832.377c-.36.211-.8.508-1.385.906c-.902.613-1.782.74-2.084.73a.2.2 0 1 0-.012.4c.385.012 1.348-.138 2.321-.8c.588-.4 1.015-.688 1.362-.89a3.2 3.2 0 0 1 .7-.327c.265.177.845.482 1.616.698a4.53 4.53 0 0 1 2.026 1.234c.758.792 1.456 2.074 1.594 4.149a.2.2 0 1 0 .399-.027c-.144-2.16-.875-3.532-1.704-4.398a4.93 4.93 0 0 0-2.208-1.344a6 6 0 0 1-1.412-.588c.109-.382.37-1.171.74-1.91c.261-.522.407-.88.5-1.184c.085-.282.123-.512.165-.766z");
}

.eq34akbcd {
  stop-color: var(--svg-color--ff9be1, #FF9BE1);
}

.f-xdjubpn {
  d: path("M30 18.179c-.322 4.59-1.916 7.886-6.662 7.886h-9.175c-2.407 0-4.371-1.253-5.126-3.16l-.327-.777c-.23-.581-.697-.698-1.32-.735c-2.915-.172-4.876-1.539-5.165-4.484c0-7.841 6.469-12.846 13.659-12.846A14.06 14.06 0 0 1 30 18.179");
}

.ffovvfaww {
  stop-color: var(--svg-color--ffabbe, #FFABBE);
}

.fo-yxvudw {
  stop-color: var(--svg-color--db60b2, #DB60B2);
}

.ft5dv1b6b {
  fill: none;
}

.fv3gkxczc {
  stop-color: var(--svg-color--ff4ac6, #FF4AC6);
}

.g32nxud2q {
  d: path("m22.499 28.752l-3.521-3.672h4.898v3.118c0 .721-.878 1.074-1.377.554");
}

.gmgelrdch {
  d: path("M24.467 13.172c.44-.595.863-2.276.939-2.654c.83.421 2.64 2.182 3.236 5.858c-.803-2.097-3.075-2.977-4.175-3.204");
}

.h5ezrbc0c {
  stop-color: var(--svg-color--ff8cce, #FF8CCE);
  stop-opacity: 0;
}

.i_imqobti {
  stop-color: var(--svg-color--ff6fe1, #FF6FE1);
}

.i-l7nnvvt {
  stop-color: var(--svg-color--ff788c, #FF788C);
}

.i6pc9bbks {
  stop-color: var(--svg-color--ffaebc, #FFAEBC);
  stop-opacity: 0;
}

.ighdobcmy {
  stroke: var(--svg-color--c0568d, #C0568D);
  d: path("M10.576 7.116a.2.2 0 0 0-.4.02c.015.278.006.905-.113 1.375c-2.17.524-3.604 1.789-4.514 3.209c-1.02 1.591-1.382 3.377-1.404 4.543a.2.2 0 0 0 .4.008c.02-1.105.367-2.816 1.34-4.335c.868-1.354 2.233-2.557 4.32-3.048a.2.2 0 0 0 .115-.026q.313-.069.647-.116a.2.2 0 0 0-.056-.396q-.213.03-.418.069a6 6 0 0 0 .083-1.303Z");
}

.j8zktjb7b {
  stop-color: var(--svg-color--ff7daf, #FF7DAF);
}

.k5l38rwfa {
  fill: var(--svg-color--cc5073, #CC5073);
  d: path("M16.113 5.652c-1.027.059-1.854.465-2.27.789a.2.2 0 0 1-.244.001c.446-.378 1.48-.953 2.514-.79");
}

.kl9fmm9uh {
  stop-color: var(--svg-color--ff8dcf, #FF8DCF);
}

.kxjixkbyf {
  stop-color: var(--svg-color--be6f90, #BE6F90);
  stop-opacity: 0;
}

.lei71bc-l {
  stop-color: var(--svg-color--ed4d98, #ED4D98);
  stop-opacity: 0;
}

.ln762cbgv {
  stop-color: var(--svg-color--ffbad9, #FFBAD9);
}

.lvuo9p5_p {
  stop-color: var(--svg-color--ff97b4, #FF97B4);
}

.lwe6sgqds {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M23.58 9.189c-.105.76-.75 2.65-2.5 4.125");
}

.lyfw5451x {
  fill-rule: evenodd;
  d: path("M18.818 6.374c-2.172-1.355-4.229-.513-4.975.067a.2.2 0 1 1-.245-.316c.836-.65 3.077-1.56 5.431-.09a.2.2 0 0 1-.212.34");
}

.mju7lobqn {
  stop-color: var(--svg-color--ff8dcf, #FF8DCF);
  stop-opacity: 0;
}

.n57p5bcpj {
  d: path("M8.814 15.267c-.388-.288-.224-.64-.094-.781l-.828-1.078c-1.5.906-1.219 2.53-.187 3.125c.825.475 1.083 1.385 1.109 1.78c.35-.712.937-1.202 1.187-1.359c-.156-1.015-.703-1.328-1.187-1.687");
}

.n89svekgu {
  stop-color: var(--svg-color--ff9be1, #FF9BE1);
  stop-opacity: 0;
}

.oglh9zxsh {
  d: path("M24.808 9.394a.2.2 0 0 0-.394-.066l-.01.057c-.043.257-.077.463-.154.718c-.084.275-.22.611-.474 1.121c-.38.76-.648 1.564-.764 1.97c-.257.07-.52.194-.832.377c-.36.211-.8.508-1.385.906c-.902.613-1.782.74-2.084.73a.2.2 0 1 0-.012.4c.385.012 1.348-.138 2.321-.8c.588-.4 1.015-.688 1.362-.89a3.2 3.2 0 0 1 .7-.327c.265.177.845.482 1.616.698a4.53 4.53 0 0 1 2.026 1.234c.758.792 1.456 2.074 1.594 4.149a.2.2 0 1 0 .399-.027c-.144-2.16-.875-3.532-1.704-4.398a4.93 4.93 0 0 0-2.208-1.344a6 6 0 0 1-1.412-.588c.109-.382.37-1.171.74-1.91c.261-.522.407-.88.5-1.184c.085-.282.123-.512.165-.766z");
}

.p-6jvcbdc {
  stop-color: var(--svg-color--ff8cdc, #FF8CDC);
}

.pp1npubop {
  d: path("M10.576 7.116a.2.2 0 0 0-.4.02c.015.278.006.905-.113 1.375c-2.17.524-3.604 1.789-4.514 3.209c-1.02 1.591-1.382 3.377-1.404 4.543a.2.2 0 0 0 .4.008c.02-1.105.367-2.816 1.34-4.335c.868-1.354 2.233-2.557 4.32-3.048a.2.2 0 0 0 .115-.026q.313-.069.647-.116a.2.2 0 0 0-.056-.396q-.213.03-.418.069a6 6 0 0 0 .083-1.303Z");
}

.ql65a_bdr {
  d: path("M9.217 14.644a.2.2 0 1 0-.15.37c.441.18 1.33.826 1.389 1.971c-.332.293-.625.61-.882.938c-.89 1.14-1.35 2.423-1.474 3.3a.2.2 0 0 0 .396.056c.115-.81.547-2.026 1.393-3.11c.844-1.079 2.094-2.019 3.847-2.298a.2.2 0 1 0-.063-.395a6.3 6.3 0 0 0-2.847 1.207c-.188-1.18-1.123-1.843-1.609-2.039");
}

.qmgy1xm4d {
  d: path("M17.521 18.39a.2.2 0 0 1 .122.256c-.175.497-.367.883-.583 1.182c.063.2.29.536.895.536h1.568a1.43 1.43 0 0 1 .849.215l1.886-.276c.226-.028.502-.11.755-.245c.253-.136.47-.32.595-.545c.3-.537.45-.79.49-.853a.2.2 0 0 1 .338.214c-.033.052-.178.296-.479.834c-.174.313-.458.543-.755.702c-.296.16-.62.255-.892.29l-1.57.23c.116.16.206.362.255.61c.174.888.25 1.266.265 1.344a.2.2 0 1 1-.392.078l-.266-1.344c-.076-.386-.27-.6-.472-.718c-.21-.123-.44-.15-.58-.137h-1.596c-.644 0-1.006-.302-1.18-.602q-.06.059-.124.11c-.4.327-.853.443-1.356.492c-.83.08-1.736-.178-2.044-.313a.2.2 0 1 1 .16-.366c.264.115 1.101.353 1.846.28c.465-.044.828-.147 1.14-.402c.316-.258.602-.692.87-1.45a.2.2 0 0 1 .255-.121");
}

.qot1ieb5a {
  stop-color: var(--svg-color--be6f90, #BE6F90);
}

.rutrsfbfu {
  stop-color: var(--svg-color--ffaebc, #FFAEBC);
}

.rzh01fbcg {
  stop-color: var(--svg-color--e85b90, #E85B90);
}

.s0e1f0bvh {
  stop-color: var(--svg-color--ffacc7, #FFACC7);
  stop-opacity: 0;
}

.s2ikkphtb {
  stop-color: var(--svg-color--ff8cdc, #FF8CDC);
  stop-opacity: 0;
}

.sz6fvubde {
  stop-color: var(--svg-color--ff9e9d, #FF9E9D);
}

.sz8qdsb_i {
  stop-color: var(--svg-color--ca4794, #CA4794);
}

.t_fu81bpn {
  stroke: var(--svg-color--de4b9e, #DE4B9E);
  d: path("M9.217 14.644a.2.2 0 1 0-.15.37c.441.18 1.329.826 1.389 1.971c-.332.293-.625.61-.882.938c-.89 1.14-1.282 2.017-1.407 2.894a.2.2 0 0 0 .396.056c.115-.81.48-1.62 1.326-2.704c.844-1.079 2.093-2.019 3.847-2.298a.2.2 0 1 0-.063-.395a6.3 6.3 0 0 0-2.847 1.207c-.188-1.18-1.123-1.843-1.61-2.039Z");
}

.t3hqum9nu {
  d: path("M17.521 18.506a.2.2 0 0 1 .122.255c-.175.497-.367.883-.583 1.182c.063.2.29.535.895.535h1.568a1.43 1.43 0 0 1 .849.215l1.886-.276c.226-.028.502-.109.755-.244c.253-.136.47-.32.595-.545c.3-.537.45-.791.49-.854a.2.2 0 1 1 .338.215c-.033.052-.178.296-.479.834c-.174.312-.458.543-.755.702c-.296.16-.62.255-.892.29l-1.57.229c.116.161.206.363.255.611c.174.888.25 1.266.265 1.344a.2.2 0 1 1-.392.078l-.266-1.344c-.076-.387-.27-.6-.472-.719a1 1 0 0 0-.58-.136h-1.596c-.644 0-1.006-.303-1.18-.602q-.06.058-.124.11c-.4.326-.853.443-1.356.492c-.83.08-1.736-.178-2.044-.313a.2.2 0 1 1 .16-.367c.264.116 1.101.353 1.846.281c.465-.045.828-.147 1.14-.403c.316-.258.602-.692.87-1.449a.2.2 0 0 1 .255-.121Z");
}

.taevttb_u {
  stop-color: var(--svg-color--f24fa6, #F24FA6);
}

.tl1tof8bm {
  stop-color: var(--svg-color--ff83dd, #FF83DD);
  stop-opacity: 0;
}

.tldakt0oz {
  stop-color: var(--svg-color--ff7cdf, #FF7CDF);
  stop-opacity: 0;
}

.tob3vvy2j {
  d: path("M9.217 14.644a.2.2 0 1 0-.15.37c.441.18 1.329.826 1.389 1.971c-.332.293-.625.61-.882.938c-.89 1.14-1.282 2.017-1.407 2.894a.2.2 0 0 0 .396.056c.115-.81.48-1.62 1.326-2.704c.844-1.079 2.093-2.019 3.847-2.298a.2.2 0 1 0-.063-.395a6.3 6.3 0 0 0-2.847 1.207c-.188-1.18-1.123-1.843-1.61-2.039Z");
}

.togktq2pf {
  stop-color: var(--svg-color--ff99f8, #FF99F8);
  stop-opacity: 0;
}

.ty0-ihbrv {
  stop-color: var(--svg-color--ff9ce7, #FF9CE7);
}

.u04_3ubys {
  stop-color: var(--svg-color--db60b2, #DB60B2);
  stop-opacity: 0;
}

.ugzgtz2au {
  stop-color: var(--svg-color--ff94d4, #FF94D4);
}

.ukd7oxxye {
  stop-color: var(--svg-color--ff56a5, #FF56A5);
}

.v2tgkuemq {
  stop-color: var(--svg-color--ff97b4, #FF97B4);
  stop-opacity: 0;
}

.vgc5kmt_a {
  stop-color: var(--svg-color--dd45a8, #DD45A8);
}

.vr7t62ztn {
  stop-color: var(--svg-color--ff99f8, #FF99F8);
}

.vyqdsgbvd {
  stop-color: var(--svg-color--ff83dd, #FF83DD);
}

.w6kyxgb3g {
  stop-color: var(--svg-color--ed4d98, #ED4D98);
}

.wpfj19b6t {
  stroke: var(--svg-color--ff65c6, #FF65C6);
  d: path("M17.521 18.506a.2.2 0 0 1 .122.255c-.175.497-.367.883-.583 1.182c.063.2.29.535.895.535h1.568a1.43 1.43 0 0 1 .849.215l1.886-.276c.226-.028.502-.109.755-.244c.253-.136.47-.32.595-.545c.3-.537.45-.791.49-.854a.2.2 0 1 1 .338.215c-.033.052-.178.296-.479.834c-.174.312-.458.543-.755.702c-.296.16-.62.255-.892.29l-1.57.229c.116.161.206.363.255.611c.174.888.25 1.266.265 1.344a.2.2 0 1 1-.392.078l-.266-1.344c-.076-.387-.27-.6-.472-.719a1 1 0 0 0-.58-.136h-1.596c-.644 0-1.006-.303-1.18-.602q-.06.058-.124.11c-.4.326-.853.443-1.356.492c-.83.08-1.736-.178-2.044-.313a.2.2 0 1 1 .16-.367c.264.116 1.101.353 1.846.281c.465-.045.828-.147 1.14-.403c.316-.258.602-.692.87-1.449a.2.2 0 0 1 .255-.121Z");
}

.wze32bcum {
  stop-color: var(--svg-color--ffabbe, #FFABBE);
  stop-opacity: 0;
}

.y6dxxqbvo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
}

.yhl2a0siy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M18.818 6.374c-2.172-1.355-4.229-.513-4.975.067a.2.2 0 1 1-.245-.316c.836-.65 3.077-1.56 5.431-.09a.2.2 0 0 1-.212.34Z");
}

.yk0rx7w0s {
  stop-color: var(--svg-color--ff6791, #FF6791);
}

.z9yd4obqp {
  stop-color: var(--svg-color--ff8cce, #FF8CCE);
}

.ze6qky5tg {
  fill: var(--svg-color--ff73a8, #FF73A8);
  d: path("M24.808 9.394a.2.2 0 0 0-.394-.066l-.01.057c-.043.257-.077.463-.154.718c-.084.275-.22.611-.474 1.121c-.38.76-.648 1.564-.764 1.97c-.257.07-.52.194-.832.377c-.36.211-.8.508-1.385.906c-.902.613-1.782.74-2.084.73a.2.2 0 1 0-.012.4c.385.012 1.348-.138 2.321-.8c.588-.4 1.015-.688 1.362-.89a3.2 3.2 0 0 1 .7-.327c.265.177.845.482 1.616.698a4.53 4.53 0 0 1 2.026 1.234c.758.792 1.456 2.074 1.594 4.149a.2.2 0 1 0 .399-.027c-.144-2.16-.875-3.532-1.704-4.398a4.93 4.93 0 0 0-2.208-1.344a6 6 0 0 1-1.412-.588c.109-.382.37-1.171.74-1.91c.261-.522.407-.88.5-1.184c.085-.282.123-.512.165-.766z");
}

.zhbsv9dst {
  stop-color: var(--svg-color--ff3fc0, #FF3FC0);
}

</style>
