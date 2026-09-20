<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="go450wbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chopsticks-16-filled" /></template>
<style>
.go450wbfq {
  fill: currentColor;
  d: path("M2.732 1.078a.5.5 0 0 1 .69.154L7.092 7h1.815L5.578 1.77a.5.5 0 0 1 .844-.537L10.092 7h4.437c.26 0 .471.21.471.47V8c0 .695-.101 1.366-.29 2H1.29A7 7 0 0 1 1 8v-.53c0-.26.21-.47.47-.47h4.437L2.578 1.77a.5.5 0 0 1 .154-.69M8 15a7 7 0 0 1-6.326-4h12.652A7 7 0 0 1 8 15");
}

</style>
