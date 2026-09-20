<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t7dfx7a_n"/><path class="ocurb7blv"/><path class="vt87hzqgk"/><circle class="a90ss9i9u"/><circle class="nux-erb1g"/><circle class="avs8s6bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:eye" /></template>
<style>
.a90ss9i9u {
  cx: 18px;
  cy: 18px;
  r: 8.458px;
  fill: var(--svg-color--8b5e3c, #8b5e3c);
}

.avs8s6bsv {
  cx: 14.983px;
  cy: 15px;
  r: 2px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.nux-erb1g {
  cx: 18px;
  cy: 18px;
  r: 4.708px;
  fill: var(--svg-color--292f33, #292f33);
}

.ocurb7blv {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M35.059 18H.925c0-3.313 7.642-11 17.067-11s17.067 7.686 17.067 11");
}

.t7dfx7a_n {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M35.059 18c0 3.304-7.642 11-17.067 11S.925 22.249.925 18c0-3.314 34.134-3.314 34.134 0");
}

.vt87hzqgk {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M33.817 18c0 2.904-7.087 9.667-15.826 9.667S2.166 21.732 2.166 18c0-2.912 7.085-9.666 15.825-9.666C26.73 8.333 33.817 15.088 33.817 18");
}

</style>
