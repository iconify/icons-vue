<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp3zkrbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:delete-sweep-outline-sharp" /></template>
<style>
.lp3zkrbao {
  fill: currentColor;
  d: path("M15 18v-2h4v2zm0-8V8h7v2zm0 4v-2h6v2zM3 8H2V6h4V4.5h4V6h4v2h-1v11H3zm2 0v9h6V8zm0 0v9z");
}

</style>
