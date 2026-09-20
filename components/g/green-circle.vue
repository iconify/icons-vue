<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="s7lk2nbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:green-circle" /></template>
<style>
.s7lk2nbec {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--78b159, #78b159);
}

</style>
