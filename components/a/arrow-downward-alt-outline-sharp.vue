<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-gjwwbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-downward-alt-outline-sharp" /></template>
<style>
.i-gjwwbyp {
  fill: currentColor;
  d: path("m12 18l-6-6l1.4-1.4l3.6 3.6V5h2v9.2l3.6-3.6L18 12z");
}

</style>
