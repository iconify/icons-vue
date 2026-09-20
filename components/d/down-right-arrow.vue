<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="udswgk8qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:down-right-arrow" /></template>
<style>
.udswgk8qa {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M98.25 98.18L44.51 89.9l14.18-14.18l-28.94-28.93l16.96-16.96l28.94 28.93l14.32-14.32z");
}

</style>
