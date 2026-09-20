<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ath5kzl5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cleaning-services-outline-sharp" /></template>
<style>
.ath5kzl5h {
  fill: currentColor;
  d: path("M3 23V11h6V1h6v10h6v12zm2-2h2v-4h2v4h2v-4h2v4h2v-4h2v4h2v-8H5zm8-10V3h-2v8zm0 0h-2z");
}

</style>
