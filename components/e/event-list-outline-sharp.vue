<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7uqy0bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-list-outline-sharp" /></template>
<style>
.a7uqy0bij {
  fill: currentColor;
  d: path("M14 21v-8h8v8zm2-2h4v-4h-4zM2 18v-2h9v2zm12-7V3h8v8zm2-2h4V5h-4zM2 8V6h9v2zm16-1");
}

</style>
