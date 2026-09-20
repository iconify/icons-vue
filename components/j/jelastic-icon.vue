<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":289};
const content = `<defs><linearGradient id="svgIDa" x1="50.008%" x2="50.008%" y1="87.683%" y2=".077%"><stop offset="0%" class="fuhaldksb"/><stop offset="25%" class="fuhaldksb"/><stop offset="70%" class="z3qdfs8_g"/><stop offset="100%" class="cpi4-fn4i"/></linearGradient></defs><path class="ex6qaedhu"/><path fill="url(#svgIDa)" class="m8gxmbcwt"/><path class="kb4yqz19q"/><path class="qvg9y_0vs"/><path class="c6bd3ib0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:jelastic-icon" /></template>
<style>
.c6bd3ib0u {
  fill: var(--svg-color--0064c8, #0064C8);
  d: path("m63.968 181.15l63.926-36.915v-73.83L63.968 107.32v73.83Zm63.926-36.915v-73.83l63.968 36.915v73.83l-63.968-36.915Z");
}

.cpi4-fn4i {
  stop-color: var(--svg-color--00acff, #00ACFF);
}

.ex6qaedhu {
  fill: var(--svg-color--0064c8, #0064C8);
  d: path("m64.011 181.15l63.925-36.915v-73.83L64.011 107.32v73.83Zm63.925-36.915v-73.83l63.926 36.915v73.83l-63.926-36.915Z");
}

.fuhaldksb {
  stop-color: var(--svg-color--0056b3, #0056B3);
}

.kb4yqz19q {
  fill: var(--svg-color--0056b3, #0056B3);
  d: path("M0 144.235v46.39c0 28.04.514 27.697 23.71 40.902l80.474 46.647c23.195 13.377 23.195 14.02 47.419 0l-23.71-60.024l-63.925-37v-73.958L0 144.235Z");
}

.m8gxmbcwt {
  d: path("M252.572 72.25c-4.802-7.975-12.863-11.02-20.58-15.564l-80.389-46.433c-22.98-13.376-22.98-13.977-47.419.043L63.968 33.491l127.894 73.7v73.959l-63.926 36.914l-63.968-36.914v-73.958L0 144.235v46.39c0 28.04.514 27.697 23.71 40.902l80.474 46.647c23.195 13.377 23.195 14.02 47.419 0l80.518-46.647c23.195-13.377 23.666-13.12 23.666-41.074V97.717c0-9.09 1.458-17.45-3.215-25.468Z");
}

.qvg9y_0vs {
  fill: var(--svg-color--0088fb, #0088FB);
  d: path("M252.529 72.292c-4.802-7.974-12.863-11.018-20.58-15.563L151.56 10.296c-23.152-13.377-23.195-13.977-47.419 0L63.925 33.534l127.894 73.658v74l-63.968 36.915l-63.926-36.914v-74.001L0 144.278v46.433c0 27.954.472 27.696 23.667 41.073l80.474 46.433c23.195 13.376 23.195 14.02 47.42 0l80.474-46.433c23.195-13.377 23.666-13.12 23.666-41.073V97.759c.043-9.089 1.544-17.406-3.172-25.467Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z3qdfs8_g {
  stop-color: var(--svg-color--0088fb, #0088FB);
}

</style>
