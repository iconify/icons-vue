<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uhgwdubil"/><circle class="qja0zjb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-bangladesh" /></template>
<style>
.qja0zjb8u {
  fill: var(--svg-color--f42a41, #F42A41);
  cx: 16px;
  cy: 17.5px;
  r: 7px;
}

.uhgwdubil {
  fill: var(--svg-color--006a4d, #006A4D);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

</style>
