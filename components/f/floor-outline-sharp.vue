<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i90wcrbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:floor-outline-sharp" /></template>
<style>
.i90wcrbxx {
  fill: currentColor;
  d: path("M3 22v-2h3.5v-4.5H11V11h4.5V6.5H20V3h2v5.5h-4.5V13H13v4.5H8.5V22z");
}

</style>
