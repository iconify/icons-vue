<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5ubt8i7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-21-9" /></template>
<style>
.u5ubt8i7s {
  fill: currentColor;
  d: path("M4.616 16q-.691 0-1.153-.462T3 14.385v-4.77q0-.69.463-1.152T4.615 8h14.77q.69 0 1.152.463T21 9.616v4.769q0 .69-.463 1.153T19.385 16z");
}

</style>
