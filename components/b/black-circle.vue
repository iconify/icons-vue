<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="v6ehlpb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:black-circle" /></template>
<style>
.v6ehlpb7m {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--31373d, #31373d);
}

</style>
