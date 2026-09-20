<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xituzj2io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-or-edge-outline" /></template>
<style>
.xituzj2io {
  fill: currentColor;
  d: path("m7.827 20.02l-3.288-3.29l.688-.707l2.1 2.094v-6.655q0-.27-.173-.443t-.443-.173H3.846q-.671 0-1.143-.472t-.472-1.143V4h1v5.23q0 .27.173.443t.442.173h2.866q.67 0 1.143.472q.472.472.472 1.143v6.637l2.094-2.075l.695.708zm8.346 0l-3.288-3.29l.688-.707l2.1 2.094v-6.655q0-.671.472-1.144t1.144-.472h2.865q.269 0 .442-.173t.173-.442V4h1v5.23q0 .672-.472 1.144t-1.143.472h-2.866q-.269 0-.442.173t-.173.443v6.661l2.094-2.1l.694.708z");
}

</style>
