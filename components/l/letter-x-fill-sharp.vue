<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umpfuubtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-x-fill-sharp" /></template>
<style>
.umpfuubtt {
  fill: currentColor;
  d: path("m13.179 12l4.669 7.47a1 1 0 0 1-1.696 1.06L12 13.887L7.848 20.53a1 1 0 0 1-1.696-1.06L10.821 12L6.152 4.53a1 1 0 0 1 1.696-1.06L12 10.113l4.152-6.643a.998.998 0 0 1 1.731.061a1 1 0 0 1-.035.999Z");
}

</style>
