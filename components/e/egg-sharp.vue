<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msku_kbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:egg-sharp" /></template>
<style>
.msku_kbbh {
  fill: currentColor;
  d: path("M13 17.02h.5v-1H13q-1.458 0-2.48-1.022q-1.02-1.02-1.02-2.479v-.5h-1v.5q0 1.868 1.316 3.184T13 17.019m-5.29 1.203q-1.749-1.797-1.749-4.362q0-1.689.551-3.437q.552-1.748 1.43-3.182t1.945-2.347t2.094-.913q1.033 0 2.101.902t1.943 2.335t1.425 3.193t.55 3.449q0 2.565-1.753 4.362q-1.754 1.797-4.27 1.797T7.71 18.222");
}

</style>
