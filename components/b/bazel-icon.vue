<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255};
const content = `<path class="egornqcbs"/><path class="geop2-bjt"/><path class="d4ipfjh-b"/><path class="n4pohsfwv"/><path class="r-bxzmbmg"/><path class="npyydqnsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bazel-icon" /></template>
<style>
.d4ipfjh-b {
  fill: var(--svg-color--004300, #004300);
  d: path("m127.971 192.015l64.044-63.986v62.811l-64.044 63.985z");
}

.egornqcbs {
  fill: var(--svg-color--76d275, #76d275);
  d: path("m63.985 0l63.986 63.985L192.015 0L256 63.985v62.81l-63.985 64.045l-64.044 63.985l-63.986-63.985L0 126.796v-62.81z");
}

.geop2-bjt {
  fill: var(--svg-color--00701a, #00701a);
  d: path("M127.971 192.015v62.81L63.985 190.84v-62.811z");
}

.n4pohsfwv {
  fill: var(--svg-color--43a047, #43a047);
  d: path("M63.985 128.029v62.811L0 126.796V63.985zM256 63.985v62.811l-63.985 64.044v-62.811zm-128.029 128.03l-63.986-63.986l63.986-64.044l64.044 64.044z");
}

.npyydqnsp {
  fill: var(--svg-color--76d275, #76d275);
  d: path("m192.015 128.029l-64.044-64.044L192.015 0L256 63.985z");
}

.r-bxzmbmg {
  fill: var(--svg-color--76d275, #76d275);
  d: path("M63.985 128.029L0 63.985L63.985 0l63.986 63.985z");
}

</style>
