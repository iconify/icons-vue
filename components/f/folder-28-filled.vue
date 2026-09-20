<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qchjxmlvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-28-filled" /></template>
<style>
.qchjxmlvo {
  fill: currentColor;
  d: path("M2 6.75A3.75 3.75 0 0 1 5.75 3h3.672c.729 0 1.428.29 1.944.805L13.25 5.69l-2.944 2.945A1.25 1.25 0 0 1 9.422 9H2zm.004 3.75v9.75A3.75 3.75 0 0 0 5.754 24H22.25A3.75 3.75 0 0 0 26 20.25V9.75A3.75 3.75 0 0 0 22.25 6h-7.19l-3.694 3.695a2.75 2.75 0 0 1-1.944.805z");
}

</style>
