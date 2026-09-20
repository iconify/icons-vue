<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r1szqyahq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:letter-i" /></template>
<style>
.r1szqyahq {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M76.32 16.27H51.68c-1.29 0-2.33 1.05-2.33 2.33v99.96c0 1.29 1.04 2.33 2.33 2.33h24.64c1.29 0 2.33-1.04 2.33-2.33V18.6c0-1.28-1.04-2.33-2.33-2.33");
}

</style>
