<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7i1m_bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-double-compare-20-regular" /></template>
<style>
.f7i1m_bye {
  fill: currentColor;
  d: path("M7 3H3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2M3 4h4a1 1 0 0 1 1 1v1H2V5a1 1 0 0 1 1-1m4 12H3a1 1 0 0 1-1-1V7h6v8a1 1 0 0 1-1 1M17 3h-4a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2m-4 1h4a1 1 0 0 1 1 1v5h-6V5a1 1 0 0 1 1-1m4 12h-4a1 1 0 0 1-1-1v-2h6v2a1 1 0 0 1-1 1");
}

</style>
