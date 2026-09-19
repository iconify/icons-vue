<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iISHvHb)"><path fill="url(#iVJsfhe)" class="w0njd_brp"/><path fill="url(#iJeoW1P)" class="w0njd_brp"/></g><g filter="url(#ioMtOgc)"><path class="jj1cjsmik"/></g><g filter="url(#ihb7wnb)"><path class="amrh-ccud"/></g><g filter="url(#iLHaV0s)"><path stroke="url(#iZtw73n)" class="po-acwbuf"/></g><g filter="url(#ieaW1BX)"><path stroke="url(#iVwPC2c)" class="vw6zqccnh"/></g><g filter="url(#iadOHsc)"><path stroke="url(#iKoeY8d)" class="yh68q-yaz"/></g><g filter="url(#i1RLCED)"><path stroke="url(#ii1ps5j)" class="re2w64bgv"/></g><g filter="url(#icMA5mj)"><path stroke="url(#i7ZmuPb)" class="rxgeqgbmf"/></g><g filter="url(#iq6bQyc)"><path stroke="url(#iw9NEYe)" class="hi19c8b_d"/></g><g filter="url(#iWEvbme)"><path stroke="url(#iSGTVAe)" class="uu5ziccwi"/></g><g filter="url(#i7J8bIb)"><path stroke="url(#iHJp9KX)" class="xtgublwvl"/></g><g filter="url(#iQ0cG8b)"><path stroke="url(#i6Y88se)" class="a0d5z1-dt"/></g><g filter="url(#iuTR0kA)"><ellipse fill="url(#iFbFQIL)" transform="rotate(45.133 18.817 12.49)" class="jrguqyb5o"/></g><defs><filter id="iISHvHb" width="26.831" height="28.072" x="2.725" y="1.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.770833 0 0 0 0 0.102778 0 0 0 0 0.344827 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_7139_6201"/></filter><filter id="ioMtOgc" width="18.008" height="17.79" x="6.564" y="6.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation="1"/></filter><filter id="ihb7wnb" width="12.789" height="12.665" x="10.564" y="8.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.966667 0 0 0 0 0.507026 0 0 0 0 0 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_7139_6201"/></filter><filter id="iLHaV0s" width="6.094" height="5.172" x="7.625" y="3.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="ieaW1BX" width="1.948" height="4.612" x="17.136" y="5.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="iadOHsc" width="1.031" height="4.031" x="16.336" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="i1RLCED" width="4.063" height="3.875" x="17.812" y="12.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="icMA5mj" width="2.203" height="4.594" x="19.686" y="19.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="iq6bQyc" width="7.812" height="5.35" x="20.704" y="12.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="iWEvbme" width="2.656" height="2.297" x="12.625" y="10.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="i7J8bIb" width="2.063" height="4.313" x="14.625" y="16.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="iQ0cG8b" width="1.297" height="2.719" x="17.125" y="15.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".125"/></filter><filter id="iuTR0kA" width=".941" height=".939" x="18.347" y="12.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6201" stdDeviation=".05"/></filter><linearGradient id="iVJsfhe" x1="18.953" x2="16.008" y1="28.859" y2="-1.891" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset=".372" class="emo973b4a"/><stop offset=".807" class="uojyabbji"/></linearGradient><linearGradient id="iJeoW1P" x1="18.985" x2="19.75" y1="12.381" y2="-8.838" gradientUnits="userSpaceOnUse"><stop offset=".297" class="msakmjbbj"/><stop offset=".774" class="oyfwheb3w"/><stop offset=".818" class="oyfwheb3w"/></linearGradient><linearGradient id="iZtw73n" x1="13.625" x2="9.363" y1="8.266" y2="6.128" gradientUnits="userSpaceOnUse"><stop class="po0p75bsb"/><stop offset="1" class="evjfggbts"/></linearGradient><linearGradient id="iVwPC2c" x1="16.886" x2="14.228" y1="9.313" y2="5.283" gradientUnits="userSpaceOnUse"><stop class="po0p75bsb"/><stop offset="1" class="evjfggbts"/></linearGradient><linearGradient id="iKoeY8d" x1="16.836" x2="16.915" y1="10.578" y2="8.438" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></linearGradient><linearGradient id="ii1ps5j" x1="21.859" x2="16.172" y1="15.328" y2="11.672" gradientUnits="userSpaceOnUse"><stop class="fej9_egjo"/><stop offset=".412" class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></linearGradient><linearGradient id="i7ZmuPb" x1="20.061" x2="25.393" y1="19.609" y2="26.022" gradientUnits="userSpaceOnUse"><stop offset=".167" class="mw03nqbmr"/><stop offset=".75" class="xqxzn0btc"/></linearGradient><linearGradient id="iw9NEYe" x1="21.797" x2="29.718" y1="14.086" y2="15.317" gradientUnits="userSpaceOnUse"><stop class="w-wecnm0f"/><stop offset="1" class="bsgri27km"/></linearGradient><linearGradient id="iSGTVAe" x1="14.875" x2="13.109" y1="12.594" y2="10.844" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></linearGradient><linearGradient id="iHJp9KX" x1="15.906" x2="17.172" y1="19.859" y2="16.703" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></linearGradient><linearGradient id="i6Y88se" x1="18.547" x2="17.68" y1="17.609" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></linearGradient><linearGradient id="iFbFQIL" x1="18.817" x2="18.689" y1="12.015" y2="12.878" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:collision" /></template>
<style>
.a0d5z1-dt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m17.5 15.75l.547 1.969");
}

.amrh-ccud {
  fill: var(--svg-color--ffb628, #FFB628);
  d: path("M12.539 15.318L11.11 16.65c-.182.17-.03.474.216.428l2.694-.497a.25.25 0 0 1 .295.23l.266 4.209c.017.279.403.337.502.076l1.385-3.642a.25.25 0 0 1 .395-.101l1.195 1.011a.25.25 0 0 0 .404-.249l-.398-1.66a.25.25 0 0 1 .26-.309l4.666.308c.224.014.298-.295.091-.384l-4.435-1.9a.25.25 0 0 1-.12-.35l.77-1.385a.25.25 0 0 0-.296-.359l-1.697.562a.25.25 0 0 1-.329-.241l.055-3.294c.004-.267-.355-.354-.474-.116l-1.155 2.32a.25.25 0 0 1-.375.088l-2.155-1.63a.25.25 0 0 0-.391.27l.82 2.826a.25.25 0 0 1-.193.315l-2.34.455a.25.25 0 0 0-.055.473l1.761.802a.25.25 0 0 1 .067.41");
}

.bsgri27km {
  stop-color: var(--svg-color--ff3e87, #FF3E87);
  stop-opacity: 0;
}

.emo973b4a {
  stop-color: var(--svg-color--ea0a4f, #EA0A4F);
}

.evjfggbts {
  stop-color: var(--svg-color--ff5696, #FF5696);
  stop-opacity: 0;
}

.fej9_egjo {
  stop-color: var(--svg-color--ffd530, #FFD530);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hi19c8b_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m28.14 17.21l-6.459-3.56a1.165 1.165 0 0 1-.595-1.15v0");
}

.jj1cjsmik {
  fill: var(--svg-color--a2131b, #A2131B);
  d: path("m10.81 15.5l-1.653 1.544c-.183.17-.03.473.216.428l3.062-.565a.25.25 0 0 1 .295.23l.3 4.759c.019.279.404.337.503.076l1.573-4.134a.25.25 0 0 1 .395-.102l1.392 1.18a.25.25 0 0 0 .405-.25l-.462-1.925a.25.25 0 0 1 .26-.308l5.262.346c.225.015.3-.294.092-.383l-4.993-2.138a.25.25 0 0 1-.12-.351l.89-1.596a.25.25 0 0 0-.298-.36l-1.952.647a.25.25 0 0 1-.329-.24l.062-3.754c.005-.267-.355-.354-.474-.116l-1.327 2.667a.25.25 0 0 1-.375.088l-2.445-1.85a.25.25 0 0 0-.391.27l.927 3.195a.25.25 0 0 1-.192.315l-2.666.518a.25.25 0 0 0-.056.473l2.033.926a.25.25 0 0 1 .067.41");
}

.jrguqyb5o {
  cx: 18.817px;
  cy: 12.49px;
  rx: 0.218px;
  ry: 0.475px;
}

.msakmjbbj {
  stop-color: var(--svg-color--a11749, #A11749);
  stop-opacity: 0;
}

.mw03nqbmr {
  stop-color: var(--svg-color--ff5c7a, #FF5C7A);
}

.oyfwheb3w {
  stop-color: var(--svg-color--a21749, #A21749);
}

.p8j84vbpc {
  stop-color: var(--svg-color--ffd530, #FFD530);
}

.po-acwbuf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m8 3.5l5.344 4.422");
}

.po0p75bsb {
  stop-color: var(--svg-color--ff5696, #FF5696);
}

.re2w64bgv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.781 12.75l-.535 1.006a.5.5 0 0 0 .228.687l3.026 1.432");
}

.rxgeqgbmf {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.515 23.344L20.06 19.5");
}

.uojyabbji {
  stop-color: var(--svg-color--ec008c, #EC008C);
}

.uu5ziccwi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13 10.5l1.906 1.547");
}

.vw6zqccnh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m17.511 5.5l.444 3.282a.67.67 0 0 0 .846.554v0");
}

.w-wecnm0f {
  stop-color: var(--svg-color--ff3e87, #FF3E87);
}

.w0njd_brp {
  d: path("M9.453 11.18L6.526 2.291a.25.25 0 0 1 .393-.275l7.143 5.657a.5.5 0 0 0 .702-.081l2.618-3.301a.25.25 0 0 1 .444.123l.551 4.264a.5.5 0 0 0 .642.414l7.212-2.203c.238-.073.425.21.263.401l-4.63 5.448a.5.5 0 0 0 .137.76l7.277 4.059c.218.12.144.45-.105.467l-8.258.555a.5.5 0 0 0-.436.671l1.563 4.265a.25.25 0 0 1-.383.288l-3.697-2.725a.5.5 0 0 0-.756.206l-3.592 8.447c-.097.23-.434.19-.476-.056l-1.689-9.885a.5.5 0 0 0-.608-.402l-7.807 1.85c-.257.061-.42-.266-.217-.435l5.538-4.615a.5.5 0 0 0-.094-.83l-3.954-2.013a.25.25 0 0 1 .058-.466l4.722-1.057a.5.5 0 0 0 .366-.644");
}

.xqxzn0btc {
  stop-color: var(--svg-color--ff5c7a, #FF5C7A);
  stop-opacity: 0;
}

.xtgublwvl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.313 17L15 20.563");
}

.yh68q-yaz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.711 9.5v2.875c0 .224.182.406.407.406v0");
}

.yiq__d07e {
  stop-color: var(--svg-color--e81123, #E81123);
}

</style>
