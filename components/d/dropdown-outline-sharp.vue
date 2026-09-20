<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe3m8k5zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dropdown-outline-sharp" /></template>
<style>
.fe3m8k5zi {
  fill: currentColor;
  d: path("M12 12h6V6h-6zm-8 8V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
