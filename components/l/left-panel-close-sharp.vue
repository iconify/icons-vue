<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig_mtb54g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:left-panel-close-sharp" /></template>
<style>
.ig_mtb54g {
  fill: currentColor;
  d: path("M16.5 16V8l-4 4zM10 19h9V5h-9zm-7 2V3h18v18z");
}

</style>
