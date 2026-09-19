<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="ft5dv1b6b"><path fill="url(#idYOHtb)" class="v264kjbrf"/><path fill="url(#iG2oCMo)" class="ggt0791ke"/><g filter="url(#ir6QRFe)"><path fill="url(#iJQcWYc)" class="cof5sjb1u"/></g><g filter="url(#iuX9idd)"><path fill="url(#inRaDud)" class="oyoco-vfe"/></g><g filter="url(#iLfhWkc)"><path fill="url(#iPhvufe)" class="sj6o6hbjt"/></g><g filter="url(#ihTCtte)"><path stroke="url(#iW4hhwc)" class="gee96sbqr"/></g><g filter="url(#iUuLcnr)"><path fill="url(#iJDMdbT)" class="zasi__b9e"/></g><g filter="url(#ipSl32b)"><ellipse class="ag55nabyn"/></g><defs><filter id="ir6QRFe" width="10.491" height="15.799" x="14.779" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6129" stdDeviation="1"/></filter><filter id="iuX9idd" width="13.569" height="16.002" x="16.978" y="5.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6129" stdDeviation=".75"/></filter><filter id="iLfhWkc" width="12.852" height="21.845" x="5.284" y="3.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6129" stdDeviation="1.5"/></filter><filter id="ihTCtte" width="7.531" height="5.959" x="21.717" y="5.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6129" stdDeviation=".5"/></filter><filter id="iUuLcnr" width="16" height="21.875" x="1.717" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6129" stdDeviation="1"/></filter><filter id="ipSl32b" width="6.095" height="4.586" x="6.09" y="4.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6129" stdDeviation="1"/></filter><linearGradient id="iG2oCMo" x1="17.217" x2="18.978" y1="7.628" y2="9.046" gradientUnits="userSpaceOnUse"><stop class="y3-jcgu9q"/><stop offset=".68" class="z2nilm9io"/></linearGradient><linearGradient id="iJQcWYc" x1="18.529" x2="27.091" y1="17.699" y2="-1.878" gradientUnits="userSpaceOnUse"><stop class="n6py9cbnh"/><stop offset="1" class="kw94nnytc"/></linearGradient><linearGradient id="iW4hhwc" x1="27.873" x2="24.842" y1="8.355" y2="6.605" gradientUnits="userSpaceOnUse"><stop class="z6_tf9m8r"/><stop offset="1" class="b46ggxb6o"/></linearGradient><linearGradient id="iJDMdbT" x1="18.654" x2="9.279" y1="30.608" y2="15.511" gradientUnits="userSpaceOnUse"><stop class="djjn4maas"/><stop offset="1" class="yl_otjbty"/></linearGradient><radialGradient id="idYOHtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 26.5871 -32.8735 0 15.861 5.842)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="b3euzjgjd"/><stop offset=".469" class="c0mx4cc7j"/><stop offset="1" class="z1_t8xbos"/></radialGradient><radialGradient id="inRaDud" cx="0" cy="0" r="1" gradientTransform="matrix(-6.06251 9.43753 -3.93674 -2.5289 26.467 8.324)" gradientUnits="userSpaceOnUse"><stop class="z6_tf9m8r"/><stop offset="1" class="b46ggxb6o"/></radialGradient><radialGradient id="iPhvufe" cx="0" cy="0" r="1" gradientTransform="rotate(-124.103 14.268 4.892)scale(16.8321 6.35394)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="z-togtbqu"/><stop offset="1" class="b46ggxb6o"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:black-heart" /></template>
<style>
.ag55nabyn {
  cx: 9.138px;
  cy: 6.492px;
  fill: var(--svg-color--857f8c, #857F8C);
  rx: 1.048px;
  ry: 0.293px;
}

.b3euzjgjd {
  stop-color: var(--svg-color--49454e, #49454E);
}

.b46ggxb6o {
  stop-color: var(--svg-color--6c6a70, #6C6A70);
  stop-opacity: 0;
}

.c0mx4cc7j {
  stop-color: var(--svg-color--32263e, #32263E);
}

.cof5sjb1u {
  d: path("M16.779 10.672v6.83c0 1.07 1.6 1.467 2.148.548c2.701-4.536 5.649-8.782 3.727-11.039c-.84-.987-4.557 1.163-5.762 3.215a.9.9 0 0 0-.113.446");
}

.djjn4maas {
  stop-color: var(--svg-color--492965, #492965);
}

.ft5dv1b6b {
  fill: none;
}

.gee96sbqr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.842 6.324c1.086-.135 4.062.281 5.28 3.687");
}

.ggt0791ke {
  d: path("m15.31 8.015l.348.318c.954.873 2.498.63 3.364-.331c.914-1.014 2.14-2.063 3.625-2.791c-1.404.03-2.842.507-4.148 1.534q-.228.177-.476.366c-.497.38-1.026.786-1.422 1.175c-.237.234-.656.258-.903.034a14 14 0 0 0-.389-.34z");
}

.kw94nnytc {
  stop-color: var(--svg-color--2c2834, #2C2834);
  stop-opacity: 0;
}

.n6py9cbnh {
  stop-color: var(--svg-color--27232e, #27232E);
}

.oyoco-vfe {
  d: path("M26 7.12c2.597 1.069 3.974 3.487 2.342 7.454c-2.875 5.437-5.963 5.534-7.563 4.875c-1.875-1.125-3.195-4.408-1.562-8.375S23.4 6.05 25.999 7.12");
}

.sj6o6hbjt {
  d: path("m14.931 9.39l.205 13.406C8.261 16.108 7.03 8.943 9.37 7.336c1.67-1.147 4.812.491 5.562 2.054");
}

.v264kjbrf {
  d: path("M15.196 29.41a1.73 1.73 0 0 0 1.71-.022c3.583-2.048 9.81-6.761 12.255-12.885c3.589-7.972-4.838-14.336-10.663-9.759c-.607.478-1.371 1.024-1.897 1.542c-.237.234-.656.258-.903.033c-.691-.628-1.771-1.435-2.465-1.904c-4.965-3.36-14 1.068-10.146 10.52c1.412 4.242 8.14 10.26 12.109 12.475");
}

.y3-jcgu9q {
  stop-color: var(--svg-color--535255, #535255);
}

.yl_otjbty {
  stop-color: var(--svg-color--492965, #492965);
  stop-opacity: 0;
}

.z-togtbqu {
  stop-color: var(--svg-color--7d7a82, #7D7A82);
}

.z1_t8xbos {
  stop-color: var(--svg-color--371f4b, #371F4B);
}

.z2nilm9io {
  stop-color: var(--svg-color--535255, #535255);
  stop-opacity: 0;
}

.z6_tf9m8r {
  stop-color: var(--svg-color--6c6a70, #6C6A70);
}

.zasi__b9e {
  d: path("M3.717 13.733c2.062 8.063 9.479 13.23 12 14.813c-2.9-5.25-5.563-15.542-5.625-17.875z");
}

</style>
