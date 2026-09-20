<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw7igmbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ev-mobiledata-badge-sharp" /></template>
<style>
.fw7igmbtw {
  fill: currentColor;
  d: path("M5.885 16.5h4.884v-1H6.885v-3h2.884v-1H6.885v-3h3.884v-1H5.885zm9 0h1.076l2.693-9h-1.039l-2.192 7.23l-2.192-7.23h-1.039zM2 20V4h20v16z");
}

</style>
