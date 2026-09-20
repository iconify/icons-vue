<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0a3a4qjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-9-plus-sharp" /></template>
<style>
.t0a3a4qjo {
  fill: currentColor;
  d: path("M6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1zm6.116-6.5H13v-7H9v4h3v2H9.616zM12 9.5h-2v-2h2zm4.116 3h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
