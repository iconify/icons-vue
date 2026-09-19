<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvoufo8om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:event-busy" /></template>
<style>
.gvoufo8om {
  fill: currentColor;
  d: path("m9.31 17l2.44-2.44L14.19 17l1.06-1.06l-2.44-2.44l2.44-2.44L14.19 10l-2.44 2.44L9.31 10l-1.06 1.06l2.44 2.44l-2.44 2.44zM19 3h-1V1h-2v2H8V1H6v2H5c-1.11 0-1.99.9-1.99 2L3 19a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V8h14z");
}

</style>
