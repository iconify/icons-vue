<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDo6xGc)" class="xtozo0bap"/><path fill="url(#iwVm2bb)" class="xtozo0bap"/><path fill="url(#iBvqNuH)" class="xtozo0bap"/><path fill="url(#izEDuZc)" class="xtozo0bap"/><path fill="url(#iM571ub)" class="xtozo0bap"/><path fill="url(#i48jqyd)" class="xtozo0bap"/><path fill="url(#i7t21Ob)" class="xtozo0bap"/><path fill="url(#iSV6MFd)" class="xtozo0bap"/><g filter="url(#iWEb5vc)"><path fill="url(#iRgmU9b)" class="wsqxe4bzi"/><path fill="url(#ijwccxe)" class="wsqxe4bzi"/><path fill="url(#i9gIFme)" class="wsqxe4bzi"/></g><path fill="url(#iUO1tOe)" class="wsqxe4bzi"/><path fill="url(#iJjMSzb)" class="wsqxe4bzi"/><g filter="url(#ie5hqLp)"><path fill="url(#iBYCx4b)" class="g0fzgbpcw"/></g><g filter="url(#iyoLWwe)"><path fill="url(#i0Ga4ge)" class="hxi7600ju"/></g><defs><radialGradient id="iDo6xGc" cx="0" cy="0" r="1" gradientTransform="rotate(-179.474 12.046 9.805)scale(17.0988 25.7861)" gradientUnits="userSpaceOnUse"><stop class="ukp9kl79f"/><stop offset="1" class="go0shebij"/></radialGradient><radialGradient id="iwVm2bb" cx="0" cy="0" r="1" gradientTransform="rotate(-157.937 6.712 6.816)scale(10.3441 17.8495)" gradientUnits="userSpaceOnUse"><stop class="ia9qvtbmk"/><stop offset="1" class="sghrx4bwn"/></radialGradient><radialGradient id="izEDuZc" cx="0" cy="0" r="1" gradientTransform="rotate(24.015 -31.353 18.85)scale(3.10465 25.6991)" gradientUnits="userSpaceOnUse"><stop class="l9u7y-blc"/><stop offset="1" class="xytkt0b5b"/></radialGradient><radialGradient id="iM571ub" cx="0" cy="0" r="1" gradientTransform="matrix(.843 3.74668 -4.675 1.05188 9.31 6.25)" gradientUnits="userSpaceOnUse"><stop class="akr6cbckn"/><stop offset="1" class="leu95sb4v"/></radialGradient><radialGradient id="i48jqyd" cx="0" cy="0" r="1" gradientTransform="matrix(.37467 10.13047 -9.3768 .3468 16.429 1.366)" gradientUnits="userSpaceOnUse"><stop class="lb-akhwjq"/><stop offset="1" class="zfft5sbeg"/></radialGradient><radialGradient id="i7t21Ob" cx="0" cy="0" r="1" gradientTransform="matrix(2.07795 .9835 -1.9737 4.17002 13.9 4.8)" gradientUnits="userSpaceOnUse"><stop class="jwyse3b-w"/><stop offset="1" class="o63o_4u1e"/></radialGradient><radialGradient id="iSV6MFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.89842 2.09375 -.4798 -.20588 12.458 8.21)" gradientUnits="userSpaceOnUse"><stop class="aysfvkbww"/><stop offset="1" class="iabcjvb7t"/></radialGradient><radialGradient id="iRgmU9b" cx="0" cy="0" r="1" gradientTransform="rotate(-168.558 11.823 11.126)scale(10.0291 12.4891)" gradientUnits="userSpaceOnUse"><stop class="yz8i4ac9u"/><stop offset="1" class="ub1vowg6i"/></radialGradient><radialGradient id="ijwccxe" cx="0" cy="0" r="1" gradientTransform="matrix(5.05808 13.20705 -11.47512 4.39478 12.4 8.592)" gradientUnits="userSpaceOnUse"><stop class="qkczxmb_v"/><stop offset="1" class="bm8jgpp9i"/></radialGradient><radialGradient id="i9gIFme" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74917 .98358 -2.40823 -23.87023 19.239 20.629)" gradientUnits="userSpaceOnUse"><stop offset=".628" class="vyn70y7mv"/><stop offset="1" class="hyjtqxw7k"/></radialGradient><radialGradient id="iJjMSzb" cx="0" cy="0" r="1" gradientTransform="rotate(143.063 8.353 13.24)scale(16.0546 11.6174)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="k4on2779b"/><stop offset="1" class="eiuzqr_hc"/></radialGradient><linearGradient id="iBvqNuH" x1="18.336" x2="18.336" y1="29.944" y2="24.846" gradientUnits="userSpaceOnUse"><stop class="aap4e_cus"/><stop offset="1" class="zblq95blo"/></linearGradient><linearGradient id="iUO1tOe" x1="16.503" x2="16.503" y1="10.612" y2="14.259" gradientUnits="userSpaceOnUse"><stop class="t0wcfpvwl"/><stop offset="1" class="uil4heork"/></linearGradient><linearGradient id="iBYCx4b" x1="14.996" x2="7.655" y1="4.255" y2="22.732" gradientUnits="userSpaceOnUse"><stop class="jcc6c0bmc"/><stop offset="1" class="gur199tun"/></linearGradient><linearGradient id="i0Ga4ge" x1="9.541" x2="5.582" y1="8.144" y2="19.479" gradientUnits="userSpaceOnUse"><stop class="ep3g_rbti"/><stop offset="1" class="bpsvkqboj"/></linearGradient><filter id="iWEb5vc" width="14.525" height="18.91" x="9.49" y="11.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.615686 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15821"/></filter><filter id="ie5hqLp" width="11.424" height="22.115" x="5.723" y="2.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15821" stdDeviation=".625"/></filter><filter id="iyoLWwe" width="6.868" height="14.084" x="4.492" y="6.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15821" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fire" /></template>
<style>
.aap4e_cus {
  stop-color: var(--svg-color--ff7583, #FF7583);
}

.akr6cbckn {
  stop-color: var(--svg-color--ff5e47, #FF5E47);
}

.aysfvkbww {
  stop-color: var(--svg-color--ffa682, #FFA682);
}

.bm8jgpp9i {
  stop-color: var(--svg-color--fe5533, #FE5533);
  stop-opacity: 0;
}

.bpsvkqboj {
  stop-color: var(--svg-color--ff9c6d, #FF9C6D);
}

.eiuzqr_hc {
  stop-color: var(--svg-color--f18a52, #F18A52);
}

.ep3g_rbti {
  stop-color: var(--svg-color--ff815b, #FF815B);
}

.ft5dv1b6b {
  fill: none;
}

.g0fzgbpcw {
  d: path("M11.814 11.539c2.315-3.39 3.67-7.058 4.083-7.962c-.603 4.634-2.36 8.028-5.668 12.398c-2.646 3.496-3.124 6.488-3.101 7.217c-.827-5.562 1.791-7.416 4.686-11.653");
}

.go0shebij {
  stop-color: var(--svg-color--ff5141, #FF5141);
}

.gur199tun {
  stop-color: var(--svg-color--f38758, #F38758);
}

.hxi7600ju {
  d: path("M9.814 7.874c-1.3 1.614-3.884 6.09-3.82 11.084c1.28-5.122 4.275-6.736 3.82-11.084");
}

.hyjtqxw7k {
  stop-color: var(--svg-color--d7812d, #D7812D);
}

.ia9qvtbmk {
  stop-color: var(--svg-color--ce5327, #CE5327);
}

.iabcjvb7t {
  stop-color: var(--svg-color--ffa682, #FFA682);
  stop-opacity: 0;
}

.jcc6c0bmc {
  stop-color: var(--svg-color--ff7558, #FF7558);
}

.jwyse3b-w {
  stop-color: var(--svg-color--ff846c, #FF846C);
}

.k4on2779b {
  stop-color: var(--svg-color--f18a52, #F18A52);
  stop-opacity: 0;
}

.l9u7y-blc {
  stop-color: var(--svg-color--ffaa7b, #FFAA7B);
}

.lb-akhwjq {
  stop-color: var(--svg-color--ff2f3c, #FF2F3C);
}

.leu95sb4v {
  stop-color: var(--svg-color--ff5e47, #FF5E47);
  stop-opacity: 0;
}

.o63o_4u1e {
  stop-color: var(--svg-color--ff846c, #FF846C);
  stop-opacity: 0;
}

.qkczxmb_v {
  stop-color: var(--svg-color--fd5639, #FD5639);
}

.sghrx4bwn {
  stop-color: var(--svg-color--ce5327, #CE5327);
  stop-opacity: 0;
}

.t0wcfpvwl {
  stop-color: var(--svg-color--f95131, #F95131);
}

.ub1vowg6i {
  stop-color: var(--svg-color--ff8e41, #FF8E41);
}

.uil4heork {
  stop-color: var(--svg-color--f95131, #F95131);
  stop-opacity: 0;
}

.ukp9kl79f {
  stop-color: var(--svg-color--ff953d, #FF953D);
}

.vyn70y7mv {
  stop-color: var(--svg-color--d7812d, #D7812D);
  stop-opacity: 0;
}

.wsqxe4bzi {
  d: path("M10.178 19.877c1.302-3.1 3.975-6.529 5.78-8.39a1.336 1.336 0 0 1 1.872-.038c3.461 3.189 4.503 6.072 5.387 9.428c.92 3.492 0 9.118-6.921 9.118c-5.96 0-8.026-5.578-6.118-10.118");
}

.xtozo0bap {
  d: path("M12.555 8.935c1.537-2.397 2.447-4.611 2.921-6.177c.182-.6.95-.845 1.406-.415c6.873 6.481 9.12 11.43 9.567 17.148c.328 5.531-2.39 10.453-9.687 10.453c-6.85 0-11.907-4.781-11.22-12.36c.412-4.528 2.173-7.979 3.58-10.033c.438-.639 1.351-.648 1.856-.06l1.259 1.466c.087.101.246.09.318-.022");
}

.xytkt0b5b {
  stop-color: var(--svg-color--ffaa7b, #FFAA7B);
  stop-opacity: 0;
}

.yz8i4ac9u {
  stop-color: var(--svg-color--ffda2f, #FFDA2F);
}

.zblq95blo {
  stop-color: var(--svg-color--ff7583, #FF7583);
  stop-opacity: 0;
}

.zfft5sbeg {
  stop-color: var(--svg-color--ff2f3c, #FF2F3C);
  stop-opacity: 0;
}

</style>
