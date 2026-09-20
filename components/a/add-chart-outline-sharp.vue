<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaiodtbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-chart-outline-sharp" /></template>
<style>
.aaiodtbkg {
  fill: currentColor;
  d: path("M7 17h2v-7H7zm4 0h2V7h-2zm4 0h2v-4h-2zM3 21V3h11v2H5v14h14v-9h2v11zM17 9V7h-2V5h2V3h2v2h2v2h-2v2zm-5 3");
}

</style>
