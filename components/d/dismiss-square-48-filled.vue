<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsqn7bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-square-48-filled" /></template>
<style>
.rlsqn7bqf {
  fill: currentColor;
  d: path("M35.75 6A6.25 6.25 0 0 1 42 12.25v23.5A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6zm-4.116 10.366a1.25 1.25 0 0 0-1.768 0L24 22.232l-5.866-5.866a1.25 1.25 0 0 0-1.768 1.768L22.232 24l-5.866 5.866a1.25 1.25 0 0 0 1.768 1.768L24 25.768l5.866 5.866a1.25 1.25 0 0 0 1.768-1.768L25.768 24l5.866-5.866a1.25 1.25 0 0 0 0-1.768");
}

</style>
