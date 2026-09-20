<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieou1ts7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-sharp" /></template>
<style>
.ieou1ts7p {
  fill: currentColor;
  d: path("M1 21v-2h22v2zm1-3V3h20v15z");
}

</style>
