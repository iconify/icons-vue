<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vmhikv9fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:diamond-suit" /></template>
<style>
.vmhikv9fz {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M113.99 62.45L65.95.97c-.94-1.2-2.96-1.2-3.9 0L14.01 62.44c-.7.9-.7 2.16 0 3.05l48.04 61.48a2.478 2.478 0 0 0 3.9 0l48.03-61.48c.7-.89.7-2.15.01-3.04");
}

</style>
