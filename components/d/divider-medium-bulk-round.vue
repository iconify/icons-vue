<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9qwkaj6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-medium-bulk-round" /></template>
<style>
.y9qwkaj6s {
  fill: currentColor;
  d: path("M13 7v10a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0");
}

</style>
