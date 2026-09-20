<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qm6qkxbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:large-orange-diamond" /></template>
<style>
.qm6qkxbbw {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M64 126.82c-.78 0-1.55-.3-2.14-.89L2.07 66.15c-.57-.57-.89-1.34-.89-2.15c0-.8.32-1.58.89-2.14L61.86 2.07a3.03 3.03 0 0 1 4.29 0l59.79 59.79a3.04 3.04 0 0 1 0 4.29l-59.79 59.79c-.6.58-1.37.88-2.15.88");
}

</style>
