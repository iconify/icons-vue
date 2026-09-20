<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tzdbrpljp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-16-filled" /></template>
<style>
.tzdbrpljp {
  fill: currentColor;
  d: path("M13.78 3.28a.75.75 0 0 0-1.06-1.06L10.5 4.44V3.25a.75.75 0 0 0-1.5 0v2.9l.002.052a.748.748 0 0 0 .796.796L9.85 7h2.9a.75.75 0 0 0 0-1.5h-1.19zM6.25 13.5a.75.75 0 0 1-.75-.75v-1.19l-2.22 2.22a.75.75 0 0 1-1.06-1.06l2.22-2.22H3.25a.75.75 0 0 1 0-1.5h2.9l.052.002a.748.748 0 0 1 .796.796L7 9.85v2.9a.75.75 0 0 1-.75.75");
}

</style>
