<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ab8yl7xtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-up-28-filled" /></template>
<style>
.ab8yl7xtk {
  fill: currentColor;
  d: path("M22 24a1 1 0 1 1 0 2H6a1 1 0 0 1 0-2zM13.293 2.293a1 1 0 0 1 1.414 0l6.5 6.5a1 1 0 1 1-1.414 1.414L15 5.414V21a1 1 0 1 1-2 0V5.414l-4.793 4.793a1 1 0 1 1-1.414-1.414z");
}

</style>
