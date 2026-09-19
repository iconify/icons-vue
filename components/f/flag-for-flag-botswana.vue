<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="oe7nljgxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-botswana" /></template>
<style>
.oe7nljgxq {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M5.133 39.867a28 28 0 0 1-.692-2.95h55.118a28 28 0 0 1-.691 2.95zm-.692-12.784q.268-1.505.692-2.949h53.734q.425 1.445.691 2.949z");
}

</style>
