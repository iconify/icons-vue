<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od-latgrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-cursor-24-regular" /></template>
<style>
.od-latgrw {
  fill: currentColor;
  d: path("M12 11a1 1 0 0 1 1.6-.8l8 6c.768.577.361 1.8-.6 1.8h-4.4a1 1 0 0 0-.882.53l-1.835 3.44c-.49.92-1.883.571-1.883-.47zM10 1a8 8 0 0 1 7.473 10.855l-1.26-.945A6.5 6.5 0 1 0 4.33 12.178a.75.75 0 0 1 .074.549l-.623 2.492l2.492-.623l.141-.022a.75.75 0 0 1 .408.095a6.47 6.47 0 0 0 4.179.754v1.513a7.96 7.96 0 0 1-4.645-.815l-3.423.857a.75.75 0 0 1-.91-.91l.856-3.425A8 8 0 0 1 10 1");
}

</style>
