<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmso4q5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-flex-end-sharp" /></template>
<style>
.nmmso4q5h {
  fill: currentColor;
  d: path("M2 22v-2h20v2zm8.5-4V4h3v14z");
}

</style>
