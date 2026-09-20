<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="d92lmubry"/><path class="zut58gbmm"/><path class="tzse-8bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-yemen" /></template>
<style>
.d92lmubry {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 27.063C0 29.272 1.791 31 4 31h28c2.209 0 4-1.728 4-3.937V22H0z");
}

.tzse-8bre {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M32 5H4C1.791 5 0 6.854 0 9.063V14h36V9.063C36 6.854 34.209 5 32 5");
}

.zut58gbmm {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 14h36v8H0z");
}

</style>
