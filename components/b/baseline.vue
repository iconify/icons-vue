<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":146};
const content = `<path class="vvxb-pwme"/><path class="s9uvrus9y"/><path class="dkp8m1ylz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:baseline" /></template>
<style>
.dkp8m1ylz {
  fill: var(--svg-color--008f32, #008f32);
  d: path("M73.082 110.691L17.523 55.132L0 72.654l73.082 73.082l17.095-17.095l.428-.427L200.868 17.95L183.346.427z");
}

.s9uvrus9y {
  fill: var(--svg-color--99dbb3, #99dbb3);
  d: path("m72.655 0l-55.56 55.559l17.523 17.523l38.037-38.037l23.506 23.506l17.522-17.522l-23.506-23.506z");
}

.vvxb-pwme {
  fill: var(--svg-color--99dbb1, #99dbb1);
  d: path("m182.918 35.045l38.037 38.036l-37.61 37.611l-23.505-23.506l-17.523 17.521l23.506 23.506l17.522 17.523L256 73.081L238.477 55.56l-38.036-38.037z");
}

</style>
