<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs7bqrbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:g-mobiledata-badge-sharp" /></template>
<style>
.xs7bqrbpv {
  fill: currentColor;
  d: path("M8 17h8v-6h-4v2h2v2h-4V9h6V7H8zm-5 4V3h18v18z");
}

</style>
