<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pznt0ob-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flex-no-wrap" /></template>
<style>
.pznt0ob-e {
  fill: currentColor;
  d: path("M1 17V7h6v10zm8 0V7h6v10zm8 0V7h6v10zM3 15h2V9H3zm16 0h2V9h-2z");
}

</style>
