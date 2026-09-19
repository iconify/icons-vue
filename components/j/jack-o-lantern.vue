<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="b3i3jcd0y"/><path fill="url(#iJbMWRc)" class="myl_0gbqy"/><path fill="url(#iWWZMjd)" class="myl_0gbqy"/><path fill="url(#iaPBmmd)" class="myl_0gbqy"/><g filter="url(#ivf9ccb)"><path fill="url(#iMkUBKw)" class="avh505bqb"/><path fill="url(#i3qYuQb)" class="avh505bqb"/><path fill="url(#ia2aLwK)" class="avh505bqb"/><path fill="url(#inibmFd)" class="avh505bqb"/></g><path fill="url(#i5mMcId)" class="avh505bqb"/><g filter="url(#iYG0Fsb)"><path fill="url(#i0NDoJb)" class="oysb_w93s"/></g><g clip-rule="evenodd" filter="url(#inJD15W)" class="d2kvgvbvc"><path fill="url(#i4J6RZF)" class="a48eqcbch"/><path fill="url(#i8WkSwb)" class="a48eqcbch"/></g><g filter="url(#i9PH55b)"><path class="dhc15-kyi"/><path fill="url(#iPMu8Ac)" class="kf4qj6bfi"/><path fill="url(#iCkK0yo)" class="kf4qj6bfi"/></g><g filter="url(#irIFdqD)"><path class="adpypzb_l"/><path fill="url(#iHHWARc)" class="zr1hl7bvh"/><path fill="url(#i9DMSxd)" class="zr1hl7bvh"/></g><g filter="url(#iDYN8nb)"><path class="kj0fl6pwj"/></g><defs><radialGradient id="iaPBmmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.507 .4301 -.46 -.54224 18.014 4.363)" gradientUnits="userSpaceOnUse"><stop class="tsy_1np-n"/><stop offset="1" class="af74ivbav"/></radialGradient><radialGradient id="ia2aLwK" cx="0" cy="0" r="1" gradientTransform="rotate(151.53 13.365 10.244)scale(15.0276 24.0101)" gradientUnits="userSpaceOnUse"><stop class="hes3ez37z"/><stop offset="1" class="vflrmjbae"/></radialGradient><radialGradient id="inibmFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.09375 9.14205 0 15.953 18.531)" gradientUnits="userSpaceOnUse"><stop class="l5g19r_dy"/><stop offset="1" class="nv7l02rai"/></radialGradient><radialGradient id="i5mMcId" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.84375 1.43852 3.94261 2.25 24.219)" gradientUnits="userSpaceOnUse"><stop class="kf4926hvk"/><stop offset="1" class="u9jzbkbyo"/></radialGradient><radialGradient id="i4J6RZF" cx="0" cy="0" r="1" gradientTransform="matrix(11.87498 -6.62498 4.02236 7.20989 11.688 24)" gradientUnits="userSpaceOnUse"><stop class="zjhfjrbwr"/><stop offset="1" class="snke8hbii"/></radialGradient><radialGradient id="i8WkSwb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.76628 9.41783 -9.26654 -5.67365 17.875 15.486)" gradientUnits="userSpaceOnUse"><stop offset=".876" class="v52okgxcd"/><stop offset="1" class="erwk3vbee"/></radialGradient><radialGradient id="iCkK0yo" cx="0" cy="0" r="1" gradientTransform="rotate(-44.3 28.498 -16.82)scale(1.75341 .86552)" gradientUnits="userSpaceOnUse"><stop class="kvqnmlbyr"/><stop offset="1" class="qi8hcibrf"/></radialGradient><radialGradient id="i9DMSxd" cx="0" cy="0" r="1" gradientTransform="rotate(-44.3 22.99 -3.29)scale(1.75341 .86552)" gradientUnits="userSpaceOnUse"><stop class="kvqnmlbyr"/><stop offset="1" class="qi8hcibrf"/></radialGradient><linearGradient id="iJbMWRc" x1="15.733" x2="16.218" y1="5.403" y2="5.859" gradientUnits="userSpaceOnUse"><stop class="ggi4hnyeq"/><stop offset="1" class="aw-js1viw"/></linearGradient><linearGradient id="iWWZMjd" x1="18.166" x2="17.273" y1="6.633" y2="6.633" gradientUnits="userSpaceOnUse"><stop class="l66bqnbww"/><stop offset="1" class="cx4wtzbcy"/></linearGradient><linearGradient id="iMkUBKw" x1="15.953" x2="17.281" y1="7.063" y2="31.052" gradientUnits="userSpaceOnUse"><stop class="iv40aibfj"/><stop offset="1" class="fnqjygtsy"/><stop offset="1" class="zf92i_-sd"/></linearGradient><linearGradient id="i3qYuQb" x1="2.677" x2="5.644" y1="14.688" y2="15.701" gradientUnits="userSpaceOnUse"><stop class="mupc-2vci"/><stop offset="1" class="qx_v0mhrw"/></linearGradient><linearGradient id="i0NDoJb" x1="26.918" x2="18.452" y1="13.819" y2="16.352" gradientUnits="userSpaceOnUse"><stop class="ajuf8q--x"/><stop offset="1" class="sa_23dr3t"/></linearGradient><linearGradient id="iPMu8Ac" x1="20.281" x2="20.656" y1="13.781" y2="14.156" gradientUnits="userSpaceOnUse"><stop class="ohp1fvxsw"/><stop offset="1" class="vlrgmpc_h"/></linearGradient><linearGradient id="iHHWARc" x1="9.266" x2="9.641" y1="13.781" y2="14.156" gradientUnits="userSpaceOnUse"><stop class="ohp1fvxsw"/><stop offset="1" class="vlrgmpc_h"/></linearGradient><filter id="ivf9ccb" width="28.091" height="23.688" x="1.907" y="6.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.592157 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_170"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.627451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_170" result="effect2_innerShadow_18_170"/></filter><filter id="iYG0Fsb" width="10.33" height="16.301" x="20.07" y="8.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_170" stdDeviation="1"/></filter><filter id="inJD15W" width="17.484" height="7.841" x="6.46" y="17.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.0901961 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_170"/></filter><filter id="i9PH55b" width="3.887" height="2.581" x="19.258" y="13.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.121569 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_170"/></filter><filter id="irIFdqD" width="3.886" height="2.581" x="8.242" y="13.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.121569 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_170"/></filter><filter id="iDYN8nb" width="9.159" height="18.689" x="1.054" y="7.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_170" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:jack-o-lantern" /></template>
<style>
.a48eqcbch {
  d: path("M17.418 17.063h-2.931a2.227 2.227 0 0 1-4.116 0h-2.41v.105a7.996 7.996 0 0 0 5.976 7.736a2.219 2.219 0 0 1 4.031 0a7.996 7.996 0 0 0 5.976-7.841h-2.41a2.227 2.227 0 0 1-4.116 0");
}

.adpypzb_l {
  fill: var(--svg-color--583674, #583674);
  d: path("M9.93 13.276L8.81 14.63a.3.3 0 0 0 .232.491h2.785a.3.3 0 0 0 .23-.492l-1.127-1.355a.65.65 0 0 0-1.001.002");
}

.af74ivbav {
  stop-color: var(--svg-color--c4e973, #C4E973);
  stop-opacity: 0;
}

.ajuf8q--x {
  stop-color: var(--svg-color--ffab81, #FFAB81);
}

.avh505bqb {
  d: path("M12.857 7.063h6.19c4.767 0 8.152 2.65 9.225 6.5l1.344 4.825C31.23 24.188 27.704 30 19.516 30H12.39C4.2 30 .675 24.189 2.289 18.388l1.344-4.825c1.073-3.85 4.459-6.5 9.224-6.5");
}

.aw-js1viw {
  stop-color: var(--svg-color--9ec44e, #9EC44E);
  stop-opacity: 0;
}

.b3i3jcd0y {
  fill: var(--svg-color--aec64b, #AEC64B);
  d: path("m17.18 4.287l-3.323 2.98h4.157V4.66a.5.5 0 0 0-.834-.372");
}

.cx4wtzbcy {
  stop-color: var(--svg-color--c7ec76, #C7EC76);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dhc15-kyi {
  fill: var(--svg-color--583674, #583674);
  d: path("m20.946 13.276l-1.119 1.354a.3.3 0 0 0 .231.491h2.786a.3.3 0 0 0 .23-.492l-1.128-1.355a.65.65 0 0 0-1 .002");
}

.erwk3vbee {
  stop-color: var(--svg-color--3b1652, #3B1652);
}

.fnqjygtsy {
  stop-color: var(--svg-color--ed3724, #ED3724);
}

.ft5dv1b6b {
  fill: none;
}

.ggi4hnyeq {
  stop-color: var(--svg-color--9ec44e, #9EC44E);
}

.hes3ez37z {
  stop-color: var(--svg-color--ffa182, #FFA182);
}

.iv40aibfj {
  stop-color: var(--svg-color--ff7b3e, #FF7B3E);
}

.kf4926hvk {
  stop-color: var(--svg-color--cd7769, #CD7769);
}

.kf4qj6bfi {
  d: path("m20.946 13.276l-1.119 1.354a.3.3 0 0 0 .231.491h2.786a.3.3 0 0 0 .23-.492l-1.128-1.355a.65.65 0 0 0-1 .002");
}

.kj0fl6pwj {
  fill: var(--svg-color--ff9470, #FF9470);
  d: path("M4.92 13.385c1.06-3.18 2.714-3.763 3.293-3.98l-4.378 14.69c-.904-1.267-.82-3.377-.723-3.98c.24-1.158.94-4.125 1.809-6.73");
}

.kvqnmlbyr {
  stop-color: var(--svg-color--6f5384, #6F5384);
}

.l5g19r_dy {
  stop-color: var(--svg-color--coral, coral);
}

.l66bqnbww {
  stop-color: var(--svg-color--c7ec76, #C7EC76);
}

.mupc-2vci {
  stop-color: var(--svg-color--e89b88, #E89B88);
}

.myl_0gbqy {
  d: path("m17.18 4.287l-3.323 2.98h4.157V4.66a.5.5 0 0 0-.834-.372");
}

.nv7l02rai {
  stop-color: var(--svg-color--coral, coral);
  stop-opacity: 0;
}

.ohp1fvxsw {
  stop-color: var(--svg-color--501e76, #501E76);
}

.oysb_w93s {
  d: path("M26.556 13.681c-.352-1.329-1.089-2.4-1.645-3.026c-.275-.31-.68-.454-1.096-.454c-.964 0-1.745.782-1.745 1.745v9.557a1 1 0 0 0 1 1h4.33a.998.998 0 0 0 .974-1.223c-.565-2.446-1.427-6.127-1.818-7.599");
}

.qi8hcibrf {
  stop-color: var(--svg-color--6f5384, #6F5384);
  stop-opacity: 0;
}

.qx_v0mhrw {
  stop-color: var(--svg-color--e89b88, #E89B88);
  stop-opacity: 0;
}

.sa_23dr3t {
  stop-color: var(--svg-color--ffab81, #FFAB81);
  stop-opacity: 0;
}

.snke8hbii {
  stop-color: var(--svg-color--462162, #462162);
}

.tsy_1np-n {
  stop-color: var(--svg-color--c4e973, #C4E973);
}

.u9jzbkbyo {
  stop-color: var(--svg-color--cd7769, #CD7769);
  stop-opacity: 0;
}

.v52okgxcd {
  stop-color: var(--svg-color--3b1652, #3B1652);
  stop-opacity: 0;
}

.vflrmjbae {
  stop-color: var(--svg-color--ffa182, #FFA182);
  stop-opacity: 0;
}

.vlrgmpc_h {
  stop-color: var(--svg-color--501e76, #501E76);
  stop-opacity: 0;
}

.zf92i_-sd {
  stop-color: var(--svg-color--f6586d, #F6586D);
}

.zjhfjrbwr {
  stop-color: var(--svg-color--694582, #694582);
}

.zr1hl7bvh {
  d: path("M9.93 13.276L8.81 14.63a.3.3 0 0 0 .232.491h2.785a.3.3 0 0 0 .23-.492l-1.127-1.355a.65.65 0 0 0-1.001.002");
}

</style>
