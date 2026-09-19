<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isMSpXd)" class="hy4x1nb-j"/><path fill="url(#iccWxqb)" class="hy4x1nb-j"/><path fill="url(#i4UGkBe)" class="hy4x1nb-j"/><path fill="url(#iFU87wb)" class="hy4x1nb-j"/><path fill="url(#ijqumHc)" class="hy4x1nb-j"/><defs><radialGradient id="isMSpXd" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.831 9.886)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="x97fmacfc"/><stop offset=".853" class="yae35fbuf"/></radialGradient><radialGradient id="i4UGkBe" cx="0" cy="0" r="1" gradientTransform="matrix(-9.47663 8.74999 -8.07914 -8.75007 24.227 10.75)" gradientUnits="userSpaceOnUse"><stop class="nf2nbtihb"/><stop offset="1" class="eul_yij3i"/></radialGradient><radialGradient id="iFU87wb" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.04 16)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="qvc6c42kq"/><stop offset=".951" class="f668jzb6q"/></radialGradient><radialGradient id="ijqumHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 21 -23.3208 0 15.547 9)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="cr2naacom"/><stop offset="1" class="r5hh2-bgj"/></radialGradient><linearGradient id="iccWxqb" x1="15.547" x2="15.547" y1="2" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="n_emqeb6f"/><stop offset="1" class="uwnlobbkw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:brown-circle" /></template>
<style>
.cr2naacom {
  stop-color: var(--svg-color--703952, #703952);
  stop-opacity: 0;
}

.eul_yij3i {
  stop-color: var(--svg-color--9e6c66, #9E6C66);
  stop-opacity: 0;
}

.f668jzb6q {
  stop-color: var(--svg-color--9f8d8c, #9F8D8C);
}

.ft5dv1b6b {
  fill: none;
}

.hy4x1nb-j {
  d: path("M29.547 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.n_emqeb6f {
  stop-color: var(--svg-color--876a62, #876A62);
}

.nf2nbtihb {
  stop-color: var(--svg-color--aa7e73, #AA7E73);
}

.qvc6c42kq {
  stop-color: var(--svg-color--755551, #755551);
  stop-opacity: 0;
}

.r5hh2-bgj {
  stop-color: var(--svg-color--673754, #673754);
}

.uwnlobbkw {
  stop-color: var(--svg-color--876a62, #876A62);
  stop-opacity: 0;
}

.x97fmacfc {
  stop-color: var(--svg-color--8c5e51, #8C5E51);
}

.yae35fbuf {
  stop-color: var(--svg-color--703b50, #703B50);
}

</style>
