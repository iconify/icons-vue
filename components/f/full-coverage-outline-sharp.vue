<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gouislc6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:full-coverage-outline-sharp" /></template>
<style>
.gouislc6l {
  fill: currentColor;
  d: path("M3 20V8h1v11h14v1zm4-4V4h15v12zm1-1h13V5H8zm2-3h4V7h-4zm5 0h4v-2h-4zm0-3h4V7h-4zm-7 6V5z");
}

</style>
