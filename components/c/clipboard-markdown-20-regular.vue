<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h9jf5138b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-markdown-20-regular" /></template>
<style>
.h9jf5138b {
  fill: currentColor;
  d: path("M11.5 2a1.5 1.5 0 0 1 1.415 1H14.5A1.5 1.5 0 0 1 16 4.5v6.587a1.5 1.5 0 0 0-1 1.413v-8a.5.5 0 0 0-.5-.5h-1.585A1.5 1.5 0 0 1 11.5 5h-3a1.5 1.5 0 0 1-1.415-1H5.5a.5.5 0 0 0-.5.5v12a.5.5 0 0 0 .5.5H6v.5c0 .175.032.343.087.5H5.5A1.5 1.5 0 0 1 4 16.5v-12A1.5 1.5 0 0 1 5.5 3h1.585A1.5 1.5 0 0 1 8.5 2zm1.115 10.014A.5.5 0 0 1 13 12.5v5a.5.5 0 0 1-1 0v-2.882l-1.553 3.106a.5.5 0 0 1-.894 0L8 14.618V17.5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .947-.224L10 16.382l.028-.058l2.025-4.048a.5.5 0 0 1 .562-.262M16.5 12a.5.5 0 0 1 .5.5v3.793l1.146-1.146a.5.5 0 1 1 .707.707l-2 2a.5.5 0 0 1-.707 0l-2-2a.5.5 0 1 1 .707-.707L16 16.293V12.5a.5.5 0 0 1 .5-.5m-8-9a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
