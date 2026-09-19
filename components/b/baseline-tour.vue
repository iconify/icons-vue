<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fouui64mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-tour" /></template>
<style>
.fouui64mx {
  fill: currentColor;
  d: path("M21 4H7V2H5v20h2v-8h14l-2-5zm-6 5c0 1.1-.9 2-2 2s-2-.9-2-2s.9-2 2-2s2 .9 2 2");
}

</style>
