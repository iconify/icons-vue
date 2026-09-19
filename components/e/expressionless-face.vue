<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="r4wibjb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:expressionless-face" /></template>
<style>
.r4wibjb1v {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40 48H24c-1.5 0-1.5-4 0-4h16c1.5 0 1.5 4 0 4M27.1 32h-16c-1.5 0-1.5-4 0-4h16c1.5 0 1.5 4 0 4m25.8 0h-16c-1.5 0-1.5-4 0-4h16c1.5 0 1.5 4 0 4");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
