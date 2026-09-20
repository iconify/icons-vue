<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="pi2g5bq9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:blue-circle" /></template>
<style>
.pi2g5bq9h {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--55acee, #55acee);
}

</style>
