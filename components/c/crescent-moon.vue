<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ictnqrd)"><path fill="url(#izFXBUb)" class="hlawox35s"/><path fill="url(#igRJrNc)" class="hlawox35s"/><path fill="url(#ivNKt3b)" class="hlawox35s"/></g><path fill="url(#i1Hy4wc)" class="hlawox35s"/><g filter="url(#i27eOod)"><path stroke="url(#i6DQUze)" class="f_cc8vb0f"/></g><g filter="url(#ig2oX5c)"><path fill="url(#iQEHmmd)" class="mf3rojb6a"/></g><g filter="url(#idZvoJd)"><path stroke="url(#ijQihRc)" class="og-2bobhw"/></g><g filter="url(#ieNP9Vd)"><path fill="url(#iEbxmYc)" class="s1sdrtb1c"/></g><g filter="url(#i4uNyyb)"><path stroke="url(#ipMUcxa)" class="ti4ytebbs"/></g><g filter="url(#iAbQcBb)"><path fill="url(#iagTMOe)" class="h54d16dmt"/></g><g filter="url(#ihd7Zfq)"><path stroke="url(#iEzdN7G)" class="jpzbc5bbi"/></g><g filter="url(#iDepxDb)"><path fill="url(#iiCZI7U)" class="s55d2exsm"/></g><defs><filter id="ictnqrd" width="26.87" height="25.658" x="3.538" y="4.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.372549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14563"/></filter><filter id="i27eOod" width="4.04" height="4.04" x="11.46" y="23.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14563" stdDeviation=".15"/></filter><filter id="ig2oX5c" width="3.69" height="3.79" x="11.659" y="23.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.462745 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14563"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.839216 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14563" result="effect2_innerShadow_18_14563"/></filter><filter id="idZvoJd" width="3.74" height="3.74" x="24.53" y="10.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14563" stdDeviation=".1"/></filter><filter id="ieNP9Vd" width="3.69" height="3.69" x="24.579" y="10.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.552941 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14563"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.921569 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14563" result="effect2_innerShadow_18_14563"/></filter><filter id="i4uNyyb" width="2.58" height="2.58" x="25.61" y="16.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14563" stdDeviation=".1"/></filter><filter id="iAbQcBb" width="2.33" height="2.33" x="25.759" y="16.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.552941 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14563"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.921569 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14563" result="effect2_innerShadow_18_14563"/></filter><filter id="ihd7Zfq" width="6.9" height="6.9" x="18.45" y="18.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14563" stdDeviation=".15"/></filter><filter id="iDepxDb" width="6.55" height="6.65" x="18.649" y="18.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.537255 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14563"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.882353 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14563" result="effect2_innerShadow_18_14563"/></filter><radialGradient id="igRJrNc" cx="0" cy="0" r="1" gradientTransform="rotate(-23.408 47.47 -27.137)scale(15.7323 16.4902)" gradientUnits="userSpaceOnUse"><stop offset=".769" class="lwp46fz1n"/><stop offset=".984" class="hdlafp84a"/></radialGradient><radialGradient id="ivNKt3b" cx="0" cy="0" r="1" gradientTransform="matrix(10.75852 -8.9783 9.41086 11.27684 8.705 31.214)" gradientUnits="userSpaceOnUse"><stop class="zjx3mee6y"/><stop offset="1" class="p_sxsbcam"/></radialGradient><radialGradient id="i1Hy4wc" cx="0" cy="0" r="1" gradientTransform="rotate(13.627 -37.103 98.544)scale(2.62816 6.65588)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="k8wmdubpd"/><stop offset=".979" class="dd7y-mbvz"/></radialGradient><radialGradient id="iQEHmmd" cx="0" cy="0" r="1" gradientTransform="rotate(-22.978 69.701 -18.654)scale(2.4298)" gradientUnits="userSpaceOnUse"><stop class="y5net8bru"/><stop offset="1" class="ajc05dbrm"/></radialGradient><radialGradient id="iEbxmYc" cx="0" cy="0" r="1" gradientTransform="rotate(-15.521 60.009 -87.983)scale(2.32168)" gradientUnits="userSpaceOnUse"><stop class="c_wkqn0bf"/><stop offset="1" class="g75he_nwl"/></radialGradient><radialGradient id="iagTMOe" cx="0" cy="0" r="1" gradientTransform="rotate(-15.521 79.877 -88.064)scale(1.46399)" gradientUnits="userSpaceOnUse"><stop class="eh8fib09n"/><stop offset="1" class="ridk5vs2w"/></radialGradient><radialGradient id="iiCZI7U" cx="0" cy="0" r="1" gradientTransform="rotate(-22.978 65.74 -39.472)scale(4.64293)" gradientUnits="userSpaceOnUse"><stop class="ovf37fyfk"/><stop offset="1" class="y71wzl23i"/></radialGradient><linearGradient id="izFXBUb" x1="28.688" x2="10.75" y1="11.188" y2="29.313" gradientUnits="userSpaceOnUse"><stop class="izutjjo9i"/><stop offset="1" class="hxogylb2z"/></linearGradient><linearGradient id="i6DQUze" x1="14.857" x2="13.074" y1="24.65" y2="25.582" gradientUnits="userSpaceOnUse"><stop class="ubjpj7eor"/><stop offset="1" class="i-70k_04h"/></linearGradient><linearGradient id="ijQihRc" x1="27.748" x2="25.295" y1="11.227" y2="13.854" gradientUnits="userSpaceOnUse"><stop class="sezsm5bpw"/><stop offset="1" class="ruojivbbh"/></linearGradient><linearGradient id="ipMUcxa" x1="27.75" x2="26.203" y1="17.141" y2="18.797" gradientUnits="userSpaceOnUse"><stop class="sezsm5bpw"/><stop offset="1" class="ruojivbbh"/></linearGradient><linearGradient id="iEzdN7G" x1="24.531" x2="21.125" y1="20.469" y2="22.25" gradientUnits="userSpaceOnUse"><stop class="qobq3e2gp"/><stop offset="1" class="c_wkqn0bf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crescent-moon" /></template>
<style>
.ajc05dbrm {
  stop-color: var(--svg-color--eb9e58, #EB9E58);
}

.c_wkqn0bf {
  stop-color: var(--svg-color--ffd778, #FFD778);
}

.dd7y-mbvz {
  stop-color: var(--svg-color--ba935b, #BA935B);
  stop-opacity: 0;
}

.eh8fib09n {
  stop-color: var(--svg-color--ffde8f, #FFDE8F);
}

.f_cc8vb0f {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.48 27.012a1.57 1.57 0 1 0 0-3.14a1.57 1.57 0 0 0 0 3.14Z");
}

.ft5dv1b6b {
  fill: none;
}

.g75he_nwl {
  stop-color: var(--svg-color--ffc767, #FFC767);
}

.h54d16dmt {
  d: path("M26.9 18.972a.99.99 0 1 0 0-1.98a.99.99 0 0 0 0 1.98");
}

.hdlafp84a {
  stop-color: var(--svg-color--ffecae, #FFECAE);
}

.hlawox35s {
  d: path("M23.51 5.632c.5 2.04.56 4.26.02 6.56c-1.26 5.33-5.64 9.51-11.02 10.48c-2.91.53-5.68.13-8.09-.92c-.56-.25-1.09.39-.8.93c2.65 4.88 8.11 8 14.22 7.19c6.23-.83 11.22-5.91 11.97-12.15c.6-5.18-1.6-9.86-5.28-12.75c-.47-.36-1.16.08-1.02.66");
}

.hxogylb2z {
  stop-color: var(--svg-color--ffbc4c, #FFBC4C);
}

.i-70k_04h {
  stop-color: var(--svg-color--ffca6d, #FFCA6D);
}

.izutjjo9i {
  stop-color: var(--svg-color--ffd874, #FFD874);
}

.jpzbc5bbi {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.9 24.982a3 3 0 1 0 0-6a3 3 0 0 0 0 6Z");
}

.k8wmdubpd {
  stop-color: var(--svg-color--ba935b, #BA935B);
}

.lwp46fz1n {
  stop-color: var(--svg-color--ffecae, #FFECAE);
  stop-opacity: 0;
}

.mf3rojb6a {
  d: path("M13.48 27.012a1.57 1.57 0 1 0 0-3.14a1.57 1.57 0 0 0 0 3.14");
}

.og-2bobhw {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.4 14.132a1.57 1.57 0 1 0 0-3.14a1.57 1.57 0 0 0 0 3.14Z");
}

.ovf37fyfk {
  stop-color: var(--svg-color--ffc75f, #FFC75F);
}

.p_sxsbcam {
  stop-color: var(--svg-color--ff984f, #FF984F);
  stop-opacity: 0;
}

.qobq3e2gp {
  stop-color: var(--svg-color--e2a842, #E2A842);
}

.ridk5vs2w {
  stop-color: var(--svg-color--ffc25b, #FFC25B);
}

.ruojivbbh {
  stop-color: var(--svg-color--ffe9a7, #FFE9A7);
}

.s1sdrtb1c {
  d: path("M26.4 14.132a1.57 1.57 0 1 0 0-3.14a1.57 1.57 0 0 0 0 3.14");
}

.s55d2exsm {
  d: path("M21.9 24.982a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.sezsm5bpw {
  stop-color: var(--svg-color--e7ac47, #E7AC47);
}

.ti4ytebbs {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M26.9 18.972a.99.99 0 1 0 0-1.98a.99.99 0 0 0 0 1.98Z");
}

.ubjpj7eor {
  stop-color: var(--svg-color--d0883b, #D0883B);
}

.y5net8bru {
  stop-color: var(--svg-color--ffba6a, #FFBA6A);
}

.y71wzl23i {
  stop-color: var(--svg-color--fabc5a, #FABC5A);
}

.zjx3mee6y {
  stop-color: var(--svg-color--ff984f, #FF984F);
}

</style>
