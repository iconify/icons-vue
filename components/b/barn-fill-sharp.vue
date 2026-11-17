<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1my1kbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-fill-sharp" /></template>
<style>
.i1my1kbvr {
  fill: currentColor;
  d: path("m12.514 2.143l5 3q.168.1.286.257l3 4a1 1 0 0 1 .2.6v10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2V10a1 1 0 0 1 .2-.6l3-4q.118-.156.286-.257l5-3a.99.99 0 0 1 1.028 0M12 12a2 2 0 1 0 .001-3.999A2 2 0 0 0 12 12m3 4H9v4h6Z");
}

</style>
