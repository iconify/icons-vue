<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#ifFWMwe)" class="d2kvgvbvc"><path fill="url(#itMAy4C)" class="a-qehubga"/><path fill="url(#i2djICc)" class="a-qehubga"/></g><g filter="url(#iycfDhe)"><path class="hicxv-mpr"/><path fill="url(#iYjPb8c)" class="q0o7nub1u"/><path fill="url(#iJeY9gR)" class="q0o7nub1u"/><path fill="url(#ihMZaJc)" class="q0o7nub1u"/></g><path clip-rule="evenodd" class="xtqi5ub2b"/><path fill="url(#iamniRT)" clip-rule="evenodd" class="otubgmbbe"/><path fill="url(#iMAoXSb)" clip-rule="evenodd" class="otubgmbbe"/><g filter="url(#i2J3Qhe)"><path class="as444yvvv"/></g><g filter="url(#iCgxl9b)"><path stroke="url(#iKlVwpe)" class="oil451bbc"/></g><g filter="url(#ihTmaMb)"><path stroke="url(#ily4Htk)" class="hverv0njz"/></g><g filter="url(#idhMCQb)"><path stroke="url(#ilSqb1s)" class="u6wmgh48o"/></g><g filter="url(#iQ3i6lb)"><path stroke="url(#iyILuub)" class="ohj_rvb7x"/></g><defs><radialGradient id="itMAy4C" cx="0" cy="0" r="1" gradientTransform="matrix(-8.34381 6.31243 -6.97483 -9.21937 14.969 11.466)" gradientUnits="userSpaceOnUse"><stop class="fft6y9elh"/><stop offset="1" class="eb6bfzbys"/></radialGradient><radialGradient id="i2djICc" cx="0" cy="0" r="1" gradientTransform="rotate(123.476 .7 10.163)scale(4.64565 3.41798)" gradientUnits="userSpaceOnUse"><stop offset=".497" class="n89a9egqe"/><stop offset="1" class="ft5pgnkzc"/></radialGradient><radialGradient id="iYjPb8c" cx="0" cy="0" r="1" gradientTransform="matrix(-7.375 -2.42806 1.75385 -5.32716 14.75 29.863)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="w9ewt285a"/><stop offset="1" class="gll5--6mp"/></radialGradient><radialGradient id="iJeY9gR" cx="0" cy="0" r="1" gradientTransform="rotate(-128.919 14.305 8.69)scale(6.46664 2.55443)" gradientUnits="userSpaceOnUse"><stop class="ku7euibtv"/><stop offset="1" class="y73jcgbxe"/></radialGradient><radialGradient id="ihMZaJc" cx="0" cy="0" r="1" gradientTransform="rotate(132.013 3.78 11.19)scale(5.08924 3.88381)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="banwryaas"/><stop offset="1" class="ykv83hk3g"/></radialGradient><radialGradient id="iamniRT" cx="0" cy="0" r="1" gradientTransform="matrix(-10.37497 -9.90623 3.07089 -3.2162 26.938 16.716)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="khy8pi8et"/><stop offset="1" class="zr5cz1b9r"/></radialGradient><radialGradient id="iMAoXSb" cx="0" cy="0" r="1" gradientTransform="matrix(3.39062 3.125 -1.83606 1.99212 22.39 14.703)" gradientUnits="userSpaceOnUse"><stop offset=".44" class="uf135_blg"/><stop offset="1" class="bf54num2n"/></radialGradient><radialGradient id="ily4Htk" cx="0" cy="0" r="1" gradientTransform="matrix(-6.37496 4.62505 -3.3986 -4.68448 30.844 19.497)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="rklgsjb8r"/><stop offset="1" class="jzve0dbbs"/></radialGradient><filter id="ifFWMwe" width="11.192" height="9.903" x="4.983" y="10.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.258824 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7183"/></filter><filter id="iycfDhe" width="16.457" height="19.582" x="1.897" y="10.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7183"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.176471 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7183" result="effect2_innerShadow_20020_7183"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.235294 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_7183" result="effect3_innerShadow_20020_7183"/></filter><filter id="i2J3Qhe" width="16.457" height="19.582" x="13.825" y="10.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.121569 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7183"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.109804 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7183" result="effect2_innerShadow_20020_7183"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.258824 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_7183" result="effect3_innerShadow_20020_7183"/></filter><filter id="iCgxl9b" width="9.25" height="8.72" x="17.031" y="10.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7183" stdDeviation=".5"/></filter><filter id="ihTmaMb" width="6.406" height="11.906" x="23.781" y="16.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7183" stdDeviation=".5"/></filter><filter id="idhMCQb" width="8.094" height="7.844" x="13.469" y="21.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7183" stdDeviation=".5"/></filter><filter id="iQ3i6lb" width="9.398" height="10.094" x="6.427" y="17.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7183" stdDeviation=".5"/></filter><linearGradient id="iKlVwpe" x1="24.281" x2="15.375" y1="17.216" y2="11.278" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></linearGradient><linearGradient id="ilSqb1s" x1="15.906" x2="19.499" y1="28.154" y2="23.04" gradientUnits="userSpaceOnUse"><stop class="jf0h6sbmn"/><stop offset="1" class="mtz69zbdz"/></linearGradient><linearGradient id="iyILuub" x1="11.813" x2="9.606" y1="20.813" y2="24.559" gradientUnits="userSpaceOnUse"><stop class="hup7tubus"/><stop offset="1" class="opjyatrah"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:heart-hands-dark" /></template>
<style>
.a-qehubga {
  d: path("M10.537 14.579c.749-.46 1.716-.382 2.348-.066a2.1 2.1 0 1 0 1.879-3.756c-1.62-.81-4.17-1.142-6.424.242c-3.087 1.894-3.357 4.894-3.357 6.859a2.1 2.1 0 1 0 4.2 0c0-1.637.24-2.596 1.354-3.28");
}

.as444yvvv {
  fill: var(--svg-color--4a3134, #4A3134);
  d: path("m17.527 16.058l.014-.016l.045-.042q.058-.052.157-.123c.134-.093.3-.186.49-.258a1.9 1.9 0 0 1 1.249-.052c.975.295 1.535 1.073 1.895 2.208c.16.896.145 2.622-.676 3.433c-.24.269-.765.61-1.436 1.046c-1.41.918-3.475 2.26-4.935 4.251c-1.044 1.331-.095 2.74.423 3.024c.719.392 1.528.54 2.366-.125c.84-.666 2.182-1.624 3.637-1.368s2.03.352 2.88.352h4.345a1.8 1.8 0 0 0 1.8-1.8v-4.513c0-1.957-1.23-4.44-3.197-5.122c-.637-.221-1.242-.634-1.5-1.258c-.681-1.649-1.942-3.41-4.388-4.149c-2.983-.9-5.437.692-6.373 1.797a2.1 2.1 0 1 0 3.204 2.715");
}

.banwryaas {
  stop-color: var(--svg-color--2f1722, #2F1722);
}

.bf54num2n {
  stop-color: var(--svg-color--422c29, #422C29);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.eb6bfzbys {
  stop-color: var(--svg-color--453230, #453230);
}

.fft6y9elh {
  stop-color: var(--svg-color--553d39, #553D39);
}

.ft5dv1b6b {
  fill: none;
}

.ft5pgnkzc {
  stop-color: var(--svg-color--2e1d1d, #2E1D1D);
  stop-opacity: 0;
}

.gll5--6mp {
  stop-color: var(--svg-color--432833, #432833);
  stop-opacity: 0;
}

.hicxv-mpr {
  fill: var(--svg-color--4d3437, #4D3437);
  d: path("m14.151 16.058l-.014-.016l-.045-.042a2 2 0 0 0-.158-.123a2.3 2.3 0 0 0-.49-.258a1.9 1.9 0 0 0-1.248-.052c-.975.295-1.535 1.073-1.895 2.208c-.16.896-.145 2.622.676 3.433c.24.269.764.61 1.435 1.046c1.412.918 3.475 2.26 4.936 4.251c1.044 1.331.095 2.74-.423 3.024c-.72.392-1.528.54-2.367-.125c-.838-.666-2.18-1.624-3.636-1.368s-2.03.352-2.88.352H3.697a1.8 1.8 0 0 1-1.8-1.8v-4.513c0-1.957 1.231-4.44 3.197-5.122c.638-.221 1.243-.634 1.5-1.258c.682-1.649 1.943-3.41 4.389-4.149c2.983-.9 5.437.692 6.373 1.797a2.1 2.1 0 0 1-3.204 2.715");
}

.hup7tubus {
  stop-color: var(--svg-color--5d4a48, #5D4A48);
}

.hverv0njz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M25.781 18.185c.802.375 2.407 1.637 2.407 3.687v4.22");
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.jf0h6sbmn {
  stop-color: var(--svg-color--55343b, #55343B);
}

.jzve0dbbs {
  stop-color: var(--svg-color--65504f, #65504F);
  stop-opacity: 0;
}

.khy8pi8et {
  stop-color: var(--svg-color--5c4745, #5C4745);
}

.ku7euibtv {
  stop-color: var(--svg-color--32221f, #32221F);
}

.mtz69zbdz {
  stop-color: var(--svg-color--55343b, #55343B);
  stop-opacity: 0;
}

.n89a9egqe {
  stop-color: var(--svg-color--2e1d1d, #2E1D1D);
}

.ohj_rvb7x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.45 19.091c-.105.802.093 2.606 1.718 3.406c1.676 1.063 3.115 2.125 3.657 2.688");
}

.oil451bbc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.031 12.497c1.375-.041 4.275.844 5.25 4.719");
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.opjyatrah {
  stop-color: var(--svg-color--5d4a48, #5D4A48);
  stop-opacity: 0;
}

.otubgmbbe {
  fill-rule: evenodd;
  d: path("M21.141 14.579c-.749-.46-1.716-.382-2.349-.066a2.1 2.1 0 1 1-1.878-3.756c1.62-.81 4.17-1.142 6.424.242c3.087 1.894 3.357 4.894 3.357 6.859a2.1 2.1 0 1 1-4.2 0c0-1.637-.24-2.596-1.354-3.28");
}

.q0o7nub1u {
  d: path("m14.151 16.058l-.014-.016l-.045-.042a2 2 0 0 0-.158-.123a2.3 2.3 0 0 0-.49-.258a1.9 1.9 0 0 0-1.248-.052c-.975.295-1.535 1.073-1.895 2.208c-.16.896-.145 2.622.676 3.433c.24.269.764.61 1.435 1.046c1.412.918 3.475 2.26 4.936 4.251c1.044 1.331.095 2.74-.423 3.024c-.72.392-1.528.54-2.367-.125c-.838-.666-2.18-1.624-3.636-1.368s-2.03.352-2.88.352H3.697a1.8 1.8 0 0 1-1.8-1.8v-4.513c0-1.957 1.231-4.44 3.197-5.122c.638-.221 1.243-.634 1.5-1.258c.682-1.649 1.943-3.41 4.389-4.149c2.983-.9 5.437.692 6.373 1.797a2.1 2.1 0 0 1-3.204 2.715");
}

.rklgsjb8r {
  stop-color: var(--svg-color--65504f, #65504F);
}

.u6wmgh48o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.469 27.841c.52-.854 2.493-2.669 4.094-3.844");
}

.uf135_blg {
  stop-color: var(--svg-color--422c29, #422C29);
}

.w9ewt285a {
  stop-color: var(--svg-color--341b29, #341B29);
}

.xtqi5ub2b {
  fill: var(--svg-color--47312d, #47312D);
  fill-rule: evenodd;
  d: path("M21.141 14.579c-.749-.46-1.716-.382-2.349-.066a2.1 2.1 0 1 1-1.878-3.756c1.62-.81 4.17-1.142 6.424.242c3.087 1.894 3.357 4.894 3.357 6.859a2.1 2.1 0 1 1-4.2 0c0-1.637-.24-2.596-1.354-3.28");
}

.y73jcgbxe {
  stop-color: var(--svg-color--32221f, #32221F);
  stop-opacity: 0;
}

.ykv83hk3g {
  stop-color: var(--svg-color--2f1722, #2F1722);
  stop-opacity: 0;
}

.zr5cz1b9r {
  stop-color: var(--svg-color--5c4745, #5C4745);
  stop-opacity: 0;
}

</style>
