<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="krr4fewsc"/><path class="l_loqb3ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foldersync" /></template>
<style>
.krr4fewsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.641 33.986c-1.454 1.488-3.69 4.6-8.543 4.57c-5.813-.035-9.581-4.57-9.598-9.53c-.017-5.217 3.808-8.854 8.076-9.515");
}

.l_loqb3ku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.733 27.582s3.462-3.47 5.665-5.591s4.415-2.573 6.852-2.618s7.608 2.122 8.789 6.576s.028 7.56-2.717 10.17s-6.616 2.787-9.48 1.943s-5.796-4.445-8.692-7.383s-7.205-6.315-7.745-10.105s1.77-7.414 3.248-8.626S23.67 7.805 28.5 10.641c3.924 2.304 4.723 5.114 4.981 6.863");
}

</style>
