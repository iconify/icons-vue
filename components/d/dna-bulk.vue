<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zzhtv4blh"/><path class="r0mz8-loo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dna-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r0mz8-loo {
  d: path("M7 3v1h11a1 1 0 0 1 0 2H7.151c.235.764.722 1.426 1.267 2H16a1 1 0 0 1 0 2h-5.162c1.308.919 2.667 1.764 3.956 2.709a18 18 0 0 1 1.941 1.613C18.037 15.593 19 17.126 19 19v2a1 1 0 0 1-2 0v-1H6a1 1 0 0 1 0-2h10.849c-.235-.764-.722-1.426-1.267-2H8a1 1 0 0 1 0-2h5.162c-1.308-.919-2.667-1.764-3.956-2.709a18 18 0 0 1-1.941-1.613C5.963 8.407 5 6.874 5 5V3a1 1 0 0 1 2 0");
}

.zzhtv4blh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 5c0 .916-.242 1.813-.671 2.62c-.418.785-.996 1.477-1.631 2.096a.999.999 0 1 1-1.396-1.432c.487-.475.94-1.001 1.261-1.604A3.6 3.6 0 0 0 17 5V3a1 1 0 0 1 2 0ZM7 19v2a1 1 0 0 1-2 0v-2c0-.916.242-1.813.671-2.62c.418-.785.996-1.477 1.631-2.096a.999.999 0 1 1 1.396 1.432c-.487.475-.94 1.001-1.261 1.604A3.6 3.6 0 0 0 7 19");
}

</style>
