<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="tokenBrandedAsto0" width="20" height="20" x="2" y="2" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="f-_0sobvu"/></mask><g class="ft5dv1b6b"><g mask="url(#tokenBrandedAsto0)"><path class="fkymuybfc"/><path fill="url(#tokenBrandedAsto1)" class="u5muvsbga"/><path fill="url(#tokenBrandedAsto2)" class="bomimxbpe"/><path fill="url(#tokenBrandedAsto3)" class="pst_j36_x"/></g><defs><linearGradient id="tokenBrandedAsto1" x1="11.999" x2="11.999" y1="6.286" y2="16.643" gradientUnits="userSpaceOnUse"><stop class="e753_xn9z"/><stop offset=".53" class="f525ah5dz"/><stop offset="1" class="zoj5zwnqd"/></linearGradient><linearGradient id="tokenBrandedAsto2" x1="12.301" x2="14.296" y1="6.286" y2="15.369" gradientUnits="userSpaceOnUse"><stop class="f359amjsb"/><stop offset="1" class="zlxpjqbjj"/></linearGradient><linearGradient id="tokenBrandedAsto3" x1="13.918" x2="15.036" y1="7.454" y2="13.607" gradientUnits="userSpaceOnUse"><stop class="t2fuzy21w"/><stop offset=".57" class="lbnxf9b1f"/><stop offset="1" class="ps7d16x8s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:asto" /></template>
<style>
.bomimxbpe {
  d: path("M14.322 14.143a3.393 3.393 0 1 0 0-6.786a3.393 3.393 0 0 0 0 6.786");
}

.e753_xn9z {
  stop-color: var(--svg-color--7f70fd, #7F70FD);
}

.f-_0sobvu {
  fill: var(--svg-color--fff, #fff);
  d: path("M22 2H2v20h20z");
}

.f359amjsb {
  stop-color: var(--svg-color--f4c9ea, #F4C9EA);
}

.f525ah5dz {
  stop-color: var(--svg-color--6551f1, #6551F1);
}

.fkymuybfc {
  fill: var(--svg-color--1e1e20, #1E1E20);
  d: path("M2 2h20v20H2z");
}

.ft5dv1b6b {
  fill: none;
}

.lbnxf9b1f {
  stop-color: var(--svg-color--ed9ff9, #ED9FF9);
}

.ps7d16x8s {
  stop-color: var(--svg-color--f3bbfb, #F3BBFB);
}

.pst_j36_x {
  d: path("M13.8 7.396a3.393 3.393 0 1 0 3.14 5.515a13 13 0 0 0-.9-2.204c-.411-.81-1.232-2.286-2.24-3.31");
}

.t2fuzy21w {
  stop-color: var(--svg-color--f9dbff, #F9DBFF);
}

.u5muvsbga {
  d: path("M9.428 16.396a5.1 5.1 0 0 1 2.31-.493c.472 0 1.35.025 2.311.493c.911.443 3.143.536 3.143-1.939c0-1.057-.485-2.436-1.153-3.75c-.668-1.321-2.44-4.421-4.3-4.421c-1.857 0-3.629 3.103-4.3 4.421c-.668 1.314-1.154 2.693-1.154 3.75c0 2.475 2.236 2.382 3.143 1.94");
}

.zlxpjqbjj {
  stop-color: var(--svg-color--e995ae, #E995AE);
}

.zoj5zwnqd {
  stop-color: var(--svg-color--846df8, #846DF8);
}

</style>
