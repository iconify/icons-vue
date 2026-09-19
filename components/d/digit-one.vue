<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="orkp_28we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:digit-one" /></template>
<style>
.orkp_28we {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m6 46h-6.107V24.979Q28.545 28.108 24 29.608v-5.543q2.391-.783 5.195-2.967T33.043 16H38z");
}

</style>
