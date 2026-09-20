<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-y_0x31k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-dismiss-48-regular" /></template>
<style>
.o-y_0x31k {
  fill: currentColor;
  d: path("M19.583 4.829a6.25 6.25 0 0 1 8.839 0l14.753 14.753a6.25 6.25 0 0 1 0 8.839L28.422 43.173a6.25 6.25 0 0 1-8.839 0L4.83 28.42a6.25 6.25 0 0 1 0-8.839zm7.071 1.769a3.75 3.75 0 0 0-5.303 0L6.599 21.35a3.75 3.75 0 0 0 0 5.303L21.35 41.405a3.75 3.75 0 0 0 5.303 0l14.753-14.752a3.75 3.75 0 0 0 0-5.303zm3.212 9.768a1.25 1.25 0 0 1 1.768 1.768L25.768 24l5.866 5.866a1.25 1.25 0 1 1-1.768 1.768L24 25.768l-5.866 5.866a1.25 1.25 0 0 1-1.768-1.768L22.232 24l-5.866-5.866a1.25 1.25 0 0 1 1.768-1.768L24 22.232z");
}

</style>
