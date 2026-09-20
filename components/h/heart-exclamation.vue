<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w9nqt-bwe"/><circle class="pf1fceypc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:heart-exclamation" /></template>
<style>
.pf1fceypc {
  cx: 18px;
  cy: 31px;
  r: 5px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.w9nqt-bwe {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M18 4C14.875-2.375 6-.731 6 7c0 7.062 12 17 12 17s12-9.938 12-17c0-7.731-8.875-9.375-12-3");
}

</style>
