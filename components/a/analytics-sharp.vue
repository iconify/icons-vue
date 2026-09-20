<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak2rfhb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:analytics-sharp" /></template>
<style>
.ak2rfhb2z {
  fill: currentColor;
  d: path("M3 21V3h18v18zm4-4h2v-5H7zm8 0h2V7h-2zm-4 0h2v-3h-2zm0-5h2v-2h-2z");
}

</style>
