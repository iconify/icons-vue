<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6b56efqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contextual-token-add-sharp" /></template>
<style>
.n6b56efqy {
  fill: currentColor;
  d: path("M18 9V7h-2V5h2V3h2v2h2v2h-2v2zM6 16h7v-3H6zm0-5h7V8H6zm-4 9V4h12.425q-.2.45-.312.963T14 6q0 .85.263 1.613T15 9v7h3v-5.1q.25.05.488.075T19 11q.85 0 1.613-.262T22 10v10z");
}

</style>
