<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocf-iebjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:full-coverage-sharp" /></template>
<style>
.ocf-iebjz {
  fill: currentColor;
  d: path("M2 21V7h2v12h15v2zm4-4V3h17v14zm4-5h4V7h-4zm5 0h4v-2h-4zm0-3h4V7h-4z");
}

</style>
