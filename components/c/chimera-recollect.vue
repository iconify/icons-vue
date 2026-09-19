<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="nqfditd-n"/><path class="oichsg00j"/><path class="lq8r6y5mo"/><path class="hwsvxtdxt"/><path class="cp-sn2wiv"/><path class="y5sjd9buv"/><circle class="rgxba6bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chimera-recollect" /></template>
<style>
.cp-sn2wiv {
  d: path("M13.303 15.455c-.279.103-2.021 1.791-2.599 7.444c-.178 2.91.285 4.45-1.699 8.13l3.958-1.758m4.582-8.241s1.432-.782 1.934.267m8.619.557s1.52-1.126 2.524-.317m-14.205 4.419s1.398-3.268 3.061-1.422m9.177.554s2.307-2.396 2.908 1.704m-13.051-2.454v3.652m11.217-3.096l-.431 3.535M15.86 29.896s7.033 8.923 16.994-.07");
}

.hwsvxtdxt {
  d: path("M22.736 9.764s6.453.011 1.267-4.631c0 0-7.762-6.58-10.752 6.678c0 0-.474 2.122-3.69.764c0 0 .94 4.563 6.723 2.227");
}

.lq8r6y5mo {
  d: path("M16.25 19.076s-3.32 7.088 1.573 16.347c0 0-11.427-9.467-1.49-20.621l2.702-2.662");
}

.nqfditd-n {
  d: path("M20.035 17.788s-.266 4.294 3.969 6.414c0 0-2.415-5.599.573-8.1c0 0-.698 3.857.896 7.362c0 0 .978-6.782 3.143-6.471c0 0 3.408 2.333 2.18 5.978c0 0 2.371-1.775 1.83-3.596c0 0 1.548 11.68-.974 15.881c0 0 8.936-11.624 1.537-20.858");
}

.oichsg00j {
  d: path("M34.95 28.985s1.654 1.084 4.045 2.2c0 0-1.628-.81-1.197-6.572c0 0 1.232-13.817-12.452-15.348m-5.311 8.438s-4.312 1.579-2.46 5.268c0 0-2.272-2.25-.891-5.337");
}

.rgxba6bvs {
  cx: 23.68px;
  cy: 38.311px;
  r: 0.557px;
}

.y5sjd9buv {
  d: path("M23.624 37.263c.032-.117-.902-2.467-1.27-3.45c0 0-2.942.213-4.222 4.194l1.346 1.095s.042 3.072.739 4.857l2.048.541l1.31-4.887m.09-2.298l1.632-3.493c.008-.038 2.956 1.199 3.444 3.376l-1.206 1.959l-.09 4.117l-2.655 1.132l-1.2-4.77m-5.078-1.326l-2.014 4.65m11.982-4.953l2.048 5.614m-12.016-.105l.999-2.71m8.043.353l1.187 2.667");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
