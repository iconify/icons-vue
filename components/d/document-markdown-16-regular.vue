<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jylwt247l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-markdown-16-regular" /></template>
<style>
.jylwt247l {
  fill: currentColor;
  d: path("M5.615 10.014A.5.5 0 0 1 6 10.5v4a.5.5 0 0 1-1 0v-1.882l-1.02 2.04l-.023.045l-.01.02a.5.5 0 0 1-.894 0L2 12.619V14.5a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 .947-.224L3.5 13.382l1.553-3.106a.5.5 0 0 1 .562-.262M9 10a.5.5 0 0 1 .5.5v2.793l.646-.646a.5.5 0 1 1 .707.707l-1.5 1.5a.5.5 0 0 1-.113.082a.5.5 0 0 1-.339.054a.5.5 0 0 1-.142-.055a.5.5 0 0 1-.113-.082l-1.5-1.5a.5.5 0 1 1 .708-.707l.646.647V10.5A.5.5 0 0 1 9 10m-.414-9a1.5 1.5 0 0 1 1.06.44l2.914 2.914a1.5 1.5 0 0 1 .44 1.06V13a2 2 0 0 1-2 2h-.379l.94-.94c.283-.283.428-.653.437-1.025L12 13V6H9.5A1.5 1.5 0 0 1 8 4.5V2H5a1 1 0 0 0-1 1v7.146l-.5 1l-.5-1V3a2 2 0 0 1 2-2zM9 4.5a.5.5 0 0 0 .5.5h2.293L9 2.207z");
}

</style>
