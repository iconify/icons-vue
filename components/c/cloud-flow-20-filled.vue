<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l8qvu8blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-flow-20-filled" /></template>
<style>
.l8qvu8blr {
  fill: currentColor;
  d: path("M10 2c2.817 0 4.415 1.923 4.647 4.246h.07C16.532 6.246 18 7.758 18 9.623q0 .07-.003.138A3 3 0 0 0 13.17 11a2.5 2.5 0 0 0-2.32 1.71l-.098.29h-5.47C3.469 13 2 11.488 2 9.623s1.47-3.377 3.282-3.377h.071C5.587 3.908 7.183 2 10 2m6 12a2 2 0 1 0-2-2h-.78a1.5 1.5 0 0 0-1.422 1.026l-.544 1.632a.5.5 0 0 1-.475.342H9.732A2 2 0 1 0 10 16h.78a1.5 1.5 0 0 0 1.422-1.026l.544-1.632a.5.5 0 0 1 .475-.342h1.047A2 2 0 0 0 16 14m0-1a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-7 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
