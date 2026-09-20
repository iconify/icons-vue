<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="egna2tb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-markdown-16-filled" /></template>
<style>
.egna2tb4j {
  fill: currentColor;
  d: path("M9.615 10.014A.5.5 0 0 1 10 10.5v4a.5.5 0 0 1-1 0v-1.882l-1.053 2.106a.5.5 0 0 1-.894 0L6 12.618V14.5a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 .947-.224L7.5 13.382l1.553-3.106a.5.5 0 0 1 .562-.262M13 10a.5.5 0 0 1 .5.5v2.793l.646-.646a.5.5 0 1 1 .707.707l-1.5 1.5a.5.5 0 0 1-.707 0l-1.5-1.5a.5.5 0 1 1 .707-.707l.647.646V10.5a.5.5 0 0 1 .5-.5M9.5 1a1.5 1.5 0 0 1 1.415 1h.585A1.5 1.5 0 0 1 13 3.5V9a1.5 1.5 0 0 0-1.5 1.5v1q-.256 0-.5.087V10.5a1.5 1.5 0 0 0-2.842-.67L7.5 11.145l-.658-1.317A1.5 1.5 0 0 0 4 10.5v4q.001.227.064.435A1.5 1.5 0 0 1 3 13.5v-10A1.5 1.5 0 0 1 4.5 2h.585A1.5 1.5 0 0 1 6.5 1zm-3 1a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
