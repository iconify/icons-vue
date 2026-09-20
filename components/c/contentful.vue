<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":289};
const content = `<path class="s0rjs61hx"/><path class="qiyco7brr"/><path class="yvlgezlrb"/><circle class="ug_4u89ew"/><circle class="asahgcyzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:contentful" /></template>
<style>
.asahgcyzs {
  cx: 64.825px;
  cy: 223.285px;
  r: 31.512px;
  fill: var(--svg-color--cd4739, #cd4739);
}

.qiyco7brr {
  fill: var(--svg-color--4fb5e1, #4fb5e1);
  d: path("M87.333 87.333c14.406-15.306 34.213-24.309 56.722-24.309s42.316 9.003 56.722 23.409c12.604 12.605 32.412 12.605 45.017 0s12.605-32.412 0-45.017C219.684 16.206 183.67 0 144.055 0S68.426 16.206 42.316 42.316c-12.605 12.605-12.605 32.413 0 45.017c12.605 11.705 32.413 11.705 45.017 0");
}

.s0rjs61hx {
  fill: var(--svg-color--fae501, #fae501);
  d: path("M87.333 200.777c-15.306-14.406-24.309-34.213-24.309-56.722s9.003-42.316 23.409-56.722c12.605-12.604 12.605-32.412 0-45.017s-32.412-12.605-45.017 0C16.206 68.426 0 104.44 0 144.055s16.206 75.629 42.316 101.739c12.605 12.605 32.413 12.605 45.017 0c11.705-12.605 11.705-32.413 0-45.017");
}

.ug_4u89ew {
  cx: 64.825px;
  cy: 64.825px;
  r: 31.512px;
  fill: var(--svg-color--0681b6, #0681b6);
}

.yvlgezlrb {
  fill: var(--svg-color--f05751, #f05751);
  d: path("M200.777 200.777c-14.406 15.305-34.213 24.309-56.722 24.309s-42.316-9.004-56.722-23.41c-12.604-12.604-32.412-12.604-45.017 0c-12.605 12.606-12.605 32.413 0 45.018c26.11 25.21 62.124 41.416 101.739 41.416s75.629-16.206 101.739-42.316c12.605-12.605 12.605-32.413 0-45.017c-12.605-11.705-32.413-11.705-45.017 0");
}

</style>
