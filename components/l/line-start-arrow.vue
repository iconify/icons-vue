<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kel900s3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-arrow" /></template>
<style>
.kel900s3c {
  fill: currentColor;
  d: path("M11.808 16.827L4.212 12l7.596-4.827V11.5h9.115v1h-9.115z");
}

</style>
