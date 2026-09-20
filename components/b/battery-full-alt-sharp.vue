<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcem6-bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-full-alt-sharp" /></template>
<style>
.jcem6-bqg {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10z");
}

</style>
