<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngma_9qff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:docs-sharp" /></template>
<style>
.ngma_9qff {
  fill: currentColor;
  d: path("M12 2v7h7v13H5V2zm2 0l5 5h-5zM9 19h4v-2H9zm0-4h6v-2H9z");
}

</style>
