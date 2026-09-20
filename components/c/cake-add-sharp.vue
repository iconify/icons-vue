<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k73yw-bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cake-add-sharp" /></template>
<style>
.k73yw-bge {
  fill: currentColor;
  d: path("M3 21v-6.538h16V21zm2-7.539V8.077h5.5V6.588q-.43-.28-.715-.638T9.5 5.11q0-.3.112-.568t.334-.488L11 3l1.052 1.052q.225.225.337.491t.111.568q0 .481-.285.839q-.284.358-.715.638v1.489H17v5.385zM19 8V6h-2V5h2V3h1v2h2v1h-2v2z");
}

</style>
