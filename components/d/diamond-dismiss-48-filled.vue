<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x-94q8tva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-dismiss-48-filled" /></template>
<style>
.x-94q8tva {
  fill: currentColor;
  d: path("M19.584 4.83a6.25 6.25 0 0 1 8.839 0l14.753 14.754a6.25 6.25 0 0 1 0 8.839L28.423 43.175a6.25 6.25 0 0 1-8.84 0L4.832 28.423a6.25 6.25 0 0 1 0-8.84zm12.052 11.536a1.25 1.25 0 0 0-1.768 0l-5.866 5.866l-5.866-5.866a1.25 1.25 0 0 0-1.768 1.768L22.234 24l-5.866 5.866a1.25 1.25 0 0 0 1.768 1.768l5.866-5.867l5.866 5.867a1.25 1.25 0 0 0 1.768-1.768L25.769 24l5.867-5.866a1.25 1.25 0 0 0 0-1.768");
}

</style>
