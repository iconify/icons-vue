<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1-m95bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:h-mobiledata-badge-sharp" /></template>
<style>
.o1-m95bxx {
  fill: currentColor;
  d: path("M8 17h2v-4h4v4h2V7h-2v4h-4V7H8zm-5 4V3h18v18z");
}

</style>
