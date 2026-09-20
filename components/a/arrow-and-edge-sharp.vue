<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id7yskq1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-and-edge-sharp" /></template>
<style>
.id7yskq1e {
  fill: currentColor;
  d: path("m12 21l-4-4l1.4-1.4l1.6 1.575V13q0-.825-.587-1.412T9 11H1V3h2v6h6q.9 0 1.675.363T12 10.35q.55-.625 1.325-.987T15 9h6V3h2v8h-8q-.825 0-1.412.588T13 13v4.175l1.575-1.575L16 17z");
}

</style>
