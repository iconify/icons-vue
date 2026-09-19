<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jkf2ozb2j"/><path class="f_ca_d7qs"/><ellipse class="ci7g1rbnt"/><path class="rho5b5zca"/><ellipse class="kpr1mdl3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:eyes" /></template>
<style>
.ci7g1rbnt {
  cx: 42.621px;
  cy: 32.3px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 7.426px;
  ry: 9px;
}

.f_ca_d7qs {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M63.732 30.09c0 13.13-7.102 23.774-15.869 23.774c-8.771 0-15.885-10.643-15.885-23.774c0-13.14 7.115-23.775 15.885-23.775S63.732 16.954 63.732 30.09");
}

.jkf2ozb2j {
  fill: var(--svg-color--d1d2d3, #d1d2d3);
  d: path("M63.66 32.389c0 13.13-7.103 23.775-15.87 23.775c-8.771 0-15.885-10.643-15.885-23.775c0-13.14 7.115-23.775 15.885-23.775s15.87 10.638 15.87 23.775m-31.903.183c0 13.13-7.102 23.777-15.872 23.777C7.117 56.349 0 45.705 0 32.572C0 19.432 7.117 8.798 15.885 8.798c8.771 0 15.872 10.638 15.872 23.774");
}

.kpr1mdl3a {
  cx: 9.887px;
  cy: 32.482px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 7.428px;
  ry: 9px;
}

.rho5b5zca {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M31.83 30.27c0 13.13-7.102 23.775-15.873 23.775C7.189 54.045.072 43.402.072 30.27c0-13.14 7.117-23.774 15.885-23.774c8.771 0 15.873 10.638 15.873 23.774");
}

</style>
