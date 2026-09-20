<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qugl2rpws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-48-filled" /></template>
<style>
.qugl2rpws {
  fill: currentColor;
  d: path("M24 4C15.992 4 9.5 10.492 9.5 18.5c0 4.235 1.817 8.047 4.71 10.696c.448.41.748.873.87 1.349l1.27 4.955h15.3l1.27-4.955c.122-.476.422-.938.87-1.35A14.47 14.47 0 0 0 38.5 18.5C38.5 10.492 32.008 4 24 4m7.008 34H16.992l.623 2.43a4.75 4.75 0 0 0 4.6 3.57h3.57a4.75 4.75 0 0 0 4.6-3.57z");
}

</style>
