<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wkduv4b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:downwards-button" /></template>
<style>
.wkduv4b9q {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M64 88.77c-.91 0-1.75-.46-2.25-1.23l-28.4-44.2c-.53-.83-.57-1.87-.1-2.72s1.37-1.39 2.34-1.39H92.4c.97 0 1.87.53 2.34 1.39c.47.85.43 1.9-.1 2.72l-28.4 44.2c-.49.77-1.33 1.23-2.24 1.23");
}

</style>
