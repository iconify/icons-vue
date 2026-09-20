<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nbsaajwxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-markdown-20-regular" /></template>
<style>
.nbsaajwxs {
  fill: currentColor;
  d: path("M6.615 12.014A.5.5 0 0 1 7 12.5v5a.5.5 0 0 1-1 0v-2.882l-1.553 3.106a.5.5 0 0 1-.894 0L2 14.618V17.5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .947-.224L4 16.382l.028-.058l2.025-4.048a.5.5 0 0 1 .562-.262M10.5 12a.5.5 0 0 1 .5.5v3.793l1.146-1.146a.5.5 0 1 1 .707.707l-2 2a.5.5 0 0 1-.113.082a.5.5 0 0 1-.339.054a.5.5 0 0 1-.142-.054a.5.5 0 0 1-.113-.082l-2-2a.5.5 0 1 1 .708-.707L10 16.293V12.5a.5.5 0 0 1 .5-.5m.086-10a1.5 1.5 0 0 1 1.06.44l3.914 3.914a1.5 1.5 0 0 1 .44 1.06V16a2 2 0 0 1-2 2h-1.879l1-1H14a1 1 0 0 0 1-1V8h-3.5A1.5 1.5 0 0 1 10 6.5V3H6a1 1 0 0 0-1 1v8.146l-1 2V4a2 2 0 0 1 2-2zM11 6.5a.5.5 0 0 0 .5.5h3.293L11 3.207z");
}

</style>
